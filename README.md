# spring

#spring-starters-project

The project has been build following the guide in the following link: https://spring.io/guides/gs/rest-service/#scratch

This guide walks you through the process of creating a "hello world" RESTful web service with Spring.

What has been built

A service that will accept HTTP GET requests at:
http://localhost:8080/greeting
and respond with a JSON representation of a greeting:

{"id":1,"content":"Hello, World!"}
You can customize the greeting with an optional name parameter in the query string:

http://localhost:8080/greeting?name=User
The name parameter value overrides the default value of "World" and is reflected in the response:

{"id":1,"content":"Hello, User!"}

What you’ll need

About 15 minutes
A favorite text editor or IDE
JDK 1.8 or later
Gradle 2.3+ or Maven 3.0+
You can also import the code from this guide as well as view the web page directly into Spring Tool Suite (STS) and work your way through it from there.
