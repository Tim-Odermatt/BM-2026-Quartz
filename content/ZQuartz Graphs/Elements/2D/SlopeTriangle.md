# SlopeTriangle

Creates slope triangle which displays the slope based on a point on a line. The parameter are a line and a glider which can be passed in through composing elements `[eLine, eGlider]`. You can also pass in a tangent as a parameter `[eTangent]`.

````yaml
```graph
bounds: [-10, 10, 10, -10]
elements: [
    {type: line, def: [[0,0], [2,5]]},
    {type: glider, def: [0, 0, e0]},
    {type: slopetriangle, def: [e0, e1]}
]
```
````

```graph
bounds: [-10, 10, 10, -10]
elements: [
    {type: line, def: [[0,0], [2,5]]},
    {type: glider, def: [0, 0, e0]},
    {type: slopetriangle, def: [e0, e1]}
]
```

![slopeTriangle1](SlopeTriangle-graph-1.png)

````yaml
```graph
bounds: [-10, 10, 10, -10]
elements: [
    {type: functiongraph, def: [f:sin(x)]},
    {type: glider, def: [0, 0, e0]},
    {type: tangent, def: [e1]},
    {type: slopetriangle, def: [e2]}
]
```
````

![slopeTriangle2](SlopeTriangle-graph-2.png)

