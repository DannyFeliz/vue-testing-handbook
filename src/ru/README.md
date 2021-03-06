## О чём это руководство?

Добро пожаловать в руководство по тестированию Vue-приложений!

Здесь собрана коллекция коротких примеров тестирования компонентов с использованием `vue-test-utils` – официальной библиотекой для тестированию vue-компонентов. Также используется `Jest` – современный тестовый фреймворк. Рассматривается `vue-test-utils` API и лучшие практики тестирования.

Руководство написано так, что его главы независимы одна от другой. Мы начнём с настройки окружения с помощью `vue-cli` и написания простейших тестов. Затем изучим два способа отрисовки компонентов – `mount` и `shallowMount`, поймём разницу между ними.

Затем разберем несколько сценариев, которые возникают при тестировании компонентов:

- принятие входных параметров
- использование вычисляемых свойств
- отрисовка других компонентов
- пользовательские события

и так далее. Потренируемся на таких интересных кейсах, как:

- тестирование Vuex в компонентах и изоляции
- тестирование Vue router
- тестирование сторонних компонентов

Также поработаем с Jest API, сделаем наши тесты более надежными:

- замокаем API ответы
- замокаем модули и добавим spies (шпионы)
- используем снимки

## Переводы

На данный момент руководство доступно на английском, японском и русском языках.
