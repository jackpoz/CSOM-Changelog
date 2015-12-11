# Microsoft.SharePoint.Client.Search.Applications.dll v.16.1.0.0 API documentation

Created by 
[mddox](https://github.com/loxsmoke/mddox) on 06/04/2023

# All types

|   |   |   |
|---|---|---|
| [AnalyticsItemData Class](#analyticsitemdata-class) | [UsageAnalytics Class](#usageanalytics-class) |   |
| [AnalyticsItemDataPropertyNames Class](#analyticsitemdatapropertynames-class) | [ScriptTypeFactory Class](#scripttypefactory-class) |   |
# AnalyticsItemData Class

Namespace: Microsoft.SharePoint.Client.Search.Analytics

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **LastProcessingTime** | DateTime |  |
| **TotalHits** | int |  |
| **TotalUniqueUsers** | int |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **AnalyticsItemData(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetHitCountForDay(DateTime day)** | ClientResult\<int\> |  |
| **GetHitCountForMonth(DateTime month)** | ClientResult\<int\> |  |
| **GetUniqueUsersCountForDay(DateTime day)** | ClientResult\<int\> |  |
| **GetUniqueUsersCountForMonth(DateTime month)** | ClientResult\<int\> |  |
# AnalyticsItemDataPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Search.Analytics


## Fields

| Name | Type | Summary |
|---|---|---|
| **LastProcessingTime** | string |  |
| **TotalHits** | string |  |
| **TotalUniqueUsers** | string |  |
# UsageAnalytics Class

Namespace: Microsoft.SharePoint.Client.Search.Analytics

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **UsageAnalytics(ClientRuntimeContext context, Site site)** |  |
| **UsageAnalytics(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteCustomEventUsageData(Guid appEventTypeId)** | void |  |
| **DeleteStandardEventUsageData(int eventType)** | void |  |
| **GetAnalyticsItemData(int eventType, ListItem listItem)** | [AnalyticsItemData](#analyticsitemdata-class) |  |
| **GetAnalyticsItemDataForApplicationEventType(Guid appEventType, ListItem listItem)** | [AnalyticsItemData](#analyticsitemdata-class) |  |
# ScriptTypeFactory Class

Namespace: Microsoft.SharePoint.Client.Search.Applications


## Methods

| Name | Returns | Summary |
|---|---|---|
| **CreateObjectFromScriptType(string scriptType, ClientRuntimeContext context)** | IFromJson |  |
