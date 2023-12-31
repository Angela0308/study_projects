# Исследование эффективности маркетинга Procrastinate Pro+
## Описание проекта
Несмотря на огромные вложения в рекламу развлекательного приложения Procrastinate Pro+, последние несколько месяцев компания терпит убытки. Необходимо разобраться в причинах и помочь компании выйти в плюс.
Есть данные о пользователях, привлечённых с 1 мая по 27 октября 2019 года:
* лог сервера с данными об их посещениях,
* выгрузка их покупок за этот период,
* рекламные расходы.

## Задачи
Изучить:
* откуда приходят пользователи и какими устройствами они пользуются,
* сколько стоит привлечение пользователей из различных рекламных каналов;
* сколько денег приносит каждый клиент,
* когда расходы на привлечение клиента окупаются,
* какие факторы мешают привлечению клиентов.

## Используемые библиотеки:
- pandas
- numpy
- datetime
- matplotlib

## Выводы:
В ходе исследования эффективности маркетинга компании Procrastinate Pro+ на основании данных о пользователях, привлечённых с 1 мая по 27 октября 2019 года установлено, что на рекламу было потрачено 105497.3, стоимость привлечения одного пользователя составила 1.42, пользователи приходят из 4 стран:
+ Соединенных Штатов Америки - 67%
+ Великобритании - 12%
+ Франции - 11%
+ Германии - 10%

Пользователи из США активнее других стран становятся покупателями и их LTV выше, но они быстро уходят и их привлечение обходится намного дороже, чем привлечение пользователей из Европы, рекламная кампания не окупается только для США.

По используемым устройствам клиенты распределены более равномерно:
+ iPhone - 36%
+ Android - 24%
+ PC - 20%
+ Mac - 20%

Конверсия в покупателей отличается не сильно, но отстают пользователи PC. При этом привлечение через PC обходится дешевле и окупается, удержание происходит чуть лучше, чем у пользователей с других устройств.

Рекламный бюджет распределен неравномерно, более 80% процентов ушло в два канала TipTop и FaceBoom, что оказалось проигрышной стратегией. Несмотря на то, что из этих каналов пришло больше всего покупателей, оба источника не окупились и принесли убытки, а привлечение пользователей из этих каналов оказалось черезмерно дорогим. Удержание платящих пользователей из FaceBoom и AdNonSense практически не происходит. При самой высокой стоимости привлечения клиенты из TipTop хуже превращаются в покупателей.

Таким образом причины плохой окупаемости рекламы:
+ слабая конверсия в покупателей в целом,
+ повышенная стоимость привлечения iPhone и Mac,
+ повышенная стоимость привлечения и слабое удержание платящих пользователей из США,
+ сильно высокая стоимость привлечения и низкая конверсия клиентов из TipTop,
+ слабое удержание клиентов из FaceBoom и AdNonSense.

Стоит обратить внимание на:
+ повышение конверсии в покупателей пользователей PC,
+ повышение LTV  и конверсии для Великобритании, Германии, Франции,
+ развитие канала lambdaMediaAds, у канала самый высокий LTV и конверсия,
+ развитие канала RocketSuperAds, LTV растет, реклама окупается, в пятерке по конверсии и лидерах по удержанию.