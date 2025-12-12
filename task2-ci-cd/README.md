# Task 2 – CI/CD Pipeline (GitHub Actions)

For this task, I created a GitHub Actions workflow that runs automatically when I push changes to the task2-ci-cd folder. This workflow installs dependencies, checks syntax, and builds a Docker image from the app.

## What the pipeline does:
- Checks out the repository
- Sets up Python 3.10
- Installs dependencies from requirements.txt
- Performs syntax check on app.py
- Builds Docker image using Dockerfile

## How to trigger the pipeline:
1. Commit any file inside `task2-ci-cd/`
2. Push to GitHub
3. Go to the Actions tab
4. Open "Task2 CI Pipeline"
5. Take screenshots of the run logs

