# Environment Prep for UBUNTU on Windows 11 WSL2

## Pre-requisites

- Windows Terminal
- WSL Ubuntu 
- Docker Desktop
- NVIDIA GEForce drivers
- NVIDIA CUDA Toolkit
- VS Code (or your choice of IDE)

> [!IMPORTANT]
>
> Q: I am learning about LLMs and want to use ollama+gpu. How do I install cuda on my windows laptop if I'm coding on WSL Ubuntu? Do I install on windows OS or on the WSL Ubuntu partition?
>
> A: In this case, you'll actually install CUDA on the Windows side, not directly on the WSL Ubuntu partition. see [gemini chat](https://g.co/gemini/share/59edca85664e)

## Install Terminal

1. Go to the Microsoft Store App
1. Search for Terminal and install it
1. [Install Powershell](https://learn.microsoft.com/en-us/powershell/scripting/install/installing-powershell-on-windows?view=powershell-7.4)

## Install WSL and Ubuntu

1. https://learn.microsoft.com/en-us/windows/wsl/install
   - if you follow the guide, the default and recommended Linux Distro is the current Ubuntu LTS (long-term-support) for new linux users 
1. Learn the [basic WSL commands](https://learn.microsoft.com/en-us/windows/wsl/basic-commands)
1. Learn the basic UNIX commands with [Linux Crash Course for Beginners with Labs](https://youtu.be/6WatcfENsOU?si=6pcVmlSlviyKYwJm) 
   - via freeCodeCamp.org's youtube channel 
   - the tutorial is 2hours++ video, with chapters


## Install Docker Desktop

1. Follow the official [Install Docker Desktop on Windows](https://docs.docker.com/desktop/install/windows-install/) Guide from docker.com documentation pages
1. Perform the [post-install steps](https://docs.docker.com/desktop/wsl/) to check Docker is setup to run on WSL properly

## Install CUDA Toolkit

1. update nvidia driver via GE Experience
1. download the [CUDA Toolkit](https://developer.nvidia.com/cuda-downloads?target_os=Windows), with below choices
   - Windows
   - x86_64
   - 11 (if on Windows 11)
   - exe (local)
1. click on the green `Download` button for the Base Installer
1. locate the downloaded `.exe` file in your Downloads folder
1. double-click the `.exe` and follow the on-screen instructions

