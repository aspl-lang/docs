# sqlite
## <sub>class</sub> sqlite.Database
Source: /home/runner/work/aspl/aspl/stdlib/sqlite/Database.aspl:2:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/sqlite/Database.aspl:7:5
```aspl
method construct(string file)
```
### <sub>method</sub> prepare
Source: /home/runner/work/aspl/aspl/stdlib/sqlite/Database.aspl:12:5
```aspl
method prepare(string query) returns Statement
```
### <sub>method</sub> query
Source: /home/runner/work/aspl/aspl/stdlib/sqlite/Database.aspl:17:5
```aspl
method query(string query) returns Response
```
### <sub>method</sub> close
Source: /home/runner/work/aspl/aspl/stdlib/sqlite/Database.aspl:22:5
```aspl
method close()
```

## <sub>class</sub> sqlite.Response
Source: /home/runner/work/aspl/aspl/stdlib/sqlite/Response.aspl:2:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/sqlite/Response.aspl:7:5
```aspl
method construct(any handle)
```
### <sub>method</sub> fetchRow
Source: /home/runner/work/aspl/aspl/stdlib/sqlite/Response.aspl:12:5
```aspl
method fetchRow() returns map<string, any>?
```
### <sub>method</sub> fetchRows
Source: /home/runner/work/aspl/aspl/stdlib/sqlite/Response.aspl:23:5
```aspl
method fetchRows() returns list<map<string, any>>
```
### <sub>method</sub> finalize
Source: /home/runner/work/aspl/aspl/stdlib/sqlite/Response.aspl:35:5
```aspl
method finalize()
```

## <sub>class</sub> sqlite.Statement
Source: /home/runner/work/aspl/aspl/stdlib/sqlite/Statement.aspl:2:1
### <sub>method</sub> bind
Source: /home/runner/work/aspl/aspl/stdlib/sqlite/Statement.aspl:11:5
```aspl
method bind(string parameter, any value)
```
### <sub>method</sub> execute
Source: /home/runner/work/aspl/aspl/stdlib/sqlite/Statement.aspl:16:5
```aspl
method execute() returns Response
```