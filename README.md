# PLPBasicGitAssignment
## Task 1: Repository Setup

LoggedIn to github account and created a repository `PLPBasicGitAssignment` and initialized it with a README file.

![Creating-a-Repository](https://github.com/user-attachments/assets/f8647dbd-b9c7-4e9f-8910-6404393ddfcd)


## Task 2: Local Setup

created a new folder on my local machine `PLPBasicGitAssignment`

![Local-Machine-folder](https://github.com/user-attachments/assets/8ade7c88-6dd2-40c7-b988-0b733172e3ee)

Then navigated to the folder using GitBash terminal then initialized the repo.

![Navigated-to-local-folder](https://github.com/user-attachments/assets/35148297-8af5-46bf-bafa-701fcc64a8a9)

Then linked my local repository to the remote repository on GitHub by following these steps:
- `git init`
- `git remote add origin https://github.com/yourusername/my-app.git`
- `git fetch origin`
- `git merge origin\main`

![linking-to-remote-repo](https://github.com/user-attachments/assets/5d341e70-3ab7-45a0-adca-8b77380fbb15)

## Task 3: Making Changes

created a `hello.txt` file using Visual Studio Code and added the `Hello,Git` message.

**Steps**
- Open the VS Code
- Go to file > open folder (open the folder that you created on your local machine)
- Inside the folder create a new text file `name.txt`
- Then write your message

#### Commiting changes:
Go to your GitBash terminal and add the following commands
- `git add hello.txt`
- `git commit -m "Add hello.txt with a greeting"`

### Task 4: Pushing to GitHub
I used VS code to push the commited changes because GitBash was giving me an error.

![Error](https://github.com/user-attachments/assets/760813b7-361e-425d-a704-0df6fc8d53d2)

