![Команды GIT](git.jpg)

# Команды GIT

## Всего несколько команд нужно для базового варианта использования Git для ведения истории изменений.

## Git сегодня - это очень популярная система контроля версий. Поэтому шпаргалка по Git, состоящая из основных команд.

* **git --version** - *узнать версию Git-а (установлен ли)*;

* **git init** - *создание репозитория*;

    ![Репозиторий](repository.png)

* **git status** - *узнать статус (что происходит)*;

* **git add FileName** - *сохранить файл*;

* **git commit -m "Comment"** - *комментарий к сохранениию/изменению*;
    ![Комментарий к сохранению](Comments.jpg)

* **git log** - *просмотр версий/изменений*;

* **git checkout {4+ symbol}** - *перейти к какой-либо из версий*;

* **git checkout master** - *продолжить работу после переключения версий*;

* **git diff** - *просмотреть разницу между сохраненной и текущей версиями*;

* **git config --global user.name "Username"** - *указать название пользователя*;

* **git config --global user.email "Email"** - *указать адрес пользователя*;

* **git branch** - *отобразить ветки, узнать, на какой ветке находимся;*

* **git branch new_branch** - *создать новую ветку;*

* **git checkout new_branch** - *перейти на указанную ветку;*

* **git merge new_branch** - *добавить изменения указанной ветки в текущий;*

* **git branch -d new_branch** - *удалить ветку;*

* **git clone http://...** - *создать на компьютере локальную папку удаленного репозитория;*

* **cd [название папки]** - *переместиться в другую папку;*

* **git remote add origin https://...** - *связать локальный репозиторий с удаленным;*

* **git push -u origin master** - *отправить локальный репозиторий на удаленный;*

* **git branch -M master** - *сделать ветку master основной;*

* **git pull** - *взять актуальную версию с GitHub;*

* *и другие...([Нажми, чтобы увидеть больше комманд](https://git-scm.com/book/ru/v2/%D0%9F%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D0%B5-C%3A-%D0%9A%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D1%8B-Git-%D0%9E%D1%81%D0%BD%D0%BE%D0%B2%D0%BD%D1%8B%D0%B5-%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D1%8B))*