# Git Remote
When working with git a **remote**  is any git repository is not on the machine you're working on. 

Take GitHub for example. While get is the technology that allows you to create local repositorys, GitHUb is the site that will host your remote repositories. Once stored remotely, you can brig that repository back down or share it with others. 

**Note**: While repositories (local and remote) are related and track the same project, they can have different states if changes are not shared between the two.

### Adding a Remote
A remote can be added with the `git remote add` command, followed by the name and location of the remote. The anme is a local remote, meaning it doesn't impact the actual remote whatsoever.
```
git remote add orgin https://github.com/ElevenFifityAcadamy/GitFundamentals.git
```

### Removing a Remote
A remote canbe added with the `git remote remove` command, followed by the name of the 
```
git remote remove orgin
```
## Resources 

- [Git Remote Documentation](https://git-scm.com/docs/git-remote)

---
[Return to home](../README.md)
