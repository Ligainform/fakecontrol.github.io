---
layout: post
title: Об отмене гривны
date: 2014-03-27 20:44:13 +0200
comments: true
categories:
---

С 20 марта ходят слухи о правительстве Яценюка, которое собирается изъять гривны. Нестрашные, казалось бы: замена старых гривен на новые. Дальше ситуация нагнетается — правительство будет гривну обрушать и изымать, доходит до «вспомните, как было в СССР», когда новые рубли меняли на старые по курсу не 1:1. Возможно, это рассчитано на людей постарше — для большинства молодёжи страшилки про Советский Союз не имеют особенной силы.

Сам текст находится [здесь](http://odessitos1.livejournal.com/4588.html) (если автор его удалит, у нас всё сохранено отдельно). Весь жж — довольно однонаправленный, позиция автора: он как бы хочет разобраться, но ненавязчиво нагнетает, блог [создан](http://odessitos1.livejournal.com/profile) 10 марта 2014. Вброс о гривне он начал делать практически [сразу же](http://odessitos1.livejournal.com/795.html), с «прогнозов».

По ссылке 5 причин, почему это слеплено вместе, хотя и не так топорно как обычно:

<!-- more -->
1.

  НБУ [опроверг](http://glavcom.ua/news/194378.html) эту информацию;

2.

  Мы связались с [банком Львов](http://www.banklviv.com/) и получили официальный комментарий начальника отдела маркетинга Христины Стефанчук: « […] протягом останнього тижня на російських сайтах та в ефірі російського телеканалу з’явилось фальшиве повідомлення від імені банку «Львів» щодо «изъятия гривны». Дана інформація не відповідає дійсності. Прес-служба ПАТ АКБ «Львів» не публікувала жодної інформації щодо цього питання на своєму сайті. Такі повідомлення є неправдивими та такими, які мають на меті підірвати імідж нашого банку та інших банківських установ України».

3.

  Наличие [страницы ](http://archive.is/g9Pyg/image) в кэше Google — самый серьёзный аргумент из всех. Но стоит обратить внимание, что сайт банка сделан, скорее всего, одним человеком, который [позиционирует себя как студия](http://www.sitegist.com) веб-разработки и 10 лет пишет свою CMS на PHP.  Учитывая это и остальные детали, _предполагаем_ либо уязвимость системы, либо чью-то инсайдерскую работу. В любом случае, наш запрос не стал для банка новостью, возможно, свой пресс-релиз они выпустят позже. К тому же, скриншот якобы этой страницы всё равно потом был поправлен.

  В предыдущем абзаце — ссылка не на кэш Google, а на Archive.is, который позволяет сохранять версии сайтов из кэша Google. Сегодня около полудня [прямая](http://webcache.googleusercontent.com/search?q=cache:0RQLLouF9DEJ:www.banklviv.com/uk/individuals/rule/&client=safari&hl=en&strip=0) ссылка Google ещё работала, сейчас уже нет.

4.

  Мы разобрали изображения  и документ:

  ![Скриншот автора](http://i.imgur.com/fexDfbo.jpg)
  [Полный размер](http://i.imgur.com/fexDfbo.jpg)

  Скриншот автора сам по себе выглядит более-менее правдоподобно, но не совпадает с версией кэша Google. Разные оттенки розового внутри, отсутствие полупрозрачного градиента на иконке документа (этот эффект накладывается поверх исходного изображения в броузере).

  ![Imgur](http://i.imgur.com/E6PTLVA.png)
  [Полный размер](http://i.imgur.com/E6PTLVA.png)

  [Результат](http://fotoforensics.com/analysis.php?id=69961c99af5779e5877f7b0b9740f511e5c5197b.209757) ELA говорит о том, что изображение пересохраняли поверх. (Сравните с [настоящим](http://fotoforensics.com/analysis.php?id=27e7d00ab5e48a363130661db5babe20c2c08cdf.657983)). Кривая Rainbow curve, спасавшая не раз, тоже хорошо [показывает](http://imgur.com/xdthu8a) чужеродные вещи, там же видно, о каком градиенте идёт речь.

  Профиль скриншотов — Adobe RGB и нет exif-данных. Это само по себе не криминал, но это очень похоже на результат работы команды Save For Web в Adobe Photoshop, которая подпортила цветопередачу в разных броузерах не одному фотографу.

  Кто-то сохранил два «снимка» всего сайта в archive.is: [20 марта в 12:54](http://archive.is/La2Sy) («монеты и банкноты», внизу страницы есть ссылка на «новость»)» и [20 марта в 16:12](http://archive.is/g9Pyg), который и показывали в скриншоте броузера. Всего у Банка Львова [четыре таких сохранённых «снимка»](http://archive.is/www.banklviv.com) — один за 2013 год и последний за сегодня, сделанный нами. Archive.is работает так: вы заходите и указываете ссылку, которую хотите сохранить. То есть, это было сделано специально (интересно, что [судя по статистике](http://whois.domaintools.com/archive.org), третья по количеству группа пользователей этого сайта— из России).

  _[PDF-файл](http://rusfolder.com/40183364)_:

  Самое важное: он ссылается на «постанову Правління Національного банку України від 12 березня 2014 No 31 «Про затвердження дизайну і дати випуску в обіг банкнот гривні нового зразка». На [официальном сайте](http://www.bank.gov.ua/control/uk/publish/category?cat_id=58478) она отсутствует, а нумерация не совпадает с текущей. Здесь можно было бы закончить, но мы продолжим рассматривать белые нитки дальше.

  Во-вторых, название — áàíê ëüâîâ .pdf.pdf. Если бы он был скачан напрямую с сайта, он бы назывался аккуратнее, по примеру соседнего документа, «Правила обслуговування рахунків фізичних осіб.pdf» и вряд ли имел бы ещё одно расширение .pdf в названии. Размер немного отличается от А4 — 20.96 × 29.21 см. Дальше, если мы скопируем само название файла в [подзабытый декодер](http://www.artlebedev.ru/tools/decoder/) Студии Лебедева из времени, когда почта ещё приходила в неизвестных кодировках, бНОПНЯ, то получим «банк львов» и переход из CP1252 → CP1251. Самое интересное здесь — название на русском языке (сайт банка существует строго в украинской версии и не имеет ни одного русского слова).

  В-третьих, он сделан по образцу «Правил обслуживания…» с той же страницы (Verdana, разбивка текста), но без внимания к деталям — шрифт разного размера, интервал, есть несколько ошибок, опечаток и стилистических неточностей — «у зв’язку з заміною перебувають в обігу банкнот національної валюти України» (не имеет смысла), «у зв’язку з зміною» (зi), «аж до окремого роз’яснення» (аж до дідька цікавий офіційний стиль!).

5.

  Мы разобрали одну купюру, она показалась очень знакомой. Если отразить «10 новых гривен» по горизонтали (2) и вертикали (3) и сравнить с 5 евро старого (до 2013) образца  — становится понятен источник вдохновения. Размеры совпадают, герб Украины вписан ужасно. Если пойти дальше и поискать «[София Киевская](http://bit.ly/1dwfVjB)», найдётся популярный и иконический вид собора. Вот, [возможный источник](http://citycard-ua.com/sites/default/files/imagecache/product_full/sof._sobor.jpg), избражения подходят друг другу чуть ли не попиксельно (4).

  ![Imgur](http://i.imgur.com/cvc6uW6.jpg)
  [Полный размер](http://i.imgur.com/cvc6uW6.jpg)

  Дополнительные ссылки:

  [Форум](http://fkiev.com/pro-banki-30259/), где цепи Маркова симулируют общение.
  [Вброс](http://forum.vidido.ua/viewtopic.php?f=3&t=26906) на форум Черновцов, где не поддаются панике.
  [Вброс](http://www.prostobank.ua/servisy/onlayn_konsultatsii/valyuta/natsbank_ukrainy_gotovit_vyvod_staryh_deneg_iz_obrascheniya) на форум простобанка пользователем Lupechko. адрес почты «сестры немецкого сотрудника G&D» — loopechka@i.ua

  Если посмотреть вКонтакте [коллегу](https://vk.com/id242012389), на которого в одном из постов ссылается источник вброса — там целая палата наполеонов, сталиных и кутузовых, все с имперскими лентами.

  [Видео](https://www.youtube.com/watch?v=RXdZW5AvQ0I) из того же блога в livejournal, но выложенное другим несуществующим автором со свежего аккаунта. Очень романтично, энигмоподобная музыка, как будто смотришь региональный телеканал в девяностые.

Объём получился таким, что выводы уже лишние. Отдельно хотим написать, что теории о сионистском оккупационном правительстве достоверности в документы ещё не добавляли.

Мы отправили запрос в [G&D](http://www.gi-de.com/en/index.jsp) с просьбой прокомментировать ситуацию. Если ответят — сразу же напишем.

Пожалуйста, распространите это дальше.
