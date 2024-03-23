# :octicons-git-merge-16: Git Setup

## Initial Setup

1. Download and install the [latest version of Git](https://git-scm.com/downloads).
2. Set your username and email address,

```sh
git config --global user.name "Jane Doe"
git config --global user.email "jane.doe@aspiresoftware.com"
```

3. Confirm that you set the username and email correctly,

```sh
git config --global user.name
git config --global user.email
```

## Settings for Line Endings

Windows and Linux have different line endings for text files. You will want to
configure git to convert line endings on Windows or leave them as-is on Mac and
Linux.

For Windows, it is best if line endings are converted to Unix style when you
commit files. To do so, run the command,

```sh
git config --global core.autocrlf true
```

On Mac and Linux which both use Unix style line endings, you should configure git
to leave line-endings as-is.

```sh
git config --global core.autocrlf input
```

## Ignore Files

Each repository should have a `.gitignore` file that prevents binary files and
other changing files from getting checked into the repository by mistake. Simply
add a `.gitignore` file to the root of a repository.

!!! info
    The website [gitignore.io](https://www.toptal.com/developers/gitignore) will
    generate appropriate `.gitignore` files for your programming language, operating
    system or IDE.

## Further Reading

- [Git Cheat Sheet](https://training.github.com/downloads/github-git-cheat-sheet/)
- [Git Submodules](https://training.github.com/downloads/submodule-vs-subtree-cheat-sheet/)
- [Migrating Subversion/SVN to Git](https://training.github.com/downloads/subversion-migration/)
- [GitHub Training Manual](https://githubtraining.github.io/training-manual/#/01_getting_ready_for_class)
- [Getting started with Git](https://docs.github.com/en/get-started/getting-started-with-git)
- [Using Git](https://docs.github.com/en/get-started/using-git)
