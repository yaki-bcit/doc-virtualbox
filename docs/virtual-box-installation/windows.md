---
layout: default
title: Installing VirtualBox on Windows
parent: Installation
nav_order: 1

---
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Step 1: Download the Redistributable

Head over to [virtualbox.org](https://www.virtualbox.org/) and click the Download button.

![VirtualBox welcome page](https://yaki-bcit.github.io/doc-virtualbox/docs/assets/VB-download-01.png)

The button is hard to miss, but alternatively, you can also click the [Downloads](https://www.virtualbox.org/wiki/Downloads) navigation link on the left.

> **Note**: The End-user docs link in the navigation may prove useful as you perfect your virtualization skills and tackle more complex tasks.

The Downloads page offers versions of VirtualBox for different host operating systems. Since your computer runs Windows, click the link that says “**Windows hosts**”.

![VirtualBox download page](https://yaki-bcit.github.io/doc-virtualbox/docs/assets/VB-download-02.png)

> **Warning**: It is a common mistake for beginners to download the wrong OS version of VirtualBox. Remember, it does not matter which guest OS you want to run. What matters is the operating system that is currently installed and running on your computer.

> **Note**:    The Downloads page links to other useful resources, such as the Extension Pack (more on it later) or the full VirtualBox manual.

Once you click the “Windows hosts” link, the browser should prompt you for confirmation. An example is shown below.

![File download dialog](https://yaki-bcit.github.io/doc-virtualbox/docs/assets/VB-download-03.png)

Depending on your browser, you may see the options to “Run” or “Save” the file. We recommend saving your file. This is useful because having the downloaded file will let you postpone the installation until the most convenient time.

Depending on the settings of your browser, the downloaded file may be saved in the “Downloads” folder of your user, or the browser may prompt you to select the folder.

![Save file dialog](https://yaki-bcit.github.io/doc-virtualbox/docs/assets/VB-download-04.png)

In the latter case, select the location that you will remember, so that accessing or deleting the file is easier in the future.

## Step 2: Install VirtualBox

> **Warning**: Choose installation time wisely. You don’t want any critical process running during installation. Close any unnecessary programs and files before you proceed.

> **Warning**: Make sure that you run installation when your network connection is not critically important.

Although you may be used to installing programs on your computer, installation of VirtualBox involves steps that you may be unfamiliar with. Before you begin, please take at least a quick look at this section to learn what to expect.

One aspect that may be unusual to you is installation of a virtual network adapter. This happens automatically, but you will get a warning that your network, and internet, connection will be temporarily broken.

![Installer network interface warning](https://yaki-bcit.github.io/doc-virtualbox/docs/assets/VB-04.png)

The above warning will be followed by a prompt to confirm installing virtual network adapter software.

![Installer virtual network adapter dialog](https://yaki-bcit.github.io/doc-virtualbox/docs/assets/VB-04.png)

**Note**: If you do not allow the installer to add a virtual network adapter to your computer, your virtual machines will not be able to connect to the internet or your local network.

At the end, the installer will invite you to start VirtualBox.

![Installer final screen](https://yaki-bcit.github.io/doc-virtualbox/docs/assets/VB-08.png)

Now you are ready to [create a virtual machine in VirtualBox](create-vm).
