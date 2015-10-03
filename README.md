# EarthBound-Russian-Translation
Перевод игры EarthBound на русский язык

Проэкт создан благодоря программе CoilSnake ( http://kiij.github.io/CoilSnake/ ). Компиляция требует ROM игры Earthbound.

Русские буквы переведены в шестнадцетеричный код, указывающие на расположение изображения буквы в шрифте. Для большей информации пройдите по ссылке https://github.com/kiij/CoilSnake/wiki/Tutorial%3A-Modifying-Game-Fonts

#Для использования скрипта Пайтона, вам понадобится:

* Pyhton 3.5.0 ( https://www.python.org/downloads/ )
* Коммандная Строка Windows

Скрипт, который вам нужен находится в папке PyScripts, файл CyrillicToCode.py.

Для его использования откройте коммандную строку (Запуск от имени администратора), введите:
`cd *расположение папки PyScripts на вашем диске*`
`py CyrillicToCode.py <файл, который вы хотите перевести - обычно input.txt> <1, если хотите перевести из шестнадцетеричного в кириллицу>`
**Пример:**
```
cd c:\\Development\EarthBound-Russian-Translation\PyScripts
py CyrillicToCode.py input.txt
```