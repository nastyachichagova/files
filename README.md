# files
Начало
Ввод значения x
Положить k = 0
Положить a = 0
Положить b = 0
Положить c = 0
Если x < 0
То:
Вывести 'Ошибка'
Иначе:
Положить x1 = x 
Пока not (x1 div 10 = 0) повторить:
k = k + 1
x1 = x div 10
Положить a = x div 10^k
Положить b = (x div 10) mod 10^(k-1)
Положить с = x mod 10 
Если not (a mod 2 = 0) and not (c mod 2 = 0)
То
Вывести значение выражения (c * 10^k + b * 10 + a)
Иначе
Вывести «Условие не выполнено»
Конец
