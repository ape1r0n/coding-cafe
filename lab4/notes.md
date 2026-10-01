# Lab 4: Git and GitHub

### Q1. What is the difference between using `--global` and not using it?

`--global` applies the configuration to all repositories for my user account. Without it, the setting applies only to the current repository.

### Q2. What is the purpose of the `.git` directory?

The `.git` directory is hidden and stores repository information, configuration, and version history.

### Q3. How many untracked files did Git show, and what does the `.venv` folder contain?

Git showed 3 untracked entries: `.DS_Store`, `README.md`, and `week02/`. The `.venv` folder contains files related to the Python virtual environment.

### Q4. What changed after creating the `.gitignore` file?

The ignored virtual environment and system files disappeared from the untracked list.

### Q5. Why should `.gitignore` be committed?

`.gitignore` should be committed because it tells Git which files to ignore, ensuring that unnecessary files are not included in the repository.

### Q6. What happened after running `git add README.md`?

README.md moved from Untracked files to Changes to be committed. It was moved from the working directory to the staging area.

### Q7. What did Git report after the first commit?

Git created a commit and reported 4 files changed, with 92 insertions.

### Q8. What do the first seven characters in the commit output represent?

The first seven characters are the abbreviated commit hash. They identify the commit.

### Q9. What is the basic Git workflow?

The four steps are edit, stage, commit, and repeat.

### Q10. What is the purpose of README.md?

README.md is the standard introductory file displayed on a repository's front page. It provides information about the project and its contents.

### Q11. What does `gh auth login` do?

`gh auth login` authenticates GitHub CLI and stores authentication credentials so GitHub can authorize future operations.

### Q12. Why does README.md appear on the GitHub repository's front page?

README.md appears on the front page because GitHub automatically renders it as the repository description.

### Q13. Does pushing change local commit history?

Pushing does not change local commit history. It copies commits to the remote repository.

### Q14. What is the difference between a private repository and a repository that does not exist on GitHub?

A private repository exists on GitHub but is accessible only to authorized people. A repository that does not exist on GitHub has no hosted repository to access.
