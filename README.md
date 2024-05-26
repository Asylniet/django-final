# Hair Salon Booking Application

## Project Objective:

The goal of this project is to optimize the booking and management processes in a hair salon. It aims to provide an efficient platform for managers, barbers, and clients to interact and handle their appointments.

## Models

The project includes various models that represent different entities within the hair salon ecosystem:

- Manager: Represents a salon manager.
- Barber: Represents a barber employed at the salon.
- Client: Represents a client of the salon.
- Barbershop: Represents a physical location of the salon.
- BookingRequest: Represents a client's request to book a seat at the salon.
- ApplicationRequest: Represents a barber's request to work at the salon.

## Functionality

- Managers: Can manage barbers, clients, barbershops, and requests. They have the ability to accept or reject applications from barbers and bookings from clients.
- Barbers: Can apply to work at a barbershop and update the status of their bookings to "done" after completing their work.
- Clients: Can make appointments at barbershops.

## Permissions

Permissions are implemented to control access to different parts of the application:

- Managers have full control over all aspects of the application.
- Barbers and clients have restricted access to certain operations.
- Admin users have full permissions over the data through the Django admin interface.

## REST API

- The project provides a RESTful API using Django REST Framework to interact with the application's data. Viewsets are used to define the API endpoints for each model, and serializers are used to convert model instances to JSON representations.
