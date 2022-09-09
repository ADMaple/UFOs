# UFOs
## Project Overview
Working with Dana who is a Data Journalist on an analysis of UFO sightings. Dana wants to provide a more in-depth analysis of the sightings by allowing users to filter for multiple criteria at the same time. Using the dataset provided by Dana I've created a webpage adding filters for the date, city, state, country, and shape.
Deliverable 1: Filter UFO sightings on multiple criteria

## Resources
-Data Source: Data.js

-Software: Visual Studio Code, Javascript, HTML, CSS

## Analysis and Results of Data
When creating the webpage one of the main objectives was to create a table with the ability to call the data from the dataset using JavaScript, HTML/CSS and Bootstrap to modify style to look of the page. 

![Final Webpage](https://user-images.githubusercontent.com/108022219/189267829-1dcace8e-2b82-440e-a630-14ed0e8281e5.png)

I had to create a empty variable to keep track of all the elements that changed when a search is entered.  Then write code for 2 functions that will filter the data.
I also created a variable that saves the element that was changed using d3.select().  If/Else states were used to check if a value was changed by the user.  Then  loop through the filters object and store the data that matches the filter values.  Then lastly rebuild the table with the filtered data by passing the variable.



## Summary 
The drawback of the page in its format makes it unclear what values users may enter that will actually return results. All entries are also case sensitive and must be lowercase. This will likely make searching not user friendly to someone who isn't familiar with the dataset. There could be a resolution by selecting options from the data and adding drop down menus in the search boxes for each category based on actual values from values that exist in each field in the dataset. For example the shapes could easily be done with an initial select distinct query to populate the select options. The data could also be more a bit more comprehensive, perhaps using an API as a source would provide not only MORE data but also the possibility of regular updates. Adding these features would make the webpage capable of so much more and maybe make the user experience better.
