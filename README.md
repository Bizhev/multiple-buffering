# Multiple buffering
![alt text](doc/main.gif)

## Описание приложения
Программа служит для хранения нескольких буферов обмена, программа может работать в фоновом режиме т.е. можно копировать\вставлять горячими клавишами сразу.

## Установка
1. Скачать последнюю версию [Multibufer.zip](https://raw.githubusercontent.com/delphi-m/multiple-buffering/master/appDebug/MultiBuffer.zip)
1. Запустить приложение и с удовольствием его использовать 😉

## Как пользоваться?
Нужно сначала настроить какие буфера нам нужны, после пользуемся не открывая главное окно. Программа работает в фоновом режиме. 
Например, ставим курсор где нам нужно вставить, нажимаем нужную комбинацию(ctrl + 1) и программа сразу вставляет ячейку '1'.

## Главное окно:
![alt text](doc/form-main.png)
* 1 — Номер текущей страницы
* 2,3 — выводит об некоторых событиях, например когда текущее состояние страницы успешно сохранен.
* 4 — все кнопки "copy" всавляют содершимое поле (6) 
* 5 — текущее содержимое буфера вставляет в свою ячейку (6)
* 7 — служит пометкой для своего содержимого ячейки (6)

## Окно буфера:
![alt text](doc/form-bufer.png)
* 1 — тема текущей страницы
* 2 — выводит содержимое после буфера
* 3,4 — выводит номер текщей страницы

**Окно буфера обновляется только после нажатия ctrl + 0-9**

## Горячие кнопки
* `ctrl + 0-9` (4) — копирует в буфер обмена содержимое (6) и вставляет для windows (в консолях нужно еще нажать shift + insert) 
* `ctrl+Q` — переходит на предыдущую страницу 
* `ctrl+E` — переходит на следующую страницу
* `ctrl+B` — Вставляет текущую дату и время 
* `F4` — Переход на страницу
* `F6` — Меняет текущую страницу

* ![alt text](doc/button-edit-title.png) — служит для изменения темы страницы
* ![alt text](doc/button-up.png) — служит для перемещения ячейки на верх

## Лог изменений
### Версия 0.12.0
1. Добавлен progress bar при создании страницы 🎉
1. При скачивании из архива теперь доступна база на 99 страниц (не нужно ждать при первом запуске).
1. Добавлена форма "О программе", можно переходить на сайт программы.
1. Каждый шаг записываем в лог 🙌 

## Для разрабочиков
Кому интересно данное ПО прошу присоединится к его разработке.

**Для этого нужно:**

1. Форкнуть данный репозиторий (**Fork**)
1. Склонировать себе на локальную машину форкнутый репозиторий
1. Сделать необходимые изменения 
1. Сделать commit, отправить на 

