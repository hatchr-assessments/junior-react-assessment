# React Customer Dashboard Assessment

## Introduction

This task is designed to evaluate your fundamental Angular development skills. You will be asked to implement a customer management dashboard and connect it to a mock customers API endpoint. You are also posed a small technical design consideration: What data structure will you use to represent the customer data? 

It is difficult to estimate how long a programming task will take for a developer to complete, but we believe it is unfair to reward candidates who are able to dedicate more time to a "take home" assessment than others. For these reasons, please limit your total working time to 90 minutes, this test is not about going the extra mile or investing as much time as you can.

## The API

This project uses json-server (https://github.com/typicode/json-server) as a mock customer data REST API 

To spin up the mock backend you need to run the following command in the terminal:

`json-server --watch db.json --port 3004`

This will start a local server on port 3004

eg GET to `http://localhost:3004/customers` fetches all customers. While DELETE to `http://localhost:3004/customers/1` deletes the customer with `"id": 1`

## Task steps

1. Create a new component called "customer-list" that will display a table of all customers.
2. Choose or create a data structure to represent the customer data. The data structure should have the fields needed to display the customer information in the table, as well as any additional fields needed to interact with the API endpoints.
3. Implement methods in the CustomerService.js to interface with the customer management API. The service should have a method to get all customers (You can use `http://localhost:3004/customers`) and delete a customer.
4. Implement the functionality to display all customers in the table using the service.
5. Add a form that allows the user to add customers to the list, and a button to delete a customer from the list

## How to Submit

1. Fork the repository
2. Clone the repository to your local machine
3. Create a branch for task 1 and make your changes 
4. Create a branch for task 2 and your changes
4. Push your changes to your fork
5. Submit a pull request to the original repository
6. You can comment your PR with next steps, blockers, and comments if you would like

Note: Please submit the pull request within the 90 minute time window

Good luck, and we look forward to reviewing your submission!
