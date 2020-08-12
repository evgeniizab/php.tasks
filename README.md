# Сборник PHP задач 
## Отработка навыков решения задач c использованием TDD

   ```sh
   $ git clone https://github.com/evgeniizab/php.tasks.git
   $ cd php.tasks
   $ composer install
   $ vendor/bin/phpunit
   ```
## Оглавление
###Массивы
```sh
vendor/bin/phpunit ./tests/ArrayTaskTest.php 
```
#### Задача 1
Дан массив с элементами 'Привет, ', 'мир' и '!'. Необходимо вывести на экран фразу 'Привет, мир!'.
#### Задача 2
ан массив с числами. Запишите в новый массив только те числа, в которых есть цифра 5
#### Задача 3
1: Напишите функцию, которая будет сливать два массива таким образом: из, к
   примеру, [1, 2, 3] и ['a', 'b', 'c'] она сделает [1, 'a', 2, 'b', 3, 'c'].

2: Сделайте аналогичную функцию, которая параметрами будет принимать
   не два массива, а произвольное количество (пусть функция параметром принимает
   двухмерный массив, где его подмассивы – это то, что мы будем сливать).
#### Задача 4
Напишите функцию, которая корректно будет складывать часы и минуты.
Примеры: на вход функции подается такое – 01:20:00 + 00:50:00. В результатте функция выведет 02:10:00
#### Задача 5
Дан многомерный массив $arr. Напишите функцию, которая принимает строки
 вида 'строка1.строка2.строка3' – буквы разделенные точками, а возвращает элемент
 многомерного массива $arr['строка1']['строка2']['строка3']. Количество точек в строке
 может быть любым, вложенность массива тоже любая, ключи массива не содержат точек.
