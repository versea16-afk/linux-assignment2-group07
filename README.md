# Linux Assignment 2 – Template:
This repo is just a "template" to be used by my students for the `**Linux Lab - Assignment2**`.

# Linux Assignment 2 – Topics:
Practice navigating the filesystem, working with paths, managing files/directories using basic Linux commands, and apply and practice all **CRUD** operations.  Includes a starter folder structure for students to explore with GitHub Codespaces.

# Linux Assignment 2 - Instructions:
Please refer to our LMS and PDF for the assignment detailed instructions.

# How to Use This Repo Template and Setup Your Assignment Repo:
Follow these steps *(exactly as you did with assignment 1 template)* to use this repository as a starting point for your assignment:

**NOTE: Don't forget to login to your GitHub Account :-)**

## Step 1: Create a New Repository from the Template
1. Go to the template repository page: [Linux Assignment2 Template](https://github.com/anmarjarjees/linux-assignment2-template)
2. Click the **"Use this template"** button (green button at the top)
3. In the dropdown, click **"Create a new repository."**
4. Enter a repository name: `**linux-assignment2-groupX**` (replace X with your group number)
5. Choose **Public** or **Private**, depending on the assignment instructions
6. Click **"Create repository"** button

## Step 2: Start answering the questions
1. Open your new repository (linux-assignment2-groupX)
2. Click the green "Code" button
3. Click "Create codespace on main"
4. A GitHub Codespace will open in the browser, giving you access to all folders and files from the template
5. You can now start editing files directly in the browser without needing to install Git or clone anything locally

# README.md Important Action:
Be advised that you have to modify the content of your "README.md". Remove the initial content you received from the template, and add the following content as explained in the assignment instructions:
- Assignment number
- Group number
- Group member names
- Any other useful content you like or prefer to add (Optional)

# The official Linux Filesystem Hierarchy (FHS):
According to the **FHS**, a typical Linux root / directory looks like this:

- bin/ ==> Essential command binaries (ls, cp, mv, cat, etc.)
- boot/ ==> Boot loader files
- dev/ ==> Device files (hard drives, USBs, etc.)
- etc/ ==> System-wide configuration files
- home/ ==> User home directories (/home/username)
- lib/ ==> Shared libraries for essential binaries
- media/ ==> Mount points for removable media (USB, CD-ROM)
- mnt/ ==> Temporary mount point
- opt/ ==> Optional add-on applications
- proc/ ==> Virtual filesystem providing process and kernel info
- root/ ==> Home directory of the root user
- run/ ==> Process runtime data
- sbin/ ==> System binaries (for root/admin)
- srv/ ==> Service data (like web servers, FTP)
- tmp/ ==> Temporary files
- usr/ ==> User programs and utilities
- var/ ==> Variable data (logs, cache, mail, etc.)


Link: https://refspecs.linuxfoundation.org/FHS_3.0/fhs/index.html 

# LINUX System Essential Folder Structure Used in this Assignment:
- home/user1/ --> represents the users's personal space "user1 for example" (~ or /home/student)
- etc/ --> system configuration (safe to view only)
- bin/ --> executable scripts (practice running and copying files)
- var/ --> logs and temporary files (practice listing, moving, deleting)
- media/ --> mounted devices (practice navigation)
- docs/ --> assignment theory answers and instructions

## Real Ubuntu Directory and Simulated in Assignment Folder Names:
- Users' personal folders:
    - Real Ubuntu Directory: `/home`
    - Simulated in Assignment: `home/`
-  Configuration files:
    - Real Ubuntu Directory: `/etc` 
    - Simulated in Assignment: `etc/`
- Executable scripts:
    - Real Ubuntu Directory:  `/bin`   
    - Simulated in Assignment: `bin/`  
- Logs and temporary data:
    - Real Ubuntu Directory: `/var`
    - Simulated in Assignment:`var/` 
- Mounted devices:
    - Real Ubuntu Directory: `/media`  
    - Simulated in Assignment:`media/`
- Assignment documents:
    - Real Ubuntu Directory: `/docs` *(custom)*  
    - Simulated in Assignment: `docs/` 


# Folder Structure:
Below is the folder structure of this repo created with the use of **AI tool**:
    - Create your folders/files manually (in VS Code for example)
    - Inside VS Code, click "Explorer" Icon to open the Explorer Bar
    - Make sure that all folders are revealed, take a screen shot (You can use the sniping tool in windows)
    - copy the screenshot to any AI tools to generate the folder structure as shown below:
    - NOTICE that we need to wrap the generated diagram with **```** otherwise it will be displayed as one paragraph
    
```
linux-assignment2/
│
├── bin/
│   ├── backup.sh
│   └── start.sh
│
├── docs/
│   ├── assignment2_groupX_theory.txt
│   └── guide.txt
│
├── etc/
│   ├── config/
│   │   └── system.conf
│   └── network/
│       └── interfaces.txt
│
├── home/
│   └── user1/
│       ├── documents/
│       │   └── notes.txt
│       ├── downloads/
│       │   └── setup.log
│       └── pictures/
│           └── profile.png
│
├── media/
│   ├── cdrom/
│   │   └── setup.iso
│   └── usb/
│       └── photo.jpg
│
├── var/
│   ├── log/
│   │   ├── error.log
│   │   └── syslog.txt
│   └── tmp/
│       └── cache.tmp
│
├── .gitignore
└── README.md
```



----
----

**Good Luck :-)**

**Anmar Jarjees**