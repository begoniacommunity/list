Здесь хранятся версии модулей, которые мы сделали сами/модифицировали, а так же те, что трудно найти на просторах Интернета.  
Все прикрепленные модули, что поддерживают работу с OverlayFS, уже содержат необходимый скрипт в установщике.

## Sensitive Props
Модифицированная версия [модуля от HuskyDG.](https://github.com/Magisk-Modules-Alt-Repo/sensitive_props)

Что сделано:

- Удален бесполезный код скрытия, приводящий к обнаружению ресетпропов и root-прав соответственно // [08e4804.](https://github.com/Magisk-Modules-Alt-Repo/sensitive_props/commit/08e480446e25f2e3a4286943ebc3a567b9321b04)
- Добавлена подмена `ro.build.flavor` с `userdebug` на `user`.

[Скачать модуль](https://github.com/begoniacommunity/list/blob/magisk-modules/sensitive_props.zip)

## Disable logs
Модифицированная версия [модуля от mrfrost475.](https://4pda.to/forum/index.php?showtopic=915158&st=220#entry105651495)

Что сделано:

- Удалены опасные перманентные чистки / изменения, приводящие к обнаружению ресетпропов.
- Убрана очистка кэша превью фотографий.
- Убрано отключение logd, чтобы предотвратить внутренний логоспам в LSPosed.
- Отключены логи говернора.
- Добавлено предупреждение с запросом подтверждения установки по нажатии кнопки громкости.
- По умолчанию отключен tcpdump, если он вам нужен, закомментируйте строку `stop tcpdump` в `service.sh`.

>
> [!CAUTION]
> На некоторых прошивках модуль приводит к бутлупу или перезагрузке в fastboot (например, на crDroid 10.x). Пожалуйста, сохраните важные данные перед установкой, а лучше и вовсе проверьте работоспособность на чистой системе перед использованием на основном сетапе.

[Скачать модуль](https://github.com/begoniacommunity/list/blob/magisk-modules/disable_logs.zip)

## BetterQS
Эстетически правильная и удобная разметка панели быстрого доступа при горизонтальной ориентации экрана. [Превью.](https://github.com/begoniacommunity/list/blob/magisk-modules/betterqs_preview.png)  
>
> [!NOTE]
> После установки может слететь оверлей интерфейса, учитывающий вырез на экране.  
> Чтобы восстановить его, пройдите в Настройки → Система → Для разработчиков → Вырез на экране → Вариант по умолчанию.

[Скачать модуль](https://github.com/begoniacommunity/list/blob/magisk-modules/better_qs.zip)

## LSPosed Mod No Logs
LSPosed с поддержкой Android 14 QPR2+ без внутренних логов. 

[Скачать модуль](https://github.com/begoniacommunity/list/blob/magisk-modules/lsposed_no-logs.zip)
