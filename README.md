# UFO SIGHTINGS

## **Overview of Project**
In this Project, a dynamic table will be built from data stored in JavaScript and then placed into HTML format inorder to load into a webpage. It will provide a user interface where users can use multpile search criteria to filter information within a data file. 

## **Results**

On the bottom left of the webpage, users can filter results of UFO sightings around the world by selecting appropriate criteria they want to use for their search. The new interface makes it easier to search on multiple criteria. In the image below a date filter was entered to search for all UFO sightings on 1/10/2010 and the results was displayed.
![Search by Date](/static/images/search_img1.png)
 As the user includes additional filters, the result is filtered to meet the search criteria of not only the current filter entered but also all the previously entered filters. In the image below it shows that the state filter was entered (ca) in addition to the date filter (1/10/2010) thus showing the results for UFO sightings in California on 1/10/2010  

![Search by Date and State](/static/images/search_img2.png)

When additional filters are added, the results are updated to show for the multiple filters selected.

## **Summary**

The new design though provides different filters, appears that after selecting a filter, the page automatically loads to update the results. This makes it less user friendly. A recommentdation will be to add a button at the end of the filter search where D3 can be used to listen to display results after all filters have been selected. 
Also, the search data entered does not clear after the results have been displayed. This means the user has to manually delete all filters in order to start a new search. A recommendation will be to automatically clear data entered in the filter boxes to make it easier and qicker to enter a new search. 
