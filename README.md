# ACS-3922-W25-A0
ACS-3922 W25 Assignment 0 is meant to provide you with experience using Git and Markdown. 

*This is assignment is not for marks and does not need to be completed.*

*The instructions below, assume that you have git installed on your machine. For additional information on installing git please view the [Git Cheatsheet shared on Nexus](https://nexus.uwinnipeg.ca/d2l/le/content/67597/viewContent/1909269/View).*

## Student Information
### Student Name:
### Student Number:

## Assignment Setup (Using a Command Line)

1. To start working on the assignment, clone this repository to your local machine. To do that you should first copy the repository's web URL by clicking on Github's green '<> Code' button.
   
    ![Screenshot of Github's branch, add file, and code button.](assets/github_code_button.png)
Then beside the dispalyed URL click the copy icon.

    ![Screenshot of Github's code options.](assets/github_code_options.png)
1. With the repository's web URL copied, you will next want to open up a 'command line interface' (Terminal on Mac or Command Prompt on Windows)
     - Use ```cd``` on both Windows and Linux/Mac to choose a directory (i.e., folder) that you would like to save the repository to locally. You will have to move through directories as they appear in your file explorer. For example:
  ```cd Documents/UW/ACS-3922/Assignments/A0```
          - If you are unsure about what folders/directories you have you can press Tab to view available options given your current working directory.
      - Once in a desired directory use the following git command to clone the remote repository to your local machine:
    ```git clone [insert the web url copied here without the square brackets]```
      - A few lines of output should appear (likely similar to what is shown below):

        ![Output from a git clone command is shown](assets/git_clone_success.png)
      - You now have a local copy of the repository from which you can work on. To verify this you should be able to graphically see these folders/files in your file explorer wherever you have cloned the repository!
          - You should also be able to view these folders/files in your command line interface. Use ```dir /a:h``` on Windows or ```ls -a``` on Linux/Mac machines to see the files within your directory.
  
        ![Image showing a list of files in a directory, including hidden folders/files](assets/ls_all.png)
      - Once the above is complete, you can open a desired file in your editor of choice to begin working on it.

## Assignment Setup (Using Github Desktop)

## Assignment Instructions
1. Add your name and student number to the top of this README.md file, save the file as you would in your editor, and then commit the file to your repository. To commit you should first, however, add the file to your next commit (stage):
```git add README.md```
   - This step allows you to choose which files that you've edited will later be commited, and lets you keep certain files/changes not commited if desired.
1. With the new README added/staged, you can optionally first check which files have been added for your next commit:
```git status```
Now, commit the file/changes to the repository by using:
```git commit -m "Updated README given assignment instructions"```
Note a few things:
  - ```-m``` is a flag that lets us include a message (i.e., a description of what the commit is)
  - The message at the end should have quotes and should be short and succinct
  - At this point, you have saved a *snapshot* of the new status/version of your files. Notice, however, if you go to Github online you will not yet see these changes. That's becuase you have only saved a snapshot/committed to your local repository.
1. To have the changes appear in the remote (online) repository, you need to now use the ```push``` command:
```git push```
``````
