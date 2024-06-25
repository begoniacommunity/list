# 🚫 Обход блокировок

### VPN
* [**Настройка личного сервера.**](https://github.com/begoniacommunity/unrestrict) Это платно (совсем не дорого), но надёжно. Рекомендуем использовать Promo (~1,1€/мес.) или Shared (~5€/мес.) VPS в европейских локациях от хостинга [aéza.](https://aeza.net/)

<details>

<summary>Другое</summary>

Варианты ниже могут быть менее безопасными (например, по части вашей анонимизации перед интернет-провайдером, так и с подозрением на утечку трафика третьим лицам) и сильно менее надёжными (уязвимые к блокировкам или попросту нестабильные).

### [GoodbyeDPI](https://github.com/ValdikSS/GoodbyeDPI)
Умный обход систем глубокой проверки пакетов (ТСПУ).

Установка на Windows:
1. [Скачиваем последнюю версию GoodbyeDPI со страницы релизов.](https://github.com/ValdikSS/GoodbyeDPI/releases)
2. Переносим папку в любую точку на диске, откуда впоследствии папку удалять не будем.
3. Берём свежие листы:
   * Под VPN, заходим по адресу [antizapret.prostovpn.org/domains-export.txt](https://antizapret.prostovpn.org/domains-export.txt) и сохраняем файл в раннее скачанную папку, с именем `russia-blacklist.txt`.
4. В зависимости от ваших предпочтений, от имени администратора запускаем:
   * `service_install_russia_blacklist.cmd`
   * `service_install_russia_blacklist_dnsredir.cmd` c перенаправлением DNS-резолвера на DNS Яндекса.

Это установит сервис GoodbyeDPI в Windows, он будет запускаться автоматически вместе с системой. Не мешает работе VPN. Чтобы удалить, воспользуйтесь `service_remove.cmd`.  
[Варианты для других платформ.](https://github.com/ValdikSS/GoodbyeDPI#similar-projects) Не рекомендуется использовать на Android ввиду агрессивной реакции банковских приложений (например, Mir Pay автоматически стирает все карты и блокирует функционал).

### Сеть Tor
Вкратце то, что из себя представляет Tor, можно описать как огромную систему прокси-серверов, позволяющую устанавливать анонимное сетевое соединение из любой точки Интернета.
* [Tor Browser.](https://tor.calyxinstitute.org/download/) Самый простой и очевидный юзкейс Tor в оформлении фирменного браузера, также включающего в себя различные уровни защиты от трекеров и другой слежки. 
* [Tor Bridges.](https://bridges.torproject.org/) Запрос мостов для обхода блокировки сети Tor (необходимо для России). Мосты можно получить по электронной почте, отправив пустое письмо на адрес bridges@torproject.org (только с ящиков Gmail).
* [Tor Control Panel.](https://github.com/abysshint/tor-control-panel/blob/main/README.ru.md#readme-top) Управление и мониторинг сети Tor в Windows (Tor Expert Bundle).

### Прокси
Списки бесплатных прокси (они могут быть небезопасны!). Такими стоит пользоваться только в крайнем случае.  
* [hidemyname](https://hidemy.io/ru/proxy-list/)  
* [SPYS.ONE](https://spys.one/)

### [MTProto в Telegram](https://core.telegram.org/mtproto)
* [MTProxyStar.](https://t.me/MTProxyStar) Свежие прокси. Низкий пинг, работают стабильно.

</details>

