# oppdoor_travell_planner

## About

The backend of online trip management where the admin can log in to the system and can manage the features of the website. And the customer can also log in and perform activities such as view routes, hotels, and packages and can also book, cancel and print ticket details and provide feedback too.


## Admin Features

- Login/Logout using Session Id
- User Management
- Route and Bus Booking Management
  - All fundamental CRUD operation.
- Hotel and Package Booking Management
  - All fundamental CRUD operation.
- View Reports 


## User Features

- Login as Customer
- create Booking
- View and Book Packages,Bus and hotels. 
- Wallet Payment
- PaymentDetails. 
- Feedback


## Tech Stack

**Client:** Java, SpringBoot, Spring Data JPA

**RDBMS:** MySQL

**Testing:** Postman


##  Entity Relationship
![Travel Management System (ER Diagram)](https://user-images.githubusercontent.com/103635204/216791371-5ca2f626-2de4-4d1e-b59f-ee21eb72a62d.jpeg)

## Run Locally

Clone the project

```bash
  git clone https://github.com/abhidas0810/oppdoor_travell_planner.git
```

Go to the project resources


-  src/main/resources and change the MySQL credentials.


Run the main file

- src/main/java/com/tj/oppdoor_travell_planner.java 

Start the server

 - http://localhost:8888/swagger-ui/#/

![Logo](https://i.postimg.cc/kM0tpJKd/p2.png)
