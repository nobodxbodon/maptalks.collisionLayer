# maptalks-collisionLayer

A marker collision plugin for [maptalks](http://maptalks.org/) and uses [rbush](https://github.com/mourner/rbush) library.

[demo](https://ageeye-cn.github.io/maptalks.collisionLayer/demo/index.html)

# Usage

```javascript
    var collisionLayer = new maptalks.CollisionLayer('layerName').addTo(map)
    collisionLayer.updateCollision()
```

# Options

Option | Type | Default
------ | ---- | -------
`activeId` | String | ```null```
`hidePointsSymbol` | Object | ```{'markerType': 'ellipse','markerFillOpacity': 0.3,'markerLineOpacity': 0.3,'markerWidth': 3,'markerHeight': 3,}```

# License

MIT License.






