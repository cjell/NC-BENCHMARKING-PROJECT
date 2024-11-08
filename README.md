# Setting up this repository in VSCODE
- In vscode, if you are on the welcome page you should see an option called "Clone Git Repository." If you are not on the welcome page, just click 'File' in the top left and then select 'CLose Folder' and you should be returned to it.
- Click 'Clone Git Repository,' and you will be prompted to provide a repository URL. To get the URL, click the green Code<> button in github and copy the HTTPS.

# Using the repository
- Before beginning making changes to the code, in your terminal type the command 'git checkout -b nameofbranch'
- This creates a new branch named whatever you replace 'nameofbranch' with which makes it so that you are editing a copy of the code rather than the pre-existing code itself so when you push to to github both the code from before you edited it and your code will appear.
- Once you have finished what you wanted to do, and want to push it to github, use the commands:
  - 'git add .' (This stages the changes you have made)
  - 'git commit -m "some message like what changes you made"' (Saves your staged changes)
  - 'git push -u origin nameofbranch' (Pushes your code to github. You only have to inclue the '-u' the first time that you push code to a new branch)

