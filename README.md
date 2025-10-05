# Playwright Practice App

This project was created to demonstrate **Playwright**, **Page Object Model (POM)**, and **End-to-End automation** skills.

## Objective

Automate functional tests of a local Angular dashboard (example: IoT Dashboard) using **Playwright**.

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

Follow these steps to install, configure, and execute the Playwright tests:

### 1. Clone the repository
```bash
git clone https://github.com/sergiodealencar/pw-practice-app.git
cd pw-practice-app
```

### 2. Install dependencies

Make sure you have Node.js (v18 or higher) installed, then run:
```bash
npm install
```

### 3. Install Playwright browsers

Playwright requires browser binaries for testing:
```bash
npx playwright install
```

### 4. Start the web application (if testing a local app)

If your app runs locally (e.g., Angular dashboard on port 4200), start it in a separate terminal:
```bash
npm start
```

### 5. Run all tests

Execute all Playwright tests:
```bash
npx playwright test
```

### 6. Run a specific test file

Run only one spec file (for example uiComponents.spec.ts):
```bash
npx playwright test tests/uiComponents.spec.ts
```

### 7. Run tests in headed mode (visible browser)

Useful for debugging:
```bash
npx playwright test --headed
```

### 8. View the HTML report

After tests finish running, open the Playwright HTML report:
```bash
npx playwright show-report
```

