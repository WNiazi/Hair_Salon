# Project Hair Salon 

#### By Wajma Niazi

#### 

## Technologies Used

* VS Code
* C# 
* .NET 5.0
* Razor
* MySQL
* ASP.NET Core
* Entity Framework


## Description
* Create a C# console application for a Hair Salon that includes a list of stylist and their clients, both of which can be  viewed, added and deleted. 

## Setup/Installation Requirements
 
* Go to GitHub: https://github.com/WNiazi/HairSalon.git 
* Clone Repository to your desktop
* If you haven't already, please download the following: C#, .NET, MySQL Community Server and MySQL Workbench.  Please go to https://www.learnhowtoprogram.com/c-and-net-part-time/getting-started-with-c/installing-c-and-net, if you need to download C# and .NET and  https://www.learnhowtoprogram.com/c-and-net-part-time/getting-started-with-c/installing-and-configuring-mysql, if needed to download MySQL. 
* Launch the MySQL server with the command mysql -uroot -p[YOUR-PASSWORD-HERE]
* Go to MySQL Workbench, select MySQL instance, select Data Import/Restore, then select Self-Contained file, navigate to  wajma_niazi.sql file in the root directory of the project (HairSalon/)
*  Refresh All
* dotnet run
* Navigate to the appsettings.json file $ cd appsettings.json and enter:
```
{
    "ConnectionStrings": {
        "DefaultConnection": "Server=localhost;Port=3306;database=wajma_niazi;uid=root;pwd=[YOUR-PASSWORD-HERE];"
    }
}
``` 
* dotnet build /restore
* dotnet run


## Known Bugs
* None 

## License

_MIT

Copyright (c) 2022 Wajma Niazi

