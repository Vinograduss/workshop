# workshop

Пример использования сервиса Vision от Mail.ru Cloud Solutions для раскрашивания черно-белых фильмов

В 2019 году компания Mail.ru запустила сервис для реставции старых военных фотографий https://9may.mail.ru/restoration/
Сервис позволяет загрузать фотографию на странице проекта, закрасить царапины и превратить фото в цветное изображение.

Нейроная сетка обучалась специально на ч/б фотографиях военного времени, подбробнее о работе нейроной сети можно почитать https://habr.com/ru/company/mailru/blog/453872/

В рамках данного workshop рассмотрим процесс превращение страого фильма в цветной. Будем отправлять запросы на  /api/v1/photo/improve
И склеивать результаты обработки кадров в видеоряд
