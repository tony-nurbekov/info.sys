# Awesome Computer Architecture 

## Contents

- Архитектура фон Неймана
- Клод Шеннон
- Машина Тьюринга
- Логические элементы
- Логические схемы
- Арифметико-логическое устройство (АЛУ)
- Центральный процессор (CPU)
- Регистры
- Стек (Stack)
- Куча (Heap)
- Указатели
- Ссылки
- Оперативная память (RAM)
- Внешняя память (HDD/SSD) 
- Системная плата (материнская плата)
- компоненты ввода (клавиатура, мышь) и вывода (монитор, принтер) данных
- Шины
- Машинные команды
- Представление данных внутри компьютера





----------------------------------------------------
*Системные уровни (от софта к железу)*
- Операционные системы: Среда выполнения (Unix, GNU/Linux, Ubuntu, Android).
- Языки низкого уровня: Ассемблер (x86-64, arm64), который переводит код человека в бинарный код (001100).
- Аппаратный уровень: Процессор (CPU) и оперативная память (RAM), состоящие из миллиардов транзисторов — 
полупроводников, которые управляют электрическими сигналами.



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


- [Hetman Software](https://www.youtube.com/@Hetman-Software/playlists) 
- [remontka.pro](https://remontka.pro/)









## video survellance

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




