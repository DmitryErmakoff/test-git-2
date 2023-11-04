1. git status
2. git add [files] - добавляет файлы в stage
3. git commit -m "comment"
4. git log / git log --oneline
5. git push [rep_link] [branch_name]

Полезное --
1. git remote -v посмотреть ссылку на гит
2. git remote add origin [rep_link] привязать пустой гид к папке
3. git reset [название файла] убрать из stage
4. git diff просмотр изменений, можно так же у отдельного файла
5. git reset --hard отменяет все изменения
6. git config --list посмотреть настройки гита

Работа с ветками
1. git branch посмотреть все ветки
2. git branch [название] создать новую ветку
3. git checkout [название] переключиться на другую ветку
5. git pull [rep_link] [branch_name] получить слияние веток с гита
6. git merge [branch_name] склеить ветки  (обычно делают слияние находясь в мейн)
7. git branch -d [branch_name] удалить ветку (обычно после слияния удаляют)
8. git checkout -b [branch_name] переместиться в сразу созданную ветку
git pull origin master --allow-unrelated-histories принудительное слияние
