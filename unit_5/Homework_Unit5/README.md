---
title: "README.md"
author: "Matt Chinchilla"
date: "6/7/2019"
output: 
  md_document:
---
<b>Files</b><br>
yob2016.txt - This file is a series of popular children’s names born in the year 2016 in the United States.  It consists of three columns with a first name, a gender, and the amount of children given that name.
Source: https://raw.githubusercontent.com/BivinSadler/MSDS-6306-Doing-Data-Science/master/Unit%205/yob2016.txt

yob2015.txt - This file is a series of popular children’s names born in the year 2015 in the United States.  It consists of three columns with a first name, a gender, and the amount of children given that name.
Source: https://raw.githubusercontent.com/BivinSadler/MSDS-6306-Doing-Data-Science/master/Unit%205/yob2015.txt

Homework_Unit5.Rmd - This is the Unit 5 homework R Markdown file

Homework_Unit5.html - This is the unit 5 homework in html for convienitent display in a web browser

GirlsTop10Names.csv - This file contains the top ten Female names sourced from yob2015.txt and yob2016.txt

<b>R Version and System Info</b><br>
Platform: "x86_64-apple-darwin15.6.0"<br>
R version: "R version 3.5.3 (2019-03-11)"

<b>R Packagees Used</b><br>
utils<br>
base<br>
dplyr<br>


<b>R Objects</b>
path - Url path<br>
df - data frame of yob2016.txt data<br>
y2016 - data frame of yob2016.txt data tidy<br>
y2015 - data frame of yob2015.txt data<br>
final - y2015 and y2016 merged on common First names<br>
finaldec - data frame with final data sorted in decending order<br>
JustGirls - finaldec data filtered on just girls<br>
JustGirlsTop10 - JustGirls subsetted data to display the top ten girl names and total children with that name

