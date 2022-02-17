# git remote

When working with git, a **remote** is an git repository that is not on the machine you're working on.  The counterpart to this is **local**, or the machine that is being developed on.

Take GitHub for example. While git is the technology that allows you to create local repositories, GitHub is the site that will host your remote repositories, Once stored remotely, you can bring that repostiory back down or share it with others.

**Note**: While the repositories (local and remote) are related and trach the same project, they can have different states if changes are not shared between the two.

### Adding a remote

A remote can be added with the `git remote add` command, followed by the name and location of the remote.

## Git Commands
- [git config ](./Commands/Config)
- [git init](./Commands/Init.md)
- [git add](./Commands/Add.md)
- [git commit](./Commands/Commit.md)
- [git remote](./Commands/Remote.md)

The name is a local name, meaning its you lavel and does not impact the actual remore whatsoever.

```
git remote add origin https://github.come/elevenfiftyAcademt/GitFundamentals.git
```

### Removing a remote

A remote can be removed with the `git remote remove` command, followed by the name of the remote.

```
git remote remove origin
```

## Resources 

 - [Git Remote Documentation](https://git-scm.docs/git-remote)

 ---

 [Back to home](../README.md)

