# Store-server
![](https://img.shields.io/badge/Project%20status%20-in%20process-green)

## Оглавление

- [Оглавление](#оглавление)
  - [Автор](#автор)
  - [Описание](#описание)
  - [Технологии](#технологии)
  - [Запуск проекта в dev-режиме](#запуск-проекта-в-dev-режиме)
  - [Загрузка тестовых данных в базу данных](#загрузка-тестовых-данных-в-базу-данных)

### Автор

- [Максим Савилов](https://github.com/msavilov/)

### Описание

Интернет-магазин одежды. 

### Технологии

- ![](https://img.shields.io/badge/Python-3.11-brightgreen)

- ![](https://img.shields.io/badge/Django-3.2-brightgreen)

- ![](https://img.shields.io/badge/djangorestframework-3.12.4-brightgreen)

### Запуск проекта в dev-режиме

- клонировать репозиторий или скачать архив

```bash
git clone https://github.com/msavilov/Store-server.git
```

- Установите и активируйте виртуальное окружение

```bash
python3 -m venv venv
```

```bash
source venv/bin/activate
```

- обновить pip

```bash
python3 -m pip install --upgrade pip
```

- Установите зависимости из файла requirements.txt

```bash
pip install -r requirements.txt
```

- В папке с файлом manage.py выполните команду:

```bash
python3 manage.py runserver
```
