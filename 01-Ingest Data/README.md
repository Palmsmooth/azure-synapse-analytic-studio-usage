# Ingest Data

Click the ‘Open’ button on Open Synapse Studio

<img src="image\Click Open on Open Synapse Studio.png" width=100% height=40%>
<img src="image\Azure Synapse Analytic.png" width=100% height=40%>

Click data

<img src="image\Click ‘data’.png" width=100% height=40%>

Click SQL database > Click dbo.logdata > Click New SQL script > Click Select TOP 100 rows

<img src="image\Click SQL database , Click dbo.logdata , Click New SQL script and Click Select TOP 100 rows.png" width=100% height=40%>

Attempting to show the top 100 rows from the table dbo.logdata, but since the table is empty, no data is returned

<img src="image\table dbo.logdata is empty.png" width=100% height=40%>

Go back to the home page and click Ingest

<img src="image\click Ingest.png" width=100% height=40%>

Click Built-in copy task > Click Next

<img src="image\Click Built-in copy task and Click Next.png" width=100% height=40%>

Select Source type and choose a Connection. If the connection path is not available, click New connection to create one.

<img src="image\Select the Source type and choose a Connection.png" width=100% height=40%>
<img src="image\New linked service.png" width=100% height=40%>

Select File or folder > Click Next

<img src="image\Select the File or folder and Click Next.png" width=100% height=40%>

Select File format > Select Column delimiter > Click Next

<img src="image\Select File format and Select Column delimiter.png" width=100% height=40%>

Select Target type > Select Connection > Click Use existinng table 

We choose Use existing table because the table dbo.logdata has already been created

<img src="image\Click Use existinng table .png" width=100% height=40%>

Select Azure Data Lake Storage Gen2 file > Click Next

<img src="image\Select Azure Data Lake Storage Gen2 file.png" width=100% height=40%>

Check Column mapping > Click Next

<img src="image\Check Column mapping and Click Next.png" width=100% height=40%>

Enter the task name > Tick the Enable staging checkbox > Select Staging account linked service > Select Storage Path > Select Copy method > Click Next

<img src="image\Enter the task name , Tick the Enable staging checkbox , Select Staging account linked service , Select Storage Path , Select Copy method and Click Next.png" width=100% height=40%>

View Summary > Click Next

<img src="image\View Summary.png" width=100% height=40%>

Click Monitor

<img src="image\Click Monitor.png" width=100% height=40%>

Click CopyPipeline_LogCSV

<img src="image\Click CopyPipeline_LogCSV.png" width=100% height=40%>

Click the glasses icon

<img src="image\Click the glasses icon.png" width=100% height=40%>

View Details

<img src="image\View Details.png" width=100% height=40%>

Once all the steps are completed, the data will be ingested into the table dbo.logdata

<img src="image\the data will be ingested into the table dbo.logdata.png" width=100% height=40%>