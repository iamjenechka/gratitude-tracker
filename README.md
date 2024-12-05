# Gratitude Tracker

Я верю, что благодарность — одна из самых исцеляющих эмоций. Если практиковать благодарность каждый день и фиксировать этот путь, это может помочь нам жить более осознанно и гармонично. Это приложение создано, чтобы поддержать вас в этом процессе, помогая отслеживать и отражать моменты благодарности на пути к внутреннему равновесию.

Это простое приложение для отслеживания благодарностей, которое сохраняет их в базе данных SQLite. Пользователи могут добавлять благодарности и просматривать все свои записи, упорядоченные по времени.

## Особенности

- Добавление благодарностей с временной меткой.
- Просмотр всех благодарностей, отсортированных по времени.
- Данные сохраняются в базе данных SQLite.
- Простое консольное приложение.

## Установка

Для работы с этим проектом потребуется Python 3.x и библиотека `sqlite3`, которая входит в стандартную библиотеку Python.

1. Склонируйте или загрузите репозиторий:

   ```bash
   git clone https://github.com/iamjenechka/gratitude-tracker.git
   ```

2. Перейдите в папку с проектом:

  ```bash
    cd gratitude-tracker
  ```

3. Запустите программу:

 ```python gratitude_tracker.py```


### Использование

Программа предлагает несколько вариантов:

    - Добавить благодарность — введите свою благодарность, и она будет сохранена с временной меткой.
    - Показать все благодарности — все записи будут отображены в порядке добавления, начиная с последней.
    - Выход — завершение работы программы.

### Cтруктура проекта

    - gratitude_tracker.py — основной исполняемый файл, содержащий логику приложения.
    - gratitudes.db — файл базы данных SQLite, где сохраняются благодарности.

### Примечания

    - При первом запуске программы будет автоматически создана таблица в базе данных, если она еще не существует.
    - Данные сохраняются на локальном уровне, и они доступны для просмотра до тех пор, пока не удалите базу данных вручную.

### Лицензия

Этот проект распространяется под лицензией MIT. См. файл LICENSE для подробностей.

