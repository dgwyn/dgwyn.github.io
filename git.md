### Making git branches

This is how to make a git branches. Substitute BRANCH-NAME with your desired
name.

```shell
git checkout-b BRANCH-NAME
```
 
Check that you are on the right branch. The branch you are on has an asterisk
next to it.

```shell
git branch
```

When you make a new branch, GitHub doesn't know about the branch. You have to
push the branch to GitHub.

```shell
git push -u origin BRANCH-NAME
```

After doing this command, you do not have do it again because the working area
has associated GitHub with the branch by the -u option. The benefit is you can
type git push without the arguments.


```shell
git push
```
