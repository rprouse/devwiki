# Contributing to the Manos Dev Wiki

You are invited to contribute 💖 to this guide by opening issues and
submitting pull requests!

Here are some ideas 💡 for how and where you can help most with
contributions:

- Fix any spelling or grammatical mistakes you see as you read.
- Fix technical inaccuracies.
- Fix logical or compilation errors in code examples.
- Expand an explanation to provide more context or improve the clarity of some
  topic or concept.

If you're making a small to modest correction, such fixing a spelling error or
a syntax error in a code example, then feel free to submit a pull request
directly. For changes that may require a large effort on your part (and
reviewers as a result), it is strongly recommended that you submit an issue
and seek approval of the maintainers/editors before investing your time. It
will avoid heartbreak 💔 if the pull request is rejected for various reasons.

This wiki is built with [MkDocs](https://www.mkdocs.org) and
[Material for MkDocs](https://squidfunk.github.io/mkdocs-material/). Visit their
sites for full documentation.

## Quick Start for Docker with VSCode

1. Start VS Code and click on the quick actions Status Bar item in the lower left corner of the window.
2. Select **Remote-Containers: Open Folder in Container...** from the command list that appears, and open the root folder of the project you just cloned.
3. The window will then reload, but since the container does not exist yet, VS Code will create one. This may take some time, and a progress notification will provide status updates. Fortunately, this step isn't necessary the next time you open the folder since the container will already exist.
4. After the container is built, VS Code automatically connects to it and maps the project folder from your local file system into the container.
5. Open the terminal in VS Code to a bash prompt within the container by clicking on **Terminal > New Terminal**
6. In the terminal, type `mkdocs serve` to build and run the web site.
7. Open the web site at [http://127.0.0.1:8000/](http://127.0.0.1:8000/).
8. Begin developing in Visual Studio Code.

## Build Requirements

- [Python](https://www.python.org/)
- [MkDocs](https://www.mkdocs.org)
- [MkDocs Material](https://squidfunk.github.io/mkdocs-material/)

With Python installed, run the following command from the command line:

```sh
pip install mkdocs-material
pip install mkdocs-video
```

## Commands

- `mkdocs new [dir-name]` - Create a new project.
- `mkdocs serve` - Start the live-reloading docs server.
- `mkdocs build` - Build the documentation site.
- `mkdocs -h` - Print help message and exit.

## Project layout

```txt
mkdocs.yml    # The configuration file.
docs/
    index.md  # The documentation homepage.
    ...       # Other markdown pages, images and other files.
```
