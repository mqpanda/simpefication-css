# Установка
Склонируете репозиторий на свой компьютер

    git clone https://github.com/mqpanda/simpefication-css.git


Далее добавьте файл CSS файл в свой проект.

Подключите в свой HTML file

    <link rel='stylesheet' type='text/css' href='/simplefication.css'>

# Использование

Внизу в таблице приведены примеры классов, которые можно использовать. Вместо символа "*" укажите одну букву любой стороны. Если не указывать сторону, то отступы будут задаваться со всех сторон.

Сторона => сокращение:

- `left` => `l`
- `right` => `r`
- `top` => `t`
- `bottom` => `b`
- `horizontal` => `h` - одновременно слева и справа
- `vertical` => `v` - одновременно сверху и снизу

## Например

| Класс | Значение |
|----------|----------|
| `mr-10 mb-50` | `margin-right: 10px; margin-bottom: 50px;`|
| `m-25`| `margin: 25px;` |
| `p-50` | `padding: 50px;` |

Возможны значения от `5px до 100px` с промежутком в `5px` и `10px` от `100px до 200px`

# Отступы margin
| Класс | Значение |
|----------|----------|
| m\*-5 | margin-*: 5px;|
| m\*-10| margin-*: 10px; |
| m\*-15 | margin-*: 15px; |
| ... | ... |
| m\*-85 | margin-*: 85px; |
| m\*-90 | margin-*: 90px; |
| m\*-95 | margin-*: 95px; |
| m\*-100 | margin-*: 100px; |
| m\*-110 | margin-*: 110px; |
| m\*-120 | margin-*: 120px; |
| ... | ... |
| m\*-190 | margin-*: 190px; |
| m\*-200 | margin-*: 200px; |

# Отступы padding
| Класс | Значение |
|----------|----------|
| p\*-5 | padding-*: 5px;|
| p\*-10| padding-*: 10px; |
| p\*-15 | padding-*: 15px; |
| ... | ... |
| p\*-85 | padding-*: 85px; |
| p\*-90 | padding-*: 90px; |
| p\*-95 | padding-*: 95px; |
| p\*-100 | padding-*: 100px; |
| p\*-110 | padding-*: 110px; |
| p\*-120 | padding-*: 120px; |
| ... | ... |
| p\*-190 | padding-*: 190px; |
| p\*-200 | padding-*: 200px; |

# Отчистка базовых стилей
| Класс | Значение |
|----------|----------|
| clear | Очищает базовые стили, которые устанавливает браузер для: `<a>`, `<ul>`, `<li>`.|
| box | Для всех (*) остальных элементов: box-sizing: border-box; outline: none |

# Flex, позиционирование, размер

| Класс           | Значение                        |
| --------------- | ------------------------------- |
| h100p           | height: 100%;                   |
| w100p           | width: 100%;                    |
| d-ib            | display: inline-block;          |
| d-if            | display: inline-flex;           |
| d-flex          | display: flex;                  |
| d-block         | display: block;                 |
| justify-between | justify-content: space-between; |
| justify-around  | justify-content: space-around;  |
| justify-center  | justify-content: center;        |
| align-center    | align-items: center;            |
| align-end       | align-items: flex-end;          |
| align-start     | align-items: flex-start;        |
| flex-column     | flex-direction: column;         |
| flex-row        | flex-direction: row;            |
| flex-wrap       | flex-wrap: wrap;                |
| flex-auto       | flex: 1 1 auto;                 |
| flex            | flex: 1;                        |
| m-auto          | margin: auto;                   |
| ml-auto         | margin-left: auto;              |
| mr-auto         | margin-right: auto;             |
| text-center     | text-align: center;             |
| pos-r           | position: relative;             |
| pos-a           | position: absolute;             |

# Текст

| Класс           | Значение                                                        |
| --------------- | --------------------------------------------------------------- |
| text-center     | text-align: center;                                             |
| text-capitalize | text-transform: capitalize;                                     |
| text-uppercase  | text-transform: uppercase;                                      |
| text-lowercase  | text-transform: lowercase;                                      |
| text-truncate   | white-space: nowrap; overflow: hidden; text-overflow: ellipsis; |
| fw-bold         | font-weight: bold;                                              |

# Opacity

| Класс      | Значение      |
| ---------- | ------------- |
| opacity-1  | opacity: 0.1; |
| opacity-2  | opacity: 0.2; |
| opacity-3  | opacity: 0.3; |
| opacity-4  | opacity: 0.4; |
| opacity-5  | opacity: 0.5; |
| opacity-6  | opacity: 0.6; |
| opacity-7  | opacity: 0.7; |
| opacity-8  | opacity: 0.8; |
| opacity-9  | opacity: 0.9; |
| opacity-10 | opacity: 1;   |
