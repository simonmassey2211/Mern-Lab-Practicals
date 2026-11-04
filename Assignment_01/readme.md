1. Experiment Title
Starting a Git Repository
2. Aim
Create a local Git repository, configure identity, create and commit an HTML page, and inspect commit history.
3. Software / Tools Required
Git, VS Code terminal, text editor
4. Theory
Git tracks changes to files through commits. A repository stores project history. The staging area selects changes for the next commit; commits record snapshots with messages. Local Git configuration sets author name and email.
5. Algorithm / Procedure
->1.	Create a project folder and initialize Git.
->2.	Set local user.name and user.email; verify both values.
->3.	Create index.html with an h1 and check git status.
->4.	Stage and commit the page with the required message.
->5.	Add an h2, stage and commit again.
->6.	Run git log --oneline to verify history.
6. Program / Queries / Commands
Task 1 (run inside a terminal):
mkdir html-lab
cd html-lab
git init
git config --local user.name "Your Name"
git config --local user.email "you@example.com"
git config user.name
git config user.email

Task 2:
Create index.html using the included index.html.
git status
git add index.html
git commit -m "Add home page"

Task 3:
Add the h2 shown in index.html, then:
git add index.html
git commit -m "Add next meeting heading"
git log --oneline

Note: the included index.html represents the final state after Task 3.

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>HTML Lab Home</title>
</head>
<body>
  <h1>Welcome to My HTML Lab</h1>
  <h2>Next Meeting</h2>
</body>
</html>

7. Input
No interactive input; Git commands are entered in the terminal.
8. Output
Terminal displays configured identity, clean/changed status, successful commits, and a two-entry one-line log.
Output screenshot: Insert a browser/terminal screenshot here after running the experiment.
9. Result
The experiment 'Starting a Git Repository' was completed successfully. The required concepts and tasks were implemented and verified using the stated tools.
10. Viva-Voce Questions
•	What is Git?
•	What is a repository?
•	What is the staging area?
•	What does git commit do?
