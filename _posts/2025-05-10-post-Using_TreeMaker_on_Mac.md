---
title: "在Mac上使用TreeMaker"
date: 2025-05-10T00:00:00-04:00
categories:
  - Blog
tags:
  - origami
  - apps
  - Mac
---
# Using TreeMaker on Mac

Recently, origami master Robert Lang released the latest TreeMaker tool on his [official website](https://langorigami.com/). This tutorial will guide you on how to install and use this tool on macOS.

## Update Information

> At present, I have no plans to update TreeMaker any further. Alas, with the continued evolution of operating systems and their dropping of backward compatibility, there are fewer and fewer computers on which it will work. However, I invite anyone who is interested to update any version for a current OS, and I’d be happy to post links here if you do.

**Update Date: January 30, 2025**

Vish Vishvanath has successfully made TreeMaker run on **macOS Sonoma**!  
**[Click here for the GitHub project](https://github.com/vishvish/treemaker)** to check the latest developments.

## Installation Steps (macOS)

### 1. Download TreeMaker

Go to the [GitHub Releases page](https://github.com/vishvish/treemaker/releases) or click the link below to download directly:

- [treemaker.zip Download Link](https://github.com/vishvish/treemaker/releases/download/v5.1.1M-beta/TreeMaker.zip)

You can also directly download [TreeMaker.zip](https://github.com/user-attachments/files/19907649/TreeMaker.zip).

### 2. Extract the Installation Package

Double-click the `treemaker.zip` file to extract it on your Mac. After extraction, you will get the `treemaker.app`.

### 3. Move to Applications Folder

Drag the extracted `treemaker.app` to the **Applications** folder.

### 4. If the application does not open, follow these steps:

1. Open [Terminal](https://support.apple.com/zh-cn/guide/terminal/welcome/mac).
   
2. In Terminal, type the following command:

   ```bash
   sudo xattr -d com.apple.quarantine
   ```

3. Then, drag the `treemaker.app` file into the Terminal window.

4. Press Enter. The system will prompt you to enter your password (characters will not be displayed when you type, which is normal).

### 5. Open TreeMaker Application

Now, double-click the `treemaker.app` again, and it should open successfully!

