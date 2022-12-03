<img width="568" alt="Screen Shot 2022-12-02 at 6 40 54 PM" src="https://user-images.githubusercontent.com/98800997/205409672-d7c6533a-cd75-4507-8ac6-6ceef106dbcc.png">

<img width="459" alt="Screen Shot 2022-12-02 at 6 42 52 PM" src="https://user-images.githubusercontent.com/98800997/205409815-23fe476c-d4f5-4f43-bd2f-6fcdf3d7b6b9.png">


This visualization was based on the graph that was made in "Coding Out Loud" episode 4. In this episode, they made a visual displaying the distribution of the first letters of Wordle words. Red being the most common and blue being the least common. I decided to use the same ggplot package as them, "ggkeyboard", but use a different data set. I used a dataset that contained the most common baby names from 1880-2010. 

I created a subset of this data to look at girl names from the year 2003, when I was born! (K was one of the most common first letters) Then I colored the keys based on the frequency of the letter and I determined this scale based on the distribution of the letter counts. I used case_when in my mutate function to assign colors to certain letters based on their frequency. I used different red, orange, yellow, green, and blue colors than what they used in the coding out loud episode and I had to create a different scale.  In order to put the data in ggkeyboard, we needed to rearrange the letters so they would be ordered based on how they appear on the standard computer keyboard. 

One thing that they didn't do in the coding out loud episode was create a custom color palette for ggkeyboard. I made a custom palette to turn the background blue and the letters white to match the inspiration photo better. Another thing they didn't do in the video was make a legend for the visualization. In the last code chunk I made a legend with ggplot because ggkeyboard doesn't have a legend parameter. 
