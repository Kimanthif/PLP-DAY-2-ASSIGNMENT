# PLP-DAY-2-ASSIGNMENT

se-day-2-git-and-github

Explain the fundamental concepts of version control and why GitHub is a popular tool for managing versions of code. How does version control help in maintaining project integrity?

Version control systems enable software developers to track every change made to a code. Through VCS(Version control systems), it is possible to view the entire history of a code from who made changes, what changes were made and the time the changes were made. VCS also enable collaboration, by enabling multiple developers to work on the same project simultaneously without overwritting each other's work. Github is a popular VCS because it is user friendly and fosters collaboration among developers. VCS helps in maintaining project intergrity through its ability to track all changes made on a code i.e by providing history of a code, it is possible to track who made changes on a code.



Describe the process of setting up a new repository on GitHub. What are the key steps, and what are some of the important decisions you must make during this process?

* One must be logged in Github in order to create a new repository. 
* On the left-upper corner, below the the dashboard, you will find a green icon that says 'New'.
* This is where all other repositories are also listed. If this is the first repository, there will be no others listed.
* Once you click on new, there is a new page that opens. This page contains all important fields marked in (*) asterick that must be filled so as to create the repository. Choose an 'owner'. This is the account that will be identified to with the repository.
* Add the repository's name. Here, Github will allocate the name according to its availability. If the repository's name is not available, you'll get an error that the name has been taken, prmpting you to choose another name. One can add a description of the repository which is optional. This is to briefly describe the repository that you're creating.
* Next, one chooses if the repository will be 'public' or 'private'. Basically this is to choose if the public will have access to your repository or it will only be visible to you as the developer.
* Select 'initialize this repositry with a README.md file'. This creates a repository with a readme file.
* lastly, click on create repository to create the repo.

Discuss the importance of the README file in a GitHub repository. What should be included in a well-written README, and how does it contribute to effective collaboration? A readMe file is added in a repository to communicate important information about the project at hand. 

It includes the following: 
Documentation and clarity ~ it provides important information about the project's purpose,functionality and how to use it. 
Onboarding and collaboration ~ new team members or collaborators in a project, visit the README file to familiarize/understand the project's goals, architecture and guidelines. 
Community engagement ~ for an open source/public project, the README file may act as the project;'s ambasador as it tells on the project. 

A good README file should contain the following:
1. Project overview - describe consisely the project from the purpose,why it exists and what problem is the project solving.
2. Installation - provides clear instructions on how to install the project(prerequisites, dependencies, set -up steps, links etc)
3. Usage - Explains how to use the project. Provides code examples, command-line usage etc covering common use cases and any relevant configuration options.
4. Documentation - If the project has more information beyond README, link it here to enable users stay up-to date with the relevant information regarding your project.
5. Contribution guidelines - Encourages other developers to contribute to your project by providing clear guidelines for code contribution, bug reports and feature requests.
6. Licences - specifies the project's license to clarify how others can use your code legally.
7. Troubleshooting and FAQs - Anticipate common issues users might encounter and provide solutions or workarounds.
8. Credits - acknowledge contributors and give credit to any libraries, frameworks or tools your project relies on.
9. Contact information - provide a way for users and contributors to get in touch with you or your team.



Compare and contrast the differences between a public repository and a private repository on GitHub. What are the advantages and disadvantages of each, particularly in the context of collaborative projects?

~ Public repositories are accessible to everyone on the internet. Anyone can view, fork and clone code. This kind of repository is ideal for open-source projects and collaboration.The advantage of this repos include: collaboration with other developers, visibility through showcasing portfolios to potential employers, it is free-hosted for open-source projects, a developer has access to inbuilt documentation tools and there is room for feedback for codes, improving ones' coding skills.

~ Private repositories on the other hand have restricted access(grants access to owner and invited collaborators). These kind of repos protects sensitive data and proprietary code. They also offer more control over who can view and modify code. The advantages for private repos include code protection by keeping sensitive data secure, access is controlled only to authorized personnel, collaboration can only be through invites only.

**Feature 	      Public 	                Private**
Visibility 	    Open 	                    Limited
Collaboration 	Anyone 	                  Invited only
Security 	      Less secure 	            More protected
Cost 	          Often free 	              May have costs
Use Cases 	    Open-source, portfolios 	Proprietary software

Detail the steps involved in making your first commit to a GitHub repository. What are commits, and how do they help in tracking changes and managing different versions of your project?

1. Create a sample project in Github by right clicking on 'New repository'. Choose an account to be mapped to the project. Name the project. Ensure to 'initialize repository with a README' is selected. Create project.
2. Clone the repository to your local computer.
3. Create a branch and make changes.
4. Commit and push the changes.
5. Merge your changes.

How does branching work in Git, and why is it an important feature for collaborative development on GitHub? Discuss the process of creating, using, and merging branches in a typical workflow.

~ Branching in Git helps a developer to test/work on a project without having to tamper with the main branch.Branches also help to work on different parts of a project simultaneously. When the work is complete, a branch then gets merged with the main branch. Steps to create, use and merge a branch to main are:
* On terminal, Git status --> this is see branch details and commit status.
* Git branch 'images-upload' --> creates a new branch called images-upload.
* Git checkout images-upload --> switches to the new branch images-upload. Make the changes needed, when done commit.
* Git add . --> stages new changes.
* Git commit -m "Your commit message" --> commit changes.
* Git checkout main --> switch to main if this is your main branch.
* Git merge images-upload --> merge changes from images-upload into main.

Explore the role of pull requests in the GitHub workflow. How do they facilitate code review and collaboration, and what are the typical steps involved in creating and merging a pull request?

~ A pull request is a method for submitting contributions to a project. This allows developers to propose changes to a code, which then can be reveiwed, discussed and eventually merged to the main code. When a pull is created by a developer, it is reviewed and if the changes meet the required standards, it is then merged into the main. Pull requests allow review of codes hence improving code quality, better collaboration and streamlined workflows. By requiring reviews before merging, pull requests ensure that multiple eye evaluate the code, increasing the likelihood of catching bugs and enhancing code quality.
Steps involved in creating and merging a pull request include:
* Fork a repository to which you want to contribute to.
* Check for issues that the project admin has put in their repository and choose one of the listed.
* Ask the project admin to assign of the issues to you and then start working on them.
* Clone the repository to your local environment(computer)
* Create a new branch using the git checkout -b "branch name".
* Make the changes to the file and then add the file back to main using "git add ."
* Add a commit message for your repository using "git commit m- "Changes made to the file".
* On the repository in Github, there will be a display that there have been a recent push done on main. Add comments on the changes done and submit for the project admin to review and merge the push to the main code.


Discuss the concept of "forking" a repository on GitHub. How does forking differ from cloning, and what are some scenarios where forking would be particularly useful?

Examine the importance of issues and project boards on GitHub. How can they be used to track bugs, manage tasks, and improve project organization? Provide examples of how these tools can enhance collaborative efforts.

Reflect on common challenges and best practices associated with using GitHub for version control. What are some common pitfalls new users might encounter, and what strategies can be employed to overcome them and ensure smooth collaboration?
