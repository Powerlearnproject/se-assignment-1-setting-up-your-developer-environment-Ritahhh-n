[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15292691&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. . Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

Operating System: Microsoft Windows 11
Steps 
Download Microsoft Windows 11 by visiting the official website
If available on your PC, upgrade to the latest version.
https://www.microsoft.com/software-download/windows11

Installation Process:
 Ensure your PC meets the minimum system requirements.
Back up your important files.
Follow the installation steps.
![alt text](image.png)

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

   INSTALLATION OF AN IDE
   Download the VS code by visiting the Visual Studio download website and clicking on it.
   Select the appropriate version and click on the download button
   https://code.visualstudio.com/download
   ![alt text](image-1.png)

    Installation Process:
   Run the downloaded installer.
   Follow the installation wizard, accept the license agreement, and choose the installation location.
   ![alt text](image-2.png)
   Select additional tasks such as adding to PATH and creating a desktop icon.
   Launch VS Code and install recommended extensions 
   ![alt text](image-3.png)

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com
   VERSION CONTROL SYSTEM
   Install Git by searching it on the official website such as the one below. 
   https://git-scm.com/download/win
   Run the installer and follow the setup instructions, choosing your preferred options for PATH, line endings, and other settings.
    Create a GitHub Account:
   - Visit [GitHub](https://github.com) and sign up for a new account if needed.
   ![alt text](image-4.png)

    Initialize a Git Repository:
   - Open Git Bash or the terminal in VS Code.
   - Navigate to your project directory or create a new one:
  ```bash
  mkdir my_project
  cd my_project
  ```
   - Initialize a Git repository:
  ```bash
  git init
  ```
   - Create a README file:
  ```bash
  echo "# My Project" >> README.md
  ```
   - Add the README file to the staging area:
  ```bash
  git add README.md
  ```
   - Commit the changes:
  ```bash
  git commit -m "Initial commit"
  ```
   ![alt text](image-5.png)

4. Install Necessary Programming Languages and Runtimes:
  Install Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

  Python Download
  Download Python by visiting the official website
  https://www.python.org/
  Download the latest and most suitable version for your device
  ![alt text](image-7.png)

  Installation Process:
   Run the installer and check the option to add Python to PATH.
   Follow the installation wizard.
   If already installed one can repair the changes for more efficient working
   ![alt text](image-8.png)

   Verify Installation:
   - Open the Command Prompt and type:
  ```bash
  python --version
  ```
   - Verify pip installation:
  ```bash
  pip --version
  ```
   ![alt text](image-9.png)
   




5. Install Package Managers:
   If applicable, install package managers like pip (Python).
Installation of PIP
   Verification of pip Installation:
    Verify pip:
   - Open the Command Prompt and type:
  ```bash
  pip --version
  ```
![alt text](image-10.png)

6. Configure a Database (MySQL) Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
Download of MySQL
   Download MySQL from the official website below
   https://dev.mysql.com/downloads/installer/
   Download the required version for your device
   ![alt text](image-11.png)

    Installation 
     Run the MySQL Installer and follow the setup wizard.
     Choose the setup type (e.g., Developer Default).
     Configure MySQL Server settings, including the root password.
     ![alt text](image-12.png)

     Open MySQL 


7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.
Docker Download
   . Download Docker by visiting the Docker Desktop download page 
   https://docs.docker.com/desktop/install/windows-install/
   - Download and run the Docker Desktop installer.
   ![alt text](image-13.png)

   Installation Process:
   Follow the installation instructions
   Start Docker Desktop and follow the setup wizard.



8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
Procedure
   Open VS Code.
   - Go to the Extensions view (`Ctrl+Shift+X`).
   - Search for and install the following extensions:
  Python
  GitLens — Git supercharged
  Prettier - Code formatter
  ESLint
  MySQL
  Code runner

  ![alt text](image-14.png)

9. Document Your Setup:
    Create a comprehensive document outlining the steps taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 
    
    Challenges: One of the challenges faced was how to download and install MySQL 
    Solution: Watched several tutorials on the correct process and could install it easily.


