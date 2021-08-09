//[woua-matrimony-sdk](../../../index.md)/[com.woualabs.matrimony.errors](../index.md)/[HandlerResult](index.md)

# HandlerResult

[common]\
sealed class [HandlerResult](index.md)<out [T](index.md), out [E](index.md) : [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)>

## Types

| Name | Summary |
|---|---|
| [Failure](-failure/index.md) | [common]<br>class [Failure](-failure/index.md)<out [E](-failure/index.md) : [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)>(**error**: [E](-failure/index.md)) : [HandlerResult](index.md)<[Nothing](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html), [E](-failure/index.md)> |
| [Success](-success/index.md) | [common]<br>class [Success](-success/index.md)<out [T](-success/index.md)>(**value**: [T](-success/index.md)) : [HandlerResult](index.md)<[T](-success/index.md), [Nothing](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html)> |

## Inheritors

| Name |
|---|
| [HandlerResult](-success/index.md) |
| [HandlerResult](-failure/index.md) |
