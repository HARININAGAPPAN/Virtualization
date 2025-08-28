# Aim:
To set up a virtualized environment using Oracle VirtualBox, install Kali Linux as a guest OS, and execute fundamental Linux commands.

3.a) Installation and Configuration of Oracle VirtualBox
# Aim:
To install and configure Oracle VM VirtualBox.

# Pre-requisites:
Machine with Internet access
Minimum 4 GB RAM
Sufficient storage space
# Steps:
# Download Oracle VM VirtualBox:

Visit Oracle VirtualBox Official Site
Download installer for your OS (Windows/macOS/Linux).
# Install Oracle VM VirtualBox (Example: Windows):

Launch Installer → Allow Changes → Click Next.
Choose Installation Options → Click Next.
Accept Network Interface Warning → Click Yes.
Click Install.
Finish Installation and Launch VirtualBox.
# Configure VirtualBox:

Open VirtualBox.
Click New → Name VM → Select Type (Linux/Windows) and Version.
# Allocate:
Minimum 2 GB RAM
Create Virtual Hard Disk (20 GB recommended).
Start Virtual Machine and provide ISO to install OS.
# Result:
Thus, Oracle VM VirtualBox was installed successfully.

# 3.b) Installation and Configuration of Kali Linux
# Aim:
To install and configure Kali Linux in Oracle VirtualBox.

# Pre-requisites:
Oracle VM VirtualBox Installed
4 GB RAM and 20 GB Storage Minimum
Kali Linux ISO image
# Steps:
# Download Kali Linux ISO:

Visit Kali Linux Official Site
Download 64-bit ISO (Installer version).
# Create a New Virtual Machine:

Open VirtualBox → Click New.
Name: "Kali Linux" → Type: Linux → Version: Debian (64-bit).
# Allocate Memory:

Minimum 2 GB RAM (recommended 4 GB).
# Create Virtual Hard Disk:

Select VDI (VirtualBox Disk Image).
Choose Dynamically allocated.
Set Disk size to 20 GB or more.
# Configure ISO Image:

Settings → Storage → Controller: IDE → Empty CD → Choose Disk File → Select Kali Linux ISO.
# Start Installation:

Boot Virtual Machine → Choose Graphical Install.
Set Language, Region, Keyboard.
Configure Network → Set Hostname (e.g., kali).
Set root password.
Disk Partitioning: Use entire disk → All files in one partition.
Install System → Install GRUB Bootloader → Finish Installation.
# Login to Kali Linux:

Use root credentials.
(Optional) Install Guest Additions:

Devices → Insert Guest Additions CD Image → Follow steps inside Kali.
Snapshots:
AWS Account Creation Snapshot

# Snapshot 1: Installing Oracle VirtualBox 
<img width="836" height="436" alt="image" src="https://github.com/user-attachments/assets/60f0c5d7-e417-445d-841d-563a99fbc273" />


# Snapshot 2: Kali Running in Virtual
<img width="838" height="504" alt="image" src="https://github.com/user-attachments/assets/ac98f08e-9f32-460c-b8fa-f235ef7c2cbd" />

# Result:
Thus, Kali Linux guest OS was installed and configured successfully.

# 3.c) Execution of Linux Commands in Kali
# About Linux:
Open-source operating system.
Kernel manages communication between hardware and software.
Commands are case-sensitive.
# Linux Commands:
ls Command

The ls command is used to display a list of content of a directory.

# Syntax:
```
ls
```
<img width="737" height="81" alt="image" src="https://github.com/user-attachments/assets/53ebd631-e49f-4d66-8a88-5e02e6cb5887" />


# pwd Command

The pwd command is used to display the location of the current working directory.

Syntax:
```
pwd
```
<img width="291" height="91" alt="image" src="https://github.com/user-attachments/assets/deb575e1-f70a-4384-9a77-c1b7a49d1cf0" />


# mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax:
```
mkdir <directory_name>
```
<img width="450" height="74" alt="image" src="https://github.com/user-attachments/assets/843409cf-3406-4eb3-849d-d747dabe2585" />


# rmdir Command

The rmdir command is used to delete a directory.

Syntax:
```
rmdir <directory_name>
```
<img width="403" height="75" alt="image" src="https://github.com/user-attachments/assets/21e66c11-010c-491b-9360-caf122141ac0" />


# cd Command The cd command is used to change the current directory
Syntax:
```
cd <directory_name>
```
<img width="322" height="66" alt="image" src="https://github.com/user-attachments/assets/c878b6d4-76ca-4c13-aa74-ec0bbfb3a13c" />


# cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content ofthe file, copy the content of one file to another file, and more.

Syntax:
```
cat [options] [file_name]
```

<img width="839" height="183" alt="image" src="https://github.com/user-attachments/assets/42c815cc-638d-4ea1-b144-48d26ac76d03" />


# cp Command

The cp command is used to copy a file or directory.

Syntax:
```
cp [source] [destination]
```
<img width="851" height="155" alt="image" src="https://github.com/user-attachments/assets/4616229b-a97d-45e6-ab66-557a68c1869d" />




# mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax:
```
mv [source] [destination]
```


<img width="480" height="153" alt="image" src="https://github.com/user-attachments/assets/dd092e2b-82f4-478f-b488-fdd939166e47" />


# touch Command

Create empty file.

Syntax:

```
touch [filename]
```
<img width="337" height="62" alt="image" src="https://github.com/user-attachments/assets/ffa6889c-f459-4b90-bea8-c3812f36ccfc" />


# vi Command

Edit file contents using editor.

Syntax:
```
vi [filename]
```
<img width="238" height="84" alt="image" src="https://github.com/user-attachments/assets/aa4ab2ba-715a-4c76-985b-52a7bf5bcc7a" />


Result:
Thus, various Linux commands were executed successfully in Kali Linux virtual machine.

Aim:
To set up a virtualized environment using Oracle VirtualBox, install Kali Linux as a guest OS, and execute fundamental Linux commands.

# 3.a) Installation and Configuration of Oracle VirtualBox
# Aim:
To install and configure Oracle VM VirtualBox.

# Pre-requisites:
Machine with Internet access
Minimum 4 GB RAM
Sufficient storage space
# Steps:
# Download Oracle VM VirtualBox:

Visit Oracle VirtualBox Official Site
Download installer for your OS (Windows/macOS/Linux).
Install Oracle VM VirtualBox (Example: Windows):

Launch Installer → Allow Changes → Click Next.
Choose Installation Options → Click Next.
Accept Network Interface Warning → Click Yes.
Click Install.
Finish Installation and Launch VirtualBox.
# Configure VirtualBox:

Open VirtualBox.
Click New → Name VM → Select Type (Linux/Windows) and Version.
# Allocate:
Minimum 2 GB RAM
Create Virtual Hard Disk (20 GB recommended).
Start Virtual Machine and provide ISO to install OS.
# Result:
Thus, Oracle VM VirtualBox was installed successfully.

# 3.b) Installation and Configuration of Kali Linux
# Aim:
To install and configure Kali Linux in Oracle VirtualBox.

# Pre-requisites:
Oracle VM VirtualBox Installed
4 GB RAM and 20 GB Storage Minimum
Kali Linux ISO image
# Steps:
# Download Kali Linux ISO:

Visit Kali Linux Official Site
Download 64-bit ISO (Installer version).
# Create a New Virtual Machine:

Open VirtualBox → Click New.
Name: "Kali Linux" → Type: Linux → Version: Debian (64-bit).
# Allocate Memory:

Minimum 2 GB RAM (recommended 4 GB).
# Create Virtual Hard Disk:

Select VDI (VirtualBox Disk Image).
Choose Dynamically allocated.
Set Disk size to 20 GB or more.
# Configure ISO Image:

Settings → Storage → Controller: IDE → Empty CD → Choose Disk File → Select Kali Linux ISO.
# Start Installation:

Boot Virtual Machine → Choose Graphical Install.
Set Language, Region, Keyboard.
Configure Network → Set Hostname (e.g., kali).
Set root password.
Disk Partitioning: Use entire disk → All files in one partition.
Install System → Install GRUB Bootloader → Finish Installation.
# Login to Kali Linux:

Use root credentials.
# (Optional) Install Guest Additions:

Devices → Insert Guest Additions CD Image → Follow steps inside Kali.
Snapshots:
# AWS Account Creation Snapshot

Snapshot 1: Installing Oracle VirtualBox 
<img width="841" height="448" alt="image" src="https://github.com/user-attachments/assets/aa2faffc-f5e1-4fe9-a473-edf1739999d5" />


Snapshot 2: Kali Running in Virtual 
<img width="849" height="503" alt="image" src="https://github.com/user-attachments/assets/7772cd8c-d4c4-4e91-bee9-d9b365eb9d48" />


# Result:
Thus, Kali Linux guest OS was installed and configured successfully.

# 3.c) Execution of Linux Commands in Kali
About Linux:
Open-source operating system.
Kernel manages communication between hardware and software.
Commands are case-sensitive.
Linux Commands:
# ls Command

The ls command is used to display a list of content of a directory.

Syntax:
```
ls
```
<img width="740" height="77" alt="image" src="https://github.com/user-attachments/assets/f1e830dc-60bc-4914-91c5-255328b8a60d" />


# pwd Command

The pwd command is used to display the location of the current working directory.

Syntax:
```
pwd
```
<img width="309" height="90" alt="image" src="https://github.com/user-attachments/assets/741752e6-c264-43b1-8e92-bc55a0f8f652" />


# mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax:
```
mkdir <directory_name>
```
<img width="407" height="68" alt="image" src="https://github.com/user-attachments/assets/7e8c635d-0cae-44d7-a991-f2c9a6e5f340" />


# rmdir Command

The rmdir command is used to delete a directory.

Syntax:
```
rmdir <directory_name>
```
<img width="427" height="72" alt="image" src="https://github.com/user-attachments/assets/0378601e-ef6a-4156-9ca2-a0f94faec3fe" />

# cd Command The cd command is used to change the current directory
Syntax:
```
cd <directory_name>
```
<img width="264" height="60" alt="image" src="https://github.com/user-attachments/assets/8ac27942-9e10-4fa1-aca9-5f1f2a53db61" />

# cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content ofthe file, copy the content of one file to another file, and more.

Syntax:
```
cat [options] [file_name]
```
<img width="837" height="181" alt="image" src="https://github.com/user-attachments/assets/fc03c461-5cbf-44c8-a799-8ecd867568c3" />

# cp Command

The cp command is used to copy a file or directory.

Syntax:
```
cp [source] [destination]
```
<img width="865" height="158" alt="image" src="https://github.com/user-attachments/assets/8490df04-d2a4-4941-9e41-9534c0ee91cf" />

# mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax:
```
mv [source] [destination]
```
<img width="423" height="145" alt="image" src="https://github.com/user-attachments/assets/4380b437-edcc-4478-b6d4-34905feb972f" />

# touch Command

Create empty file.

Syntax:
```
touch [filename]
```
<img width="244" height="73" alt="image" src="https://github.com/user-attachments/assets/37835ab4-0b2c-422f-bb97-9eed1b266012" />


# vi Command

Edit file contents using editor.

Syntax:
```
vi [filename]
```
<img width="251" height="69" alt="image" src="https://github.com/user-attachments/assets/39c646eb-8c5f-4699-91bd-9c818d5138d2" />

# Result:
Thus, various Linux commands were executed successfully in Kali Linux virtual machine.# Virtualization
