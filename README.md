# BusTicketGenerator
"Implement a bus ticket generator program in C/C++ that calculates the distance between boarding station and destination, calculates the fare based on the distance and user input, and generates a ticket displaying relevant information."
PROBLEM STATEMENT:-
                                                         Question: Bus Ticket Generator

You have been assigned the task of creating a bus ticket generator program. The program should calculate the distance between the boarding station and the destination, and generate a ticket with the appropriate fare based on the distance traveled.

Your task is to implement the following functionalities in C/C++:

Prompt the user to enter the boarding station and the destination.
Calculate the distance between the boarding station and the destination using a suitable algorithm or API.
Ask the user to enter the fare per kilometer.
Calculate the total fare by multiplying the distance by the fare per kilometer.
Display the boarding station, destination, distance, and the calculated fare on the ticket.

                                      Project: Bus Ticket Generator

Description:
This project aims to develop a bus ticket generator program in C/C++ that calculates the fare based on the distance between the boarding station and destination. The program will take user input for the boarding station and destination, calculate the distance using a suitable algorithm or API, determine the fare per kilometer, and generate a ticket with the relevant details.

Inputs:

Boarding station (user input)
Destination (user input)
Algorithm:

Prompt the user to enter the boarding station and destination.
Calculate the distance between the boarding station and destination using a suitable algorithm or API.
Ask the user to enter the fare per kilometer.
Calculate the total fare by multiplying the distance by the fare per kilometer.
Steps involved:

Prompt the user to enter the boarding station and destination.
Store the user input for the boarding station and destination in appropriate variables.
Calculate the distance between the boarding station and destination using a suitable algorithm or API.
Prompt the user to enter the fare per kilometer.
Store the user input for the fare per kilometer in an appropriate variable.
Calculate the total fare by multiplying the distance by the fare per kilometer.
Generate the ticket by printing the boarding station, destination, distance, and the calculated fare.
Procedure:

Display a welcoming message to the user.
Prompt the user to enter the boarding station.
Take user input for the boarding station and store it in a variable.
Prompt the user to enter the destination.
Take user input for the destination and store it in a variable.
Calculate the distance between the boarding station and destination using a suitable algorithm or API.
Prompt the user to enter the fare per kilometer.
Take user input for the fare per kilometer and store it in a variable.
Calculate the total fare by multiplying the distance by the fare per kilometer.
Print the ticket, displaying the boarding station, destination, distance, and the calculated fare.


                                                        CODE
                                                                      
```                                                                      
#include <iostream>
using namespace std;
int main() {
  
    // Prompt for boarding station
    string boardingStation, destination;
    double distance, farePerKm, totalFare;
    cout << "Enter the boarding station: ";
    getline(cin, boardingStation);

    // Prompt for destination
    cout << "Enter the destination: ";
    getline(cin, destination);

    // Calculate distance (example calculation)
    // Replace this with your own algorithm or API
    distance = 50.5; 

    // Prompt for fare per kilometer
    cout << "Enter the fare per kilometer: ";
    cin >> farePerKm;

    // Calculate total fare
    totalFare = distance * farePerKm;

    // Print the ticket
    cout << "----- Ticket -----" << endl;
    cout << "Boarding Station: " << boardingStation << endl;
    cout << "Destination: " << destination << endl;
    cout << "Distance: " << distance << " km" << endl;
    cout << "Total Fare: " << totalFare << " $" << endl;

    return 0;
}
```js
  
                                                                          OUTPUT
  Enter the boarding station: ABC Bus Stop
Enter the destination: XYZ Bus Stop
Enter the fare per kilometer: 2.5
----- Ticket -----
Boarding Station: ABC Bus Stop
Destination: XYZ Bus
