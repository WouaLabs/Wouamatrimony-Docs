//[woua-matrimony-sdk](../../../index.md)/[com.woualabs.matrimony.errors.handler](../index.md)/[ExceptionHandlerContext](index.md)

# ExceptionHandlerContext

[common]\
abstract class [ExceptionHandlerContext](index.md)<[R](index.md)>

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [common]<br>object [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [catch](catch.md) | [common]<br>inline fun <[E](catch.md) : [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)> [catch](catch.md)(noinline catcher: ([E](catch.md)) -> [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [ExceptionHandlerContext](index.md)<[R](index.md)><br>abstract fun <[E](catch.md) : [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)> [catch](catch.md)(clazz: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[E](catch.md)>, catcher: ([E](catch.md)) -> [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [ExceptionHandlerContext](index.md)<[R](index.md)> |
| [execute](execute.md) | [common]<br>abstract suspend fun [execute](execute.md)(): [HandlerResult](../../com.woualabs.matrimony.errors/-handler-result/index.md)<[R](index.md), [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)> |
| [finally](finally.md) | [common]<br>abstract fun [finally](finally.md)(block: () -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): [ExceptionHandlerContext](index.md)<[R](index.md)> |
