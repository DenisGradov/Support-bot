# Бот поддержки
## Немного о боте
### Данный бот создан для облегчения жизни медийным личностям, либое же просто людям, которым потенциально пишет много людей. Вы просто указываете как контант - этого бота. Человек заходит в бот, отвечает на капчу (за 3 попытки, иначе - ban). Дальше выбирает категорию своего обращения (которые вы заранее настроите) и задаст сам вопрос. Новый запрос юзер не сможет задать до вашего ответа. А уже вы, как администратор можете в админ.меню смотреть пришедшие запросы, отвечать на них. Так же отдельному юзеру можно отправить сообщение / забанить юзера. Есть возможность провести рассылку для всех юзеров
___
## Установка и настройка бота
### Для установки бота - необходимо перейти на [официальный сайт питона](https://www.python.org/downloads/) и скачать инсталятор последней версии. При установке очень важно нажать на галочку ADD TO PATCH, ведь без нее установка библиотек будет некорректно работать<p>
### Теперь настроим самого бота. Его нужно создать в телеграм боте @BotFather. Открываем файл config.py через любой редактор кода (или даже блокнот) и ранее полученный токен (в ботфазере) вставляем в поле bot_token. В поле admin ужно указать свой id, взять который вы можете в боте @userinfobot. Список category отвечает за категории, в нем вы просто должны перечислить все свои категории
___
## Запуск бота
### Для запуска бота нужно просто запустить файл start.bat. Этот файл сам установит нужные боту библиотеки
