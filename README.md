# Git basic
**1.1 Initialize a Git repository**\
`git init`\
**1.2 Checking the Status**\
`git status`\
**1.3 Adding Changes**\
Add file to the staging area\
`git add <file>`\
Adding All Changes\
`git add '*.extend'`\
Removing a file in staging area\
`git rm --cached <file>`\
**1.4 Committing**\
`git commit -m "A message describing changed"`\
**1.5 History**\
See what all the changes committed so far\
`git log`\
**1.6 Remote Repositories**\
Add a remote GitHub repository\
`git remote add <remote_name> <repository URL>`\
**1.7 Pushing Remotely**\
The `-u` tell Git to remember the parameters, so that next time can simply run `git push` and Git will know what to do.\
`git push -u <remote_name> <branch_name>`\
**1.8 Pulling Remotely**\
Pull down any new changes on GitHub repository\
`git pull <remote_name> <branch_name>`\
**1.9 Differences**\
Look different from last commit, using the `HEAD` pointer see diff of most recent commit
`git diff HEAD`\
See the changes just staged\
`git diff --staged`\
**1.10 Resetting the Stage***\
Unstaging files\
`git reset <file>`\
**1.11 Undo**\
Back (Remove) all the changes since the last commit\
`git checkout -- <target>`\
**1.12 Branching Out**\
`git branch <branch_name>`\
**1.13 Switching Branches**\
`git checkout <branch_name>`\
**1.14 Removing All the Things***\
`git rm '*.extend'`\
After removed all, need to commit changes\
`git commit -m 'A message descriping changed'`\
**1.15 Switching Back to master**\
After bug fix, need to switch back to the **master** branch so can copy (or **merge**) changes\
`git checkout master`\
**1.16 Preparing to Merge**\
`git merge <branch_name>`\
**1.17 Keeping Things Clean**\
Successful bugfix and merge. To do is clean up, to delete a branch
`git branch -d <branch_name>`\
**1.18 The Final Push**\
Last step. To push everything to remote repository, and done!\
`git push`\
Source: https://try.github.io \
Learning more about Git: https://git-scm.com/docs, https://git-scm.com/book/en/v2, https://help.github.com/, https://services.github.com/on-demand/downloads/github-git-cheat-sheet.pdf \
Tutorial: https://backlog.com/git-tutorial/, https://www.atlassian.com/git/tutorials
