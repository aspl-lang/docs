# io
## <sub>class</sub> io.BinaryStream
Source: /home/runner/work/aspl/aspl/stdlib/io/BinaryStream.aspl:2:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/io/BinaryStream.aspl:7:2
```aspl
method construct(list<byte> bytes)
```
### <sub>method</sub> getBytes
Source: /home/runner/work/aspl/aspl/stdlib/io/BinaryStream.aspl:12:5
```aspl
method getBytes() returns list<byte>
```
### <sub>method</sub> peekByte
Source: /home/runner/work/aspl/aspl/stdlib/io/BinaryStream.aspl:17:5
```aspl
method peekByte() returns byte
```
### <sub>method</sub> peekBytes
Source: /home/runner/work/aspl/aspl/stdlib/io/BinaryStream.aspl:22:5
```aspl
method peekBytes(int count) returns list<byte>
```
### <sub>method</sub> readByte
Source: /home/runner/work/aspl/aspl/stdlib/io/BinaryStream.aspl:29:5
```aspl
method readByte() returns byte
```
### <sub>method</sub> readBytes
Source: /home/runner/work/aspl/aspl/stdlib/io/BinaryStream.aspl:36:5
```aspl
method readBytes(int count) returns list<byte>
```
### <sub>method</sub> writeByte
Source: /home/runner/work/aspl/aspl/stdlib/io/BinaryStream.aspl:45:5
```aspl
method writeByte(byte b)
```
### <sub>method</sub> writeBytes
Source: /home/runner/work/aspl/aspl/stdlib/io/BinaryStream.aspl:51:5
```aspl
method writeBytes(list<byte> bytes)
```

## <sub>class</sub> io.Stream
Source: /home/runner/work/aspl/aspl/stdlib/io/Stream.aspl:3:1
### <sub>property</sub> position
Source: /home/runner/work/aspl/aspl/stdlib/io/Stream.aspl:6:5
```aspl
property int position
```
### <sub>method</sub> getPosition
Source: /home/runner/work/aspl/aspl/stdlib/io/Stream.aspl:10:2
```aspl
method getPosition() returns int
```
### <sub>method</sub> setPosition
Source: /home/runner/work/aspl/aspl/stdlib/io/Stream.aspl:16:2
```aspl
method setPosition(int position)
```

## <sub>function</sub> io.exists_directory
Source: /home/runner/work/aspl/aspl/stdlib/io/directories.aspl:2:1
```aspl
function exists_directory(string path) returns bool
```

## <sub>function</sub> io.create_directory
Source: /home/runner/work/aspl/aspl/stdlib/io/directories.aspl:7:1
```aspl
function create_directory(string path)
```

## <sub>function</sub> io.delete_directory
Source: /home/runner/work/aspl/aspl/stdlib/io/directories.aspl:12:1
```aspl
function delete_directory(string path)
```

## <sub>function</sub> io.full_directory_path
Source: /home/runner/work/aspl/aspl/stdlib/io/directories.aspl:17:1
```aspl
function full_directory_path(string path) returns string
```

## <sub>function</sub> io.directory_name
Source: /home/runner/work/aspl/aspl/stdlib/io/directories.aspl:22:1
```aspl
function directory_name(string path) returns string
```

## <sub>function</sub> io.directories
Source: /home/runner/work/aspl/aspl/stdlib/io/directories.aspl:27:1
```aspl
function directories(string path) returns list<string>
```

## <sub>function</sub> io.get_home_directory
Source: /home/runner/work/aspl/aspl/stdlib/io/directories.aspl:32:1
```aspl
function get_home_directory() returns string
```

## <sub>function</sub> io.exists_file
Source: /home/runner/work/aspl/aspl/stdlib/io/files.aspl:2:1
```aspl
function exists_file(string path) returns bool
```

## <sub>function</sub> io.read_file
Source: /home/runner/work/aspl/aspl/stdlib/io/files.aspl:7:1
```aspl
function read_file(string path) returns string
```

## <sub>function</sub> io.read_file_bytes
Source: /home/runner/work/aspl/aspl/stdlib/io/files.aspl:12:1
```aspl
function read_file_bytes(string path) returns list<byte>
```

## <sub>function</sub> io.write_file
Source: /home/runner/work/aspl/aspl/stdlib/io/files.aspl:17:1
```aspl
function write_file(string path, string data)
```

## <sub>function</sub> io.write_file_bytes
Source: /home/runner/work/aspl/aspl/stdlib/io/files.aspl:22:1
```aspl
function write_file_bytes(string path, list<byte> data)
```

## <sub>function</sub> io.file_name
Source: /home/runner/work/aspl/aspl/stdlib/io/files.aspl:27:1
```aspl
function file_name(string path) returns string
```

## <sub>function</sub> io.delete_file
Source: /home/runner/work/aspl/aspl/stdlib/io/files.aspl:32:1
```aspl
function delete_file(string path)
```

## <sub>function</sub> io.files
Source: /home/runner/work/aspl/aspl/stdlib/io/files.aspl:37:1
```aspl
function files(string path) returns list<string>
```

## <sub>function</sub> io.glob
Source: /home/runner/work/aspl/aspl/stdlib/io/glob.aspl:2:1
```aspl
function glob(string pattern) returns list<string>
```

## <sub>function</sub> io.abs
Source: /home/runner/work/aspl/aspl/stdlib/io/path.aspl:2:1
```aspl
function abs(string relative) returns string
```

## <sub>function</sub> io.join_path
Source: /home/runner/work/aspl/aspl/stdlib/io/path.aspl:7:1
```aspl
function join_path(list<string> paths) returns string
```

## <sub>function</sub> io.get_executable_path
Source: /home/runner/work/aspl/aspl/stdlib/io/path.aspl:21:1
```aspl
function get_executable_path() returns string
```

## <sub>function</sub> io.copy
Source: /home/runner/work/aspl/aspl/stdlib/io/path.aspl:26:1
```aspl
function copy(string from, string to)
```

## <sub>function</sub> io.move
Source: /home/runner/work/aspl/aspl/stdlib/io/path.aspl:31:1
```aspl
function move(string from, string to)
```

## <sub>function</sub> io.create_symlink
Source: /home/runner/work/aspl/aspl/stdlib/io/symlink.aspl:2:1
```aspl
function create_symlink(string origin, string target)
```