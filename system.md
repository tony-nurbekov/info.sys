# Awesome System Software

## Contents

1. UEFI/BIOS
2. Операционная система
3. Прикладное программное обеспечение
4. Виртуализация и Контейнеризация



## UEFI/BIOS

Unified Extensible Firmware Interface или UEFI  — это встроенное программное обеспечение, 
которое управляет аппаратными устройствами, и предоставляет программный интерфейс, 
который помогает операционной системе управлять оборудованием.
Он пришел на смену устаревшему классическому BIOS.

**Процесс загрузки Linux**
1. Инициализация оборудования (BIOS / UEFI)
	- BIOS: Выполняет самотестирование при включении (POST), ищет загрузочный сектор (MBR) на физическом носителе и передает управление первичному загрузчику.
	- UEFI: Современный стандарт прошивки. Считывает таблицу разделов GPT и загружает исполняемый файл .efi (например, GRUB) со специального системного раздела (ESP).
2. Загрузчик (Bootloader, например, GRUB2)
	- Находит и загружает в оперативная память (RAM) образ ядра Linux (vmlinuz) и начальный виртуальный диск (initrd.img или initramfs) из директории /boot.
	- Передает управление ядру вместе с заданными параметрами командной строки.
3. Инициализация ядра (Kernel Init)
	- Ядро распаковывает само себя, определяет и инициализирует аппаратные устройства (процессор, память, периферию).
	- Монтирует временную файловую систему из initramfs для получения доступа к драйверам и поиска постоянной корневой файловой системы (rootfs).
	- Запускает первый пользовательский процесс с идентификатором PID 1 (systemd или классический init).
4. Система инициализации и службы (systemd / init)
	- Systemd (в современных дистрибутивах) читает конфигурационные файлы, монтирует основные и дополнительные файловые системы согласно /etc/fstab.
	- Запускает системные службы, сетевые интерфейсы и целевой уровень загрузки (target, например, многопользовательский текстовый или графический graphical.target).
5. Вход в систему (Login)
	- Запускается графический дисплейный менеджер (GDM, SDDM, LightDM) или текстовая консоль с приглашением ввести имя пользователя и пароль.



## Операционная система

Операционная система (ОС) - это системное программное обеспечение, которое управляет 
аппаратными и программными ресурсами компьютера и предоставляет общие услуги для компьютерных программ. 

**Основные функции ОС**

• Управление ресурсами: выделение оперативной памяти, распределение процессорного времени между задачами и управление накопителями.
• Взаимодействие с оборудованием: драйверы связывают ОС с комплектующими (видеокартами, принтерами, клавиатурами).
• Обеспечение интерфейса: создание графической (GUI) или командной (CLI) оболочки, через которую пользователь управляет системой.
• Файловая система: организация хранения, удаления и быстрого доступа к данным на дисках (например, через NTFS или EXT4).
• Запуск программ: создание изолированной среды для выполнения прикладного софта.

*Kernel Space (Пространство ядра)*
- Драйверы устройств, firmware
- Системные вызовы (System Calls)
- Системные библиотеки
- Компиляторы и интерпретаторы
- Файлы и файловые системы
- Управление процессами и потоками
- Сервисы (Daemon)
- Управление памятью
- Ввод/Вывод (Input/Output - I/O)
- Сетевая подсистема
* Форматы исполняемых файлов (PE, ELF)
- Прерывание
- Безопасность системы:
    - Пользователи и Группы (Users & Groups)
    - Права доступа к файлам (File Permissions)
----------------------------------------------------
*User Space (Пространство пользователя)*
- Initialization Daemon (init, systemd) 
- System Daemons (sshd, udevd)
- Оконные менеджеры и интерфейсы
- Standard C Library (up to 2000 subroutines)
- GNU Compiler Collection (GCC) 
- Shell - bash, PowerShell, cmd
- Интерфейсы приложений (GUI, CLI, TUI)





## Виртуализация и Контейнеризация

- [docker-github](https://github.com/docker)
- [Manuals/Docker Engine](https://docs.docker.com/engine/)
- [Install Docker Engine](https://docs.docker.com/engine/install/ubuntu/)
- [download Docker Engine](https://download.docker.com/linux/ubuntu/dists/noble/pool/stable/amd64/)
- [docker-cheat-sheet](https://github.com/wsargent/docker-cheat-sheet.git) - Docker Cheat Sheet
- [VirtualBox, VMWare, Genymotion, QEMU]



## Daemon (computing)

- systemd is a software suite for system and service management on Linux
- daemons and utilities, including device management, login management, network connection and event logging.
of naming daemons by appending the letter d (sshd, udevd)
*systemd utils* - systemctl, journalctl, loginctl


##  Pipeline

Pipeline - the output (stdout) of each process is 
passed directly as the input (stdin) to the next process.










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


## Расширение файлов

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
- .tar / .gz / .zip — Archives (may include sources or binaries)  
- .pdf — Portable Document Format (docs, manuals)  
- .png / .jpg / .jpeg / .gif / .svg — Images (assets)   
- .ttf / .otf — Fonts  
- .mp3 / .wav / .ogg — Audio files  
- .mp4 / .avi / .mkv — Video files  









*awesome-linux* 
* [Awesome-Linux-Software](https://github.com/luong-komorebi/Awesome-Linux-Software.git) 
* [awesome-the-secret-book](https://github.com/T-450/the-book-of-secret-knowledge)
* [awesome-shell](https://github.com/alebcay/awesome-shell.git)
* [awesome-cli-apps](https://github.com/agarrharr/awesome-cli-apps.git)
* [awesome-cheatsheets](https://github.com/LeCoupa/awesome-cheatsheets.git)
* [awesome-windows](https://github.com/0PandaDEV/awesome-windows.git)
* [GNU Linux Pro](https://gnulinux.pro) 
- [stackexchange](https://psychology.stackexchange.com/) - All Sites stackexchange Hub

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













