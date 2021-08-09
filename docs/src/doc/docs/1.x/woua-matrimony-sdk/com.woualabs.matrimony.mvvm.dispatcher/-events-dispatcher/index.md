//[woua-matrimony-sdk](../../../index.md)/[com.woualabs.matrimony.mvvm.dispatcher](../index.md)/[EventsDispatcher](index.md)

# EventsDispatcher

[common, android, iOS, js]\
class [EventsDispatcher](index.md)<[ListenerType](index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>

## Constructors

| | |
|---|---|
| [EventsDispatcher](-events-dispatcher.md) | [android]<br>fun [EventsDispatcher](-events-dispatcher.md)(executor: [Executor](https://developer.android.com/reference/kotlin/java/util/concurrent/Executor.html)) |
| [EventsDispatcher](-events-dispatcher.md) | [android]<br>fun <[ListenerType](index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [EventsDispatcher](-events-dispatcher.md)(executor: [Executor](https://developer.android.com/reference/kotlin/java/util/concurrent/Executor.html), listener: [ListenerType](index.md))<br>Constructor without lifecycle connection. |
| [EventsDispatcher](index.md#-138681014%2FConstructors%2F2061961823) | [iOS]<br>fun [EventsDispatcher](index.md#-138681014%2FConstructors%2F2061961823)(queue: dispatch_queue_t) |
| [EventsDispatcher](index.md#-585664842%2FConstructors%2F2061961823) | [iOS]<br>fun <[ListenerType](index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [EventsDispatcher](index.md#-585664842%2FConstructors%2F2061961823)(listener: [ListenerType](index.md)) |

## Functions

| Name | Summary |
|---|---|
| [bind](bind.md) | [android]<br>fun [bind](bind.md)(lifecycleOwner: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html), listener: [ListenerType](index.md)) |
| [dispatchEvent](dispatch-event.md) | [common, android, iOS, js]<br>[common, android, iOS, js]<br>fun [dispatchEvent](dispatch-event.md)(block: [ListenerType](index.md).() -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)) |

## Properties

| Name | Summary |
|---|---|
| [listener](listener.md) | [iOS]<br>var [listener](listener.md): [ListenerType](index.md)? |
