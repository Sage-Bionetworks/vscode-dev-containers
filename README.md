# Sage Bionetworks Development Containers

A **development container** is a running [Docker](https://www.docker.com)
container with a well-defined tool/runtime stack and its prerequisites. The [VS
Code Remote - Containers](https://aka.ms/vscode-remote/download/containers)
extension and [GitHub Codespaces](https://github.com/features/codespaces) allow
you to open or clone code in a local or cloud-hosted dev container and take
advantage of VS Code's full development feature set.

This repository contains a set of **dev container definitions** to help get you
up and running with a containerized environment. The definitions describe the
appropriate container image, runtime arguments for starting the container, and
VS Code extensions that should be installed. Each provides a container
configuration file (`devcontainer.json`) and other needed files that you can
drop into any existing folder as a starting point for containerizing your
project.

Modeled after [microsoft/vscode-dev-containers]

<!-- Links -->

[microsoft/vscode-dev-containers]: https://github.com/microsoft/vscode-dev-containers