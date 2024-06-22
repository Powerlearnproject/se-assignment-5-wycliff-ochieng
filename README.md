[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15311252&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

   prerequisites
Make sure you have Windows 11 installed on your computer.
Installing software on your machine may require administrative privileges.
steps:
(a)Open your preferred web browser and go to the official Visual Studio Code download page

(b)On the Visual Studio Code homepage, click on the "Download for Windows" button. This will download the installer file 

(c)Run the Installer:Once the download is complete, locate the installer file in your Downloads folder or the location where you saved it.Double-click on the installer file to run it.

(d)You may see a User Account Control (UAC) prompt asking if you want to allow the app to make changes to your device. Click "Yes" to proceed.The Visual Studio Code Setup Wizard will open. Click "Next" to continue.

(e)Read through the license agreement, then click the "I accept the agreement" checkbox.Click "Next" to proceed.

(f)Choose the destination folder where you want Visual Studio Code to be installed. The default location is usually fine. Click "Next."

(g)Select whether you want to create a Start menu folder, add VS Code to your PATH,

(h)Click "Install" to begin the installation process. Wait for the installation to complete.

(i)Once the installation is complete, click "Finish" to close the Setup Wizard.

(j)Open Visual Studio Code: You can find Visual Studio Code in your Start menu or by searching

To enhance your development experience, you might want to install extensions. Click on the Extensions view icon on the Sidebar or press Ctrl+Shift+X to open the Extensions view.
Search for popular extensions like Python, C++, JavaScript, or whatever languages and tools you are using, and click "Install" for the ones you need.(REFRENCES visual studio code documentation)



2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

   (a)Install Key Extensions:

Go to the Extensions view (Ctrl+Shift+X) and install essential extensions like:
Prettier - Code formatter: Automatically formats your code.
ESLint: Integrates ESLint into VS Code to identify and fix JavaScript issues.
Python: Adds support for Python development.
Live Server: Launch a local development server with live reload.
GitLens: Enhances Git capabilities within VS Code.
   
   (b)Customize Settings:

Open settings (Ctrl+,) and adjust:
Editor: Word Wrap: Enable word wrap to avoid horizontal scrolling.
Editor: Tab Size: Set your preferred tab size (e.g., 2 or 4 spaces).
Editor: Font Size: Set a comfortable font size (e.g., 14px).
Workbench: Color Theme: Choose a theme that suits your preference, such as "Dark+"
Files: Auto Save: Set to "afterDelay" to automatically save changes.

   (c)Configure Default Formatter:

Set Prettier as the default formatter:
Open settings (Ctrl+,), search for "default formatter", and select esbenp.prettier-vscode.
(REFRENCES visual studio code documentation)


3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

   (a)activity bar
   Located on the far left, it allows quick access to different views like Explorer, Search, Source Control, Run & Debug, and Extensions.

   (b)side bar
   Displays contextual information and tools for the selected activity from the Activity Bar, such as the file explorer, search results, or version control changes.

   (c)Editor group
   The main area where you open and edit files. You can split the editor into multiple groups to view and work on multiple files simultaneously.

   (d)Status bar
   Located at the bottom, it shows information about the current file and project, such as line/column number, encoding, language mode, and git branch status.
   (REFRENCES visual studio code documentation)

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

   Open it by pressing Ctrl+Shift+P or F1.

    common Tasks:
    (a)Search and install extensions: Extensions: Install Extensions
    (b)Change color theme: Preferences: Color Theme
    (c)Format document: Format Document
    (d)Open settings: Preferences: Open Settings
    (REFRENCES visual studio code documentation)

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

   Extensions enhance the functionality of VS Code by adding support for additional languages, debuggers, tools, and more.
   It is accessed by opening  the Extensions view (Ctrl+Shift+X), search for the desired extension, and click "Install".
   popular extensions for web development include:
   HTML Snippets
   CSS IntelliSense
   JavaScript (ES6) code snippets
   Debugger for Chrome
   (REFRENCES visual studio code documentation)

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

   Use the shortcut Ctrl+ or go to View > Terminal.
   Using the Terminal:Run shell commands directly within VS Code, manage project files, and execute scripts without leaving the editor.

   advantages are:
   -Streamlined workflow by eliminating the need to switch between VS Code and an external terminal.
   -Supports multiple terminal instances and types (e.g., PowerShell, Command Prompt, Git Bash).
   (REFRENCES visual studio code documentation)


7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

   Use the Explorer view in the Side Bar then Right-click in the Explorer view to create new files or folders.
   Drag and drop files/folders into the Explorer to open them.

   To navigate, open files and change directories Use Ctrl+P to quickly open files by name.
   Use breadcrumbs at the top of the editor to navigate the file structure.
   (REFRENCES visual studio code documentation)


8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

   To find settings go to File > Preferences > Settings.

   To change theme open settings search theme and set your prefered theme
   To change font size go to setting and search font size and set your prefferd size
   To customize keybindings go to file then preferences and lastly keyboard shortcuts
   

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

   Setting Up Debugging:
Open the Debug view from the Activity Bar or press Ctrl+Shift+D.
Click on "create a launch.json file" to configure the debugger for your environment.

Starting Debugging:
Set breakpoints by clicking in the gutter next to the line numbers.
Press F5 to start debugging.
Key Debugging Features:

Breakpoints: Pause execution at specific lines.
Watch: Monitor variables and expressions.
Call Stack: View the call stack to trace function calls.
Debug Console: Evaluate expressions and interact with the debugger.
(REFRENCES visual studio code documentation)

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

    Integrating Git:
Open the Source Control view from the Activity Bar or press Ctrl+Shift+G.
Initialize a repository by clicking on "Initialize Repository".

Making Commits:
Stage changes, write a commit message, and click the commit button.

Pushing Changes to GitHub:
Set up a remote repository by running git remote add origin <repo-url> in the integrated terminal.
Push changes using the command git push -u origin main.
(REFRENCES visual studio code documentation)

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

