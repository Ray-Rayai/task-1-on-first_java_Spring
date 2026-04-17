# Project Name 
Spring Boot Greeting Application 

## Overview
This project is a simple web application that built using Spring Boot. 
it demonstration how to create HTTP endpoint and return both plain text and dynamic
HTML content using a controller.

## Features
Dynamic greeting based on user-provided name 
Simple HTTP endpoint handling
Clean and minimal UI output
Lightweight and fast execution

## How It Works
The application defines a controller class: 
HelloController

It provides two endpoints
1 Root Endpoint (/)
  .URL:http://loclhost:8080/,
  .Return a plain text rsponse
Output:
Hello Vistula, in my first Spring controller.

2. Greeting Endpoint ( /greeting)
   .URL:http://localhost:8080/greeting?name = Vistula
   .Accepts a query paramete: name
   .Passes thr value to a view (HTML template)

Example: http://localhost:8080/greeting?name=Vistula

Output:
    Hello, Viatula!
   
 ## Use of Cases
1. Access Root Endpoint 
.User opens browser
.Navigates to /
.System return a static text message

2. Personalized Greeting
 .User enters /greeting?name=Vistula
 .Application extract the name parameter
 .Adds it to the model
 .Displays a personalized greeting in the HTML view

## Screenshots
<img width="887" height="920" alt="image" src="https://github.com/user-attachments/assets/cf808742-4cb0-4f31-810f-296ff8d4188d" />

## Technologies Used 
. Java
. Spring Boot
. Spring MVC
. Maven
. Thymeleaf
. IntelliJ IDEA

## Project Structure
. HelloController.java - handle HTTP requests
. templates/greeting.html - HTML view template
. application.properties - configuration file


 
