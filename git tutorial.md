# 1. Инструкция Git (запуск и основные команды)

## Начало работы

1. Скачать и установить приложения:

https://git-scm.com/book/ru/v2/Введение-Установка-Git


https://code.visualstudio.com/

2. После установки представится системе: ввести в терминале

    **git config --global user.name** *«Ваше имя англ буквами»*

    **git config --global user.email** *ваша_почта@example.com*

3. Запустить Visualstudio

4. Открыть в Visualstudio папку/файл в которой необходимо создать контроль версий

5. Открыть терминал

6. Инициализировать репозиторий в папке командой **git init**

## Команды:

**git init** - инициализирует репозиторий в папке

**git status** - показывает текущее состояние и наличие изменений

**git add** *'.\название файла'* - добавляет конкретный файл для сохранения

**git add .** добавляет все файлы для сохранения

**git log** - журнал событий (показывает перечень и характеристики коммитов)

**git commit -m** *"комментарий"* - фиксация комита - состояния системы(сохранение)

**git checkout** *номер комита (можно частично)* - получение конкретного коммита

**git diff** - отличия в коммитах

## Полезные сочетания клавиш

таб - переход между названиями комитов/файлов

Q - выход

ctrl+S - сохранение

# 2. Инструкция Git (слияние веток)
## 1. Создание новой ветки и переходы между ветками

**git branch** - просмотр всех веток

**git branch** *имя_ветки* - создание ветки *имя_ветки*

**git checkout** *имя_ветки* - переход на ветку *имя_ветки*

## 2. Слияние веток
**git merge** *имя_ветки* - сливаем ветку *имя_ветки* в текущую (вызывается из ветки, в которую нужно добавить)

## 3. Конфликты

* Fast-forward
* Auto-merdge ORT

## 4. Удаление ветки

**git branch -d** *имя_ветки* - удаление ветки *имя_ветки*

Новая тестовая строка
