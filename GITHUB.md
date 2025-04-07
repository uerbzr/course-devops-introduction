# Git/Github Introduction

- Git is a version control system created by Linuis Torvalds (Linux Guy!)
- Github is a web-based platform for version control and collaboration.
- It uses Git as its underlying version control system.
- It allows developers to work together on projects, track changes, and manage code repositories.

## Basic Concepts

**Repository**: A storage space for your project, which contains all the files and their revision history.

**Commit**: A snapshot of changes made to files in the repository.

**Branch**: A parallel version of the repository where you can make changes without
affecting the main codebase.

![Branch](branch.jpeg)

**Fork**: Take someone elses project from their account and put it in yours so you can improve it

**Pull Request**: A request to merge changes from one project into another, sort of opposite of the Fork so you can send back your updates/improvements.

## Installation

- Install Gitbash
- Future you - consider SSH keys for github [here](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

## Workshop

- Create a repo with [repo.new](http://repo.new)
- Clone it with `git clone https://github.com/uerbzr/nameofrepo`
- CD into directory with `cd nameofrepo`
- Now create some files / a project / whatever you want
  - we can create a quick C# app with some tests
- Push Changes with:

  - `git add .`
  - `git commit -m "first commit"`
  - `git push`

- Add a workflow to run tests

```json

```

## Useful Commands

-- `dotnet new classlib --name workshop.calculator`

-- `dotnet new nunit --name workshop.tests`

-- `dotnet sln add **/*.csproj `

-- `start devenv workshop.sln`

## Resources

- [Git Download](https://git-scm.com/downloads/win)
- [Github Cheatsheet](https://education.github.com/git-cheat-sheet-education.pdf)
- [Github Documentation](https://docs.github.com/)
- [SSH Setup](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

[Return](https://github.com/uerbzr/course-devops-introduction)
