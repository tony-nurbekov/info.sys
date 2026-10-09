# Awesome Computer Networking

## Contents

1. Архитектура и базовые понятия сетей
- Локальная сеть (Local Area Network - LAN)
- Глобальная сеть (Wide Area Network - WAN)
- Клиент и сервер (Client / Server)
- Сетевой протокол (Network Protocol)
- Сетевая модель OSI, модель TCP/IP
- Инкапсуляция/ДеИнкапсуляция
- Маршрутизация и коммутация (Routing and Switching)
- Network address translation (NAT)
- Топология сетеи (Network Topology) - Шина, Звезда, Кольцо
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
5. Активное сетевое оборудование
6. Пассивное сетевое оборудование



## model OSI and model TCP/IP

1. Application layer: HTTPS, FTP, DNS, DHCP, Telnet, SSH, Secure Shell, SMTP, SMB
2. Presentation layer: SSL, TLS, MIME, JPEG, GIF
3. Session layer: Sockets, PPTP, L2TP, NetBIOS, RPC
4. Transport layer: TCP and UDP
5. Network layer (Router): IP (IPv4, IPv6), ICMP, IPsec
6. Data link layer (Switch): ARP, MAC, Ethernet
7. Physical layer (Hubs/0011001): Twisted pair, Optical fiber, Bluetooth, Wi-Fi, 



## Активное сетевое оборудование

* Сетевой контроллер (Net Controller / NIC)
* Маршрутизатор (Router) 
* Коммутатор (Switch) и Хаб (Hub)
  * CLI, SNMP agent and web interface
* Беспроводная точка доступа (Wireless Access Point — AP)
* Повторитель (Repeater)
* Оптический медиаконвертер (Fiber Media-Converter)
* Brand network hardware: TP-Link, D-Link, hikvision, HUAWEI


## Пассивное сетевое оборудование

* Кабели связи (Витая пара), Cable UTP, FTP Сat5e
* Модульный разъем (Modular Connector)
* Оптическое волокно и SFP-модули (Optical fiber & SFP)
* IP-телефония (VoIP)
* Мобильные сети (Mobile Networking) GSM, UMTS, LTE
----------------------------------------------------
- Network address translation (NAT) - Transformation 
Local area network (LAN) => в Wide area network (WAN).
Router (NAT): 192.168.0.2:5432(LAN) → 93.184.216.34:6001(WAN)


## Local Private addresses

1. Class A: 10.0.0.0 – 10.255.255.255
2. Class B: 172.16.0.0 – 172.31.255.255
3. Class C: 192.168.0.0 – 192.168.255.255
- 192.168.0.0/24 or 192.168.0.0/16


## Network CLI Tools

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


## Маршрутизация и коммутация

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



----------------------------------------------------
- Virtual Private Server (VPS)
- Google Drive, Dropbox, Yandex Disk
- cloud.google.com - Cloud Computing Services
----------------------------------------------------





- [Linux Network Administrators Guide](https://tldp.org/LDP/nag2/index.html) - 
- [Introduction to TCP/IP Networks](https://mirrors.edge.kernel.org/pub/linux/docs/man-pages/book/)
- [The Apache HTTP Server](https://httpd.apache.org/docs-project/) 


