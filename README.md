# Galaxy-Online-Battle-Calculator
A calculator of battle outcomes for online browser game Galaxy Online.

Uses PySimpleGUI. Requires python3-tk

Right now there is no translation of text, it is all in russian, because the main audience is russian. But I may add english, if it will be needed.
You can contact me via telegram @fadedness

## Installation
install Python3

When installing Python on Windows or MacOs from python.org make sure you check the box with the "td/tk and IDLE" in Optional Features

Linux
```
apt install python3-pip
sudo apt-get install python3-tk
pip3 install PYSimpleGUI
```
Macos

You'd better install python from python.org with all Optional Features

then download GO_calculator.py, in terminal change to folder with it and enter:
```
pip3 install PYSimpleGUI
```
wait for installation and enter
```
python3 GO_Calculator.py
```

## Added GO_Calculator_android.py
It is not a native application for android.

It is a GUI adaptation to be run on android via Pydroid3 application, that can be found on google play store.

## Добавлен файл GO_Calculator_android.py
Это не приложение на андроид.

Это адаптация интерфейса для запуска на андроиде через приложение Pydroid3, которое можно найти в google play store.

## Установка и запуск скрипта на Windows
Устанавливаем Python 3 с python org, при установке проверяем, что в "Optional Features" стоит галочка напротив "td/tk and IDLE".
В командной строке пишем
```
pip3 install PySimpleGUI
```
Скачиваем GO_Calculator.py
Запускаем его.
## Описание
Эта программа - калькулятор - это инструмент для расчётов. Выглядит с первого раза страшно, но в ней несложно разобраться.
Минимальные действия для использования:
В первой вкладке вводим количество кораблей для Флота 1 и Флота 2 и нажимаем кнопку Рассчитать потери.

В релизах есть экзешник - Go_Calculator.exe - на него могут ругаться антивирусы. Поэтому для снижения риска изучаем код, гуглим, что надо для запуска скрипта пайтона на винде и запускаем скрипт .py напрямую, минуя exe файл ;-)
