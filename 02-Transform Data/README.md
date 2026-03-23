# Transform Data

Click Develop

<img src="image\Click Develop.png" width=100% height=40%>

Click the three dots (…) > Click New data flow

<img src="image\Click the three dots (…) and Click New data flow.png" width=100% height=40%>

Enter Name

<img src="image\Enter Name.png" width=100% height=40%>

Click Add Source

<img src="image\Click Add Source.png" width=100% height=40%>

Enter Output stream name > Click New

<img src="image\Enter Output stream name and Click New.png" width=100% height=40%>

Click Azure SQL Database > Click Continue

<img src="image\Click Azure SQL Database.png" width=100% height=40%>

Select Linked service. If there is no Linked service available, click New to create a new Linked service

<img src="image\Select Linked service. If there is no Linked service available, click New to create a new Linked service.png" width=100% height=40%>

Edit linked service

<img src="image\Edit linked service.png" width=100% height=40%>

Select Table name > Select Import schema > Click OK

<img src="image\Select Table name, Select Import schema and Click OK.png" width=100% height=40%>

Click Add Source

<img src="image\Click Add Source2.png" width=100% height=40%>

Enter Output stream name > Click New

<img src="image\Enter Output stream name and Click New2.png" width=100% height=40%>

Click Azure SQL Database > Click Continue

<img src="image\Click Azure SQL Database2.png" width=100% height=40%>

Select Linked service > Select Table name > Select Import schema > Click OK

<img src="image\Select Linked service , Select Table name , Select Import schema and Click OK.png" width=100% height=40%>

Click + > Click Conditional Split

<img src="image\Click Conditional Split.png" width=100% height=40%>

Enter Output stream name > Select Right stream > Select Join type > Select Join conditions

<img src="image\Join settings.png" width=100% height=40%>

Click + > Click Select

<img src="image\Click + and Click Select.png" width=100% height=40%>

Select the columns you want. If there are any columns you don’t need, remove them

<img src="image\Select the columns you want.png" width=100% height=40%>

<img src="image\If there are any columns you don’t need, remove them.png" width=100% height=40%>

Click + > Click Alter Row

<img src="image\Click + and Click Alter Row.png" width=100% height=40%>

Select Alter row conditions > Click Open expression builder

<img src="image\Select Alter row conditions and Click Open expression builder.png" width=100% height=40%>

Filter by keyword > Click isNull

<img src="image\Filter by keyword and Click isNull.png" width=100% height=40%>

Click StoreID

<img src="image\Click StoreID.png" width=100% height=40%>

Save and finish
w
<img src="image\Save and finish.png" width=100% height=40%>

Click + > Click Sink

<img src="image\Click + and Click Sink.png" width=100% height=40%>

Click sink1

<img src="image\Click sink1.png" width=100% height=40%>

Select Azure Synapse Analytics

<img src="image\Select Azure Synapse Analytics.png" width=100% height=40%>

Select Linked service > Select Table name > Select Import schema > Click OK

<img src="image\Select Linked service , Select Table name and Select Import schema.png" width=100% height=40%>

DimDataFlow

<img src="image\DimDataFlow.png" width=100% height=40%>

DimensionDataFlow

<img src="image\DimensionDataFlow.png" width=100% height=40%>

Click Monitor

<img src="image\Click Monitor.png" width=100% height=40%>

Click Pipeline_Sales_Total

<img src="image\Click Pipeline_Sales_Total.png" width=100% height=40%>

Click the glasses icon

<img src="image\Click the glasses icon.png" width=100% height=40%>

View Data flow status

<img src="image\View Data flow status.png" width=100% height=40%>