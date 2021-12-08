#git remote

When working with git, a **remote** is any git repository tht is not on the machine you're working on. The counterpart to this is  **local** , or the machine tht is being developed on. 

Take GitHub for example. Whiel git is the technolody that allows you to creat local repositories, gitHub is the technology that allows you to creat local repositories, GitHub is the site that will host your repositories. Once stored remotely, you can bring that repository back down or share it with others.


**Note**: While the repositories  (local and remote) are related and track the #same project, they can have diffrent states if changes are not shared between the two.

### Adding a remote

A remote can be added with the `git remote add` command, followed by the name and location of the remote.

the name is a local name, meaning it's your lable and does not impact the actual remote whatsoever.
``
git remote remove origin
```


## Resources
[Git Remote Documentation](https:.//git-scm.com/docs/git-remote)

-----

## Git Commands
- [git config](./commands/config.md)
- [git init](./commands/Init.md)
- [git add](./commands/Add.md)
- [git commit](./commands/Commit.md)
- [git remote](./commands.Remote.md)
