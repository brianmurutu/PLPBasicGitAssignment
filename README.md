# Assignment Documentation: Basic Git and GitHub Workflow

## Objective
The objective of this assignment was to familiarize with the basic workflow of creating a GitHub repository, connecting it to a local folder, and making commits and pushes.

## Requirements
- A GitHub account
- Git installed on the local machine
- A code editor (e.g., Visual Studio Code, Sublime Text)

## Task 1: Repository Setup

1. **GitHub Repository Creation:**
   - Logged in to GitHub account.
   - Created a new repository named "PLPBasicGitAssignment".
   - Initialized the repository with a README file.

## Task 2: Local Setup

2. **Local Folder Setup:**
   - Created a new folder named "PLPBasicGitAssignment" on the local machine.

3. **Git Initialization:**
   - Opened a terminal.
   - Navigated to the "PLPBasicGitAssignment" folder.
   - Initialized a new Git repository using the command `git init`.

4. **Connecting to GitHub:**
   - Linked the local repository to the GitHub repository using the command:
     ```
     git remote add origin <repository-url>
     ```

## Task 3: Making Changes

5. **Create a File:**
   - Created a new text file named `hello.txt` inside the "PLPBasicGitAssignment" folder.
   - Added a simple text message "Hello, Git!" to the `hello.txt` file.

6. **Committing Changes:**
   - Staged the changes using the command:
     ```
     git add hello.txt
     ```
   - Committed the changes with the message "Add hello.txt with a greeting" using the command:
     ```
     git commit -m "Add hello.txt with a greeting"
     ```

## Task 4: Pushing to GitHub

7. **Pushing to GitHub:**
   - Pushed the committed changes to the GitHub repository using the command:
     ```
     git push -u origin main
     ```

## Task 5: Verification

8. **Verify on GitHub:**
   - Visited the GitHub repository in a web browser.
   - Confirmed that the `hello.txt` file and commit message are visible.

## Additional Notes
- This is my documentetion of all steps and commands used in this assignment for future reference.
