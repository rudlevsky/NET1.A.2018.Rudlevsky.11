# NET1.A.2018.Rudlevsky.11

1. Добавить в класс с методом трансформером массива вещественных чисел перегруженную версию, принимающую делегат. Проверить работу метода на модульных тестах.
[Ссылка](https://github.com/rudlevsky/NET1.A.2018.Rudlevsky.04/blob/master/WordGeneration/WordGeneration/WordGenerator.cs)

2. Выполнить рефакторинг класса (с целью сокращения повторного кода) в алгоритмах Евклида (рефакторинг возможен только в случае, когда все метод находятся в одном классе!). Интерфейс класса измениться не должен. Проверить работу существующих модульных тестов.
[Ссылка](https://github.com/rudlevsky/NET1.A.2018.Rudlevsky.04/blob/master/NodAlgorithms/NodAlgorithms/NodSearcher.cs)
3. В класс с алгоритмом сортировки не прямоугольной матрицы, принимающий как компаратор интерфейс, добавить перегруженный метод, принимающий как параметр делегат-компаратор, инкапсулирующий логику сравнения строк матрицы. Протестировать работу разработанного метода на примере сортировки матрицы, используя прежние критерии сравнения. Класс реализовать двумя способами (два отдельных класса), «замкнув» в первом варианте реализацию метода сортировки с делегатом на метод с интерфейсом (работу выполняет метод с параметром-интерфейсом, метод с делегатом его вызывает), во втором – наоборот (работу выполняет метод с параметром-делегатом, метод с интерфейсом его вызывает).
[Ссылка](https://github.com/rudlevsky/NET1.A.2018.Rudlevsky.07/tree/master/JaggedArrays/JaggedArrays)