## Привет! 👋

<a href="https://t.me/limitedeternity"><img align="left" height=20 width=20 src="https://telegrapher.ru/images/download/icons/telegram.svg" /></a>
<a href="https://vk.me/limitedeternity"><img align="left" height=20 width=20 src="https://pngicon.ru/file/uploads/vk-256x256.png" /></a>
<br>

Меня зовут **Вячеслав**. Для простоты можно **Ви**. 

Решаю судоку перманентным маркером, слушаю синтвейв, починяю примус и участвую в CTF-соревнованиях.<br>
Я – IT-энтузиаст с широким набором языков, инструментов и реализованных проектов за плечами. В сфере IT меня привлекает творческая составляющая – как писатель выражает свои идеи через слова, я выражаю их в виде команд вычислительному устройству.

В настоящее время учусь в РГПУ им. А. И. Герцена по направлению «Информационные системы и технологии» (2018-2022). Связаться со мной можно, кликнув любую из кнопочек соцсетей *выше*, а я продолжу свой нарратив.

## 🔖 Внешние профили

**Мой профиль на CodeWars:** 

[![](https://www.codewars.com/users/limitedeternity/badges/small)](https://www.codewars.com/users/limitedeternity)

**Мой профиль на HackTheBox:** 

[![](https://www.hackthebox.eu/badge/image/369200)](https://app.hackthebox.eu/profile/369200)

## 🖥 Мои проекты

### JavaScript

* 🔑 [Unblocker](https://github.com/UnblockerAPI/unblocker) – задумывавшийся изначально как приложение для рендера веб-страниц в PDF-формат, был реорганизован для обеспечения read-only доступа к заблокированным ресурсам. Может конвертировать magnet-ссылки в torrent-файлы, выступать в качестве прокси-сервера для скачивания файлов по прямым ссылкам. И, конечно же, рендерить страницы в PDF-формат. Регулярно набирает 800+ часов аптайма на Heroku в месяц.

* 📒 [DnevnikClient](https://github.com/limitedeternity/dnevnik-client) – альтернатива официальному клиенту [dnevnik.ru](https://dnevnik.ru), которая разрабатывалась мной в школьные годы и принесла мне победу на районном конкурсе IT-проектов. PWA-приложение, поддерживающее работу в офлайн-режиме. Лёгкое и быстрое, написано на фреймворке Vue.js.

* 💡 [AbitOnline](https://github.com/limitedeternity/AbitOnline) – проект с хакатона "Цифровой Прорыв" в номинации "Государственное управление". Электронная приёмная комиссия. Тоже реализован на Vue.js, на бэкенде Zeit Micro.

* 🔎 [MimeDetect](https://github.com/limitedeternity/MimeDetect) – эксперимент по написанию нативного Node-модуля на языке Rust с обёрткой в виде Electron.js и использованию Blocs для вёрстки UI. Приложение идентифицирует формат передаваемых ему файлов по "магическим байтам", а если это сделать не удаётся – сопоставляет расширение файла со внутренней базой данных.

* 📄 [TextReader](https://github.com/limitedeternity/TextReader) – тоже Electron.js приложение. Позволяет читать большие текстовые файлы по кусочкам в 1000 байт. Так, например, можно заглянуть в файл, не загружая его в память полностью.

* ⌨️ [MathNote](https://github.com/limitedeternity/MathNote) – и ещё одно Electron.js приложение. Позволяет делать заметки в формате Markdown с поддержкой LaTeX выражений. Можно сохранять часто используемые выражения в виде *сокращений*, которые при использовании будут раскрываться приложением при отображении заметки.

* ⚙️ [Channel4](https://www.npmjs.com/package/@limitedeternity/channel4) – форк библиотеки, реализующей [**CSP**](https://en.wikipedia.org/wiki/Communicating_sequential_processes) для выполнения асинхронных задач в простейшем виде. Провёл рефакторинг и сделал пару фиксов, касающихся универсальности этого решения.

### Python

* 💾 [Foxford Downloader](https://github.com/limitedeternity/foxford_courses/tree/master/foxford_downloader) – magnum opus, начало моей истории. Ныне представляет чисто историческую ценность. Титанический комбайн для сохранения материалов курсов с сайта [foxford.ru](https://foxford.ru), который поддерживался мной в одиночку. Умел скачивать видеолекции различными способами, которые активно исправлялись командой Нетологии, а также "рулил" headless-браузером для сохранения домашних заданий с ответами на них и лекциями в текстовом формате.

* 📡 [UpDown](https://github.com/limitedeternity/UpDown) – программа для мониторинга доступности веб-сайтов. Создаёт уведомление, когда сайт падает или возвращается в онлайн. Поле экспериментов с различными шаблонами; в качестве базы данных используется SQLite3.

* ☎️ [gRPC-AddressBook](https://github.com/limitedeternity/gRPC-AddressBook) – Программа "Контакты", или же "Адресная книга". Учился использовать gRPC в качестве альтернативы REST.

### Java
> Этому языку я с нуля учился на платформе JetBrains Academy (он же Hyperskill). За месяц (вплоть до истечения пробного периода) сумел выполнить два проекта наивысшего уровня сложности. Вот они:

* 📬 [WebQuizEngine](https://github.com/limitedeternity/JBA-WebQuizEngine) – полноценный бэкенд приложения для создания и проведения опросов, написанный при помощи Spring Boot. Система сборки – Maven. В качестве базы данных используется H2. Есть система авторизации и валидация данных.

* 🔗 [Blockchain](https://github.com/limitedeternity/JBA-Blockchain) – упрощённая модель блокчейна с транзакциями, ботами и сервисами. Многопоточность, сериализация данных и многое другое. Система сборки – Gradle.

* 📝 [TextEditor](https://github.com/limitedeternity/TextEditor) – простенький редактор, сделанный при помощи Swing. "Читатель" есть, а "редактора" не было. Я это исправил 😊

> ---------------- TODO ---------------

**Что по программированию?**

* Использую Dart для Android [[1](https://github.com/limitedeternity/Scanner), [2](https://github.com/limitedeternity/GetItUploaded)] (Flutter).

* Использую Rust [[1](https://github.com/limitedeternity/squidclient), [2](https://github.com/limitedeternity/yanes)] в качестве языка для системного программирования. [Но и C++ не брезгую](https://github.com/limitedeternity/TIPS-Labs).

* Пишу в случае необходимости на Haskell [[1](https://github.com/limitedeternity/some-gists/blob/master/RelationalAlgebra/logicTable.hs), [2](https://github.com/limitedeternity/some-gists/blob/master/RelationalAlgebra/zhegalkinPoly.hs), [3](https://github.com/limitedeternity/some-gists/blob/master/LambdaCalculus/Lambda-to-SKI-to-JS/main.hs)].

-----

**"Дневные" достижения** (помимо репозиториев на GitHub):

* **"Гранд родео"**: за месяц выполнить два проекта уровня Challenging на платформе [**HyperSkill**](https://hyperskill.org/profile/37482557), имея нулевой опыт работы с Java в начале пути.

**"Ночные" достижения**:

* **"Не Mr. Robot, но..."**: добраться до ранга Elite Hacker на [**HackTheBox**](https://app.hackthebox.eu/profile/369200) с Noob за месяц и по пути захватить пол сотни машин.

* **"А что, так можно было?"**: расширить знания по эксплуатации Linux-систем, используя [**Nebula**](https://exploit.education/nebula/).

* **"process is executing new program /bin/dash"**: расширить знания по эксплуатации бинарных уязвимостей, используя [**Phoenix**](https://exploit.education/phoenix/).

* **"Приключение на 20 минут"**: пройти [dostackbufferoverflowgood](https://github.com/limitedeternity/dostackbufferoverflowgood) за 20 минут, в процессе открыв для себя пару-тройку тайных знаний.

* **"Индиана Джонс"**: выполнить все задания [**ROPEmporium**](https://ropemporium.com/) для архитектур i386 и amd64.

* **"Одного байта хватит"**: пройти курс на [**Udemy**](https://www.udemy.com/course/linux-heap-exploitation-part-1) по эксплуатации "выделителей памяти" (malloc).

-----

<img src="https://www.nicepng.com/png/detail/98-982258_footer-bg-waves-audio.png" height=200px width=100% />
