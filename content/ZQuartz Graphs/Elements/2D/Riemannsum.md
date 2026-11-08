# Riemannsum

Creates a riemannsum for a function that is given. The first parameter is a function, the second one is how many boxes to draw, the third one is a string of the type of riemannsum `[f:, #ofBoxes, type]`.

Types
* left
* right
* middle
* lower
* upper
* random
* simpson
* trapezoidal

````yaml
```graph
bounds: [-10, 10, 10, -10]
elements: [
    {type: riemannsum, def: [f:x, 10, upper]}
]
```
````

![riemannsum](Riemannsum-graph-1.png)

