# Identify and Fix Issues in Your Repositories

## Introduction
During the program, you'll have noticed that the structure of a repository evolves over the course of a project. By the end of the project, you need to pause and review your repository to align it with employer expectations. In this lesson, we'll outline some typical issues that can be easily fixed in order to make your repository exemplary.
​
## Objectives
You will be able to:  
* Identify key issues within an example data science project repository  
* Review industry standards and employer expectations for project organization  
​
## Reviewing a Typical Repo and Identifying Issues 
### Typical Repo  

Here is a picture of a typical data science project repository. Take a moment to review it and see if you can identify five aspects that could be improved:  


<img src="https://raw.githubusercontent.com/learn-co-curriculum/dsc-postgrad-repo-org-problems/master/MessyRepo.png" alt="Image of repository with errors before any changes are made.">  

​
### Issues Identified  
The issues are identified in the picture below:  
​

<img src="https://raw.githubusercontent.com/learn-co-curriculum/dsc-postgrad-repo-org-problems/master/MessyRepo_numbered.png">  
​

#### Issues List:  
1. No project description
2. No `.gitignore` file , so unwanted files such as `.DS_Store` and `.ipynb_checkpoints` are included
3. Non-descriptive names for the presentation, notebook and data file
4. Images are at the same level as the rest of the repository, instead of inside an image folder
5. Data is included in repo instead of in a data folder (or not provided in repo at all)  

<br/>
​
<a src="https://drivendata.github.io/cookiecutter-data-science/#directory-structure"><strong>Cookie Cutter Data Science </strong></a>is a great resource to guide how you structure a repository. At the end of the reorganization, the cleaner project repository will look like this:  

​
<img src="https://raw.githubusercontent.com/learn-co-curriculum/dsc-postgrad-repo-org-problems/master/PolishedRepo.png">   

​
A combination of Git & bash commands, along with some thoughtful renaming through GitHub's platform, will fix a messy repository. Please fork and clone the <a src="https://github.com/learn-co-curriculum/dsc-postgrad_Project-Repository"><strong>Messy Repository Example</strong></a> if you want to follow along with the steps detailed on your own machine.  
​
## Summary 
Great! Next up, we'll be guiding you through a list of steps you can use to clean up a repository.