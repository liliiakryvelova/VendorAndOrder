# Vendor and Order Tracker

#### By Liliia Kryvelova

https://github.com/liliiakryvelova/VendorAndOrder.git

#### _Pierre was so pleased with your console app for his bakery that he wants to hire you for a new project. This time, he would like you to build him an MVC application to help him track the vendors that purchase baked goods from him and the orders belonging to those vendors. For example, Pierre might supply croissants to a vendor called "Suzie's Cafe" once a week. Pierre may want to create a new Vendor to represent the cafe and add new Orders to it to help keep track of his expanding business relationships._

## Technologies Used

* _ASP.NET Core MVC_
* _Razor_

## Description

* _Create a Vendor class. This class should include properties for the vendor's name, a description of the vendor, a List of Orders belonging to the vendor, and any other properties you would like to include._

* _Create an Order class. This class should include properties for the title, the description, the price, the date, and any other properties you would like to include._

* _The homepage of the app at the root path (localhost:5000/) should be a splash page welcoming Pierre and providing him with a link to a Vendors page._

* _The vendors page should contain a link to a page presenting Pierre with a form he can fill out to create a new Vendor. After the form is submitted, the new Vendor object should be saved into a static List and Pierre should be routed back to the homepage._

* _Pierre should be able to click a Vendor's name and go to a new page that will display all of that Vendor's orders._

* _Pierre should be provided with a link to a page presenting him with a form to create a new Order for a particular Vendor. Hint: The route for this page might look something like: "/vendors/1/orders/new"._

## TDD 
_For running the tests -> go to the directory ToDoList.Test and run command: dotnet test_

_Testing for class Vendor:_
* _GetName_ReturnsName_String()_
* _GetId_ReturnsVendorId_Int()_
* _GetAll_ReturnsAllVendorObjects_VendortList()_
* _Find_ReturnsCorrectVendor_Vendor()_
* _AddOrder_AssociatesOrderWithVendor_List()_

_Testing for class Order:_
* _OrderConstructor_CreatesInstanceOfOrder_Order()_
* _SetTitle_ReturnsTitle_String()_
* _GetAll_ReturnsEmptyList_OrderList()_
* _GetAllOrders_ReturnsOrders_OrderList()_
* _GetId_FindOrderByOrderId_OrderTrue()_

## Setup/Installation Requirements

* _Clone this git on your local computer *For clonning: use button Clone -> from repository. *Copy the clone command(SSH format or HTTPS)._
* _From a terminal on your local computer, use command "cd" to find the directory where you want to clone this repository. *Type the command ($ git clone HTTPs)._
* _If you clone successfully , a new sub-directory appears on your local computer. *For working with project, install npm module inside the working folder._
* _(`npm install`): after successful install, run command (`npm run build`) for building project on your own computer after it type (`npm run start`) for star your project._ 
* _For running the tests, use command (`npm test`) on the Terminal._


## Known Bugs
* _No known bugs_

## License


Copyright (c) _7-17-2022_ _Liliia Kryvelova(s)_
