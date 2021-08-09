//[woua-matrimony-sdk](../../../index.md)/[com.woualabs.matrimony.errors.presenters](../index.md)/[ToastErrorPresenter](index.md)

# ToastErrorPresenter

[common, js]\
class [ToastErrorPresenter](index.md)(**duration**: [ToastDuration](../-toast-duration/index.md)) : [ErrorPresenter](../-error-presenter/index.md)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>

[android]\
class [ToastErrorPresenter](index.md)(**duration**: [ToastDuration](../-toast-duration/index.md#1026510616%2FExtensions%2F1327381271)) : [ErrorPresenter](../-error-presenter/index.md)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>

[iOS]\
class [ToastErrorPresenter](index.md)(**duration**: [ToastDuration](../-toast-duration/index.md)) : [ErrorPresenter](../-error-presenter/index.md)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)> 

In iOS there is no such thing as toast, so it shows [AlertErrorPresenter](../-alert-error-presenter/index.md).

## Constructors

| | |
|---|---|
| [ToastErrorPresenter](-toast-error-presenter.md) | [common, iOS, js]<br>fun [ToastErrorPresenter](-toast-error-presenter.md)(duration: [ToastDuration](../-toast-duration/index.md) = ToastDuration.SHORT)<br>[android]<br>fun [ToastErrorPresenter](-toast-error-presenter.md)(duration: [ToastDuration](../-toast-duration/index.md#1026510616%2FExtensions%2F1327381271) = ToastDuration.SHORT) |

## Functions

| Name | Summary |
|---|---|
| show | [iOS, android, js]<br>[iOS]<br>open override fun [show](index.md#764847532%2FFunctions%2F2061961823)(throwable: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html), viewController: UIViewController, data: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))<br>[android]<br>open override fun [show](show.md)(throwable: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html), activity: [FragmentActivity](https://developer.android.com/reference/kotlin/androidx/fragment/app/FragmentActivity.html), data: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))<br>[js]<br>open override fun [show](index.md#627671202%2FFunctions%2F951734917)(throwable: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html), activity: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), data: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
