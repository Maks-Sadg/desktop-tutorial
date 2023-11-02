#TEST BRANCH1

##создание директории и переход в неё

$ mkdir Desktop/git_exercise/

$ cd Desktop/git_exercise/

$ git init


##Работа с файлами

git add .

git reset css/style.css

git rm text.txt

##Коммит(изменение коммита)

git commit -m 'Add some code'

git commit --amend -m 'New comment'

##История

git log

git status


##

git clone https://github.com/Maks-Sadg/desktop-tutorial.git

##Создание ветви локально

git branch testbranch1

##Перход к ветви

git checkout testbranch1

##Создание ветви на удаленном

git push --set-upstream origin testbranch1

##Подключение

git remote add origin https://github.com/Maks-Sadg/desktop-tutorial.git

##Отправка изменений на сервер

git push origin master

##Запрос изменений с сервера

git pull origin master

##SSH

ssh-keygen -t ed25519-sk -C "your_email@example.com"

ввели пароль

clip < ~/.ssh/id_ed25519.pub

В GH добавили открытый ключ.

Создали репозиторий локально

git clone git@github.com:Maks-Sadg/desktop-tutorial.git

 

