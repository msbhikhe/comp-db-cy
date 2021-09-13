# Computer Database

Inventory for computers.

## Testcases

Testcases are available in file _ComputerDB-Testcases.xlsx_ and via [Google Sheet](https://docs.google.com/spreadsheets/d/1IYmnTgcBQcawzc4oIb8nImLyadwLdldCVgMNyQ-P9wU/edit?usp=sharing)

## Setup

> npm install

## Run tests on local machine

> npm run test

## Experiments

### Github Actions

https://github.com/msbhikhe/comp-db-cy/actions

### Mochawesome Report

A sample report is zipped in the project. Alternatively, steps to generate report on local machine:

-   Delete following files/folders
    -   cypress/reports/\*
    -   mocha\*
-   Run tests
-   Run npm script _generate-report_
-   Check HTML report in mochawesome-report folder
