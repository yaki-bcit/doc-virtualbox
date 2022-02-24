---
layout: default
title: Installing VirtualBox on macOS
parent: Installation
nav_order: 2

---

# Install VirtualBox
{: .no_toc }

In this section, you will learn how to get and install the latest version of VirtualBox for macOS.

The download size is approximately 100 MB, and depending on your internet connection speed, it may take from 1 to 10 minutes on most modern connections.

Installation time mostly depends on the type of your storage, although other specifications may also play a minor role.

> **Warning**: The installation involves changes to some deep system settings and creation of virtual hardware such as network adapters. As such, **your computer WILL require a full reboot** after installation. Before you start the installation, **make sure to save and close any open files and close unnecessary programs**.

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Download the Redistributable

Head over to [virtualbox.org](https://www.virtualbox.org/) and click the Download button.

![VirtualBox welcome page](./assets/VB-download-01.png)

The button is hard to miss, but alternatively, you can also click the Downloads(https://www.virtualbox.org/wiki/Downloads) navigation link on the left.

> **Note**: The End-user docs link in the navigation may prove useful as you perfect your virtualization skills and tackle more complex tasks.

The Downloads page offers versions of VirtualBox for different host operating systems. Since your computer runs macOS, click the link that says “**OS X hosts**”.

![VirtualBox download page](./assets/VB-download-02.png)

> **Warning**: It is a common mistake for beginners to download the wrong OS version of VirtualBox. Remember, it does not matter which guest OS you want to run. What matters is the operating system that is currently installed and running on your computer.

> **Note**:    The Downloads page links to other useful resources, such as the Extension Pack (more on it later) or the full VirtualBox manual.

Once you click the "OS X hosts” link, the browser should start downloading automatically. 

![File download on Safari](./assets/VB-download-01-macOS.png)

Depending on the settings of your browser, the downloaded file may be saved in the “Downloads” folder of your user. We recommend moving it to a location that you will remember, so that accessing or deleting the file is easier in the future.

## Install VirtualBox

Although you may be used to installing programs on your computer, installation of VirtualBox involves steps that you may be unfamiliar with. Before you begin, please take at least a quick look at this section to learn what to expect.
