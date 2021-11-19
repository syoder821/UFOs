# Project UFOs

## Overview of analysis
The purpose of this project is to create a table to organize UFO data that is stored as a JavaScript array and display on a webpage. This table has the ability to filter data based on certain criteria and is created using JavaScript as the primary coding language.  A dynamic table is generated that provides an in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. Filter criteria include: date, city, state, country, and shape.

## Resources
- Data Source: JavaScript array in static/js/data.js
- Software: JavaScript, HTML

## Results:
A guide to performing searches with filter options using images of the webpage during the filtering process are shown below.  The filtering fields are selected one at a time and the results are updated after each filter selection.  
### Filtering step 1:
Enter a filter option in the filter search table for the Date, City, State, Country, or shape. Once you hit enter or click on the next filter box the table will be updated.  Below is the image of the initial table prior to any filters selected.   

![Alt Text](https://github.com/syoder821/UFOs/blob/main/static/images/initial_unfiltered_table.png)

Image of the updated table after ca is entered in the Enter State filter box.  

![Alt Text](https://github.com/syoder821/UFOs/blob/main/static/images/state_ca_filtered_table.png)

### Filtering step 2:

Enter another filter option in the filter search table for the Date, City, State, Country, or shape. Once you hit enter or click on the next filter box the table will be updated with the additional filter selection. 
Image of the updated table after ca is entered in the Enter State filter search box and light is entered in the Enter Shape search box.  As seen in the image, the results are now filtered on both State and Shape.  

![Alt Text](https://github.com/syoder821/UFOs/blob/main/static/images/state_ca_shape_light_filtered%20table.png)

### Filtering step 3+: 
Additional filters can be added just as in steps 1 and 2. 

### Reseting / Removing filter selections
To remove a filter selection delete the text inputed in the filter selection box and press enter or click the mouse.    

## Summary
One drawback to this design is the inital background values shown in the filter boxes may be confusing and not clear that the intial table has no filtering applied at all.  
A nice improvement for the website would be to remove these and add drop down menus for the filter search items in their place.  This would show intially the filter items blank prior to selecting values from the dropdown menus and would make it clearer that the intial table shows an unfiltered result.  Another recommendation for improvement to the site would be to add a reset filter button to clear all selected filters.  

