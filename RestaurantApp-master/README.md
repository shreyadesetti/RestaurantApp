# Project Restaurant Application SQL Application using donet mvc

GitHub_ID                    Name                               Contributions   WSUID's

saitejadesetti          Sri Shreya Desetti                      100             A594F253

Project Link to github
https://github.com/shreyadesetti/RestaurantApp

Project Youtube Video Link
https://youtu.be/TRAopvBO5DE


# Restaurant App

Welcome to our project! This is a Restaurant Web App made using C#(ASP.NET framework). It allows users to quickly and easily add, delete, and update and view the restaurants info and also able to get the data which is present in different tables.

Here we have considered 5 3NF tables classifying Restaurant Table such as Restaurant Info, Cuisine, Zipcode, Restaurant Menu,Restaurant MenuItem type.

Here above Five tables contains following attributes with primary key information as well

1. RestaurantInfo Table(ID(pk),Name,Address,Zipcode(fk),Phone,Website,Cuisine_ID(fk),Rating,PriceRange)

2. Cuisine Table(ID(pk),Name,nutritioninfo,texture)

3. ZipCode Table(Zipcode(pk),City,State)

4. RestaurantMenu Table(ID(pk),Menuitem,Description,price)

5. MenuItemType Table(ID,(pk)Type,RestaurantID(fk),Description,Price)

# Requirements

Editor - Visual Studio 2019 and above

Database - SQLServer EXpress

# Features
(CRUD)
* Read Data From Table In DB
* Insert Data To DB
* Update Data To DB
* Delete Data From DB
* Joins are used to get data from multiple tables using foreign key references.
