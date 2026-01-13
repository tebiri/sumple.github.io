
<!doctype html>
<html lang="ja">
  <head>
    <meta charset="UTF-8">
    <title>My Carendar</title>
 
   <style>
       body {
           font-family: -apple-system,BlinkMacSystemFont,sans-serif;
           background: #faf8f5;
           margin: 0;
       }
      
       .app {
           max-width: 430px;
           margin: 0 auto;
           padding: 16px;
       }
      
       .header {
           text-align: center;
           margin-bottom: 12px;
       }
      
       .week {
           display: grid;
           grid-template-columns: repeat(7,1fr);
           text-align: center;
           color: #888888;
           font-size: 14px;
       }
      
       .calendar {
           display: grid;
           grid-template-columns: repeat(7,1fr);
           gap: 6px;
           margin-top: 8px;
       }
      
       .day {
           height: 56px;
           border-radius: 8px;
           padding: 6px;
           background: #ffffff;
           font-size: 14px;
       }
      
       .day.muted {
           color: #cccccc;
       }
      
       .day.selected {
           background: #e5e5e5;
       }
      
       .day.today {
           background: #f2c27d;
           color: #ffffff;
       }
   </style>
  </head>

  <body>
     <div class="app">
         <header class="header">
             <h1>2026.January</h1>
         </header>
     <div class="week">
         <div>月</div><div>火</div><div>水</div><div>木</div><div>金</div><div>土</div><div>日</div>
     </div>
     <div class="calendar">
         <div class="day muted">29</div>
         <div class="day muted">30</div>
         <div class="day muted">31</div>
         <div class="day">1</div>
         <div class="day">2</div>
         <div class="day">3</div>
         <div class="day">4</div>
         <div class="day">5</div>
         <div class="day">6</div>
         <div class="day">7</div>
         <div class="day">8</div>
         <div class="day">9</div>
         <div class="day">10</div>
         <div class="day">11</div>
         <div class="day">12</div>
         <div class="day">13</div>
         <div class="day">14</div>
         <div class="day">15</div>
         <div class="day">16</div>
         <div class="day">17</div>
         <div class="day">18</div>
         <div class="day">19</div>
         <div class="day">20</div>
         <div class="day">21</div>
         <div class="day">22</div>
         <div class="day">23</div>
         <div class="day">24</div>
         <div class="day">25</div>
         <div class="day">26</div>
         <div class="day">27</div>
         <div class="day">28</div>
         <div class="day">29</div>
         <div class="day">30</div>
         <div class="day">31</div>
         <div class="day muted">1</div>
     </div>
     </div>
    
     <script>
         const today =13;
         document.querySalectorAll("day").farEach(day => { if(day.textContent === String(today)){day.classList.add("today");}
             });
     </script>
    
  </body>
  </html>
