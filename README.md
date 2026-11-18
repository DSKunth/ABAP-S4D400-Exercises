# ABAP Programming S4D400 – Exercises

This repository contains my solutions to the exercises from the SAP Learning Journey **Acquiring Core ABAP Skills**, based on the SAP training course **S4D400 – Basic ABAP Programming**.

> **Work in progress:** This repository is updated as I progress through the S4D400 course. New classes and exercise solutions are added regularly.

## Exercises

The exercises are organized in the ABAP package `ZS4D400_3964_EXERCISES`.

Each exercise is implemented as a global ABAP class using `IF_OO_ADT_CLASSRUN`, allowing it to be executed directly in the ADT Console.

| No. | Exercise | Class | Tasks |
|---:|---|---|---|
| – | 1 - Create an ABAP Cloud Project and Investigate ABAP Coding | – | Set up an ABAP Cloud project and analyze existing ABAP code to become familiar with the basic features of the ABAP development environment. |
| – | 2 - Create an ABAP Package | – | Create a new package under the superpackage `ZSTUDENTS`. |
| 1 | 3 - Create a 'Hello World' Application | `ZCL_3964_HELLO_WORLD` | Create a new ABAP class and implement the interface `IF_OO_ADT_CLASSRUN`. |
| 2 | 4 - Declare Variables and Process Data | `ZCL_3964_COMPUTE` | Create a program that performs calculations based on two numbers. |
| 3 | 5 - Implement Conditional Branching | `ZCL_3964_BRANCH` | Extend the program to support the four basic arithmetic operations and handle error situations. |
| 4 | 6 - Work with Simple Internal Tables | `ZCL_3964_ITERATE` | Use iterations and simple internal tables to calculate and display Fibonacci numbers. |
| 5 | 7 - Debug ABAP Code | `ZCL_3964_DEBUG` | Analyze ABAP code using the ABAP debugger. |
| 6 | 8 - Define a Local Class | `ZCL_3964_LOCAL_CLASS` | Define a local class within a global class. |
| 7 | 9 - Create and Manage Instances | `ZCL_3964_INSTANCES` | Create and manage class instances. |
| 8 | 10 - Define and Call Methods | `ZCL_3964_METHODS` | Define and implement methods in the local class `LCL_CONNECTION` and call them from the `main( )` method of the global class. |
| 9 | 11 - Use Private Attributes and a Constructor | `ZCL_3964_CONSTRUCTOR` | Make the static attribute read-only, declare the instance attributes as private, and use a constructor to initialize their values. |
| 10 | 12 - Read Data from a Database Table | `ZCL_3964_SELECT` | Extend the local class with attributes for the departure and destination airports, and retrieve their values from a database table using a SELECT statement. |
| 11 | 13 - Analyze and Use a CDS View Entity | `ZCL_3964_CDS` | Read data from a CDS view entity instead of directly from a database table, allowing convenient access to the airline name as well. |
| 12 | 14 - Use a Structured Data Object | `ZCL_3964_STRUCTURE` | Declare a structured attribute, populate it using a SELECT statement, and access its individual components. |
| 13 | 14 - Use a Structured Data Object | `ZCL_3964_STRUCTURE_2` | Use the alternative syntax `INTO CORRESPONDING FIELDS OF` to populate a structured data object. |
| 14 | 15 - Use a Complex Internal Table | `ZCL_3964_ITAB` | Declare a table-like attribute, populate it using a SELECT statement, and access its contents. |
| - | 16 - Analyze a Business Object | - | Analyze the business object interface `/DMO/I_AgencyTP` to find out about its structure and the data manipulation operations. |


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
