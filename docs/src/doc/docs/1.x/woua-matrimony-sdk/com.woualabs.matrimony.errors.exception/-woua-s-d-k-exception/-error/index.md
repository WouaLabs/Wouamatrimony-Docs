//[woua-matrimony-sdk](../../../../index.md)/[com.woualabs.matrimony.errors.exception](../../index.md)/[WouaSDKException](../index.md)/[Error](index.md)

# Error

[common]\
sealed class [Error](index.md)

## Types

| Name | Summary |
|---|---|
| [AuthError](-auth-error/index.md) | [common]<br>class [AuthError](-auth-error/index.md)(**code**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) : [WouaSDKException.Error](index.md) |
| [Failure](-failure/index.md) | [common]<br>class [Failure](-failure/index.md)(**code**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) : [WouaSDKException.Error](index.md) |
| [InvalidModule](-invalid-module/index.md) | [common]<br>class [InvalidModule](-invalid-module/index.md) : [WouaSDKException.Error](index.md) |
| [IOError](-i-o-error/index.md) | [common]<br>class [IOError](-i-o-error/index.md)(**code**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) : [WouaSDKException.Error](index.md) |
| [NoNetwork](-no-network/index.md) | [common]<br>class [NoNetwork](-no-network/index.md)(**code**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) : [WouaSDKException.Error](index.md) |
| [SocketTimeout](-socket-timeout/index.md) | [common]<br>class [SocketTimeout](-socket-timeout/index.md)(**code**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) : [WouaSDKException.Error](index.md) |
| [UnknownError](-unknown-error/index.md) | [common]<br>class [UnknownError](-unknown-error/index.md)(**code**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) : [WouaSDKException.Error](index.md) |

## Properties

| Name | Summary |
|---|---|
| [code](code.md) | [common]<br>val [code](code.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

## Inheritors

| Name |
|---|
| [WouaSDKException.Error](-invalid-module/index.md) |
| [WouaSDKException.Error](-failure/index.md) |
| [WouaSDKException.Error](-no-network/index.md) |
| [WouaSDKException.Error](-auth-error/index.md) |
| [WouaSDKException.Error](-unknown-error/index.md) |
| [WouaSDKException.Error](-socket-timeout/index.md) |
| [WouaSDKException.Error](-i-o-error/index.md) |
