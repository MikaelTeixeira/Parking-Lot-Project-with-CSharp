# Parking Lot Project with C#
![Status](https://img.shields.io/badge/status-active-brightgreen)
![Version](https://img.shields.io/badge/version-0.1-blue)
![Language](https://img.shields.io/badge/language-C%23-178600)
![License](https://img.shields.io/badge/license-none-lightgrey)

A simple and functional parking lot management system built in C#.  
It registers vehicles, assigns parking spots, calculates fees based on parking time, and displays spot availability.

---

## 📚 Index
- [Description](#description)
- [Features](#features)
- [Architeture/Design](#architeturedesign)
- [Motivation / Why This Project?](#motivation--why-this-project)
- [Installation](#installation)
  - [Requirements](#requirements)
  - [Running the project](#running-the-project)
- [Contributing](#contributing)

---

## Description

The **Parking Lot Project with C#** is a console-based management system that handles vehicle entries, exits, payment calculation, and parking spot allocation.

This was the **first full project I developed using C#**, created as a hands-on exercise to learn .NET, object-oriented programming, and general backend logic.

---

## Features
- Register new vehicles
- Display all available parking spots
- Assign a vehicle to a specific spot
- Calculate fees based on time parked
- Remove vehicles after payment
- List all vehicles currently parked
- 100% console-based interactive system

---

##  Architeture/Design
Main Components:
- Car.cs
    Stores vehicle data (name, year, assigned parking spot).

- Parking.cs
    Manages spot allocation, fee calculation, and all internal storage logic.

- CRUDS.cs
    Handles the console menu and user interactions.

Flow Overview:
Program.cs
    ↓
CRUDS (menu & user choices)
    ↓
Parking ↔ Car (business logic & data)

---

## Motivation / Why This Project?

- Practice real object-oriented programming (classes, models, responsibilities).  
- Solidify C# fundamentals through a real scenario.  
- Understand how a full console workflow works (input, output, validation).  
- Build a clean and organized structure for a simple real-world problem.

---

## Installation

### Requirements
- Windows, Linux or macOS  
- .NET SDK installed  
- No external dependencies

### Running the project
```bash
git clone https://github.com/MikaelTeixeira/ProjetoEstacionamentoComCSharp
cd ProjetoEstacionamentoComCSharp
dotnet run 
```

## Contributing
1. Fork the repository  
2. Create a new branch  
3. Implement your improvements  
4. Open a pull request
