# 100 Days Of Code - Log

### Day 0: August 21, Wednesday
I'm finally committing to #100DaysOfCode. My primary goals are to complete the @freeCodeCamp Front-End Libraries certification, to learn to write useful web apps, and to get more involved in the community. Looking forward to coding along side you all!


### Day 1: August 22, Thursday
Nearly finished with tweaking the layout of my Random Quote Machine @freeCodeCamp project. Hoping I get better and faster at design over time. Right now it feels totally like trial & error - I just keep trying different things until it doesn't look awful


### Day 2: August 23, Friday
Nearly finished with my Random Quote Machine project. Improved handling of empty quote string using conditional rendering. Spent WAY too much time deciding on the hover effect for my buttons, but loving CSS transitions! #freeCodeCamp


### Day 3: August 25, Sunday
Figured out how to publish my React app using GitHub Pages. I'm feeling good about learning git and moving to GitHub for my #freeCodeCamp projects. Much more intimidating than Codepen, but I think it's important to learn and it's starting to make sense


### Day 4: August 26, Monday
Polished up my code and made one last tweak to the button hover effect (last time, for real!). Did some testing in other browsers. Learned about polyfill for Promise support in IE, and that Firefox & IE don't support CSS transition on background-image :-\

I loved the idea of a rotating background image for my Random Quote Machine project, but I'm not sure if it will be too bandwidth-intensive? All 6 images are <800KB combined.

[Random Quote Machine live demo](https://tmonks.github.io/random-quote-machine)
[Random Quote Machine git repository](https://github.com/tmonks/random-quote-machine)


### Day 5: August 27, Tuesday
Learned how to downgrade packages and resolve security vulnerabilities in npm

I could keep tweaking my Random Quote Machine project for weeks, but calling it good enough and moving on to the next one. Pretty happy with how it turned out.  #freeCodeCamp 

![Random Quote Machine finished](https://pbs.twimg.com/media/EDC5CLQWkAEMlZv?format=png&name=900x900)


### Day 6: August 28, Wednesday
Had a productive day making a few last tweaks to my Random Quote Machine project. Implemented an initial loading message. Used git branching for the first time. Got IE11 working. Used the excellent @tinyjpg to compress my background images


### Day 7: August 29, Thursday
I'm excited to have gotten a great start on my Markdown Previewer #freeCodeCamp project today. Set up create-react-app, reactstrap, & git repository. Created a rough outline, and got a controlled input working for the Markdown input.


### Day 8: August 30, Friday
More progress on my #freeCodeCamp Markdown Previewer. Added the react-fcctest and marked.js libraries and got all the tests passing! Even used DOMPurify to protect against XSS attacks. Now I just need to make the code and the UI much prettier!

![Markdown Previewer with all tests passing](https://pbs.twimg.com/media/EDP8YohXsAA05AN?format=jpg&name=small)

**Thoughts:** Really happy with how this is progressing. Only 2 days (couple hours) in, and I've already got most of the functionality done!

### Day 9: August 31, Saturday
Had the best time coding at Barnes & Noble while my wife shopped :-) There's nothing like coding with good coffee and good music. Got the design of my Markdown Previewer looking okay #reactjs #freeCodeCampo

![Markdown Previewer improved design](https://pbs.twimg.com/media/EDYHbC0W4AIr2zS?format=jpg&name=small)

### Day 10: September 2, Monday
Did lots of fun things with the kids this weekend, but was able to fit in an hour of coding last night. I struggled for a frustratingly long time with making the layout for my #freeCodeCamp Markdown Previewer full-height but without having a scroll bar! After lots of searching and trial & error, i think I finally have a handle on it.

I realized two things: 
-'height: 100%' means 100% of the parent's height, even if there's a sibling element with a fixed height (like a navbar). 
- By default, height is based on the height of content inside the element. To set it to anything less, you have to set the parent to a specific height (e.g. px, not %). [Why doesn't percentage height work](https://stackoverflow.com/questions/5657964/css-why-doesn-t-percentage-height-work)

### Day 11: September 3, Tuesday
Struggled a little more with the full-height-without-scrollbar layout on my Markdown Previewer, but got it working. Tracked down the problem with navbar dark not having a white font. Getting better at tracking these things down in the Chrome Developer console!

### Day 12: September 4, Wednesday
Nearly done with my #freeCodeCamp Markdown Previewer. Made a few more improvements to the styling (textarea & title). Improved the sample markdown. Took a few notes to so I would remember the new things I learned. Should be able to finish it up and submit it tomorrow.

![Markdown Previewer app nearly finished](https://pbs.twimg.com/media/EDsC4C0WsAAgHGD?format=jpg&name=small)

### Day 13: September 5, Thursday
Finished up and submitted my Markdown Previewer project! Two front-end library projects down, 3 to go. Looking forward to tackling the drum machine project next. Looks like fun! @freeCodeCamp
https://tmonks.github.io/markdown-previewer/

### Day 14: September 6, Friday
Started on my #freeCodeCamp Drum Machine project. Did some initial research and planning, got the React app setup, and drafted the initial layout. I'm a bit rusty on CSS Grid, but I found this excellent visual cheat sheet: http://grid.malven.co/

### Day 15: September 7, Saturday
Had a great afternoon yesterday coding at the coffee shop. Got my drum machine playing audio and reacting to keypresses. I'm not quite sure how to pass keyboard events down to the children components, but I'm obsessed with figuring it out. I woke up and was thinking about it in the middle of the night! Not sure how I'm going to let it go today so I can enjoy time with the girls and get some chores done.

### Day 16: September 9, Monday
After much Googling about audio playback and React Hooks on Sunday, my coding session went great and according to plan today. I got the audio to play in a child component from a change in state in the parent, as triggered by mouse click or keypress. Awesome! Now I don't feel like all my obsessive Googling during every spare minute over the weekend was a waste! 

### Day 17: September 10, Tuesday
Refactored my main App component on my #freeCodeCamp Drum Machine using React Hooks. Hit a couple snags but got it working in the end. In a good position to start building out the data model for all the drum pads tomorrow. This is my first project using Hooks, but liking them so far!

### Day 18: September 11, Wednesday
Implemented data structure and state to track all details of the drum pads, and render them using map() on my #freeCodeCamp Drum Machine app. It was tricky, but fun to figure out. I'm enjoying this project so much, it's really hard to stop working on it!

### Day 19: September 12, Thursday
Got most of the tests passing on my #freeCodeCamp drum machine. Had trouble linking all the audio files without importing them all one by one. After some more obsessive Googling, I figured out how to put them in the public folder & ended the day on a good note

### Day 20: September 13, Friday
D20 #100DaysOfCode
Got all of the #freeCodeCamp tests passing on my drum machine! Before I submit it, I still want to improve the design and figure out how to fix the warnings I'm getting, but I'm getting close. My kids are excited to play with it anyway :-)

![drum machine all tests passing](https://pbs.twimg.com/media/EEal_y1XoAEsfLB?format=png&name=small)

### Day 21: September 14, Saturday
D21 #100DaysOfCode Found some good MP3 sound clips from sampleswap.org which load much faster than the WAV files on my drum machine. Watched some Youtube videos while washing the dishes to learn more about the useEffect warnings I'm getting and resolved my last one. #freeCodeCamp

### Day 22: September 16, Monday
D22 #100DaysOfCode #freeCodeCamp
Found some cool CSS tricks and had fun experimenting with a retro design for my drum machine app.

![drum machine with retro design](https://pbs.twimg.com/media/EEpx4VvWsAAD-SE?format=jpg&name=small)

### Day 23: September 17, Tuesday
D23 #100DaysOfCode #freeCodeCamp
Worked on a keyframe button click animation on my drum machine. The CSS transition approach wasn't working on mobile devices, since there seems to be 0 delay between the mousedown and mouseup events. Enjoying the process of figuring it out anyway

### Day 24: September 18, Wednesday
D24 #100DaysOfCode #freeCodeCamp
The keyframe animation on the drum pads worked out, so now my click effect works on touch screens. There's probably a better way, but this seems to work pretty well. Feels good when a plan comes together 😁

https://tmonks.github.io/drum-machine/

### Day 25: September 19, Thursday
D25 #100DaysOfCode #freeCodeCamp 
Used Sass for the first time. Using variables for the colors made it so much easier to play around with different color schemes. Also moved the display to its own component and added left/right buttons which I'll use to switch the bank.

![screenshot of drum-machine app](https://pbs.twimg.com/media/EE5VrPOU4AkvpUB?format=png&name=small)

### Day 26: September 20, Friday
D26 #100DaysOfCode #freeCodeCamp
Implemented a separate BankSelector component to select different sound banks. Downloaded clips and set up the JSON for 4 more sound banks. Found some my kids will have fun with - animal sounds, cartoon sounds, beat boxing, & Donkey Kong 😀
![screenshot of drum machine with bank selector](https://pbs.twimg.com/media/EE-6NJKWsAIErN4?format=png&name=small)

### Day 27: September 21, Saturday
D27 #100DaysOfCode #freeCodeCamp
Figured out the weird "uncaught DOMExceptions" I was getting only during the FCC tests. Turns out it's because audio.play() returns a Promise and I wasn't handling it that way. Glad to have that figured out! 😌

https://developers.google.com/web/updates/2017/06/play-request-was-interrupted

### Day 28: September 22, Sunday
D28 #100DaysOfCode #freeCodeCamp
Refactored my data structure to work better with multiple sound banks on my drum machine. I like this approach so much better. Now it's easy to drop in and reorder sounds. A couple bugs to work out and then I'll be done!
https://tmonks.github.io/drum-machine/

It's usually hard to find time to code on the weekends, but yesterday I involved my daughters to help test my drum machine. They had a great time with it, and my youngest (with her furious clicking & dragging) discovered a bug I never would have!

### Day 29: September 23, Monday
D29 #100DaysOfCode #freeCodeCamp
Fixed two bugs on my drum machine. Learned how to use useCallback hook. Improved the logic so that the animations are consistent between keyboard & mouse presses. All I need to do now is polish up my code. Looking forward to starting the next one!

### Day 30: September 24, Tuesday
D30 #100DaysOfCode #freeCodeCamp
3 down, 2 to go! I optimized, commented, & polished up all my code and submitted my drum machine project 🥳

https://tmonks.github.io/drum-machine/

Looking forward to starting the JavaScript Calculator next!

![3 of 5 Front-End Libraries Projects Complete](https://pbs.twimg.com/media/EFT9OYwW4AAIUeK?format=png&name=small)

### Day 31: September 25, Wednesday
D31 #100DaysOfCode #freeCodeCamp
Needed to brush up on CSS Grid before starting the calculator project. I watched some good YouTube videos during my workout and got a better handle on it. Improved my drum machine layout and drafted one for the calculator

https://codepen.io/monksy/pen/OJLqogz

![Codepen: CSS Grid Test - Calculator](https://pbs.twimg.com/card_img/1177147357647056901/2ZxDo11l?format=png&name=small)

### Day 32: September 26, Thursday
D32 #100DaysOfCode #freeCodeCamp
Wrote the first draft of my calculator app. Set up the React app, the initial style, state, and functionality to update the display. Got half of the FCC tests passing. Super excited that did all this and only had to look up syntax for one line!

![Calculator app with 8/16 tests passing](https://pbs.twimg.com/media/EFdXSm-UYAA8mSU?format=png&name=small)

### Day 33: September 27, Friday
D33 #100DaysOfCode #freeCodeCamp
Worked on the input and calculation logic and got all but one test passing! My idea to use recursion to solve the equations actually worked out. I love it when I find a real reason to use recursion, it feels a little bit like magic 🧙 🤓 

![Calculator app with 15/16 tests passing](https://pbs.twimg.com/media/EFigkdDX0AIYfBd?format=png&name=small)

### Day 34: September 28, Saturday
D34 #100DaysOfCode #freeCodeCamp
Rewrote the input handling algorithm on my calculator app to make it more graceful. Still failing one test, but getting closer. Can't stop thinking about it, so I carried around 3x5 cards to work on the algorithm whenever I got a spare minute 🤓

### Day 35: September 29, Sunday
D35 #100DaysOfCode #freeCodeCamp
Got up at 5am to work on my calculator app for a little while in the hotel lobby (on a weekend trip with my family). The new approach to my input algorithm worked, and I got the last test to pass!

https://tmonks.github.io/js-calculator/

![Calculator app with all tests passing](https://pbs.twimg.com/media/EFs3nfCXkAEjgiR?format=png&name=small)

**Thoughts:** Really happy with how this one is going. I thought it was going to be a really hard one, but after only about 3.5 hours of coding (and a lot of offline thinking), I've got all the test passing and I didn't even use `eval()`. 
### Day 36: September 30, Monday
D36 #100DaysOfCode #freeCodeCamp 
Added a one-line history and a live calculation result to the display of my calculator. Worked out a design I like a lot better. 

https://tmonks.github.io/js-calculator/

[video of improved display and design](https://twitter.com/i/status/1178952454475587584)

### Day 37: October 1, Tuesday
D37 #100DaysOfCode #freeCodeCamp
Worked on improving the responsiveness of my calculator. Got the display to handle long lines of input without breaking. Took some trial and error, but got there in the end 😅

https://tmonks.github.io/js-calculator/

[Video showing responsiveness](https://twitter.com/i/status/1179324442100604928)

### Day 38: October 2, Wednesday
D38 #100DaysOfCode #freeCodeCamp
Refactored the code for my calculator into separate click handling functions to make it easier to read and understand. Implemented a backspace button. Just a little more polishing to do, and I'm going wrap this one up.

https://tmonks.github.io/js-calculator/

![Calculator app with backspace button](https://pbs.twimg.com/media/EF8OPpAXoAAne95?format=png&name=small)

### Day 39: October 3, Thursday
D39 #100DaysOfCode #freeCodeCamp
Made various improvements to my calculator that were on my list - better file organization, simplified  clickNumber function (40 to 25 lines), better handling of numbers when a new solution is displayed. It's almost done!
https://tmonks.github.io/js-calculator/

### Day 40: October 4, Friday
D40 #100DaysOfCode #freeCodeCamp
Finished cleaning up and commenting my code, and submitted my calculator app. 
https://tmonks.github.io/js-calculator/

4 down, 1 to go! I'm looking forward to starting the pomodoro clock, my last project for the front-end libraries certification.

![4 of 5 front-end libraries projects complete](https://pbs.twimg.com/media/EGG0V1UWkAER0rj?format=png&name=small)

### Day 41: October 5, Saturday
D41 #100DaysOfCode
Did couple katas on CodeWars. They are so addicting, I can't stop thinking about them until they're solved. I like that I can learn from others' solutions afterwards. I'm trying hard to be inspired (and not depressed) by how much better they are than mine!

[Find the odd int](https://www.codewars.com/kata/54da5a58ea159efa38000836) - feel like my solution to this one was fairly clever :-)
[Maximum subarray sum](https://www.codewars.com/kata/54521e9ec8e60bc4de000d6c) - this one was challenging. I feel like the top solutions were much better than mine, and I'm still working on understanding some of them!

### Day 42: October 7, Monday
D42 #100DaysOfCode #freeCodeCamp
Started setting up my pomodoro clock app with Redux (thanks to all those who encouraged me to give it a try!). Got the basics in place - state for session times, actions (increment/decrement, play/pause, countdown), and reducers. So far so good.

### Day 43: October 8, Tuesday
D43 #100DaysOfCode #freeCodeCamp
Coded along with a great YouTube tutorial on Redux
https://youtube.com/watch?v=nrg7zhgJd4w

I was good up to part 7, then got a little overwhelmed by  the file organization for the components, store, actions, & reducers and mapping state & dispatch to props 🥴

### Day 44: October 9, Wednesday
D44 #100DaysOfCode #freeCodeCamp
Mindmapped out the details of my pomodoro timer (thanks @rdnkta!). Reorganized my files. Implemented new reducers. Was totally puzzled by some weird behavior while testing them, then finally realized I was making a shallow copy of an array 😬

***Thoughts:*** The domain-based file organization makes a lot more sense to me (keeping all the files for the timer in one folder, rather than grouping them by component, reducer, etc). 

### Day 45: October 10, Thursday
D45 #100DaysOfCode #freeCodeCamp
Got my pomodoro timer components connected to the Redux store. It's not pretty yet, but I implemented some basic functionality. I'm liking Redux so far, but I need to learn where best to implement the business logic and side effects. 

[Animation of first draft of pomodoro timer](https://twitter.com/i/status/1182578627168391168)

### Day 46: October 11, Friday
D46 #100DaysOfCode #freeCodeCamp
I've settled on putting the timer logic inside functions in the parent App component. They handle the interval, then dispatch actions to Redux store. Seems like it will work ok. Added the FCC test suite and got 21/29 of the tests passing

![Pomodoro timer with 21/29 tests passing](https://pbs.twimg.com/media/EGqy8rVWwAAO_lj?format=jpg&name=small)

### Day 47: October 12, Saturday
D47 #100DaysOfCode #freeCodeCamp
Snuck in a little coding time while grilling the chicken yesterday 😁 and learned about redux-thunk. It was intimidating at first, but turns out it's really not that complicated, and it's so powerful. Got first one working in my pomodoro timer 💪

I feel like redux-thunk is the piece of #redux I've been missing. It allows you to create smart action-creators with access to dispatch() and global state using getState(). Now I have a place for logic with access to all slices of state!

### Day 48: October 13, Monday
D48 #100DaysOfCode #freeCodeCamp
Centralized the remaining logic on my pomodoro timer into action creators using redux-thunk. I really wasn't sure why some of the tests were failing at first, but got them passing by adding some error-proofing. 3 more tests and design left to do.

![Pomodoro timer with 26/29 tests passing](https://pbs.twimg.com/media/EG6EXhbX4AAqUGQ?format=png&name=small)

### Day 49: October 15, Tuesday
D49 #100DaysOfCode #freeCodeCamp
Added an alarm sound to my pomodoro timer and got the rest of the tests to pass! Now it's time to come up with a better design 😅

![Pomodor timer with 29/29 tests passing](https://pbs.twimg.com/media/EG_Bp8vXYAAIjX0?format=jpg&name=small)

### Day 50: October 16, Wednesday
D50 #100DaysOfCode #freeCodeCamp
Half way there! 🥳 I worked on the design of my pomodoro timer. It still needs work, but I'm happy with how it's coming along. It really helped to look at some other timer apps for inspiration, and then do some sketches on paper before I started.

![Pomodoro timer - new monochrome design](https://pbs.twimg.com/media/EHEWGBiXkAAk7A9?format=jpg&name=small)

### Day 51: October 17, Thursday
D51 #100DaysOfCode #freeCodeCamp 
Added Font Awesome icons to my pomodoro timer and worked improving on the layout a little more. Broke half of the FCC tests, and then got them working again 😅

https://tmonks.github.io/pomodoro-timer/

![Pomodoro timer with Font Awesome icons](https://pbs.twimg.com/media/EHJbQxPXkAAa9SP?format=jpg&name=small)

### Day 52: October 18, Friday
D52 #100DaysOfCode #freeCodeCamp
I followed a great article on creating an animated SVG radial progress meter (https://codepen.io/xgad/post/svg-radial-progress-meters) and got it working on my Pomodoro timer. I still have some work to do on the positioning, but it was super fun and I like how it looks.

[Animation of Pomodoro timer with radial progress meter](https://twitter.com/i/status/1185481350100463616)

### Day 53: October 19, Saturday
D53 #100DaysOfCode
Went to an @MLHHacks Local Hack Day yesterday and learned how to start creating video games in #unity and C#. It was great meeting some new people and getting together to learn about code. Big thanks to @dana7160, @\_JasconScharf & @JKim\_Tran for making it happen

### Day 54: October 21, Monday
D54 #100DaysOfCode #freeCodeCamp
Worked on polishing and improving the responsiveness of my pomodoro timer. Added an 'active' prop for the Preset to visually indicate which preset is active, and disable the buttons while the timer is running. Getting close to wrapping this one up

[Animation of Pomodoro timer responsiveness](https://twitter.com/i/status/1186559541909118976)

### Day 55: October 22, Tuesday
D55 #100DaysOfCode #freeCodeCamp
Made a few last minor updates to my pomodoro timer. Switched to a new alarm sound, adjusted margin & positioning, and added a new Google font (a decision which took way longer than I'd like to admit 😅)

![Pomodoro app screenshot](https://pbs.twimg.com/media/EHjP9gVWoAE7h64?format=png&name=small)

### Day 56: October 23, Wednesday
D56 #100DaysOfCode #freeCodeCamp 
Hit a snag while reorganizing my code due to global variables I was using for the interval ID and audio DOM ref. After a lot of obsessing, I found a workaround, but not sure it's the best way. Should I put things like these into the Redux store?

**Thoughts:** Feel like I need a course in React/JavaScript best practices around file organization and importing. 

### Day 57: October 24, Thursday
D57 #100DaysOfCode #freeCodeCamp
Decided to move the DOM ref and interval ID into the Redux store. I got a weird error at first with one of the new action creators, but figured it out while I was on the treadmill (love when that happens 🤓) and it went smoothly after that.

### Day 58: October 25, Friday
D58 #100DaysofCode #freeCodeCamp
Refactored the code in my pomodoro timer for a better separation of concerns between the different components. I was hesitant to make changes this big when I'm almost done, but I mapped it out on paper first and it went surprisingly well 😌

### Day 59: October 26, Saturday
D59 #100DaysOfCode #freeCodeCamp
Worked more on improving the distribution of logic between the components of my pomodoro timer. Learned about writing middleware. I'm a little concerned that I'm spending so much time on this one project, but I'm learning a lot and having fun! 😊

### Day 60: October 27, Sunday
D60 #100DaysOfCode #freeCodeCamp
Refactored my pomodoro timer yesterday with custom middleware to handle the audio playback. It worked great and simplified the action creators. There's nothing like starting my day with coffee, good music, and a productive coding session ☕️ 😁

### Day 61: October 28, Monday
D61 #100DaysOfCode #freeCodeCamp
Implemented my own #redux middleware to handle the timer side effects and complex logic of my pomodoro timer. I'm much happier with this approach and the redux-thunk action creators I was initially using. It seems much cleaner and easier to follow

### Day 62: October 29, Tuesday
D62 #100DaysOfCode #freeCodeCamp
Finished simplifying my action creators, moving logic to my #redux middleware, and fixing several new bugs 😅 Almost ready to wrap the pomodoro timer up for now (for real this time 😊). I'm looking forward to starting something new!

### Day 63: October 30, Wednesday
D63 #100DaysOfCode #freeCodeCamp
Finished up and submitted my pomodoro timer 🥳 It took longer than I planned since I refactored and tried several different approaches to managing the side effects, but I learned a ton about React & Redux in the process! https://tmonks.github.io/pomodoro-timer/

The pomodoro timer was my last of the 5 projects, and I collected the Front End Libraries certification yesterday! 🥳  Thanks to @freeCodeCamp for providing such an excellent learning platform and community! I've come such a long way since I started.

![Front-End Libraries Certification](https://pbs.twimg.com/media/EIMhH95XkAAUDMt?format=png&name=small)
![JavaScript Algorithm and Data Structures Certification](https://pbs.twimg.com/media/EIMhH-CWsAAEDiq?format=png)
![Responsive Web Design Certification](https://pbs.twimg.com/media/EIMhH-DX0AUlD4D?format=png)

### Day 64: October 31, Thursday
D64 #100DaysOfCode
My personal website really needs some love. Got ssh access set up and researched how to use git to manage the files & push updates to my web host. It used to be such a complex process to make changes; maybe I'll actually keep it updated if I can just use git 😊

Also fixed the animation on my Pomodoro timer so that it ends exactly on 0:00. The calculation was off because the stroke length needed to be calculated on the inside of the stroke-width, not the outside.
