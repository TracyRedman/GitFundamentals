# git commit

The command `git commit` will tkae all tracked changes (items added with[git add](./ADD.md)) and package them upin what is called a commit.

Commits come with commit messages that are requied for each commit. You add a message to a commit command by useing the `-m` flag followed bt a message in quotes.

A commit message _can_ be anything, but nest practice dictates taht you should use that message to indicate the changes included in the commit.

For example, if we have an appliceation we're working on where we just builtout the ability to register new accounts, then you might have some variations of the following:

 - [git commit](./Commands/Commit.md)
 
```
git add .
git commit -m "Added register functionality"
```

Then when viewing the history of a git repository, you can pinpoint where the registration functionality was added.

## Resources

-[Git Commit Documentation](https://git-scm.com/docs/git-commit)

---

[Back to home](../README.md)
