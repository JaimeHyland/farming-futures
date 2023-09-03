#farming-futures
First code institute portfolio project demonstrating html and css competence. A static site.

##Introduction
This website was prepared for presentation as a first portfolio project for my online course in Full-Stack programming with the Code Institute, based in Blackrock, Co. Dublin. I have interpreted the as being to exhibit my ability to produce a simple website
using effectively only html and css technologies. This includes a requirement to make at least basic adjustments so that the website looks professional and complete, but as my course is not in creative web design, I have not spent much time nor made much effort on finer
aesthetic questions. The site should be judged according to the criteria set out under the headings set out below:

##Accessibility

I have given all images used (other than merely decorative background images) a sr-readable alt text. Throughout the website, font colours appear on sufficiently contrasting backgrounds, with the addition where necessary of semi-opaque background colours over
background images.

##Acknowledgement of others' work and inspiration and help from others.

All the code is my own, though much of it follows closely the code created by Jo Heyndels for the 'Love Running' walkthrough project. Many thanks are due to Jo for her lovely static website and her clear instructions and high-quality learning material. 
I have of course researched widely to find out how to implement features not included in Jo's website, including many visits to the following sites. With the exception of the favicon I created, none of the images used on this project were original to me.
I have provided acknowlegements for each of the images individually below.

I have made use of a lot of publicly available information on the internet, including the following sites:
w3schools.com
stackoverflow.com
freecodecamp.com
geeksforgeeks.org
...

I have not, however directly copied any code from any of these sources. I therefore have not marked any code in my project as being other than my own (with the exception of some lines copied directly from Jo Heyndels' walkthrough project).

##Development and implementation environment, and iterative deployment
All the code created during this project was written using gitpod.io, with version control using git, and deployed using github on a daily basis.

##Design methodology version control philosophy
The code was written on a section-by-section according to "mobile-first" principle, only building screen-query-based responsiveness into the product once the broad lines of the app were built and tested on the Galaxy-S8 emulator provided by Google. If I were to do the
job again, I might well change my approach. I provide more details in the "Lessons learnt" section below.
I committed new changes relatively often, and tried to keep a certain thematic logic to the changes included in each commit, but I did make some minor changes "on the fly" as I encountered them, sometimes not mentioning them at all in commit comments. I have tried to make sure such undocumented changes and bug fixes were limited to minor tweaks. I made pretty intensive use of the "git diff HEAD" command to make sure of this.

##Coding philosophy
I have tried to follow a "clean programming" paradigm in my work. I have therefore:
- not added code for any as-yet unimplemented functionalities
- deleted rather than commented out redundant lines of code
- avoided repetition in my css code as much as possible
Given that javascript programming is outside the scope of the project, quite a deal of cutting and pasting was required in my html code.

 
##Iterative testing, validation and troubleshooting - during testing and before final submission.
The main browser against which my code was tested in an iterative process (running a smoke test before every commit at the very least) was the latest version of Google Chrome (using the development toolkit provided by Google). Near the end of the development process, I used my own Samsung Galaxy A7 (running on the latest version of Chrome), my ipod (running on the latest version of Safari), and my laptop, using the latest versions of Chrome, Microsoft Edge and Firefox. Owing to lack of time, I was unable to do any testing on any legacy versions of these or on any other browsers or machines.
Testing included checking the images (including background images) on different screen sizes for unsightly pixilation.

All internal and external links were checked systematically before submitting the project for assessment.

I validated my html and css code regularly during development via direct input into the validation services provided by W3C at https://validator.w3.org/ and https://jigsaw.w3.org/css-validator/. My final code passes both validation tests.

##comments in code and css code arrangement
I have tried to err on the side of too many rather than too few comments in my code files, as the point in this case it to show the assessors that I understand what I'm doing, and not simply cutting and pasting code from elsewhere. As is required in css code, I have tried to organise my selectors from generally applicable selectors to more particular ones, from homepage to linked pages (in order of appearance on the menu), and within pages from left to right and from top to bottom. 

##Lessons learnt
The next time I do a similar project, I will continue follow the "mobile first" design paradigm, but in future I will embed that approach iteratively within the development of each section of the site. The effect of completing a round of coding for the whole site before switching to media-query-based coding was that I needed reacquaint myself with the code in each section before beginning work. I hope that if I start the media-query-based programming as I finish each section, the code for that section will still be fresh in my mind, thus saving me time and effort.

When faced with the inevitable coding issues due to my status as a beginner coder, I could sometimes have managed my time a little better.


##outstanding tasks

###as outside scope of project
Some functionality is incomplete in the project, especially the following:
social media links are to the home pages of the respective media
form data entered via the site is sent to code institute's test environment rather than being collected and saved
the traditional splashscreen to conform with EU GPDR regulations is unnecessary, as no data is being collected in reality
various functionalities requiring javascript have not been implemented as the site is designed to use effectively exclusively html and css technologies
- the menus should disappear when the user selects an item on them or taps/clicks anywhere else on the screen
- 

###for lack of time
The favicon images are not perfect either in basic design or colour scheme. If I my time over, I would have made them differently.
I would like to have implemented more css-only modal dialogs.


###todo
add some external links (on new browser tab)
add video
add tooltip to anchor icon
add screenshots and feature explanations to readme
complete comments in code
add key project goals (for fictional site owner) to readme
check file names for consistency, conformity and logic
check attribute names and values for consistency, conformity and logic
check for correct use of ids and classes
check headers and footers for function and consistency on each page
implement main sections on gallery, present, future and imprimatur pages






