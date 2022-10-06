# skole

Method: https://bertt.wordpress.com/2022/02/20/cesium-3d-tiles-model-placement/

https://sandcastle.cesium.com/

Matrix:

```
var lon =  10.25035;
var lat = 59.686055;
var height = 78.5;
var location = Cesium.Cartesian3.fromDegrees(lon, lat, 0);
var t = Cesium.Transforms.eastNorthUpToFixedFrame(location);
const a = Cesium.Matrix4.transpose(t, new Cesium.Matrix4());
console.log(a);
```

