//[woua-matrimony-sdk](../../index.md)/[com.woualabs.matrimony.errors.exception](index.md)

# Package com.woualabs.matrimony.errors.exception

## Types

| Name | Summary |
|---|---|
| [WouaRemoteException](-woua-remote-exception/index.md) | [common]<br>open class [WouaRemoteException](-woua-remote-exception/index.md)(**httpCode**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, **responseMessage**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [Exception](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html) |
| [WouaSDKException](-woua-s-d-k-exception/index.md) | [common]<br>class [WouaSDKException](-woua-s-d-k-exception/index.md)(**code**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **httpCode**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, **description**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **error**: [WouaSDKException.Error](-woua-s-d-k-exception/-error/index.md)?) : [WouaRemoteException](-woua-remote-exception/index.md) |
| [WouaValidationException](-woua-validation-exception/index.md) | [common]<br>class [WouaValidationException](-woua-validation-exception/index.md)(**httpCode**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **message**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **errors**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[WouaValidationException.Error](-woua-validation-exception/-error/index.md)>) : [WouaRemoteException](-woua-remote-exception/index.md) |
