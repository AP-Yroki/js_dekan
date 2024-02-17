# js_dekan

Введение
К вам обратилась компания по разработке игр для веб-сайтов. Компания просит
помочь в разработке веб-игры. 
Ваша задача – только клиентское программирование.
Описание проекта и задач
Экран входа
При переходе на сайт с игрой должен быть отображен экран входа.
На данном экране отображаются карта, на которой можно играть.
После выбора карты пользователь должен ввести свое имя и нажать на кнопку
для начала игры.
При клике на кнопку экран должен смениться на игровой.
Игровой экран
На игровом экране должна отображаться следующая информация:
 Имя, введенное пользователем
 Текущее время в системе в формате чч:мм:сс
 Время прошедшее с начала игры в формате мм:сс
 Счетчик жизней – при старте у игрока 5 жизней
Игровое поле представляет собой карту (вид сверху), по которой игрок должен
пройти, используя стрелки на клавиатуре.
Игрок должен двигаться в 4 направлениях.
В процессе игры, каждые 3 секунды на карте должны появляться монстры
(10 шт) и ловушки (2 шт).
Монстры должны двигаться в случайном направлении и пропадать за
границей игрового поля.
Ловушки должны находиться на месте и иметь видимую зону поражения.Если игрок сталкивается с монстром или попадает в ловушку, то теряет 1
жизнь.
После столкновения игрока с монстром/ловушкой они должны пропасть.
Задача игрока дойти до конца карты.
Должна быть возможность поставить игру на паузу нажав кнопку ESC.
Повторное нажатие должно продолжить игру. Во время паузы все
интерактивные действия (анимация, секундомер, фрукты, корзина) должны быть
приостановлены.
Когда жизни будут равны нулю, то игра должна закончиться и должен
отобразиться экран с результатами.
Экран с результатами
На экране с результатами необходимо отобразить статистику игры:
 Время, которое игрок продержался в игре
 Количество монстров, с которыми игрок столкнулся
 Количество ловушек, в которые игрок попал
 Сколько жизней осталось у игрока
На экране с результатами есть кнопка «Играть сначала» при клике, на которую
игра должна сразу перезапуститься.
