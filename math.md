# math
## <sub>class</sub> math.geometry.Ellipse
Source: /home/runner/work/aspl/aspl/stdlib/math/geometry/Ellipse.aspl:4:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/math/geometry/Ellipse.aspl:12:5
```aspl
method construct(Point position, Size size)
```
### <sub>method</sub> containsPoint
Source: /home/runner/work/aspl/aspl/stdlib/math/geometry/Ellipse.aspl:18:5
```aspl
method containsPoint(Point point) returns bool
```

## <sub>class</sub> math.geometry.Point
Source: /home/runner/work/aspl/aspl/stdlib/math/geometry/Point.aspl:2:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/math/geometry/Point.aspl:10:5
```aspl
method construct(float x, float y)
```

## <sub>class</sub> math.geometry.Rectangle
Source: /home/runner/work/aspl/aspl/stdlib/math/geometry/Rectangle.aspl:4:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/math/geometry/Rectangle.aspl:12:2
```aspl
method construct(Point position, Size size)
```
### <sub>method</sub> containsPoint
Source: /home/runner/work/aspl/aspl/stdlib/math/geometry/Rectangle.aspl:18:5
```aspl
method containsPoint(Point point) returns bool
```

## <sub>class</sub> math.geometry.Size
Source: /home/runner/work/aspl/aspl/stdlib/math/geometry/Size.aspl:2:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/math/geometry/Size.aspl:10:2
```aspl
method construct(float width, float height)
```

## <sub>function</sub> math.abs
Source: /home/runner/work/aspl/aspl/stdlib/math/abs.aspl:2:1
```aspl
function abs(double x) returns double
```

## <sub>function</sub> math.radians
Source: /home/runner/work/aspl/aspl/stdlib/math/angular_units.aspl:2:1
```aspl
function radians(double degrees) returns double
```

## <sub>function</sub> math.degrees
Source: /home/runner/work/aspl/aspl/stdlib/math/angular_units.aspl:7:1
```aspl
function degrees(double radians) returns double
```

## <sub>function</sub> math.min
Source: /home/runner/work/aspl/aspl/stdlib/math/comparison.aspl:2:1
```aspl
function min(double a, double b) returns double
```

## <sub>function</sub> math.max
Source: /home/runner/work/aspl/aspl/stdlib/math/comparison.aspl:10:1
```aspl
function max(double a, double b) returns double
```

## <sub>function</sub> math.clamp
Source: /home/runner/work/aspl/aspl/stdlib/math/comparison.aspl:18:1
```aspl
function clamp(double value, double min, double max) returns double
```

## <sub>function</sub> math.pi
Source: /home/runner/work/aspl/aspl/stdlib/math/constants.aspl:2:1
```aspl
function pi() returns double
```

## <sub>function</sub> math.e
Source: /home/runner/work/aspl/aspl/stdlib/math/constants.aspl:7:1
```aspl
function e() returns double
```

## <sub>function</sub> math.pow
Source: /home/runner/work/aspl/aspl/stdlib/math/pow.aspl:2:1
```aspl
function pow(double base, double exponent) returns double
```

## <sub>function</sub> math.root
Source: /home/runner/work/aspl/aspl/stdlib/math/pow.aspl:7:1
```aspl
function root(double x, double n) returns double
```

## <sub>function</sub> math.sqrt
Source: /home/runner/work/aspl/aspl/stdlib/math/pow.aspl:12:1
```aspl
function sqrt(double x) returns double
```

## <sub>function</sub> math.floor
Source: /home/runner/work/aspl/aspl/stdlib/math/round.aspl:2:1
```aspl
function floor(double x) returns double
```

## <sub>function</sub> math.ceil
Source: /home/runner/work/aspl/aspl/stdlib/math/round.aspl:7:1
```aspl
function ceil(double x) returns double
```

## <sub>function</sub> math.round
Source: /home/runner/work/aspl/aspl/stdlib/math/round.aspl:12:1
```aspl
function round(double x, int d = 0) returns double
```

## <sub>function</sub> math.sin
Source: /home/runner/work/aspl/aspl/stdlib/math/trigonometry.aspl:2:1
```aspl
function sin(double x) returns double
```

## <sub>function</sub> math.asin
Source: /home/runner/work/aspl/aspl/stdlib/math/trigonometry.aspl:7:1
```aspl
function asin(double x) returns double
```

## <sub>function</sub> math.cos
Source: /home/runner/work/aspl/aspl/stdlib/math/trigonometry.aspl:12:1
```aspl
function cos(double x) returns double
```

## <sub>function</sub> math.acos
Source: /home/runner/work/aspl/aspl/stdlib/math/trigonometry.aspl:17:1
```aspl
function acos(double x) returns double
```

## <sub>function</sub> math.tan
Source: /home/runner/work/aspl/aspl/stdlib/math/trigonometry.aspl:22:1
```aspl
function tan(double x) returns double
```

## <sub>function</sub> math.atan
Source: /home/runner/work/aspl/aspl/stdlib/math/trigonometry.aspl:27:1
```aspl
function atan(double x) returns double
```