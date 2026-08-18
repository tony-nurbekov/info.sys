# Unix.projects

1. Digital agency
    - Web and Mobile app
2. Client-Server Remote administration software
    - Android/IOS Remote Agent
3. AI Image/Doc Editor


----------------------------------------------------
# My Project

- Краткое описание
## Возможности
## Технологии
## Требования
## Использование
----------------------------------------------------


## Digital Agency

Современный Веб приложение для Цифровое агентство, специализирующееся на создании веб-сайтов, 
мобильных приложений и решениях на основе искусственного интеллекта

## Tech Stack

- **Backend:** Python, FastAPI
- **Frontend:** React, TypeScript
- **Database:** PostgreSQL
- **Cache:** Redis
- **AI:** OpenAI API
- **Containerization:** Docker
- **CI/CD:** GitHub Actions


----------------------------------------------------



## Android Remote Agent (ARA)

Клиент-серверное приложение удаленного управления Android-устройствами без root.
Система должна обеспечивать постоянное защищенное соединение между Android-устройством и сервером под Ubuntu 24.04 LTS.
Сервер отправляет команды, агент (Android Demon/Фоновая Служба) выполняет действия и возвращает результат.
Постоянное WebSocket-соединение.

**Архитектура**

*Сервер*
ОС: Ubuntu 24.04 LTS
Язык: Python 3.12+
Технологии:
asyncio
FastAPI
WebSocket
PostgreSQL (или SQLite на этапе разработки)

*Клиент*
ОС: Android 16+
Язык: Kotlin

*Принцип работы*
После запуска телефона агент автоматически запускается и при разрыве сети агент автоматически переподключается.
Агент устанавливает защищенное WebSocket-соединение с сервером.
Соединение поддерживается постоянно.

*Функции*
- System Information
- Network Information

*Парадигма программирования*
- Модульное программирование

*Android Debug Bridge (adb) client-server program*
----------------------------------------------------

## AI Image/Doc Editor







