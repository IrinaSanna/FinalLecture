# 1. Перечень автоматизируемых сценариев

## Первый сценарий через блок «Направления обучения»

### Шаги воспроизведения:
1. В браузере Google Chrome открыть страницу по адресу http://netology.ru.

*Ожидаемый результат:* открылась страница http://netology.ru.

2.	В каталоге «Направления обучения» кликнуть на каталог «Программирование».

*Ожидаемый результат:* осуществлен переход на станицу https://netology.ru/development.

3.	В списке каталога «Программирование» найти профессию «Инженер по автоматизации» и кликнуть по ней.
*Ожидаемый результат:* осуществлен переход на станицу https://netology.ru/programs/automation-engineer.

4.	Проскролить страницу до формы записи на курс.

*Ожидаемый результат:* форма для записи на курс находится внизу страницы.

5.	Осуществить позитивные и негативные проверки.

*Ожидаемый результат:* форма проверена по тестовым данным из раздела «Тестовые данные для проверки формы записи на курс».

## Второй сценарий через «Каталог курсов» поисковой строки

### Шаги воспроизведения:
1.	В браузере Google Chrome открыть страницу по адресу http://netology.ru.

*Ожидаемый результат:* открылась страница http://netology.ru.

2.	Выбрать меню «Каталог курсов».

*Ожидаемый результат:* появилось поисковое поле для ввода запроса и кнопка «Найти курс».

3.	В поисковую строку ввести профессию «Инженер по автоматизации» и нажать Enter либо кнопку «Найти курс».

*Ожидаемый результат:* отобразился результат поиска.

4. Кликнуть на результат поиска.

*Ожидаемый результат:* осуществлен переход на станицу https://netology.ru/programs/automation-engineer.

5.	Пролистать страницу до формы записи на курс.

*Ожидаемый результат:* форма для записи на курс находится внизу страницы.

6.	Осуществить позитивные и негативные проверки

*Ожидаемый результат:* форма проверена по тестовым данным из раздела «Тестовые данные для проверки формы записи на курс».

## Третий сценарий через «Каталог курсов» выбора блока «Профессии»

### Шаги воспроизведения:
1.	В браузере Google Chrome открыть страницу по адресу http://netology.ru.

*Ожидаемый результат:* открылась страница http://netology.ru

2.	Выбрать меню «Каталог курсов».

*Ожидаемый результат:* появилось поисковое поле для ввода запроса и кнопка «Найти курс» и блоки «Направления обучения».

3.	Выбрать каталог «Программирование».

*Ожидаемый результат:* осуществлен переход на станицу https://netology.ru/development.

4.	В списке каталога «Программирование» найти профессию «Инженер по автоматизации» и кликнуть по ней.

*Ожидаемый результат:* осуществлен переход на станицу https://netology.ru/programs/automation-engineer.

5.	Пролистать страницу до формы записи на курс.

*Ожидаемый результат:* форма для записи на курс находится внизу страницы.

6.	Осуществить позитивные и негативные проверки.

*Ожидаемый результат:* форма проверена по тестовым данным из раздела «Тестовые данные для проверки формы записи на курс».

## Четвертый сценарий через футер и выбора блока «Программирование» раздела «Обучение

### Шаги воспроизведения:
1.	В браузере Google Chrome открыть страницу по адресу http://netology.ru.

*Ожидаемый результат:* открылась страница http://netology.ru.

2.	Проскролить страницу до футера.

*Ожидаемый результат:* отображен раздел «Обучение» с перечнем направлений.

3.	Выбрать блок «Программирование».

*Ожидаемый результат:* осуществлен переход на станицу https://netology.ru/development.

4.	В списке каталога «Программирование» найти профессию «Инженер по автоматизации» и кликнуть по ней.

*Ожидаемый результат:* осуществлен переход на станицу https://netology.ru/programs/automation-engineer.

4.	Пролистать страницу до формы записи на курс.

*Ожидаемый результат:* форма для записи на курс находится внизу страницы.

5. Осуществить позитивные и негативные проверки.

*Ожидаемый результат:* форма проверена по тестовым данным из раздела «Тестовые данные для проверки формы записи на курс».

# 2. Перечень используемых инструментов с обоснованием выбора

2.1. IntelliJ IDEA Community Edition 2023.3.3 JUnit5 с использованием библиотеки selenide:

* простая настойка (установка плагина и подключение зависимости в IDEA).
*	поиск элементов по тексту, test-id, CSS селектору, атрибуту.
* читабельный (понятный) код.
* вывод логики страниц в отдельный класс PageObject. При каких-либо изменениях логики на странице можно будет поменять код только для одной странице.

# 3. Перечень необходимых разрешений, данных и доступов.

3.1. Разрешение на написание и прогон автотестов для формы записи.

3.2. Доступ к тестовой базе данных для проверки конечной точки бизнес-логики. То есть, сайт может отработать правильно (форма отправилась, сообщение о записи на курс появилось), но данные могут не записаться в базу.

# 4. Перечень и описание возможных рисков при автоматизации

4.1. Изменение страницы (перенос функционала на другую страницу).

# 5. Перечень необходимых специалистов для автоматизации

5.1. Автотестировщик.

# 6. Интервальная оценка с учётом рисков в часах
6.1. 5 дней.

# Тестовые данные для проверки формы записи на курс

## 1. Позитивная проверка формы записи	
1.1. Ввести валидное имя на кириллице.

*Ожидаемый результат:* поле приняло значение.

1.2. Ввести валидный телефон из 10 цифр.

*Ожидаемый результат:* поле приняло значение.

1.3. Ввести электронную почту на латинице со спецсимволом @.

*Ожидаемый результат:* поле приняло значение.

1.4. Отправить форму через кнопку «Записаться».

*Ожидаемый результат:* форма отправилась. Появилось сообщение «Вы записаны на курс».

## 2. Негативная проверка формы записи	
2.1. Ввести в поле «Имя» латиницу, например, Petr. Остальные поля заполнить валидными данными.

*Ожидаемый результат:* появляется сообщение под полем ввода красным цветом.

2.2. Ввести в поле «Имя» цифры, например, 123. Остальные поля заполнить валидными данными.

*Ожидаемый результат:* появляется сообщение под полем ввода красным цветом.

2.3. Оставить поле пустым. Остальные поля заполнить валидными данными.

*Ожидаемый результат:* появляется сообщение под полем ввода красным цветом.

2.4. Ввести невалидный номер телефона из 9 цифр, например, +7999111223. Остальные поля заполнить валидными данными.

*Ожидаемый результат:* появляется сообщение под полем ввода красным цветом.

2.5. Ввести электронную почту без @, например, test.ru. Остальные поля заполнить валидными данными.

*Ожидаемый результат:* появляется сообщение под полем ввода красным цветом.