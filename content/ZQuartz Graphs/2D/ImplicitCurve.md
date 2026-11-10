# ImplicitCurve

Creates an implicit curve from an implicit equation with two independent variables (x,y). It takes a function as a parameter with x and y as the variables. `[f:]`.

````yaml
```graph
bounds: [-10, 10, 10, -10]
keepAspectRatio: true
elements: [
    {type: implicitcurve, def: [f:1/16*x**2+y**2-1]},
]
```
````

```graph
bounds: [-10, 10, 10, -10]
keepAspectRatio: true
elements: [
    {type: implicitcurve, def: [f:1/16*x**2+y**2-1]},
]
```