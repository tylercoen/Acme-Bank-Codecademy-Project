# Acme-Bank-Codecademy-Project

## Overview
The **Acme Bank Codecademy Project** is a simulated online banking application designed to practice and demonstrate secure coding practices against common web vulnerabilities. The primary focus of this project is to implement protections against **SQL Injection**, **Cross-Site Scripting (XSS)**, and **insecure JavaScript coding patterns** in a Node.js and Express environment.

## Key Security Objectives
- **Prevent SQL Injection Attacks** by using parameterized queries and ORM best practices.
- **Mitigate Cross-Site Scripting (XSS)** through input validation, output encoding, and Content Security Policy (CSP).
- **Secure JavaScript Code** by avoiding insecure DOM manipulation, securing client-side scripts, and implementing best practices.

## Tech Stack
- **Node.js**
- **Express.js**
- **PostgreSQL (or SQLite/MySQL as a fallback)**
- **EJS (or other template engines)**
- **Express-Validator**
- **Helmet.js for HTTP Security Headers**
- **Sequelize ORM (Optional)**
- **ESLint (Security-focused ruleset)**

## Installation & Setup
1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/Acme-Bank-Codecademy-Project.git
   cd Acme-Bank-Codecademy-Project
