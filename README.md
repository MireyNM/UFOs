# UFOs
UFO Sightings with Javascript
## Overview
In this project, we built a table using data stored in a JavaScript array. And we have created filters to make this table fully dynamic, meaning that it will react to user input, and then place the table into an HTML file for easy viewing.
We have customized the webpage using Bootstrap, and equiped the table with several fully functional filters that will allow users to interact with our visualizations

### Aim
The aim of this project is to create an interactive webpage that allows readers to parse the data around UFO sightings.

## Resources 
- Data Source: data.js (link)
- Software: Visual Studio 1.69.1
- HTML code: https://github.com/MireyNM/UFOs/blob/main/UFO%20Final/index.html
- JavaScript code: https://github.com/MireyNM/UFOs/blob/main/UFO%20Final/static/js/app.js
- Style .css code: https://github.com/MireyNM/UFOs/blob/main/UFO%20Final/static/css/style.css


## Results
Using JavaScript and HTML we have created an interactive webpage that allows the reader to parse the data around UFO sightings. 
As we can see in Fig.1 below, the user can search the data by filtering based on: 
- Date 
- City 
- State 
- Country
- Shape 

<p align = "center">
<img width="499" alt="Outcomes_vs_Goals" src="https://user-images.githubusercontent.com/109363759/201279568-4de5b53a-6be7-4a65-98d8-a56f036a02c1.png">
</p>
<p align = "center">
Figue 1 - Figure showing the webpage before filtering data.
</p>


When a user wants to see data for the date ```1/13/2010``` per exemple, he/she must write this value in the first filter field. As we can see in Fig.2 below, 3 sightings were recorded in that date. 

<p align = "center">
<img width="499" alt="Outcomes_vs_Goals" src="https://user-images.githubusercontent.com/109363759/201279167-80330cde-9700-40be-9f0d-46865c318081.png">
</p>
<p align = "center">
Figue 2 - Recorded UFO sightings on 1/13/2010
</p>

If the user wants to see UFO light sightings on ```1/13/2010```, he/she must enter light in shape filter. One recorded value will remain in the table (See Fig.3)
 
 <p align = "center">
<img width="499" alt="Outcomes_vs_Goals" src="https://user-images.githubusercontent.com/109363759/201279198-b9a4e885-3c7e-4dbb-a51e-dba6637629b7.png">
</p>
<p align = "center">
Figue 3 - Recorded UFO light sightings on 1/13/2010
</p>

Users may enter as many filters as wanted together and empty the filter boxes that they don’t in order to parse the data around UFO sightings. 

### Summary
Despite being visually appealing and dynamic, this design present one important drawback. Each time, users want to start a new selection criteria, one must go through all the input fields to delete the previous search criteria. This could take a lot of time and could easily annoy the user. I would suggest adding a "clear filters" button that would empty all input fields by one click.
Moreover, in order to make the code shorter and faster, I would suggest refactoring the code by deleting filterTable() function and merging it with updateFilters() function.  

