## Brief

## Self studies check-in

There is no self studies related to GIT. Learners should be informed that GIT is not easy to master and it will take years to become good. Learning on-demand is pretty much every Developers' experience in learning GIT.

In the first half (1.5 hours) of the lesson, we will be learning about GIT. In the second half, we will be having a short recap on HTML and CSS which learners should have been working on their self studies. We will then use HTML and CSS to create a simple profile page (refer to [assignment](./assignment.md)) and upload the code to GitHub using GIT CLI.

---

## Conceptual Knowledge about GIT (15 mins)

### What is GIT?

Review this [video](https://youtu.be/2ReR1YJrNOM) in class.

Check-in with learners for a short Q&A about the video.

---

## Part 1 - Fork, Clone. (30 mins)

### Fork and clone repository

Step 1: Visit [this repository url](https://github.com/su-ntu-ctp/6m-software-1.2-cli-git) on the browser.

Step 2: Fork it as your own repository.

Step 3: Launch VS Code and open the folder where you would clone all repositories (this folder is created in the previous lesson).

Step 4: Start a Terminal within VS Code.

Step 5: Enter the command `git clone https://github.com/su-ntu-ctp/6m-software-1.2-cli-git` and hit Enter.

Step 6: A new folder should appear the directory.

### The difference between FORK and CLONE

<img src="./assets/clone-vs-fork.png" />

When you fork, you are copying someone else's remote repository to your remote repository.

When you clone, you are copying a remote repository to your local machine (laptop).

---

## Part 2 - Push Changes, Create Pull Request. (20 mins)

Follow these steps to try making changes and push them to the remote repository.

Step 1: Create a new file `test.txt` in the cloned repository (folder). 

Step 2: Open the file and simply type "testing 123" in it.

Step 3: Open up the Terminal and ensure that you are in the directory of the cloned repository (folder) by using `pwd` command.

Step 4: Stage the changed file by typing `git add .`

Step 5: Commit it with a simple message `git commit -m "made changes"`.

Step 6: Push the committed change to remote repository `git push origin main`.

Step 7: Visit your remote repository at github.com to see the changes. The remote repository URL is `https://github.com/<your username>/6m-software-1.2-cli-git`.

Step 8: Perform a pull request to the upstream repository 

From: `https://github.com/your_username/6m-software-1.2-cli-git`

To: `https://github.com/su-ntu-ctp/6m-software-1.2-cli-git` 


---

## Part 3 - HTML & CSS Recap. (40 mins)

There are many HTML tags and styling properties. The best way to reference them is through a [cheatsheet](https://htmlcheatsheet.com/).

### Basic HTML

Demonstrate to the learners the use of the following HTML tags:

- `<html>`
- `<head>`
- `<body>`
- `<title>`
- `<h1>` to `<h6>`
- `<p>`
- `<ul>` and `<li>`
- `<a href>`
- `<img>`

### Using the `style` attribute

Try styling with the following properties:

- `background-color`
- `color`
- `font-style`
- `opacity`
- `border-radius`

### Using the <style> tag

Try moving the applied styling into `<style>...</style>` tag.

### Importing a CSS File

Try moving the styling to `styles.css` file.
