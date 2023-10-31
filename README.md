$ mkdir Desktop/git_exercise/
$ cd Desktop/git_exercise/
$ git init

///
git add .
git reset css/style.css
git rm text.txt
///
git commit -m 'Add some code'
git commit --amend -m 'New comment'
git log



git clone https://github.com/Maks-Sadg/desktop-tutorial.git
//подключение
git remote add origin https://github.com/Maks-Sadg/desktop-tutorial.git

//Отправка изменений на сервер
$ git push origin master

//Запрос изменений с сервера
git pull origin master
