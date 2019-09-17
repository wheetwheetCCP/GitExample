# GitExample# GitClass
Please make changes to this project to familiarize yourself with Git!

Use Git Bash! Here are commands to help you do the following:

## Cloning the project:
1. In Git Bash, navigate to where you want to create a folder for this project.
2. Make the folder
  `mkdir GitCode`
3. Move info that folder
  `cd GitCode`
4. In Github, Click o "Clone or Download" and copy the URL [https://github.com/wheetwheetCCP/GitExample.git](https://github.com/wheetwheetCCP/GitExample.git)
5. In Git Bash, clone the repo
  `git clone https://github.com/wheetwheetCCP/GitExample.git`
6. Move into the project folder
  `cd GitExample`
7. *MAY NEED TO DO THIS*
  Connect to Github
  ```bash
   git config --global user.name "YOUR NAME"
   git config --global user.email "YOUR.NAME@gmail.com"
  ```
  
## Making your own branch:
1. In Git Bash, navigate to your project folder
  `cd GitExample`
2. Create a new branch with your name as the branch title
  `git branch YOUR_NAME`
3. Make your branch your active branch
  `git checkout YOUR_NAME`

## Make a Change
1. Open up file explorer and navigate to your GitExample folder
2. Open New Text Document.txt and make a change to it (or add your own file)

## Checking that you made changes and saving them:
1. Check to make sure your changes show up in Git Bash
  `git status`
2. Add all your changes to the branch
  `git add *`
3. Commit your changes and add a change message
  `git commit -m "your message here"`
4. Push to your remote branch
  `git push`


## Uploading your changes for everyone to have:
1. Switch to the master branch
  `git checkout master`
2. push your changes to the master branch
  `git push origin YOUR_NAME`
