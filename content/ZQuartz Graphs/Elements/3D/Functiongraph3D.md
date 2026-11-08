# Functiongraph3D

Functiongraph3D creates a function on the 3D board it takes a function as the first parameter and then an array for the range of X and then an array for the range of Y. For example `[f:, [xMin, xMax], [yMin, yMax]]` can use both x and y as variables in the function.

````yaml
```graph
bounds: [-10, 10, 10, -10]
bounds3d: [[-5,5], [-5,5], [-5,5]]
axis: false
keepAspectRatio: true
elements: [
    {type: functiongraph3d, def: [f:sin(x*y/4), [-5,5], [-5,5]]}
]
```
````

```graph
bounds: [-10, 10, 10, -10]
bounds3d: [[-5,5], [-5,5], [-5,5]]
axis: false
keepAspectRatio: true
elements: [
    {type: functiongraph3d, def: [f:sin(x*y/4), [-5,5], [-5,5]]}
]
```