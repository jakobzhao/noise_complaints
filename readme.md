# Practical Exercise 6: 3D Thematic Map using a Virtual Globe

> Winter 2017 | Geography 371 | Geovisualization: Web Mapping
>
> Instructor: Bo Zhao | TA: Andy Wilson | Location: 210 Wilkinson | Time: Thursday 2-3:50pm
>
> Assigned: 02/23/2017 | Due: `03/16/2017 @11:59pm` | Points Available = 50

This practical exercise will help you make a 3D thematic map using a virtual globe. 



数据来历。 

预处理： 距离。

geojson

review, 两个字段。

下载



有了数据，寻找color， 我们可以通过qgis 对数据进行classification, 颜色可以用默认的颜色，也可以用colorbrewer寻找。







重新选择，一个base imager provider

一个新的color ramp

更新字体？

上传到







#### Color.fromCssColorString(color)  [Color](http://cesiumjs.org/releases/b30/Build/Documentation/Color.html)

Creates a Color instance from a CSS color value.

| Name    | Type   | Description                              |
| ------- | ------ | ---------------------------------------- |
| `color` | String | The CSS color value in #rgb, #rrggbb, rgb(), rgba(), hsl(), or hsla() format. |

##### Returns:

The color object, or undefined if the string was not a valid CSS color.

## References

[1]. https://data.cityofnewyork.us/Social-Services/Noise-SRs-since-20151101/fqi4-uxkk

[2]. http://cesiumjs.org/releases/b30/Build/Documentation/Color.html