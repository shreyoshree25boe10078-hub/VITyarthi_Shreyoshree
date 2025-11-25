# Hospital Navigation
This project is a simple, menu-driven command-line hospital navigation system that helps patients find the right department based on their symptoms and view an overview of the hospital layout.

# Overview of the Project

This application is a simulation of a hospital information desk. It maps common symptoms or diseases to the right department and floor in a hospital and provides directions for the patient. It runs completely in a terminal and uses a text-based menu to guide user interaction.

# Overview Features

- Maps patient symptoms, such as "chest pain" or "headache," to an appropriate specialty department, such as Cardiology, Neurology, or Orthopedics.
- It shows the layout of a hospital: floors, departments, rooms, and common issues that each department can treat.

Provides step-by-step instructions inclusive of elevator directions to get from the ground floor to a desired department.

# Project Structure
- HospitalNavigation class
- _init_: Defines floors, departments, rooms and common diseases or symptoms.
find_department(disease_input): The function takes in the user's input, matches it with the keywords of known diseases, and returns corresponding floor and department information.
- display_hospital_info(): Prints out a summarized list of all floors, departments, and key rooms along with example conditions.
- get_patient_directions: Main loop that displays the menu for finding a department, viewing all departments, or exiting, and processes user choices.
- _handle_disease_search(): Asks for symptoms from the user, finds the department, and prints the detailed directions along with room information.

- main: Creates an instance of HospitalNavigation and begins the interaction loop.

- if _name_ == "_main_": main(): Entry point when script runs directly.

# Requirements

- Python 3.x installed on your system.

- No external libraries are needed; the script uses only standard Python functionality.

## How to Run

1. Save the code to a file, for instance:
hospital_navigation.py

2. Open a terminal or command prompt in the directory where you saved the file.
3. Run:python hospital_navigation.py

4. Follow the on-screen menu:

- Press 1 for entering symptoms and getting directions to the right department.

- Press 2 for all hospital departments and floors.
- Press 3 to exit the program.
Usage Example
- Type 1.

- When prompted, type something like:

chest pain- The system will match this to the Cardiology department and display:

The floor, for example: “1st Floor.” 
Department name : Cardiology. - Available rooms on that floor - Common conditions treated there. - Directions to reach the floor and department from the ground floor.
## Customization You can easily modify the system to match a real hospital by: - Add or edit floors and departments in self.departments inside _init_ - Updating lists to include the room numbers and services actually available. - Extending disease lists for every department in support of disease-to-department matching. This makes the script a simple starting point for educational demos, prototypes of hospital kiosks, or beginner Python projects.

[5](https://en.wikipedia.org/wiki/Hospital-acquired_infection)
[6](https://en.wikipedia.org/wiki/Hospital)
[7](https://emedicine.medscape.com/article/967022-overview)
[8](https://www.goaid.in/hospital-department-list/)
[9](https://www.dzif.de/en/glossary/hospital-pathogens)
[10](https://fr.scribd.com/document/727758512/Departments-in-a-Hospital)
