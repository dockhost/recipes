<div align="center">
  <a href="https://dockhost.ru">
    <img src="https://upload.dockhost.ru/images/logo/favicon-cube.svg" alt="Logo" width="80" height="80">
  </a>
  <h3 align="center">Dockhost</h3>
  <p align="center">
    Пример запуска приложения NestJS на платформе Dockhost
    <br />
    <a href="https://dockhost.ru">Узнать больше</a>
    ·
    <a href="https://docs.dockhost.ru">Документация и инструкции</a>
  </p>
</div>

## О Dockhost

Dockhost - это бессерверная платформа для развёртывания приложений на основе Docker-контейнеров.

## Развёртывание

### Развёртывание через веб-интерфейс

1. В панели управления [Dockhost](https://my.dockhost.ru) выберите проект, в который хотите выполнить развёртывание примера.
2. В разделе проекта «Обзор» в меню «⋮» выберите пункт «Загрузить конфигурацию», или перейдите в раздел «Конфигурация» / «Файл конфигурации» и в меню «⋮» выберите пункт «Загрузить конфигурацию».
3. В открывшемся модальном окне укажите адрес к файлу.
4. Нажмите на кнопку «Загрузить» и дождитесь выполнения результата.

### Развёртывание через Dockhost CLI

Вы можете воспользоваться консольной утилитой [Dockhost CLI](https://docs.dockhost.ru/cli) для
быстрого развёртывания данного примера через dockhost.yaml файл. Для этого в терминале выполните следующую команду:

```shell
dockhost compose apply [путь к файлу или url]
```

## Поддержка

Если у вас есть какие-либо вопросы, идеи или предложения относительно этого примера приложения,
вы можете написать в службу поддержки [support@dockhost.ru](mailto:support@dockhost.ru) или
отправить [pull request](https://github.com/dockhost/example-nestjs/pulls).