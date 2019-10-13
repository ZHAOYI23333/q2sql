1. pull repository from github: `git clone <url copied from clone or download button>`

2. checkout a branch:  `git checkout <branch_name>`

3. create new branch from old one: `git checkout -b <new_branch> <old_branch>`

4. Add changes and commit (update changes to branch storage): `git add --all` and `git commit -m <any message about the commit>`

5. Receive update of branch from remote branch: `git pull <remote_name> <remote_branch>`
*remote_name means name of remote repository, by default `origin` for repository created by `git clone ...` command in 1.*
6. Push local update to remote repository: at current branch call `git push <remote_name> <remote_branch>`
*remote_branch means branch name in remote repository, i.e. `dev` in this reposity*
7. initialize empty local repository: `git init`
