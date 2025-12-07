# TECH-ED-SD023-Week-00

Git branches demo folder

##TIPS

- When we clone a repo to our local device, both projects are already connected --> when we push code from local to remote, the code knows where to go!

```zsh
git clone sshKey
```

- The cycle of git:

```zsh
git add .
```

or if a specific folder
:

```zsh
git add folderName
```

- Then, commit your changes:

```zsh
git commit -m "commit message"
```

- Then, push to GitHub:

```zsh
git push
```

- To check the state of git, you can get a report by using:

```zsh
git status
```

(!) This is about the local status of git; not the status of your online repo.

<!-- ----------------------- -->

GIT BRANCHES

- Branches should be used once per task
- Once a branch has been merged with main, you should **NEVER (EVER!)** use it again!
