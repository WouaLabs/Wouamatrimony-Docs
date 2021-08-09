//[woua-matrimony-sdk](../../index.md)/[com.woualabs.matrimony.mvvm](index.md)

# Package com.woualabs.matrimony.mvvm

## Types

| Name | Summary |
|---|---|
| [ViewModelFactory](-view-model-factory/index.md) | [android]<br>class [ViewModelFactory](-view-model-factory/index.md)(**viewModelBlock**: () -> [ViewModel](https://developer.android.com/reference/kotlin/androidx/lifecycle/ViewModel.html)) : [ViewModelProvider.Factory](https://developer.android.com/reference/kotlin/androidx/lifecycle/ViewModelProvider.Factory.html) |

## Functions

| Name | Summary |
|---|---|
| [createViewModelFactory](create-view-model-factory.md) | [android]<br>inline fun <[T](create-view-model-factory.md) : [ViewModel](https://developer.android.com/reference/kotlin/androidx/lifecycle/ViewModel.html)> [ViewModelStoreOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/ViewModelStoreOwner.html).[createViewModelFactory](create-view-model-factory.md)(noinline viewModelBlock: () -> [T](create-view-model-factory.md)): [ViewModelFactory](-view-model-factory/index.md) |
| [getViewModel](get-view-model.md) | [android]<br>inline fun <[T](get-view-model.md) : [ViewModel](https://developer.android.com/reference/kotlin/androidx/lifecycle/ViewModel.html)> [ViewModelStoreOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/ViewModelStoreOwner.html).[getViewModel](get-view-model.md)(noinline viewModelBlock: () -> [T](get-view-model.md)): [T](get-view-model.md) |

## Properties

| Name | Summary |
|---|---|
| [UI](-u-i.md) | [common]<br>val Dispatchers.[UI](-u-i.md): CoroutineDispatcher |
