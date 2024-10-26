
# Rule Engine with AST

## Overview
The Rule Engine with AST is a robust 3-tier application designed to evaluate user eligibility based on various attributes like age, department, and salary using an Abstract Syntax Tree (AST). This project provides a seamless interface for creating, combining, and evaluating rules dynamically.

## Features
- Create rules using intuitive strings (e.g., "age > 30 AND department = 'Sales'").
- Combine multiple rules into a single AST for complex evaluations.
- Evaluate user data through RESTful APIs.

## Installation

### Frontend
1. Clone the repository:
   ```bash
   git clone https://github.com/Brijes987/RuleEngineWithAST.git
   cd RuleEngineWithAST/RuleEngineAST-Frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```

### Backend
1. Navigate to the backend directory:
   ```bash
   cd RuleEngineWithAST/RuleEngineAST-Backend
   ```
2. Install dependencies:
   ```bash
   mvn clean install
   ```

## Usage

### Frontend
Start the frontend application:
```bash
npm run dev
```
Access the app at [http://localhost:3000](http://localhost:3000).

### Backend
Start the backend application:
```bash
mvn spring-boot:run
```

## API Endpoints
- **/create_rule**: Creates a rule and returns the AST.
- **/combine_rules**: Combines rules into one AST.
- **/evaluate_rule**: Evaluates user data against a rule.

## Technologies Used
- **Frontend**: React.js, JavaScript (ES6+), Abstract Syntax Tree (AST)
- **Backend**: Java, Spring Boot, PostgreSQL

## Contributing
Contributions are welcome! Please create a pull request with your changes.

## License
This project is licensed under the MIT License. 
