# Questions

## Introduction
Use this document as a starting point for the Class 6 exercise. Please note that these questions will test your knowledge of both the Git CLI and the command line in general.

## Instructions
- Start by creating a new folder and initializing it as a Git repository.
- Copy this file and its contents into your new repository and commit. The copied file should also be named `README.md`.
- Answer the questions below. Introduce each answer as a separate commit.
- Push the resulting repository to your personal GitHub account.
- See the class page for additional submission instructions.

## Questions
1. Assuming that you aren't sure whether you're currently inside of a Git repository, write the command (or commands) that will give you this information.
A: git rev-parse --is-inside-work-tree

2. Assuming that you are currently within a Git repository, write the command (or commands) that will create a new file named 'hello-world.txt' then stage and commit it.
A: cat > hello-world.txt ; git add . ; git commit -m "message"

3. Assuming that you are currently within a Git repository that contains a file named 'README.md', write the command (or commands) that will display any uncommitted changes made to this file.
A: git diff README.md

4. Assuming that you are currently within a Git repository that includes several commits, write the command (or commands) that will display the changes from the commit with the ID of abc123.
A: git show abc123

5. Assuming that you are currently within a Git repository that includes multiple commits, write the command (or commands) that will display the IDs and commit messages for the 3 most recent commits.
A: git commit -n 3
