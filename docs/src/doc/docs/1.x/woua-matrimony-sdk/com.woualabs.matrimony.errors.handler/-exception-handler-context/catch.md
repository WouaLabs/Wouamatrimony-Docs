//[woua-matrimony-sdk](../../../index.md)/[com.woualabs.matrimony.errors.handler](../index.md)/[ExceptionHandlerContext](index.md)/[catch](catch.md)

# catch

[common]\
abstract fun <[E](catch.md) : [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)> [catch](catch.md)(clazz: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[E](catch.md)>, catcher: ([E](catch.md)) -> [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [ExceptionHandlerContext](index.md)<[R](index.md)>

inline fun <[E](catch.md) : [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)> [catch](catch.md)(noinline catcher: ([E](catch.md)) -> [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [ExceptionHandlerContext](index.md)<[R](index.md)>
