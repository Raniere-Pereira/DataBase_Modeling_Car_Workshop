# DataBase_Modeling_Car_Workshop
Second project challenge of DIO "SQL Database Specialist" course.
## Car Workshop
Entities: Client, Vehicle, Mechanic, Team, Service Order, Service, Part

## Story
Control and management system for executing work orders in a car workshop.

Customers take vehicles to the shop to be repaired or to go through periodic inspections.

Each vehicle is assigned to a team of mechanics who identify the services to be performed and fill out an WO with a delivery date.

From the WO, the price of each service is calculated, consulting a reference table.

The price of each part will also be a part of the WO.

The customer authorizes the execution of the services.

The same team evaluates and performs the services.

Mechanics have a code, name, address and specialty.

Each WO has: number, issue date, value ($), status and completion date.

An WO can be made up of several services and the same service can be in more than one WO.

An WO can have several types of parts and a part can be present in more than one WO.

## Challenge Description
Create the conceptual schema for the workshop context based on the narrative provided.

## Solution
<img width="965" height="538" alt="DataBase_Modeling_Car_Workshop" src="https://github.com/user-attachments/assets/ad19b5e4-f31d-4848-b056-214a6a56c7a0" />

## Technologies
MySQL WorkBench
