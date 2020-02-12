# Read Me

## Git Basics

### Objectives

- Set up git
- Fork a repository
- Clone a repository
- Develop a commit workflow
- Create branches
- Push changes to GitHub


## Before You Begin

Check to see if git is installed by typing `which git` in the terminal. If there is a response, git is installed!

### Installation

If git is not installed...

**MacOS:** Type `git` at the command line. This will prompt you to install "Command Line Developer Tools."

**Windows:** [Download git](https://git-scm.com/download/win) from the official web site.

### Configuration

Configure the software with your `user.name`, `user.email` and `core.editor`.

(i.e. `git config --global user.name "Jane Doe"`)

If you are working on your *personal computer*, you may want to configure git to automatically save your username/password for connecting to GitHub. Follow the steps in ["Caching your GitHub password in Git"](https://help.github.com/en/articles/caching-your-github-password-in-git).


## Instructions

1. Fork this repository. You will find the "fork" button on the right, just below the navigation bar. "Forking a repository" creates a copy of the repo in your GitHub account. **Moving forward, use the version in *your* account.** If you use the repository in `umiami-front-end` you will be unable to push changes.

2. Switch to the repository in your account. Click the green "Clone or Download" button, then click the clipboard icon next to the URL of the repository's location. The URL should be something similar to: `https://github.com/your-username/exercise-02.git`.

3. Using the command line, navigate to the directory on your computer where you would like to work. This may be your home folder or another directory -- choose what is comfortable for you. Type `git clone` followed by a space and the URL you copied from GitHub. Hit enter. This will download a copy of the repository to your computer.

4. Change to the directory you just cloned.

5. On the `master` branch of this repository, remove the `README.md` file. Commit this change.

6. Create a new branch called `fix-typo`. Fix the typo in `index.html` (it is in the `h2`). Commit this change.

7. Using the `fix-typo` branch as the basis, create another new branch called `update-web-site`.

9. Within the `update-web-site` branch, you will make a couple changes to the web site. In `index.html`, add a footer tag. Within the footer, add copyright information. Add text which reads "Last updated:" and the date. In the style sheet, change the font so it uses one from Google Fonts. When finished, commit these changes together in a single commit.

10. Push all three branches (`master`, `fix-typo`, `update-web-site`) to GitHub using the following command: `git push origin --all`. Check on GitHub.com to see that all the branches are there.

**Good Luck**
