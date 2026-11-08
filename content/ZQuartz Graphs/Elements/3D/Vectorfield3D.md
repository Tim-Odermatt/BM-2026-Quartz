# Vectorfield3D

Vectorfield3D creates a vectorfield on the 3D board it takes an array of three functions for the x, y, and z axes and then takes three arrays of length three which describe the start value, number of steps, and the end value of the x, y, and z axes. For example `[[f:x, f:y, f:z], [xStart, xSteps, xEnd], [yStart, ySteps, yEnd], [zStart, zSteps, zEnd]]`. 

````yaml
```graph
bounds: [-10, 10, 10, -10]
bounds3d: [[-5,5], [-5,5], [-5,5]]
axis: false
keepAspectRatio: true
elements: [
    {type: vectorfield3d, def: [[f:sin(x),f:sin(y),f:sin(z)], [-5,5,5], [-5,5,5], [-5,5,5]]}
]
```
````


```graph
bounds: [-10, 10, 10, -10]
bounds3d: [[-5,5], [-5,5], [-5,5]]
axis: false
keepAspectRatio: true
elements: [
    {type: vectorfield3d, def: [[f:sin(x),f:sin(y),f:sin(z)], [-5,5,5], [-5,5,5], [-5,5,5]]}
]
```


![vectorfield3d](Vectorfield3D-graph-1.png)
