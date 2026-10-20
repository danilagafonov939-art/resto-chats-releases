# Resto Чаты — сборки

Сюда автоматически выкладываются обновления приложения Resto Чаты. Исходников тут нет.
После установки приложение обновляется само.

## Windows
Скачайте [RestoChats-Setup.exe](https://github.com/danilagafonov939-art/resto-chats-releases/raw/main/RestoChats-Setup.exe) и запустите.

## Mac
- Mac на M1/M2/M3/M4: [RestoChats-mac-arm64.zip](https://github.com/danilagafonov939-art/resto-chats-releases/raw/main/RestoChats-mac-arm64.zip)
- Mac на Intel: [RestoChats-mac-intel.tar.xz](https://github.com/danilagafonov939-art/resto-chats-releases/raw/main/RestoChats-mac-intel.tar.xz)

1. Откройте скачанный архив — появится «Resto Chats».
2. Перетащите его в «Программы».
3. Первый запуск: правый клик по приложению → «Открыть» → «Открыть»
   (или Системные настройки → Конфиденциальность и безопасность → «Всё равно открыть»).
   Это нужно один раз: приложение не подписано в Apple.
4. Если macOS пишет «приложение повреждено» — в Терминале:
   `xattr -cr "/Applications/Resto Chats.app"` и запустите снова.

---
- `latest.json` — актуальная версия (приложение проверяет при запуске и раз в 2 часа)
- `app-*.asar` — начинка приложения для обновления
- `stickers/` — общий набор стикеров
