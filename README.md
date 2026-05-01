# AI Test Case Generator

A simple AI-inspired QA utility that converts acceptance criteria into structured test scenarios.

## Goal
To help QA engineers quickly draft positive, negative, and edge test cases from story requirements.

## Tech Stack
- Java
- Maven
- Simple rule-based logic
- Future scope: Gemini/OpenAI API integration

## Sample Input
User should be able to create an account only when mandatory fields are completed.

## Sample Output
- Positive: Create account with all mandatory fields
- Negative: Submit form without mandatory fields
- Edge: Enter maximum allowed characters in text fields

## How to Run
```bash
mvn clean test
