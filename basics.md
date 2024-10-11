# basic commands & concepts

git status

git log HEAD..origin/main

git diff

git log ..origin/main

git fetch

git commit

git pull

git push

git branch

git checkout

HEAD/head detached HEADS

How to manage updating local from remote

1. **Fetch Remote Changes**: Use `git fetch origin` to update your local repository with the latest changes from the remote without merging them [1](https://git-scm.com/book/en/v2/Git-Branching-Remote-Branches) [2](https://docs.github.com/en/get-started/using-git/getting-changes-from-a-remote-repository).

2. **Merge Remote Changes**: Merge the fetched changes into your local branch using `git merge origin/main` (replace `main` with your branch name) [3](https://docs.github.com/en/get-started/using-git/getting-changes-from-a-remote-repository).

3. **Resolve Conflicts**: If there are conflicts, resolve them manually, then commit the changes.

4. **Push Local Changes**: Finally, push your local commits to the remote repository using `git push origin main`[4](https://git-scm.com/book/ms/v2/Git-Basics-Working-with-Remotes) [4](https://www.varonis.com/blog/how-to-merge-in-git)
