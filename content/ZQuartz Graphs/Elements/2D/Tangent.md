# Tangent

Creates a tangent line based on where a glider is on an element. Takes a glider as a parameter `[e]`.

````yaml
```graph
bounds: [-10, 10, 10, -10]
keepAspectRatio: true
elements: [
    {type: circle, def: [[0,2], 2]},
    {type: glider, def: [e0]},
    {type: tangent, def: [e1]}
]
```
````

![tangent](Tangent-graph-1.png)

