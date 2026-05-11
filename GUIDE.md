# Rule Structure = the selector + the declaration block

The declaration block is composed of one or more declarations
Each declaration is a pairing of property and a value

h1 {color: maroon; background: yellow;}

h1 = selector
{color: maroon; background: yellow;} = declaration block

color = property
maroon = value

background = property
yellow = value

# CSS Comments

/* This is a CSS comment */

/* This is a CSS comment, and it 
can be several lines long without 
any problem whatsoever. */

# Element Display Roles

CSS has two basic display roles: 
- block formatting context (блочные элементы)
- inline formatting context (строчные элементы)

# Вариант 1: CSS внутри HTML

<style> — это HTML-тег для CSS внутри HTML-файла

# Вариант 2: отдельный CSS-файл

<link rel="stylesheet" href="style.css"> — это HTML-строка, которая подключает внешний CSS-файл к HTML-странице.

<link> = HTML-тег для подключения внешнего ресурса
rel="stylesheet" = говорит, что подключаемый файл — это CSS-таблица стилей
href="style.css" = путь к CSS-файлу


@import используется в CSS, чтобы подключить один CSS-файл внутрь другого CSS-файла.

