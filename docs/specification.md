# Чат

[Видео к спецификации](https://youtu.be/WUAtCji3RRY)

## Требования к системе
Сервис "Чат" предназначен для общения пользователей и обмена документами

1. Пользователь отправить сообщение чат с текстом и вложениями 
1. Пользователь видит онлайн все сообщения чата
1. Пользователь получает оповещения о новых сообщениях
1. Пользователь может просмотреть все вложения чата
1. Внешняя система может получить все вложения чата

## Варианты использования системы

![usecases](usecases.svg)

## Модель данных

![model](model.svg)

## Модель предметной области

## Дорожная карта

1. Текстовый чат с вложениями, интегрируемый как api / iframe
2. Аудио-видео чат с использованием [Janus](https://janus.conf.meetecho.com/docs/), пример приложения [jangouts](https://github.com/jangouts/jangouts)
