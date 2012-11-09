schedule-admin
==============

Расписание занятий. Админ.часть.

09-11-2010 Выполнены задачи:
----------------------------
* В лайтбоксе записи на занятие не должно быть маркированного списка в правой колонке.
* Между числами в дате занятия в правой колонке должны стоять точки.
* Если название занятия (или любое другое поле, в т.ч. поле ошибки) слишком длинное, то переносимая строчка не должна растягиваться на всю ширину столбца, выравнивание текста должно быть по левому краю. text-align: left;
* Сообщение об ошибке "Номер вашего абонемента (клубной карты) не найден." должно влазить в 2 строки. При этом поле ввода номера должно подсвечиваться красным цветом. Можно выводить сообщение: "Введен неверный номер абонем. (клубной карты)".
* Немного напутаны отступы в правом столбце (высоты строк или др.), в итоге сообщение об ошибке заполнения из двух строк должно быть на уровне кнопки "записаться", а оно значительно ниже.
* В выпадающем списке скрыть/убрать пункт "Разовое посещение по купону". Эти посетители будут записываться только по телефону, а вносить в список записавшихся их будет администратор (наверное, через админку сайта).
