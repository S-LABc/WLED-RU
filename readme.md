<p align="center">
<img src="/images/ru/wled_logo_akemi_ru.png">
</p>

  
# WLED на русском языке ✨
В этом репозитории находятся **русскоязычные** версии проекта ***WLED***. Переведено лишь то, что мне было по-силам. Могут встречаться ошибки или опечатки, которые я проглядел. *Переведено одно расширение пользователя, называется* **battery_status_basic**.

- Официальный [GitHub репозиторий](https://github.com/Aircoookie/WLED)
- Официальный [сайт проекта](https://kno.wled.ge/)
- Официальные [файлы релизов](https://github.com/Aircoookie/WLED/releases)
- **Русскоязычные** [файлы релизов](https://github.com/S-LABc/WLED-RU/releases)

Если нужно связаться со мной:
- [Почта](mailto:romansklyar15@gmail.com)

## 🖼️ Изображения
<img src="/images/ru/wled_phone_mode.jpg" width="50%"><img src="/images/ru/wled_phone_mode_info.jpg" width="50%">

## ✌️ От автора

*Лицензия [MIT license](https://raw.githubusercontent.com/Aircoookie/WLED/master/LICENSE)*

[Список авторов!](https://kno.wled.ge/about/contributors/)

*Предупреждение от авторов проекта WLED:*

Если у вас может возникнуть эпилепсия от вспышек или света, не рекомендуется использовать это программное обеспечение.
Если вы все же хотите попробовать, не используйте режимы с эффектом стробоскопа, вспешек, шума, не задавайте высокую скорость эффектам.
В соответствии с лицензией MIT я не несу ответственности за любой ущерб, причиненный вам или любому другому человеку или оборудованию. 

## 🔨 Измененные файлы v0.13.1 "Toki"
Изменениям подвергся англоязычный текст и параметры стилей CSS в некоторых исходных файлах. Никакие функции оригинальной прошивки изменены не были! Акцент перевода был сделан на пользовательском интерфейсе и сообщениях о действиях. Некоторые сообщения мне не удалось адаптировать к русскому языку, для этого пришлось бы изменить логику работы самой прошивки, другие же исходят от сторонних сервисов.

**wled-ru/**
- [**platformio.ini**](https://github.com/S-LABc/WLED-RU/blob/main/platformio.ini) @ Выбор сборки для модуля

**../wled00/**
- [**FX.h**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/FX.h) @ Названия эффектов и палитр цветов
- [**wled_server.cpp**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/wled_server.cpp) @ Сообщения серверной части
- [**xml.cpp**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/xml.cpp) @ Изменения XML-содержимого страниц
- [**set.cpp**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/set.cpp)
- [**cfg.cpp**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/cfg.cpp)

*Изменяются автоматически при использовании команд: **npm install**, **npm run dev** или **npm run build***
- [**html_other.h**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/html_other.h)
- [**html_settings.h**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/html_settings.h)
- [**html_ui.h**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/html_ui.h)

**../usermods/**
- [**battery_status_basic/usermod_v2_battery_status_basic.h**](https://github.com/S-LABc/WLED-RU/blob/main/usermods/battery_status_basic/usermod_v2_battery_status_basic.h) @ Уровень заряда АКБ

**../data/**
- [**404.htm**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/data/404.htm) @ Ошибка 404
- [**dmxmap.htm**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/data/dmxmap.htm) @ Карта устройств DMX
- [**edit.htm**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/data/edit.htm) @ Редактор файлов 8266
- [**index.css**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/data/index.css) @ Стили главной страницы
- [**index.htm**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/data/index.htm) @ Главное страница
- [**index.js**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/data/index.js) @ Интерфейс и всплывающие собщения
- [**liveview.htm**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/data/liveview.htm)
- [**liveviewws.htm**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/data/liveviewws.htm)
- [**msg.htm**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/data/msg.htm) @ Шаблон сообщений
- [**settings.htm**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/data/settings.htm) @ Перечень настроек
- [**settings_dmx.htm**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/data/settings_dmx.htm) @ Настройки DMX
- [**settings_leds.htm**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/data/settings_leds.htm) @ Настройки светодиодов
- [**settings_sec.htm**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/data/settings_sec.htm) @ Настройки безопасности
- [**settings_sync.htm**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/data/settings_sync.htm) @ Настройки синхронизации
- [**settings_time.htm**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/data/settings_time.htm) @ Настройки времени
- [**settings_ui.htm**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/data/settings_ui.htm) @ Настройки интерфейса пользователя
- [**settings_um.htm**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/data/settings_um.htm) @ Настройки расширений
- [**settings_wifi.htm**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/data/settings_wifi.htm) @ Настройки Wi-Fi
- [**update.htm**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/data/update.htm) @ Обновление прошивки
- [**usermod.htm**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/data/usermod.htm) @ Шаблон расширений пользователя
- [**welcome.htm**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/data/welcome.htm) @ Страница приветствия

## 💡 Инструкции
Для модулей *ESP32* сначала нужно зашить загрузчик **esp32_bootloader_vX.bin** (X - номер версии) по адресу **0x0**, а потом шить файл прошивки WLED по адресу **0x10000**. Актуально для Flash Download Tools

- Прошивка через [Flash Download Tools](https://www.espressif.com/en/support/download/other-tools)
- Прошивка через [PlatformIO](https://github.com/Aircoookie/WLED/wiki/How-To-Compile-WLED-.bin-File)
- Прошивка через [OTA](https://kno.wled.ge/basics/install-binary/#flashing-method-4-ota-update)
- Изменение [веб-интерфейса](https://github.com/Aircoookie/WLED/wiki/Add-own-functionality#changing-web-ui)

## ⚙️ Расширения пользователей (usermods)

В стандартных двоичных файлах прошивки никакие расширения пользателей не включены!
Чтобы их включить необходимо выполнить действия, описанные в файлах `readme.md` или `readme_ru.md` в папке с нужным вам расширением. Например [**battery_status_basic**](https://github.com/S-LABc/WLED-RU/blob/main/usermods/battery_status_basic/readme_ru.md)
После этого, нужно пересобрать проект WLED из исходников, получив новый файл прошивки, где будет присутствовать нужное расширение.

- Папка [**usermods**](https://github.com/S-LABc/WLED-RU/blob/main/usermods/)
- Общий [**readme_ru.md**](https://github.com/S-LABc/WLED-RU/blob/main/usermods/readme_ru.md)
