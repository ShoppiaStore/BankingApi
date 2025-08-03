# BankingApp

A simple banking application built with Spring Boot that allows user authentication, account balance viewing, transaction history, deposit and withdrawal operations, and token validation.

## Overview
This project provides REST APIs for:
- User registration and login (JWT-based authentication)
- Viewing the current account balance
- Viewing account transactions
- Getting the account card number
- Depositing and withdrawing money
- Validating authentication tokens

## Prerequisites
- Java 17+ (or as configured)
- Maven or Gradle
- Database (PostgreSQL / MySQL) configured in application settings
- Lombok enabled in your IDE
- Tools like curl or Postman for API testing

## Setup
1. Clone the repository:
   ```bash
   git clone <repo-url>
   cd BankingApp
