# Contributing
We are glad if you want to help make our game better and making this game the best that it can be. 
We have a few things we ask to do before editing our files and adding features.

### Project Branches
This section mainly applies to those with read/write access to our repositories, but can be helpful for others.

The `development/development` branch should always be in a runnable state, and not contain any major breaking features. For the most part, this means you will need to create `feature/` branches in order to add new functionality or change how things work. When making a feature branch, if it is referencing something in the issue tracker, please title the branch `feature/HS-###` where `###` is the issue number.

Moving forward all commits from contributors should be in the form of a PR, unless it is something we have previously discussed as being able to be pushed right into `development/development`.

All new code should contain unit tests at a minimum (where applicable). There is a lot of uncovered code currently, so as you are doing things please be looking for places that you can write tests.

### Update the CHANGELOG
When adding something that is new, fixed, changed, or security-related for the next release you should be adding a note to the CHANGELOG. If something is changing within the same version (i.e. fixing a bug introduced but not released) it should _not_ go into the CHANGELOG.
