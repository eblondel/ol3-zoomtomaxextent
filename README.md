# OpenLayers 3 Zoom to Max Extent

ZoomToMaxExtent control for an [OL3](https://github.com/openlayers/ol3) map.

This module has been initially developed for the needs of the OpenFIGIS [FigisMap](https://github.com/openfigis/FigisMap) project used as web-mapping framework in the FAO Fisheries & Aquaculture [website](http://www.fao.org/fishery/en), principally through the Fisheries Global Information System (FIGIS).

## Status

The plugin has been **successfully tested** and, for information, it is used in production in [FIGIS](http://www.fao.org/fishery/topic/18042/en).

For users/developers interested in contributing, contributions, bug reporting and/or fixing are more than welcome! If you have questions or suggestions, please do not hesitate to [contact me](mailto:emmanuel.blondel1@gmail.com)

## Examples

The examples demonstrate usage and can be viewed online thanks to [RawGit](http://rawgit.com/):

* [Basic usage](http://rawgit.com/eblondel/ol3-zoomtomaxextent/master/examples/zoomtomaxextent-default.html)
   * Create a map instance with a basic ZoomToMaxExtent control
   
## API

### `new ol.control.ZoomToMaxExtent(opt_options)`

OpenLayers 3 Loading Panel.

See [the examples](./examples) for usage.

#### Parameters:

The ``ol.control.ZoomToMaxExtent`` accepts a single ``opt_options`` parameter (of type ``Object``) that extends ``olx.control.ControlOptions``, and accepts the following properties:

|Name|Type|Description|
|:---|:---|:----------|
|`className`|`String`| control CSS class name. Default value is ``ol-zoom-max-extent``|
|`label`|`String`| Label displayed as control button. Default value is world extent image html markup that will displays as button|
|`tipLabel`|`String`| Tip label displayed on mouse over the control button. Default value is ``Fit to extent``|
|`extent`|`Array`| Max extent to use for the control|
|`zoom`|`Integer`| Zoom level to use for the control|

#### Extends

`ol.control.Control`

#### Methods

##### `setExtent(extent)`

Set the max extent

##### `getExtent()`

Get the max extent

##### `setZoom(zoom)`

Set the zoom level

##### `getZoom()`

Get the zoom level

###### Parameters:

|Name|Type|Description|
|:---|:---|:----------|
|`map`|`ol.Map`| The map instance. |

## License

MIT (c) 2015 Emmanuel Blondel

## Contributors


## Applications

* [FigisMap](https://github.com/openfigis/FigisMap) Javascript API for the Fisheries Global Information System (FIGIS)

## Sponsors

* UN FAO FI Department, as part of the [Fisheries Global Information System](http://www.fao.org/fishery/topic/18042/en) (FIGIS)
[![FIGIS](http://www.fao.org/figis/servlet/IRS?iid=17437)](http://www.fao.org/fishery/topic/18042/e)
