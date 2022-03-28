# UFOs
Module 11
## Project Background
The purpose of this challenge is to help Dana build a webpage with a dynamic table to organize UFO sightings data that is store as a JavaScript array. The table was created using JavaScript and it has the ability to filter data base on date, city, state, country or shape. HTML/CSS and Bootstrap were used to customize the webpage.

## Resources
Data Source: data.js
Software: Visual Studio Code, 1.63.2

## Results
1. Make the webpage visually appealing
<img src="/static/images/img1.png" width="50%" height="50%">

2. Deliverable 1: Filter UFO sightings on multiple criteria
- Source Code

| index.html | app.js |
| --- | --- |
| <img src="/static/images/img2.png"> | <img src="/static/images/img3.png"> | 


  - The event listener (_"click"_) has been modified so that it detects a _"change"_ on each input element and the list element that creates the button is removed
  - 5 Filters have been included that allow users to look only at sightings that match specific criteria.
  
| module 11 | challenge 11 |
| --- | --- |
| <img src="/static/images/img4.png"> | <img src="/static/images/img5.png"> | 


- Filters

| city | state | 
| --- | --- |
| <img src="/static/images/img6.png"> | <img src="/static/images/img7.png"> | 
| country | shape |
| --- | --- |
| <img src="/static/images/img8.png"> | <img src="/static/images/img9.png"> |

## Summary
Drawbacks in this webpage: 
- The user must know specific dates, cities, states, countries or shapes to search.
- The filters require exact match against the data being entered.

Recomendatios:
1. Include a drop down feature on the existing filters so users could scroll through the options or implement an autocomplete on the textbox.
2. Filter between dates to get records in specific date range.
3. Add a _clear button_.

