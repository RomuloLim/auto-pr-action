
# Github Actions Auto PR
This is a basic example to practice my knowledge of github actions.

## How it works?
The actions works when have a new accepted PR in **Main** branch. The action creates automaticaly a PR updating **Main** branch changes to **Homol** Branch, and if this PR is accepted, the action creates a PR updating **Homol** branch changes to **Dev** branch changes.

## Example
- First, make changes and create a PR to **Main** branch:

<img src="https://github.com/RomuloLim/github-actions-test/blob/main/src/creating-pr.gif"
 width="600"
 height="400" />

- After, merge PR:

  <img src="https://github.com/RomuloLim/github-actions-test/blob/main/src/accept-pr-main.gif"
 width="600"
 height="400" />
 
 - Now, the action will dispatch creating a PR to **Homol**:

<img src="https://github.com/RomuloLim/github-actions-test/blob/main/src/accept-pr-homol.gif"
 width="600"
 height="400" />
 
 - When you merge PR, the action will dispatch creating a PR to **Dev**
 
 <img src="https://github.com/RomuloLim/github-actions-test/blob/main/src/pr-dev.gif"
 width="600"
 height="400" />
 
 ## Can you test?
You can access the repository with the action running and perform a fork [here](https://github.com/RomuloLim/github-actions-test).
 
 ## Notes
 - I'm learning english, but if you found an error in this readme, please contact me 😅
 - Contributions make the open source community an amazing place to learn, inspire and create. all contributions
are **extremely appreciated**

## Contributors
<kbd align="center">
 <a href="https://github.com/RomuloLim" text-decoration="none">
   <img src="https://avatars.githubusercontent.com/u/37809622?v=4" width="120">
   <br><br>
    Rômulo Lima
   <br><br>
  </a>
</kbd>
