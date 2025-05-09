---
title: "在Mac上使用TreeMaker"
excerpt_separator: "<!--more-->"
categories:
  - Blog
tags:
  - origami
  - apps
  - Mac
---

# 在Mac上使用TreeMaker
近期，折纸大师 Robert Lang 在他的 [官网](https://langorigami.com/) 上发布了 [最新 TreeMaker 工具](https://langorigami.com/article/treemaker/)。本教程将指导您如何在 macOS 上安装和使用这款工具。

<!--more-->

## 更新信息

> At present, I have no plans to update TreeMaker any further. Alas, with the continued evolution of operating systems and their dropping of backward compatibility, there are fewer and fewer computers on which it will work. However, I invite anyone who is interested to update any version for a current OS, and I’d be happy to post links here if you do.

**更新时间：2025-01-30**

Vish Vishvanath 已成功让 TreeMaker 在 **macOS Sonoma** 上运行！  
**[点击查看 GitHub 项目](https://github.com/vishvish/treemaker)**，了解最新进展。

---

## 安装步骤（macOS）

### 1. 下载 TreeMaker

前往 [GitHub Releases 页面](https://github.com/vishvish/treemaker/releases) 或点击以下链接直接下载：

- [treemaker.zip 下载链接](https://github.com/vishvish/treemaker/releases/download/v5.1.1M-beta/TreeMaker.zip)

您也可以直接  
[TreeMaker.zip](https://github.com/user-attachments/files/19907649/TreeMaker.zip)下载

### 2. 解压安装包

在 Mac 上双击解压 `treemaker.zip` 文件，解压后得到 `treemaker.app`。

![解压文件示意图](https://www.zhezhixueyuan.com/data/attachment/album/202503/18/193916ssp5s2a3js5if5li.png)

### 3. 移动到应用程序文件夹

将解压得到的 `treemaker.app` 拖动到 **Applications** 文件夹中。

![移动应用程序](https://www.zhezhixueyuan.com/data/attachment/album/202503/18/194332z5aedaedaflk1nkf.png)

### 4. 如无法打开应用，解决办法如下：

1. 打开 [Terminal 终端](https://support.apple.com/zh-cn/guide/terminal/welcome/mac)

   ![Terminal 图标](https://help.apple.com/assets/65DFB7A79DFEC61A7A0517AC/65DFB7A793CD15C0410BA37D/zh_CN/d94aa1c4979b25e9ffbda97fcbae219a.png)

2. 在 Terminal 中输入以下命令：

   ```bash
   sudo xattr -d com.apple.quarantine 
   ```

3. 将 `treemaker.app` 文件拖入 Terminal 窗口中，然后按下回车键：

   ![](https://www.zhezhixueyuan.com/data/attachment/album/202503/18/195248n3nkaaz7q737bsq7.png)  
   ![](https://www.zhezhixueyuan.com/data/attachment/album/202503/18/195249nl1ggpu91vvo0opg.png)

4. 系统提示输入密码时，请直接输入（不会显示字符是正常的）：

   ![](https://www.zhezhixueyuan.com/data/attachment/album/202503/18/195500o60262jxq6q2zbr3.png)

### 5. 打开 TreeMaker 应用

现在再次双击 `treemaker.app` 应用即可成功运行！

![程序运行截图](https://www.zhezhixueyuan.com/data/attachment/album/202503/18/195739tw1u1ge44vg4g8gc.png)
