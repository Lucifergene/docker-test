# Linux World DevOps Training 

This is the repository where the Project has been uploaded.

### 1. Setting up the Developer/Host  System

This is the system in which the developer works. We are considering it to be **Windows**. Here, Git is installed and authenticated. To make this project more realistic, we are going to work on 2 GitHub branches:
- master
- dev1

First we open the Git Bash. We create 2 directories on our Desktop.
- master_folder
- dev1_folder

Then, we create a new repository in GitHub. We copy the clone url of the repository and clone the it in the master_folder using `git clone <repo url>`.

We move inside the folder just created and create an `index.html` file.
Inside the file, lets type	<br>
`This is from master branch`
<br>
Then we add the file in the Staging Area using `git add . `<br>
Then we commit the changes  using the command: `git commit . -m "first commit from master"`<br>
Finally we push to GitHub using: `git push` <br>

We can also cross-check the contents from the GitHub website to confirm.

Now, we want to work with the `dev1` branch. We want to pull the contents from the `master` branch first.

To create and change the branch, we type: `git checkout -b dev1`
Now, all the codes from `master` branch are present in the `dev1` branch. We want to add an extra line in this branch:<br>
`cat >> This line is from Dev1 branch`

To stage, commit and push, we use the following commands:
```
git add . 
git commit . -m "Second commit from DEV1"
git push -u origin dev1
```

Now, we have setup 2 branches in Github, having some differential codes.


### 2. Setting up the Server System

This is the system where the Web Server will be running. We are going to use 





















