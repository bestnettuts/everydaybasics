## SQL Server
### Standard Security 
`Server=myServerAddress;Database=myDataBase;User Id=myUsername;Password=myPassword;` 
### Trusted Connection
`Server=myServerAddress;Database=myDataBase;Trusted_Connection=True;`
### Connection to a SQL Server instance
`Server=myServerName\myInstanceName;Database=myDataBase;User Id=myUsername;Password=myPassword;`
### Attach a database file, located in the data directory, on connect to a local SQL Server Express instance
`Server=.\SQLExpress;AttachDbFilename=|DataDirectory|mydbfile.mdf;Database=dbname;Trusted_Connection=Yes;`
### Using an User Instance on a local SQL Server Express instance
`Data Source=.\SQLExpress;Integrated Security=true;AttachDbFilename=C:\MyFolder\MyDataFile.mdf;User Instance=true;` 