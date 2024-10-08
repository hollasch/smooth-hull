This example illustrates a way to construct a loose bounding area around a set of points. The
general technique is to use `d3.polygonHull`, then offset each segment of the resulting polygon
outwards, and finally to bridge the gaps with circular arcs.

One could also envision using Bézier curves to get a blob with no straight segments.

See also [Smooth Polygon Convex Hull](http://bl.ocks.org/hollasch/9d3c098022f5524220bd84aae7623478).
