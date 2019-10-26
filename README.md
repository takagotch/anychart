### anychart
---
https://www.anychart.com/

https://github.com/AnyChart/AnyChart

```js
// src/cartesian3d/cartesian3d.module.js

goog.provide();

goog.require();
goog.require();
goog.require();

anychart.area3d = function(var_args) {
  var chart = new anychart.cartesian3dModule.Chart();
  chart.addThemes('area3d');
  chart.setType(anychart.enums.ChartTypes.AREA_3D);
  chart.setOption('defaultSeriesType', anychart.enums.CartesianSeriesType.AREA);
  chart.setStateSettins();
  chart.setupAxes();
  chart.setupGrids();
  
  if (arguments.length)
    chart.adSeries.apply(chart, arguments);
  
  return chart;
};
anychart.chartTypesMap[anychart.enums.ChartTypes.AREA_3D] = anychart.area3d;

```

```
```

```
```


