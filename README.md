# WAPH-Web Application Programming and Hacking -- Individual Project 1 Report

## Instructor: Dr. Phu Phung

## Student

**Name**: Ong Jai Sheng

**Email**: [ongjs@mail.uc.edu](mailto:ongjs@mail.uc.edu)

![Jai's headshot](assets/jai_headshot.png)

### Individual Project 1 Overview

Individual Project 1 Folder's URL: [https://github.com/jaisheng-ong/jaisheng-ong.github.io/tree/main](https://github.com/jaisheng-ong/jaisheng-ong.github.io/tree/main)

Live Site: https://jaisheng-ong.github.io/

Original (Reference) Portfolio: [https://jaisheng-ong.github.io/jaisheng-ong-portfolio/](https://jaisheng-ong.github.io/jaisheng-ong-portfolio/)

### General Requirements

Since I already had a portfolio a while ago, so I imported it and used it as stepping stone to start off for this project., I created an /assets folder to hold my images and 2 html file; index.html for main portfolio and waph.html for introducing course. I included the required name, headshot, contact info, education, experience and skills sections. On top of that I add a clickable link to bring guest(s) to the HTML page that introduce WAPH course.

### Non-Technical Requirements

Since I've imported my original portfolio as stepping stone so I added Bootsrap to what I already built which is 2 lines of code in my <_head_> tag, which are basically just Bootstrap's CSS and JS file. On top of that, I added both Google Analytics and FlagCounter page trackers, but because Google Analytics is invisible to visitors, thus I proceed to add a flag counter as it is visible widget.

### Technical Requirements

#### Basic JavaScript code

For this requirements, I included show/hide email feature (Under 'Contact' section in portfolio), digital clock, analog clock and jQuery which we went through in Lab 2, After that I proceed to implement two public web APIs as without jQuery both can't be loaded, then I proceed to integrate the two public Web APIs (XKCD + JokeAPI), each has their own javascript function. Since JokeAPI allows any category (if statement) and needs to refreshes every 1 minute (setInterval()).  

I included cookies for first timer and returning visitor(s), where I code a function call 'getCookie' which takes in cookies and return user previous Visit cookie's date. Another function 'checkVisit', esentially checks if the visitor(s) has the required cookie, if not alert with first timer message and set a cookie call 'lastVisit' that expires in 67 days starting the current date the cookie is assigned. If the visitor(s) is a returning visitor(s), then alert a returning message with its last visit date which we got from 'getCookie' function.

For the "one more functionality", I added the timeline feature that shows my journey so far in between in between 'Projects' section and 'Certifications' section. This feature is first implented in my original portfolio, I move it to this assignment thinking it would be cool. 
