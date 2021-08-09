//[woua-matrimony-sdk](../../../index.md)/[com.woualabs.matrimony.errors.handler](../index.md)/[ExceptionHandler](index.md)

# ExceptionHandler

[common]\
interface [ExceptionHandler](index.md) : [ExceptionHandlerBinder](../-exception-handler-binder/index.md)

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [common]<br>object [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [handle](handle.md) | [common]<br>abstract fun <[R](handle.md)> [handle](handle.md)(block: suspend () -> [R](handle.md)): [ExceptionHandlerContext](../-exception-handler-context/index.md)<[R](handle.md)> |
