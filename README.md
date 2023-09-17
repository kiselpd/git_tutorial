# GIT tutorial for new user

## ***1. Installing git***
```
   sudo apt install git
```

## ***2. Creating a repository***
```
    mkdir "name of your new folder"
    cd "name of your new folder"
    git init
```

**If you want to delete repository:**
```
    rm -rf .git
```

**Check status of repository:**
```
    git status
```

## ***3. Prepare files for saving***
```
    git add "file's name"
```
***or for add all files:***
```
    git add -All

    git add .
```

## ***4. Commit execution***
```
    git commit -m "Your description of commit"
```
**If you want to check commit history:**
```
    git log
```

## ***5. Synchronizing git and GitHub***
* Create new repository on github.com
* Copy URL of your repository
* Synchronizing git directory and GitHub repository:
```
    git add remote origin "HTTPS of your repository"
```

## ***6. Pushing commit on GitHub***
```
    git add .
    git commit -m "Initial commit"
    git push
```


### __Thank you for watching this tutorial!__
[![Typing SVG](https://readme-typing-svg.herokuapp.com?color=%2336BCF7&lines=Your,+kiselpd!)](https://git.io/typing-svg)