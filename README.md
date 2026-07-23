#  My-Second-Pipeline

A beginner-friendly Jenkins Pipeline project demonstrating a basic CI/CD workflow using Jenkins and GitHub.

##  Project Overview

This project is created to understand how Jenkins executes a Pipeline from a GitHub repository. It includes multiple pipeline stages such as Build, Test, and Deploy using a Jenkinsfile.

##  Technologies Used

- Jenkins
- Git
- GitHub
- Ubuntu Linux
- Java 21
- Node.js
- Docker (Next Phase)

##  Project Structure

```
my-second-pipeline/
├── Jenkinsfile
├── app.js
├── package.json
├── Dockerfile
└── README.md
```

##  Pipeline Stages

-  Checkout Source Code
-  Build Application
-  Run Test Stage
-  Deploy Stage

##  How to Run

1. Install Java 21
2. Install Jenkins
3. Install Git
4. Create a Pipeline Job in Jenkins
5. Connect the GitHub repository
6. Set Script Path:
   ```
   my-second-pipeline/Jenkinsfile
   ```
7. Click **Build Now**
8. Verify **Finished: SUCCESS** in Console Output.

##  Expected Output

```
Building Application...
Running Tests...
Deploying Application...
Finished: SUCCESS
```

##  Learning Outcome

- Jenkins Installation
- GitHub Integration
- Pipeline as Code (Jenkinsfile)
- Multi-stage CI/CD Pipeline
- Basic DevOps Workflow

##  Author  ##

**Samir Kotwal**

---

⭐ This repository is part of my DevOps learning journey from Zero to Hero.
