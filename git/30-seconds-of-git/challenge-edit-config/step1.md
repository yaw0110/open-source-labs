# Edit Git Configuration File

## Problem

As a developer, you may need to modify the Git configuration file to customize the behavior of Git. The Git configuration file is a plain text file that contains settings in the form of key-value pairs. The file can be edited using any text editor, but Git provides a built-in text editor that can be used to modify the configuration file.

## Example

In this example, we will use the Git repository named `https://github.com/labex-labs/git-playground` directory.

1. Open the terminal and navigate to the Git repository directory.
2. Open the Git configuration file in the Git text editor.
3. Change the setting so that the username is `labex_git` and the user email is `labex_git@example.com`.
4. Once you have made the necessary changes, press <kbd>Esc</kbd> and enter the <kbd>:wq</kbd> command, then press <kbd>Enter</kbd> to save your changes and exit the editor.

This is the result after completion:

```shell
# This is Git's per-user configuration file.
[user]
    name = labex_git
    email = labex_git@example.com
# Please adapt and uncomment the following lines:
#   name =
#   email = labex@64b8c76af840a200973e9d16.(none)
```
