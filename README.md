# r-bootcamp-fall-2020

Materials for the August 2020 virtual R bootcamp at UC Berkeley. See below (under the listing of files) for information about the bootcamp, including logistics, how to get the course content, and how to install the software you need for the bootcamp on your laptop.

This site is UNDER CONSTRUCTION. The information in this README and the installation instructions in the `install` directory should be up-to-date. The content in the `modules` directory is still being finalized as of Tuesday August 4.

Co-trainers: UC Berkeley Statistics and the D-Lab

## Description

### Overview

This is the website for the eighth annual R bootcamp at Berkeley. The bootcamp will be an intensive four-morning introduction to R using RStudio. Topics will include:

 * R basics - reading and manipulating data, working with R data objects, doing calculations, making plots
 * programming in R
 * doing data analysis / data science / statistical work in R
 * more advanced topics: efficiency, object-oriented programming, advanced graphics, batch jobs, parallel processing

No prior experience with R is expected, but some familiarity with programming concepts such as variables, loops, if-then-else statements, functions, etc. will be helpful.

## Logistics - when, where, and how

Course logistics

Location: online on Zoom, Zoom link to be provided via email.

Time: 
  - Monday, August 10 - Thursday August 13
  - 8:30 am - 1 pm

The 1 pm ending time is tentative. We may end a bit before 1 pm on some days.


We'll start formally on Monday morning at 8:30 am, but please plan to arrive in the Zoom room by 8:20 so you can  get settled. And if you need help with any software installation please come at 8 am. (Actually it would be even better if you email us in advance if you have installation problems.

## Course Discussion and Questions

We'll have an active [online discussion forum on Piazza](https://piazza.com/berkeley/fall2020/rbootcampfall2020) during the event. 

We'll also have in-person help using a Zoom virtual front desk (see email for link).

If you need to contact us directly with an administrative question you can email r-bootcamp@lists.berkeley.edu.

## Zoom Recordings

Recordings of the Zoom sessions will be available for each day. 

## Preparing for the course - course content

Course content is available through Github. Please download a copy of the course materials before arriving at the bootcamp using one of the two options below (if you're familiar with Git you'll also know how to do this by cloning the repository):

  1) open RStudio. Go to “File→New Project” and select “Version Control” and “Git”. Enter 'https://github.com/berkeley-scf/r-bootcamp-fall-2020' as the “Repository URL” and click “Create Project” (you can choose the directory in which to place the project with the “Create project as subdirectory of” option). It should create a “r-bootcamp-fall-2020” directory with all of the materials within whichever directory you chose. To open one of the R Markdown files, go to the lower right panel, click on 'Files', then 'r-bootcamp-fall-2020', then 'modules' and finally click on the .Rmd file of interest. It will open in the upper left panel.

  2) Alternatively, simply download a zip file containing all the content at https://github.com/berkeley-scf/r-bootcamp-fall-2020/archive/master.zip.

Here is the [schedule for the main track of the bootcamp](https://github.com/berkeley-scf/r-bootcamp-fall-2020/blob/master/schedule/schedule.pdf). We will also offer a second track that allows those first encountering R or programming to have time for more intensive practice with the initial material. Here is the [schedule for the second track](https://github.com/berkeley-scf/r-bootcamp-fall-2020/blob/master/schedule/schedule-track2.pdf). At the beginning of the second day, you'll have the opportunity to decide whether you want to stay with the main track or attend the second track. You do NOT need to decide in advance.

We recommend that you take a look at the syllabus and the background module (https://htmlpreview.github.io/?https://github.com/berkeley-scf/r-bootcamp-fall-2020/blob/master/modules/module0_induction.html) in advance to get a sense for what we'll cover. And for those of you with absolutely no experience with R, it will help with your learning curve if you try to play around with R using the material in (https://htmlpreview.github.io/?https://github.com/berkeley-scf/r-bootcamp-fall-2020/blob/master/modules/module1_basics.html) beforehand.
Alternatively, if you have absolutely no experience with R or similar languages (e.g., Python, MATLAB), you might check out [Swirl](https://swirlstats.com).

For the presentation materials (including embedded demo code), see the html files in *modules*. The *_slides_* files have individual pages, while the other html files are one continuous page per module. To run the demo code, open the .Rmd file for the module in RStudio. You can then run individual chunks of code.

## Preparing for the course - software installation
Please have a laptop (Mac, Windows, or Linux are all ok) with R, RStudio, and Git installed. RStudio and Git are optional but highly recommended. 

To install the software, it's best if you can install software directly on your laptop.

  - Install the following directly on your laptop:
  
      - R [(details here)](https://htmlpreview.github.io/?https://github.com/berkeley-scf/r-bootcamp-fall-2020/blob/master/install/RandRStudioInstall.html)
      - RStudio (optional but highly recommended) [(details here)](https://htmlpreview.github.io/?https://github.com/berkeley-scf/r-bootcamp-fall-2020/blob/master/install/RandRStudioInstall.html)
      - Git (optional but recommended for obtaining course content) [(details here)](https://htmlpreview.github.io/?https://github.com/berkeley-scf/r-bootcamp-fall-2020/blob/master/install/gitInstall.html)

Please install the software in advance. If you have trouble that can't be addressed with some troubleshooting on Google, feel free to email us at r-bootcamp@lists.berkeley.edu.

Alternatively, IF INSTALLING ON YOUR LAPTOP FAILS, the following is an alternative way to access R and RStudio through a browser:

  - Please use your CalNet ID and password to login [here](https://r.datahub.berkeley.edu). Once logged in, you should be in an RStudio session in the browser. At this point you can get a copy of the bootcamp files that your RStudio session can access by following instruction #1 above under the section "Preparing for the course - course content".

Note that our ability to troubleshoot R or RStudio installed directly on your machine is limited (particularly in Windows). We'll try to help, but if we run into roadblocks, we'll direct you to the browser option.

