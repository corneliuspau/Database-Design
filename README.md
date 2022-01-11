# Inventory Management Database Design - Project Lightyear

### Project Background/Description

I currently own a business dealing with agricultural spare parts and I want to have my own inventory management system that works online/offline. Create a DB definition that allows me to track purchases (customer sales history and supplier purchase history), inventory and its location, and the ability to receive quotations from prospective customers that will show recent purchases (bought and sold).

### Project Scope

We need an architectural layout of the database with source code, documentation, a diagram, and a plan / writeup for a proof of concept to be used for interview purposes. The code should adhere to best practices and be scalable, the documentation should be informative and consistent while easy to read and navigate for reference, the diagram should be clear and helpful, and the writeup should explain the project in detail.

### Major Functional Requirements

Must track inventory.
Must track and sell spare parts by part name and part number.
Vendors must be tracked and associated with products.
Must accept large volumes of data and be scalable to local and national web traffic.
Must accept quotations from customer and return list of information regarding quoted spare parts (history of prices, location of part(s), suppliers/buyers, and dates)

### Entities 

Parts
Supplier
Buyers 
Location
Sales
User
Quotation

### Assumptions
User logs in to make a quotation for parts but does not make purchase(s) through the application.
Employee files invoices after receiving a quotation.
Onsite managers have to manually monitor inventory in-flow/out-flow based on their respective locations.
Inventory warehouse will have adequate storage capacity.

### Architecture

Tables must be efficient, enforce data integrity, lack redundancy, and be sensible.

