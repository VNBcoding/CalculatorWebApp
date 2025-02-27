# Binary Calculator API

This is a simple REST API built with Java Spring Boot that performs basic binary arithmetic operations.

## Features
- Addition of two binary numbers
- OR operation on two binary numbers
- AND operation on two binary numbers
- Multiplication of two binary numbers
- Division of two binary numbers

## Prerequisites
- Java 17 or later
- Maven
- Spring Boot

## How to Run
1. Clone the repository:
   ```sh
   git clone https://github.com/VNBcoding/binary-calculator.git
   ```
2. Navigate into the project directory:
   ```sh
   cd binary-calculator
   ```
3. Build and run the application:
   ```sh
   mvn spring-boot:run
   ```

## Example Usage
You can test the API using a web browser or tools like `curl` or Postman:

```sh
curl "http://localhost:8080/add?a=101&b=10"
```
Response:
```json
"111"
```

## License
This project is licensed under the MIT License.

