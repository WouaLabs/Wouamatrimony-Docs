//[woua-matrimony-sdk](../../../index.md)/[com.woualabs.matrimony.errors.presenters](../index.md)/[ErrorPresenter](index.md)

# ErrorPresenter

[common, android, iOS, js]\
interface [ErrorPresenter](index.md)<[T](index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>

## Functions

| Name | Summary |
|---|---|
| show | [android, js, iOS]<br>[android]<br>abstract fun [show](show.md)(throwable: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html), activity: [FragmentActivity](https://developer.android.com/reference/kotlin/androidx/fragment/app/FragmentActivity.html), data: [T](index.md))<br>[js]<br>abstract fun [show](index.md#-2091069812%2FFunctions%2F951734917)(throwable: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html), activity: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), data: [T](index.md))<br>[iOS]<br>abstract fun [show](index.md#1517594181%2FFunctions%2F2061961823)(throwable: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html), viewController: UIViewController, data: [T](index.md)) |

## Inheritors

| Name |
|---|
| [AlertErrorPresenter](../-alert-error-presenter/index.md) |
| [SelectorErrorPresenter](../-selector-error-presenter/index.md) |
| [SnackBarErrorPresenter](../-snack-bar-error-presenter/index.md) |
| [ToastErrorPresenter](../-toast-error-presenter/index.md) |
