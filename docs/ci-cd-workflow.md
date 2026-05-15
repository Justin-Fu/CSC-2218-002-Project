Justin Fu
2026-04-05
CSC-2218-002
Week 09 - Assignment 01 - CI/CD Workflow Design
ci-cd-workflow.md



1. Overview of CI/CD

Continuous Integration is when the source code is changed frequently and continuously. Continuous
Deployment/Delivery is when the project is updated frequently, which is in this
means that the deployment occurs often. CI/CD is important for the modern
software development because it allows for the code to be frequently updated
and maintained.


2. Proposed Pipeline Stages

When the developer commits the code to GitHub, they will commit the code to a testing branch, not the
production (main) branch. At the time of submission, the CI pipeline will
automatically trigger and run automated tests, as well as build the project.
Then, the application is deployed to a staging environment to wait for a manual
review/approval. Once the approval is made and the commit is properly tested
and ready to deploy, then the code is submitted for deployment to the
production (main) branch.


3. Tools that could be used

Some tools that can be used are GitHub or GitLab to host the project.
These platforms are useful for hosting projects, and if the project were to be set to public,
it can be accessible to view and in addition for other people to make a fork,
or make a copy and make their own modifications to the project.

