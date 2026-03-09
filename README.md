# Best Bike Paths — Software Architecture & Requirements

This repository contains the **Requirements Analysis and Specification Document (RASD)** and the **Design Document (DD)** for the *Best Bike Paths (BBP)* system, developed as part of the **Software Engineering II** course at Politecnico di Milano.

BBP is a platform designed to help cyclists **discover, record, and share bike routes**, combining community-generated data with automated analysis to provide reliable information about cycling paths. :contentReference[oaicite:0]{index=0}

---

## System Overview

The **Best Bike Paths** platform allows users to:

- Discover bike routes between an origin and a destination  
- Record trips automatically using **GPS and device sensors**  
- Manually insert and publish new cycling routes  
- Share information about **route quality, obstacles, and safety**  
- Access route statistics such as **distance, duration, and average speed**  

The system aggregates community contributions and external data (such as weather information) to provide accurate and up-to-date cycling route recommendations. :contentReference[oaicite:1]{index=1}

---

## Repository Contents

### Requirements Analysis and Specification Document (RASD)

The **RASD** describes the problem domain and the system requirements, including:

- Goals and system objectives  
- Functional and non-functional requirements  
- Use cases and interaction scenarios  
- Domain models and state diagrams  
- Formal analysis using Alloy  

It defines **what the system must do** and the constraints it must satisfy.

---

### Design Document (DD)

The **Design Document** provides the architectural and technical design of the system.

Key aspects include:

- System architecture and component structure  
- Interface specifications and API design  
- Deployment and runtime views  
- Integration and testing plan  

The system adopts a **4-tier architecture** consisting of:

- **Presentation Tier** – web and mobile clients  
- **Application Tier** – web layer and backend services  
- **Data Tier** – persistent storage and databases  
- **External Services** – maps, weather APIs, and identity providers  

This architecture promotes **modularity, scalability, and separation of concerns**. :contentReference[oaicite:2]{index=2}

---

## Purpose of the Project

The goal of this project is to design a **complete software system starting from requirements analysis to architectural design**, applying software engineering practices such as:

- requirements modeling  
- system architecture design  
- UML diagrams and formal specification  
- traceability between requirements and implementation decisions

---

## Authors

- Giacomo Rigo  
- Wojciech Maciej Bukala  
- Mattia Zonzin  

Politecnico di Milano — Software Engineering II
