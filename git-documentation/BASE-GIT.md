# Шпаргалки (базовые команды)  

### Инициализация и подключение репозитория  

```bash
git init
git clone <url>
```

### Работа с состоянием  

```bash
git status
git add <file>          # добавить файл
git add .               # добавить все изменённые файлы
```

### Коммиты  
```bash
git commit -m "Описание изменений"
```

### Ветки  
```bash
git branch              # список веток
git branch <name>       # создать ветку
git checkout <name>     # переключиться на ветку
git checkout -b <name>  # создать и переключиться
```

### Отправка и получение изменений  
```bash
git push origin <branch>
git pull origin <branch>
```

### Просмотр истории  
```bash
git log
git log --oneline
```