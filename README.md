# Мануал бота для Discord

## Ссылка приглашения бота - [Нажми на меня](https://discord.com/api/oauth2/authorize?client_id=583233909211267072&permissions=2148392129&scope=bot)

**ВНИМАНИЕ - Для того чтобы бот работал на сервере вы должны подать заявку на верификацию. Подать её можно тут ---> [Подать заявку на верификацию сервера](https://docs.google.com/forms/d/1YBB72PuJw3GGwKzqIlxuBeXeFMajOL0vVb84iLrTog8).**

## Вводная часть:

- **Префикс бота** - *является символом точки.*
- **Описание работы бота** - *бот проверяет всех прибывших участников сервера на наличии их **ID** в нашей базе данных. В случае нахождения данного **ID** бот высылает в назначенный канал сообщение об этом инцинденте.*

## Команды для владельцев верифицированных серверов:

- **.force** - *команда для принудительной проверки всех участников сервера на наличия записей о них в базе данных.* **- ВНИМАНИЕ! Данная команда будет доступна для исполнения всего 1 раз на сервере так-как в новом обновлении бот будет автоматически проверять сходства на ВСЕХ серверах при добавлении в базу ID нарушителя.**
- **.addmoder ID** - *вместо **ID** вписываете **ID** участника которого вы хотите назначить модератором в боте. Где взять **ID** пользователя или сервера описано в этой статье - [Где найти ID участника в Discrod](https://support.discord.com/hc/ru/articles/206346498-%D0%93%D0%B4%D0%B5-%D0%BC%D0%BD%D0%B5-%D0%BD%D0%B0%D0%B9%D1%82%D0%B8-ID-%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D1%8F-%D1%81%D0%B5%D1%80%D0%B2%D0%B5%D1%80%D0%B0-%D1%81%D0%BE%D0%BE%D0%B1%D1%89%D0%B5%D0%BD%D0%B8%D1%8F-).*
- **.delmoder ID** - *снятие участника с модеративной роли в боте.* 
- **.channel ID** - *назначение канала куда бот будет присылать уведомления.*
- **.rechannel ID** - *переназначения канала бота.*
- **.prefix P** - *команда переназначает префикс бота. Где P можно поставить любое значение.*

## Команды модераторов назначенных в боте:

**ВНИМАНИЕ - Модератор назначенный на одном сервере не может пользоваться ботом на втором сервере !**

- **.check ID** - Принудительный запрос на проверку **ID**

## Общие команды:

- **.help** - *Выводит справку о боте*
- **.status** - *Выводит количество верифицированных серверов и записей в базе данных*

## Новые функции:

- **Новая функция от 07/15/2021** - *Теперь когда новый ID заносится в базу бот автоматически проверяет все верифицированные сервера и если находит этого пользователя на Вашем сервере оповещает Вас об этом в назначенном канале.*
- **Новая функция от 07/21/2021** - *добавлена новая команда .force*
- **Новая функция от 07/24/2021** - *добавлена новая команда .prefix*
- **Изменения ответа бота на невозможность исполнения команд от XX/XX/2021** - *мы переработали логику ответов бота при возникновении ошибки или невозможности исполнения команды, теперь ответы бота стали болле информативны и понятны в отличии от прошлого варианта без сообщения.* 
