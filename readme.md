# Инструкция для работы с Git и удалёнными репозиториями

## Что такое Git?
Git - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.

## Предварительная настройка

Вы установили себе Git и можете им пользоваться. Давайте теперь его настроим, чтобы когда вы создавали commit, указывался автор, кто его создал.

### Установим имя и email для вашего пользователя ###

Вместо <ваше_имя> можно ввести, например, Grisha_Popov. Кавычки оставляем:

*git config user.name "<ваше_имя>"* 

Теперь установим email. Принцип тот же:

*git config user.email "<адрес_почты@email.com>"*

## Создание репозитория
Для создание репозитория необходимо выполнить команду *git init*  в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git)

## Создание коммитов

### Git add
Для добавления измений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add <имя файла>*

### Просмотр состояния репозитория
Для того, чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите были ли измения в файлах, или их не было.

### Создание коммитов
Для того, чтобы создать коммит(сохранение) необходимо выполнить команду *git commit*. Выполняется она так: *git commit -m "<сообщение к коммиту>*. Все файлы для коммита должны быть ***ДОБАВЛЕНЫ*** и сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.

## Перемещение между сохранениями
Для того, чтобы перемещаться между коммитами, используется команда *git checkout*. Используется она в папке с пепозиторием следующим образом: *git checkout <номер коммита>*

## Журнал изменений
Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда *git log*. Для этого достаточно выполнить команду *git log* в папке с репозиторием

## Ветки в Git

### Создание ветки

Для того, чтобы создать ветку, используется команда *git branch*. Делается это следующим образом в папке с репозиторием: *git branch <название новой ветки>*

### Слияние веток

Для того чтобы дабавить ветку в текущую ветку используется команда *git merge <name branch>*

### Удаление веток
Для удаления ветки ввести команду:

*git branch -d 'name branch'*

## Вспомогательные команды ##
Просмотреть изменения относительно двух веток можно командой:

*git diff <исходная_ветка> <целевая_ветка>*

Удалить ненужную ветку:

*git branch -d <название_ветки>*

## Подсказки по популярным командам:

По популярным командам:

*git help*

Или по конкретной команде:

*git help <название_команды>*

Например clone:

*git help clone*

## Использование расширений в работе 

Меню расширений вызывается сочетанием клавиш *Ctrl + Shift + X* , либо нажатием по иконке меню расширений на таскбаре слева (на примере VSC) (см. скриншот):

![alt text](https://i.imgur.com/tFLkpzy.png)


### Установка расширений (см. скриншот):


![alt text](https://i.imgur.com/KdEiHLe.png)

