# TEST BRANCH1


*тут было сказано, что надо делать красиво. Ну попробуем*

*З.Ы.:Есть котик. БЛЭД!*
![Alt text][id]

[id]: https://octodex.github.com/images/dojocat.jpg  "The Dojocat"

---

**Оглавнение**

*по крайней мере попытка, интересно, будет ли работать*

- __[создание директории, выбор директории и переход в неё](#создание-директории-выбор-директории-и-переход-в-неё)__
- __[Работа с файлами](#работа-с-файлами)__
- __[Коммит(изменение коммита)](#коммитизменение-коммита)__
- __[История](#история)__
- __[Ветви](#ветви)__
- __[Работа с удаленным ](#работа-с-удаленным)__
- __[SSH](#ssh)__


## создание директории, выбор директории и переход в неё

```
mkdir Desktop/git_exercise/
```

```
cd Desktop/git_exercise/
```

```
git init
```

## Работа с файлами

```
git add .
```

```
git reset css/style.css
```

```
git rm text.txt
```

## Коммит(изменение коммита)

```
git commit -m 'Add some code'
```

```
git commit --amend -m 'New comment'
```

## История

```
git log
```

```
git status
```

## Ветви

создание ветви

```
git branch testbranch1
```

Перход к ветви

```
git checkout testbranch1
```

Создание ветви на удаленном

```
git push --set-upstream origin testbranch1
```


## Работа с удаленным 

Клонировать удаленный репозиторий

```
git clone https://github.com/Maks-Sadg/desktop-tutorial.git
```

HTTPS

```

git remote add origin https://github.com/Maks-Sadg/desktop-tutorial.git
```

SSH
```
git clone git@github.com:Maks-Sadg/desktop-tutorial.git
```

Отправка изменений на сервер

```
git push origin master
```

Запрос изменений с сервера

```
git pull origin master
```

## SSH создание ключа

    // Создание на локальном
    ssh-keygen -t ed25519-sk -C "your_email@example.com"  
    ввели пароль
    clip < ~/.ssh/id_ed25519.pub
    В GH добавили открытый ключ.
    Создали репозиторий локально
    

 

