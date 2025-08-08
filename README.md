# DevOps Git Demo

## About
I created this project to practice Git workflows and DevOps concepts.

## What I Did
- Set up Git repository with proper branching
- Created `main`, `dev`, and `feature` branches
- Used pull requests to merge changes
- Added deployment script and documentation

## Project Structure
```
devops-git-demo/
├── src/app.py
├── scripts/deploy.sh
├── README.md
└── .gitignore
```

## Git Workflow I Used

### 1. Created Dev and feature Branch
![Dev Branch Creation](images/devandfeature.png)

### 3. adding features
![Feature Merge Success](images/changesinfeature.png)

### 3. Merged Feature to Dev
![Feature Merge Success](images/mergingdev-feature.png)

### 2. merged successfully
![Feature Branch Creation](images/mergedsuccessfully.png)

### 4. Merged Dev to Main
![Dev to Main Merge](images/mergingmain-dev.png)

## Usage
```bash
# Run the app
python src/app.py

# Deploy
./scripts/deploy.sh
```

## What I Learned
- Git branching strategies
- Pull request workflow
- DevOps best practices
- Project documentation

## Technologies
- Git & GitHub
- Python
- Bash scripting

---
Created by [@Mohdaasif97](https://github.com/Mohdaasif97)
