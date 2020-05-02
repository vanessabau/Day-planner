# Day-planner
SCHEDULING PROGRAM

OVERVIEW:
The day-scheduler offers a heading that includes the current date. Below are rows of hour blocks that show the hour, have spaces for text, and end with save buttons. Users can type in the textareas and cick save to store their input, even if the page is refreshed. The day-scheduler shows hour blocks for each hour of the work day. The text areas are color coded depending on the time of day.  The color coding changes automatically: past hours display gray, the current hour displays red, and future hours display green. 

CREATING THE CODE
I began with items provided and looked through the existing html and css to utilize items already build (like css, tags, and ids), so as not to build elemets that already existed. Secondarily I wrote pseudo code so I could organize my approach with methods and concepts I already knew or with which I was familiar. Thirdly, I looked up tutorials on the moment plug in. I watched three you tube videos on moment.js (the link is below) which were very helpful in settting up the plugin and learning basic ways to target and display values I wanted to utilize. I attempted to read the documentation, but found the basic video tutorials more helpful. The videos helped show very directly basic functionality of moment js. 

I started with the moment js functionality, then created basic styling, then build the user-functionality portion. The largest challenge has been attempting to minimize the repetition in my code. I was able to create a working daily planner pretty quickly, but have spent hours doing various attempts to create more general variables and functions that can work by looping through all the iterations of page elements (most notably those textareas!). 

I have a version where each row is targeted individually. I am working on creating a loop for my text area to color code them via a loop rather than 9 if/else statements. 


PSEUDO CODE

* Structure already given
    - html page
    - links to bootstrap, jquery, minute.js, js, css stylesheet
    - jumbotron header

STEPS USED TO COMPLETE:

1. Using a moment object, insert the current day in the jumbotron 
    - Current day & date in jumbotron (remove time) 

2. Build the timeblocks 
    - 24 blocks (one for each hour) each needs to be a text input 
    - Each needs a submit button

3. Build timeblock features
    - When time block is clicked text can be edited -DONE-
    - On click event for save button that stores text to local storage 
    - Timeblocks are color coded: past, present, future
        
4. When page is refreshed timeblock text entries persist 

RESOURCES
Moment JS youtube video series(first in set): https://www.youtube.com/watch?v=n80RRNS1k64&t=181s
