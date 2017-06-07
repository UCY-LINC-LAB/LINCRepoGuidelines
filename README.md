# LINC Git Repository Guidelines
This repository will  provide basic guidelines on how to properly create and manage Software Repositories that will be hosted under LINC's Git Organization.

More specifically the topics covered in this guideline are listed below:
* [Naming Conventions](#naming-conventions)
* [Providing sufficient repository descriptions](#providing-sufficient-repository-descriptions)
* [Repository Good and Bad Practices](#repository-good-and-bad-practices)
* [Collaborative coding - Repository Contributors](#collaborative-coding---repository-contributors)
* [Organization of Repositories](#organization-of-repositories)
* [Licencing](#licencing) 

## Naming Conventions  
It is important to use proper naming when creating a repository which will be hosted
under LINC. A repository name should be clear, easy to read and by reading it someone should get an idea of what the repository is about.

The following list can be used as a checklist in order to properly chose a name for your repository:
1. **Select a descriptive name for your repository.** 
 When thinking about naming your repository try to avoid selecting names that are too generic. Be specific! The name of your repository should reflect to the capabilities of your project and inform everyone that is interested about your project what is it about.
   >Example: You are a Bsc student that is doing his Bsc Thesis
   in LINC. Your Thesis topic demands from you to develop an Eclipse CHE plugin 
    that orchestrates cloud application deployments to Amazon Web Service
    
    **__Bad repository naming:__** Based on the example above names such:
     * ADE
     * Thesis
     * Diplomatiki
     * .....
     
     The names above are too generic and do not provide any useful information about the capabilities and nature of your work.
     
     **__Good repository naming:__** On the other hand as good repository names based on the example above can be considered: 
     * eclipse-che-aws-orchestration-plugin
     * EclipseCheAWSOrchestrator
2. **Follow one of the naming conventions below**
    1. **Use lower case letters and dashes** to seperate different words. This is your best option and the easiest one to read (e.g., eclipse-che-aws-orchestrator-plugin)
    2. **Use the camel case** (e.g., EclipseCheAWSOrchestrator) Although this conventions is ok it is a little bit more difficult to read especially for longer repository names.
3. **Be consistent when naming your repositories**

## Providing sufficient repository descriptions
Every repository that is hosted under LINC should have at least **_one_** `README.md` file inside the repository root folder(like the one you are reading now) that contains cobrehensive description of the content of the repository.

Inside the `README.md` one should include:
1. Short description of the problem that the software is trying to solve.
2. What was the approach used to solve the problem and the basic features of the software.
3. Complete and clear step-by-step description of the development and execution environments needed to run the software (e.g., how to resolve dependencies, versions of programming language etc. )
4. Complete and clear step-by-step description of how to use and run the software.
5. Explanation of the API/Classes/Functions (with examples if possible)
6. State what kind of licence is your software under.
7. List the contributors and contact information.

`README.md` is written in [Markdown language](https://guides.github.com/features/mastering-markdown/). It is advised to use .md files within subfolders of your projects whenever you feel there is a need to explain something specific in detail.
## Repository Good and Bad Practices

## Collaborative Coding - Repository Contributors

## Organization of Repositories

## Licencing