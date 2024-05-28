# WSL Setup: Zsh with Oh My Zsh

## Introduction
This guide outlines the process of setting up Zsh with Oh My Zsh on Windows Subsystem for Linux (WSL) on your Windows machine.

## Prerequisites
- Windows Subsystem for Linux (WSL) installed on your Windows machine.
- Access to a terminal emulator for running commands.

## Step-by-Step Guide
1. **Update Package Lists**
    ```bash
    sudo apt update
    ```
    Ensure that the package lists for apt, the package manager for Ubuntu on WSL, are up to date.

2. **Install Build Essential**
    ```bash
    sudo apt install build-essential
    ```
    Install "build-essential," which includes packages needed for compiling software from source code.

3. **Install Zsh**
    ```bash
    sudo apt install zsh
    ```
    Install Zsh on your system.

4. **Install Oh My Zsh**
    ```bash
    sh -c "$(wget https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh -O -)"
    ```
    Download and run the Oh My Zsh installation script from its GitHub repository.

## Optional Steps
- **Choosing a Zsh Theme**: Edit the `~/.zshrc` file to change the `ZSH_THEME` variable to your preferred theme.
- **Customizing Oh My Zsh**: Explore `~/.oh-my-zsh` to discover available plugins and customize your Zsh environment further. Refer to the `README.md` file in this directory for additional information.

By following these steps, you'll have Zsh with Oh My Zsh set up on your WSL instance, providing a powerful and customizable shell experience.
