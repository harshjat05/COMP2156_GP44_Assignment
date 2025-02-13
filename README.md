# COMP2156_Group1_Assignment

## Group Members

- **Leader:** Harsh (101484916) - [GitHub](https://github.com/Harshjat05)
- **Member 2:** PRINCE (101483969) - [GitHub](https://github.com/princegahlawat)
- **Member 3:** Umang (101490930) - [GitHub](https://github.com/Umang06092004)

## Project Description
This repository is created as part of the **COMP2156 - DevOps for System Administration** course.  
It demonstrates:
- Collaborative GitHub workflows with multiple team members.
- Best practices in **branching, merging, and resolving conflicts**.
- Implementing **Continuous Integration (CI)** using GitHub Actions.
- **Pull Request management** and structured workflow strategies.

---
## Setup Instructions

1. Each member Cloned the repository.
https://github.com/harshjat05/COMP2156_GP44_Assignment

2. Each member created their own branch following the STUDENTID-Name format:

git checkout -b 101483969-PRINCE
git push -u origin 101483969-PRINCE.

3. Each member was responsible for creating three text files containing relevant .

4.Each member was responsible for creating three text files containing relevant information

5.Files Created by Each Member
Each member created the following files:

Prince:

101483969_gb.txt → About George Brown College.
101483969_devops.txt → Information about COMP 3104 (DevOps).
101483969_sdlc.txt → Importance of DevOps in SDLC.
   Harsh,Umang: (Similar format using their Student ID)

6.Each member made at least 10 commits:

7.Once all files were created and modified, each member merged their branch into main.

#CI/CD Pipeline

The project utilizes GitHub Actions for Continuous Integration (CI). The workflow is defined in .github/workflows/ci.yml >

Runs on every push and pull request to main

Checks out the repository

Displays repository structure

#Branching Strategy

Each group member follows the branch naming convention:

STUDENTID-Name (e.g., 101483969-PRINCE)

Work is done in individual branches before merging into main.

Merge process:
git checkout main
git pull origin main
git merge STUDENTID-Name
git push origin main

