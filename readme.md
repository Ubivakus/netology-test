# **Основные команды Git**
  
✦ git init – инициализация локального репозитория  
✦ git status – получить информацию от git о его текущем состоянии  
✦ git add – добавить файл или файлы к следующему коммиту  
✦ git commit -m “message” – создание коммита  
✦ git log – вывод на экран истории всех коммитов с их хеш-кодами  
✦ git checkout – переход от одного коммита к другому  
✦ git checkout master – вернуться к актуальному состоянию и продолжить работу  
✦ git diff – увидеть разницу между текущим файлом и закомиченным файлом  
✦ git status – вызывается для определения состояния файлов  
  
## **Возможности языка разметки Markdown**
  
### Заголовки бывают от 1 до 6 уровня 
  
Язык разметки *Markdown* поддерживает 2 стиля обозначения заголовков:  
подчеркивание и выделение символом («#»). Выделение заголовков с помощью  
подчеркивания производится знаками равенства («=») в случае, если заголовок  первого  
уровня, и дефисами («-») в случае, если заголовок второго уровня.  Количество знаков  
подчеркивания не ограничивается.  
  
#### Цитаты  
Для обозначения цитат в языке Markdown используется знак «больше» («>»).  
Его можно вставлять как перед каждой строкой цитаты, так и только перед первой строкой  
параграфа.  
Также синтаксис __Markdown__ позволяет создавать вложенные цитаты (цитаты внутри цитат).  
Для их разметки используются дополнительные уровни знаков цитирования («>»).  
Цитаты в Markdown могут содержать всевозможные элементы разметки.  
Цитаты в языке Markdown выглядят следующим образом:  
> Туча мглою небо кроет,  
> Вихри снежные крутя.  
> То как зверь она завоет,  
> То заплачет, как дитя.  
>> (Автора не помню)  

##### Списки  
Markdown поддерживает упорядоченные (нумерованные) и неупорядоченные (ненумерованные)  
списки.  
Как бы ни нумеровал пользователь список, на выходе он в любом случае будет иметь  
упорядоченный список, начинающийся с единицы (1, 2, 3…).  

1. Первый элемент списка  
 1. Второй элемент списка  
  1. Третий элемент списка  

Для того чтобы создать горизонтальную линию с использованием синтаксиса языка Markdown,  
необходимо поместить три (или более)дефиса или звездочки на отдельной строке текста.  
Между ними возможно располагать пробелы. Горизонтальные линии в ***Markdown*** выглядят  
следующим образом:  

Первая часть текста  

---
Текст, который нужно отделить разделителем  

***  

###### Ссылки и картинки  

[Источник информации](https://github.com/OlgaVlasova/markdown-doc/blob/master/README.md#Parag/ "Сайт github.com")  

<https://github.com/OlgaVlasova/markdown-doc/blob/master/README.md#Parag>  

<https://ru.markdown.net.br/bazovyy-sintaksis/>  

Добавим картинку  

![Добавление картинок](https://markdown.net.br/assets/img/markdown.jpg "Логотип Markdown")  

## Создание таблиц в Markdown

| Столбец 1 | Столбец 2 | Столбец 3 |  
| --------- | --------- | --------- |  
| Строка 1  | Строка 2  | Строка 3  |  
| Еще текст | Снова текст | Заключительный текст |  

Таблица готова!  

![Новая картинка](https://www.mactale.com/images/macdown.jpg "Картинка с таблицей")  

