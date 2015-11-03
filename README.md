# onlineConsultantBlocker

Самый простой способ избавиться от назойливых онлайн-консультантов — заблокировать доступ к ним на самом низком уровне, т.е. через host файл. И браузер не перегружается лишними расширениями и блокировка надёжная по всем фронтам.

## Где лежит файл hosts?

- **Windows:** C:/Windows/System32/drivers/etc/hosts
- **Linux:** /etc/hosts
- **OSX:** /private/etc/hosts

## Известные консультанты:
:exclamation: — блокируется

:grey_exclamation: — пока не блокируется (не натыкался)

- :exclamation: [jivosite.ru](http://jivosite.ru)
- :exclamation: [siteheart.com](http://siteheart.com)
- :exclamation: [redhelper.ru](http://redhelper.ru)
- :grey_exclamation: [webim.ru](http://webim.ru)
- :exclamation: [krible.ru](http://krible.ru)
- :grey_exclamation: [cloudim.ru](http://cloudim.ru)
- :exclamation: [gotalk.ru](http://gotalk.ru)
- :exclamation: [livetex.ru](http://livetex.ru)
- :exclamation: [p3chat.com](http://p3chat.com)
- :grey_exclamation: [sitehelp.inkiev.net](http://sitehelp.inkiev.net)
- :grey_exclamation: [spexe.com](http://spexe.com)
- :exclamation: [consultsystems.ru](http://consultsystems.ru)
- :grey_exclamation: [consultant-web.ru](http://consultant-web.ru)
- :grey_exclamation: [activetalk.ru](http://activetalk.ru)
- :grey_exclamation: [livecontact.ru](http://livecontact.ru)
- :grey_exclamation: [marva.ru](http://marva.ru)
- :grey_exclamation: [mibew.org](http://mibew.org)
- :grey_exclamation: [netroxsc.ru](http://netroxsc.ru)
- :grey_exclamation: [onlinesaler.ru](http://onlinesaler.ru)
- :grey_exclamation: [rustalk.net](http://rustalk.net)
- :grey_exclamation: [siteheart.com](http://siteheart.com)
- :grey_exclamation: [talkdriver.ru](http://talkdriver.ru)
- :grey_exclamation: [zopim.com](http://zopim.com)
- :exclamation: [onicon.ru](http://onicon.ru/)
- :exclamation: [leadiacloud.com](http://leadiacloud.com/)
- :exclamation: [skobeeff.ru](http://skobeeff.ru/)
- :exclamation: [pravoved.ru](https://pravoved.ru/)
- :exclamation: [cleversite.ru](http://cleversite.ru/)
- :exclamation: [blablateka.com](http://blablateka.com/)
- :exclamation: [chatra.io](http://chatra.io/)
- :exclamation: [eyenewton.ru](http://eyenewton.ru/)
- :exclamation: [zopim.com](http://zopim.com/)

   
## Код для вставки 
```
# Блокируем онлайн-консультанты
# http://git.io/vkfQv
#------------------------------

# Блокируем jivosite.ru
127.0.0.1 cdn.jivosite.com code.jivosite.com

# Блокируем siteheart.com
127.0.0.1 widget.siteheart.com static.siteheart.com

# Блокируем redhelper.ru
127.0.0.1 web.redhelper.ru

# Блокируем livetex.ru
127.0.0.1 web-client.livetex.ru
127.0.0.1 web-client-02.livetex.ru

# Блокируем gotalk.ru
127.0.0.1 www.gotalk.ru gotalk.ru

# Блокируем p3chat.com
127.0.0.1 p3chat.com

# Блокируем onicon.ru
127.0.0.1 cp.onicon.ru

# Блокируем leadiacloud.com
127.0.0.1 api.leadiacloud.com

# Блокируем krible.com
127.0.0.1 cdn.krible.com

# Блокируем skobeeff.ru
127.0.0.1 widget.skobeeff.ru

# Блокируем pravoved.ru
127.0.0.1 api-pravoved.s3.amazonaws.com

# Блокируем cleversite.ru
127.0.0.1 cleversite.ru

# Блокируем blablateka.com
127.0.0.1 code.blablateka.com

# Блокируем chatra.io
127.0.0.1 chat.chatra.io

# Блокируем consultsystems.ru
127.0.0.1 consultsystems.ru

# Блокируем zopim.com
127.0.0.1 v2.zopim.com

# Блокируем eyenewton.ru
127.0.0.1 eyenewton.ru

#------------------------------
```

## Как добавить новую блокировку
Если вы наткнулись на сайт, где установлен онлайн-консультант, не указанный в списке или не помеченный красным восклицательным знаком - [напишите об этом](https://github.com/pafnuty/onlineConsultantBlocker/issues), при написании сообщения добавьте упоминание меня (@pafnuty) для более быстрого реагирования.
Либо вы можете самостоятельно отредактировать файл readme.md и отправить pull-request.

