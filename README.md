**Подборка полезного софта**  
<sup>[от участников /b/egonia community](https://t.me/begoniacommunity) :heartpulse:</sup> 

> [!NOTE]
> Последнее обновление: 11 октября 2023.

> В текущем виде, текст составлялся пользователями с упором на Windows и Android. Под другие платформы перечисленного ниже софта может не быть.  

# :window: Windows  
> [!NOTE]
> [Перманентная активация Windows 10-11 с серверной привязкой по железу:](https://github.com/massgravel/Microsoft-Activation-Scripts) открываем PowerShell, запускаем команду `irm massgrave.dev/get | iex`, выбираем **[1] HWID.** Готово.  
* [SophiApp.](https://github.com/Sophia-Community/SophiApp) Для тонкой подстройки рабочего окружения под себя. Использует только то, что реализуемо путём задокументированного разработчиками Windows функционала. Никакого пердолинга.
* [VCRHyb64.](https://t.me/begoniacommunity/1310689) Сборник всех устанавливаемых Visual C++ Redistributable 2005-2022, устаналиваются сразу версии x86/x64.
* [.NET Runtime](https://dotnet.microsoft.com/en-us/download/dotnet-framework) и [VCLibs.](https://learn.microsoft.com/ru-ru/troubleshoot/developer/visualstudio/cpp/libraries/c-runtime-packages-desktop-bridge#how-to-install-and-update-desktop-framework-packages) Порой нужные зависимости. 
* [Windows Terminal.](https://github.com/microsoft/terminal/) Терминал от Microsoft с широкой кастомизацией, поддерживает любые виды консолей, будь то cmd, PowerShell или WSL. Сразу ставьте как приложение для командной строки по умолчанию. 
* [Ventoy.](https://www.ventoy.net/en/index.html) Софт для создания установочных, мульти/загрузочных флешек. Крайне прост в использовании: достаточно в один клик установить загрузочный раздел, а затем в автоматически созданный пустой раздел положить загрузочный(-е) .iso-образ(-ы). Работает с MBR и GPT (с последним не всегда стабильно).
* [Netboot.](https://netboot.xyz/) PXE-загрузчик различных установщиков/LiveCD-шек систем. Сложнее варианта выше.
* [WSABuilds.](https://github.com/MustardChef/WSABuilds) Подсистема Windows для Android, увидевшая свет с выходом Windows 11. Репозиторий содержит сборки как для Windows 11, так и 10. Есть вариации с OpenGApps/MindTheGApps, Magisk/KernelSU. И вырезан бесполезный Amazon Store, конечно. Установка проста даже для ёжика — распаковать архив и запустить Run.bat. Мастхэв, ёпта
* *(Windows 10)* [TrayVolumeControl.](https://github.com/krlvm/TrayVolumeControl) Регулировка громкости колёсиком мыши при наведении курсора на иконку громкости. Быстро привыкаешь и без этого становится неудобно, советую.
* *(Windows 10/11 <22H2)* [EarTrumpet.](https://eartrumpet.app/) Альтернативное меню управления звуком для панели задач. Основная польза в наличии микшера громкости приложений под общим ползунком громкости. Переключение источника звука через ПКМ по иконке. Так же по умолчанию есть регулировка громкости колёсиком по наведении на иконку, соответственно программа выше не нужна.
* *(Windows 10)* [BeautySearch.](https://github.com/krlvm/BeautySearch) Хорошая и красивая модификация для интерфейса поиска. Преимущества указаны на странице программы, они настраиваются вручную при установке.
* *(Windows 11)* [MicaForEveryone.](https://github.com/MicaForEveryone/MicaForEveryone) Кастомизация внешнего вида окон Win32-приложений. Рекомендации: проставить всё на "По умолчанию" в разделе "Глобальное правило", в дальнейшем создавая для каждой программы отдельный конфиг. Цвет заголовка окна выбирайте в соответствии с темой приложения; фон на Tabbed; включить "Расширить рамку окна в клиентскую область". 
* *(Windows 11)* [StartAllBack.](https://t.me/repack_me_clone) Незаменимый софт для комфортного перехода с Windows 10 на 11. Можно использовать пресет "Правильная 11", либо настроить всё вручную. Нормальная панель задач, улучшенный тёмный режим и акцентный цвет для Win32-элементов, акриловый фон для классического контекстного меню, регулировка громкости колёсиком мыши и другое. Пробуйте.
  - Экспериментальная функция, добавляющая Mica для шапки и акрил для контекстных меню внутри сторонних программ. Включается через Win+R командой `startisbackcfg /magic`. Отключается так же.
* [MSEdgeRedirect.](https://github.com/rcmaehl/MSEdgeRedirect) Кастомизация для панелей новостей, погоды и смена стандартного браузера для переадресации из поиска в системе.
* [SKTimeStamp.](https://tools.stefankueng.com/SKTimeStamp.html) Добавляет раздел для точного изменения времени создания/модификации/открытия через свойства файла в Проводнике.
* [SuperF4.](https://github.com/stefansundin/superf4/releases/download/v1.4/SuperF4-1.4.exe) Принудительно закрывает зависшее окно (останавливает его процесс) по сочетанию клавиш Ctrl+Alt+F4 вместо стандартного сочетания Alt+F4, которое в таких случаях не помогает.
* [Monitorian.](https://apps.microsoft.com/store/detail/monitorian/9NW33J738BL0) Изменение яркости внешних мониторов через Windows.
* [PowerToys.](https://github.com/microsoft/PowerToys) Приложение от Microsoft, что-то вроде сборника утилит всё-в-одном. Содержит миллиард самой разной полезной хуйни, однозначно найдете применение для себя.
* [Sysinternals Suite.](https://learn.microsoft.com/en-us/sysinternals/downloads/sysinternals-suite) Ещё один набор мелких утилит. Можно скачать всё разом, [либо необходимое по отдельности.](https://learn.microsoft.com/en-us/sysinternals/downloads/sysinternals-suite#introduction)
* [RustDesk (Windows.)](https://rustdesk.com/) Свободная альтернатива AnyDesk/TeamViewer. Возможен селфхост, но отлично работает и на бесплатных серверах из Германии и Киева.
* [ShareX.](https://getsharex.com/) Лучший скрин-шотер/рекордер для Windows. Вкратце: мега кастомизируемая прога с полностью открытым исходным кодом. Удобный, точный выбор области записи/снимка, есть широкий выбор инструментов для редактирования скриншота, умеет записывать экран с использованием NVENC, автоматически конвертировать записанное видео в GIF, опционально выгружать скриншоты на всевозможные имейдж-аплоадеры выборочно в пару кликов. Всё управление через хоткеи. Абсолютный мастхэв.
* [Okular.](https://okular.kde.org/ru/) Универсальная читалка от KDE для форматов PDF, EPub, Tiff [и подобных.](https://okular.kde.org/ru/formats/)
* [WingetUI.](https://github.com/marticliment/WingetUI) Графический интерфейс управления пакетным менеджером winget. Из наболее очевидных удобств, автоматическое/выборочное обновление всего установленного софта на ПК через winget. Советуем попробовать начать пользоваться этим. 
* [WinPaletter.](https://github.com/Abdelrhman-AK/WinPaletter) Редактор внешнего окружения Windows. Относительно не костыльный, потому можем рекомендовать к эксплуатации. Но всё же, будьте аккуратны.
* [Alternative A2DP Driver.](https://www.bluetoothgoodies.com/a2dp/) Незаменимая вещь для владельцев Bluetooth-наушников с поддержкой HiRes кодеков aptX HD и LDAC/LDHC. По умолчанию, Windows умеет работать только с AAC (Windows 11)/SBC кодеками, что существенно режет качество воспроизводимого аудио. Данная программа действительно панацея, но... Внимание: платно! Есть пробный период, в течение которого доступен весь функционал. Проверьте совместимость с вашими наушниками, затем либо программа прекращает работу, либо вами покупается перманентная лицензия с привязкой по железу — $5.99. В рублях, на момент написания текста, это ~850 руб. оплатой через карту, [приобретённую на Plati.market.](https://plati.io/itm/1065234)
* [EqualizerAPO.](https://sourceforge.net/projects/equalizerapo/) Лучший эквлайзер для Windows, легко устаналивается и не вредит системе. Имеет широкий спектр различных настроек, возможность сохранять/применять пресеты для разных параметров.
* [HandBrake.](https://handbrake.fr/) Энкодинг видео по различным критериям.
* [Uninstall Tool.](https://t.me/repack_me_clone) Расширенное удаление программ вместе с их "хвостами". Можно опционально выбрать установку сервиса, который будет отслеживать установки и собирать точную информацию про инсталляцию любого софта в систему. 
* [Free Download Manager.](https://www.freedownloadmanager.org/ru/) Удобный менеджер загрузок. 
* Ну и конечно база: свободный архиватор [7-Zip,](https://www.7-zip.org/) [Process Hacker 2](https://processhacker.sourceforge.io/downloads.php) (обязательно в полном режиме установки), [Notepad++,](https://notepad-plus-plus.org/downloads/) [qBittorrent,](https://www.fosshub.com/qBittorrent.html) [Mp3tag,](https://www.mp3tag.de/en/download.html) [Rufus.](https://www.mp3tag.de/en/download.html)

# :globe_with_meridians: Браузеры и дополнения к ним
**Браузеры:**  
to be filled... *юзайте Edge ( ͡° ͜ʖ ͡°).* А вообще, этот моментик уж *слишком* индивидуальный, потому ищите наиболее близкий себе вариант сами.

**Расширения:**
* [uBlock Origin.](https://ublockorigin.com/ru) Самый популярный свободный блокировщик рекламы. В представлении не нуждается.  
Фильтры для uBlock (рунет):
> Файл (фильтр) не нужно скачивать. Его надо добавить в лист фильтров расширения, чтобы поддерживались автообновления.  

(RU AdList: BitBlock) `https://easylist-downloads.adblockplus.org/bitblock.txt`  
(RU AdList: Counters) `https://easylist-downloads.adblockplus.org/cntblock.txt`
* [AdGuard.](https://adguard.com/ru/welcome.html) Тоже самое, что выше, но с более интуитивным интерфейсом.
* [SponsorBlock.](https://sponsor.ajay.app/) Автоматически пропускает любые рекламные секции в видео на YouTube. Полностью community-powered, вы можете сами добавлять метки и загружать рекламные секции для пропуска по своему усмотрению.
* [Track24.](https://chrome.google.com/webstore/detail/track24ru/lfijgegefgcgbfcgjgnhnkclenhfijhk?hl=ru) Удобное расширение для отслеживания посылок в браузере.
* [Tampermonkey.](https://www.tampermonkey.net/index.php?locale=ru) Реализация работы пользовательских скриптов в вашем браузере. 
* [ClearURLs.](https://chrome.google.com/webstore/detail/clearurls/lckanjgmijmafbedllaakclkaicjfmnk) Автоматически очищает URL страницы от трекинг-содержимого.
* [Voice-Over-Translation.](https://raw.githubusercontent.com/ilyhalight/voice-over-translation/master/dist/vot.user.js) Автоматический закадровый перевод видео в реальном времени, свободный "порт" из Яндекс Браузера. Для работы нужен Tampermonkey! *Нажмите на название расширения, чтобы установить.*
* [Dark Reader.](https://chrome.google.com/webstore/detail/dark-reader/eimadpbcbfnmbkopoojfekhnkhdbieeh?hl=ru) Хорошее расширения для автоматической перекраски сайтов в тёмные тона. Единственное неудобство: нужно вручную отключать его работу для сайтов, где темная тема уже предусмотрена разработчиками, расширение не умеет определять это самостоятельно. В остальном маст-хев, множество настроек.
* [Search by Image.](https://chrome.google.com/webstore/detail/search-by-image/cnojnbdhbhnkbcieeekonklommdnndci) Приятный интерфейс, большое количество сервисов для поиска, можно добавлять свои. Небольшой дополнительный функционал. Пробуйте.
* [Bing AI Plus.](https://github.com/patrik-martinko/app-bing-ai-plus) Позволяет модифицировать внешний вид страницы чатбота, снимает ограничение на количество символов.
* [User-Agent Switcher and Manager.](https://chrome.google.com/webstore/detail/user-agent-switcher-and-m/bhchdcejhohfmigjafbampogmaanbfkg) Позволяет быстро подменить useragent вашего девайса.
* [Old Genius (Song Page Switcher).](https://chrome.google.com/webstore/detail/old-genius-song-page-swit/dgdnchkkkknfdahaehnkfifchgnoidjj) Автоматически и без задержек (релоада) возвращает старую версию дизайна страницы текста на Genius.com.
* [Web Archives.](https://chrome.google.com/webstore/detail/just-black/aghfnjkcakhmadgdomlmlhhaocbkloab?hl=ru) Быстрый переход к сохранённым копиям сайта/его версиям на archive.org (Wayback Machine).
* [Enable Right Click & Copy.](https://chrome.google.com/webstore/detail/absolute-enable-right-cli/jdocbkpgdakpekjlhemmfcncgdjeiika) Добавляет возможность выделять и копировать текст/контент на сайтах, которые это блокируют. Параметр Enable Copy разрешает копировать текст; Absolute Mode отключает защиту от копирования любого контента.

**Темы:**
* [Just Black.](https://chrome.google.com/webstore/detail/just-black/aghfnjkcakhmadgdomlmlhhaocbkloab?hl=ru) Простая и минималистичная тема в тёмных тонах от Google.  

# :notes: Spotify
**Полезное:**
* [volt.fm.](https://volt.fm) Сервис сбора и анализа статистики вашего прослушивания. Предоставляет огромное количество полезных данных по жанрам, категориям, промежуткам времени.  
* [Google-таблица с прямыми ссылками на загрузку оффлайн-установщика всех версий Spotify для Windows.](https://docs.google.com/spreadsheets/d/1wztO1L4zvNykBRw7X4jxP8pvo11oQjT0O5DvZ_-S4Ok/edit?pli=1#gid=0)
* [Скрипт блокировки обновлений настольного клиента Spotify.](https://github.com/amd64fox/Rollback-Spotify)
* [Полное удаление клиента Spotify из системы.](https://github.com/amd64fox/Uninstall-Spotify)

**Для ПК:**
1. [Spicetify](https://github.com/spicetify/spicetify-cli) (рекомендуется):
   - [Сразу устанавливаем Spicetify с Маркетплейсом одной командой.](https://github.com/spicetify/spicetify-marketplace/wiki/Installation)  
     Дальнейшая установка производится в основном только через меню Маркетплейса → Расширения. Этот метод установки подразумевает дальнейшее автоматическое обновление расширений по мере поступления апдейтов.
   - Установка Spicetify добавляет меню экспериментальных функций клиента (не меняя ничего по умолчанию). Используйте осторожно!  
   - Для пользователей без Premium-подписки → [Adblock.](https://github.com/CharlieS1103/spicetify-extensions/blob/main/adblock/README.md)

**Темы:**
* [Bloom.](https://github.com/nimsandu/spicetify-bloom) Качественная тема для Spotify в стиле Fluent Design из Windows 11. На данный момент находится в процессе глобального обновления. Когда будет готово — смело рекомендуем к установке.
* [Comfy.](https://github.com/Comfy-Themes/Spicetify) Минималистичная тема с большим количеством цветовых пресетов и настроек.
* [Ziro.](https://github.com/schnensch0/ziro) Простая, очень плоская тема.  

**Расширения и приложения:**
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
* [Playing Source.](https://github.com/Aimarekin/Aimarekins-Spicetify-Extensions/tree/main/playing-source) Отображение источника воспроизведения (плейлист/радио/из карточки артиста etc.) при наведении на обложку.
* [Play on YouTube.](https://github.com/Tetrax-10/Spicetify-Extensions/tree/master/Play-on-YouTube) Автоматически открывает поисковой запрос с названием трека/открывает непосредственно трек (используя ваш ключ API YouTube, читайте на странице расширения).
* [Copy to Clipboard.](https://github.com/pnthach95/spicetify-extensions) Позволяет копировать название песен.
* [Seek on scroll.](https://github.com/SunsetTechuila/seekonscroll) Перемотка трека колёсиком мыши по таймлайну.
* [Spicetify Stats.](https://github.com/harbassan/spicetify-stats) Отображение статистики, как в [volt.fm.](https://volt.fm) Установка производится [вручную.](https://github.com/harbassan/spicetify-stats#manual-installation)  

2. [SpotX](https://github.com/amd64fox/SpotX) (отключение рекламы для пользователей без Premium и активация экспериментальных функций; установка либо [автоматическая,](https://raw.githack.com/amd64fox/SpotX/main/Install_New_theme.bat) либо через выбор необходимых флагов [вручную](https://github.com/amd64fox/SpotX/discussions/60)).  

**Для Android:**
1. [XManager.](https://t.me/xManagerUpdates) Лучший мод оригинального клиента Spotify. Подойдёт как для non-premium, так и для Premium-аккаунтов. В случае с первыми, мод отключает всю аудио и визуальную рекламу, оставляя лишь серверные ограничения на качество воспроизводимого аудио и необходимость в релогине каждые 2 недели (если вы из России). Для обоих типов пользователей будет полезна активация экспериментального режима (значок колбочки сверху в приложении XManager) с большим количеством новых и полезных функций. 

# :airplane: Telegram
**Для ПК:**
* [AyuGram.](https://github.com/AyuGram/AyuGramDesktop) Добавлен полноценный режим невидимки, нечиталки и неписалки. Можно включить "локальный" Telegram Premium (активация функций, не требующих серверного подтверждения); отключить рекламу, истории. Сохраняются удалённые сообщения, история редактирования сообщений во всех чатах; отображение ID профиля, чата или канала.

**Для Android:**  

**Клиенты:**
* [exteraGram.](https://t.me/exteraGram) Актуальный клиент Telegram с большим количеством приятных мелочей и опрятными внешними аддонами от адекватного разработчика. Добавлена поддержка CameraX для видеокружков, редизайн встроенного аудиоплеер, есть подстройка закругления элементов, Monet-оформление для устройств с Android 12>, свой набор иконок посреди UI, увеличение скорости загрузки/выгрузки файлов и другие функции/дополнения. Обновляется намного чаще [в beta-канале](https://t.me/exteraGramCI) (при том работает не хуже стабильной).
* [AyuGram.](https://github.com/AyuGram/AyuGram4A) Форк exteraGram с функциями из одноимённого настольного клиента. Дополнительно можно выделить разрешенные скриншоты в секретных чатах и сохранение чатов, из которых вы были исключены. [Обновления здесь.](https://t.me/ayugramchat/1238)
* [Nekogram.](https://github.com/Nekogram/Nekogram) А почему бы и нет? Добротный старейший клиент с регулярными обновлениями. Имеет небольшой, "классический" набор дополнительного функционала.  

**Модули:**
* [Killergram.](https://github.com/AetherMagee/Killergram) Модуль для LSPosed, совместим [с почти всеми клиентами.](https://github.com/AetherMagee/Killergram#support-clients) Убирает рекламу из каналов, снимает лимит на количество аккаунтов и разрешает локальное копирование контента из чатов и каналов, где это запрещено.

# :pager: Discord
**Моды:**
* [Связка Vencord + OpenAsar.](https://vencord.dev/) Существенное улучшение скорости запуска, производительности и плавности в Discord. Широкая поддержка плагинов, ускоренное применение любых тем и облачное сохранение настроек.  

Установку производим через инсталлер Vencord. Сохраните его в любом удобном для вас месте. Иногда Vencord и OpenAsar слетают после обновления Discord, в этом случае нужно заново запустить установщик и выбрать Reinstall / Repair (это восстановит Vencord), затем Install OpenAsar.  
> [!NOTE]
> В конфигурации OpenAsar можно выбирать режим производительности. Для настольных ПК/при постоянном питании рекомендуется использовать Performance, в ином случае Balanced. 

**Плагины:**  
<sup>*(все перечисленные плагины сразу доступны в разделе Vencord → Plugins, их нужно только активировать)*</sup>
* AlwaysTrust. Убирает назойливое всплывающее окно о подозрительном сайте/файле.
* AnonymiseFileNames. Анонимизирует имя отправляемых файлов.
* BetterAltGifText. Меняет приписку *"GIF"* на GIF-теги/имя файла.
* BiggerStreamPreview. Увеличивает превью стримов.
* CallTimer. Добавляет счетчик времени в голосовых чатах.
* ClearURLs. Удаляет следы трекеров из ссылок.
* CopyUserURLs. Добавляет пункт копирования ссылки на пользователя.
* CrashHandler. Пытается предотвратить вылеты приложения.
* DisableDMCallIdle. Отключает автокик из голосового канала после трёхминутного отсутствия активности.
* EmoteCloner. Быстрое клонирование кастомного эмодзи/стикера на ваш сервер.
* Experiments. Предоставляет доступ к вкладке с экспериментальными функциями.
* FakeNitro. Подделывает некоторые функции Nitro (использование фейковых эмодзи/стикеров) и позволяет стримить в высоком качестве.
* FavoriteEmojiFirst. Выводит любимые эмодзи на первое место в автозаполнении.
* ForceOwnerCrown. Принудительное отображение короны у владельца сервера.
* GifPaste. Вместо моментальной отправки GIF, вставляет ссылку на неё в поле ввода.
* GreetStickerPicker. Ручной выбор приветственного стикера.
* HideAttachments. Добавляет кнопку для скрытия медиа и вложений на панель действий сообщений.
* IgnoreActivities. Выборочная настройка отображения разных активностей.
* iLoveSpam. Отображает сообщения, которые Discord может расценить как *потенциально нежелательные.*
* ImageZoom. Позволяет приближать изображения и GIF.
* MessageClickActions. Быстрые действия с сообщениями. *Backspace+клик* удалит сообщение, а *Backspace+двойной клик* позволяет отредактировать/ответить на сообщение.
* MessageLogger. Сохранение удалённых и отредактированных сообщений.
* MoreUserTags. Больше тегов для вебхуков и ролей модерации. (staff, mod, и т. д.)
* MuteNewGuild. Автоматически заглушает новые сервера, на которые вы заходите.
* MutualGroupDMs. Показывает общие группы в профиле пользователя.
* NoBlockedMessages. Полное скрытие сообщений от заблокированных пользователей.
* NoF1. Отключает вызов центра помощи при нажатии клавиши *F1.*
* NoProfileThemes. Отключает кастомное оформление Nitro-профиля, приводя его к единому стилю с обычным.
* NoScreensharePreview. Полная противоположность плагину *BiggerStreamPreview.* Отключает превью стримов.
* NoUnblockToJump. Отключает обязательную разблокировку пользователя для перехода на его сообщения.
* OnePingPerDM. При нескольких сообщениях от одного пользователя в ЛС будет звучать лишь одно аудио-оповещение.
* OpenInApp. Открывает ссылки Spotify, Steam и Epic Games в соответствующих приложениях, а не в браузере.
* PermissionsViewer. Просмотр разрешений, которыми обладает пользователь/канал/роль сервера.
* PictureInPicture. Добавляет режим *"картинка в картинке"* для видео (рядом с кнопкой загрузки).
* PlatformIndicators. Добавляет индикаторы платформ. (ПК, Телефон, Браузер...)
* QuickMention. Добавляет кнопку упоминания на панель действий сообщений.
* ReadAllNotificationsButton. Позволяет прочитать уведомления со всех серверов одной кнопкой.
* RelationshipNotifier. Уведомляет, если друг удаляет вас из друзей, если ваш запрос в друзья был отклонён, или если вы были удалены с сервера/группы.
* RevealAllSpoilers. Открывает все спойлеры в сообщении с помощью *Ctrl+клик* по одному из спойлеров или в чате с помощью *Ctrl+Shift+клик.*
* ReverseImageSearch. Что-то делает... Но даже я не справился с задачей выяснить, что именно :)
* RoleColorEverywhere. Добавляет цвет роли везде, где только возможно (кроме индикатора печати, см. *TypingTweaks*).
* SearchReply. Добавляет кнопку *"ответить"* для сообщений в поиске.
* ServerListIndicators. Отображает количество серверов или друзей онлайн над списком серверов.
* ShikiCodeblocks. Красивое оформление блоков кода в стиле VSCode. Можно поставить свою тему.
* ShowAllMessageButtons. Принудительно показывать все кнопки на панели действий сообщений.
* ShowHiddenChannels. Показывать каналы, к которым отсутствует доступ. Показывает участников (если это голосовой канал), и дату последнего сообщения в канале.
* ShowTimeouts. Отображает в чате иконки тайм-аута пользователей независимо от прав доступа.
* SilentMessageToggle. Добавляет кнопку на панель чата для переключения отправки *"тихого"* сообщения. По сути заменяет ручное добавление *@silent* перед сообщением.
* SilentTyping. Скрывает статус о наборе сообщения. Можно включить переключатель справа от поля ввода сообщения.
* SortFriendRequests. Сортирует запросы в друзья по дате получания. Можно включить показ самой даты.
* Translate. Перевод сообщений с помощью Google Translate.
* TypingIndicator. Добавляет индикатор печати возле канала.
* TypingTweaks. Показ аватарок и цвета роли возле индикатора печати. Более информативное сообщение, если печатает несколько человек.
* ValidUser. Исправляет кривое отображение пингов незнакомых пользователей.
* ViewRaw. Копирование и просмотр *сырого* содержимого/данных любого сообщения, канала или сервера.
* VoiceMessages. Добавляет возможность отправки голосовых сообщений, как на мобильном приложении.
* VolumeBooster. Позволяет устанавливать громкость пользователя в звонке выше максимальной.
* WhoReacted. Отображает аватары пользователей, отреагировавших на сообщение.

**Темы:**
> [!IMPORTANT]
> Рекомендуем устаналивать темы через OpenAsar для моментального применения после запуска. Делается это через настройки → OpenAsar → Theming.  
> Порядок действий, как поставить тему, чтобы поддерживалось автообновление:
> 1. Перейдите в репозиторий нужной темы.
> 2. В поиск по репо введите `@import url`.
> 3. Найдите основной файл в формате .css, **который состоит только из импорта ссылки на ресурсы темы и настроек.** Если такого нет среди файлов самого репозитория, то поищите его в релизах.
> 4. Скопируйте содержимое файла в поле ввода раздела Theming.  

* [Dark Discord.](https://github.com/discord-modifications/dark-discord) Действительно *тёмная* тема. Простая и неброская. [Превью.](https://gibbu.github.io/ThemePreview/?file=https://discord-modifications.github.io/dark-discord/src/source.css) Прямая ссылка: `https://raw.githubusercontent.com/localip/dark-discord/main/DarkDiscord.theme.css`
* [Fluent Discord.](https://github.com/TakosThings/Fluent-Discord) Тема, выполненная под стиль Microsoft Fluent Design (как в Windows 11). [Превью.](https://raw.githubusercontent.com/TakosThings/Fluent-Discord/develop/images/ui-1.5.5.png)  
Можно заменить фон приложения на свой (в соответствии с обоями рабочего стола, например). Для этого замените содержимое в скобках параметра `--fluent-acrylic-background: url` на прямую ссылку к картинке.

# :musical_note: TikTok
> [!NOTE]
> Иногда TikTok ограничивает активность аккаунта после авторизации в моде, отключая возможность ставить лайки на медиа из ленты, профиля или из личных сообщений. Если это произошло — пройдёт через некоторое время, если вы используете мод с актуальной версией базы. На старых версиях этот функционал может быть частично или полностью отключен.
* [Chikutaku](https://t.me/thedise/1933) от [thedise.](https://thedise.me/) Основан на [revanced-patches](https://github.com/ReVanced/revanced-patches). **Можно подделать регион** в настройках приложения (по умолчанию установлено `us`<sup>*США*</sup>). Доступна подмена кода страны, кода мобильной сети и названия оператора. Отключена реклама любого вида (так же можно скрыть LIVE-эфиры/истории/фото из ленты). Включена перемотка (таймлайн) для всех роликов; скачивание видео/фото без водяного знака. Публикация видео без VPN не работает! Комментарии и лайки работают.
* [TikTok Mod от Jaggu.](https://t.me/tiktalkupdate) Обновляется реже и обновления бывают нестабильны (как, например, последняя на момент написания этого текста версия). Сборка, где работает публикация видео без VPN и с применением звука — [27.9.4.](https://t.me/tiktalkupdate/63) 

# :robot: Android
**Приложения:**
* [ReVanced Extended.](https://github.com/MatadorProBr/revanced-extended-magisk-module/releases) Включает в себя SponsorBlock, ReturnYoutubeDislikes. Есть как root, так и non-root версии. В том числе для клиента YouTube Music.
* [PurpleTV.](https://t.me/pubTw) Самая качественная модификация клиента Twitch (ранее называлась TwitchMod).
* [mcpro24fps.](https://t.me/mcpro24fps) Лучший бесплатный софт для профессиональной (и не очень) видеосъёмки на Android. К огромному удивлению, действительно удобнее и качественнее своих платных аналогов. Отмечу крайнюю легковесность (приложение весит меньше 2 МБ).
* [Anixart.](https://t.me/anixart) Лучший агрегатор аниме на мобильных устройствах.
* [Kotatsu.](https://github.com/KotatsuApp/Kotatsu) Приложение для чтения манги.
* [Seal.](https://github.com/JunkFood02/Seal) Загрузчик видео/аудио, использующий yt-dlp (можно включить aria2c). Очень удобный и простой в использовании. Выполнен в соответствии с MD3.
* [AdAway.](https://github.com/AdAway/AdAway) Блокировка рекламы через локальные hosts-файлы подключением к VPN (т.е. root-доступ не нужен). Готовые списки можно взять [здесь.](https://4pda.to/forum/index.php?showtopic=275091&st=8000#entry89665467)
> Рекомендуем добавить в разрешённые листы `firebase-settings.crashlytics.com`, `firebaseremoteconfig.googleapis.com` и *(опционально)* `firebaselogging.googleapis.com`. Эти адреса должны быть разблокированы для корректной работы некоторых приложений (например, Oldubil).  
* [NetGuard.](https://github.com/M66B/NetGuard/) Выборочная блокировка доступа к интернету для приложений и ограничение рекламы через hosts, как в приложении выше. Тоже не требует рут, так как работает через локальное VPN-подключение. [Активация Pro-функций.](https://4pda.to/forum/index.php?showtopic=700336&st=1820#entry113141886)
* [K-9 Mail.](https://k9mail.app/) Простой и свободный почтовый клиент.
* [Aves.](https://github.com/deckerst/aves) Свободная, очень красивая и функциональная галерея. Поддерживает огромное количество форматов фото/видео, расширенный поиск по медиатеке, сортировку по различным критериям и другие функции. 
* [Aegis (2FA-аутентификатор).](https://github.com/beemdevelopment/Aegis)  Поддерживает авто-создание бэкапов, вход по биометрии, [установку кастомных иконок](https://aegis-icons.github.io/) (либо своими изображениями) для внесённых сервисов.
* [Photok.](https://f-droid.org/packages/dev.leonlatsch.photok/) Хранение фотографий на устройстве под кодовой защитой с применением шифрования.
* [Cromite.](https://github.com/uazo/cromite) Форк Bromite [с большим количеством функций.](https://github.com/uazo/cromite#features)
* [Iceraven.](https://github.com/fork-maintainers/iceraven-browser) Форк Firefox на GeckoView с нормальной поддержкой расширений, чуть более широкой кастомизацией и доступом к флагам (about:config). 
* [HabitKit.](https://play.google.com/store/apps/details?id=com.roehl.habitkit&hl=en_US) Индивидуальный журнал-трекер вашей продуктивности.
* [Advanced Download Manager.](https://play.google.com/store/apps/details?id=com.dv.adm&hl=en_US) Менеджер загрузок с поддержкой торрентов.
* [Material Files.](https://f-droid.org/ru/packages/me.zhanghai.android.files/) Свободная альтернатива Google Files с расширенным функционалом. Поддерживает работу с FTP.
* *(Android 12<)* [Clipboard Cleaner.](https://f-droid.org/ru/packages/io.github.deweyreed.clipboardcleaner/) Выводит уведомления об операциях приложений/пользователя с буфером обмена, и тоггл в шторку для его очистки.
* [Memory Guardinan.](https://apt.izzysoft.de/fdroid/index/apk/ara.memoryguardian) Настройка автоочистки буфера обмена.
* [Total Commander.](https://www.ghisler.com/android.htm) Хороший файловый менеджер и архиватор.
* [Shizuku.](https://shizuku.rikka.app/) Предоставление повышенных прав приложениям через adb с помощью локального сервера.
* [Skit.](https://play.google.com/store/apps/details?id=com.pavelrekun.skit&hl=ru&gl=US) Менеджер установленных приложений. Умеет устанавливать сплит-пакеты, сохранять установленные приложения как .apk/сплит, быстро переходить к папкам с содержимым конкретных программ и другие функции.
* [Canta.](https://apt.izzysoft.de/fdroid/index/apk/org.samo_lego.canta) Деблоатер любых приложений, не треюует доступа к root (работает через Shizuku).
* [Obtainium.](https://github.com/ImranR98/Obtainium) Менеджер обновлений приложений из большого количества вручную настраиваемых истчоников (например GitHub, F-Droid или Huawei AppGallery, полезный для загрузки российских приложений).
* [F-Droid.](https://f-droid.org/ru/) Крупнейший каталог свободных (FOSS) приложений.
  * Рекомендуемые репозитории:  
`https://apt.izzysoft.de/fdroid/`
* [ForPDA.](https://f-droid.org/ru/packages/org.softeg.slartus.forpdaplus/) Альтернативный клиент для 4PDA, если оригинальный чем-то не устраивает.
* [QuickTiles.](https://f-droid.org/packages/com.asdoi.quicktiles/) Позволяет добавлять готовые или кастомные быстрые тогглы для панели управления. 
* [CellMapper](https://www.cellmapper.net/apps) & [NetMonster.](https://play.google.com/store/apps/details?id=cz.mroczis.netmonster&hl=ru&gl=US) Мониторинг качества и доступности мобильной сети (местоположение вышек и подобное).
* [Track24.](https://play.google.com/store/apps/details?id=net.track24.android&hl=ru&gl=US) Отслеживание посылок в виде сводки информации со всех международных источников.
* [AltoCar.](https://altocar.ru/) Агрегатор выгодных предложений такси для России.
* [Geometric Weather.](https://f-droid.org/packages/wangdaye.com.geometricweather/) Красивое и удобное приложение для погоды. Из минусов можно отметить слишком простенькие виджеты, в большинство "интерьеров" рабочего стола не впишутся.
* [Weather Today.](https://play.google.com/store/apps/details?id=com.kokoschka.michael.weather&hl=en&gl=US) Название говорит за себя, приложение выполнено в MD3-стиле, можно просматривать карту осадков с использованием таймлана.
* [DashchanFork.](https://github.com/TrixiEther/DashchanFork) Актуальная версия мобильного клиента для различных имиджбордов.
* [iChan.](https://github.com/Zchandev/iChan) Клиент имиджбордов 2ch и 4chan.
* *(Android 12+)* [Repainter.](https://repainter.app/) Приложения для тонкой настройки вашей Monet-темы. Требуется покупка подписки/единоразовой оплаты лицензии и root-права (за редким исключением ваша прошивка может поддерживать интеграцию с приложением, например, PixelOS/ProtonAOSP для Pixel 4).
* [PCAPdroid.](https://f-droid.org/ru/packages/com.emanuelef.remote_capture/) Инструмент мониторинга и записи сетевого трафика. Рут-права не для работы необязательны, ибо приложение может работать через локальное VPN-подключение.
* [Data Monitor.](https://github.com/itsdrnoob/DataMonitor) Статистика использования трафика приложениями.
* [NekoBox.](https://github.com/MatsuriDayo/NekoBoxForAndroid) Менеджер прокси.
* [inviZible Pro.](https://f-droid.org/packages/pan.alexander.tordnscrypt.stable/) Обход блокировок через сеть Tor и i2p, а также шифрование DNS-запросов с помощью DNSCrypt. 
> Для нормального запуска Tor, пройдите в быстрые настройки → Настройки Tor → Мосты → Запросить новый мост → выберите *obfs4* → введите капчу и подтвердите запрос, готово.  
* [DroidFS.](https://f-droid.org/packages/sushi.hardcore.droidfs/) Шифрование контента с использованием [gocryptfs](https://github.com/rfjakob/gocryptfs) или [CryFS](https://github.com/cryfs/cryfs) и управление им на устройстве.
* [EDS Lite.](https://f-droid.org/ru/packages/com.sovworks.edslite/) Создание и управление зашифрованными контейнерами (разделами) на Android.
* [Shortcut Maker.](https://play.google.com/store/apps/details?id=rk.android.app.shortcutmaker&hl=en_US) Приложение для создания ярлыков, но основное его применение, найденное сообществом — автоматическая генерация Monet-иконок для приложений, не поддерживающих это по умолчанию. Работает в 9/10 случаев. Либо можно выбирать иконки из стороннего иконпака. Анимации запуска/сворачивания ярлыка идентичные приложению, если у вас Android 12L+ с Pixel-подобным ланучером. Нужно вручную подобрать оптимальный размер иконки (например, для Pixel 4 это 92%).
* [MacroDroid.](https://www.macrodroid.com/) Автоматизация действий на Android.
* [Basic Call Recorder.](https://github.com/chenxiaolong/BCR) Простое приложение для записи звонков в разных форматах. Требуются root-права.
* [Samourai Wallet.](https://samouraiwallet.com/) Анонимный криптокошелёк не требующий идентификации личности.
* [KeePassDX.](https://github.com/Kunzisoft/KeePassDX) Локальное хранение паролей в зашифрованном файле с унифицированным форматом дата-баз для KeePass.
* [Translate You.](https://github.com/you-apps/TranslateYou) Свободное приложение-переводчик, выполненное в Material Design 3. [Поддерживает сразу несколько сервисов](https://github.com/you-apps/TranslateYou#supported-translation-engines) (из наиболее популярных можно выделить DeepL и Reverso).
* [ReadEra.](https://readera.org/ru) Читалка для всего: fb2, epub, pdf, мсоффис-документы и т.д.
* [Neo Backup.](https://f-droid.org/ru/packages/com.machiav3lli.backup/) Свободный бэкапер. Выборочное резервирование и восстановление одного или нескольких приложений. Работает только с root-правами.

**Модули для Magisk:**
* [ViPER4Android Repackaged.](https://github.com/programminghoch10/ViPER4AndroidRepackaged) Не требует никаких дополнительных манипуляций с любым устройством. Всё работает сразу после установки.
* [Basic Call Recorder.](https://github.com/chenxiaolong/BCR#readme) Простой рекордер звонков без ненужных фич. Поставил, включил и забыл.
* [LSPosed.](https://github.com/LSPosed/LSPosed) Наследник мощного фреймворка Xposed, позволяющего внедрять собственный код в приложения во время работы. Имеет встроенный репозиторий с большим количеством полезных модулей.
* [Zygisk Detach.](https://github.com/j-hc/zygisk-detach) Блокировка автообновления приложений через Google Play путём скрытия их наличия в системе от маркета. Мастхэв при установленном ReVanced rooted-методом.

# :information_source: Как скрыть root-доступ
> [!NOTE]
> Актуально на момент последнего редактирования для всех банковских и платёжных приложений в России.
1. Скачиваем app-release.apk из [Magisk Delta](https://github.com/HuskyDG/magisk-files/releases) и устанавливаем так же, как обычный.  
2. В настройках Magisk Delta пересобираем приложение с рандомным именем пакета, включаем Zygisk, защиту от Bootloop и пункт Unmount modules (ещё опционально можно включить биометрическую аутентификацию, для вашего удобства).  
3. Проходим в Configure unmount, находим в списке Сервисы Google Play, разворачиваем приложение и ставим галочки на `com.google.android.gms` и `com.google.android.gms.unstable`. Затем ставите галочки рядом с остальными нужными вам приложениями.  
4. Скачиваем и устанавливаем Zygisk-версию модуля [LSPosed,](https://github.com/LSPosed/LSPosed/releases) затем скачиваем и устанавливаем [Hide My Applist.](https://github.com/Dr-TSNG/Hide-My-Applist/releases) Перезагружаем устройство.  
5. Проходим в LSPosed → Модули → активируем Hide My Applist (автоматически поставится галочка на Системный фреймворк). Перезагружаем устройство.  
6. Заходим в Hide My Applist, убеждаемся, что модуль активирован и системная служба работает. Переходим в Управление шаблонами → Создать шаблон с чёрным списком → выбираем всё, что может потенциально быть связано с root-доступом. Добавляем название для шаблона и сохраняем его.  
7. Возвращаемся в главное меню и открываем Управление приложениями. Там находите все ваши банковские и прочие приложения, чувствительные к root. В меню каждого из них включаете скрытие и применяете созданный ранее шаблон (первый пункт в разделе "Конфигурация шаблонов").

# :wrench: CLI-утилиты
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

# :stars: Полезное
**Визуальное оформление:**
* [Огромная подборка качественных обоев на Google Фото.](https://photos.google.com/share/AF1QipOIcbtWWVSIYkq21nNYNLOwzCdIhQWlJetX2qT-5XZMQuKinJa8pyboRc9j-gL2aA?pli=1&key=OXI4MUxma3dHUEtoMFJIOEMwQ1JBYWFVY0sxQVZR)
* [Cursor Colors Synchronizer.](https://github.com/SunsetTechuila/Cursor-Colors-Synchronizer) Синхронизирует цвет акцента системы и курсора.
* [Icon Archive.](https://iconarchive.com/) Большая и бесплатная библиотека иконок в форматах .ico/.png.

**Сайты:**
* [waifu2x.](https://waifu2x.udp.jp/) Быстрый и полностью бесплатный сервис по апскейлу фотографий/артов с открытым исходным кодом.
* [Startpage.](https://startpage.com/) Приватный поисковик с неординарной киллер-фичей: анонимный просмотр любых сайтов, суть которого заключается в использовании их собственного прокси. Достаточно нажать на кнопку Anonymous View рядом с результатом поиска и откроется вкладка сайта, прогоняемая через прокси Startpage без дополнительных установок и ожидания.
* [Discogs.](https://discogs.com/) Огромная база данных о музыке со всего мира (различная информация, варианты релизов, продажа винилов и подобное).
* [HDRezka.](https://hdrezka.co/) Крупнейший пиратский агрегатор сериалов и фильмов.
* [Nightcore Studio.](https://nightcore.studio/) Ну где же мой SLOWED & REVERB???
* [BrowserLeaks.](https://browserleaks.com/ip) Для большинства подойдёт вместо заезженного рекламного 2IP, но так же даёт и множество другой информации о вашем IP-адресе.
* [RIPE.](https://apps.db.ripe.net/db-web-ui/query) Дата-база IP-адресов, кому принадлежат и когда были замечены.
* [MassGrave.](https://massgrave.dev) Да, он указан в начале списка как метод активации. Но помимо того, сайт содержит прямые ссылки на загрузку оригинальных инсталлеров/образов Office или Windows всех языков, различные FAQ и полезности, например, активация других продуктов Microsoft или обход геоблокировки для пользователей из России.
* [SimpleLogin,](https://simplelogin.io/) [DuckDuckGo Email Protection](https://duckduckgo.com/email/) & [Firefox Relay.](https://relay.firefox.com/) Форвардинг почты. 

**Telegram-боты:**
* [@murglar_bot.](https://t.me/murglar_bot) Загрузка музыки с российских площадок и Deezer в форматах MP3/FLAC. Поддерживает параметры поиска, устанавливаются перед запросом. Здесь подробнее...  
  - `s:<сервис>` — Выбор сервиса, возможные значения — vk/ynd/sc/dzr/sz.  
  - `b:<битрейт>` — Выбор битрейта, зависит от сервиса. Возможные значения — 128/192/320/max. Max — загрузка в FLAC.  
  - Параметр `l` — используется для запроса текста песни.  

Так же можно вставить ссылку на необходимый трек с указанных выше платформ.
* [@Spotify_Track_Info_Bot.](https://t.me/Spotify_Track_Info_Bot) Управление музыкой. Можно найти любой релиз, информацию про него, обложку в полном качестве, текст с разных платформ, скачать в .mp3 формате.
* [@StickersConverterBot.](https://t.me/StickersConverterBot) На удивление почти единственный поддерживаемый бот из подобных. Конвертирует стикеры/эмодзи в .png файлы.
* [@sonmiaudio_bot.](https://t.me/sonmiaudio_boy) Поиск литературы.
* [@orforobot.](https://https://t.me/orforobot) Проверка текста на орфографические ошибки.
* [@GetBridgesBot.](https://t.me/GetBridgesBot) Запрос мостов для доступа в Tor.

**Скрипты:**
* [Platform Tools Installer.](https://github.com/SunsetTechuila/Platform-Tools-Installer) Скрипт автоматически скачивает актуальные Platform-tools для вашей платформы, предлагает выбрать место для распаковки, после чего добавляет их в PATH.
* [Прошивка модема для активации VoLTE/VoWi-Fi на Google Pixel 4.](https://4pda.to/forum/index.php?act=findpost&pid=121460611&anchor=Spoil-121460611-1) **Перевод SELinux в Permissive не требуется!** Для чего было добавлено автором – загадка.

**Модификация интерфейса Windows через .reg-файлы:**
> [!WARNING]
> Имейте ввиду, что данный метод не самый безопасный и может повлечь за собой визуальные баги и нестабильность оболочки Проводника.

* [Скрыть стрелку с ярлыков на рабочем столе.](https://t.me/begoniacommunity/1384476) Перемещаем файл Blank.ico в корневую папку Windows и запускаем RemoveArrow.bat; перезагружаем Проводник. Чтобы откатить изменения, запускаем RestoreArrow.bat.

**Программы:**
* [RustDesk.](https://rustdesk.com/) Свободная альтернатива AnyDesk/TeamViewer. Возможен селфхост, но отлично работает и на бесплатных серверах из Германии и Киева.
* [Hitomi Downloader.](https://github.com/KurtBestor/Hitomi-Downloader) Графический интерфейс для yt-dlp, соответственно, список поддерживаемых сайтов тот же.
* [Universal Android Debloater.](https://github.com/0x192/universal-android-debloater) Лучший деблоатер для Android. [Функции перечислены здесь,](https://github.com/0x192/universal-android-debloater#features) в дополнение хочется отметить, что для удобства приложения заранее разбиты по готовым категориям (например, безопасные для отключения), а так же почти у каждого пакета есть описание, за что конкретно он отвечает.
* [Bleachbit.](https://www.bleachbit.org/) Свободный софт по чистке хвостов и мусора по типу CCleaner. Использовать с осторожностью.
* [Grabber.](https://github.com/Bionus/imgbrd-grabber) Загрузчик картинок и видео с booru-сайтов (rule34, gelbooru, danbooru, safebooru, yande.re и другие).
* [SauceNAO.](https://f-droid.org/ru/packages/com.luk.saucenao/) Android-клиент [одноимённого сервиса](https://saucenao.com/) для обратного поиска изображений.
* [HakuNeko.](https://hakuneko.download/) Загрузчик манги, поддерживает большое количество источников.
* [Simplewall.](https://www.henrypp.org/product/simplewall) Настройка трафика с Windows Filtering Platform (WFP).
* [Tailscale.](https://tailscale.com/) Виртуальная локальная сеть на основе WireGuard без необходимости поднимать свой сервер. Позволяет связать телефон, компьютер и что-либо ещё в единую сеть для различных целей. Важно: не подойдёт для игр, поскольку 1) бывает слишком высокий пинг; 2) на личных почтах в одной сети может быть только один пользователь.

**Подборки:**
* [Огромная подборка свободного софта под разные платформы.](https://github.com/paulaime/awesome-privacy)
* [Свободные альтернативы базовым приложениям на Android.](https://www.simplemobiletools.com/)  
* [Список всевозможных приложений, выполненных в Material Design 3.](https://github.com/nyas1/Material-You-app-list)

# :no_entry_sign: Обход блокировок
* [IVPN.](https://www.ivpn.net/) Бесплатно для пользователей из России, Украины и Беларуси. Как получить доступ: заходим по ссылке [ivpn.net/supportua](https://www.ivpn.net/supportua/) с IP-адреса указанных ранее стран (другие не подойдут!), запрашиваем доступ и в течение 3-15 минут получаем на почту 30-дневный ваучер. Запрашивать доступ можно сколько угодно на одну и ту же почту, но только раз в 30 дней. Разрешено использовать сервис на двух устройствах одновременно, превысить не получится.
* Настройка собственного сервера под нужды VPN. Это платно (совсем не дорого), но очень надёжно. Рекомендуем использовать хостинг [aéza](https://aeza.net/) (иногда доступен Promo-тариф в Швеции за 100 руб./мес) или [VDSina.](https://vdsina.ru/) 
  1. Инструкция по настройке [WireGuard](https://github.com/angristan/wireguard-install#usage) или [OpenVPN.](https://github.com/angristan/openvpn-install#usage)  
  2. [Outline VPN](https://getoutline.org/ru/get-started) или [Amnezia.](https://amnezia.org/ru) **Строго рекомендуется пользователям из России.**  
Для Outline следуйте инструкциям в Manager'e, [вот его версия для Android,](https://f-droid.org/ru/packages/org.sirekanyan.outline/) если понадобится. В Amnezia нужно указать авторизационные данные сервера, затем выбрать High censorship lever (OpenVPN over Cloak), а после указать любой зарубежный сайт, не заблокированный РКН.  
Если хочется чего-то ещё, можете опробовать [Marzban,](https://github.com/Gozargah/Marzban) поддерживающий целый набор современных протоколов. [Интересное чтиво по методам обхода на Хабре.](https://habr.com/ru/articles/727868)
* [FreeOpenVPN.org.](https://www.freeopenvpn.org/) Бесплатные OpenVPN-конфиги разных стран. Нормальная доступность и плавающая скорость. Необходимо раз в 10 часов обновлять пароль для подключения.
* [АнтиЗапрет.](https://antizapret.prostovpn.org/) Бесплатно, но не слишком полезно ввиду того, что это по сути своей прокси, обходящее блокировки только по реестру РКН. Крайне подвержен блокировкам, [которые уже происходят.](https://ntc.party/t/topic/4269) Есть схожий проект для пользователей из Украины — [ЗаборонаХелп.](https://zaborona.help/)
