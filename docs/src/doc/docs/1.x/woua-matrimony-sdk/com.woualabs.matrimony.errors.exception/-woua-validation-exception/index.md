//[woua-matrimony-sdk](../../../index.md)/[com.woualabs.matrimony.errors.exception](../index.md)/[WouaValidationException](index.md)

# WouaValidationException

[common]\
class [WouaValidationException](index.md)(**httpCode**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **message**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **errors**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[WouaValidationException.Error](-error/index.md)>) : [WouaRemoteException](../-woua-remote-exception/index.md)

## Types

| Name | Summary |
|---|---|
| [Error](-error/index.md) | [common]<br>data class [Error](-error/index.md)(**field**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **message**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |

## Properties

| Name | Summary |
|---|---|
| [cause](index.md#-762646541%2FProperties%2F-2142679453) | [common]<br>open val [cause](index.md#-762646541%2FProperties%2F-2142679453): [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)? |
| [errors](errors.md) | [common]<br>val [errors](errors.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[WouaValidationException.Error](-error/index.md)> |
| [httpStatusCode](index.md#637743191%2FProperties%2F-2142679453) | [common]<br>val [httpStatusCode](index.md#637743191%2FProperties%2F-2142679453): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? |
| [isAccessDenied](index.md#1588870613%2FProperties%2F-2142679453) | [common]<br>val [isAccessDenied](index.md#1588870613%2FProperties%2F-2142679453): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isNotFound](index.md#-1712589563%2FProperties%2F-2142679453) | [common]<br>val [isNotFound](index.md#-1712589563%2FProperties%2F-2142679453): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isUnauthorized](index.md#1237864608%2FProperties%2F-2142679453) | [common]<br>val [isUnauthorized](index.md#1237864608%2FProperties%2F-2142679453): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [message](index.md#506228309%2FProperties%2F-2142679453) | [common]<br>open val [message](index.md#506228309%2FProperties%2F-2142679453): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? |
