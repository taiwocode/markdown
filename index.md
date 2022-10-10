# INTRODUCTION TO GITHUB

## Table of content
1. Introduction
2. What is GitHub
3. Why GitHub
4. Git vs. GitHub
5. Cloning (how to clone a repository)
6. Pull request (how to do a pull request)
7. Commit (how to do a commit)
8. GitHub Desktop vs. Github CLI
9. Conclusion
    

# INTRODUCTION
### GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

This tutorial teaches you GitHub essentials like repositories, branches, commits, and pull requests. You'll create your own Hello World repository and learn GitHub's pull request workflow, a popular way to create and review code.

# Why Github
GitHub is an online software development platform used for storing, tracking, and collaborating on software projects. It enables developers to upload their own code files and to collaborate with fellow developers on open-source projects

# Git vs. GitHub
### What Is Git?
#### First developed back in 2005, Git is an extremely popular version control system that is at the heart of a wide variety of high-profile projects. Git is installed and maintained on your local system (rather than in the cloud) and gives you a self-contained record of your ongoing programming versions. It can be used completely exclusive of any cloud-hosting service — you don’t even need internet access, except to download it. 

 

 

Compared to other version control systems, Git is responsive, easy to use, and inexpensive (free, actually). Git is also specially designed to work well with text files — which, if you think about it, is what code actually is. But one thing that really sets Git apart is its branching model. Branching allows you to create independent local branches in your code. This means you can try out new ideas, set aside branches for production work, jump back to earlier branches, and easily delete, merge, and recall branches at the click of a button.

# What Is GitHub?
### In the discussion of Git vs. GitHub, it’s been said that GitHub is to Git what Facebook is to your actual face. What’s that mean? Well, it means that while Facebook is kind of like an online face database (of sorts). GitHub is designed as a Git repository hosting service. 

 

 

And what exactly is a Git repository hosting service? It’s an online database that allows you to keep track of and share your Git version control projects outside of your local computer/server. Unlike Git, GitHub is exclusively cloud-based. Also unlike Git, GitHub is a for-profit service (although basic repository-hosting features are available at no cost to those who are willing to create a user profile, making GitHub a popular choice for open-source projects).

# cloning a repository
### You can clone a repository from GitHub.com to your local computer to make it easier to fix merge conflicts, add or remove files, and push larger commits. When you clone a repository, you copy the repository from GitHub.com to your local machine.

Cloning a repository pulls down a full copy of all the repository data that GitHub.com has at that point in time, including all versions of every file and folder for the project. You can push your changes to the remote repository on GitHub.com
[Git](https://www.GitHub.com) .

# Pulling a request In summary, if you want to contribute to a project, the simplest way is to:

1. Find a project you want to contribute to
2. Fork it
3. Clone it to your local system
4. Make a new branch
5. Make your changes
6. Push it back to your repo
7. Click the Compare & pull request button
8. Click Create pull request to open a new pull request
   

# How to commit
1.  Create a new repository on GitHub.com
2. Open TerminalTerminalGit Bash.
3. Change the current working directory to your local project.
4. Use the init command to initialize the local directory as a Git repository
5. Add the files in your new local repository. ...
6. Commit the files that you've staged in your local repository.
    
# GitHub Desktop vs. Github CLI
When I first started using GitHub, I downloaded GitHub desktop to circumvent the CLI. Fast-foward a few months, and although I have learned how to use the command line, I still find it much faster to commit and push changes to my projects using GitHub Desktop. For example, to commit and push a single file to my repository:
# Using GH Desktop:
1. Click "commit to master"
2. Click "Push origin" button twice
3. Done
   
# Using the Command line:
1. git add filename
2. git commit
3. git push origin master
   
   Despite the fact that the typing process taking longer, most developers/engineers seem to use the CLI instead of GH Desktop.
   # CONCLUSION
   In conclusion, Git provides a way of keeping track of past versions of software and papers,
making collaboration between various authors easy, and provides backup for your software.
It has proven very useful to the open-source community and in academia as well. Git also has
several other commands that can be useful to perform less standard actions such as remove
sensitive data, clean up past history to save space, and so on, but you should know enough toget started with Git. An extension to Git, known as Git LFS (Git large file system) can be
useful if you want to store large files in your repository such as datasets or generated results.
Additional useful resources include Software Carpentry and Stack Overflow, which both
contain a vast store of knowledge on how to use the software. Git’s documentation is rather
exhaustive, but uses a lot of jargon. Once you have a rough idea of what the various commands
do, it can be quite useful especially to better understand the various options.
# REFERENCES 
37https://guides.github.com/introduction/getting-your-project-on-github/
38https://guides.github.com/activities/hello-world/
39https://guides.github.com/features/pages/
40https://guides.github.com/introduction/flow/
41http://pcottle.github.io/learnGitBranching/
42http://sixrevisions.com/resources/git-tutorials-beginners/
43http://www.vogella.com/articles/Git/article.html
44http://jetheis.com/blog/2013/02/17/using-dropbox-as-a-private-github/
45http://book.git-scm.com/
46http://hoth.entp.com/output/git_for_designers.html
47http://www-cs-students.stanford.edu/ blynn/gitmagic/ch02.html
48http://schacon.github.com/git/gittutorial.html
49http://www.youtube.com/watch?v=TPY8UwlTIc0&feature=rel





