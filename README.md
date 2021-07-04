# Simple CI/CD Project

## Overview of purpose
TDZ Inc., production team used share point to share and update many of their projects. Issue:  works were uncontrollable and waiting time was wasted. DevOps, a better way to increases an organization's ability to deliver applications and services at high velocity. A simple CICD created high level to share with them.

![devOps](devOps.png)

## GihHub Actions to build a CI/CD 
(Continuous integration and either continuous delivery or continuous deployment. Team Collaboration by enforcing automation in building, testing and deployment of applications withing GitHub)

![CI_CD_worflow](CI_CD_worflow.png)

## Steps of basic myGithubActions Github CICD
1. Signing up for a new GitHub account (https://docs.github.com/en/get-started/signing-up-for-github/signing-up-for-a-new-github-account)
2. Creating a new repository and add a ReadmeFile (https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-on-github/creating-a-new-repository)
3. Create the workflow using superlinter.yml & input the code name: Super-Linter
4. Create a workflow (https://docs.github.com/en/actions/quickstart)
* Add file and create new file example : mygithubactions/.github/workflows/superlinter.yml
* Input the code (Push event on ubuntu lastest continer, check the code and Run the Super-Linter
* Commmit to main branch & click the Code tap, back to main repository
* On staticside icon show Yellow as running the workflow & checking the code. If all check code pass, it will turn Green. If all check code fail, it will turn Red. 
* Clieck on staticside icon or Actions tap to review the Super-Linter workflow. 
* Super-Linter workflow.Able to reveiw the setup job, Pull the code & check code and run the Super-Linter again
* Back to main Code area, it will show staticside icon status (pass or fail). First setup, it passed & shwon the green checkmark.
5. Push some code to generate errror, workflow name : main.py
6. Same step as item 4 above. Staticside icon status shown Red icon
7. Correct the code, back to code, correct main.py code and run the main.py again & commit changes. If code no issue, staticside icon will show green check 
8. Any error, Github will notify via email 

# Click this [myGithubActions](https://nethanialtan.github.io/myGithubActions/)









 
 
 





