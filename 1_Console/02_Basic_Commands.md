# Basic Commands

This section introduces some essential terminal commands to help you navigate, organize, and manage files in a Linux environment.

---

## Opening the Terminal

Before you begin, open your terminal.

On most systems, you can do this by pressing **Ctrl + Alt + T** or searching for **“Terminal”** in your applications menu.

---

## Existential Crisis

Get to know your current environment.

```bash
# Where am I?
pwd
```

Displays the current working directory.

```bash
# Who am I?
whoami
```

Shows your current username.

---

## File Manipulation and Viewing

Work with text files using simple commands.

```bash
# Create a new text file
touch notes.txt
```

```bash
# Edit the text file with a simple text editor
nano notes.txt
```

```bash
# View the contents of the file
cat notes.txt
```

---

## Organizing Files

Practice basic file organization.

```bash
# Create a new directory
mkdir Files
```

```bash
# Move all text files into the Files directory
mv *.txt Files/
```

```bash
# List the contents of Files
ls Files
```

---

## Cleanup

Remove unnecessary files and directories.

```bash
# Remove the Documents directory and its contents
rm -r Documents
```

```bash
# Create a folder called Delete
mkdir Delete
```

```bash
# Move into the Delete directory
cd Delete
```

```bash
# Create a file called Trash
touch Trash
```

```bash
# Copy the file and name it Trashier
cp Trash Trashier
```

```bash
# Move back to the parent directory
cd ..
```

```bash
# Remove the Delete folder (only works if it’s empty)
rmdir Delete
```

---

## Talk So You’re Not So Alone

The terminal doesn’t have to be silent. You can make it “talk” back to you using echo.

```
echo "Hello there!"
```

echo simply prints whatever you type after it — great for testing or adding small messages to scripts.


## Get Some Lore
Want to see what you’ve been doing?
Use the history command to look through your past commands — it’s like scrolling back through your terminal’s memory.

```
history
```

You’ll see a numbered list of commands you’ve entered.



## Optional

You’ve now learned some of the most common commands — ones you’ll encounter again and again.
If you want to go further:

1. **Check the man pages**
   Almost every command has a “man page”:

   ```bash
   man whoami
   ```

   These can be quite detailed, so don’t hesitate to look up unfamiliar terms online.

2. **Watch tutorials**
   A great video that covers a lot of basics:
   [You Need to Learn BASH Scripting RIGHT NOW!! // EP 1](https://www.youtube.com/watch?v=SPwyp2NG-bE)

3. **Experiment and explore**
   The best way to learn the shell is by using it. Try commands, make mistakes, and explore your system.
