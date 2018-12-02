# Team Koalafied Website
After deliberation by the Media Team and Amber at the 2/12/18 meeting, it has been decided a new layout for the website will be created. We're doing this from scratch, so we'll all get to know the development process, and will have everything set up properly, and not just adding things in dribs and drabs. **PLANNING!**
This website will use the layout as featured in my binder drawings, if you want to see 'em, hit me up at [smithomaster@gmail.com](mailto:smithomaster@gmail.com).
Also, I am writing this and the syntax guide to my own specs, without communal discussion, so if you think there's something I could do better, tell me. I'll fix it up.
## Editing
We are using GitHub now, so we won't have any more source control problems as we add more members to our website team! If you have any problems with GitHub, hit me up!
## Syntax!
The most important part of code is the beautiful Syntax we know and love. 
To keep the code neat, we will **nest** everything beautifully, like this: 

    <!DOCTYPE html>
	<html>
	    <head>
	        <link rel="stylesheet" type="text/css" href="koalafied.css">
	        <title>Team Koalafied - FRC #6996</title>
	    </head>
	    <body>
	        <div id = "header">
	            <p class= "credit">Website made by Team Koalafied Student members</p>
	        <nav>
	            <!-- Menu List -->
	            <ul class="menu">
	                <li>
	                    <a href = "index.html">
	                        <!-- The dropdown container -->
	                        <div class = "dropdown">
	                            <!-- The button -->
	                            <button class="dropbtn">Home</button>
	                        </div>
	                    </a>
	                </li>
The  tab key (or as I call it, the "*indent button*", is your friend! I'm not fussed about empty lines between code, because that's just a waste of space, but please remember to use the tab key.
## Commenting
**Comment** out of necessity, not needlessly.

A **good** comment is something like this:
	

    <!-- title for each page, won't go inside the menu div, keep underneath -->
        <div class = "page-title">
            <h1 class = "title">Team Koalafied <br> FRC Team #6996</h1>
In this comment, the comment is signalling **what** the code does, the **problem** encountered with it, and **what** needs to be kept the same to keep it running well.
A **bad** comment looks like this:

    <!-- this is a div that holds info -->
    <div class = "info">
            <!-- this is a heading -->
            <h1 class = "info">Who we are</h1>
            <!-- this is a paragraph -->
            <p>All about </p>
        </div>
In this comment, the comments are being used needlessly to describe things which are just in front of it, and have nothing that needs to be noted or problem that has been solved. It is a waste of space, and  in our code, we want to waste as little space as possible. 
## HTML5 Semantics
As a general rule, I won't be using the HTML5 semantic elements (apart from article), because I feel that the names are way too general, and that if there are enough different semantic names to make the things I want, it will be too complicated and annoying. So my good friend `<div>` wins here. 
**However**, I will be using the `<article>` tag for articles in the news and journal pages, that is a notable exception because it serves a very clear and defined purpose (unlike section).
## Hyphens or camelCase?
While I am a big fan of camelCase, and use it when I'm in C or Python, I like to use hyphens when I'm in HTML and CSS, because I think that it looks neater and is easier to read without any extra work, and making the code easier to read is what we want to do.
## Music while coding
Coding is fun, challenging at times, and can be stressful, and to make the best of the experience, you need good music. For our friends who don't already have a playlist, here are some good music choices that you can use to get the best code done:

 - **Sgt. Pepper's Lonely Hearts Club Band** - The Beatles
 - **Captain Fingers** - Lee Ritenour
 - **Maggot Brain** - Funkadelic
 - **Spiderland** - Slint
 - **Bat Out of Hell** - Meat Loaf
 - **Live at Carnegie Hall** - Stevie Ray Vaughan
 - **Master of Puppets** - Metallica
 - **Soul Circus** - Victor Wooten
 - **Bottle it In** - Kurt Vile
 - **Alien Love Secrets** - Steve Vai
 - **Surfing With the Alien** - Joe Satriani
 - **Sticky Fingers** - The Rolling Stones
 - **Word of Mouth** - Jaco Pastorius
 - **Bright Size Life** - Pat Metheny

This is by no means a complete or extensive list of good coding music, but a good starting point.
## Colour Schemes?
Yes, there is a Team Koalafied Colour Scheme that I maintain, you can find it [here](https://color.adobe.com/team-koalafied-color-theme-11235339/) with hex codes for them, which you can use on the website.
## Problems? Complaints? Queries?
If you have any problems, you can send me an email at [smithomaster@gmail.com](mailto:smithomaster@gmail.com), or if it is urgent, drop me a line at 0405 956 798 (if I am overseas, this is bound to change, so if you think there may be problems, find out my overseas number before problems arise).