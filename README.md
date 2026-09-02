Garden App GitFlow Project
Overview

This project demonstrates the use of the GitFlow workflow using Git and GitHub. The project consists of a simple Garden Advice application containing HTML, JavaScript, and Python files. The purpose of the project was to practice branching, committing changes, creating pull requests, and merging code into the main branch.

Repository Structure
Plain Text
1
garden-app
2
│
3
├── garden_advice.py
4
├── garden_advice.js
5
└── index.html
Show more lines
GitFlow Workflow Implemented

The following GitFlow process was followed:

1. Created Feature Branches

Two feature branches were created from the main branch:

Plain Text
1
feature/refactor-functions
2
feature/add-comments
Show more lines
2. Refactored Code

A feature branch was used to refactor the existing code into functions to improve structure and maintainability.

Commit:

Plain Text
1
Refactor code into functions
Show more lines
3. Added Comments

A second feature branch was used to add explanatory comments throughout the code to improve readability and understanding.

Commit:

Plain Text
1
Add detailed comments to improve readability
Show more lines
4. Created Pull Requests

Separate Pull Requests were created for each feature branch and submitted for review before merging.

Pull Requests:

Plain Text
1
Refactor code into functions
2
Add detailed comments to improve readability
Show more lines
5. Merged into Main

Both Pull Requests were successfully merged into the main branch.

Git Commands Used
Create Branch
Shell
1
git checkout -b feature/refactor-functions
2
git checkout -b feature/add-comments
Show more lines
Stage and Commit Changes
Shell
1
git add .
2
git commit -m "Refactor code into functions"
Show more lines
Shell
1
git add .
2
git commit -m "Add detailed comments to improve readability"
Show more lines
Push Branches
Shell
1
git push origin feature/refactor-functions
2
git push origin feature/add-comments
Show more lines
Create Pull Requests

Pull Requests were created through the GitHub web interface and merged into the main branch.

Verify Merge History
Shell
1
git log --oneline --graph --all
Show more lines
Verify Repository Status
Shell
1
git status
Show more lines

Output:

Plain Text
1
On branch main
2
Your branch is up to date with 'origin/main'.
3
 
4
nothing to commit, working tree clean
Show more lines
Evidence Collected

The following screenshots were captured as evidence of the GitFlow process:

Repository contents
Feature branches created
Commit history
GitFlow commit graph
Pull Request 1 merged
Pull Request 2 merged
Pull Requests overview page
Final clean repository status
Conclusion

This project successfully demonstrates the GitFlow workflow by creating feature branches, implementing changes, committing code, creating Pull Requests, merging changes into the main branch, and maintaining a clean repository state throughout the development process.
