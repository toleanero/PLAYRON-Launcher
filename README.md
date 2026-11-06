# PLAYRON

PLAYRON — лаунчер для серверов Counter-Strike 1.6 на Windows. В нём можно найти сервер и зайти на него через установленную CS.

[Скачать PLAYRON 1.0.149](https://github.com/toleanero/PLAYRON-Launcher/releases/tag/v1.0.149) | [English](#english)

![Список серверов Counter-Strike 1.6 в PLAYRON 1.0.149](launcher.png)

У меня стоит CS 1.6 в Steam и ещё несколько сборок. Когда хочется поиграть, я сперва выбираю, куда зайти. На одном сервере идёт карта, которую я люблю, но людей пока мало. На другом уже играют, зато пинг выше. Мне хотелось видеть всё это до запуска игры и выбирать, какую CS открыть. Для этого я и начал делать PLAYRON.

Например, хочется сыграть на Mansion. Ввожу название карты, смотрю, где есть игроки, и выбираю сервер. Лаунчер запускает мою CS и подключается к нему. Если сервер понравился, добавляю его в избранное. Когда помню карту, но забыл название сервера, выручает история. В списке игр можно переключиться со Steam на другую сборку и настроить для неё параметры запуска.

Позже я взялся за зеркала. В поиске Steam попадаются разные адреса, которые приводят на один и тот же сервер. Для Steam-версии CS 1.6 я добавил отдельный фильтр. Он блокирует обращения к известным зеркалам через брандмауэр Windows. Если нужен конкретный адрес, его можно добавить в исключения. [Как работает фильтр](https://servers.playron.ru/mirrors/about)

### Спасибо Ch0wW

Ch0wW описал, как блокировать зеркала через брандмауэр Windows. С его разбора я начал работу над фильтром PLAYRON. Спасибо, что поделился этим способом. [Разбор Ch0wW на GitHub](https://github.com/Ch0wW/goldsrc-fake-servers-firewall#the-solution)

Список серверов можно открыть и в браузере. Если не получается зайти через лаунчер, напиши, на каком сервере и с какой сборкой возникла проблема. [Серверы CS 1.6](https://servers.playron.ru/servers) | [Поддержка](https://servers.playron.ru/support)

## English

PLAYRON is a Windows launcher for Counter-Strike 1.6 servers. Find a server and join it with the copy of CS you already have installed.

[Download PLAYRON 1.0.149](https://github.com/toleanero/PLAYRON-Launcher/releases/tag/v1.0.149)

I have CS 1.6 on Steam and a few other builds installed. When I feel like playing, I start by picking a server. One might be running a map I like but still waiting for players. Another is already busy, but the ping is higher. I wanted to see that before starting the game and choose which copy of CS to launch. That's why I started PLAYRON.

Say I want to play Mansion. I search for the map, see where people are playing and pick a server. PLAYRON starts my copy of CS and connects to it. If I like the server, I add it to Favorites. If I remember the map but forget the server's name, I can find it in History. The game list also lets me switch from Steam to another build and edit its launch options.

I worked on mirrors later. In the Steam server browser, different addresses can send you to the same server. I added a separate filter for the Steam version of CS 1.6. It uses Windows Firewall to block requests to known mirrors, and you can add an exception for a server you want to reach. [How the filter works](https://servers.playron.ru/mirrors/about)

### Thanks to Ch0wW

Ch0wW explained how to block mirrors with Windows Firewall. His write-up was my starting point for the PLAYRON filter. Thanks for sharing it. [Ch0wW's write-up on GitHub](https://github.com/Ch0wW/goldsrc-fake-servers-firewall#the-solution)

You can also open the server list in your browser. If you run into trouble joining from the launcher, tell me which server and build you were using. [CS 1.6 server list](https://servers.playron.ru/servers) | [Support](https://servers.playron.ru/support)
