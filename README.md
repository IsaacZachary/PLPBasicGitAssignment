### PLPBasicGitAssignment GitHub Repository Creation

#### GitHub Repository Creation:
I began by creating a new repository on GitHub named "PLPBasicGitAssignment". To do this, I logged into my GitHub account, clicked on the "+" icon in the top-right corner, and selected "New repository". After naming the repository and configuring other settings as needed, I clicked on "Create repository".

#### Local Folder Setup:
Next, I set up a local folder on my machine to work with the repository. I created a new folder named "PLPBasicGitAssignment" on my Desktop. Using the command line, I navigated to this folder by running:
```bash
cd Desktop
mkdir PLPBasicGitAssignment
cd PLPBasicGitAssignment
```

#### Initialize Git:
Inside the local folder, I initialized a new Git repository by running the command:
```bash
git init
```

#### Link Local Repository with GitHub:
To connect my local repository with the GitHub repository I just created, I added a remote named "origin" using the command:
```bash
git remote add origin https://github.com/YourUsername/PLPBasicGitAssignment.git
```
Replace "YourUsername" with your actual GitHub username.

#### Add Files:
I added the files I wanted to include in the repository to the staging area. For example, if I had a file named "hello.txt", I used the command:
```bash
git add hello.txt
```

#### Configure User Information:
I configured my Git user email and username globally using the commands:
```bash
git config --global user.email "isaaczachary18@gmail.com"
git config --global user.name "Isaac Zachary"
```

#### Commit Changes:
After adding the files, I committed the changes to the repository along with a descriptive message using the command:
```bash
git commit -m "Add hello.txt with a greeting"
```

#### Push Changes to GitHub:
Finally, I pushed the committed changes from my local repository to the GitHub repository by running:
```bash
git push -u origin master
```

#### Verification:
To ensure that the changes were successfully pushed to GitHub, I checked the repository on the GitHub website.

This process allowed me to create a new GitHub repository, set up a corresponding local folder, add files, commit changes, and push them to the remote repository on GitHub.
