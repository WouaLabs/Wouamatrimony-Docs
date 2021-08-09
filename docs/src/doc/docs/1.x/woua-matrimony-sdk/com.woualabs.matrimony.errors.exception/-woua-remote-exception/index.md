//[woua-matrimony-sdk](../../../index.md)/[com.woualabs.matrimony.errors.exception](../index.md)/[WouaRemoteException](index.md)

# WouaRemoteException

[common]\
open class [WouaRemoteException](index.md)(**httpCode**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, **responseMessage**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [Exception](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html)

## Properties

| Name | Summary |
|---|---|
| [cause](index.md#-875589184%2FProperties%2F-2142679453) | [common]<br>open val [cause](index.md#-875589184%2FProperties%2F-2142679453): [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)? |
| [httpStatusCode](http-status-code.md) | [common]<br>val [httpStatusCode](http-status-code.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? |
| [isAccessDenied](is-access-denied.md) | [common]<br>val [isAccessDenied](is-access-denied.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isNotFound](is-not-found.md) | [common]<br>val [isNotFound](is-not-found.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isUnauthorized](is-unauthorized.md) | [common]<br>val [isUnauthorized](is-unauthorized.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [message](index.md#-657469214%2FProperties%2F-2142679453) | [common]<br>open val [message](index.md#-657469214%2FProperties%2F-2142679453): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? |

## Inheritors

| Name |
|---|
| [WouaSDKException](../-woua-s-d-k-exception/index.md) |
| [WouaValidationException](../-woua-validation-exception/index.md) |
