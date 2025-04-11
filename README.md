# draft
This shouldn't be public, this is my personal GitHub draft for clear structure and for me to be able to clone the GitHub repository for feature uses.


## How to Use the Private Template Repository
1. Start by cloning the private template repository to your local machine:

```bash
git clone https://github.com/TimothyLin8888/draft.git
cd your-private-template-repository
```
2. To prevent pushing the old commit history, remove the .git directory:
```bash
rm -rf .git
```

3. Reinitialize the repository with a new Git history:
```bash
git init
```

4. Go to GitHub and create a new repository for your new project:
```bash
Click on New to create a new repository.
Name the repository and set the appropriate settings (public or private).
```

5. Add the new repository as a remote:
```bash
git remote add origin https://github.com/your-username/new-repository.git
```

6. Add, commit, and push the files from the template repository to your newly created GitHub repository:
```bash
git add .
git commit -m "Initial commit based on template"
git push -u origin master
```
