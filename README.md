# Git Assignment 3 - Repository

This repository is created for the Git Assignment 3, involving the setup of Git branches, committing files, and performing various operations locally and on GitHub.

## Table of Contents

- [Git Working Directory Setup](#git-working-directory-setup)
- [Commit Main.txt to Master](#commit-main.txt-to-master)
- [Commit Develop.txt, F1.txt, and F2.txt to Respective Branches](#commit-develop.txt-f1.txt-and-f2.txt-to-respective-branches)
- [Push Branches to GitHub](#push-branches-to-github)
- [Delete F2 Branch Locally](#delete-f2-branch-locally)
- [Delete F2 Branch on GitHub](#delete-f2-branch-on-github)

## Git Working Directory Setup

1. Create a new directory for the Git repository:

    ```bash
    mkdir git-assign3
    cd git-assign3
    ```

2. Initialize a Git repository:

    ```bash
    git init
    ```

3. Create branches: Develop, F1, and F2

    ```bash
    git branch Develop
    git branch F1
    git branch F2
    ```

4. Switch to the Develop branch:

    ```bash
    git checkout Develop
    ```

## Commit Main.txt to Master

1. Switch to the Master branch:

    ```bash
    git checkout master
    ```

2. Create and commit the `main.txt` file:

    ```bash
    echo "This is main.txt" > main.txt
    git add main.txt
    git commit -m "Add main.txt to master"
    ```

## Commit Develop.txt, F1.txt, and F2.txt to Respective Branches

1. Switch to the Develop branch:

    ```bash
    git checkout Develop
    ```

2. Create and commit the `develop.txt` file:

    ```bash
    echo "This is develop.txt" > develop.txt
    git add develop.txt
    git commit -m "Add develop.txt to Develop"
    ```

3. Switch to the F1 branch:

    ```bash
    git checkout F1
    ```

4. Create and commit the `f1.txt` file:

    ```bash
    echo "This is f1.txt" > f1.txt
    git add f1.txt
    git commit -m "Add f1.txt to F1"
    ```

5. Switch to the F2 branch:

    ```bash
    git checkout F2
    ```

6. Create and commit the `f2.txt` file:

    ```bash
    echo "This is f2.txt" > f2.txt
    git add f2.txt
    git commit -m "Add f2.txt to F2"
    ```

## Push Branches to GitHub

1. Create a new repository on GitHub.

2. Add the GitHub remote to your local repository:

    ```bash
    git remote add origin https://github.com/your-username/git-assign3.git
    ```

3. Push all branches to GitHub:

    ```bash
    git push -u origin --all
    ```

## Delete F2 Branch Locally

1. Switch to the Develop branch:

    ```bash
    git checkout Develop
    ```

2. Delete the F2 branch locally:

    ```bash
    git branch -d F2
    ```

## Delete F2 Branch on GitHub

1. Delete the F2 branch on GitHub:

    ```bash
    git push origin --delete F2
    ```

Feel free to customize this README.md with additional information or details specific to your assignment.
