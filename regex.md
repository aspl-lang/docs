# regex
## <sub>class</sub> regex.Match
Source: /home/runner/work/aspl/aspl/stdlib/regex/Match.aspl:2:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/regex/Match.aspl:12:2
```aspl
method construct(int start, int end, string value)
```

## <sub>function</sub> regex.find_first
Source: /home/runner/work/aspl/aspl/stdlib/regex/regex.aspl:2:1
```aspl
function find_first(string pattern, string haystack) returns Match?
```

## <sub>function</sub> regex.match_string
Source: /home/runner/work/aspl/aspl/stdlib/regex/regex.aspl:12:1
```aspl
function match_string(string pattern, string haystack) returns Match?
```

## <sub>function</sub> regex.replace_first
Source: /home/runner/work/aspl/aspl/stdlib/regex/regex.aspl:22:1
```aspl
function replace_first(string pattern, string replace, string haystack) returns string
```

## <sub>function</sub> regex.find_all
Source: /home/runner/work/aspl/aspl/stdlib/regex/regex.aspl:27:1
```aspl
function find_all(string pattern, string haystack) returns list<Match>
```

## <sub>function</sub> regex.replace_all
Source: /home/runner/work/aspl/aspl/stdlib/regex/regex.aspl:37:1
```aspl
function replace_all(string pattern, string replace, string haystack) returns string
```