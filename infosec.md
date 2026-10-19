# Awesome Information Security

## Contents

- Конфиденциальная информация
- Триада ИБ
- Угрозы
- Защита
- Анализ систем, Reverse Engineering
- Уязвимость
- Тестирование безопасности:
    - мобильных приложений
    - веб-безопасности
- The OWASP Foundation


## 4. Конфиденциальная информация

1. Персональные данные (ПДн) общего характера
* Паспортные данные (серия, номер, дата выдачи, кем выдан).
* Индивидуальный идентификационный номер (ИИН).
* Фамилия, Имя, Отчество (ФИО).
* Контактные данные (номера телефонов, адреса электронной почты).
* Сведения о месте жительства и регистрации, адрес фактического проживания.
* Сведения о трудовой деятельности (место работы, должность, рабочий адрес).
* Данные водительского удостоверения.
* Сведения о социальных связях (списки близких родственников, контактных лиц).
* Личные неструктурированные записи (записные книжки, памятки, рабочие заметки).
* Ключи электронной цифровой подписи (ЭЦП) и соответствующие им сертификаты.

1. Биометрические персональные данные
* Цифровые модели и фотоизображения лица.
* Фонограммы голоса (голосовые слепки).
* Данные ДНК-анализа.
* Дактилоскопические данные (отпечатки пальцев).

1. Специальные категории персональных данных (Медицинские данные)
* Электронные и бумажные медицинские карты, истории болезней.
* Паспорта здоровья.
* Сведения о состоянии здоровья, установленных диагнозах и назначенных медицинских препаратах.

1. Финансовая и банковская информация
* Номера банковских счетов, транзакционные и платежные реквизиты.
* Данные платежных карт (номера карт, срок действия, CVV/CVC-коды).
* Сведения об обязательствах (кредитная история, договоры займов и кредитов).

1. Корпоративные данные и коммерческая тайна
* Учредительные, финансово-хозяйственные и внутренние нормативные документы компании.
* Документация по IT-инфраструктуре (схемы сети, конфигурации оборудования, учетные данные администраторов).
* Персональные данные должностных лиц, сотрудников, клиентов и контрагентов.

1. Технические средства сбора данных (Датчики и периферийные устройства)
* Встроенные и периферийные микрофоны (аудиопоток).
* Видеокамеры и оптические датчики (видеопоток, фотофиксация).
* Модули геопозиционирования (данные GPS, координаты базовых станций).

1. Объекты защиты (Хранилища, форматы данных и каналы передачи)
* Файловые объекты любых расширений (.txt, .jpg, .png, .doc/.docx, .pdf, .md).
* Облачные хранилища (Google Диск, Облако Mail.ru, iCloud и др.).
* Корпоративные и личные учетные записи электронных почтовых служб.
* Аккаунты и история переписки в мессенджерах (Telegram, WhatsApp и др.).
* Журналы системных событий (логи), технические файлы сессий (cookies), метаданные файлов и сетевых пакетов.
* Корпоративные и личные профили в социальных сетях (Instagram, TikTok, YouTube и др.).


## Триада ИБ

- Конфиденциальность
- Целостность
- Доступность


## Угрозы

* Ошибка, программная ошибка (Error, Software bug)
- Shellcode — машинный код на C/C++/Assembly
- Бэкдор (Backdoor) 
- Удалённый троян (RAT, Remote Access Trojan) 
- Полезная нагрузка (Payload) 
- Обратная оболочка (Reverse Shell) 
- Вредоносное ПО (Malware), шпионское ПО (Spyware)
- Социальная инженерия (Social Engineering)
- Суперпользователь, администратор (Superuser, root, Administrator)
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

* *C2-Инфраструктура (Command and Control)*
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
----------------------------------------------------
- декомпиляция, внедрение кода и обратная сборка apk файлов



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
- Электронная цифровая подпись (ЭЦП)
- Родительский контроль (Parental controls)
- Information Security, Offensive security, Red teaming, Penetration testing

* *Antivirus software*
1. Microsoft Defender (Basic security, Antivirus + Firewall)
2. Kaspersky Small Office Security (Усиленная защита)

* *Родительский контроль (Parental controls)*
- Google Family Link 
- Apple (Экранное время, раздел Семья)
- AirDroid


## Уязвимость

*Уязвимость* — это недостаток или слабость в проектировании, 
реализации или управлении системой.
Если ошибка может позволить злоумышленнику скомпрометировать 
конфиденциальность, целостность или доступность системных ресурсов, 
её можно считать уязвимостью.
Без уязвимости эксплойт, как правило, не может получить доступ. 
Также возможно, что вредоносное ПО может быть установлено напрямую, 
без эксплойта, посредством социальной инженерии или слабой физической защиты, 
например, через незапертую дверь или открытый порт.
- Error, Software bug


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



## Тестирование безопасности мобильных приложений

- *OWASP Mobile Application Security Testing Guide (MASTG)*
- MITRE ATT&CK
- AArch64, as ARM64, is a 64-bit version of the ARM architecture family
- APK and other executing files
- Executable and Linkable Format (ELF)
- Android and Java virtual machine (JVM)
- Java Development Kit (JDK), javac
- Toybox and Android Debug Bridge (adb)
- [termux, PRoot Distro](https://github.com/termux/proot-distro)
* *Эмуляторы Android*
- Android Studio (AVD)
- Genymotion
- Wayland
- Waydroid 
* *Build tools*	
- Gradle, Maven, TeamCity
----------------------------------------------------
* [kali tools](https://www.kali.org/tools/all-tools/)
- OWASP Project, Burp Suite, MobSF (Mobile Security Framework)
- Frida & Objection
- Magisk, KernelSU - Rooting device, Xposed Framework
- Google for Developers - Developer products
----------------------------------------------------
- Exploitation: The Metasploit Project, Burp Suite, sqlmap, Veil Frameworks, SEToolkit
- Post-Exploitation: C2 frameworks - Cobalt Strike, Sliver, Havoc, Mythic, Empire, Armitage
----------------------------------------------------



## Тестирование веб-безопасности

- *OWASP Web Security Testing Guide*
- MITRE ATT&CK



## infosec resource

- [The OWASP Foundation](https://github.com/OWASP)
- [The OWASP attacks](https://owasp.org/www-community/attacks/)
- [MITRE ATT&CK](https://attack.mitre.org/)
----------------------------------------------------
- Google and Firefox Developer Tools
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
- [Malware-Bible](https://github.com/Perkins-Fund/Malware-Bible)
- [Kuba Gretzky](https://github.com/kgretzky) - reverse engineering and C/C++ dev.
- [breakdev of Kuba](https://breakdev.org/) - offensive security tools & research
* [Hacking Articles by Raj Chandel’s Blog](https://hackingarticles.in)
* [AppSec сообщество - ORDA](https://cyberorda.com/#)
- [4PDA:](https://4pda.to/)
*Practice Labs & CTFs*
- [exploit-db](https://www.exploit-db.com/)
- TryHackMe, Hack The Box, Metasploitable, Root-Me (root-me.org)




