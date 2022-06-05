# ![icons8-github-with-cat-logo-an-online-community-for-software-development-72](https://user-images.githubusercontent.com/83048295/162607041-557590b5-bb2f-4354-8d75-9deaffe87887.png) Git Automation Scripts 
A few scripts to automate git common usages.

### Supported Platforms
Currently, there are only scripts for Linux/MacOS. Windows version is coming soon!

### Why do we even need these? 

Well, simply to make our lives easier. With these automation scripts, we can simple use `pushbr` instead of verbosely typing `git add.`, then `git commit`, and then `git push origin current-feature-branch`. These scripts included in this repo will cover the most popular git commands that developers use daily.

Another reason is that I'm just a guy who is obssessed with automating stuff
![automation-gif](https://media.giphy.com/media/1nR6fu93A17vWZbO9c/giphy.gif)


---
## Usages
You can look for the usages of the existing scripts below

<details><summary><strong>br</strong></summary>
Print the name of the current branch and also copy it to the clipboard so that you don't have to memorize and type out your lengthy feature branch's name.
</details>

<details><summary><strong>pushbr</strong></summary>
Execute the following commands sequentially: 
  <code>git add .</code>, &nbsp;
  <code>git commit</code>, &nbsp;
  <code>git push origin current-branch-name</code> &nbsp;
</details>

<details><summary><strong>resbr</strong></summary>
Reset the main branch to remote when something gets messed up
</details>


---
## Setup

### Linux/MacOS
Clone this repo to your home directory:

`git clone git@github.com:truongluan303/git-automation.git`

Add this repo to your `PATH` in your `bashrc` file (or depends on your shell preference you can add to your `zshrc`, `.profile`, etc.): 

`echo 'export PATH="$HOME/git-automation/bash_commands:$PATH"' >> ~/.bashrc`

To update when new features are released, simply use `git pull`.
