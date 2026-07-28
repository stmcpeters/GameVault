# GameVault QA Automation Platform

## Overview

GameVault is an in-progress, full-stack quality-engineering portfolio project. It models a fictional digital-content library service so that its API, frontend workflows, and quality practices can be tested end to end. The game-themed sample data provides a clear domain; the primary focus is automated software quality assurance.

## Planned technical stack

- **Frontend:** React, Vite, JavaScript, CSS
- **Backend:** Python, Flask, REST API, SQLite
- **Testing:** pytest, Postman, Selenium WebDriver, JSON-schema validation, data-driven testing, HTML reports
- **Workflow:** Git, GitHub Issues and pull requests, GitHub Actions

## Functional scope

The application will allow a user to:

1. Retrieve a catalog of fictional digital-content titles.
2. View items saved to a personal library.
3. Add a valid item to that library.
4. Remove an item from that library.
5. Receive clear responses for invalid, duplicate, incomplete, or unauthorized requests.

## Quality-engineering goals

- Build automated regression coverage for API success paths, validation failures, authorization failures, duplicate requests, and error responses.
- Create reusable test utilities and data-driven test cases.
- Validate API response structures, HTTP status codes, and critical browser workflows.
- Configure GitHub Actions to run the API test suite on pushes and pull requests.
- Document the test strategy, quality risks, test cases, and defect-resolution process.

## Out of scope

- Real user accounts, passwords, or payment processing
- Production deployment architecture
- Mobile development or game-development features
- Sony, PlayStation, real game titles, or third-party intellectual property

> GameVault is an unofficial portfolio project that uses fictional data only. It is not affiliated with Sony, PlayStation, or any third-party company.
