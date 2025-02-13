# COMP2156_Group44_Assignment

## Group Members
- **Leader:** Harsh (101484916) - [GitHub](https://github.com/harshjat05)
- **Member 2:* PRINCE (101483969) - [GitHub](https://github.com/princegahlawat)
- **Member 3:* Umang (101490930) - [GitHub](https://github.com/Umang06092004)

## Project Description
This repository is for the **COMP 2156 - DevOps for System Administration** assignment.  
It demonstrates Git collaboration, branching strategies, and CI/CD integration using **GitHub Actions**.

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/yourgithub/COMP2156_Group44_Assignment.git
2.Switch to Your Branch:
    git checkout -b 101484916-Harsh
    git push origin 101484916-Harsh
3.Create and Add Your Files:
  touch 101484916_gb.txt 101484916_devops.txt 101484916_sdlc.txt
echo "Information about George Brown College" > 101484916_gb.txt
echo "DevOps concepts from COMP 3104" > 101484916_devops.txt
echo "Importance of DevOps in software development" > 101484916_sdlc.txt
git add .
git commit -m "Added project files"
git push origin 101484916-Harsh

#CI/CD Pipeline

The project utilizes GitHub Actions for Continuous Integration (CI). The workflow is defined in .github/workflows/ci.yml and performs the following actions:

Runs on every push and pull request to main

Checks out the repository

Displays repository structure

# Branching Strategy

Each group member follows the branch naming convention:

STUDENTID-Name (e.g., 101484916-Harsh)

Work is done in individual branches before merging into main.

Merge process:      
git checkout main
git pull origin main
git merge STUDENTID-Name
git push origin main


