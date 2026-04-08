# DevOps Learning Project 🚀

A simple Node.js project focused on learning and implementing CI/CD workflows using GitHub Actions.

## 📋 Table of Contents
- [About](#about)
- [Getting Started](#getting-started)
- [CI/CD Pipeline](#cicd-pipeline)
- [Scripts](#scripts)

## 📖 About
This project serves as a practical playground for mastering Continuous Integration and Continuous Deployment (CI/CD). It features a basic Node.js application with automated testing and workflow automation.

## 🚀 Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v20 or higher recommended)
- [npm](https://www.npmjs.com/)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Dhavalkurkutiya/devops.git
   ```
2. Navigate to the project directory:
   ```bash
   cd devops
   ```
3. Install dependencies:
   ```bash
   npm install
   ```

## ⚙️ CI/CD Pipeline
The project includes a GitHub Actions workflow located in `.github/workflows/pipeline.yaml`. 

### Workflow Highlights:
- **Trigger**: Runs automatically on every `push` to the `main` branch.
- **Environment**: Executes on `ubuntu-latest`.
- **Node Setup**: Uses Node.js v20.
- **Tasks**:
  1. Checks out the code.
  2. Installs dependencies (`npm install`).
  3. Runs automated tests (`npm test`).

## 📜 Scripts
Available commands in the project:
- `npm start` (alias for `node index.js`) - Run the application.
- `npm test` - Execute the project tests.
