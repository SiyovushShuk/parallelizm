IO-bound. Проверяем ссылки на страницах Википедии

![Image alt](https://github.com/SiyovushShuk/parallelizm/blob/master/img/1%20%D1%8F%D0%B4%D1%80%D0%BE.PNG)

24m:20s - время затраченное на 1 поток
1:37 - 5 воркеров
1:02 - 10 воркеров
1:50 - 100 воркеррв

5 воркеров - цп 20 процентов в среднем
10 воркеров - в среднем 25 процентов
100 воркеров - значения сильно скакали.

А основном воркеров имеет небольшое влияние на количество цп. 100 воркеров в основном нестабильно влиял на цп. Значения могли быть как 18% так и 30%


1:40 - скорость генерации на 1 ядре
![Image alt](https://github.com/SiyovushShuk/parallelizm/blob/master/img/1%20%D1%8F%D0%B4%D1%80%D0%BE.PNG)
1:18 - 2 воркера
![Image alt](https://github.com/SiyovushShuk/parallelizm/blob/master/img/2%20workers.PNG)
1:39 - 4 воркера
![Image alt](https://github.com/SiyovushShuk/parallelizm/blob/master/img/4workers.PNG)
0:52 - 5 воркеров
![Image alt](https://github.com/SiyovushShuk/parallelizm/blob/master/img/5workers.PNG)
2:04 - 10 воркеров
![Image alt](https://github.com/SiyovushShuk/parallelizm/blob/master/img/10workers.PNG)
100 workers - error
![Image alt](https://github.com/SiyovushShuk/parallelizm/blob/master/img/maxworkers.PNG)
