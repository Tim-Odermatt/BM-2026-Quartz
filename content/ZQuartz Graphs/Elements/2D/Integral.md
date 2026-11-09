# Integral

Creates an integral of an existing function on the graph. Takes in an array for the min and max range of the integral and then the element that contains the function graph `[[-2.0, 2.0], e0]`.

````yaml
```graph
bounds: [-10, 10, 10, -10]
elements: [
    {type: functiongraph, def: [f:2*x]},
    {type: integral, def: [[-2,2], e0]}
]
```
````

```graph
bounds: [-10, 10, 10, -10]
elements: [
    {type: functiongraph, def: [f:2*x]},
    {type: integral, def: [[0,2], e0]}
]
```

![integral](Integral-graph-1.png)

