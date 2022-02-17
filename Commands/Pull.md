# git pull

Similar to a [git push](./Push.md), a `git pull  will interact with a remote repository. Only this time it will **pull** the changes it does not have from the remote down to the local repository

This means any commits made that are on the remote repository will be pulled down and added to the local repository.

Thi can be done by adding the remote name and banch name:
```
git pull origin main
```

If there is any upstream connection estrablished, you can us `git pull` without specifying a remote or branch.

## Resources 

- [Git Pull Documentation](https://git-scm/docs/got-pull)

---

[Back home](../README.md)
