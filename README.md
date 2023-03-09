# Java-Car-Reservation
Using Java, I have created a simple car reservation program

The code is an implementation of a Car Reservation program in Java that allows users to view the available cars for rental, reserve a car, and view the list of reservations.

The CarReservation class has a Map object to store the inventory of cars and their availability status. The keys of the map represent the types of cars, and the values are Boolean objects indicating whether a car of that type is available for rental. It also has a List object to store the reservations made by customers.

The showAvailableCars method iterates through the Map object and displays the types of cars that are available for rental.

The reserveCar method prompts the user to enter their name and the type of car they want to reserve. It checks if the entered car type is valid and if a car of that type is available for rental. If the car is available, it marks it as unavailable in the Map object and adds a new Reservation object to the List object.

The showReservations method iterates through the List object and displays the name of the person who made the reservation and the type of car they reserved.

The main method runs an infinite loop that displays a menu of options to the user and prompts them to enter a choice. Depending on the choice, it calls the appropriate method of the CarReservation object.

The Reservation class is a nested class that represents a car reservation. It has a name field to store the name of the person who made the reservation and a carType field to store the type of car they reserved. It has getter methods for both fields.
