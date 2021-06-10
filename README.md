## Когда можно будет отказать от этого костыля?
Как только я подниму готовый сайт, а будет это в июне - июле. Более точных дат не могу назвать, тк есть штуки более приоритетные.

## Examples

### Stickers list
Список стикеров можно заполнить в файле stickers.js
Каждый стикер в новой строчке с запятой на конце, без пробелов:
```
Sticker | Team Dignitas (Holo) | Cologne 2014,
Sticker | iBUYPOWER (Holo) | Cologne 2014,
```
### List
Пока что формат списка будет достаточно строгим, нужно будет соблюдать такой вид записи. Пробелы и отстуы не важны, значение имеюь лишь спецсимволы по типу кавычек, заыпятых, скобок.

***Важно не писать эти коментарии в итоговом списке. Последний член списка не должен сопровождаться запятой после себя.***

Список можно заполнить в файле list.js.

Пример:
```javascript
[{
        name: "AK-47 | Redline (Field-Tested)";
        price: 10000; // Это комментарий, он ни на что  не влияет, его можно не писать. Я лишь хотел сказать что это максимальная цена, ее можно поставить хоть миллион и не ставить автоацепт, в таком случае вы можете ловить скин, не зная его цены
        minFloat: number; //  любое число в промежутке (0;1), включая десятичные дроби через точку
        maxFloat: number; // same energy
        accept: boolean; //автопринятие, если отключено у скина, то придет уведомление в тг 
    },
    {
        name: "AK-47 | Redline (Field-Tested)";
        price: 10000; // Это комментарий, он ни на что  не влияет, его можно не писать. Я лишь хотел сказать что это максимальная цена, ее можно поставить хоть миллион и не ставить автоацепт, в таком случае вы можете ловить скин, не зная его цены
        minFloat: number; //  любое число в промежутке (0;1), включая десятичные дроби через точку
        maxFloat: number; // same energy
        accept: boolean; //автопринятие, если отключено у скина, то придет уведомление в тг 
    },
];
```
