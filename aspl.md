# aspl
## <sub>class</sub> aspl.compiler.CompilationResult
Source: /home/runner/work/aspl/aspl/stdlib/aspl/compiler/CompilationResult.aspl:4:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/compiler/CompilationResult.aspl:10:5
```aspl
method construct(list<byte> output)
```

## <sub>class</sub> aspl.compiler.backend.Backend
Source: /home/runner/work/aspl/aspl/stdlib/aspl/compiler/backend/Backend.aspl:6:1
### <sub>method</sub> compile
Source: /home/runner/work/aspl/aspl/stdlib/aspl/compiler/backend/Backend.aspl:10:5
```aspl
method compile(ParserResult result) returns CompilationResult
```

## <sub>class</sub> aspl.compiler.backend.bytecode.ByteList
Source: /home/runner/work/aspl/aspl/stdlib/aspl/compiler/backend/bytecode/ByteList.aspl:7:1
### <sub>property</sub> bytes
Source: /home/runner/work/aspl/aspl/stdlib/aspl/compiler/backend/bytecode/ByteList.aspl:10:5
```aspl
property list<byte> bytes
```
### <sub>property</sub> length
Source: /home/runner/work/aspl/aspl/stdlib/aspl/compiler/backend/bytecode/ByteList.aspl:12:5
```aspl
property int length
```
### <sub>method</sub> add
Source: /home/runner/work/aspl/aspl/stdlib/aspl/compiler/backend/bytecode/ByteList.aspl:19:5
```aspl
method add(any value, IntType type = IntType.Int) returns self
```

## <sub>class</sub> aspl.compiler.backend.bytecode.BytecodeBackend
Source: /home/runner/work/aspl/aspl/stdlib/aspl/compiler/backend/bytecode/BytecodeBackend.aspl:13:1
### <sub>method</sub> encode
Source: /home/runner/work/aspl/aspl/stdlib/aspl/compiler/backend/bytecode/BytecodeBackend.aspl:16:5
```aspl
method encode(Node node, bool standalone = false) returns ByteList
```

## <sub>class</sub> aspl.compiler.backend.bytecode.ail.AILBytecodeBackend
Source: /home/runner/work/aspl/aspl/stdlib/aspl/compiler/backend/bytecode/ail/AILBytecodeBackend.aspl:17:1
### <sub>method</sub> compile
Source: /home/runner/work/aspl/aspl/stdlib/aspl/compiler/backend/bytecode/ail/AILBytecodeBackend.aspl:22:5
```aspl
method compile(ParserResult result) returns CompilationResult
```

## <sub>class</sub> aspl.compiler.backend.bytecode.ail.TypeUtils
Source: /home/runner/work/aspl/aspl/stdlib/aspl/compiler/backend/bytecode/ail/TypeUtils.aspl:3:1
### <sub>method</sub> shortName
Source: /home/runner/work/aspl/aspl/stdlib/aspl/compiler/backend/bytecode/ail/TypeUtils.aspl:7:5
```aspl
method shortName(string s) returns string
```

## <sub>class</sub> aspl.compiler.backend.bytecode.twail.TreeWalkingAILBytecodeBackend
Source: /home/runner/work/aspl/aspl/stdlib/aspl/compiler/backend/bytecode/twail/TreeWalkingAILBytecodeBackend.aspl:17:1
### <sub>method</sub> compile
Source: /home/runner/work/aspl/aspl/stdlib/aspl/compiler/backend/bytecode/twail/TreeWalkingAILBytecodeBackend.aspl:20:5
```aspl
method compile(ParserResult result) returns CompilationResult
```

## <sub>class</sub> aspl.compiler.backend.bytecode.twail.TypeUtils
Source: /home/runner/work/aspl/aspl/stdlib/aspl/compiler/backend/bytecode/twail/TypeUtils.aspl:3:1
### <sub>method</sub> shortName
Source: /home/runner/work/aspl/aspl/stdlib/aspl/compiler/backend/bytecode/twail/TypeUtils.aspl:7:5
```aspl
method shortName(string s) returns string
```

## <sub>class</sub> aspl.compiler.backend.stringcode.StringcodeBackend
Source: /home/runner/work/aspl/aspl/stdlib/aspl/compiler/backend/stringcode/StringcodeBackend.aspl:13:1
### <sub>property</sub> indentLevel
Source: /home/runner/work/aspl/aspl/stdlib/aspl/compiler/backend/stringcode/StringcodeBackend.aspl:16:5
```aspl
property int indentLevel
```
### <sub>method</sub> encode
Source: /home/runner/work/aspl/aspl/stdlib/aspl/compiler/backend/stringcode/StringcodeBackend.aspl:19:5
```aspl
method encode(Node node, bool standalone = false) returns string
```

## <sub>class</sub> aspl.compiler.backend.stringcode.c.CBackend
Source: /home/runner/work/aspl/aspl/stdlib/aspl/compiler/backend/stringcode/c/CBackend.aspl:21:1
### <sub>method</sub> compile
Source: /home/runner/work/aspl/aspl/stdlib/aspl/compiler/backend/stringcode/c/CBackend.aspl:39:5
```aspl
method compile(ParserResult result) returns CompilationResult
```

## <sub>class</sub> aspl.compiler.backend.stringcode.c.TypeUtils
Source: /home/runner/work/aspl/aspl/stdlib/aspl/compiler/backend/stringcode/c/TypeUtils.aspl:3:1
### <sub>method</sub> shortName
Source: /home/runner/work/aspl/aspl/stdlib/aspl/compiler/backend/stringcode/c/TypeUtils.aspl:7:5
```aspl
method shortName(string s) returns string
```
### <sub>method</sub> typeToCIdentifier
Source: /home/runner/work/aspl/aspl/stdlib/aspl/compiler/backend/stringcode/c/TypeUtils.aspl:19:5
```aspl
method typeToCIdentifier(string type) returns string
```

## <sub>class</sub> aspl.compiler.utils.IncludeUtils
Source: /home/runner/work/aspl/aspl/stdlib/aspl/compiler/utils/IncludeUtils.aspl:3:1
### <sub>property</sub> files
Source: /home/runner/work/aspl/aspl/stdlib/aspl/compiler/utils/IncludeUtils.aspl:8:5
```aspl
property list<string> files
```
### <sub>method</sub> include
Source: /home/runner/work/aspl/aspl/stdlib/aspl/compiler/utils/IncludeUtils.aspl:12:5
```aspl
method include(string file)
```

## <sub>class</sub> aspl.compiler.utils.LinkUtils
Source: /home/runner/work/aspl/aspl/stdlib/aspl/compiler/utils/LinkUtils.aspl:3:1
### <sub>property</sub> libraries
Source: /home/runner/work/aspl/aspl/stdlib/aspl/compiler/utils/LinkUtils.aspl:8:5
```aspl
property list<string> libraries
```

## <sub>class</sub> aspl.parser.Module
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Module.aspl:2:1
### <sub>property</sub> modules
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Module.aspl:7:5
```aspl
property map<string, Module> modules
```
### <sub>property</sub> mainModule
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Module.aspl:11:5
```aspl
property Module mainModule
```
### <sub>property</sub> id
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Module.aspl:28:5
```aspl
property string id
```
### <sub>method</sub> init
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Module.aspl:19:5
```aspl
method init(Module mainModule)
```
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Module.aspl:37:5
```aspl
method construct(string name, string directory)
```

## <sub>class</sub> aspl.parser.Options
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Options.aspl:4:1
### <sub>property</sub> targetOs
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Options.aspl:20:5
```aspl
property string targetOs
```
### <sub>property</sub> targetArchitecture
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Options.aspl:39:5
```aspl
property Architecture targetArchitecture
```
### <sub>property</sub> outputFile
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Options.aspl:53:5
```aspl
property string? outputFile
```
### <sub>property</sub> production
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Options.aspl:57:5
```aspl
property bool production
```
### <sub>property</sub> keepTemporary
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Options.aspl:61:5
```aspl
property bool keepTemporary
```
### <sub>property</sub> guiApp
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Options.aspl:65:5
```aspl
property bool guiApp
```
### <sub>property</sub> customConditionalCompilationSymbols
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Options.aspl:69:5
```aspl
property list<string> customConditionalCompilationSymbols
```
### <sub>property</sub> backend
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Options.aspl:73:5
```aspl
property string backend
```
### <sub>property</sub> _cCompiler
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Options.aspl:77:5
```aspl
property string? _cCompiler
```
### <sub>property</sub> cCompiler
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Options.aspl:80:5
```aspl
property string cCompiler
```
### <sub>property</sub> useDynamicCTemplate
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Options.aspl:104:5
```aspl
property bool useDynamicCTemplate
```
### <sub>property</sub> showCCommand
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Options.aspl:108:5
```aspl
property bool showCCommand
```
### <sub>property</sub> heapBased
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Options.aspl:112:5
```aspl
property bool heapBased
```
### <sub>property</sub> stackSize
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Options.aspl:116:5
```aspl
property int? stackSize
```
### <sub>property</sub> useSsl
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Options.aspl:120:5
```aspl
property bool useSsl
```
### <sub>property</sub> enableErrorHandling
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Options.aspl:124:5
```aspl
property bool enableErrorHandling
```
### <sub>property</sub> noCachedTemplate
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Options.aspl:128:5
```aspl
property bool noCachedTemplate
```
### <sub>property</sub> internalTemplateType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Options.aspl:132:5
```aspl
property string internalTemplateType
```
### <sub>property</sub> internalDoNotBundle
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Options.aspl:136:5
```aspl
property bool internalDoNotBundle
```
### <sub>method</sub> getConditionCompilationSymbols
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Options.aspl:140:5
```aspl
method getConditionCompilationSymbols() returns list<string>
```

## <sub>class</sub> aspl.parser.ParseFileResult
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ParseFileResult.aspl:4:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ParseFileResult.aspl:10:5
```aspl
method construct(list<Node> nodes)
```

## <sub>class</sub> aspl.parser.Parser
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Parser.aspl:20:1
### <sub>property</sub> module
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Parser.aspl:23:2
```aspl
property Module module
```
### <sub>property</sub> file
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Parser.aspl:25:2
```aspl
property string file
```
### <sub>property</sub> currentNamespace
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Parser.aspl:27:2
```aspl
property string currentNamespace
```
### <sub>property</sub> currentClass
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Parser.aspl:48:2
```aspl
property Class? currentClass
```
### <sub>property</sub> currentEnum
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Parser.aspl:51:2
```aspl
property Enum? currentEnum
```
### <sub>property</sub> currentMethod
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Parser.aspl:53:2
```aspl
property Method? currentMethod
```
### <sub>property</sub> attributeCache
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Parser.aspl:55:2
```aspl
property list<AttributeInstance> attributeCache
```
### <sub>property</sub> importTable
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Parser.aspl:60:2
```aspl
property ImportTable importTable
```
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Parser.aspl:85:2
```aspl
method construct(Module module, string file)
```
### <sub>method</sub> parse
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Parser.aspl:102:2
```aspl
method parse(ParseMode parseMode = ParseMode.Normal) returns ParseFileResult
```
### <sub>method</sub> parseToken
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Parser.aspl:623:2
```aspl
method parseToken(Token token, TokenList tokens, bool standalone = false, PrecedenceLevel precedenceLevel = PrecedenceLevel.None, Expression? previousExpression = null, Types? expectedTypes = null) returns Node
```
### <sub>method</sub> peekTypeIdentifier
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Parser.aspl:3080:2
```aspl
method peekTypeIdentifier(TokenList tokens, Token? first = null) returns IdentifierResult
```
### <sub>method</sub> parseTypeIdentifier
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Parser.aspl:3157:2
```aspl
method parseTypeIdentifier(TokenList tokens, Token? first = null) returns IdentifierResult
```

## <sub>class</sub> aspl.parser.ParserResult
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ParserResult.aspl:4:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ParserResult.aspl:10:5
```aspl
method construct(list<Node> nodes)
```

## <sub>class</sub> aspl.parser.Timings
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Timings.aspl:5:1
### <sub>property</sub> total
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Timings.aspl:33:5
```aspl
property long total
```
### <sub>method</sub> startLexer
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Timings.aspl:41:5
```aspl
method startLexer()
```
### <sub>method</sub> stopLexer
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Timings.aspl:47:5
```aspl
method stopLexer()
```
### <sub>method</sub> startPreprocessorTypes
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Timings.aspl:54:5
```aspl
method startPreprocessorTypes()
```
### <sub>method</sub> stopPreprocessorTypes
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Timings.aspl:60:5
```aspl
method stopPreprocessorTypes()
```
### <sub>method</sub> startPreprocessor
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Timings.aspl:67:5
```aspl
method startPreprocessor()
```
### <sub>method</sub> stopPreprocessor
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Timings.aspl:73:5
```aspl
method stopPreprocessor()
```
### <sub>method</sub> startParser
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Timings.aspl:80:5
```aspl
method startParser()
```
### <sub>method</sub> stopParser
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/Timings.aspl:86:5
```aspl
method stopParser()
```

## <sub>class</sub> aspl.parser.ast.Node
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/Node.aspl:6:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/Node.aspl:12:2
```aspl
method construct(Location? location)
```

## <sub>class</sub> aspl.parser.ast.expressions.AndExpression
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/AndExpression.aspl:4:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/AndExpression.aspl:7:5
```aspl
method construct(Expression left, Expression right, Location? location)
```
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/AndExpression.aspl:12:5
```aspl
method getType() returns Types
```
### <sub>method</sub> getConstantValue
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/AndExpression.aspl:17:5
```aspl
method getConstantValue() returns any
```

## <sub>class</sub> aspl.parser.ast.expressions.BinaryOperator
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/BinaryOperator.aspl:6:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/BinaryOperator.aspl:14:5
```aspl
method construct(Expression left, Expression right, Location? location)
```
### <sub>method</sub> isConstant
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/BinaryOperator.aspl:21:5
```aspl
method isConstant() returns bool
```

## <sub>class</sub> aspl.parser.ast.expressions.CastExpression
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/CastExpression.aspl:5:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/CastExpression.aspl:13:5
```aspl
method construct(Expression value, Type type, Location? location)
```
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/CastExpression.aspl:20:5
```aspl
method getType() returns Types
```

## <sub>class</sub> aspl.parser.ast.expressions.CatchExpression
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/CatchExpression.aspl:6:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/CatchExpression.aspl:20:5
```aspl
method construct(Expression expression, string? variable, list<Node> code, list<string> capturedVariables, bool standalone, Location? location)
```
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/CatchExpression.aspl:30:2
```aspl
method getType() returns Types
```

## <sub>class</sub> aspl.parser.ast.expressions.CheckEqualsExpression
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/CheckEqualsExpression.aspl:5:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/CheckEqualsExpression.aspl:8:5
```aspl
method construct(Expression left, Expression right, Location? location)
```
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/CheckEqualsExpression.aspl:13:5
```aspl
method getType() returns Types
```
### <sub>method</sub> getConstantValue
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/CheckEqualsExpression.aspl:18:5
```aspl
method getConstantValue() returns any
```

## <sub>class</sub> aspl.parser.ast.expressions.ClassInstantiateExpression
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/ClassInstantiateExpression.aspl:6:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/ClassInstantiateExpression.aspl:14:5
```aspl
method construct(Class c, list<Expression> arguments, Location? location)
```
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/ClassInstantiateExpression.aspl:21:5
```aspl
method getType() returns Types
```

## <sub>class</sub> aspl.parser.ast.expressions.DereferenceExpression
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/DereferenceExpression.aspl:5:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/DereferenceExpression.aspl:11:5
```aspl
method construct(Expression pointer, Location? location)
```
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/DereferenceExpression.aspl:17:5
```aspl
method getType() returns Types
```

## <sub>class</sub> aspl.parser.ast.expressions.EmbedFileExpression
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/EmbedFileExpression.aspl:5:1
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/EmbedFileExpression.aspl:16:2
```aspl
method getType() returns Types
```
### <sub>method</sub> isConstant
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/EmbedFileExpression.aspl:21:2
```aspl
method isConstant() returns bool
```
### <sub>method</sub> getConstantValue
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/EmbedFileExpression.aspl:26:2
```aspl
method getConstantValue() returns any
```

## <sub>class</sub> aspl.parser.ast.expressions.EnumFieldAccessExpression
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/EnumFieldAccessExpression.aspl:6:1
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/EnumFieldAccessExpression.aspl:17:2
```aspl
method getType() returns Types
```
### <sub>method</sub> isConstant
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/EnumFieldAccessExpression.aspl:22:2
```aspl
method isConstant() returns bool
```
### <sub>method</sub> getConstantValue
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/EnumFieldAccessExpression.aspl:27:2
```aspl
method getConstantValue() returns any
```

## <sub>class</sub> aspl.parser.ast.expressions.Expression
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/Expression.aspl:7:1
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/Expression.aspl:11:2
```aspl
method getType() returns Types
```
### <sub>method</sub> isConstant
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/Expression.aspl:14:2
```aspl
method isConstant() returns bool
```
### <sub>method</sub> getConstantValue
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/Expression.aspl:19:2
```aspl
method getConstantValue() returns any
```

## <sub>class</sub> aspl.parser.ast.expressions.FunctionCallExpression
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/FunctionCallExpression.aspl:6:1
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/FunctionCallExpression.aspl:26:2
```aspl
method getType() returns Types
```
### <sub>method</sub> isConstant
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/FunctionCallExpression.aspl:31:2
```aspl
method isConstant() returns bool
```

## <sub>class</sub> aspl.parser.ast.expressions.GreaterThanExpression
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/GreaterThanExpression.aspl:5:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/GreaterThanExpression.aspl:8:5
```aspl
method construct(Expression left, Expression right, Location? location)
```
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/GreaterThanExpression.aspl:13:5
```aspl
method getType() returns Types
```
### <sub>method</sub> getConstantValue
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/GreaterThanExpression.aspl:18:5
```aspl
method getConstantValue() returns any
```

## <sub>class</sub> aspl.parser.ast.expressions.GreaterThanOrEqualExpression
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/GreaterThanOrEqualExpression.aspl:5:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/GreaterThanOrEqualExpression.aspl:8:5
```aspl
method construct(Expression left, Expression right, Location? location)
```
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/GreaterThanOrEqualExpression.aspl:13:5
```aspl
method getType() returns Types
```
### <sub>method</sub> getConstantValue
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/GreaterThanOrEqualExpression.aspl:18:5
```aspl
method getConstantValue() returns any
```

## <sub>class</sub> aspl.parser.ast.expressions.ImplementationCallExpression
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/ImplementationCallExpression.aspl:6:1
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/ImplementationCallExpression.aspl:20:2
```aspl
method getType() returns Types
```
### <sub>method</sub> isConstant
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/ImplementationCallExpression.aspl:25:2
```aspl
method isConstant() returns bool
```

## <sub>class</sub> aspl.parser.ast.expressions.LessThanExpression
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/LessThanExpression.aspl:5:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/LessThanExpression.aspl:8:5
```aspl
method construct(Expression left, Expression right, Location? location)
```
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/LessThanExpression.aspl:13:5
```aspl
method getType() returns Types
```
### <sub>method</sub> getConstantValue
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/LessThanExpression.aspl:18:5
```aspl
method getConstantValue() returns any
```

## <sub>class</sub> aspl.parser.ast.expressions.LessThanOrEqualExpression
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/LessThanOrEqualExpression.aspl:5:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/LessThanOrEqualExpression.aspl:8:5
```aspl
method construct(Expression left, Expression right, Location? location)
```
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/LessThanOrEqualExpression.aspl:13:5
```aspl
method getType() returns Types
```
### <sub>method</sub> getConstantValue
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/LessThanOrEqualExpression.aspl:18:5
```aspl
method getConstantValue() returns any
```

## <sub>class</sub> aspl.parser.ast.expressions.ListAssignExpression
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/ListAssignExpression.aspl:5:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/ListAssignExpression.aspl:15:5
```aspl
method construct(Expression base, Expression index, Expression value, Location? location)
```
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/ListAssignExpression.aspl:23:5
```aspl
method getType() returns Types
```

## <sub>class</sub> aspl.parser.ast.expressions.ListIndexExpression
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/ListIndexExpression.aspl:5:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/ListIndexExpression.aspl:13:5
```aspl
method construct(Expression base, Expression index, Location? location)
```
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/ListIndexExpression.aspl:20:5
```aspl
method getType() returns Types
```
### <sub>method</sub> isConstant
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/ListIndexExpression.aspl:33:5
```aspl
method isConstant() returns bool
```
### <sub>method</sub> getConstantValue
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/ListIndexExpression.aspl:38:5
```aspl
method getConstantValue() returns any
```

## <sub>class</sub> aspl.parser.ast.expressions.MapAccessExpression
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/MapAccessExpression.aspl:5:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/MapAccessExpression.aspl:13:5
```aspl
method construct(Expression base, Expression key, Location? location)
```
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/MapAccessExpression.aspl:20:5
```aspl
method getType() returns Types
```
### <sub>method</sub> isConstant
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/MapAccessExpression.aspl:33:5
```aspl
method isConstant() returns bool
```
### <sub>method</sub> getConstantValue
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/MapAccessExpression.aspl:38:5
```aspl
method getConstantValue() returns any
```

## <sub>class</sub> aspl.parser.ast.expressions.MapAssignExpression
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/MapAssignExpression.aspl:5:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/MapAssignExpression.aspl:15:5
```aspl
method construct(Expression base, Expression key, Expression value, Location? location)
```
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/MapAssignExpression.aspl:23:5
```aspl
method getType() returns Types
```

## <sub>class</sub> aspl.parser.ast.expressions.MinusExpression
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/MinusExpression.aspl:5:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/MinusExpression.aspl:8:5
```aspl
method construct(Expression left, Expression right, Location? location)
```
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/MinusExpression.aspl:13:5
```aspl
method getType() returns Types
```
### <sub>method</sub> getConstantValue
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/MinusExpression.aspl:79:5
```aspl
method getConstantValue() returns any
```

## <sub>class</sub> aspl.parser.ast.expressions.ModuloExpression
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/ModuloExpression.aspl:5:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/ModuloExpression.aspl:8:5
```aspl
method construct(Expression left, Expression right, Location? location)
```
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/ModuloExpression.aspl:13:5
```aspl
method getType() returns Types
```
### <sub>method</sub> getConstantValue
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/ModuloExpression.aspl:79:5
```aspl
method getConstantValue() returns any
```

## <sub>class</sub> aspl.parser.ast.expressions.MultiplyExpression
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/MultiplyExpression.aspl:5:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/MultiplyExpression.aspl:8:5
```aspl
method construct(Expression left, Expression right, Location? location)
```
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/MultiplyExpression.aspl:13:5
```aspl
method getType() returns Types
```
### <sub>method</sub> getConstantValue
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/MultiplyExpression.aspl:79:5
```aspl
method getConstantValue() returns any
```

## <sub>class</sub> aspl.parser.ast.expressions.NegateExpression
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/NegateExpression.aspl:5:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/NegateExpression.aspl:8:5
```aspl
method construct(Expression expression, Location? location)
```
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/NegateExpression.aspl:13:5
```aspl
method getType() returns Types
```
### <sub>method</sub> getConstantValue
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/NegateExpression.aspl:18:5
```aspl
method getConstantValue() returns any
```

## <sub>class</sub> aspl.parser.ast.expressions.NonStaticPropertyAccessExpression
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/NonStaticPropertyAccessExpression.aspl:6:1
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/NonStaticPropertyAccessExpression.aspl:20:2
```aspl
method getType() returns Types
```
### <sub>method</sub> isConstant
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/NonStaticPropertyAccessExpression.aspl:25:2
```aspl
method isConstant() returns bool
```

## <sub>class</sub> aspl.parser.ast.expressions.NonStaticPropertyAssignExpression
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/NonStaticPropertyAssignExpression.aspl:7:1
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/NonStaticPropertyAssignExpression.aspl:24:2
```aspl
method getType() returns Types
```
### <sub>method</sub> isConstant
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/NonStaticPropertyAssignExpression.aspl:29:2
```aspl
method isConstant() returns bool
```

## <sub>class</sub> aspl.parser.ast.expressions.OfTypeExpression
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/OfTypeExpression.aspl:5:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/OfTypeExpression.aspl:13:5
```aspl
method construct(Expression expression, Type type, Location? location)
```
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/OfTypeExpression.aspl:20:5
```aspl
method getType() returns Types
```
### <sub>method</sub> isConstant
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/OfTypeExpression.aspl:25:5
```aspl
method isConstant() returns bool
```
### <sub>method</sub> getConstantValue
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/OfTypeExpression.aspl:34:5
```aspl
method getConstantValue() returns any
```

## <sub>class</sub> aspl.parser.ast.expressions.OrExpression
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/OrExpression.aspl:5:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/OrExpression.aspl:8:5
```aspl
method construct(Expression left, Expression right, Location? location)
```
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/OrExpression.aspl:13:5
```aspl
method getType() returns Types
```
### <sub>method</sub> getConstantValue
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/OrExpression.aspl:18:5
```aspl
method getConstantValue() returns any
```

## <sub>class</sub> aspl.parser.ast.expressions.ParentExpression
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/ParentExpression.aspl:6:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/ParentExpression.aspl:12:5
```aspl
method construct(Class c, Location? location)
```
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/ParentExpression.aspl:18:5
```aspl
method getType() returns Types
```
### <sub>method</sub> isConstant
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/ParentExpression.aspl:23:5
```aspl
method isConstant() returns bool
```

## <sub>class</sub> aspl.parser.ast.expressions.PlusExpression
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/PlusExpression.aspl:5:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/PlusExpression.aspl:8:5
```aspl
method construct(Expression left, Expression right, Location? location)
```
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/PlusExpression.aspl:13:5
```aspl
method getType() returns Types
```
### <sub>method</sub> getConstantValue
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/PlusExpression.aspl:85:5
```aspl
method getConstantValue() returns any
```

## <sub>class</sub> aspl.parser.ast.expressions.PropagateErrorExpression
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/PropagateErrorExpression.aspl:5:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/PropagateErrorExpression.aspl:11:5
```aspl
method construct(Expression expression, Location? location)
```
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/PropagateErrorExpression.aspl:17:5
```aspl
method getType() returns Types
```

## <sub>class</sub> aspl.parser.ast.expressions.ReferenceExpression
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/ReferenceExpression.aspl:5:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/ReferenceExpression.aspl:11:5
```aspl
method construct(Expression expression, Location? location)
```
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/ReferenceExpression.aspl:17:5
```aspl
method getType() returns Types
```

## <sub>class</sub> aspl.parser.ast.expressions.StaticMethodCallExpression
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/StaticMethodCallExpression.aspl:6:1
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/StaticMethodCallExpression.aspl:26:2
```aspl
method getType() returns Types
```
### <sub>method</sub> isConstant
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/StaticMethodCallExpression.aspl:31:2
```aspl
method isConstant() returns bool
```

## <sub>class</sub> aspl.parser.ast.expressions.StaticPropertyAccessExpression
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/StaticPropertyAccessExpression.aspl:6:1
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/StaticPropertyAccessExpression.aspl:20:2
```aspl
method getType() returns Types
```
### <sub>method</sub> isConstant
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/StaticPropertyAccessExpression.aspl:25:2
```aspl
method isConstant() returns bool
```

## <sub>class</sub> aspl.parser.ast.expressions.StaticPropertyAssignExpression
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/StaticPropertyAssignExpression.aspl:7:1
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/StaticPropertyAssignExpression.aspl:24:2
```aspl
method getType() returns Types
```
### <sub>method</sub> isConstant
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/StaticPropertyAssignExpression.aspl:29:2
```aspl
method isConstant() returns bool
```

## <sub>class</sub> aspl.parser.ast.expressions.StringIndexExpression
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/StringIndexExpression.aspl:5:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/StringIndexExpression.aspl:13:5
```aspl
method construct(Expression base, Expression index, Location location)
```
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/StringIndexExpression.aspl:20:5
```aspl
method getType() returns Types
```
### <sub>method</sub> isConstant
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/StringIndexExpression.aspl:25:5
```aspl
method isConstant() returns bool
```
### <sub>method</sub> getConstantValue
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/StringIndexExpression.aspl:30:5
```aspl
method getConstantValue() returns any
```

## <sub>class</sub> aspl.parser.ast.expressions.ThisExpression
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/ThisExpression.aspl:6:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/ThisExpression.aspl:12:5
```aspl
method construct(Class c, Location? location)
```
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/ThisExpression.aspl:18:5
```aspl
method getType() returns Types
```
### <sub>method</sub> isConstant
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/ThisExpression.aspl:23:5
```aspl
method isConstant() returns bool
```

## <sub>class</sub> aspl.parser.ast.expressions.UnaryOperator
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/UnaryOperator.aspl:6:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/UnaryOperator.aspl:12:5
```aspl
method construct(Expression expression, Location? location)
```
### <sub>method</sub> isConstant
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/UnaryOperator.aspl:18:5
```aspl
method isConstant() returns bool
```

## <sub>class</sub> aspl.parser.ast.expressions.VariableAccessExpression
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/VariableAccessExpression.aspl:7:1
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/VariableAccessExpression.aspl:18:2
```aspl
method getType() returns Types
```
### <sub>method</sub> isConstant
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/VariableAccessExpression.aspl:23:2
```aspl
method isConstant() returns bool
```

## <sub>class</sub> aspl.parser.ast.expressions.VariableAssignExpression
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/VariableAssignExpression.aspl:7:1
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/VariableAssignExpression.aspl:21:2
```aspl
method getType() returns Types
```
### <sub>method</sub> isConstant
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/VariableAssignExpression.aspl:26:2
```aspl
method isConstant() returns bool
```

## <sub>class</sub> aspl.parser.ast.expressions.VariableDeclareExpression
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/VariableDeclareExpression.aspl:7:1
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/VariableDeclareExpression.aspl:21:2
```aspl
method getType() returns Types
```
### <sub>method</sub> isConstant
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/VariableDeclareExpression.aspl:26:2
```aspl
method isConstant() returns bool
```

## <sub>class</sub> aspl.parser.ast.expressions.XorExpression
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/XorExpression.aspl:5:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/XorExpression.aspl:8:5
```aspl
method construct(Expression left, Expression right, Location? location)
```
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/XorExpression.aspl:13:5
```aspl
method getType() returns Types
```
### <sub>method</sub> getConstantValue
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/expressions/XorExpression.aspl:18:5
```aspl
method getConstantValue() returns any
```

## <sub>class</sub> aspl.parser.ast.literals.BooleanLiteral
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/literals/BooleanLiteral.aspl:5:1
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/literals/BooleanLiteral.aspl:16:2
```aspl
method getType() returns Types
```
### <sub>method</sub> isConstant
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/literals/BooleanLiteral.aspl:21:2
```aspl
method isConstant() returns bool
```
### <sub>method</sub> getConstantValue
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/literals/BooleanLiteral.aspl:26:2
```aspl
method getConstantValue() returns any
```

## <sub>class</sub> aspl.parser.ast.literals.DoubleLiteral
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/literals/DoubleLiteral.aspl:5:1
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/literals/DoubleLiteral.aspl:16:2
```aspl
method getType() returns Types
```
### <sub>method</sub> isConstant
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/literals/DoubleLiteral.aspl:21:2
```aspl
method isConstant() returns bool
```
### <sub>method</sub> getConstantValue
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/literals/DoubleLiteral.aspl:26:2
```aspl
method getConstantValue() returns any
```

## <sub>class</sub> aspl.parser.ast.literals.FloatLiteral
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/literals/FloatLiteral.aspl:5:1
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/literals/FloatLiteral.aspl:16:2
```aspl
method getType() returns Types
```
### <sub>method</sub> isConstant
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/literals/FloatLiteral.aspl:21:2
```aspl
method isConstant() returns bool
```
### <sub>method</sub> getConstantValue
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/literals/FloatLiteral.aspl:26:2
```aspl
method getConstantValue() returns any
```

## <sub>class</sub> aspl.parser.ast.literals.IntegerLiteral
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/literals/IntegerLiteral.aspl:5:1
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/literals/IntegerLiteral.aspl:16:2
```aspl
method getType() returns Types
```
### <sub>method</sub> isConstant
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/literals/IntegerLiteral.aspl:21:2
```aspl
method isConstant() returns bool
```
### <sub>method</sub> getConstantValue
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/literals/IntegerLiteral.aspl:26:2
```aspl
method getConstantValue() returns any
```

## <sub>class</sub> aspl.parser.ast.literals.ListLiteral
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/literals/ListLiteral.aspl:6:1
### <sub>property</sub> type
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/literals/ListLiteral.aspl:9:2
```aspl
property Types type
```
### <sub>property</sub> value
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/literals/ListLiteral.aspl:11:2
```aspl
property list<Expression> value
```
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/literals/ListLiteral.aspl:20:2
```aspl
method getType() returns Types
```
### <sub>method</sub> isConstant
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/literals/ListLiteral.aspl:25:2
```aspl
method isConstant() returns bool
```
### <sub>method</sub> getConstantValue
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/literals/ListLiteral.aspl:35:2
```aspl
method getConstantValue() returns any
```

## <sub>class</sub> aspl.parser.ast.literals.Literal
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/literals/Literal.aspl:5:1

## <sub>class</sub> aspl.parser.ast.literals.LongLiteral
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/literals/LongLiteral.aspl:5:1
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/literals/LongLiteral.aspl:16:2
```aspl
method getType() returns Types
```
### <sub>method</sub> isConstant
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/literals/LongLiteral.aspl:21:2
```aspl
method isConstant() returns bool
```
### <sub>method</sub> getConstantValue
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/literals/LongLiteral.aspl:26:2
```aspl
method getConstantValue() returns any
```

## <sub>class</sub> aspl.parser.ast.literals.MapLiteral
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/literals/MapLiteral.aspl:5:1
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/literals/MapLiteral.aspl:22:2
```aspl
method getType() returns Types
```
### <sub>method</sub> isConstant
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/literals/MapLiteral.aspl:27:2
```aspl
method isConstant() returns bool
```
### <sub>method</sub> getConstantValue
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/literals/MapLiteral.aspl:40:2
```aspl
method getConstantValue() returns any
```

## <sub>class</sub> aspl.parser.ast.literals.NullLiteral
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/literals/NullLiteral.aspl:5:1
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/literals/NullLiteral.aspl:12:2
```aspl
method getType() returns Types
```
### <sub>method</sub> isConstant
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/literals/NullLiteral.aspl:17:2
```aspl
method isConstant() returns bool
```
### <sub>method</sub> getConstantValue
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/literals/NullLiteral.aspl:22:2
```aspl
method getConstantValue() returns any
```

## <sub>class</sub> aspl.parser.ast.literals.StringLiteral
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/literals/StringLiteral.aspl:5:1
### <sub>method</sub> getType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/literals/StringLiteral.aspl:19:2
```aspl
method getType() returns Types
```
### <sub>method</sub> isConstant
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/literals/StringLiteral.aspl:24:2
```aspl
method isConstant() returns bool
```
### <sub>method</sub> getConstantValue
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/literals/StringLiteral.aspl:29:2
```aspl
method getConstantValue() returns any
```

## <sub>class</sub> aspl.parser.ast.statements.AssertStatement
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/statements/AssertStatement.aspl:6:1

## <sub>class</sub> aspl.parser.ast.statements.BlockStatement
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/statements/BlockStatement.aspl:6:1

## <sub>class</sub> aspl.parser.ast.statements.BreakStatement
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/statements/BreakStatement.aspl:6:1

## <sub>class</sub> aspl.parser.ast.statements.ClassDeclareStatement
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/statements/ClassDeclareStatement.aspl:7:1

## <sub>class</sub> aspl.parser.ast.statements.ContinueStatement
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/statements/ContinueStatement.aspl:6:1

## <sub>class</sub> aspl.parser.ast.statements.EnumDeclareStatement
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/statements/EnumDeclareStatement.aspl:7:1

## <sub>class</sub> aspl.parser.ast.statements.EscapeStatement
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/statements/EscapeStatement.aspl:6:1

## <sub>class</sub> aspl.parser.ast.statements.FallbackStatement
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/statements/FallbackStatement.aspl:6:1

## <sub>class</sub> aspl.parser.ast.statements.ForeachStatement
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/statements/ForeachStatement.aspl:6:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/statements/ForeachStatement.aspl:18:5
```aspl
method construct(Expression collection, string? key, string? value, list<Node> code, Location? location)
```

## <sub>class</sub> aspl.parser.ast.statements.FunctionDeclareStatement
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/statements/FunctionDeclareStatement.aspl:7:1

## <sub>class</sub> aspl.parser.ast.statements.IfElseIfStatement
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/statements/IfElseIfStatement.aspl:6:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/statements/IfElseIfStatement.aspl:16:5
```aspl
method construct(Expression condition, list<Node> ifCode, IfStatement|IfElseIfStatement|IfElseStatement elseIf, Location? location)
```

## <sub>class</sub> aspl.parser.ast.statements.IfElseStatement
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/statements/IfElseStatement.aspl:6:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/statements/IfElseStatement.aspl:16:5
```aspl
method construct(Expression condition, list<Node> ifCode, list<Node> elseCode, Location? location)
```

## <sub>class</sub> aspl.parser.ast.statements.IfStatement
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/statements/IfStatement.aspl:6:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/statements/IfStatement.aspl:14:5
```aspl
method construct(Expression condition, list<Node> code, Location? location)
```

## <sub>class</sub> aspl.parser.ast.statements.IncludeFileStatement
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/statements/IncludeFileStatement.aspl:5:1

## <sub>class</sub> aspl.parser.ast.statements.LinkLibraryStatement
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/statements/LinkLibraryStatement.aspl:5:1

## <sub>class</sub> aspl.parser.ast.statements.MethodDeclareStatement
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/statements/MethodDeclareStatement.aspl:7:1

## <sub>class</sub> aspl.parser.ast.statements.NopStatement
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/statements/NopStatement.aspl:4:1

## <sub>class</sub> aspl.parser.ast.statements.PropertyDeclareStatement
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/statements/PropertyDeclareStatement.aspl:7:1

## <sub>class</sub> aspl.parser.ast.statements.RepeatStatement
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/statements/RepeatStatement.aspl:6:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/statements/RepeatStatement.aspl:18:5
```aspl
method construct(Expression iterations, string? variable, int start, list<Node> code, Location? location)
```

## <sub>class</sub> aspl.parser.ast.statements.ReturnStatement
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/statements/ReturnStatement.aspl:10:1

## <sub>class</sub> aspl.parser.ast.statements.Statement
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/statements/Statement.aspl:6:1

## <sub>class</sub> aspl.parser.ast.statements.ThrowStatement
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/statements/ThrowStatement.aspl:6:1

## <sub>class</sub> aspl.parser.ast.statements.WhileStatement
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/statements/WhileStatement.aspl:6:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/ast/statements/WhileStatement.aspl:14:5
```aspl
method construct(Expression condition, list<Node> code, Location? location)
```

## <sub>class</sub> aspl.parser.attributes.Attribute
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/attributes/Attribute.aspl:5:1
### <sub>property</sub> minimumParameterCount
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/attributes/Attribute.aspl:15:5
```aspl
property int minimumParameterCount
```
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/attributes/Attribute.aspl:33:5
```aspl
method construct(string identifier, list<Parameter> parameters, AttributeUsage usage, list<string> conflicting)
```
### <sub>method</sub> canPair
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/attributes/Attribute.aspl:41:5
```aspl
method canPair(Attribute other) returns bool
```
### <sub>method</sub> init
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/attributes/Attribute.aspl:47:5
```aspl
method init()
```
### <sub>method</sub> register
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/attributes/Attribute.aspl:62:5
```aspl
method register(Attribute attribute)
```
### <sub>method</sub> exists
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/attributes/Attribute.aspl:68:5
```aspl
method exists(string identifier) returns bool
```
### <sub>method</sub> get
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/attributes/Attribute.aspl:74:5
```aspl
method get(string identifier) returns Attribute
```

## <sub>class</sub> aspl.parser.attributes.AttributeInstance
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/attributes/AttributeInstance.aspl:6:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/attributes/AttributeInstance.aspl:18:5
```aspl
method construct(Attribute attribute, list<Expression> arguments, Location? location, list<Token> comments)
```

## <sub>class</sub> aspl.parser.callbacks.Callback
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/callbacks/Callback.aspl:6:1
### <sub>property</sub> code
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/callbacks/Callback.aspl:15:5
```aspl
property list<Node>? code
```
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/callbacks/Callback.aspl:22:5
```aspl
method construct(Type type, list<Parameter> parameters, Types returnTypes, list<Node>? code, ScopeBundle creationScope, Location location)
```

## <sub>class</sub> aspl.parser.classes.Class
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/classes/Class.aspl:7:1
### <sub>property</sub> classes
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/classes/Class.aspl:12:5
```aspl
property map<string, Class> classes
```
### <sub>property</sub> parents
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/classes/Class.aspl:17:5
```aspl
property list<Type>? parents
```
### <sub>property</sub> code
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/classes/Class.aspl:29:5
```aspl
property list<Node>? code
```
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/classes/Class.aspl:36:5
```aspl
method construct(Type type, list<Type>? parents, list<AttributeInstance>? attributes, list<Node>? code, Module module, Location location)
```

## <sub>class</sub> aspl.parser.enums.Enum
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/enums/Enum.aspl:6:1
### <sub>property</sub> enums
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/enums/Enum.aspl:11:5
```aspl
property map<string, Enum> enums
```
### <sub>property</sub> fields
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/enums/Enum.aspl:22:5
```aspl
property map<string, EnumField>? fields
```
### <sub>property</sub> location
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/enums/Enum.aspl:26:5
```aspl
property Location location
```
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/enums/Enum.aspl:29:5
```aspl
method construct(Type type, list<AttributeInstance>? attributes, map<string, EnumField>? fields, Module module, Location location)
```

## <sub>class</sub> aspl.parser.enums.EnumField
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/enums/EnumField.aspl:5:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/enums/EnumField.aspl:19:5
```aspl
method construct(Enum e, string name, int? value, list<AttributeInstance> attributes, Location location)
```

## <sub>class</sub> aspl.parser.functions.CustomFunction
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/functions/CustomFunction.aspl:7:1
### <sub>property</sub> code
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/functions/CustomFunction.aspl:10:5
```aspl
property list<Node>? code
```
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/functions/CustomFunction.aspl:19:5
```aspl
method construct(string identifier, list<Parameter> parameters, Types returnTypes, list<AttributeInstance> attributes, list<Node>? code, Module module, Location? location, Location? headerEndLocation)
```

## <sub>class</sub> aspl.parser.functions.Function
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/functions/Function.aspl:8:1
### <sub>property</sub> functions
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/functions/Function.aspl:13:5
```aspl
property map<string, Function> functions
```
### <sub>property</sub> parameters
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/functions/Function.aspl:18:5
```aspl
property list<Parameter> parameters
```
### <sub>property</sub> minimumParameterCount
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/functions/Function.aspl:20:5
```aspl
property int minimumParameterCount
```
### <sub>property</sub> returnTypes
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/functions/Function.aspl:33:5
```aspl
property Types returnTypes
```
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/functions/Function.aspl:46:5
```aspl
method construct(string identifier, list<Parameter> parameters, Types returnTypes, list<AttributeInstance> attributes)
```
### <sub>method</sub> init
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/functions/Function.aspl:55:5
```aspl
method init()
```
### <sub>method</sub> register
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/functions/Function.aspl:65:5
```aspl
method register(Location? location)
```
### <sub>method</sub> exists
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/functions/Function.aspl:76:5
```aspl
method exists(string identifier) returns bool
```
### <sub>method</sub> get
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/functions/Function.aspl:82:5
```aspl
method get(string identifier) returns Function
```

## <sub>class</sub> aspl.parser.functions.InternalFunction
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/functions/InternalFunction.aspl:5:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/functions/InternalFunction.aspl:8:5
```aspl
method construct(string identifier, list<Parameter> parameters, Types returnTypes, list<AttributeInstance> attributes)
```

## <sub>class</sub> aspl.parser.lexer.Lexer
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/lexer/Lexer.aspl:12:1
### <sub>property</sub> cache
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/lexer/Lexer.aspl:17:2
```aspl
property map<string, TokenList> cache
```
### <sub>property</sub> column
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/lexer/Lexer.aspl:30:2
```aspl
property int column
```
### <sub>method</sub> lex
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/lexer/Lexer.aspl:45:2
```aspl
method lex() returns list<Token>
```
### <sub>method</sub> forward
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/lexer/Lexer.aspl:64:2
```aspl
method forward(int amount)
```
### <sub>method</sub> newline
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/lexer/Lexer.aspl:70:2
```aspl
method newline()
```
### <sub>method</sub> lexToken
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/lexer/Lexer.aspl:76:2
```aspl
method lexToken() returns Token?
```

## <sub>class</sub> aspl.parser.lexer.RegexTokenPattern
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/lexer/RegexTokenPattern.aspl:2:1

## <sub>class</sub> aspl.parser.lexer.RegularTokenPattern
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/lexer/RegularTokenPattern.aspl:2:1

## <sub>class</sub> aspl.parser.lexer.StringToken
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/lexer/StringToken.aspl:4:1

## <sub>class</sub> aspl.parser.lexer.Token
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/lexer/Token.aspl:4:1
### <sub>property</sub> comments
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/lexer/Token.aspl:67:2
```aspl
property list<Token>? comments
```

## <sub>class</sub> aspl.parser.lexer.TokenPattern
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/lexer/TokenPattern.aspl:3:1

## <sub>class</sub> aspl.parser.methods.CustomMethod
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/methods/CustomMethod.aspl:6:1
### <sub>property</sub> code
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/methods/CustomMethod.aspl:9:5
```aspl
property list<Node>? code
```
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/methods/CustomMethod.aspl:16:5
```aspl
method construct(Type type, string name, list<Parameter> parameters, Types returnTypes, list<AttributeInstance> attributes, list<Node>? code, Location? location, Location? headerEndLocation)
```
### <sub>method</sub> withType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/methods/CustomMethod.aspl:38:5
```aspl
method withType(Type type) returns Method
```

## <sub>class</sub> aspl.parser.methods.InternalMethod
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/methods/InternalMethod.aspl:5:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/methods/InternalMethod.aspl:8:5
```aspl
method construct(Type type, string name, list<Parameter> parameters, Types returnTypes, list<AttributeInstance> attributes)
```
### <sub>method</sub> withType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/methods/InternalMethod.aspl:18:5
```aspl
method withType(Type type) returns Method
```

## <sub>class</sub> aspl.parser.methods.Method
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/methods/Method.aspl:9:1
### <sub>property</sub> methods
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/methods/Method.aspl:14:5
```aspl
property map<string, map<string, Method>> methods
```
### <sub>property</sub> parameters
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/methods/Method.aspl:21:5
```aspl
property list<Parameter> parameters
```
### <sub>property</sub> minimumParameterCount
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/methods/Method.aspl:23:5
```aspl
property int minimumParameterCount
```
### <sub>property</sub> returnTypes
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/methods/Method.aspl:36:5
```aspl
property Types returnTypes
```
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/methods/Method.aspl:53:5
```aspl
method construct(Type type, string name, list<Parameter> parameters, Types returnTypes, list<AttributeInstance> attributes)
```
### <sub>method</sub> init
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/methods/Method.aspl:63:5
```aspl
method init()
```
### <sub>method</sub> register
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/methods/Method.aspl:99:5
```aspl
method register(Location? location)
```
### <sub>method</sub> exists
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/methods/Method.aspl:115:5
```aspl
method exists(Type type, string name, bool checkParents = true) returns bool
```
### <sub>method</sub> get
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/methods/Method.aspl:138:5
```aspl
method get(Type type, string name) returns Method
```
### <sub>method</sub> getAllFor
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/methods/Method.aspl:161:5
```aspl
method getAllFor(Type type) returns list<Method>
```
### <sub>method</sub> withType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/methods/Method.aspl:193:5
```aspl
method withType(Type type) returns Method

    metho
```
### <sub>method</sub> createMethodFromAny
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/methods/Method.aspl:201:5
```aspl
method createMethodFromAny(Type type, string name) returns Method
```

## <sub>class</sub> aspl.parser.precedence.PrecedenceUtils
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/precedence/PrecedenceUtils.aspl:5:1
### <sub>method</sub> GetTokenPrecendenceLevel
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/precedence/PrecedenceUtils.aspl:9:5
```aspl
method GetTokenPrecendenceLevel(Token token) returns PrecedenceLevel
```

## <sub>class</sub> aspl.parser.properties.CustomNormalProperty
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/properties/CustomNormalProperty.aspl:6:1
### <sub>property</sub> defaultValue
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/properties/CustomNormalProperty.aspl:9:5
```aspl
property Expression? defaultValue
```
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/properties/CustomNormalProperty.aspl:16:5
```aspl
method construct(Type type, string name, Types types, list<AttributeInstance> attributes, Expression? defaultValue, Location location, Location headerEndLocation)
```
### <sub>method</sub> withType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/properties/CustomNormalProperty.aspl:38:5
```aspl
method withType(Type type) returns Property
```

## <sub>class</sub> aspl.parser.properties.CustomReactiveProperty
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/properties/CustomReactiveProperty.aspl:6:1
### <sub>property</sub> getCode
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/properties/CustomReactiveProperty.aspl:9:5
```aspl
property list<Node>? getCode
```
### <sub>property</sub> setCode
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/properties/CustomReactiveProperty.aspl:11:5
```aspl
property list<Node>? setCode
```
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/properties/CustomReactiveProperty.aspl:18:5
```aspl
method construct(Type type, string name, Types types, list<AttributeInstance> attributes, list<Node>? getCode, list<Node>? setCode, Location location, Location headerEndLocation)
```
### <sub>method</sub> withType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/properties/CustomReactiveProperty.aspl:44:5
```aspl
method withType(Type type) returns Property
```

## <sub>class</sub> aspl.parser.properties.InternalProperty
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/properties/InternalProperty.aspl:5:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/properties/InternalProperty.aspl:8:5
```aspl
method construct(Type type, string name, Types types, list<AttributeInstance> attributes)
```
### <sub>method</sub> withType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/properties/InternalProperty.aspl:17:5
```aspl
method withType(Type type) returns Property
```

## <sub>class</sub> aspl.parser.properties.Property
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/properties/Property.aspl:8:1
### <sub>property</sub> properties
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/properties/Property.aspl:13:5
```aspl
property map<string, map<string, Property>> properties
```
### <sub>property</sub> types
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/properties/Property.aspl:20:5
```aspl
property Types types
```
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/properties/Property.aspl:37:5
```aspl
method construct(Type type, string name, Types types, list<AttributeInstance> attributes)
```
### <sub>method</sub> init
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/properties/Property.aspl:46:5
```aspl
method init()
```
### <sub>method</sub> register
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/properties/Property.aspl:55:5
```aspl
method register(Location? location)
```
### <sub>method</sub> exists
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/properties/Property.aspl:71:5
```aspl
method exists(Type type, string name, bool checkParents = true) returns bool
```
### <sub>method</sub> get
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/properties/Property.aspl:94:5
```aspl
method get(Type type, string name) returns Property
```
### <sub>method</sub> getAllFor
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/properties/Property.aspl:117:5
```aspl
method getAllFor(Type type) returns list<Property>
```
### <sub>method</sub> withType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/properties/Property.aspl:151:5
```aspl
method withType(Type type) returns Property

    metho
```
### <sub>method</sub> createPropertyFromAny
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/properties/Property.aspl:159:5
```aspl
method createPropertyFromAny(Type type, string name) returns Property
```

## <sub>class</sub> aspl.parser.properties.ReactivePropertyCallback
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/properties/ReactivePropertyCallback.aspl:5:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/properties/ReactivePropertyCallback.aspl:13:5
```aspl
method construct(Property p, Types returnTypes)
```

## <sub>class</sub> aspl.parser.utils.AttributeUtils
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/AttributeUtils.aspl:14:1
### <sub>method</sub> parseAttributesIfAny
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/AttributeUtils.aspl:18:5
```aspl
method parseAttributesIfAny(Parser parser, Token token, TokenList tokens) returns bool
```

## <sub>class</sub> aspl.parser.utils.ClassUtils
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/ClassUtils.aspl:8:1
### <sub>property</sub> classesWithParsers
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/ClassUtils.aspl:13:5
```aspl
property map<string, Parser> classesWithParsers
```
### <sub>property</sub> parentHandledTypes
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/ClassUtils.aspl:17:5
```aspl
property list<string> parentHandledTypes
```
### <sub>method</sub> handleParents
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/ClassUtils.aspl:21:5
```aspl
method handleParents(Parser parser, Class c)
```
### <sub>method</sub> throwOnInvalidInheritance
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/ClassUtils.aspl:42:5
```aspl
method throwOnInvalidInheritance(Class c, list<string> children, Location location)
```
### <sub>method</sub> getAllParentsRecursively
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/ClassUtils.aspl:73:5
```aspl
method getAllParentsRecursively(Class c) returns list<Type>
```
### <sub>method</sub> getAllAbstractMethods
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/ClassUtils.aspl:86:5
```aspl
method getAllAbstractMethods(Class c) returns list<string>
```
### <sub>method</sub> isParent
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/ClassUtils.aspl:113:5
```aspl
method isParent(Class child, Class parent) returns bool
```

## <sub>class</sub> aspl.parser.utils.DirectoryUtils
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/DirectoryUtils.aspl:5:1
### <sub>method</sub> index
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/DirectoryUtils.aspl:9:5
```aspl
method index(string dir) returns list<string>
```

## <sub>class</sub> aspl.parser.utils.ErrorUtils
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/ErrorUtils.aspl:9:1
### <sub>property</sub> hasCompilationErrors
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/ErrorUtils.aspl:14:5
```aspl
property bool hasCompilationErrors
```
### <sub>method</sub> canExpressionThrow
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/ErrorUtils.aspl:18:5
```aspl
method canExpressionThrow(Expression expression) returns bool
```
### <sub>method</sub> canCallableThrow
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/ErrorUtils.aspl:32:5
```aspl
method canCallableThrow(Function|Method|Callback|ReactivePropertyCallback? func) returns bool
```

## <sub>class</sub> aspl.parser.utils.GenericsUtils
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/GenericsUtils.aspl:5:1
### <sub>property</sub> typePlaceholders
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/GenericsUtils.aspl:10:5
```aspl
property map<string, list<string>> typePlaceholders
```
### <sub>property</sub> functionPlaceholders
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/GenericsUtils.aspl:14:5
```aspl
property map<string, list<string>> functionPlaceholders
```
### <sub>method</sub> init
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/GenericsUtils.aspl:18:5
```aspl
method init()
```

## <sub>class</sub> aspl.parser.utils.IdentifierResult
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/IdentifierResult.aspl:2:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/IdentifierResult.aspl:12:5
```aspl
method construct(string identifier, int tokenCount, Location? location)
```

## <sub>class</sub> aspl.parser.utils.IdentifierUtils
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/IdentifierUtils.aspl:6:1
### <sub>method</sub> handleTypeIdentifier
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/IdentifierUtils.aspl:14:5
```aspl
method handleTypeIdentifier(string identifier, Parser? parser = null) returns string
```
### <sub>method</sub> handleFunctionIdentifier
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/IdentifierUtils.aspl:76:5
```aspl
method handleFunctionIdentifier(Parser parser, string identifier) returns string
```
### <sub>method</sub> lowerNamespaceInIdentifier
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/IdentifierUtils.aspl:94:5
```aspl
method lowerNamespaceInIdentifier(string identifier) returns string
```
### <sub>method</sub> relativeToAbsoluteIdentifier
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/IdentifierUtils.aspl:113:5
```aspl
method relativeToAbsoluteIdentifier(Parser parser, string identifier) returns string
```

## <sub>class</sub> aspl.parser.utils.ImplementationCallUtils
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/ImplementationCallUtils.aspl:3:1
### <sub>property</sub> usedImplementationCalls
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/ImplementationCallUtils.aspl:8:5
```aspl
property map<string, int> usedImplementationCalls
```

## <sub>class</sub> aspl.parser.utils.ImportTable
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/ImportTable.aspl:4:1
### <sub>method</sub> importNamespace
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/ImportTable.aspl:9:5
```aspl
method importNamespace(string namespace)
```
### <sub>method</sub> canResolveAbbreviation
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/ImportTable.aspl:14:5
```aspl
method canResolveAbbreviation(Parser parser, string abbreviation) returns bool
```
### <sub>method</sub> resolveAbbreviation
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/ImportTable.aspl:24:5
```aspl
method resolveAbbreviation(Parser parser, string abbreviation) returns Type
```

## <sub>class</sub> aspl.parser.utils.Location
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/Location.aspl:2:1

## <sub>class</sub> aspl.parser.utils.ModuleUtils
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/ModuleUtils.aspl:6:1
### <sub>method</sub> getModulePath
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/ModuleUtils.aspl:10:5
```aspl
method getModulePath(string module) returns string
```
### <sub>method</sub> isFilePartOfStdlib
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/ModuleUtils.aspl:23:5
```aspl
method isFilePartOfStdlib(string file) returns boolean
```

## <sub>class</sub> aspl.parser.utils.Pair
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/Pair.aspl:4:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/Pair.aspl:12:5
```aspl
method construct(Expression k, Expression v)
```

## <sub>class</sub> aspl.parser.utils.Parameter
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/Parameter.aspl:5:1
### <sub>property</sub> optional
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/Parameter.aspl:14:5
```aspl
property bool optional
```
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/Parameter.aspl:23:5
```aspl
method construct(string name, Types types, Expression? defaultValue = null, Location? location = null)
```

## <sub>class</sub> aspl.parser.utils.ReturnTypeUtils
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/ReturnTypeUtils.aspl:8:1
### <sub>method</sub> getReturnTypes
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/ReturnTypeUtils.aspl:12:5
```aspl
method getReturnTypes(Function|Method|Callback|ReactivePropertyCallback? func) returns Types
```

## <sub>class</sub> aspl.parser.utils.TokenList
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/TokenList.aspl:4:1
### <sub>property</sub> length
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/TokenList.aspl:11:2
```aspl
property int length
```
### <sub>method</sub> peek
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/TokenList.aspl:22:2
```aspl
method peek(int offset = 0) returns Token
```
### <sub>method</sub> shift
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/TokenList.aspl:27:2
```aspl
method shift(int amount = 1)
```
### <sub>method</sub> next
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/TokenList.aspl:32:2
```aspl
method next(int offset = 0) returns Token
```
### <sub>method</sub> empty
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/TokenList.aspl:39:2
```aspl
method empty() returns bool
```
### <sub>method</sub> in
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/TokenList.aspl:44:2
```aspl
method in(int offset) returns TokenList
```
### <sub>method</sub> clone
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/TokenList.aspl:51:2
```aspl
method clone() returns TokenList
```
### <sub>method</sub> set
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/TokenList.aspl:56:2
```aspl
method set(TokenList other)
```

## <sub>class</sub> aspl.parser.utils.TokenUtils
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/TokenUtils.aspl:5:1
### <sub>method</sub> skipTokensTillSeparator
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/TokenUtils.aspl:9:5
```aspl
method skipTokensTillSeparator(TokenList tokens)
```

## <sub>class</sub> aspl.parser.utils.Type
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/Type.aspl:9:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/Type.aspl:22:5
```aspl
method construct(string identifier)
```
### <sub>method</sub> existsByName
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/Type.aspl:28:5
```aspl
method existsByName(Parser? parser, string identifier) returns bool
```
### <sub>method</sub> fromString
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/Type.aspl:65:5
```aspl
method fromString(string identifier, Parser? parser = null, Location? location = null) returns Type
```
### <sub>method</sub> matches
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/Type.aspl:191:5
```aspl
method matches(Types expected, Types got, bool ignoreGenerics = false) returns bool
```
### <sub>method</sub> getGenericTypeIdentifier
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/Type.aspl:223:5
```aspl
method getGenericTypeIdentifier(string identifier) returns string
```
### <sub>method</sub> getGenericTypesIdentifiers
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/Type.aspl:229:5
```aspl
method getGenericTypesIdentifiers(string identifier) returns list<string>
```
### <sub>method</sub> getGenericTypes
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/Type.aspl:262:5
```aspl
method getGenericTypes(string identifier) returns list<Types>
```
### <sub>method</sub> toString
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/Type.aspl:272:5
```aspl
method toString() returns string
```
### <sub>method</sub> getDefaultValue
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/Type.aspl:277:5
```aspl
method getDefaultValue(Location location) returns Literal?
```
### <sub>method</sub> canCast
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/Type.aspl:315:5
```aspl
method canCast(Type target) returns bool
```
### <sub>method</sub> isPointer
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/Type.aspl:358:5
```aspl
method isPointer() returns bool
```
### <sub>method</sub> getPointer
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/Type.aspl:363:5
```aspl
method getPointer() returns self
```
### <sub>method</sub> getReferenced
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/Type.aspl:368:5
```aspl
method getReferenced() returns self
```
### <sub>method</sub> isPrimitive
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/Type.aspl:373:5
```aspl
method isPrimitive() returns bool
```
### <sub>method</sub> containsPlaceHolder
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/Type.aspl:379:5
```aspl
method containsPlaceHolder(Type type, string placeholder) returns bool
```
### <sub>method</sub> replacePlaceHolder
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/Type.aspl:401:5
```aspl
method replacePlaceHolder(Type type, string placeholder, Type replacement) returns Type
```
### <sub>method</sub> isPublic
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/Type.aspl:424:5
```aspl
method isPublic(Type type) returns bool
```

## <sub>class</sub> aspl.parser.utils.Types
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/Types.aspl:4:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/Types.aspl:10:5
```aspl
method construct(list<Type> types)
```
### <sub>method</sub> existsByName
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/Types.aspl:16:5
```aspl
method existsByName(Parser parser, string identifier) returns bool
```
### <sub>method</sub> fromString
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/Types.aspl:27:5
```aspl
method fromString(string identifier, Parser? parser = null) returns Types
```
### <sub>method</sub> toString
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/Types.aspl:36:5
```aspl
method toString() returns string
```
### <sub>method</sub> toType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/Types.aspl:48:5
```aspl
method toType() returns Type
```
### <sub>method</sub> getPartsOfMultiType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/Types.aspl:54:5
```aspl
method getPartsOfMultiType(string type) returns list<string>
```
### <sub>method</sub> canCast
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/Types.aspl:85:5
```aspl
method canCast(Type target) returns bool
```
### <sub>method</sub> isPointer
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/Types.aspl:95:5
```aspl
method isPointer() returns bool
```
### <sub>method</sub> getPointer
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/Types.aspl:100:5
```aspl
method getPointer() returns Type
```
### <sub>method</sub> getReferenced
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/Types.aspl:105:5
```aspl
method getReferenced() returns self
```
### <sub>method</sub> withoutType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/Types.aspl:114:5
```aspl
method withoutType(Type type) returns self
```

## <sub>class</sub> aspl.parser.variables.Scope
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/variables/Scope.aspl:8:1
### <sub>property</sub> variables
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/variables/Scope.aspl:15:5
```aspl
property map<string, Variable> variables
```
### <sub>property</sub> capturedVariables
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/variables/Scope.aspl:19:5
```aspl
property list<string> capturedVariables
```
### <sub>method</sub> pushBundle
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/variables/Scope.aspl:27:5
```aspl
method pushBundle(Function|Method|Callback|ReactivePropertyCallback? func)
```
### <sub>method</sub> push
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/variables/Scope.aspl:33:5
```aspl
method push(bool closure = false)
```
### <sub>method</sub> pop
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/variables/Scope.aspl:39:5
```aspl
method pop()
```
### <sub>method</sub> popBundle
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/variables/Scope.aspl:45:5
```aspl
method popBundle()
```
### <sub>method</sub> getCurrentBundle
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/variables/Scope.aspl:51:5
```aspl
method getCurrentBundle() returns ScopeBundle
```
### <sub>method</sub> getCurrent
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/variables/Scope.aspl:57:5
```aspl
method getCurrent() returns self
```
### <sub>method</sub> passCapturedVariables
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/variables/Scope.aspl:63:5
```aspl
method passCapturedVariables(list<string> capturedVariables)
```

## <sub>class</sub> aspl.parser.variables.ScopeBundle
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/variables/ScopeBundle.aspl:7:1
### <sub>property</sub> func
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/variables/ScopeBundle.aspl:12:5
```aspl
property Function|Method|Callback|ReactivePropertyCallback? func
```
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/variables/ScopeBundle.aspl:15:5
```aspl
method construct(Function|Method|Callback|ReactivePropertyCallback? func)
```

## <sub>class</sub> aspl.parser.variables.Variable
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/variables/Variable.aspl:5:1
### <sub>method</sub> construct
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/variables/Variable.aspl:13:5
```aspl
method construct(string identifier, Types types)
```
### <sub>method</sub> register
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/variables/Variable.aspl:20:5
```aspl
method register(string identifier, Types types, Location? location) returns Variable
```
### <sub>method</sub> exists
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/variables/Variable.aspl:31:5
```aspl
method exists(string identifier) returns bool
```
### <sub>method</sub> get
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/variables/Variable.aspl:42:5
```aspl
method get(string identifier) returns Variable
```

## <sub>enum</sub> aspl.compiler.backend.bytecode.IntType
Source: /home/runner/work/aspl/aspl/stdlib/aspl/compiler/backend/bytecode/IntType.aspl:2:1
```aspl

```

## <sub>enum</sub> aspl.parser.attributes.AttributeUsage
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/attributes/AttributeUsage.aspl:3:1
```aspl

```

## <sub>enum</sub> aspl.parser.precedence.PrecedenceLevel
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/precedence/PrecedenceLevel.aspl:2:1
```aspl

```

## <sub>enum</sub> aspl.parser.utils.ParseMode
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/ParseMode.aspl:2:1
```aspl

```

## <sub>function</sub> aspl.compiler.compile
Source: /home/runner/work/aspl/aspl/stdlib/aspl/compiler/main.aspl:37:1
```aspl
function compile(string main) returns CompilationResult
```

## <sub>function</sub> aspl.compiler.utils.out_exe_name
Source: /home/runner/work/aspl/aspl/stdlib/aspl/compiler/utils/filenames.aspl:5:1
```aspl
function out_exe_name(string file) returns string
```

## <sub>function</sub> aspl.compiler.utils.out_temp_name
Source: /home/runner/work/aspl/aspl/stdlib/aspl/compiler/utils/filenames.aspl:39:1
```aspl
function out_temp_name(string file) returns string
```

## <sub>function</sub> aspl.compiler.utils.choose_executable_template
Source: /home/runner/work/aspl/aspl/stdlib/aspl/compiler/utils/templates.aspl:6:1
```aspl
function choose_executable_template(string os, Architecture arch, string internalTemplateType, bool gui) returns string
```

## <sub>function</sub> aspl.parser.parse
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/main.aspl:29:1
```aspl
function parse() returns ParserResult
```

## <sub>function</sub> aspl.parser.sort
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/main.aspl:104:1
```aspl
function sort(list<Node> nodes) returns list<Node>
```

## <sub>function</sub> aspl.parser.utils.notice
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/errors.aspl:6:1
```aspl
function notice(string message, Location? location = null)
```

## <sub>function</sub> aspl.parser.utils.warning
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/errors.aspl:15:1
```aspl
function warning(string message, Location? location = null)
```

## <sub>function</sub> aspl.parser.utils.fatal_error
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/errors.aspl:24:1
```aspl
function fatal_error(string message, Location? location = null)
```

## <sub>function</sub> aspl.parser.utils.syntax_error
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/errors.aspl:35:1
```aspl
function syntax_error(string message, Location? location = null)
```

## <sub>function</sub> aspl.parser.utils.generic_error
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/errors.aspl:46:1
```aspl
function generic_error(string message, Location? location = null)
```

## <sub>function</sub> aspl.parser.utils.type_error
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/errors.aspl:56:1
```aspl
function type_error(string message, Location? location = null)
```

## <sub>function</sub> aspl.parser.utils.verify_expression
Source: /home/runner/work/aspl/aspl/stdlib/aspl/parser/utils/expressions.aspl:6:1
```aspl
function verify_expression(Node node) returns Expression
```