//[woua-matrimony-sdk](../../../../index.md)/[com.woualabs.matrimony.errors.presenters](../../index.md)/[AlertDialogFragment](../index.md)/[DialogSettings](index.md)

# DialogSettings

[android]\
data class [DialogSettings](index.md)(**title**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **positiveButtonText**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **messageText**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?) : [Parcelable](https://developer.android.com/reference/kotlin/android/os/Parcelable.html)

## Constructors

| | |
|---|---|
| [DialogSettings](-dialog-settings.md) | [android]<br>fun [DialogSettings](-dialog-settings.md)(parcel: [Parcel](https://developer.android.com/reference/kotlin/android/os/Parcel.html)) |

## Types

| Name | Summary |
|---|---|
| [CREATOR](-c-r-e-a-t-o-r/index.md) | [android]<br>object [CREATOR](-c-r-e-a-t-o-r/index.md) : [Parcelable.Creator](https://developer.android.com/reference/kotlin/android/os/Parcelable.Creator.html)<[AlertDialogFragment.DialogSettings](index.md)> |

## Functions

| Name | Summary |
|---|---|
| [describeContents](describe-contents.md) | [android]<br>open override fun [describeContents](describe-contents.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [writeToParcel](write-to-parcel.md) | [android]<br>open override fun [writeToParcel](write-to-parcel.md)(parcel: [Parcel](https://developer.android.com/reference/kotlin/android/os/Parcel.html), flags: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |

## Properties

| Name | Summary |
|---|---|
| [messageText](message-text.md) | [android]<br>val [messageText](message-text.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? |
| [positiveButtonText](positive-button-text.md) | [android]<br>val [positiveButtonText](positive-button-text.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? |
| [title](title.md) | [android]<br>val [title](title.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? |
