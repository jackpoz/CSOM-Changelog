# Microsoft.Office.SharePoint.Tools.dll v.16.1.0.0 API documentation

Created by 
[mddox](https://github.com/loxsmoke/mddox) on 2024-10-15

# All types

|   |   |   |
|---|---|---|
| [AccessControlEntry Class](#accesscontrolentry-class) | [HttpHeader Class](#httpheader-class) | [ODataAutogenException Class](#odataautogenexception-class) |
| [Action Class](#action-class) | [HttpMethods Class](#httpmethods-class) | [ODataBdcArtifactGenerator Class](#odatabdcartifactgenerator-class) |
| [ActionParameter Class](#actionparameter-class) | [Identifier Class](#identifier-class) | [ODataBdcMethodGenerator Class](#odatabdcmethodgenerator-class) |
| [Association Class](#association-class) | [IdentifierType Enum](#identifiertype-enum) | [ODataBdcModelGenerator Class](#odatabdcmodelgenerator-class) |
| [AssociationDetail Class](#associationdetail-class) | [IndividuallySecurableMetadataObject Class](#individuallysecurablemetadataobject-class) | [ODataEntityUriHelper Class](#odataentityurihelper-class) |
| [AssociationGroup Class](#associationgroup-class) | [LobDateTimeMode Enum](#lobdatetimemode-enum) | [OperationModeType Enum](#operationmodetype-enum) |
| [AssociationReference Class](#associationreference-class) | [LobSystem Class](#lobsystem-class) | [Parameter Class](#parameter-class) |
| [BdcConstants Class](#bdcconstants-class) | [LobSystemInstance Class](#lobsysteminstance-class) | [ParameterDirection Enum](#parameterdirection-enum) |
| [BdcMetadataFactory Class](#bdcmetadatafactory-class) | [LobSystemType Enum](#lobsystemtype-enum) | [PayloadKind Enum](#payloadkind-enum) |
| [BdcRightName Enum](#bdcrightname-enum) | [LocalizedDisplayName Class](#localizeddisplayname-class) | [Property Class](#property-class) |
| [ColumnHelper Class](#columnhelper-class) | [MetadataObject Class](#metadataobject-class) | [ResourceIds Class](#resourceids-class) |
| [ConvertType Class](#converttype-class) | [Method Class](#method-class) | [Resources Class](#resources-class) |
| [DefaultValue Class](#defaultvalue-class) | [MethodInstance Class](#methodinstance-class) | [Right Class](#right-class) |
| [DestinationEntity Class](#destinationentity-class) | [MethodInstanceType Enum](#methodinstancetype-enum) | [SourceEntity Class](#sourceentity-class) |
| [EdmHelper Class](#edmhelper-class) | [MethodNames Class](#methodnames-class) | [StringNormalizeMode Enum](#stringnormalizemode-enum) |
| [Entity Class](#entity-class) | [MimeConstants Class](#mimeconstants-class) | [SystemFilterFactory Class](#systemfilterfactory-class) |
| [EntityMetadata Class](#entitymetadata-class) | [Model Class](#model-class) | [SystemFilterType Enum](#systemfiltertype-enum) |
| [FilterDescriptor Class](#filterdescriptor-class) | [NormalizeDateTime Class](#normalizedatetime-class) | [TypeConstants Class](#typeconstants-class) |
| [FilterDescriptorType Enum](#filterdescriptortype-enum) | [NormalizeString Class](#normalizestring-class) | [TypeDescriptor Class](#typedescriptor-class) |
| [FilterNames Class](#filternames-class) | [ODataAutoGen Class](#odataautogen-class) | [UserFilterFactory Class](#userfilterfactory-class) |
| [FunctionMetadata Class](#functionmetadata-class) | [ODataAutogenConstants Class](#odataautogenconstants-class) | [UserFilterType Enum](#userfiltertype-enum) |
# AccessControlEntry Class

Namespace: Microsoft.Office.SharePoint.Tools


## Properties

| Name | Type | Summary |
|---|---|---|
| **Right** | [Right](#right-class)[] |  |
| **Principal** | string |  |
# Action Class

Namespace: Microsoft.Office.SharePoint.Tools

Base class: [MetadataObject](#metadataobject-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **ActionParameters** | [ActionParameter](#actionparameter-class)[] |  |
| **Position** | string |  |
| **IsOpenedInNewWindow** | bool |  |
| **Url** | string |  |
| **ImageUrl** | string |  |
| **LocalizedDisplayNames** | [LocalizedDisplayName](#localizeddisplayname-class)[] |  |
| **Properties** | [Property](#property-class)[] |  |
| **Name** | string |  |
| **DefaultDisplayName** | string |  |
| **IsCached** | bool |  |
# ActionParameter Class

Namespace: Microsoft.Office.SharePoint.Tools

Base class: [MetadataObject](#metadataobject-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **Index** | string |  |
| **LocalizedDisplayNames** | [LocalizedDisplayName](#localizeddisplayname-class)[] |  |
| **Properties** | [Property](#property-class)[] |  |
| **Name** | string |  |
| **DefaultDisplayName** | string |  |
| **IsCached** | bool |  |
# Association Class

Namespace: Microsoft.Office.SharePoint.Tools

Base class: [MethodInstance](#methodinstance-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **SourceEntity** | [SourceEntity](#sourceentity-class)[] |  |
| **DestinationEntity** | [DestinationEntity](#destinationentity-class) |  |
| **Type** | [MethodInstanceType](#methodinstancetype-enum) |  |
| **Default** | bool |  |
| **ReturnParameterName** | string |  |
| **ReturnTypeDescriptorName** | string |  |
| **ReturnTypeDescriptorLevel** | string |  |
| **ReturnTypeDescriptorPath** | string |  |
| **AccessControlList** | [AccessControlEntry](#accesscontrolentry-class)[] |  |
| **LocalizedDisplayNames** | [LocalizedDisplayName](#localizeddisplayname-class)[] |  |
| **Properties** | [Property](#property-class)[] |  |
| **Name** | string |  |
| **DefaultDisplayName** | string |  |
| **IsCached** | bool |  |
# AssociationDetail Class

Namespace: Microsoft.Office.SharePoint.Tools


## Properties

| Name | Type | Summary |
|---|---|---|
| **SourceMetadata** | [EntityMetadata](#entitymetadata-class) |  |
| **DestinationMetadata** | [EntityMetadata](#entitymetadata-class) |  |
| **SourceName** | string |  |
| **DestinationName** | string |  |
| **DestinationEntityTypeName** | string |  |
| **DestinationProperties** | IEnumerable\<IEdmStructuralProperty\> |  |
| **AssociationMultiplicity** | EdmMultiplicity |  |
| **AssociationFunctionName** | string |  |
## Constructors

| Name | Summary |
|---|---|
| **AssociationDetail(EntityMetadata srcMetadata, EntityMetadata destMetadata, IEdmNavigationProperty edmNavProperty)** |  |
# AssociationGroup Class

Namespace: Microsoft.Office.SharePoint.Tools

Base class: [MetadataObject](#metadataobject-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **AssociationReference** | [AssociationReference](#associationreference-class)[] |  |
| **LocalizedDisplayNames** | [LocalizedDisplayName](#localizeddisplayname-class)[] |  |
| **Properties** | [Property](#property-class)[] |  |
| **Name** | string |  |
| **DefaultDisplayName** | string |  |
| **IsCached** | bool |  |
# AssociationReference Class

Namespace: Microsoft.Office.SharePoint.Tools


## Properties

| Name | Type | Summary |
|---|---|---|
| **EntityNamespace** | string |  |
| **EntityName** | string |  |
| **AssociationName** | string |  |
| **Reverse** | bool |  |
# BdcConstants Class

Namespace: Microsoft.Office.SharePoint.Tools


## Fields

| Name | Type | Summary |
|---|---|---|
| **ODataRequestHeaderPropertyName** | string |  |
| **ODataServiceMetadataUrlPropertyName** | string |  |
| **ODataMetadataAuthenticationModePropertyName** | string |  |
| **ODataServiceUrlPropertyName** | string |  |
| **ODataServiceAuthenticationModePropertyName** | string |  |
| **ODataFormatPropertyName** | string |  |
| **ODataServicesVersionPropertyName** | string |  |
| **ODataRequiredInForms** | string |  |
| **ODataEntityUrlPropertyName** | string |  |
| **ODataFilterUrlPropertyName** | string |  |
| **ODataPayloadKindPropertyName** | string |  |
| **ODataHttpMethodPropertyName** | string |  |
| **ODataServiceOperationPropertyName** | string |  |
| **HttpHeaderSetAcceptLanguage** | string |  |
| **LogicalOperatorPropertyName** | string |  |
| **OrderPropertyName** | string |  |
# BdcMetadataFactory Class

Namespace: Microsoft.Office.SharePoint.Tools


# BdcRightName Enum

Namespace: Microsoft.Office.SharePoint.Tools


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **Execute** |  |
| **Edit** |  |
| **SetPermissions** |  |
| **SelectableInClients** |  |
# ColumnHelper Class

Namespace: Microsoft.Office.SharePoint.Tools


# ConvertType Class

Namespace: Microsoft.Office.SharePoint.Tools


## Properties

| Name | Type | Summary |
|---|---|---|
| **LOBType** | string |  |
| **BDCType** | string |  |
| **LOBLocale** | string |  |
# DefaultValue Class

Namespace: Microsoft.Office.SharePoint.Tools


## Properties

| Name | Type | Summary |
|---|---|---|
| **MethodInstanceName** | string |  |
| **Type** | string |  |
| **Text** | string[] |  |
# DestinationEntity Class

Namespace: Microsoft.Office.SharePoint.Tools


## Properties

| Name | Type | Summary |
|---|---|---|
| **Namespace** | string |  |
| **Name** | string |  |
# EdmHelper Class

Namespace: Microsoft.Office.SharePoint.Tools


# Entity Class

Namespace: Microsoft.Office.SharePoint.Tools

Base class: [IndividuallySecurableMetadataObject](#individuallysecurablemetadataobject-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **Identifiers** | [Identifier](#identifier-class)[] |  |
| **Methods** | [Method](#method-class)[] |  |
| **AssociationGroups** | [AssociationGroup](#associationgroup-class)[] |  |
| **Actions** | [Action](#action-class)[] |  |
| **Namespace** | string |  |
| **Version** | string |  |
| **EstimatedInstanceCount** | string |  |
| **DefaultOperationMode** | [OperationModeType](#operationmodetype-enum) |  |
| **AccessControlList** | [AccessControlEntry](#accesscontrolentry-class)[] |  |
| **LocalizedDisplayNames** | [LocalizedDisplayName](#localizeddisplayname-class)[] |  |
| **Properties** | [Property](#property-class)[] |  |
| **Name** | string |  |
| **DefaultDisplayName** | string |  |
| **IsCached** | bool |  |
# EntityMetadata Class

Namespace: Microsoft.Office.SharePoint.Tools


## Properties

| Name | Type | Summary |
|---|---|---|
| **EntitySet** | IEdmEntitySet |  |
| **EntityType** | IEdmEntityType |  |
| **EntityName** | string |  |
| **EntityOriginalName** | string |  |
| **EntitySetName** | string |  |
| **KeyProperties** | IEnumerable\<IEdmStructuralProperty\> |  |
| **StructuralProperties** | IEnumerable\<IEdmStructuralProperty\> |  |
| **NavigationProperties** | IEnumerable\<IEdmNavigationProperty\> |  |
## Constructors

| Name | Summary |
|---|---|
| **EntityMetadata(IEdmEntitySet entitySet)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **FindProperty(string propName)** | IEdmStructuralProperty |  |
| **IsKeyProperty(IEdmStructuralProperty property)** | bool |  |
# FilterDescriptor Class

Namespace: Microsoft.Office.SharePoint.Tools

Base class: [MetadataObject](#metadataobject-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **Type** | [FilterDescriptorType](#filterdescriptortype-enum) |  |
| **FilterField** | string |  |
| **LocalizedDisplayNames** | [LocalizedDisplayName](#localizeddisplayname-class)[] |  |
| **Properties** | [Property](#property-class)[] |  |
| **Name** | string |  |
| **DefaultDisplayName** | string |  |
| **IsCached** | bool |  |
# FilterDescriptorType Enum

Namespace: Microsoft.Office.SharePoint.Tools


## Values

| Name | Summary |
|---|---|
| **Limit** |  |
| **PageNumber** |  |
| **Wildcard** |  |
| **UserContext** |  |
| **UserCulture** |  |
| **Username** |  |
| **Password** |  |
| **LastId** |  |
| **SsoTicket** |  |
| **UserProfile** |  |
| **Comparison** |  |
| **Timestamp** |  |
| **Input** |  |
| **Output** |  |
| **InputOutput** |  |
| **Batching** |  |
| **BatchingTermination** |  |
| **ActivityId** |  |
| **Sorting** |  |
# FilterNames Class

Namespace: Microsoft.Office.SharePoint.Tools


## Fields

| Name | Type | Summary |
|---|---|---|
| **Default** | string |  |
| **ActivityId** | string |  |
| **UserContext** | string |  |
| **UserCulture** | string |  |
| **PageNumber** | string |  |
| **Limit** | string |  |
# FunctionMetadata Class

Namespace: Microsoft.Office.SharePoint.Tools


## Properties

| Name | Type | Summary |
|---|---|---|
| **Name** | string |  |
| **InputParameters** | IEnumerable\<IEdmFunctionParameter\> |  |
| **ReturnType** | IEdmTypeReference |  |
| **HttpMethod** | string |  |
## Constructors

| Name | Summary |
|---|---|
| **FunctionMetadata(IEdmModel odataEdmModel, IEdmFunctionImport import)** |  |
# HttpHeader Class

Namespace: Microsoft.Office.SharePoint.Tools


## Fields

| Name | Type | Summary |
|---|---|---|
| **AcceptLanguage** | string |  |
# HttpMethods Class

Namespace: Microsoft.Office.SharePoint.Tools


## Fields

| Name | Type | Summary |
|---|---|---|
| **Get** | string |  |
| **Put** | string |  |
| **Post** | string |  |
| **Delete** | string |  |
| **Merge** | string |  |
# Identifier Class

Namespace: Microsoft.Office.SharePoint.Tools

Base class: [MetadataObject](#metadataobject-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **TypeName** | [IdentifierType](#identifiertype-enum) |  |
| **LocalizedDisplayNames** | [LocalizedDisplayName](#localizeddisplayname-class)[] |  |
| **Properties** | [Property](#property-class)[] |  |
| **Name** | string |  |
| **DefaultDisplayName** | string |  |
| **IsCached** | bool |  |
# IdentifierType Enum

Namespace: Microsoft.Office.SharePoint.Tools


## Values

| Name | Summary |
|---|---|
| **SystemBoolean** |  |
| **SystemByte** |  |
| **SystemChar** |  |
| **SystemDateTime** |  |
| **SystemDecimal** |  |
| **SystemDouble** |  |
| **SystemGuid** |  |
| **SystemInt16** |  |
| **SystemInt32** |  |
| **SystemInt64** |  |
| **SystemSByte** |  |
| **SystemSingle** |  |
| **SystemString** |  |
| **SystemTimeSpan** |  |
| **SystemUInt16** |  |
| **SystemUInt32** |  |
| **SystemUInt64** |  |
# IndividuallySecurableMetadataObject Class

Namespace: Microsoft.Office.SharePoint.Tools

Base class: [MetadataObject](#metadataobject-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **AccessControlList** | [AccessControlEntry](#accesscontrolentry-class)[] |  |
| **LocalizedDisplayNames** | [LocalizedDisplayName](#localizeddisplayname-class)[] |  |
| **Properties** | [Property](#property-class)[] |  |
| **Name** | string |  |
| **DefaultDisplayName** | string |  |
| **IsCached** | bool |  |
# LobDateTimeMode Enum

Namespace: Microsoft.Office.SharePoint.Tools


## Values

| Name | Summary |
|---|---|
| **UTC** |  |
| **Local** |  |
| **Unspecified** |  |
# LobSystem Class

Namespace: Microsoft.Office.SharePoint.Tools

Base class: [IndividuallySecurableMetadataObject](#individuallysecurablemetadataobject-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **Proxy** | string |  |
| **LobSystemInstances** | [LobSystemInstance](#lobsysteminstance-class)[] |  |
| **Entities** | [Entity](#entity-class)[] |  |
| **Type** | [LobSystemType](#lobsystemtype-enum) |  |
| **AccessControlList** | [AccessControlEntry](#accesscontrolentry-class)[] |  |
| **LocalizedDisplayNames** | [LocalizedDisplayName](#localizeddisplayname-class)[] |  |
| **Properties** | [Property](#property-class)[] |  |
| **Name** | string |  |
| **DefaultDisplayName** | string |  |
| **IsCached** | bool |  |
# LobSystemInstance Class

Namespace: Microsoft.Office.SharePoint.Tools

Base class: [MetadataObject](#metadataobject-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **LocalizedDisplayNames** | [LocalizedDisplayName](#localizeddisplayname-class)[] |  |
| **Properties** | [Property](#property-class)[] |  |
| **Name** | string |  |
| **DefaultDisplayName** | string |  |
| **IsCached** | bool |  |
# LobSystemType Enum

Namespace: Microsoft.Office.SharePoint.Tools


## Values

| Name | Summary |
|---|---|
| **Database** |  |
| **DotNetAssembly** |  |
| **Wcf** |  |
| **WebService** |  |
| **Custom** |  |
| **OData** |  |
# LocalizedDisplayName Class

Namespace: Microsoft.Office.SharePoint.Tools


## Properties

| Name | Type | Summary |
|---|---|---|
| **LCID** | string |  |
| **Text** | string[] |  |
# MetadataObject Class

Namespace: Microsoft.Office.SharePoint.Tools


## Properties

| Name | Type | Summary |
|---|---|---|
| **LocalizedDisplayNames** | [LocalizedDisplayName](#localizeddisplayname-class)[] |  |
| **Properties** | [Property](#property-class)[] |  |
| **Name** | string |  |
| **DefaultDisplayName** | string |  |
| **IsCached** | bool |  |
# Method Class

Namespace: Microsoft.Office.SharePoint.Tools

Base class: [IndividuallySecurableMetadataObject](#individuallysecurablemetadataobject-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **FilterDescriptors** | [FilterDescriptor](#filterdescriptor-class)[] |  |
| **Parameters** | [Parameter](#parameter-class)[] |  |
| **MethodInstances** | [MethodInstance](#methodinstance-class)[] |  |
| **IsStatic** | bool |  |
| **LobName** | string |  |
| **AccessControlList** | [AccessControlEntry](#accesscontrolentry-class)[] |  |
| **LocalizedDisplayNames** | [LocalizedDisplayName](#localizeddisplayname-class)[] |  |
| **Properties** | [Property](#property-class)[] |  |
| **Name** | string |  |
| **DefaultDisplayName** | string |  |
| **IsCached** | bool |  |
# MethodInstance Class

Namespace: Microsoft.Office.SharePoint.Tools

Base class: [IndividuallySecurableMetadataObject](#individuallysecurablemetadataobject-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **Type** | [MethodInstanceType](#methodinstancetype-enum) |  |
| **Default** | bool |  |
| **ReturnParameterName** | string |  |
| **ReturnTypeDescriptorName** | string |  |
| **ReturnTypeDescriptorLevel** | string |  |
| **ReturnTypeDescriptorPath** | string |  |
| **AccessControlList** | [AccessControlEntry](#accesscontrolentry-class)[] |  |
| **LocalizedDisplayNames** | [LocalizedDisplayName](#localizeddisplayname-class)[] |  |
| **Properties** | [Property](#property-class)[] |  |
| **Name** | string |  |
| **DefaultDisplayName** | string |  |
| **IsCached** | bool |  |
# MethodInstanceType Enum

Namespace: Microsoft.Office.SharePoint.Tools


## Values

| Name | Summary |
|---|---|
| **Finder** |  |
| **SpecificFinder** |  |
| **GenericInvoker** |  |
| **IdEnumerator** |  |
| **ChangedIdEnumerator** |  |
| **DeletedIdEnumerator** |  |
| **Scalar** |  |
| **AccessChecker** |  |
| **AssociationNavigator** |  |
| **Associator** |  |
| **Disassociator** |  |
| **Creator** |  |
| **Deleter** |  |
| **Updater** |  |
| **StreamAccessor** |  |
| **BinarySecurityDescriptorAccessor** |  |
| **BulkSpecificFinder** |  |
| **BulkAssociatedIdEnumerator** |  |
| **BulkAssociationNavigator** |  |
| **BulkIdEnumerator** |  |
| **EventSubscriber** |  |
| **EventUnsubscriber** |  |
# MethodNames Class

Namespace: Microsoft.Office.SharePoint.Tools


## Fields

| Name | Type | Summary |
|---|---|---|
| **Creator** | string |  |
| **Deleter** | string |  |
| **Finder** | string |  |
| **SpecificFinder** | string |  |
| **Updater** | string |  |
# MimeConstants Class

Namespace: Microsoft.Office.SharePoint.Tools


## Fields

| Name | Type | Summary |
|---|---|---|
| **MimeApplicationAtom** | string |  |
| **MimeApplicationJson** | string |  |
| **MimeApplicationXml** | string |  |
| **WildCard** | string |  |
# Model Class

Namespace: Microsoft.Office.SharePoint.Tools

Base class: [IndividuallySecurableMetadataObject](#individuallysecurablemetadataobject-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **LobSystems** | [LobSystem](#lobsystem-class)[] |  |
| **AccessControlList** | [AccessControlEntry](#accesscontrolentry-class)[] |  |
| **LocalizedDisplayNames** | [LocalizedDisplayName](#localizeddisplayname-class)[] |  |
| **Properties** | [Property](#property-class)[] |  |
| **Name** | string |  |
| **DefaultDisplayName** | string |  |
| **IsCached** | bool |  |
# NormalizeDateTime Class

Namespace: Microsoft.Office.SharePoint.Tools


## Properties

| Name | Type | Summary |
|---|---|---|
| **LobDateTimeMode** | [LobDateTimeMode](#lobdatetimemode-enum) |  |
# NormalizeString Class

Namespace: Microsoft.Office.SharePoint.Tools


## Properties

| Name | Type | Summary |
|---|---|---|
| **FromLOB** | [StringNormalizeMode](#stringnormalizemode-enum) |  |
| **ToLOB** | [StringNormalizeMode](#stringnormalizemode-enum) |  |
# ODataAutoGen Class

Namespace: Microsoft.Office.SharePoint.Tools


## Constructors

| Name | Summary |
|---|---|
| **ODataAutoGen(IEdmModel metadataModel, Uri odataServiceUri, Uri odataMetadataUri)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **AddColumn(Model bdcModel, string entityName, string columnName)** | void |  |
| **AddSystemFilter(Model bdcModel, string entityName, SystemFilterType systemFilter)** | void |  |
| **AddUserFilter(Model bdcModel, string entityName, UserFilterType filterType, string columnName, string defaultValue)** | void |  |
| **CreateAssociation(Model bdcModel, string sourceEntity, string destinationEntity)** | void |  |
| **GenerateExternalContentTypes(string lsiName, IEnumerable\<string\> entitiesToGenerate)** | [Model](#model-class) |  |
| **GetEntitiesAndFunctionImports(out IEnumerable\<string\> entityNames, out IEnumerable\<string\> functionNames)** | void |  |
| **RemoveColumn(Model bdcModel, string entityName, string columnName)** | void |  |
| **RemoveSystemFilter(Model bdcModel, string entityName, SystemFilterType systemFilter)** | void |  |
| **RemoveUserFilter(Model bdcModel, string entityName, UserFilterType filterType, string columnName)** | void |  |
# ODataAutogenConstants Class

Namespace: Microsoft.Office.SharePoint.Tools


## Fields

| Name | Type | Summary |
|---|---|---|
| **ExcludeFromOfflineClientForList** | string |  |
| **HttpGet** | string |  |
| **DynamicType** | string |  |
| **DynamicTypeArray** | string |  |
| **IDynamicTypeEnumerator** | string |  |
| **PassThrough** | string |  |
| **ODataVersion2** | string |  |
| **Version** | string |  |
| **MaxInstanceCount** | string |  |
| **HttpFailErrorCode** | int |  |
| **ComparatorPropertyValue** | string |  |
| **AndOperatorPropertyValue** | string |  |
| **DefaultOperatorPropertyValue** | string |  |
| **EqualsFilter** | string |  |
| **IdentifierNone** | string |  |
| **ServiceOperations** | string |  |
| **UserContextTypePropertyName** | string |  |
| **QualifiedUserName** | string |  |
| **MaxNrItems** | string |  |
| **UsedForDisambiguationProperty** | string |  |
# ODataAutogenException Class

Namespace: Microsoft.Office.SharePoint.Tools

Base class: Exception


## Properties

| Name | Type | Summary |
|---|---|---|
| **TargetSite** | MethodBase |  |
| **StackTrace** | string |  |
| **Message** | string |  |
| **Data** | IDictionary |  |
| **InnerException** | Exception |  |
| **HelpLink** | string |  |
| **Source** | string |  |
| **HResult** | int |  |
## Constructors

| Name | Summary |
|---|---|
| **ODataAutogenException(string message)** |  |
| **ODataAutogenException(Exception inner)** |  |
| **ODataAutogenException(string message, Exception inner)** |  |
# ODataBdcArtifactGenerator Class

Namespace: Microsoft.Office.SharePoint.Tools


# ODataBdcMethodGenerator Class

Namespace: Microsoft.Office.SharePoint.Tools


## Methods

| Name | Returns | Summary |
|---|---|---|
| **ConstructGenericInvokerMethod(FunctionMetadata functionImport, IEnumerable\<EntityMetadata\> allEntityMetadata)** | [Method](#method-class) |  |
# ODataBdcModelGenerator Class

Namespace: Microsoft.Office.SharePoint.Tools


# ODataEntityUriHelper Class

Namespace: Microsoft.Office.SharePoint.Tools


# OperationModeType Enum

Namespace: Microsoft.Office.SharePoint.Tools


## Values

| Name | Summary |
|---|---|
| **Online** |  |
| **Cached** |  |
| **Offline** |  |
| **Default** |  |
# Parameter Class

Namespace: Microsoft.Office.SharePoint.Tools

Base class: [MetadataObject](#metadataobject-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **TypeDescriptor** | [TypeDescriptor](#typedescriptor-class) |  |
| **Direction** | [ParameterDirection](#parameterdirection-enum) |  |
| **LocalizedDisplayNames** | [LocalizedDisplayName](#localizeddisplayname-class)[] |  |
| **Properties** | [Property](#property-class)[] |  |
| **Name** | string |  |
| **DefaultDisplayName** | string |  |
| **IsCached** | bool |  |
# ParameterDirection Enum

Namespace: Microsoft.Office.SharePoint.Tools


## Values

| Name | Summary |
|---|---|
| **In** |  |
| **Out** |  |
| **InOut** |  |
| **Return** |  |
# PayloadKind Enum

Namespace: Microsoft.Office.SharePoint.Tools


## Values

| Name | Summary |
|---|---|
| **Void** |  |
| **Entry** |  |
| **Feed** |  |
| **Value** |  |
| **Property** |  |
| **Collection** |  |
| **Stream** |  |
# Property Class

Namespace: Microsoft.Office.SharePoint.Tools


## Properties

| Name | Type | Summary |
|---|---|---|
| **Name** | string |  |
| **Type** | string |  |
| **Text** | string[] |  |
# ResourceIds Class

Namespace: Microsoft.Office.SharePoint.Tools


## Fields

| Name | Type | Summary |
|---|---|---|
| **AddColumn_MissingFinder** | string |  |
| **AddColumn_InvalidColumn** | string |  |
| **AddColumn_Failed** | string |  |
| **RemoveColumn_MissingFinder** | string |  |
| **RemoveColumn_InvalidColumn** | string |  |
| **Identifier_TypeNotSupported** | string |  |
| **UnknownDotNetType** | string |  |
| **UnknownEdmType** | string |  |
| **MissingBCSEntity** | string |  |
| **MissingEntityContainer** | string |  |
| **MisingEdmEntity** | string |  |
| **MisingEdmDestinationEntity** | string |  |
| **MissingFunctionEntity** | string |  |
| **NoEntityOrFunctionImports** | string |  |
| **AssociationGenerationFailed** | string |  |
| **SystemFilterExist** | string |  |
| **UserFilterMissingMethod** | string |  |
| **CompFilterMisingColumn** | string |  |
| **RemoveFilterMissingMethod** | string |  |
| **UserFilterExist** | string |  |
| **UserFilterExistOnEntity** | string |  |
| **MissingMethodInstance** | string |  |
| **MissingAssociationMethodInstance** | string |  |
| **WildCardFilterInvalidColumn** | string |  |
# Resources Class

Namespace: Microsoft.Office.SharePoint.Tools


# Right Class

Namespace: Microsoft.Office.SharePoint.Tools


## Properties

| Name | Type | Summary |
|---|---|---|
| **BdcRight** | [BdcRightName](#bdcrightname-enum) |  |
# SourceEntity Class

Namespace: Microsoft.Office.SharePoint.Tools


## Properties

| Name | Type | Summary |
|---|---|---|
| **Namespace** | string |  |
| **Name** | string |  |
# StringNormalizeMode Enum

Namespace: Microsoft.Office.SharePoint.Tools


## Values

| Name | Summary |
|---|---|
| **NoChange** |  |
| **NormalizeToEmptyString** |  |
| **NormalizeToNull** |  |
# SystemFilterFactory Class

Namespace: Microsoft.Office.SharePoint.Tools


# SystemFilterType Enum

Namespace: Microsoft.Office.SharePoint.Tools


## Values

| Name | Summary |
|---|---|
| **ActivityId** |  |
| **UserContext** |  |
| **UserCulture** |  |
# TypeConstants Class

Namespace: Microsoft.Office.SharePoint.Tools


## Fields

| Name | Type | Summary |
|---|---|---|
| **SystemInt32** | string |  |
| **SystemString** | string |  |
| **SystemBoolean** | string |  |
| **SystemDateTimeOffset** | string |  |
# TypeDescriptor Class

Namespace: Microsoft.Office.SharePoint.Tools

Base class: [MetadataObject](#metadataobject-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **Interpretation** | Object[] |  |
| **DefaultValues** | [DefaultValue](#defaultvalue-class)[] |  |
| **TypeDescriptors** | [TypeDescriptor](#typedescriptor-class)[] |  |
| **TypeName** | string |  |
| **LobName** | string |  |
| **IdentifierEntityNamespace** | string |  |
| **IdentifierEntityName** | string |  |
| **IdentifierName** | string |  |
| **ForeignIdentifierAssociationName** | string |  |
| **ForeignIdentifierAssociationEntityName** | string |  |
| **ForeignIdentifierAssociationEntityNamespace** | string |  |
| **AssociatedFilter** | string |  |
| **IsCollection** | bool |  |
| **ReadOnly** | bool |  |
| **CreatorField** | bool |  |
| **UpdaterField** | bool |  |
| **PreUpdaterField** | bool |  |
| **Significant** | bool |  |
| **IsSortInput** | bool |  |
| **LocalizedDisplayNames** | [LocalizedDisplayName](#localizeddisplayname-class)[] |  |
| **Properties** | [Property](#property-class)[] |  |
| **Name** | string |  |
| **DefaultDisplayName** | string |  |
| **IsCached** | bool |  |
# UserFilterFactory Class

Namespace: Microsoft.Office.SharePoint.Tools


# UserFilterType Enum

Namespace: Microsoft.Office.SharePoint.Tools


## Values

| Name | Summary |
|---|---|
| **Comparison** |  |
| **Limit** |  |
| **PageNumber** |  |
| **Wildcard** |  |
