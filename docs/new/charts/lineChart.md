# Line Chart

## Example

<iframe width="100%" height="400" src="//jsfiddle.net/YangWei/9g7zbk0h/embedded/result,js,html/" allowfullscreen="allowfullscreen" frameborder="0"></iframe>

## Props

* [**Cartesian Chart Props Mixin**](../cartesianChartPropsMixin)

Name | Type  | Default  | Description
--- | --- | ---- | ---
circleRadius | number | `3` |
hoverAnimation | bool | `true` |
margins | object | `{ top: 10, right: 20, bottom: 50, left: 45 }` |
data | any |  |
domain | object | { x: [], y: [] } | Specify minimum and maximum values for X and Y axis.  E.g., domain={y:[0,]} will fix the minimum chart Y value at zero instead of using `min(input Y values)`.
className |  | `'rd3-linechart'` |
xAxisClassName |  | `'rd3-linechart-xaxis'` |
yAxisClassName |  | `'rd3-linechart-yaxis'` |
