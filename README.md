# Azure Functions on Apple silicone

Quick guide to running Azure functions on Apple silicone through devcontainers. This example uses Python 3.10, but this can be changed in the Dockerfile.
The devcontainer.json file includes settings that I found useful, but that are not nesessary when running functions in a container. This is also the case for some of the extensions.

## Docker
In order to run the function, Docker must be installed and running. You also need to make sure the "Use Virtualization framework" is checked and under "Features in development" in settings, Use Rosetta for x86/amd64 emulation on Apple Silicon must be checked. 

## Dev Container
The Dev Containers extenstion needs to be installed in Visual Studio Code:

https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers
