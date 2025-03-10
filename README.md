# VKR_painting_of_city_objects

Управления:
Учет художников. (Задача ведения «проектов» в личном кабинете художника.) (Задача демонстрации квалификации и предыдущих работ каждого художника. Задача демонстрации идеи художника. Задача ведения требований художников для реализации (одному нужны краски, другому битое стекло для мозаики).)

Учет объектов. (Задача выдвижения кандидатуры городского объекта на роспись.) (Задача ведения рейтинга объектов (каждые 6 месяцев 1, 2 и 3 места рейтинга будут выдвинуты на роспись).) Задача предоставления характеристик объекта (площадь покраски, кривизна, другие факторы). Учет стоимостей проектов (сколько средств администрация готова выделить на проект)

Учет отзывов по расписным объектам.
Разыгрывание тендеров среди художников (голосование).
Учет голосов за самые актуальные росписи (люди сами выберут самый актуальный объект под роспись). Учет сроков голосования.
Учет завершенных росписей.
Анализ росписей. (поиск с фильтрами по БД сайта)

Технические:
Задача визуализации карты с выдвинутыми кандидатурами (дружелюбный интерфейс).
Задача приоритизации голосов местных жителей. (Подумать как быть с голосованием)
Задача предотвращения вбросов за определенный объект.

Принцип выдвижения объекта на роспись:
1)	Пользователь регистрируется или входит в аккаунт
2)	На карте администрация отмечает потенциальные места с объектом для росписи (должен приложить фото)
3)	Пользователь может поставить лайк любой метке на карте и оставить отзыв.
4)	Каждая метка попадает в рейтинг «Выдвижение на роспись», позиция в рейтинге определяется количеством лайков.
- Каждой метке соответствует один объект по определенным координатам.
- Если количество лайков совпало, то объекты делят одно место в рейтинге.
5)	Каждые X месяцев N первых объекта в рейтинге «Выдвижение на роспись» автоматически выдвигаются на роспись, при этом они исключаются из него.
6)	Эти N выбранных объекта должны получить описательные характеристики, если никто ранее не указал эти данные.
7)	На роспись выбранных объектов разыгрываются тендеры. Художники начинают подавать свои заявки на роспись, прикрепляя свои прошлые проекты, заслуги, идею, требования и т.д. (Формируются рейтинги художников на каждый выбранный объект) (Художники прикрепляют полноценный проект).
8)	Позицию каждого художника в рейтинге определяет количество лайков за его идею.
9)	После истечения таймера выбирается один первый художник:
- Если несколько художников делят первое место, то пользователям доступны варианты:
•	Поделить объект между художниками
•	Выбрать одного из всех
•	Отказаться от всех
10)	Художник выигрывает тендер и средства, объект снимается с голосований и отмечается на карте как «В работе».
11)	Когда художник закончил, проект по росписи помечается «Выполнено».
Принцип просмотрен, он хороший.


