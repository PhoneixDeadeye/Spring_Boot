# Spring Boot Store Application

This is a simple Spring Boot application that demonstrates the use of dependency injection and service components. The application includes an `OrderService` that processes orders using a `PaymentService`.

## Features
- **OrderService**: Handles order placement.
- **PaymentService**: Processes payments for orders.
- **Spring Dependency Injection**: Demonstrates the use of `@Service` and `@Component` annotations.

## Project Structure
```
store/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com.phoneixdeadeye.store/
│   │   │       ├── StoreApplication.java
│   │   │       ├── OrderService.java
│   │   │       └── PaymentService.java
│   │   └── resources/
│   │       └── application.properties
│   └── test/
│       └── java/
│           └── com.phoneixdeadeye.store/
│               └── StoreApplicationTests.java
├── pom.xml
└── mvnw.cmd
```

## Getting Started

### Prerequisites
- Java 17 or higher
- Maven

### Running the Application
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/spring-boot-store.git
   cd spring-boot-store
   ```

2. Run the application:
   ```bash
   ./mvnw spring-boot:run
   ```

3. The application will start on `http://localhost:8080`.

### Example Output
When the application runs, it will process an order and display:
```
Processing payment of $100.0
```

## Customization
You can modify the `PaymentService` implementation to use different payment methods (e.g., PayPal, Stripe).

## License
This project is licensed under the MIT License - see the LICENSE file for details.
