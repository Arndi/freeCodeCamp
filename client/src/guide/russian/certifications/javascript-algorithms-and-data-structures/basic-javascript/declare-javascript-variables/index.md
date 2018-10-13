---
title: Declare JavaScript Variables
localeTitle: Объявление переменных JavaScript
---
# Объявление переменных JavaScript

Когда мы храним данные в структуре данных, мы называем это переменной. Переменные JavaScript написаны на верблюжьем корпусе. Примером случая с верблюдом является: `camelCase` .

Вы можете объявить переменную таким образом

```js
    var myName = "Rafael"; 
```

ES6 представила два других способа объявления переменных. **let** и **const** . _Пусть_ довольно похоже на var и по большей части взаимозаменяемо:

```js
    let myAge = 36; 
```

Где _пусть_ отличается, находится в его объеме. Когда мы объявляем использование _var_ , оно является глобальным по объему. Когда мы объявляем использование _let_ , область действия ограничена этой функцией. Если вы хотите использовать переменную _let_ вне функции, вы должны сделать ее глобальной в области видимости или переопределить ее в следующей функции.

**const** , с другой стороны, может быть объявлен только один раз. Его ценность никогда не изменится.

```js
    const myName = "Christina"; 

```