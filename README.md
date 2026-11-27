# COMP 360 Project 3 AdtCheckIn

	COMP 360-01 Programming Languages Fall 2026

Project 3

Due Date: Nov 29 

Objective: In this project we apply object-oriented techniques and exception to the assigned problem.

Assignment: The Auditorium of the TEST University can hold 300 students with 10 rows and 30 columns. In this project we use 3 rows and 5 columns (15 seats). Each seat has a row and column number. A student must check in online to reserve a seat before attending the meeting. The check in system is written in Java and implements the following functions:

- A constructor sets the meeting date, time and number of seats.
- A method auditoriumFull checks if there is a seat available.
- A student reserves a seat via StudentReserveSeat.
- If a student tries to reserve a seat but all seats are reserved, a NoSeatAvailable exception will occur. The exception handler displays "No Seat Available" with the meeting date and time.
- If a student reserves a seat, the meeting date, time and seat number are displayed.
- If a student cancels the reservation, the seat becomes available.

Files:

- CheckIn.java: the auditorium class with the constructor, auditoriumFull, StudentReserveSeat, and cancelReservation
- NoAvailSeat.java: the user-defined exception class
- TestAdt.java: the test program (main) with the exception handler

How to Run:

1. 

Completed by:

- 
- Brianna Williams
