<img src="https://cdn.svgporn.com/logos/ubuntu.svg" width="182" align="right" />

# Ubuntu environment

This repo contains [Ansible](https://www.ansible.com/) script for fast and easy DevOps/Web Developer environment setup on [Ubuntu](https://ubuntu.com/) and destributions based on it.

## TL;DR

1. 📝 Open [`config.yml`](config.yml) and adjust for your needs
2. ✨ Run `./install` script
3. ...
4. ✅ Done, your system now is fully loaded with all useful web developer tools! 

## Motivation

Setting up a new developer machine can be an ad-hoc, manual, and time-consuming process. The current project aims to simplify the process with instructions and dotfiles/scripts to automate the setup of the apps and tools useful for web development.

## Applications list

Following tools will be installed:

- <img src="https://cdn.svgporn.com/logos/nodejs-icon.svg" height="14"> **Node.JS** (via [node version manager](https://github.com/nvm-sh/nvm)) + global **npm** packages
- <img src="https://cdn.svgporn.com/logos/php.svg" height="14"> **PHP** +  <img src="https://cdn.svgporn.com/logos/composer.svg" height="14"> **Composer** + global packages
- <img src="https://cdn.svgporn.com/logos/python.svg" height="14"> **Python** + **PIP** + global packages
- <img src="https://cdn.svgporn.com/logos/visual-studio-code.svg" height="14"> **Visual Studio Code** + extensions and themes
- <img src="https://cdn.svgporn.com/logos/jetbrains.svg" height="14"> **JetBrains Toolbox**
- <img src="https://cdn.svgporn.com/logos/postman.svg" height="14"> **Postman**
- <img src="https://cdn.svgporn.com/logos/docker-icon.svg" height="14"> **Docker** + <img src="https://d33wubrfki0l68.cloudfront.net/96d4dedb7aa3fbf371d01d3356a97ec463b23e04/ca713/images/docksal-mark-color.svg" height="14"> [**Docksal**](https://docksal.io/)
- Cloud tools:
  - <img src="https://cdn.svgporn.com/logos/kubernetes.svg" height="14"> **Kubernetes** + Minikube
  - <img src="https://cdn.svgporn.com/logos/google-cloud.svg" height="14"> **Google Cloud SDK**
  - <img src="https://cdn.svgporn.com/logos/aws.svg" height="14"> **AWS CLI v2**

- **zsh** + [antigen](https://github.com/zsh-users/antigen)
- CLI utilities and tools
- Office, Media apps, Internet apps and many-many more (see [`config.yml`](config.yml) file).

## Requirements

<img src="https://cdn.svgporn.com/logos/ubuntu.svg" height="14" /> **Ubuntu 20.04**

**Ubuntu** here means [Ubuntu](https://ubuntu.com/) itself and all its flavors and distributions based on certain Ubuntu version like: Kubuntu, Lubuntu, Xubuntu, Linux Mint, Pop!\_OS, elementary OS, Zorin OS, etc.

## Tested on:

- <img src="https://cdn.svgporn.com/logos/ubuntu.svg" height="14" /> <img src="https://upload.wikimedia.org/wikipedia/commons/1/1f/Kubuntu_logo.svg" height="14" /> **Ubuntu**: 20.04

- <img src="https://cdn.svgporn.com/logos/linux-mint.svg" height="14" /> **Linux Mint**: 20, 20.1

- <img src="https://upload.wikimedia.org/wikipedia/commons/c/c5/Pop_OS-Logo-nobg.svg" height="14" /> **Pop!_OS**: 20.04

- - -

## Contribution

If you experiencing any problems with your distribution, please raise an issue on [GitHub](https://github.com/alexander-danilenko/ubuntu-environment/issues/new).

- - -

## MIT License

Copyright (c) 2020 [Alexander Danilenko](https://github.com/alexander-danilenko)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
