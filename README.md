# CE3101 - CoTEC-20
<p align=justify>CoTEC-2020 Virus tracking web app built with Angular, Ionic, .NET Core MVC API, Entity Framework Core &amp; SQL Server Database.</p>
<p align=center><img src="https://res.cloudinary.com/estalvgs1999/image/upload/v1597896745/Whitetail/CoTEC/app_logo.png" ></p>

***
# 🦠 CoTEC-20 | Case Monitoring System
<p align="left">
  <img
       src="https://camo.githubusercontent.com/a3469255f3fcdead1593919251ab6f438744e9be/68747470733a2f2f63692e6170707665796f722e636f6d2f6170692f70726f6a656374732f7374617475732f346f3338706c743078626f31756263382f6272616e63682f6d61737465723f7376673d74727565">

  <img src = "https://img.shields.io/badge/license-GPL-blue">

  <img src="https://camo.githubusercontent.com/bc442b82f9ee7ab250bdee5c6fd1f61ee3965952/68747470733a2f2f6170692e636f646163792e636f6d2f70726f6a6563742f62616467652f47726164652f6431313438336130636335633465626439646134666639663763643536363930">
</p>

## Description

<p align=justify>
  <b>CoTEC Map</b> is a suite of virus case monitoring and hospital management applications. The web application provides a view for monitoring cases worldwide, presenting a specific breakdown of each country, it also provides the hospital administration system that allows managing patients and their recent contacts.
</p>

<table>
  <tr>
    <td>
      <img src="https://res.cloudinary.com/estalvgs1999/image/upload/v1598236668/Whitetail/CoTEC/home_qaqggg.png" width="400">
    </td>
    <td>
      <img src="https://res.cloudinary.com/estalvgs1999/image/upload/v1598236676/Whitetail/CoTEC/Paciente_sxhudl.png" width="400">
    </td>
    <td>
      <img src="https://res.cloudinary.com/estalvgs1999/image/upload/v1598236673/Whitetail/CoTEC/Reports_jd9a1w.png" width="400">
    </td>
  </tr>
</table>
 
### Prerequisites 📋

_To run this program you must have the following dependencies installed_

* Nodejs
* NPM
* Angular 7
* Dotnet Core 3.1
* Entity Framework
* Android SDK +3.6

## Deployment 📤

### CotecMap - Web Application
```PowerShell
# Dev mode
> npm install
> npm fund
> ng serve -o

# Production
> ng build --prod
> ng deploy
```
### CotecDB - Database
* Create a SQL database on your local server or in some cloud service.
* Run the DDL [file](file.sql) for the creation of the database tables.
* Create a user for the backend application and a password, such as access credentials to the server and the database.

### CotecAPI - Backend
First you must enter the access credentials to the server and database in the file [appsetting.json](https://github.com/estalvgs1999/CE3101-CoTEC-API/blob/0b48dfc09e3bc52723c31e80a6dbab533abe1628/CotecAPI/appsettings.json)

```JSON5
"ConnectionStrings":
  {
    "CotecConnection": "Server=<YOUR_SERVER_IP>;Initial Catalog=COTEC_DB; User=<USERNAME>; Password=<PASSWORD>;"
  }
```
Then, open a terminate in the CotecAPI directory and run:
```PowerShell
# Dev mode
> dotnet run

# Production
> dotnet build
> dotnet publish -c Release
```

## Built With

For the development of this project we use the following resources

<table style="border:1px solid black;margin-left:auto;margin-right:auto;">
  <tr>
    <td>
      <p align=center><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/cf/Angular_full_color_logo.svg/1200px-Angular_full_color_logo.svg.png" width="100"></p>
    </td>
    <td>
      <p align=center><img src="https://www.indogic.in/images/development/asp.net-border-526x335.png" width="150"></p>
    </td>
    <td>
      <p align=center><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/82/Android_logo_2019.svg/1173px-Android_logo_2019.svg.png" width="100"></p>
    </td>
    <td>
      <p align=center><img src="https://allvectorlogo.com/img/2017/02/microsoft-sql-server-logo.png" width="220"></p>
    </td>
  </tr>
  
  <tr>
    <td>
      <p align=center><a href="https://www.angular.io"><b>Angular</b></a>
        </br>Web development Framework</p>
    </td>
    <td>
      <p align=center><a href="https://dotnet.microsoft.com/apps/aspnet"><b>ASP.NET MVC</b></a>
</br>Backend Framework</p>
    </td>
    <td>
      <p align=center>
        <a href="https://developer.android.com/studio"><b>Andriod SDK</b></a>
</br>Mobile app development</p>
    </td>
    <td>
      <p align=center> <a href="https://www.microsoft.com/es-es/sql-server/sql-server-downloads"><b>SQL Server</b></a>
        </br>Database</p>
    </td>
  </tr>
</table>

## Versioning 🗃

For the versions available, see the [releases on this repository](https://github.com/Whitetail-CR/CoTEC/releases). 

## Docs 📖

You can find much more about how to use this project in our [documentation section](https://github.com/estalvgs1999/CE3104-Fun-Skills/tree/master/docs)

## Authors

This project has an excellent development group formed by ITCR computer engineering students

* **Esteban Alvarado** - *Backend & DBA* - [@estalvgs1999](https://github.com/estalvgs1999)
* **Bertha Brenes** - *Mobile Application* - [@BerthaBrenes](https://github.com/BerthaBrenes)
* **Olman Castro** - *Frontend Development* - [@Kstro379](https://github.com/Kstro379)
* **Randall Mendez** - *Frontend Development* - [@Hack998](https://github.com/Hack998)

<p align="center"> Project developed at the <b>Technological Institute of Costa Rica</b> | 2020 🄯</p>


## License 📄

This project is licensed under the GNU License - see the [LICENSE.md](https://github.com/Whitetail-CR/CoTEC/blob/master/LICENSE) file for details

***
<p align="center">
<img src="https://res.cloudinary.com/estalvgs1999/image/upload/v1597896745/Whitetail/CoTEC/app_logo.png" width="200"/>
</p>
