# Tech Environment Setup Guide

This document outlines the necessary steps and tools for setting up a development environment. It covers essential software installation, account creation, and workstation recommendations.

## Prerequisites

Before proceeding, ensure your system meets the following minimum requirements:

*   **[Operating System](pplx://action/followup):** Windows (recommended for VSCode and Git integration)
*   **[Memory](pplx://action/followup):** 8GB RAM minimum (16GB recommended for virtualization)
*   **[Internet Connection](pplx://action/followup):** A stable internet connection is required for downloading software and accessing online services. Consider a backup internet solution for uninterrupted workflow.

## A. Account Setup

### 1. AWS Account

*   **[Purpose](pplx://action/followup):** Access to cloud computing resources for development and deployment.
*   **[Action](pplx://action/followup):** Create a free tier AWS account. - https://aws.amazon.com/

*   ![](https://github.com/istephenmichael/DevOps/blob/144289f75dc8bfda62fe602863b997f2e014b696/mini-projects/aws.png)

*   ![](https://github.com/istephenmichael/DevOps/blob/e7114b839be95e6d8869b04a56869ccb0a8c1c0c/mini-projects/awsconsole.png)
* 
*   **[Note](pplx://action/followup):** Ensure you understand the limitations of the free tier to avoid unexpected charges.
*   **[Security Best Practice](pplx://action/followup):** Create a root user for initial setup, but subsequently create IAM users with specific permissions for daily use.
* ![]()

### 2. GitHub Account

*   **[Purpose](pplx://action/followup):** Version control, collaboration, and code hosting.
*   **[Action](pplx://action/followup):** Create a GitHub account. - https://github.com/
*   ![](https://github.com/istephenmichael/DevOps/blob/27bb45c197bc3864c301d9bcda49d0d04f5cbd62/mini-projects/github2.png)

*   ![](https://github.com/istephenmichael/DevOps/blob/e7114b839be95e6d8869b04a56869ccb0a8c1c0c/mini-projects/githubnew.png) 
*   **[Note](pplx://action/followup):** Enable two-factor authentication (2FA) for enhanced security.


## B. Software Installation and Configuration

### 1. VS Code (Code Editor)

*   **[Purpose](pplx://action/followup):** A versatile code editor for writing and editing code.
*   **[Action](pplx://action/followup):** Download and install VS Code for Windows from the official website 
  - https://code.visualstudio.com/
  - ![](https://github.com/istephenmichael/DevOps/blob/9f8f358e5ce9972927c94b1f8e213caf455e55ca/mini-projects/vscode.png)
  - ![](https://github.com/istephenmichael/DevOps/blob/9f8f358e5ce9972927c94b1f8e213caf455e55ca/mini-projects/vscode2.png)

*   **[Configuration](pplx://action/followup):** Install relevant extensions for your preferred programming languages.

### 2. MobaXterm (Remote Terminal)

*   **[Purpose](pplx://action/followup):** A comprehensive terminal emulator for connecting to remote servers and virtual machines.
*   **[Action](pplx://action/followup):** Download and install MobaXterm - https://mobaxterm.mobatek.net/download.html
*   ![](https://github.com/istephenmichael/DevOps/blob/f516767a81e9f0322bdde367c1422778c721d88b/mini-projects/mobaxterm.png)
  
 *   **[Configuration](pplx://action/followup):** Configure SSH keys for secure and password-less connections to remote servers.

### 3. Git for Windows (Version Control)

*   **[Purpose](pplx://action/followup):** Track changes to code, collaborate with others, and manage code effectively.
*   **[Action](pplx://action/followup):** Download and install Git for Windows - https://git-scm.com/downloads/win
*   ![](https://github.com/istephenmichael/DevOps/blob/9f8f358e5ce9972927c94b1f8e213caf455e55ca/mini-projects/git.png)
*   
*   **[Configuration](pplx://action/followup):** Configure Git with your name and email address:

    ```
    git config --global user.name "Your Name"
    git config --global user.email "your.email@example.com"
    ```
*   **[Verification](pplx://action/followup):** Use MobaXterm to verify Git installation by running `git --version`. 
*   ![](https://github.com/istephenmichael/DevOps/blob/d5fa5c51d71e9711cca02f3a1fe95d760ec5232b/mini-projects/git-version.png)

### 4. VirtualBox (Virtualization)

*   **[Purpose](pplx://action/followup):** Run multiple operating systems on a single machine for testing and development.
*   **[Action](pplx://action/followup):** Download and install VirtualBox - https://www.virtualbox.org/wiki/Downloads
*   ![](https://github.com/istephenmichael/DevOps/blob/01da347c01f10d06fbf4837d16e25ff3e34535bb/mini-projects/virtualbox.png)
*   **[Note](pplx://action/followup):** Enable Virtualization Technology (VT-x/AMD-V) in your BIOS/UEFI settings for optimal performance.

### 5. Ubuntu (Virtual Machine)

*   **[Purpose](pplx://action/followup):** A Linux distribution for development and testing.
*   **[Action](pplx://action/followup):**
    1.  Download the Ubuntu ISO file from the official website - https://ubuntu.com/download/desktop
    2.  ![](https://github.com/istephenmichael/DevOps/blob/9f8f358e5ce9972927c94b1f8e213caf455e55ca/mini-projects/ubuntu.png)
    3.  Create a new virtual machine in VirtualBox.
    4.  Mount the Ubuntu ISO file to the virtual machine.
    5.  Start the virtual machine and follow the on-screen instructions to install Ubuntu.
    6.

## 3. Workstation Recommendations

*   **[RAM](pplx://action/followup):** 8GB minimum, 16GB recommended for running virtual machines and resource-intensive applications.
*   **[Storage](pplx://action/followup):** SSD (Solid State Drive) for faster boot times and application loading.

## Conclusion

By following these steps, you should have a fully functional development environment ready for your projects. Remember to regularly update your tools and software to ensure you have the latest features and security patches.
