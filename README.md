# GitHub Tutorial

by Habiba Khedr

---
## Git vs. GitHub

 ## Git                                         Github
    * enables you to work on and                    * It is web-based 
      keeps track of your code.                     * It stores your information
    * It is a Version Control System                  in cloud
      which leeps a snapshot of your work           * Allows you to easily work
    * It doesnt require Github                        with others.
                                                    * Tracks your changes
    
 ![git vs github](https:/github-tutorial/blob/master/git-vs-github.png)
 
 
 



---
## Initial Setup
To make a github account folow the steps below:
1. Go to [https://github.com/]( https://github.com/)
2. On the right top corner you will see a "sign Up" button. Click on it 
3. Now you will see a page  that says "create your account". 
4. Type in your username (if you are a HSTAT student use school email)
5. Type in password
6. Verify account by slocing a quick puzzle.
7. Click the blue button on the bottom of the page to continue
8. Choose your plan
9. Then answer the 3 questions (or you can skip this step)
10. After done answering the questions click the button that says "Complete setup"
11. Verify your email adress
12. Now you have a github account.

Now to set up your ide follow the steps below.
1. Start out with going to [ide.cs50.io](ide.cs50.io)
2. Login with your github account 
3. Then go to this link and follow every step [https://github.com/hstatsep/ide50](https://github.com/hstatsep/ide50)
4. Now you have your ide set up for you.

As you were setting up your ide you set up an SSH Key between your ide and Github which is really important for you to have. When working with a GitHub repository, you'll often need to identify yourself to GitHub using your username and password. An SSH key is an efficent way to identify yourself that doesn't require you to enter you username and password every time.


---
## Repository Setup
After setting up both your ide and Github accountyo can start yo create reposistories.
1. Choose or make a directory
2. Now to intialize git ti turn it into a repository type `git init`in the command line.
3. Make a new file by typing in `touch "filename"`in the command line.
4. Now type `c9 "filename"` to open your file.
5. Once you have done that try typing anything you want
6. After you are done with the changes you have made go back to the command line and type `git add .`
7. Then type `git commit -m "short message`. The message that you should type in should be short and in present tense.It would also be good if you write what you have changed at that point.
8. As you keep editing your file dont forget to add and commit.
9. you should also use git statu alot as you are coding and making chnages to keep track of what you are doing.


---
## Workflow & Commands
The commands below are all typed in the command line and are ones that you will use often when coding.

`git init`: This command is used to initialize git in our directory and should only be done once in the beginning.
* This should be done in a directory of your choice that you would like to turn into a repository.
* If done in the wrong or root directory you can use the command `rm -rf .git`. This command can just be typed in and it will unintialize git.

`git status`: This command should always be used when coding because it allows you to see what ypou have just done. For instance if you just added something.This command will always be useful to anyone when coding to check if the code that they are typing is actually doing what the want.
 
Both of these commands can be used when you are done making your changes and want to add them so that they can be saved to the stage:
* `git add .`: This command adds all of the changes that you have just made to your files to the stage.
* `git add file.ext `: This command adds files to the stage to be committed.

`git commit -m "message"`:This command should be used when you have already added your changes and want to commit them.
* Be sure that th message that you type in shoulde be in present tense, short, and what you changed.

When you have a local and remote repo the two command below will be very important to know:
* `git push`: This command sends the changes from the local repo to the remote repo.

You are proablly wondering where you are pushing your commits to. You will have to follow the steps below:
1. Make a new repository (if you dont remember how to do so to scroll up to the scetion before)
2. Create a README.md by typing in `touch README.md`
3. Save, add, and commit
4. Once ypu have followed all of the steps above go log into your github account.
5. On the top tight of yur scrfeen you will see a plus icon. Click it.
6. Then click on create new repository
7. The name of your repository should always match the name of your repository in your ide.
8. Now click on the button that says "create repository" 
9. Now you should be on a a new page
10. 



---
## Rolling Back Changes