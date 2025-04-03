# template-repository
A template for repositories with standard Strategy Unit files

It is advisable to add branch protections to all repositories.  The minimum protections applied to the main branch are usually:
-  Require a pull request before merging
-  Require at least one approval before merging
-  Do not allow force pushes

## Suggested branching strategy

1. Create a new GitHub issue with detailed information about the feature needing to be developed or the bug that needs fixing etc and assign yourself to it, or assign yourself to an existing issue.
2. From the main branch of the repo, create a new branch with a name that explains simply what the branch is for (consider adding the issue number to the branch name). Only one person should work on a branch at any one time.
3. Make your changes, test locally, and commit little and often to protect your work, using informative commit messages.
4. Push to GitHub and open a pull request, adding all relevant detail and assigning reviewers.
5. Once your PR is approved, merge to main.

For more detail see [out Git and GitHub style page](https://the-strategy-unit.github.io/data_science/style/git_and_github.html)




