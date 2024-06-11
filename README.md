[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15247749&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
   ![alt text](<Screenshot from 2024-06-11 16-18-54.png>)
    Open your browser and type in "Visual Studio Code"
    Click on the 1st VsCode Link to open the official site
    On their download page, choose the Windows option and click it
    Locate the installer file ".exe" and run it. Grant permission to the installer to make changes to your device.
    Read the license agreement and accept it, You can specify the installation location or leave it as default.
    You can click on additional tasks like the desktop icon and any other task you may want to add
    Click Next and finally Install
    Once the installation is complete, you can choose to launch it, or finish the setup and open it later.

    Prerequisites: WIndows 11 OS, Admin priviledges for application installations

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

   1) you can choose to change the theme of your editor. File > Preferences > Color Theme (light, dark)
   2) you can sync your editor to woke across multiple devices on File > Preferences > Settings Sync
   3) Install extensions youll need to use like Prettier, ESLint and any other language specific extensions
   4) Configure Git through the terminal. Install the git extension. (Configure your username and email too)

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

   1) Activity Bar - on the far left contains icons to switch between different views eg, Extensions, Explorer, Search, Run and Debug etc
   2) Side Bar: Next to the Activity Bar. Displays different panels based on the icon selected in the Activity Bar eg, the Explorer panel shows the file structure of your project.
   3) Editor Group: The central area where you write and edit your code. You can open multiple files in tabs and split the editor to view files side by side.
   4) Status Bar: Located at the bottom of the window. Provides information about the current file and workspace, such as language mode, Git branch, line and column numbers, and more.


4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

   THe command palette is a tool that appears at the top of the vscode and provides access to commands and functions in Vscode. It can be accessed by pressing "F1" 
   It can open file, run tasks, change language mode and open git commands 

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

   Extensions in Vscode provide support from external sources for different languages, debuggers, tools etc. You can find them at the activity bar under the "EXtensions" and searching for the desired extension and installing it. You can choose whether to enable, disable or uninstall them as a way of managing them. 

   For web development, we can use LIve SErver, ESLint for Javascript, Prettier for code formatting, Html5 extension etc

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

   On the top of the Vscode, click on View > Terminal > Open New Terminal. Once its open, you can run commands directly from there eg commit your changes to github (git add . , git commit -m "" , git push), run code eg python run main.py , npm start, npm run dev etc

   Advantages: 
   1) Offers a seamles workflow as there is no need to keep switching between it and say git bash, or an external terminal to execute  commands
   2) Customize terminal appearance and behaviour through settings

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

   On the Explorer, right click, select New File, New Folder according to your needs
   To open a file / folder : File > Open File / Open Folder , select the folder / file you want opened per your location file
   Once they are created, you can right click on them to either Rename, delete, move etc

   Efficient Navigation: 
   1) ctrl + p search by typing the file name
   2) Enable breadcrumbs to navigate file structure easily "View > Show Breadcrumbs" 
   3) use explorer panel to switch between them easily.

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

         Customizing Settings:
      Accessing Settings: 
      Go to File > Preferences > Settings or press Ctrl+,.

      Changing Theme:
      Navigate to File > Preferences > Color Theme.
      
      Adjusting Font Size:
      Search for "Font Size" in the Settings and adjust as needed.

      Modifying Keybindings:
      Go to File > Preferences > Keyboard Shortcuts or press Ctrl+K Ctrl+S.

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

         Setting Up and Starting Debugging:
      Open Debug View:
      Click the Run & Debug icon in the Activity Bar or press Ctrl+Shift+D.

      Configure Debugger:
      Create a launch.json file if prompted, which configures debug settings for your project.

      Set Breakpoints:
      Click in the margin next to the line numbers to set breakpoints.

      Start Debugging:
      Click the green play button in the debug view or press F5.


      Key Debugging Features:
         Breakpoints: Pause execution at specific lines.
         Watch Variables: Monitor variables for changes.
         Call Stack: View the call stack and navigate through function calls.
         Debug Console: Execute commands and evaluate expressions while debugging.

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

         Initialize Repository:

      Open the Source Control view by clicking the Source Control icon in the Activity Bar or pressing Ctrl+Shift+G.
      Click "Initialize Repository" to set up a new Git repository. "git init"

      Making Commits:
      Stage changes by selecting files and clicking the plus icon or using the git add command in the terminal.
      Enter a commit message in the input box and click the checkmark icon or use the git commit command.
      "git add . "
      "git commit -m "changes you want made"

      Pushing Changes to GitHub:
      Set up a remote repository on GitHub and copy the repository URL.
      Use the terminal to add the remote: git remote add origin [URL].
      Push changes with git push -u origin master (or the relevant branch name).
      "git push"


 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

