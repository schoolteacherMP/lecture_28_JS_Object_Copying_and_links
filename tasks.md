-  JavaScript имеет два типа копирования объектов: копирование по ссылке и копирование по значению. Когда объект копируется по ссылке, в новую переменную записывается ссылка на существующий объект, и изменения в одном объекте будут отражаться и в другом. Когда объект копируется по значению, создается новая копия объекта, и изменения в одном объекте не будут отражаться в другом.  

-  В JavaScript копирование объектов по ссылке происходит автоматически, когда вы присваиваете одну переменную другой. Чтобы создать копию объекта по значению, можно использовать функцию Object.assign() или оператор spread.  

![image](https://user-images.githubusercontent.com/113675674/212060581-cdee6335-1705-42ac-be74-0015f054f7d2.png)  


## Задача 1  
###   Создание копии объекта  
Напишите функцию copyObject, которая принимает объект и возвращает его копию.   

## Задача 2    
###   Копирование свойств объекта   
Напишите функцию copyProperties, которая принимает два объекта и копирует свойства из первого объекта во второй.  

## Задача 3        
###   Слияние объектов   
 Напишите функцию mergeObjects, которая принимает несколько объектов и сливает их свойства в один объект. 

## Задача 4        
###   Разницу между копированием объектов и копированием ссылок    
Задача:  
Написать программу на JavaScript, которая демонстрирует разницу между копированием объектов и копированием ссылок.  

Решение:  
Для демонстрации разницы между копированием объектов и копированием ссылок, можно создать объект и его копию, а затем изменить значения свойств в оригинальном объекте и скопированном объекте, чтобы увидеть, как это повлияет на каждый из них.  

## Задача 5          
###   Копирование с учетом вложенности  
Написать программу на JavaScript, которая копирует объект const obj = { a: 42, b: 'qwerty', c: { aa: 11, bb: 'Batumi' } } с учетом вложенных свойств.  

## Задача 6      
###   Сравнение объектов  
Напишите функцию compareObjects, которая сравнивает два объекта и возвращает true, если они равны, и false в противном случае.  
мы перебираем свойства объектов obj1 и obj2 с помощью циклов for..in. Для каждого свойства мы проверяем, что оно присутствует в другом объекте и что значения этих свойств равны. Если какое-то свойство отсутствует или его значения не равны, мы возвращаем false. Если все свойства объектов совпадают, мы возвращаем true.  
почитайте про [hasOwnProperty](https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Object/hasOwnProperty)  
