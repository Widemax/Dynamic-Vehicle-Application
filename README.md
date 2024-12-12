# Dynamic Database

A command-line application for managing a company's employee database, built with TypeScript, PostgreSQL, and Inquirer.

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Walkthrough Video](#walkthrough-video)

## Description

This application allows users to manage departments, roles, and employees in a company database. It provides functionality to view, add, and update departments, roles, and employees, all through an intuitive command-line interface.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Widemax/Employee-Tracker.git
2. Install Dependencies:
   ```bash
   npm install
3. Set up the database:
   Ensure PostgreSQL is installed and running.
   Run the schema.sql file to create the database:
   ```bash
   psql -U postgres -f src/db/schema.sql
   sql -U postgres -f src/db/seeds.sql

## Usage

1. Compile the typescript
   ```bash
   npx tsc
2. Run the application:
   ```bash
   node/dist/index.js
   
3. Follow the prompts to
      View all departments, roles, or employees.
      Add a department, role, or employee.
      Update an employee's role.
## Walkthrough Video

[Click here to watch the walkthrough video]
