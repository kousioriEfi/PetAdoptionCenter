# 🐾 Pet Adoption Platform

A web platform for adopting pets from animal shelters, built with **Java** and **Spring Boot**.
Developed as a team project for the course *Distributed Systems* at Harokopio University of Athens.

## ✨ Features
- **Role-based access** with separate dashboards for each user type:
  - 🛡️ **Admin**: approves shelter profiles and pet listings, manages user accounts
  - 🏠 **Shelter**: lists pets for adoption and reviews adoption requests
  - 🩺 **Vet**: checks and confirms pets' health status, manages vet visits
  - 🙋 **Adopter**: browses pets, applies for adoption and schedules visits
- User registration and login
- Pet listings that require admin approval before going public

## 🛠️ Tech Stack
- **Java** & **Spring Boot**
- **Spring Security** for authentication and roles
- **Spring Data JPA** for database access
- **Thymeleaf** templates for the web pages
- **Bootstrap**, **CSS** & **jQuery** for the UI
- **Maven**

## 🏗️ Architecture
Layered MVC structure:
- `controller`: handles web requests
- `service`: business logic
- `repository`: database access (JPA)
- `model`: entities (User, Pet, Shelter, Vet, AdoptionRequest, VetVisit…)
- `config`: security and app configuration

## 🚀 How to Run
1. Clone the repository
2. Go to the project folder: `adOPTION/PetAdoption`
3. Set your database settings in `src/main/resources/application.properties`
4. Run with Maven:
