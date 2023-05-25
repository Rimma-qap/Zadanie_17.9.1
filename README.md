# Задание 17.9.1
Напишите программу, которой на вход подается последовательность 
чисел через пробел, а также запрашивается у пользователя любое число.

В качестве задания повышенного уровня сложности 
можете выполнить проверку соответствия указанному в условии ввода данных.

Далее программа работает по следующему алгоритму:
1. Преобразование введённой последовательности в список
2. Сортировка списка по возрастанию элементов в нем 
(для реализации сортировки определите функцию)
3. Устанавливается номер позиции элемента, 
который меньше введенного пользователем числа, 
а следующий за ним больше или равен этому числу.

При установке позиции элемента воспользуйтесь алгоритмом двоичного поиска, 
который был рассмотрен в этом модуле. Реализуйте его также отдельной функцией.

### Подсказка
Помните, что у вас есть числа, которые могут не соответствовать 
заданному условию. В этом случае необходимо вывести соответствующее сообщение.