[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15279495&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

   steps to download vs code.
   Open a web browser and go to the Visual Studio Code website.
   Click the "Download for Windows" button. This will download the installer.
  ![alt text](<Screenshot (16).png>) 
  
  Installing visual studio code
  Run the installer,locate the installer and double click to start the installation process.

  Follow the installation process wizard.
  Accept the license agreement.
  Choose the installation location or use the default path.
  Select additional tasks (optional but recommended):
  Create a desktop icon.
  Add "Open with Code" action to Windows Explorer file context menu.
  Add "Open with Code" action to Windows Explorer directory context menu.
  Register Code as an editor for supported file types.
  Add to PATH 

  complete the installation.
  This is done by Clicking "Install" to begin the installation.
  After that one can choose to launch VS Code immediately by checking the "Launch Visual Studio Code" box and clicking "Finish".

  Prerequisites
  A 64-bit version of Windows 10
  Stable internet connection.
  Admin priveldges to install vs code
2. First-time Setup:

- After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

cofigurations
  User setting i.e font size,auto save and light height
  Themes and icons ie dark or light mode as per your preference,I opted for dark mode.

  Essential extensions
  Language support for python,html/css
  Code Formatting eg code formatter
  git and version control
  productivity enhancer eg live server and docker
  debugger and testing 

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

   Activity bar

   Its located on the left side of vs code window
   Allows userd switch between different views and acces commonly used features and extension
   components include 
   explorer for files and  manage projects  files and folders
   search used to search as the name suggest
   source control to provide access to version control system
   Run and debug allowing a user   run and debug applications
   Extensions to let user install,manage and browse extensions

   Status Bar
    The Status Bar is located at the bottom of the VS Code window.
    provides information about the current state of the editor and workspace, and it offers quick access to certain functionalities.
   Components:
    Current Branch: Shows the current Git branch.
    Encoding: Displays the file's character encoding.
    Line and Column: Indicates the current cursor position in the file 
    Language Mode: Shows the language mode of the currently open file.
    Notifications: Displays alerts and messages.
    Indentation: Shows the current indentation setting.
    Live Server: If the Live Server extension is installed, provides a button to start/stop the server.

   Editor Group
    Located at the central part of vs code
    code files are opened, edited, and displayed in editor groups
   Components:
    Tabs: Each open file is represented by a tab at the top of the Editor Group. Tabs allow switching between open files.
    Editor Area: The main area where the contents of the selected file are displayed and edited.
    Split View: Users can split the editor into multiple groups to view and edit files side by side.
    Breadcrumps: Display the current file's location in the project hierarchy and allow quick navigation.

   Side Bar
     located next to the Activity Bar, on the left side of the window.
     displays different panels based on the selected activity from the Activity Bar. 
   Components:
    Explorer: Displays the file and folder structure of the workspace or project.
   Search: Provides a search interface for finding text within the project files.
   Source Control: Shows version control status, changes, and allows for committing and pushing code.
   Run and Debug: Displays debug configurations, breakpoints, and call stacks.
   Extensions: Lists installed extensions and provides a marketplace to discover new ones.
   Custom Panels: Extensions can add their own panels to the Side Bar.


4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
   It is a feature that allows users to access and execute various commands quickly and efficiently without navigating through menus. 
   Acts as a centralized command center for performing a wide range of tasks

   How to access
   Click on the top menu,click view and access command palette

   Tasks that can be perfomed using command palette
   Opening Files and Folders
   Running Commands
   Version Control
   Navigating and Editing
   Debugging
   Customization
   Terminal commands
   windows management


5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

   Roles of extensions in Vs code
   Testing and debuging-Provides additional testing and debugging tools to ease development process
   language support-supports various languages eg python,javascript
   Customization as it allows users customize as per their needs eg theme color
   Version control integration as one can integrate with version control
   Productivity enhancement with features like auto completion

   How can users find, install, and manage extensions?
    Press Ctrl+Shift+X and acces where one can browse and search for extensions

    Installing
    search for the extension you want and click install
    
    managing extension
    Open the Extensions view Ctrl+Shift+X ,click on gear action and choose the action you want to take ie disable,enable,update or unistall
    ![alt text](<Screenshot (17)-1.png>)

    Essential extension for web development
    live server
    Prettier - Code Formatter: esbenp.prettier-vscode
    GitHub Pull Requests and Issues: GitHub.vscode-pull-request-github
    Path Intellisense: christian-kohler.path-intellisense


6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

   opening intergrated terminal
   go to the menu on top and select terminal and click new terminal
   
   Advantages
   convenience and efficiency
   Enhanced features
   Resource management as it comes with vs code
   seamless workflow because of synchronized paths

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
   
   creating files and folders
   Click explorer icon in the activity bar,right cick an existing folder and select ne file/folder
   
   opening files and folders
   click the file name and it will open in the editor
   
   Managing folders and files
   To move right click the folder/file and move it.
   To delete right click the folder/file and delete it.
   To rename right click the folder/file and rename it.

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
   User goes  to file then preference then setting to customize

   Changing theme
   Type theme in the search bar settings,select color theme and choose

   changing font size
   Search font size in setting and adjust editor font size

   changing keyboard binding
   Go to file then preference then keyboard shortcuts,use search bar to find commands needed,click on pencil icon next to command an key combination


9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?
 
    Click on the fourth icon on the left side of vs code to open run and debug.
    clico on create a launcg.json file,select environmenr and vs code will generate one
    Set a break point by clicking on the left  of the line numbers 
    in the gutter
    Press F5 to start debugging

    key debugging features
    variables
    call stack
    Watch
    Breakpoints
    Debug console
10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
    First click on the three dots on the toppest part,click terminal then new terminal
    Initializing
    Use the command git init

    making commits
    use the command git commit -m "these are changes made"

    pushing changes
    Use the command git push

   


 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
  https://code.visualstudio.com/docs/editor/extension-marketplace#:~:text=VS%20Code%20extensions%20let%20you,APIs%20used%20by%20VS%20Code.
  https://git-scm.com/book 
- Submit your completed assignment by 1st July 

