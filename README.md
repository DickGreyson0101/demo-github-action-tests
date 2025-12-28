# Demo GitHub Action Tests

This repository demonstrates how to set up GitHub Actions for **Cypress** and **Playwright** testing.

## Project Structure

- **cypress/**: Cypress E2E test suite.
- **playwright/**: Playwright E2E test suite.
- **.github/workflows/**: CI/CD configurations for automated testing.

## How to Run

### Locally

**Cypress**
```bash
cd cypress
npm ci
npx cypress open
```

**Playwright**
```bash
cd playwright
npm ci
npx playwright test
```

### GitHub Actions
Go to the **Actions** tab in this repository, select the desired workflow (`Cypress Tests` or `Playwright Tests`), and click **Run workflow**.

Artifacts (videos/reports) are generated after each run.
