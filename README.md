# UFOs
Overview

In this analysis, we created a UFO sightings website that allows users to filter for multiple criteria at the same time. Once the HTML is created, users are able to filter the website by date, city, state, country or shape.

Results

Using the index.html file we created in the module, we modified the code in the HTML file by creating more table filters. We created four more list elements similar to the “Enter Date” list element we created in the module. Since the codes are exactly the same, I copied and pasted the code for “Enter Date” four times and replaced the “Enter Date” with “Enter City”, “Enter State” and so on. The app.js and index.html files were modified to achieve our goal. To filter by city, the user simply need to enter the name of the desired city he/she would like to view. For instance, in the screenshot below, I filtered by Benton City, which only had one result.

<img width="1082" alt="Filtered by City" src="https://user-images.githubusercontent.com/85265504/152092081-e6522a4e-bb88-45b3-a294-ab405d496ec0.png">

The same logic is used to filter by Date, State, Country or Shape. Below is a screenshot of filtering by Date. When we filtered by 1/2/2010, we had eight results. 

<img width="1437" alt="Filtered by Date" src="https://user-images.githubusercontent.com/85265504/152092115-ee315e41-5a78-414d-84c1-d29c36dbe6a1.png">

In the screenshot below, we filtered by the state of California, which generated more results than any other state. 

<img width="1435" alt="Filtered by State" src="https://user-images.githubusercontent.com/85265504/152092143-4d65b0ac-0f73-491e-886c-049bfbb31be2.png">

In the image below, we filtered by the county of Canada and received two UFO sightings in Canada, both sightings were in Ontario, Canada

<img width="1406" alt="Filtered by Country" src="https://user-images.githubusercontent.com/85265504/152092181-8596a4ab-a889-4388-bbb4-b46a0660198b.png">

In our final filter result, I filtered by the Circle Shape, which displayed four results.

 <img width="1075" alt="Filtered by Shape" src="https://user-images.githubusercontent.com/85265504/152092210-48c96485-a49b-4076-b0ec-f200f346ab14.png">

Summary

In conclusion, the filter table worked as it should, and the website looks great and matches the information provided in our module. The drawback of this website is that we do not know exactly how many cities, states, shapes or Countries had UFO sightings at first glance, unless we scroll through the page first before attempting to filter. For instance, there are only two Countries with UFO sightings, Canada and USA. If the user is not aware and just type random countries like Ireland, Germany, and other countries before attempting to try United States and Canada, it might take a while for their search to generate a result. 

A great addition to the website will be to have a dropdown like an Excel table dropdown that includes all the Countries, Cities, States, Shapes and Dates of the UFO sightings, giving the user ability to select and filter using the dropdown button.  

Another addition is showing the amount of result each search generated. For instance, if we filtered by Benton city, it should display “1 result found” or if we filter by 1/2/2010, it should display something like, “8 results found”. 


