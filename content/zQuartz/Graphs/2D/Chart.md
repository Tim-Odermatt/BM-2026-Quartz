# Chart

Chart creates different types of charts it takes in an array of data and in the att you need to set chartStyle which can be:
* bar
* fit
* line
* pie
* points
* radar
* spline

## Bar

````yaml
```graph
bounds: [-10, 10, 10, -10]
elements: [
    {type: chart, def: [1,2,3,4], att: {chartStyle: bar}}
]
```
````

```graph
bounds: [-10, 10, 10, -10]
elements: [
    {type: chart, def: [1,2,3,4], att: {chartStyle: bar}}
]
```

## Fit

````yaml
```graph
bounds: [-10,  10,  10,  -10]
elements: [
    {type: chart, def: [1,2,3,4], att: {chartStyle: fit}}
]
```
````

```graph
bounds: [-10,  10,  10,  -10]
elements: [
    {type: chart, def: [1,2,3,4], att: {chartStyle: fit}}
]
```

## Line

````yaml
```graph
bounds: [-10, 10, 10, -10]
elements: [
    {type: chart, def: [1,2,3,4], att: {chartStyle: line}}
]
```
````

```graph
bounds: [-10, 10, 10, -10]
elements: [
    {type: chart, def: [1,2,3,4], att: {chartStyle: line}}
]
```

## Pie

````yaml
```graph
bounds: [-10,10,10,-10]
elements: [
    {type: chart, def: [1,2,3,4], att: {chartStyle: pie}}
]
```
````

```graph
bounds: [-10,10,10,-10]
elements: [
    {type: chart, def: [1,2,3,4], att: {chartStyle: pie}}
]
```

## Radar

Radar needs a paramArray.

````yaml
```graph
bounds: [-10, 10, 10, -10]
elements: [
    {type: chart, def: [[1,2,3], [4,3,2], [-5,-6,0], [-1,5,1]], att: {chartStyle: radar, paramArray: [x, y, z]}}
]
```
````

```graph
bounds: [-10, 10, 10, -10]
elements: [
    {type: chart, def: [[1,2,3], [4,3,2], [-5,-6,0], [-1,5,1]], att: {chartStyle: radar, paramArray: [x, y, z]}}
]
```

## Spline

Takes an array of x coordinates and an array of y coordinates

````yaml
```graph
bounds: [-10, 10, 10, -10]
elements: [
    {type: chart, def: [[1,2,3], [4,3,2]], att: {chartStyle: spline}}
]
```
````

```graph
bounds: [-10, 10, 10, -10]
elements: [
    {type: chart, def: [[1,2,3], [4,3,2]], att: {chartStyle: spline}}
]
```