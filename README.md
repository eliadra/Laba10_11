# Laba№ 10-11 Стандартная библиотека шаблонов (STL). Алгоритмы
Создать три проекта демонстрацити: использования контейнерных классов для хранения встроенных типов данных; использования контейнерных классов для хранения пользовательских типов данных; использования алгоритмов STL.
В проекте № 1 выполнить следующее:
1. Создать объект-контейнер в соответствии с вариантом задания и заполнить его данными, тип которых определяется вариантом задания. Просмотреть контейнер.
2. Изменить контейнер, удалив из него одни элементы и заменив другие.
3. Просмотреть контейнер, используя для доступа к элементам итераторы.
4. Создать второй контейнер этого же класса и заполнить его данными того же типа, что и первый контейнер.
5. Изменить первый контейнер, удалив из него n элементов после заданного и добавив затем в него все элементы из второго контейнера. Просмотреть первый и второй контейнеры.
В проекте № 2 выполнить то же самое, но для данных пользовательского типа. В качестве пользовательского типа данных использовать пользовательский класс практикума № 6. Для вставки и удаления элементов контейнера использовать соответствующие операции, определенные в классе контейнера. Для ввода-вывода объектов пользовательского класса следует перегрузить операции >> и <<.
В проекте № 3 выполнить следующее:
1. Создать контейнер, содержащий объекты пользовательского типа. Тип контейнера выбирается в соответствии с вариантом задания. Отсортировать его по убыванию элементов. Если алгоритмы не поддерживают используемые контейнеры, написать свой алгоритм. Просмотреть контейнер.
2. Используя подходящий алгоритм, найти в контейнере элемент, удовлетворяющий заданному условию.
3. Переместить элементы, удовлетворяющие заданному условию в другой (предварительно пустой) контейнер. Тип второго контейнера определяется вариантом задания (при перемещении элементов ассоциативного контейнера в неассоциативный перемещаются только данные, ключи не перемещаются и наоборот, при перемещении элементов неассоциативного контейнера в ассоциативный должен быть сформирован ключ). Просмотреть второй контейнер.
4. Отсортировать первый и второй контейнеры по возрастанию элементов. Просмотреть их.
5. Получить третий контейнер путем слияния первых двух. Просмотреть третий контейнер.
6. Подсчитать, сколько элементов, удовлетворяющих заданному условию, содержит третий контейнер. Определить, есть ли в третьем контейнере элемент, удовлетворяющий заданному условию.
Первый контейнер    vector, Второй контейнер list, Встроенный тип данных int
