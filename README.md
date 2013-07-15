cuSel &mdash; кастомные селекты на jQuery
=====

Возрождение проекта cuSel

Скачать https://raw.github.com/fetis/cusel/master/build/cusel.min.js  
В файл включены плагины jScrollPane и mousewheel.

Особенности
-----------
- умное позиционирование (если подключена библиотека jQuery UI). Если выпадающему списку не хватает места вниз, 
он будет открываться вверх

Зависимости
------------
- jQuery
- [jQuery Migrate плагин](http://plugins.jquery.com/migrate/) (планируется убрать в будущих версиях)
- jQuery Mousewheel плагин, входит в мин-версию
- jScrollPane, переделанная версия плагина jScrollPane. Входит в мин-версию

Документация
------------

http://www.xiper.net/collect/html-and-css-tricks/verstka-form/nice-select-jquery.html

План работ
----------
- [x] Открытие селекта поверх элементов
- [ ] Переделать на jQuery плагин
- [ ] Убрать поддержку старых бразуеров
- [ ] Убрать использование $.browser, т.к. это несовместимо с последними версиями jQuery.
- [ ] Программная установка значения селекта. Сейчас это возможно через непосредственный вызов .click() на опции.
