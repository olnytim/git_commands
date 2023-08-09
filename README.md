## Git Basics 😎

Hey there! 👋 Git is a fantastic tool for collaborating with your team on code projects 🤝 Here's a beginner-friendly guide on how to work with Git like a pro 🚀

### Setting Up

1. **Install Git**: If you haven't already, install Git on your machine. You can download it from [here](https://git-scm.com/downloads).

2. **Configure User Info**: Set your name and email, so your commits are tagged with your identity.
   ```shell
   git config --global user.name "Your Name"
   git config --global user.email "your@email.com"
   ```

### Creating a Repository

3. **Initialize a Repository**: Create a new folder for your project and turn it into a Git repository.
   ```shell
   git init
   ```

### Working on Your Project

4. **Add Files**: Add files to the staging area before committing changes.
   ```shell
   git add file1.js file2.css
   ```

5. **Commit Changes**: Save staged changes with a meaningful message.
   ```shell
   git commit -m "Add awesome feature"
   ```

6. **Stash Changes**: Temporarily save changes that are not ready to be committed, allowing you to switch branches or pull changes without losing work.
   ```shell
   git stash
   ```

7. **Reset Changes**: Unstage changes from the staging area.
   ```shell
   git reset file1.js
   ```

8. **Revert Commits**: Create a new commit that undoes the changes introduced by a specific commit.
   ```shell
   git revert <commit_hash>
   ```

9. **Push with Force**: Push your changes to a remote branch and overwrite history (use with caution).
   ```shell
   git push origin new-feature --force
   ```

10. **Amend Commit**: Modify the most recent commit's message or add more changes to it.
    ```shell
    git commit --amend
    ```

### Collaborating with Your Team

11. **Clone a Repository**: Get a copy of a remote repository on your machine.
    ```shell
    git clone <repository_url>
    ```

12. **Branching**: Create a new branch to work on features without affecting the main code.
    ```shell
    git checkout -b new-feature
    ```

13. **Switch Branches**: Move between different branches.
    ```shell
    git checkout main
    ```

14. **Pull Changes**: Update your local repository with remote changes.
    ```shell
    git pull origin main
    ```

15. **Push Changes**: Share your local changes with the team.
    ```shell
    git push origin new-feature
    ```

16. **Merge Branches**: Combine your changes from one branch into another.
    ```shell
    git checkout main
    git merge new-feature
    ```

17. **Resolve Conflicts**: If two branches have conflicting changes, resolve them manually.

### Keeping Things Organized

18. **View Status**: See the status of your working directory.
    ```shell
    git status
    ```

19. **View History**: Check the commit history.
    ```shell
    git log
    ```

20. **Discard Changes**: Throw away changes in your working directory.
    ```shell
    git checkout -- file.js
    ```

### Remote Collaboration

21. **Add Remote**: Connect your local repository to a remote server.
    ```shell
    git remote add origin <repository_url>
    ```

22. **Create Pull Request**: Propose your changes to be merged into the main codebase.
    - Push your branch to the remote repository.
    - Create a pull request through the repository's interface (e.g., GitHub, GitLab).

23. **Review Pull Request**: Collaborators review, comment, and suggest changes before merging.

24. **Merge Pull Request**: Once approved, merge your changes into the main branch.

25. **Fetch Remote Changes**: Get the latest changes from the remote repository.
    ```shell
    git fetch origin
    ```

Remember, Git is all about collaboration and version control. Don't hesitate to ask for help and keep practicing 🤗 Happy coding! 🎉
