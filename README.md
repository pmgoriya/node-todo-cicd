# Project Overview
This project can be used to learn and implement CI/CD pipeline with the help of Jenkins.

# Installation Instruction
For Local sudo apt install nodejs sudo apt install npm
npm install node app.js

# Usage Guide
For Jenkins
Setup a freestyle project with this project link as a repo and in Build trigger function add GitHub SCM.
Use GitHub webhook to connect Jenkins and GitHub.
Commit changes in the code and check the automated build and inturn the deployment of the final application.

Commands to build through Docker 

* `cd /var/lib/jenkins/workspace/node-todo`
* `docker build -t node-todo .`
* `docker run -d -p 8000:8000 --name node-todo-container node-todo`

Commands to build through Docker-Compose

* `docker-compose down`
* `docker-compose up -d`


![Screenshot (126)](https://github.com/pmgoriya/node-todo-cicd/assets/139645682/14207fc9-c58d-4d82-95ae-7cacf635bd12)

# Detailed Guide
For more information on How to configure the webhook and how to complete the project refer to the below links

1.[Freestyle guide](https://hashnode.com/post/clnh7t1vb000209mn7n868zkq)

2.[End to end including webhook](https://hashnode.com/post/clnm1rqf0000209l4377b77qx)
