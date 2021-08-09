//[woua-matrimony-sdk](../../index.md)/[com.woualabs.matrimony](index.md)/[createViewModelScope](create-view-model-scope.md)

# createViewModelScope

[common]\
var [createViewModelScope](create-view-model-scope.md): () -> CoroutineScope

Factory of viewModelScope. Internal API, for ability of mvvm-test to change viewModelScope dispatcher.

In default implementation create main-thread dispatcher scope.
