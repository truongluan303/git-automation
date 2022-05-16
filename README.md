# ![icons8-github-with-cat-logo-an-online-community-for-software-development-72](https://user-images.githubusercontent.com/83048295/162607041-557590b5-bb2f-4354-8d75-9deaffe87887.png) Git Automation Scripts 
A few scripts to automate git common usages.

Why do we even need these? Well, simply to make our lives easier. With these automation scripts, we can simple use `pushbr` instead of verbosely typing `git add.`, then `git commit`, and then `git push origin current-feature-branch`. These scripts included in this repo will cover the most popular git commands that developers use daily.

![giphy](https://user-images.githubusercontent.com/83048295/162607390-acf60ff4-e1b8-4fb5-aaad-f4f8d7f01f45.gif)


---
## Usages
You can look for the usages of the existing scripts below

<details><summary><strong>br</strong></summary>
Print the name of the current branch and also copy it to the clipboard.
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
<details><summary><strong>Linux/MacOS</strong></summary>
  Run <code>setup</code> script and you should be good to go. 🙌
  <br/> 
  The <code>setup</code> script will automatically copy the <code>commands</code> folder to your home directory and also add it to the path enviroment variables
</details>

<details><summary><strong>Windows</strong></summary>
Coming soon!
</details>
