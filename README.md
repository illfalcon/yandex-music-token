Проект для авторизации в свой аккаунт в [Telegram-боте Яндекc.Музыки](https://t.me/music_yandex_bot).

[v1](https://github.com/MarshalX/yandex-music-token/tree/v1) версия устарела. Уже не во все аккаунты можно войти через неё.

Существует вторая версия (ветка main). Доступна по https://music-yandex-bot.ru/v2/. 
Работает на новом API авторизации (подробнее [тут](https://t.me/MarshalC/766)). 
К сожалению, это API научилось в CORS. Соответвенно без сервера, на браузерном 
JS'e, получить ответ на запрос нельзя. Для того чтобы заработал сайт
нужно поставить расширение в браузер отключающее CORS. Например [это для FF](https://github.com/balvin-perrie/Access-Control-Allow-Origin---Unblock).
Ещё там нужно натыкать галочки в настройках чтобы жрало заголовок content type,
но это уже сами разберётесь.