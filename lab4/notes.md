# Lab 4: Git & GitHub

1. `--global` saves the name and email for Git to use across all repositories for my user account. Without it, the setting applies only to the current repository.

2. `ls -a` also shows the hidden `.git` directory. It contains Git's local database and settings, including the commit history and references that let Git manage the repository.

3. Before adding `.gitignore`, Git would offer the files and folders in the coding-cafe folder that are not ignored. In my folder there are about 8 files, plus the two week folders; the notebooks and lab files are course work, while the archive is a downloaded dataset rather than code I wrote.

4. After adding `.gitignore`, files in `.venv/`, Python cache folders, `.pyc` files and `.DS_Store` no longer appear as untracked items. Other course files remain visible.

5. `.gitignore` should be committed. It tells Git and anyone who clones the project which generated or machine-specific files to leave out, so the same clean setup is used by everyone.

6. `README.md` moved from “Untracked files” to “Changes to be committed.” Adding it staged the file: it moved from the working directory into Git's staging area, ready for a commit.

7. Git's commit output reports the commit ID, author, message, and a summary of files changed and insertions or deletions. [After your first commit, replace this sentence with the exact “X files changed” count Git printed.]

8. The first seven characters are the short form of the commit's hash (object ID). They identify that commit so it can be referred to without typing the full hash.

9. The four steps are edit a file, check the change, stage it, and commit it. The cycle saves each finished change as a point in the project history.

10. `README.md` is the standard first page for a project. GitHub displays it on the repository front page, so it gives visitors a quick introduction and explains what the folders contain.

11. `gh auth login` signs the GitHub CLI in and stores an authentication token on the computer. Git can use that saved login for HTTPS pushes, so it does not ask for the account password each time.

12. GitHub shows `README.md` on the repository front page, formatted as Markdown. It uses that file by convention as the project introduction.

13. Pushing does not change my local commit history. It copies commits that already exist locally to GitHub; `git log --oneline` should show the same commits afterward.

14. A private repository exists on GitHub, but only its owner and invited collaborators can see it. If no repository exists, there is no hosted project page or remote history to access at all.
