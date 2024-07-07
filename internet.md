# internet
## <sub>class</sub> internet.HttpResponse
Source: /home/runner/work/aspl/aspl/stdlib/internet/HttpResponse.aspl:2:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/internet/HttpResponse.aspl:16:5
```aspl
method construct(string text, map<string, list<string>> headers, int statusCode, string statusMessage, string httpVersion)
```

## <sub>class</sub> internet.WebSocketClient
Source: /home/runner/work/aspl/aspl/stdlib/internet/WebSocketClient.aspl:2:1
### <sub>property</sub> onConnect
Source: /home/runner/work/aspl/aspl/stdlib/internet/WebSocketClient.aspl:7:5
```aspl
property callback onConnect
```
### <sub>property</sub> onMessage
Source: /home/runner/work/aspl/aspl/stdlib/internet/WebSocketClient.aspl:9:5
```aspl
property callback<string> onMessage
```
### <sub>property</sub> onError
Source: /home/runner/work/aspl/aspl/stdlib/internet/WebSocketClient.aspl:11:5
```aspl
property callback<string> onError
```
### <sub>property</sub> onClose
Source: /home/runner/work/aspl/aspl/stdlib/internet/WebSocketClient.aspl:13:5
```aspl
property callback<int, string> onClose
```
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/internet/WebSocketClient.aspl:18:2
```aspl
method construct(string uri)
```
### <sub>method</sub> connect
Source: /home/runner/work/aspl/aspl/stdlib/internet/WebSocketClient.aspl:37:5
```aspl
method connect()
```
### <sub>method</sub> send
Source: /home/runner/work/aspl/aspl/stdlib/internet/WebSocketClient.aspl:42:5
```aspl
method send(string content)
```
### <sub>method</sub> disconnect
Source: /home/runner/work/aspl/aspl/stdlib/internet/WebSocketClient.aspl:47:5
```aspl
method disconnect(int code, string reason)
```

## <sub>class</sub> internet.WebSocketServerClient
Source: /home/runner/work/aspl/aspl/stdlib/internet/WebSocketServerClient.aspl:2:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/internet/WebSocketServerClient.aspl:9:5
```aspl
method construct(any handle)
```
### <sub>method</sub> send
Source: /home/runner/work/aspl/aspl/stdlib/internet/WebSocketServerClient.aspl:15:5
```aspl
method send(string content)
```

## <sub>enum</sub> internet.AddressFamily
Source: /home/runner/work/aspl/aspl/stdlib/internet/AddressFamily.aspl:2:1
```aspl

```

## <sub>function</sub> internet.get
Source: /home/runner/work/aspl/aspl/stdlib/internet/http.aspl:2:1
```aspl
function get(string uri, string data = "", map<string, list<string>>? headers = null) returns HttpResponse
```

## <sub>function</sub> internet.post
Source: /home/runner/work/aspl/aspl/stdlib/internet/http.aspl:8:1
```aspl
function post(string uri, string data, map<string, list<string>>? headers = null) returns HttpResponse
```

## <sub>function</sub> internet.put
Source: /home/runner/work/aspl/aspl/stdlib/internet/http.aspl:14:1
```aspl
function put(string uri, string data, map<string, list<string>>? headers = null) returns HttpResponse
```

## <sub>function</sub> internet.head
Source: /home/runner/work/aspl/aspl/stdlib/internet/http.aspl:20:1
```aspl
function head(string uri, string data, map<string, list<string>>? headers = null) returns HttpResponse
```

## <sub>function</sub> internet.delete
Source: /home/runner/work/aspl/aspl/stdlib/internet/http.aspl:26:1
```aspl
function delete(string uri, string data, map<string, list<string>>? headers = null) returns HttpResponse
```

## <sub>function</sub> internet.options
Source: /home/runner/work/aspl/aspl/stdlib/internet/http.aspl:32:1
```aspl
function options(string uri, string data, map<string, list<string>>? headers = null) returns HttpResponse
```

## <sub>function</sub> internet.trace
Source: /home/runner/work/aspl/aspl/stdlib/internet/http.aspl:38:1
```aspl
function trace(string uri, string data, map<string, list<string>>? headers = null) returns HttpResponse
```

## <sub>function</sub> internet.connect
Source: /home/runner/work/aspl/aspl/stdlib/internet/http.aspl:44:1
```aspl
function connect(string uri, string data, map<string, list<string>>? headers = null) returns HttpResponse
```

## <sub>function</sub> internet.patch
Source: /home/runner/work/aspl/aspl/stdlib/internet/http.aspl:50:1
```aspl
function patch(string uri, string data, map<string, list<string>>? headers = null) returns HttpResponse
```