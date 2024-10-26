Rule Engine with AST

Description:

This project is a 3-tier rule engine application that evaluates user eligibility based on various attributes such as age, department, and salary using an Abstract Syntax Tree (AST).

Installation:

Frontend:
Clone the repository:
git clone https://github.com/Brijes987/RuleEngineWithAST.git
cd RuleEngineWithAST/RuleEngineAST-Frontend

Install dependencies:

npm install

Backend:
git clone https://github.com/Brijes987/RuleEngineWithAST.git
cd RuleEngineWithAST/RuleEngineAST-Backend

Install dependencies:
mvn clean install

Usage:
Frontend
Start the application:
npm run dev
Access it at http://localhost:3000.

Backend
Start the application:
mvn spring-boot:run

API Endpoints

Frontend

/create_rule: Creates a rule and returns the AST.

/combine_rules: Combines rules into one AST.

/evaluate_rule: Evaluates user data against a rule.

Technologies Used:
Frontend: React.js, JavaScript (ES6+), Abstract Syntax Tree (AST)

Backend: Java, Spring Boot, PostgreSQL, Abstract Syntax Tree (AST)







