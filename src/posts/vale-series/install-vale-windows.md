---
title: Install the Vale CLI (Windows)
date: '2020-05-08'
tags:
    - vale
    - beginners
    - tutorial 
    - vale CLI
---
## Step one: Install a package manager 

To install Vale on your computer, you'll need to use a package manager. Package managers allow you to install and update packages and libraries. 

Windows users can install Vale using [**Chocolatey**][Chocolatey link]. If you've already installed Chocolatey, skip to [step two](#heading-step-two:-install-vale). Otherwise, continue reading the instructions below. 

---

The documentation for Chocolatey is very thorough and walks you through the steps to install it on your computer. [Here's](https://chocolatey.org/install) the link with the installation steps.

To verify that you installed Chocolatey, run the command `choco -?`. This command prints help info to the screen. If you see output in the terminal, you successfully installed Chocolatey.

## Step two: Install Vale

From the terminal, run the command `choco install vale`. You'll see some output in the terminal as Chocolatey installs Vale on your computer.

## Step three: Verify installation 

To verify that you installed Vale, run the command `vale -v` in the terminal. The terminal prints the current version to the screen. As of May 2020, the latest version is `1.7.1`. 

---

That's all you need to do to install the Vale CLI on your Windows computer! Next, you'll learn how to configure and customize Vale for your documentation needs. 

[Chocolatey link]: https://package.chocolatey.org/




