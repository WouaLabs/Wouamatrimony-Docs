//[woua-matrimony-sdk](../../index.md)/[com.woualabs.matrimony](index.md)

# Package com.woualabs.matrimony

## Types

| Name | Summary |
|---|---|
| [Builder](-builder/index.md) | [common]<br>class [Builder](-builder/index.md) |
| [Configuration](-configuration/index.md) | [common]<br>class [Configuration](-configuration/index.md)(**builder**: [Builder](-builder/index.md)) |
| [ECDHUtils](-e-c-d-h-utils/index.md) | [common, android, iOS, js]<br>[common, android, iOS, js]<br>class [ECDHUtils](-e-c-d-h-utils/index.md) |
| [ErrorElement](-error-element/index.md) | [common]<br>data class [ErrorElement](-error-element/index.md)(**message**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **path**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [FlowWrapper](-flow-wrapper/index.md) | [iOS]<br>class [FlowWrapper](-flow-wrapper/index.md)<[T](-flow-wrapper/index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>(**scope**: CoroutineScope, **flow**: Flow<[T](-flow-wrapper/index.md)>) |
| [IosSDK](-ios-s-d-k/index.md) | [iOS]<br>class [IosSDK](-ios-s-d-k/index.md)(**isDebug**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>Base class for iOS initialization |
| [JsDriver](-js-driver/index.md) | [js]<br>class [JsDriver](-js-driver/index.md) |
| [JsSDK](-js-s-d-k/index.md) | [js]<br>@[ExperimentalJsExport](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.js/-experimental-js-export/index.html)()<br>class [JsSDK](-js-s-d-k/index.md)(**configuration**: [Configuration](-configuration/index.md), **isDebug**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [MainScope](-main-scope/index.md) | [iOS]<br>class [MainScope](-main-scope/index.md)(**mainContext**: [CoroutineContext](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.coroutines/-coroutine-context/index.html), **log**: Kermit) : CoroutineScope |
| [Name](index.md#1432953060%2FClasslikes%2F951734917) | [js]<br>typealias [Name](index.md#1432953060%2FClasslikes%2F951734917) = [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [NullableFlowWrapper](-nullable-flow-wrapper/index.md) | [iOS]<br>class [NullableFlowWrapper](-nullable-flow-wrapper/index.md)<[T](-nullable-flow-wrapper/index.md)>(**scope**: CoroutineScope, **flow**: Flow<[T](-nullable-flow-wrapper/index.md)>) |
| [NullableSuspendWrapper](-nullable-suspend-wrapper/index.md) | [iOS]<br>class [NullableSuspendWrapper](-nullable-suspend-wrapper/index.md)<[T](-nullable-suspend-wrapper/index.md)>(**scope**: CoroutineScope, **suspender**: suspend () -> [T](-nullable-suspend-wrapper/index.md)) |
| [Person](-person/index.md) | [js]<br>@[ExperimentalJsExport](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.js/-experimental-js-export/index.html)()<br>external interface [Person](-person/index.md) |
| [Response](-response/index.md) | [common]<br>sealed class [Response](-response/index.md)<out [T](-response/index.md)> |
| [SDK](-s-d-k/index.md) | [common]<br>open class [SDK](-s-d-k/index.md) |
| [SuspendWrapper](-suspend-wrapper/index.md) | [iOS]<br>class [SuspendWrapper](-suspend-wrapper/index.md)<[T](-suspend-wrapper/index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>(**scope**: CoroutineScope, **suspender**: suspend () -> [T](-suspend-wrapper/index.md)) |
| [Thing](-thing/index.md) | [common]<br>data class [Thing](-thing/index.md)(**count**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [ThingRepository](-thing-repository/index.md) | [common]<br>class [ThingRepository](-thing-repository/index.md) |
| [WouaMatrimonySDK](-woua-matrimony-s-d-k/index.md) | [common]<br>object [WouaMatrimonySDK](-woua-matrimony-s-d-k/index.md) |

## Functions

| Name | Summary |
|---|---|
| [create](create.md) | [android]<br>fun [SDK.Companion](-s-d-k/-companion/index.md#565128667%2FExtensions%2F1327381271).[create](create.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), configuration: [Configuration](-configuration/index.md), isDebug: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [createUIDispatcher](create-u-i-dispatcher.md) | [common, android, iOS, js]<br>[common, android, iOS, js]<br>fun [createUIDispatcher](create-u-i-dispatcher.md)(): CoroutineDispatcher |
| [currentTimeMillis](current-time-millis.md) | [common, android, iOS, js]<br>[common, android, iOS, js]<br>fun [currentTimeMillis](current-time-millis.md)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| deviceId | [js, android]<br>[js]<br>fun [deviceId](index.md#709770303%2FFunctions%2F951734917)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>[android]<br>fun [deviceId](device-id.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| getAbsolutePath | [js, android]<br>[js]<br>fun [getAbsolutePath](index.md#-167586184%2FFunctions%2F951734917)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>[android]<br>fun [getAbsolutePath](get-absolute-path.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [getLogger](get-logger.md) | [common, android, iOS, js]<br>[common, android, iOS, js]<br>fun [getLogger](get-logger.md)(): Logger |
| [main](main.md) | [js]<br>fun [main](main.md)() |
| [randomUUID](random-u-u-i-d.md) | [common, android, iOS, js]<br>[common, android, iOS, js]<br>fun [randomUUID](random-u-u-i-d.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [sayFormalHello](say-formal-hello.md) | [js]<br>@[ExperimentalJsExport](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.js/-experimental-js-export/index.html)()<br>fun [sayFormalHello](say-formal-hello.md)(person: [Person](-person/index.md)): [Name](index.md#1432953060%2FClasslikes%2F951734917) |
| [sayHello](say-hello.md) | [js]<br>@[ExperimentalJsExport](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.js/-experimental-js-export/index.html)()<br>fun [sayHello](say-hello.md)(name: [Name](index.md#1432953060%2FClasslikes%2F951734917) = "Mr. PP Trump"): [Name](index.md#1432953060%2FClasslikes%2F951734917) |

## Properties

| Name | Summary |
|---|---|
| [createViewModelScope](create-view-model-scope.md) | [common]<br>var [createViewModelScope](create-view-model-scope.md): () -> CoroutineScope<br>Factory of viewModelScope. |
