# АВ тесты

| Наименование | Описание проекта  
| ------------- |------------------| 
| AA тест  |Проведена симуляция, как будто мы провели 10000 АА-тестов. На каждой итерации вам нужно сформировать подвыборки без повторения в 500 юзеров из 2 и 3 экспериментальной группы. Провести сравнение этих подвыборок t-testом. Построена гистограмму распределения получившихся 10000 p-values. Посчитано, какой процент p values оказался меньше либо равен 0.05. Сделан вывод по проведенному АА-тесту, корректно ли работает наша система сплитования.|
| АВ тест |Проверена гипотеза о том, что новый алгоритм во 2-й группе приведет к увеличению CTR. Проведен t-тест, Пуассоновский бутстреп, тест Манна-Уитни, t-тест на сглаженном ctr (α=5) а также t-тест и тест Манна-Уитни поверх бакетного преобразования. Сделана рекомендация о раскатывании нового алгоритма на всех новых пользователей| 

