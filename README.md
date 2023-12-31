# Общее описание решения

## Содержание проекта
Данный проект состоит из модулей, содержащих функции рассчёта площади и периметра геометрических фигур, таких как круг, прямоугольник, квадрат и треугольник.

## Дополнительная информация
В документации содержится описание функций, которые содержатся в модулях, а также примеры их вызовов. 

История изменений проекта содержит всю историю коммитов репозитория (хэши, комментарии, даты, автора коммитов)

---

# Описание модулей

## Модуль circle.py
В данном модуле содержатся функции для расчёта площади и периметра круга.
### Функция area(r)

Данная функция рассчитывает площадь круга по заданному радиусу r.

_Пример вызова:_
```
import circle
print(circle.area(5))  
```  
_Вывод:_  
```
15,70796326794897
```
### Функция perimeter(r)

Данная функция рассчитывает периметр круга по заданному радиусу r.  

_Пример вызова:_  
```
import circle
print(circle.perimeter(2))  
```  
_Вывод:_  
```
6,283185307179586
```
    
## Модуль rectangle.py
В данном модуле содержатся функции для расчёта площади и периметра прямоугольника.
### Функция area(a, b)  

Данная функция рассчитывает площадь прямоугольника по заданным сторонам a и b.  

_Пример вызова:_  
```
import rectangle
print(rectangle.area(3, 7))  
```  
_Вывод:_  
```
21  
```
### Функция perimeter(a, b)  

Данная функция рассчитывает периметр прямоугольника по заданным сторонам a и b.  

_Пример вызова:_  
```
import rectangle
print(rectangle.perimeter(2, 5))  
```  
_Вывод:_  
```
14  
```
## Модуль square.py  
В данном модуле содержатся функции для расчёта площади и периметра квадрата.
### Функция area(a)  

Данная функция рассчитывает площадь квадрата по заданной стороне a.  

_Пример вызова:_  
```
import square
print(square.area(7))  
```  
_Вывод:_  
```
49  
```
### Функция perimeter(a)  

Данная функция рассчитывает периметр квадрата по заданной стороне a.  

_Пример вызова:_  
```
import square
print(square.perimeter(4))  
```  
_Вывод_:  
```
16  
```
## Модуль triangle.py  
В данном модуле содержатся функции для расчёта площади и периметра треугольника.
### Функция area(a, h)  

Данная функция рассчитывает площадь треугольника по заданным основанию a и высоте h.  

_Пример вызова:_  
```
import triangle
print(triangle.area(3, 4))  
```  
_Вывод:_  
```
6  
```
### Функция perimeter(a, b, c)  

Данная функция рассчитывает периметр треугольника по заданным сторонам a, b и c.  

_Пример вызова:_  
```
import triangle
print(triangle.perimeter(1, 3, 5))  
```  
_Вывод:_   
```
9  
```
---
# История изменение проекта
| **Hash** | **Author** | **Comments** |
|----------|----------|----------|
| 8ba9aeb3cea847b63a91ac378a2a6db758682460    | smartiqa <info@smartiqa.ru>   | L-03: Circle and square added   |
| d078c8d9ee6155f3cb0e577d28d337b791de28e2    | smartiqa <info@smartiqa.ru>   |  L-03: Docs added   |
| fa0d43aaeb3c348505c586a2605f99cbd6f59b2f    | Levalnik <levkuimov34@gmail.com>   | Added new file   |
| 2b8665be539574295a48cf7a9c1042f8bc4ed005    |  Levalnik <levkuimov34@gmail.com>   |  Fixed the mistake   |
| 33ffd40a2a3b5ad22ff3717dba825aac5c74bc0d         |  Levalnik <levkuimov34@gmail.com>          | Added comments to functions  |