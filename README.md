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
- :exclamation: [leadia.ru](http://leadia.ru)
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
- :exclamation: [callbackhunter.com](http://callbackhunter.com/)
- :exclamation: [me-talk.ru](http://me-talk.ru/)
- :exclamation: [binotel.ua](http://binotel.ua)
- :exclamation: [leadback.ru](http://leadback.ru)
- :exclamation: [venyoo.ru](http://venyoo.ru)

   
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

# Блокируем leadia.ru
127.0.0.1 api.leadiacloud.com
127.0.0.1 api.cloudleadia.com

# Блокируем livetex.ru
127.0.0.1 web-client.livetex.ru
127.0.0.1 web-client-02.livetex.ru
127.0.0.1 widgets.livetex.ru

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

# Блокируем callbackhunter.com
127.0.0.1 cdn.callbackhunter.com

# Блокируем me-talk.ru
127.0.0.1 me-talk.ru

# Блокируем binotel.ua
127.0.0.1 my.binotel.ua

# Блокируем leadback.ru
127.0.0.1 leadback.ru

# Блокируем api.venyoo.ru
127.0.0.1 api.venyoo.ru

#------------------------------
```

## Как добавить новую блокировку
Если вы наткнулись на сайт, где установлен онлайн-консультант, не указанный в списке или не помеченный красным восклицательным знаком - [напишите об этом](https://github.com/pafnuty/onlineConsultantBlocker/issues), при написании сообщения добавьте упоминание меня (@pafnuty) для более быстрого реагирования.
Либо вы можете самостоятельно отредактировать файл readme.md и отправить pull-request.

## Бонус!

```
# Блокируем рекламу в skype
# http://git.io/vkfQv
#------------------------------
127.0.0.1 ads1.msn.com
127.0.0.1 a.ads2.msads.net
127.0.0.1 b.ads2.msads.net
127.0.0.1 *.msads.net
127.0.0.1 *.msecn.net
127.0.0.1 *.rad.msn.com
127.0.0.1 *.rads.msn.com
127.0.0.1 *.ads?.*
127.0.0.1 ac3.msn.com
127.0.0.1 ad.doubleclick.net
127.0.0.1 adnexus.net
127.0.0.1 adnxs.com
127.0.0.1 ads?.*
127.0.0.1 adriver.ru
127.0.0.1 aka-cdn-ns.adtech.de
127.0.0.1 api.skype.com
127.0.0.1 apps.skype.com
127.0.0.1 bs.serving-sys.com
127.0.0.1 c.msn.com
127.0.0.1 c.msn.com.nsatc.net
127.0.0.1 cdn.atdmt.com
127.0.0.1 cds26.ams9.msecn.net
127.0.0.1 db3aqu.atdmt.com
127.0.0.1 ec.atdmt.com
127.0.0.1 flex.msn.com
127.0.0.1 flex.msn.com.nsatc.net
127.0.0.1 g.msn.com
127.0.0.1 live.rads.msn.com
127.0.0.1 msntest.serving-sys.com
127.0.0.1 preview.msn.com
127.0.0.1 rad.msn.com
127.0.0.1 rad.msn.com.nsatc.net
127.0.0.1 secure.flashtalking.com
127.0.0.1 sO.2mdn.net
127.0.0.1 static.2mdn.net
127.0.0.1 static.skypeassets.com
127.0.0.1 static-asm.secure.skypeassets.com
127.0.0.1 ui.skype.akadns.net
127.0.0.1 ui.skype.com
```

Если вы ещё хотите убрать пустые ракламные блоки в skype 7, тогда:
- Открываем файл `c:/Users/ИМЯ_ПОЛЬЗОВАТЕЛЯ/AppData/Roaming/Skype/ЛОГИН_В_СКАЙПЕ/config.xml`
- Заменяем нулями значения, указанные в тегах:
```
AdvertEastRailsEnabled
AdvertLargeEastRailCutoff
AdvertNorthRailCutoff
AdvertPlaceholder
AdvertSmallEastRailCutoff
```
Должно получиться так:
```
<AdvertEastRailsEnabled>0</AdvertEastRailsEnabled>
<AdvertLargeEastRailCutoff>0</AdvertLargeEastRailCutoff>
<AdvertNorthRailCutoff>0</AdvertNorthRailCutoff>
<AdvertPlaceholder>0</AdvertPlaceholder>
<AdvertSmallEastRailCutoff>0</AdvertSmallEastRailCutoff>
```
Для полной уверенности делаем файл доступным только для чтения.

