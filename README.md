###Задание 6

Запустить в отладчике программу из примера организации функций (func.S). Вывести в область данных массивы Symbols и Numbers, а также содержимое стека. Выполняя пошагово (или по блокам) программу, подробно и полно объяснить инструктору смысл и размещение параметров, работу функций, выполнение команд соглашения о связях, используемые режимы адресации.

В примере, в функции Read_Sym определяется локальная переменная в стеке, которая не используется. Модифицировать программу таким образом, чтобы она накапливала в этой локальной переменной количество обнаруженных в массиве Symbols байтов, коды которых не являются кодами цифр. Полученное значение должно быть возвращено в вызывающую программу. Кроме того, такие символы не должны передаваться в функцию Trans_Sym.

Разработать программу для вычисления факториала заданного числа с использованием рекурсивного вызова функции. Число вводится из потока стандартного ввода. Результат выводится в стандартный поток вывода в десятичной системе исчисления.
