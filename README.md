# Environment Setup Documentation

This document outlines the steps I took to set up my development environment, including the installation of Visual Studio Code, VirtualBox, Ubuntu, and the setup of GitHub and AWS accounts. Screenshots are included for better clarity.


#### Tools needed to be installed

1. Vsisual Studio code
2. Git
3. Virtual Box
4. Ubuntu on Virtual box (Mac OS)

#### Accounts to be created

1. Github account
2. Amazon Web Services (AWS) Account

---

## 1. Installing Visual Studio Code

I was able to successfully install Visual Studio Code by following these steps:

1. Navigated to the [official Visual Studio Code website](https://code.visualstudio.com/).
2. Downloaded the macOS installer.
3. Opened the downloaded file and followed the installation prompts.
4. Verified the installation by launching Visual Studio Code.

Here is the screenshot of Visual studio code welcome screen as I already have it installed on my laptop.

**Visual Studio Code Screenshot:**  
![Screenshot for vscode installation](images/vs-code-welcome-screen.png)

---

## 2. Installing Git

I was able to successfully install Git by:

1. Opened the Terminal on macOS.
2. Ran the following command to install Git using Homebrew:

   ```bash
   brew install git
   ```

   Verify Installation:

   ```
   git --version
   ```

   Basic Git Setup:

   ```
   git config --global user.name "Ajaezo Kingsley"
   git config --global user.email "ajaezokingsley@gmail.com"
   git init
   git add .
   git commit -m "Initial commit"
   ```

   **Git website homescreen:**  
   ![Screenshots for git setup](images/git-website-homepage.png)

   **Brew Installation guide:**  
   ![Screenshots for git setup](images/brew-download-git-installation.png)

   **Brew Installation confirmation:** Though I already had git installed on my machine
   ![Screenshots for git setup](images/git-screenshots.png)

---

## 3. Installing VirtualBox

I was able to successfully install VirtualBox by doing the following:

1. Visited the [official VirtualBox website](https://www.virtualbox.org/).
2. Downloaded the macOS version of VirtualBox.
3. Opened the installer and followed the on-screen instructions.
4. Confirmed the installation by launching VirtualBox.

**Screenshots:**

**Download Page:**  
![Virtual box installation screenshots](images/virtual-box-download.png)

**Welcome Screen:**  
![Virtual box installation screenshots](images/virtual-box-welcome-screen.png)

---

## 4. Installing Ubuntu

I was able to successfully install Ubuntu on VirtualBox by:

1. Downloaded the Ubuntu ISO file from the [official Ubuntu website](https://ubuntu.com/).
2. Created a new virtual machine in VirtualBox and selecting the downloaded ISO file.
3. Followed the installation steps within the virtual machine.
4. Ensured Ubuntu was running correctly in VirtualBox.

**Screenshot of Ububtu's login terminal:**  
![Screenshot for Ubuntu](images/ubuntu.png)

**Screenshot of Ububtu's login terminal on Virtual box:**  
![Screenshot for Ubuntu](images/ubuntu's-terminal.png)

**Screenshot of Ububtu's login terminal:**  
![Screenshot for Ubuntu](images/ubuntu's-desktop-on-virtual-box.png)

---

## 5. Setting Up a GitHub Account

I was able to successfully set up my GitHub account by:

1. Visited the [GitHub website](https://github.com/).
2. Clicked on "Sign up" and filling in the required details.
3. Verified my email address and completing the account setup process.
4. Configured Git on my local machine to connect with my GitHub account.

**Screenshot:**  
![Screenshots for github account setup](images/git-profile-screenshot.png)

---

## 6. Setting Up an AWS Account

I was able to successfully set up my AWS account by:

1. Navigated to the [AWS website](https://aws.amazon.com/).
2. Clicked on "Create an AWS Account" and providing the necessary information.
3. Verified my identity and payment details.
4. Logged into the AWS Management Console to confirm the setup.

**Screenshot:**  
![Screenshot for AWS account setup](images/aws.png)
