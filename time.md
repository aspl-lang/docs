# time
## <sub>class</sub> time.Timestamp
Source: /home/runner/work/aspl/aspl/stdlib/time/Timestamp.aspl:2:1
### <sub>property</sub> microseconds
Source: /home/runner/work/aspl/aspl/stdlib/time/Timestamp.aspl:7:5
```aspl
property long microseconds
```
### <sub>property</sub> milliseconds
Source: /home/runner/work/aspl/aspl/stdlib/time/Timestamp.aspl:13:5
```aspl
property long milliseconds
```
### <sub>property</sub> seconds
Source: /home/runner/work/aspl/aspl/stdlib/time/Timestamp.aspl:19:5
```aspl
property long seconds
```
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/time/Timestamp.aspl:26:5
```aspl
method construct(long nanoseconds)
```

## <sub>function</sub> time.sleep
Source: /home/runner/work/aspl/aspl/stdlib/time/sleep.aspl:2:1
```aspl
function sleep(long seconds)
```

## <sub>function</sub> time.millisleep
Source: /home/runner/work/aspl/aspl/stdlib/time/sleep.aspl:7:1
```aspl
function millisleep(long milliseconds)
```

## <sub>function</sub> time.microsleep
Source: /home/runner/work/aspl/aspl/stdlib/time/sleep.aspl:12:1
```aspl
function microsleep(long microseconds)
```

## <sub>function</sub> time.nanosleep
Source: /home/runner/work/aspl/aspl/stdlib/time/sleep.aspl:17:1
```aspl
function nanosleep(long nanoseconds)
```

## <sub>function</sub> time.now
Source: /home/runner/work/aspl/aspl/stdlib/time/time.aspl:3:1
```aspl
function now() returns Timestamp
```

> now returns the current time since the Unix Epoch (UTC)


## <sub>function</sub> time.local
Source: /home/runner/work/aspl/aspl/stdlib/time/time.aspl:9:1
```aspl
function local() returns Timestamp
```

> local returns the current time since the Unix Epoch (local timezone)