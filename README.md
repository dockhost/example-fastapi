<div align="center">
  <a href="https://dockhost.ru">
    <img src="https://upload.dockhost.ru/images/logo/favicon-cube.svg" alt="Logo" width="80" height="80">
  </a>
  <h3 align="center">Dockhost</h3>
  <p align="center">
    Пример запуска приложения FastAPI на платформе Dockhost
    <br />
    <a href="https://dockhost.ru">Узнать больше</a>
    ·
    <a href="https://docs.dockhost.ru">Документация и инструкции</a>
  </p>
</div>

## О Dockhost и примере приложения FastAPI

Dockhost - это бессерверная платформа для развёртывания приложений на основе Docker-контейнеров.

Этот пример приложения предназначен для демонстрации того, как приложение FastAPI может быть развёрнуто на Dockhost при помощи Push-to-Deploy.

## Требования

Для развёртывания и запуска этого приложения вам потребуется учётная запись Dockhost.
Если у вас ещё нет учётной записи, вы можете бесплатно зарегистрироваться [здесь](https://account.dockhost.ru/auth/registration?redirect=console).

## Развёртывание

Выполните одно из следующих действий, чтобы развернуть и запустить приложение FastAPI на Dockhost.

### Развёртывание через веб-интерфейс

1. В панели управления [Dockhost](https://my.dockhost.ru) выберите проект, в который хотите выполнить развёртывание примера.
2. В разделе проекта «Обзор» в меню «⋮» выберите пункт «Загрузить конфигурацию», или перейдите в раздел «Конфигурация» / «Файл конфигурации» и в меню «⋮» выберите пункт «Загрузить конфигурацию».
3. В открывшемся модальном окне укажите адрес: https://raw.githubusercontent.com/dockhost/example-fastapi/main/dockhost.yaml
4. Нажмите на кнопку «Загрузить» и дождитесь выполнения результата.

### Развёртывание через Dockhost CLI

Вы можете воспользоваться консольной утилитой [Dockhost CLI](https://docs.dockhost.ru/cli) для
быстрого развёртывания данного примера через dockhost.yaml файл. Для этого в терминале выполните следующую команду:

```shell
dockhost compose apply https://raw.githubusercontent.com/dockhost/example-fastapi/main/dockhost.yaml
```

### Форк и подключение репозитория

Вы можете сделать свой форк данного приложения, настроить или улучшить его.
Воспользуйтесь следующей инструкцией, чтобы развернуть свой форк приложения на Dockhost.

1. В панели управления [Dockhost](https://my.dockhost.ru) выберите проект, в который хотите подключить репозиторий.
2. Перейдите в раздел «Репозитории» и нажмите на кнопку «Добавить».
3. В открывшемся модальном окне в качестве адреса укажите репозиторий, который вы только что форкнули.
4. Введите название, например «fastapi», и нажмите на кнопку «Применить».
5. После того как завершится первая сборка приложения, перейдите в раздел «Контейнеры»

## Поддержка

Если у вас есть какие-либо вопросы, идеи или предложения относительно этого примера приложения,
вы можете написать в службу поддержки [support@dockhost.ru](mailto:support@dockhost.ru) или
отправить [pull request](https://github.com/dockhost/example-fastapi/pulls).