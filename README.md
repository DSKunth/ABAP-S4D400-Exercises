# ABAP Programming S4D400 – Exercises

This repository contains my solutions to the exercises from the SAP Learning Journey **Acquiring Core ABAP Skills**, based on the SAP training course **S4D400 – Basic ABAP Programming**.

> **Work in progress:** This repository is updated as I progress through the S4D400 course. New classes and exercise solutions are added regularly.

## Exercises

The exercises are organized in the ABAP package `ZS4D400_3964_EXERCISES`.

The exercises cover ABAP programming, database operations, Core Data Services (CDS), and business object development. Executable programs are implemented as global ABAP classes using IF_OO_ADT_CLASSRUN, allowing them to run directly in the ADT Console.

| Exercise | Class No. | Class | Tasks |
|---|---:|---|---|
| 1 - Create an ABAP Cloud Project and Investigate ABAP Coding | – | – | Set up an ABAP Cloud project and analyze existing ABAP code to become familiar with the basic features of the ABAP development environment. |
| 2 - Create an ABAP Package | – | – | Create a new package under the superpackage `ZSTUDENTS`. |
| 3 - Create a 'Hello World' Application | 1 | `ZCL_3964_HELLO_WORLD` | Create a new ABAP class and implement the interface `IF_OO_ADT_CLASSRUN`. |
| 4 - Declare Variables and Process Data | 2 | `ZCL_3964_COMPUTE` | Create a program that performs calculations based on two numbers. |
| 5 - Implement Conditional Branching | 3 | `ZCL_3964_BRANCH` | Extend the program to support the four basic arithmetic operations and handle error situations. |
| 6 - Work with Simple Internal Tables | 4 | `ZCL_3964_ITERATE` | Use iterations and simple internal tables to calculate and display Fibonacci numbers. |
| 7 - Debug ABAP Code | 5 | `ZCL_3964_DEBUG` | Analyze ABAP code using the ABAP debugger. |
| 8 - Define a Local Class | 6 | `ZCL_3964_LOCAL_CLASS` | Define a local class within a global class. |
| 9 - Create and Manage Instances | 7 | `ZCL_3964_INSTANCES` | Create and manage class instances. |
| 10 - Define and Call Methods | 8 | `ZCL_3964_METHODS` | Define and implement methods in the local class `LCL_CONNECTION` and call them from the `main( )` method of the global class. |
| 11 - Use Private Attributes and a Constructor | 9 | `ZCL_3964_CONSTRUCTOR` | Make the static attribute read-only, declare the instance attributes as private, and use a constructor to initialize their values. |
| 12 - Read Data from a Database Table | 10 | `ZCL_3964_SELECT` | Extend the local class with attributes for the departure and destination airports, and retrieve their values from a database table using a SELECT statement. |
| 13 - Analyze and Use a CDS View Entity | 11 | `ZCL_3964_CDS` | Read data from a CDS view entity instead of directly from a database table, allowing convenient access to the airline name as well. |
| 14 - Use a Structured Data Object | 12 | `ZCL_3964_STRUCTURE` | Declare a structured attribute, populate it using a SELECT statement, and access its individual components. |
| 14 - Use a Structured Data Object | 13 | `ZCL_3964_STRUCTURE_2` | Use the alternative syntax `INTO CORRESPONDING FIELDS OF` to populate a structured data object. |
| 15 - Use a Complex Internal Table | 14 | `ZCL_3964_ITAB` | Declare a table-like attribute, populate it using a SELECT statement, and access its contents. |
| 16 - Analyze a Business Object | – | – | Analyze the business object interface `/DMO/I_AgencyTP` to understand its structure and data manipulation operations. |
| 17 - Modify Data Using EML | 15 | `ZCL_3964_EML` | Use EML to perform the standard UPDATE operation on the root entity of the business object `/DMO/R_AGENCYTP` via its released stable interface `/DMO/I_AGENCYTP`. |
| 18 - Copy a Database Table | 16 | `ZCL_3964_COPY` | Create subpackage `ZS4D400_3964_RAP` for OData UI Service development, copy the database table `/LRN/S4D400_APT` to `Z3964FLIGHT`, and use an ABAP class to populate the new database table with flight data. |
| 19 - Generate and Preview an OData UI Service | - | - | Generate the repository objects for an OData UI service and preview the service as an SAP Fiori app. |
| 20 - Validate the Flight Price | - | - | Define and implement a validation for the flight price |
| 21 - Adjust the User Interface | - | - | Explore the value help provided in the application and adjust the user interface of the generated app directly by editing the UI metadata |


## Prerequisites

To import and execute these exercises, you need:

- An SAP S/4HANA training system with ABAP development access.
- Eclipse IDE with ABAP Development Tools (ADT) installed.
- abapGit for importing the repository into your SAP system.
- The SAP S4D400 training environment and its required reference objects.

### SAP Reference Objects and Dependencies

Some exercises reference SAP-provided development objects and database tables that are not included in this repository.

In particular:

- **`/DMO/FLIGHT`** – SAP Flight Reference Scenario, including demonstration data used in database access exercises.
- **S4D400 training objects** – Certain examples may depend on objects provided as part of the SAP training environment.

These dependencies must already be available and activated in your SAP system for the relevant exercises to work.

**Note:** SAP reference objects and training packages are external dependencies. They are not part of this repository and are not maintained by me.

## How to Run

1. Import the repository into your SAP system using abapGit.
2. Open the relevant global class in Eclipse using ABAP Development Tools (ADT).
3. Activate the class using **Ctrl + F3**.
4. Execute the class using **F9**.
5. View the execution results in the ABAP Console.

Each exercise class implements `IF_OO_ADT_CLASSRUN` and uses its `main( )` method as the execution entry point.

## Tools and Technologies

- ABAP Cloud
- SAP S/4HANA
- Eclipse IDE with ABAP Development Tools (ADT)
- abapGit
- Git / GitHub

## Repository Structure

The repository follows the standard abapGit serialization format.

- `src/` – ABAP source files serialized by abapGit.
- `README.md` – Repository documentation.

**Important:** The files in `src/` are intended to be managed through abapGit. Avoid editing the serialized files directly unless you understand the abapGit serialization format.

## About This Project

These exercises are part of my ongoing ABAP development learning journey.

The focus is on understanding ABAP programming concepts through practical implementation, experimentation, and debugging.

The solutions reflect my learning progress and may evolve as I deepen my understanding of ABAP.
