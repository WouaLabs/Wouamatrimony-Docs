//[woua-matrimony-sdk](../../../index.md)/[com.woualabs.matrimony.lookup.repository](../index.md)/[LookupRepository](index.md)

# LookupRepository

[common]\
interface [LookupRepository](index.md)

## Functions

| Name | Summary |
|---|---|
| [fetchLocality](fetch-locality.md) | [common]<br>abstract suspend fun [fetchLocality](fetch-locality.md)(localityType: [LocalityType](../../com.woualabs.matrimony.type/-locality-type/index.md), id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [HandlerResult](../../com.woualabs.matrimony.errors/-handler-result/index.md)<[LookUpRecord](../../com.woualabs.matrimony.lookup.mapper/-look-up-record/index.md), [WouaSDKException](../../com.woualabs.matrimony.errors.exception/-woua-s-d-k-exception/index.md)> |
| [fetchLookUp](fetch-look-up.md) | [common]<br>abstract suspend fun [fetchLookUp](fetch-look-up.md)(lookupType: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[LookupType](../../com.woualabs.matrimony.type/-lookup-type/index.md)>): [HandlerResult](../../com.woualabs.matrimony.errors/-handler-result/index.md)<[LookUpRecord](../../com.woualabs.matrimony.lookup.mapper/-look-up-record/index.md), [WouaSDKException](../../com.woualabs.matrimony.errors.exception/-woua-s-d-k-exception/index.md)> |
