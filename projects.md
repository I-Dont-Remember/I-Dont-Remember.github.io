---
layout: page
title: Projects
permalink: /projects/
---

My [Github](https://github.com/I-Dont-Remember) is the best place to view projects I have worked on, am working on, or have on my list of want-tos.


* ### Web Scraping
  * [Github](https://github.com/I-Dont-Remember/web-scraping)
  * *Faculty scraper* - Though only a short project, I feel it is worth mentioning because it's not the number of lines or the time spent on a project that make it useful, but it's impact. A friend had been asked to grab a filtered list of names and emails from an online database, which would have taken days (3500ish names) to go through.  I wrote a scraper that both filters out the unneeded depts and sorts the list into a .csv file and delivered them a handy list of 2500 names to their undying gratitude (I got food, totally worth it).
  * *IT book downloader* - Website of free technology e-books in pdf form, many looked very interesting so I figured I'd scrape all 7300 titles.  What's the point of having an NFS server if you don't have any files right? :) 

* ### Ansible Laptop Installation
  * [Github](https://github.com/I-Dont-Remember/AnsibleLaptophttps://github.com/I-Dont-Remember/AnsibleLaptop)
  * After having to reinstall Linux because Windows had messed up yet again, I had hoped to find a tool that could help automate all of the setup and customization that goes into a laptop.  Luckily, I found a lot of neat articles suggesting to use Ansible directed at localhost to accomplish this.  It's a somewhat slow/iterative process as I think of more pieces that I want in certain ways, but a good chunk of the base packages and tools I use are functional. I have a bootstrap script in the git repo so I just have to clone the repo and run the installation.  I test it in a VM snapshot after a clean install so I can be 100% sure things are working as expected.
  * Hand in hand with this is my dotfiles repo, to store even more configuration!  Not only does the Ansible repo install with a single script, but it calls the dotfiles repo which also installs in one command.  Wowza!  It's so automated I love it!

* ### LifeText
  * [Frontend](www.lifetext.us)
  * [Github](https://github.com/I-Dont-Remember/MHacks2017)
  * SMS based API hub to allow access to information when you don't have data.  MHacks X project.  We used the Twilio API to handle SMS, then used Python's built in difflib to make it so texts can be somewhat natural sounding as long as they include something close to spelled like a key word.  API's were Dark Sky for weather, Wikipedia, and NewsAPI.  It's hosted on AWS in a Docker container for ease of setup and rebuilding.  The frontend we added later on in the hackathon to give users a way to adjust the emergency contacts that want listed, but it ended up causing the most trouble so we had to pivot and build it just as a mock.  We'd like to continue on and see what this could become if we integrated social media and had a strong focus on countries/ areas that rarely have data connection.

* #### sms2sheets
  * Connects the Twilio SMS API with the Google Sheets API to let me input data into my finance sheet when I don't have wifi or my laptop.  Flask server running from a Docker image on AWS, [HighCharts](https://www.highcharts.com/) for the graphs.  Depending on when this is being read, it should have a front end input to the sheet as well as charts to display information from the sheet.  Would like to eventually rework the sheets connection act more like a database, whereas right now the structure of the sheet is what I was using when I was manually inputting all the data.

* ### Copundrum
  * [Chat bot](https://i-dont-remember.github.io/copundrum/)
  * Chat bot project from the MadHacks Hackathon (Spring 2017).  Got the Iphone theme from Codepen and created the bot to have a variety of words it watches out for, and if it doesn't know how to process it responds with either a pun or uses the Giphy API to respond with a (hopefully) relevant gif.  We also incorporated the ability for it to play tic tac toe.

* ### This Website
  * Uses a neat theme made for Github pages and Jekyll.

* ### Microprocessors ECE353 Final project
  <a href='http://www.youtube.com/watch?feature=player_embedded&v=cX48qmks5qg' target='_blank'><img class='center' src='http://img.youtube.com/vi/cX48qmks5qg/0.jpg' alt='YouTube video' width='240' height='180' border='10'/></a>
  * [Video link](https://www.youtube.com/watch?v=cX48qmks5qg)  
  * Using a Tiva Launchpad and a number of drivers we helped write over the length of the course, my partner and I decided on the game Missile Command to emulate with our microprocessor.

* ### My Previous Site
  * [Old site](https://i-dont-remember.github.io/PersonalSite/)
  * First attempt at web development.  Decided on Bootstrap since it made life so much easier, without it I would have been even less of a fan of CSS than I already am.

* ### W.E. Sorter
  * White elephant name sorting program.  People at work had brought up the possibility, and it was one of the first times I finally saw where programming could solve a problem in my life.

* ### Text2Vote
  * On hold until sms2sheets is done to our satisfaction. Goal is to use that knowledge of Twilio and gspread to make a small voting application for use with the Gymnastics Club.

* ### Personal Scripts
  * Repo I use to hold scripts I end up writing for use on my home machine.
