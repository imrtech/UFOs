# UFOs

## Overview of the analysis:

The purpose of this project was to use our knowledge of JavaScript to organize the UFO data into tables that can be filtered based on a user's selection. We used Javascript functions to loop through the data to build the table and to create a visual dashboard on an HTML page. We used event listeners to record the information once a change in an element occured. We built a filter search that would allow a user to search based on a date, city, state, country and shape. We also used Bootstrap to help organize the webpage's content into containers, rows, and columns and used CSS to customize the font color and font size of the body and navigation bar. This created a visually pleasing webpage with light text and a dark background, that can be easily read and searched.  

## Results:


- The user interface is a clean webpage.
Webpage: 
![This is an image](/static/images/webpage.png)

- It contains a filter search that allows a user to select a date, city, state, country and shape. 
Filter Search:
![This is an image](/static/images/filter_search.png)

-- The filter search records the selections and stores the results in the table to it's right. The table contains columns for Date, City, State, Country, Shape, Duration and Comments.

Table:
![This is an image](/static/images/results_table.png)


-- You can select multiple items from the filter to narrow your search criteria.  For example, when you search by "city", the table will update to only show that "city". If you select an additional search item such as "shape", the results will only show rows that contain the shape you selected for the "city" in your first search results.
Search criteria 1:
![This is an image](/static/images/search1.png)

Search criteria 2:
![This is an image](/static/images/search2.png)


- The code files can be found here:  [filename](/static/js/app.js)
- The code files can be found here:  [filename](/static/js/data.js)
- The code files can be found here:  [filename](/static/css/style.css)
- The code files can be found here:  [filename](/index.html)

## Summary: 

**Drawback:**
While the webpage seems clean and simple enough to use there is one drawback. In the filter search fields, the entries are case-sensitive. If a user misspells a word, or uses capital letters, the search will fail to show results.

For example, in this particular search for the city of "el cajon" I typed "El cajon" using a capital "E". The search did not yield results even though it was spelled correctly.
![This is an image](/static/images/case_sensitive.png)

**Recommendations:**
A recommendation would be to add instructions for the user to make sure they use only lower-case letters or converted the text fields into drop-down lists. That would ensure the user does not encounter any errors.

Another recommendation would be to sort the results by latest UFO sightings. That could be an additional filter.