# AzureSQLConnection
Connecting Docker SQL container to python Script
#### Prerequisites: 
1. Running container

2.  Flask , pyodbc
  -pip install Flask
  -pip install pyodbc


3. ODBC Driver for SQL Server (17)
   
  -Driver download 
  
   https://learn.microsoft.com/en-us/sql/connect/odbc/download-odbc-driver-for-sql-server?view=sql-server-ver16
   
#### The link shows us how to connect our container instance of the Azure SQL image to our python script .
  - Proof of concept connecting to SQL using pyodbc
    
     https://learn.microsoft.com/en-us/sql/connect/python/pyodbc/step-3-proof-of-concept-connecting-to-sql-using-pyodbc?view=sql-server-ver16

    
#### Postman Testing (PUT Menthod only)
  1. Route


    localhost:5000/update/expedition_id/expeditiondDataID_FK_id

     
  3. Body : JSON

     
      { "HtmlError": "1000 Test Works", "URL": "https://example.com/image.jpg" }
