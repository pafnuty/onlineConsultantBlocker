# onlineConsultantBlocker

Самый простой способ избавиться отназойливых онлайн-консультантов — заблокировать доступ к ним на саомм низком уровне, т.е. через host файл. И браузер не перегружается лишними расширениями и блокировка надёжная по всем фронтам.

## Где лежит файл hosts?

- **Windows:** C:/Windows/System32/drivers/etc/hosts
- **Linux:** /etc/hosts
- **OSX:** /private/etc/hosts

## Известные консультанты:
:exclamation: — блокируется

:grey_exclamation: — пока не блокируется (не натыкался)

- :exclamation: [jivosite.ru](jivosite.ru)
- :exclamation: [siteheart.com](siteheart.com)
- :grey_exclamation: [webim.ru](webim.ru)
- :grey_exclamation: [krible.ru](krible.ru)
- :grey_exclamation: [cloudim.ru](cloudim.ru)
- :grey_exclamation: [gotalk.ru](gotalk.ru)
- :grey_exclamation: [livetex.ru](livetex.ru)
- :grey_exclamation: [nicon.ru](nicon.ru)
- :grey_exclamation: [p3chat.com](p3chat.com)
- :grey_exclamation: [redhelper.ru](redhelper.ru)
- :grey_exclamation: [sitehelp.inkiev.net](sitehelp.inkiev.net)
- :grey_exclamation: [spexe.com](spexe.com)
- :grey_exclamation: [consultsystems.ru](consultsystems.ru)
- :grey_exclamation: [consultant-web.ru](consultant-web.ru)
- :grey_exclamation: [activetalk.ru](activetalk.ru)
- :grey_exclamation: [livecontact.ru](livecontact.ru)
- :grey_exclamation: [marva.ru](marva.ru)
- :grey_exclamation: [mibew.org](mibew.org)
- :grey_exclamation: [netroxsc.ru](netroxsc.ru)
- :grey_exclamation: [onlinesaler.ru](onlinesaler.ru)
- :grey_exclamation: [rustalk.net](rustalk.net)
- :grey_exclamation: [siteheart.com](siteheart.com)
- :grey_exclamation: [talkdriver.ru](talkdriver.ru)
- :grey_exclamation: [zopim.com](zopim.com)

   
## Код для вставки 
```
# Блокируем jivosite.ru
127.0.0.1 cdn.jivosite.com
127.0.0.1 jivosite.com
127.0.0.1 code.jivosite.com

# Блокируем siteheart.com
127.0.0.1 widget.siteheart.com
127.0.0.1 static.siteheart.com
```

## Как добавить новую блокировку
Если вы наткнулись на сайт, где установлен онлайн-консультант, не указанный в списке или не помеченный красным восклицательным знаком - [напишите об этом](https://github.com/pafnuty/onlineConsultantBlocker/issues).

