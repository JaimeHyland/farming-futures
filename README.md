#farming-futures
First code institute portfolio project demonstrating html and css competence. A static site.

##Introduction
This website was prepared for presentation as a first portfolio project for my online course in Full-Stack programming with the Code Institute, based in Blackrock, Co. Dublin. I have interpreted the as being to exhibit my ability to produce a simple website
using effectively only html and css technologies. This includes a requirement to make at least basic adjustments so that the website looks professional and complete, but as my course is not in creative web design, I have not spent much time nor made much effort on finer
aesthetic questions. The site should be judged according to the criteria set out under the headings set out below:

##Accessibility

I have given all images used (other than merely decorative background images) a sr-readable alt text. Throughout the website, font colours appear on sufficiently contrasting backgrounds, with the addition where necessary of semi-opaque background colours over
background images.


##Development & implementation environment, and iterative deployment
All the code created during this project was written using gitpod.io, with version control using git, and deployed using github on a daily basis.

##Design methodology version control philosophy
The code was written on a section-by-section according to "mobile-first" principle, only building screen-query-based responsiveness into the product once the broad lines of the app were built and tested on the Galaxy-S8 emulator provided by Google. If I were to do the job again, I might well change my approach. I provide more details in the "Lessons learnt" section below.
I committed new changes relatively often, and tried to keep a certain thematic logic to the changes included in each commit, but I did make some minor changes "on the fly" as I encountered them, sometimes not mentioning them at all in commit comments. I have tried to make sure such undocumented changes and bug fixes were limited to minor tweaks. I made pretty intensive use of the "git diff HEAD" command to make sure of this. I intend to add a step to this process the next time I'm working on a similar project (see "Lessons learnt" below).

##Coding philosophy
I have tried to follow a "clean programming" paradigm in my work. I have therefore:
- not added code for any as-yet unimplemented functionalities
- deleted rather than commented out redundant lines of code
- avoided repetition in my css code as much as possible
Given that javascript programming is outside the scope of the project, quite a deal of cutting and pasting was required in my html code (for the almost identical headers and footers on each page, for example).

In relation to the question of when to use the class attribute and when to use id to identify elements to style in the style.css file, I have preferred the class attribute unless the element in question is both unique in the relevant styling context and is likely to remain unique in new iterations of the site development process. 

 
##Iterative testing, validation and troubleshooting - during testing and before final submission.
The main browser against which my code was tested in an iterative process (running a smoke test before every commit at the very least) was the latest version of Google Chrome (using the development toolkit provided by Google). Near the end of the development process, I used my own Samsung Galaxy A7 (running on the latest version of Chrome), my ipod (running on the latest version of Safari), and my laptop, using the latest versions of Chrome, Microsoft Edge and Firefox. Owing to lack of time, I was unable to do any testing on any legacy versions of these or on any other browsers or machines.
Testing included checking the images (including background images) on different screen sizes for unsightly pixilation.

All internal and external links were checked systematically before submitting the project for assessment.

I validated my html and css code regularly during development via direct input into the validation services provided by W3C at https://validator.w3.org/ and https://jigsaw.w3.org/css-validator/. My final code passes both validation tests.

##comments in code and css code arrangement
I have tried to err on the side of too many rather than too few comments in my code files, as the point in this case it to show the assessors that I understand what I'm doing, and not simply cutting and pasting code from elsewhere. As is required in css code, I have tried to organise my selectors from generally applicable selectors to more particular ones, from homepage to linked pages (in order of appearance on the homepage menu), and within pages from left to right and from top to bottom. 

##Lessons learnt
The next time I do a similar project, I will continue follow the "mobile first" design paradigm, but in future I will embed that approach iteratively within the development of each section of the site. The effect of completing a round of coding for the whole site before switching to media-query-based coding was that I needed reacquaint myself with the code in each section before beginning work. I hope that if I start the media-query-based programming as I finish each section, the code for that section will still be fresh in my mind, thus saving me time and effort.

Another lesson I have learnt is that immediately following each push, I should hold a mini "stand-up" meeting with myself to identify the tasks

When faced with the inevitable coding issues due to my status as a beginner coder, I could sometimes have managed my time a little better.

##Lessons not (yet) learned
One issue I haven't had yet time to research is the implications of differing user interactions on touchscreens as opposed to desktop and laptop screens. As a result, some of the icons do not respond to user interaction in as elegant a manner as I would have hoped. This is a deficit I need to remedy.

##acknowledgements for images used

| Page | Image | Usage | Original URL | Site owner |
|................|................|................|................|................|
|................|................|................|................|................|
|................|................|................|................|................|
|................|................|................|................|................|
|................|................|................|................|................|


##What doesn't work

###Because it's outside the scope of project
Some functionality is incomplete in the project, especially the following:
- Social media links are to the home pages of the respective media
- No account exists for the e-mail link that appears on the imprimatur page
- All addresses are fictional
- Form data entered via the site is sent to code institute's test environment rather than being collected and saved
- The traditional splashscreen to conform with EU GPDR regulations is unnecessary, as no data is being collected in reality
- Various functionalities requiring javascript have not been implemented as the site is designed to use effectively exclusively html and css technologies
-- The menus should disappear when the user selects an item on them or taps/clicks anywhere else on the screen (most effectively done using javascript)

###for lack of time
- The favicon images are not particularly attractive in basic design or colour scheme. If I had my time over, I would have made them differently.
- I would like to have implemented a couple more css-only modal dialogs.


##Acknowledgement of others' work and inspiration and help from others.

Almost all the code is my own, though much of it follows closely the code created by Jo Heyndels for the 'Love Running' walkthrough project. Many thanks are due to Jo for her lovely static website and her clear instructions and high-quality learning material. I have included an appropriate comment on any code directly copied from Jo's walkthrough project.
With the exception of the very rough and ready favicon that I cobbled together, none of the images used on this project were original to me. I have provided acknowlegements for each of the images individually below.

Naturally enough, have researched widely to find out how to implement features not included in Jo's website, including several visits to the following sites:
- https://w3schools.com/
- https://stackoverflow.com/
- https://www.freecodecamp.org/
- https://www.bestcolleges.com/
...

However, aside from Jo's walkthrough project, the only source from which I directly copied was freecodecamp.org, from which I more or less directly copied the back-to-top button functionality (https://www.freecodecamp.org/news/css-only-back-to-top-button/). The place where I copied that code is therefore the only place in my projecgt I have marked any code as being other than my own.

Apart from Jo and the authors of the various online resources I used, I owe special thanks to my mentor, Oluwafemi Medale, for being available every time I needed him, and for providing high-quality, relevant and timely advice, to David Calikes of Code Institute's student welfare service, who provided encouragement when it mattered and who gave more than a few practical tips in the run up to my deadline, and to the Code Institute tutoring team, whose help I probably didn't lean on as much as I should have, and on whose time I am determined to infringe much more intensely in the run-up to my next deadline!


###todo
- add some external links (on new browser tab)
- add video
- add tooltip to anchor icon
- add screenshots and feature explanations to readme
- complete comments in code
- add key project goals (for fictional site owner) to readme
- check file names for consistency, conformity and logic
- check attribute names and values for consistency, conformity and logic
- check for correct use of ids and classes
- check headers and footers for function and consistency on each page
- implement main sections on gallery, present, future and imprimatur pages