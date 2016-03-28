#Email Development Framework
Фреймворк для клевой верстки email рассылок. Иными словами - бутстрап для писем.

<a href="http://dudeonthehorse.github.io/kilogram/">Демо здесь</a>

#Основная ветка
В основной ветке репозитория расположен шаблон письма на основе моего подхода к верстке писем. Отдельное спасибо Nicole Merlin https://github.com/emailwizardry. Многие идеи я перенял у нее. Если вы хотите использовать этот шаблон в своих целях, то перед использованием на продакшене, объединяйте файл стилей с основным файлом верстки и прогоняйте полученный код через http://inliner.cm/

#Dev ветка
Здесь у нас уже более полноценная для разработки писем вещь. Для начала работы, вам необходимо завести на своей машине NodeJS и клонировать репозиторий. Находясь в корневой папке, выполните команду:

$ npm install

и менеджер пакетов подтянет все необходимые модули. В папке projects располагаются проекты, над которыми ведется разработка. Для того, чтобы запустить gulp сборщик писем и инлайнер стилей, а также минификатор для build версии, выполните команду:

$ gulp

находясь в папке проекта. И тут начинается волшебство. Работу над проектом мы ведем в папке "dev". В это время gulp watcher в реальном времени отслеживает все изменения верстки и делает работоспособный билд в папке "build". Билд объединяет все файлы стилей шаблона в один, подключает его к файлу верстки и инлайнит все необходимые стили по DOM структуре. После чего код полученного письма минифицируется.

Спасибо Александру Зидыганову https://github.com/csscoderRU/ за участие в развитии фреймворка.

#Поддержка почтовых клиентов
- MS Outlook 2003-2007
- MS Outlook 2010-2013
- Outlook.com (web, iOS, android, windows phone)
- Thunderbird (windows)
- AOL (iOS)
- Yahoo! (web, iOS)
- Google Inbox (iOS, android)
- Gmail (web, iOS, android)
- Mail.ru (web, iOS)
- Rambler.ru (web)
- Yandex mail (web, iOS, android)
- myMail (iOS, android)
- Sparrow (OSX, iOS) <i>deleted from Apple Store</i>
- Airmail (OSX)
- Apple Mail (OSX, iOS)
- Mailbox (OSX, iOS, android)
- Spark (iOS)
