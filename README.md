## Get-vector-tile

Fetches a vector tile from a web endpoint, and returns its contents as GeoJSON. Based on @mapbox/vt2geojson. Does less, but in a more modern way.

Usage:

```js
import getVectorTile from 'get-vector-tile';
const features = getVectorTile({
    uri: 'https://example.com/tiles/{z}/{x}/{y}.pbf',
    layer: 'trees',
    z: 1
    x: 2,
    y: 3,
});
```
