# Temperature usermod

Основано на замечательном расширении `QuinLED_Dig_Uno_Temp_MQTT` от srg74 и 400killer!  
Это расширение пользователя будет считывать данные с подключенного датчика температуры DS18B20 (доступного на QuinLED Dig-Uno).
Температура отображается в разделе «Инфо» веб-интерфейса и публикуется в теме MQTT `/temperature`, если она включена.
Это пользовательское расширение может быть улучшено в будущем за счет добавления поддержки различных типов датчиков.

Если датчик температуры не обнаружен во время загрузки, это расширение будет отключено.

## Установка

Скопируйте файл `platformio_override.ini` в корневой каталог. Этот файл должен находиться в той же директории, что и `platformio.ini`.

### Определение параметров

* `USERMOD_DALLASTEMPERATURE`                      - добавьте это определение, чтобы включить это пользовательское расширение wled00\usermods_list.cpp
* `USERMOD_DALLASTEMPERATURE_FIRST_MEASUREMENT_AT` - количество миллисекунд после загрузки чтоюы выполнить первое измерение, по умолчанию 20 секунд

Все параметры можно указать на странице настроек Расширений пользователя(Usermods), включая контакт подключения датчика, выбор отображения температуры в градусах Цельсия или Фаренгейта и интервал измерения.

## Ссылки на проекты

* [QuinLED-Dig-Uno](https://quinled.info/2018/09/15/quinled-dig-uno/) - Проект
* [Srg74-WLED-Wemos-shield](https://github.com/srg74/WLED-wemos-shield) - Другой проект DIY WLED board

### Требования для PlatformIO

Если вы используете `platformio_override.ini`, вы сможете обновить список задач и увидеть свою пользовательскую задачу, например `env:d1_mini_usermod_dallas_temperature_C`.


Если вы не используете `platformio_override.ini`, вам, возможно, придется раскомментировать `OneWire@~2.3.5 ниже `[common]` в файле `platformio.ini`:

```ini
# platformio.ini
...
[platformio]
...
; default_envs = esp07
default_envs = d1_mini
...
[common]
...
lib_deps =
  ...
  #Для датчика Dallas раскомментируйте следующую строку
  OneWire@~2.3.5
...
```

## Список изменений

2020-09-12 
* Changed to use async, non-blocking implementation
* Do not report low temperatures that indicate an error to mqtt
* Disable plugin if temperature sensor not detected
* Report the number of seconds until the first read in the info screen instead of sensor error
2021-04
* Adaptation for runtime configuration.