# betting_shop

Чат-бот в Telegram для ставок на локальные события в ИШ

# Участники
+ Борисова Ксения 
+ Прокофьев Илья
+ Лукьянов Андрей

# Проблема
В инженерной школе уже давно существует культура ставок и различных споров, связанных с внутренними событиями нашего потока, тем не менее, все еще отсутствует платформа, которая обеспечивает данную деятельность.

# Потенциальные пользователи
+ Студенты ИШ, которые делали "ставки", организовываясь самостоятельно, так как никакой площадки на данный момент не имеется
+ Студенты ИШ, раннее не занимающиеся подобным, но с появлением нашей платформы решившие внести элемент азарта в образовательный процесс и свою жизнь
+ Будущие студенты ИШ
+ Преподаватели ИШ

# MVP



# Основные компоненты системы



# Точки расширения
+ Поддержка разных типов аккаунтов с разными возможностями
+ Расширение до масштабов всего университета
+ Подключение платежной системы

# Основные сценарии использования
1. Пользователь, захотевший ознакомиться с ботом
  + Заходит в telegram, вводит /start и получает информацию, как пользоваться ботом.
2. Заинтересовавшийся пользователь, захотевший сделать ставку
    + Выбирает раздел "События" 
    + Выбирает интересное для себя событие
    + Бот выводит список линий на данное событие
    + Пользователь выбирает линию и вводит размер ставки
    + Когда событие проходит, все выигравшие получают все, поставленное проигравшими (с учетом комиссии букмекера), поделенное в зависимости от того, какую долю внес каждый
3. Пользователь, захотевший предложить свое событие
  + Выбирает раздел "Предложить событие"
  + Вводит название события и список предлагаемых линий
  + Это событие появляется во вкладке "События"
4. Пользователь, захотевший проверить свой счет, посмотреть, в каких событиях он принимает участие
  + Выбирает раздел "Аккаунт"
  + Пользователю показывается остаток на его счету, события, на которые он ставил (с суммой, которую поставил)
