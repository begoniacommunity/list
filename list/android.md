# 🤖 Android

## Приложения:
### 📹 Клиенты стриминговых платформ
* [ReVanced Extended.](https://github.com/MatadorProBr/revanced-extended-magisk-module/releases) Включает в себя [SponsorBlock,](https://sponsor.ajay.app/) [ReturnYoutubeDislike.](https://www.returnyoutubedislike.com/) Есть как root, так и non-root версии. В том числе для клиента YouTube Music.
* [PurpleTV.](https://t.me/pubTw) Самая качественная модификация клиента Twitch (ранее называлась TwitchMod). Можно скрывать ненужные элементы интерфейса, обходить блокировки в чатах (писать нельзя, но доступен просмотр), есть VODHunter (доступ к записям для подписчиков).

### 🗾 Аниме и манга
* [Anixart.](https://t.me/anixart) Лучший агрегатор аниме на мобильных устройствах.
* [Kotatsu.](https://github.com/KotatsuApp/Kotatsu) Приложение для чтения манги.

### ⌛️ Блокировка рекламы
* [AdAway.](https://github.com/AdAway/AdAway) Блокировка рекламы через локальные hosts-файлы подключением к VPN (т.е. root-доступ не нужен). Готовые списки можно взять [здесь.](https://4pda.to/forum/index.php?showtopic=275091&st=8000#entry89665467)
> Рекомендуем добавить в разрешённые листы `firebase-settings.crashlytics.com`, `firebaseremoteconfig.googleapis.com` и *(опционально)* `firebaselogging.googleapis.com`. Эти адреса должны быть разблокированы для корректной работы некоторых приложений.  

### ⬇️ Менеджеры загрузки
* [Seal.](https://github.com/JunkFood02/Seal) Загрузчик видео/аудио, использующий yt-dlp (ещё можно включить aria2c). Очень удобный и простой в использовании. Выполнен в соответствии с MD3.
* [Advanced Download Manager.](https://play.google.com/store/apps/details?id=com.dv.adm&hl=en_US) Менеджер загрузок с поддержкой торрентов.

### 🎦 Съёмка
* [mcpro24fps.](https://t.me/mcpro24fps) Лучший бесплатный софт для профессиональной (и не очень) видеосъёмки на Android. К огромному удивлению, действительно удобнее и качественнее своих платных аналогов. Отмечу крайнюю легковесность (приложение весит меньше 2 МБ).

### 📷 Веб-камера
* [DroidCam.](https://play.google.com/store/apps/details?id=com.dev47apps.droidcam&hl=ru&gl=US) Использование камеры и микрофона устройства на ПК. [Клиенты для декстопных платформ.](https://dev47apps.com/)

### 📪 Почта
* [K-9 Mail.](https://k9mail.app/) Простой и свободный почтовый клиент.

### 🛡 Безопасность и пароли
* 2FA-аутентификация: [Authenticator Pro (MD3),](https://apt.izzysoft.de/fdroid/index/apk/me.jmh.authenticatorpro) [Mauth (MD3),](https://www.f-droid.org/packages/com.xinto.mauth/) [Aegis (MD2).](https://github.com/beemdevelopment/Aegis) 
* [KeePassDX.](https://github.com/Kunzisoft/KeePassDX) Локальное хранение паролей в зашифрованном файле с унифицированным форматом дата-баз для KeePass.
* [Samourai Wallet.](https://samouraiwallet.com/) Анонимный криптокошелёк, не требующий идентификации личности.

### 🗄 Защищенное хранилище
* [Photok.](https://f-droid.org/packages/dev.leonlatsch.photok/) Хранение фотографий на устройстве под кодовой защитой с применением шифрования.
* [DroidFS.](https://f-droid.org/packages/sushi.hardcore.droidfs/) Шифрование контента с использованием [gocryptfs](https://github.com/rfjakob/gocryptfs) или [CryFS](https://github.com/cryfs/cryfs) и управление им на устройстве.
* [EDS Lite.](https://f-droid.org/ru/packages/com.sovworks.edslite/) Создание и управление зашифрованными контейнерами (разделами) на Android.

### 🛜 Управление и мониторинг сетей
* [NetGuard.](https://github.com/M66B/NetGuard/) Выборочная блокировка доступа к интернету для приложений и ограничение рекламы через hosts, как в AdAway. Тоже не требует рут, так как работает через локальное VPN-подключение. [Версия с Pro-функциями.](https://4pda.to/forum/index.php?showtopic=700336&st=1820#entry113141886)
* [CellMapper](https://cellmapper.net/apps) & [NetMonster.](https://play.google.com/store/apps/details?id=cz.mroczis.netmonster&hl=ru&gl=US) Мониторинг качества и доступности мобильной сети (местоположение вышек и подобное).
* [Hiddify Next](https://github.com/hiddify/hiddify-next) Однокнопочный клиент для различных прокси. Рекомендуется в связке с [Marzban](https://github.com/begoniacommunity/list/blob/main/list/blocking_bypass.md#-%D0%BE%D0%B1%D1%85%D0%BE%D0%B4-%D0%B1%D0%BB%D0%BE%D0%BA%D0%B8%D1%80%D0%BE%D0%B2%D0%BE%D0%BA).
* [NekoBox.](https://github.com/MatsuriDayo/NekoBoxForAndroid) То же самое, что и Hiddify Next, но намного более управляемое и ручное
* [inviZible Pro.](https://f-droid.org/packages/pan.alexander.tordnscrypt.stable/) Обход блокировок через сеть Tor и i2p, а также шифрование DNS-запросов с помощью DNSCrypt.
* [PCAPdroid.](https://f-droid.org/ru/packages/com.emanuelef.remote_capture/) Инструмент мониторинга и записи сетевого трафика. Рут-права не для работы необязательны, ибо приложение может работать через локальное VPN-подключение.
* [Rethink.](https://f-droid.org/ru/packages/com.celzero.bravedns/) Управление трафиком.
* [Data Monitor.](https://github.com/itsdrnoob/DataMonitor) Статистика использования трафика приложениями.

> Для нормального запуска Tor, пройдите в быстрые настройки → Настройки Tor → Мосты → Запросить новый мост → выберите *obfs4* → введите капчу и подтвердите запрос, готово.  

### 🖼 Галерея
* [Aves.](https://github.com/deckerst/aves) Свободная, очень красивая и функциональная галерея. Поддерживает огромное количество форматов фото/видео, расширенный поиск по медиатеке, сортировку по различным критериям и другие функции.

### 🌐 Браузеры
* [Kiwi Browser.](https://kiwibrowser.com/) Поддерживает десктопные расширения для Chrome и ещё [несколько полезных функций.](https://kiwibrowser.com/features/)
* [Cromite.](https://github.com/uazo/cromite) Форк Bromite [с большим количеством функций.](https://github.com/uazo/cromite#features)
* [Iceraven.](https://github.com/fork-maintainers/iceraven-browser) Форк Firefox на GeckoView с нормальной поддержкой расширений, чуть более широкой кастомизацией и доступом к флагам (about:config).

### 🏃 Продуктивность
* [HabitKit.](https://play.google.com/store/apps/details?id=com.roehl.habitkit&hl=en_US) Индивидуальный журнал-трекер вашей продуктивности.
* [Гречка (Buckwheat).](https://apt.izzysoft.de/fdroid/index/apk/com.danilkinkin.buckwheat) Менеджер финансов и трат.

### 🔍 Поиск
* [SauceNAO.](https://f-droid.org/ru/packages/com.luk.saucenao/) Android-клиент [одноимённого сервиса](https://saucenao.com/) для обратного поиска изображений.

### 📁 Управление файлами 
* [Material Files.](https://f-droid.org/ru/packages/me.zhanghai.android.files/) Свободная альтернатива Google Files с расширенным функционалом. Поддерживает работу с FTP.
* [Total Commander.](https://ghisler.com/android.htm) Хороший файловый менеджер и архиватор.

### 💠 ADB Shell
* [Shizuku.](https://shizuku.rikka.app/) Предоставление повышенных прав приложениям через adb с помощью локального сервера.

### 🛍 Дисконтные карты
* [Catima.](https://github.com/CatimaLoyalty/Android) Карты лояльности с категориями и прочими опциями. В MD3.

### 🎙 Запись аудио
* [Record You.](https://github.com/you-apps/RecordYou) Запись аудио (диктофон) с параметрами качества, и старый добрый, не лагающий метод скринрекординга в одном приложении.

### ⚙️ Управление приложениями
* [Skit.](https://play.google.com/store/apps/details?id=com.pavelrekun.skit&hl=ru&gl=US) Менеджер установленных приложений. Умеет устанавливать сплит-пакеты, сохранять установленные приложения как .apk/сплит, быстро переходить к папкам с содержимым конкретных программ и другие функции.
* [Canta.](https://apt.izzysoft.de/fdroid/index/apk/org.samo_lego.canta) Деблоатер любых приложений, не требует доступа к root (работает через Shizuku).

### 📥 Магазины приложений
* [Droid-ify.](https://f-droid.org/packages/com.looker.droidify/) Фронтенд F-Droid, выполненный в стиле Material Design 3. 
  * Рекомендуемые репозитории:  
`https://apt.izzysoft.de/fdroid/`
* [Aurora Store.](https://f-droid.org/ru/packages/com.aurora.store/) FOSS-клиент для Google Play. Не требует авторизации в аккаунт – выбираем анонимную сессию, доступны приложения из всех регионов.
* [Obtainium.](https://github.com/ImranR98/Obtainium) Менеджер обновлений приложений из большого количества вручную настраиваемых истчоников (например GitHub, F-Droid или Huawei AppGallery, полезный для загрузки российских приложений).

<details>

<summary>Прямые ссылки на некоторые российские приложения из AppGallery</summary>

Тинькофф: `https://appgallery.huawei.com/app/C101291451`  
Альфа-Банк: `https://appgallery.huawei.com/app/C101515897`  
Сбер: `https://appgallery.huawei.com/app/C100994843`  
ВТБ: `https://appgallery.huawei.com/app/C102312137`  
ПСБ: `https://appgallery.huawei.com/app/C102409911`  
Райффайзен: `https://appgallery.huawei.com/app/C101231337`  
Почта Банк: `https://appgallery.huawei.com/app/C101191061`  
Газпром Банк: `https://appgallery.huawei.com/app/C102137729`  
Мегафон: `https://appgallery.huawei.com/app/C101202073`  
Yota: `https://appgallery.huawei.com/app/C105436239`  
Тинькофф Мобайл: `https://appgallery.huawei.com/app/C101426731`  
ЮMoney: `https://appgallery.huawei.com/app/C103046791`  
QIWI: `https://appgallery.huawei.com/app/C101130485`  
2ГИС: `https://appgallery.huawei.com/app/C100888583`
Mir Pay: `https://appgallery.huawei.com/app/C103191567`

</details>

### 🗣 Имиджборды и форумы
* [DashchanFork.](https://github.com/TrixiEther/DashchanFork) Актуальная версия мобильного клиента для различных имиджбордов.
* [iChan.](https://github.com/Zchandev/iChan) Клиент имиджбордов 2ch и 4chan.
* [ForPDA.](https://f-droid.org/ru/packages/org.softeg.slartus.forpdaplus/) Альтернативный клиент для 4PDA, если оригинальный чем-то не устраивает.

### 🛠 Системное
* [QuickTiles.](https://f-droid.org/packages/com.asdoi.quicktiles/) Позволяет добавлять готовые или кастомные быстрые тогглы для панели управления.
* [Shortcut Maker.](https://play.google.com/store/apps/details?id=rk.android.app.shortcutmaker&hl=en_US) Приложение для создания ярлыков, но основное его применение, найденное сообществом — автоматическая генерация Monet-иконок для приложений, не поддерживающих это по умолчанию. Работает в 9/10 случаев. Либо можно выбирать иконки из стороннего иконпака. Анимации запуска/сворачивания ярлыка идентичные приложению, если у вас Android 12L+ с Pixel-подобным ланучером. Нужно вручную подобрать оптимальный размер иконки (например, для Pixel 4 это 92%).
* [MacroDroid.](https://macrodroid.com/) Автоматизация действий на Android.
* [Blocker.](https://github.com/lihenggui/blocker) Блокировка компонентов приложений с помощью Intent Firewall. Имеет встроенные списки для массового отключения компонентов аналитики и слежки в других установленных приложениях.

### 📦 Посылки
* [Track24.](https://play.google.com/store/apps/details?id=net.track24.android&hl=ru&gl=US) Отслеживание посылок в виде сводки информации со всех международных источников.

### 🚕 Такси и навигация
* [AltoCar.](https://altocar.ru/) Агрегатор выгодных предложений такси для России.

### 🎨 Персонализация
* *(Android 12+)* [Repainter.](https://repainter.app/) Приложения для тонкой настройки вашей Monet-темы. Требуется покупка подписки/единоразовой оплаты лицензии [(наконец-то появился взлом)](https://4pda.to/forum/index.php?showtopic=1042309&st=180#entry125994171) и root-права (за редким исключением ваша прошивка может поддерживать интеграцию с приложением, например, PixelOS/ProtonAOSP для Pixel 4).
* [WallMan.](https://apt.izzysoft.de/fdroid/index/apk/com.colorata.wallman) Живые обои со всех моделей Google Pixel в одном, очень красивом приложении. Работает на всех устройствах с Android 11 и выше.

### 🔠 Переводчики
* [Translate You.](https://github.com/you-apps/TranslateYou) Свободное приложение-переводчик, выполненное в Material Design 3. [Поддерживает сразу несколько сервисов](https://github.com/you-apps/TranslateYou#supported-translation-engines) (из наиболее популярных можно выделить DeepL и Reverso).

### 📖 Чтение
* [ReadEra.](https://readera.org/ru) Читалка для всего: fb2, epub, pdf, мсоффис-документы и т.д.

### ♻️ Бэкапы
* [Neo Backup.](https://f-droid.org/ru/packages/com.machiav3lli.backup/) Свободный бэкапер. Выборочное резервирование и восстановление одного или нескольких приложений. Работает только с root-правами.
* [Lucky Patcher.](https://4pda.to/forum/index.php?showtopic=298302) Нестареющая классика взлома приложений. Строго рекомендуем не лезть этой утилитой в недра системы, пользуйтесь только для операций с софтом.

### 💡 Полезные приложения
* [Barcode Scanner.](https://f-droid.org/packages/com.atharok.barcodescanner/) Сканер штрих/QR-кодов.
* *(Android 12<)* [Clipboard Cleaner.](https://f-droid.org/ru/packages/io.github.deweyreed.clipboardcleaner/) Выводит уведомления об операциях приложений/пользователя с буфером обмена, и тоггл в шторку для его очистки.
* [Memory Guardian.](https://apt.izzysoft.de/fdroid/index/apk/ara.memoryguardian) Настройка автоочистки буфера обмена.

## Модули:

### Для Magisk
* [ViPER4Android Repackaged.](https://github.com/programminghoch10/ViPER4AndroidRepackaged) Не требует никаких дополнительных манипуляций с любым устройством. Всё работает сразу после установки.
* [Basic Call Recorder.](https://github.com/chenxiaolong/BCR#readme) Простой рекордер звонков без ненужных фич. Поставил, включил и забыл.
* [LSPosed.](https://github.com/LSPosed/LSPosed) Наследник мощного фреймворка Xposed, позволяющего внедрять собственный код в приложения во время работы. Имеет встроенный репозиторий с большим количеством полезных модулей.
* [QuickSwitch.](https://github.com/skittles9823/QuickSwitch) Безболезненная замена стандартного лаунчера вместе с провайдером Недавних. Рекомендую связку [Lawnchair 12.1.0 **Dev** с Lawnicons.](https://apkmirror.com/apk/lawnchair/) Ещё можно поставить [Pixel Search.](https://play.google.com/store/apps/details?id=rk.android.app.pixelsearch) Вот вам и красивая, свободная альтернатива прожорливому Pixel Launcher ;) с огромной дополнительной кастомизацией.
* [GPhotos Unlimited Zygisk.](https://github.com/cuynu/gphotos-unlimited-zygisk) Безлимитное хранилище в Google Фото без потерь качества. 
* [microG Installer Revived.](https://github.com/nift4/microg_installer_revived) Почти единственный актуальный установщик microG для Magisk. Включает в себя всё для стабильной работы (включая пуши и геолокацию). Если система не поддерживает подмену подписи, активируем её через [этот модуль для LSPosed.](https://github.com/whew-inc/FakeGApps/releases) 

<details>

<summary>Если нужна синхронизация контактов и календаря с Google-аккаунтом</summary>

Действия производим после установки модуля.  
Не проверял, работает ли синхроинзация уже после входа в аккаунт, но должна. В противном случае просто перелогиньтесь.

1. Скачиваем последние версии [Google Contacts Sync](https://apkmirror.com/apk/google-inc/google-contacts-sync/) и [Google Calendar Sync.](https://apkmirror.com/apk/google-inc/google-calendar-sync/) Переименовываем файлы в `GoogleContactsSyncAdapter.apk` и `GoogleCalendarSyncAdapter.apk`.
2. Проходим по пути `/data/adb/modules/microg_revived/system/app` и создаём две одноименные папки (`GoogleContactsSyncAdapter` и `GoogleCalendarSyncAdapter`). 
3. Переносим файлы соответственно. Каждому файлу выдаём права (chmod) 0644. Перезагружаем систему, идём в настройки приложений и выдаём им все запрашиваемые разрешения. 

</details>

* [Magisk Overlayfs.](https://github.com/Magisk-Modules-Alt-Repo/magisk_overlayfs) Монтирование системных разделов a/b-устройств в Read/Write через overlayfs.
* [Zygisk Detach.](https://github.com/j-hc/zygisk-detach) Блокировка автообновления приложений через Google Play путём скрытия их наличия в системе от маркета. Мастхэв при установленном ReVanced rooted-методом.

Визуальное оформление:
* [Шрифт Inter для системы и Google Sans с часов экрана блокировки.](https://github.com/LeddaZ/inter-font-pack/) Установка на Android 12+ через Magisk. 
* [Эмодзи из iOS 16.4.](https://github.com/Keinta15/Magisk-iOS-Emoji) Установка на Android 12+ через Magisk. 

### Специфичные модули для KernelSU
>
> [!WARNING]
> Мы не рекомендуем использовать KernelSU. 
* [Zygisk Next.](https://github.com/Dr-TSNG/ZygiskNext) Имплементация Zygisk API.

## Как скрыть root-доступ
>
> [!NOTE]
> Актуально на момент последнего редактирования для всех банковских и платёжных приложений в России.

1. Скачиваем app-release.apk из [Kitsune Mask](https://github.com/HuskyDG/magisk-files/releases) (ранее Magisk Delta) и устанавливаем.  
2. В настройках Kitsune Mask пересобираем приложение с рандомным именем пакета, включаем Zygisk, MagiskHide и Enforce SuList (ещё опционально можно включить биометрическую аутентификацию, для вашего удобства).  
Перезагружаем устройство. Приложения, которые должны иметь доступ к root-правам, выбираем в списке Configure SuList. 
> Следующие пункты можно пропустить, если ваши приложения больше не находят рут-права/разблокированный загрузчик (и, соответственно, не ограничивают функционал).
### Дополнительный уровень защиты от обнаружений
1. Скачиваем и устанавливаем Zygisk-версию модуля [LSPosed,](https://github.com/LSPosed/LSPosed/releases) затем скачиваем и устанавливаем [Hide My Applist.](https://github.com/Dr-TSNG/Hide-My-Applist/releases) Перезагружаем устройство.  
2. Проходим в LSPosed → Модули → активируем Hide My Applist (автоматически поставится галочка на Системный фреймворк). Перезагружаем устройство.  
3. Заходим в Hide My Applist, убеждаемся, что модуль активирован и системная служба работает. Переходим в Управление шаблонами → Создать шаблон с чёрным списком → выбираем всё, что может потенциально быть связано с root-доступом. Добавляем название для шаблона и сохраняем его.  
4. Возвращаемся в главное меню и открываем Управление приложениями. Там находите все ваши банковские и прочие приложения, чувствительные к root. В меню каждого из них включаете скрытие и применяете созданный ранее шаблон (первый пункт в разделе "Конфигурация шаблонов").  

P.S. На некоторых прошивках устройство может не пройти проверку [Device Integrity.](https://developer.android.com/google/play/integrity/verdicts#device-integrity-field) Проверить у себя можно [этим приложением](https://play.google.com/store/apps/details?id=gr.nikolasspyr.integritycheck) (должны быть галочки рядом с MEETS_DEVICE_INTEGRITY/MEETS_BASIC_INTEGRITY). Для России и местных банковских или платёжных приложений, ни одна из указанных сертификаций не требуется. Тем не менее, если вам это нужно, [есть модуль.](https://github.com/chiteroman/PlayIntegrityFix) Недавно Google взялись за активные блокировки используемых в комьюнити фингерпринтов, потому обновления теперь выходят чуть ли не каждый день.

## Модификации в системе с помощью Shizuku
Эти приложения поддерживают работу на устройствах без root-прав!  
[Автоматический запуск Shizuku после перезагрузки через Automate](https://llamalab.com/automate/community/flows/44848) и [как поставить.](https://www.reddit.com/r/Android/comments/128eak8/comment/jescmhz/?utm_source=share&utm_medium=web2x&context=3)
* *(Android 12+)* [Better Internet Tiles.](https://github.com/CasperVerswijvelt/Better-Internet-Tiles) Возвращает раздельные тайлы для мобильного интернета и Wi-Fi.
* [RootlessJamesDSP.](https://github.com/ThePBone/RootlessJamesDSP) Эквалайзер с огромным количеством настроек. Обратывает не весь аудиопоток на устройстве – [есть ограничения.](https://github.com/ThePBone/RootlessJamesDSP#limitations)
* [LSPatch.](https://github.com/LSPosed/LSPatch) It just works?... Имплементация Xposed API в .apk приложения с дальнейшим управлением модулями через менеджер.
* [Smartspacer.](https://github.com/KieronQuinn/Smartspacer) Модификация встроенного виджета "Самое главное" (At a Glance) для устройств Pixel.
* [Pixel VoLTE Patch.](https://github.com/kyujin-cho/pixel-volte-patch/blob/main/README.en.md) Активация VoLTE на устройствах Pixel с процессором Tensor.
* [aShell.](https://f-droid.org/packages/in.sunilpaulmathew.ashell/) Терминал для ADB Shell с запущенным Shizuku.
Дополнительно, советую заглянуть в [Awesome Shizuku.](https://github.com/ThePBone/awesome-shizuku) Это обновляемый список приложений, поддерживающих работу через локальный adb.

## Полезное
* Принудительный запуск оптимизации приложений (бывает полезно в случаях, если сделали клинфлеш с последующей установкой большого количества приложений/обновили версию Android с сохранением данных): 
  1. Если у вас есть root-права: запускаем в Терминале команду `su -c "cmd package bg-dexopt-job"` и ожидаем окончания процесса (будет выведена строка Success).
  2. Если root-прав нет, выполняем `cmd package bg-dexopt-job` через Shizuku или классический `adb shell`.
  3. *(Экспериментально)* Предкомпиляция байт-кода, принудительное пересоздание уже созданного раннее системой кэша: `pm compile -a -f -m everything; pm bg-dexopt-job`.
* [scrspy.](https://github.com/Genymobile/scrcpy) Универсальное решение для захвата экрана, звука или видео с Android-устройства через прямое подключение по USB или Wi-FI.
* [Universal Android Debloater.](https://github.com/0x192/universal-android-debloater) Лучший деблоатер для Android. [Функции перечислены здесь,](https://github.com/0x192/universal-android-debloater#features) в дополнение хочется отметить, что для удобства приложения заранее разбиты по готовым категориям (например, безопасные для отключения), а так же почти у каждого пакета есть описание, за что конкретно он отвечает.

# ✈️ Telegram:

### Клиенты
Рекомендация, касающаяся многих клиентов – ищите обновления в принадлежащих им Beta/CI-каналах. На GitHub в основном ведут историю коммитов в рамках отдельного дерева и не обновляют релизы, соответственно кажется, что разработка заброшена. На деле (зачастую) это не так. 

* [exteraGram.](https://t.me/exteraGram) Действительно актуальный клиент Telegram с большим количеством приятных мелочей и опрятным внешним видом от адекватного разработчика. Присутствует поддержка CameraX внутри всего приложения. В том числе для видеосообщений. Ещё, во время их записи можно включать подсветку/вспышку; есть режим статичного зума. Редизайн встроенного аудиоплеера, есть ручная настройка закругления элементов, три вариации тем Monet для устройств с Android 12+, набор UI-иконок [Solar,](https://t.me/Design480/358) центрирование заголовка в списке чатов и изменение его названия, изменение стиля папок (так же можно включить иконки, синхронизируемые с десктопной версией) и категорий по всему приложению. Увеличение скорости загрузки/выгрузки файлов, активация нового сжатия изображений (2560px). Можно скрыть плитку камеры в меню скрепки, скрывать клавиатуру жестом в области чата, бесконечные недавние стикеры. Можно добавить ключ OpenAI ChatGPT и генерировать ответы прямо в области ввода. [Обновляется (пока что) только здесь.](https://t.me/exteraGramCI)
* [AyuGram4A.](https://github.com/AyuGram/AyuGram4A) Форк exteraGram с функциями из одноимённого настольного клиента. Дополнительно можно выделить разрешенные скриншоты в секретных чатах и сохранение чатов, из которых вы были исключены. [Обновления здесь.](https://t.me/ayugramchat/1238)
* [Nnngram.](https://t.me/Nnngram) Доведённый до ума (по мере возможности) форк [Nullgram.](https://github.com/qwq233/Nullgram) Это клиент, совмещающий в себе функционал от привычного Nekogram, одноимённой X-версии [без китайских странностей](https://github.com/PreviousAlone/Nnngram#why-nullgram) и некоторые свои полезные дополнения.
* [Plus.](https://t.me/PlusMessengerUpdates) Адово напердоленный чем только можно клиент. Идейный собрат ныне покойного [BGram.](https://t.me/BGramChannel) По насранности миллиардом разных настроек не имеет конкурентов. На соответствующего любителя.

P.S. Есть и некоторые альтернативы ЭкстераГраму. Например, [OctoGram](https://github.com/OctoGramApp/OctoGram) или... [Cherrygram?](https://t.me/Cherry_gram) :trollface:  
Может быть понравятся. Не упомянуть их существование не могу, так как клиенты регулярно обновляются и поддерживаются разработчиками. В остальном думайте сами.

### Модули

* [Killergram.](https://github.com/AetherMagee/Killergram) Модуль для LSPosed, совместим [с почти всеми клиентами.](https://github.com/AetherMagee/Killergram#support-clients) Убирает рекламу из каналов, снимает лимит на количество аккаунтов и разрешает локальное копирование контента из чатов и каналов, где это запрещено.

# 📟 Discord:
### Моды
* [Vendetta.](https://github.com/vendetta-mod/Vendetta) Работает по аналогии с Vencord, только на телефоне. Удобнее устаналивать через [Vendetta Manager.](https://github.com/vendetta-mod/VendettaManager) Запускается сильно дольше немодифицированного клиента.

### [Плагины и темы можно найти здесь.](https://github.com/topics/vendetta-plugins)

# 🎧 Spotify
[XManager.](https://t.me/xManagerUpdates) Лучший мод оригинального клиента Spotify. Подойдёт как для non-premium, так и для Premium-аккаунтов. В случае с первыми, мод отключает всю аудио и визуальную рекламу, оставляя лишь серверные ограничения на качество воспроизводимого аудио и необходимость в релогине каждые 2 недели (если вы из России). Для обоих типов пользователей будет полезна активация экспериментального режима (значок колбочки сверху в приложении XManager) с большим количеством новых и полезных функций.

# 🎵 TikTok
>
> [!NOTE]
> Иногда TikTok ограничивает активность аккаунта после авторизации в моде, отключая возможность ставить лайки на медиа из ленты, профиля или из личных сообщений. Если это произошло — пройдёт через некоторое время, если вы используете мод с актуальной версией базы. На старых версиях этот функционал может быть частично или полностью отключен.

* [TikTok Mod от Jaggu.](https://t.me/tiktalkupdate) Наиболее популярный и удобный мод со всеми фукнциями. Включена перемотка (таймлайн) для всех роликов; скачивание видео/фото без водяного знака. Вырезана вся реклама. Обновления бывают нестабильными. Сборка, где работает публикация видео с применением звука — [27.9.4.](https://t.me/tiktalkupdate/63)
* [Chikutaku](https://t.me/thedise/1933) от [Дайса.](https://thedise.me/) Основан на [revanced-patches.](https://github.com/ReVanced/revanced-patches) Можно подделать регион в настройках приложения (по умолчанию установлено `us`<sup>США</sup>). Доступна подмена кода страны, кода мобильной сети и названия оператора. Публикация видео без VPN не работает!
* [TikTok Mod](https://www.mediafire.com/file/qw5fhr7y6miqhwi/TikTok_32.0.2.DarkMode.apk/file) от [Tech Day.](https://t.me/tech_d4y) Тоже самое, что и верхний пункт, но с частичной тёмной темой. Самая актуальная на данный момент версия базы среди всех модов (32.0.2).

# 📚 Подборки софта
* [Большой список исключительно свободного софта для Android. Некоторые приложения могут быть устаревшими](https://github.com/offa/android-foss)
* [Свободные альтернативы базовым приложениям на Android.](https://simplemobiletools.com/)  
* [Список всевозможных приложений, выполненных в Material Design 3.](https://github.com/nyas1/Material-You-app-list)
