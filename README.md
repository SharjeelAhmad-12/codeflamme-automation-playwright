# CodeFlamme Automation Tests

Simple Playwright tests for [CodeFlamme](https://codeflamme.com/) website using Page Object Model.

## Project Structure

```
codeflamme-automation/
├── pages/
│   ├── BasePage.ts          # Base page functionality
│   └── CodeFlammePage.ts    # CodeFlamme specific page object
├── tests/
│   └── codeflamme.spec.ts   # Main test
├── resume.pdf               # Dummy resume file for testing
├── playwright.config.ts      # Playwright configuration
└── package.json             # Dependencies
```

## Test Steps

1. Launch website
2. Toggle theme mode (checkbox)
3. Navigate to Portfolio page
4. Smooth scroll to bottom
5. Navigate to Careers page
6. Fill job application form with test data
7. Submit job application

## Job Application Form Data

- **Job Title**: Jr Web Developer
- **Full Name**: Sharjeel Ahmad
- **Email**: sharjeel@example.com
- **Phone**: 03001234567
- **Location**: Lahore
- **GitHub**: https://github.com/sharjeel
- **LinkedIn**: https://linkedin.com/in/sharjeel
- **Resume**: resume.pdf (dummy file)
- **Cover Letter**: "I am excited to apply for this role and contribute my skills to Codeflamme."

## Run Tests

```bash
# Install dependencies
npm install

# Run tests
npm test

# Run with visible browser
npm run test:headed
```

## Requirements

- Node.js
- npm
