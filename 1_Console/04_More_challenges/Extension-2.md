
12. **Experiment with Permissions**
    Create a file and change its permissions with `chmod`.
    Try making it read-only, then attempt to edit it.

13. **Alias Something**
    Make your own shortcut command (alias).
    For example:

    ```bash
    alias updateall='sudo dnf update -y'
    ```

    Then try running `updateall` instead of the full command.

14. **Create and Run a Script**
    Write a simple script called **hello.sh** that prints your name or a message.
    Make it executable and run it:

    ```bash
    chmod +x hello.sh
    ./hello.sh
    ```

15. **Schedule Something for the Future**
    Use `at` or `cron` to schedule a command (like `echo "Take a break!"`) to run later.

16. **Clean Up**
    Delete all the test files and directories you created once you’re done — but make sure you do it safely.