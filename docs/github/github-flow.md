# :simple-github: GitHub Flow

The GitHub Flow is a lightweight, branch-based workflow that supports teams and
projects where deployments are made regularly. This method is designed to be
straightforward, facilitating continuous delivery and integration. It's
particularly well-suited for projects that require a nimble approach to
development and deployment. Here’s how to implement the GitHub Flow in your
projects:

## Introduction to GitHub Flow

Unlike Git Flow, the GitHub Flow is centered around a single branch, `main`, and
uses feature branches for development. The steps are simple:

- Create a branch.
- Add commits.
- Open a Pull Request (PR).
- Discuss and review your code.
- Merge into `main`.
- Deploy from `main`.

## Initial Setup

Ensure your repository is set up on GitHub and all team members have cloned the
repository to their local machines. The `main` branch will be your primary branch
for deployment.

## Creating a Branch

For every new feature, bug fix, or enhancement, create a new branch off the `main`
branch. Use descriptive names for your branches to reflect the work being done.

```bash
git checkout main
git pull origin main
git checkout -b <branch_name>
```

This isolates your work from the production code in the `main` branch. It is often
helpful to include the issue number in the branch name for reference. For example,
`git checkout -b issue/123`.

## Add Commits

Make your changes locally and commit them to your branch. Commit messages should
be clear and descriptive. It is a good idea to "commit early and often" as it
backs up your work and provides a safety-net. A good rule of thumb is to commit
your changes whenever you complete a logical step in the code.

```bash
git add .
git commit -m "A descriptive commit message"
```

Regularly push your commits to GitHub to back up your work and make it available
to other team members.

```bash
git push origin <branch_name>
```

## Opening a Pull Request (PR)

Once your changes are ready and pushed to GitHub, open a Pull Request against the
`main` branch. PRs are a way to start a conversation about the changes you propose.
It’s a place to review code, discuss with teammates, and make additional adjustments.

- Navigate to your repository on GitHub and click the "Pull request" button.
- Select your branch and ensure it's compared against `main`.
- Fill in the details of your PR and create it.

It is considered good practice to include a link to the issue/ticket for the work
that you completed and a detailed explanation of what you changed and why. You
can make it easier on reviewers by leaving comments on the changes in the PR.

If you want to share your changes with your team before it is ready for final
review, you can also create a **Draft Pull Request**.

## Review and Discuss

Your team can now review the changes, leave comments, and suggest modifications.
This is an opportunity for collaborative improvement and ensuring code quality.

If changes are requested, simply continue work on your branch and push the changes
to GitHub. Your changes will automatically appear in your pull request when you
push.

## Deploy from the Feature Branch (Optional)

For some teams, it's beneficial to deploy the branch to a staging environment
for testing. This ensures that your changes work as expected in a live environment
before merging them into `main`.

This can be setup using [GitHub Actions](https://docs.github.com/en/actions).

## Merge into Main

Once your PR has been reviewed and approved, and all tests pass, it’s time to
merge your changes into `main`. This action typically triggers an automated
deployment process, depending on your project's CI/CD setup.

## Keep Your Branches in Sync

After merging, keep your local `main` and any active feature branches updated
to avoid merge conflicts.

```bash
git checkout main
git fetch -p
git pull
```

## Best Practices

- **Small, Frequent Changes**: Make small, incremental changes with frequent
  commits and merges to keep the workflow agile.
- **Code Review**: Utilize Pull Requests for code review to maintain quality
  and foster collaboration.
- **Continuous Integration (CI)**: Implement CI to automatically build and test
  your code for errors. Branch protection rules should be setup to ensure that
  the code builds and tests pass before a pull request can be merged.
- **Automate Deployments**: Use Continuous Deployment (CD) tools to automate
  deployments from `main`, ensuring smooth and swift updates to your production
  environment.

The GitHub Flow offers a simple yet effective way to manage development,
encouraging collaboration and streamlining the process of getting changes into
production.

## Further Reading

- [GitHub Flow](https://githubflow.github.io/)
- [GitHub Flow - GitHub Docs](https://docs.github.com/en/get-started/using-github/github-flow)
- [GitHub Training Manual](https://githubtraining.github.io/training-manual/#/01_getting_ready_for_class)
