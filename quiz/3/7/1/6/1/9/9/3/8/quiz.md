# Язык Java (Магистратура, 1 курс)
## Осенний семестр 2022 года

### Зачет, вариант 371619938

Зачет состоит из 9 заданий. Максимальное количество баллов за выполнение заданий: 13.
- Для получения оценки 3 необходимо набрать от 5 до 7 баллов.
- Для получения оценки 4 необходимо набрать от 8 до 10 баллов.
- Для получения оценки 5 необходимо набрать от 11 до 13 баллов.

#### Вопрос 1 (количество баллов: 3)

Напишите метод, который берет на вход целое положительное число n и возвращает список `List<Integer>`, содержащий n случайных чисел. Используйте Java Stream API.


#### Вопрос 2 (количество баллов: 1)

Какие из следующих утверждений верны?


- A. Добавление элемента в `ArrayList<T>` имеет в худшем случае сложность O(1).
- B. Размер `ArrayList` может увеличиваться по мере необходимости, в то время как размер массива нельзя изменить.
- C. Поиск элемента списка `ArrayList<T>` по индексу имеет в худшем случае сложность O(1).
- D. В отличие от массивов, для списков нельзя использовать for-each цикл для итерации по всем его элементам.

#### Вопрос 3 (количество баллов: 1)

Какие строки в приведенном фрагменте кода не компилируются? Выберите все верные варианты.

![](https://github.com/java-bfu/master-22-exam/blob/main/img/q1_v4.png)

- A. 13
- B. 14
- C. 15
- D. 16
- E. 17
- F. 18

#### Вопрос 4 (количество баллов: 1)

Что можно сказать о результате компиляции и выполнения следующей программы? Выберите все верные ответы.

![](https://github.com/java-bfu/master-22-exam/blob/main/img/q7_v3.png)

- A. Программа зациклится.
- B. Программа не скомпилируется.
- C. Программа может при выполнении завершиться с ошибкой.
- D. В случае успешного завершения программа выводит в консоль длину самого длинного аргумента командной строки.
- E. В случае успешного завершения программа выводит в консоль длину самого короткого аргумента командной строки.
- F. В случае успешного завершения программа выводит в консоль длину первого аргумента командной строки.

#### Вопрос 5 (количество баллов: 1)

Какие из следующих исключений являются проверямыми?


- A. `ArithmeticException`
- B. `Exception`
- C. `IOException`
- D. `NullPointerException`
- E. `StackOverflowError`

#### Вопрос 6 (количество баллов: 1)

Какое утверждение верно относительно данной программы?

![](https://github.com/java-bfu/master-22-exam/blob/main/img/q2_v3.png)

- A. Программа не компилируется.
- B. Программа компилируется, но при запуске выдаст исключение.
- C. Программа компилируется и запустится без ошибок, но ничего не выведет.
- D. Программа компилируется и запустится без ошибок и напечатает числа от 0 до 19.
- E. Программа компилируется и запустится без ошибок и выведет 0 двадцать раз.
- F. Программа компилируется и запустится без ошибок и двадцать раз выведет null.

#### Вопрос 7 (количество баллов: 1)

Какие из следующих конструкторов можно использовать для класса 
 final class A {}


- A. `A() {}`
- B. `public A(int a) {}`
- C. `private A() {}`
- D. `final A() {}`
- E. `protected A() {}`
- F. `static A() {}`

#### Вопрос 8 (количество баллов: 1)

Какое из следующих утверждений является верным?


- A. Статический метод может вызывать другие нестатические методы в том же классе, используя ключевое слово `this`.
- B. Класс может содержать как статические, так и нестатические поля, а также статические и нестатические методы.
- C. Каждый объект класса имеет собственный экземпляр статических переменных, объявленных в классе.
- D. Нестатический метод не может изменить значение статического поля.

#### Вопрос 9 (количество баллов: 3)

Реализуйте интерфейс `MaxElementFinder`.

![](https://github.com/java-bfu/master-22-exam/blob/main/img/q3_v2.png)