# Functiongraph

Function creates an element based on a function that has the x as it parameter. The second parameter is a number that gives the start of the bounds and the third parameter is a number that gives the end of the bounds. `[f:, start, end]`

````yaml
```graph
bounds: [-10, 10, 10, -10]
elements: [
    {type: functiongraph, def: [f:sin(x)]}
]
```
````

![functiongraph](Functiongraph-graph-1.png)
