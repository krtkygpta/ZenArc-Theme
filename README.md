# ZenArc Browser Theme

A minimalist Zen-inspired browser theme focused on clean aesthetics and functionality. Compatible with Twilight 1.8t.

## Overview

ZenArc delivers a modern, distraction-free browsing experience with thoughtfully designed UI elements. The theme emphasizes visual harmony while maintaining full browser functionality.

## Key Features

### Visual Elements
- **Clean, Minimalist Design**: Streamlined interface elements that reduce visual clutter
- **Dynamic Transparency**: Elegant transparency effects throughout the UI (Work in Progress)
- **Blur Effects**: Sophisticated blur on urlbar and expanded sidebar for depth
- **Zen Accent Integration**: Seamlessly follows your chosen Zen accent theme

### Enhanced Components

#### FindBar
A redesigned search experience with improved visibility.  
*Credit: Natsumi*

![Made some tweaks to the findbar, use zenarc.findbar.disabled as false](images/image.png)

#### URL Bar
Clean and intuitive address bar design.

![Enhanced URL Bar Design](images/image-2.png)


#### Context Menu
Streamlined right-click menu interface.

![Context Menu tweaks](image.png)


#### Bookmarks
Improved bookmark management and visualization.

![Bookmarks Interface](images/image-5.png)


### Additional Features
- **Audio Visualizer**: Visual representation of audio playback
- **Custom Icons**: Fresh icon set for a cohesive look
- **Enhanced PDF Viewer**: Improved reading experience for PDF documents

## Installation Guide

Follow these steps to install the Zen theme in your browser:

1.  Locate Your Browser's Profile Directory:
    *   In your browser's address bar, type about:profiles and press Enter.
    *   Find the profile you're currently using.
    *   Click the "Open Folder" button for your profiles root directory.
2.  Access or Create the chrome Folder:
    *   Inside your profile directory, check if a folder named "chrome" exists.
    *   If it doesn't exist, create a new folder and name it "chrome" lowercase.
3.  Edit or Create userChrome.css:
    *   Inside the chrome folder, check if a file named userChrome.css exists.
    *   If it doesn't exist, create a new text file and rename it to "userChrome.css".
    *   Make sure file extensions are visible in your file explorer.
    *   Open userChrome.css in a text editor.
    *   Add the following line to the file:
        ```css
        @import url("ZenArc V1.2/ZenArc.css");
        ```
4.  Install the ZenArc Theme:
    *   Move the "ZenArc V1.2" folder into the chrome folder next to userChrome.css file.
    *   The final directory structure should look like this:
        ```
        your_profile (folder)
        └── chrome (folder)
            ├── userChrome.css
            └── ZenArc V1.2 (folder)
                ├── ZenArc.css
                ├── config.css
                ├── ZenArcContent.css
5.  Restart Your Browser:
    *   Close and reopen your browser for the changes to take effect.
6.  Enjoy!

## Required Configuration

1. Access the advanced configuration page
   - Type `about:config` in the address bar
   - Accept the warning message

2. Enable the following settings:

| Name | Value | Meaning |
| ---- | :-----: | ------- |
| Zenarc.audiovisual.enabled	| true	| enables audiovisualiser on tabs|
| Zenarc.use-windows-accent.enabled | true| Use OS accent as Zen-accent |

## Configs You can / should edit

1. go to 'chrome' folder
2. open 'config.css'
3. edit

## Troubleshooting

### Known Issues
- If transparency effects aren't working, ensure your system supports composition
- For blur-related issues, verify your graphics drivers are up to date

