# CSI-PCE x Alegria: Git and GitHub Workshop

## Git
Git is a tool used for source code management. It is a free and open-source version control system used to handle small to very large projects efficiently. Git is used to tracking changes in the source code, enabling multiple developers to work together on non-linear development.

## Github
GitHub is an Internet hosting service for software development and version control using Git. It provides the distributed version control of Git plus access control, bug tracking, software feature requests, task management, continuous integration, and wikis for every project.

## Task Summary
The task is to clone this repository. After which, you have to edit the html file and add your personal details. Once you have completed updating your details you have to make a commit. Then you need to create a new repo on Github, once done you need to update the remote origin of your local repo and then make a push to your newly created repo. Once your repo is ready, you have to host it using Github pages. You can follow the steps provided below to perform the task.

# Cloning, Editing And Hosting A Repository 

## How to install Git?

To clone a repository, you will need to have Git installed on your computer. If you don't already have it, you can download it from the official Git website (https://git-scm.com/downloads).


Once the download is complete, continue with the following steps:

1. Run the installer and follow the prompts to install Git on your computer.
2. Open a terminal or command prompt and type git --version to verify that Git has been installed.
3. Configure your name and email address. Git uses this information to associate your commits with your identity. You can use the following commands to set your name and email address:

`git config --global user.name "Your Name"`

`git config --global user.email "your_email@example.com"`

### To check configuration
`git config -global user.name`
`git config -global user.email`

Git on Windows 11 (https://www.youtube.com/watch?v=JgOs70Y7jew)

Git on Windows 10 (https://www.youtube.com/watch?v=cJTXh7g-uCM)

Git on MacOS (https://www.youtube.com/watch?v=hMEyBtsuAJE)



## How to Create Github Account?
To create a GitHub account, you can follow these steps:

1. Go to the GitHub website (https://github.com/) and click on the "Sign up" button in the top right corner.
2. Fill out the form to create a new account. You will need to provide your email address and choose a username and password.
3. Follow the prompts to complete the sign-up process. You may need to verify your email address before you can use your account.

Reference video: https://www.youtube.com/watch?v=nHXw4mGoqiE


## How to Clone a Repository?
Once you have Git installed, you can clone a repository by following these steps:

 1. Open a terminal window or a command prompt.
 2. Navigate to the directory where you want to clone the repository (Preferably Desktop for ease of accessibility). You can use the cd command to change directories.
 3. Copy the URL of the repository you want to clone. This can usually be found on the repository's GitHub page.
Use the <mark>git clone "[Repo Link]"</mark> command, followed by the repository URL, to clone the repository. For example: git clone https://github.com/user/repository.git
 4. Press Enter to run the command.Git will now download a copy of the repository to your computer.

Carryout the above steps and clone the given repository: https://github.com/Subuthai/VerySimplePortfolio.git


## How to Edit the Cloned Repository ?
Once you have cloned the repository, to edit the repository Follow the given steps:
1. Navigate the cloned repository folder on the computer 
2. Right click the folder and select -open with code (opens the folder in VScode) 
3. Select the html file named `index.html`. Edit the details such as Title of the page, Your Name, About Yourself, Your Skills, Your e-mail and so on in the respective tags
4. After you are done with editing, Select -Terminal -> New Terminal from the navbar at top
5. Run the command `git status` which will indicate that the file named "index.html" has been modified.

6. Follow up with the command `git add .` This will add the file "index.html" file to the staging area .
7. Now to commit the changes write the command `git commit -m Edit_Index.html`

## Creating a new Repository and adding a remote origin 
After You have commited the changes, Follow the given steps:
1. Go to your GitHub Page. Click on the "+" button at the top-right corner of the page, Then click on "New Repository"
2. Add a repository name of the format "username.github.io"
3. After adding the name scroll-down and hit "Create Repository"
4. Now on the repository page copy the repo link 
5. Go to VScode and run the command `git remote remove origin` - Which removes the original remote origin of the repository .
6. After that run the command `git remote add origin <paste the link you copied>` - This will add set the remote origin of Repo .
7. To view the origin of the repository u can run the command `git remote show origin`
8. Finally to push your repo on GitHub: 
Run the command `git push origin main`

## Hosting on GitHub Pages
After you have successfully pushed the respective repository on your GitHub profile follow these steps to host your page:
1. On the repository page, Go to settings -> pages.
2. In the "Build and deployment" section -> branch -> select -> main -> save.
3. Reload the current github page and you will be able to see the link for your website, eg. (https://username.github.io/username.github.io) .
 Note : If you find "Error 404" on the site or if u dont find the site link on your page after the refresh, Do wait for sometime until GitHub is finished deploying the entire site on the GitHub pages.
 
 ## Contributors
 Yuvraj Darekar
 Shreeyash Patil
 Varad Page
 
 
