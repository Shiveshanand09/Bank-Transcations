# Bank Transcation– Fullstack Banking Application (Docs)

This document provides detailed notes and references for building the **iobank** backend.

---

## 📂 Development Overview

### Introduction to the Application
- Bootstrapping project with Spring Initializr  
- Installing Tabnine & JpaBuddy  
- Prompting AI agent for code generation  

### Entities, Repositories & JPA
- Defining User, Card, Transaction, and Account entities  
- Creating UserRepository, AccountRepository, TransactionRepository, and CardRepository  
- Using JpaBuddy to generate query methods  

### Spring Security & JWT
- Setting up AppConfig & SecurityConfig  
- Adding JWT dependency and creating JwtService  
- Implementing Authentication Filter  
- Configuring Security for the application  
- Building User Controller and Authentication Service  
- Using DTOs for clean data transfer  
- Testing authentication with Postman  

### Bank Account Logic
- Account creation logic with AccountService & AccountController  
- Implementing funds transfer between accounts  
- Integrating external Currency API for conversion  
- Testing account-related endpoints  

### Bank Card Logic
- Card operations (Create, Debit, Credit) with CardService & CardController  
- Testing endpoints with Testfully  
- Applying transaction rollbacks using `@Transactional`  

### Bank Transaction Logic
- Retrieving transactions for users, accounts, and cards  
- Testing transaction endpoints with Testfully  
- Adding Javadoc comments with Tabnine  

---

## 🚀 Features Implemented

- Secure JWT-based authentication  
- Multi-currency account creation  
- Funds transfer between accounts  
- Currency conversion with external API  
- Card creation, debit & credit  
- Transaction retrieval by user/account/card  
- Transaction rollbacks (`@Transactional`)  

---

## 🛠️ Tools Used

- Spring Boot  
- PostgreSQL  
- Spring Security & JWT  
- React.js + Tailwind CSS (Part 2 – frontend)  
- Tabnine  
- JpaBuddy  
- Postman  
- Testfully  
- IntelliJ IDEA  

---

## ⭐ Support

If you enjoy this project:  
- Give the repo a **star** ⭐  
- Share feedback or contribute to improvements
