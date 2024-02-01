# CustomerManagementSystems

## Project Summary
This repository contains a CRUD application for managing customers. The backend is built with Spring Boot and MySQL, featuring JWT Bearer token-based authentication. The frontend is integrated using HTML, CSS, JavaScript, React.js, Bootstrap,Router and axios, allowing users to interact with the backend APIs.

## Technology Used
* Java
* Spring boot
* Hibernate
* MySQL
* HTML
* CSS
* JS
* React.js
* Bootstrap
* React-Router
* axios

## Dependecies
 Following Dependecies are Required to run the project

 * Springboot Dev Tools
 * Spring Web
 * Lombok
 * MySQL
 * Validation
 * Spring Security
 * Spring Data Jpa

## Table Created
* user `for authentication Purpose`
* Customer
## Table Contents
 `Customer`
 * uuId ` Unique Identification for each User `
 * first_name `First Name of the Customer`
 * last_name `Last Name of the Customer`
 * Street `Street Name`
 * address `Full Address of The customer`
 * city `City of the customer`
 * state `state of the customer`
 * email `email of the customer`
 * phone `phone number of the customer`

   `User`
 * Id `id of the user which is auto generated`
 * name `name of the user`
 * email `email of the user`
 * password `password of the user`
 * role `role of the user`

## API end pont
the following endpoints are avalible in the API
 * `Customer Controller`
 * RequestMapping("/customer")
   ```
   POST/register : Add Customer
   GET/{customerId} : get customer by Id from database
   GET/all : get all customer list from database
   DELETE/remove/{customerId} : Delete customer from database
   PUT/update/{customerId} : Update Customer By Id
   
   ```
* `user controler`
*  * RequestMapping("/user")
  ```
  POST/register : Register The User
  ```
* Authe Controller
*  RequestMapping("/auth")
  ```
POST/login : login user useing email and password after user successfully login the jwt bearer token generated
  ```
## Data Structure Used
`MySQL Database`
```
We have used persistant database to implement CRUD Operations.
```
## Author

Mantu Kumar

