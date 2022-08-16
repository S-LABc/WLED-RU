<p align="center">
<img src="/images/ru/wled_logo_akemi_ru.png">
</p>
  
# WLED на русском языке ✨
В этом репозитории находятся **русскоязычные** версии проекта ***WLED***. Переведено лишь то, что мне было по-силам. Могут встречаться ошибки или опечатки, которые я проглядел. *Переведено одно расширение пользователя* **battery_status_basic**.

- Официальный [GitHub репозиторий](https://github.com/Aircoookie/WLED)
- Официальный [сайт проекта](https://kno.wled.ge/)
- Официальные [файлы релизов](https://github.com/Aircoookie/WLED/releases)
- **Русскоязычные** [файлы релизов](https://github.com/S-LABc/WLED-RU/releases)
- Измененные исходные [файлы](https://github.com/S-LABc/WLED-RU/wiki/%D0%98%D0%B7%D0%BC%D0%B5%D0%BD%D0%B5%D0%BD%D0%BD%D1%8B%D0%B5-%D1%84%D0%B0%D0%B9%D0%BB%D1%8B)

## 🖼️ Изображения
<img src="/images/ru/wled_phone_mode.jpg" width="50%"><img src="/images/ru/wled_phone_mode_info.jpg" width="50%">

## ✌️ От автора

*Лицензия [MIT license](https://raw.githubusercontent.com/Aircoookie/WLED/master/LICENSE)*

[Список авторов!](https://kno.wled.ge/about/contributors/)

*Предупреждение от авторов проекта WLED*

Если у вас может возникнуть эпилепсия от вспышек или света, не рекомендуется использовать это программное обеспечение.
Если вы все же хотите попробовать, не используйте режимы с эффектом стробоскопа, вспешек, шума, не задавайте высокую скорость эффектам.
В соответствии с лицензией MIT я не несу ответственности за любой ущерб, причиненный вам или любому другому человеку или оборудованию. 

## 💡 Инструкции
Для модулей *ESP32* сначала нужно зашить загрузчик **esp32_bootloader_vX.bin** (X - номер версии) по адресу **0x0**, а потом шить файл прошивки WLED по адресу **0x10000**. Для модулей ESP8266 просто шить файл прошивки WLED по адресу 0x0. Актуально для Flash Download Tools

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
