# Inequality

Inequalities can be displayed by creating an element and passing it into the inequality element as a parameter. The default is less than or equal to. To make it greater than or equal to in `att` set `inverse: true`.

````yaml
```graph
bounds: [-10, 10, 10, -10]
elements: [
    {type: line, def: [[1,1], [0,0]]},
    {type: inequality, def: [e0]}
]
```
````

```graph
bounds: [-10, 10, 10, -10]
elements: [
    {type: line, def: [[1,1], [0,0]]},
    {type: inequality, def: [e0]}
]
```