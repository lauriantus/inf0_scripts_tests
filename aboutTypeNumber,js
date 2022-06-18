// Ivan Rybak
let intVar = 2;
let floatVar = 10.5;
let stringVar = '4';
let nanVar = NaN;
let infinityVar = Infinity;
let nullVar = null;
let undefinedVar = undefined;

/*
JavaScript - это язык с динамической типизацией, что означает, что интерпретатор 
определяет тип переменной во время выполнения. На практике это позволяет нам 
использовать одну и ту же переменную для хранения разных типов данных в одном и 
том же коде. Это также означает, что без документации и согласованности мы не 
всегда знаем тип переменной в нашем коде, когда мы ее используем.
Работа со строкой или массивом, когда мы ожидаем числа, может привести к 
странным результатам в нашем коде. В этой статье мы рассмотрим различные функции, 
которые могут помочь определить, является ли переменная, которую мы используем, 
числом.

Строки, содержащие числа вроде «10», не принимаются. В JavaScript специальные 
значения, такие как NaN , Infinity и -Infinity , тоже являются числами, однако 
мы будем игнорировать эти значения.

С учетом этих требований лучше всего использовать функцию isFinite() из 
встроенного объекта Number

Однако разработчики обычно использовали для этой цели другие функции, 
в частности Number.isNaN() и функцию typeof()

*****************************************************************************
-----------------------------------------------------------------------------
Функция Number.isFinite() проверяет, является ли переменная числом, 
но также проверяет, является ли это конечным значением. Следовательно, 
он возвращает false для чисел NaN , Infinity или -Infinity .

Если вы хотите проверить, является ли переменная числом, 
лучше всего использовать Number.isFinite() .

------------------------------------------------------------------------------
Стандартный объект Number имеет метод isNaN() Он принимает один аргумент и 
определяет, равно ли его значение NaN . 

Этот метод является довольно разрешительным, поскольку он принимает значения, 
которые вообще не являются числами. Этот метод лучше всего подходит, когда вы 
знаете, что у вас есть число и хотите проверить, является ли оно NaN , а не для 
общей проверки числа.

-------------------------------------------------------------------------------
Функция typeof() - это глобальная функция, которая принимает переменную или 
значение в качестве аргумента и возвращает строковое представление своего типа. 
Всего у JavaScript 9 типов:
-undefined
-boolean
-number
-string
-bigint
-symbol
-object
-null ( typeof() отображается как объект)
-function (особый тип объекта)

Чтобы проверить, является ли переменная числом, нам просто нужно проверить, 
является ли значение, возвращаемое typeof() , "number" .

Функция typeof() работает намного лучше, чем Number.isNaN() . Он правильно 
определяет, что строковая переменная, null и undefined не являются числами. 
Однако он возвращает true для NaN и Infinity .

Хотя это технически правильный результат, NaN и Infinity являются специальными 
числовыми значениями, и в большинстве случаев мы бы предпочли их игнорировать.
-----------------------------------------------------------------------------
                                Заключение                                   
-----------------------------------------------------------------------------
В этой статье мы узнали, как проверить, является ли переменная в JavaScript 
числом. Функция Number.isNaN() подходит только в том случае, если мы знаем, 
что наша переменная является числом, и нам нужно проверить, является ли она 
конкретно NaN или нет.

Функция typeof() подходит, если ваш код может работать с NaN , Infinity или 
-Infinity а также с другими числами.

Метод Number.isFinite() захватывает все конечные числа и наиболее соответствует 
нашим требованиям.
*/
console.log(`-------------------------------------------------------`)
console.log(`intVar = ${intVar} \nNumber.isFinite(intVar) = ${Number.isFinite(intVar)}`);
console.log(`Number.isNaN(intVar) = ${Number.isNaN(intVar)}`);
console.log(`typeof(intVar) = ${typeof(intVar)}\n`);
console.log(`-------------------------------------------------------`)
console.log(`floatVar = ${floatVar} \nNumber.isFinite(floatVar) = ${Number.isFinite(floatVar)}`);
console.log(`Number.isNaN(floatVar) = ${Number.isNaN(floatVar)}`);
console.log(`typeof(floatVar) = ${typeof(floatVar)}\n`);
console.log(`-------------------------------------------------------`)
console.log(`stringVar = ${stringVar} \nNumber.isFinite(stringVar) = ${Number.isFinite(stringVar)}`);
console.log(`Number.isNaN(stringVar) = ${Number.isNaN(stringVar)}`);
console.log(`typeof(stringVar) = ${typeof(stringVar)}\n`);
console.log(`-------------------------------------------------------`)
console.log(`nanVar = ${nanVar} \nNumber.isFinite(nanVar) = ${Number.isFinite(nanVar)}`);
console.log(`Number.isNaN(nanVar) = ${Number.isNaN(nanVar)}`);
console.log(`typeof(nanVar) = ${typeof(nanVar)}\n`);
console.log(`-------------------------------------------------------`)
console.log(`infinityVar = ${infinityVar} \nNumber.isFinite(infinityVar) = ${Number.isFinite(infinityVar)}`);
console.log(`Number.isNaN(infinityVar) = ${Number.isNaN(infinityVar)}`);
console.log(`typeof(infinityVar) = ${typeof(infinityVar)}\n`);
console.log(`-------------------------------------------------------`)
console.log(`nullVar = ${nullVar} \nNumber.isFinite(nullVar) = ${Number.isFinite(nullVar)}`);
console.log(`Number.isNaN(nullVar) = ${Number.isNaN(nullVar)}`);
console.log(`typeof(nullVar) = ${typeof(nullVar)}\n`);
console.log(`-------------------------------------------------------`)
console.log(`undefined = ${undefined} \nNumber.isFinite(undefined) = ${Number.isFinite(undefined)}`);
console.log(`Number.isNaN(undefined) = ${Number.isNaN(undefined)}`);
console.log(`typeof(undefined) = ${typeof(undefined)}\n`);
console.log(`-------------------------------------------------------`)
