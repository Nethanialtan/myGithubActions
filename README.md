# Simple CI/CD Project


GihHub Action to build a CI/CD actions
* Continuous integration and either continuous delivery or continuous deployment. Team Collaboration by enforcing automation in building, testing and deployment of applications withing GitHub)



![CI_CD_worflow](CI_CD_worflow.png)


## Allow Continues Integration 

* Build 
* Test
* Merge

## Allow Continues Delivery

* Automactically Release to repostitory 

## Allow Continues deployment 

* Automactically Deploy to production

# Create New repostitory

* Input repostitory name, add Readme & create repostitory

# Create Workflow

* Go to Add File, Click Create new file
* Input  naming dir. example:  .github/workflows/durian
* Input yml file for Push event run on ubunto lastest, Checkour code
* run code: super-linter & Commit file
* Go back to Code and check file 
* Click on ACtions tap to view the workflows running on Super-Linter
* Clink the Lint Code base, viewing all running super-linter code, running behind
* Any error will show on log file
* Click Code tap, back to main to check. If pass, there will be a green tick, if any concern, will shown a yellow deployment

# Push new code, check the update/testing code (pass/fail)

* Click add file, create a new file
* input the new code, name the file & commit input
* Green tick Shown testing code Passed
* Yellow dot, show there is a issue, click and review the code edit the error code, and commit again to test the code
