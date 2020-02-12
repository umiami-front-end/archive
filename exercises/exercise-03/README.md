# Read Me

## Collaborating with Git

### Objectives

- Reinforce familiarity of working with branches
- Transfer work from/to GitHub
- Handle merges in a collaborative environment

### Instructions

Included in this repository are the following files.

- README.md
- css
  - style.css
- img
  - spaceship-earth.jpg
- spaceship-earth.html

*Note:* This exercise requires a GitHub account and at least two people to complete.

1. Discuss (or play "Paper, Rock, Scissors") to determine whose GitHub repository will serve as the project's hub. The developer hosting the "hub" should fork this repository. Developers who will not serve as the hub should clone the hub repository.

  (For instance if Alice is the hub, Alice forks this repository. Bob and Chris will clone *Alice's* repository — *not* the one hosted by `umiami-front-end`!)


2. *Developer hosting the hub:* Once the repository has been forked, you will need to add your partners as collaborators. In the forked repository, click "Settings", then select "Collaborators & teams" in the left menu. In the "Collaborators" section, add your each partner's username. Each collaborator will receive an email inviting her/him to contribute to the repo.

  *Collaborators:* Accept the invite your "hub" developer has sent.

  Move ahead with the tasks below.


3. Divide the following tasks among developers. Each developer will go to a different computer to complete the work. Create a branch (using `master` as the foundation in each case) and give it a name which describes the task.

- Fix the image's directory path and a caption.

- Add the last entry in the "Narrator" list.

- Add links to the "Links" section.

All details are in comments provided in `spaceship-earth.html`.


4. Each developer is to add a Google Font to the style sheet, selecting a font they feel reflects the content. Call this branch `update-font-to-<fontname>` where <fontname> is the font you have chosen.

  To assure there will be a conflict 😏, one developer should choose a font whose name starts with a letter between A-L; the other should choose a font whose name starts with a letter between M-Z. (If there is a third person in the group, use fonts only available on the computer, i.e. Arial, Georgia, Helvetica, etc.)

  Apply the font to headings only.


5. When the tasks are finished, each developer should push these branches to the hub using: `git push -u origin branch-name` (where `branch-name` is the name of the branch you created and worked on). This will upload your branch to the hub repository.


6. On GitHub, create a pull request for each branch you contributed.


7. When you reach this step, gather your group! You will work on merging the changes together. Each developer should try a merge on GitHub.

  For the branches which do not include the font change, (which should have no conflicts) merge these pull requests in the hub repository.


8. When you merge the font changes, follow the command line steps provided by GitHub to merge the conflict. (See: "Use the web editor or the command line...").

  You will fetch the project repository, checkout the remote branch and merge. Resolve the conflict, deciding which font is preferred. Then merge the changes on GitHub using the steps provided. Checkout the master, merge the local repository and push the local version of master to the origin (on GitHub).

  (If there are three developers, repeat the same steps above, but with one of the other developers performing entering the commands at the command line.)

**Good Luck!**
