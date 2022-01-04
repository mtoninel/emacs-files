
# A Quick Cheat Sheet for Magit v3

<img src="https://magit.vc/assets/magit-400x400px.png" alt="drawing" width="150" class="center">

This sheet contains a list of commands following a typical Git workflow in Emacs using the [Magit porcelain](https://magit.vc/).

### Minimal workflow
Invoke the _magit-status_ buffer by using C-x g,  then navigate files in the repo and mark the wanted ones. On the marked files use the following commands. 

|                |                |
|----------------|----------------|
|Initialize a local repo | `I` |
|Adding file (staging) | `s` |
|Removing file (unstaging)* | `u` |
|Removing all files (unstaging)* | `U` |
|Committing          |`c`      |
|Exit message buffer successfully          |`C-c C-c`      |
|Abort commit and exit message buffer          |`C-c C-k`      |
|Pushing to configured remote repo          |`P p`|
*Unstaging also works on alredy-committed changes.

### Additional workflow steps
|                |                |
|----------------|----------------|
|Cloning a remote repo | `C C` |
|Pulling from a remote repo (fetch and merge) | `F p` |
|Fetching from a remote repo | `f p` |
|Rebase onto remote | `r p` |
|Interactively rebase onto remote | `r i` |

For info regarding the difference between fetching and pulling see [here](https://stackoverflow.com/questions/292357/what-is-the-difference-between-git-pull-and-git-fetch) while for rebasing see [here](https://stackoverflow.com/questions/36148602/git-pull-vs-git-rebase).

### Working with branches
|                |                |
|----------------|----------------|
|Create a new branch | `b n` |
|Create a new branch and check it out | `b c` |
|Check out an existing branch | `b b` |

... and others to come...
