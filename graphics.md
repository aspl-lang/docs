# graphics
## <sub>class</sub> graphics.Canvas
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Canvas.aspl:4:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Canvas.aspl:13:2
```aspl
method construct(int width, int height, any handle = null)
```
### <sub>method</sub> getInternalHandle
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Canvas.aspl:26:2

> getInternalHandle returns the internal handle of the canvas

```aspl
method getInternalHandle() returns any
```
### <sub>method</sub> getPixel
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Canvas.aspl:31:2
```aspl
method getPixel(int x, int y) returns Color
```
### <sub>method</sub> setPixel
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Canvas.aspl:37:2
```aspl
method setPixel(int x, int y, Color color, bool blend = true)
```
### <sub>method</sub> fill
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Canvas.aspl:42:2
```aspl
method fill(Color color, bool blend = true)
```
### <sub>method</sub> drawImage
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Canvas.aspl:47:2
```aspl
method drawImage(Canvas image, int x, int y, bool blend = true)
```
### <sub>method</sub> drawLine
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Canvas.aspl:52:2
```aspl
method drawLine(int x1, int y1, int x2, int y2, Color color, int thickness = 1, bool blend = true, bool antialias = true)
```
### <sub>method</sub> drawRectangle
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Canvas.aspl:57:2
```aspl
method drawRectangle(Rectangle rectangle, Color color, bool blend = true)
```
### <sub>method</sub> fillRectangle
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Canvas.aspl:62:2
```aspl
method fillRectangle(Rectangle rectangle, Color color, bool blend = true)
```
### <sub>method</sub> drawCircle
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Canvas.aspl:66:2
```aspl
method drawCircle(Ellipse circle, Color color, bool blend = true)
```
### <sub>method</sub> fillCircle
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Canvas.aspl:71:2
```aspl
method fillCircle(Ellipse circle, Color color, bool blend = true)
```
### <sub>method</sub> drawText
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Canvas.aspl:76:2
```aspl
method drawText(string text, int x, int y, Font font, Color color, HorizontalAlignment horizontalAlignment = HorizontalAlignment.Left, VerticalAlignment verticalAlignment = VerticalAlignment.Bottom, bool blend = true)
```
### <sub>method</sub> replaceColor
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Canvas.aspl:81:2
```aspl
method replaceColor(Color from, Color to, bool blend = true)
```
### <sub>method</sub> replaceColorIgnoreAlpha
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Canvas.aspl:87:2

> replaceColorIgnoreAlpha works like replaceColor, but checks only the R, G and B components and leaves the alpha value unchanged

```aspl
method replaceColorIgnoreAlpha(Color from, Color to)
```
### <sub>method</sub> blur
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Canvas.aspl:92:2
```aspl
method blur(int radius)
```
### <sub>method</sub> resize
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Canvas.aspl:97:2
```aspl
method resize(int width, int height)
```
### <sub>method</sub> resizeScale
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Canvas.aspl:107:2
```aspl
method resizeScale(float scale)
```
### <sub>method</sub> extendTo
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Canvas.aspl:117:2
```aspl
method extendTo(int width, int height)
```
### <sub>method</sub> getSubImage
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Canvas.aspl:127:2
```aspl
method getSubImage(int x, int y, int width, int height) returns Canvas
```
### <sub>method</sub> copy
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Canvas.aspl:132:2
```aspl
method copy() returns Canvas
```
### <sub>method</sub> save
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Canvas.aspl:137:2
```aspl
method save(string path)
```
### <sub>method</sub> fromFile
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Canvas.aspl:143:2
```aspl
method fromFile(string file) returns Canvas
```
### <sub>method</sub> fromFileData
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Canvas.aspl:150:2
```aspl
method fromFileData(list<byte> bytes) returns Canvas
```
### <sub>method</sub> fromData
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Canvas.aspl:157:2
```aspl
method fromData(list<byte> bytes, int width, int height, int channels) returns Canvas
```

## <sub>class</sub> graphics.Color
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Color.aspl:4:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Color.aspl:17:2
```aspl
method construct(byte a, byte r, byte g, byte b)
```
### <sub>method</sub> fromRGBA
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Color.aspl:26:2
```aspl
method fromRGBA(byte r, byte g, byte b, byte a) returns self
```
### <sub>method</sub> fromRGB
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Color.aspl:32:2
```aspl
method fromRGB(byte r, byte g, byte b) returns self
```
### <sub>method</sub> fromARGB
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Color.aspl:38:2
```aspl
method fromARGB(byte a, byte r, byte g, byte b) returns self
```
### <sub>method</sub> toString
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Color.aspl:43:2
```aspl
method toString() returns string
```
### <sub>method</sub> random
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Color.aspl:49:2
```aspl
method random() returns Color
```

## <sub>class</sub> graphics.Font
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Font.aspl:4:1
### <sub>property</sub> default
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Font.aspl:11:5
```aspl
property Font default
```
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Font.aspl:40:2
```aspl
method construct(string name, string path, string regularPath, int size, bool bold = false, bool italic = false, bool underline = false, bool strikeout = false)
```
### <sub>method</sub> withSize
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Font.aspl:52:2
```aspl
method withSize(int size) returns Font
```
### <sub>method</sub> asBold
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Font.aspl:57:2
```aspl
method asBold(bool value = true) returns Font
```
### <sub>method</sub> asItalic
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Font.aspl:62:2
```aspl
method asItalic(bool value = true) returns Font
```
### <sub>method</sub> asUnderlined
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Font.aspl:67:2
```aspl
method asUnderlined(bool value = true) returns Font
```
### <sub>method</sub> asStrikedout
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Font.aspl:72:2
```aspl
method asStrikedout(bool value = true) returns Font
```

## <sub>class</sub> graphics.ICanvas
Source: /home/runner/work/aspl/aspl/stdlib/graphics/ICanvas.aspl:5:1
### <sub>method</sub> getPixel
Source: /home/runner/work/aspl/aspl/stdlib/graphics/ICanvas.aspl:14:5
```aspl
method getPixel(int x, int y) returns Color
```
### <sub>method</sub> setPixel
Source: /home/runner/work/aspl/aspl/stdlib/graphics/ICanvas.aspl:18:5
```aspl
method setPixel(int x, int y, Color color, bool blend = true)
```
### <sub>method</sub> fill
Source: /home/runner/work/aspl/aspl/stdlib/graphics/ICanvas.aspl:22:5
```aspl
method fill(Color color, bool blend = true)
```
### <sub>method</sub> drawImage
Source: /home/runner/work/aspl/aspl/stdlib/graphics/ICanvas.aspl:26:5
```aspl
method drawImage(Canvas image, int x, int y, bool blend = true)
```
### <sub>method</sub> drawLine
Source: /home/runner/work/aspl/aspl/stdlib/graphics/ICanvas.aspl:30:2
```aspl
method drawLine(int x1, int y1, int x2, int y2, Color color, int thickness = 1, bool blend = true, bool antialias = true)
```
### <sub>method</sub> drawRectangle
Source: /home/runner/work/aspl/aspl/stdlib/graphics/ICanvas.aspl:34:2
```aspl
method drawRectangle(Rectangle rectangle, Color color, bool blend = true)
```
### <sub>method</sub> fillRectangle
Source: /home/runner/work/aspl/aspl/stdlib/graphics/ICanvas.aspl:38:2
```aspl
method fillRectangle(Rectangle rectangle, Color color, bool blend = true)
```
### <sub>method</sub> drawCircle
Source: /home/runner/work/aspl/aspl/stdlib/graphics/ICanvas.aspl:42:2
```aspl
method drawCircle(Ellipse circle, Color color, bool blend = true)
```
### <sub>method</sub> fillCircle
Source: /home/runner/work/aspl/aspl/stdlib/graphics/ICanvas.aspl:46:2
```aspl
method fillCircle(Ellipse circle, Color color, bool blend = true)
```
### <sub>method</sub> drawText
Source: /home/runner/work/aspl/aspl/stdlib/graphics/ICanvas.aspl:50:2
```aspl
method drawText(string text, int x, int y, Font font, Color color, HorizontalAlignment horizontalAlignment = HorizontalAlignment.Left, VerticalAlignment verticalAlignment = VerticalAlignment.Bottom, bool blend = true)
```
### <sub>method</sub> replaceColor
Source: /home/runner/work/aspl/aspl/stdlib/graphics/ICanvas.aspl:54:2
```aspl
method replaceColor(Color from, Color to, bool blend = true)
```
### <sub>method</sub> replaceColorIgnoreAlpha
Source: /home/runner/work/aspl/aspl/stdlib/graphics/ICanvas.aspl:59:2

> replaceColorIgnoreAlpha works like replaceColor, but checks only the R, G and B components and leaves the alpha value unchanged

```aspl
method replaceColorIgnoreAlpha(Color from, Color to)
```
### <sub>method</sub> blur
Source: /home/runner/work/aspl/aspl/stdlib/graphics/ICanvas.aspl:63:2
```aspl
method blur(int radius)
```
### <sub>method</sub> resize
Source: /home/runner/work/aspl/aspl/stdlib/graphics/ICanvas.aspl:67:2
```aspl
method resize(int width, int height)
```
### <sub>method</sub> resizeScale
Source: /home/runner/work/aspl/aspl/stdlib/graphics/ICanvas.aspl:71:2
```aspl
method resizeScale(float scale)
```
### <sub>method</sub> extendTo
Source: /home/runner/work/aspl/aspl/stdlib/graphics/ICanvas.aspl:75:2
```aspl
method extendTo(int width, int height)
```
### <sub>method</sub> getSubImage
Source: /home/runner/work/aspl/aspl/stdlib/graphics/ICanvas.aspl:79:2
```aspl
method getSubImage(int x, int y, int width, int height) returns Canvas
```
### <sub>method</sub> copy
Source: /home/runner/work/aspl/aspl/stdlib/graphics/ICanvas.aspl:83:2
```aspl
method copy() returns Canvas
```
### <sub>method</sub> save
Source: /home/runner/work/aspl/aspl/stdlib/graphics/ICanvas.aspl:87:2
```aspl
method save(string path)
```

## <sub>class</sub> graphics.LazyChunkedCanvas
Source: /home/runner/work/aspl/aspl/stdlib/graphics/LazyChunkedCanvas.aspl:4:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/graphics/LazyChunkedCanvas.aspl:23:2
```aspl
method construct(int width, int height, string directory, any handle = null)
```
### <sub>method</sub> getPixel
Source: /home/runner/work/aspl/aspl/stdlib/graphics/LazyChunkedCanvas.aspl:35:2
```aspl
method getPixel(int x, int y) returns Color
```
### <sub>method</sub> setPixel
Source: /home/runner/work/aspl/aspl/stdlib/graphics/LazyChunkedCanvas.aspl:41:2
```aspl
method setPixel(int x, int y, Color color, bool blend = true)
```
### <sub>method</sub> fill
Source: /home/runner/work/aspl/aspl/stdlib/graphics/LazyChunkedCanvas.aspl:46:2
```aspl
method fill(Color color, bool blend = true)
```
### <sub>method</sub> drawImage
Source: /home/runner/work/aspl/aspl/stdlib/graphics/LazyChunkedCanvas.aspl:51:2
```aspl
method drawImage(Canvas image, int x, int y, bool blend = true)
```
### <sub>method</sub> drawLine
Source: /home/runner/work/aspl/aspl/stdlib/graphics/LazyChunkedCanvas.aspl:56:2
```aspl
method drawLine(int x1, int y1, int x2, int y2, Color color, int thickness = 1, bool blend = true, bool antialias = true)
```
### <sub>method</sub> drawRectangle
Source: /home/runner/work/aspl/aspl/stdlib/graphics/LazyChunkedCanvas.aspl:61:2
```aspl
method drawRectangle(Rectangle rectangle, Color color, bool blend = true)
```
### <sub>method</sub> fillRectangle
Source: /home/runner/work/aspl/aspl/stdlib/graphics/LazyChunkedCanvas.aspl:66:2
```aspl
method fillRectangle(Rectangle rectangle, Color color, bool blend = true)
```
### <sub>method</sub> drawCircle
Source: /home/runner/work/aspl/aspl/stdlib/graphics/LazyChunkedCanvas.aspl:71:2
```aspl
method drawCircle(Ellipse circle, Color color, bool blend = true)
```
### <sub>method</sub> fillCircle
Source: /home/runner/work/aspl/aspl/stdlib/graphics/LazyChunkedCanvas.aspl:76:2
```aspl
method fillCircle(Ellipse circle, Color color, bool blend = true)
```
### <sub>method</sub> drawText
Source: /home/runner/work/aspl/aspl/stdlib/graphics/LazyChunkedCanvas.aspl:81:2
```aspl
method drawText(string text, int x, int y, Font font, Color color, HorizontalAlignment horizontalAlignment = HorizontalAlignment.Left, VerticalAlignment verticalAlignment = VerticalAlignment.Bottom, bool blend = true)
```
### <sub>method</sub> replaceColor
Source: /home/runner/work/aspl/aspl/stdlib/graphics/LazyChunkedCanvas.aspl:86:2
```aspl
method replaceColor(Color from, Color to, bool blend = true)
```
### <sub>method</sub> replaceColorIgnoreAlpha
Source: /home/runner/work/aspl/aspl/stdlib/graphics/LazyChunkedCanvas.aspl:92:2

> replaceColorIgnoreAlpha works like replaceColor, but checks only the R, G and B components and leaves the alpha value unchanged

```aspl
method replaceColorIgnoreAlpha(Color from, Color to)
```
### <sub>method</sub> blur
Source: /home/runner/work/aspl/aspl/stdlib/graphics/LazyChunkedCanvas.aspl:97:2
```aspl
method blur(int radius)
```
### <sub>method</sub> resize
Source: /home/runner/work/aspl/aspl/stdlib/graphics/LazyChunkedCanvas.aspl:102:2
```aspl
method resize(int width, int height)
```
### <sub>method</sub> resizeScale
Source: /home/runner/work/aspl/aspl/stdlib/graphics/LazyChunkedCanvas.aspl:109:2
```aspl
method resizeScale(float scale)
```
### <sub>method</sub> extendTo
Source: /home/runner/work/aspl/aspl/stdlib/graphics/LazyChunkedCanvas.aspl:116:2
```aspl
method extendTo(int width, int height)
```
### <sub>method</sub> getSubImage
Source: /home/runner/work/aspl/aspl/stdlib/graphics/LazyChunkedCanvas.aspl:123:2
```aspl
method getSubImage(int x, int y, int width, int height) returns Canvas
```
### <sub>method</sub> copy
Source: /home/runner/work/aspl/aspl/stdlib/graphics/LazyChunkedCanvas.aspl:128:2
```aspl
method copy() returns LazyChunkedCanvas
```
### <sub>method</sub> requireArea
Source: /home/runner/work/aspl/aspl/stdlib/graphics/LazyChunkedCanvas.aspl:133:2
```aspl
method requireArea(int x, int y, int width, int height)
```
### <sub>method</sub> isChunkLoaded
Source: /home/runner/work/aspl/aspl/stdlib/graphics/LazyChunkedCanvas.aspl:138:2
```aspl
method isChunkLoaded(int x, int y) returns bool
```
### <sub>method</sub> loadChunk
Source: /home/runner/work/aspl/aspl/stdlib/graphics/LazyChunkedCanvas.aspl:143:2
```aspl
method loadChunk(int x, int y)
```
### <sub>method</sub> unloadChunk
Source: /home/runner/work/aspl/aspl/stdlib/graphics/LazyChunkedCanvas.aspl:148:2
```aspl
method unloadChunk(int x, int y)
```
### <sub>method</sub> save
Source: /home/runner/work/aspl/aspl/stdlib/graphics/LazyChunkedCanvas.aspl:153:2
```aspl
method save(string path)
```
### <sub>method</sub> fromFile
Source: /home/runner/work/aspl/aspl/stdlib/graphics/LazyChunkedCanvas.aspl:159:2
```aspl
method fromFile(string file, string directory) returns LazyChunkedCanvas
```

## <sub>class</sub> graphics.PrimitiveChunkedCanvas
Source: /home/runner/work/aspl/aspl/stdlib/graphics/PrimitiveChunkedCanvas.aspl:4:1
### <sub>property</sub> width
Source: /home/runner/work/aspl/aspl/stdlib/graphics/PrimitiveChunkedCanvas.aspl:8:2
```aspl
property int width
```
### <sub>property</sub> height
Source: /home/runner/work/aspl/aspl/stdlib/graphics/PrimitiveChunkedCanvas.aspl:10:2
```aspl
property int height
```
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/graphics/PrimitiveChunkedCanvas.aspl:21:2
```aspl
method construct(int width, int height, any handle = null)
```
### <sub>method</sub> getPixel
Source: /home/runner/work/aspl/aspl/stdlib/graphics/PrimitiveChunkedCanvas.aspl:32:2
```aspl
method getPixel(int x, int y) returns Color
```
### <sub>method</sub> setPixel
Source: /home/runner/work/aspl/aspl/stdlib/graphics/PrimitiveChunkedCanvas.aspl:38:2
```aspl
method setPixel(int x, int y, Color color, bool blend = true)
```
### <sub>method</sub> fill
Source: /home/runner/work/aspl/aspl/stdlib/graphics/PrimitiveChunkedCanvas.aspl:43:2
```aspl
method fill(Color color, bool blend = true)
```
### <sub>method</sub> drawImage
Source: /home/runner/work/aspl/aspl/stdlib/graphics/PrimitiveChunkedCanvas.aspl:48:2
```aspl
method drawImage(Canvas image, int x, int y, bool blend = true)
```
### <sub>method</sub> drawLine
Source: /home/runner/work/aspl/aspl/stdlib/graphics/PrimitiveChunkedCanvas.aspl:53:2
```aspl
method drawLine(int x1, int y1, int x2, int y2, Color color, int thickness = 1, bool blend = true, bool antialias = true)
```
### <sub>method</sub> drawRectangle
Source: /home/runner/work/aspl/aspl/stdlib/graphics/PrimitiveChunkedCanvas.aspl:58:2
```aspl
method drawRectangle(Rectangle rectangle, Color color, bool blend = true)
```
### <sub>method</sub> fillRectangle
Source: /home/runner/work/aspl/aspl/stdlib/graphics/PrimitiveChunkedCanvas.aspl:63:2
```aspl
method fillRectangle(Rectangle rectangle, Color color, bool blend = true)
```
### <sub>method</sub> drawCircle
Source: /home/runner/work/aspl/aspl/stdlib/graphics/PrimitiveChunkedCanvas.aspl:68:2
```aspl
method drawCircle(Ellipse circle, Color color, bool blend = true)
```
### <sub>method</sub> fillCircle
Source: /home/runner/work/aspl/aspl/stdlib/graphics/PrimitiveChunkedCanvas.aspl:73:2
```aspl
method fillCircle(Ellipse circle, Color color, bool blend = true)
```
### <sub>method</sub> drawText
Source: /home/runner/work/aspl/aspl/stdlib/graphics/PrimitiveChunkedCanvas.aspl:78:2
```aspl
method drawText(string text, int x, int y, Font font, Color color, HorizontalAlignment horizontalAlignment = HorizontalAlignment.Left, VerticalAlignment verticalAlignment = VerticalAlignment.Bottom, bool blend = true)
```
### <sub>method</sub> replaceColor
Source: /home/runner/work/aspl/aspl/stdlib/graphics/PrimitiveChunkedCanvas.aspl:83:2
```aspl
method replaceColor(Color from, Color to, bool blend = true)
```
### <sub>method</sub> replaceColorIgnoreAlpha
Source: /home/runner/work/aspl/aspl/stdlib/graphics/PrimitiveChunkedCanvas.aspl:89:2

> replaceColorIgnoreAlpha works like replaceColor, but checks only the R, G and B components and leaves the alpha value unchanged

```aspl
method replaceColorIgnoreAlpha(Color from, Color to)
```
### <sub>method</sub> blur
Source: /home/runner/work/aspl/aspl/stdlib/graphics/PrimitiveChunkedCanvas.aspl:94:2
```aspl
method blur(int radius)
```
### <sub>method</sub> resize
Source: /home/runner/work/aspl/aspl/stdlib/graphics/PrimitiveChunkedCanvas.aspl:99:2
```aspl
method resize(int width, int height)
```
### <sub>method</sub> resizeScale
Source: /home/runner/work/aspl/aspl/stdlib/graphics/PrimitiveChunkedCanvas.aspl:106:2
```aspl
method resizeScale(float scale)
```
### <sub>method</sub> extendTo
Source: /home/runner/work/aspl/aspl/stdlib/graphics/PrimitiveChunkedCanvas.aspl:113:2
```aspl
method extendTo(int width, int height)
```
### <sub>method</sub> getSubImage
Source: /home/runner/work/aspl/aspl/stdlib/graphics/PrimitiveChunkedCanvas.aspl:120:2
```aspl
method getSubImage(int x, int y, int width, int height) returns Canvas
```
### <sub>method</sub> copy
Source: /home/runner/work/aspl/aspl/stdlib/graphics/PrimitiveChunkedCanvas.aspl:125:2
```aspl
method copy() returns PrimitiveChunkedCanvas
```
### <sub>method</sub> save
Source: /home/runner/work/aspl/aspl/stdlib/graphics/PrimitiveChunkedCanvas.aspl:130:2
```aspl
method save(string path)
```
### <sub>method</sub> convertToLazy
Source: /home/runner/work/aspl/aspl/stdlib/graphics/PrimitiveChunkedCanvas.aspl:135:2
```aspl
method convertToLazy(string file, string directory)
```
### <sub>method</sub> fromFile
Source: /home/runner/work/aspl/aspl/stdlib/graphics/PrimitiveChunkedCanvas.aspl:141:2
```aspl
method fromFile(string file) returns PrimitiveChunkedCanvas
```
### <sub>method</sub> fromFileData
Source: /home/runner/work/aspl/aspl/stdlib/graphics/PrimitiveChunkedCanvas.aspl:148:2
```aspl
method fromFileData(list<byte> bytes) returns PrimitiveChunkedCanvas
```

## <sub>class</sub> graphics.TouchPoint
Source: /home/runner/work/aspl/aspl/stdlib/graphics/TouchPoint.aspl:4:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/graphics/TouchPoint.aspl:16:5
```aspl
method construct(long identifier, Point position, TouchToolType toolType, bool changed)
```

## <sub>class</sub> graphics.Window
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Window.aspl:4:1
### <sub>property</sub> title
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Window.aspl:9:2
```aspl
property string title
```
### <sub>property</sub> fps
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Window.aspl:24:2
```aspl
property int fps
```
### <sub>property</sub> onLoad
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Window.aspl:31:2
```aspl
property callback onLoad
```
### <sub>property</sub> onPaint
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Window.aspl:33:2
```aspl
property callback<Canvas> onPaint
```
### <sub>property</sub> onResize
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Window.aspl:35:2
```aspl
property callback<int, int> onResize
```
### <sub>property</sub> onKeyPress
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Window.aspl:37:2
```aspl
property callback<KeyCode> onKeyPress
```
### <sub>property</sub> onKeyDown
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Window.aspl:39:2
```aspl
property callback<KeyCode> onKeyDown
```
### <sub>property</sub> onKeyUp
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Window.aspl:41:2
```aspl
property callback<KeyCode> onKeyUp
```
### <sub>property</sub> onMouseClick
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Window.aspl:43:2
```aspl
property callback<Point, MouseButton> onMouseClick
```
### <sub>property</sub> onMouseDown
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Window.aspl:45:2
```aspl
property callback<Point, MouseButton> onMouseDown
```
### <sub>property</sub> onMouseUp
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Window.aspl:47:2
```aspl
property callback<Point, MouseButton> onMouseUp
```
### <sub>property</sub> onMouseMove
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Window.aspl:49:2
```aspl
property callback<Point, float, float> onMouseMove
```
### <sub>property</sub> onMouseWheel
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Window.aspl:51:2
```aspl
property callback<Point, float, float> onMouseWheel
```
### <sub>property</sub> onTouchDown
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Window.aspl:53:2
```aspl
property callback<list<TouchPoint>> onTouchDown
```
### <sub>property</sub> onTouchMove
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Window.aspl:55:2
```aspl
property callback<list<TouchPoint>> onTouchMove
```
### <sub>property</sub> onTouchUp
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Window.aspl:57:2
```aspl
property callback<list<TouchPoint>> onTouchUp
```
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Window.aspl:60:2
```aspl
method construct(string|int title, int width, int? height = null)
```
### <sub>method</sub> show
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Window.aspl:134:2
```aspl
method show()
```
### <sub>method</sub> isFullscreen
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Window.aspl:139:2
```aspl
method isFullscreen() returns bool
```
### <sub>method</sub> toggleFullscreen
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Window.aspl:144:2
```aspl
method toggleFullscreen()
```
### <sub>method</sub> isMouseButtonDown
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Window.aspl:149:5
```aspl
method isMouseButtonDown(MouseButton button) returns bool
```
### <sub>method</sub> isKeyDown
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Window.aspl:154:2
```aspl
method isKeyDown(KeyCode key) returns bool
```

## <sub>enum</sub> graphics.HorizontalAlignment
Source: /home/runner/work/aspl/aspl/stdlib/graphics/HorizontalAlignment.aspl:2:1
```aspl

```

## <sub>enum</sub> graphics.KeyCode
Source: /home/runner/work/aspl/aspl/stdlib/graphics/KeyCode.aspl:2:1
```aspl

```

## <sub>enum</sub> graphics.MouseButton
Source: /home/runner/work/aspl/aspl/stdlib/graphics/MouseButton.aspl:2:1
```aspl

```

## <sub>enum</sub> graphics.TouchToolType
Source: /home/runner/work/aspl/aspl/stdlib/graphics/TouchToolType.aspl:2:1
```aspl

```

## <sub>enum</sub> graphics.VerticalAlignment
Source: /home/runner/work/aspl/aspl/stdlib/graphics/VerticalAlignment.aspl:2:1
```aspl

```

## <sub>function</sub> graphics.get_image_width_from_file
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Canvas.aspl:165:1
```aspl
function get_image_width_from_file(string file) returns int
```

## <sub>function</sub> graphics.get_image_height_from_file
Source: /home/runner/work/aspl/aspl/stdlib/graphics/Canvas.aspl:170:1
```aspl
function get_image_height_from_file(string file) returns int
```

## <sub>function</sub> graphics.measure_text_size
Source: /home/runner/work/aspl/aspl/stdlib/graphics/text.aspl:4:1
```aspl
function measure_text_size(string text, Font font) returns Size
```