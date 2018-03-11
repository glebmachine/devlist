# devlist

Frontend - ветки раскачки

Полезные ссылки:
http://webmasters.teamdev.com/#checklist
https://github.com/kamranahmedse/developer-roadmap (перевод https://proglib.io/p/web-developer-2018/?utm_source=telegram.me&utm_medium=social&utm_campaign=shemy-v-pomosch-po-razrabotke-plana-profe&utm_content=15651323)


Разобрать:
https://habrahabr.ru/post/346010/
https://refactoring.guru/ru/design-patterns/catalog
Сводная таблица по всем курсам: https://docs.google.com/spreadsheets/d/1XCKaqR0qT0ZAQGZuGJmyyZHVPLWNwSikOvYTskmtnvo/edit#gid=0


Middle Frontend Developer

Обязанности
- Верстка и программирование разделов приложения
- Написание компонентов, интеграция и сопровождение
- Интеграция с API
- Оптимизация производительности кода и рендеринга
- Написание тестов (отдельных модулей, иногда проекта в целом)
- Сопровождение проекта (разбор логов ошибок, исправлени багов, разбор кейсов)
- Наставничество младших разработчиков

Общие знания:
- Git 
    - курс 1: https://githowto.com/ru 
    - курс 2: https://learngitbranching.js.org/
    - видеокурс от lynda с переводом https://www.youtube.com/watch?v=GyI0T2U_vO8&list=PLpY_9m7gHQDibfa9MJfnEQd2UWI5gztp8
    - документация, частично на русском https://git-scm.com/book/ru/v2/
- Семантическая верстка
- Подключение шрифтов
    - Подключение шрифта к странице: как нужно делать сейчас. И как не нужно делать сейчас: http://nicothin.pro/page/web-fonts 
    - Оптимизация шрифтов. Как получить наименьший размер шрифтовых файлов: http://nicothin.pro/page/webfonts-min
    - Иконочные шрифты и почему они не нужны. Покойся с миром, технология иконочных шрифтов: http://nicothin.pro/page/icon-fonts-2017
- Текст и типографика
- Формы (как работают)
- ARIA (Accessibility Rich Internet Applications)
    - Сайт с рекомендациями по разработке сайтов для людей с нарушениями зрения https://weblind.ru/
- Общие принципы работы http протокола (+чуть реста)
- Понимание принципов SOLID
- Понимание общих принципов и шаблонов проектирования
- Умение пользоваться devtools (курс от paul irish'a http://discover-devtools.codeschool.com/)
- SVG (анимация/подключение?)

JS
- Манипуляции с DOM
- События (пассивные/активные, правильная обработка событий, delegate event паттерн)
- Числа / строки / булы / Объекты
- Массивы и примеры работы с даннными 
- Функции (скоупы/замыкания/конструкторы)
- Прототипное наследование
- Асинхронность: Коллбэки/Промисы
- XHR
- Джаваскрипт машина и асинхронность 

Анимации и производительность
- GSAP
- Принципы отрисовки браузером (конвейер от html/css до изображения на экране)
- Скорость загрузки и отрисовки: https://developers.google.com/web/fundamentals/performance/rail
- Как отлаживать производительность https://developers.google.com/web/fundamentals/codelabs/web-perf/
- 


 Новые технологии и концепции:
- Как делать PWA https://developers.google.com/web/fundamentals/codelabs/your-first-pwapp/
    - Серия видео про интеграцию безопасность надежность: https://www.youtube.com/playlist?list=PLNYkxOF6rcICnIOm4cfylT0-cEfytBtYtСер
- Что такое APPSHELL https://developers.google.com/web/fundamentals/architecture/app-shell
- Как отлаживать сервис воркеры: https://developers.google.com/web/fundamentals/codelabs/debugging-service-workers/
- Как делать доступные оффлайн приложения: https://developers.google.com/web/fundamentals/codelabs/offline/
- Payment API https://developers.google.com/web/fundamentals/codelabs/payment-request-api/
- Push Notifications https://developers.google.com/web/fundamentals/codelabs/push-notifications/

Ангуляр и программирование (https://angular-2-training-book.rangle.io/):
уровень 1
- Компоненты https://angular-2-training-book.rangle.io/handout/components/
- Роутинг https://angular-2-training-book.rangle.io/handout/routing/
- Директивы https://angular-2-training-book.rangle.io/handout/directives/
- Компоненты lifecycle/ViewChild/Style Encapsulation/ElementRef/ChangeDetection https://angular-2-training-book.rangle.io/handout/advanced-components/
- Angular CLI https://angular-2-training-book.rangle.io/handout/cli/

уровень 2
- Реактивные формы https://angular-2-training-book.rangle.io/handout/forms/reactive-forms/reactive-forms.html
- HTTP запросы https://angular-2-training-book.rangle.io/handout/http/
- Модули https://angular-2-training-book.rangle.io/handout/modules/
- Dependency Injection
- RXJS
    - Общее по обрервабл https://angular-2-training-book.rangle.io/handout/observables/
    - Про subject'ы https://www.youtube.com/watch?v=KFV7IgCU68Q (первый доклад)
- nrgx и State Management https://angular-2-training-book.rangle.io/handout/state-management/

- Иммутабельность https://angular-2-training-book.rangle.io/handout/immutable/

- ngx-translate
    - Как пользоваться
    - Как собирать конфиг
    - Как переводить бабелем
- flex-layout
- ssr?
- Change Detection https://angular-2-training-book.rangle.io/handout/change-detection/
- Написать как планировать стили для компонентов (запрещено свойства макета хранить в стилях, как стилизовать сторонние либы)
- nrwl 
  - Дока https://nrwl.io/nx
  - Бесплатный онлайн курс https://angularplaybook.com/p/nx-workspaces

Тулинг:
- Webpack
- Bazel
- Gulp
    - видеокурс на русском по Gulp: https://www.youtube.com/watch?v=uPk6lQoTThE&list=PLDyvV36pndZFLTE13V4qNWTZbeipNhCgQ

Разобрать (куда-то добавить):
- Адаптивные гриды (сетки)

Описать серию статей с ноушн:
- Стейт менеджмент:
    - Файловая структура
    - Именование
    - Описать основные паттерны
- Observable
    - Как импортировать
    - Как работают отписки, когда нужно/ненужно отписываться
