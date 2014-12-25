Automated Reveal.js
===================

reveal.js + external markdown mixed with some bash awesomeness to automated routine presentation tasks

Requirements
============

1. a copy of reveal.js git repository from https://github.com/hakimel/reveal.js/ (Location to be marked as BASE) (it is assumed that $BASE/reveal.js will contain git clone of reveal.js)
2. Chrome / Chromium browser as its --app feature is extensively used.
3. a centeral directory to keep reusable resources such as images marked in RESOURCES (optional to keep images there)
4. a index.html to be placed as template in $BASE which will contain a #markdownfilename# which will be replaced with acutal markdown filename at setup time.
5. python 2.7 is what is used to test this. if you are using python 3 then you need to modify python simplehttpserver command (2 places in whole script)

SETUP
=====

1. git clone the repository to some location in the system.

2. modify the present script with proper location variables. (BASE, BROWSER, needs to be modified specifically as per environment)

3. either place the git clone location into PATH or place present into path directory I prefer ~/bin/

4. give execute permission to present script by chmod 755 present in the location.

[steps above are written considering the person is well versed with commandline if you think details are need feel free to add and create a pull request]


Usage
=====

0) perform steps from SETUP section

1) create a directory at any location on system

2) create your markdown file. (slides are horizontally seperated by --- and vertical seperation is by -- )

3) Once markdown file is created run following command

4) present setup markdown.md (if presentation.md then this command is not needed)
This step will do all the necesaary linking and place a index.html 

5) present
This step will launch browser with proper parameters which you can just maximize. The usual slide notes and stuff all works by default as per the template.

6) present print
This step will launch browser with proper parameters to provide printing. All you need to do is ctrl + P and save as PDF.

7) present clean
This step will clean all the stuff that present setup performed.


Disclaimer 
==========

I have taken care as to not harm the computer by this code but if something happens i am not to be held responsible.
