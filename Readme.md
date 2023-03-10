# Инструкция по работе с Git

## Что такое гит?
***Git*** - самая популярная реализация распределенной системы контроля версий(версионность поддерживается и на сервере, и у каждого клиента). Самой распостраненной реализацией ***Git*** является (*GitHub*)[https://github.com]
## Подготовка репозитория
Для создания репозитория используется команда "git init". Для этого необходимо открыть в терминале папку с будущим репозитарием и написать "git init"

## Создание коммитов

### Добавление файлов к комиту
Для добавления файла к новому коммиту используется команда "git add". Используется она следующим образом : в терминали с папкой-репозиторием пишем "git add <название файла>*.

## Перемещение между коммитами

## Журнал изменений
Для просмотра истории изменений используется команда "git log". Для этого в терминале с папкой-репозиторием необходимо написать "git log"

## Создание коммита
Для создания новой фиксации(коммита) используется команда "git commit" . Для этого в терминале с папкой-репозиторием пишем "git commit -m <сообщение к коммиту>*. Сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО!!!***

## Перемещение между коммитами

Для перемещения не другую фиксацию(коммит) используется команда "git checkout". Для этого необходимо, как показано в прошлом пункте, в журнале изменений найти необходимый коммит и его кеш(номер), после чего в терминале с папкой-репозиторием надо написать "git checkiut <хеш коммита>*. После выполнения этой команды мы попадаем в состояние **detached head** , в котором никакие следующие коммиты сохранятся не будут. Для выхода из этого состояние необходимо написать "git checkout master*.

## Ветки в git
### Создание веток в git
Для создания новой ветки используется команда *git branch*. Для этого в терминале с папкой-репозиторием необходимо написать *git branch < название ветки >*.
### Просмотр списка веток
Для просмотра списка веток используется команда *git branch*. Выделенная зеленым со звездочкой ветка - это ветка, в данный момент на которой мы находимся.

### Перемещение между ветками
Для перехода на другую ветку используется команда *git checkout*. Для этого в терминале с папкой-репозиторием необходимо написать *git checkout < название ветки >*. Такая ветка должна **существовать**.

## Слияние веток и разрешение конфликтов

## Удаление веток
