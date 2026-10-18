# Awesome Information System Engineer toolkit

****************************************************
## The Research interests of Computing Information Systems
## Computing Information Systems Engineering toolkit
1. AI & Automation, AI Coding Agents with ->
- Git/GitHub, Anthropic, Google, OpenAI, x.ai, OpenRouter, Huggingface
2. Algorithms & Programming Science
- Language: BASH/CPP/Kotlin/Python/Swift/Go/PostgreSQL/SQLite 
----------------------------------------------------
**IT Service**
- AI & Automation
- Web & Mobile Development
- IT and Programming Courses, Mentoring
----------------------------------------------------
- Configure & Development of cell phones, tablets, laptops
----------------------------------------------------
- Terminal, VSCode, Android Studio, XCode, Antigravity, Neovim, Nano, Markdown
- Docker, Docker Compose
----------------------------------------------------
**System architecture, Network and Information Security**
- System: GNU/Linux x86-64 and Android/IOS arm64
- Netowork: model TCP/IP, CLI netTools, Remote administration tools, Virtual private network (VPN)
- Infosec: Offensive Security, Red Teaming, Reverse Engineering
- GNU toolchain, *OWASP Project, MITRE ATT&CK, C2(Command and Control)*,  Post-Exploitation
- Parental controls: Google Family Link, Apple (Экранное время, раздел Семья), AirDroid
----------------------------------------------------
**Cloud computing**
- Google Workspace: cloud.google.com, Google Docs Editors, Google Drive
- DigitalOcean, Vercel, Netlify, Cloudflare, ngrok
----------------------------------------------------
**Graphic Apps**
- Office - Google Docs Editors, LibreOffice, OpenOffice, MS Office
- Graph - GIMP, Inkscape, Canva, Pinta, Adobe Photoshop, Acrobat, Scan, CorelDraw, Picsart, Figma
- Videos - Adobe Premiere + Firefly, OpenShot, Shotcut, CapCut, OBS Studio, VLC, K-Lite Codec Pack
- PDF - Adobe Acrobat Pro, Foxit Phantom PDF, LibreOffice Draw, Adobe Scan, PDF-XChange Editor
-------------------------------------------------------
**AI Multimodal Processing**
- Google AI Studio
- VideoGen: Google Vids, Veo3, Omni, OpenAI API, Runway, Pika Labs, Higgsfield.ai
- ImageGen: Nano Banana, Kling, Flux, Diffusers, Stable Diffusion, Midjourney
- AudioGen: ElevenLabs, Suno 
----------------------------------------------------
## Unix.projects
- Digital agency - Web and Mobile app (client-server infrastructure)
- Unix Interactive lessons of IT and Programming webApp(unix.sys.md directories to react.js)
- C2-architecture (Command & Control) tools for Ubuntu/Android/IOS
- AI Agent for Automation Multimodal, Office Data processing
- The Game and Animation, Google Dino
****************************************************





## Режимы Android

- Пользовательские — Normal Mode, Safe Mode, SOS Mode.
- Сервисные — Recovery, Fastboot, Bootloader, Download, Rescue.
- Инженерные — Factory Mode, Engineer Mode, Meta Mode.
- Низкоуровневые аварийные — EDL Mode и другие специализированные режимы восстановления.







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
- Mi Flash Tool
- SP Flash Tool
- QFIL
- 3uTools
- QPST
- Chimera Tool (платный)
- SamFW Tool
- [UnlockTool](https://unlocktool.net/)



## Общий доступ к файлам по сети (Windows, Unix)

- [SMB](https://support.microsoft.com/) — сетевая файловая система для Windows-сетей и сетевых дисков.  
- [Samba](https://www.samba.org/) file and print services to all manner of SMB/CIFS clients  
- [FTP / SFTP / WebDAV]() — безопасная передача файлов через интернет.   
- [tp-link print-server](https://www.tp-link.com/kz/home-networking/print-server/)





## Общий доступ к принтеру

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







## Microphones

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



## Удлинитель для бытовой техники - 3500W

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




- [Hetman Software](https://www.youtube.com/@Hetman-Software/playlists) 
- [remontka.pro](https://remontka.pro/)

