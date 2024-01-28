# 03.Git.Hosting 
 
## Homework Assignment 1

### Points 1-3

#### GitHub link:
[https://github.com/ussnorma/Git.Hosting.03]
#### GitLab link:
[https://gitlab.com/ussnorma/git.hosting.03]

```bash
git init
git branch -M main
git add --all
git commit -m "first commit"
git remote add github-origin git@github.com:ussnorma/Git.Hosting.03.git
git remote add gitlab-origin git@gitlab.com:ussnorma/git.hosting.03.git
git push -u github-origin main
git push -uf gitlab-origin main
```