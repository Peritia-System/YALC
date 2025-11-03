# 03_Packagemanage.md

## DNF — The Linux Equivalent of an Installer

If you’re coming from Windows, you’re probably used to downloading **.exe** files to install programs. You find a setup file, double-click it, and the installer handles everything — copying files, creating shortcuts, and sometimes adding entries to the Start Menu or registry.

Linux can do all that too — but in a much cleaner and more controlled way. Instead of downloading random **.exe** files from different websites, Linux uses **package managers** to install and manage software.

On Fedora (and similar distributions like RHEL or CentOS), the package manager is called **DNF** (short for *Dandified YUM*).

---

## What DNF Does

Think of **DNF** as your system’s built-in **app store and installer** combined.
It can:

* Install software
* Update existing packages
* Remove programs you don’t need
* Automatically handle dependencies (extra packages that your software needs to run)

You don’t have to browse the web for downloads — everything comes from **trusted repositories** (official servers maintained by your Linux distribution).

---

## Common Commands

Here are a few examples that mirror what you might do on Windows.

### 1. Installing Software

**Windows analogy:** You’d download and run `setup.exe`.
**Linux equivalent:**

```bash
sudo dnf install fastfetch
```

This command automatically finds, downloads, and installs fastfetch and anything it depends on.

---

### 2. Removing Software

**Windows analogy:** You’d go to “Add or Remove Programs” and uninstall it.
**Linux equivalent:**

```bash
sudo dnf remove fastfetch
```

This completely removes fastfetch and cleans up related files.

---

### 3. Updating Software

**Windows analogy:** You might run Windows Update or update each app manually.
**Linux equivalent:**

```bash
sudo dnf update
```

This checks all your installed packages and updates them to the latest version available in the repositories.

---

### 4. Searching for Packages

**Windows analogy:** Searching for an installer online.
**Linux equivalent:**

```bash
dnf search vlc
```

This searches the repositories for anything related to VLC — you can then install it directly.

---

### 5. Listing Installed Packages

If you want to see what’s installed:

```bash
dnf list installed
```



---

## Summary

| Task                | Windows (.exe) Way         | Linux (DNF) Way            |
| ------------------- | -------------------------- | -------------------------- |
| Install a program   | Download `.exe`, run setup | `sudo dnf install program` |
| Uninstall a program | Use “Add/Remove Programs”  | `sudo dnf remove program`  |
| Update programs     | Manual or Windows Update   | `sudo dnf update`          |
