# Parking Lot Project with C#
![Status](https://img.shields.io/badge/status-active-brightgreen)
![Version](https://img.shields.io/badge/version-0.1-blue)
![Language](https://img.shields.io/badge/language-C%23-178600)
![License](https://img.shields.io/badge/license-none-lightgrey)

A simple and functional parking lot management system built in C#.  
It registers vehicles, assigns parking spots, calculates fees based on parking time, and displays spot availability.

---

## 🌐 Language Index
- <img src="https://twemoji.maxcdn.com/2/svg/1f1fa-1f1f8.svg" width="20" /> **English Version** → (you are here)
- <img src="https://twemoji.maxcdn.com/2/svg/1f1e7-1f1f7.svg" width="20" /> **Versão em Português** → [README-ptBR.md](README-ptBR.md)

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



# Hotel System com C#
![Status](https://img.shields.io/badge/status-ativo-brightgreen)
![Version](https://img.shields.io/badge/versão-0.1-blue)
![Language](https://img.shields.io/badge/linguagem-C%23-178600)
![License](https://img.shields.io/badge/licença-nenhuma-lightgrey)

Um sistema de gerenciamento de hotel feito inteiramente em C#.  
Registra hóspedes, gerencia suítes, cria reservas, calcula custo total da estadia e organiza as operações do hotel usando uma estrutura limpa baseada em orientação a objetos.

---

## 🌐 Índice de Idiomas
- 🇺🇸 **English Version** → [README.md](README.md)
- 🇧🇷 **Versão em Português** → Você está aqui

---

## 📚 Índice
- [Descrição](#descrição)
- [Funcionalidades](#funcionalidades)
- [Arquitetura/Design](#arquiteturadesign)
- [Motivação / Por que este projeto?](#motivação--por-que-este-projeto)
- [Instalação](#instalação)
  - [Requisitos](#requisitos)
  - [Rodando o projeto](#rodando-o-projeto)
- [Contribuição](#contribuição)

---

## Descrição

O **Hotel System** é uma aplicação de console em C# projetada para simular operações essenciais de um hotel real.  
Ele gerencia o registro de hóspedes, cadastro de suítes, criação de reservas, cálculo da estadia e exibe resumos em uma interface totalmente interativa pelo terminal.

O projeto foi criado como exercício para reforçar conceitos de C#, programação orientada a objetos e lógica backend.

---

## Funcionalidades

- Registrar novos hóspedes  
- Registrar suítes do hotel  
- Criar reservas vinculando hóspedes e suítes  
- Calcular o valor total da estadia com base nos dias reservados  
- Exibir o resumo das reservas  
- Listar todos os hóspedes  
- Listar todas as suítes  
- Sistema totalmente interativo via console  
- Arquitetura limpa baseada em OOP  

---

## Arquitetura/Design

### **Guest.cs**
Armazena informações do hóspede como nome e dados de identificação.

### **Suite.cs**
Contém atributos da suíte como descrição, capacidade e valor da diária.

### **Reservation.cs**
Vincula um hóspede a uma suíte, gerencia a quantidade de dias reservados e calcula o valor total.

### **Hotel.cs**
Gerencia listas globais (suítes, hóspedes) e oferece operações de nível superior.

### **Program.cs**
Ponto de entrada da aplicação.  
Controla menus, entrada de dados e chama a lógica principal das outras classes.

---

### Fluxo Geral

Program.cs (Menu & Entrada)
↓
Hotel.cs (operações principais)
↓
Guest.cs / Suite.cs / Reservation.cs (dados & regras)


---

## Motivação / Por que este projeto?

- Praticar conceitos de orientação a objetos em um cenário real  
- Criar uma aplicação de console estruturada do zero  
- Entender modelagem lógica envolvendo hóspedes, suítes e reservas  
- Reforçar fundamentos de C# com uma arquitetura organizada  

---

## Instalação

### Requisitos
- Windows, Linux ou macOS  
- .NET SDK instalado  
- Nenhuma dependência externa  

---

### Rodando o projeto

```bash
git clone https://github.com/MikaelTeixeira/Hotel-System
cd Hotel-System
dotnet run

```

###Contribuição

Faça um fork do repositório

Crie uma nova branch

Adicione suas melhorias

Abra um pull request
---
