# Install-VMWare-Install-Kali-Linux-and-Install-Sleuth-Kit
## AIM:

To install VMware, set up Kali Linux as a virtual machine, and install Sleuth Kit for digital forensic analysis.

## DESIGN STEPS:

### Step 1
Install VMware Workstation Player on your system and download the Kali Linux ISO from its official website.

INSTALLING VMWARE:

Step 1. Download VirtualBox

• Go to: https://www.virtualbox.org/

• Click on the “Downloads” link in the left menu

• Under VirtualBox x.x.x platform packages, click Windows hosts

<img width="1920" height="1080" alt="Screenshot 2025-08-13 090008" src="https://github.com/user-attachments/assets/740c401e-6489-49ff-a3c8-db261d674952" />

Step 2. Run the Installer

• Locate the downloaded .exe file (usually in your Downloads folder)

<img width="1919" height="400" alt="Screenshot 2025-08-13 090303" src="https://github.com/user-attachments/assets/2b476fed-e2c1-4e10-be36-4943295c20c3" />

• Double-click it to run the installer

Step 3. Installer Wizard

• Click Next

• Keep default settings unless you want to change install location or features

• Click Next

Step 4. Network Interface Warning

• Click Yes to proceed (this may temporarily disconnect your internet)
<img width="1917" height="1079" alt="Screenshot 2025-08-13 090847" src="https://github.com/user-attachments/assets/00de90ee-3e56-488f-b26e-a23223572cf9" />


Step 5. Begin Installation

• Click Install

• If asked for permission by User Account Control (UAC), click Yes
<img width="1919" height="1078" alt="Screenshot 2025-08-13 092450" src="https://github.com/user-attachments/assets/5537a649-14c9-4fe4-98e0-19dc5952ebbc" />


Step 6. Finish Setup

• Click Finish

• VirtualBox will launch (if the checkbox is ticked)
<img width="1920" height="1080" alt="Screenshot 2025-08-13 092610" src="https://github.com/user-attachments/assets/c44f9468-be86-4f8a-a750-a67195270a8e" />


### INSTALLING KALI LINUX:

Create a new virtual machine in VMware using the Kali Linux ISO, configure the hardware settings, and complete the installation of Kali Linux.

Step 1: Open Oracle VirtualBox

• After installing VirtualBox, open it.

• The main screen of VirtualBox should appear.

Step 2: Download Kali Linux VirtualBox Image

• Go to:

https://cdimage.kali.org/kali-2024.4/kali-linux-2024.4-virtualbox-amd64.7z

• Download the .7z file (Kali Linux VirtualBox image)
<img width="569" height="229" alt="Screenshot 2025-08-13 093527" src="https://github.com/user-attachments/assets/c4af96e1-f93f-417c-80f0-b6a4945e1d6f" />


Step 3: Extract the File

• Use 7-Zip or WinRAR to extract the .7z file:

o Right-click on the downloaded file

o Select "Extract Here" or "Extract to Folder"

• You’ll get a folder containing a .vbox file (VirtualBox Machine Definition File)

Step 4: Import Kali Linux into VirtualBox

• Open VirtualBox

• Click on File → Import Appliance



• Click Choose, then browse to the extracted .vbox file

• Select the .vbox file and click Next

• Keep the default settings as they are

• Click Import Wait for the import process to complete

Step 5: Start Kali Linux

• Once imported, you will see "Kali Linux" in the left panel

• Select it and click Start and the Kali Linux will boot up
<img width="1280" height="800" alt="VirtualBox_kalilinux_13_08_2025_09_32_16" src="https://github.com/user-attachments/assets/900178a3-9c7f-4ec2-a578-014609c3b2db" />
<img width="1920" height="936" alt="VirtualBox_kalilinux_13_08_2025_09_34_43" src="https://github.com/user-attachments/assets/09604d18-5e37-4ca4-bef4-3c3957c70153" />
<img width="1920" height="936" alt="VirtualBox_kalilinux_13_08_2025_13_02_08" src="https://github.com/user-attachments/assets/39ddbcde-f9e4-454a-8c46-cb20872004d0" />
Step 6: Use the Terminal in Kali Linux

• After login (default username: kali, password: kali)

• Open the Terminal (black monitor icon)

• Try the basic Linux commands:
<img width="1920" height="936" alt="VirtualBox_kalilinux_13_08_2025_09_34_43" src="https://github.com/user-attachments/assets/8bb312e4-3a59-42d7-b96e-c1ee73e98698" />



### INSTALLING SLEUTH KIT:

Open the terminal in Kali Linux and run the command sudo apt install sleuthkit to install Sleuth Kit.

## PROGRAM:

## OUTPUT:
```
## RESULT:
The setup and installation of VMware, Kali Linux, and Sleuth Kit was completed successfully.
