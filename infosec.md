# Awesome Information Security

## Contents

- Триада ИБ
- Угрозы
- Защита
- Analyze, Reverse Engineering
- Уязвимость


## Защита

- Антивирусное программное обеспечение (Antivirus Software)
- Межсетевой экран / брандмауэр (Firewall) — контролирует сетевой трафик
- Система обнаружения вторжений (IDS, Intrusion Detection System)
- Аутентификация (Authentication) — подтверждение личности пользователя
- Многофакторная аутентификация (Multi-Factor Authentication, MFA)
- Авторизация (Authorization) — определение прав и уровня доступа пользователя
- Обфускация (Software Obfuscation) — усложнение анализа и понимания исходного или исполняемого кода
- Шифрование (Encryption) — преобразование данных в защищённый вид
- Контроль доступа


## Триада ИБ

- Конфиденциальность
- Целостность
- Доступность


## Угрозы

* Ошибка, программная ошибка (Error, Software bug)
- Shellcode — машинный код/скрипт на C/C++/Assembly
- Бэкдор (Backdoor) 
- Удалённый троян (RAT, Remote Access Trojan) 
- Полезная нагрузка (Payload) 
- Обратная оболочка (Reverse Shell) 
- Вредоносное ПО (Malware), шпионское ПО (Spyware)
- Социальная инженерия (Social Engineering)
- Суперпользователь (Superuser), root, администратор (Administrator, Admin)
- Повышение привилегий (Privilege Escalation)
- Уязвимость (Vulnerability), CVE, эксплойт (Exploit) 
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
- Архитектура C2 (Command & Control) 
- Обход EDR/AV (EDR/AV Bypasses) — C, ASM, обфускация, шифрование
- Выполнение программ (Program Execution), исполняемый файл (Executable File)
- Статический / динамический анализ (Static / Dynamic Analysis)





## Antivirus software

1. Microsoft Defender (Basic security, Antivirus + Firewall)
2. Kaspersky Small Office Security (Усиленная защита)


## Analyze, Reverse Engineering

*Анализ, обратная инженерия (Analyze, Reverse Engineering)*
- Статический анализ (Static Analysis) — анализ исходного кода без выполнения программы
- Динамический анализ (Dynamic Analysis) — анализ программы во время её выполнения
- Декомпилятор (Decompiler) — преобразует исполняемый код в код, близкий к исходному
- Дизассемблер (Disassembler) — преобразует машинный код в инструкции языка ассемблера
----------------------------------------------------
- Ghidra, x64dbg and Interactive Disassembler (IDA Free) 
- Bytecode Viewer, Smali/Baksmali - analyze dalvik-byte code
- Radare2, GDB, QEMU, Strace, Ltrace, objdump, readelf
- JADX, Apktool - decompile Java code


## 2. Mobile Security tools

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


## C2-Инфраструктура (Command and Control)

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






## Уязвимость

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


## Сфера ИБ

Information Security, Offensive security, Red teaming, Penetration testing


## infosec resource

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



