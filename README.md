# Configuration-language


Однострочные комментарии:

\ Это однострочный комментарий

Многострочные комментарии:

<!--

Это многострочный

комментарий

-->

Массивы:

{ значение. значение. значение. ... }

Словари:

([

 имя : значение,

 имя : значение,

 имя : значение,

 ...

])

Имена:

[_a-zA-Z][_a-zA-Z0-9]*

Значения:

• Числа.

• Строки.

• Массивы.

• Словари.

Строки:

@"Это строка"

Объявление константы на этапе трансляции:

имя := значение

Вычисление константы на этапе трансляции:

!(имя)