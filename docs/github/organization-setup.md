# :simple-github: GitHub Organization Setup

## Teams

All organization users should be added through teams in GitHub rather than added
to individual repositories. At a minimum, a Developer and an Administrators team
should be added with appropriate permissions. Additional teams can be added as
needed.

- Add a Developers team and invite members
- Add an Administrators team and invite members

## Organization Setup

### Billing & Plans

If an organization is using source control, they should be updated to at least
the Team plan to enable advanced security options. The only time a free account
is appropriate is to purchase GitHub Copilot licenses for teams using alternative
source control systems.

- Upgrade to a Team plan
- Enter the credit card info
- Review and click the final "Upgrade your Organization Account"

### Member Privileges

- Disable Allow forking of private repositories

### Organization Security

Enabling two-factor authentication will remove any users without 2FA enabled
from the organization. Review the organization members and ensure everyone has
2FA enabled.

- Require two-factor authentication

### Security & Analysis

All available security scanning features should be enabled.

- Enable all for each option

### Repository Defaults

- Switch the default branch to `main`
- Edit/Add labels as desired

## GitHub Repository Setup

Do the following for each repository

### Options

- Disable features you are not using like Issues, Discussions and Wiki
- Under the Merge button section, Automatically delete head branches

### Manage Access

- Access should only be given to teams, not to individuals so that permissions can be controlled at the organization level
- Add Developers team with the Maintain permission
- Add the Administrators team with the Admin permission

### Branches

- Add Branch protection rules for `main` and other branches like `release`
- At a minimum, you should set Require a pull request before merging and require at least one approver depending on the team size
- If CI/CD is enabled, require status checks to pass before merging
- Enable other options depending on the team
- Never allow force pushes or deletions, even by admins
