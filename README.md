# Adjust Case Study
The test cases in the case study was automated in this project by using Cypress.io test automation tool. 

In order to run the tests, node.js and cypress.io must be installed as prerequisites

- Please refer [Node.js](https://nodejs.org/en/download/) installation
- Please refer [Cypress.io](https://docs.cypress.io/guides/getting-started/installing-cypress) installation

## Setup

Please execute the following command in project path in order to install necessary libraries

```bash
npm install
```
### Test cases

Please see test cases for the first and the second tasks in: AdjustTestCases.xlsx file.

### Run Via Cypress Interface

Please execute following command in order to start cypress interface in the terminal;

```bash
./node_modules/.bin/cypress open    
```

or

```bash
npx cypress open
```

Afterwards you can select spec.js file that you want to run.