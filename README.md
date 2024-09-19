# Airline_Ticket_Reservation_System

### Welcome to the **Airline Ticket Reservation System** developed in Java. This project allows users to book, cancel, and view tickets for flights between major cities in India. The system includes different classes, seat availability, and flight details for users to manage their travel bookings.

## Features

- **Flight Booking**: Users can book flights between four major cities (Delhi, Mumbai, Chennai, Kolkata).
- **Ticket Cancellation**: Users can cancel their reserved tickets and receive a refund.
- **View Ticket Details**: Users can view their booked ticket information and flight details.
- **Seat Availability**: The system provides real-time information on available seats in both Economy and First class.
- **Randomized Flight Schedules**: Each flight has a random traffic status, frequency, and departure time to simulate a dynamic flight system.

## Technologies Used

- **Java**: Core programming language used for logic and user interaction.
- **Java `LocalDate`**: To handle date and time for bookings.
- **Scanner**: For user input during console interactions.
- **Random**: To generate random numbers for various features like flight schedules and seat availability.

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/airline-ticket-reservation-system.git
2. Open the project in your preferred Java IDE (e.g., IntelliJ IDEA, Eclipse).

3. Compile and run the AirlineTicketReservationSystem.java file.

4. Follow the on-screen instructions to book, cancel, or view your flight details.

## Booking Flow
1. Select your departure and arrival cities from the available options.
2. Choose your travel date within the next three months.
3. View available flights and select the desired one.
4. Confirm seat availability and choose your class (Economy or First Class).
5. Make the payment to finalize your booking.
   
## Classes and Functions
1. AirlineTicketReservationSystem: The main class containing the system's core functionality.
2. Route: Class representing flight routes between cities.
3. Aircraft: Class representing details of the aircrafts used in the system.
4. Ticket: Class for handling ticket details and operations.
   
## Key Functions:
- initializeAircrafts(): Initializes aircraft data.
- initializeFlightRoutes(): Sets up the flight routes.
- seatAvailability(): Handles seat availability and booking.
- getTravelDate(): Validates and parses user input for travel date.

## Screenshots:
![image](https://github.com/user-attachments/assets/1a8388ce-8c91-47f5-b1f4-96565c727cad) ![image](https://github.com/user-attachments/assets/cdaae8ee-6b08-4a11-8fc8-285fa12ba456)
![image](https://github.com/user-attachments/assets/d042aad9-0ebb-4e0e-8c9b-cb64a8673f1e)

## Future Enhancements
1. Graphical User Interface (GUI): Plan to implement a user-friendly GUI to replace the current console-based interaction.
2. Additional Cities: Expand the system to include more cities and international routes.
3. Frequent Flyer Program: Introduce a loyalty program for regular customers.
   
## License
This project is licensed under the MIT License
