## Initiate your notes
If you will start from scratch, you have to create your notes repository. If you have files already or if you will create them.
```bash
mkdir MyNotes
cd MyNotes
touch note1 note2 note3
cd ..
```
This if you don't have your notes folder, if you have it or you have already create the folder, you now have to initiate your git repo:
### Initiating Git Repo
>Make sure that you are in the parent directory that contains directories you want to add in the repo
```bash
git init
git add MyNotes
git commit -m "First Commit of MyNotes Repo"
git branch -M main
```
Now you have created the repo with only one branch named `master`, then we will push it GitHub
### Push to GitHub
- Go to GitHub and create a repo with the same repo name
- Go to code, and get the repo URL
```bash
git remote add origin https://github.com/ar4x0/Note.git
git push -u origin main
```

