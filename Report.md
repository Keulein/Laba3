РУБЕЖНЫЙ КОНТРОЛЬ. АБСТРАКТНЫЕ ТИПЫ ДАННЫХ.

    ##Рубежный контроль II

Выбрать на github по одному проекту, иллюстрирующему работу с абстрактными типами данных (список, очередь, дерево, множество).

Для приведенных типов данных необходимо отметить (номерами строк в файлах) функции работы с абстрактными типами данных (далее АТД), которые были пройдены на лекциях.

Также необходимо отметить, для чего применяется данный АТД в проекте (2-3 предложения).

Про каждый АТД в отчете необходимо написать:

Имя проекта Тип данных Номера строк с функциями АТД Описание назначения АТД

#Задачи

Отчет для списка (list, vector, ...) Отчет для очереди (queue, dequeue, ...) Отчет для дерева (tree) Отчет для множества (set, map, ...)


    ##ОТЧЕТ

1. Список

Проект: Math_learning
Ссылка: https://github.com/tommyguoguo/Math_Learning/tree/master/learn_math_1

##СТРОКИ С ФУНКЦИЯМИ АТД:

а) Вставка элемента: https://github.com/tommyguoguo/Math_Learning/blob/master/learn_math_1/calcu.cpp#L16

б) Объявление вектора: https://github.com/tommyguoguo/Math_Learning/blob/master/learn_math_1/calcu.hpp#L23

##ОПИСАНИЕ НАЗНАЧЕНИЯ АТД

vector<int> Your_ans - вектор, хранящий ответы, введенные пользователем
vector<int> Ans - вектор, хранящий правильные ответы
vector<string> Problems - вектор, хранящий заданные выражения
vector<int> Num1 - вектор, хранящий генерируемый номер выражения
vector<int> Num2 - вектор, хранящий генерируемый номер выражения

2. Очередь

Проект: RestaurantSimulator
Ссылка: https://github.com/davismariotti/RestaurantSimulator/tree/2073b74fb2d6f7ee69de1e49c9132fbc2c553384

##СТРОКИ С ФУНКЦИЯМИ АТД:

а) Добавление в конц очереди: https://github.com/davismariotti/RestaurantSimulator/blob/2073b74fb2d6f7ee69de1e49c9132fbc2c553384/EatingQueue.h#L43

б) Удаление из начала очереди: https://github.com/davismariotti/RestaurantSimulator/blob/2073b74fb2d6f7ee69de1e49c9132fbc2c553384/TableQueue.h#L58

в) Доступ к первому элементу очереди: https://github.com/davismariotti/RestaurantSimulator/blob/2073b74fb2d6f7ee69de1e49c9132fbc2c553384/TableQueue.h#L48

##ОПИСАНИЕ НАЗНАЧЕНИЯ АТД

В данном проекте очередь используется для "эмуляции" работы ресторана( люди, ждущие обслуживания; люди, уже обслуженные; люди, ждущие перемены блюд).

3. Дерево

Проект: aA-algorithms-practice
Ссылка: https://github.com/tungeric/aA-algorithms-practice/blob/d7f0087bef3dd27a9d77cbee82051d5aaefa3094/Algorithms5/

##СТРОКИ С ФУНКЦИЯМИ АТД:

а) Удаление узла: https://github.com/tungeric/aA-algorithms-practice/blob/d7f0087bef3dd27a9d77cbee82051d5aaefa3094/Algorithms5/spec/binary_search_tree_spec.rb#L81

б) Получение значения узла: https://github.com/tungeric/aA-algorithms-practice/blob/d7f0087bef3dd27a9d77cbee82051d5aaefa3094/Algorithms5/solution/spec/binary_search_tree_spec.rb#L58

##ОПИСАНИЕ НАЗНАЧЕНИЯ АТД

В данном проекте дерево используется для реализации двоичного дерева поиска.

4. Множество

Проект: C-containers
Ссылка: https://github.com/efidoalo/C-containers/blob/master/graph.h

##СТРОКИ С ФУНКЦИЯМИ АТД:

а) Вставка элемента во множество(функция): https://github.com/efidoalo/C-containers/blob/master/graph.h#L120

б) Удаление всей памяти множества: https://github.com/efidoalo/C-containers/blob/master/graph.h#L349


