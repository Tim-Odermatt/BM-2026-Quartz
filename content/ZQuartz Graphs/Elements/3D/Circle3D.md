# Circle3D

Circle3D creates a circle on the 3D graph which takes an point 3D for the center `[x,y,z]` then it takes an array with three numbers for the normal `[num, num, num]` lastly it takes a number for the radius of the circle

````yaml
```graph
bounds: [-10, 10, 10, -10]
bounds3d: [[-5,5], [-5,5], [-5,5]]
axis: false
keepAspectRatio: true
elements: [
    {type: circle3d, def: [[1,1,1], [1,1,1], 3]}
]
```
````


```graph
bounds: [-10, 10, 10, -10]
bounds3d: [[-5,5], [-5,5], [-5,5]]
axis: false
keepAspectRatio: true
elements: [
    {type: circle3d, def: [[1,1,1], [1,1,1], 3]}
]
```


![circle3d](Circle3D-graph-1.png)
