EXPERIMENT NO. 2

1. Experiment Title
Pushing and Cloning a Repository

2. Aim
Create a bare remote repository, push local commits, clone it, and inspect the cloned history.

3. Software / Tools Required
Git, VS Code terminal

4. Theory
A bare repository stores Git data without a working tree and can act as a remote. A remote name such as origin identifies a repository URL. Push transfers commits; clone creates a working copy with history.

5. Algorithm / Procedure
7.	From html-lab, initialize a bare repository at ../html-remote.
8.	Add it as origin and verify with git remote -v.
9.	Push the current branch to origin.
10.	Move to the parent directory and clone html-remote as html-copy.
11.	Enter html-copy and inspect git log --oneline.

6. Program / Queries / Commands
Run these commands after completing Assignment 1 inside html-lab:
git init --bare ../html-remote
git remote add origin ../html-remote
git remote -v
git branch -M main
git push origin main
cd ..
git clone html-remote html-copy
cd html-copy
git log --oneline

If your branch is named master instead of main, use master consistently for the push.

7. Input
Local repository html-lab with commits from Experiment 1.

8. Output
Remote listing shows origin for fetch and push; push succeeds; cloned history contains the same commits.
Output screenshot: Insert a browser/terminal screenshot here after running the experiment.

9. Result
The experiment 'Pushing and Cloning a Repository' was completed successfully. The required concepts and tasks were implemented and verified using the stated tools.

10. Viva-Voce Questions
•	What is a bare repository?
•	What does git remote add do?
•	What is the difference between push and clone?
