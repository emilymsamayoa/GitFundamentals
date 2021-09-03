# Git Push
When you have a [remote](../remote.md) set up you'll need to begin to move [commits](../commit.md) to the remote. This can be done witht he command `git push`. 
You can attach a name and branch to your command to specify where you're pushing it to.
```
git push orgin main
```

This command will push the **main** branch to the remote called **orgin**. This means any commits in your local will be  **pushed** to the remote.

### Upstream Tracking
Instead of including the name of the remote and the branch yo're on every time, you can set local branches to track an upstream branch. This means ypu can thell the branch to push to its upstream remote branch by using the command `git push`.  Before doing so you will need to use a `-u` or `-set-upstream` flag. This can be done on any `git push`.
```
git push -u orgin main
```

## Resources
[Git Push Docuentation](https://git-scm.com/docs/git-push)

---
[Back to home](../README.md)