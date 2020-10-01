Руководство по Markdown
=======================

> Официальный перевод от [Alimektor](https://github.com/Alimektor).
>
> Так же вариант руководства можно посмотреть [здесь](https://github.com/sandino/Markdown-Cheatsheet).

Markdown — облегчённый и лёгкий в использовании синтаксис для стилизации любого текста на платформе GitHub.

**Что вы изучите:**

- Как Markdown делает совместное редактирование простым.
- Как Markdown отличается от стандартных подходов форматирования.
- Как использовать Markdown для форматирования текста.
- Как движок GitHub автоматически рендерит Markdown.
- Как применять уникальные расширения Markdown от GitHub.

Что такое Markdown?
-------------------

[Markdown](http://daringfireball.net/projects/markdown/) — это способ стилизации текста в WEB. Вы сможете управлять содержимым документа, форматировать слова жирным или курсивным начертанием, добавлять изображения и добавлять списки — это лишь малая часть того, что мы можем сделать с помощью данного языка разметки. В основном, Markdown — это обычный текст с несколькими неалфавитными символами, к примеру `#` или `*`.

Вы можете использовать Markdown в большинстве сервисов GitHub:

- В [Gists](https://gist.github.com/)
- В комментариях в Вопросах (Issues) и в Запросах на включение изменений (Pull Requests)
- В файлах с расширением `.md` или `.markdown`

Чтобы получить больше информации, посетите “[Writing on GitHub](https://help.github.com/categories/writing-on-github/)” в *GitHub Help*.

Примеры
-------

### Текст ###

```markdown
Это очень простой способ сделать слова **жирными** или другие слова *курсивными* с Markdown.
Вы даже можете сделать [ссылку на Google!](http://google.com).
```

Это очень простой способ сделать слова **жирными** или другие слова *курсивными* с Markdown. Вы даже можете сделать [ссылку на Google!](http://google.com).

### Списки ###

```markdown
Временами у вас появится желание использовать нумерованные списки:

1. Раз.
2. Два.
3. Три.

Временами у вас появится желание использовать ненумерованные списки:

* Начните свой текст с астериска (звёздочки).
* Доказано!

Как альтернатива,

- Дефис работает также.
- Если вам нужны подсписки, поставьте два пробела перед дефисом или астериском:
  - Как здесь
  - И здесь
```

Временами у вас появится желание использовать нумерованные списки:

1. Раз.
2. Два.
3. Три.

Временами у вас появится желание использовать ненумерованные списки:

* Начните свой текст с астериска (звёздочки).
* Доказано!

Как альтернатива,

- Дефис работает также.
- Если вам нужны подсписки, поставьте два пробела перед дефисом или астериском:
  - Как здесь
  - И здесь

### Изображения ###

```markdown
Если вы хотите встроить изображение в ваш документ, то используйте следующий пример:

![Изображение Yakotocat](https://octodex.github.com/images/yaktocat.png)
```

Если вы хотите встроить изображение в ваш документ, то используйте следующий пример:

![Изображение Yakotocat](https://octodex.github.com/images/yaktocat.png)

### Заголовки и цитаты ###

```markdown
Структурированные документы
===========================

Иногда бывает полезно иметь разные уровни заголовков для создания структуры ваших документов.
Начните строку с `#` для создания заголовков.
Несколько строк `##` в строке обозначают меньшие уровни заголовков.

### Это заголовок третьего уровня ###

Вы можете использовать от одного `#` до `######` шести шарпов (знаков решётки) для разных размеров заголовков.

Если вы хотите процитировать кого-то, используйте символ `>` перед строкой:

> Кофе - лучшая когда-либо созданная органическая смесь.
> - Капитан Джейнвэй
```

### Код ###

````markdown
Существует много разных способов стилизация кода с разметкой GitHub.
Если вы хотите встроить кодовые блоки прямо в текст, то оберните их в гравис (машинописный обратный апостроф): `var example = true`.
Если у вас есть более длинный блок кода, вы можете создать его путём отступа с четырьмя пробелами:

    if (isAwesome){
      return true
    }

GitHub также поддерживает запись кодовых блоков, которая допускает несколько строк без отступов:

```
if (isAwesome){
  return true
}
```

И если вы хотите использовать подсветку синтаксиса, укажите язык программирования:

```javascript
if (isAwesome){
  return true
}
```
````

Существует много разных способов стилизация кода с разметкой GitHub. Если вы хотите встроить кодовые блоки прямо в текст, то оберните их в гравис (машинописный обратный апостроф): `var example = true`. Если у вас есть более длинный блок кода, вы можете создать его путём отступа с четырьмя пробелами:

    if (isAwesome){
      return true
    }

GitHub также поддерживает запись кодовых блоков, которая допускает несколько строк без отступов:
```
if (isAwesome){
  return true
}
```

И если вы хотите использовать подсветку синтаксиса, укажите язык программирования:

```javascript
if (isAwesome){
  return true
}
```

> **Совет!**
>
> Всегда используйте способ для создания блоков кода с ` ``` `, желательно указывая язык.

### Дополнительно ###

```
GitHub поддерживает множество дополнительных функций в Markdown, которые помогают вам ссылаться на людей.
Если вы когда-нибудь захотите отправить комментарий кому-то, вы можете прикрепить его имя символом @:
Эй, @kneath — люблю твой свитер!

Но я должен признаться, что списки задач — мои самые любимые:

- [x] Это выполненная задача
- [ ] Это невыполненная задача

Когда вы включайте свой список задач в первом комментарии в Вопросах (Issue), вы увидите полезный индикатор процента выполнения операции в вашем списке вопросов. Это также работает и в Запросах на включение изменений (Pull Requests)!

И, конечно, эмодзи! :sparkles: :camel: :boom:
```

GitHub поддерживает множество дополнительных функций в Markdown, которые помогают вам ссылаться на людей. Если вы когда-нибудь захотите отправить комментарий кому-то, вы можете прикрепить его имя символом @: Эй, [@kneath](https://github.com/kneath) — люблю твой свитер!

Но я должен признаться, что списки задач — мои самые любимые:

- [x] Это выполненная задача
- [ ] Это невыполненная задача

Когда вы включайте свой список задач в первом комментарии в Вопросах (Issue), вы увидите полезный индикатор процента выполнения операции в вашем списке вопросов. Это также работает и в Запросах на включение изменений (Pull Requests)!

И, конечно, эмодзи! ![:sparkles:](https://assets-cdn.github.com/images/icons/emoji/unicode/2728.png ":sparkles:") ![:camel:](https://assets-cdn.github.com/images/icons/emoji/unicode/1f42b.png ":camel:") ![:boom:](https://assets-cdn.github.com/images/icons/emoji/unicode/1f4a5.png ":boom:")

Руководство по синтасису
------------------------

Вот краткий синтаксис Markdown, который вы можете использовать в любом месте на GitHub.com или в ваших собственных текстовых файлах.

### Заголовки ###

```markdown
# Это заголовок первого уровня #

Это заголовок первого уровня
============================

## Это заголовок второго уровня ##

Это заголовок второго уровня
----------------------------

###### This is an <h6> tag ######
```

> **Совет!**
>
> Шарп `#` закрывать необязательно. Но для лучшей читаемости всегда необходимо закрывать заголовок.
>
> Ещё причина в том, что некоторые парсеры Markdown не воспринимают данный код правильно:
>
> ```markdown
> ### Руководство по C#
> ```
>
> Поэтому лучше писать так:
>
> ```markdown
> ### Руководство по C# ###
> ```

### Выделение в тексте ###

```markdown
*Этот текст станет курсивным*
_Этот текст станет курсивным_

**Этот текст станет жирным**
__Этот текст станет жирным__

_Вы **можете** сочетать их_
```

### Списки ###

#### Ненумерованые ####


```markdown
* Пункт 1
* Пункт 2
  * Пункт 2a
  * Пункт 2b
```

#### Нумерованные ###


```markdown
1. Пункт 1
2. Пункт 2
3. Пункт 3
   1. Пункт 3a
   2. Пункт 3b
```

### Изображения ###

```markdown
![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)
```

### Ссылки ###


```markdown
http://github.com — автоматически!
[GitHub](http://github.com)
```

### Цитаты ###

``` markdown
Как сказал Канье Уэст:

> Мы живем в будущем, так что
> настоящее — наше прошлое.
```

### Код внутри текста ###

```markdown
Я думаю, вы должны использовать элемент `<addr>` здесь.
```

GitHub Flavored Markdown
------------------------

GitHub.com использует собственную версию синтаксиса Markdown, которая предоставляет дополнительный набор полезных функций, многие из которых упрощают работу с контентом на GitHub.com.

Обратите внимание, что некоторые функции GitHub Flavored Markdown доступны только в описаниях и комментариях Вопросах (Issues) и в Запросах на включение изменений (Pull Requests). К ним относятся @упоминания, а также отссылки на SHA-1 hashes, Вопросы (Issues) Запросы на включение изменений (Pull Requests). Списки задач также доступны в комментариях Gist и в файлах Gist Markdown.

### Подсветка синтаксиса ###

Это пример того, как вы можете использовать подсветку синтаксиса с помощью [GitHub Flavored Markdown](https://help.github.com/articles/basic-writing-and-formatting-syntax/):


````markdown
```javascript
function fancyAlert(arg) {
  if(arg) {
  }
}
```
````

Вы также можете сделать блок кода, отступая четырьмя пробелами:

```markdown
    function fancyAlert(arg) {
      if(arg) {
      }
    }
```

Вот пример кода Python без подсветки синтаксиса:

```
def foo():
    if not bar:
        return True
```

### Списки задач ###

```markdown
- [x] @упоминания, #отсылки, [links](), **форматирование**, and <del>теги</del> поддерживаются.
- [x] Требуется синтаксис списка (поддерживается любой неупорядоченный или упорядоченный список).
- [x] Это выполненный список.
- [ ] Это невыполненный список.
```

Когда вы включайте свой список задач в первом комментарии в Вопросах (Issue), вы увидите полезный индикатор процента выполнения операции в вашем списке вопросов. Это также работает и в Запросах на включение изменений (Pull Requests)!

### Таблицы ###

Вы можете создавать таблицы, отделяя заголовки дефисом `-` (только для первой строки), а затем разделяя каждый столбец с помощью вертикальной черты `|`: 

``` markdown
Первый заголовок | Второй заголовок |
---------------- | ---------------- |
Контент клетки 1 | Контент клетки 2 |
Контент в первой колонке | Контент во второй колонке |
```


Этот код станет:

| Первый заголовок         | Второй заголовок          |
| ------------------------ | ------------------------- |
| Контент клетки 1         | Контент клетки 2          |
| Контент в первой колонке | Контент во второй колонке |

### SHA-ссылки ###

Любая отссылка на коммит [SHA-1 hash](http://en.wikipedia.org/wiki/SHA-1) будет автоматически преобразована в ссылку на коммит на GitHub.


```markdown
16c999e8c71134401a78d4d46435517b2271d6ac
mojombo@16c999e8c71134401a78d4d46435517b2271d6ac
mojombo/github-flavored-markdown@16c999e8c71134401a78d4d46435517b2271d6ac
```

### Ссылки внутри Вопроса (Issue) ###

Любое число, которое ссылается на Вопрос (Issue) или на Запрос на включение изменений (Pull Request), автоматически преобразуется в ссылку.

```markdown
#1
mojombo#1
mojombo/github-flavored-markdown#1
```

### Пользовательские @упоминания ###

Ввод символа `@`, за которым следует имя пользователя, уведомит этого человека, чтобы он пришел и просмотрел комментарий. Это называется @упоминание команды внутри организации.

### Автоматические ссылки для URL ###

Любой URL (как `http://www.github.com/`) будет автоматически конвертируем в кликабельную ссылку.

> **Совет!**
>
> Используйте такой стиль как вот этот `<http://www.github.com/>` для лучшей читаемости разметки. GitHub поддерживает это.

### Зачёркнутый текст ###

Любое слово, обёрнутое двумя тильдами (как `~~это~~`)
будет зачёркнуто.

> **Пример!**
>
> ~~Это зачёркнутый текст~~

### Эмодзи ###

GitHub поддерживает [эмодзи](https://help.github.com/articles/basic-writing-and-formatting-syntax/#using-emoji)!

![:sparkles:](https://assets-cdn.github.com/images/icons/emoji/unicode/2728.png ":sparkles:") ![:camel:](https://assets-cdn.github.com/images/icons/emoji/unicode/1f42b.png ":camel:") ![:boom:](https://assets-cdn.github.com/images/icons/emoji/unicode/1f4a5.png ":boom:")

Чтобы посмотреть список эмодзи, которые поддерживает данный сервис, посмотрите в [Emoji Cheat Sheet](http://www.emoji-cheat-sheet.com).
