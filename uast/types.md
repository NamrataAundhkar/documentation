<!-- Code generated by 'make types' DO NOT EDIT. -->
# UAST Types

For every [UAST type](semantic-uast.md#types)
in every driver the following two values are reported:
 - _fixtures usage_  - number of times this type was used in driver _fixtures_ (_*.sem.uast_ files)
 - _code usage_ - number of times this type was used in in the driver mapping DSL code (_normalizer.go_ file)

The format is _fixtures usage_ / _code usage_ in case _code usage_ is not zero.
Otherwise, only _fixture usage_ is reported.

|                         | [Bash](https://github.com/bblfsh/bash-driver) | [C++](https://github.com/bblfsh/cpp-driver) | [C#](https://github.com/bblfsh/csharp-driver) | [Go](https://github.com/bblfsh/go-driver) | [Java](https://github.com/bblfsh/java-driver) | [JavaScript](https://github.com/bblfsh/javascript-driver) | [PHP](https://github.com/bblfsh/php-driver) | [Python](https://github.com/bblfsh/python-driver) | [Ruby](https://github.com/bblfsh/ruby-driver) | [TypeScript](https://github.com/bblfsh/typescript-driver) |
| :---------------------- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| [uast:Position](https://godoc.org/github.com/bblfsh/sdk/uast#Position) | 15884 | 52948 | 36468 | 45464 | 12684 | 69088 | 9738 | 16924 | 7992 | 2348 |
| [uast:Positions](https://godoc.org/github.com/bblfsh/sdk/uast#Positions) | 7942 | 26474 | 18258 | 18530 | 6342 | 34580 | 6557 | 11319 | 3996 | 1174 |
| [uast:Identifier](https://godoc.org/github.com/bblfsh/sdk/uast#Identifier) | 1840 | 9805 | 3028 | 8129 | 2043 | 11817 | 2097 | 4758 | 1683 | - |
| [uast:String](https://godoc.org/github.com/bblfsh/sdk/uast#String) | 538 | 729 | 118 | 150 | 21 | 670 | 299 | 429 | 267 | - |
| [uast:Bool](https://godoc.org/github.com/bblfsh/sdk/uast#Bool) | - | - | 29 | - | - | - | - | 34 | 55 | - |
| [uast:QualifiedIdentifier](https://godoc.org/github.com/bblfsh/sdk/uast#QualifiedIdentifier) | - | 948 | 24 | 72 | 36 | - | 30 | 18 | - | - |
| [uast:Comment](https://godoc.org/github.com/bblfsh/sdk/uast#Comment) | 121 | 178 | 40 | 870 | 60 | 1986 | 146 | 331 | 6 | - |
| [uast:Group](https://godoc.org/github.com/bblfsh/sdk/uast#Group) | - | - | 24 | - | 12 | - | - | 3 | - | - |
| [uast:FunctionGroup](https://godoc.org/github.com/bblfsh/sdk/uast#FunctionGroup) | 28 | 274 | 222 | 236 | 120 | 36 | 54 | 202 | 114 | - |
| [uast:Block](https://godoc.org/github.com/bblfsh/sdk/uast#Block) | 28 | 600 | 322 | 765 | 369 | 1352 | 411 | 202 | 326 | - |
| [uast:Alias](https://godoc.org/github.com/bblfsh/sdk/uast#Alias) | 28 | 274 | 223 | 242 | 120 | 74 | 84 | 217 | 114 | - |
| [uast:Import](https://godoc.org/github.com/bblfsh/sdk/uast#Import) | - | - | 38 | 198 | 13 | 35 | - | - | - | - |
| [uast:RuntimeImport](https://godoc.org/github.com/bblfsh/sdk/uast#RuntimeImport) | - | - | - | - | - | - | 29 | 66 | 12 | - |
| [uast:RuntimeReImport](https://godoc.org/github.com/bblfsh/sdk/uast#RuntimeReImport) | - | - | - | - | - | - | 7 | - | - | - |
| [uast:InlineImport](https://godoc.org/github.com/bblfsh/sdk/uast#InlineImport) | - | 144 | - | - | - | - | - | - | - | - |
| [uast:Argument](https://godoc.org/github.com/bblfsh/sdk/uast#Argument) | - | 386 | 405 | 645 | 94 | 71 | 234 | 478 | 166 | - |
| [uast:FunctionType](https://godoc.org/github.com/bblfsh/sdk/uast#FunctionType) | 28 | 274 | 222 | 259 | 120 | 36 | 54 | 202 | 114 | - |
| [uast:Function](https://godoc.org/github.com/bblfsh/sdk/uast#Function) | 28 | 274 | 222 | 236 | 120 | 36 | 54 | 202 | 114 | - |

**Don't see your favorite AST construct represented? [Help us!](../join-the-community.md)**
