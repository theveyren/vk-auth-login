# Авторизация посетителей на вашем сайте
Что нужно чтобы всё заработало:

в `main.py` вписать все что нужно для работы с авторизацией:

```
VKID = "12345678" #ID приложения на vk.com/editapp?id=АйдиПриложения&section=options
REDIRECTURI = "http://127.0.0.1:5000/login" # Редирект посетителя после авторизации
VKSECRET = "12345678901234567890" # Секретный ключ, найти можно на vk.com/editapp?id=АйдиПриложения&section=options и найти Защищенный ключ
```

Создайте приложение как сайт и поменяйте домен сайта на `http://127.0.0.1:5000` (для теста конечно же):

https://cdn.discordapp.com/attachments/1006481428671889470/1062478683148914748/image.png

Найти секретный ключ можно тут:

https://cdn.discordapp.com/attachments/1006481428671889470/1062478683148914748/image.png

Также установите Flask: `cmd` `>>` `pip install flask`

Когда вы уже поставите свой сайт на домен - не забудьте поменять домен сайта в коде и на dev.vk.com
