# project_euler

This repo is a starting ground for Claudia to learn a lot of things at the same time.
Some of the things that Claudia will learn

- python
- linux
- git

 We will do so by focusing on the problems available on the [Project Euler Site](https://github.com/dimasgonzales/project_euler).

## Setup

Below are a list of references and documentation for all the things to install and setup.

### Windows Subsystem for Linux

In order to develop some real experience with linux we are going to use the WSL(i.e: Windows Subsystem for Linux) to quickly install linux on your laptop.

This video has a great explanation about what WSL is and what you can do it with it. [Youtube: What can I do with WSL? | One Dev Question
](https://youtu.be/48k317kOxqg)

#### Installation Instructions
Please follow this [guide](https://docs.microsoft.com/en-us/windows/wsl/install-win10).

**Special Notes:**

- For step 6. Please install Ubuntu
[Microsoft App Store: Ubuntu](https://www.microsoft.com/en-us/p/ubuntu-2004-lts/9n6svws3rx71?rtc=1&activetab=pivot:overviewtab)

You can also follow this video for up-to-date step-by-step instructions on how to install Ubuntu to the WSL. [Youtube: How to Install Ubuntu on Windows 10](https://youtu.be/X-DHaQLrBi8)

#### Post Installation Validation

Play around with the WSL. It should be easy to start it.
Open a windows terminal or the powershell and run the following command.

```bash
wsl
```

Or you can start it like any other windows application from your start menu.
Afterwards you should have full access to the linux straight from your Windows desktop.

### Git

Source code version control is an important concept to learn as a software engineer. However you might not learn about it until late in your college career and trying to learn it on your first job is just a recipe for disaster. To that effect we will manage this code using `git` and `github` so that you can get a hang of the basics and give you a safe place to learn this important skill and tools.

#### Introductory Reading

- [Git: About Version Control](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control).

#### Installation Instructions

This one will be really easy. Just one command

```bash
sudo apt install git-all
```

### Python

In order to install the python runtime we will use `pyenv` and `pipenv` to install and manage the python runtimes as well as virtual environments.

#### Pyenv

For detailed instructions you can follow the following guides. 
[Github: Pyenv-install](https://github.com/pyenv/pyenv-installer)
[Github: Pyenv Installation Guide](https://github.com/pyenv/pyenv#installation)

But if you just want the commands to execute run the following.

**Quick Start**

1. Install `pyenv` and restart your shell instance

```bash
curl https://pyenv.run | bash
exec $SHELL
```

1. Install Python Runtime Dependencies

```bash
sudo apt-get update; sudo apt-get install --no-install-recommends make build-essential libssl-dev zlib1g-dev libbz2-dev libreadline-dev libsqlite3-dev wget curl llvm libncurses5-dev xz-utils tk-dev libxml2-dev libxmlsec1-dev libffi-dev liblzma-dev
```

1. Install a Python runtime

For this work let's use Python version `2.8.1`

```bash
pyenv install 3.8.1
```

#### Pipenv
As you start to develop more and more complicated code you will learn to you can "stand on the shoulders of giants". Python allows you import code that other people wrote to solve your immediate problems in a clean and neat way.

But it can be easy to install a ton of things and really muck up your machine. To that effect we will leverage the concept of virtual environments to cleanly manage the depedancies that you need for a project.

**Installation**
Setting up is really easy.

```bash
pip install pipenv
```

## Euler Problems

TODO