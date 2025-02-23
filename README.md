## 🇬🇧 EN
# HatOS  
HatOS is an open-source operating system for virtual machines, written entirely in C# using third-party CosmosOS packages.  

## Contents  
- [Technologies](#technologies)  
- [Getting Started](#getting-started)  
- [Testing](#testing)  
- [Contributing](#contributing)  
- [To do](#to-do)  
- [Contacts](#contacts)  

## Technologies  
- [CosmosOS](https://www.gocosmos.org/)  
- [Visual Studio](https://visualstudio.microsoft.com/)  

## Usage  
Installing the project does not take much time. You need to install Visual Studio and C# support packages, as well as the Cosmos User Kit. After that, restart your computer and open the `.sln` file in `src`. To run, VMware Workstation/Player is required. This can be changed in the project settings.  

## Development  
The development of the project did not take me much time, but the project will be updated, and gradually, my workload will increase. Support for a graphical OS is planned soon.  

### Requirements  
To install and run the project, you need [Visual Studio](https://visualstudio.microsoft.com/) 2022 and [Cosmos User Kit](https://www.gocosmos.org/) of any version, but it must be compatible with Visual Studio 2022 (I recommend the latest version, as it is quite stable).  

## Testing  
Since this OS is designed for virtual machines, it can only be launched through `src`. When the system starts, it automatically waits for a Visual Studio debugger connection, and only then does it launch. The system is not suitable for main computers.  

## Contributing  
How to help develop the project? How to submit a suggestion or bug report? How to send an improvement (submit a pull request, what style guides are used)?  
Since the OS is open-source, you can develop your own simple programs for it and send them to our [Discord Server](https://discord.gg/TJamYrQJaE).  

## FAQ  
# How do I launch the system?  
Described above.  
# Why can't the system be installed on a main PC?  
1. The system waits for a Visual Studio debugger connection.  
2. The code is adapted for Windows.  

### Why did you develop this project?  
Just because. My work is to show why open-source OSs are better than closed-source ones.  

## To do  
- [x] Add graphical interface support  
- [ ] Improve the current OS and release bug-fix builds before working on the graphical interface  

## Contacts  

- [Discord Server](https://discord.gg/TJamYrQJaE)  
- [Telegram Channel](https://t.me/hatosgit)  


## 🇷🇺 RU
# HatOS
HatOS - операционная система для виртуальнх машин с открытым исходным кодом,написанная полностью на c# с использованием сторонних пакетов CosmosOS

## Содержание
- [Технологии](#технологии)
- [Начало работы](#начало-работы)
- [Тестирование](#тестирование)
- [Contributing](#contributing)
- [To do](#to-do)
- [Контакты](#контакты)

## Технологии
- [CosmosOS](https://www.gocosmos.org/)
- [Visual Studio](https://visualstudio.microsoft.com/)

## Использование
Установка проекта не займет достаточно много времени.Необходимо установить visual studio и пакеты поддержки c#,а также cosmos user kit.После чего перезапустить компьютер и открыть .sln файл в src.Для запуска необходима vmware workstation/player.Это можно изменить в свойствах проекта

## Разработка
Разработка проекта не заняла у меня много времени,однако проект будет обновляться и постепенно обьем моей работы будет увеличиваться.Планируется скоро сделать поддержку графической ОС

### Требования
Для установки и запуска проекта, необходимы [Visual Studio](https://visualstudio.microsoft.com/ru/) 2022, [Cosmos User Kit](https://www.gocosmos.org/) любой версии,но главное чтобы она подходила под visual studio 2022 (рекомендую последнюю версию,она довольно стабильная)


## Тестирование
Так как это ОС для виртуальных машин запустить ее можно только через ее src. При запуске системы она автоматически ждет подключение debugger visual studio и только после этого запускаеися. Система не подходит для основных компьютеров


## Contributing
Как помочь в разработке проекта? Как отправить предложение или баг-репорт. Как отправить доработку (оформить pull request, какие стайлгайды используются).
Из-за того,что ОС с открытым кодом можно разрабатывать свои простенькие программы на нее и отправлять в наш [Discord Server](https://discord.gg/TJamYrQJaE)


## FAQ 
# Как запустить систему?
Расписано выше.
# Почему систему нельзя установить на основной пк?
1. Система ожидает подключение debugger visual studio
2. Код адаптирован под windows

### Зачем вы разработали этот проект?
Чтобы был. Моя работа показать,чем ОС с открытым исходным кодом лучше чем ос с закрытым

## To do
- [x] Сделать поддержку графического интерфейса
- [ ] Улучшать уже текущую ОС и выпускать баг-фикс билды,а уже потом взяться за графический интерфейс

## Контакты

- [Discord Server](https://discord.gg/TJamYrQJaE)
- [Telegram Channel](https://t.me/hatosgit)
