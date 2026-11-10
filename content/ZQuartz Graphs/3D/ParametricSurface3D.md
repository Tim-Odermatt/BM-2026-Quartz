# ParametricSurface3D

ParametricSurface3D creates a parametric surface on the 3D board which takes three function for the x, y, and z axes and then two arrays of length two the first being the range of u and the second being the range of v.  For example `[f:. f:. f:, [min, max], [min, max]]` in the functions use __x__ as u and __y__ as v.

````yaml
```graph
bounds: [-10, 10, 10, -10]
bounds3d: [[-5,5], [-5,5], [-5,5]]
axis: false
keepAspectRatio: true
elements: [
    {type: parametricsurface3d, def: [f:(2+cos(x))*cos(y), f:(2+cos(x))*sin(y), f:sin(x), [-5,f:2*PI], [-5,f:PI]]},
]
```
````

```graph
bounds: [-10, 10, 10, -10]
bounds3d: [[-5,5], [-5,5], [-5,5]]
axis: false
keepAspectRatio: true
elements: [
    {type: parametricsurface3d, def: [f:(2+cos(x))*cos(y), f:(2+cos(x))*sin(y), f:sin(x), [-5,f:2*PI], [-5,f:PI]]},
]
```