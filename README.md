# Luma: This is a test project for Luma playwright tests

## Follow below instructions to run the playwright scipts.

# Install node:
[NodeJS](https://nodejs.org/en/download)
follow steps for mac or windows.

If you have already npm installed run the below command to update npm
```
npm update
```

# Install Playwright with npm:
```
npm init playwright@latest
```
*Choose between TypeScript or JavaScript (default is TypeScript)
*Name of your Tests folder (default is tests or e2e if you already have a tests folder in your project)
*Add a GitHub Actions workflow to easily run tests on CI
*Install Playwright browsers (default is true)

Browse to the correct root folder
use the below command to run tests
```
npx playwright test /pd/ --headed --workers=1    --retries=2
```

By default, Playwright runs Tests in multiple types of browsers. Focussed only on Chromium for this assignment.

