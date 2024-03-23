# :simple-github: GitHub Organization Setup

## Teams

- Add a Developers team and invite members
- Add an Administrators team and invite members

## Billing & Plans

- Upgrade to a Team plan
- Enter the credit card info
- Review and click the final "Upgrade your Organization Account"

## Member Privileges

- Disable Allow forking of private repositories

## Organization Security

- Require two-factor authentication

## Security & Analysis

- Enable all for each option

## Repository Defaults

- Switch the default branch to `main`
- Edit/Add labels as desired

## GitHub Repository Setup

Do the following for each repository

### Options

- Disable features you are not using
- Under the Merge button section, Automatically delete head branches

### Manage Access

- Access should only be given to teams, not to individuals so that permissions can be controlled at the organization level
- Add Developers team with the Maintain permission
- Add the Administrators team with the Admin permission

### Branches

- Add Branch protection rules for `main` and other branches like `release`
- At a minimum, you should set Require a pull request before merging and require approvals
- If CI/CD is enabled, require status checks to pass before merging
- Enable other options depending on the team
- Never allow force pushes or deletions
