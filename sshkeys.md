# How-to create and add your SSH keys for GitHub
   This guide will assist you in setting up your SSH Keys to be able to use `git` on the command line to get and backup your work.

---
## Requirements
- [GitHub.com](https://github.com) account created
- access to your terminal of choice
    - *MacOS* - terminal should be installed
    - *Windows* - [GitBash](https://git-scm.com/download/win) should be installed.
    - *Ubuntu / Linux* - any terminal emulator you have installed.
---
## :point_right: ***Note***
 - in any of the code examples, the `$` character should not be copied, it is there to refer to your command line prompt.
---

### Step 1
 - You will type in the following command, you will need to change the email address to your email address used with GitHub.
```
$ ssh-keygen -t ed25519 -C "your_email@example.com"
```


 - after you enter in that command it's going to ask for some information.
    - Where to place the files. *Hit* **`ENTER`** *here*
### Step 2