# CPP_OOP_HW4
1) Написать контейнерный класс и добавить в него методы:
    а)для удаления последнего элемента массива (аналог функции pop_back() в векторах)
    б)для удаления первого элемента массива (аналог pop_front() в векторах)
    в)для сортировки массива
    г)для вывода на экран элементов.
2) Дан вектор чисел, требуется выяснить, сколько среди них различных. Постараться использовать максимально быстрый алгоритм.
3) Реализовать класс Hand, который представляет собой коллекцию карт. В классе будет одно поле: вектор указателей карт (удобно использовать вектор, т.к. это по сути динамический      массив, а тип его элементов должен быть - указатель на объекты класса Card). Также в классе Hand должно быть 3 метода:
    а)метод Add, который добавляет в коллекцию карт новую карту, соответственно он принимает в качестве параметра указатель на новую карту
    б)метод Clear, который очищает руку от карт
    в)метод GetValue, который возвращает сумму очков карт руки (здесь предусмотреть возможность того, что туз может быть равен 11).
