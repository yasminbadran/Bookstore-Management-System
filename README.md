# Bookstore Management System

A console-based bookstore management system developed using Python. The application allows users to register, log in, buy or borrow books, earn loyalty points, request delivery, and choose a payment method.

## Features

* User registration and login system
* Account data saved in an external `accounts.txt` file
* Full name, phone number, and password validation
* Buy or borrow book options
* Multiple book categories and price ranges
* Personalized book category suggestions based on user age and gender
* Random availability check for borrowed books
* Shopping total calculation
* Loyalty points for selected books
* Discount system using a valid student ID
* Delivery service to selected Egyptian governorates
* Visa or cash payment options
* Customer rating system

## Technologies Used

* Python
* `os` module for account file handling
* `random` module for book availability and discounts

## How It Works

1. The user creates an account or logs in.
2. The user selects whether to buy or borrow books.
3. The system asks for age and gender to display suitable book categories.
4. The user chooses one or more books.
5. For purchases, the system calculates prices, discounts, delivery fees, and loyalty rewards.
6. The user selects a payment method and rates the bookstore experience.

## Project Purpose

This project applies fundamental Python programming concepts, including:

* Functions
* Loops and conditional statements
* Dictionaries
* File handling
* Input validation
* Randomization
* User interaction through a console interface
