# PLPBasicGitAssignment
# PLP Basic Git Assignment

This README documents the steps and commands used to complete the PLP Basic Git Assignment.

## Task 1: Repository Setup

1. GitHub Repository Creation:
   - Logged in to GitHub account
   - Created a new repository named "PLPBasicGitAssignment"
   - Initialized with a README file

## Task 2: Local Setup

2. Local Folder Setup:
   - Created a new folder on local machine:
     ```
     mkdir PLPBasicGitAssignment
     cd PLPBasicGitAssignment
     ```

3. Git Initialization:
   - Initialized a new Git repository in the local folder:
     ```
     git init
     ```

4. Connecting to GitHub:
   - Linked local repository to the GitHub repository:
     ```
     git remote add origin https://github.com/yourusername/PLPBasicGitAssignment.git
     ```

## Task 3: Making Changes

5. Create a File:
   - Created a new text file named hello.txt:
     ```
     echo "Hello, Git!" > hello.txt
     ```

6. Committing Changes:
   - Staged the changes:
     ```
     git add hello.txt
     ```
   - Committed the changes:
     ```
     git commit -m "Add hello.txt with a greeting"
     ```

## Task 4: Pushing to GitHub

7. Pushing to GitHub:
   - Pushed the committed changes to GitHub repository:
     ```
     git push -u origin main
     ```

## Task 5: Verification

8. Verify on GitHub:
   - Visited the GitHub repository in a web browser
   - Confirmed that hello.txt file and commit message are visible
