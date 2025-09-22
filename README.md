# Store Application

A simple Java Spring Boot application demonstrating dependency injection and payment processing.

## Features

- Order placement with payment processing
- Supports multiple payment services (Stripe, PayPal)
- Simple web controller with a static home page

## Technologies

- Java
- Spring Boot
- Maven

## Project Structure

- `OrderService` - Handles order placement and payment processing
- `PaymentService` - Interface for payment services
- `StripePaymentService` and `PayPalPayementService` - Implementations of `PaymentService`
- `HomeController` - Serves the home page
- `src/main/resources/static/index.html` - Static home page

## Running the Application

1. Build the project:
    ```sh
    mvn clean install
    ```
2. Run the application:
    ```sh
    mvn spring-boot:run
    ```
3. Visit [http://localhost:8080](http://localhost:8080) in your browser.

## License

MIT
