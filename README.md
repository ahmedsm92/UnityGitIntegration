# Unity and Github Integration

This repository was made to explain how to use Git and Git LFS with Unity projects, especially projects that contain large files, to be able to use Github normally through the Git Bash terminal.

First, you have to move these two files which are uploaded to the repo local destination:
- .gitattributes
- .gitignore

Since they do contain shortcuts for the types of files that are usually used in LFS.

Move the files to the directory which you want to initiate the repo in.

Write the following commands to initiate the repository, choose the branch name and commit the changes:

```
 git lfs install
 
 git init

 git lfs track "*.psd"
 
 Write the following command to identify the URL of the repository created in your account:
```
 git remote add origin [REPO_URL]
 ```
 git branch -M main
```

Write the following command to add the recently added files to the repository:
```
 git add .
 ```
 To commit to the previously selected branch:
 ```
  git commit -m "initial commit"
```
 
Write the following command to push to the chosen branch:
```
 git push origin main
 ```
 




