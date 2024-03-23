---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

 <link href='https://cdnjs.cloudflare.com/ajax/libs/fullcalendar/3.10.2/fullcalendar.min.css' rel='stylesheet' />
 <script src='https://cdnjs.cloudflare.com/ajax/libs/moment.js/2.24.0/moment.min.js'></script>
 <script src='https://cdnjs.cloudflare.com/ajax/libs/jquery/3.5.1/jquery.min.js'></script>
 <script src='https://cdnjs.cloudflare.com/ajax/libs/fullcalendar/6.0.0/index.js'></script>
 
 <script>
 document.addEventListener('DOMContentLoaded', function() {
  var calendarEl = document.getElementById('calendar');

  var calendar = new FullCalendar.Calendar(calendarEl, {
    initialView: 'dayGridMonth',
    initialDate: '2024-02-07',
    headerToolbar: {
      left: 'prev,next today',
      center: 'title',
      right: 'dayGridMonth,timeGridWeek,timeGridDay'
    },
    events: [
      {
        title: 'All Day Event',
        start: '2024-02-01'
      },
      {
        title: 'Long Event',
        start: '2024-02-07',
        end: '2024-02-10'
      },
      {
        groupId: '999',
        title: 'Repeating Event',
        start: '2024-02-09T16:00:00'
      },
      {
        groupId: '999',
        title: 'Repeating Event',
        start: '2024-02-16T16:00:00'
      },
      {
        title: 'Conference',
        start: '2024-02-11',
        end: '2024-02-13'
      },
      {
        title: 'Meeting',
        start: '2024-02-12T10:30:00',
        end: '2024-02-12T12:30:00'
      },
      {
        title: 'Lunch',
        start: '2024-02-12T12:00:00'
      },
      {
        title: 'Meeting',
        start: '2024-02-12T14:30:00'
      },
      {
        title: 'Birthday Party',
        start: '2024-02-13T07:00:00'
      },
      {
        title: 'Click for Google',
        url: 'https://google.com/',
        start: '2024-02-28'
      }
    ]
  });

  calendar.render();
});
 </script>

This is the temporary home for Scouts-BSA Troop 212, in Cary, NC, while our new website is under construction. 

We meet on Wednesday nights at 7:30 PM, at [St. Michael the Archangel Roman Catholic Church](https://maps.app.goo.gl/SW6FWttWySoMRwZM9), 804 High House Rd, Cary, NC 27513.
<div id='calendar'></div>
Please email the Scoutmaster, [Jim Fuller](mailto:scoutmastertroop212cary), for more information.
