//[woua-matrimony-sdk](../../../index.md)/[com.woualabs.matrimony.plan.repository](../index.md)/[PlanRepository](index.md)

# PlanRepository

[common]\
interface [PlanRepository](index.md)

## Functions

| Name | Summary |
|---|---|
| [requestToUpgradePlan](request-to-upgrade-plan.md) | [common]<br>abstract suspend fun [requestToUpgradePlan](request-to-upgrade-plan.md)(planId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), planState: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [HandlerResult](../../com.woualabs.matrimony.errors/-handler-result/index.md)<[Result](../../com.woualabs.matrimony.data.common/-result/index.md), [WouaSDKException](../../com.woualabs.matrimony.errors.exception/-woua-s-d-k-exception/index.md)> |
| [viewPlans](view-plans.md) | [common]<br>abstract suspend fun [viewPlans](view-plans.md)(): [HandlerResult](../../com.woualabs.matrimony.errors/-handler-result/index.md)<[PlanRecord](../../com.woualabs.matrimony.plan.mapper/-plan-record/index.md), [WouaSDKException](../../com.woualabs.matrimony.errors.exception/-woua-s-d-k-exception/index.md)> |
