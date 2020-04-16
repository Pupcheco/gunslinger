# Gunslinger

Developed with Unreal Engine 4. 

## Using Git + GitHub

- Please watch [this video](https://www.youtube.com/watch?v=FXMTHrLWFKQ) for 
Git + UE4 setup and usage.
- We are using a special `.gitignore` and `.gitattributes` scheme. Basically,
**we include only a specific set of files and ignore all irrelevant files.**
  - If you need to force add files, you should use PowerShell or Terminal
  on Windows or Mac/Linux respectively. Open the current folder in your shell
  (terminal) and use `git add -f <FILE1> <FILE2> ...`.

### Troubleshooting Git or GitHub

- Git is a [version control system (VCS)](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control).
We are using an extension to this to help manage large files (like art assets)
called Git Large File System (Git LFS or `git-lfs`).
GitHub is a cloud service to host *remote* Git repositories, and provides
additional features in addition to Git. 
  - This is why you should be wary when troubleshooting Git vs. GitHub issues.
  First, find if your issue is Git, git-lfs or GitHub related.
