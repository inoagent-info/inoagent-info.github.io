# Сайт «Иноагент-Инфо Реестр»

Удобный реестр «иностранных агентов», который ведет Минюст России. Обновляется каждую пятницу.

[Перейти на сайт «Иноагент-Инфо Реестр»](https://inoagent-info.github.io)

## Как работает

Минюст России публикует реестр «иноагентов» в формате `.pdf-файла`, а реестр на сайте отображается на сайте через `.json-файл`. Реализовать это получилось с помощью парсера `pdf to json` от Mozilla.

Каждую пятницу скрипт запускается вручную, после чего обновляется файл `registry.json` (расположен в репозитории inoagent-info/script). Как только новый реестр в формате `.json-файла` будет добавлен на GitHub, информация на сайте автоматически изменяется.

## Наши ресурсы

- Наш телеграм-канал — [Иноагент-Инфо](https://t.me/inoagentinfo)
- Связаться через телеграм-бота — [Иноагент-Инфо Связь](https://t.me/inoagentinfo_bot)
- Поддержать — [через сервис «Бусти»](https://boosty.to/inoagent-info)
