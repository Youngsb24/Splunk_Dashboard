<h1>Splunk Dashboard</h1>

<h2>Description</h2>
In this project I will be showing ways to maneuver through splunk. provided a detailed step by step example on how to create multiple visualization for a dashboard. As well as include how to edit the dashboard properly to make it look appealing. The dashboard I will be creating is based upon Airbnb's hosted in New York city. I will create a 6 panel dashboards to break down different views of selecting an Airbnb in New York. Lastly i'll be using a standalone splunk instance

<h3>Enviroment Used</h3>
Splunk Enterprise


<h3>Step 1</h3>
You want to create an Indexe. This is were the file downloaded will be stored. Go to settings --> then click indexe --> new indexe . Since the file im using is dealing with Airbnbs , my indexe title will be labled "Airbnb" 

<br>
<img src="https://imgur.com/wvXUg9l.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</br>
<br>
<img src=https://imgur.com/f0F4loh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</br>


<h4>Step 2</h4>
Click "Splunk Enterprise" to go back to the main page , then proceed to click "Add data" . Since we are using new data we will click the "Upload" option.Then select the file you will be using , click next , change the source type to "CSV" , then click next then change the " index" to "airbnb" then click next review it and save the data.

<br>
<img src=https://imgur.com/0RdXUNa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</br>

<br>
<img src=https://imgur.com/MIGGqC0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</br>

<br>
<img src=https://imgur.com/3Pdjlaa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</br>



<h5>Step 3</h5>
Now we want to search and make sure our file uploaded succesfully, so we click on the " Search and Report" and click search , type in "index=airbnb" remeber the field names are case sensitive and field values are not. After change the time range picker to "all time" and "verbose mode" then run the search and you should see this.

<br>
<img src=https://imgur.com/4Z80GUg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</br>

<h6>Step 4</h6>
This step we will use the fields from the side bar to create our visualization and include specific commands such as "Top and Rare command". Brief lesson , Top command is use to show the most common values of a given field , and the Rare command shows the least common values of a given field. When you run this search " index= airbnb | top 5 Neighbourhood " this screen should load up. Then you can click " Visualization" to edit what kind of visual you want to populate.

<br>
<img src=https://imgur.com/8aWR829.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
</br>
<br>
<img src=https://imgur.com/1WoJbiF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</br>

<h7>Step 5 finaly Step</h7>

As you can see I break down the top 5 neighborhoods in New york , I included the top 10 zip codes around those cities , and the prices of airbnb rooms per night dependent on how long a customers is planning on staying. And included the property type of airbnb from houses , regular apartments , also included lofts and townhouses. Lastly I just included other panels because I was bored :).
This is what your final work will look like, of course everyones will be different dependent on their preference of their dashboard. 




<br>
<img src=https://imgur.com/jbVtAyw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</br>




<h8>Extra SPl syntax</h8>




