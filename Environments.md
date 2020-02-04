1. git init - создать репозиторий 
- создать файл и внести в него изменение
git add . - указать гиту чтобы он отслежиывал файл
git status - проверить статус
-> закомитить:
git commit -m "Environments" 
- указать гиту название нового репозитория:
git remote add origin https://github.com/kotya-ra/Environments.git
- синхронизировать:
git push -u origin master

2. Клонировать:
- Создать на своем ПК папку, куда будешь копировать
- Вызывать с нее ГитБаш
- Скопировать ссылку репозитории с сайта
- Прописать команду: 
git clone https://github.com/kotya-ra/Environments.git

3. Закомитить на Git в существующий:
- проверить статус после внесенных правок:
git status
- указать гиту чтобы он отслежиывал файл:
git add .
- проверить статус:
git status
- закомитить его:
git commit -m "commit"
-> указать гиту название нового репозитория:
git remote add origin https://github.com/kotya-ra/Environments.git
- синхронизировать:
git push
- проверть статус:
git status

4. Создать бранч:
git checkout -b имя новой ветки
взять его и закомитить в него
git add Environments.md
git commit
бранч смерджить с мастером
git merge master