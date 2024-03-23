# :simple-github: GitHub Security Policy

## Enable two-factor authentication (2FA)

- Ask all organization members to enable 2FA on their GitHub accounts by visiting [https://github.com/settings/security](https://github.com/settings/security).
- As an organization owner, enforce 2FA for your organization by going to your organization's Settings > Security, and enabling "Require two-factor authentication for everyone in your organization."

## Use strong and unique passwords

- Encourage organization members to create strong, unique passwords that are at least 12 characters long and include a mix of uppercase and lowercase letters, numbers, and special characters.
- Recommend using a password manager like Bitwarden to generate and store unique passwords securely.

## Require identifiable names on user account

- Require that users set their full name on their GitHub accounts so that it is easy to identify who a person is and makes audits easier. To do so, click on your user icon, go to Your Profile and click Edit Profile. Set at least the Name field and ideally set other information and a profile photo.

## Regularly review access

- Periodically review the list of organization members, teams, and collaborators by visiting your organization's People and Teams pages.
- Remove any inactive or unnecessary users to minimize the risk of unauthorized access.

## Restrict repository access

- Use GitHub teams to manage repository access. Create teams with specific access levels and add members to those teams.
- Assign repository access to teams rather than individual members by visiting a repository's Settings > Manage Access.

## Implement branch protection

- Visit your repository's Settings > Branches.
- Click "Add rule" to create a new branch protection rule for your main branch.
- Configure the rule to require pull requests, status checks, and reviews before merging changes.

## Use codeowners

- Create a CODEOWNERS file in the root directory of your repository.
- Define code owners for specific files or directories using the GitHub username, team name, or email address, followed by the file or directory pattern.
- More information: [https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners)

## Use GitHub Actions securely

- Limit the use of third-party actions to trusted sources.
- Keep actions up to date by regularly checking for new versions and updating the version number in your workflow files.
- Review your workflows for potential security risks, like unauthorized access to secrets or inappropriate use of permissions.

## Rotate access tokens and keys

- Regularly rotate personal access tokens by going to [https://github.com/settings/tokens](https://github.com/settings/tokens) and generating new tokens with the same scope as the old ones, then updating any tools or services that use them.
- Encourage organization members to update their SSH keys regularly by visiting [https://github.com/settings/keys](https://github.com/settings/keys).

## Set up security vulnerability alerts

- Enable Dependabot by visiting your repository's Insights > Dependency graph > Dependabot.
- Configure the Dependabot settings to receive automatic security alerts and suggested updates for vulnerabilities in your project's dependencies.

## Conduct security audits

- Regularly audit your organization and repository settings, as well as your codebase, to identify and mitigate potential security risks.
- Use tools like GitHub Advanced Security, Snyk, or SonarQube to perform automated security analysis on your codebase.

## Educate team members

- Provide resources, such as blog posts, articles, and webinars, to educate your team members on security best practices.
- Organize internal training sessions and workshops to improve security awareness among your team members.

## Adopt a security policy

- Add a SECURITY.md file in your repository's root directory that outlines your security policy, and encourage your team members to follow it.

## Encourage signed commits

- Signed commits provides verification on who made changes to the code. Without signed commits, anyone with write access to a repository can make code changes that appear to have been made by another user.
- Instructions on setting up code signing can be found on [GitHub](https://docs.github.com/en/authentication/managing-commit-signature-verification/about-commit-signature-verification)
