
## Tech Environment Setup Guide

This document outlines the necessary steps and tools for setting up a development environment. It covers essential software installation, account creation, and workstation recommendations.

## Prerequisites

Before proceeding, ensure your system meets the following minimum requirements:

*   **Operating System:** Windows (recommended for VSCode and Git integration)
*   **Memory:** 8GB RAM minimum (16GB recommended for virtualization)
*   **Internet Connection:** A stable internet connection is required for downloading software and accessing online services. Consider a backup internet solution for uninterrupted workflow.

## A. Account Setup

### 1. AWS Account

*   **Purpose:** Access to cloud computing resources for development and deployment.
  
*   **Action:** Create a free tier AWS account. - https://aws.amazon.com/
    ![](https://github.com/istephenmichael/DevOps/blob/713a0f7e0b4d5e184816a4879287c579bf77219e/mini-projects/aws_free_tier.png)

    ![](https://github.com/istephenmichael/DevOps/blob/713a0f7e0b4d5e184816a4879287c579bf77219e/mini-projects/aws_signin.png)
  
*   **Note:** Ensure you understand the limitations of the free tier to avoid unexpected charges.
  
*   **Security Best Practice:** Create a root user for initial setup, but subsequently create IAM users with specific permissions for daily use.
  
* **AWS Management Console Console**
 ![](https://github.com/istephenmichael/DevOps/blob/e7114b839be95e6d8869b04a56869ccb0a8c1c0c/mini-projects/awsconsole.png)



### 2. GitHub Account

*   **Purpose:** Version control, collaboration, and code hosting.
  
*   **Action:** Create a GitHub account. - https://github.com/

     ![](https://github.com/istephenmichael/DevOps/blob/3fcb44acccca383659015c8c428ca8a23562b73f/mini-projects/github_home.png)
  
*   **Note:** Enable two-factor authentication (2FA) for enhanced security.
  
*  **GitHub User Account Setup dashboard**

  ![Github_dashboard](https://github.com/istephenmichael/DevOps/blob/ecf36556325819cdc3768f68cf34989ecd402644/mini-projects/githubnew.png)


## B. Software Installation and Configuration![]()

### 1. VS Code (Code Editor)

*   **Purpose:** A versatile code editor for writing and editing code.
  
*   **Action:** Download and install VS Code for Windows from the official website - https://code.visualstudio.com/

    ![vscode_download](https://github.com/istephenmichael/DevOps/blob/b6e6619935661404b93dea67c986ffeefb609b8d/mini-projects/vscode.png)
  
  **VS Code download page**
   ![vscode_download](https://github.com/istephenmichael/DevOps/blob/21372abac13f4439afb8d583882013ff769e32c8/mini-projects/vscode01.png)
  
*   **Configuration:** Install relevant extensions for your preferred programming languages.
  
* VS Code Welcome Screen
  ![vscode_screen](https://github.com/istephenmichael/DevOps/blob/21372abac13f4439afb8d583882013ff769e32c8/mini-projects/vscode02.png)

### 2. MobaXterm (Remote Terminal)

*   **Purpose:** A comprehensive terminal emulator for connecting to remote servers and virtual machines.
  
*   **Action:** Download and install MobaXterm - https://mobaxterm.mobatek.net/download.html
  
  **MobaXterm download page:** 
  ![MobaXterm](https://github.com/istephenmichael/DevOps/blob/21372abac13f4439afb8d583882013ff769e32c8/mini-projects/mobaxterm.png)
  
* **Configuration:** Configure SSH keys for secure and password-less connections to remote servers.

### 3. Git for Windows (Version Control)

*   **Purpose:** Track changes to code, collaborate with others, and manage code effectively.
  
*   **Action:** Download and install Git for Windows - https://git-scm.com/downloads/win
  
  **Git download page:** 
![git_win](https://github.com/istephenmichael/DevOps/blob/21372abac13f4439afb8d583882013ff769e32c8/mini-projects/git.png)

*   **Configuration:** Configure Git with your name and email address:

    ```
    git config --global user.name "Your Name"
    git config --global user.email "your.email@example.com"
    ```
*   **[Verification](pplx://action/followup):** Use MobaXterm to verify Git installation by running `git --version`.
  
  **Git Installation Confirmation page:** 
![git_win2](https://github.com/istephenmichael/DevOps/blob/21372abac13f4439afb8d583882013ff769e32c8/mini-projects/git-version.png)

### 4. VirtualBox (Virtualization)

*   **Purpose:** Run multiple operating systems on a single machine for testing and development.
*   **Action:** Download and install VirtualBox - https://www.virtualbox.org/wiki/Downloads
    
    ![virtualbox](https://github.com/istephenmichael/DevOps/blob/7e7a14245026fa94dd66ee9532c5c8dc5dcaf4a6/mini-projects/virtualbox.png)
       
  ![[virtualbox 1.png]]
*   **Note:** Enable Virtualization Technology (VT-x/AMD-V) in your BIOS/UEFI settings for optimal performance.

### 5. Ubuntu (Virtual Machine)

*   **Purpose:** A Linux distribution for development and testing.
*  **Action:**
    1.  Download the Ubuntu ISO file from the official website - https://ubuntu.com/download/desktop

    ![ubuntu](https://github.com/istephenmichael/DevOps/blob/f0717ea639a6a917a4e4f913ff9e0520edae4912/mini-projects/ubuntu.png)
    
    2.  Create a new virtual machine in VirtualBox.
    3.  Mount the Ubuntu ISO file to the virtual machine.
    4.  Start the virtual machine and follow the on-screen instructions to install Ubuntu.
    5.

## 3. Workstation Recommendations

*   **RAM:** 8GB minimum, 16GB recommended for running virtual machines and resource-intensive applications.
  
*   **Storage:** SSD (Solid State Drive) for faster boot times and application loading.

## Conclusion

By following these steps, you should have a fully functional development environment ready for your projects. Remember to regularly update your tools and software to ensure you have the latest features and security patches.
