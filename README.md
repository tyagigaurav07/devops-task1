# 🚀 DevOps Task 1 – Node.js CI/CD Project

[![Node.js CI](https://github.com/tyagigaurav07/devops-task1/actions/workflows/nodejs.yml/badge.svg)](https://github.com/tyagigaurav07/devops-task1/actions)

This is a simple **Node.js app** integrated with a **GitHub Actions CI/CD pipeline**. The workflow automatically installs dependencies and runs tests on every push to the `main` branch.

---

## 🧰 Tech Stack

- Node.js  
- Express.js  
- Git & GitHub  
- GitHub Actions (CI/CD)

---

## 📂 Folder Structure

```
devops-task1/
│
├── .github/workflows/     # CI workflow file
├── bin/                   # App entry point
├── public/                # Static files
├── routes/                # Express routes
├── views/                 # EJS views/templates
├── app.js                 # Main application
├── package.json           # Project config
└── README.md              # Project info
```

---

## ⚙️ GitHub Actions – CI Pipeline

- ✅ **Triggers on:** Every push to `main`
- 🔧 **Runs:**  
  - `npm install`  
  - `npm test` (if tests are defined)

The badge above reflects the latest pipeline status:  
🟢 Passed | 🔴 Failed | 🟡 Running

---

## 🚀 Running the App Locally

```bash
git clone https://github.com/tyagigaurav07/devops-task1.git
cd devops-task1
npm install
npm start
```

Visit: **http://localhost:3000**

---

## 🙋‍♂️ Author

**Gaurav Tyagi**  
[GitHub](https://github.com/tyagigaurav07)

---
