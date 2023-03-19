# ZenAyush
Hello, today i am learning git from Harry Bhai videos.

## Git Commands

Use these commands to use git.

---

The "git status" command is used to show the current status of your Git repository. It will show you which files are staged for commit, which files have been modified but not yet staged, and which files are untracked.

```bash
git status
```

---

The "git add ." command is used to stage all changes in the current directory and its subdirectories for commit. When you make changes to files in your local Git repository, those changes are considered "unstaged" until you use the "git add" command to stage them. Staging changes allows you to group related changes together before committing them to the repository.

```bash
git add .
```

---

The "git commit -m" command is used to create a new commit in your Git repository with a commit message. When you make changes to files in your local Git repository, you can use the "git add" command to stage those changes, and then use the "git commit -m" command to create a new commit with a message that describes the changes you made.

```bash
git commit -m "a commit msg"
```

---

The "git push -u origin master" command is used to push the changes you made in your local Git repository to the remote repository on the "master" branch. The "-u" flag is used to set the upstream branch for the current branch. This means that in the future, when you run the "git push" command without specifying a branch, Git will automatically push changes to the upstream branch (in this case, "origin master").

```bash
git push -u origin master
```

---

The "git remote set-url origin" command is used to change the URL of the remote repository named "origin". In this specific case, the command is used to change the URL of the "origin" remote repository to a new repository located at git@github.com:username/new-repo.git.

```bash
git remote set-url origin git@github.com:username/new-repo.git
```

---

The "git remote -v" command is used to show a list of the remote repositories associated with your local Git repository. It will show the name of each remote repository (usually "origin"), along with its URL.

```bash
git remote -v
```
