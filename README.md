# Hospital Navigation
This project is a simple, menu‑driven, command‑line “hospital navigation system” that helps patients find the right department based on their symptoms and view an overview of the hospital layout.[4]

## Project Overview

This application simulates a hospital information desk that maps common symptoms or diseases to appropriate hospital departments and floors, and then prints clear directions for the patient. It runs entirely in the terminal and uses a text menu to guide user interaction.[4]

## Features

- Maps patient symptoms (like “chest pain” or “headache”) to a suitable specialty department (Cardiology, Neurology, Orthopedics, etc.).[4]
- Displays hospital layout with floors, departments, rooms, and common issues treated in each department.  
- Provides step‑by‑step directions (including elevator instructions) to reach the chosen department from the ground floor.

## Project Structure

- `HospitalNavigation` class  
  - `__init__`: Defines floors, departments, rooms, and common diseases/symptoms.  
  - `find_department(disease_input)`: Matches user input against known disease keywords and returns the appropriate floor and department data.  
  - `display_hospital_info()`: Prints a summarized list of all floors, departments, and key rooms, along with example conditions.  
  - `get_patient_directions()`: Main loop presenting the menu (find department, view all departments, exit) and handling user choices.  
  - `_handle_disease_search()`: Prompts the user for symptoms, finds the department, and prints detailed directions and room information.  
- `main()`: Creates a `HospitalNavigation` instance and starts the interaction loop.  
- `if __name__ == "__main__": main()`: Entry point when the script is run directly.

## Requirements

- Python 3.x installed on your system.  
- No external libraries are required; the script uses only standard Python functionality.

## How to Run

1. Save the code to a file, for example:

   ```bash
   hospital_navigation.py
   ```

2. Open a terminal/command prompt in the directory containing the file.

3. Run:

   ```bash
   python hospital_navigation.py
   ```

4. Follow the on‑screen menu:

   - Press `1` to enter symptoms and get directions to the right department.  
   - Press `2` to view all hospital departments and floors.  
   - Press `3` to exit the program.

## Usage Example

- Choose option `1`.  
- When prompted, type something like:

  ```text
  chest pain
  ```

- The system will match this to the Cardiology department and show:

  - The floor (e.g., “1st Floor”).  
  - Department name (Cardiology).  
  - Available rooms on that floor.  
  - Common conditions treated there.  
  - Directions to reach the floor and department from the ground floor.[4]

## Customization

You can easily adapt the system to match a real hospital by:

- Adding or editing floors and departments in `self.departments` inside `__init__`.  
- Updating `rooms` lists to reflect actual room numbers and services.  
- Extending `diseases` lists for each department to improve disease‑to‑department matching.[4]

This makes the script a simple starting point for educational demos, prototypes of hospital kiosks, or beginner Python projects.

[1](https://www.ncbi.nlm.nih.gov/books/NBK559312/)
[2](https://www.scribd.com/document/795222806/C-Hospital-design-project)
[3](https://inivos.com/5-most-common-hospital-acquired-infections-hais/)
[4](https://hospi.info/departments-of-hospital/)
[5](https://en.wikipedia.org/wiki/Hospital-acquired_infection)
[6](https://en.wikipedia.org/wiki/Hospital)
[7](https://emedicine.medscape.com/article/967022-overview)
[8](https://www.goaid.in/hospital-department-list/)
[9](https://www.dzif.de/en/glossary/hospital-pathogens)
[10](https://fr.scribd.com/document/727758512/Departments-in-a-Hospital)
