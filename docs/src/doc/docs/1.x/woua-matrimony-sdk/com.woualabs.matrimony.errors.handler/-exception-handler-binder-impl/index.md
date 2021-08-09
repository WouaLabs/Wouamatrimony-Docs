//[woua-matrimony-sdk](../../../index.md)/[com.woualabs.matrimony.errors.handler](../index.md)/[ExceptionHandlerBinderImpl](index.md)

# ExceptionHandlerBinderImpl

[common, android, iOS, js]\
class [ExceptionHandlerBinderImpl](index.md)<[T](index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>(**errorPresenter**: [ErrorPresenter](../../com.woualabs.matrimony.errors.presenters/-error-presenter/index.md)<[T](index.md)>, **eventsDispatcher**: [EventsDispatcher](../../com.woualabs.matrimony.mvvm.dispatcher/-events-dispatcher/index.md)<[ErrorEventListener](../../com.woualabs.matrimony.errors/-error-event-listener/index.md)<[T](index.md)>>) : [ExceptionHandlerBinder](../-exception-handler-binder/index.md)

## Types

| Name | Summary |
|---|---|
| EventsListener | [android, js]<br>[android]<br>class [EventsListener]([android]-events-listener/index.md)<[T]([android]-events-listener/index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>(**activity**: [FragmentActivity](https://developer.android.com/reference/kotlin/androidx/fragment/app/FragmentActivity.html), **errorPresenter**: [ErrorPresenter](../../com.woualabs.matrimony.errors.presenters/-error-presenter/index.md)<[T]([android]-events-listener/index.md)>) : [ErrorEventListener](../../com.woualabs.matrimony.errors/-error-event-listener/index.md)<[T]([android]-events-listener/index.md)> <br>[js]<br>class [EventsListener]([js]-events-listener/index.md)<[T]([js]-events-listener/index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>(**activity**: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), **errorPresenter**: [ErrorPresenter](../../com.woualabs.matrimony.errors.presenters/-error-presenter/index.md)<[T]([js]-events-listener/index.md)>) : [ErrorEventListener](../../com.woualabs.matrimony.errors/-error-event-listener/index.md)<[T]([js]-events-listener/index.md)> |

## Functions

| Name | Summary |
|---|---|
| bind | [iOS, android, js]<br>[iOS]<br>open override fun [bind](index.md#-2145935927%2FFunctions%2F2061961823)(viewController: UIViewController)<br>[android]<br>open override fun [bind](bind.md)(lifecycleOwner: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html), activity: [FragmentActivity](https://developer.android.com/reference/kotlin/androidx/fragment/app/FragmentActivity.html))<br>[js]<br>open override fun [bind](index.md#-563080094%2FFunctions%2F951734917)(lifecycleOwner: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), activity: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)) |
