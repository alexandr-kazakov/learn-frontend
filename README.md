# Старт в верстке-сайтов на фрилансе

## Вступление

- Рекомендую использовать редактор Visual Studio Code. В сети много хвалебных отзывов насчет Sublime Text, однако я настоятельно рекомендую использовать VSCode а не Sublime. Я сам продолжительное время использовал Sublime Text 3 и могу сказать, что VSCode на голову выше его. В VSCode многое работает "из коробки", что в Sublime нужно настраивать или это отсутствует(может быть информация устарела, было актуально примерно на 2017 год). VSCode бесплатен, а Sublime нет. Переход на VSCode скорее всего будет легкий, есть полноценный русский язык редактора, а также как уже говорилось, много работает "из коробки" и не требует настройки. 

## Перед поиском первых заказов на фрилансе

Есть типовые элементы, которые в верстке встречаются особенно часто и к ним нужно быть готовым. Вот они:
1. Адаптивное меню, например такое: https://i.imgur.com/RHhzfFi.png Меню идет с прозрачным фоном, над секцией с картинкой-фоном. При скролле страницы, меню фиксированное(всегда наверху), следовательно, при скролле страницы у меню появляется темный фон, также само меню становится меньше(по высоте, логотип и любой текст). На мобильных часть меню скрывается и появляется кнопка-гамбургер, при клике на кнопку-габмургер - меню появляется. Нужно уметь делать два базовых типа появления мобильного меню: горизонтальное(выезжает вниз от шапки, например как у bootstrap) и вертикальное, что появляется справа или слева.
2. Адаптивный слайдер и карусель.
3. Модальное окно с контактной формой.

## Подготовка

### Сообщества разработчиков 
Есть различные сообщества разработчиков, также разные open source проекты. Правильным решением будет, если вы будете в чем-нибудь участвовать, это покажет потенциальному заказчику/работодателю вашу заинтересованность в своей работе, также вы сможете кому-нибудь в чем-нибудь помочь. Итак, я рекомендую на самом старте карьеры завести и использовать данные аккаунты:
1. **GitHub**. Здесь на GitHub Pages у вас будет ваш первый сайт-портфолио на бесплатном хостине. Пока вы будете создавать свой сайт-портфолио, вы потренируетесь в самой верстке, а также немного разберетесь как работать с Git.
    - Для начала рекомендую сделать простой одностраничный сайт-портфолио, основные разделы: Стартовый экран => Немного о себе, о своих навыках => Портфолио работ => Ссылки на разные свои отзывы и аккаунты, например stackoverflow => Свои контакты.
    - Порфтолио лучше собирать с первой работы, пусть даже это будет ваша практика. При случае лучше показать что-то, пусть и не самое лучшее, чем ничего.
    - В портфолио можно добавлять свой код, например как вы решаете задачи на JavaScript.
    - Можно оставлять ссылки на свои профили на сайтах по обучению, например sololearn com или codecademy com, там где в профиле указан ваш прогресс в виде ачивок/достижений. Можно даже дать линк на свой профиль disqus, если у вас там есть какие-нибудь разговоры о веб-разработке. Главное, что-бы было что-нибудь и работодатель видел вашу заинтересованность и потенциал. А когда что-то посерьезнее будет, просто старое удалите, новое добавите. 
    - Пусть на старте карьеры у вас будет хотя бы одна работа в портфолио, даже если это будет ваша практика.
    - В разделе - о себе, лучше писать все как есть: что вы начинающий и перспективный, развиваетесь в JavaScript.
2. **Сodepen**. На данном ресурсе вы будете сохранять свой код, который можно сразу запустить. Это будет ваше портфолио всяких классных штук. Смастерите сразу что-нибудь, после сохраните в работы.
3. **Stack Overflow(или например Тостер)**. Дайте ответ хотя бы на один вопрос.
4. **Gist.github**. Здесь сохраняйте код, который не требует запуска. В будущем данный код вы сможете вставлять на страницы сайтов и так далее.
    - Здесь есть подсветка синтаксиса. Чтобы ее активировать, нужно в названии указать расширение файла, например: https://i.imgur.com/Fyv9nTU.png Тогда подсветка автоматически появится.
5. **Фриланс биржы**. Зарегистрируйтесь на всех известных русскоязычных фриланс биржах, а также англоязычных: upwork и freelancer com. Это нужно, чтобы при поиске работы, у вас не виднелось, что ваш аккаунт был создан вчера.
    - Мои реферальные ссылки: https://erweb.ru/ref-links
6. **Вспомогательные инструменты**.
    - В нашем деле нужно уметь делать хорошо скриншоты, с разными там областями выделения и стрелками. Рекомендую: https://getsharex.com/  На русском языке, легко разобраться. Пример: https://i.imgur.com/awuJSHC.png Много раз придется подобным образом заказчикам объяснять что-либо.
    - Также часто необходимо сделать быстро запись экрана. Я использую: https://www.apowersoft.com/free-online-screen-recorder Не могу рекомендовать, не идеальный, но в целом со своей работой справляется(быстро записать видео и выложить на google-диск).

### Кроссбраузерность

Вообще нужно понимать, что здесь необходимы и определенные вложения с исполнителя, если он собирается заниматься фрилансом. Вопрос кроссбраузерности в вопросе вёрстки играет важную роль.

Минимальные вложения такие: 
* телефон на IOS, обязательно с последней версией,
* телефон на Android с актуальной версией,
* Mac с Safari или например как у меня платный сервис browserstack.

На самом деле это минимальный набор, иначе лишь вопрос времени. когда вас объявят некомпетентным специалистом, со всеми вытекающими последствиями.

Мой минимальный набор вышел по деньгам(сверил актуальность на начало 2019 года):
* Новый iPhone SE  ~ 300$(лучше брать именно SE, у него минимальная диагональ экрана на которую верстается).
* Новый телефон на самом свежем Android ~ 230$
* Годовой тарифный план на browserstack.com самый недорогой тариф для фрилансеров = 150$.

Итого минимальные вложения: 680$. Возможно это будет не такая и маленькая сумма для новичка.
Поэтому кто будет заниматься фрилансом более-менее стабильно, то нужно первые более-менее солидные деньги потратить на это. На начальном этапе вам конечно хорошо бы найти более опытного коллегу, кто вам поможет с проверкой кроссбраузерности, например я так помогаю людям.

Конечно для профессиональной вёрстки нужен нормальный монитор c минимальным разрешением 1920×1080. Поэтому работа на ноутбуках с меньшим разрешением кажется мне делом сомнительным.

В общем это необходимо понимать и готовиться к приобретениям.

Конечно, хорошо бы ещё иметь планшет с последней iOS, также монитор с 4к+ разрешеним, Mac с последней версией MacOS и в любом случае подписку на browserstack или похожий сервис, потому что через него, по запросу клиента, можно тестировать на куче старых браузеров и устройств.

### Итого о подготовке:   
 
После того, как сайт-портфолио и все нужные аккаунты готовы, вы идете на Мой круг(возможно, что это только для России) и любые популярные сайты по поиску работы. Там заполняете информацию о себе и оставляете ссылки на все те ваши ресурсы о которых здесь была речь. Если у вас большой город, то не факт, что вам вскоре не начнут писать(особенно если з/п укажите небольшую) работодатели, видя вашу активность и целеустремленность.

## HTML

1. Рекомендую писать классы по БЭМ, можно освоить за один вечер. Это позволит вам прийти к единому стилю кода(почитайте про приоритеты различных стилей записи в CSS) и понять как делать вёрстку независимыми блоками.
2. Сам я пишу на шаблонизаторе Pug, очень нравится, для начала возможно его и не стоит касаться. Это та вещь, которую возможно изучить будет тяжеловато, но затем без него не захотите писать код.
3. Cемантическая верстка. Рекомендую использовать сразу специальные теги, а не делать все div-ами.
Примеры кода, которые показывают насколько лучше читаемость у кода со специальными тегами:
```html
<!-- ##### 1 ##### -->

<article class="article">
  <header class="article__header">
    <h1>Заголовок статьи</h1>
    <p>Подзаголовок статьи</p>
  </header>
  <div class="article__body">
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quibusdam mollitia eaque asperiores, laborum magni repudiandae dolore, totam voluptatem delectus sapiente ullam possimus incidunt nulla, sint consectetur adipisci dolor eos expedita?</p>
    <figure>
      <img src="https://developer.cdn.mozilla.net/media/img/mdn-logo-sm.png" alt="Классная картинка">
      <figcaption>Рис1. Логотип MDN</figcaption>
    </figure>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quibusdam mollitia eaque asperiores, laborum magni repudiandae dolore, totam voluptatem delectus sapiente ullam possimus incidunt nulla, sint consectetur adipisci dolor eos expedita?</p>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quibusdam mollitia eaque asperiores, laborum magni repudiandae dolore, totam voluptatem delectus sapiente ullam possimus incidunt nulla, sint consectetur adipisci dolor eos expedita?</p>
    <figure>
      <img src="https://developer.cdn.mozilla.net/media/img/mdn-logo-sm.png" alt="Классная картинка">
      <figcaption>Рис1. Логотип MDN</figcaption>
    </figure>
    <blockquote cite="http://developer.mozilla.org">
      <p>This is a quotation taken from the Mozilla Developer Center.</p>
    </blockquote>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quibusdam mollitia eaque asperiores, laborum magni repudiandae dolore, totam voluptatem delectus sapiente ullam possimus incidunt nulla, sint consectetur adipisci dolor eos expedita?</p>
  </div>
</article>

<!-- ##### 2 ##### -->

<div class="article">
  <div class="article__header">
    <h1>Заголовок статьи</h1>
    <p>Подзаголовок статьи</p>
  </div>
  <div class="article__body">
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quibusdam mollitia eaque asperiores, laborum magni repudiandae dolore, totam voluptatem delectus sapiente ullam possimus incidunt nulla, sint consectetur adipisci dolor eos expedita?</p>
    <div>
      <img src="https://developer.cdn.mozilla.net/media/img/mdn-logo-sm.png" alt="Картинка">
      <span>Рис1. Логотип MDN</span>
    </div>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quibusdam mollitia eaque asperiores, laborum magni repudiandae dolore, totam voluptatem delectus sapiente ullam possimus incidunt nulla, sint consectetur adipisci dolor eos expedita?</p>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quibusdam mollitia eaque asperiores, laborum magni repudiandae dolore, totam voluptatem delectus sapiente ullam possimus incidunt nulla, sint consectetur adipisci dolor eos expedita?</p>
    <div>
      <img src="https://developer.cdn.mozilla.net/media/img/mdn-logo-sm.png" alt="Картинка">
      <span>Рис1. Логотип MDN</span>
    </div>
    <div cite="http://developer.mozilla.org">
      <p>This is a quotation taken from the Mozilla Developer Center.</p>
    </div>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quibusdam mollitia eaque asperiores, laborum magni repudiandae dolore, totam voluptatem delectus sapiente ullam possimus incidunt nulla, sint consectetur adipisci dolor eos expedita?</p>
  </div>
</div>
```

```html
<!-- ##### 1 ##### -->

<header class="header">
  <div class="container">
    <nav class="nav">
      <ul>
        <li><a href="#"></a></li>
        <li><a href="#"></a></li>
        <li><a href="#"></a></li>
        <li><a href="#"></a></li>
        <li><a href="#"></a></li>
      </ul>
    </nav>
  </div>
</header>

<!-- ##### 2 ##### -->

<div class="header">
  <div class="container">
    <div class="nav">
      <ul>
        <li><a href="#"></a></li>
        <li><a href="#"></a></li>
        <li><a href="#"></a></li>
        <li><a href="#"></a></li>
        <li><a href="#"></a></li>
      </ul>
    </div>
  </div>
</div>
```

## CSS

1. На **id** почти никогда не пишутся стили, id используются в html и js.
2. Забудьте про **!important**, он пишется в исключительных случаях(например чтобы перекрыть стили какого-нибудь плагина или когда в коде уже месиво и когда другое не срабатывает), в верстке с нуля его вообще использовать не стоит. Это будет большой промах и плохая практика, если у вас это будет.
3. В CSS в большинстве своем пишем стили на классы, а не на теги. 
В некоторых случаях допустимо писать стили на теги, если коротко, то когда контент будет подтягиваться из админки(например запись в блоге). В таком случае, отдельно тегам никто(например контент-менеджер) не будет прописывать специально классы, следовательно будут просто теги, на них и записываем стили.
4. Хорошо весь CSS код записывать в алфавитном порядке, сам так делаю. В таком коде гораздо легче разобраться, а еще, это как знак качества. Рекомендую сразу приучить себя так писать, по началу используйте обычную таблицу с алфавитом(EN), как подсказку. В дальнейшем вы запомните порядок и будете писать без подсказок.
5. Анимация. На начальном этапе стоит про это забыть и сконцентрироваться на обучении JavaScript. Наольшинстве сайтов нет вообще никакой анимации, кроме рчто самой элементарной. Многие новички пытаются ее добавить(и я когда-то), а не стоит. Потому что в первую очередь должна быть высокая скорость загрузки страницы, а если ты подключаешь разные там библиотеки для анимации, то для отображения страницы придется загрузать их код. Также рассуждая глобально, есть два типа анмиации: первую назову пионерской, это например библиотека Animate.css), а вторая пишется индивидуально для конкретного случая. Первая почти никому не нужна, а вторая сложна. Итого: про это стоит пока забыть и не пытаться добавлять анимацию(в том числе при скролле страницы). Нужно настроиться на высокую скорость загрузки страницы, чистый код и кроссбраузерность. Стоит стараться на сайт подключать как можно меньше всяких там плагинов.

## Проверка готовой вёрстки

1. Конечно всю верстку проверяем в HTML-валидаторе: https://validator.w3.org/#validate_by_uri
2. Проверяем скорость загрузки страницы:
    - https://developers.google.com/speed/pagespeed/insights/?hl=ru
    - https://testmysite.withgoogle.com/intl/ru-ru

## Современные возможности

Здесь постараюсь писать, что нужно использовать в настоящее момент, чтобы не тратить время на изучение устаревших технологий:
1. Используйте flex и не используйте float. Раньше, в эпоху Bootstrap-3, для построения сетки использовались float-ы, так как flex-ы старые браузеры не поддерживали. Можно увидеть массовое использование float-ов в старой верстке, а аткже в разных там учебниках/видео/курсах, это всё вчерашний день. С момента прихода Bootstrap-4 преимущественно используются flex-ы. Про float-ы нужно знать и иногда можно их применять, но не более того.
2. Не используйте Bootstrap-3. В Bootstrap-4 изменились классы у сетки и сам принцип построения блоков, следовательно, знание Bootstrap-3 вам ничего особенного не даст, стоит сразу учить Bootstrap-4 или актуальную версию(на момент когда вы это читаете).
