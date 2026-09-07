## Git commands

```powershell
git
```

Displays Git's common commands and general help.

```powershell
git branch -a
```

Lists all local and remote branches. The local `main` branch is checked out,
and the remote branches include `origin/main` and `origin/DevSanz`.

```powershell
git branch group-04
```

Creates a local branch named `group-04`.

```powershell
git checkout group-04
```

Switches to the `group-04` branch.

```powershell
git log
```

Displays the repository's commit history.

```powershell
git remote -v
```

Displays the remote repository URLs. The `origin` remote is
`https://github.com/ICT-Robotics26/lab1.git` for fetching and pushing.
