### Процесс инициализации
1. Создаем новый проект
    > mkdir hexlet-git
2. Переходим в созданную директорию
    > cd hexlet-git
3. Выполняем инициализацию
    > git init
4. С помощью команды git status статус репозитория:
    > git status
5. Создаем файл README.md со строкой текста
    > echo 'Hello, Hexlet!' > README.md
6. Для каждого нового или измененного файла
    > git add README.md
7. Коммит
   > - git commit -m 'add README.md'
   > - git commit -am 'do something'
   > - git commit --amend --no-edit (без vim)
   > - git add -i 
   - -m означает message, то есть описание коммита. Коммит можно выполнять и без него, но тогда откроется редактор, в котором нужно будет ввести описание коммита.
   - -a автоматически добавляет все изменения 
   - amend - добавить изменения в текущий коммит
   рабочей директории в индекс
   - ![x](https://cdn2.hexlet.io/derivations/image/original/eyJpZCI6IjI1MWVjOWE3NmFlY2Y2N2JkNTlmNGQwMzk4Y2U2ZjkxLmpwZyIsInN0b3JhZ2UiOiJjYWNoZSJ9?signature=dc86a08384582ba8b6fb654cb92bdfa9ee0dce1d0c58455a7ebf2fea65066390)
8. Линк репозитория
    > - git remote add origin git@github.com:<имя>/hexlet-git.git
    >  - git branch -M main
    >  - git push -u origin main
    - ![x](https://cdn2.hexlet.io/derivations/image/original/eyJpZCI6IjQ0NjZiYmFiYzczMTA2YmFkMjNiZTM3NDRlYzc3N2FlLmpwZyIsInN0b3JhZ2UiOiJjYWNoZSJ9?signature=4f3c7bbd9bac576cdd99294abba6d04a193f5770bf5272926c194b00ab85333b)
9. Клонирование
    > git clone git@github.com:<ИМЯ>/hexlet-git.git
10. Получить изменения
    >  git pull --rebase - одним коммитом
11. Отмена изменения
    > git restore PEOPLE.md
12. Удаление и подготовка к коммиту
    > git rm PEOPLE.md
13. Разница
    > git diff --staged - для индексов
14. Список коммитов
    > - git log -p - диф для каждого коммита
    > - git log --oneline - сокращенный вывод
    > - git log --name-status
    > - git log --graph - в графах
15. Изменения в коммите
    > git show
16. Кто менял файл
    > git blame
17. Поиск
    > - git grep -i hexlet - i без учета регистра
    > - git grep Hexlet $(git rev-list --all) - Возвращаем список хешей коммитов `rev-list`
18. Очистка репо
    > git clean -fd ,-f – force, -d – directory
19. Отмена коммитов
    > git revert
    ![](https://cdn2.hexlet.io/derivations/image/original/eyJpZCI6ImZkMjUyYzFlMTI5NzQ5NGFjZTQ5Y2NhZmU0YmFmZjY3LmpwZyIsInN0b3JhZ2UiOiJjYWNoZSJ9?signature=6e0043f6655d074e854006447658a6d21a246ff6352df835ea747527a6143fa5)
20. Удалить коммит
    > git reset --hard HEAD~2 ,полное удаление, без него изменения будут отправлены в рабочую директорию
    > ![x](https://cdn2.hexlet.io/derivations/image/original/eyJpZCI6ImJmOWY1OGUwMGRmYzdkODcyNzgzNjhiMThiNzY1MzNjLmpwZyIsInN0b3JhZ2UiOiJjYWNoZSJ9?signature=4daa23884f41e776ff8c2ab7e961baccf9c8a50f6d23d41e329324c499d9ec62)
21. Переход к коммитам
    > git checkout
22. Узнать местонахождение
    > git branch
    ![x](https://cdn2.hexlet.io/derivations/image/original/eyJpZCI6Ijk2ODU5NmM5ZWFmNTliOGNiNWMzOGY0ZmMyYWJkMTg2LmpwZyIsInN0b3JhZ2UiOiJjYWNoZSJ9?signature=76a289ba31298052e27e2f2de8c4ed2c233a3579b6a1a106c975a0903c4d5551)
23. Припрятать изменения
    > - git stash - отправить
    > - git stash pop - вернуть
    ![x](https://cdn2.hexlet.io/derivations/image/original/eyJpZCI6IjM0MmM0NjRmYjc4ZmU1ZjUyMTUwYmMzY2ZmZGRhZDE1LmpwZyIsInN0b3JhZ2UiOiJjYWNoZSJ9?signature=29483c2c0c99501f6a25dc42e4560ee0828ca6d17c7adde8c51680fe234a808e)
24. d
25. 
