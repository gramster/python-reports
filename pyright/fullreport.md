
# GITHUB ISSUES REPORT FOR microsoft/pyright


Generated on 2026-02-23 using: stale=30, all=True


* marks items that are new to report in past 7 day(s)


## FOR ISSUES THAT ARE MARKED AS BUGS:


### Issues in pyright that need a response from team:

| Days Ago | Issue | Title |
| --- | --- | --- |
 | \* OP:0  |[11294](https://github.com/microsoft/pyright/issues/11294 "False unreachable warning when matching type[X]")  |False unreachable warning when matching type[X] |
 | \* OP:2  |[11292](https://github.com/microsoft/pyright/issues/11292 "Decorator expressions implying `deprecated` calls typically issue no warning")  |Decorator expressions implying `deprecated` calls typically issue no warning |
 | \* OP:3  |[11289](https://github.com/microsoft/pyright/issues/11289 "[match-case]: mapping pattern narrowing inconsistent with equivalent `isinstance` narrowing")  |[match-case]: mapping pattern narrowing inconsistent with equivalent `isinstance` narrowing |
 |  OP:15  |[11275](https://github.com/microsoft/pyright/issues/11275 "deprecateTypingAliases incorrectly reports Optional as deprecated") | deprecateTypingAliases incorrectly reports Optional as deprecated |
 |  OP:19  |[11270](https://github.com/microsoft/pyright/issues/11270 "Enum.value inferred as tuple[Literal[..]]") | Enum.value inferred as tuple[Literal[..]] |
 |  OP:22  |[11261](https://github.com/microsoft/pyright/issues/11261 "Setting `()` to `Union`, which means no type arguments doesn't get error") | Setting `()` to `Union`, which means no type arguments doesn't get error |
 |  OP:26  |[11255](https://github.com/microsoft/pyright/issues/11255 "reportAbstractUsage check ignores __new__ return type") | reportAbstractUsage check ignores __new__ return type |
 |  OP:26  |[11252](https://github.com/microsoft/pyright/issues/11252 "OOM on numpy in dict with an update") | OOM on numpy in dict with an update |
 |  OP:27  |[11249](https://github.com/microsoft/pyright/issues/11249 "Pyright incorrectly marks a match case as unreachable (regression in 1.1.408)") | Pyright incorrectly marks a match case as unreachable (regression in 1.1.408) |
 |  OP:29  |[11247](https://github.com/microsoft/pyright/issues/11247 "Surprising type analysis failure") | Surprising type analysis failure |
 |  OP:32  |[11243](https://github.com/microsoft/pyright/issues/11243 "sequence pattern on NamedTuple infers `tuple` type") | sequence pattern on NamedTuple infers `tuple` type |
 |  OP:37  |[11236](https://github.com/microsoft/pyright/issues/11236 "pyright ignores from __future__ import annotations when it comes to method definitions") | pyright ignores from __future__ import annotations when it comes to method definitions |
 |  OP:41  |[11228](https://github.com/microsoft/pyright/issues/11228 "Slow code analysis") | Slow code analysis |
 |  OP:41  |[11227](https://github.com/microsoft/pyright/issues/11227 "Generic nested classes cannot reference each other") | Generic nested classes cannot reference each other |
 |  OP:42  |[11226](https://github.com/microsoft/pyright/issues/11226 "Default value for dataclass field with bound TypeVar type") | Default value for dataclass field with bound TypeVar type |
 |  OP:44  |[11220](https://github.com/microsoft/pyright/issues/11220 "Instances of classes that define `__iter__ = None` and `__getitem__` should not be iterable.") | Instances of classes that define `__iter__ = None` and `__getitem__` should not be iterable. |
 |  OP:50  |[11200](https://github.com/microsoft/pyright/issues/11200 "`reportUninitializedInstanceVariable` false negatives/positives for the `__weakref__` slot") | `reportUninitializedInstanceVariable` false negatives/positives for the `__weakref__` slot |
 |  OP:53  |[11196](https://github.com/microsoft/pyright/issues/11196 "`--verifytypes` sometimes reports imported symbol as partially unknown, despite `--ignoreexternal`") | `--verifytypes` sometimes reports imported symbol as partially unknown, despite `--ignoreexternal` |
 |  OP:62  |[11187](https://github.com/microsoft/pyright/issues/11187 "Problem inferring nested generic classes with defaults") | Problem inferring nested generic classes with defaults |
 |  OP:68  |[11179](https://github.com/microsoft/pyright/issues/11179 "Problem inferring type variables with a default in `Protocol`") | Problem inferring type variables with a default in `Protocol` |
 |  OP:68  |[11178](https://github.com/microsoft/pyright/issues/11178 "Incorrect inference of `Never` after empty loop, properties and use of `Generic`") | Incorrect inference of `Never` after empty loop, properties and use of `Generic` |
 |  OP:70  |[11173](https://github.com/microsoft/pyright/issues/11173 "Wrong signature of decorated method seen inside the decorated method") | Wrong signature of decorated method seen inside the decorated method |
 |  OP:72  |[11171](https://github.com/microsoft/pyright/issues/11171 "Static protocols' (`type[IFoo[T]]]`) type parameters (`T`) are unknown") | Static protocols' (`type[IFoo[T]]]`) type parameters (`T`) are unknown |
 |  OP:74  |[11167](https://github.com/microsoft/pyright/issues/11167 "Type forms not allowed in any order in TypedDict functional syntax") | Type forms not allowed in any order in TypedDict functional syntax |
 |  OP:75  |[11162](https://github.com/microsoft/pyright/issues/11162 "Adding a decorator to a dataclass breaks the signature") | Adding a decorator to a dataclass breaks the signature |
 |  OP:76  |[11158](https://github.com/microsoft/pyright/issues/11158 "Missing SyntaxError check for `async for` in lambda inside an async function") | Missing SyntaxError check for `async for` in lambda inside an async function |
 |  OP:80  |[11155](https://github.com/microsoft/pyright/issues/11155 "Incorrect diagnostic message for `isinstance(None, object)`") | Incorrect diagnostic message for `isinstance(None, object)` |
 |  OP:80  |[11154](https://github.com/microsoft/pyright/issues/11154 "Missing warning when using ClassVar without subscript") | Missing warning when using ClassVar without subscript |
 |  OP:85  |[11146](https://github.com/microsoft/pyright/issues/11146 "1.1.365 regression: tuples created from iterating over a tuple of literals looses literal type information") | 1.1.365 regression: tuples created from iterating over a tuple of literals looses literal type information |
 |  OP:85  |[11145](https://github.com/microsoft/pyright/issues/11145 "False positive `InconsistentOverload` with generic class of tuple argument") | False positive `InconsistentOverload` with generic class of tuple argument |
 |  OP:86  |[11144](https://github.com/microsoft/pyright/issues/11144 "Taking a slice of a class inherited from a tuple sometimes ignores the custom typing of the __getitem__ method") | Taking a slice of a class inherited from a tuple sometimes ignores the custom typing of the __getitem__ method |
 |  OP:92  |[11134](https://github.com/microsoft/pyright/issues/11134 "`TypedDict` not considered as matching `dict()` pattern in match") | `TypedDict` not considered as matching `dict()` pattern in match |
 |  OP:92  |[11133](https://github.com/microsoft/pyright/issues/11133 "Wrong (missing?) type inference on `{}` in match/case") | Wrong (missing?) type inference on `{}` in match/case |
 |  OP:92  |[11131](https://github.com/microsoft/pyright/issues/11131 "@runtime_checkable should require a direct inheritance from Protocol") | @runtime_checkable should require a direct inheritance from Protocol |
 |  OP:95  |[11128](https://github.com/microsoft/pyright/issues/11128 "No Liskov violation reported in a situation where a non-generic method overrides a generic method") | No Liskov violation reported in a situation where a non-generic method overrides a generic method |
 |  OP:95  |[11127](https://github.com/microsoft/pyright/issues/11127 "`tuple[int, int, *tuple[Any, ...]]` should be assignable to `tuple[int, ...]`") | `tuple[int, int, *tuple[Any, ...]]` should be assignable to `tuple[int, ...]` |
 |  OP:95  |[11126](https://github.com/microsoft/pyright/issues/11126 "False positive when extending both Enum and another class") | False positive when extending both Enum and another class |
 |  OP:96  |[11124](https://github.com/microsoft/pyright/issues/11124 "Pyright Will Use non Stubs Package Import if `py.typed` is Present") | Pyright Will Use non Stubs Package Import if `py.typed` is Present |
 |  OP:96  |[11123](https://github.com/microsoft/pyright/issues/11123 "`yield from` combines single-type iterators") | `yield from` combines single-type iterators |
 |  OP:98  |[11117](https://github.com/microsoft/pyright/issues/11117 "dataclass instance attribute type wrong for field with descriptor type and no default") | dataclass instance attribute type wrong for field with descriptor type and no default |
 |  OP:98  |[11116](https://github.com/microsoft/pyright/issues/11116 "&quot;key&quot; in typed_dict checks for non-closed TypedDict doesn't allow typed_dict[&quot;key&quot;] afterwards") | "key" in typed_dict checks for non-closed TypedDict doesn't allow typed_dict["key"] afterwards |
 |  OP:98  |[11115](https://github.com/microsoft/pyright/issues/11115 "Pyright 1.1.405 regression with sentinels") | Pyright 1.1.405 regression with sentinels |
 |  OP:104  |[11104](https://github.com/microsoft/pyright/issues/11104 "Re-Adding Workspaces to the Language Server should retrigger Diagnostic generation") | Re-Adding Workspaces to the Language Server should retrigger Diagnostic generation |
 |  OP:104  |[11103](https://github.com/microsoft/pyright/issues/11103 "Language Server hangs due to uninitialized workspaces") | Language Server hangs due to uninitialized workspaces |
 |  OP:109  |[11099](https://github.com/microsoft/pyright/issues/11099 "Sequence pattern sometimes matches strings") | Sequence pattern sometimes matches strings |
 |  OP:110  |[11095](https://github.com/microsoft/pyright/issues/11095 "Strange inference behavior when using replace on dataclasses in asynchronous functions") | Strange inference behavior when using replace on dataclasses in asynchronous functions |
 |  OP:112  |[11088](https://github.com/microsoft/pyright/issues/11088 "Valid match cases are reported as unreachable") | Valid match cases are reported as unreachable |
 |  OP:118  |[11067](https://github.com/microsoft/pyright/issues/11067 "exponential slowdown when using `yield from` with type alias") | exponential slowdown when using `yield from` with type alias |
 |  OP:126  |[11048](https://github.com/microsoft/pyright/issues/11048 "A bunch of overlapping protocols in `@overload`s causes Pyright's runtime to explode.") | A bunch of overlapping protocols in `@overload`s causes Pyright's runtime to explode. |
 |  OP:129  |[11042](https://github.com/microsoft/pyright/issues/11042 "False errors when using issubclass on argument of type type[T] where T is generic") | False errors when using issubclass on argument of type type[T] where T is generic |
 |  OP:129  |[11039](https://github.com/microsoft/pyright/issues/11039 "Incorrect type narrowing with subclassed descriptors") | Incorrect type narrowing with subclassed descriptors |
 |  OP:131  |[11035](https://github.com/microsoft/pyright/issues/11035 "Function return type depends on previous calls") | Function return type depends on previous calls |
 |  OP:132  |[11029](https://github.com/microsoft/pyright/issues/11029 "Subsequent `partial` functions in a list are not type-checked") | Subsequent `partial` functions in a list are not type-checked |
 |  OP:146  |[10976](https://github.com/microsoft/pyright/issues/10976 "Method-bound type-parameter can &quot;leak&quot; through a `Protocol`") | Method-bound type-parameter can "leak" through a `Protocol` |
 |  OP:159  |[10941](https://github.com/microsoft/pyright/issues/10941 "Type Annotation are not allowed for enum members when using nonmember") | Type Annotation are not allowed for enum members when using nonmember |
 |  OP:164  |[10927](https://github.com/microsoft/pyright/issues/10927 "False positive when callback protocol uses a function-scoped type variable") | False positive when callback protocol uses a function-scoped type variable |
 |  OP:164  |[10926](https://github.com/microsoft/pyright/issues/10926 "Unexpected assignability rules of generic TypedDicts") | Unexpected assignability rules of generic TypedDicts |
 |  OP:167  |[10911](https://github.com/microsoft/pyright/issues/10911 "Argument type to an `IntEnum` should be compatible with `int`") | Argument type to an `IntEnum` should be compatible with `int` |
 |  OP:168  |[10905](https://github.com/microsoft/pyright/issues/10905 "1.1.405 : Type of &quot;xxx&quot; could not be determined because it refers to itself") | 1.1.405 : Type of "xxx" could not be determined because it refers to itself |
 |  OP:171  |[10899](https://github.com/microsoft/pyright/issues/10899 "`divmod` still not working right") | `divmod` still not working right |
 |  OP:182  |[10845](https://github.com/microsoft/pyright/issues/10845 "Methods of a variadic generic class become uncallable when specified with TypeVarTuple and a suffix") | Methods of a variadic generic class become uncallable when specified with TypeVarTuple and a suffix |
 |  OP:186  |[10833](https://github.com/microsoft/pyright/issues/10833 "False positives with non-terminating generators") | False positives with non-terminating generators |
 |  OP:187  |[10826](https://github.com/microsoft/pyright/issues/10826 "Pyright incorrectly refers to `NewType` as an instance of `FunctionType` in diagnostic messages, does not allow attributes to be accessed") | Pyright incorrectly refers to `NewType` as an instance of `FunctionType` in diagnostic messages, does not allow attributes to be accessed |
 |  OP:188  |[10823](https://github.com/microsoft/pyright/issues/10823 "&quot;type[UnionType]&quot; is not assignable to &quot;type&quot;") | "type[UnionType]" is not assignable to "type" |
 |  OP:189  |[10817](https://github.com/microsoft/pyright/issues/10817 "JavaScript heap out of memory with AbstractEventLoop and call_soon_threadsafe") | JavaScript heap out of memory with AbstractEventLoop and call_soon_threadsafe |
 |  OP:190  |[10813](https://github.com/microsoft/pyright/issues/10813 "False positive when calling overloaded `*args` with union of tuples") | False positive when calling overloaded `*args` with union of tuples |
 |  OP:191  |[10808](https://github.com/microsoft/pyright/issues/10808 "Incorrect scope lookup in class bodies in 3.14") | Incorrect scope lookup in class bodies in 3.14 |
 |  OP:192  |[10800](https://github.com/microsoft/pyright/issues/10800 "Error: Function declaration &quot;x&quot; is obscured by a declaration of the same name when it should not.") | Error: Function declaration "x" is obscured by a declaration of the same name when it should not. |
 |  OP:192  |[10799](https://github.com/microsoft/pyright/issues/10799 "ParamSpec allowed to be used before import") | ParamSpec allowed to be used before import |
 |  OP:194  |[10793](https://github.com/microsoft/pyright/issues/10793 "TypeForm error when used in function with specific structure") | TypeForm error when used in function with specific structure |
 |  OP:208  |[10759](https://github.com/microsoft/pyright/issues/10759 "bug: Incorrect overload overlaps in sync, or missing overlap in async") | bug: Incorrect overload overlaps in sync, or missing overlap in async |
 |  OP:210  |[10754](https://github.com/microsoft/pyright/issues/10754 "Implicit override not flagged for decorated methods") | Implicit override not flagged for decorated methods |
 |  OP:215  |[10744](https://github.com/microsoft/pyright/issues/10744 "Sentinel instances only work as constants") | Sentinel instances only work as constants |
 |  OP:216  |[10733](https://github.com/microsoft/pyright/issues/10733 "False positive &quot;reportArgumentType&quot; if ParamSpec is inferred as generic argument") | False positive "reportArgumentType" if ParamSpec is inferred as generic argument |
 |  OP:220  |[10725](https://github.com/microsoft/pyright/issues/10725 "bug: bidirectional inference when using typeguard") | bug: bidirectional inference when using typeguard |
 |  OP:221  |[10719](https://github.com/microsoft/pyright/issues/10719 "Inconsistent choice of `Union` variant when multiple choices are valid") | Inconsistent choice of `Union` variant when multiple choices are valid |
 |  OP:222  |[10714](https://github.com/microsoft/pyright/issues/10714 "Different narrowing with `isinstance` vs match-case against Callback-Protocol") | Different narrowing with `isinstance` vs match-case against Callback-Protocol |
 |  OP:222  |[10713](https://github.com/microsoft/pyright/issues/10713 "`list[str]` is assignable to `list[int | Any]`, but shouldn't be") | `list[str]` is assignable to `list[int | Any]`, but shouldn't be |
 |  OP:229  |[10689](https://github.com/microsoft/pyright/issues/10689 "sequence or mapping pattern on generic variables makes case unreachable") | sequence or mapping pattern on generic variables makes case unreachable |
 |  OP:233  |[10678](https://github.com/microsoft/pyright/issues/10678 "Incorrect reachability analysis involving NewType") | Incorrect reachability analysis involving NewType |
 |  OP:236  |[10668](https://github.com/microsoft/pyright/issues/10668 "New-types seem to have an under-specified callable signature of `(...) -> Any` on 1.1.402") | New-types seem to have an under-specified callable signature of `(...) -> Any` on 1.1.402 |
 |  OP:238  |[10660](https://github.com/microsoft/pyright/issues/10660 "Propagating ParamSpec through wrappers differ by class & function") | Propagating ParamSpec through wrappers differ by class & function |
 |  OP:238  |[10657](https://github.com/microsoft/pyright/issues/10657 "false positive on map with a conditional expression") | false positive on map with a conditional expression |
 |  OP:243  |[10646](https://github.com/microsoft/pyright/issues/10646 "false positive incompatible-override error when expanding `bool` args over different overloads") | false positive incompatible-override error when expanding `bool` args over different overloads |
 |  OP:246  |[10637](https://github.com/microsoft/pyright/issues/10637 "Unpacking a tuple containing an unpacked TypeVarTuple results in an illegal list type inference") | Unpacking a tuple containing an unpacked TypeVarTuple results in an illegal list type inference |
 |  OP:246  |[10636](https://github.com/microsoft/pyright/issues/10636 "Generic method argument with Self type causes incomplete signature") | Generic method argument with Self type causes incomplete signature |
 |  OP:248  |[10631](https://github.com/microsoft/pyright/issues/10631 "Passing a generic type via a parameter of type `type[T]` can leak an unsolved type variable") | Passing a generic type via a parameter of type `type[T]` can leak an unsolved type variable |
 |  OP:248  |[10626](https://github.com/microsoft/pyright/issues/10626 "dataclass_transform as decorator for class decorator blocks type checking") | dataclass_transform as decorator for class decorator blocks type checking |
 |  OP:248  |[10625](https://github.com/microsoft/pyright/issues/10625 "`Any | Never` evaluates to `Never` instead of `Any`") | `Any | Never` evaluates to `Never` instead of `Any` |
 |  OP:249  |[10624](https://github.com/microsoft/pyright/issues/10624 "Pyright hangs forever on a namedtuple with classmethod constructor") | Pyright hangs forever on a namedtuple with classmethod constructor |
 |  OP:250  |[10622](https://github.com/microsoft/pyright/issues/10622 "Incorrect narrowing applied for `x is type(<final type instance>)` construct") | Incorrect narrowing applied for `x is type(<final type instance>)` construct |
 |  OP:251  |[10618](https://github.com/microsoft/pyright/issues/10618 "Truthy type-narrowing of None bound or constraint TypeVar not happening") | Truthy type-narrowing of None bound or constraint TypeVar not happening |
 |  OP:254  |[10607](https://github.com/microsoft/pyright/issues/10607 "Order dependent inference results with some protocols against numpy") | Order dependent inference results with some protocols against numpy |
 |  OP:255  |[10603](https://github.com/microsoft/pyright/issues/10603 "Failing to narrow Any to None") | Failing to narrow Any to None |
 |  OP:258  |[10592](https://github.com/microsoft/pyright/issues/10592 "`--createstub` can drop directories if a source file is named the same as its parent directory.") | `--createstub` can drop directories if a source file is named the same as its parent directory. |
 |  OP:260  |[10560](https://github.com/microsoft/pyright/issues/10560 "`list(filter(None, map(func, ...)))` is typed as `list[Unknown]` if `func`'s return type doesn't include `None`") | `list(filter(None, map(func, ...)))` is typed as `list[Unknown]` if `func`'s return type doesn't include `None` |
 |  OP:272  |[10509](https://github.com/microsoft/pyright/issues/10509 "TypeIs Does Not Properly Narrow Generics") | TypeIs Does Not Properly Narrow Generics |
 |  OP:277  |[10491](https://github.com/microsoft/pyright/issues/10491 "&quot;could not be determined because it refers to itself&quot; error occurs depending on variable name and string literal value") | "could not be determined because it refers to itself" error occurs depending on variable name and string literal value |
 |  OP:280  |[10469](https://github.com/microsoft/pyright/issues/10469 "Slow Typechecking 50-element homogeneous tuple") | Slow Typechecking 50-element homogeneous tuple |
 |  OP:281  |[10466](https://github.com/microsoft/pyright/issues/10466 "Type &quot;Shape[int]&quot; is not assignable to declared type &quot;Shape[int]&quot;") | Type "Shape[int]" is not assignable to declared type "Shape[int]" |
 |  OP:282  |[10457](https://github.com/microsoft/pyright/issues/10457 "&quot;possibly unbound&quot; error when redefining builtin in try-except") | "possibly unbound" error when redefining builtin in try-except |
 |  OP:292  |[10420](https://github.com/microsoft/pyright/issues/10420 "Regression: crtp type bounds lost") | Regression: crtp type bounds lost |
 |  OP:306  |[10364](https://github.com/microsoft/pyright/issues/10364 "Pyright hangs when a generic type alias definition refers to itself via typevar bound") | Pyright hangs when a generic type alias definition refers to itself via typevar bound |
 |  OP:321  |[10271](https://github.com/microsoft/pyright/issues/10271 "Type inference bug with self-application of a generic function containing `ParamSpec`") | Type inference bug with self-application of a generic function containing `ParamSpec` |
 |  OP:329  |[10231](https://github.com/microsoft/pyright/issues/10231 "Pyright fails to fully infer the type of a curried function when applied to a generic function") | Pyright fails to fully infer the type of a curried function when applied to a generic function |
 |  OP:334  |[10174](https://github.com/microsoft/pyright/issues/10174 "&quot;Type is partially unknown&quot; under very specific circumstances") | "Type is partially unknown" under very specific circumstances |

### Issues in pyright that have comments from OP after last team response:

| Days Ago | Issue | Title |
| --- | --- | --- |
 |  TM:27, OP:26  |[11176](https://github.com/microsoft/pyright/issues/11176 "Useless lines affect type checking") | Useless lines affect type checking |
 |  TM:73, OP:73  |[11169](https://github.com/microsoft/pyright/issues/11169 "Enum type not assignable to complete union of its literal members") | Enum type not assignable to complete union of its literal members |
 |  TM:113, OP:42  |[11076](https://github.com/microsoft/pyright/issues/11076 "Process never finishes in `1.1.405`, `1.1.406`, `1.1.407`, `1.1.408`") | Process never finishes in `1.1.405`, `1.1.406`, `1.1.407`, `1.1.408` |
 |  TM:121, OP:121  |[11063](https://github.com/microsoft/pyright/issues/11063 "False positive: `TypeVar`s in functional-style`TypedDicts` are allowed but unsupported") | False positive: `TypeVar`s in functional-style`TypedDicts` are allowed but unsupported |
 |  TM:131, OP:131  |[11031](https://github.com/microsoft/pyright/issues/11031 "Completion giving incorrect options when editing multiline function invocation") | Completion giving incorrect options when editing multiline function invocation |
 |  TM:141, OP:141  |[10993](https://github.com/microsoft/pyright/issues/10993 "Type arithmetic inconsistency") | Type arithmetic inconsistency |
 |  TM:148, OP:148  |[10973](https://github.com/microsoft/pyright/issues/10973 "Numerous FPs when `Literal['abc']` and var named `abc` coexist (but only if `enableExperimentalFeatures=true`)") | Numerous FPs when `Literal['abc']` and var named `abc` coexist (but only if `enableExperimentalFeatures=true`) |
 |  TM:160, OP:160  |[10934](https://github.com/microsoft/pyright/issues/10934 "Wrong type interference for inheritance with statements") | Wrong type interference for inheritance with statements |
 |  TM:165, OP:165  |[10923](https://github.com/microsoft/pyright/issues/10923 "Strange regression in lamda parameter type inference in 1.1.405") | Strange regression in lamda parameter type inference in 1.1.405 |
 |  TM:222, OP:119  |[10702](https://github.com/microsoft/pyright/issues/10702 "Function having return type as type variable with `Callable` bound does not allow `Callable[..., Any]` to be returned") | Function having return type as type variable with `Callable` bound does not allow `Callable[..., Any]` to be returned |
 |  TM:234, OP:231  |[10676](https://github.com/microsoft/pyright/issues/10676 "The undefined variable goes unnoticed") | The undefined variable goes unnoticed |
 |  TM:241, OP:241  |[10656](https://github.com/microsoft/pyright/issues/10656 "Generic ParamSpec on class produces `reportCallIssue` error after conditional check `len(args) == x` or `len(args) != x`") | Generic ParamSpec on class produces `reportCallIssue` error after conditional check `len(args) == x` or `len(args) != x` |
 |  TM:243, OP:243  |[10649](https://github.com/microsoft/pyright/issues/10649 "`reportInvalidTypeVarUse` superfluous when using default values?") | `reportInvalidTypeVarUse` superfluous when using default values? |
 |  TM:258, OP:258  |[10580](https://github.com/microsoft/pyright/issues/10580 "`reportUnknownVariableType` sometimes not reported") | `reportUnknownVariableType` sometimes not reported |
 |  TM:328, OP:328  |[10237](https://github.com/microsoft/pyright/issues/10237 "False negative for callable assignability") | False negative for callable assignability |
 |  TM:333, OP:299  |[10187](https://github.com/microsoft/pyright/issues/10187 "Pyright hangs when a unification variable occurs inside itself") | Pyright hangs when a unification variable occurs inside itself |

### Issues in pyright that have comments from 3rd party after last team response:

| Days Ago | Issue | Title |
| --- | --- | --- |
 |  P:41,  |[11225](https://github.com/microsoft/pyright/issues/11225 "Whether strict mode or not, setting an empty tuple to the generic type alias type argument of `ParamSpec` base gets no error") | Whether strict mode or not, setting an empty tuple to the generic type alias type argument of `ParamSpec` base gets no error |
 |  P:140,  |[10936](https://github.com/microsoft/pyright/issues/10936 "False Unreachable Code Detection on Startup - Gets Fixed by LSP Restart") | False Unreachable Code Detection on Startup - Gets Fixed by LSP Restart |
 |  P:21,  |[10881](https://github.com/microsoft/pyright/issues/10881 "Consuming large amount of heap memory") | Consuming large amount of heap memory |
 |  P:196,  |[10778](https://github.com/microsoft/pyright/issues/10778 "Referring to a different instantiation whilst defining a generic class") | Referring to a different instantiation whilst defining a generic class |
 |  P:225,  |[10703](https://github.com/microsoft/pyright/issues/10703 "Incorrectly inferring generic function parameter type") | Incorrectly inferring generic function parameter type |
 |  P:228,  |[10690](https://github.com/microsoft/pyright/issues/10690 "pyright 1.1.403 started reporting &quot;is not a known attribute of module&quot;") | pyright 1.1.403 started reporting "is not a known attribute of module" |
 |  P:170,  |[10671](https://github.com/microsoft/pyright/issues/10671 "workspaceEdit missing changeAnnotations") | workspaceEdit missing changeAnnotations |
 |  P:301,  |[10329](https://github.com/microsoft/pyright/issues/10329 "False positive unreachable with unrelated types in match-case statement") | False positive unreachable with unrelated types in match-case statement |

### Issues in pyright that have no external responses since team response in 30+ days:

| Days Ago | Issue | Title |
| --- | --- | --- |
 |  TM:82  |[11150](https://github.com/microsoft/pyright/issues/11150 "TypedDict w/ extra items accepts `str` key but not `LiteralString`") | TypedDict w/ extra items accepts `str` key but not `LiteralString` |
 |  TM:107  |[11100](https://github.com/microsoft/pyright/issues/11100 "Enum member alias is wrongly considered a canonical member of the enum") | Enum member alias is wrongly considered a canonical member of the enum |
 |  TM:111  |[11089](https://github.com/microsoft/pyright/issues/11089 "reportOptionalMemberAccess after raise ValueError") | reportOptionalMemberAccess after raise ValueError |
 |  TM:121  |[11061](https://github.com/microsoft/pyright/issues/11061 "`--createstub` creates incorrect stub for async generator functions") | `--createstub` creates incorrect stub for async generator functions |
 |  TM:122  |[11058](https://github.com/microsoft/pyright/issues/11058 "Classes with `__slots__` require that their subclasses have the same amount of slots") | Classes with `__slots__` require that their subclasses have the same amount of slots |
 |  TM:136  |[11023](https://github.com/microsoft/pyright/issues/11023 "Erroneous &quot;undefined variable&quot; after specific method call") | Erroneous "undefined variable" after specific method call |
 |  TM:138  |[11008](https://github.com/microsoft/pyright/issues/11008 "Slowdown when enabling enableExperimentalFeatures on string-heavy files") | Slowdown when enabling enableExperimentalFeatures on string-heavy files |
 |  TM:147  |[10974](https://github.com/microsoft/pyright/issues/10974 "Unpacking a NamedTuple leads to unusual results") | Unpacking a NamedTuple leads to unusual results |
 |  TM:153  |[10951](https://github.com/microsoft/pyright/issues/10951 "Inconsistent narrowing into nested function when using TypeIs guard stored in a local variable") | Inconsistent narrowing into nested function when using TypeIs guard stored in a local variable |
 |  TM:160  |[10932](https://github.com/microsoft/pyright/issues/10932 "Constrained TypeVar narrowing does not work with Callable") | Constrained TypeVar narrowing does not work with Callable |
 |  TM:160  |[10931](https://github.com/microsoft/pyright/issues/10931 "Adding a for loop breaks narrowing of a constrained TypeVar") | Adding a for loop breaks narrowing of a constrained TypeVar |
 |  TM:165  |[10924](https://github.com/microsoft/pyright/issues/10924 "Inconsistent overload resolution on `Generic` methods") | Inconsistent overload resolution on `Generic` methods |
 |  TM:172  |[10889](https://github.com/microsoft/pyright/issues/10889 "Request textDocument/completion failed on custom code") | Request textDocument/completion failed on custom code |
 |  TM:199  |[10776](https://github.com/microsoft/pyright/issues/10776 "incorrectly `reportUnknownParameterType` with double type alias") | incorrectly `reportUnknownParameterType` with double type alias |
 |  TM:217  |[10728](https://github.com/microsoft/pyright/issues/10728 "Type resolution fails for class attributes with Callable[[], None] annotation") | Type resolution fails for class attributes with Callable[[], None] annotation |
 |  TM:229  |[10688](https://github.com/microsoft/pyright/issues/10688 "Unexpected `Unknown` type arguments when using class factory which has access to bound and defaults") | Unexpected `Unknown` type arguments when using class factory which has access to bound and defaults |
 |  TM:236  |[10667](https://github.com/microsoft/pyright/issues/10667 "When a data-class with `order=True` is being subclassed, the comparator methods get re-synthesized, and therefore have argument types narrowed") | When a data-class with `order=True` is being subclassed, the comparator methods get re-synthesized, and therefore have argument types narrowed |
 |  TM:243  |[10645](https://github.com/microsoft/pyright/issues/10645 "implicit override not reported for overloaded methods without implementation") | implicit override not reported for overloaded methods without implementation |
 |  TM:243  |[10643](https://github.com/microsoft/pyright/issues/10643 "False positive incompatible override with *args + keyword-only param") | False positive incompatible override with *args + keyword-only param |
 |  TM:247  |[10632](https://github.com/microsoft/pyright/issues/10632 "Shadowing names in cases of a match with non-trivial scrutinee") | Shadowing names in cases of a match with non-trivial scrutinee |
 |  TM:255  |[10605](https://github.com/microsoft/pyright/issues/10605 "`isinstance` detects module as a type") | `isinstance` detects module as a type |
 |  TM:266  |[10528](https://github.com/microsoft/pyright/issues/10528 "reassigning instance attribute causes it to become unbound") | reassigning instance attribute causes it to become unbound |
 |  TM:250  |[10516](https://github.com/microsoft/pyright/issues/10516 "TypeForm + TypeVar type inference") | TypeForm + TypeVar type inference |
 |  TM:314  |[10311](https://github.com/microsoft/pyright/issues/10311 "False positive of `reportUnnecessaryComparison` for loop variables") | False positive of `reportUnnecessaryComparison` for loop variables |
 |  TM:321  |[10270](https://github.com/microsoft/pyright/issues/10270 "Incorrect type inference after type narrowing using isinstance with protocols") | Incorrect type inference after type narrowing using isinstance with protocols |
 |  TM:328  |[10235](https://github.com/microsoft/pyright/issues/10235 "False positive unreachable when pattern matching `int` with `http.HTTPStatus`") | False positive unreachable when pattern matching `int` with `http.HTTPStatus` |

---

## FOR ISSUES THAT ARE NOT MARKED AS BUGS:


### Issues in pyright that need a response from team:

| Days Ago | Issue | Title |
| --- | --- | --- |
 | \* OP:7  |[11283](https://github.com/microsoft/pyright/issues/11283 "@overload type checking for overload signatures")  |@overload type checking for overload signatures |
 |  OP:12  |[11278](https://github.com/microsoft/pyright/issues/11278 "Allow more fine-grained configuration of tagged hints") | Allow more fine-grained configuration of tagged hints |
 |  OP:13  |[11277](https://github.com/microsoft/pyright/issues/11277 "`--verifytypes --ignoreexternal` reports public parameter as partially unknown with conditional optional-dependency alias") | `--verifytypes --ignoreexternal` reports public parameter as partially unknown with conditional optional-dependency alias |
 |  OP:18  |[11272](https://github.com/microsoft/pyright/issues/11272 "Pyright hangs/fails opaquely on large codebase") | Pyright hangs/fails opaquely on large codebase |
 |  OP:24  |[11257](https://github.com/microsoft/pyright/issues/11257 "Add `namespaceOverridePaths` configOption for fragmented package support") | Add `namespaceOverridePaths` configOption for fragmented package support |
 |  OP:27  |[11251](https://github.com/microsoft/pyright/issues/11251 "Warn on wrong Concatenate usage") | Warn on wrong Concatenate usage |
 |  OP:30  |[11245](https://github.com/microsoft/pyright/issues/11245 "Support usage of slack variables (lower bound emulation)") | Support usage of slack variables (lower bound emulation) |
 |  OP:64  |[11182](https://github.com/microsoft/pyright/issues/11182 "Ignore unknown key `&quot;$schema&quot;` in schema validation") | Ignore unknown key `"$schema"` in schema validation |
 |  OP:136  |[11021](https://github.com/microsoft/pyright/issues/11021 "allow non-descriptor subtypes") | allow non-descriptor subtypes |
 |  OP:145  |[10981](https://github.com/microsoft/pyright/issues/10981 "Detect non-empty loops") | Detect non-empty loops |
 |  OP:146  |[10977](https://github.com/microsoft/pyright/issues/10977 "Improvement to type controls: apply across statement rather than line") | Improvement to type controls: apply across statement rather than line |
 |  OP:165  |[10921](https://github.com/microsoft/pyright/issues/10921 "Ignore a missing module globally for reportMissingModuleSource") | Ignore a missing module globally for reportMissingModuleSource |
 |  OP:174  |[10880](https://github.com/microsoft/pyright/issues/10880 "Better UX for suppressing reportAttributeAccessIssue and similar static analysis warnings") | Better UX for suppressing reportAttributeAccessIssue and similar static analysis warnings |
 |  OP:180  |[10853](https://github.com/microsoft/pyright/issues/10853 "Improve match subject narrowing") | Improve match subject narrowing |
 |  OP:180  |[10852](https://github.com/microsoft/pyright/issues/10852 "Use match case guard to narrow else cases") | Use match case guard to narrow else cases |
 |  OP:201  |[10770](https://github.com/microsoft/pyright/issues/10770 "Expand `reportUninitializedInstanceVariable` to protocol variable implementation detection") | Expand `reportUninitializedInstanceVariable` to protocol variable implementation detection |
 |  OP:210  |[10753](https://github.com/microsoft/pyright/issues/10753 "`reveal_type` should descend into anonymous types (such as inline `TypeDict`s), not show placeholder") | `reveal_type` should descend into anonymous types (such as inline `TypeDict`s), not show placeholder |
 |  OP:259  |[10566](https://github.com/microsoft/pyright/issues/10566 "Allow Ignoring Specific Libraries for Strict Type Checking in Pyright") | Allow Ignoring Specific Libraries for Strict Type Checking in Pyright |

### Issues in pyright that have comments from OP after last team response:

| Days Ago | Issue | Title |
| --- | --- | --- |
 |  TM:83, OP:81  |[11149](https://github.com/microsoft/pyright/issues/11149 "Re-exported submodule results in &quot;Import could not be resolved from source&quot;") | Re-exported submodule results in "Import could not be resolved from source" |
 |  TM:129, OP:56  |[11041](https://github.com/microsoft/pyright/issues/11041 "Avoid triggering reportUnreachable on exception raising?") | Avoid triggering reportUnreachable on exception raising? |
 |  TM:167, OP:167  |[10916](https://github.com/microsoft/pyright/issues/10916 "No narrowing after `isinstance(obj, tuple)`  if  `tuple` contains a term.") | No narrowing after `isinstance(obj, tuple)`  if  `tuple` contains a term. |

### Issues in pyright that have comments from 3rd party after last team response:

| Days Ago | Issue | Title |
| --- | --- | --- |
 |  P:89,  |[11130](https://github.com/microsoft/pyright/issues/11130 "`override` decorator doesn't report problems when paired with `cached_property` decorator") | `override` decorator doesn't report problems when paired with `cached_property` decorator |
 |  P:137,  |[11007](https://github.com/microsoft/pyright/issues/11007 "type[] can be used in a contravariant manner, which is unsound") | type[] can be used in a contravariant manner, which is unsound |

### Issues in pyright that have no external responses since team response in 30+ days:

| Days Ago | Issue | Title |
| --- | --- | --- |
 |  TM:131  |[11036](https://github.com/microsoft/pyright/issues/11036 "Keyword-only first argument in instance method not reported") | Keyword-only first argument in instance method not reported |
 |  TM:145  |[10986](https://github.com/microsoft/pyright/issues/10986 "Magic calls to deprecated __getitem__ not flagged as deprecated") | Magic calls to deprecated __getitem__ not flagged as deprecated |
 |  TM:182  |[10795](https://github.com/microsoft/pyright/issues/10795 "Extend exclude config option") | Extend exclude config option |

## PULL REQUEST ACTIVITY


### Pull Requests opened in the past 7 day(s):

| | PR | Created By | Created | Days Open | Closed/Merged | Closed/Merged By | Title |
| --- | --- | --- | --- | --- | --- | --- | --- |
| \* | [#11293](https://github.com/microsoft/pyright/pull/11293) | ActaVerba | 2026-02-22 | 0 | - | - | Fix percent-encoded drive letter colon (%3A) in Windows file URIs |

### Pull Requests still open that were opened more than 7 days ago:

| | PR | Created By | Created | Days Open | Closed/Merged | Closed/Merged By | Title |
| --- | --- | --- | --- | --- | --- | --- | --- |
| \* | [#10875](https://github.com/microsoft/pyright/pull/10875) | erictraut | 2025-08-31 | 175 | - | - | Fixed bug that resulted in incorrect simplification of `Any | Never`.… |
| \* | [#11242](https://github.com/microsoft/pyright/pull/11242) | dependabot | 2026-01-21 | 33 | - | - | Bump lodash from 4.17.21 to 4.17.23 |
| \* | [#11256](https://github.com/microsoft/pyright/pull/11256) | q4rk | 2026-01-30 | 24 | - | - | Implement `namespaceOverridePaths` for Fragmented Package Support |
| \* | [#11265](https://github.com/microsoft/pyright/pull/11265) | Zaczero | 2026-02-02 | 21 | - | - | Optimize TextRangeCollection.getItemContaining |
| \* | [#11269](https://github.com/microsoft/pyright/pull/11269) | dependabot | 2026-02-03 | 20 | - | - | Bump @isaacs/brace-expansion from 5.0.0 to 5.0.1 in /packages/vscode-pyright |
| \* | [#11273](https://github.com/microsoft/pyright/pull/11273) | dependabot | 2026-02-05 | 18 | - | - | Bump webpack from 5.102.1 to 5.105.0 in /packages/pyright |
|   | [#11281](https://github.com/microsoft/pyright/pull/11281) | dependabot | 2026-02-14 | 9 | - | - | Bump qs from 6.14.0 to 6.14.2 in /packages/vscode-pyright |

## RECENTLY CLOSED ISSUES


### Issues closed in the past 7 day(s):

| Days Ago | Issue | Title |
| --- | --- | --- |
 | \* TM:0  |[11295](https://github.com/microsoft/pyright/issues/11295 "Pylance false positive for missing method on a wrapt.ObjectProxy subclass")  |Pylance false positive for missing method on a wrapt.ObjectProxy subclass |
 | \* TM:0  |[11291](https://github.com/microsoft/pyright/issues/11291 "Default argument of `converter` doesn't work in field specifiers of `dataclass_transform`")  |Default argument of `converter` doesn't work in field specifiers of `dataclass_transform` |
 | \* TM:0  |[11288](https://github.com/microsoft/pyright/issues/11288 "Add option to allow implicit re-exports (mypy compatibility)")  |Add option to allow implicit re-exports (mypy compatibility) |
 | \* TM:0  |[11287](https://github.com/microsoft/pyright/issues/11287 "Literal typehint on parameter in __init__ does not propagate to class instance attribute")  |Literal typehint on parameter in __init__ does not propagate to class instance attribute |
 | \* TM:0  |[11286](https://github.com/microsoft/pyright/issues/11286 "typing issue: type with list of literals is extended to string")  |typing issue: type with list of literals is extended to string |
 | \* TM:204  |[10752](https://github.com/microsoft/pyright/issues/10752 "Add support for Android and iOS")  |Add support for Android and iOS |






![](bugcount.png)

![](time_to_merge_prs.png)

![](time_to_close_issues.png)

![](time_to_first_response.png)

![](label_frequencies.png)

![](files_changed_per_pr.png)

![](lines_changed_per_pr.png)

![](termcloud.png)