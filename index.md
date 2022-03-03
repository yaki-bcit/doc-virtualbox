---
layout: default
title: VirtualBox Documentation
nav_order: 1
---

# VirtualBox Documentation

![VirtualBox Logo](https://wiki.robotz.com/images/e/ea/Virtualbox-logo.png)

## Introduction
{: .no_toc }

This document is for Level 1 Full-Stack Web Development students and other entry-level students at BCIT who need to use a linux operating system, but don't want to reinstall their main operating system or buy new dedicated hardware.

These instructions will help you get started with VirtualBox, powerful virtualization software that lets you run various guest operating systems on your computer.

This document will help you get started with an Ubuntu virtual machine:

* You will download and install VirtualBox on your Windows or Mac computer or laptop
* You will create a virtual machine for Ubuntu in VirtualBox
* You will download and install Ubuntu inside your virtual machine
* You will take the first steps to get started in Ubuntu.

[Ubuntu virtual machine running in VirtualBox in Windows](.assets/screen.png)

While these instructions focus on VirtualBox specifically, other virtualization software from different vendors also exists. While there are important differences among such software, the core concepts remain the same. Thus, once you are comfortable with VirtualBox, you may find other virtualization software, such as VMWare Workstation Player, easy to install and use.

For the purposes of these instructions, we will assume that your host operating system is Windows 10 (for Windows) or macOS Monterey (for macOS).



{: .fs-6 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Important Terminology

**Virtualization software** is a program that allows you to run extra operating systems, called guest systems or virtual machines, on top of the main operating system, called host operating system.

A host operating system is what is installed for your computer and what you run your programs in every day.

A guest operating system or a virtual machine is an operating system that is run with the help of special virtualization software while the host operating system is still running.

For example, if your host operating system is Windows 10, you can run another instance of Windows 10 as a guest system, or a guest linux-based operating system such as Ubuntu.

## Who This Guide is For

This guide is for users who have experience working with graphical interfaces, downloading files from the internet and installing programs.

## What You Need

First of all, virtualization is a fairly demanding task. To run your guest operating systems smoothly, your computer should have sufficient specifications. At the bare minimum, your computer must have:

- [A processor with at least 2 processing cores](https://support.microsoft.com/en-us/windows/find-out-how-many-cores-your-processor-has-3126ef99-0247-33b3-81fc-065e9fb0c35b)
- 4 GB of RAM
- 10 GB of free disk space.

Arguably, some specialized guest operating systems can take advantage of even lower specs. You should note, however, that the above numbers are the absolute lowest limits that allow useful operation of your virtual operating system in most circumstances.

> **Note**: You should always expect your computer to run somewhat more slowly when a virtual operating system is on. This will happen because the single pool of your hardware resources is shared by two operating systems at once.

## Notes and Warnings

These instructions will include important warnings and additional useful information.

You have already seen notes on this page. They contain extra details that are not critical for following the steps but may give you useful background. Notes look like this:

> **Note**: Some text.

In some places, you will see warnings, which point out critically important thinks you should do or know. **Don't skip warnings!** Warnings look like this:

> **Warning**: Some text.

Let's get started!
