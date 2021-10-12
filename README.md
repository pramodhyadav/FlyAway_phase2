# FlyAway_phase2
FlyAway is a ticket-booking portal that lets people book flights on their website.
Flyaway Ticket Booking App in JAVA - Servlet&JSP
Table of contents
General info
Using the application
Technologies
Demo
Setup
Coming Up
General info
A small flight booking demo project in JAVA

Using the application
Home displays the application name (FlyAway) and two options - Book Flights and Admin Panel Acces


Book Flights - 
The user enters flight details (date, source, destination, travellers). A query is sent to the remote database to fetch related flights and displayed to user. The User enters other details and proceeds to book the flight. 

Admin - 
Admin dashboard is accessed with a preset username and password. Admin can see all entries in database table. Admin can change his password after Login
Technologies
Frontend - JSP, HTML, CSS, Bootstrap 
Backend - JAVA Servlets 
Database - MySQL - Hosted on a remote server at AWS RDS 
Application Server - Tomcat 8.5 with Corretto 11 running on 64bit Amazon Linux 2/4.1.6 on AWS Elasticbeanstalk 

Setup
To run in your localhost - Clone into local and run project on tomcat server. If any issue check artifact is build properly. 

To deploy on a server use FlyAway.war file.
