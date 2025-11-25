# Playwright Javascript Automation

Small Playwright test project containing example tests and notes.

## What's here
- `tests/` – Playwright Test files (example.spec.js, UIBasicstest.spec.js, etc.)
- `tests-examples/` – extra example specs
- `e2e/` – additional example tests
- `notes.txt` – simple glossary and explanations for the tests
- `.github/workflows/playwright.yml` – GitHub Actions workflow (Playwright)

## Prerequisites
- Node.js (v14+ recommended)
- npm (comes with Node.js)

## Setup
1. Install dependencies:

```powershell
cd D:\Playwright_Javascript_Automation
npm install
```

2. Install Playwright browsers (only required once):

```powershell
npx playwright install
```

## Run tests
- Run all tests:

```powershell
npx playwright test
```

- Run a single file:

```powershell
npx playwright test tests\example.spec.js
```

- Run in headed mode to see the browser:

```powershell
npx playwright test --headed
```

## View report
After a run, open the Playwright HTML report:

```powershell
npx playwright show-report
```

## CI
This repository includes a GitHub Actions workflow at `.github/workflows/playwright.yml` which runs Playwright tests on push/PR.

## Notes
- See `notes.txt` for a plain-language glossary explaining the test files and Playwright concepts.

If you want this README expanded (badges, contribution guide, license), tell me what to add and I will update it and push the change.
