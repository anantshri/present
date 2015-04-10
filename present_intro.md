<!-- .slide: class="center" -->
# Present 
## reveal.js Workflow Automation
<center>
https://github.com/anantshri/automated_revealjs/
</center>
--

# Workflow features

1. Write presentation in Markdown
1. setup presentation
1. present to the audience
1. save as pdf
1. Aggregate multiple markdown files in one place
1. clean the folder


--

# Project page

* Project Page : https://github.com/anantshri/automated_revealjs/

* Blog Post: http://blog.anantshri.info/automated_revealjs_setup/

--

# Why?

1. Cure the itch
1. Reveal.js works as a good base but lacks a workflow.
1. provide a workflow to reveal.js.
1. leverage external markdown to version control text

--

# why Reveal.js

1. HTML5 based hence "no installation needed"
1. Any modern browser works
1. Markdown support

Check http://lab.hakim.se/reveal-js/ for more details.

--

# Installation

<pre>
wget https://raw.githubusercontent.com/anantshri/automated_revealjs/1.0/present -O ~/bin/present
chmod 755 ~/bin/present
~/bin/present init
</pre>
--


# present init

This will initialize the automation tool
<center>
![Present INIT](resources/images/present/init_70.png)
</center>
--

# present setup

Once you have your folder decided and you want to present the slide all you need to do is.

`present setup file_name.md`

where file_name.md will be name of markdown file

<center>
![Present Setup](resources/images/present/setup.png)
</center>

Notes:
This step will perform basic setup and html file creation and linking.

--

# present

This will open chromium or chrome and will start projecting the presentation

<center>
![Present](resources/images/present/present.png)
</center>

--

# present print

Various scenarious exist where its needed to print the slide deck as PDF. `present pdf` does just that it opens chrome and allows you to just do a CTRL+P and save pdf file.

<center>
![Present pdf](resources/images/present/pdf.png)
</center>

--

# present clean

As the name suggest it cleans the current directory.

<center>
![Present Clean](resources/images/present/clean.png)
</center>

--

# More Features

One of the advance feature which i have added is shown in next page

There are many features that i would like to add in the workflow however i am also keen on listening to what the users need and will update it accordingly.



--

# present require

This allows you to keep all your markdown at one location and then create a requirement file to point to those and use all of them to create one slide.

This allows us to modularise the slide deck and keep common repeatable elements in one location and allowing easy reuse.

`present require requirement.txt`


<center>
![Present Require](resources/images/present/require.png)
</center>


--

<!-- .slide: class="center" -->
# Any Questions
