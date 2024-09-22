Здесь хранятся версии модулей, которые мы сделали сами/модифицировали, а так же те, что трудно найти на просторах Интернета.  

## Sensitive Props
Модифицированная версия [модуля от PixelProps.](https://www.pling.com/p/2129780/)

Что сделано:

- Возвращена и актуализирована логика resetprop из [оригинальной версии модуля](https://github.com/Magisk-Modules-Alt-Repo/sensitive_props) (применяется для значительно большего количества строк, в т.ч. с учетом aosp-based прошивок).
- Добавлено удаление ro.dalvik.vm.native.bridge посредством HexPatch.

[Скачать модуль](https://github.com/begoniacommunity/list/blob/files/sensitive-props-v6.4.4-bc.zip)

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
> На некоторых прошивках модуль приводит к бутлупу или перезагрузке в fastboot. Пожалуйста, сохраните важные данные перед установкой, а лучше и вовсе проверьте работоспособность на чистой системе перед использованием на основном сетапе.

[Скачать модуль](https://github.com/begoniacommunity/list/blob/files/disable_logs.zip)

## BetterQS
Эстетически правильная и удобная разметка панели быстрого доступа при горизонтальной ориентации экрана. [Превью.](https://github.com/begoniacommunity/list/blob/files/betterqs_preview.png)  

[Скачать модуль](https://github.com/begoniacommunity/list/blob/files/better_qs.zip)

## LSPosed Mod No Logs
LSPosed с поддержкой Android 14 QPR2+ без внутренних логов. 

[Скачать модуль](https://github.com/begoniacommunity/list/blob/files/lsposed_no-logs.zip)

## disable_ripple_on_unlock.apk
Отключает анимацию волны при разблокировке экрана (Android 12+).

[Скачать модуль](https://github.com/begoniacommunity/list/blob/files/disable_ripple_on_unlock.apk)

## wall_zoom_anim_disabler.zip
Отключает анимацию приближения/отдаления обоев при разблокировке экрана (Android 11+).

[Скачать модуль](https://github.com/begoniacommunity/list/blob/files/wall_zoom_anim_disabler.zip)

## magisk-overlayfs-v3.2.2-fixed.zip
Поддерживает новые версии Magisk, APatch и KernelSU.

[Скачать модуль](https://github.com/begoniacommunity/list/blob/files/magisk-overlayfs-v3.2.2-fixed.zip)

