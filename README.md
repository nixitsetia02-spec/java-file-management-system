# ROOT_BASE

ROOT_BASE is a desktop-based File Management System developed using **Java Swing**. It provides a simple, interactive, and user-friendly graphical interface for managing files and folders on a local computer. The application enables users to browse drives, navigate directories, create and delete files/folders, and edit text files efficiently.

---

## Features

- Browse available disk drives
- Navigate through folders and subfolders
- Display files and directories
- Open and read text files
- Edit and save text files
- Create new files
- Create new folders
- Delete files and folders
- Navigate back to the parent directory
- Display the current file or folder path
- User-friendly graphical interface
- Protection against deletion of restricted Windows system locations

---

## Technologies Used

- Java
- Java Swing
- Java IO (File Handling)
- NetBeans IDE

---

## Project Structure

```
ROOT_BASE/
│
├── src/
│   ├── Root_base.java
│   ├── start_project.java
│   └── ...
│
├── nbproject/
├── images/
├── dist/
├── build.xml
├── manifest.mf
└── README.md
```

---

## Requirements

- Java JDK 17 or later
- Java Runtime Environment (JRE)
- NetBeans IDE (Recommended for development)

---

# How to Run

## Method 1: Run Using NetBeans

1. Clone or download this repository.
2. Open the project in **NetBeans IDE**.
3. Click **Clean and Build Project**.
4. Run **`start_project.java`**.
5. Click **Start Application** to launch ROOT_BASE.

> **Application Entry Point:** `start_project.java`

---

## Method 2: Run Using the Executable JAR File

1. Open the project's **`dist`** folder.
2. Locate the generated executable JAR file (for example, **`ROOT_BASE.jar`**).
3. Double-click the JAR file to launch the application.

Or run it from the command line:

```bash
cd dist
java -jar ROOT_BASE.jar
```

> **Note:** Ensure that Java JDK/JRE 17 or later is installed before running the JAR file.

---

## Functionalities

- Drive Explorer
- Folder Navigation
- File Explorer
- Text File Viewer
- Text File Editor
- File Creation
- Folder Creation
- File and Folder Deletion
- Directory Navigation
- Current Path Display

---

## Platform Support

This application is currently designed for **Windows** systems because it utilizes Windows drive letters (C:, D:, etc.) for drive navigation.

---

## Screenshots

Add screenshots of the application in this section.

Example:

```
images/home.png
images/file_browser.png
images/text_editor.png
images/about.png
```

---

## Future Enhancements

- Copy files and folders
- Cut and paste functionality
- Rename files and folders
- Image preview
- Search files and folders
- Drag-and-drop support
- Dark mode
- Linux and macOS support
- Keyboard shortcuts
- File properties viewer

---

## Developer

**Nixit Setia**

B.E. Computer Engineering (COE)

Thapar Institute of Engineering and Technology, Patiala

---

## License

This project is licensed under the **MIT License**.

---

## Acknowledgements

This project was developed as a learning project to strengthen concepts of:

- Java Programming
- Java Swing GUI Development
- File Handling using Java IO
- Event-Driven Programming
- Desktop Application Development
