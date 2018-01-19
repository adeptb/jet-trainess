# Описание
  Отборочное тестовое задание на курсы стажировки разработчиков пользовательских интерфейсов в [«Инфосистемы Jet»](https://jet.su/)
# Установка
  Склонируйте или загрузите репозиторий
  ```
  $ git clone https://github.com/anpt-jet/jet-trainess.git
  ```
  Запустите `yarn` или `npm` с командой `start` для запуска dev-сервера
  ```
  yarn start
  ```
  или
  ```
  npm run start
  ```
# Сборка
  Запустите `yarn` или `npm` с командой `build` для сборки проекта (выходная директория `./build`)
```
yarn build
```
  или
```
npm run build
```

***


## Задача

> Разработать модуль пользовательского интерфейса: **«Компонент Таблица»**

### Функциональные требования
- Сортировка: при нажатии по названию столбца происходит сортировка по этому столбцу, при повторном нажатии по названию столбца - сортировка в обратном порядке.
- Фильтрация: поле с кнопкой. При нажатии на кнопку происходит фильтрация данных по введенному значению.
- Пагинация.
- Модуль является независимым.
- Модуль имеет возможность переиспользования.


### Нефункциональные требования:
- Синтаксис `ES5+`.
- Чистый JS без использования сторонних библиотек.
- `CSS` / `PostCSS` / `LESS` / `SCSS`.

### Требования к дизайну
Модуль должен быть выполнен в соответствии с макетом.

![Макет](./docs/blank.jpg "The Stormtroopocat")
> Допускаются отклонения от дизайна макета.
### Дополнительные требования
- Код не должен содержать синтаксических ошибок.
- Код должен быть форматирован в соответствии с правилами `ESLint`, `Stylelint`.

- Результат работы должен быть выложен на
<a href="https://github.com">GitHub</a>
/
<a href="https://bitbucket.org">Bitbucket</a>.