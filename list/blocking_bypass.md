# 🚫 Обход блокировок:

### VPN
* [**Настройка собственного сервера под нужды VPN.**](https://github.com/begoniacommunity/unrestrict) Это платно (совсем не дорого), но надёжно. Рекомендуем использовать Promo (~110 руб./мес) или Shared (~500 руб./мес) тарифы хостинга [aéza.](https://aeza.net/)

### GoodbyeDPI
Умный обход систем глубокой проверки пакетов (ТСПУ).
1. [Скачиваем последнюю версию GoodbyeDPI для Windows со страницы релизов.](https://github.com/ValdikSS/GoodbyeDPI/releases)
2. Переносим папку в любую точку на диске, откуда впоследствии папку удалять не будем.
3. Берём свежие листы:
   * Под VPN, заходим по адресу [antizapret.prostovpn.org/domains-export.txt](https://antizapret.prostovpn.org/domains-export.txt) и сохраняем файл в раннее скачанную папку, с именем `russia-blacklist.txt`.
4. В зависимости от ваших предпочтений, от имени администратора запускаем:
   * `service_install_russia_blacklist.cmd`
   * `service_install_russia_blacklist_dnsredir.cmd` c перенаправлением DNS-резолвера на DNS Яндекса.

Это установит сервис GoodbyeDPI в Windows, он будет запускаться автоматически вместе с системой. Не мешает работе VPN. Чтобы удалить, воспользуйтесь `service_remove.cmd`.  
[Варианты для других платформ](https://github.com/ValdikSS/GoodbyeDPI#similar-projects)  
[Больше информации в профильном репозитории](https://github.com/ValdikSS/GoodbyeDPI#how-to-use)
<details>

<summary>Другое</summary>

### Tor
Вкратце то, что из себя представляет Tor, можно описать как огромную систему прокси-серверов, позволяющую устанавливать анонимное сетевое соединение из любой точки Интернета.
* [Tor Browser.](https://tor.calyxinstitute.org/download/) Самый простой и очевидный юзкейс Tor в оформлении фирменного браузера, также включающего в себя различные уровни защиты от трекеров и другой слежки. 
* [Tor Bridges.](https://bridges.torproject.org/) Запрос мостов для обхода блокировки сети Tor (необходимо для России). Мосты можно получить по электронной почте, отправив пустое письмо на адрес bridges@torproject.org (только с ящиков Gmail).
* [Tor Control Panel.](https://github.com/abysshint/tor-control-panel/blob/main/README.ru.md#readme-top) Управление и мониторинг сети Tor в Windows (Tor Expert Bundle).

### Прокси
Списки бесплатных прокси. Такими лучше пользоваться в крайнем случае.  
* [hidemyname](https://hidemy.io/ru/proxy-list/)  
* [SPYS.ONE](https://spys.one/)

### MTProto для Telegram
* [MTProxyStar.](https://t.me/MTProxyStar) Свежие прокси. Низкий пинг, работают стабильно.

### Мессенджеры
>
> На текущий момент, этот раздел позиционируется как "на всякий случай". Здесь будут перечислены наиболее жизнеспособные методы безопасного общения в реальности, если Чебурнет всё-таки случится.  

* [Briar.](https://briarproject.org/) Обмен зашифрованными сообщениями через сеть Tor, локальный Wi-Fi или Bluetooth.
* [Delta Chat.](https://delta.chat/ru/) Обмен зашифрованными сообщениями через электронную почту, там, [где поддерживается Autocrypt.](https://autocrypt.org/dev-status.html) Интерфейс приложения представлен в виде стандартного мессенджера. [Подробнее здесь.](https://delta.chat/ru/help)

</details>

