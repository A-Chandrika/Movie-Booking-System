PROJECT TITLE:
Movie Ticket Booking System

DESCRIPTION OF PROJECT:
The project has five main tables:

Users:
Stores user details like username, password, and role (admin or customer).

Movies:
Contains movie_id, title, genre, and release_date.

Theaters:
Includes theater_id, name, and location.

Shows:
Stores show_id, movie_id, theater_id, showtime, and available_seats.

Bookings:
Includes booking_id, user_id, show_id, seats_booked, and booking_date.

The functionalities include user login and registration, viewing available movies and shows, booking tickets, and administrative management like adding movies, theaters, and shows.

INSTALLATION AND RUNNING:
Dependencies:

Streamlit: For the user interface.
Steps:

Create a database movie_booking in MySQL.
Run db.sql to initialize the database schema.

Run the application:
-- streamlit run app.py

FUNCTIONALITIES OF THE PROJECT:
Customer Functionalities:
View Shows: Customers can view available movies and their showtimes.
Book Tickets: Select a show and book available seats.
If available seats are insufficient, a warning is displayed.
Booking records are stored in the database.
Admin Functionalities:
Add Movies: Input movie title, genre, and release date.
Add Theaters: Input theater name and location.
Add Shows: Assign a movie to a theater with details like showtime and available seats.
Delete Entries: Admin can delete movies or shows.

PROJECT FLOW:
Login and Registration: Users can register and log in. Admins manage movie data; customers book tickets.
Admin Panel: Admins add/edit/delete movies, theaters, and shows.
Booking System: Customers select shows and book seats.
