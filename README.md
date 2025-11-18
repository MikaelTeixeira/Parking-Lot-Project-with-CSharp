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
- <img src="https://twemoji.maxcdn.com/2/svg/1f1e7-1f1f7.svg" width="20" /> [**Versão em Português**](#projeto-de-estacionamento-com-c)

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

---
# Projeto de Estacionamento com C#
![Status](https://img.shields.io/badge/status-ativo-brightgreen)
![Versão](https://img.shields.io/badge/versão-0.1-blue)
![Linguagem](https://img.shields.io/badge/linguagem-C%23-178600)
![Licença](https://img.shields.io/badge/licença-nenhuma-lightgrey)

## 🌐 Índice de Idiomas
- <img src="https://twemoji.maxcdn.com/2/svg/1f1fa-1f1f8.svg" width="20" /> [**English Version**](#parking-lot-project-with-c)
- <img src="https://twemoji.maxcdn.com/2/svg/1f1e7-1f1f7.svg" width="20" /> **Versão em Português** → (você está aqui)

Um sistema simples e funcional de gerenciamento de estacionamento desenvolvido em C#.  
Ele registra veículos, aloca vagas, calcula o valor com base no tempo estacionado e exibe a disponibilidade das vagas.

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

O **Projeto de Estacionamento com C#** é um sistema de console que gerencia entradas e saídas de veículos, cálculo de pagamento e alocação de vagas.

Este foi o **primeiro projeto completo que desenvolvi usando C#**, criado como um exercício prático para aprender .NET, programação orientada a objetos e lógica backend.

---

## Funcionalidades

- Registrar novos veículos  
- Exibir todas as vagas disponíveis  
- Alocar um veículo em uma vaga específica  
- Calcular o valor do estacionamento com base no tempo parado  
- Remover veículos após o pagamento  
- Listar todos os veículos atualmente estacionados  
- Sistema 100% interativo via console  

---

## Arquitetura/Design

Componentes principais:

- **Car.cs**  
  Armazena dados do veículo (nome, ano e vaga associada).

- **Parking.cs**  
  Gerencia alocação de vagas, cálculo do valor e toda a lógica interna de armazenamento.

- **CRUDS.cs**  
  Controla o menu do console e todas as interações com o usuário.

Fluxo geral:


