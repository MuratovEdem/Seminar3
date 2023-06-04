# Туториал по основам системы контроля версий GIT


## Инициализация проекта
**Чтобы добавить возможность использовать разные версии файлов, необходимо использовать следующую команду:**

```fix
git init
```


## Как добавить файл в отслеживание

**Чтобы добавить файл на отслеживание, используйте следующую команду:**

```
git add .
```

## Как получить информацию о текущем состоянии файла

**Чтобы получить информацию от git о текущем состоянии, необходимо ввести следующую команду:**

```
git status
```

## Как перейти от одного сохранения к другому

**Чтобы перейти от одного коммита к другому, необходимо ввести следующую команду:**

```
git checkout
```

## Как увидеть разницу между текущим состоянием файла и последним коммитом

**Для того чтобы увидеть разницу между текущим состоянием файла и последним коммитом, необходимо ввести команду:**

```
git diff
```

# Инструкция - туториал по разметке MarkDown


## Заголовки
3312312312
1231231232112
3123123
## Исходный код
В чистом Маркдауне блоки кода отбиваются 4 пробелами в
начале каждой строки.
Но в GitHub-Flavored Markdown (сокращенно GFM) есть
более удобный способ: ставим по три апострофа (на букве
Ё) до и после кода. Также можно указать язык исходного
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
## Таблицы
В чистом Маркдауне нет синтаксиса для таблиц, а в GFM
есть.
First Header | Second Header
------------- | -------------
Content Cell | Content Cell
Content Cell | Content Cell
Для красоты можно и по бокам линии нарисовать:
| First Header | Second Header |
| ------------- | ------------- |
| Content Cell | Content Cell |
| Content Cell | Content Cell |
Можно управлять выравниванием столбцов при помощи
двоеточия.
| Left-Aligned | Center Aligned | Right Aligned |
|:------------- |:---------------:| -------------:|
| col 3 is | some wordy text | **$1600** |
| col 2 is | centered | $12 |
| zebra stripes | are neat | ~~$1~~ |
Внутри таблиц можно использовать ссылки, наклонный,
жирный или зачеркнутый текст.
Для всего остального есть обычный HTML.


##  Изображения

**Чтобы добавить изображения, воспользуйтесь следующей командой**

```
![Альтернативный текст](ссылка на это фото)
```
Пример: 

![Здесь был Вася и его фото](https://plus.unsplash.com/premium_photo-1674939149067-54c18a73efa2?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2487&q=80)

**Если свое фото - то указываем его название**

![Фото лучшей девочки](Image.jpg)

**Если мы хотим добавить изображение-ссылки, то нашу конструкцию нужно сделать такой:**

```
[![альтернативный текст](ссылка)](ссылка на другую картинку - наш перевертыш)
```

[![фото трап](https://images.unsplash.com/photo-1685446983943-81ffb3073581?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=930&q=80)](https://images.unsplash.com/photo-1685491107139-7d7f4f17b3eb?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=688&q=80)

