# Online Bookstore Management System

## Project Overview
An online bookstore needs an information system to manage customer accounts, book inventories, shopping carts, orders, and payment processing. This repository contains the complete documentation, project description report, UML class diagram report, and electronic diagram files for the assignment.

## Project Scope
* **Included:** Managing customer profiles, browsing and searching book catalogs, managing shopping cart items, placing and tracking orders, and processing secure payments.
* **Excluded:** Fully functional payment gateway integration, live shipping carrier API integrations, and frontend user interface deployment.

## Main Classes
* **Customer:** Manages user registration, login credentials, and shipping addresses.
* **Book:** Manages book details such as title, author, price, and stock quantity.
* **ShoppingCart:** Manages the collection of books selected by a customer before checkout.
* **Order:** Tracks order placement dates, status, and total amounts.
* **Payment:** Handles payment transactions, amounts, and statuses.

## Repository Structure
```
uml-class-diagram-assignment/
├── README.md
├── documentation/
│   ├── report_1_project_description.pdf
│   └── report_2_uml_class_diagram.pdf
└── diagrams/
    ├── uml_class_diagram.drawio
    └── uml_class_diagram.png
