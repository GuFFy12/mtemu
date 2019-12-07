### ToDo list

#### Primary

- [ ] В панель отладки добавить поле для отображения устройства, с которым производится работа
- [ ] Добавить ограничения при выборе устройств. `PORT0` и `PORT1` - только для записи. `PORT2` и `PORT3` - только для чтения. Соответственно команды `Str Dev` и `Load Dev` должны блокировать выбор неподходящих
- [ ] Проверить отключение полей ввода при выборе той или иной F<sub>АЛУ</sub>, исправить при необходимости
- [ ] Проработать тексты label-ов полей ввода для каждой F<sub>АЛУ</sub>
- [ ] Продумать синхронизацию адресов между микрокомандами и командами (т.е. в обратную сторону). Использовать для этого поле AR в инструкции END/LDM
- [x] Вынести код для тетриса в отдельное поле
- [x] Устранить баг с последней пасхалкой, воспроизводится: 1, 2, 3, 0, 1
- [x] Исправить иконки диалоговых окон на нашу (стоит стандартная)
- [ ] Исправить коды яиц, чтобы не было вхождений одного в другой (использовать префиксный код)

#### Secondary

- [ ] Разработать руководство пользователя
- [ ] Разработать примеры программ, демонстрирующие новый (расширенный функционал)
- [ ] Разработать методичку с приведением примеров программ и пояснений к ним