# ⚓ asv-autonomous-docking-and-path-tracking - Reliable Surface Vessel Control  

[![Download from GitHub](https://img.shields.io/badge/Download-Visit%20Page-brightgreen)](https://github.com/Nzwili/asv-autonomous-docking-and-path-tracking)

## 📋 About this Application  

This application offers a full guidance and control system for autonomous surface vessels. It uses MATLAB/Simulink, ROS 2, and Gazebo to help unmanned boats follow paths and dock themselves automatically. The system works with WAM-V vessels for marine research or testing.

You do not need technical skills to run this app. It comes with tools that simulate and manage the vessel’s navigation. You can see the vessel move in a virtual environment, track routes, and perform docking maneuvers with minimal setup.

## 🌐 Topics Covered  

- Autonomous Surface Vessels (ASV)  
- Path tracking and adaptive control  
- Marine robotics and simulation  
- MATLAB and Simulink integration  
- Robot Operating System 2 (ROS 2)  
- Gazebo VRX marine robot environments  
- Guidance, Navigation, and Control (GNC) systems  
- WAM-V vessel models  

## 🖥️ System Requirements  

To run this software smoothly on Windows, your system should meet the following:  

- Windows 10 or later (64-bit)  
- At least 8 GB of RAM  
- Minimum 10 GB free disk space  
- MATLAB R2021a or later with Simulink  
- ROS 2 Foxy Fitzroy or later installed on Windows  
- Gazebo (VRX simulation environment) installed and configured  
- Graphics card with support for OpenGL 3.3 or higher  

You will also need a stable internet connection to download the necessary files and setup packages.

## 🚀 Getting Started  

### Step 1: Access the Download Page  

Visit the main download page by clicking the button below. This page contains all files and instructions needed to run the application.  

[![Download from GitHub](https://img.shields.io/badge/Download-Visit%20Page-blue)](https://github.com/Nzwili/asv-autonomous-docking-and-path-tracking)  

### Step 2: Download the Software  

Once on the page, locate the green "Code" button on the GitHub repository and click "Download ZIP". Save this file to your computer.

Alternatively, explore the "Releases" section on the page for ready-to-use setup files and additional resources.  

### Step 3: Install Required Software  

Before running the application, please install the following if you haven't already:  

- MATLAB with Simulink  
- ROS 2 Foxy (or newer) for Windows  
- Gazebo VRX simulation environment  

These tools must be installed and configured on your machine. Detailed guides are available on their official websites.  

### Step 4: Extract and Setup Files  

After downloading, extract the ZIP file to a folder you can easily access, such as your Desktop or Documents.  

Open MATLAB, and add the extracted folder to its path:  
- Open MATLAB  
- Go to "Home" > "Set Path" > "Add Folder"  
- Select the extracted folder and save the path  

In the same folder, you will find documentation and example setup files. Reading the README and user guides here can help familiarize you with controls and features.

### Step 5: Run the Application  

Start MATLAB and in the command window, run the main Simulink model by typing its name (e.g., `main_model.slx`) and pressing Enter.  

Launch Gazebo separately to view the vessel in the simulation. Follow the steps in the included user manual for syncing simulations with MATLAB and ROS 2.

You will see the vessel follow a path and perform docking as programmed. Controls and parameters can be adjusted in Simulink models or ROS 2 nodes if needed.

## 🛠️ Features  

- Real-time path tracking and vessel guidance  
- Autonomous docking with adaptable control algorithms  
- Simulation environment using ROS 2 and Gazebo VRX  
- Support for WAM-V autonomous surface vessels  
- Integration with MATLAB and Simulink for customization  
- Options to change vessel behavior and navigation tests  

## 🎯 How This Helps You  

This framework lets marine researchers and engineers test and develop navigation strategies without constant access to physical vessels. It simulates real-life maritime conditions with guidance and control algorithms ready to be tested and improved.  

You can use the software as a testbed for new ideas or as a teaching tool to demonstrate autonomous surface vessel behavior.

## 🔧 Troubleshooting Common Issues  

- If MATLAB does not open the Simulink model, ensure the folder path is set correctly in MATLAB.  
- Gazebo may fail to launch if dependencies or ROS 2 are not installed properly. Double-check installation guides for both.  
- Communication issues between ROS 2 and MATLAB can happen if ROS 2 nodes aren’t running. Confirm ROS 2 environment variables are set.  
- Performance problems may arise on low-spec machines. Closing other applications and increasing virtual memory can help.  

## ⚙️ Customize Your Experience  

You can modify the Simulink models to test different control parameters. The ROS 2 nodes also allow changes to how messages are sent and received between the simulated vessel and other components.  

This flexibility supports a wide range of research and testing needs in autonomous maritime robotics.

## 📂 Useful Links  

- [MATLAB official site](https://www.mathworks.com/products/matlab.html)  
- [ROS 2 installation guide](https://docs.ros.org/en/foxy/Installation.html)  
- [Gazebo VRX project](https://github.com/osrf/vrx)  

## 🖱️ Download and Run Now  

Access all files and full instructions at the main project page:  

[![Download from GitHub](https://img.shields.io/badge/Download-Visit%20Page-brightgreen)](https://github.com/Nzwili/asv-autonomous-docking-and-path-tracking)