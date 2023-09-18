# Elevator Simulation

## Description
This is a C# console application that simulates the movement of elevators within a large building. The goal of the application is to optimize passenger transportation efficiently. The simulation adheres to Object-Oriented Programming (OOP) principles, including SOLID principles, for modularity and maintainability.

The key features of this elevator simulation include:

1. Real-Time Elevator Status:
   - Displays the real-time status of each elevator, including its current floor, direction of movement, whether it's in motion or stationary, and the number of passengers it is carrying.

2. Interactive Elevator Control:
   - Allows users to interact with the elevators through the console application.
   - Users can call an elevator to a specific floor and indicate the number of passengers waiting on each floor.

3. Multiple Floors and Elevators Support:
   - Designed to accommodate buildings with multiple floors and multiple elevators.
   - Elevators can efficiently move between different floors.

4. Efficient Elevator Dispatching:
   - Implements an algorithm that efficiently directs the nearest available elevator to respond to an elevator request.
   - Minimizes wait times for passengers and optimizes elevator usage.

5. Passenger Limit Handling:
   - Considers the maximum passenger limit for each elevator.
   - Prevents the elevator from becoming overloaded and handles scenarios where additional elevators might be required.

6. Consideration for Different Elevator Types (Future Extension):
   - The architecture is designed to accommodate future extensions for different elevator types, such as high-speed elevators, glass elevators, and freight elevators.

7. Real-Time Operation:
   - The console application operates in real-time, providing immediate responses to user interactions and accurately reflecting elevator movements and status.

## Usage
1. Clone the repository to your local machine.
2. Open the solution in your preferred C# development environment (e.g., Visual Studio).
3. Build and run the application
4. for unit testing and uncomment all code lines in the class "ElevatorControlTests" and Install the MSTest NuGet package "MSTest.TestFramework" and "MSTest.TestAdapter" 

## Instructions
1. Upon running the application, you will see the current status of each elevator.
2. Follow the on-screen instructions to interact with the elevators:
   - Enter the target floor (1-10) where you want to call an elevator.
   - Enter the passenger count for the elevator. 
   - The nearest available elevator will be dispatched to your specified floor.
   - Elevator status and passenger movement will be displayed in real-time.

## Configuration
You can configure the elevator simulation by modifying parameters in the code, such as the number of elevators, the number of floors.

## Dependencies
The application utilizes C# and .NET Core libraries. No external dependencies are required. 
