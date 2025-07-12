# Online Food Ordering System ER Diagram Summary

This document provides a summary of the Entity Relationship Diagram (ERD) for an Online Food Ordering System, as detailed by iNetTutor.com. This ERD serves as a foundational step for database creation, outlining the entities, their relationships, and attributes within a web and mobile-based e-commerce platform for food ordering..

![Food Delivery System](fms.gif)

## Key Components of the ERD:

* The ERD identifies nine core entities crucial to the Online Food Ordering System:
*User: Represents system users.
* Site Information: Stores details related to the overall system or site.
* Payment: Manages payment transactions
* Order: Records customer orders.
* Order Details: Contains specifics for each item within an order.
* Customer: Stores customer profiles.
* Rating: Handles customer feedback and ratings for menus/orders.
* Menu: Contains information about food items available for order.
* Menu Type: Categorizes different types of menus.

## Attributes:

* Each entity has specific attributes, with primary keys underlined and foreign keys linking related entities to maintain data integrity. The detailed attributes for each entity are:
* User: Includes user ID (primary key) and other relevant user details.
* Site: Information: Contains site info ID (primary key) and other site-specific data.
* Payment: Payment ID (primary key) and transaction details.
* Order: Order ID (primary key), customer ID (foreign key), and order specifics.
* Order Details: Order details ID (primary key), order ID (foreign key), menu ID (foreign key), and item-specific information.
* Customer: Customer ID (primary key) and customer profile details.
* Rating: Rating ID (primary key), customer ID (foreign key), menu ID (foreign key), and rating information.
* Menu: Menu ID (primary key), menu type ID (foreign key), and details about the food item.

## Conclusion
* This ERD serves as a blueprint for developing the database schema for the online food ordering system.

