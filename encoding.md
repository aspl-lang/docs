# encoding
## <sub>class</sub> encoding.ascii.LegacyASCIITable
Source: /home/runner/work/aspl/aspl/stdlib/encoding/ascii/LegacyASCIITable.aspl:2:1
### <sub>property</sub> idToChar
Source: /home/runner/work/aspl/aspl/stdlib/encoding/ascii/LegacyASCIITable.aspl:6:5
```aspl
property map<byte, string> idToChar
```
### <sub>property</sub> charToId
Source: /home/runner/work/aspl/aspl/stdlib/encoding/ascii/LegacyASCIITable.aspl:271:5
```aspl
property map<string, byte> charToId
```

## <sub>function</sub> encoding.ascii.decode
Source: /home/runner/work/aspl/aspl/stdlib/encoding/ascii/decoder.aspl:4:1
```aspl
function decode(list<byte> bytes) returns string
```

## <sub>function</sub> encoding.ascii.decode_char
Source: /home/runner/work/aspl/aspl/stdlib/encoding/ascii/decoder.aspl:13:1
```aspl
function decode_char(byte b) returns string
```

## <sub>function</sub> encoding.ascii.encode
Source: /home/runner/work/aspl/aspl/stdlib/encoding/ascii/encoder.aspl:4:1
```aspl
function encode(string s) returns list<byte>
```

## <sub>function</sub> encoding.ascii.encode_char
Source: /home/runner/work/aspl/aspl/stdlib/encoding/ascii/encoder.aspl:13:1
```aspl
function encode_char(string c) returns byte
```

## <sub>function</sub> encoding.base64.encode
Source: /home/runner/work/aspl/aspl/stdlib/encoding/base64/base64.aspl:2:1
```aspl
function encode(string s) returns string
```

## <sub>function</sub> encoding.base64.decode
Source: /home/runner/work/aspl/aspl/stdlib/encoding/base64/base64.aspl:7:1
```aspl
function decode(string s) returns string
```

## <sub>function</sub> encoding.hex.encode
Source: /home/runner/work/aspl/aspl/stdlib/encoding/hex/hex.aspl:5:1
```aspl
function encode(string hex) returns int
```

## <sub>function</sub> encoding.hex.encode_digit
Source: /home/runner/work/aspl/aspl/stdlib/encoding/hex/hex.aspl:16:1
```aspl
function encode_digit(string hex) returns byte
```

## <sub>function</sub> encoding.hex.decode
Source: /home/runner/work/aspl/aspl/stdlib/encoding/hex/hex.aspl:53:1
```aspl
function decode(int n) returns string
```

## <sub>function</sub> encoding.hex.decode_digit
Source: /home/runner/work/aspl/aspl/stdlib/encoding/hex/hex.aspl:65:1
```aspl
function decode_digit(byte b) returns string
```

## <sub>function</sub> encoding.utf8.encode
Source: /home/runner/work/aspl/aspl/stdlib/encoding/utf8/utf8.aspl:2:1
```aspl
function encode(string s) returns list<byte>
```

## <sub>function</sub> encoding.utf8.encode_char
Source: /home/runner/work/aspl/aspl/stdlib/encoding/utf8/utf8.aspl:7:1
```aspl
function encode_char(string c) returns int
```

## <sub>function</sub> encoding.utf8.decode
Source: /home/runner/work/aspl/aspl/stdlib/encoding/utf8/utf8.aspl:12:1
```aspl
function decode(list<byte> bytes) returns string
```

## <sub>function</sub> encoding.utf8.decode_char
Source: /home/runner/work/aspl/aspl/stdlib/encoding/utf8/utf8.aspl:17:1
```aspl
function decode_char(int code) returns string
```