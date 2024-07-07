# gui
## <sub>class</sub> gui.Control
Source: /home/runner/work/aspl/aspl/stdlib/gui/Control.aspl:6:1
### <sub>property</sub> position
Source: /home/runner/work/aspl/aspl/stdlib/gui/Control.aspl:9:2
```aspl
property Point position
```
### <sub>property</sub> hasFocus
Source: /home/runner/work/aspl/aspl/stdlib/gui/Control.aspl:12:2
```aspl
property bool hasFocus
```
### <sub>property</sub> onGainFocus
Source: /home/runner/work/aspl/aspl/stdlib/gui/Control.aspl:28:2
```aspl
property callback onGainFocus
```
### <sub>property</sub> onLoseFocus
Source: /home/runner/work/aspl/aspl/stdlib/gui/Control.aspl:30:2
```aspl
property callback onLoseFocus
```
### <sub>method</sub> onLoad
Source: /home/runner/work/aspl/aspl/stdlib/gui/Control.aspl:33:2
```aspl
method onLoad()
```
### <sub>method</sub> onResize
Source: /home/runner/work/aspl/aspl/stdlib/gui/Control.aspl:35:2
```aspl
method onResize(int width, int height)
```
### <sub>method</sub> onKeyPress
Source: /home/runner/work/aspl/aspl/stdlib/gui/Control.aspl:37:2
```aspl
method onKeyPress(KeyCode key)
```
### <sub>method</sub> onKeyDown
Source: /home/runner/work/aspl/aspl/stdlib/gui/Control.aspl:39:2
```aspl
method onKeyDown(KeyCode key, bool isShiftDown)
```
### <sub>method</sub> onKeyUp
Source: /home/runner/work/aspl/aspl/stdlib/gui/Control.aspl:41:2
```aspl
method onKeyUp(KeyCode key)
```
### <sub>method</sub> onMouseClick
Source: /home/runner/work/aspl/aspl/stdlib/gui/Control.aspl:43:2
```aspl
method onMouseClick(Point position, MouseButton button)
```
### <sub>method</sub> onMouseClickAny
Source: /home/runner/work/aspl/aspl/stdlib/gui/Control.aspl:45:2
```aspl
method onMouseClickAny(Point position, MouseButton button) returns bool
```
### <sub>method</sub> onMouseDown
Source: /home/runner/work/aspl/aspl/stdlib/gui/Control.aspl:49:2
```aspl
method onMouseDown(Point position, MouseButton button)
```
### <sub>method</sub> onMouseDownAny
Source: /home/runner/work/aspl/aspl/stdlib/gui/Control.aspl:51:2
```aspl
method onMouseDownAny(Point position, MouseButton button) returns bool
```
### <sub>method</sub> onMouseUp
Source: /home/runner/work/aspl/aspl/stdlib/gui/Control.aspl:55:2
```aspl
method onMouseUp(Point position, MouseButton button)
```
### <sub>method</sub> onMouseUpAny
Source: /home/runner/work/aspl/aspl/stdlib/gui/Control.aspl:57:2
```aspl
method onMouseUpAny(Point position, MouseButton button) returns bool
```
### <sub>method</sub> onMouseMove
Source: /home/runner/work/aspl/aspl/stdlib/gui/Control.aspl:61:2
```aspl
method onMouseMove(Point from, float deltaX, float deltaY)
```
### <sub>method</sub> onMouseMoveAny
Source: /home/runner/work/aspl/aspl/stdlib/gui/Control.aspl:63:2
```aspl
method onMouseMoveAny(Point from, float deltaX, float deltaY) returns bool
```
### <sub>method</sub> onMouseWheel
Source: /home/runner/work/aspl/aspl/stdlib/gui/Control.aspl:67:2
```aspl
method onMouseWheel(Point position, float deltaX, float deltaY)
```
### <sub>method</sub> onTouchDown
Source: /home/runner/work/aspl/aspl/stdlib/gui/Control.aspl:69:2
```aspl
method onTouchDown(list<TouchPoint> points)
```
### <sub>method</sub> onTouchDownAny
Source: /home/runner/work/aspl/aspl/stdlib/gui/Control.aspl:71:2
```aspl
method onTouchDownAny(list<TouchPoint> points) returns bool
```
### <sub>method</sub> onTouchUp
Source: /home/runner/work/aspl/aspl/stdlib/gui/Control.aspl:75:2
```aspl
method onTouchUp(list<TouchPoint> points)
```
### <sub>method</sub> onTouchUpAny
Source: /home/runner/work/aspl/aspl/stdlib/gui/Control.aspl:77:2
```aspl
method onTouchUpAny(list<TouchPoint> points) returns bool
```
### <sub>method</sub> onTouchMove
Source: /home/runner/work/aspl/aspl/stdlib/gui/Control.aspl:81:2
```aspl
method onTouchMove(list<TouchPoint> points)
```
### <sub>method</sub> onTouchMoveAny
Source: /home/runner/work/aspl/aspl/stdlib/gui/Control.aspl:83:2
```aspl
method onTouchMoveAny(list<TouchPoint> points) returns bool
```

## <sub>class</sub> gui.SingleLineTextBox
Source: /home/runner/work/aspl/aspl/stdlib/gui/SingleLineTextBox.aspl:6:1
### <sub>property</sub> text
Source: /home/runner/work/aspl/aspl/stdlib/gui/SingleLineTextBox.aspl:9:2
```aspl
property string text
```
### <sub>property</sub> font
Source: /home/runner/work/aspl/aspl/stdlib/gui/SingleLineTextBox.aspl:11:2
```aspl
property Font font
```
### <sub>property</sub> caret
Source: /home/runner/work/aspl/aspl/stdlib/gui/SingleLineTextBox.aspl:13:2
```aspl
property int caret
```
### <sub>property</sub> textColor
Source: /home/runner/work/aspl/aspl/stdlib/gui/SingleLineTextBox.aspl:15:2
```aspl
property Color textColor
```
### <sub>property</sub> backgroundColor
Source: /home/runner/work/aspl/aspl/stdlib/gui/SingleLineTextBox.aspl:17:2
```aspl
property Color backgroundColor
```
### <sub>property</sub> borderColor
Source: /home/runner/work/aspl/aspl/stdlib/gui/SingleLineTextBox.aspl:19:2
```aspl
property Color borderColor
```
### <sub>property</sub> horizontalAlignment
Source: /home/runner/work/aspl/aspl/stdlib/gui/SingleLineTextBox.aspl:21:5
```aspl
property HorizontalAlignment horizontalAlignment
```
### <sub>property</sub> verticalAlignment
Source: /home/runner/work/aspl/aspl/stdlib/gui/SingleLineTextBox.aspl:23:5
```aspl
property VerticalAlignment verticalAlignment
```
### <sub>property</sub> useCustomVirtualKeyboard
Source: /home/runner/work/aspl/aspl/stdlib/gui/SingleLineTextBox.aspl:25:2
```aspl
property bool useCustomVirtualKeyboard
```
### <sub>property</sub> bounds
Source: /home/runner/work/aspl/aspl/stdlib/gui/SingleLineTextBox.aspl:30:2
```aspl
property Rectangle bounds
```
### <sub>property</sub> blinkInterval
Source: /home/runner/work/aspl/aspl/stdlib/gui/SingleLineTextBox.aspl:67:2
```aspl
property int blinkInterval
```
### <sub>property</sub> blinkState
Source: /home/runner/work/aspl/aspl/stdlib/gui/SingleLineTextBox.aspl:70:2
```aspl
property bool blinkState
```
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/gui/SingleLineTextBox.aspl:77:5
```aspl
method construct(Point position, string text, Font font, int caret = 0, Color? textColor = null, Color? backgroundColor = null, Color? borderColor = null, HorizontalAlignment? horizontalAlignment = null, VerticalAlignment? verticalAlignment = null, bool useCustomVirtualKeyboard = false)
```
### <sub>method</sub> draw
Source: /home/runner/work/aspl/aspl/stdlib/gui/SingleLineTextBox.aspl:129:2
```aspl
method draw(Canvas canvas)
```
### <sub>method</sub> insert
Source: /home/runner/work/aspl/aspl/stdlib/gui/SingleLineTextBox.aspl:170:2
```aspl
method insert(string text)
```
### <sub>method</sub> backspace
Source: /home/runner/work/aspl/aspl/stdlib/gui/SingleLineTextBox.aspl:184:2
```aspl
method backspace(int amount)
```
### <sub>method</sub> onMouseDownAny
Source: /home/runner/work/aspl/aspl/stdlib/gui/SingleLineTextBox.aspl:192:2
```aspl
method onMouseDownAny(Point position, MouseButton button) returns bool
```
### <sub>method</sub> onMouseUpAny
Source: /home/runner/work/aspl/aspl/stdlib/gui/SingleLineTextBox.aspl:201:2
```aspl
method onMouseUpAny(Point position, MouseButton button) returns bool
```
### <sub>method</sub> onMouseClick
Source: /home/runner/work/aspl/aspl/stdlib/gui/SingleLineTextBox.aspl:210:2
```aspl
method onMouseClick(Point clickPosition, MouseButton button)
```
### <sub>method</sub> onMouseClickAny
Source: /home/runner/work/aspl/aspl/stdlib/gui/SingleLineTextBox.aspl:226:2
```aspl
method onMouseClickAny(Point position, MouseButton button) returns bool
```
### <sub>method</sub> onTouchDownAny
Source: /home/runner/work/aspl/aspl/stdlib/gui/SingleLineTextBox.aspl:235:2
```aspl
method onTouchDownAny(list<TouchPoint> points) returns bool
```
### <sub>method</sub> onTouchUp
Source: /home/runner/work/aspl/aspl/stdlib/gui/SingleLineTextBox.aspl:249:2
```aspl
method onTouchUp(list<TouchPoint> points)
```
### <sub>method</sub> onTouchUpAny
Source: /home/runner/work/aspl/aspl/stdlib/gui/SingleLineTextBox.aspl:254:2
```aspl
method onTouchUpAny(list<TouchPoint> points) returns bool
```
### <sub>method</sub> onKeyDown
Source: /home/runner/work/aspl/aspl/stdlib/gui/SingleLineTextBox.aspl:268:2
```aspl
method onKeyDown(KeyCode key, bool isShiftDown)
```

## <sub>class</sub> gui.VirtualKeyboard
Source: /home/runner/work/aspl/aspl/stdlib/gui/VirtualKeyboard.aspl:5:1
### <sub>property</sub> font
Source: /home/runner/work/aspl/aspl/stdlib/gui/VirtualKeyboard.aspl:8:2
```aspl
property Font font
```
### <sub>property</sub> textColor
Source: /home/runner/work/aspl/aspl/stdlib/gui/VirtualKeyboard.aspl:10:2
```aspl
property Color textColor
```
### <sub>property</sub> backgroundColor
Source: /home/runner/work/aspl/aspl/stdlib/gui/VirtualKeyboard.aspl:12:2
```aspl
property Color backgroundColor
```
### <sub>property</sub> buttonColor
Source: /home/runner/work/aspl/aspl/stdlib/gui/VirtualKeyboard.aspl:14:2
```aspl
property Color buttonColor
```
### <sub>property</sub> borderColor
Source: /home/runner/work/aspl/aspl/stdlib/gui/VirtualKeyboard.aspl:16:2
```aspl
property Color borderColor
```
### <sub>property</sub> keyDownColor
Source: /home/runner/work/aspl/aspl/stdlib/gui/VirtualKeyboard.aspl:18:2
```aspl
property Color keyDownColor
```
### <sub>property</sub> keys
Source: /home/runner/work/aspl/aspl/stdlib/gui/VirtualKeyboard.aspl:20:2
```aspl
property list<list<string>> keys
```
### <sub>property</sub> onKeyPress
Source: /home/runner/work/aspl/aspl/stdlib/gui/VirtualKeyboard.aspl:29:2
```aspl
property callback<string> onKeyPress
```
### <sub>property</sub> bounds
Source: /home/runner/work/aspl/aspl/stdlib/gui/VirtualKeyboard.aspl:38:2
```aspl
property Rectangle bounds
```
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/gui/VirtualKeyboard.aspl:77:5
```aspl
method construct(Point position, Font font, Color? textColor = null, Color? backgroundColor = null, Color? borderColor = null, Color? keyDownColor = null)
```
### <sub>method</sub> draw
Source: /home/runner/work/aspl/aspl/stdlib/gui/VirtualKeyboard.aspl:104:2
```aspl
method draw(Canvas canvas)
```
### <sub>method</sub> onMouseDown
Source: /home/runner/work/aspl/aspl/stdlib/gui/VirtualKeyboard.aspl:141:2
```aspl
method onMouseDown(Point position, MouseButton button)
```
### <sub>method</sub> onMouseUp
Source: /home/runner/work/aspl/aspl/stdlib/gui/VirtualKeyboard.aspl:151:2
```aspl
method onMouseUp(Point position, MouseButton button)
```
### <sub>method</sub> onTouchDown
Source: /home/runner/work/aspl/aspl/stdlib/gui/VirtualKeyboard.aspl:179:2
```aspl
method onTouchDown(list<TouchPoint> points)
```
### <sub>method</sub> onTouchUp
Source: /home/runner/work/aspl/aspl/stdlib/gui/VirtualKeyboard.aspl:192:2
```aspl
method onTouchUp(list<TouchPoint> points)
```