# Glider

Creates a glider which lives on another element and moves along its path. Takes a element as a parameter `[e0]`

````yaml
```graph
bounds: [-10, 10, 10, -10]
keepAspectRatio: true
elements: [
    {type: circle, def: [[0,2], 2]},
    {type: glider, def: [e0]}
]
```
````

![glider](Glider-graph-1.png)

