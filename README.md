
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=800, initial-scale=1">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=League+Spartan:wght@400;600;800&display=swap');

        * {
            box-sizing: border-box;
        }
        body {
            margin: 0;
            font-family: 'League Spartan', sans-serif;
            color: #444;
            background-image:url("https://dicdevelopmenttrust.com/wp-content/uploads/2024/11/Whats-On-BG-Only.png");
            background-color: #44b0ec;
        }
       .title{            
            margin: 0;
            color:#fff;
            text-align:center;
        }
        div.title {padding:20px 0;}
        .title h1{font-weight:800;margin:0;font-size:45px;}
        .title h3{font-weight:600;margin:0;}
        
        .calendar-container {
            display: flex;
            flex-wrap: wrap;
            gap: 0.75rem;
            justify-content: center;
            padding: 10px;
            color: #fff;
            width: 100%;
            max-width: 1000px;
            margin: 0 auto;
        }
        .day-column {
            flex-basis: 32%;
            display: flex;
            flex-direction: column;
            padding: 8px;
            background-color: #fff;
            color: #44b0ec;
            border-radius: 8px;
            margin-bottom: 5px;
        }
        .day-header {
            font-size: 1.1rem;
            font-weight: 600;
            color: #44b0ec;
            display: flex;
            justify-content: space-between;
        }
        .day-date {
            font-size: 1rem;
            color: #444;
        }
        .events {
            font-size: 0.9rem;
            padding-top: 4px;
        }
        .event {
            padding-top: 4px;
            padding-bottom: 8px;
            border-bottom: 1px solid #ddd;
        }
        .event-title {
            font-weight: 600;
            color: #444;
            display: block;
        }
        .event-time {
            display: block;
            color: #444;
        }
        .no-event {
            font-style: italic;
            color: #aaa;
        }
    </style>
</head>
<body>
    <div class="title">
        <h1 class="title">What's On This Week</h1>
        <h3>@CastlelandVenue</h3>
        <h3>www.castlelandcentre.com</h3>
    </div>
    
    <div class="calendar-container">
        
            <div class="day-column">
                <div class="day-header">Mon <span class="day-date">10 Feb</span></div>
                <div class="events">
                    
                <div class="event">
                    <span class="event-title">Barnardos Cygnet Parent group 🚸</span>
                    <span class="event-time">10:00 - 14:00</span>
                </div>
            
                <div class="event">
                    <span class="event-title">Vale Youth Forum Meeting 📅</span>
                    <span class="event-time">17:30 - 19:30</span>
                </div>
            
                <div class="event">
                    <span class="event-title">Miranda Lee Dance 💃</span>
                    <span class="event-time">15:00 - 22:00</span>
                </div>
            
                </div>
            </div>
        
            <div class="day-column">
                <div class="day-header">Tue <span class="day-date">11 Feb</span></div>
                <div class="events">
                    
                <div class="event">
                    <span class="event-title">Miranda Lee Dance 💃</span>
                    <span class="event-time">15:00 - 22:00</span>
                </div>
            
                </div>
            </div>
        
            <div class="day-column">
                <div class="day-header">Wed <span class="day-date">12 Feb</span></div>
                <div class="events">
                    
                <div class="event">
                    <span class="event-title">Warm Space ☕</span>
                    <span class="event-time">12:30 - 16:00</span>
                </div>
            
                <div class="event">
                    <span class="event-title">Dinki Dragons ⚽</span>
                    <span class="event-time">13:00 - 14:00</span>
                </div>
            
                <div class="event">
                    <span class="event-title">Slimrite ⚖️</span>
                    <span class="event-time">18:00 - 19:00</span>
                </div>
            
                <div class="event">
                    <span class="event-title">NYLO 👶</span>
                    <span class="event-time">09:00 - 12:00</span>
                </div>
            
                <div class="event">
                    <span class="event-title">FoodShare 🍲</span>
                    <span class="event-time">13:30 - 15:00</span>
                </div>
            
                <div class="event">
                    <span class="event-title">CAVDAS 💊</span>
                    <span class="event-time">13:00 - 15:00</span>
                </div>
            
                <div class="event">
                    <span class="event-title">Miranda Lee Dance 💃</span>
                    <span class="event-time">15:00 - 22:00</span>
                </div>
            
                </div>
            </div>
        
            <div class="day-column">
                <div class="day-header">Thu <span class="day-date">13 Feb</span></div>
                <div class="events">
                    
                <div class="event">
                    <span class="event-title">Olivia Fleur Dance Academy 🩰</span>
                    <span class="event-time">16:00 - 19:15</span>
                </div>
            
                <div class="event">
                    <span class="event-title">Get Cooking 🍲</span>
                    <span class="event-time">12:30 - 15:30</span>
                </div>
            
                <div class="event">
                    <span class="event-title">Let's Talk with your Baby 👶</span>
                    <span class="event-time">12:30 - 14:30</span>
                </div>
            
                </div>
            </div>
        
            <div class="day-column">
                <div class="day-header">Fri <span class="day-date">14 Feb</span></div>
                <div class="events">
                    
                <div class="event">
                    <span class="event-title">SEND Academy 🎓</span>
                    <span class="event-time">10:00 - 15:00</span>
                </div>
            
                </div>
            </div>
        
            <div class="day-column">
                <div class="day-header">Sat <span class="day-date">15 Feb</span></div>
                <div class="events">
                    
                <div class="event">
                    <span class="event-title">Dinki Dragons ⚽</span>
                    <span class="event-time">09:00 - 11:30</span>
                </div>
            
                <div class="event">
                    <span class="event-title">Friendly Bingo 🎰</span>
                    <span class="event-time">18:30 - 21:30</span>
                </div>
            
                <div class="event">
                    <span class="event-title">Harmony Choir (Adult) 🎵</span>
                    <span class="event-time">10:00 - 11:00</span>
                </div>
            
                </div>
            </div>
        
            <div class="day-column">
                <div class="day-header">Sun <span class="day-date">16 Feb</span></div>
                <div class="events">
                    
                <div class="event">
                    <span class="event-title">GodFirst 🛐</span>
                    <span class="event-time">09:30 - 13:30</span>
                </div>
            
                <div class="event">
                    <span class="event-title">GodFirst 🛐</span>
                    <span class="event-time">10:00 - 13:00</span>
                </div>
            
                </div>
            </div>
        
    </div>
    
</body>
</html>
