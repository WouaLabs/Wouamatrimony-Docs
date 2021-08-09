//[woua-matrimony-sdk](../../../../index.md)/[com.woualabs.matrimony.errors.handler](../../index.md)/[ExceptionHandlerContext](../index.md)/[Companion](index.md)

# Companion

[common]\
object [Companion](index.md)

## Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | [common]<br>operator fun <[T](invoke.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [R](invoke.md)> [invoke](invoke.md)(exceptionMapper: [ExceptionMapper](../../index.md#1774241992%2FClasslikes%2F-2142679453)<[T](invoke.md)>, eventsDispatcher: [EventsDispatcher](../../../com.woualabs.matrimony.mvvm.dispatcher/-events-dispatcher/index.md)<[ErrorEventListener](../../../com.woualabs.matrimony.errors/-error-event-listener/index.md)<[T](invoke.md)>>? = null, onCatch: ([Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)?, block: suspend () -> [R](invoke.md)): [ExceptionHandlerContext](../index.md)<[R](invoke.md)> |
