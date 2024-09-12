# TASK-4
Patient Information System

This repository includes a C++ program that implements a patient information management system using a priority queue. The system organizes patients by age and offers a menu-based interface for adding, removing, and displaying patient details.

Key Features

- Patient class to represent a patient with age information.
- Hospital class to handle the priority queue and offer methods for managing patient data.
- Menu-based interface for user interaction.
- Priority queue to prioritize patients by their age.

How to Use

- Clone the repository.
- Compile the program using C++.
- Run the executable.
- Use the menu options to add, remove, and view patient details.

Classes and Functions

Patient class:
  - age: an integer representing the patient's age.
  - Patient(int age): constructor to create a patient object.

Hospital class:
  - priorityQueue: a priority queue for managing patients by age.
  - addPatient(): function to add a patient to the queue.
  - deletePatient(): function to remove a patient from the queue.
  - displayPatients(): function to show all patients in the queue.
  - run(): function that provides the menu-based interface for the user.
