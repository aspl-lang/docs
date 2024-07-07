# strings
## <sub>class</sub> strings.StringBuilder
Source: /home/runner/work/aspl/aspl/stdlib/strings/StringBuilder.aspl:3:1
### <sub>property</sub> length
Source: /home/runner/work/aspl/aspl/stdlib/strings/StringBuilder.aspl:7:5
```aspl
property int length
```
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/strings/StringBuilder.aspl:14:5
```aspl
method construct(string str = "")
```
### <sub>method</sub> append
Source: /home/runner/work/aspl/aspl/stdlib/strings/StringBuilder.aspl:24:5

> append writes the given string or string builder to the end of this string builder

```aspl
method append(string|StringBuilder str) returns self
```
### <sub>method</sub> toString
Source: /home/runner/work/aspl/aspl/stdlib/strings/StringBuilder.aspl:36:5

> toString returns the constructed string

```aspl
method toString() returns string
```
### <sub>method</sub> toStringFlush
Source: /home/runner/work/aspl/aspl/stdlib/strings/StringBuilder.aspl:44:5

> toStringFlush returns the constructed string and empties the string builder

```aspl
method toStringFlush() returns string
```