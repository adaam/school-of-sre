# Linux 基礎知識

## 介紹
### 準備事項

- 操作過任何一種作業系統，像是 Windows, Linux 或是 Mac
- Should be comfortable in using any operating systems like Windows, Linux or Mac
- 對作業系統有基礎理解
- Expected to have fundamental knowledge of operating systems

## 從這個課程會學到什麼

課程分為三個部分，在第一個部分會講到有關於 Linux 作業系統的基礎知識，像是 Linux 的架構，各種不同的 Linux 發行版，以及如何使用 Linux 系統等等。在這裡也會提到一些關於圖形介面，以及命令列的差別。

This course is divided into three parts. In the first part, we cover the
fundamentals of Linux operating systems. We will talk about Linux architecture,
Linux distributions and uses of Linux operating systems. We will also talk about the
difference between GUI and CLI.

第二部分會講到一些 Linux 的基礎指令，這部分將會著重在跟檔案系統有關的部分，像是查看檔案、修改檔案或是輸出入重導向等等。

In the second part, we cover some basic commands used in Linux. 
We will focus on commands used for navigating the file system, viewing and manipulating files,
I/O redirection etc.

第三部分會講到 Linux 系統管理，包含管理員會做的每日例行事項，像是管理系統的使用者及群組、管理檔案系統、監控系統效能、監控紀錄檔等等。

In the third part, we cover Linux system administration. This includes day to day tasks 
performed by Linux admins, like managing users/groups, managing file permissions, 
monitoring system performance, log files etc.

在第二及第三部分，我們會使用許多例子來幫助讀者理解其中的概念。

In the second and third part, we will be taking examples to understand the concepts.

## 課程不會討論的範圍
這個課程不會談論到進階的 Linux 指令、 bash 腳本以及 Linux 內部相關資訊。

We are not covering advanced Linux commands and bash scripting in this
course. We will also not be covering Linux internals. 

## 課程內容
課程將涵蓋以下主題：
The following topics has been covered in this course:

-  [Linux 簡介](https://linkedin.github.io/school-of-sre/linux_basics/intro/)
    -  [什麼是 Linux 作業系統](https://linkedin.github.io/school-of-sre/linux_basics/intro/#what-are-linux-operating-systems)
    -  [有哪些熱門的 Linux 發行版](https://linkedin.github.io/school-of-sre/linux_basics/intro/#what-are-popular-linux-distributions)
    -  [如何使用 Linux 作業系統](https://linkedin.github.io/school-of-sre/linux_basics/intro/#uses-of-linux-operating-systems)
    -  [Linux 系統架構](https://linkedin.github.io/school-of-sre/linux_basics/intro/#linux-architecture)
    -  [圖形化使用者介面 (GUI) vs 命令列 (CLI)](https://linkedin.github.io/school-of-sre/linux_basics/intro/#graphical-user-interface-gui-vs-command-line-interface-cli)
-  [命令列基礎](https://linkedin.github.io/school-of-sre/linux_basics/command_line_basics/)
    -  [設定實驗環境](https://linkedin.github.io/school-of-sre/linux_basics/command_line_basics/#lab-environment-setup)
    -  [什麼是指令](https://linkedin.github.io/school-of-sre/linux_basics/command_line_basics/#what-is-a-command)
    -  [檔案系統](https://linkedin.github.io/school-of-sre/linux_basics/command_line_basics/#file-system-organization)
    -  [檔案系統導覽](https://linkedin.github.io/school-of-sre/linux_basics/command_line_basics/#commands-for-navigating-the-file-system)
    -  [修改檔案](https://linkedin.github.io/school-of-sre/linux_basics/command_line_basics/#commands-for-manipulating-files)
    -  [查看檔案](https://linkedin.github.io/school-of-sre/linux_basics/command_line_basics/#commands-for-viewing-files)
    -  [Echo 指令](https://linkedin.github.io/school-of-sre/linux_basics/command_line_basics/#echo-command)
    -  [文字編輯指令](https://linkedin.github.io/school-of-sre/linux_basics/command_line_basics/#text-processing-commands)
    -  [輸出入重定向](https://linkedin.github.io/school-of-sre/linux_basics/command_line_basics/#io-redirection)
-  [Linux 系統管理](https://linkedin.github.io/school-of-sre/linux_basics/linux_server_administration/)
    -  [設定實驗環境](https://linkedin.github.io/school-of-sre/linux_basics/linux_server_administration/#lab-environment-setup)
    -  [管理使用者及群組](https://linkedin.github.io/school-of-sre/linux_basics/linux_server_administration/#usergroup-management)
    -  [成為超級使用者](https://linkedin.github.io/school-of-sre/linux_basics/linux_server_administration/#becoming-a-superuser)
    -  [檔案權限](https://linkedin.github.io/school-of-sre/linux_basics/linux_server_administration/#file-permissions)
    -  [SSH 指令](https://linkedin.github.io/school-of-sre/linux_basics/linux_server_administration/#ssh-command)
    -  [套件管理](https://linkedin.github.io/school-of-sre/linux_basics/linux_server_administration/#package-management)
    -  [行程管理](https://linkedin.github.io/school-of-sre/linux_basics/linux_server_administration/#process-management)
    -  [記憶體管理](https://linkedin.github.io/school-of-sre/linux_basics/linux_server_administration/#memory-management)
    -  [常駐程式以及 Systemd 系統](https://linkedin.github.io/school-of-sre/linux_basics/linux_server_administration/#daemons)
    -  [紀錄檔](https://linkedin.github.io/school-of-sre/linux_basics/linux_server_administration/#logs)
-  [結論](https://linkedin.github.io/school-of-sre/linux_basics/conclusion)
    -  [各種 SRE 角色的運用](https://linkedin.github.io/school-of-sre/linux_basics/conclusion/#applications-in-sre-role)
    -  [有用的課程及教學](https://linkedin.github.io/school-of-sre/linux_basics/conclusion/#useful-courses-and-tutorials)

## 什麼是 Linux 作業系統

大多數人所熟悉的是 Windows 作業系統，占了個人電腦的市場有 75% 以上，Windows 作業系統是基於 Windows NT 核心所設計的。

Most of us are familiar with the Windows operating system used in more than
 75% of the personal computers. The Windows operating systems
are based on Windows NT kernel. 

所謂的核心是作業系統最重要的部分，它被用來執行重要的功能，像是行程管理、記憶體管理以及檔案系統管理等等。

A kernel is the most important part of
an operating system - it performs important functions like process
management, memory management, filesystem management etc.

Linux 作業系統基於 Linux 核心所開發，作業系統包含了 Linux 核心、圖形介面或是命令列、系統函式庫以及系統程式。Linux 核心是由 Linus Torvalds 獨立開發並發布的，整個核心是免費而且開源的  [https://github.com/torvalds/linux](https://github.com/torvalds/linux)

Linux operating systems are based on the Linux kernel. A Linux based
operating system will consist of Linux kernel, GUI/CLI, system libraries
and system utilities. The Linux kernel was independently developed and
released by Linus Torvalds. The Linux kernel is free and open-source -
[https://github.com/torvalds/linux](https://github.com/torvalds/linux)

Linux 的歷史 [https://en.wikipedia.org/wiki/History_of_Linux](https://en.wikipedia.org/wiki/History_of_Linux)


History of Linux -
[https://en.wikipedia.org/wiki/History_of_Linux](https://en.wikipedia.org/wiki/History_of_Linux)

## 有哪些熱門的 Linux 發行版

Linux 發行版指的是基於 Linux 核心所開發的作業系統，並搭配了自己的套件管理系統，套件管理系統包含了一系列在作業系統中，用來幫助使用者做安裝、升級以及移除軟體的工具。

A Linux distribution(distro) is an operating system based on
the Linux kernel and a package management system. A package management
system consists of tools that help in installing, upgrading,
configuring and removing softwares on the operating system.

軟體通常依附在某個發行版中，並且包裝成適合某個發行版的特定格式。這些包裝好的軟體，通常會儲存在某個發行版的軟體倉庫中，而這些包裝好的軟體，可以被系統中的套件管理程式所安裝。

Software are usually adopted to a distribution and are packaged in a
distro specific format. These packages are available through a distro
specific repository. Packages are installed and managed in the operating
system by a package manager.

**部份熱門的 Linux 發行版：**

- Fedora

- Ubuntu

- Debian

- Centos

- Red Hat Enterprise Linux

- Suse

- Arch Linux


| 套件管理系統      | 發行版名稱                              | 套件管理程式
| ---------------------- | ------------------------------------------ | -----------------
| Debian 格式 (.deb)    |   Debian, Ubuntu                          |   APT
| Red Hat 格式 (.rpm)   |   Fedora, CentOS, Red Hat Enterprise Linux |  YUM

## Linux 架構

![](images/linux/commands/image25.png)

# *** 下一句還沒翻譯 ***
- The Linux kernel is monolithic in nature. 

- 系統呼叫是用來跟 Linux 核心層做溝通的
- System calls are used to interact with the Linux kernel space.

- 核心程式只能在核心模式被執行，非核心程式將運行在使用者模式。
- Kernel code can only be executed in the kernel mode. Non-kernel code is executed in the user mode.

- 裝置的驅動程式用來跟硬體裝置溝通
- Device drivers are used to communicate with the hardware devices.

## Linux 作業系統的使用

基於 Linux 核心的作業系統被廣泛的使用在

Operating system based on Linux kernel are widely used in:

- 個人電腦
- Personal computers

- 伺服器
- Servers

- 行動電話 - Android 是基於 Linux 作業系統所開發的
- Mobile phones - Android is based on Linux operating system

- 嵌入式系統 - 手錶、電視、交通號誌等等
- Embedded devices - watches, televisions, traffic lights etc

- 人造衛星
- Satelites

- 網路裝置 - 路由器、交換器等等
- Network devices - routers, switches etc.

## 圖形化介面 (GUI) vs 命令列 (CLI)

使用者都是藉由使用者介面的幫助來跟電腦互動的，它可以是圖形化介面或是命令列。

A user interacts with a computer with the help of user interfaces. The
user interface can be either GUI or CLI.

圖形化介面讓使用者可以藉由圖像，像是影像或是標誌，來跟電腦做互動。當使用者點擊標誌來打開在電腦上的應用程式時，他這時候就是在使用圖型化介面了，透過圖形化介面執行工作是很輕鬆的。

Graphical user interface allows a user to interact with the computer
using graphics such as icons and images. When a user clicks on an icon
to open an application on a computer, he or she is actually using the
GUI. It's easy to perform tasks using GUI.

命令列讓使用者可以藉由指令跟電腦做互動，使用者在終端機輸入指令，而系統則負責執行使用者所輸入的指令。當使用者只有操作過圖形化介面的經驗時，會發現使用命令列較為困難，因為需要知道要使用哪個特定的指令，才能做到他想要叫系統做的事情。

Command line interface allows a user to interact with the computer using
commands. A user types the command in a terminal and the system helps in
executing these commands. A new user with experience on GUI may find it 
difficult to interact with CLI as he/she needs to be aware of the commands
to perform a particular operation.

## 未翻譯
## Shell vs Terminal 

Shell is a program that takes commands from the
users and gives them to the operating system for processing. Shell is an
example of a CLI(command line interface). Bash is one of the most popular shell
programs available on Linux servers. Other popular shell programs are
zsh, ksh and tcsh.

Terminal is a program that opens a window and lets you interact with the
shell. Some popular examples of terminals are gnome-terminal, xterm,
konsole etc.

Linux users do use the terms shell, terminal, prompt, console etc.
interchangeably. In simple terms, these all refer to a way of taking
commands from the user.
