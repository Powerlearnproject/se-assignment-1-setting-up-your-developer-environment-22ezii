[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15291640&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.


Answers


Objective:
To set up a robust and efficient developer environment conducive to coding, debugging, version control, and collaboration.

Tasks and Deliverables:
1. Select and Install Operating System (Windows 11)
Instructions:

Visit the Windows 11 Download Page:

Go to Windows 11 Download.
Download Windows 11:

Click the “Download Now” button and follow the prompts to download the Windows 11 Installation Assistant.
Run the Installation Assistant:

Double-click the downloaded file to start the Installation Assistant.
Follow the on-screen instructions to install Windows 11. Your PC will restart several times during the installation process.
Deliverables:

Confirm successful installation by navigating to Settings > System > About and verify the version number is Windows 11.
2. Install Visual Studio Code
Instructions:

Visit the Visual Studio Code Download Page:

Go to Visual Studio Code Download.
Download VS Code:

Click on the download button for Windows to get the installer (VSCodeUserSetup-x64-x.y.z.exe).
Run the Installer:

Locate the downloaded file and double-click to run it.
Accept the license agreement, choose the installation location, and select additional options like adding VS Code to PATH.
Complete the installation and launch VS Code.
Deliverables:

Screenshot of VS Code open on your desktop.
3. Set Up Version Control System
Instructions:

Install Git:

Visit Git Downloads and download the Git installer.
Run the installer and follow the default installation steps.
Configure Git:

Open Git Bash from the Start menu.
Set up your name and email using the commands:
bash
Copy code
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
Create a GitHub Account:

Go to GitHub and sign up for a free account.
Initialize a Git Repository:

Open VS Code, create a new folder for your project.
Open a terminal in VS Code (Ctrl + ) and run:
bash
Copy code
git init
echo "# My Project" >> README.md
git add README.md
git commit -m "Initial commit"
Deliverables:

Link to your GitHub repository with the initial commit.
Screenshot of the Git Bash window showing the configuration.
4. Install Python
Instructions:

Visit the Python Download Page:

Go to Python Downloads.
Download Python:

Click the download button for the latest release.
Run the Installer:

Locate the installer and run it.
Ensure "Add Python to PATH" is checked, then click "Install Now."
Verify Installation:

Open Command Prompt and type python --version to verify the installation.
Deliverables:

Screenshot of the Command Prompt showing the Python version.
5. Install pip
Instructions:

Install pip (if not included with Python):

Typically, pip is included with Python. Verify by typing pip --version in Command Prompt.
Upgrade pip:

Run the command python -m pip install --upgrade pip.
Deliverables:

Screenshot of the Command Prompt showing the pip version.
6. Configure MySQL Database
Instructions:

Visit MySQL Download Page:

Go to MySQL Community Downloads.
Download MySQL Installer:

Click the download button and save the installer.
Run the Installer:

Select the setup type (Developer Default is recommended).
Follow the prompts to install MySQL Server and other components.
Configure MySQL:

During installation, set up the root password and configure MySQL Server as needed.
Verify Installation:

Open MySQL Workbench or Command Line and connect to your MySQL server.
Deliverables:

Screenshot of MySQL Workbench connected to your local MySQL instance.
7. (Optional) Set Up Development Environments and Virtualization
Instructions:

Install Docker:

Go to Docker Desktop and download Docker Desktop for Windows.
Follow the installation instructions on the website.
Run Docker:

Open Docker Desktop and ensure it starts successfully.
Deliverables:

Screenshot of Docker Desktop running.
8. Explore Extensions and Plugins
Instructions:

Open VS Code and Navigate to Extensions:

Click on the Extensions icon or press Ctrl + Shift + X.
Install Essential Extensions:

Search for and install extensions such as:
Prettier: Code formatter.
ESLint: Linter for JavaScript.
Python: Support for Python.
GitLens: Enhances Git capabilities in VS Code.
Deliverables:

List of installed extensions and their purposes.
Screenshot of the Extensions tab showing installed extensions.
9. Document Your Setup
Instructions:

Create a Document:

Open your preferred word processor or text editor.
Document Each Step:

Detail the steps taken for each task.
Include screenshots where necessary.
Note any challenges faced and how you resolved them.
Deliverables:

A comprehensive document (.docx, .pdf, or .md) detailing your setup process.
Include screenshots and explanations for each task.
10. Reflection
Instructions:

Reflect on the Process:
Describe any difficulties encountered during the setup.
Explain how you overcame those challenges.
Deliverables:

A reflection section at the end of your setup document.
Sample Documentation Outline
Title: Setting Up Your Developer Environment

Introduction:

Overview of the setup process and its importance.
1. Installing Windows 11:

Steps with screenshots.
2. Installing Visual Studio Code:

Steps with screenshots.
3. Setting Up Version Control System:

Steps with screenshots and GitHub repository link.
4. Installing Python:

Steps with screenshots.
5. Installing pip:

Steps with screenshots.
6. Configuring MySQL Database:

Steps with screenshots.
7. Optional: Setting Up Docker:

Steps with screenshots.
8. Exploring Extensions:

List of extensions with purposes and screenshots.
9. Reflection:

Challenges and solutions.
Appendices (Optional):

Additional resources or tools explored.
Sample GitHub Repository
Create a New Repository:

Go to GitHub and click "New" to create a new repository.
Name it appropriately, e.g., developer-environment-setup.
Push Initial Code:

Add a simple README and a .gitignore file for your project.
Include configuration files like requirements.txt for Python or docker-compose.yml if using Docker.
Deliverables:

Link to the repository with the initial setup and configuration files.
Example Reflection
During the setup, I faced an issue with installing Python due to a corrupted download. I resolved this by clearing the browser cache and re-downloading the installer from the official site. The integration of GitHub with VS Code was seamless, but understanding how to commit and push changes required reading the Git documentation thoroughly.


