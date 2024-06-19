# Dev_Setup
Setup Development Environment
#Assignment: Setting Up My Developer Environment

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

**MAIN QUESTION**:
Q-9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 
   
**DOCUMENTATION**:
**ANSWERS**

1. Select Your Operating System (OS):Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11.

**ANS**: I already had windows 11 install long before the course program began: Screenshot ref below:
<img src = "" width="" height="">

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code.

**ANS**:
- Downloaded the installer:
<img src = "" width="" height="">

- Ran the downloaded installer:
<img src = "" width="" height="">

- Followed through the installation process: 
<img src = "" width="" height="">

- Launched the IDE and configured the necessary extensions:
<img src = "" width="" height="">

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit.

**ANS**: 
- Downloaded Git installer:
<img src = "" width="" height="">
<img src="" width="" height="">

Note: took the following steps to install git;
      ----------------------------------------
- Ran the installer setup, Read and accepted the GNU General Public License.
- Left the default installation folder as was and clicked next onto the "Select components window
- On the "default editor" used by Git, I selected "Use Vim (the ubiquious text editor) as Git's default editor
- Left the default initial branch as "master"
- on the next window, I picked the "Git from the command line and also from 3rd-party software" option
- choose the "use bundled OpenSSH" SSH executable option
- chose "use the OpenSSL library"
- chose the "Checkout window-style, commit Unix-style line endings" option for line ending conversions window.
- Terminal emulator to use with Git Bash was left at default
- The default behavior of Git pull was optioned at "Fast-forware or Merge" option.
- credential helper was picked at "Git credential Manager"
- Then enabled file system caching on the "Config extra options"
- The finally picked "Install" all configurations and allowed Git to make changes to my computer system.

- Finally finished the installation.
<img src="" width="" height="">

- Verified if git is installed correctly:
<img src="" width="" height="">

- Created Github Acc:
<img src ="" width="" height="">

Initialized Git repository and First commit:
# new repo: 
<img src="" width="" height=""> 

# Git bash dir commands: 
<img src="" width="" height="">

# README.md file: 
<img src="" width="" height="">

# Completed First Commit repo results: 
<img src="" width="" height="">

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
  **ANS**
  **a**. PYTHON INSTALLATION:
  - Downloaded the latest installer from "http://www.python.org"
  <img src="" width="" height="">

  - Ran the python installer and ticked the "add python.exe to PATH" options
  <img src="" width="" height="">
  
  - Setup begin installation process:
  <img src="" width="" height="">

  - Setup completed installation:
  <img src="" width="" height="">

  - Checked the environment variables to ensure that the python installer "add python.exe to PATH" option added the path to my user system path.
  <img src="" width="" height="">

  - checked if the pip was also installed:
  <img src="" width="" height="">

  **b**. DART INSTALLATION:
  -  Downloaded the Dart SDK (zipped)
  <img src="" width="" height="">

  - Extracted the SDK folder using WinRAR and placed it in the local disk C:
  <img src="" width="" height="">
  
  - Copied the path of the SDK and created an environment path in my user path system env:
  <img src="" width="" height="">

  - Verified correct installation via Git Bash:
  <img src="" width="" height="">

  **c**. FLUTTER INSTALLATION:
   
  - Downloaded the flutter SDK:
 <img src="" width="" height="">

  - Extracted the files and moved them to the local disk C:
<img src="" width="" height="">

  - Copied the flutter path and made changes to my system env user path to add flutter\bin:
  <img src="" width="" height="">
  
  - Created a path for Flutter in my User Sys-environment path:
  <img src="" width="" height="">

  - Checked flutter doctor to see if I needed to install other features or dependencies:(after which, I downloaded "Android Studio" as well)
  # flutter doctor: <img src="" width="" height="">
  # android studio: <img src="" width="" height="">

  - Created a dart file (index.dart) to test the "flutter devices" and "flutter emulators --launce <device name>" commands as seen below:
  # flutter devices: <img src="" width="" height="">
  # Flutter emulators: <img src="" width="" height="">

5. Install Package Managers:
   If applicable, install package managers like pip (Python).
**ANS** pip package manager installed with the python installation: Refer to verification screenshot attached below:
# Pip package manager: <img src="" width="" height="">


6. Configure a Database (MySQL):
   Download and install MySQL database.

**ANS**
- Downloaded the MySQL installer community.exe file:
<img src="" width="" height="">
- Ran the installer and chose "Server only" under "Choosing setup type option"
<img src="" width="" height="">

- Type & Networking: chose the "Development Computer" under Server Configuration Type (Config Type)
<img src="" width="" height="">
 i. Ensured that TCP/IP were ticked, PORT # = 3307, X Protocol Port = default "33060
 ii. Ticked both "Named Pipe" & "Shared memory" and kept the pipe and memory names at "MYSQL" for both
 iii. Ticked "Show advanced and Logging Options" and clicked Next

**Further instructions**:
- Under "Authentication Method", I left the option at the default (RECOMMENDED OPTION) and Next.
- Accounts and Roles window: created a password, for both input boxes, checked them and proceeded on to the next.
<img src="" width="" height="">

- Logging Options: Ticked [General Log], [Slow Query Log], [Bin Log] and clicked Next
- Server File Permissions: I granted full access to the user running the windows service and Admins only option.
<img src="" width="" height="">

- Applied the configurations by clicking Execute
<img src="" width="" height="">


- Checked via git bash to verify installation:
<img src="" width="" height="">

- Tested db access via MySQL CLC:
<img src="" width="" height="">

- Tested MySQL-Workbench:
<img src="" width="" height="">


7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

**ANS** (Dev Environments and Virtualization for Python "Steps"):
- opened my Git bash and use the commands; 
- "pip install virtualenv" (to install the virtual environment).
- cd downloads/pythonproject/ (target dir for venv)
- "virtualenv" (to create the virtual environment)
- pythonproject\Scripts\activate (Activated my virtual environment using, for windows)
- pip install -r requirements.txt (to install project dependencies)


8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

   **ANS**
   i. EXTENSIONS EXPLORED AND CONFIGURED:
   - Code Runner
   - Dart
   - Django
   - Flutter
   - GitHub Pull Request
   - JSON Crack
   - Prettier Code Formatter
   - Pylance
   - Python
   - Python Debugger
   - SQLite 
   - SQLite Viewer
   - Tailwind CSS intelliSense
   - . NET Install Tool
   - HTML CSS Support

   ii. PLUGINS INSTALLED:
   - Code Gpt
   - Path Intellisense
   - Markdownlint

   iii. Add-ons:
   - Jupyter
   - Azure Tools (for DevOps and Cloud)
   - Docker

   iv. Version Control Integrations:
   - GitLens
   - GitHub via Source Control


9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

    **ANSWERED AND DELIVERED ABOVE**

**DELIVERABLES**
a. Document detailing the setup process with step-by-step instructions and screenshots where necessary. **COMPLETED ABOVE**

b.  A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore). **USE LINK FOR VIEWING SAMPLE PROJECT: <https://github.com/Chilundika/SAMPLE_PROJECT.git>**

# created new repo: 
<img src="" width="" height="">

# cloned new repo to local machine: 
<img src="" width="" height="">

# (.gitignore) config available in cloned repo: 
<img src="" width="" height="">

# Opened repo in Vs code to create the sample project: 
<img src="" width="" height="">

# Tested the sample project: 
<img src="" width="" height="">

# Added, Commited, Pushed and updated the repository on github: 
<img src="" width="" height="">

c.  A reflection on the challenges faced during setup and strategies employed to overcome them. 

**CHALLENGES FACED**
- i. *Configuring Git*: after my successful installation while being guided by the instructors, my main challenge was configuring git because I kept forgetting to use the command, "git config --global user.email "my_githubemail" & "git config --global user.name "github_handle" **Solution**: I kept on practicing with git commands and github repo creations and deletions (for practice reasons)

- ii. *Git commands*: Proper and sequential execution of git commands to initialize a local repo and push or commit was confusing. **Solution**: I watched some youtube tutorials on how to use Git and Gitbash commands to ensure best practices.

- iii. *Errors during the Environment Setup*: I encountered errors at first as a result of my antivirus being active and continously blocking "controlled access admin permissions" to prevent system changes. **Solution**: I would temporarily deactivate my "Controlled access admin permissions" just so my installations could go through, which they did. 

- iv. *Configuring MySQL Port Number*: This was as a result of the default port "3306" already being used by "XAMPP". **Solution**: I had to change the for MySQL Community port number from "3306" to "3307" as this new one was readily available.

- v. *VS CODE EXTENTIONS*: Before having to engage with the instructor's lecturers, I had personally atempted to install extensions, then later uninstalled VS code. **Solution**: I received the proper guidance by watching the lecture videos setup by PLP LMS platform and additionally read the community recommendations

