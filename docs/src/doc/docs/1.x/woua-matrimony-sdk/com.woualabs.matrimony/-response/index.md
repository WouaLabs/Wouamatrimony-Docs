//[woua-matrimony-sdk](../../../index.md)/[com.woualabs.matrimony](../index.md)/[Response](index.md)

# Response

[common]\
sealed class [Response](index.md)<out [T](index.md)>

## Types

| Name | Summary |
|---|---|
| [Error](-error/index.md) | [common]<br>data class [Error](-error/index.md)(**exception**: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html), **code**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, **error**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)?, **errorCollection**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[ErrorElement](../-error-element/index.md)>?, **message**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **method**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **path**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?) : [Response](index.md)<[Nothing](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html)> |
| [Success](-success/index.md) | [common]<br>class [Success](-success/index.md)<out [T](-success/index.md)>(**data**: [T](-success/index.md)) : [Response](index.md)<[T](-success/index.md)> |

## Inheritors

| Name |
|---|
| [Response](-success/index.md) |
| [Response](-error/index.md) |
