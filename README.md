# Flight Booking System

This Flight Booking System is a C++ program that allows users to make domestic and international flight bookings. It provides separate classes for domestic booking (`d_booking`) and international booking (`i_booking`), with functionalities for entering journey details, selecting flights, and generating unique PNRs.

## Classes

### `d_booking`

The `d_booking` class handles domestic flight bookings. It contains the following member functions:

- `enter_details()`: Allows the user to enter journey details such as departure city, arrival city, and travel date.
- `select_flight()`: Presents a list of available domestic flights for the given journey and allows the user to select a flight.
- `generate_pnr()`: Generates a unique Passenger Name Record (PNR) for the booking.

### `i_booking`

The `i_booking` class handles international flight bookings. It shares similar member functions as the `d_booking` class but is specific to international flights.

## Usage

To use this Flight Booking System:

1. Compile the source code using a C++ compiler.
2. Run the compiled executable.
3. Choose between domestic and international booking options.
4. Follow the prompts to enter journey details, select flights, and generate a PNR.

