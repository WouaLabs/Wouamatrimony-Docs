//[woua-matrimony-sdk](../../../index.md)/[com.woualabs.matrimony.mvvm.dispatcher](../index.md)/[EventsDispatcher](index.md)/[EventsDispatcher](-events-dispatcher.md)

# EventsDispatcher

[android, iOS, js, common]\
[android]\
fun [EventsDispatcher](-events-dispatcher.md)(executor: [Executor](https://developer.android.com/reference/kotlin/java/util/concurrent/Executor.html))

[iOS]\
fun [EventsDispatcher](index.md#-138681014%2FConstructors%2F2061961823)(queue: dispatch_queue_t)

[iOS]\
fun <[ListenerType](index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [EventsDispatcher](index.md#-585664842%2FConstructors%2F2061961823)(listener: [ListenerType](index.md))

[js, common, iOS]\
fun EventsDispatcher()

[android]\
fun [EventsDispatcher](-events-dispatcher.md)()

[android]\
fun <[ListenerType](index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [EventsDispatcher](-events-dispatcher.md)(executor: [Executor](https://developer.android.com/reference/kotlin/java/util/concurrent/Executor.html), listener: [ListenerType](index.md))

Constructor without lifecycle connection. Used for tests
