# Day Lengths in Helsinki and New York
## Overview
The objective of this project was to show the seasonal changes in the length of days. I was much inspired by this set of graphics published by [Helsingin Sanomat](https://www.hs.fi/kotimaa/art-2000009325191.html). I decided to improve my skills by trying to create a similar set of graphics depicting Helsinki and New York. My goal was also to improve my grasp of the work flow in creating graphics with Adobe Illustrator and make two things: make webpage content that collapse on top of one another when the webpage is narrowed and make a responsive `ai2html` graphic that has mobile and desktop versions.
## Data
I collected the sunset and sunrise times from [this website](https://sunrise-sunset.org/). Calculating the length of days and showing the visually was challenging because an hour is split into 60 units, not into 100 units. I used to functions in an Excel spreadsheet to calculate the length of days from sunrise and sunset times decimal numerals. Then I converted those figures into hours and minutes. For example, 5.93 became 5 hours and 56 minutes. The `excel` file containing data is in the `data` folder. 
## Visualization
 I used Datawrapper to sketch first drafts of the charts. I then imported the sketches in `svg` format into Adobe Illustrator. I used `ai2html` to create the responsive graphics. The code for the graphics is in the `graphics` folder.
 ## Webpage
The code and images for the webpage are in the `docs` folder. The webpage is [here](https://juhanarossi.github.io/helsinki-nyc-days/). I worked with `css`  and Bulma and created a style sheet through trial and error.
## Lessons Learned
This project's main goal was to create charts that collapse on top of one another when the webpage is narrowed and to a responsive `ai2html` graphic that has mobile and desktop versions. That I did, though my output is rather unpolished. I made progress in visualizing data. The next steps are to become more proficient in working with `html` and `css` and to learn to use Abode Illustrator better. 
