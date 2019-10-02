# A03

Git is a distributed version-control system that is designed to help keep track of a developer's computer programs, 
files and also any changes made in the files over time. Git helps a programmer collaborate with his or her peers when working on a coding project. For example, when developing an application or a website, different developers may decide to work together on the same project but each one of them working on their own module. On the other hand, Git works hand in hand with github, Github is a website for hosting developer’s programs and projects using the Git server system. 

Here are the steps to follow in order to use git and github;

Step 1 - For you to use Git for your projects, you first need to install it on your computer.
Step 2 - Open the git official website with the link: https://git-scm.com/downloads . 
Step 3 - Select the appropriate OS of your computer (Windows, Mac OS, etc.) and download the program on your computer. 
Step 4 - Run the program to install.  
Step 5 - Open github website with the link: https://github.com/join and create an account with github in order to use git and github. 
Step 6 - On signing up and opening an account, you will need to create a repository on the github website in your account. 
Step 7 - After creating your repository and want to start controlling your local project with git, you will be required to initialize 
your local repository with the one that already exists on github. 

Here are some commands you will run on git in order to achieve this with pc -
  $ cd /c / user / your_project then hit enter
 And type $ git init 
 On doing so you need now to add your files to the github repository by typing the following command -
 $ git add .
After adding the the files you will be require to specify the files that you have added to the subdirectory for tracking. This is done with the help of git command -
  $ git commit –m “my first commit”  hit enter
To make sure that the changes that you’ve made in the local repository are pushed to the remote repository that is the github, you will use the $ git push command. For instance, 
$git push hit enter

There are other git commands the you should probably get familiar with when using git and github. Such as;

Repository - "A Git repository is the .git/ folder inside a project. This repository tracks all changes made to files in your project, building a history over time." Silva, Jonathan. “Learning Git: What Is a Git Repository?”
Commit - A command used to save any changes made to the local repository
Clone - Clone is used to make a duplicate or copy of an existing repository. We use it as $ git clone the link url. For example, $git clone  <url>
Push - "The git push command is used to upload local repository content to a remote repository. Pushing is how you transfer commits from your local repository to a remote repo." Atlassian. “Git Push: Atlassian Git Tutorial.”
Pull - Pull is a git command used to fetch and download content from remote repository and update the local repository. Here is its command $ git pull <remote repo>
Branch - A feature on the version control systems that keeps a record of the changes and commits that has been updated. It acts as a reference with a series of commits.
Merge - Merge is used to join together independent lines created by git branch to make the one branch. We simply use $ git merge
Merge Conflict - "Merge conflicts happen when you merge branches that have competing commits, and Git needs your help to decide which changes to incorporate in the final merge." About Merge Conflicts - GitHub Help
Fetch - Git fetch is a command on git that is used to download changes from the remote folder to the local folder in order to match the changes in both repositories. $ git fetch .
  
Remote - The repository stored on the hosting service that is used by team members to exchange their changes.
  
  
  
References

https://git.github.io/htmldocs/git.html

https://git-scm.com/docs.

Silva, Jonathan. “Learning Git: What Is a Git Repository?” Dev Blog by Axosoft, Dev Blog by Axosoft, 10 Apr. 2018, https://blog.axosoft.com/learning-git-repository/.

Atlassian. “Git Push: Atlassian Git Tutorial.” Atlassian, https://www.atlassian.com/git/tutorials/syncing/git-push.
“About Merge Conflicts.” About Merge Conflicts - GitHub Help, https://help.github.com/en/articles/about-merge-conflicts.
