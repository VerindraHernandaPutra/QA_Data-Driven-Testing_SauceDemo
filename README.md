# Automated Data-Driven Testing - SauceDemo Login

This repository contains an automation testing project developed using **Katalon Studio**. The primary objective of this project is to validate the login functionality of the [SauceDemo](https://www.saucedemo.com/) website by implementing **Data-Driven Testing (DDT)**.

## 📄 Project Overview
This project demonstrates the implementation of automated test scripts that iterate through multiple data sets to verify various user scenarios. The testing logic separates the test script (logic) from the test data (CSV file), ensuring a modular and maintainable testing structure.

**Key Features:**
* **Test Case Creation:** Automated script for the Login scenario.
* **Data-Driven Implementation:** Integration of CSV files to drive test execution.

## 🛠️ Technology Stack
* **Katalon Studio** (Automation Tool)
* **Google Chrome** (Target Browser)
* **Git & GitHub** (Version Control)

## 📂 Test Data Structure
The test execution relies on a CSV file named `login_data.csv` located in the `Data Files` directory. It covers all available user roles provided by SauceDemo:

| Username | Password | User Scenario |
| :--- | :--- | :--- |
| `standard_user` | `secret_sauce` | Standard User (Valid) |
| `locked_out_user` | `secret_sauce` | Locked Out User (Invalid state) |
| `problem_user` | `secret_sauce` | Problem User (UI Issues) |
| `performance_glitch_user` | `secret_sauce` | Performance Glitch User (High Latency) |
| `error_user` | `secret_sauce` | Error User (JavaScript/Logic Errors) |
| `visual_user` | `secret_sauce` | Visual User (Layout/Element overlaps) |

## 🚀 Getting Started

### Prerequisites
* Katalon Studio installed on your machine.
* Git installed.

### Installation & Usage

**1. Clone the Repository**
Open your terminal or Git Bash and run the following command:
```bash
git clone [INSERT YOUR REPOSITORY URL HERE]
