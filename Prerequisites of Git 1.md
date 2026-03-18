#### **Prerequisites**



>> Install Git on your system [Website link](https://git-scm.com/install/) for downloading the git 



>> Restart VS Code after installation so it can detect Git.​



>> Create or log in to a GitHub account in your browser.





**Create a new repo on GitHub Refer here for the repo creation** [**Document for Creating Repo**](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-new-repository)



>> **Go to** [**github**](https://github.com) **and log in**



>> In the top‑right corner, click the “+” icon → New repository.



>> Fill details:



Repository name: e.g. my-react-app.



Description: optional.



Visibility: choose Public or Private



>> Click Create repository. Now GitHub shows you some commands to run in your terminal.





**Git in VS Code** [**Document for adding git in Vscode**](https://code.visualstudio.com/docs/copilot/setup)



**>> Open VS Code.

>> Look at the left sidebar (Activity Bar) or bottom status bar for an icon that looks like a person or shows “Sign in”.**



**>> Click that Accounts icon to open the account menu.**





###### **Open project and initialize Git**



Open your React project folder in VS Code (File → Open Folder), make sure it contains package.json, src, etc.





**Command to Upload the Project from the vs code to the GitHub**



Initialize git in the project folder



>> git init



Stage all files (including Readme if present)



>> git add . 





Save the files with a message



>> git commit -m "first commit"





Rename branch to 'main' to match GitHub's default



>> git branch -M main





Link your local folder to your GitHub repository



>> git remote add origin https://github.com/navee88/SDMSSite.git





Upload the code and link the 'main' branch



>> git push -u origin main







**Updating an Existing Project**



Steps



Step 1: Stage Your Changes



This command adds your recent modifications to the staging area, preparing them to be saved.



>> git add .



Step 2: Commit Your Changes



This saves the staged files as a new version. Always use a clear, descriptive message that explains what you changed.



>> git commit -m "Update file name like that"





Step 3: Push to GitHub



This uploads your committed changes to the connected GitHub repository.



>> git push









