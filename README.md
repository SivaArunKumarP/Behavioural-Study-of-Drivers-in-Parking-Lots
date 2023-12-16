# Behavioural Study of Drivers in Parking Lots

## Centre for Infrastructure, Sustainable Transportation, and Urban Planning
### Siva Arun Kumar P

## Aim
The aim of this project is to develop a system that can auto-steer a vehicle from a starting point to a parking lot, park the vehicle using existing waypoints, and auto-steer the vehicle back to the road.

## Background
In our day-to-day lives, parking lots play a crucial role in traffic management for efficiency and time management. The behavior of drivers in parking lots poses a challenge. Efficient use of parking lots not only manages time but also contributes to the smooth flow of overall traffic. Understanding driver patterns is essential for effective parking lot management.

## Methodology
We employ the semaphore concept to park the car in a parking lot, utilizing a wait and signal function. The signal function indicates whether parking is available, and if not, the car enters a wait state within the parking lot. Hashing is implemented for faster retrieval of data, especially in scenarios with multiple parking lots and cars. Threading and parallel processing are utilized to minimize time loss while signaling the car to enter or wait.

## Challenges
As a newcomer to the simulator, understanding its basics took considerable time. Facing errors at the outset, including issues during the simulator's initialization, posed initial challenges. Limited knowledge of how built-in functions operate on simulations added complexity. Understanding various functions required more time than anticipated.

## Conclusion
The project aims to enable the auto-steering of a vehicle from a designated point to a parking lot, facilitate parking using predetermined waypoints, and subsequently auto-steer the vehicle back to the road after a 5-minute interval.
