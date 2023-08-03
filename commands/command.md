Certainly! Here are some common Git commands along with brief explanations:

1. **Initialize a new repository:**
```bash
git init
```
Initializes a new Git repository in the current directory.

2. **Clone a repository:**
```bash
git clone <repository-url>
```
Clones an existing remote repository to your local machine.

3. **Add files to staging area:**
```bash
git add <file1> <file2> ...
```
Adds specified files to the staging area to be committed.

4. **Commit changes:**
```bash
git commit -m "commit message"
```
Commits the staged changes with a descriptive commit message.

5. **View status:**
```bash
git status
```
Shows the current status of the repository, including modified files and untracked files.

6. **View commit history:**
```bash
git log
```
Displays the commit history with commit messages, authors, and timestamps.

7. **Create a new branch:**
```bash
git branch <branch-name>
```
Creates a new branch with the given name.

8. **Switch to a branch:**
```bash
git checkout <branch-name>
```
Switches to the specified branch.

9. **Merge branches:**
```bash
git merge <branch-name>
```
Merges the specified branch into the current branch.

10. **Pull changes from a remote repository:**
```bash
git pull
```
Pulls and merges changes from the remote repository to the current branch.

11. **Push changes to a remote repository:**
```bash
git push origin <branch-name>
```
Pushes local commits to the remote repository.

12. **View remote repositories:**
```bash
git remote -v
```
Shows a list of remote repositories associated with the current repository.

13. **Create and switch to a new branch in one step:**
```bash
git checkout -b <branch-name>
```
Creates a new branch and switches to it in one step.

14. **Discard changes in a file:**
```bash
git checkout -- <file>
```
Discards changes in a specific file and restores it to the last committed state.

15. **Undo the last commit and keep changes:**
```bash
git reset HEAD~1
```
Removes the last commit from history while keeping the changes in the working directory.

These are just a few of the most commonly used Git commands. Git has a wide range of functionalities, and you can explore more by checking out the official Git documentation or other Git tutorials.