# Практика по массивам

Для работы создайте и используйте ветку develop, это нужно для того, чтобы избежать ошибки при обновлении этого репозитория преподавателем.

### Задание №1

    Напишите функцию `countAverage()`, которая будет возвращать среднее арифметическое значение элементов массива. На вход функция принимает 1 массив.

    **Пример использования**

    ```javascript
    countAverage([2, 4]); // 3
    countAverage([0, 1, 2]); // 1
    ```

### Задание №2

    Напишите функцию `alphaOmega()`, которая будет создавать новый массив, первый элемент которого будет равен первому у входящего массива, а второй - последнему. Воспользуйтесь функцией **at**.

    **Пример использования**

    ```javascript
    countAverage([2, 4, 6, 4]); // [2, 4]
    countAverage([0, 1, 2]); // [0, 2]
    ```

### Задание №3

    Напишите функцию `fill()`, которая будет принимать на вход число и элемент, а возвращать массив с таким количеством этих элементов, который указан передаваемым числом. Воспользуйтесь циклом **for** или методом **newArray**

    **Пример использования**

    ```javascript
    fill(4, 'someString'); // ['someString', 'someString', 'someString', 'someString']
    fill(2, ['anotherString']); // [['anotherString'], ['anotherString']]
    ```

### Задание №4

    Напишите функцию `fromPairs()`, которая возвращает объект, составленный из значений вложенных массивов. Первое элемент массива - ключ, второй - зачение. Воспользуйтесь встроенной в язык функцией **reduce** у массивов, а также методом **Array.isArray**. Документацию вы найдёте [тут](https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce) и ещё [тут](https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Array/isArray)

    *Пример использования**

    ```javascript
    fromPairs([['a', 1], ['b', 2]]); // { 'a': 1, 'b': 2 }
    fromPairs([['someString', [2, 3]], ['b', 2]]); // { 'someString': [2, 3], 'b': 2 }
    ```

### Задание №5

    Напишите функцию `intersection()`, которая создаст массив из уникальных значений, которые есть в каждом из предоставленных массивов. Воспользуйтесь встроенной в язык функцией **filter** у массивов, а также методом **Array.from**. Документацию вы найдёте [тут](https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Array/filter) и ещё [тут](https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Array/from)

    *Пример использования**

    ```javascript
    intersection([1, 2], [2, 3]); // [2]
    intersection(['b', 'e', 'c'], ['b', 'b', 'e']); // ['b', 'e']
    ```