# windspeed_analysis

Project is intended to become a repository of windspeeds for Canadian cities from 1953-2014. 158 Canadian cities represented, each with their own data visualization created with matplotlib, and pandas python libraries. Heavy emphasis on data cleaning throughout this project, the data sets were received from the Canadian federal government's Open Data Portal as text files. 

<b>The data cleaning process for each of the 158 files was:</b>
<br>navigate to textfile</br>
<br>Open in Microsoft Excel</br> 
<br>Convert from .txt to .csv using the Data tab in Microsft Excel</br>
<br>Save File as a .csv UTF-8 encoded</br>
<br>read files from directory into pandas data frames</br>
<br>replace all outliers with median values of each column</br>
<br>remove null values</br>
