ТЗ приложения «Английская лексика»(EWords)

**Концепция и основная идея**

Создание данного приложения необходимо для помощи в обучении **Пользователей**
лексикой английского языка.

**Задачи, решаемые при помощи приложения**

Основная **цель** – организовать личный словарь английского языка с удобным
интерфейсом для каждого **Пользователя**, а так же регулярно подталкивать
**Пользователя** к обучению незнакомых слов английского языка посредством
интерактивных уведомлений.

**Этапы работы по созданию системы**

Работа по созданию приложения разделяется на следующие этапы:

-   Верстка данного ТЗ

-   Разработка дизайна приложения

-   Выбор технологии взаимодействия с БД и оптимизация запросов к реляционной БД
    серверной части

-   Выбор технологии и оптимизация передачи данных клиент-сервер

-   Доработка интерфейса серверной части приложения

-   Доработка интерфейсов клиентской части приложения

-   Тестирование

**Требование к проекту**

Язык серверной и клиентской части: русский

Серверная часть и клиентские части должны быть написаны на языке С\#. Серверная
часть должна работать под ОС Windows и иметь графический интерфейс Windows
(Windows Form). Обе клиентские части (с веб интерфейсом и андройд приложение)
должны быть написаны на языке C\#.

База данных, технология взаимодействия с базой данных и передачи данных между
клиентом и сервером определяется в процессе разработки.

**Общие требования к дизайну экранов пользователя**

-   Андройд приложение

Дизайн указанного приложения должен быть не хуже чем дизайн мобильно приложения
Quizlet (quizlet.com)

Элементы графического дизайна должны представлять собой простые геометрические
фигура разных цветов (оттенков)

Внешний вид каждого из экранов должен быть разработан под горизонтальное и
вертикальное положение экрана мобильный устройств.

-   веб-интерфейс

**Карта проекта мобильного приложения – экраны пользователя**

*экран АВТОРИЗАЦИИ*

На данном этапе имеются следующие возможности:

-   Кнопка зарегистрироваться (РЕГИСТРАЦИЯ)

-   Пройти авторизацию(поле ввода логина, поле ввода пароля, кнопка войти)

-   Восстановить пароль(ВОСТАНОВЛЕНИЕ ПАРОЛЯ) - доступно после ввода логина, при
    неверном вводе логина, нажатие кнопки приводит отображению надписи об
    ошибке, остаемся на экране авторизации.

После успешной авторизации попадаем в окно словаря(КАТАЛОГ)

*экран РЕГИСТРАЦИИ*

На данном этапе имеются следующие возможности:

-   Заполнить анкету (поля: логин, пароль(не менее 4 символов), секретный
    вопрос, ответ на секретный вопрос, кнопка подтвердить регистрацию, капча)

После регистрации попадаем в окно авторизации (АВТОРИЗАЦИЯ)

*экран ВОСТАНОВЛЕНИЕ ПАРОЛЯ*

На данном этапе имеются следующие возможности:

-   ответитить на секретный вопрос (поле логин, поле секретный вопрос, надпись
    секретный вопрос, кнопка ответить на секретный вопрос)

После успешной попытки попадаем в окно (ИЗМЕНИТЬ ПАРОЛЬ)

*экран ИЗМЕНИТЬ ПАРОЛЬ*

На данном этапе имеются следующие возможности:

-   ввести новый пароль

-   повторить пароль

-   ввести капчу

После успешной попытки попадаем в окно (КАБИНЕТ)

*экран КАТАЛОГ*

На данном этапе имеются следующие возможности:

-   Перейти в личный кабинет (КАБИНЕТ)

-   экспортировать словарь (ЭКСПОРТ СЛОВАРЯ)

-   Добавить словарь (НОВЫЙ СЛОВАРЬ)

-   Открыть доступный словарь (СЛОВАРЬ)

-   вход в режим обучения(КОНФИГУРАЦИЯ ОБУЧЕНИЯ)

Переход в словарь(СЛОВАРЬ) происходит нажатие на доступный словарь, при
длительном нажатии всплывающее окно предлагает удалить словарь.

Каждый словарь помечается кол-вом слов в словаре.

*Экран КАБИНЕТ*

На данном этапе имеются следующие возможности:

-   Изменить пароль (ИЗМЕНИТЬ ПАРОЛЬ)

-   ползунок включить/отключить все интерактивные уведомления (вкл/откл)

-   просмотреть/изменить имя пользователя

-   просмотреть/изменить секретный вопрос

-   просмотреть/изменить ответ секретный вопрос

-   увидеть свою статистику (количество ответов без подсказки/всего вопросов,
    кол-во знакомых слов, кол-во усвоенных слов, слов в словарях, место в общем
    рейтинге)

-   LOGOUT (кнопка logout)

*экран НОВЫЙ СЛОВАРЬ*

На данном этапе имеются следующие возможности:

-   ввести название нового словаря (поле имя словаря)

-   ввести описание раздела (поле описание словаря)

-   выбрать интенсивность интерактивных уведомлений для данного словаря
    (ползунок легче ___*___ интенсивнее)

-   изменить статус словаря (публичный/приватный)

-   кнопка добавить поле (в режиме онлайн добавляет 2 поля для ввода нового
    слова и перевода, не более 10 пар полей)

-   метка удалить добавленное поле

-   кнопка сохранить

-   увидеть перевод внешнего переводчика (translate.ru или др.) в еще одном поле
    при наличие онлайн подключения.

После нажатия кнопки сохранить переходим в окно каталог (КАТАЛОГ)

!Возврат в предыдущее меню осуществляется кнопкой назад устройства Андройд. При
наличие заполненных полей всплывающий комментарий должен предлагать нажать на
кнопку назад второй раз для выхода в предыдущее меню без сохранений.

*экран ЭКСПОРТ СЛОВАРЯ*

На данном этапе имеются следующие возможности:

-   ввести свое название экспортированного словаря (поле имя словаря)

-   ввести описание словаря (поле описание словаря+ не редактируемое курсивом
    дата экспорта и название пользователя/словаря родителя)

-   выбрать доступный для экспорта словарь из списка (список экспорт)+кнопка
    экспорт для подтверждения экспорта

-   выбрать интенсивность интерактивных уведомлений для данного словаря
    (ползунок легче ___*___ интенсивнее)

-   изменить статус словаря (публичный/приватный)

-   кнопка добавить поле (в режиме онлайн добавляет 2 поля для ввода нового
    слова и перевода)

-   кнопка сохранить

-   метка удалить добавленное поле

-   метка удалить слово

-   увидеть перевод внешнего переводчика (translate.ru или др.) в еще одном поле
    при наличие онлайн подключения.

После нажатия кнопки сохранить переходим в окно каталог (КАТАЛОГ)

!Возврат в предыдущее меню осуществляется кнопкой назад устройства Андройд. При
наличие заполненных полей всплывающий комментарий должен предлагать нажать на
кнопку назад второй раз для выхода в предыдущее меню без сохранений.

*экран СЛОВАРЬ*

На данном этапе имеются следующие возможности:

-   изменить описание словаря

-   изменить название словаря

-   изменить интенсивность интерактивных уведомлений для данного словаря
    (ползунок легче ___*___ интенсивнее)

-   изменить статус словаря (публичный/приватный)

-   кнопка добавить поле (в режиме онлайн добавляет 2 поля для ввода нового
    слова и перевода)

-   кнопки сохранить(при наличии изменений)

-   увидеть перевод внешнего переводчика (translate.ru или др.) в еще одном поле
    при наличие онлайн подключения.

-   метка удалить слово

-   метка удалить добавленное поле

-   увидеть статус каждого слова словаря (незнакомое/знакомое и т.д.)

После нажатия кнопки сохранить остаемся в словаре

!Возврат в предыдущее меню осуществляется кнопкой назад устройства Андройд. При
наличие заполненных полей всплывающий комментарий должен предлагать нажать на
кнопку назад второй раз для выхода в предыдущее меню без сохранений.

*экран КОНФИГУРАЦИЯ ОБУЧЕНИЯ*

На данном этапе имеются следующие возможности:

-   увидеть все не пустые словари и выбрать нужные

-   кнопка старт(активна если хотя бы один словарь выбран) (ОБУЧЕНИЕ)

*экран ОБУЧЕНИЕ*

На данном этапе имеются следующие возможности:

-   ответить на предложенный вопрос (поле ответ)

-   кнопка к следующему(переходит к следующему вопросу только если ответ верный)

-   значок получить подсказку

-   увидеть статистику обучения (ответов без подсказки/всего вопросов)

-   увидеть таймер

Обучение длится минуту или до истечения актуальных слов, затем автовозрат.

*Алгоритм обучения: частота опроса слова в обучении и в интерактивных
уведомлениях зависит от статуса слова (незнакомое/знакомое и т.д.). Переход от
одного статуса в другой и обратно зависит от кол-ва правильных и неправильных
ответов по этому слову (кол-во правильных-кол-во неправильных > N). Слово,
которое находится в финальном статусе, больше не опрашивается, т.е. не может
перейти в другой статус.*

**Карта проекта серверного приложения – экраны сервера**

*ГЛАВНАЯ СТРАНИЦА*

На данном этапе имеются следующие возможности:

-   поля авторизации (поле ввода логина, поле ввода пароля, кнопка войти)

-   После успешной авторизации указанные ниже вкладки становятся доступны и
    скрываются поля авторизации

-   статистические данные: общее кол-во зарегистрированных пользователей, блок
    последних зарегистрированных пользователей, общее кол-во словарей, блок
    последних добавленных словарей, общее кол-во залитых слов, блок последних
    добавленных слов

-   вкладки УПРАВЛЕНИЕ ПОЛЬЗОВАТЕЛЯМИ, УПРАВЛЕНИЕ СЛОВАРЯМИ, СЛОВА, которые
    становятся доступными после авторизации

Пароль администратора стандартный (abcd), считывается из файла, который
храниться в папке с программой сервера, логин admin.

*УПРАВЛЕНИЕ ПОЛЬЗОВАТЕЛЯМИ*

На данном этапе имеются следующие возможности:

-   просмотреть список пользователей в табличной форме с различными вариантами
    сортировки

-   возможность выделения группы пользователей (с помощью Checkbox)

-   кнопка обновить список

-   кнопка добавить пользователя (НОВЫЙ ПОЛЬЗОВАТЕЛЬ)

-   кнопка удалить (доступна после выделения пользователя(группы пользователей))

-   щелчком по пользователю перейти в профиль пользователя (ПРОФИЛЬ
    ПОЛЬЗОВАТЕЛЯ)

*УПРАВЛЕНИЕ СЛОВАРЯМИ*

На данном этапе имеются следующие возможности:

-   просмотреть список словарей в табличной форме с различными вариантами
    сортировки

-   возможность выделения группы словарей

-   кнопка обновить список (с помощью Checkbox)

-   кнопка удалить (доступна после выделения словаря(групп словарей))

-   щелчком по словарю перейти в словарь (СЛОВАРЬ)

*СЛОВА*

На данном этапе имеются следующие возможности:

-   просмотреть список слов из всех словарей в табличной форме с различными
    вариантами сортировки, в т.ч. общий суммарный процент правильных ответов по
    данному слову

-   возможность выделения группы слов (с помощью Checkbox)

-   кнопки обновить список, удалить выделенные

-   кнопка удалить (доступна после выделения слова(группы слов))

*НОВЫЙ ПОЛЬЗОВАТЕЛЬ*

На данном этапе(организован в появляющемся поверх основного окна окошке) имеются
следующие возможности:

-   Заполнить анкету (поля: ФИО, логин, пароль(не менее 4 символов), секретный
    вопрос, ответ на секретный вопрос, кнопка подтвердить регистрацию, капча)

*ПРОФИЛЬ ПОЛЬЗОВАТЕЛЯ*

На данном этапе(организован в появляющемся поверх основного окна окошке) имеются
следующие возможности:

-   Просмотреть и изменить пароль (поле пароль)

-   ползунок включить/отключить все интерактивные уведомления (вкл/откл)

-   Просмотреть и изменить имя пользователя (поле имя пользователя)

-   просмотреть секретный вопрос (поле секретный вопрос)

-   просмотреть и изменить ответ на секретный вопрос (поле ответ на секретный
    вопрос)

-   увидебть и сбросить статистику (количество ответов без подсказки/всего
    вопросов, кол-во знакомых слов, кол-во усвоенных слов, слов в словарях,
    место в общем рейтинге) и кнопка сброс статистики

-   кнопка сохранить изменения (появляется при наличии хотя-бы одного изменения)

-   перейти во вкладку каталог пользователя (КАТАЛОГ)

*КАТАЛОГ*

Реализован во вкладке окна ПРОФИЛЬ ПОЛЬЗОВАТЕЛЯ. На данном этапе имеются
следующие возможности:

-   экспортировать словарь (ЭКСПОРТ СЛОВАРЯ)

-   возможность выделения группы словарей (с помощью Checkbox)

-   кнопка удалить (доступна после выделения словаря(группы словарей))

-   кнопки обновить список

-   Добавить словарь (НОВЫЙ СЛОВАРЬ)

-   Открыть доступный словарь (СЛОВАРЬ)

Каждый словарь помечается кол-вом слов в словаре.

*экран НОВЫЙ СЛОВАРЬ*

На данном этапе(организован в появляющемся поверх основного окна окошке) имеются
следующие возможности:

-   ввести название нового словаря (поле имя словаря)

-   ввести описание словаря (поле описание словаря)

-   выбрать интенсивность интерактивных уведомлений для данного словаря
    (ползунок легче ___*___ интенсивнее)

-   изменить статус словаря (публичный/приватный)

-   кнопка добавить поле (в режиме онлайн добавляет 2 поля для ввода нового
    слова и перевода)

-   метка удалить добавленное поле

-   кнопка сохранить (при наличии изменений)

-   увидеть перевод внешнего переводчика (translate.ru или др.) в еще одном поле
    при наличие онлайн подключения.

После нажатия кнопки сохранить переходим в окно каталог (КАТАЛОГ)

!Возврат в предыдущий экран осуществляется закрытием окна нового словаря. При
наличие заполненных полей новых слов и попытке выхода MessageBox должен спросить
о выходе без сохранений.

*экран ЭКСПОРТ СЛОВАРЯ*

На данном этапе(организован в появляющемся поверх основного окна окошке) имеются
следующие возможности:

-   ввести свое название экспортированного словаря (поле имя словаря)

-   ввести описание словаря (поле описание словаря + не редактируемая дата
    экспорта и название пользователя/словаря родителя)

-   выбрать доступный для экспорта словарь из списка (список экспорт) + кнопка
    экспорт (для подтверждения)

-   выбрать интенсивность интерактивных уведомлений для данного словаря
    (ползунок легче ___*___ интенсивнее)

-   изменить статус словаря (публичный/приватный)

-   кнопка добавить поле (в режиме онлайн добавляет 2 поля для ввода нового
    слова и перевода)

-   кнопка сохранить (при наличии изменений)

-   метка удалить добавленное поле

-   метка удалить слово

-   увидеть перевод внешнего переводчика (translate.ru или др.) в еще одном поле
    при наличие онлайн подключения.

После нажатия кнопки сохранить переходим в окно каталог (КАТАЛОГ)

!Возврат в предыдущий экран осуществляется закрытием окна нового словаря. При
наличие заполненных полей новых слов и попытке выхода MessageBox должен спросить
о выходе без сохранений.

*СЛОВАРЬ*

На данном этапе (реализуется в новом окне) имеются следующие возможности:

-   изменить название словаря

-   изменить описание словаря (поле описание словаря+дата экспорта и название
    пользоввателя/словаря родителя)

-   выбрать интенсивность интерактивных уведомлений для данного словаря
    (ползунок легче ___*___ интенсивнее)

-   изменить статус словаря (публичный/приватный)

-   кнопка добавить поле (в режиме онлайн добавляет 2 поля для ввода нового
    слова и перевода)

-   кнопки сохранить(при наличии измененений).

-   увидеть перевод внешнего переводчика (translate.ru или др.) в еще одном поле
    при наличие онлайн подключения.

-   метка удалить слово

-   метка удалить добавленное поле

-   увидеть статус каждого слова словаря (незнакомое/знакомое и т.д.)

После нажатия кнопки сохранить остаемся в словаре

!Возврат в предыдущий экран осуществляется закрытием окна словаря. Можно открыть
до 10 окон словарей одновременно. При наличие заполненных полей новых слов и
попытке выхода MessageBox должен спросить о выходе без сохранений.
