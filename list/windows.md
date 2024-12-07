# 🪟 Windows:  
>
> [!NOTE]
> [Перманентная активация Windows 10-11 с серверной привязкой по железу:](https://github.com/massgravel/Microsoft-Activation-Scripts)  
Открываем PowerShell, запускаем команду `irm massgrave.dev/get | iex`, выбираем **[1] HWID.** Готово.  

### ⚙️ Настройка и дополнения к системе
* [SophiApp.](https://github.com/Sophia-Community/SophiApp) Тонкая подстройка рабочего окружения под себя. Использует только то, что реализуемо путём задокументированного разработчиками Windows функционала.<sup>[`ℹ️`](https://github.com/Sophia-Community/SophiApp?tab=readme-ov-file#key-features)</sup>
* [VisualCppRedist AIO.](https://github.com/abbodi1406/vcredist) Сборник всех устанавливаемых Visual C++ Redistributable 2005-2022, устаналиваются сразу версии x86/x64.
* [.NET Runtime](https://dotnet.microsoft.com/en-us/download/dotnet-framework)<sup>[`ℹ️`](https://github.com/reddxae/list/blob/main/list/info.md#net-runtime)</sup> и [VCLibs.](https://learn.microsoft.com/ru-ru/troubleshoot/developer/visualstudio/cpp/libraries/c-runtime-packages-desktop-bridge#how-to-install-and-update-desktop-framework-packages)<sup>[`ℹ️`](https://github.com/reddxae/list/blob/main/list/info.md#vclibs)</sup> Порой нужные зависимости.
* [SKTimeStamp.](https://tools.stefankueng.com/SKTimeStamp.html) Добавляет раздел для точного изменения времени создания/модификации/открытия через свойства файла в Проводнике.
* [Windows Terminal.](https://github.com/microsoft/terminal/) Терминал от Microsoft с широкой кастомизацией, поддерживает любые виды консолей, будь то cmd, PowerShell или WSL. Сразу ставьте как приложение для командной строки по умолчанию.<sup>[`ℹ️`](https://learn.microsoft.com/ru-ru/windows/terminal/install#set-your-default-terminal-application)</sup>
* [SuperF4.](https://github.com/stefansundin/superf4/releases/download/v1.4/SuperF4-1.4.exe) «Принудительно закрывает»‎ зависшее окно, иными словами убивает его процесс, по сочетанию клавиш Ctrl+Alt+F4. То есть используется вами вместо стандартного сочетания Alt+F4, которое в случаях повисшего процесса не помогает.
* [Monitorian.](https://apps.microsoft.com/store/detail/monitorian/9NW33J738BL0) Изменение яркости внешних мониторов<sup>[`ℹ️`](https://github.com/emoacht/Monitorian#detection-of-external-monitors)</sup> через Windows.
* [System Informer.](https://github.com/winsiderss/systeminformer) Свободный форк Process Explorer/Hacker с поддержкой тёмной темы (Options → General → Enable theme support). Управление работающими процессами в системе. Расширенная альтернатива диспетчера задач и монитора ресурсов.

### 🎨 Персонализация
* [BeautySearch.](https://github.com/krlvm/BeautySearch) Модификации для поиска, встроенного в панель задач.
* <sup>`(Windows 10)`</sup>[TrayVolumeControl.](https://github.com/krlvm/TrayVolumeControl) Регулировка громкости колёсиком мыши при наведении курсора на иконку громкости. Быстро привыкаешь и без этого становится неудобно, советую.
* <sup>`(Windows 10/11 <22H2)`</sup>[EarTrumpet.](https://eartrumpet.app/) Альтернативное меню управления звуком для панели задач. Основная польза в наличии микшера громкости приложений под общим ползунком громкости. Переключение источника звука через ПКМ по иконке.<sup>[превью](https://github.com/reddxae/list/blob/main/list/info.md#eartrumpet)</sup> Так же по умолчанию есть регулировка громкости колёсиком по наведении на иконку, соответственно программа выше не нужна.
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
   `clearWinUIBg` меняем на `false`<sup>[превью](https://github.com/reddxae/list/blob/main/list/info.md#explorerblurmica-false)</sup> или оставляем `true`<sup>[превью](https://github.com/reddxae/list/blob/main/list/info.md#explorerblurmica-true)</sup> – попробуйте, какой вариант больше понравится. 
   3. Открываем Mica For Everyone и полностью удаляем пресет для explorer.
   4. Добавляем правила для классов `#32700` и `OperationStatusWindow`. В обоих устаналиваем параметр Фон на *Tabbed* и включаем Расширение рамки в клиентскую область.
   5. Принудительно перезагружаем Проводник.
</details>
 
* [Windhawk.](https://github.com/ramensoftware/windhawk) Инъекции кода в Windows.
  * [Windows 11 Start Menu Styling.](https://github.com/ramensoftware/windows-11-start-menu-styling-guide) [Различные стили](https://github.com/ramensoftware/windows-11-start-menu-styling-guide#themes) для меню Пуск в Windows 11. Например, скрывающий секцию "Рекомендации", или добавляющий разметку с закрепленными приложениями и списком всех приложений. [Инструкция.](https://github.com/ramensoftware/windows-11-start-menu-styling-guide#introduction)
* [MSEdgeRedirect.](https://github.com/rcmaehl/MSEdgeRedirect) Кастомизация для панелей новостей, погоды и смена стандартного браузера для переадресации из поиска в системе.
* [Cursor Colors Synchronizer.](https://github.com/SunsetTechuila/Cursor-Colors-Synchronizer) Синхронизирует тему и акцентный цвет [одной из двух версий кастомного курсора](https://github.com/SunsetTechuila/Cursor-Colors-Synchronizer?tab=readme-ov-file#description) с системой.
* [WinPaletter.](https://github.com/Abdelrhman-AK/WinPaletter) Гибкая настройка цветовой палитры различных элементов интерфейса Windows.<sup>[`ℹ️`](https://github.com/Abdelrhman-AK/WinPaletter#-winpaletter-advanced-windows-appearance-editor)</sup>

### ⏺ Скрин-шеринг, запись экрана и скринрекордеры
* [RustDesk (Windows).](https://rustdesk.com/) Свободная альтернатива AnyDesk/TeamViewer. Возможен селфхост, но отлично работает и на бесплатных серверах из Германии и Киева. Последний не будет работать в России без VPN (РКН заблокировал любые подключения к UA-зоне).
* [ShareX.](https://getsharex.com/) Лучший скрин-шотер/рекордер для Windows. Вкратце: мега кастомизируемая прога с полностью открытым исходным кодом. Удобный, точный выбор области записи/снимка, есть широкий выбор инструментов для редактирования скриншота, умеет записывать экран с использованием NVENC, автоматически конвертировать записанное видео в GIF, опционально выгружать скриншоты на всевозможные имейдж-аплоадеры выборочно в пару кликов. Всё управление через хоткеи. Абсолютный мастхэв.
* [OBS.](https://obsproject.com/ru) Продвинутый захват экрана и стриминг. Поддерживает разные сцены, удобная панель управления, поддержка плагинов. Гибко настраивается.  

### 🌐 Браузеры
* [Chromium GOST.](https://github.com/deemru/Chromium-Gost) Браузер с открытым исходным кодом на основе Chromium с поддержкой алгоритмов ГОСТ (т.е. для российских сайтов, форсирующих использование государственных сертификатов).

### 🌸 Природа и жизнь
* [Lively Weather.](https://github.com/rocksdanister/weather) Шикарное приложение для просмотра прогноза погоды.

### 🤖 Эмуляторы
* [(*EOL*)](https://github.com/microsoft/WSA/commit/5e0b982be3f6a9613d65a389d12554844d931bba) [WSABuilds.](https://github.com/MustardChef/WSABuilds) Подсистема Windows для Android, увидевшая свет с выходом Windows 11. Репозиторий содержит сборки как для Windows 11, так и 10. Есть вариации с OpenGApps/MindTheGApps, Magisk/~~KernelSU~~. И вырезан бесполезный Amazon Store, конечно. Установка проста даже для ёжика — распаковать архив и запустить Run.bat. 

### 🖼 Медиаконтент
* [Mp3tag.](https://mp3tag.de/en/download.html) Редактирование метаданных в аудиофайлах.

### 🔈Звук
* [Alternative A2DP Driver.](https://bluetoothgoodies.com/a2dp/) Незаменимая вещь для владельцев Bluetooth-наушников с поддержкой HiRes кодеков aptX HD, aptX HD Low Latency и LDAC. По умолчанию, Windows умеет работать только с AAC (Windows 11)/SBC/aptX кодеками, что существенно режет качество воспроизводимого аудио. Данная программа действительно панацея, но... Внимание: платно! Есть пробный период, в течение которого доступен весь функционал. Проверьте совместимость с вашими наушниками, затем либо программа прекращает работу, либо вами покупается перманентная лицензия с привязкой по железу — $5.99. В рублях, на момент написания текста, это ~850 руб. оплатой через карту, [приобретённую на Plati.market.](https://plati.io/itm/1065234)
* [EqualizerAPO.](https://sourceforge.net/projects/equalizerapo/) Лучший эквлайзер для Windows, легко устаналивается и не вредит системе. Имеет широкий спектр различных настроек, возможность сохранять/применять пресеты для разных параметров.
* [EQAPOtoGraphicEQ.](https://github.com/zettonaender/eqapotographiceq-gui) Конвертация настроек Parametric EQ/Convolution EQ из EqualizerAPO или Peace в формат AutoEQ (например, для Wavelet). Рекомендую использовать Python-версию.

### ✉️ Почта
* [Thunderbird.](https://www.thunderbird.net/en-US/) Классический полнофункциональный почтовый клиент.
* Существует довольно красивый [Wino Mail,](https://github.com/bkaankose/Wino-Mail) вдохновленный ныне заброшенным нативным клиентом Outlook. Однако, за добавление более чем трёх ящиков, приложение просит донат.

### 📄 Офисное
* [Notepad++.](https://notepad-plus-plus.org/downloads/) Текстовый редактор с широкой поддержкой сообщества. Поддерживает плагины, темы, разные форматы.
* [Office Tool Plus.](https://github.com/YerongAI/Office-Tool) Загрузка и установка, гибкая настройка, активация... в целом, управление пакетами Office.
* [Okular.](https://okular.kde.org/ru/) Универсальная читалка от KDE для форматов PDF, EPub, Tiff [и подобных.](https://okular.kde.org/ru/formats/)

### 🎞 Транскодирование
* [HandBrake.](https://handbrake.fr/) Конвертирование видео с различными параметрами в почти любой формат.

### 🖥 Управление программами
* [WingetUI.](https://github.com/marticliment/WingetUI) Графический интерфейс управления пакетным менеджером winget. Из наболее очевидных удобств, автоматическое/выборочное обновление всего установленного софта на ПК через winget. Советуем попробовать начать пользоваться этим.
* [Uninstall Tool.](https://t.me/repack_me_clone) Расширенное удаление программ вместе с их "хвостами". Можно опционально выбрать установку сервиса, который будет отслеживать установки и собирать точную информацию про инсталляцию любого софта в систему.

### 📶 Управление сетью
* [Simplewall.](https://henrypp.org/product/simplewall) Настройка трафика с Windows Filtering Platform (WFP).

### 📀 Запись установочных образов
* [Rufus.](https://rufus.ie) Базированнейшая тулза для записи образов. 
* [Ventoy.](https://ventoy.net/en/index.html) Софт для создания установочных, мульти/загрузочных флешек. Крайне прост в использовании: достаточно в один клик установить загрузочный раздел, а затем в автоматически созданный пустой раздел положить загрузочный(-е) .iso-образ(-ы). Работает с MBR и GPT (не всегда корректно).
* [Netboot.](https://netboot.xyz/) PXE-загрузчик<sup>[`ℹ️`](https://github.com/reddxae/list/blob/main/list/info.md#pxe-%D0%B7%D0%B0%D0%B3%D1%80%D1%83%D0%B7%D1%87%D0%B8%D0%BA)</sup> различных установщиков/LiveCD-шек систем. Сложнее варианта выше.

### ⬇️ Управление файлами и загрузки
* [NanaZip.](https://github.com/M2Team/NanaZip) Форк 7-Zip с модернизированным интерфейсом.
* [Free Download Manager.](https://freedownloadmanager.org/ru/) Удобный менеджер загрузок.
* [qBittorrent.](https://fosshub.com/qBittorrent.html) Загрузка торрентов.
* [cppcryptfs.](https://github.com/bailey27/cppcryptfs) Управление файлами, зашифрованными с помощью gocryptfs.

### 💡 Полезное
* [MacType.](https://github.com/snowie2000/mactype) Альтернативный рендеринг шрифтов.
* [PowerToys.](https://github.com/microsoft/PowerToys) Приложение от Microsoft, что-то вроде сборника утилит всё-в-одном. Содержит [миллиард самой разной полезной хуйни,](https://github.com/microsoft/PowerToys#about) однозначно найдете применение для себя.
* [Sysinternals Suite.](https://learn.microsoft.com/en-us/sysinternals/downloads/sysinternals-suite) Ещё один набор мелких утилит. Можно скачать всё разом, [либо необходимое по отдельности.](https://learn.microsoft.com/en-us/sysinternals/downloads/sysinternals-suite#introduction)

## ✈️ Telegram
* [64Gram.](https://github.com/TDesktop-x64/tdesktop) Простой модифицированный клиент на основе официального [с небольшим количеством полезных дополнений.](https://github.com/TDesktop-x64/tdesktop/blob/dev/features.md)
* [Unigram.](https://github.com/UnigramDev/Unigram) UWP-клиент c Fluent дизайном. Анимации заметно подтормаживают, в целом юзабельный, но сильно уступает TGDesktop по удобству. 

## 📟 Discord:
### Моды

* [Связка Vencord + OpenAsar.](https://vencord.dev/) Широкая поддержка полезных плагинов и тем от сообщества, ускорение холодного старта программы и повышение общей производительности в Discord (в конфигурации OpenAsar можно выбирать режим производительности: для настольных ПК/при постоянном питании рекомендуется использовать Performance, в ином случае Balanced).

Установку производим через [инсталлер Vencord.](https://github.com/Vencord/Installer/releases/latest/download/VencordInstaller.exe) Важно: сохраните его в любом удобном для Вас месте. Иногда Vencord (и реже OpenAsar) слетают после обновления Discord, в таком случае нужно заново запустить установщик и переустановить их кнопками **Install Vencord** или **Reinstall / Repair** и **Install OpenAsar.** Это восстановит моды со всеми вашими настройками, плагинами и темами.  
> [!WARNING]
> В последнее время участились случаи, когда Discord после холодного старта висит на сплеше и ни на что не реагирует, при том перезапуск приложения не помогает. Это происходит из-за Vencord. Запустите VencordInstaller и переустановите нужные модификации, после этого всё заработает. Кстати, иногда процесс установки OpenAsar немного тупит (например, жалуется на то, что процесс занят) – просто несколько раз подряд кликайте на установку и это действительно сработает. ¯\\\_(ツ)_/¯

### Плагины  

<sup>*(все перечисленные плагины сразу доступны в разделе Vencord → Plugins, их нужно только активировать)*</sup>

* [AlwaysTrust.](https://vencord.dev/plugins/AlwaysTrust) Убирает всплывающее окно о подозрительном сайте или файле.
* [AnonymiseFileNames.](https://vencord.dev/plugins/AnonymiseFileNames) Анонимизирует имя отправляемых файлов, присваивая им рандомное название.
* [AutomodContext.](https://vencord.dev/plugins/AutomodContext) Позволяет перейти к сообщениям, на которые срабатала автомодерация.
* [BetterGifAltText.](https://vencord.dev/plugins/BetterGifAltText) Меняет приписку *"GIF"* на теги GIF или имя файла.
* [BetterGifPicker.](https://vencord.dev/plugins/BetterGifPicker) По умолчанию открывает вкладку с избранными в меню выбора GIF.
* [BetterRoleContext.](https://vencord.dev/plugins/BetterRoleContext) Добавляет опции для копирования цвета роли, редактирования роли и просмотра иконки роли при нажатии ПКМ.
* [BetterSettings.](https://vencord.dev/plugins/BetterSettings) Добавляет альтернативное меню настроек с улучшенной анимацией перехода и размещением опций по категориям, доступное по нажатию ПКМ по шестерёнке.
* [BetterSessions.](https://vencord.dev/plugins/BetterSessions) Позволяет просматривать точное время у сессий, давать каждой сессии название и получать уведомления о новых сессиях.
* [BiggerStreamPreview.](https://vencord.dev/plugins/BiggerStreamPreview) Увеличивает превью стримов.
* [BlurNSFW.](https://vencord.dev/plugins/BlurNSFW) Размывает медиафайлы в каналах NSFW до тех пор, пока на них не наведён курсор.
* [CallTimer.](https://vencord.dev/plugins/CallTimer) Добавляет таймер продолжительности разговора в голосовые чаты.
* [ClearURLs.](https://vencord.dev/plugins/ClearURLs) Автоматически чистит трекеры в ссылках.
* [CopyUserURLs.](https://vencord.dev/plugins/CopyUserURLs) Добавляет пункт копирования прямой ссылки на пользователя в контекстное меню.
* [CrashHandler.](https://vencord.dev/plugins/CrashHandler) *Пытается* предотвратить вылеты приложения.
* [CtrlEnterSend.](https://vencord.dev/plugins/CtrlEnterSend) Позволяет использовать сочетание клавиш Ctrl+Enter для отправки сообщений.
* [CustomIdle.](https://vencord.dev/plugins/CustomIdle) Позволяет задать своё время до установки статуса *"Не активен"*, или совсем отключить его автоустановку.
* [DisableCallIdle.](https://vencord.dev/plugins/DisableCallIdle) Отключает автокик из звонка в ЛС или перемещение в АФК-канал на сервере при инактиве.
* [DontRoundMyTimestamps.](https://vencord.dev/plugins/DontRoundMyTimestamps) Округляет относительные метки времени в меньшую сторону.
* [EmoteCloner.](https://vencord.dev/plugins/EmoteCloner) Быстрое клонирование кастомного эмодзи/стикера на Ваш сервер.
* [Experiments.](https://vencord.dev/plugins/Experiments) Предоставляет доступ к разделу экспериментальных функций.
* [FakeNitro.](https://vencord.dev/plugins/FakeNitro) Подделывает некоторые функции Nitro (использование фейковых эмодзи/стикеров) и позволяет стримить в высоком качестве.
* [FavoriteEmojiFirst.](https://vencord.dev/plugins/FavoriteEmojiFirst) При :автозаполнении: выводит Ваши избранные эмодзи наверх.
* [FixCodeblockGap.](https://vencord.dev/plugins/FixCodeblockGap) Убирает пустой промежуток между блоком кода и текстом под ним.
* [FixSpotifyEmbeds.](https://vencord.dev/plugins/FixSpotifyEmbeds) Исправляет проблему с чрезмерной громкостью эмбедов Spotify, позволяя настраивать громкость.
* [FixYoutubeEmbeds.](https://vencord.dev/plugins/FixYoutubeEmbeds) Обходит блокировку отображения видео с YouTube в Discord.
* [ForceOwnerCrown.](https://vencord.dev/plugins/ForceOwnerCrown) Принудительно отображает корону рядом с ником владельца сервера.
* [FriendsSince.](https://vencord.dev/plugins/FriendsSince) Отображает дату добавления в друзья при открытии всплывающего окна пользователя.
* [GameActivityToggle.](https://vencord.dev/plugins/GameActivityToggle) Добавляет кнопку рядом с кнопками мута и заглушения для переключения отображения игровой активности.
* [GifPaste.](https://vencord.dev/plugins/GifPaste) Вместо моментальной отправки GIF, вставляет ссылку на неё в поле ввода. В результате отправленное сообщение выглядит идентично, при этом предотвращаются неудобные случаи с мисскликами.
* [GreetStickerPicker.](https://vencord.dev/plugins/GreetStickerPicker) Ручной выбор приветственного стикера по ПКМ.
* [HideAttachments.](https://vencord.dev/plugins/HideAttachments) Добавляет кнопку скрытия медиа и вложений на панель ввода.
* [IgnoreActivities.](https://vencord.dev/plugins/IgnoreActivities) Настройки отображения выборочных активностей.
* [iLoveSpam.](https://vencord.dev/plugins/iLoveSpam) Принудительно отображает сообщения, помеченные как потенциально нежелательные.
* [ImageZoom.](https://vencord.dev/plugins/ImageZoom) Приближение изображений и GIF через ЛКМ+колёсико мыши.
* [ImplicitRelationships.](https://vencord.dev/plugins/ImplicitRelationships) Отображает Ваши неявные отношения во вкладке "Друзья". Неявные отношения в Discord — это люди, с которыми Вы недавно взаимодействовали и у которых есть общий сервер с Вами. В таком случае, Discord предполагает, что Вы могли бы быть друзьями.
* [KeepCurrentChannel.](https://vencord.dev/plugins/KeepCurrentChannel) Пытается вернуть Вас в канал, в котором Вы находились до смены аккаунта или перезапуска Discord.
* [MaskedLinkPaste.](https://vencord.dev/plugins/MaskedLinkPaste) При вставке ссылки в выделенный текст, будет создана гиперссылка.
* [MessageLatency.](https://vencord.dev/plugins/MessageLatency) Помечает сообщения, отправка которых заняла более указанного количества секунд.
* [MessageLogger.](https://vencord.dev/plugins/MessageLogger) Временное сохранение удалённых сообщений и истории редактирования.
* [MoreUserTags.](https://vencord.dev/plugins/MoreUserTags) Больше тегов для вебхуков и ролей модерации (owner, admin, и другие).
* [MuteNewGuild.](https://vencord.dev/plugins/MuteNewGuild) Приглушает новые сервера, на которые Вы заходите.
* [MutualGroupDMs.](https://vencord.dev/plugins/MutualGroupDMs) Показывает общие группы в профиле пользователя.
* [NewGuildSettings.](https://vencord.dev/plugins/NewGuildSettings) Автоматически заглушает новые сервера и позволяет задать другие настройки по умолчанию.
* [NoBlockedMessages.](https://vencord.dev/plugins/NoBlockedMessages) Полное скрытие сообщений от заблокированных Вами пользователей.
* [NoF1.](https://vencord.dev/plugins/NoF1) Убирает вызов центра помощи по нажатию клавиши F1.
* [NoPendingCount.](https://vencord.dev/plugins/NoPendingCount) Убирает пинги от входящих запросов в друзья, запросах сообщений и предложениях Nitro.
* [NoProfileThemes.](https://vencord.dev/plugins/NoProfileThemes) Отключает кастомное оформление Nitro-профиля, приводя его к единому стилю с обычным.
* [NoReplyMention.](https://vencord.dev/plugins/NoReplyMention) Отключает пинги при ответах по умолчанию.
* [NoScreensharePreview.](https://vencord.dev/plugins/NoScreensharePreview) Отключает отправку превью Ваших стримов.
* [NoServerEmojis.](https://vencord.dev/plugins/NoServerEmojis) Убирает эмодзи сервера в меню :автозаполнения:.
* [NotificationVolume.](https://vencord.dev/plugins/NotificationVolume) Позволяет установить отдельную громкость для уведомлений и звуков в приложении.
* [NoTypingAnimation.](https://vencord.dev/plugins/NoTypingAnimation) Отключает анимацию точек при печати, которая нагружает процессор.
* [NoUnblockToJump.](https://vencord.dev/plugins/NoUnblockToJump) Позволяет переходить к сообщениям от пользователей, которых Вы заблокировали.
* [OnePingPerDM.](https://vencord.dev/plugins/OnePingPerDM) При получении нескольких сообщений от пользователя в ЛС, пройдёт только один звук уведомления.
* [OpenInApp.](https://vencord.dev/plugins/OpenInApp) Открывает ссылки на Spotify, Steam и Epic Games в соответствующих приложениях, а не в браузере.
* [PauseInvitesForever.](https://vencord.dev/plugins/PauseInvitesForever) Возвращает возможность бессрочно приостанавливать приглашения на сервер.
* [PermissionFreeWill.](https://vencord.dev/plugins/PermissionFreeWill) Отключает клиентские ограничения для управления правами доступа к каналам.
* [PermissionsViewer.](https://vencord.dev/plugins/PermissionsViewer) Просмотр разрешений, которыми обладает пользователь/канал/роль сервера.
* [PictureInPicture.](https://vencord.dev/plugins/PictureInPicture) Добавляет режим картинка-в-картинке для видео (рядом с кнопкой загрузки).
* [PlatformIndicators.](https://vencord.dev/plugins/PlatformIndicators) Добавляет индикаторы платформ к пользователям, которые онлайн (ПК, телефон, браузер).
* [QuickMention.](https://vencord.dev/plugins/QuickMention) Добавляет кнопку упоминания на панель ввода.
* [ReadAllNotificationsButton.](https://vencord.dev/plugins/ReadAllNotificationsButton) Добавляет кнопку "Read all", которая очищает висящие непрочитанные сообщения со всех серверов.
* [RelationshipNotifier.](https://vencord.dev/plugins/RelationshipNotifier) Уведомляет, если Вас удалили из друзей, Ваш запрос дружбы был отклонён, или Вы были удалены с сервера или группы.
* [ReplaceGoogleSearch.](https://vencord.dev/plugins/ReplaceGoogleSearch) Замена Google на иные поисковые системы.
* [ReplyTimestamp.](https://vencord.dev/plugins/ReplyTimestamp) Добавляет время ответа на сообщение.
* [RevealAllSpoilers.](https://vencord.dev/plugins/RevealAllSpoilers) Открывает все спойлеры в сообщении с помощью Ctrl+клик по одному из спойлеров или во всём чате с помощью Ctrl+Shift+клик.
* [ReverseImageSearch.](https://vencord.dev/plugins/ReverseImageSearch) Добавляет пункт поиска по картинке в контекстное меню изображений.
* [ReviewDB.](https://vencord.dev/plugins/ReviewDB) Позволяет оставлять отзывы о других пользователях в их профилях.
* [RoleColorEverywhere.](https://vencord.dev/plugins/RoleColorEverywhere) Добавляет цвет роли везде, кроме индикатора печати.
* [SearchReply.](https://vencord.dev/plugins/SearchReply) Добавляет кнопку "Ответить" для сообщений в поиске.
* [ShikiCodeblocks.](https://vencord.dev/plugins/ShikiCodeblocks) Красивое оформление блоков кода в стиле VSCode. Можно применять свои темы.
* [ShowAllMessageButtons.](https://vencord.dev/plugins/ShowAllMessageButtons) Включает отображение всех кнопок на панели действий сообщения без необходимости зажимать Shift.
* [ShowHiddenChannels.](https://vencord.dev/plugins/ShowHiddenChannels) Отображение каналов, к которым отсутствует доступ. Показывает участников (если это голосовой канал) и дату последнего сообщения.
* [ShowHiddenThings.](https://vencord.dev/plugins/ShowHiddenThings) Отображает различные скрытые и доступные только модераторам вещи, независимо от уровня прав пользователя.
* [ShowTimeoutDuration.](https://vencord.dev/plugins/ShowTimeoutDuration) Показывает, сколько времени осталось до окончания тайм-аута пользователя во всплывающей подсказке иконки тайм-аута, либо рядом с ней.
* [SilentMessageToggle.](https://vencord.dev/plugins/SilentMessageToggle) Добавляет кнопку беззвучной отправки сообщений на панель ввода (заменяет ручное добавление *@silent* перед каждым сообщением).
* [SilentTyping.](https://vencord.dev/plugins/SilentTyping) Скрывает статус о печати. Можно добавить переключатель справа от поля ввода.
* [SortFriendRequests.](https://vencord.dev/plugins/SortFriendRequests) Сортирует запросы в друзья по дате получения, отображает дату.
* [StreamerModeOnStream.](https://vencord.dev/plugins/StreamerModeOnStream) Автоматически включает режим стримера, когда Вы начинаете стрим в Discord.
* [Summaries.](https://vencord.dev/plugins/Summaries) Включает экспериментальную функцию "сводок" на каждом сервере. Отображает информативные сводки разговоров, сгенерированные искусственным интеллектом.
* [SuperReactionTweaks.](https://vencord.dev/plugins/SuperReactionTweaks) Позволяет настраивать лимит одновременно проигрываемых супер-реакций и ставить супер-реакцию по умолчанию.
* [Translate.](https://vencord.dev/plugins/Translate) Перевод сообщений через Google Переводчик.
* [TypingIndicator.](https://vencord.dev/plugins/TypingIndicator) Добавляет индикатор печати рядом с аватаркой канала.
* [TypingTweaks.](https://vencord.dev/plugins/TypingTweaks) Выводит аватарку и цвет роли в индикатор печати. Применимо в том числе, когда печатает несколько человек.
* [ValidReply.](https://vencord.dev/plugins/ValidReply) Исправляет ошибку, из-за которой сообщения о ссылках (ответах на них) отображаются как «Сообщение не может быть загружено».
* [ValidUser.](https://vencord.dev/plugins/ValidUser) Исправляет некорректное отображение пингов от незнакомых пользователей.
* [ViewRaw.](https://vencord.dev/plugins/ViewRaw) Копирование и просмотр любого сообщения в формате Raw.
* [UnlockedAvatarZoom.](https://vencord.dev/plugins/UnlockedAvatarZoom) Увеличивает лимит на увеличение изображения в инструменте обрезки при смене аватара.
* [VoiceMessages.](https://vencord.dev/plugins/VoiceMessages) Добавляет возможность отправки аудио в формате голосовых сообщений.
* [VoiceDownload.](https://vencord.dev/plugins/VoiceDownload) Добавляет кнопку скачивания голосовых сообщений.
* [VolumeBooster.](https://vencord.dev/plugins/VolumeBooster) Позволяет устанавливать громкость пользователя в звонке выше максимальной.
* [WhoReacted.](https://vencord.dev/plugins/WhoReacted) Отображает аватары пользователей в области реакций (как в Telegram).
* [YoutubeAdblock.](https://vencord.dev/plugins/YoutubeAdblock) Блокировка рекламы в YouTube при использовании активности Watch Together. Для блокировки используется AdGuard.

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
* [Volume Percentage.](https://github.com/daksh2k/Spicetify-stuff/blob/master/EXTENSIONS.md#volume-percentage) Добавляет отображения громкости в процентах рядом с ползунком на панели плеера.
* [Immersive View.](https://github.com/ohitstom/spicetify-extensions/tree/main/immersiveView) Добавляет кнопку, скрывающую боковые панели, оставляя только текущую открытую страницу.
* [Scannables.](https://github.com/ohitstom/spicetify-extensions/tree/main/scannables) Сканируемые коды Spotify с мобильной версии клиента, открываются через контекстное меню.
* [Image Opener.](https://github.com/Tetrax-10/Spicetify-Extensions/tree/master/Image-Opener) Добавляет возможность открыть картинку с аватарки/облокжи/баннера в полном размере.
* [Show The Genres.](https://github.com/Delusoire/spicetify-extensions/tree/main/extensions/show-the-genres) Отображает общие жанры, присущие работам воспроизводимого артиста, в панели плеера.
* [Copy Lyrics.](https://github.com/Aimarekin/Aimarekins-Spicetify-Extensions/tree/main/copy-lyrics) Возможность копировать текст песен в режиме Караоке.
* [Copy to Clipboard.](https://github.com/pnthach95/spicetify-extensions) Позволяет копировать название песен.
* [Seek on scroll.](https://github.com/SunsetTechuila/seekonscroll) Перемотка трека колёсиком мыши по таймлайну.
* [Spicetify Stats.](https://github.com/harbassan/spicetify-stats) Отображение статистики, как в [volt.fm.](https://volt.fm) Установка производится [вручную.](https://github.com/harbassan/spicetify-stats#manual-installation)  

2. [SpotX](https://github.com/amd64fox/SpotX) (отключение рекламы для пользователей без Premium и активация экспериментальных функций; установка либо [автоматическая,](https://raw.githack.com/amd64fox/SpotX/main/Install_New_theme.bat) либо через выбор необходимых флагов [вручную](https://github.com/amd64fox/SpotX/discussions/60)). Не рекомендуется использовать вместе со Spicetify.

### Полезное

* [volt.fm.](https://volt.fm) Сервис сбора и анализа статистики вашего прослушивания. Предоставляет огромное количество полезных данных по жанрам, категориям, промежуткам времени.  
* [Google-таблица с прямыми ссылками на загрузку оффлайн-установщика всех версий Spotify для Windows.](https://docs.google.com/spreadsheets/d/1wztO1L4zvNykBRw7X4jxP8pvo11oQjT0O5DvZ_-S4Ok)
* [Скрипт блокировки обновлений настольного клиента Spotify.](https://github.com/amd64fox/Rollback-Spotify)
* [Полное удаление клиента Spotify из системы.](https://github.com/amd64fox/Uninstall-Spotify)

## 🔧 CLI-утилиты
>
> [!NOTE]
> Для удобства использования рекомендуется прописать путь к .exe файлу приложения (или к папке, хранящей исполнямые файлы всех приложений) в переменные среды PATH. [Как это сделать](https://remontka.pro/add-to-path-variable-windows/)  
Либо установить эти утилиты через Winget/Chocolatey/Scoop (рекомендуется!).  

* [aria2c.](https://aria2.github.io/) Аналог wget, Download Master и прочих. Поддерживает торренты.
* [ffmpeg.](https://ffmpeg.org/) Конвертер аудио и видео файлов, имеет много фич.
* [yt-dlp.](https://github.com/yt-dlp/yt-dlp) Загрузчик видео и аудио с YouTube, SoundCloud, PornHub и еще [с 1838 сайтов.](https://github.com/yt-dlp/yt-dlp/blob/master/supportedsites.md) Рекомендуется использовать через Hitomi Downloader (см. ниже в разделе Полезное).
* [payload-dumper-go.](https://github.com/ssut/payload-dumper-go) Быстрая разборка payload.bin Android-прошивок на отдельные образы.
* [Revancify.](https://github.com/decipher3114/Revancify#installation) Удобная сборка и установка ReVanced/ReVanced Extended через Termux.
* [Chocolatey.](https://community.chocolatey.org/) Пакетный менеджер для Windows в стиле линуксовских apt/pacman. Мощнее встроенного Winget.
* [Scoop.](https://scoop.sh/) Аналог Chocolatey. В отличии от последнего, устанавливает программы не в систему, а в отдельную папку юзера, некие "полу-портативные" версии, которые потом легко удалить. Из минусов: ОЧЕНЬ медленный cli-поиск.

## ⏹ Скрипты
* [OfflineInsiderEnroll.](https://github.com/abbodi1406/offlineinsiderenroll) Доступ к Windows Insider Program без аккаунта Microsoft.
* [Platform Tools Installer.](https://github.com/SunsetTechuila/Platform-Tools-Installer) Скрипт автоматически скачивает актуальные [Platform tools](https://developer.android.com/tools/releases/platform-tools) для вашей OC, предлагает выбрать место для распаковки, после чего добавляет их в PATH.

## 🗂 Модификация интерфейса Windows через .reg-файлы
* [Скрыть стрелку с ярлыков на рабочем столе.](https://www.elevenforum.com/t/remove-shortcut-arrow-icon-in-windows-11.3814/) Перемещаем файл Blank.ico в корневую папку Windows и запускаем RemoveArrow.bat; перезагружаем Проводник. Чтобы откатить изменения, запускаем RestoreArrow.bat.

## ⚒️ Решение проблем
* 🔵 Регулярные отвалы Bluetooth и подключенных устройств:  
Перейдите в Диспетчер устройств → разверните категорию «Bluetooth» → найдите ваш Bluetooth-адаптер (например, Intel® Wireless Bluetooth®) и откройте его параметры → перейдите в раздел «Управление электропитанием» → снимите галочку с «Разрешить отключение этого устройства для экономии энергии» и сохраните изменения. Устройства автоматически переподкючатся.
* 📶 Отвал Wi-Fi при использовании дискретной видеокарты:  
Перейдите в Диспетчер устройств → разверните категорию «Сетевые адаптеры» → найдите ваш адаптер Wi-Fi (например, Intel® Wireless-AC 9560 – кстати, чаще всего указанная проблема возникает именно с ним) и откройте его параметры → перейдите в раздел «Дополнительно» → найдите параметры «Ширина канала для 2,4 ГГц» и «Ширина канала для 5 ГГц». Для обоих параметров, в выпадающем меню задайте значение **20 МГц.** Сохраните изменения.
* 🔐 BitLocker запрашивает пароль после полного выключения компьютера/неожиданного завершения работы:  
Вероятно, BitLocker не сохранил ключ в TPM вашего компьютера (так случилось у меня). В любом случае, стоит попробовать перезаписать его:
  * Запустите Терминал от имени администратора и выполните команду `manage-bde -protectors -delete c: -t TPM`. Это очистит уже имеющуюся запись, если она существует.
  * Перезапишите ключ с помощью команды `manage-bde -protectors -add c: -tpm`. **Выключите компьютер через «Завершение работы»,** а не перезагрузкой, и проверьте дефект снова.