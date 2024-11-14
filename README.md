Ride-Sharing Service
This project is a basic implementation of a ride-sharing service that connects passengers with drivers based on proximity. It utilizes data structures and algorithms to model driver availability, route optimization, and fare calculation.

Features
Driver Availability: A list of available drivers with unique IDs and their respective locations is created by default. When a customer books a ride, the closest driver is assigned to the request.
Route Optimization: The system calculates the optimal route between two nodes using graph data structures and prioritizes the shortest path.
Fare Calculation: Calculates fare based on distance between pickup and destination points.
Technologies and Algorithms
Programming Language: Java
Data Structures: Graphs, Priority Queues, and ArrayLists.
Algorithms:
Dijkstra’s algorithm for shortest path calculation.
Euclidean distance calculation for determining the closest driver.
Project Structure
Driver class: Represents each driver’s ID, current location, and expected arrival time.
Graph class: Represents locations as nodes and routes as weighted edges.
Main functionalities:
bookClosestDriver: Finds and assigns the closest available driver to the customer based on location.
calculateFare: Calculates fare based on distance traveled.
Future Enhancements
Dynamic pricing based on demand.
Real-time driver tracking and ETA.
Route optimization for multiple stops.
