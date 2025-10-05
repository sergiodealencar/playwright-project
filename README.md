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
