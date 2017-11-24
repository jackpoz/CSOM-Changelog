# Microsoft.SharePoint.Client.Search.dll v.16.1.0.0 API documentation

Created by 
[mddox](https://github.com/loxsmoke/mddox) on 06/04/2023

# All types

|   |   |   |
|---|---|---|
| [SearchTenantSettings Class](#searchtenantsettings-class) | [PushTenantServiceInfo Class](#pushtenantserviceinfo-class) | [QueryPropertyValue Class](#querypropertyvalue-class) |
| [ContextCondition Class](#contextcondition-class) | [PushTenantServiceInfoPropertyNames Class](#pushtenantserviceinfopropertynames-class) | [QueryPropertyValueType Enum](#querypropertyvaluetype-enum) |
| [ExpandedQueryParameters Class](#expandedqueryparameters-class) | [SearchConfigurationPortability Class](#searchconfigurationportability-class) | [QuerySuggestionQuery Class](#querysuggestionquery-class) |
| [PromotedResultQueryRule Class](#promotedresultqueryrule-class) | [SearchConfigurationPortabilityPropertyNames Class](#searchconfigurationportabilitypropertynames-class) | [QuerySuggestionRange Class](#querysuggestionrange-class) |
| [PromotedResults Class](#promotedresults-class) | [KeywordQuery Class](#keywordquery-class) | [QuerySuggestionResults Class](#querysuggestionresults-class) |
| [PromotedResultsOperationsResult Class](#promotedresultsoperationsresult-class) | [KeywordQueryObjectPropertyNames Class](#keywordqueryobjectpropertynames-class) | [QueryUtility Class](#queryutility-class) |
| [QueryCondition Class](#querycondition-class) | [KeywordQueryProperties Class](#keywordqueryproperties-class) | [RankingLabeling Class](#rankinglabeling-class) |
| [QueryConfiguration Class](#queryconfiguration-class) | [KeywordQueryPropertyNames Class](#keywordquerypropertynames-class) | [ReorderingRule Class](#reorderingrule-class) |
| [QueryContext Class](#querycontext-class) | [KnownTableTypes Class](#knowntabletypes-class) | [ReorderingRuleCollection Class](#reorderingrulecollection-class) |
| [SearchEndpoints Class](#searchendpoints-class) | [PersonalResultSuggestion Class](#personalresultsuggestion-class) | [ReorderingRuleMatchType Enum](#reorderingrulematchtype-enum) |
| [SearchObjectOwnerResult Class](#searchobjectownerresult-class) | [PopularQuery Class](#popularquery-class) | [ResultTable Class](#resulttable-class) |
| [ControlMessage Class](#controlmessage-class) | [Query Class](#query-class) | [ResultTableCollection Class](#resulttablecollection-class) |
| [MessageLevel Enum](#messagelevel-enum) | [QueryAutoCompletion Class](#queryautocompletion-class) | [ScriptTypeFactory Class](#scripttypefactory-class) |
| [DocumentCrawlLog Class](#documentcrawllog-class) | [QueryAutoCompletionMatch Class](#queryautocompletionmatch-class) | [SearchExecutor Class](#searchexecutor-class) |
| [SearchObjectLevel Enum](#searchobjectlevel-enum) | [QueryAutoCompletionResults Class](#queryautocompletionresults-class) | [Sort Class](#sort-class) |
| [SearchObjectOwner Class](#searchobjectowner-class) | [QueryObjectPropertyNames Class](#queryobjectpropertynames-class) | [SortCollection Class](#sortcollection-class) |
| [CertificateService Class](#certificateservice-class) | [QueryPersonalizationData Class](#querypersonalizationdata-class) | [SortDirection Enum](#sortdirection-enum) |
| [PushTenantManager Class](#pushtenantmanager-class) | [QueryPropertyNames Class](#querypropertynames-class) | [StringCollection Class](#stringcollection-class) |
# SearchTenantSettings Class

Namespace: Microsoft.Office.Server.Search.lib.OM.SearchSubscriptionSettings

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
| **SearchTenantSettings(ClientRuntimeContext context, ObjectPath objectPath)** |  |
| **SearchTenantSettings(ClientRuntimeContext context, Guid tenantId, Guid realmId, bool isActive, bool isReadonly, long settingsVersion, DateTime lastUpdateTimeUtc, IDictionary\<string, Object\> settings)** |  |
# ContextCondition Class

Namespace: Microsoft.Office.Server.Search.REST

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ContextConditionType** | string |  |
| **SourceId** | Guid |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# ExpandedQueryParameters Class

Namespace: Microsoft.Office.Server.Search.REST

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Properties** | IDictionary\<string, Object\> |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# PromotedResultQueryRule Class

Namespace: Microsoft.Office.Server.Search.REST

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Contact** | string |  |
| **ContextConditions** | IList\<[ContextCondition](#contextcondition-class)\> |  |
| **CreationDate** | DateTime |  |
| **DisplayName** | string |  |
| **EndDate** | DateTime |  |
| **IsPromotedResultsOnly** | bool |  |
| **LastModifiedDate** | DateTime |  |
| **PromotedResults** | IList\<[PromotedResults](#promotedresults-class)\> |  |
| **QueryConditions** | IList\<[QueryCondition](#querycondition-class)\> |  |
| **ReviewDate** | DateTime |  |
| **StartDate** | DateTime |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# PromotedResults Class

Namespace: Microsoft.Office.Server.Search.REST

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Description** | string |  |
| **IsVisual** | bool |  |
| **LastModifiedTime** | DateTime |  |
| **Title** | string |  |
| **Url** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# PromotedResultsOperationsResult Class

Namespace: Microsoft.Office.Server.Search.REST

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Result** | IList\<[PromotedResultQueryRule](#promotedresultqueryrule-class)\> |  |
| **SearchObjectOwner** | [SearchObjectOwnerResult](#searchobjectownerresult-class) |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# QueryCondition Class

Namespace: Microsoft.Office.Server.Search.REST

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **LCID** | int |  |
| **MatchingOptions** | string |  |
| **QueryConditionType** | string |  |
| **SubjectTermsOrigin** | string |  |
| **Terms** | IList\<string\> |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# QueryConfiguration Class

Namespace: Microsoft.Office.Server.Search.REST

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **QueryContext** | [QueryContext](#querycontext-class) |  |
| **QueryParameters** | [ExpandedQueryParameters](#expandedqueryparameters-class) |  |
| **SearchEndpoints** | [SearchEndpoints](#searchendpoints-class) |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# QueryContext Class

Namespace: Microsoft.Office.Server.Search.REST

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **SpSiteId** | Guid |  |
| **SpWebId** | Guid |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SearchEndpoints Class

Namespace: Microsoft.Office.Server.Search.REST

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AdminEndpoint** | string |  |
| **AfdEndpoint** | string |  |
| **QueryEndpoint** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SearchObjectOwnerResult Class

Namespace: Microsoft.Office.Server.Search.REST

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **SiteCollectionId** | string |  |
| **SiteId** | string |  |
| **TenantId** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# ControlMessage Class

Namespace: Microsoft.Office.Server.Search.WebControls

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **code** | int |  |
| **correlationID** | string |  |
| **encodeDetails** | bool |  |
| **header** | string |  |
| **level** | [MessageLevel](#messagelevel-enum) |  |
| **messageDetails** | string |  |
| **messageDetailsForViewers** | string |  |
| **serverTypeId** | string |  |
| **showForViewerUsers** | bool |  |
| **showInEditModeOnly** | bool |  |
| **stackTrace** | string |  |
| **type** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# MessageLevel Enum

Namespace: Microsoft.Office.Server.Search.WebControls


## Values

| Name | Summary |
|---|---|
| **Information** |  |
| **Warning** |  |
| **Error** |  |
# DocumentCrawlLog Class

Namespace: Microsoft.SharePoint.Client.Search.Administration

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
| **DocumentCrawlLog(ClientRuntimeContext context, Site site)** |  |
| **DocumentCrawlLog(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetCrawledUrls(bool getCountOnly, long maxRows, string queryString, bool isLike, int contentSourceID, int errorLevel, int errorID, DateTime startDateTime, DateTime endDateTime)** | ClientResult\<SimpleDataTable\> |  |
# SearchObjectLevel Enum

Namespace: Microsoft.SharePoint.Client.Search.Administration


## Values

| Name | Summary |
|---|---|
| **SPWeb** |  |
| **SPSite** |  |
| **SPSiteSubscription** |  |
| **Ssa** |  |
# SearchObjectOwner Class

Namespace: Microsoft.SharePoint.Client.Search.Administration

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
| **SearchObjectOwner(ClientRuntimeContext context, SearchObjectLevel lowestCurrentLevelToUse)** |  |
| **SearchObjectOwner(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# CertificateService Class

Namespace: Microsoft.SharePoint.Client.Search.ContentPush

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
| **CertificateService(ClientRuntimeContext context)** |  |
| **CertificateService(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **CertificateSettings()** | ClientResult\<IDictionary\<string, Object\>\> |  |
| **ValidContentEncryptionCertificates()** | IEnumerable\<byte[]\> |  |
# PushTenantManager Class

Namespace: Microsoft.SharePoint.Client.Search.ContentPush

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
| **PushTenantManager(ClientRuntimeContext context)** |  |
| **PushTenantManager(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteAllCloudHybridSearchContent()** | ClientResult\<long\> |  |
| **GetPushServiceInfo()** | [PushTenantServiceInfo](#pushtenantserviceinfo-class) |  |
| **GetTenantInfo()** | [PushTenantServiceInfo](#pushtenantserviceinfo-class) |  |
| **PreparePushTenant()** | void |  |
# PushTenantServiceInfo Class

Namespace: Microsoft.SharePoint.Client.Search.ContentPush

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AuthenticationRealm** | string |  |
| **EndpointAddress** | string |  |
| **ServiceProperties** | IDictionary\<string, Object\> |  |
| **TenantId** | string |  |
| **ValidContentEncryptionCertificates** | IEnumerable\<byte[]\> |  |
| **ValidUntil** | DateTime |  |
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
| **PushTenantServiceInfo(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# PushTenantServiceInfoPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Search.ContentPush


## Fields

| Name | Type | Summary |
|---|---|---|
| **AuthenticationRealm** | string |  |
| **EndpointAddress** | string |  |
| **ServiceProperties** | string |  |
| **TenantId** | string |  |
| **ValidContentEncryptionCertificates** | string |  |
| **ValidUntil** | string |  |
# SearchConfigurationPortability Class

Namespace: Microsoft.SharePoint.Client.Search.Portability

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ImportWarnings** | string |  |
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
| **SearchConfigurationPortability(ClientRuntimeContext context)** |  |
| **SearchConfigurationPortability(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteSearchConfiguration(SearchObjectOwner owningScope, string searchConfiguration)** | void |  |
| **ExportSearchConfiguration(SearchObjectOwner owningScope)** | ClientResult\<string\> |  |
| **ImportSearchConfiguration(SearchObjectOwner owningScope, string searchConfiguration)** | void |  |
# SearchConfigurationPortabilityPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Search.Portability


## Fields

| Name | Type | Summary |
|---|---|---|
| **ImportWarnings** | string |  |
# KeywordQuery Class

Namespace: Microsoft.SharePoint.Client.Search.Query

Base class: [Query](#query-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **CollapseSpecification** | string |  |
| **EnableSorting** | bool |  |
| **HiddenConstraints** | string |  |
| **Properties** | [KeywordQueryProperties](#keywordqueryproperties-class) |  |
| **OLSQuerySession** | string |  |
| **RefinementFilters** | [StringCollection](#stringcollection-class) |  |
| **Refiners** | string |  |
| **ReorderingRules** | [ReorderingRuleCollection](#reorderingrulecollection-class) |  |
| **SelectProperties** | [StringCollection](#stringcollection-class) |  |
| **SortList** | [SortCollection](#sortcollection-class) |  |
| **TimeZoneId** | int |  |
| **TrimDuplicatesIncludeId** | long |  |
| **UseOLSQuery** | int |  |
| **BlockDedupeMode** | int |  |
| **BypassResultTypes** | bool |  |
| **ClientType** | string |  |
| **Culture** | int |  |
| **DesiredSnippetLength** | int |  |
| **EnableInterleaving** | bool |  |
| **EnableNicknames** | bool |  |
| **EnableOrderingHitHighlightedProperty** | bool |  |
| **EnablePhonetic** | bool |  |
| **EnableQueryRules** | bool |  |
| **EnableStemming** | bool |  |
| **GenerateBlockRankLog** | bool |  |
| **HitHighlightedMultivaluePropertyLimit** | int |  |
| **HitHighlightedProperties** | [StringCollection](#stringcollection-class) |  |
| **IgnoreSafeQueryPropertiesTemplateUrl** | bool |  |
| **ImpressionID** | string |  |
| **MaxSnippetLength** | int |  |
| **PersonalizationData** | [QueryPersonalizationData](#querypersonalizationdata-class) |  |
| **ProcessBestBets** | bool |  |
| **ProcessPersonalFavorites** | bool |  |
| **QueryTag** | string |  |
| **QueryTemplate** | string |  |
| **QueryTemplateParameters** | IDictionary\<string, bool\> |  |
| **QueryText** | string |  |
| **RankingModelId** | string |  |
| **ResultsUrl** | string |  |
| **RowLimit** | int |  |
| **RowsPerPage** | int |  |
| **SafeQueryPropertiesTemplateUrl** | string |  |
| **ShowPeopleNameSuggestions** | bool |  |
| **SourceId** | Guid |  |
| **StartRow** | int |  |
| **SummaryLength** | int |  |
| **Timeout** | int |  |
| **TotalRowsExactMinimum** | int |  |
| **TrimDuplicates** | bool |  |
| **UILanguage** | int |  |
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
| **KeywordQuery(ClientRuntimeContext context)** |  |
| **KeywordQuery(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# KeywordQueryObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Search.Query


## Fields

| Name | Type | Summary |
|---|---|---|
| **Properties** | string |  |
| **RefinementFilters** | string |  |
| **ReorderingRules** | string |  |
| **SelectProperties** | string |  |
| **SortList** | string |  |
# KeywordQueryProperties Class

Namespace: Microsoft.SharePoint.Client.Search.Query

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | Object |  |
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
| **KeywordQueryProperties(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetQueryPropertyValue(string name)** | ClientResult\<[QueryPropertyValue](#querypropertyvalue-class)\> |  |
| **SetQueryPropertyValue(string name, QueryPropertyValue val)** | void |  |
# KeywordQueryPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Search.Query


## Fields

| Name | Type | Summary |
|---|---|---|
| **CollapseSpecification** | string |  |
| **EnableSorting** | string |  |
| **HiddenConstraints** | string |  |
| **OLSQuerySession** | string |  |
| **Refiners** | string |  |
| **TimeZoneId** | string |  |
| **TrimDuplicatesIncludeId** | string |  |
| **UseOLSQuery** | string |  |
# KnownTableTypes Class

Namespace: Microsoft.SharePoint.Client.Search.Query


## Methods

| Name | Returns | Summary |
|---|---|---|
| **IsKnownTableType(string tableType)** | bool |  |
## Fields

| Name | Type | Summary |
|---|---|---|
| **RelevantResults** | string |  |
| **SpecialTermResults** | string |  |
| **DefinitionResults** | string |  |
| **RefinementResults** | string |  |
| **InterleavingInformation** | string |  |
| **PersonalFavoriteResults** | string |  |
# PersonalResultSuggestion Class

Namespace: Microsoft.SharePoint.Client.Search.Query

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **HighlightedTitle** | string |  |
| **IsBestBet** | bool |  |
| **Title** | string |  |
| **Url** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# PopularQuery Class

Namespace: Microsoft.SharePoint.Client.Search.Query

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ClickCount** | int |  |
| **LCID** | int |  |
| **QueryCount** | int |  |
| **QueryText** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# Query Class

Namespace: Microsoft.SharePoint.Client.Search.Query

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **BlockDedupeMode** | int |  |
| **BypassResultTypes** | bool |  |
| **ClientType** | string |  |
| **Culture** | int |  |
| **DesiredSnippetLength** | int |  |
| **EnableInterleaving** | bool |  |
| **EnableNicknames** | bool |  |
| **EnableOrderingHitHighlightedProperty** | bool |  |
| **EnablePhonetic** | bool |  |
| **EnableQueryRules** | bool |  |
| **EnableStemming** | bool |  |
| **GenerateBlockRankLog** | bool |  |
| **HitHighlightedMultivaluePropertyLimit** | int |  |
| **HitHighlightedProperties** | [StringCollection](#stringcollection-class) |  |
| **IgnoreSafeQueryPropertiesTemplateUrl** | bool |  |
| **ImpressionID** | string |  |
| **MaxSnippetLength** | int |  |
| **PersonalizationData** | [QueryPersonalizationData](#querypersonalizationdata-class) |  |
| **ProcessBestBets** | bool |  |
| **ProcessPersonalFavorites** | bool |  |
| **QueryTag** | string |  |
| **QueryTemplate** | string |  |
| **QueryTemplateParameters** | IDictionary\<string, bool\> |  |
| **QueryText** | string |  |
| **RankingModelId** | string |  |
| **ResultsUrl** | string |  |
| **RowLimit** | int |  |
| **RowsPerPage** | int |  |
| **SafeQueryPropertiesTemplateUrl** | string |  |
| **ShowPeopleNameSuggestions** | bool |  |
| **SourceId** | Guid |  |
| **StartRow** | int |  |
| **SummaryLength** | int |  |
| **Timeout** | int |  |
| **TotalRowsExactMinimum** | int |  |
| **TrimDuplicates** | bool |  |
| **UILanguage** | int |  |
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
| **Query(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetQueryCompletions(int numberOfCompletions, string selectedSources, int cursorPosition)** | ClientResult\<[QueryAutoCompletionResults](#queryautocompletionresults-class)\> |  |
| **GetQuerySuggestionsWithResults(int iNumberOfQuerySuggestions, int iNumberOfResultSuggestions, bool fPreQuerySuggestions, bool fHitHighlighting, bool fCapitalizeFirstLetters, bool fPrefixMatchAllTerms)** | ClientResult\<[QuerySuggestionResults](#querysuggestionresults-class)\> |  |
# QueryAutoCompletion Class

Namespace: Microsoft.SharePoint.Client.Search.Query

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Matches** | IEnumerable\<[QueryAutoCompletionMatch](#queryautocompletionmatch-class)\> |  |
| **Query** | string |  |
| **Score** | double |  |
| **Source** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# QueryAutoCompletionMatch Class

Namespace: Microsoft.SharePoint.Client.Search.Query

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Alternation** | bool |  |
| **Key** | string |  |
| **Length** | long |  |
| **MatchType** | string |  |
| **Score** | double |  |
| **SourceName** | string |  |
| **Start** | long |  |
| **Value** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# QueryAutoCompletionResults Class

Namespace: Microsoft.SharePoint.Client.Search.Query

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **CoreExecutionTimeMs** | long |  |
| **CorrelationId** | string |  |
| **Queries** | IEnumerable\<[QueryAutoCompletion](#queryautocompletion-class)\> |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# QueryObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Search.Query


## Fields

| Name | Type | Summary |
|---|---|---|
| **HitHighlightedProperties** | string |  |
| **PersonalizationData** | string |  |
# QueryPersonalizationData Class

Namespace: Microsoft.SharePoint.Client.Search.Query

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
| **QueryPersonalizationData(ClientRuntimeContext context, string guidUserIdString)** |  |
| **QueryPersonalizationData(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# QueryPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Search.Query


## Fields

| Name | Type | Summary |
|---|---|---|
| **BlockDedupeMode** | string |  |
| **BypassResultTypes** | string |  |
| **ClientType** | string |  |
| **Culture** | string |  |
| **DesiredSnippetLength** | string |  |
| **EnableInterleaving** | string |  |
| **EnableNicknames** | string |  |
| **EnableOrderingHitHighlightedProperty** | string |  |
| **EnablePhonetic** | string |  |
| **EnableQueryRules** | string |  |
| **EnableStemming** | string |  |
| **GenerateBlockRankLog** | string |  |
| **HitHighlightedMultivaluePropertyLimit** | string |  |
| **IgnoreSafeQueryPropertiesTemplateUrl** | string |  |
| **ImpressionID** | string |  |
| **MaxSnippetLength** | string |  |
| **ProcessBestBets** | string |  |
| **ProcessPersonalFavorites** | string |  |
| **QueryTag** | string |  |
| **QueryTemplate** | string |  |
| **QueryTemplateParameters** | string |  |
| **QueryText** | string |  |
| **RankingModelId** | string |  |
| **ResultsUrl** | string |  |
| **RowLimit** | string |  |
| **RowsPerPage** | string |  |
| **SafeQueryPropertiesTemplateUrl** | string |  |
| **ShowPeopleNameSuggestions** | string |  |
| **SourceId** | string |  |
| **StartRow** | string |  |
| **SummaryLength** | string |  |
| **Timeout** | string |  |
| **TotalRowsExactMinimum** | string |  |
| **TrimDuplicates** | string |  |
| **UILanguage** | string |  |
# QueryPropertyValue Class

Namespace: Microsoft.SharePoint.Client.Search.Query

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **BoolVal** | bool |  |
| **IntVal** | int |  |
| **QueryPropertyValueTypeIndex** | int |  |
| **StrArray** | string[] |  |
| **StrVal** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# QueryPropertyValueType Enum

Namespace: Microsoft.SharePoint.Client.Search.Query


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **StringType** |  |
| **Int32TYpe** |  |
| **BooleanType** |  |
| **StringArrayType** |  |
| **UnSupportedType** |  |
# QuerySuggestionQuery Class

Namespace: Microsoft.SharePoint.Client.Search.Query

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **IsPersonal** | bool |  |
| **Query** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# QuerySuggestionRange Class

Namespace: Microsoft.SharePoint.Client.Search.Query

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Length** | int |  |
| **Start** | int |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# QuerySuggestionResults Class

Namespace: Microsoft.SharePoint.Client.Search.Query

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **PeopleNames** | string[] |  |
| **PersonalResults** | [PersonalResultSuggestion](#personalresultsuggestion-class)[] |  |
| **Queries** | [QuerySuggestionQuery](#querysuggestionquery-class)[] |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# QueryUtility Class

Namespace: Microsoft.SharePoint.Client.Search.Query


## Methods

| Name | Returns | Summary |
|---|---|---|
| **Create(string name, Object val)** | [QueryPropertyValue](#querypropertyvalue-class) |  |
| **GetQueryPropertyValueType(QueryPropertyValue val)** | [QueryPropertyValueType](#querypropertyvaluetype-enum) |  |
| **QueryPropertyValueToObject(QueryPropertyValue val)** | Object |  |
# RankingLabeling Class

Namespace: Microsoft.SharePoint.Client.Search.Query

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
| **RankingLabeling(ClientRuntimeContext context)** |  |
| **RankingLabeling(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **AddJudgment(string userQuery, string url, short labelId)** | void |  |
| **GetJudgementsForQuery(string query)** | ClientResult\<IDictionary\<string, int\>\> |  |
| **NormalizeResultUrl(string url)** | ClientResult\<string\> |  |
# ReorderingRule Class

Namespace: Microsoft.SharePoint.Client.Search.Query

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Boost** | int |  |
| **MatchType** | [ReorderingRuleMatchType](#reorderingrulematchtype-enum) |  |
| **MatchValue** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# ReorderingRuleCollection Class

Namespace: Microsoft.SharePoint.Client.Search.Query

Base class: ClientObjectCollection<[ReorderingRule](#reorderingrule-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [ReorderingRule](#reorderingrule-class) |  |
| **ElementType** | Type |  |
| **Expression** | Expression |  |
| **Provider** | IQueryProvider |  |
| **AreItemsAvailable** | bool |  |
| **Count** | int |  |
| **Data** | List\<Object\> |  |
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
| **ReorderingRuleCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(ReorderingRuleMatchType matchType, string matchValue, int boost)** | void |  |
| **Clear()** | void |  |
# ReorderingRuleMatchType Enum

Namespace: Microsoft.SharePoint.Client.Search.Query


## Values

| Name | Summary |
|---|---|
| **ResultContainsKeyword** |  |
| **TitleContainsKeyword** |  |
| **TitleMatchesKeyword** |  |
| **UrlStartsWith** |  |
| **UrlExactlyMatches** |  |
| **ContentTypeIs** |  |
| **FileExtensionMatches** |  |
| **ResultHasTag** |  |
| **ManualCondition** |  |
# ResultTable Class

Namespace: Microsoft.SharePoint.Client.Search.Query

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **GroupTemplateId** | string |  |
| **ItemTemplateId** | string |  |
| **Properties** | IDictionary\<string, Object\> |  |
| **QueryId** | string |  |
| **QueryRuleId** | string |  |
| **ResultRows** | IEnumerable\<IDictionary\<string, Object\>\> |  |
| **ResultTitle** | string |  |
| **ResultTitleUrl** | string |  |
| **RowCount** | int |  |
| **TableType** | string |  |
| **TotalRows** | int |  |
| **TotalRowsIncludingDuplicates** | int |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# ResultTableCollection Class

Namespace: Microsoft.SharePoint.Client.Search.Query

Base class: ClientValueObjectCollection<[ResultTable](#resulttable-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **ElapsedTime** | int |  |
| **Properties** | IDictionary\<string, Object\> |  |
| **QueryErrors** | IDictionary\<string, [ControlMessage](#controlmessage-class)\> |  |
| **QueryId** | string |  |
| **SpellingSuggestion** | string |  |
| **TriggeredRules** | IList\<Guid\> |  |
| **TypeId** | string |  |
| **ChildItemsName** | string |  |
| **Count** | int |  |
| **Item** | [ResultTable](#resulttable-class) |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# ScriptTypeFactory Class

Namespace: Microsoft.SharePoint.Client.Search.Query


## Methods

| Name | Returns | Summary |
|---|---|---|
| **CreateObjectFromScriptType(string scriptType, ClientRuntimeContext context)** | IFromJson |  |
# SearchExecutor Class

Namespace: Microsoft.SharePoint.Client.Search.Query

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
| **SearchExecutor(ClientRuntimeContext context)** |  |
| **SearchExecutor(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **ExecuteQueries(string[] queryIds, Query[] queries, bool handleExceptions)** | ClientResult\<IDictionary\<string, [ResultTableCollection](#resulttablecollection-class)\>\> |  |
| **ExecuteQuery(Query query)** | ClientResult\<[ResultTableCollection](#resulttablecollection-class)\> |  |
| **ExportPopularQueries(Web web, Guid sourceId)** | IList\<[PopularQuery](#popularquery-class)\> |  |
| **GetPromotedResults(bool siteCollectionLevel, int offset, int numberOfRules)** | ClientResult\<[PromotedResultsOperationsResult](#promotedresultsoperationsresult-class)\> |  |
| **GetQueryConfiguration()** | ClientResult\<[QueryConfiguration](#queryconfiguration-class)\> |  |
| **RecordPageClick(string pageInfo, string clickType, int blockType, string clickedResultId, int subResultIndex, string immediacySourceId, string immediacyQueryString, string immediacyTitle, string immediacyUrl)** | void |  |
# Sort Class

Namespace: Microsoft.SharePoint.Client.Search.Query

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Direction** | [SortDirection](#sortdirection-enum) |  |
| **Property** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SortCollection Class

Namespace: Microsoft.SharePoint.Client.Search.Query

Base class: ClientObjectCollection<[Sort](#sort-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [Sort](#sort-class) |  |
| **ElementType** | Type |  |
| **Expression** | Expression |  |
| **Provider** | IQueryProvider |  |
| **AreItemsAvailable** | bool |  |
| **Count** | int |  |
| **Data** | List\<Object\> |  |
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
| **SortCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(string strProperty, SortDirection direction)** | void |  |
| **Clear()** | void |  |
# SortDirection Enum

Namespace: Microsoft.SharePoint.Client.Search.Query


## Values

| Name | Summary |
|---|---|
| **Ascending** |  |
| **Descending** |  |
| **FQLFormula** |  |
# StringCollection Class

Namespace: Microsoft.SharePoint.Client.Search.Query

Base class: ClientObjectCollection<string>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | string |  |
| **ElementType** | Type |  |
| **Expression** | Expression |  |
| **Provider** | IQueryProvider |  |
| **AreItemsAvailable** | bool |  |
| **Count** | int |  |
| **Data** | List\<Object\> |  |
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
| **StringCollection(ClientRuntimeContext context)** |  |
| **StringCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(string property)** | void |  |
| **Clear()** | void |  |
