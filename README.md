# onlineConsultantBlocker

Самый простой способ избавиться от назойливых онлайн-консультантов — заблокировать доступ к ним на самом низком уровне, т.е. через host файл. И браузер не перегружается лишними расширениями и блокировка надёжная по всем фронтам.

## Где лежит файл hosts?
- **Windows:** C:/Windows/System32/drivers/etc/hosts
- **Linux:** /etc/hosts
- **OSX:** /private/etc/hosts

## Как установить?
- Скопировать текст со страницы [hosts](https://raw.githubusercontent.com/pafnuty/onlineConsultantBlocker/master/hosts) и вставить в свой hosts файл.

## Как использовать с блокировщиками рекламы?
- Добавляем [эту ссылку](https://raw.githubusercontent.com/pafnuty/onlineConsultantBlocker/master/online-consultant.txt) как источник в свой блокировщик рекламы.

## Как добавить новую блокировку?
Если вы наткнулись на сайт, где установлен онлайн-консультант
 - [напишите об этом](https://github.com/pafnuty/onlineConsultantBlocker/issues), при написании сообщения добавьте упоминание меня (@pafnuty) для более быстрого реагирования.
Либо вы можете самостоятельно отредактировать файлы и отправить pull-request.

## Благодарности!
- [Всем контрибьюторам](https://github.com/pafnuty/onlineConsultantBlocker/graphs/contributors) за помощь в добавлении и редактировании блокировок
- [acuna-public](https://github.com/acuna-public/CallbackWidgetsBlocker) за большой список консультантов и идею со ссылкой для адблокеров.
