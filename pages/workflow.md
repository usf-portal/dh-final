{% include nav.html %} {% include css.html %}

# Workflow
	
The information used for the visualization was gathered by using 
the data provided by **www.slavevoyages.org** and after a bit of clean up that allowed the generated 
data to work with other programs the workflow became more manageable. 

Below are the steps taken that will demonstrate how the information generated
by **slavevoyages.org** database was used in the site **Palladio** and the results the 
information visually generated. Farther down the steps for how **Tableau** 
will also be demonstrated. 

***

![image]({{ site.baseurl}}/assets/images/1. Prep for palladio File demo.png)

Palladio

1. The information generated from **slavevoyages.org** provided data in 
	Excel format. This allowed the image to be understood in a more plan 
	manner and edited to better fit the needs of the project. 
2. After organizing the data and ensuring the information in the Excel 
	format is what will be needed for visualization, the locations of each 
	port and/or region had to be located. By using Longitude and Latitude 
	finder with the help of  Google Earth most of the coordinates were located 
	for the project with the information provided from **Webscraper.io**. 
	Note: this method was a one by one location finder method and does take time. 
3. Once the coordinates were inputted into Excel they were combined into one 
	column. For **Palladio** <span style="color:red">Coordinates are read in one 
	Excel column i.e. |17.973379,-76.758667|</span>. In the program Tableau the 
	coordinates must be separated into two different columns. 
4. The information is double checked and ready to be converted to a **CSV** 
	file. Note: The more organize your input the easier it is for **Palladio** 
	to read and translate the data. 

![image]({{ site.baseurl}}/assets/images/2. Prep for palladio file Demo.png)
![image]({{ site.baseurl}}/assets/images/3. Prep Palladio point ot point.png)

Palladio continued…

5. Once step 4 is complete and the data is organized in a **Palladio** easy to
	understand manner the Excel file is ready to be converted to a **CSV** file. It
	is best to simplify your data to its most raw form and title each column –Place 
	and Coordinate- This allows **Palladio** to read the data as intended. 
6. Go on the **Palladio** website and simply drop your **CSV** file on to the site.
	The orange arrows show where to drop off the file. 
7. **Palladio** will bring up the work screen and any possible issues you might 
	have with your data. The more simple and consistent your data the less issues you 
	will have with **Palladio**.
8. Once the Data is submitted and you click on Map (Top Left Corner) this screen 
	will pop up. You will click on the Top right box and load your data to visualize
	your input. This is an example of the point manger that **Palladio** offers. 
9. This is an example when you use the point to point layer and its final 
	results. 
	
***

**Tableau**

![image]({{ site.baseurl}}/assets/images/6a. Tableau working flow.png)

The program **Tableau** was much more user friendly and no change of text file
was required. The only issue encountered was that unlike **Palladio** you DO need 
to make sure you have your Latitudes and Longitudes in different columns. By naming 
them Latitude and Longitude it made the process much easier.**Tableau** recognized 
the intentions and easily transferred the data.   

![image]({{ site.baseurl}}/assets/images/6.Tableau end result .png)

By having uniformed and clear data **Tableau** made it very easy to display the 
text into images that were easy to understand. 

---

# **Project Background**

Throughout the research process you are required to utalize a few skills in order to fully develop your thesis. One of many skills in the research process is data mining. This a series of data gathering that should be use in your research project to further support or null your hypothesis. In this case we used data previously scraped from the Slave Voyages database. To further our claim we searched the university database, and JSTOR to find sources that can link the Slave Voyages database and pirates. 

**Orange3**

**Orange3** is a user friendly program that is used to implement another skill in which is required to fully develop a functioning research project. Text anaylsis is a skill that many people use and not fully understand that they are using it. Simply, text anaylsis is the deep understanding on how sources link togeather. **Orange3** simplifies this process by determining constants within different sources. 
1. Open **Orange3** from the desktop app.

![image]({{ site.baseurl }}/assets/images/Orange3_1.JPG)

2. Select the **corpus** in the text mining catagory. Upload the file. For this demonstration we are going to use the data scraped by **Webscraper.IO** off the slave voyage database.

![image]({{ site.baseurl }}/assets/images/Orange3_2.JPG)

3. Next, place down a **corpus viewer** to make sure that the **corpus** pulled in the correct data.

![image]({{ site.baseurl }}/assets/images/Orange3_3.JPG)

4.Once, you have made sure that the correct data has been pulled; drop down a **bag of word**. This application will sort through your data and pick out words that show up in frequency. 

![image]({{ site.baseurl }}/assets/images/Orange3_4.JPG)

5. After the **bag of words** is placed drop down a **word cloud**.

![image]({{ site.baseurl }}/assets/images/Orange3_5.JPG)

Once you place down **word cloud** you are able to see the like words in which appear over the document. The larger the word and the closer the word is to the center of the cloud; the more frequent the word is used throughout the document.

![image]({{ site.baseurl }}/assets/images/word_cloud.png)

From the visualization above we can conclude that through all of the slave voyages gathered in the dataset, the majority of the voyages are Spanish in nature. Many words that show up frequently have ties to the Spanish government. This discovery does not falter away very far from popular history on the international slave trade. There was no secret that that the trans Atlantic slave trade was primarily dominated by the Spanish and the English. 
