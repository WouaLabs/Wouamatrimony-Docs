//[woua-matrimony-sdk](../../../index.md)/[com.woualabs.matrimony.onboard.module](../index.md)/[OnBoardModule](index.md)

# OnBoardModule

[common]\
interface [OnBoardModule](index.md)

## Functions

| Name | Summary |
|---|---|
| [changePassword](change-password.md) | [common]<br>abstract suspend fun [changePassword](change-password.md)(password: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), newPassword: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [HandlerResult](../../com.woualabs.matrimony.errors/-handler-result/index.md)<[Result](../../com.woualabs.matrimony.data.common/-result/index.md), [WouaSDKException](../../com.woualabs.matrimony.errors.exception/-woua-s-d-k-exception/index.md)><br>Method supports user to change password |
| [forgotPassword](forgot-password.md) | [common]<br>abstract suspend fun [forgotPassword](forgot-password.md)(memberId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [HandlerResult](../../com.woualabs.matrimony.errors/-handler-result/index.md)<[Result](../../com.woualabs.matrimony.data.common/-result/index.md), [WouaSDKException](../../com.woualabs.matrimony.errors.exception/-woua-s-d-k-exception/index.md)><br>Method supports user to forgot password |
| [login](login.md) | [common]<br>abstract suspend fun [login](login.md)(accountDetails: [AccountDetails](../../com.woualabs.matrimony.type/-account-details/index.md)): [HandlerResult](../../com.woualabs.matrimony.errors/-handler-result/index.md)<[Result](../../com.woualabs.matrimony.data.common/-result/index.md), [WouaSDKException](../../com.woualabs.matrimony.errors.exception/-woua-s-d-k-exception/index.md)><br>This method supports user login |
| [logout](logout.md) | [common]<br>abstract suspend fun [logout](logout.md)(): [HandlerResult](../../com.woualabs.matrimony.errors/-handler-result/index.md)<[Result](../../com.woualabs.matrimony.data.common/-result/index.md), [WouaSDKException](../../com.woualabs.matrimony.errors.exception/-woua-s-d-k-exception/index.md)><br>Method supports user to logout from app |
| [refreshToken](refresh-token.md) | [common]<br>abstract suspend fun [refreshToken](refresh-token.md)(token: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Result](../../com.woualabs.matrimony.data.common/-result/index.md) |
| [signUp](sign-up.md) | [common]<br>abstract suspend fun [signUp](sign-up.md)(details: [AccountDetails](../../com.woualabs.matrimony.type/-account-details/index.md)?): [HandlerResult](../../com.woualabs.matrimony.errors/-handler-result/index.md)<[Result](../../com.woualabs.matrimony.data.common/-result/index.md), [WouaSDKException](../../com.woualabs.matrimony.errors.exception/-woua-s-d-k-exception/index.md)><br>This method supports to create user signup request |
