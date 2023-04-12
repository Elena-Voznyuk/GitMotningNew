# Создание туториала Git
## Команды Git
* git init - позволяет инициализировать репозиторий
* git add - добавление файла для отслеживания
* git commit - фиксация текущего состояния файла
* git diff - команда сравнивает содержимое рабочего каталога с непроиндексированными изменениями
* git diff --staged - команда сравнивает содержимое рабочего каталога с проиндексированными изменениями
* git log - позволяет посмотреть журнал всех операций
* git rm - команда на удаление файла
* git mv - переименовать файл"
* git clone - команда для клонирования проекта
* git commit -amend - команда отмены коммита
* git checkout - команда переключения на ветку или файл или коммит


# Руководство по Markdown


## Раздел первый - Заголовки





## Раздел второй - Списки





## Раздел третий - Исходный код

В чистом Маркдауне блоки кода отбиваются 4 пробелами в
начале каждой строки.

Но в GitHub-Flavored Markdown (сокращенно GFM) есть
более удобный способ: ставим по три апострофа (на букве
Ё) до и после кода. 

Также можно указать язык исходного
кода.

```html
<nav class="nav nav-primary">
 <ul>
 <li class="tab-conversation active">
 <a href="#" data-role="post-count"
class="publisher-nav-color" data-nav="conversation">
 <span class="comment-count">0
комментариев</span>
 <span class="comment-countplaceholder">Комментарии</span>
 </a>
 </li>
 <li class="dropdown user-menu" data-role="logout">
 <a href="#" class="dropdown-toggle" datatoggle="dropdown">

 <span class="dropdown-toggle-wrapper">
 <span>
 Войти
 </span>
 </span>
 <span class="caret"></span>
 </a>
 </li>
 </ul>
</nav>
```
Самое приятное, что в коде не нужно заменять угловые
скобки `< >` и амперсанд `&` на их html-сущности.





## Раздел четвертый - Таблицы