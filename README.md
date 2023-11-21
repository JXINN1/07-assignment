# Normal Business Hours

A link to my server:  http://137.184.70.208:3000/


This assignment’s purpose is really relatable to me, as I'm always trying to find a balance between online and offline life. As we are exposed to the internet 24/7/365, we often lose time to seek the real value of life in this massive, complicated digital media world.

For me personally, despite being a person who doesn’t spend that much time online on SNS and gaming, it still consists of a big portion of my life, as I almost forget everything when I scroll through endless YouTube shorts and watch TV series. It’s almost like addiction without noticing, which is really overwhelming as it feels like things are getting out of my control.
However, most importantly, I value spending time with my loved ones, including my family, girlfriend, and friends, in real-time communication and interaction, even though there is a possibility for real-time interaction to happen in the virtual world in the near future as companies like Meta are developing real-life interaction experiences in the virtual world, creating realistic virtual worlds, and trying to give the corresponding experience of interacting with a real person in real life. Even if that happens, I still value time spent with my loved ones, speaking with caring words, looking into their eyes, paying attention to their gestures, voices, and thoughts, using all my senses to fully dedicate myself to relationships, having valuable time, and making unforgettable memories, which I value over tons of fancy things that could happen online.

For normal business hours, I personally think it depends on which occupation I will have during a certain period. I want to work for an entertainment tech company or run my own business after graduation. Both cases will require additional hours besides working hours to perform well. And both work need consistency and efficiency, so I set up my working business hours as 9 a.m. to 6 p.m., which is 8 working hours except 1 hour for lunch, and also work same-hours on Saturday to challenge myself and aim to fulfill near 50 fully focused working hours a week. But even though the schedule is hard, after I close my business hour at 6 p.m. as I plan to do most of the business meetings at lunch, I will try to spend every dinner with my family and friends, the time that I value the most: being happy and having a good time with loved ones. After dinner, I will use the time to review the daily work and get ready for the next day's work. On Sunday, of course, I will take a break, so my business hours will be closed.

As a student, all of this doesn’t work as every day's schedule is irregular besides the class schedule, so I'm also excited for the future, where I could decide my working hours and follow my own schedule and system to do my job and live a good life with my people. 


```javascript

  // get the current time
  const currentTime = new Date();

  const day = currentTime.getDay();

```
I added .getDay() method of Date.
Return value of getDay() method is an integer, between 0 and 6, representing the day of the week for the given date according to local time: 0 for Sunday, 1 for Monday, 2 for Tuesday, and so on. 

```javascript

  // get the hour
  const currentHour = currentTime.getHours();

  const normalBusinessHours = {
    // 24 hour time
    open: 9,
    close: 18,
  };
  
  // check if within normal business hours
  if (
    currentHour >= normalBusinessHours.open &&
    currentHour <= normalBusinessHours.close 
    && day != 0
  ) 

  ``` 

 To exclude sunday(0) from open hours i added && day != 0 

 ```html

 <div class="w3-container w3-white w3-hover-red">
<li> <span class="w3-center w3-animate-right">Sunday: Closed</span></li> </div>
<div class="w3-container w3-white w3-hover-green">
<li> <span class="w3-center w3-animate-right">Monday: 9:00-18:00</span></li> </div>

  ``` 

  I used w3css. Put animation as text appearing from left side, right side, and center. 
  Then also putThe w3-hover-color classes define the background hover color for html elements, 
  showing red colored hover when i put mouse on Sunday, and green color hover when i put mouse on monday-saturday which it's open.
