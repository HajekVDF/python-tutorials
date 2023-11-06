# Úvod do programování v jazyce Python

## Základy, které musíte znát

### Proměnné
Proměnné jsou místa, kam ukládáme různé hodnoty, které se v průběhu programu mohou měnit. Proces vytváření proměnné nazýváme ***deklarace***. 
V jazyce python nemusíme uvádět, o jaký [datový typ](<#datové typy>) se jedná. 

V jazyce python deklarujeme proměnnou vytvořením názvu a přiřazením hodnoty.
> x = 5 <br>
> y = "Hello"

Hodnotu i datový typ proměnné můžeme v průběhu programu měnit.
> x = 5 <br>
> x = "World"

*x má nyní hodnotu "World"*

### Datové typy
Proměnné mohou ukládat data v různých datových typech, které nám například určují, jakých hodnot smí proměnná nabývat nebo jaké [operace](#Operátory) se s těmito daty mohou provádět.

Základními datovými typy v pythonu jsou:

| název   | zkratka | popis                                                                             | hodnota                            |
|---------|---------|-----------------------------------------------------------------------------------|------------------------------------|
| integer | int     | celá čísla                                                                        | -2, 0, 3, 15                       |
| float   | float   | reálná čísla, čísla s plovoucí <br> desetinnou čárkou (v pythonu desetinná tečka) | -3.5, 0.2, 5.0                     |
| boolean | bool    | pravdivostní hodnoty                                                              | True, False                        |
| string  | str     | textové řetězce                                                                   | "Jakub", "ahoj světe", "5"         |
| list    | list    | seznamy, uspořádané soubory hodnot                                                | [1, 6, 8, -2], ["jablko", "banán"] |

Python obsahuje i další datové typy, ale ty pro účely tohoto návodu zatím potřebovat nebudeme.

### Operátory
