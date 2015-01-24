# Clients: easy mode for Git

github for mac, gitx https://rowanj.github.io/gitx/

`gitk` (just type it inside a repo) on windows

# Reverting mistakes

```shell
git checkout
git reset # to roll back a branch
git revert
git reflog
```

# Working with Git branches and merging 

1. Start a repo with an html
2. put on github
3. bryce checks out branch
4. bryce adds more text
5. somebody off-screen makes a pull request 1 with fixed indentation
6. bryce makes pull request 2 with more content
7. bryce merges pull request 1
8. bryce’s pull request 2 can’t be merged
9. `git fetch`
10. `git merge origin/master`
11. fix branch errors
12. `git commit`

also see https://help.github.com/articles/resolving-a-merge-conflict-from-the-command-line/ 

# Stashing 

yes
