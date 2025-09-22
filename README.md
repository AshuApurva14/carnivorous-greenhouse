# carnivorous-greenhouse
**A microservices application called the Carnivorous Greenhouse.**


## This application consists of the following services:

- **User Service:** Manages user data and authentication for the application. Such as creating users and logging in.

- **Plant Service:** Manages the creation of new plants and updates other services when a new plant is created.

- **Simulation Service:** Generates sensor data for each plant.

- **Websocket Service:** Manages the websocket connections for the application.

- **Bug Service:** A service that when enabled, randomly causes services to fail and generate additional logs.

- **Main App:** The main application that ties all the services together.
Database: A database that stores user and plant data.