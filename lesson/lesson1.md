# Создание удаленного репозитория git при наличии локального

git init # инициализация ubn
git add lesson1.md
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/m637ex/git-advanced.git # установим в локалном репозитории путь к удалённому
git push -u origin master # -u текущую верку с удаленной веткой 

# Клонирование удаленно репозитория в локальный
git clone path https://github.com/m637ex/git-advanced # слонирование удаленного репозитория в локальный


# Синхронизация изменений в ветках
git remote show origin

создадим 2 ветку - git checkout -b '1-some-issue'