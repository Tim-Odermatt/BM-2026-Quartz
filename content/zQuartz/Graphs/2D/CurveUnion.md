# CurveUnion

Union of two closed path elements. Takes two elements for parameters. You will also want to put a `fillColor` in the `att` which takes a string of a hex code or color name.

````yaml
```graph
bounds: [-10, 10, 10, -10]
keepAspectRatio: true
elements: [
    {type: functiongraph, def: [f:cos(x)]},
    {type: inequality, def: [e0], att: {inverse:true, fillOpacity: 0.1}},
    {type: circle, def: [[0,0], 4]},
    {type: curveunion, def: [e1, e2], att: {fillColor: yellow, fillOpacity: 0.6}}
]
```
````

```graph
bounds: [-10, 10, 10, -10]
keepAspectRatio: true
elements: [
    {type: functiongraph, def: [f:cos(x)]},
    {type: inequality, def: [e0], att: {inverse:true, fillOpacity: 0.1}},
    {type: circle, def: [[0,0], 4]},
    {type: curveunion, def: [e1, e2], att: {fillColor: yellow, fillOpacity: 0.6}}
]
```