Binary Calculator API

This is a simple REST API built with Java Spring Boot that performs basic binary arithmetic operations.

Features

Addition of two binary numbers

OR operation on two binary numbers

AND operation on two binary numbers

Multiplication of two binary numbers

Division of two binary numbers

Prerequisites

Java 17 or later

Maven

Spring Boot

How to Run

Clone the repository:

git clone https://github.com/yourusername/binary-calculator.git

Navigate into the project directory:

cd binary-calculator

Build and run the application:

mvn spring-boot:run

Example Usage

You can test the API using a web browser or tools like curl or Postman:

curl "http://localhost:8080/api/binary/add?a=101&b=10"

Response:

"111"

