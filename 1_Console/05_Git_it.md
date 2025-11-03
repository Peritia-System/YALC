# Introduction to Git

Now that you’ve gotten comfortable with the terminal, it’s time to learn about one of the most powerful tools you’ll ever use as a developer: **Git**.

If you’ve ever worked on a project, made changes, broken something, and wished you could go back to an earlier version — Git is exactly what you need.

---

## What Is Git?

**Git** is a **version control system**.
That means it helps you **track changes to files**, **save versions of your work**, and **collaborate with others** without losing progress.

Think of it like a **save system for your code** — or for Windows users, imagine it as a supercharged “Undo” history that never goes away.

Instead of manually copying your project folder into “MyProject_v2” or “FinalVersion_REALLY_FINAL”, Git keeps a full history of every change and lets you go back to any point in time.

---

## Why Use Git?

* **Track changes** – You can see what changed, when, and by whom.
* **Revert mistakes** – Go back to a previous version if something breaks.
* **Collaborate easily** – Multiple people can work on the same files without stepping on each other’s toes.
* **Backup your work** – By pushing your code to a remote service (like GitHub or GitLab), you have a cloud backup of your project.

---

## Git vs. GitHub

A common confusion:

* **Git** is the **tool** on your computer that tracks changes.
* **GitHub** (or GitLab, Bitbucket, etc.) is an **online platform** where you can store and share your Git repositories.

You can absolutely use Git without GitHub — it just stays local on your machine.

---

## Basic Git Workflow

Here’s a simplified overview of how Git works:

1. **Initialize a repository** – Tell Git to start tracking your project.

   ```bash
   git init
   ```

2. **Check what’s going on** – See what’s changed since your last save.

   ```bash
   git status
   ```

3. **Add changes** – Select which files you want to save.

   ```bash
   git add .
   ```

   (The `.` means “add everything”.)

4. **Commit your changes** – Save a snapshot of your project.

   ```bash
   git commit -m "Describe what you changed"
   ```

5. **Connect to a remote repository** (optional, but common).

   ```bash
   git remote add origin https://github.com/username/repo.git
   ```

6. **Upload (push) your changes** to GitHub or another service.

   ```bash
   git push -u origin main
   ```

7. **Pull updates** from others if you’re collaborating.

   ```bash
   git pull
   ```

---

## Common Git Commands Summary

| Task                   | Command                       | Description                        |
| ---------------------- | ----------------------------- | ---------------------------------- |
| Start a new repository | `git init`                    | Create a new Git project           |
| Check status           | `git status`                  | Show changes not yet committed     |
| Add files              | `git add <file>`              | Stage a file for the next commit   |
| Commit changes         | `git commit -m "message"`     | Save a version of your work        |
| View history           | `git log`                     | Show all previous commits          |
| Link remote repo       | `git remote add origin <url>` | Connect your local repo to GitHub  |
| Upload changes         | `git push`                    | Send your commits to GitHub        |
| Download changes       | `git pull`                    | Get the latest updates from GitHub |

---

## Your First Step

To start using Git, install it with:

```bash
sudo dnf install git
```

Then set up your user info so Git knows who you are:

```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```

You’re now ready to create your first repository and start tracking your own work!


## Optional
[Githubs introduction to git](https://docs.github.com/en/get-started/start-your-journey/about-github-and-git)  
[Very simple visual Demonstration](https://www.youtube.com/watch?v=hwP7WQkmECE&t=9s)