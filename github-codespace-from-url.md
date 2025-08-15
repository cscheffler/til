# GitHub Codespace from URL

You can create a free [GitHub Codespace](https://github.com/features/codespaces) for your favourite repo by creating a single URL.

If your repo lives at https://github.com/<username>/<reponame> use https://codespaces.new/<username>/<reponame>?quickstart=1 to set up a container for you running Python, connect you to VS Code in your browser, and a terminal in the root directory of your repo.

You can tweak the container configuration by creating the file `.devcontainer/devcontainer.json` in your repo. Here's documentation on what goes in there.

Here a simple example for setting up

* Python 3.13, instead of the default which is 3.12.1 at the time of writing,
* Node at the latest version, and
* the uv package manager for Python

```json
{
  "name": "Python 3.13",
  "image": "mcr.microsoft.com/devcontainers/python:3.13-bullseye",
  "features": {
    "ghcr.io/devcontainers/features/node:1": {
      "version": "latest"
    }
  },
  "postCreateCommand": "pip install uv"
}
```
