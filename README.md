# Presentation-Object

Table of Contents

>OBJECT
>
>Destructuring
>
>Spread
>
>THIS
>
>New Date()

## What is Object in JavaScript?
>Конструктор Object создаёт объект-обёртку.

## Create object
>Объект JavaScript — это непримитивный тип данных, который позволяет вам хранить несколько коллекций данных

![](https://camo.githubusercontent.com/591fcf6923b35f65cbc396c3cf64c5982a118c7c3a1e84b929b742a59114de03/68747470733a2f2f617661746172732e6d64732e79616e6465782e6e65742f693f69643d316563613237383030343733313339643363356435326265383436326336636636333538666566662d373636343038392d696d616765732d7468756d6273266e3d3133)

# Methods object
### Object.entries()
![](https://github.com/Kamolzoda/Lecture-Object/raw/main/Снимок%20экрана%202023-03-28%20100949.png)

### Object.keys()
![](https://github.com/Kamolzoda/Lecture-Object/raw/main/Снимок%20экрана%202023-03-28%20101114.png)

### 
![](https://github.com/Kamolzoda/Lecture-Object/raw/main/Снимок%20экрана%202023-03-28%20101228.png)

## What is Destructuring and Spread in JavaScript?

### Destructuring and Spread in Object
>Синтаксис деструктурирующего присваивания представляет собой выражение JavaScript, которое делает его можно распаковать свойства объекта в отдельные переменные
![](https://github.com/Kamolzoda/Lecture-Object/raw/main/Снимок%20экрана%202023-03-28%20101813.png)

## What is keyword "this" in JavaScript?
### How the this keyword works

>Поведение ключевого слова this в JavaScript несколько отличается по сравнению с остальными языками. Имеются также различия при использовании this в строгом и нестрогом режиме.

![](https://github.com/Kamolzoda/Lecture-Object/raw/main/Снимок%20экрана%202023-03-28%20102123.png)

![](https://github.com/Kamolzoda/Lecture-Object/raw/main/Снимок%20экрана%202023-03-28%20102220.png)

>This НЕ переменная. Это ключевое слово. Вы не можете изменить значение этого

## What is new Date() in JavaScript?
### Data and Time
>Создаёт экземпляр объекта Date, представляющего собой момент времени. Объект Дата содержит число миллисекунд прошедших с 1 января 1970 г. UTC
### Data and Time
>new Date()
![](https://github.com/Kamolzoda/Lecture-Object/raw/main/Снимок%20экрана%202023-03-28%20102916.png)

>new Date(milliseconds)

>New Date(milliseconds) - количество миллисекунд, прошедших с 1 января 1970 года GMT+0. new Date(datestring) - Если единственный аргумент – строка, используется вызов Date.parse для чтения даты из неё.

![](https://github.com/Kamolzoda/Lecture-Object/raw/main/Снимок%20экрана%202023-03-28%20103441.png)

### Data and Time
>new Date(date string)
>
>Конструктор Date() создает объекты Date. При вызове в качестве функции она возвращает строку, представляющую текущее время.
![](https://github.com/Kamolzoda/Lecture-Object/raw/main/Снимок%20экрана%202023-03-28%20103934.png)

### Data and Time
>new Date(year,month,day,hours,minutes,seconds,milliseconds)

>new Date(..month) создает новый объект даты с указанной датой и временем.Например

![](https://github.com/Kamolzoda/Lecture-Object/raw/main/Снимок%20экрана%202023-03-28%20104942.png)

### Data and Time 
![](https://github.com/Kamolzoda/Lecture-Object/raw/main/Снимок%20экрана%202023-03-28%20105133.png)

### Data and Time 
>now()
![](https://github.com/Kamolzoda/Lecture-Object/raw/main/Снимок%20экрана%202023-03-28%20110047.png)

>getFullYear()
![](https://github.com/Kamolzoda/Lecture-Object/raw/main/Снимок%20экрана%202023-03-28%20105657.png)

>getMonth()
![](https://github.com/Kamolzoda/Lecture-Object/raw/main/Снимок%20экрана%202023-03-28%20110300.png)

>getDate()
![](https://github.com/Kamolzoda/Lecture-Object/raw/main/Снимок%20экрана%202023-03-28%20110749.png)

>getDay()
![](https://github.com/Kamolzoda/Lecture-Object/raw/main/Снимок%20экрана%202023-03-28%20111031.png)

>getHours()
![](https://github.com/Kamolzoda/Lecture-Object/raw/main/Снимок%20экрана%202023-03-28%20110853.png)

>getMinutes()
![](https://github.com/Kamolzoda/Lecture-Object/raw/main/Снимок%20экрана%202023-03-28%20111345.png)

>setDate()
![](https://github.com/Kamolzoda/Lecture-Object/raw/main/Снимок%20экрана%202023-03-28%20111831.png)

>setMonth()
![](https://github.com/Kamolzoda/Lecture-Object/raw/main/Снимок%20экрана%202023-03-28%20112229.png)

>setFullYear()
![](https://github.com/Kamolzoda/Lecture-Object/raw/main/Снимок%20экрана%202023-03-28%20112533.png)