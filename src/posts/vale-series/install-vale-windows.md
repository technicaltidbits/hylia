---
title: Install the Vale CLI (Windows)
date: '2020-05-08'
tags:
    - vale
    - beginners
    - tutorial 
    - vale CLI
---
To install Vale on your computer, you'll need to use a package manager. Package managers allow you to install and update packages and libraries. 

Windows users can install Vale using [**Chocolatey**][Chocolatey link]. If you've already installed Chocolatey, skip to [step two](#heading-step-two:-install-vale). Otherwise, continue reading the instructions below. 

---

## Step one: Install Chocolatey 

1. The documentation for Chocolatey is very thorough and walks you through the steps to install it on your computer. [Here's](https://chocolatey.org/install) the link with the installation steps.

2. To verify that you installed Chocolatey, run the command `choco -?`. This command prints help info to the terminal.. If you see output in the terminal, you successfully installed Chocolatey.

## Step two: Install Vale

1. From the terminal, run the command `choco install vale`. You'll see some output in the terminal as Chocolatey installs Vale on your computer.

2. To verify that you installed Vale, run the command `vale -v` in the terminal. This command prints the current version to the terminal. As of May 2020, the latest version is `1.7.1`. 

---

That's all you need to do to install the Vale CLI on your Windows computer! Next, you'll learn how to configure and customize Vale for your documentation needs. 

[Chocolatey link]: https://package.chocolatey.org/




