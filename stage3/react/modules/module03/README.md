# Неделя 3

## React. API




!! Задание выполняется в личном приватном репозитории !!
~Можно~ Нужно выполнять задание на базе предыдущего




Что должно быть сделано:



1) Создать отдельную ветку для этого задания
~~2) Настроить webpack. Использование create-react-app запрещено. Можно использовать любую другую тулу для сборки(vite, rollup, esbuild)~~
~~3) Добавить скрипт для prod/dev сборки(в prod должна быть минификация, source-maps и другие оптимизации)~~
~~4) Настроить eslint(airbnb или строже), prettier так, чтобы проект не собирался при наличие ошибок.~~

2) Создать React App которое состоит из 4 логических частей:
    - **строка поиска.** Вводим текст -> нажимаем Enter -> отправляем запрос к API с введенным параметром -> список результатов поиска обновляется
    - **список результатов поиска**: отображает данные, которые вернул API запрос(чем информативнее, тем лучше, но не больше 7 параметров). Предлагается использовать следующие API(но можно использовать любое другое, которое вам нравится, если оно поддерживает поиск, пагинацию и сортировку): 
      - https://www.flickr.com/services/api/flickr.photos.search.html
      - https://newsapi.org/docs/endpoints/everything   
      - https://the-one-api.dev/documentation
    - **переключатели для сортировки**(как минимум три варианта сортировки). Выбираем параметр -> отправляем запрос к API с введенным параметром -> список результатов поиска обновляется
    -  **переключатели для пагинации.** Должна быть возможность выбрать количество результатов на странице и номер страницы, на которой мы находимся сейчас + общее количество страниц. Выбираем параметр -> отправляем запрос к API с введенным параметром -> список результатов поиска обновляется
3) Сделать индикатор загрузки (компонент с анимацией или хотя бы строка - "Загружаем"). Расположение индикатора на свое чувство прекрасного.

Все логические части должны быть вынесены в компоненты.
**User friendly интерфейс с индекатором загрузки и сообщениями на случай если данные не найдены или что-то сломалось приветствуются.**
**4) Переписать форму на Formik?**
**5) Добавить тесты, апи коллы замокать**

### Оценка




Задание будет оцениваться ментором в сентябре. Для удобства проверки создайте Pull Request(**МЕРЖИТЬ НЕ НАДО**).




1) Webpack, eslint, prettier, scripts - **0.5 балла**
2) App + API - **14.5 баллов**




Если хоть один из пунктов не выполнен, то задание оценивается в **0 баллов**.

## Теория

https://www.youtube.com/watch?v=qdCHEUaFhBk&list=PL4cUxeGkcC9gZD-Tvwfod2gaISzfRiP9d&index=17
https://www.youtube.com/watch?v=qtheqr0jgIQ&list=PL4cUxeGkcC9gZD-Tvwfod2gaISzfRiP9d&index=18
https://www.youtube.com/watch?v=DTBta08fXGU&list=PL4cUxeGkcC9gZD-Tvwfod2gaISzfRiP9d&index=19