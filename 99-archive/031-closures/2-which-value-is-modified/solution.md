**Результатом будет `true`**, т.к. `var` обработается и переменная будет создана до выполнения кода.

Соответственно, присвоение `value=true` сработает на локальной переменной, и `alert` выведет `true`.

**Внешняя переменная не изменится.**

P.S. Если `var` нет, то в функции переменная не будет найдена. Интерпретатор обратится за ней в `window` и изменит её там.

**Так что без `var` результат будет также `true`, но внешняя переменная изменится.**
