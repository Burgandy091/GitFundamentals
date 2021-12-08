#git commit

the command `git commit ` will take all tracked changes
 (items added with [git add](./ADD.md)) and package them up in what is called commit.

commits come with commit messages that are required for each commit. You add a message tocommit command by using the `-m` flag followed by a message in quotes.

A commit message_can_ be anything, but best to practice dicates that you should use that message to indicate the changes included in the commit.

for example, if we have an application we're working on where we just built out the ability to register new accounts, then you might have some variation of the following:
-[git commit](./commands/commit.md)
```
git add . 
git commit -m      "added register functinonality"
`````
then when viewing the history of a git repository, you can pinpoint where the registration functionality was added.

## Resources

-[Git Commit Documentation](https://git-scm.com/docs/git-commit)

-----

[Back to home](../README.md)