---
layout: default
title: Introduction
nav_order: 2
---

# Introduction
{: .no_toc }

These instructions will help you get started with VirtualBox, powerful virtualization software that lets you run various guest operating systems on your computer.

{: .fs-6 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---


## Important Terminology

**Virtualization software** is a program that allows you to run extra operating systems, called guest systems or virtual machines, on top of the main operating system, called host operating system.

> **Note**: While these instructions focus on VirtualBox specifically, other virtualization software from different vendors also exists. While there are important differences among such software, the core concepts will remain the same. Thus, once you are comfortable with VirtualBox, you may find other virtualization software, such as VMWare Workstation Player, easy to understand and use.

A host operating system is what is installed for your computer and what you run your programs in every day.

> **Note**: For the purposes of these instructions, we will assume that your host operating system is Windows 10.

A guest operating system or a virtual machine is an operating system that is run with the help of special virtualization software while the host operating system is still running.

For example, if your host operating system is Windows 10, you can run another instance of Windows 10 as a guest system, or a guest linux-based operating system such as Ubuntu.

> **Note**: These instructions include a tutorial for running Ubuntu (linux).

## Who This Guide is For

This guide is for users who have experience working with graphical interfaces, downloading files from the internet and installing programs.

## What You Need

First of all, virtualization is a fairly demanding task. To run your guest operating systems smoothly, your computer should have sufficient specifications. At the bare minimum, your computer must have:

- A processor with at least 2 processing cores
- 4 GB of RAM
- 10 GB of free disk space.

Arguably, some specialized guest operating systems can take advantage of even lower specs. You should note, however, that the above numbers are the absolute lowest limits that allow useful operation of your virtual operating system in most circumstances.

> **Note**: You should always expect your computer to run somewhat more slowly when a virtual operating system is on. This will happen because the single pool of your hardware resources is shared by two operating systems at once.

## Notes and Warnings

These instructions will include important warnings and additional useful information.
