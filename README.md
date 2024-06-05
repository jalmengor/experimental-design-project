# experimental-design-project

## Quick setup — if you’ve done this kind of thing before

```
git clone git@github.com:jalmengor/experimental-design-project.git
```

…or create a new repository on the command line

```
echo "# experimental-design-project" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:jalmengor/experimental-design-project.git
git push -u origin main
```

…or push an existing repository from the command line
```
git remote add origin git@github.com:jalmengor/experimental-design-project.git
git branch -M main
git push -u origin main
```

## Checking and switching the conda environments

To list the currently installed environments just type `conda env list`

Switching between environments works as simply as typing `conda activate [NAME]` and if done with it deactivating it (and going back to the base environment) with `conda deactivate`.