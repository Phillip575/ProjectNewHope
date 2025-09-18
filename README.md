NEVER PUSH TO THE MAIN BRANCH!!!
----> SUBMIT PULL REQUEST TO A DIFFERENT BRANCH!

1. Clone the repository

First, copy the repo from GitHub onto your computer:

git clone https://github.com/Phillip575/ProjectNewHope.git
cd ProjectNewHope

2. Create a new branch

Never edit directly on main. Always make a new branch for your feature or fix:

git checkout -b your-branch-name


 Examples:

git checkout -b login-page

git checkout -b fix-navbar

git checkout -b update-readme

3. Make your changes

Edit the files you need.

Save your changes.

Check what changed:

git status

4. Stage and commit your work
git add .
git commit -m "Describe what you changed"

5. Push your branch to GitHub
git push origin your-branch-name

6. Create a Pull Request (PR)

Go to the repo page on GitHub: ProjectNewHope.

GitHub will show a button like: “Compare & pull request”. Click it.

Add a short description of your changes.

Submit the Pull Request.

7. Wait for approval

(repo owner) reviews the Pull Request.

If changes are good, it gets merged into main.

If changes need updates, Phillip will add comments and you can edit your branch, commit again, and push — the PR will update automatically.

**Rules for main (important)**

main is protected.

Nobody pushes directly to main.

All changes must go through Pull Requests.

This keeps the project safe and ensures all changes get approved first.

 That’s it! Follow this every time you contribute.
