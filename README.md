# Project Branch Structure

This repository contains the Number Guessing Game project. Below is a summary of branches and their changes

- **main**: Initial project setup and stable version
- **dev**: Added encouraging messages for players
- **feature1**: Added version comment documenting quit feature and improved user feedback messages, play again loop functionality and ability to quit with negative input.
- **feature2**: Implemented max attempts logic and game over condition.
- **feature3**: Miscellaneous fixes (commits -done, had to fix, got it done, started hint).
- **hotfix**: Fixed `randomInt` to properly include max value in range.
- **documentation**: Contains this README.md file documenting branch structure and changes.



# Git Learning Summary

## Merge
- Joins two branches
- Creates a merge commit
- Keeps full history

Used when working with a team on shared branches

## Rebase
- Moves your commits on top of another branch
- No merge commits
- History looks straight (linear)

Used when updating your own feature branch

## Squash
- Combines many commits into one
- Makes history clean

Used when finishing a feature before merging

## Cherry-pick
- Copies one commit to another branch
- Does not bring full branch history

Used when you need one specific fix

## Branch History Observations

### feature1
- Used merge
- Had merge commits
- History looked messy

### feature2
- Used rebase
- History was linear
- Easier to read

### feature3
- Used squash then rebase
- One clean commit
- Best and cleanest history

## When I Would Use Each
- Merge: team collaboration
- Rebase: clean my own work
- Squash: prepare feature for dev
- Cherry-pick: apply small fixes

