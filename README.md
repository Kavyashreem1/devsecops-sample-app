DevSecOps Sample App




📄 Project Overview

This is a minimal FastAPI application created to demonstrate DevSecOps awareness.

The project includes:

✅ CI/CD pipeline using GitHub Actions

✅ Linting with Flake8

✅ Unit testing with Pytest

✅ Static code analysis with Bandit

✅ Deployment to Render (live API)

🚀 Live API

My deployed API is running here:
👉 https://devsecops-sample-app.onrender.com

Example request:

curl https://devsecops-sample-app.onrender.com/


Example response:

{
  "status": "ok",
  "message": "Hello DevSecOps!"
}

🔎 Reflection

I learned how to integrate linting, testing, and security scans into a GitHub Actions CI/CD pipeline. The tricky part was fixing flake8 errors and Bandit setup in the workflow, but solving those helped me understand how pipelines enforce coding standards.

🤖 Use of AI Tools

I used AI tools to:

Generate initial FastAPI app boilerplate code

Get guidance on fixing linting (flake8) issues

Configure the ci.yml workflow for GitHub Actions

Draft explanations and improve README documentation

This helped me save time and focus more on learning the CI/CD and security integration part.
