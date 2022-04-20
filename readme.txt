добавьте все файлы в локальное хранилище:
git add .
git commit -m 'Changes'

создайте новую ветку и перейдите в неё:
git branch blog
git checkout blog

в новой ветке создайте папку blog с файлами: index.js, index.html:
git add index.js
git add index.html
git commit -m 'Add new files'


загрузите на удаленный репозиторий лишь основную ветку вашего проекта:
git branch -M master
git 