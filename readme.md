# polyhedra
[![NPM](https://nodei.co/npm/polyhedra.png)](https://nodei.co/npm/polyhedra/)

JSON format data from the [Virtual Polyhedra](http://www.georgehart.com/virtual-polyhedra/vp.html) by
George W. Hart. It was converted to JSON by
[Lee Stemkoski](http://stemkoski.github.io/Three.js/index.html). I am merely putting
in on npm.

## Example

```
 var polyhedra = require('polyhedra')
   // polyhedra has the attributes: antiprisms, archimedean, johnson, platonic, prisms
  console.log(polyhedra.platonic.cube)
  // Prints
  {
  "name":"Cube",
  "category":["Platonic Solid"],
  "vertex":[[0,0,1.224745],[1.154701,0,0.4082483],[-0.5773503,1,0.4082483],[-0.5773503,-1,0.4082483],[0.5773503,1,-0.4082483],[0.5773503,-1,-0.4082483],[-1.154701,0,-0.4082483],[0,0,-1.224745]],
  "edge":[[0,1],[0,2],[0,3],[1,4],[1,5],[2,4],[2,6],[3,5],[3,6],[4,7],[5,7],[6,7]],
  "face":[[0,1,4,2],[0,2,6,3],[0,3,5,1],[1,5,7,4],[2,4,7,6],[3,6,7,5]]}
  }
```

## License

The data from the polyhedra is from from the website "Virtual Polyhedra: The
Encyclopedia of Polyhedra" by George W. Hart. The original
copyright by Hart allows noncommercial use. See copyright.txt.
