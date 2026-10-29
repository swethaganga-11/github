All Commands in One Place

Use these commands in order, replacing the example URLs and folder names with your own.

# 1. Clone the original repository
git clone <original-repository-url>

# 2. Enter the project folder
cd <project-folder>

# 3. Display hidden files
ls -la

# 4. Remove the original Git history
rm -rf .git

# 5. Initialize a new Git repository
git init

# 6. Stage the files
git add .

# 7. Commit the files
git commit -m "Initial commit"

# 8. Connect to your new GitHub repository
git remote add origin <your-new-repository-url>

# 9. Rename the branch
git branch -M main

# 10. Push the code
git push -u origin main

Interview Scenario: Explain These Steps

Interviewer: How do you take code from an existing GitHub repository and upload it to your own repository without the original Git history?

Answer:

"First, I clone the original repository using git clone and move into the project directory using cd.

Then I check the files, including hidden files, using ls -la. I remove the existing .git directory because I want to start with a fresh Git history.

Next, I initialize a new repository using git init, stage the files using git add ., and create an initial commit using git commit.

After that, I create a new repository on my GitHub account and connect it using git remote add origin.

Finally, I rename the branch to main and push the code using git push -u origin main.

Now, the code is available in my own GitHub repository with a new Git history."

Important Interview Questions

1. What is the difference between git clone and git init?

git clone downloads an existing repository, including its Git history.

git init initializes a new Git repository.

2. What is the .git directory?

The .git directory stores Git metadata, configuration, commit history, and references for a repository.

3. What happens when we run rm -rf .git?

It removes the .git directory and its local Git metadata. The project files remain, but the folder is no longer a Git repository.

4. What is the purpose of git remote add origin?

It connects the local repository to a remote repository, such as one hosted on GitHub.

5. What is the purpose of git push -u origin main?

It pushes the local main branch to the remote named origin and sets the upstream branch for future pushes.

6. What is the difference between a fork and this process?

A GitHub fork creates a copy of a repository under your account and normally retains its commit history and connection to the upstream repository.

Removing .git and initializing a new repository creates a fresh Git history instead. Therefore, this process is not technically a GitHub fork.


Remember: Only copy and republish code when you have permission to do so and the project's license allows it.
