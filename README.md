# Playwright E2E Automation Project – Angular IoT Dashboard

This project demonstrates the implementation of end-to-end (E2E) automated testing using Playwright and TypeScript for a responsive Angular IoT Dashboard web application.
The automation suite validates key user interactions, including navigation, form submissions, and UI component verification, ensuring application reliability across multiple browsers.

The framework follows the Page Object Model (POM) design pattern to promote scalability, readability, and reusability. It includes a complete configuration for running tests, generating HTML reports, and capturing screenshots and videos on failures, reflecting modern best practices in web test automation.

## Objective

The project serves as a demonstration of a professional-grade E2E automation framework using Playwright, showcasing best practices in test architecture, configuration, and maintainability for modern web applications.

---

## Repository Structure

```
pw-practice-app/
│
├── .vscode/
│
├── page-objects/
│   ├── formLayoutsPage.ts
│   ├── navigationPage.ts
│   ├── pageManager.ts
│
├── src/
│
├── tests/
│   ├── uiComponents.spec.ts
│   ├── usePageObjects.spec.ts
│
├── .browserslistrc
├── .editorconfig
├── .gitignore
├── .prettierignore
├── .stylelintrc.json
├── LICENSE
├── README.md
├── angular.json
├── package-lock.json
├── package.json
├── playwright.config.ts
├── tsconfig.json
└── tslint.json
```


## How to Run

## 🚀 How to Run

### 🔧 Pre-requisites
Make sure you have the following installed on your computer:
- **[Node.js](https://nodejs.org)**
- **[Visual Studio Code (VS Code)](https://code.visualstudio.com)**
- **[Git](https://git-scm.com)** and a **GitHub account**

---

### 🪜 Steps

#### 1. Clone the test application from GitHub
Open the repository below:  
👉 [https://github.com/sergiodealencar/pw-practice-app.git](https://github.com/sergiodealencar/pw-practice-app.git)

Click on **“Code” → “Copy URL to code”**

---

#### 2. Clone the repository using Git
Open your terminal in a folder of your choice and type:
```bash
git clone https://github.com/sergiodealencar/pw-practice-app.git
```

#### 3. Open the project in VS Code and install dependencies

Open the pw-practice-app folder in VS Code, then open the integrated terminal and run:
```bash
npm install --force
npm install -D @playwright/test --force
npm start
```

Once the app starts, check in your browser that it’s running properly at:
👉 http://localhost:4200

#### 4. Run Playwright tests

To execute all tests in headless mode:
```bash
npx playwright test
```

#### 5. Run tests in the graphical UI mode

To use Playwright’s graphical test runner (visual mode):
```bash
npx playwright test --ui
```


