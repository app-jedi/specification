# SPECIFICATION TEMPLATE. ТЕХНИЧЕСКОЕ ЗАДАНИЕ
## Введение
В данном репозитории представлен шаблон технического задания (далее ТЗ), который будет постепенно усовершенствоваться и обрастать новыми возможностями, стандартами и правилами, а так же будет будут предоставлены основные источники, которые помогут в написании статей.

## Содержание
* Разделы ТЗ
* Структура репозитория
* Правила наименований
* Технические требования
* Ссылки для прочтения
* Удобные сервисы

## Разделы ТЗ
* Голосарий
* Общее положение
* Требование к графическому дизайну
* Функциональные требования
* Структура разделов и описание страниц
* Данные и списки
* Требования к видам обеспечения
* Требования к приемке-сдаче проекта
* Приложения

## Структура репозитория
* ./assets/ -- используемые изображения
* ./chapters/ -- главы
* ./config/ -- кастомизация
* ./index.tex -- точка входа
* ./chapter/1-index.tex -- точка входа 1ого главы
* ./chapter/10-main.tex -- `tex` файл первого раздела

## Правила наименований
* Точки входа разделов
...Именнуются в соотствие с их порядковым номером (`i`) и литералом `-index.tex`.
* Внутренние файлы глав
... Если есть потребность -- можно разбить главу на несколько файлов ( для удобства редактирования и компановки ). Тогда их наименование начинается с порядкового номера раздела `i`. Далее следует цифра ( от 0 ) соответсвующая разбиению раздела (`j`). Для наименования используется литерал "-main.tex" Например разобьем раздел "Типы данных" на 5 частей и получим 5 файлов: *50-main.tex*, *51-main.tex*, ..., *54-main.tex*.
* Изображения
... Имя изображения строится из имени файла куда он вставляется с добавлением порядкого номера этого изображения: например разместим 2 изображения в файле *52-main.tex*. Тогда их названиями будут: *52-0-main.png*, *52-1-main.png*.

## Технические требования
* LaTeX
* pdflatex

## Ссылки для прочтения
### Как писать ТЗ?
* [ Теория ТЗ.](https://habr.com/post/138749/)
* [ Практика ТЗ. ]( https://habr.com/post/140574/)
### Примеры ТЗ
* [ Неплохое ТЗ сайта, но не корректное оглавление ](https://vk.com/doc274927580_469304836?hash=3ba29bc93c4236be15&dl=46982c09db14ed6d31)
## Удобные сервисы
* [ Рисование блок схем и диаграм ](https://draw.io)
* [ Прототипирование ](https://pencil.evolus.vn/Downloads.html)
* [ Карта сайта ](https://app.flowmapp.com)
* [ LaTex Online ](https://ru.sharelatex.com/)
