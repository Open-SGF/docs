## Week 1

Pair with another volunteer to get an overview of the assigned team project

If possible, pair program with a mid or senior dev

-   Using one laptop, designate a driver and a navigator
-   The driver types the code and the navigator tells the driver what to code

## Week 2

Pair with a senior dev to configure development machine

-   Install Docker

## Week 3

Intro to git and project work

-   How to fork a repo
-   How to clone a git repo onto your local machine
-   Basic git commands:
    -   `git add -A`
    -   `git commit -m "message"`
    -   `git push`
-   Git commit messages
    -   Open SGF convention
        -   `chore: `
        -   `feat: `
        -   `fix: `
-   Git branches (named after features)
    -   `git checkout -b feat`
    -   `git checkout main`

## Week 4

Pull requests - Make a pull request through GitHub - Use draft pull requests for
transparency and communication while working on a feature

Git rebasing 1. Update both branches - Main: `git fetch upstream`
`git reset --hard upstream/main` - Feature: `git pull` [if on team branch `git
fetch origin` `git reset --hard origin/feat`] 2. Rebase - `git checkout feat` -
`git rebase main` [if conflict fix conflict `git add -A` `git rebase -continue`
edit and save git message if in vim, use `:wq` to exit] 3. Push - `git push -f`
