# Outlier-Org Test Task

1. Clone the repository:
   git clone https://github.com/outlier-org/challenge-git.git
   cd challenge-git
2. fetch Pull requests :
    git fetch origin pull/3/head:feat/add-base64-endpoint
    git fetch origin pull/4/head:feat/add-user-agent-endpoint
3. git checkout master
4. git rebase feat/add-base64-endpoint
5. Resolve conflicts if any during the rebase process.
6. git rebase feat/add-user-agent-endpoint
7. Resolve conflicts if any during this rebase process.
8. Push the changes to your new repository
    git remote set-url origin <github _url>
    git push origin master
