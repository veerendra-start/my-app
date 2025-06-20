# My Simple CI/CD Node App
# Node.js CI/CD Pipeline with GitHub Actions

## Project Overview
This project demonstrates a simple CI/CD pipeline for a Node.js application using GitHub Actions.  
The pipeline includes steps for:
- Checking out the repository
- Setting up Node.js environment
- Installing dependencies
- Running the Node.js app
- Building a Docker image

---

## Files created

- `.github/workflows/ci-cd.yml`  
  GitHub Actions workflow file that defines the CI/CD pipeline.

- `app.js`  
  A simple Node.js application entry point.

---

## How to run

1. Make sure your `app.js` contains valid Node.js code without encoding issues, for example:

   ```js
   console.log("Hello from clean CI/CD!");
