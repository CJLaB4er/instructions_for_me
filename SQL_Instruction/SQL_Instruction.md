# Простейший запрос в SQL

Простейший запрос в SQL выглядит следующим образом:

SELECT __*__ FROM **TABLE**;

Где SELECT и FROM являются обязательными атрибутами. __*__ - указывает на то, что необходимо выбрать все имеющиеся колонки из таблицы. __TABLE__ - имя таблицы из которой производится выборка.

Вместо __*__ можно использовать список конкретных столбцов (использовать их наименование) через запятую, либо какие-то выражения:

SELECT coloumn_1, coloumn_2 AS col, expection_1, expection_2 AS exp FROM TABLE

Где coloumn_1 и coloumn_2 наименования столбцов в талице TABLE, expection_1 и expection_2 - какие-либо выражения. AS col и  AS exp - это так называемые alias (псевдонимы) колонки и выражения стоящие перед AS будут выведены под названием указанным после AS.