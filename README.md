Core Version Control and GitHub Terminology

Version control is a process to document changes to a file or set of files over time, which allows for history tracking, reverting to a previous version, and collaboration. Git is a version control system that is decentralized and enables multiple contributors to collaborate in real-time on a project. GitHub is a cloud-based service that hosts Git repositories, facilitating collaboration, issue tracking, and code review.

Version control preserves project integrity via conflict avoidance, a history of all changes, and multiple programmers working on different features without disrupting each other's work.

Creating a New Repository on GitHub

Log in to GitHub – If you don’t have a GitHub account, create one.

Create a new repository – Click on “New” in “Repositories.”

Enter repository details - Provide a name, optional description, and either a public or private repository.

Start with a README - Optional but strongly recommended.

Include a .gitignore file - This is useful in ignoring unnecessary files.

Choose a license – Helps in clarifying usage rights.

Click on "Create repository" - Your repository is now available.

Key choices are public vs. private repositories, selection of a proper license, and whether a README file is required.

The Importance of a README File

A README file is important in a GitHub repository as it provides a summary of a project. A good README should include:

Project name and description

Installation and use instructions

Contribution guidelines

License information

Writer and Contact Details

Badges (where appropriate, for CI/CD or coverage status)

A good README enables collaboration through making the project understandable and accessible to everyone who contributes.

Public vs. Private Repositories

Emphas

Public Repository

Private Repository

Visibility

Available to everyone

Limited access

Collabor

Anyone can fork and contribute

Reserved for invited partners

Security

Shown to the public

Respects privacy.

Optimal for

Open-source projects

Confidential or proprietary projects

Public repositories encourage community contributions, and private repositories provide you with control and privacy.

Making Your First Commit

Clone a repository: git clone <repo-url>

Go to the repository: cd <repo-name>

Create or modify files

Stage all changes: git add. 

Add changes to commit history: git add. 

Push to GitHub: git push origin main

Commits are project snapshots and serve to give a history for version control and tracking changes.

Branching in Git
===============

Developers can build features in isolation without affecting the main codebase.

Let's create a branch called feature-branch.

Switch to branch: git checkout feature-branch

Make changes and commit

Merge the branch: git checkout main → git merge feature-branch

Publish updates: git push origin main

Parallel development, experimentation, and structured collaboration all rely on branching.

Role of Pull Requests in Collaboration

A pull request is a request to merge changes in one branch into another.

Steps to create a pull request:

Push your branch to GitHub

Open a pull request on GitHub

Review and discuss changes

Approve and merge pull request

PRs enable code reviews, maintain code quality, and allow for controlled integration.

Forking vs. Cl

Emphas

Fork

Cloning

Purpose

Creates a copy of a repository with a different user.

Duplicates a repository to a machine.

Use Case

Engaging in an outside project

Working with a Local Repository

Relationship

Independent copy

Attached to the original repository

Forking is used for open-source contributions, and cloning is used for local development.

Issues and Project Boards

GitHub Issues and Project Boards help to manage tasks and track progress.

Issues: Used for bug tracking, feature requests, and discussion.

Project Boards: Utilize Kanban-type boards to manage tasks.

Example:

Problem: "Resolve login bug (#42)"

Project Board: "Sprint 1 - Work in Progress"

They promote collaboration and coordination in projects.

Shared best practices and challenges

Challenges

Merge conflicts

Understanding Git commands

Keeping commits meaningful

Managing Large Repositories Efficiently

Best Practices

Use descriptive commit messages

Implement a branching strategy (e.g., GitFlow)

Periodically pull updates before you push

Review and test code before merging Document workflows and contributions in the README
