# Awesome Computing Information Systems


# Algorithms for solving problems, The Art of Programming


****************************************************
## IT and Programming Fundamentals
1. Информация и информационные процессы
- Информация 
- Данные
- Классификация информации
- Информационные процессы
- Свойства информации
- Конфиденциальная информация 
- Теория кодирования
----------------------------------------------------
2. Математические основы вычислений
- Системы счисления
- Двоичная система
- Представление чисел в компьютере
- Булева алгебра (AND/OR/NOT)
- Булева логика (TRUE and FALSE, Истина/Ложь, 0/1)
- Линейная алгебра
----------------------------------------------------
3. Архитектура компьютера
- Клод Шеннон
- Машина Тьюринга
- Архитектура фон Неймана
- Логические элементы
- Логические схемы
- Арифметико-логическое устройство (АЛУ)
- Процессор
- Регистры
- Память
- Шины
- Машинные команды
- Представление данных внутри компьютера
*Системные уровни (от софта к железу)*
- Операционные системы: Среда выполнения (Unix, GNU/Linux, Ubuntu, Android).
- Языки низкого уровня: Ассемблер (x86-64, arm64), который переводит код человека в бинарный код (001100).
- Аппаратный уровень: Процессор (CPU) и оперативная память (RAM), состоящие из миллиардов транзисторов — 
полупроводников, которые управляют электрическими сигналами.
----------------------------------------------------
4. Алгоритмы
- Блок-схемы
- Псевдокод
- Условия
- Циклы
- Рекурсия
- Декомпозиция задач
- Big O
----------------------------------------------------
5. Алгоритмы и структуры данных
* Алгоритм — это четкая последовательность действий для решения задачи.
* Структура данных — формат организации и хранения данных для эффективного доступа к ним.
* Сортировка и поиск — фундаментальные механизмы для наведения порядка в данных.
*Структура данных*
- Массив
- Строка
- Связный список
- Стек
- Очередь
- Хеш-таблица
- Дерево
- Граф
- Куча
----------
**Алгоритмы**
- Сортировка и Пойск
----------------------------------------------------
6. Парадигмы и подходы к программированию
- Динамическое программирование
- Алгоритм «разделяй и властвуй»
- Структурное программирование
- Объектно-ориентированное программирование
- Компонентно-ориентированное программирование
- Событийно-ориентированное программирование
- Модульное программирование
----------------------------------------------------
7. Основы программирования
- Переменные
- Типы данных
- Операторы
- Выражения
- Ввод / вывод
- Условия
- Циклы
- Функции
- Параметры и аргументы
- Область видимости
- Пакеты и зависимости
- Стандартная библиотека
- Модули
- Обработка ошибок
- Работа с файлами
- Отладка
- Тестирование
- Управление памятью
- Интерпретация и Компиляция
****************************************************








****************************************************
**Python Language Programming and PyPi libraries**
----------------------------------------------------
- [PyPI](https://pypi.org/)
- [uv](https://github.com/astral-sh/uv)
- [python3-venv или conda] - virtual environment
----------------------------------------------------
- Package install: pip install requests
- Package delete: pip uninstall <имя>
- File requirements: requirements.txt
- Code Run: python main.py
----------------------------------------------------
*The Python Scientific libs*
- Pandas, NumPy, Matplotlib 
- SciPy, Biopython 
- Pygame 
*The Python image processing*
- Pillow, scikit-image
- OpenCV (Open Source Computer Vision Library) 
----------------------------------------------------
*Python linux directories*
/usr/bin/python3.12          ← Interpreter
/usr/lib/python3.12/         ← standart libs
/usr/lib/python3/dist-packages/ ← apt packages
~/.local/lib/python3.12/site-packages/ ← pip
venv/lib/python3.12/site-packages/     ← venv
****************************************************
*Java - Build tools*	
- Gradle, Maven, TeamCity
****************************************************
**JavaScript, TypeScript**
- [Node.js] - Среда выполнения
- [npm] - Менеджер пакетов 
- [npmjs.com](https://www.npmjs.com) - Репозиторий пакетов
- [npm install <имя>, npm uninstall <имя>]() - Установка, Удаление пакета
- [package.json] - Файл зависимостей
- [node_modules] - Виртуальная среда
****************************************************
















****************************************************
## System Software (Operating System Architecture)
- x86-64 (also known as x64, x86_64, AMD64, and Intel 64)
1. *User Space*
- Initialization Daemon (init, systemd) 
- System Daemons (sshd, udevd)
- Window manager (X Window System - X11, Desktop Window Manager)
- Standard C Library (up to 2000 subroutines)
- GNU Compiler Collection (GCC) 
- Low-level API (Windows API, Linux syscalls)
- Shell — bash, PowerShell, cmd
- Applications
----------------------------------------------------
2. *Kernel Space*
- System calls (about 380)
- Files and File Systems 
- Processes and threads 
- Daemon(Services) - is a program that runs as a background process
- User Accounts
- Memory management 16, 32, 64-bit
- Input/Output (I/O)
- Drivers, firmware
- Network Subsystem
* Portable Executable
* Executable and Linkable Format
- Interrupt
----------------------------------------------------
**Daemon (computing)**
- systemd is a software suite for system and service management on Linux
- daemons and utilities, including device management, login management, network connection and event logging.
of naming daemons by appending the letter d (sshd, udevd)
*systemd utils* - systemctl, journalctl, loginctl
----------------------------------------------------
* Pipeline - the output (stdout) of each process is 
passed directly as the input (stdin) to the next process.
----------------------------------------------------
* *Everything is a file*
----------------------------------------------------
*GNU/Linux Package*
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
----------------------------------------------------
**Software development - GNU toolchain**
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
*Containers and Virtualization*
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
*awesome-linux* 
* [Awesome-Linux-Software](https://github.com/luong-komorebi/Awesome-Linux-Software.git) 
* [awesome-the-secret-book](https://github.com/T-450/the-book-of-secret-knowledge)
* [awesome-shell](https://github.com/alebcay/awesome-shell.git)
* [awesome-cli-apps](https://github.com/agarrharr/awesome-cli-apps.git)
* [awesome-cheatsheets](https://github.com/LeCoupa/awesome-cheatsheets.git)
* [awesome-windows](https://github.com/0PandaDEV/awesome-windows.git)
* [GNU Linux Pro](https://gnulinux.pro) 
- [stackexchange](https://psychology.stackexchange.com/) - All Sites stackexchange Hub
----------------------------------------------------
*Best practice for Data storage, Data backup*
USB/HDD/SSD/Google/Dropbox/Yandex Cloud:
- /dev/sdX1 — EFI (512 MB) //Install Загрузчик GRUB2 на диске 
- /dev/sdX2 — /system (100gb GB, ext4)
- /dev/sdX3 — /data   (всё остальное, ext4) #backupcopy
****************************************************




****************************************************
## Network Technology
1. Архитектура и базовые понятия сетей
- Локальная сеть (Local Area Network - LAN)
- Глобальная сеть (Wide Area Network - WAN)
- Клиент и сервер (Client / Server)
- Сетевой протокол (Network Protocol)
- Сетевая модель OSI, модель TCP/IP
- Инкапсуляция/ДеИнкапсуляция
- Маршрутизация и коммутация (Routing and Switching)
- Network address translation (NAT)
- Топология сети (Network Topology) - Шина, Звезда, Кольцо
----------------------------------------------------
2. Сетевая адресация
- IP-адрес (IP Address), Маска подсети (Subnet Mask), Шлюз (Gateway)
- MAC-адрес 
- ARP-таблица
----------------------------------------------------
3. Передача данных
- Сетевой пакет (Network Packet)
- Сегмент (Segment)
- Датаграмма (Datagram)
- Кадр (Frame)
- Файрвол (межсетевой экран или брандмауэр)
- Virtual private network (VPN), OpenVPN, WireGuard
- Port forwarding - iptables, ufw (Uncomplicated Firewall), ngrok
4. Транспорт и соединения
- Порт (Port)
- Сокет (Socket)
----------------------------------------------------
**model OSI and model TCP/IP**
1. Application layer: HTTPS, FTP, DNS, DHCP, Telnet, SSH, Secure Shell, SMTP, SMB
2. Presentation layer: SSL, TLS, MIME, JPEG, GIF
3. Session layer: Sockets, PPTP, L2TP, NetBIOS, RPC
4. Transport layer: TCP and UDP
5. Network layer (Router): IP (IPv4, IPv6), ICMP, IPsec
6. Data link layer (Switch): ARP, MAC, Ethernet
7. Physical layer (Hubs/0011001): Twisted pair, Optical fiber, Bluetooth, Wi-Fi, 
----------------------------------------------------
- Virtual Private Server (VPS)
- Google Drive, Dropbox, Yandex Disk
- cloud.google.com - Cloud Computing Services
----------------------------------------------------
**Активное сетевое оборудование**
* Сетевой контроллер (Net Controller / NIC)
* Маршрутизатор (Router) 
* Коммутатор (Switch) и Хаб (Hub)
  * CLI, SNMP agent and web interface
* Беспроводная точка доступа (Wireless Access Point — AP)
* Повторитель (Repeater)
* Оптический медиаконвертер (Fiber Media-Converter)
* Brand network hardware: TP-Link, D-Link, hikvision, HUAWEI
----------------------------------------------------
**Пассивное сетевое оборудование**
* Кабели связи (Витая пара), Cable UTP, FTP Сat5e
* Модульный разъем (Modular Connector)
* Оптическое волокно и SFP-модули (Optical fiber & SFP)
* IP-телефония (VoIP)
* Мобильные сети (Mobile Networking) GSM, UMTS, LTE
----------------------------------------------------
- Network address translation (NAT) - Transformation 
Local area network (LAN) => в Wide area network (WAN).
Router (NAT): 192.168.0.2:5432(LAN) → 93.184.216.34:6001(WAN)
----------------------------------------------------
**Local Private addresses**
1. Class A: 10.0.0.0 – 10.255.255.255
2. Class B: 172.16.0.0 – 172.31.255.255
3. Class C: 192.168.0.0 – 192.168.255.255
- 192.168.0.0/24 or 192.168.0.0/16
----------------------------------------------------
- [Linux Network Administrators Guide](https://tldp.org/LDP/nag2/index.html) - 
- [Introduction to TCP/IP Networks](https://mirrors.edge.kernel.org/pub/linux/docs/man-pages/book/)
- [The Apache HTTP Server](https://httpd.apache.org/docs-project/) 
****************************************************
**Network CLI Tools**
1. Network Diagnostics & Routing
- ping, pathping, hping3, traceroute, tracepath, TRACERT, mtr
2. DNS Tools
- dig, nslookup 
3. Network Configuration & Interfaces
- ip, ifconfig, netstat, route, nmcli
4. Ethernet & Low-Level Networking
- inetutils, ethtool, ip link, bridge
5. Wireless / Wi-Fi Tools
- iw, iwconfig, iwlist, iwspy
6. Network & Port Scanners
- nmap, masscan
7. LAN Discovery & ARP Tools
- arp, arp-scan, Netdiscover
8. File Transfer: rsync, scp, sftp
9. HTTP/FTP Download Tools
- curl, wget
10. TCP/UDP connections and debugging
- ss, netcat (nc)
11. Firewall & Packet Filtering
- ufw, iptables, nftables
12. Traffic Monitoring
- Wireshark, tcpdump, tshark
13. Remote Access: OpenSSH, PuTTY, Termius
14. Network Performance: iperf, iperf3, speedtest-cli
15. VPN & Tunneling
- wireguard, wg, openvpn, autossh
----------------------------------------------------
- FileZilla, Anydesk, TeamViewer, IpScanner
- Mozilla Thunderbird, MS Outlook, MS Exchange Server
----------------------------------------------------
**Remote administration software**
- [Remote administration software](https://en.wikipedia.org/wiki/Remote_administration)
- The Secure Shell Protocol (SSH Protocol) 
- OpenSSH, PuTTY, Termius, MobaXterm, rsync
- RustDesk, AnyDesk, TeamViewer, Remmina, Chrome Remote Desktop
----------------------------------------------------
**Virtual private network (VPN)**
- Tailscale, OpenVPN, WireGuard
----------------------------------------------------
**Маршрутизация и коммутация**
Маршрутизация и коммутация — это два основных процесса для передачи данных в компьютерных сетях, 
которые работают на разных уровнях модели OSI.
Главные различия
* Коммутация (создание связи внутри сети):
	- Уровень OSI: Канальный (L2)
	- Адресация: Использует MAC-адреса (физические адреса устройств)
	- Задача: Соединяет устройства (компьютеры, принтеры) в пределах одной локальной сети (LAN)
	- Оборудование: Коммутатор (свитч) пересылает кадры данных только на тот порт, к которому подключен нужный адресат
* Маршрутизация (связь между сетями):
	- Уровень OSI: Сетевой (L3) и выше.
	- Адресация: Использует IP-адреса (логические адреса узлов).
	- Задача: Находит оптимальный путь и передает пакеты между разными сетями (например, из локальной сети в интернет или между офисами)
	- Оборудование: Маршрутизатор (роутер) соединяет разные сети, выполняет трансляцию адресов (NAT) и фильтрует трафик через брандмауэр
*Как они работают вместе*
В реальных сетях коммутаторы объединяют компьютеры внутри кабинетов и этажей, а маршрутизатор служит главным шлюзом, 
выпускающим этот локальный трафик во внешнюю глобальную сеть.
****************************************************












****************************************************
## Information Security, Offensive security, Red teaming, Penetration testing
- Конфиденциальность
- Целостность
- Доступность
----------------------------------------------------
*Анализ, обратная инженерия (Analyze, Reverse Engineering)*
- Статический анализ (Static Analysis) — анализ исходного кода без выполнения программы
- Динамический анализ (Dynamic Analysis) — анализ программы во время её выполнения
- Декомпилятор (Decompiler) — преобразует исполняемый код в код, близкий к исходному
- Дизассемблер (Disassembler) — преобразует машинный код в инструкции языка ассемблера
----------------------------------------------------
В компьютерной безопасности *уязвимость* — это недостаток 
или слабость в проектировании, реализации или управлении системой.
Если ошибка может позволить злоумышленнику скомпрометировать 
конфиденциальность, целостность или доступность системных ресурсов, 
её можно считать уязвимостью.
Без уязвимости эксплойт, как правило, не может получить доступ. 
Также возможно, что вредоносное ПО может быть установлено напрямую, 
без эксплойта, посредством социальной инженерии или слабой физической защиты, 
например, через незапертую дверь или открытый порт.
- Error, Software bug
----------------------------------------------------
**Угрозы**
* Ошибка, программная ошибка (Error, Software bug)
- Shellcode — машинный код/скрипт на C/C++/Assembly
- Бэкдор (Backdoor) — скрытый механизм доступа к системе
- Удалённый троян (RAT, Remote Access Trojan) — вредоносная программа для удалённого доступа и управления
- Полезная нагрузка (Payload) — код или действие, выполняемое после успешной эксплуатации уязвимости
- Обратная оболочка (Reverse Shell) — удалённая командная оболочка, инициируемая скомпрометированной системой
- Вредоносное ПО (Malware), шпионское ПО (Spyware)
- Социальная инженерия (Social Engineering)
- Суперпользователь (Superuser), root, администратор (Administrator, Admin)
- Повышение привилегий (Privilege Escalation)
- Уязвимость (Vulnerability), CVE, эксплойт (Exploit) — недостатки или слабые места в программном обеспечении, системе или сети
- Атака подмены (Spoofing Attack)
- Атака перехвата сетевого трафика (Sniffing Attack)
- Кейлоггер / перехват нажатий клавиш (Keystroke Logger)
- Отказ в обслуживании (DoS, Denial-of-Service Attack)
- Межсайтовый скриптинг (XSS, Cross-Site Scripting)
- SQL-инъекция (SQL Injection)
- Сбор данных (Data Scraping)
- Подслушивание, перехват коммуникаций (Eavesdropping, Listening)
- Фишинг (Phishing), голосовой фишинг (Vishing)
- Атака человек посередине (MITM, Man-in-the-Middle)
- Архитектура C2 (Command & Control) — архитектура командования и управления
*Device*
- Обход EDR/AV (EDR/AV Bypasses) — C, ASM, обфускация, шифрование
- Выполнение программ (Program Execution), исполняемый файл (Executable File)
- Статический / динамический анализ (Static / Dynamic Analysis)
----------------------------------------------------
**Защита**
- Антивирусное программное обеспечение (Antivirus Software)
- Аутентификация (Authentication) — подтверждение личности пользователя
- Многофакторная аутентификация (Multi-Factor Authentication, MFA)
- Авторизация (Authorization) — определение прав и уровня доступа пользователя
- Обфускация (Software Obfuscation) — усложнение анализа и понимания исходного или исполняемого кода
- Шифрование (Encryption) — преобразование данных в защищённый вид
- Межсетевой экран / брандмауэр (Firewall) — контролирует сетевой трафик
- Система обнаружения вторжений (IDS, Intrusion Detection System) — обнаруживает подозрительную активность в системе
**Antivirus software**
1. Microsoft Defender (Basic security, Antivirus + Firewall)
2. Kaspersky Small Office Security (Усиленная защита)
----------------------------------------------------
*Analyze, Reverse Engineering*
- Ghidra, x64dbg and Interactive Disassembler (IDA Free) 
- Bytecode Viewer, Smali/Baksmali - analyze dalvik-byte code
- Radare2, GDB, QEMU, Strace, Ltrace, objdump, readelf
- JADX, Apktool - decompile Java code
----------------------------------------------------
2. Mobile Security tools
- AArch64, as ARM64, is a 64-bit version of the ARM architecture family
- APK and other executing files
- Executable and Linkable Format (ELF)
- Android and Java virtual machine (JVM)
- Java Development Kit (JDK), javac
- Toybox and Android Debug Bridge (adb)
- [termux, PRoot Distro](https://github.com/termux/proot-distro)
*Эмуляторы Android*
- Android Studio (AVD)
- Genymotion
- Wayland
- Waydroid 
*Build tools*	
- Gradle, Maven, TeamCity
----------------------------------------------------
* [kali tools](https://www.kali.org/tools/all-tools/)
- OWASP Project, Burp Suite, MobSF (Mobile Security Framework)
- Frida & Objection
- Magisk, KernelSU - Rooting device, Xposed Framework
- Google for Developers - Developer products
- Vulnerability scanners: Nessus, OWASP ZAP, Core Impact, Netsparker
----------------------------------------------------
- Exploitation: The Metasploit Project, Burp Suite, sqlmap, Veil Frameworks, SEToolkit
- Post-Exploitation: C2 frameworks - Cobalt Strike, Sliver, Havoc, Mythic, Empire, Armitage
----------------------------------------------------
**infosec resource**
- [Malware-Bible](https://github.com/Perkins-Fund/Malware-Bible)
----------------------------------------------------
- [OWASP - Github](https://github.com/OWASP/)
- [The OWASP attacks](https://owasp.org/www-community/attacks/)
- [OWASP Web Security Testing Guide](https://owasp.org/www-project-web-security-testing-guide/stable/)
- [OWASP Mobile Application Security](https://mas.owasp.org/)
----------------------------------------------------
- [Developer products](https://developers.google.com/products)
- [Android OS Documentation](https://source.android.com/docs)
- [Android Developer centers](https://developer.android.com/)
----------------------------------------------------
- [OffSec: Infosec & Cybersecurity Training](https://www.offsec.com/)
- [OffSec VulnHub](https://www.vulnhub.com/resources/)
- [Rapid7](https://www.rapid7.com/)
- [metasploit](https://www.metasploit.com/)
- [blog](https://www.kaspersky.com/blog/)
----------------------------------------------------
- [The 2026 Guide to Cybersecurity](https://www.ibm.com/think/cybersecurity#605511093)
* [Information security](https://en.wikipedia.org/wiki/Information_security)
* [Black Arch](https://blackarch.org/tools)
----------------------------------------------------
- [Kuba Gretzky](https://github.com/kgretzky) - reverse engineering and C/C++ dev.
- [breakdev of Kuba](https://breakdev.org/) - offensive security tools & research
* [Hacking Articles by Raj Chandel’s Blog](https://hackingarticles.in)
* [AppSec сообщество - ORDA](https://cyberorda.com/#)
- [4PDA:](https://4pda.to/)
*Practice Labs & CTFs*
- [exploit-db](https://www.exploit-db.com/)
- [MITRE ATT&CK](https://attack.mitre.org/)
- TryHackMe, Hack The Box, Metasploitable, Root-Me (root-me.org)
- Hacking: The Art of Exploitation, 2nd Edition, 2018. Erikson, J.
----------------------------------------------------
- [youtube/@kalisploit7368](https://www.youtube.com/@kalisploit7368)
- [White2Hack Storage](https://w2h.tech/)
----------------------------------------------------
*C2-Инфраструктура (Command and Control)*
C2-сервер — управляющий центр вредоносной сети. Через такой сервер хакер 
отправляет команды заражённым устройствам и получает данные с них.
После заражения устройство подключается к серверу управления, получает инструкции 
и выполняет задачи: сбор данных, распространение вредоносного ПО или участие в атаках.
Атакующие маскируют трафик под обычные веб-запросы, применяют HTTPS, шифрование, 
генерацию доменов и прокси-серверы.
Основные компоненты
- C2 Server / Team Server
- C2 Client / Operator Console
- Agent / Beacon / Implant
- [awesome-command-control](https://github.com/tcostam/awesome-command-control)
****************************************************





****************************************************
### Архитектура компьютера
- Архитектура фон Неймана
- Клод Шеннон
- Машина Тьюринга
- Логические элементы
- Логические схемы
- Арифметико-логическое устройство (АЛУ)
- Центральный процессор (CPU)
- Регистры
- Оперативная память (RAM)
- Внешняя память (HDD/SSD) 
- Системная плата (материнская плата)
- компоненты ввода (клавиатура, мышь) и вывода (монитор, принтер) данных
- Шины
- Машинные команды
- Представление данных внутри компьютера
----------------------------------------------------
- Computing Machine is a machine that processes data according 
to a set of instructions called a computer program.
- Electronic Computer - A set of hardware and software that computes, 
performs high-speed arithmetic calculations, logical operations, 
or stores, processes, and transmits information.
- Calculation is a mathematical transformation that allows one to transform
an incoming stream of information into an output stream with a different structure.
----------------------------------------------------
**Electronic components**
*Microprocessors(CPU)*
- Brands: Intel and AMD, ARM Cortex, Qualcomm, Broadcom Inc, Exynos, Kirin, MediaTek
*Microcontrollers*
- AVR microcontrollers, Microchip Technology, ARM, Atmel ATmega328, ARM Cortex
- Printed Circuit Board (PCB) - designed for the electrical and mechanical connection of various electronic components.
- Capacitor
- Transistor 
- Resistor
- Computing Platform: x86_64, ARM(Advanced RISC Machines), ARM64, aarch64, MIPS
- x86-64 (x64, x86_64, AMD64, Intel 64) – the standard 64-bit architecture for Intel and AMD processors.
- arm64 (AArch64) – a 64-bit architecture for energy-efficient ARM chips, Android smartphones
----------------------------------------------------
**Computer Architecture**
* High-level language: Python, C/CPP, Java, Shell, Assembler
* Assembly language level – translation (compiler)
* Operating system level – translation (assembler)
* Instruction set architecture level – translation (assembler)
* Microarchitecture level
* Digital logic level – machine hardware (logic gates)
- Python, C/CPP, Java, Shell, Assembler, HTML, JS → C/CPP → *Assembly/C* Language → Binary Code(0/1)
----------------------------------------------------
**Hardware Architecture**
- Storage: Memory (RAM/HDD) DDR4 и DDR5 RAM
- Processing: Microprocessors(CPU) Intel и AMD - Arithmetic logic unit (ALU)
- Intelligence: Focus on the important (Attention)
----------------------------------------------------
* Learning to view code "through the eyes of the processor and memory" —
is a step toward a deep understanding of how C, operating systems, and computers in general work.
----------------------------------------------------
* UEFI is built-in software that manages the keyboard, monitor, disk, and other hardware devices, 
and provides a software interface that helps the operating system control the hardware.
----------------------------------------------------
* BIOS/UEFI → shimx64.efi(SecureBoot) → GRUB(grubx64.efi) → kernel(vmlinuz) + initramfs → systemd → user session
----------------------------------------------------
**A transistor** is a current switch: on = 1, off = 0.
In CPUs and RAM, transistors create logic gates (AND, OR, NOT),
store data, and control signal flows.
Billions of transistors allow vast amounts of information to be processed
simultaneously, increasing performance and the complexity of operations.
----------------------------------------------------
**Computations in Python from the Inside**
- print("Hello World")
*Python Object* - "Hello World": Type: str, Length: 11
*UTF-8 Encoding* - 48 65 6C 6C 6F 20 57 
*System Call* - write(1, "Hello World\n")
*Operating System*
*RAM Memory address*
0x1000 01001000 (H)
0x1001 01100101 (E)
0x1002 01101100 (L)
0x1003 01101100 (L)
----------------------------------------------------
Anything can be built from the simple (0 and 1).
Everything in a computer is represented as 0s and 1s.
0 means no signal, 1 means a signal is present.
**Bit and Byte**
- Bit — the smallest unit of information (0 or 1)
- Byte — 8 bits
Example:
- 01000001 = the letter ASCII
- Everything—text, video, and audio—is a sequence of bytes.
****************************************************




## Режимы Android

- Пользовательские — Normal Mode, Safe Mode, SOS Mode.
- Сервисные — Recovery, Fastboot, Bootloader, Download, Rescue.
- Инженерные — Factory Mode, Engineer Mode, Meta Mode.
- Низкоуровневые аварийные — EDL Mode и другие специализированные режимы восстановления.


### Электричество

Электричество (лат. electricus) — совокупность явлений, обусловленных 
существованием, взаимодействием и движением электрических зарядов. 

- Ток — это движение электронов через проводник. Представь это как поток 
воды по трубе.
- Сила Тока
- Проводник тока
- Напряжение — это сила, которая "толкает" электроны, как давление воды
- Сопротивление  — это то, что замедляет движение тока, как узкая труба 
замедляет поток воды

*Светодиод*
Для практики можно использовать простые схемы и компоненты, например, 
батарейки, резисторы, светодиоды. Отличным началом будет работа с 
Arduino — это поможет тебе наглядно увидеть, как электричество работает 
в реальных проектах.

Базовые законы электричества — закон Ома (напряжение = ток × сопротивление), 
что такое электрический ток и напряжение. Это даст основу, чтобы понять, 
как работают схемы.

*Закон Ома*
Закон Ома описывает линейную зависимость между силой тока на участке 
цепи и электрическим напряжением на этом участке.






## Шпаргалка IT-специалиста по электрике

**Базовые понятия**

- AC (переменный ток) — ток из розетки 220 В / 50 Гц.  
- DC (постоянный ток) — используется внутри компьютеров, адаптеров 
и аккумуляторов (5 В, 12 В, 19 В и т. д.).  
- Напряжение (V) — сила "давления" электричества.  
- Ток (A) — количество электричества, которое течёт по проводнику.  
- Мощность (Вт) = Вольты × Амперы (P = U × I).

**Розетка и питание**

- Фаза (L) — активный провод, под напряжением (опасен).  
- Ноль (N) — обратный провод.  
- Земля (PE) — защитный провод (безопасность, утечка тока).  
- Никогда не трогай фазу, даже если прибор выключен.  
- ИБП (UPS) — защита от отключений и скачков напряжения.  

**Оборудование**

- Блок питания (PSU) — преобразует 220 В AC → 12 В / 5 В / 3.3 В DC.  
- Адаптеры ноутбуков — делают то же самое (например, 19 В 3.42 А).  
- Серверы, роутеры, PoE-устройства работают от DC 12 В / 48 В.  
- Powerbank / аккумуляторы — всегда DC (обычно 3.7 В → 5 В).  

**Инструменты и безопасность**

- Мультиметр — измеряет:
  - напряжение (V),
  - ток (A),
  - сопротивление (Ω).  
- Не измеряй сопротивление под напряжением — можно сжечь прибор.  
- Работай одной рукой — не касайся одновременно двух металлических частей.  
- Используй стабилизаторы и фильтры, если напряжение скачет.

**Минимум, который нужно понимать**

| Ситуация | Что знать |
|-----------|------------|
| Зарядка не работает | Проверить адаптер AC → DC |
| Компьютер не включается | Проверить блок питания (12 В / 5 В) |
| Перегорела розетка | Проверить фазу и ноль |
| Устройства вырубаются | Проверить ИБП или стабилизатор |
| Arduino / PoE / серверы | Разобраться в уровнях DC (5 В / 12 В / 48 В) |

**Формулы для памяти**

- P = U × I → мощность (Вт)  
- U = P / I → напряжение (В)  
- I = P / U → ток (А)

**Переменный ток (AC) (Напряжение 220В, 50ГЦ)**
- Переменный ток (AC) — это когда направление и величина тока постоянно меняются (Например:  ток в разетке) 

**Постоянный ток (DC)**
- -+ Постоянный ток (DC) — это ток, который течёт только в одном направлении (например, в батарейках, аккумуляторах, powerbank’ах).

Между ними стоит блок питания (Power Supply), который делает AC → DC.


**Итог**

* Для программиста — знать разницу между AC и DC, понимать роль блока питания.  
* Для инженера — понимать, как работает фаза, земля, ИБП и выпрямители.  
* Главное — безопасность: всегда проверяй напряжение перед работой.

**Брэнды мультиметр**

- UNI‑T 
- Fluke
- Keysight




### Удлинитель для бытовой техники - 3500W

The Best Удлинитель (не сетевой фильтр), с сечением 1.5–2.5 мм², 
с заземлением и выдержкой нагрузки не менее 3500 Вт. 
Для бытовой техники > кондиционера, холодильника:
Мощность: минимум 3500 Вт
Ток: до 16 А
Сечение провода: 1.5 мм² или 2.5 мм²
Заземление: обязательно (розетки ЕвроСтандарт типа F)
Надёжным брендом: Defender, Lezard, Makel, IEK
(Надёжные, проверенные для бытовой нагрузки)
** Избегай:
Дешёвых удлинителей с сечением 0.75 мм²
Сетевых фильтров для компьютеров (ограничены 10 А)
Моделей без заземления
Китайских "noname" без маркировки и сертификатов









### Microphones

Классификация микрофонов

1. Динамический микрофон 
В отличие от конденсаторных, динамические микрофоны 
не требуют фантомного питания. 
2. Конденсаторный микрофон - обладают весьма равномерной 
амплитудно-частотной характеристикой, имеют высокую 
чувствительность и низкие искажения, благодаря чему 
широко используются в студиях звукозаписи, 
на радио и телевидении. 

Из-за большого динамического диапазона, конденсаторные 
микрофоны воспринимают посторонние звуки и шумы, 
а значит запись с них целесообразна только в специально 
подготовленном помещении. / необходимость во внешнем питании;

Характеристики микрофонов
- чувствительность;
- частотная характеристика чувствительности;
- акустическая характеристика микрофона;
- характеристика направленности;
- уровень собственных шумов микрофона.

3. разъёмы: (AUX, TRS/TS)/USB/XLR

4. brands
- Shure SM58 и SM7B
- Sennheiser E835 и MD421-II
- Electro-Voice - RE20 и RE320
- Audio-Technica ATM510, BP40.
- Beyerdynamic, AKG,

****************************************************

## Обработка звуковой инфо = микшер

- микшер = ввод/вывод 
- input/output/processing
- ввод/вывод/обработка
- микрофон/колонка/эквалайзер
---
Регулятор громкости/Volume/Fader
Left/Right

**Mixer**
- Behringer | Продукт | Mixer with XENYX1222FX
- Allen&Heath ZED SIXTY-14FX
---
- Wireless Microphone Daus M-500

**Apps for mixer**
- Ardour
- Audacity
- Daw
- Mixxx


## Video HDMI/SDI
- SDI-HDMI Converter






### IT Knowledge & Education 

- [Курсы программирования](https://purpleschool.ru/)
- [PurpleSchool | Anton Larichev](https://www.youtube.com/@PurpleSchool)
----------------------------------------------------
- [Linux Command Library](https://linuxcommandlibrary.com/) - Android app
----------------------------------------------------
- computing.book
- [foxford/info](https://foxford.ru/wiki/informatika)
----------------------------------------------------
- [Rebrain — онлайн-практикумы по инфраструктуре](www.youtube.com/@rebrainme)
- [Диджитализируй!](https://youtube.com/@t0digital) 
- [site/to.digital](https://to.digital/) 
- [GNU Linux Pro](https://www.youtube.com/@GNULinuxPro)
- [Alek OS](https://youtube.com/@AlekOS) 
- [Bogdan Stashchuk](www.youtube.com/@Bogdan_Stashchuk)
- [Тимофей Хирьянов](https://www.youtube.com/@tkhirianov) 
- [artsorax](https://www.youtube.com/@artsorax)
- [Lex Fridman](https://www.youtube.com/lexfridman) 
----------------------------------------------------
- [Hetman Software](https://www.youtube.com/@Hetman-Software/playlists) 
- [remontka.pro](https://remontka.pro/)
----------------------------------------------------
- [Wikipedia:Contents/Portals](https://en.wikipedia.org/wiki/Wikipedia:Contents/Portals)
- [wiki/Category:All_portals](https://en.wikipedia.org/wiki/Category:All_portals)
- [Wikipedia:Contents/Categories](https://en.wikipedia.org/wiki/Wikipedia:Contents/Categories)
- [Wikipedia:Featured_articles](https://en.wikipedia.org/wiki/Wikipedia:Featured_articles)
----------------------------------------------------



## Programming Language Resource
**JavaScript**
- [mdn.mozilla](https://developer.mozilla.org/ru/) 
- [w3schools](https://www.w3schools.com/)
- [html5book](https://html5book.ru/)
- [codepen.io](https://codepen.io/trending)
----------------------------------------------------
- [Award Leaders](https://www.awwwards.com/winner-list/)
- [Codrops](https://tympanus.net/codrops/hub/)
- [Behance](https://www.behance.net/)
- [envato - themeforest](https://themeforest.net/)
- [htmlrev](https://htmlrev.com/)
- [themewagon](https://themewagon.com/)
- [Agence web a Lyon - Mcube](https://www.mcube.fr)
- [Full-Stack-Разработчик Казахстан](https://aidardev.kz/ru)
**Java/kotlin**
- [awesome-java](https://github.com/akullpp/awesome-java.git)
- [Java Compiler (javac)](https://dev.java/)
- [javase](https://docs.oracle.com/en/java/javase/)
- [openJDK-Github repo](https://github.com/openjdk)
- [jdk.java.net](https://jdk.java.net/)
- [introcs.cs.princeton.edu/java/11cheatsheet](https://introcs.cs.princeton.edu/java/11cheatsheet/)
- [dev.java/learn](https://dev.java/learn/getting-started/)
----------------------------------------------------
**Python**
- [Python documentation](https://docs.python.org/3/)
- [ronreiter](https://github.com/ronreiter)
- [Interactive Tutorials of more language](http://www.learnpython.org/)
- [awesome-python](https://github.com/vinta/awesome-python.git)




### Information Systems reSearcher toolkit 

Xiaomi, Samsung, D-link, TpLink, Mikrotik, Asus, HP
* notebook, miniPC, tablet, smartphone, keyboard
* Docking station Xiaomi XMTIO01YM
* RouterBoard mikrotik - RouterOS
* коммутатор/switch TP-Link/D-Link/hikvision/HUAWEI/Ubiquiti
* microprocessors and microcontrollers for creating digital devices
* programmable microcomputers, Raspberry Pi printed circuit board, Arduino
* Electronic book (устройство, e-book reader) OnyxBoox
----------------------------------------------------
* Multimeter 
* Electric soldering iron, Solder, Pine rosin (flux)
* Silicone soldering mat
* LTE/5G/GSM  mikrotik Chateau 5G ax
* USB ethernet/Wireless card supported 5GHz for kali
* video recorder, IP camera DVR (или IP camera ) hikvision/hiwatch DS-N332 + switch
* RAM DDR1-5 1300-1600Mhz 
* connectors USB/SATA/USB Type-C
* connectors HDMI > VGA < HDMI
* connectors - Docking station USB/HDMI/RG45/Type-C
* mini Screwdriver
* Patch cable (Connector RG45, Optic cable)
* Crimp (joining)
* Cable tester RG45
* POST CARD
* Bluetoth/USB keyboard
* USB/Type-C OTG for android
* Cordless rotary hammers, cordless screwdrivers
* Construction ladders and stepladders
* TV Samsung/Xiaomi 2/4K 109cm
* monitor msi, samsung 2/4K HD,FULLHD-2000
- Uninterruptible power supply (UPS) Voltage regulator
----------------------------------------------------
*Ventoy bootable USB/SSD*
- Windows 10/11
- Ubuntu OS
- WinPE SergeyStrelec and Hiren
- MS Office offline of MASSGRAVE
--------------------------------
- MediaCreationTool 












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






***Общий доступ к файлам по сети (Windows, Unix)***

- [SMB](https://support.microsoft.com/) — сетевая файловая система для Windows-сетей и сетевых дисков.  
- [Samba](https://www.samba.org/) file and print services to all manner of SMB/CIFS clients  
- [FTP / SFTP / WebDAV]() — безопасная передача файлов через интернет.   
- [tp-link print-server](https://www.tp-link.com/kz/home-networking/print-server/)



**Общий доступ к принтеру**

1. Общий доступ через Windows (шаринг принтера)
- Подключение принтера к ПК (USB/локально).
- Установка драйверов.
- **Панель управления → Устройства и принтеры → Свойства принтера → Доступ → Открыть общий доступ**.
- Указываем имя принтера.
1.1 Подключение с других ПК:
* Win+R → \\Имя_компьютера или \\IP-адрес.
* Выбрать принтер, установить драйвер.
Минус: «хостовый» компьютер должен быть включён.

2. Сетевой принтер с LAN/Wi-Fi
* Принтер подключается к роутеру напрямую (Ethernet/Wi-Fi).
* На ПК → **Добавить принтер → по TCP/IP-адресу**.
* Ввод IP и установка драйвера.
Плюс: работает независимо от состояния «хостового» ПК.

3. Подключение через роутер или отдельный принт-сервер
* Роутер с USB-портом для принтера (или отдельный print-server).
* Настройка через веб-интерфейс роутера/сервера.
* Используются протоколы LPR, IPP, SMB.
Подходит для офисных и домашних сетей, где нужно «расшарить» простой USB-принтер.

4. SMB-шаринг (расширенный вариант)
* Включение компонента **Служба печати и документообразования**.
* Настройка прав доступа.
* Подключение: \\IP_компьютера\Имя_принтера.
Используется в корпоративных сетях с контролем доступа.

Для дома и небольшого офиса оптимальны варианты:
* **№1** — шаринг через Windows,
* **№2** — сетевой принтер по LAN/Wi-Fi.






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




## Диагностика Компьютера  x86-64, не включается

- Возможные причины неисправности
- Методы Диагностики
- Шаги для исправления неисправности
----------------------------------------------------
1. Розетка + кабель + переключатель БП
2. Замкнуть контакты Power SW отвёрткой
3. Минимальная сборка - только плата, cpu, ram
4. Замена БП
5. Сброс CMOS батерея
6. Другая ОЗУ / слот
7. Проверка МП на повреждения
- Основные причины: БП, МП



### video survellance

video survellance (IPcam, IPtel) hikvision, HiWatch DS-N332/4 + switch
Стандарты YouTube:
- 4320p (8K): 7680 x 4320
- 2160p (4K): 3840 x 2160
- 1440p (2K): 2560 x 1440
- 1080p (Full HD): 1920 x 1080
- 720p (HD): 1280 x 720
- 480p (SD): 854 x 480
- 360p (SD): 640 x 360
- 240p (SD): 426 x 240
- 144p (SD): 256 × 144




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


