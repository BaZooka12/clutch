Написать функцию, которая принимает два аргумента: массив объектов и название свойства. Возвращает массив значений по этому свойству.

```
// example of object:
var listOfObjects = [
    {
        name: 'moisei',
        text: 'blabla'
    },
    {
        name: 'luka',
        text: 'alo'
    },
    {
        name: 'arhip',
        text: 'iuh'
    },
];
```

```
getValues(listOfObjects, 'text')
> ['blabla', 'alo', 'iuh']
```

```
getValues(listOfObjects, 'name')
> ['moisei', 'luka', 'arhip']
```
