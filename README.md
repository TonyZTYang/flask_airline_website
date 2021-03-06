# Air Ticket Reservation System 
A python database system for a hypothetic airline company as the class project for CSCI-SHU 213 Databases.

HTML <-> Flask <-> Mysql


## Installation
1. Download the whole project.
2. Install requirements using the following code with terminal in the project folder.
```
$ pip3 install -r requirement.txt -U
```
3. Install mysql, create a database with name 'airline' and run sql files under 'sql' folder for table creation and data insertion.
4. Go to config_public.py, change the secret key and databse settings.
5. Run app.py
6. In browser open http://localhost:5000 to use the app.

## Use Cases
### General
- [x] View Public Info
- [x] Register
  - [x] Customer
  - [x] Booking Agent
  - [x] Airline Staff

- [x] Login
  - [x] Customer
  - [x] Booking Agent
  - [x] Airline Staff
### Customer
- [x] View my flight
- [x] Search for flight
- [x] Purchase Tickets
- [x] Giver ratings and comments on previous flight
- [x] Track my spending
- [x] Logout
### Booking Agent
- [x] View my flights
- [x] Search for flights
- [x] Purchase tickets
- [x] View my commission
- [x] View top customers
- [x] Logout
### Airline Staff
- [x] View flights
- [x] Create new flights
- [x] Change status of flights
- [x] Add airplane in the system
- [x] Add new airport in the system
- [x] View flight ratings
- [x] Add/delete phone number
- [x] View all the booking agents
- [x] View frequent customers
- [x] View reports
- [x] Comparison of revenue earned
- [x] View top destination
- [x] Logout
### Enforcing complex constraints
- [x] Prevention of http attacks
- [x] Sessions for each user and authentications each step after login
- [x] Prepared statements
- [x] Prevent cross-site scripting

## Documentation
For full documentation (ER diagram, relational diagram and all use cases), look under [documentation folder](/documentation).
