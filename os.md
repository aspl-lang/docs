# os
## <sub>class</sub> os.CommandResult
Source: /home/runner/work/aspl/aspl/stdlib/os/CommandResult.aspl:2:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/os/CommandResult.aspl:10:5
```aspl
method construct(int exitCode, string output)
```

## <sub>enum</sub> os.Architecture
Source: /home/runner/work/aspl/aspl/stdlib/os/Architecture.aspl:2:1
```aspl

```

## <sub>function</sub> os.architecture_from_string
Source: /home/runner/work/aspl/aspl/stdlib/os/Architecture.aspl:12:1
```aspl
function architecture_from_string(string arch) returns Architecture?
```

## <sub>function</sub> os.args
Source: /home/runner/work/aspl/aspl/stdlib/os/args.aspl:4:1
```aspl
function args() returns list<string>
```

> args returns the cli arguments passed to the currently running process


## <sub>function</sub> os.execute
Source: /home/runner/work/aspl/aspl/stdlib/os/commands.aspl:3:1
```aspl
function execute(string command) returns CommandResult
```

> execute executes a program and returns the exit code and the output


## <sub>function</sub> os.system
Source: /home/runner/work/aspl/aspl/stdlib/os/commands.aspl:10:1
```aspl
function system(string command) returns int
```

> system executes a program (like os.execute()), but only returns the exit code


## <sub>function</sub> os.execvp
Source: /home/runner/work/aspl/aspl/stdlib/os/commands.aspl:17:1
```aspl
function execvp(string command, list<string> args)
```

> execvp executes a program in place of the current process


## <sub>function</sub> os.getwd
Source: /home/runner/work/aspl/aspl/stdlib/os/fs.aspl:3:1
```aspl
function getwd() returns string
```

> getwd returns the current working directory


## <sub>function</sub> os.chdir
Source: /home/runner/work/aspl/aspl/stdlib/os/fs.aspl:9:1
```aspl
function chdir(string path)
```

> chdir changes the current working directory to the specified path


## <sub>function</sub> os.chmod
Source: /home/runner/work/aspl/aspl/stdlib/os/fs.aspl:15:1
```aspl
function chmod(string path, int mode)
```

> chmod changes the mode of the specified file to the specified mode


## <sub>function</sub> os.create_temp_dir
Source: /home/runner/work/aspl/aspl/stdlib/os/fs.aspl:21:1
```aspl
function create_temp_dir() returns string
```

> create_temp_dir creates and returns a unique ephemeral directory suitable for storing temporary files


## <sub>function</sub> os.user_os
Source: /home/runner/work/aspl/aspl/stdlib/os/os.aspl:3:1
```aspl
function user_os() returns string
```

> user_os returns the name of the operating system currently used to execute this program


## <sub>function</sub> os.user_architecture
Source: /home/runner/work/aspl/aspl/stdlib/os/os.aspl:9:1
```aspl
function user_architecture() returns string
```

> user_architecture returns the name of the architecture currently used to execute this program


## <sub>function</sub> os.user_architecture_generic
Source: /home/runner/work/aspl/aspl/stdlib/os/os.aspl:15:1
```aspl
function user_architecture_generic() returns Architecture
```

> user_architecture_generic returns a value from the Architecture enum and is more generic than os.user_architecture()