# EarthBound-Russian-Translation
Перевод игры EarthBound на русский язык

Проект создан благодаря программе CoilSnake ( http://kiij.github.io/CoilSnake/ ).

Русские буквы будут переведены в шестнадцатиричный код, указывающий на расположение изображения буквы в шрифте. Для большей информации можно пройти по ссылке https://github.com/kiij/CoilSnake/wiki/Tutorial%3A-Modifying-Game-Fonts

#Для перевода кириллицы в hex-код понадобятся:

* Pyhton 3.5.0 ( https://www.python.org/downloads/ )
* Командная Строка Windows

Нужный скрипт находится в папке PyScripts, файл CyrillicToCode.py.

Для его использования нужно открыть командную строку (Запуск от имени администратора) и ввести:

`cd *расположение папки PyScripts на диске*`

`py CyrillicToCode.py <файл, который вы хотите перевести - обычно input.txt> <1, если хотите перевести из шестнадцатиричного в кириллицу>`

***Пример:***
```
cd c:\\Development\EarthBound-Russian-Translation\PyScripts
py CyrillicToCode.py input.txt
```
