# 🪟 Windows:  
>
> [!NOTE]
> [Перманентная активация Windows 10-11 с серверной привязкой по железу:](https://github.com/massgravel/Microsoft-Activation-Scripts)  
Открываем PowerShell, запускаем команду `irm massgrave.dev/get | iex`, выбираем **[1] HWID.** Готово.  

### ⚙️ Настройка и дополнения к системе
* [SophiApp.](https://github.com/Sophia-Community/SophiApp) Тонкая подстройка рабочего окружения под себя. Использует только то, что реализуемо путём задокументированного разработчиками Windows функционала.<sup>[`ℹ️`](https://github.com/Sophia-Community/SophiApp?tab=readme-ov-file#key-features)</sup>
* [VCRHyb64.](https://t.me/begoniacommunity/1310689) Сборник всех устанавливаемых Visual C++ Redistributable 2005-2022, устаналиваются сразу версии x86/x64.
* [.NET Runtime](https://dotnet.microsoft.com/en-us/download/dotnet-framework)<sup>[`ℹ️`](https://github.com/begoniacommunity/list/blob/main/list/info.md#net-runtime)</sup> и [VCLibs.](https://learn.microsoft.com/ru-ru/troubleshoot/developer/visualstudio/cpp/libraries/c-runtime-packages-desktop-bridge#how-to-install-and-update-desktop-framework-packages)<sup>[`ℹ️`](https://github.com/begoniacommunity/list/blob/main/list/info.md#vclibs)</sup> Порой нужные зависимости.
* [SKTimeStamp.](https://tools.stefankueng.com/SKTimeStamp.html) Добавляет раздел для точного изменения времени создания/модификации/открытия через свойства файла в Проводнике.
* [Windows Terminal.](https://github.com/microsoft/terminal/) Терминал от Microsoft с широкой кастомизацией, поддерживает любые виды консолей, будь то cmd, PowerShell или WSL. Сразу ставьте как приложение для командной строки по умолчанию.<sup>[`ℹ️`](https://learn.microsoft.com/ru-ru/windows/terminal/install#set-your-default-terminal-application)</sup>
* [SuperF4.](https://github.com/stefansundin/superf4/releases/download/v1.4/SuperF4-1.4.exe) «Принудительно закрывает»‎ зависшее окно, иными словами убивает его процесс, по сочетанию клавиш Ctrl+Alt+F4. То есть используется вами вместо стандартного сочетания Alt+F4, которое в случаях повисшего процесса не помогает.
* [Monitorian.](https://apps.microsoft.com/store/detail/monitorian/9NW33J738BL0) Изменение яркости внешних мониторов<sup>[`ℹ️`](https://github.com/emoacht/Monitorian#detection-of-external-monitors)</sup> через Windows.
* [Process Hacker 2.](https://processhacker.sourceforge.io/downloads.php) Управление работающими процессами в системе. Расширенная альтернатива диспетчера задач и монитора ресурсов.<sup>[`ℹ️`](https://processhacker.sourceforge.io/)</sup> Строго рекомендуется установка в полном режиме.

### 🎨 Персонализация
* [BeautySearch.](https://github.com/krlvm/BeautySearch) Модификации для поиска, встроенного в панель задач.
* <sup>`(Windows 10)`</sup>[TrayVolumeControl.](https://github.com/krlvm/TrayVolumeControl) Регулировка громкости колёсиком мыши при наведении курсора на иконку громкости. Быстро привыкаешь и без этого становится неудобно, советую.
* <sup>`(Windows 10/11 <22H2)`</sup>[EarTrumpet.](https://eartrumpet.app/) Альтернативное меню управления звуком для панели задач. Основная польза в наличии микшера громкости приложений под общим ползунком громкости. Переключение источника звука через ПКМ по иконке.<sup>[превью](https://github.com/begoniacommunity/list/blob/main/list/info.md#eartrumpet)</sup> Так же по умолчанию есть регулировка громкости колёсиком по наведении на иконку, соответственно программа выше не нужна.
* <sup>`(Windows 11)`</sup>[MicaForEveryone.](https://github.com/MicaForEveryone/MicaForEveryone) Кастомизация внешнего вида окон Win32-приложений. 
* <sup>`(Windows 11)`</sup>[StartAllBack.](https://t.me/repack_me_clone) Незаменимый софт для комфортного перехода с Windows 10 на 11. Можно использовать пресет "Правильная 11", либо настроить всё вручную. Нормальная панель задач, улучшенный тёмный режим и акцентный цвет для Win32-элементов, акриловый фон для классического контекстного меню, регулировка громкости колёсиком мыши и другое. Пробуйте.
* <sup>`(Windows 10/11)`</sup>[ExplorerBlurMica.](https://github.com/Maplespe/ExplorerBlurMica) Софт для настройки эффекта акрила (как в Windows 10) или Mica для окон Проводника.

<details>

<summary>Рекомендуемые настройки для Windows 11</summary>

1. Для [MicaForEveryone:](https://github.com/MicaForEveryone/MicaForEveryone) проставить всё на "По умолчанию" в разделе "Глобальное правило", в дальнейшем создавая для каждой программы отдельный конфиг. Цвет заголовка окна выбирайте в соответствии с темой программы; фон на Tabbed; включить "Расширить рамку окна в клиентскую область".
2. [StartAllBack:](https://www.startallback.com/) открыть окно "Выполнить" (Win+R), запустить команду `startisbackcfg /magic`. Откроется окно свойств StartAllBack в разделе Magic, включаем пункт Cast dark magic. 
3. [ExplorerBlurMica:](https://github.com/Maplespe/ExplorerBlurMica) настраиваем эффект Mica для всех окон Проводника в Windows 11:
   * Должны быть установлены **все три** программы: Mica For Everyone, StartAllBack и ExplorerBlurMica.
   * В StartAllBack должена быть активирована опция Cast dark magic.
   1. Переходим к файлу config.ini, расположенном в папке с ExplorerBlurMica.
   2. Редактируем содержимое строк:  
   `effect` меняем на `2`  
   `clearWinUIBg` меняем на `false`<sup>[превью](https://github.com/begoniacommunity/list/blob/main/list/info.md#explorerblurmica-false)</sup> или оставляем `true`<sup>[превью](https://github.com/begoniacommunity/list/blob/main/list/info.md#explorerblurmica-true)</sup> – попробуйте, какой вариант больше понравится.  
   В дереве `[dark]` меняем `a` на `255`. Всё остальное должно (r, g, b) быть со значением `0`.  
   3. Открываем Mica For Everyone и полностью удаляем пресет для explorer.
   4. Добавляем правила для классов `#32700` и `OperationStatusWindow`. В обоих устаналиваем параметр Фон на *Tabbed* и включаем Расширение рамки в клиентскую область.
   5. Принудительно перезагружаем Проводник.
</details>
 
* [MSEdgeRedirect.](https://github.com/rcmaehl/MSEdgeRedirect) Кастомизация для панелей новостей, погоды и смена стандартного браузера для переадресации из поиска в системе.
* [Cursor Colors Synchronizer.](https://github.com/SunsetTechuila/Cursor-Colors-Synchronizer) Синхронизирует цвет акцента системы с [кастомным курсором на выбор.](https://github.com/SunsetTechuila/Cursor-Colors-Synchronizer#description)
* [WinPaletter.](https://github.com/Abdelrhman-AK/WinPaletter) Гибкая настройка цветовой палитры различных элементов интерфейса Windows.<sup>[`ℹ️`](https://github.com/Abdelrhman-AK/WinPaletter#-winpaletter-advanced-windows-appearance-editor)</sup>

### ⏺ Скрин-шеринг, запись экрана и скринрекордеры
* [RustDesk (Windows).](https://rustdesk.com/) Свободная альтернатива AnyDesk/TeamViewer. Возможен селфхост, но отлично работает и на бесплатных серверах из Германии и Киева.
* [ShareX.](https://getsharex.com/) Лучший скрин-шотер/рекордер для Windows. Вкратце: мега кастомизируемая прога с полностью открытым исходным кодом. Удобный, точный выбор области записи/снимка, есть широкий выбор инструментов для редактирования скриншота, умеет записывать экран с использованием NVENC, автоматически конвертировать записанное видео в GIF, опционально выгружать скриншоты на всевозможные имейдж-аплоадеры выборочно в пару кликов. Всё управление через хоткеи. Абсолютный мастхэв.
* [OBS.](https://obsproject.com/ru) Продвинутый захват экрана и стриминг. Поддерживает разные сцены, удобная панель управления, поддержка плагинов. Гибко настраивается.  

### 🌸 Жизнь
* [Lively Weather.](https://github.com/rocksdanister/weather) Шикарное приложение для прогноза погоды.

### 🤖 Эмуляция
* [(*EOL*)](https://github.com/microsoft/WSA/commit/5e0b982be3f6a9613d65a389d12554844d931bba) [WSABuilds.](https://github.com/MustardChef/WSABuilds) Подсистема Windows для Android, увидевшая свет с выходом Windows 11. Репозиторий содержит сборки как для Windows 11, так и 10. Есть вариации с OpenGApps/MindTheGApps, Magisk/~~KernelSU~~. И вырезан бесполезный Amazon Store, конечно. Установка проста даже для ёжика — распаковать архив и запустить Run.bat. 

### 🖼 Медиаконтент
* [Mp3tag.](https://mp3tag.de/en/download.html) Редактирование метаданных в аудиофайлах.

### 🔈Звук
* [Alternative A2DP Driver.](https://bluetoothgoodies.com/a2dp/) Незаменимая вещь для владельцев Bluetooth-наушников с поддержкой HiRes кодеков aptX HD и LDAC/LDHC. По умолчанию, Windows умеет работать только с AAC (Windows 11)/SBC кодеками, что существенно режет качество воспроизводимого аудио. Данная программа действительно панацея, но... Внимание: платно! Есть пробный период, в течение которого доступен весь функционал. Проверьте совместимость с вашими наушниками, затем либо программа прекращает работу, либо вами покупается перманентная лицензия с привязкой по железу — $5.99. В рублях, на момент написания текста, это ~850 руб. оплатой через карту, [приобретённую на Plati.market.](https://plati.io/itm/1065234)
* [EqualizerAPO.](https://sourceforge.net/projects/equalizerapo/) Лучший эквлайзер для Windows, легко устаналивается и не вредит системе. Имеет широкий спектр различных настроек, возможность сохранять/применять пресеты для разных параметров.

### 📄 Офисное
* [Notepad++.](https://notepad-plus-plus.org/downloads/) Текстовый редактор с широкой поддержкой сообщества. Поддерживает плагины, темы, разные форматы.
* [Office Tool Plus.](https://github.com/YerongAI/Office-Tool) Загрузка и установка, гибкая настройка, активация... в целом, управление пакетами Office.
* [Okular.](https://okular.kde.org/ru/) Универсальная читалка от KDE для форматов PDF, EPub, Tiff [и подобных.](https://okular.kde.org/ru/formats/)

### 🎞 Транскодирование
* [HandBrake.](https://handbrake.fr/) Конвертирование видео по различным критериям в почти любой формат.

### 🖥 Управление программами
* [WingetUI.](https://github.com/marticliment/WingetUI) Графический интерфейс управления пакетным менеджером winget. Из наболее очевидных удобств, автоматическое/выборочное обновление всего установленного софта на ПК через winget. Советуем попробовать начать пользоваться этим.
* [Uninstall Tool.](https://t.me/repack_me_clone) Расширенное удаление программ вместе с их "хвостами". Можно опционально выбрать установку сервиса, который будет отслеживать установки и собирать точную информацию про инсталляцию любого софта в систему.

### 📶 Управление сетью
* [Simplewall.](https://henrypp.org/product/simplewall) Настройка трафика с Windows Filtering Platform (WFP).

### 📀 Запись установочных образов
* [Rufus.](https://rufus.ie) Базированнейшая тулза для записи образов. 
* [Ventoy.](https://ventoy.net/en/index.html) Софт для создания установочных, мульти/загрузочных флешек. Крайне прост в использовании: достаточно в один клик установить загрузочный раздел, а затем в автоматически созданный пустой раздел положить загрузочный(-е) .iso-образ(-ы). Работает с MBR и GPT (не всегда корректно).
* [Netboot.](https://netboot.xyz/) PXE-загрузчик<sup>[`ℹ️`](https://github.com/begoniacommunity/list/blob/main/list/info.md#pxe-%D0%B7%D0%B0%D0%B3%D1%80%D1%83%D0%B7%D1%87%D0%B8%D0%BA)</sup> различных установщиков/LiveCD-шек систем. Сложнее варианта выше.

### ⬇️ Управление файлами и загрузки
* [7-Zip.](https://7-zip.org/) Архиватор.
* [Free Download Manager.](https://freedownloadmanager.org/ru/) Удобный менеджер загрузок.
* [qBittorrent.](https://fosshub.com/qBittorrent.html) Загрузка торрентов.

### 💡 Полезное
* [PowerToys.](https://github.com/microsoft/PowerToys) Приложение от Microsoft, что-то вроде сборника утилит всё-в-одном. Содержит [миллиард самой разной полезной хуйни,](https://github.com/microsoft/PowerToys#about) однозначно найдете применение для себя.
* [Sysinternals Suite.](https://learn.microsoft.com/en-us/sysinternals/downloads/sysinternals-suite) Ещё один набор мелких утилит. Можно скачать всё разом, [либо необходимое по отдельности.](https://learn.microsoft.com/en-us/sysinternals/downloads/sysinternals-suite#introduction)

## ✈️ Telegram
* [64Gram.](https://github.com/TDesktop-x64/tdesktop) Простой модифицированный клиент на основе официального [с небольшим количеством полезных дополнений.](https://github.com/TDesktop-x64/tdesktop/blob/dev/features.md)
* [AyuGram.](https://github.com/AyuGram/AyuGramDesktop) Добавлен полноценный режим невидимки, нечиталки и неписалки. Можно включить "локальный" Telegram Premium (активация функций, не требующих серверного подтверждения); отключить рекламу, истории. Сохраняются удалённые сообщения, история редактирования сообщений во всех чатах; отображение ID профиля, чата или канала. 
>
> [!CAUTION]
> **Некоторый функционал в AyuGram нарушает ToS.** Если команда Telegram решит заняться вопросом существования данного клиента, есть все основания полагать, что за его использование ваш аккаунт в любой момент может быть ограничен или заблокирован.
* [Unigram.](https://github.com/UnigramDev/Unigram) UWP-клиент c Fluent дизайном. Анимации заметно подтормаживают, в целом юзабельный, но сильно уступает TGDesktop по удобству. 

## 📟 Discord:
### Моды

* [Связка Vencord + OpenAsar.](https://vencord.dev/) Широкая поддержка полезных плагинов и тем от сообщества, ускорение холодного старта программы и повышение общей производительности в Discord. 

Установку производим через [инсталлер Vencord.](https://github.com/Vencord/Installer/releases/latest/download/VencordInstaller.exe) Важно: сохраните его в любом удобном для вас месте. Иногда Vencord (и реже OpenAsar) слетают после обновления Discord, в таком случае нужно заново запустить установщик и переустановить их кнопками **Install Vencord** или **Reinstall / Repair** и **Install OpenAsar.** Это восстановит моды со всеми вашими настройками, плагинами и темами.  
> [!NOTE]
> В конфигурации OpenAsar можно выбирать режим производительности. Для настольных ПК/при постоянном питании рекомендуется использовать Performance, в ином случае Balanced.

### Плагины  

<sup>*(все перечисленные плагины сразу доступны в разделе Vencord → Plugins, их нужно только активировать)*</sup>

* [AlwaysTrust.](https://vencord.dev/plugins/AlwaysTrust) Убирает всплывающее окно о подозрительном сайте или файле.
* [AnonymiseFileNames.](https://vencord.dev/plugins/AnonymiseFileNames) Анонимизирует имя отправляемых файлов, присваивая им рандомное название.
* [BetterGifAltText.](https://vencord.dev/plugins/BetterGifAltText) Меняет приписку *"GIF"* на теги GIF или имя файла.
* [BiggerStreamPreview.](https://vencord.dev/plugins/BiggerStreamPreview) Увеличивает превью стримов.
* [NoScreensharePreview.](https://vencord.dev/plugins/NoScreensharePreview) Напротив плагину выше, совсем отключает превью стримов.
* [CallTimer.](https://vencord.dev/plugins/CallTimer) Добавляет таймер продолжительности разговора в голосовые чаты.
* [ClearURLs.](https://vencord.dev/plugins/ClearURLs) Автоматически чистит трекеры в ссылках.
* [CopyUserURLs.](https://vencord.dev/plugins/CopyUserURLs) Добавляет пункт копирования прямой ссылки на пользователя в контекстное меню.
* [CrashHandler.](https://vencord.dev/plugins/CrashHandler) *Пытается* предотвратить вылеты приложения.
* [DisableDMCallIdle.](https://vencord.dev/plugins/DisableDMCallIdle) Отключает автокик из голосового канала после трёх минут инактива.
* [EmoteCloner.](https://vencord.dev/plugins/EmoteCloner) Быстрое клонирование кастомного эмодзи/стикера на ваш сервер.
* [Experiments.](https://vencord.dev/plugins/Experiments) Предоставляет доступ к разделу экспериментальных функций.
* [FakeNitro.](https://vencord.dev/plugins/FakeNitro) Подделывает некоторые функции Nitro (использование фейковых эмодзи/стикеров) и позволяет стримить в высоком качестве.
* [FavoriteEmojiFirst.](https://vencord.dev/plugins/FavoriteEmojiFirst) При :автозаполнении: выводит ваши избранные эмодзи наверх.
* [ForceOwnerCrown.](https://vencord.dev/plugins/ForceOwnerCrown) Принудительно отображает корону рядом с ником владельца сервера.
* [GifPaste.](https://vencord.dev/plugins/GifPaste) Вместо моментальной отправки GIF, вставляет ссылку на неё в поле ввода. В результате отправленное сообщение выглядит идентично, при этом предотвращаются неудобные случаи с мисскликами.
* [GreetStickerPicker.](https://vencord.dev/plugins/GreetStickerPicker) Ручной выбор приветственного стикера по ПКМ.
* [HideAttachments.](https://vencord.dev/plugins/HideAttachments) Добавляет кнопку скрытия медиа и вложений на панель ввода.
* [IgnoreActivities.](https://vencord.dev/plugins/IgnoreActivities) Настройки отображения выборочных активностей.
* [iLoveSpam.](https://vencord.dev/plugins/iLoveSpam) Принудительно отображает сообщения, помеченные как потенциально нежелательные.
* [ImageZoom.](https://vencord.dev/plugins/ImageZoom) Приближение изображений и GIF через ЛКМ+колёсико мыши.
* [MessageLogger.](https://vencord.dev/plugins/MessageLogger) Временное сохранение удалённых сообщений и истории редактирования.
* [MoreUserTags.](https://vencord.dev/plugins/MoreUserTags) Больше тегов для вебхуков и ролей модерации (staff, mod и другие).
* [MuteNewGuild.](https://vencord.dev/plugins/MuteNewGuild) Приглушает новые сервера, на которые вы заходите.
* [MutualGroupDMs.](https://vencord.dev/plugins/MutualGroupDMs) Показывает общие группы в профиле пользователя.
* [NoBlockedMessages.](https://vencord.dev/plugins/NoBlockedMessages) Полное скрытие сообщений от заблокированных вами пользователей.
* [NoF1.](https://vencord.dev/plugins/NoF1) Убирает вызов центра помощи по нажатию клавиши F1.
* [NoProfileThemes.](https://vencord.dev/plugins/NoProfileThemes) Отключает кастомное оформление Nitro-профиля, приводя его к единому стилю с обычным.
* [NoUnblockToJump.](https://vencord.dev/plugins/NoUnblockToJump) Позволяет переходить к сообщениям от пользователей, которых вы заблокировали.
* [OnePingPerDM.](https://vencord.dev/plugins/OnePingPerDM) При получении нескольких сообщений от пользователя в ЛС, пройдёт только один звук уведомления.
* [OpenInApp.](https://vencord.dev/plugins/OpenInApp) Открывает ссылки на Spotify, Steam и Epic Games в соответствующих приложениях, а не в браузере.
* [PermissionsViewer.](https://vencord.dev/plugins/PermissionsViewer) Просмотр разрешений, которыми обладает пользователь/канал/роль сервера.
* [PictureInPicture.](https://vencord.dev/plugins/PictureInPicture) Добавляет режим Картинка-в-картинке для видео (рядом с кнопкой загрузки).
* [PlatformIndicators.](https://vencord.dev/plugins/PlatformIndicators) Добавляет индикатор платформы, с которой вы онлайн (ПК, телефон, браузер и другие).
* [QuickMention.](https://vencord.dev/plugins/QuickMention) Добавляет кнопку упоминания на панель ввода.
* [ReadAllNotificationsButton.](https://vencord.dev/plugins/ReadAllNotificationsButton) Выводит кнопку "Read all", которая очищает висящие непрочитанные сообщения со всех серверов.
* [RelationshipNotifier.](https://vencord.dev/plugins/RelationshipNotifier) Уведомляет, если: вас удалили из друзей; ваш запрос дружбы был отклонён; вы были удалены с сервера или группы.
* [RevealAllSpoilers.](https://vencord.dev/plugins/RevealAllSpoilers) Открывает все спойлеры в сообщении с помощью Ctrl+клик по одному из спойлеров/во всём чате с помощью Ctrl+Shift+клик.
* [ReverseImageSearch.](https://vencord.dev/plugins/ReverseImageSearch) Добавляет пункт поиска по картинке в контекстное меню изображений.
* [RoleColorEverywhere.](https://vencord.dev/plugins/RoleColorEverywhere) Добавляет цвет роли везде, кроме индикатора печати.
* [TypingTweaks.](https://vencord.dev/plugins/TypingTweaks) Выводит аватарку и цвет роли в индикатор печати. Применимо в том числе, когда печатает несколько человек.
* [SearchReply.](https://vencord.dev/plugins/SearchReply) Добавляет кнопку "Ответить" для сообщений в поиске.
* [ShikiCodeblocks.](https://vencord.dev/plugins/ShikiCodeblocks) Красивое оформление блоков кода в стиле VSCode. Можно применять свои темы.
* [ShowAllMessageButtons.](https://vencord.dev/plugins/ShowAllMessageButtons) Включает отображение всех кнопок на панели действий сообщения без необходимости зажимать Shift.
* [ShowHiddenChannels.](https://vencord.dev/plugins/ShowHiddenChannels) Отображение каналов, к которым отсутствует доступ. Показывает участников (если это голосовой канал) и дату последнего сообщения.
* [ShowTimeouts.](https://vencord.dev/plugins/ShowTimeouts) Отображает иконки тайм-аута пользователей в чате независимо от прав доступа.
* [SilentMessageToggle.](https://vencord.dev/plugins/SilentMessageToggle) Добавляет кнопку беззвучной отправки сообщений на панель ввода (заменяет ручное добавление *@silent* перед каждым сообщением).
* [SilentTyping.](https://vencord.dev/plugins/SilentTyping) Скрывает статус о печати. Можно добавить переключатель справа от поля ввода.
* [SortFriendRequests.](https://vencord.dev/plugins/SortFriendRequests) Сортирует запросы в друзья по дате получения; отображает дату.
* [Translate.](https://vencord.dev/plugins/Translate) Перевод сообщений через Google Переводчик.
* [TypingIndicator.](https://vencord.dev/plugins/TypingIndicator) Добавляет индикатор печати рядом с аватаркой канала.
* [ValidUser.](https://vencord.dev/plugins/ValidUser) Исправляет некорректное отображение пингов от незнакомых пользователей.
* [ViewRaw.](https://vencord.dev/plugins/ViewRaw) Копирование и просмотр любого сообщения в формате Raw.
* [VoiceMessages.](https://vencord.dev/plugins/VoiceMessages) Добавляет возможность отправки аудио в формате голосовых сообщений.
* [VolumeBooster.](https://vencord.dev/plugins/VolumeBooster) Позволяет устанавливать громкость пользователя в звонке выше максимальной.
* [WhoReacted.](https://vencord.dev/plugins/WhoReacted) Отображает аватары пользователей в области реакций (как в Telegram).

### Темы

<details>

<summary>Установка через Vencord (проще)</summary>

Настройки Discord, раздел Vencord → Themes → Online Themes. Поместите прямую ссылку к .css темы в поле ввода и переключите вкладку.

</details>

<details>

<summary>Установка через OpenAsar (лучше)</summary>

Настройки Discord → OpenAsar → Theming.  
1. Перейдите в репозиторий нужной темы.
2. В поиск по репо введите `@import url`.
3. Найдите основной файл в формате .css, **который состоит только из импорта ссылки на ресурсы темы и настроек.** Если такого нет среди файлов самого репозитория, то поищите его в релизах.
4. Скопируйте содержимое файла в поле ввода раздела Theming.  

</details>

* [Dark Discord.](https://github.com/discord-modifications/dark-discord) Действительно *тёмная* тема. Простая и неброская. [Превью.](https://gibbu.github.io/ThemePreview/?file=https://discord-modifications.github.io/dark-discord/src/source.css) Прямая ссылка: `https://raw.githubusercontent.com/localip/dark-discord/main/DarkDiscord.theme.css`
* [Fluent Discord.](https://github.com/TakosThings/Fluent-Discord) Тема, выполненная под стиль Microsoft Fluent Design (как в Windows 11). [Превью.](https://raw.githubusercontent.com/TakosThings/Fluent-Discord/develop/images/ui-1.5.5.png)  
Можно заменить фон приложения на свой (в соответствии с обоями рабочего стола, например). Для этого замените содержимое в скобках параметра `--fluent-acrylic-background: url` на прямую ссылку к картинке.

## 🎧 Spotify:
### Софт
1. [Spicetify](https://github.com/spicetify/spicetify-cli) (рекомендуется):
   * [Сразу устанавливаем Spicetify с Маркетплейсом одной командой.](https://github.com/spicetify/spicetify-marketplace/wiki/Installation)  
     Дальнейшая установка производится в основном только через меню Маркетплейса → Расширения. Этот метод установки подразумевает дальнейшее автоматическое обновление расширений по мере поступления апдейтов.
   * Установка Spicetify добавляет меню экспериментальных функций клиента (не меняя ничего по умолчанию). Используйте осторожно!  
   * Для пользователей без Premium-подписки → [Adblock.](https://github.com/CharlieS1103/spicetify-extensions/blob/main/adblock/README.md)

### Расширения и приложения

* [Full Screen Mode.](https://github.com/daksh2k/Spicetify-stuff/tree/master/Extensions/full-screen) Красивый и эстетичный полноэкранный режим. Для отображения текста необходимо активировать [lyrics-plus.](https://github.com/spicetify/spicetify-cli/blob/master/CustomApps/lyrics-plus/README.md)
* [Play Next.](https://github.com/daksh2k/Spicetify-stuff/blob/master/EXTENSIONS.md#play-next) По умолчанию, кнопка "Добавить в очередь" ставит трек в конец очереди. Это расширение добавляет кнопку, которая позволяет поместить выбранную вами песню следующей (первой) в очередь воспроизведения.
* [Section Marker.](https://github.com/Aimarekin/Aimarekins-Spicetify-Extensions/tree/main/section-marker) Добавляет разделители на таймлайн воспроизведения, разделяющие трек на фрагменты по изменениям настроения и ритмики. Работает со всеми треками.
* [Imaged Folders.](https://github.com/SunsetTechuila/imaged-folders) Расширение добавляет возможность устанавливать свои изображения на обложки папок с плейлистами.
* [Volume Percentage.](https://github.com/daksh2k/Spicetify-stuff/blob/master/EXTENSIONS.md#volume-percentage) Добавляет отображения громкости в процентах рядом с ползунком на панели плеера.
* [Immersive View.](https://github.com/ohitstom/spicetify-extensions/tree/main/immersiveView) Добавляет кнопку, скрывающую боковые панели, оставляя только текущую открытую страницу.
* [Scannables.](https://github.com/ohitstom/spicetify-extensions/tree/main/scannables) Сканируемые коды Spotify с мобильной версии клиента, открываются через контекстное меню.
* [Image Opener.](https://github.com/Tetrax-10/Spicetify-Extensions/tree/master/Image-Opener) Добавляет возможность открыть картинку с аватарки/облокжи/баннера в полном размере.
* [Show The Genres.](https://github.com/Delusoire/spicetify-extensions/tree/main/extensions/show-the-genres) Отображает общие жанры, присущие работам воспроизводимого артиста, в панели плеера.
* [Copy Lyrics.](https://github.com/Aimarekin/Aimarekins-Spicetify-Extensions/tree/main/copy-lyrics) Возможность копировать текст песен в режиме Караоке.
* [Copy to Clipboard.](https://github.com/pnthach95/spicetify-extensions) Позволяет копировать название песен.
* [Seek on scroll.](https://github.com/SunsetTechuila/seekonscroll) Перемотка трека колёсиком мыши по таймлайну.
* [Spicetify Stats.](https://github.com/harbassan/spicetify-stats) Отображение статистики, как в [volt.fm.](https://volt.fm) Установка производится [вручную.](https://github.com/harbassan/spicetify-stats#manual-installation)  

2. [SpotX](https://github.com/amd64fox/SpotX) (отключение рекламы для пользователей без Premium и активация экспериментальных функций; установка либо [автоматическая,](https://raw.githack.com/amd64fox/SpotX/main/Install_New_theme.bat) либо через выбор необходимых флагов [вручную](https://github.com/amd64fox/SpotX/discussions/60)).  

### Полезное

* [volt.fm.](https://volt.fm) Сервис сбора и анализа статистики вашего прослушивания. Предоставляет огромное количество полезных данных по жанрам, категориям, промежуткам времени.  
* [Google-таблица с прямыми ссылками на загрузку оффлайн-установщика всех версий Spotify для Windows.](https://docs.google.com/spreadsheets/d/1wztO1L4zvNykBRw7X4jxP8pvo11oQjT0O5DvZ_-S4Ok/edit?pli=1#gid=0)
* [Скрипт блокировки обновлений настольного клиента Spotify.](https://github.com/amd64fox/Rollback-Spotify)
* [Полное удаление клиента Spotify из системы.](https://github.com/amd64fox/Uninstall-Spotify)

## 🔧 CLI-утилиты
>
> [!NOTE]
> Для удобства использования, исполняемый .exe нужно закинуть в /system32, либо прописать путь к файлу в переменные среды PATH. [Как это сделать](https://remontka.pro/add-to-path-variable-windows/)  
Либо установить эти утилиты через Winget/Chocolatey/Scoop (рекомендуется!).  

* [aria2c.](https://aria2.github.io/) Аналог wget, Download Master и прочих. Поддерживает торренты.
* [ffmpeg.](https://ffmpeg.org/) Конвертер аудио и видео файлов, имеет много фич.
* [yt-dlp.](https://github.com/yt-dlp/yt-dlp) Загрузчик видео и аудио с YouTube, SoundCloud, PornHub и еще [с 1838 сайтов.](https://github.com/yt-dlp/yt-dlp/blob/master/supportedsites.md//) Рекомендуется использовать через Hitomi Downloader (см. ниже в разделе Полезное).
* [payload-dumper-go.](https://github.com/ssut/payload-dumper-go) Быстрая разборка payload.bin Android-прошивок на отдельные образы.
* [Revancify.](https://github.com/decipher3114/Revancify#installation) Удобная сборка и установка ReVanced/ReVanced Extended через Termux.
* [Chocolatey.](https://community.chocolatey.org/) Пакетный менеджер для Windows в стиле линуксовских apt/pacman. Мощнее встроенного Winget.
* [Scoop.](https://scoop.sh/) Аналог Chocolatey. В отличии от последнего, устанавливает программы не в систему, а в отдельную папку юзера, некие "полу-портативные" версии, которые потом легко удалить. Из минусов: ОЧЕНЬ медленный cli-поиск.

## ⏹ Скрипты

* [Platform Tools Installer.](https://github.com/SunsetTechuila/Platform-Tools-Installer) Скрипт автоматически скачивает актуальные [Platform tools](https://developer.android.com/tools/releases/platform-tools) для вашей платформы, предлагает выбрать место для распаковки, после чего добавляет их в PATH.

## 🗂 Модификация интерфейса Windows через .reg-файлы
* [Скрыть стрелку с ярлыков на рабочем столе.](https://t.me/begoniacommunity/1384476) Перемещаем файл Blank.ico в корневую папку Windows и запускаем RemoveArrow.bat; перезагружаем Проводник. Чтобы откатить изменения, запускаем RestoreArrow.bat.
