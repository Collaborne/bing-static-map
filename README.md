bing-static-map [![Bower version](https://badge.fury.io/bo/bing-static-map.svg)](http://badge.fury.io/bo/bing-static-map)
=========

`bing-static-map` is a web component to render a [static Bing Map](http://msdn.microsoft.com/en-us/library/ff701724.aspx). The web component is built with [Polymer 1.x](https://www.polymer-project.org).

![Screenshot](/doc/screenshot.png "Screenshot")


## Usage

`bower install bing-static-map`

```html
<bing-static-map
  width="500"
  height="300"
  pushpin-latitude="52.35952"
  pushpin-longitude="4.90348"
  map-area-north-east-latitude="52.3606441"
  map-area-north-east-longitude="4.9053208"
  map-area-south-west-latitude="52.3583958"
  map-area-south-west-longitude="4.9016393"
  key="YOUR-BING-KEY"
></bing-static-map>
```


## Properties & styles

These properties are available:

Property                          | Type    | Description
--------------------------------- | ------- | ----------------------------
**width**                         | Number  | Width of the image
**height**                        | Number  | Height of the image
**pushpin-latitude**              | Number  | Latitude of the pushpin
**pushpin-longitude**             | Number  | Longitude of the pushpin
**map-area-north-east-latitude**  | Number  | Latitude of the North East point of the map area
**map-area-north-east-longitude** | Number  | Longitude of the North East point of the map area
**map-area-south-west-latitude**  | Number  | Latitude of the South West point of the map area
**map-area-south-west-longitude** | Number  | Longitude of the South West point of the map area


## Continuous integration

[Travis-CI](https://travis-ci.org/Collaborne/bing-static-map) [![Travis state](https://travis-ci.org/Collaborne/bing-static-map.svg?branch=master)](https://travis-ci.org/Collaborne/bing-static-map)


## License

    This software is licensed under the Apache 2 license, quoted below.

    Copyright 2011-2015 Collaborne B.V. <http://github.com/Collaborne/>

    Licensed under the Apache License, Version 2.0 (the "License"); you may not
    use this file except in compliance with the License. You may obtain a copy of
    the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
    WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
    License for the specific language governing permissions and limitations under
    the License.
    