[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15264479&assignment_repo_type=AssignmentRepo)
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
answers
Step 1: Select Your Operating System (OS)
Download and Install Windows 11
Visit the Windows 11 Download Page.
Click on "Download now" and follow the instructions to create a bootable USB drive or install directly.
Follow the on-screen instructions to install Windows 11 on your machine.
I did not have to do all this since I already had windows 10 installed
Step 2: Install a Text Editor or Integrated Development Environment (IDE)
Download and Install Visual Studio Code
Go to the Visual Studio Code Download Page.
Download the installer for your operating system.
Run the installer and follow the setup instructions.
Open Visual Studio Code after installation.
Step 3: Set Up Version Control System
Install Git

Visit the Git Download Page.
Download the installer for your OS and run it.
Follow the setup instructions, using default settings if unsure.
Configure Git

Open a terminal or command prompt.
Set your username and email:
sh
Copy code
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
Create a GitHub Account

Visit GitHub and sign up for an account.
Initialize a Git Repository

Create a new project directory:
sh
Copy code
mkdir myproject
cd myproject
Initialize a Git repository:
sh
Copy code
git init
Create a README file and make your first commit:
sh
Copy code
echo "# My Project" >> README.md
git add README.md
git commit -m "Initial commit"
Push to GitHub:
sh
Copy code
git remote add origin https://github.com/yourusername/myproject.git
git push -u origin master
Step 4: Install Necessary Programming Languages and Runtimes
Install Python
Go to the Python Download Page.
Download the latest version of Python for your OS.
Run the installer and ensure "Add Python to PATH" is checked.
Verify the installation:
sh
Copy code
python --version
pip --version
Step 5: Install Package Managers
Install pip
Pip is included with Python 3.4+ installations. Verify pip installation:
sh
Copy code
pip --version
Upgrade pip to the latest version:
sh
Copy code
pip install --upgrade pip
Step 6: Configure a Database (MySQL)
Download and Install MySQL
Visit the MySQL Installer Page.
Download and run the installer.
Follow the setup wizard to install MySQL.
Verify the installation:
sh
Copy code
mysql --version
Step 7: Set Up Development Environments and Virtualization (Optional)
Install Docker
Visit the Docker Download Page.
Download and run the Docker Desktop installer.
Follow the setup instructions and start Docker.
Step 8: Explore Extensions and Plugins
Visual Studio Code Extensions
Open Visual Studio Code.
Go to the Extensions view (Ctrl+Shift+X).
Search for and install the following extensions:
Python
GitLens
Prettier - Code formatter
ESLint
Reflection on Challenges and Solutions
Challenges Faced:

Installation Issues:

Some installations, like MySQL, can be complex due to various configuration options.
Solution: Followed detailed online guides and documentation. Ensured correct versions were downloaded.
Configuring Git and GitHub:

Initial setup of Git and pushing to GitHub required precise steps.
Solution: Used GitHub's setup documentation and Git's help command (git help).
Environment Variables:

Adding Python and other tools to PATH was confusing.
Solution: Carefully followed installation prompts and double-checked PATH settings in system environment variables.
Extension Compatibility:

Some extensions might conflict or not work as expected.
Solution: Tested extensions one at a time and referred to extension documentation for troubleshooting.
Deliverables:
Setup Documentation:


Challenges faced during setup and strategies employed to overcome them as detailed above.






