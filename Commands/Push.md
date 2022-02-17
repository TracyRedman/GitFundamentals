# git push

When you have a [remote](./Remote.md) set up you'll need to begin to move [commits](./Commit.md) to the remote. Thie can be down with the command `git push`.

You can attach a name and a branch name to your command to specify where you're pushing to.

```
git push origin main
```

This command will push the **main** branch to the remote called **origin**. This means any commits that are in your local will be **pushed** to the remote.

## Upstream Tracking

Instead of including the name of the remote and the branch you're on every time, you can set local branched to track an upstream branch. THis means you can tell the branch to push to its assigned upstream remote branch by using the comman `git push`.

Before doing so, you'll use the `-u` or `--set-upstream` flag. THis can be done on any `git push`.

```
git push -u origin main
```

After this command is used, you can just use `git push` and it will function the same way.

## Resources

 - [Git Push Documentation](https://git-scm/docs/git-push)

 ---

 [Back to home](./README.MD)

 