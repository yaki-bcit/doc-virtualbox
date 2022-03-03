---
layout: default
title: Add a New Virtual Machine in VirtualBox
parent: Create an Ubuntu Virtual Machine
nav_order: 2

---

# Add a New Virtual Machine in VirtualBox

> **Note**: These steps will not result in a working Ubuntu installation. To do this, you will need to install Ubuntu inside the virtual machine.

**Step 1**. Open VirtualBox and find the “New” button in the main window. Alternatively, you can click “Machine > New…” in the top menu.

![VirtualBox Main Screen](https://yaki-bcit.github.io/doc-virtualbox/docs/assets/VM-01.png)

**Step 2**. In the dialog window that appears you need to note or interact with four fields:

  a. Enter the name for your new virtual machine in the “Name” field. VirtualBox will try to detect what operating system you are planning to use and match the “Type” and “Version” fields based on your input.
  
  b. Take note of or change the location of the “Machine Folder” field. This is the folder on your computer where the system files of your virtual machine will be saved.
  
  c. Make sure that the “Type” field has “Linux” selected.
  
  d. Make sure that the “Version” field has “Ubuntu (64-bit)” selected.

![Create Virtual Machine Dialog - Name and Operating System](https://yaki-bcit.github.io/doc-virtualbox/docs/assets/VM-03.png)

**Step 3**. On the “Memory Size” screen, make sure that you allocate at least 1024 MB for your virtual machine. More is better, so see if you can safely increase the value to around 2048 MB or slightly more, but do not set the slider outside the green zone.

![Create Virtual Machine Dialog - Memory Size](https://yaki-bcit.github.io/doc-virtualbox/docs/assets/VM-05.png)

> **Warning**: setting the slider in the red zone will make your virtual machine use more memory than your computer can safely provide and may lead to slowing down, instability and crashes.

**Step 4**. On the “Hard disk” screen, make sure “Create a virtual hard disk now” is selected.

![Create Virtual Machine Dialog - Hard Disk](https://yaki-bcit.github.io/doc-virtualbox/docs/assets/VM-07.png)

**Step 5**. On the “Hard disk file type” screen, select VDI.

![Create Virtual Machine Dialog - Hard Disk File Type](https://yaki-bcit.github.io/doc-virtualbox/docs/assets/VM-08.png)

**Step 6**. Select “Dynamically allocated” in “Storage on physical hard disk”.

![Create Virtual Machine Dialog - Storage on Physical Hard Disk](https://yaki-bcit.github.io/doc-virtualbox/docs/assets/VM-09.png)

**Step 7**. In “File allocation and size”, 

  a. Note or change the location of the virtual machine system files;
  
  b. Make sure to allocate **at least 10** GB of disk storage for the virtual machine; more is better, but around 15 GB should be enough for most simple use cases;
  
  c. Click **Create** if you are ready to proceed.

![Create Virtual Machine Dialog - File Location and Size](https://yaki-bcit.github.io/doc-virtualbox/docs/assets/VM-10.png)
