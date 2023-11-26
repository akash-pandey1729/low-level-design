# Design a Parking Lot

## Problem Description

The goal of this system is to design a parking lot that can efficiently manage the parking and retrieval of vehicles.

## Requirements Gathering

- The parking lot should be able to handle different types of vehicles, such as cars, motorcycles, and buses.
- The parking lot should be able to assign a parking spot to a vehicle when it enters the lot and free up the spot when the vehicle exits via command-line input.
- The parking lot should be able to keep track of the number of available spots and display this information via command-line output.
- The parking lot should be able to handle oversize vehicles such as buses.
- The system should be able to identify the color and registration number of each vehicle when it enters the parking lot and store this information for future reference.
- The system should be able to find the registration number of vehicles based on the color of the vehicle via command-line input.
- The system should be able to find the slot number of vehicles based on the color of the vehicle via command-line input.
- The system should be able to generate a report of all parked vehicles and their respective colors and registration numbers via command-line output.
- The system should be able to show the parking fee

## Improvements

- The system should be able to accept payment from users by integrating a payments system.

# Sample Input/Output
**Input** `park_vehicle ABC-123 Red TwoWheeler`     
**Output**  :
Parking Spot: 0

**Input** `park_vehicle DEF-456 White FourWheeler`       
**Output**  :
Parking Spot: 10

**Input** `list_all_parked_vehicles`      
**Output**  :
Registration Number: ABC-123
Assigned Spot Number: 0
Vehicle Type: TwoWheeler
Color: Red

Registration Number: DEF-456
Assigned Spot Number: 10
Vehicle Type: FourWheeler
Color: White

**Input** : `free_parking_spot 0 TwoWheeler`     
**Output**  :
Parking spot {self.spot_number} is now available!

**Input** : `list_all_parked_vehicles`     
**Output**  :
Registration Number: DEF-456
Assigned Spot Number: 10
Vehicle Type: FourWheeler
Color: White

## Running Instructions
To run the Design Parking Lot project, follow the below steps:
1. Open a terminal/command prompt.
2. Navigate to the project directory by running the following command:
```cd Design_Parking_Lot/src```
3. Run the following command to start the program:
```python3 main.py```


