1. **.gitignore**: Файл, который указывает Git игнорировать определенные файлы или папки при коммитах. Это полезно для исключения конфиденциальных данных (например, `config.py`) или временных файлов.
2. **README.md**: Файл, содержащий информацию о проекте. Здесь описываются цели проекта, структура файлов и инструкции по использованию.
3. **main.py**: Главный исполняемый файл программы. В нем находится основная логика приложения.
4. **config.py**: Файл с конфигурационными данными проекта. Содержит чувствительную информацию (например, личные данные), которая не должна попадать в репозиторий.
5. **config_template.py**: Шаблон конфигурационного файла. Используется как пример для создания `config.py`. Не содержит чувствительных данных.
6. git init
7. git add .
8. git commit -m "first commit" / git commit -m "Initial commit"
9. git remote add origin
10. git remote -v
11. git push -u origin main
12. Команда **git pull**` используется для получения изменений из удаленного репозитория и их слияния с локальной веткой. Это эквивалентно выполнению `git fetch` и `git merge`.
