# Learning-GitHub

### How To Make Repository


To make an repository from GitHub :

 **Required Fields:**  
- You must add unique repository name

 - There is two type of repository that you can make it :
    - public (anyone on the internet can see this repository. You choose who can commit.)
    - private (you choose who can see and commit to this repository.)




 **Optional Fields:**  
- You can add description of  repository 

 - Add a README file (This is where you can write a long description for your project).

  - Add .gitignore (Choose which files not to track from a list of templates).

  - Choose a license (A license tells others what they can and can't do with your code).


After Choose what do you need for your project then click the green button below called *Create repository*




<br>
<br>

<u><small>*This an description by image to this process* </small></u>

![Alt text](https://i.ibb.co/gZRvRfD/1.png)

To create a repository from terminal 
``` bash
echo "# LearnGit" >> README.md
```
<small>this command will create a readme.md file with heading LearnGit</small>


``` bash
git init
```
<small>Initialize a new Git repository in the current directory or in a specified directory</small>
<small>Git creates a new directory named ".git" in the root of the working directory. This ".git" directory contains all the necessary files and subdirectories that Git uses to manage the repository.</small>


``` bash
git add README.md
```
<small>Adds the file named "README.md" to the staging area in Git.</small>

``` bash
git commit -m "first commit"
```
<small>Creates a new commit with the changes that have been staged using git add, along with a commit message "first commit".</small>

``` bash
git branch -M main
```
<small>Renames the current branch to "main".</small>

``` bash
git remote add origin <url>
```
<small>Used to add a remote repository named "origin" with the specified URL.</small>


``` bash
git push -u origin main
```
<small>Pushes the commits from your local "main" branch to the remote repository named "origin" and sets the upstream branch to "main".</small>
