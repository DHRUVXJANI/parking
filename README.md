# Vehicle Parking Management System

This is a simple C-based Vehicle Parking Management System for Windows. It allows you to manage the arrival and departure of cars and scooters in a parking lot, track parking history, and generate fines for random vehicles.

## Features
- Add (park) a car or scooter
- Remove (depart) a car or scooter
- View total vehicles, cars, or scooters parked
- Display the current parking arrangement
- View arrival, departure, and fine history
- Random fine generation for some vehicles
- Data persistence using local files

## Files Used
- `arival.dat` — Stores arrival records
- `depart.dat` — Stores departure records
- `finesheet.dat` — Stores fine records
- `backupwr.dat` — Stores backup of parking state

## Requirements
- Windows OS
- GCC (MinGW-w64) or compatible C compiler

## How to Compile
1. Open **Command Prompt** or **PowerShell**.
2. Navigate to the project directory:
   ```sh
   cd C:\GLS\Projects\parking
   ```
3. Compile the program:
   ```sh
   gcc main.c -o parking.exe
   ```

## How to Run
In **PowerShell**:
```sh
./parking.exe
```
In **Command Prompt**:
```sh
parking.exe
```

## Usage
- Follow the on-screen menu to:
  - Park a vehicle (car or scooter)
  - Remove a vehicle
  - View parking status
  - Check history
  - Exit the program
- Data files will be created in the same directory as the executable.

## Notes
- The program uses `getch()` and `system("cls")` for user interaction and screen clearing.
- Make sure you have write permissions in the project directory.
- If you encounter any issues with file creation, run the terminal as administrator.

## License
This project is for educational purposes and is provided as-is. 