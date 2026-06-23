# team-github-practice
Практическая работа: совместная разработка проекта на GitHub

## Часть 1 (создание репозитория и добавление участников)

1. Добавление участников в репозиторий

![Рисунок 1 — Добавление участников в репозиторий](screenshots/01_collaborators_1.png)

3. Ожидание принятия приглашения

![Рисунок 2 Ожидание приглашения](screenshots/01_collaborators_2.png)

4. Приглашение принято

![Рисунок 3 Принятие приглашения](screenshots/01_collaborators_3.png)

## Часть 2  Клонирование проекта всеми участниками

1. Клонирование участником 1 (владелец репозитория Эрик Кожемякин).
   
   У меня не получилось сделать через gui, поэтому я ввел команду в терминале

![](screenshots/02_clone_eric.png)

2. Клонирование учасником 3 (для ознакомления с процессом приглашения участника с другой стороны я сделал себе еще 1 аккаунт на github)

   Для того что бы на одном PC работать через разные аккаунты я клонировал через ssh

![](screenshots/02_clone_eric2.png)

   Настроил локально другого пользователя

![](screenshots/02_clone_eric2_2.png)

## Часть 3

Скриншот пуш

![](screenshots/03_first_push.png)

## Часть 4 Получение изменений остальными участниками

1. Учатник 3

![](screenshots/04_pull_eric2.png)

## Часть 5  Первая проблема: два участника меняют разные файлы

![](screenshots/05_commit_history.png)

## Часть 6 Вторая проблема: участник забыл сделать Pull перед работой

### Описание

Это учебный командный проект для практики GitHub.

### Используемые инструменты

- Git;
- GitHub;
- VS Code

Скриншот ошибки push

![](screenshots/06_push_rejected.png)

Скриншот нового дерева

![](screenshots/06_new_tree.png)

## Часть 7 Третья проблема: настоящий merge conflict

### Статус проекта

Проект находится в активной разработке: команда студентов изучает GitHub, Pull Request и разрешение конфликтов.

### Проблема: merge conflict
Мы получили конфликт, потому что два участника изменили одну и ту же строку в  README.md. Git не смог автоматически выбрать правильный вариант, поэтому мы  вручную объединили изменения.

![](screenshots/07_merge_conflict.png)

![](screenshots/08_conflict_resolved.png)

## Часть 8 Работа через отдельные ветки

## Часть 9 Pull Request

Создание Pull Request

![](screenshots/09_pull_request.png)

Review Pull Request

![](screenshots/10_pull_request_review.png)


Завершение Pull Request (merge)

![](screenshots/11_pull_request_merged.png)

## Часть 10. Конфликт внутри Pull Request

![](screenshots/12_pr_conflict.png)

![](screenshots/13_pr_conflict_resolved.png)
