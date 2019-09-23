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
