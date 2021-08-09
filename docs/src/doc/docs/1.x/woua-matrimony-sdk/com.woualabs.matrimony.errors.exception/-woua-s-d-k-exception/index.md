//[woua-matrimony-sdk](../../../index.md)/[com.woualabs.matrimony.errors.exception](../index.md)/[WouaSDKException](index.md)

# WouaSDKException

[common]\
class [WouaSDKException](index.md)(**code**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **httpCode**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, **description**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **error**: [WouaSDKException.Error](-error/index.md)?) : [WouaRemoteException](../-woua-remote-exception/index.md)

## Types

| Name | Summary |
|---|---|
| [Error](-error/index.md) | [common]<br>sealed class [Error](-error/index.md) |

## Properties

| Name | Summary |
|---|---|
| [cause](index.md#-1335235800%2FProperties%2F-2142679453) | [common]<br>open val [cause](index.md#-1335235800%2FProperties%2F-2142679453): [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)? |
| [code](code.md) | [common]<br>val [code](code.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [description](description.md) | [common]<br>val [description](description.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? |
| [error](error.md) | [common]<br>val [error](error.md): [WouaSDKException.Error](-error/index.md)? = null |
| [httpStatusCode](index.md#-1761410878%2FProperties%2F-2142679453) | [common]<br>val [httpStatusCode](index.md#-1761410878%2FProperties%2F-2142679453): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? |
| [isAccessDenied](index.md#-810283456%2FProperties%2F-2142679453) | [common]<br>val [isAccessDenied](index.md#-810283456%2FProperties%2F-2142679453): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isNotFound](index.md#1638052592%2FProperties%2F-2142679453) | [common]<br>val [isNotFound](index.md#1638052592%2FProperties%2F-2142679453): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isUnauthorized](index.md#-1161289461%2FProperties%2F-2142679453) | [common]<br>val [isUnauthorized](index.md#-1161289461%2FProperties%2F-2142679453): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [message](message.md) | [common]<br>open override val [message](message.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? |
