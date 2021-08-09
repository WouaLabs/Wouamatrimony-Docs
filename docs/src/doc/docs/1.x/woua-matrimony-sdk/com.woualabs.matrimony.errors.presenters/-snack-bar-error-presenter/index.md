//[woua-matrimony-sdk](../../../index.md)/[com.woualabs.matrimony.errors.presenters](../index.md)/[SnackBarErrorPresenter](index.md)

# SnackBarErrorPresenter

[common, js]\
class [SnackBarErrorPresenter](index.md)(**duration**: [SnackBarDuration](../-snack-bar-duration/index.md)) : [ErrorPresenter](../-error-presenter/index.md)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>

[android]\
class [SnackBarErrorPresenter](index.md)(**duration**: [SnackBarDuration](../-snack-bar-duration/index.md#1655739926%2FExtensions%2F1327381271)) : [ErrorPresenter](../-error-presenter/index.md)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>

[iOS]\
class [SnackBarErrorPresenter](index.md)(**duration**: [SnackBarDuration](../-snack-bar-duration/index.md)) : [ErrorPresenter](../-error-presenter/index.md)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)> 

In iOS there is no such thing as snackbar, so it shows [AlertErrorPresenter](../-alert-error-presenter/index.md).

## Constructors

| | |
|---|---|
| [SnackBarErrorPresenter](-snack-bar-error-presenter.md) | [common, iOS, js]<br>fun [SnackBarErrorPresenter](-snack-bar-error-presenter.md)(duration: [SnackBarDuration](../-snack-bar-duration/index.md) = SnackBarDuration.INDEFINITE)<br>[android]<br>fun [SnackBarErrorPresenter](-snack-bar-error-presenter.md)(duration: [SnackBarDuration](../-snack-bar-duration/index.md#1655739926%2FExtensions%2F1327381271) = SnackBarDuration.INDEFINITE) |

## Functions

| Name | Summary |
|---|---|
| show | [iOS, android, js]<br>[iOS]<br>open override fun [show](../-toast-error-presenter/index.md#764847532%2FFunctions%2F2061961823)(throwable: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html), viewController: UIViewController, data: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))<br>[android]<br>open override fun [show](show.md)(throwable: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html), activity: [FragmentActivity](https://developer.android.com/reference/kotlin/androidx/fragment/app/FragmentActivity.html), data: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))<br>[js]<br>open override fun [show](index.md#1764746400%2FFunctions%2F951734917)(throwable: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html), activity: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), data: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
