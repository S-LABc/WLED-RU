<p align="center">
<img src="/images/ru/wled_logo_akemi_ru.png">
</p>
  
# WLED на русском языке ✨
В этом репозитории находится **русскоязычная** версия проекта ***WLED v0.12.0***. Переведено не все содержимое, а только то, что мне было по-силам перевести. Допускаю, что местами могут быть ошибки или опечатки, которые я проглядел.

- Официальный репозиторий находится [*здесь*](https://github.com/Aircoookie/WLED).
- Официальный сайт проекта WLED находится [*здесь*](https://kno.wled.ge/).
- Официальные стабильные двоичные релизы ***v0.12.0*** находится [*здесь*](https://github.com/Aircoookie/WLED/releases/tag/v0.12.0).
- **Русскоязычные** стабильные двоичные релизы ***v0.12.0*** находится [*здесь*](https://github.com/S-LABc/WLED-RU/releases).
- Программа для записи прошивки в микроконтроллер [Flash Download Tools](https://www.espressif.com/en/support/download/other-tools). Или можно прошивать через [PlatformIO](https://platformio.org/) как это и было задумано.

Если нужно связаться со мной [romansklyar15@gmail.com](mailto:romansklyar15@gmail.com)

## ⚙️ Измененные файлы
Изменениям подвергся только англоязычный текст в некоторых исходных файлах. Никакие функции оригинальной прошивки изменены не были! Акцент перевода был сделан на пользовательском интерфейсе и сообщениях о действиях. Некоторые сообщения мне не удалось адаптировать к русскому языку, для этого пришлось бы изменить логику работы самой прошивки, другие же исходят от сторонних сервисов.
- [**platformio.ini**](https://github.com/S-LABc/WLED-RU/blob/main/platformio.ini) @ Выбор конфигурации платы и микроконтроллера


- [wled00/**FX.h**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/FX.h) @ Названия эффектов и палитр цветов


- [wled00/data/**404.htm**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/data/404.htm) @ Ошибка 404
- [wled00/data/**edit.htm**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/data/edit.htm)
- [wled00/data/**index.htm**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/data/index.js) @ Главное окно
- [wled00/data/**index.js**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/data/index.htm) @ Интерфес и собщения
- [wled00/data/**jsontest.htm**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/data/jsontest.htm)
- [wled00/data/**msg.htm**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/data/msg.htm)
- [wled00/data/**settings.htm**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/data/settings.htm) @ Перечень настроек
- [wled00/data/**settings_dmx.htm**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/data/settings_dmx.htm) @ Настройки DMX
- [wled00/data/**settings_leds.htm**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/data/settings_leds.htm) @ Настройки светодиодов
- [wled00/data/**settings_sec.htm**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/data/settings_sec.htm) @ Настройки безопасности
- [wled00/data/**settings_sync.htm**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/data/settings_sync.htm) @ Настройки синхронизации
- [wled00/data/**settings_time.htm**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/data/settings_time.htm) @ Настройки времени
- [wled00/data/**settings_ui.htm**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/data/settings_ui.htm) @ Настройки интерфейса пользователя
- [wled00/data/**settings_wifi.htm**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/data/settings_wifi.htm) @ Настройки Wi-Fi
- [wled00/data/**update.htm**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/data/update.htm) @ Обновление прошивки
- [wled00/data/**usermod.htm**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/data/usermod.htm)
- [wled00/data/**welcome.htm**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/data/welcome.htm) @ Страница приветствия

Изменены автоматически при использовании команд: **npm install**, **npm run dev** или **npm run build**
- [wled00/**html_other.h**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/html_other.h)
- [wled00/**html_settings.h**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/html_settings.h)
- [wled00/**html_ui.h**](https://github.com/S-LABc/WLED-RU/blob/main/wled00/html_ui.h)

## 💡 Официальные инструкции
- Как настроить окружение и скомпилировать *в картинках* → [How To Compile WLED .bin File](https://github.com/Aircoookie/WLED/wiki/How-To-Compile-WLED-.bin-File)
- Как настроить окружение и скомпилировать *другая версия* → [Compiling WLED](https://github.com/Aircoookie/WLED/wiki/Compiling-WLED)
- Как изменить и скомпилировать интерфейс пользователя *Web UI* → [Add own functionality](https://github.com/Aircoookie/WLED/wiki/Add-own-functionality#changing-web-ui)

## 🖼️ Изображения интерфейса
<img src="/images/ru/wled_desktop_mode.jpg" width="50%"><img src="/images/ru/wled_phone_mode.jpg" width="50%">

## ✌️ Остальное

Лицензия "MIT license"

Список авторов [тут](https://kno.wled.ge/about/contributors/)!

*Предупреждение от авторов проекта WLED:*

Если у вас может возникнуть эпилепсия от вспышек или света, не рекомендуется использовать это программное обеспечение.
Если вы все же хотите попробовать, не используйте режимы с эффектом стробоскопа, вспешек, шума, не задавайте высокую скорость эффектам.
В соответствии с лицензией MIT я не несу ответственности за любой ущерб, причиненный вам или любому другому человеку или оборудованию. 

