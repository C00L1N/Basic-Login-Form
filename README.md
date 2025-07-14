# 🧪 Cypress Testing Ground

This project serves as a **Cypress testing sandbox** to practice and improve your automation testing skills using a basic login form and other test cases.


## 🚀 Getting Started

### 1. Install Cypress

Make sure you're in your project folder, then run:

```
npm install cypress --save-dev
```

### Open Cypress Test Runner
After installation, lunch cypress with:
```
npx cypress open
```

### 📁 Project Structure
```bash
cypress/
  ├── e2e/              # Your test files go here
  ├── fixtures/         # Static test data (optional)
  ├── support/          # Commands and global config
cypress.config.js        # Cypress configuration
```

### 🧪What To Test
- ✅ Basic Login Form
- ✅ Form Validation
- ✅ Input Field Behaviors
- ✅ Error Messages and edge cases

### 💡Tip
You can also run tests in headless mode using:
```
npx cypress run
```

If you want to setup component testing, use this code:
```
npx cypress open --component
```
