Visual Studio Code provides a development environment which allows developers to share and collaborate on code with ease. This guide outlines the steps to configure an existing GitHub repository on your local computer, setting up a seamless working environment for remote collaboration on your projects.

!!! important
    Before configuring a GitHub repository on your local computer, make sure your GitHub account is linked to VS Code and that you have the GitHub repository URL ready.


## Clone a GitHub Repository to Local Computer

1. **Click** [Clone Git Repository] on the Welcome tab.

![image](Assets/img1.1.gif "[Clone Git Repository] button")

!!! tip "Tip"
    By launching VS Code, you will land on the Welcome tab unless you have opened a project. If you are directed to an existing project, close it by clicking [File] → [Close Folder] to return to the Welcome tab.

2. **Paste** or **enter** the GitHub repository URL into the text bar.

![image](Assets/img1.2.gif "Input GitHub repository URL")

3. **Select** [Clone from URL] from the dropdown menu.

![image](Assets/img1.3.gif "[Clone from URL] menu item")

4. **Choose** a local <i>direcotory</i> to save the repository to.

![image](Assets/img1.4.gif "Select your desired destination")

5. **Click** [Select as Repository Destination] button to begin the cloning process.

![image](Assets/img1.5.gif "[Select as Repository Destination] button")

6. Once the cloning is successful, a pop-up window will appear. **Click** [Open] to open the downloaded repository in VS Code.

![image](Assets/img1.6.gif "[Open] button")


## Push to a GitHub Repository from Local Computer

!!! warning "Warning"
    Your <i>commits</i> will be visible to anyone with access to the shared repository. Once pushed, your commits cannot be withdrawn or undone.

1. **Click** [View] → [Source Control] to open the Source Control panel.

2. **Enter** your <i>commit message</i> into the textbox. 

3. **Click** [✔ Commit] to commit your edits.

4. When ready, **click** [⋯] → [Push] on the Source Control panel to push your changes to the remote GitHub repository.

!!! tip "Tip"
    The [⋯] button appears only when you hover over the Source Control panel.


!!! success "Success"
    Congratulations! You can now begin collaborating with other developers in VS Code by cloning a GitHub repository to and pushing your progress from your local computer.