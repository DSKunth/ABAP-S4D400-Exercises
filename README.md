# ABAP Programming S4D400 – Exercises

This repository contains my solutions to the exercises from the SAP Learning Journey **Acquiring Core ABAP Skills**, based on the SAP training course **S4D400 – Basic ABAP Programming**.

> **Work in progress:** This repository is updated as I progress through the S4D400 course. New classes and exercise solutions are added regularly.

## Exercises

The exercises are organized in the ABAP package `ZS4D400_3964_EXERCISES`.

Each exercise is implemented as a global ABAP class using `IF_OO_ADT_CLASSRUN`, allowing it to be executed directly in the ADT Console.

| Class | Exercise | Topic |
|---|---|---|
| `ZCL_3964_HELLO_WORLD` | 3 | Hello World application |
| `ZCL_3964_COMPUTE` | 4 | Perform calculations using two numbers |
| `ZCL_3964_BRANCH` | 5 | Implement conditional branching |
| `ZCL_3964_ITERATE` | 6 | Work with simple internal tables (Fibonacci numbers) |
| `ZCL_3964_DEBUG` | 7 | Debug ABAP code |
| `ZCL_3964_LOCAL_CLASS` | 8 | Define a local class |
| `ZCL_3964_INSTANCES` | 9 | Create and manage instances |
| `ZCL_3964_METHODS` | 10 | Define, implement, and call methods in a local class |
| `ZCL_3964_CONSTRUCTOR` | 11 | Use private attributes and constructors |
| `ZCL_3964_SELECT` | 12 | Read data from a database table using ABAP SQL |
| `ZCL_3964_CDS` | 13 | Analyze and use a CDS view entity |

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
