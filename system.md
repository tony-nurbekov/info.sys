# Awesome Operating Systems

## Contents


1. *User Space (Пространство пользователя)*
- Initialization Daemon (init, systemd) 
- System Daemons (sshd, udevd)
- Window Managers & GUI (Оконные менеджеры и интерфейсы)
- Standard C Library (up to 2000 subroutines)
- GNU Compiler Collection (GCC) 
- Shell — bash, PowerShell, cmd
- Applications
- Интерфейсы приложений (GUI, CLI, TUI)
----------------------------------------------------
2. *Kernel Space (Пространство ядра)*
- System Calls (Системные вызовы)
- Файлы и файловые системы
- Управление процессами и потоками
- Daemon(Services)
- Управление памятью
- Input/Output (I/O)
- Drivers, firmware
- Сетевая подсистема
* Форматы исполняемых файлов (PE, ELF)
- Interrupt
- Безопасность системы:
    - Пользователи и Группы (Users & Groups)
    - Права доступа к файлам (File Permissions)




## Daemon (computing)

- systemd is a software suite for system and service management on Linux
- daemons and utilities, including device management, login management, network connection and event logging.
of naming daemons by appending the letter d (sshd, udevd)
*systemd utils* - systemctl, journalctl, loginctl


##  Pipeline

Pipeline - the output (stdout) of each process is 
passed directly as the input (stdin) to the next process.



## *Everything is a file*



## GNU/Linux Package

- Cookbook, Documentation, Manual is a cookery book.
- [info](https://en.wikipedia.org/wiki/Info_(Unix)) 
- [man](https://mirrors.edge.kernel.org/pub/linux/docs/man-pages/book/) 
- [help](https://en.wikipedia.org/wiki/Apropos_%28Unix%29?utm_source=chatgpt.com) 
----------------------------------------------------
- [curl cheat.sh ](https://github.com/chubin/cheat.sh) 
- [tildr-pages](https://github.com/tldr-pages/tldr) 
----------------------------------------------------
- [Пакеты «Deb»](https://packages.ubuntu.com/src) 
- [snapcraft](https://snapcraft.io/)
 ----------------------------------------------------
- [GNU Package](https://directory.fsf.org/wiki/GNU) 
- [ftp.gnu.org](https://ftp.gnu.org/) 
- [List of GNU packages](https://en.wikipedia.org/wiki/List_of_GNU_packages)
- [GNU Coreutils pdf](https://www.gnu.org/software/coreutils/manual/coreutils.pdf) 
- [GNU Coreutils html](https://www.gnu.org/software/coreutils/manual/coreutils.html)
- [GNU Software](https://www.gnu.org/software/software.html) 
- [GNU Manuals Online](https://www.gnu.org/manual/manual.html)
- [Linux Network Administrators Guide](https://tldp.org/LDP/nag2/index.html)
- [Bash (Unix shell)](https://www.gnu.org/software/bash/manual/bash.pdf)
- [LAMP: Linux+Apache2/nginx+PostgreSQL/SQLite+Python/JS/Node.js](https://github.com/gnulinuxpro)
- [BusyBox, Toybox] - is a free and open-source software - 200 Unix command line utilities.
- [util-linux] is a package of utilities.


## Software development - GNU toolchain

- GNU Autotools (build system) – Software build toolset from GNU
- GNU Binutils – GNU software development tools for executable code
- GNU Bison – Yacc-compatible parser generator program
- GNU C Library – GNU implementation of the standard C library
- GNU Compiler Collection – Free and open-source compiler for various programming languages
- GNU Debugger – Source-level debugger
- GNU m4 – General-purpose macro processor
- GNU make – Software build automation tool
- Compiler: GNU Compiler Collection (GCC), Clang
- build-essential


## Containers and Virtualization

- [docker-github](https://github.com/docker)
- [Manuals/Docker Engine](https://docs.docker.com/engine/)
- [Install Docker Engine](https://docs.docker.com/engine/install/ubuntu/)
- [download Docker Engine](https://download.docker.com/linux/ubuntu/dists/noble/pool/stable/amd64/)
- [docker-cheat-sheet](https://github.com/wsargent/docker-cheat-sheet.git) - Docker Cheat Sheet
- [VirtualBox, VMWare, Genymotion, QEMU]
----------------------------------------------------
*Operation system tools*
- top, htop, nmon – monitoring process and daemon
- tmux, screen - multisession tools
----------------------------------------------------
- Ansible
- Kubernetes
- Terraform
----------------------------------------------------


## Best practice for Data storage, Data backup*

USB/HDD/SSD/Google/Dropbox/Yandex Cloud:
- /dev/sdX1 — EFI (512 MB) //Install Загрузчик GRUB2 на диске 
- /dev/sdX2 — /system (100gb GB, ext4)
- /dev/sdX3 — /data   (всё остальное, ext4) #backupcopy





- x86-64 (also known as x64, x86_64, AMD64, and Intel 64)



## Common Directories in GitHub Repositories

- src/ – source code of the project.
- lib/ – libraries or helper modules.
- bin/ – executable scripts or binaries.
- test/ – unit tests, integration tests.
- docs/ – project documentation.
- examples/ – example usage code.
- scripts/ – utility or build scripts.
- config/ – configuration files.
- assets/ – images, fonts, static files.
- build/ or dist/ – compiled output (sometimes ignored in .gitignore).
- notebooks/ – Jupyter notebooks for data science projects.
- data/ - local data
- config/ - settings and config (YAML/JSON)
- logs/ - Логи выполнения

**Common Files in GitHub Repositories**
- README.md – main documentation (Markdown).
- LICENSE – license info (MIT, Apache, GPL, etc.).
- .gitignore – files/folders ignored by Git.
- CONTRIBUTING.md – guidelines for contributors.
- CHANGELOG.md – version history.
- Makefile – build/automation instructions (C, C++, Go, etc.).
- Dockerfile – instruc- tions for building Docker images.
- requirements.txt – Python dependencies.
- pyproject.toml / setup.py – Python packaging configs.
- package.json – Node.js project metadata & dependencies.
- CMakeLists.txt – CMake build configuration.








## Everything is a file (Unix)


**Most Popular File Extensions on GitHub**

1. Text-based Extensions
- .js — JavaScript (frontend, backend)  
- .ts — TypeScript (typed JavaScript)  
- .py — Python (scripting, backend, ML/AI)  
- .java — Java (enterprise, Android)  
- .rb — Ruby (web, scripting)  
- .php — PHP (web backend)  
- .html — HTML (markup for web)  
- .css — CSS (stylesheets)  
- .json — JSON (data, configuration)  
- .xml — XML (data, configuration)  
- .yml / .yaml — YAML (configs, CI/CD pipelines)  
- .md — Markdown (documentation, README files)  
- .c — C (systems programming)  
- .cpp — C++ (high-performance apps)  
- .h / .hpp — C/C++ headers  
- .kt — Kotlin (Android, backend)  
- .sh — Shell scripts (automation, Linux)  
- .bat — Batch scripts (Windows automation)   
- .ini — INI (legacy configs)  

---

2. Binary Extensions
- .exe — Windows executables  
- .dll — Windows dynamic-link library  
- .so — Linux shared object library  
- .o — Compiled object file  
- .class — Java bytecode  
- .jar — Java Archive (mixed code/resources)  
- .apk — Android application package  
- .app — macOS application bundle  
- .a — Static library (C/C++)  
- .bin — Raw binary data  
- .iso — Disk image  
- .dmg — macOS disk image  
- .img — System/firmware image  
- .deb — Debian package  
- .rpm — RedHat package  
- .tar / .gz / .zip — Archives (may include sources or binaries)  
- .pdf — Portable Document Format (docs, manuals)  
- .png / .jpg / .jpeg / .gif / .svg — Images (assets)  
- .ico — Icons  
- .ttf / .otf — Fonts  
- .mp3 / .wav / .ogg — Audio files  
- .mp4 / .avi / .mkv — Video files  








## Режимы Android

- Пользовательские — Normal Mode, Safe Mode, SOS Mode.
- Сервисные — Recovery, Fastboot, Bootloader, Download, Rescue.
- Инженерные — Factory Mode, Engineer Mode, Meta Mode.
- Низкоуровневые аварийные — EDL Mode и другие специализированные режимы восстановления.


- [Linux Command Library](https://linuxcommandlibrary.com/) - Android app
- [GNU Linux Pro](https://www.youtube.com/@GNULinuxPro)




## Windows version 

USB/Sources/>ei.cfg:
```
[EditionID]
[Channel]
Retail
```


## Microsoft Activation Scripts (MAS)

Open-source Windows and Office activator featuring HWID, Ohook, TSforge, and Online KMS activation methods, 
along with advanced troubleshooting.

- [Microsoft Activation Scripts (MAS) in Github](https://github.com/massgravel/Microsoft-Activation-Scripts.git)



## Windows local user
- start ms-cxh:localonly


## Diskpart
```
diskpart
list disk
select disk 2
detail disk
clean
```



## Mobile Service Toolkit

- ADB/Fastboot
- Odin
- iTunes
- SamFW Tool
- Mi Flash Tool
- SP Flash Tool
- QFIL
- 3uTools
- QPST
- Chimera Tool (платный)
- [UnlockTool](https://unlocktool.net/)




*awesome-linux* 
* [Awesome-Linux-Software](https://github.com/luong-komorebi/Awesome-Linux-Software.git) 
* [awesome-the-secret-book](https://github.com/T-450/the-book-of-secret-knowledge)
* [awesome-shell](https://github.com/alebcay/awesome-shell.git)
* [awesome-cli-apps](https://github.com/agarrharr/awesome-cli-apps.git)
* [awesome-cheatsheets](https://github.com/LeCoupa/awesome-cheatsheets.git)
* [awesome-windows](https://github.com/0PandaDEV/awesome-windows.git)
* [GNU Linux Pro](https://gnulinux.pro) 
- [stackexchange](https://psychology.stackexchange.com/) - All Sites stackexchange Hub