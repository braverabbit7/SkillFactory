# Документация для Сотрудников

Добро пожаловать в нашу команду разработки! Эта документация поможет вам начать работу с нашим проектом и внести свой вклад в его развитие.

## 1. Репозиторий и Код

- Наш репозиторий с кодом располагается на [ссылке на GitHub](https://github.com/braverabbit7/SkillFactory).
- Чтобы посмотреть существующий код, перейдите по ссылке выше.
- Вы также можете клонировать репозиторий на свой компьютер с помощью команды:
  ``git clone git@github.com:braverabbit7/SkillFactory.git``

## 2. Процесс Внесения Изменений

Процесс Внесения Изменений
Процесс внесения изменений в основную кодовую базу включает следующие шаги:

Создайте собственную ветку для разработки, используя правила именования, описанные ниже.
Внесите необходимые изменения в своей ветке.
Отправьте запрос на слияние (Pull Request) для обзора изменений.
Ожидайте обзора и, при необходимости, внесите дополнительные изменения.
После одобрения изменений, ваш код будет слит с основной кодовой базой.
## 3. Правила Именования Веток
Имена веток должны быть описательными и отражать характер изменений, которые вы вносите. Рекомендуется использовать следующий формат:
Для новых функций: feature/название-функции<br>
Для исправления ошибок: bugfix/описание-ошибки<br>
Для задач: task/номер-задачи<br>
## 4. Использование Локального .gitconfig
В проекте есть локальный файл .gitconfig, который содержит дополнительные настройки для этого проекта. Вы можете включить его в свою конфигурацию Git, чтобы использовать его параметры, выполнив следующую команду:
```git config include.path ../.gitconfig```
## 5. Инструкция по Слиянию Веток
Чтобы создать свою ветку и внести изменения:
### Создать новую ветку
```git checkout -b feature/название-функции```

#### Внести изменения
#### ...

#### Закоммитить изменения
```git commit -m "Описание изменений"```

#### Отправить изменения на сервер
```git push origin feature/название-функции```

### Чтобы слить изменения с основной кодовой базой:
1.Откройте Pull Request на GitHub из вашей ветки в основную ветку.
2.Ожидайте обзора и комментариев.
3.После одобрения, изменения будут слиты в основную кодовую базу.