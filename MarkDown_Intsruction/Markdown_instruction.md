# Инструкция по работе с языком разметки Markdown

Данный файл является шпаргалкой по работе с языком разметки Markdown. Ниже приведен синтаксис для работы с элементами текста.

## Заголовки

В Markdown имеется шесть градаций заголовков, от высшего H1 до низшего H6. Заголовки выделяются при поиощи спецсимвола "#" в начале строки. От количества символов перед текстом зависит уровень заголовка.

Пример:

# Это заголовок H1 \#H1
###### Это заголовок H6 \######H6

## Выделение текста

Для выделения текста полужирным, необходимо обрамить его с двух сторон двойным спецсимолом "__", либо "**".

Пример:

__Так выглядит полужирный текст обрамленный__ "__".

**Точно также выглядит текст обрамлённый** "**".

Для выделения тесктс курсивом, необходимо обрамить его с двух сторон одинарным спецсимволом "_", либо "*".

Пример:

_Так выглядит текст курсивом, обрамленный_ "_".

*Точно также выглядит текст обрамленный* "*".

Альтернативный способ обрамления необходим, для того, что бы была возможность использовния одновременного выделения текста курсиом и получжирным без конфликта.

Пример:

**Данный текст является полужирным, и в нем есть слово выделенное _курсивом_.**

Кроме того, текс возможно сделать зачеркнтым. Для этого необходимо обрамить его с двух сторон двойным спецсимволом "~~".

Пример:

~~Вот так выглядит зачёркнутый текст~~

## Списки и отступы

Для получения маркированного списка, необходимо поставить вначале строки один из спецсимолов: "+", "*" или "-".

Пример:

+ Элемент_1 используя "+"
+ Элемент_2 используя "+"

- Элемент_1 используя "-"
- Элемент_2 используя "-"

* Элемент_1 используя "*"
* Элемент_2 используя "*"

Для получения нумерованного списка, необходимо поставить вначале строки цифру с точкой. Нумерация будет автоматической.

Пример:

2. Пункт_2
4. Пункт_3


## Ссылки и картинки

Для вставки ссылки без "Анкора", необходимо обрамить текст ссылки в скобки "<>" с обеих сторон.

Пример:

<https://gb.ru/lessons/280120>

Для вставки ссылки с "Анкором", необходимо текст ссылки заключить в квадратные скобки, а текст "Анкора" прописать рядом в круглых скобках.

Пример:

[Введение в контроль версий (лекции)](https://gb.ru/lessons/280120)

Вставка в текст картинки, происходит аналогично вставке ссылке, с единственным различием - перед квадратными скобками ставится восклицательный знак.

Пример:

![Картинка](Rick.png)


## Цитаты и вставки кода

Для стаки цитаты, достаточно перет ней добавить спецсимвол закрывающей треугольной скобки ">".

Пример:

> Так выглядит цитата.
>
> Это ее продолжение.


Цитатыы могут быть многоуровневыми:
> Первый уровень.
>> Второй уровень.
>>> Третий уровень.

Внутри цитат могут расологаться заголовки, выделение текста, списки и код.

Код в MarkDown может быть вставлен как внутрь текста, так и отдельным блоком. Для ставки кода применяются тройные грависвы или обратные тики (рассположен на клавиши Ё, "```") 

```
print('Hello world!')
```

Пример кода внутри текста: ```print('Hello world!")```

## Таблицы и чек-боксы

Для вставки таблицы используются два спецсисвола: ертикальная черта "|" и дефис "-". Вертикальная черта является разделителем между столбцами. Дефис позволяет посроить горизонтальную черту, количество дефисов не имеет значения.

Пример:

|Наименование|Количество|
|-|-|
|Количество пунктов|7|

## К сожалению в  Visual Studio не отображаются чекбоксы. Но синтаксис выглядит следующим образом:

Для получения чекбокса, достаточно вначале строки вставить пробел заключенный в квадратные скобки.

[ ] Вот так

[X] Так выглядит выполненный чекбокс.
 
## Экранирование

Если возникает необходимость вставить в текст спецсимволы, используемые в разметке, то и как в большинстве языков программирования для этого используется обратная косая черта "\" вставленная перед экранированным символом.