Topics:
    - what is git and github (the basic concepts)
    - how to install git
    - how to use git
    - how to use github
    - how to use git and github together
    - how to contribute to open source projects
    - how to use git and github in a team

## What is Git and GitHub?
- **Git** is a distributed *version control system* that allows you to track changes in your code and collaborate with others.
- **GitHub** is a web-based platform that uses Git for version control and collaboration. It allows you to host your code, manage projects, and build software alongside millions of other developers.

## Who created Git and GitHub?
- **Git** was created by Linus Torvalds in 2005.
- **GitHub** was created by Tom Preston-Werner, Chris Wanstrath, and PJ Hyett in 2008.

## what was the first commit in GitHub?
- The first commit in GitHub was made by Tom Preston-Werner on February 10, 2008.


## history of version control systems
    https://tarynwritescode.hashnode.dev/a-history-of-version-control#heading-1960s

## what was the first repository in GitHub?
- The first repository in GitHub was created by Tom Preston-Werner on February 10, 2008.
link: 
    - [First commit](https://github.com/git/git/commit/e83c5163316f89bfbde7d9ab23ca2e25604af290)

## aqcuired by microsoft
- On June 4, 2018, Microsoft announced that it had reached an agreement to acquire GitHub for $7.5 billion. (~$8.65 billion in 2022)
---

## Git

Branches: Are simply lightweight movable pointers to commit objects. The default branch in Git is called master or main.

HEAD: A special reference that points to the current branch or directly to a commit. It represents the current snapshot your working directory is based on.

Staging Area: A file in the Git directory that stores information about what will go into your next commit. It’s sometimes referred to as the “index”, but it’s also common to refer to it as the staging area.

Repository: A directory where Git has been initialized to start version controlling your files. It’s the first step to making a repository. After using git init, a .git subdirectory will be created in the repository’s root directory. This subdirectory is where Git stores all of its metadata for the repository.

Working Directory: The files that you see in your computer’s file system. When you clone a repository, you will have a new directory created on your computer. This directory is called the working directory. It will contain all the files from the repository, and it will have a .git directory inside it, where all of the repository’s metadata is stored.

Commit: A snapshot of your repository. This is the way to save the state of your project. It is like saving a file in a word processor. You give it a message so that you remember what you did and why.

# Why git take a snapshot of the file instead of saving the changes?
- Git takes a snapshot of the file instead of saving the changes because it is faster and more efficient. It also allows you to work offline and have a complete history of your project.
## Speed
Retrieving Content: When Git needs to display or revert to a previous state, it does not have to calculate or apply a series of patches to arrive at a particular version; it simply retrieves the complete snapshot for that state. This can be much faster, especially when dealing with large repositories or when needing to access very old history.

Local Operations: In Git, the entire repository history is stored locally. This means operations like diff, log, revert, and many others are extremely fast, as Git does not need to contact a server to fetch the history of each file.





Resources:
    - [Download here](https://git-scm.com/)
    - [Git and GitHub for Beginners - Crash Course](https://www.youtube.com/watch?v=RGOj5yH7evk)
    - [GitHub Guides](https://guides.github.com/)
    - [GitHub Learning Lab](https://lab.github.com/)
    - [GitHub Desktop](https://desktop.github.com/)
    - [GitKraken](https://www.gitkraken.com/)
    - [Git Tower](https://www.git-tower.com/)
    - [GitLab](https://about.gitlab.com/)
    - [Bitbucket](https://bitbucket.org/)
    - [Git vs. GitHub](https://www.youtube.com/watch?v=1h9_cB9mPT8)
    - [Git vs. GitHub vs. GitLab](https://www.youtube.com/watch?v=U8GBXvdmHT4)
    - [Git vs. GitHub vs. Bitbucket](https://www.youtube.com/watch?v=ZK7dJ0VUZm8)
    - [Git vs. GitHub vs. GitLab vs. Bitbucket](https://www.youtube.com/watch?v=0fKg7e37bQE)
    - [Git vs. GitHub vs. GitLab vs. Bitbucket - Which is Better?](https://www.youtube.com/watch?v=0fKg7e37bQE)
    
---
