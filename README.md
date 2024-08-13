<div align="center">
  <a href="https://dockhost.ru">
    <img src="https://upload.dockhost.ru/images/logo/favicon-cube.svg" alt="Logo" width="80" height="80">
  </a>
  <h3 align="center">Dockhost</h3>
  <p align="center">
    Коллекция файлов конфигураций для платформы Dockhost
    <br />
    <a href="https://dockhost.ru">Узнать больше</a>
    ·
    <a href="https://docs.dockhost.ru">Документация и инструкции</a>
  </p>
</div>

# О Dockhost

Dockhost - это бессерверная платформа для развёртывания приложений на основе Docker-контейнеров.

# Файлы конфигурации

Файлы конфигурации (dockhost.yaml) - это описанный в формате yaml конфигурации различных приложений или сервисов проекта
которые можно быстро развернуть с помощью консольной утилиты[Dockhost CLI](https://docs.dockhost.ru/cli), или через
веб-интерфейс.

# Применение файлов

## Применение файлов конфигураций через веб-интерфейс

1. В панели управления [Dockhost](https://my.dockhost.ru) выберите проект, в который хотите выполнить развёртывание
   примера.
2. В разделе проекта «Обзор» в меню «⋮» выберите пункт «Загрузить конфигурацию», или перейдите в раздел «Конфигурация» /
   «Файл конфигурации» и в меню «⋮» выберите пункт «Загрузить конфигурацию».
3. В открывшемся модальном окне укажите адрес к файлу.
4. Нажмите на кнопку «Загрузить» и дождитесь выполнения результата.

## Применение файлов конфигураций через Dockhost CLI

Вы можете воспользоваться консольной утилитой [Dockhost CLI](https://docs.dockhost.ru/cli) для
быстрого развёртывания данного примера через dockhost.yaml файл. Для этого в терминале выполните следующую команду:

```shell
dockhost compose apply [путь к файлу или url]
```

# Коллекции файлов конфигураций

## [Базы данных](db)

### [PostgreSQL](db/postgres)

| [16](db/postgres/16)                                | [15](db/postgres/15)                                |
|-----------------------------------------------------|-----------------------------------------------------|
| [1CPU-256MB.yaml](db/postgres/16/1CPU-256MB.yaml)   | [1CPU-256MB.yaml](db/postgres/15/1CPU-256MB.yaml)   |
| [1CPU-512MB.yaml](db/postgres/16/1CPU-512MB.yaml)   | [1CPU-512MB.yaml](db/postgres/15/1CPU-512MB.yaml)   |
| [1CPU-1024MB.yaml](db/postgres/16/1CPU-1024MB.yaml) | [1CPU-1024MB.yaml](db/postgres/15/1CPU-1024MB.yaml) |
| [1CPU-2048MB.yaml](db/postgres/16/1CPU-2048MB.yaml) | [1CPU-2048MB.yaml](db/postgres/15/1CPU-2048MB.yaml) |
| [1CPU-4096MB.yaml](db/postgres/16/1CPU-4096MB.yaml) | [1CPU-4096MB.yaml](db/postgres/15/1CPU-4096MB.yaml) |
| [1CPU-8192MB.yaml](db/postgres/16/1CPU-8192MB.yaml) | [1CPU-8192MB.yaml](db/postgres/15/1CPU-8192MB.yaml) |

### [MySQL](db/mysql)

| [8.1](db/mysql/8.1)                             | [8.0](db/mysql/8.0)                             | [5.7](db/mysql/5.7)                             |
|-------------------------------------------------|-------------------------------------------------|-------------------------------------------------|
| [1CPU-256MB.yaml](db/mysql/8.1/1CPU-256MB.yaml) | [1CPU-256MB.yaml](db/mysql/8.0/1CPU-256MB.yaml) | [1CPU-256MB.yaml](db/mysql/5.7/1CPU-256MB.yaml) |
|                                                 |                                                 | [1CPU-512MB.yaml](db/mysql/5.7/1CPU-512MB.yaml) |

# Поддержка

Если у вас есть какие-либо вопросы, идеи или предложения относительно этого репозитория,
вы можете написать в службу поддержки [support@dockhost.ru](mailto:support@dockhost.ru) или
отправить [pull request](https://github.com/dockhost/recipes/pulls).