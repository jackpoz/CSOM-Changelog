# Microsoft.SharePoint.Client.Taxonomy.dll v.16.1.0.0 API documentation

Created by 
[mddox](https://github.com/loxsmoke/mddox) on 2024-05-13

# All types

|   |   |   |
|---|---|---|
| [ChangedGroup Class](#changedgroup-class) | [LabelMatchInformationPropertyNames Class](#labelmatchinformationpropertynames-class) | [TermGroupObjectPropertyNames Class](#termgroupobjectpropertynames-class) |
| [ChangedItem Class](#changeditem-class) | [LabelObjectPropertyNames Class](#labelobjectpropertynames-class) | [TermGroupPropertyNames Class](#termgrouppropertynames-class) |
| [ChangedItemCollection Class](#changeditemcollection-class) | [LabelPropertyNames Class](#labelpropertynames-class) | [TermObjectPropertyNames Class](#termobjectpropertynames-class) |
| [ChangedItemPropertyNames Class](#changeditempropertynames-class) | [MobileTaxonomyField Class](#mobiletaxonomyfield-class) | [TermPropertyNames Class](#termpropertynames-class) |
| [ChangedItemType Enum](#changeditemtype-enum) | [MobileTaxonomyFieldPropertyNames Class](#mobiletaxonomyfieldpropertynames-class) | [TermSet Class](#termset-class) |
| [ChangedOperationType Enum](#changedoperationtype-enum) | [ScriptTypeFactory Class](#scripttypefactory-class) | [TermSetCollection Class](#termsetcollection-class) |
| [ChangedSite Class](#changedsite-class) | [StringMatchOption Enum](#stringmatchoption-enum) | [TermSetItem Class](#termsetitem-class) |
| [ChangedSitePropertyNames Class](#changedsitepropertynames-class) | [TaxonomyField Class](#taxonomyfield-class) | [TermSetItemObjectPropertyNames Class](#termsetitemobjectpropertynames-class) |
| [ChangedTerm Class](#changedterm-class) | [TaxonomyFieldPropertyNames Class](#taxonomyfieldpropertynames-class) | [TermSetItemPropertyNames Class](#termsetitempropertynames-class) |
| [ChangedTermPropertyNames Class](#changedtermpropertynames-class) | [TaxonomyFieldValue Class](#taxonomyfieldvalue-class) | [TermSetObjectPropertyNames Class](#termsetobjectpropertynames-class) |
| [ChangedTermSet Class](#changedtermset-class) | [TaxonomyFieldValueCollection Class](#taxonomyfieldvaluecollection-class) | [TermSetPropertyNames Class](#termsetpropertynames-class) |
| [ChangedTermSetPropertyNames Class](#changedtermsetpropertynames-class) | [TaxonomyItem Class](#taxonomyitem-class) | [TermStore Class](#termstore-class) |
| [ChangedTermStore Class](#changedtermstore-class) | [TaxonomyItemObjectPropertyNames Class](#taxonomyitemobjectpropertynames-class) | [TermStoreCollection Class](#termstorecollection-class) |
| [ChangedTermStorePropertyNames Class](#changedtermstorepropertynames-class) | [TaxonomyItemPropertyNames Class](#taxonomyitempropertynames-class) | [TermStoreObjectPropertyNames Class](#termstoreobjectpropertynames-class) |
| [ChangeInformation Class](#changeinformation-class) | [TaxonomySession Class](#taxonomysession-class) | [TermStorePropertyNames Class](#termstorepropertynames-class) |
| [ChangeInformationPropertyNames Class](#changeinformationpropertynames-class) | [TaxonomySessionObjectPropertyNames Class](#taxonomysessionobjectpropertynames-class) | [ContentTypeInfo Class](#contenttypeinfo-class) |
| [CustomPropertyMatchInformation Class](#custompropertymatchinformation-class) | [TaxonomySessionPropertyNames Class](#taxonomysessionpropertynames-class) | [ContentTypePublisher Class](#contenttypepublisher-class) |
| [CustomPropertyMatchInformationPropertyNames Class](#custompropertymatchinformationpropertynames-class) | [Term Class](#term-class) | [ContentTypeSubscriber Class](#contenttypesubscriber-class) |
| [Label Class](#label-class) | [TermCollection Class](#termcollection-class) | [ContentTypeSyndicationResult Class](#contenttypesyndicationresult-class) |
| [LabelCollection Class](#labelcollection-class) | [TermGroup Class](#termgroup-class) | [eFailedReason Enum](#efailedreason-enum) |
| [LabelMatchInformation Class](#labelmatchinformation-class) | [TermGroupCollection Class](#termgroupcollection-class) |   |
# ChangedGroup Class

Namespace: Microsoft.SharePoint.Client.Taxonomy

Base class: [ChangedItem](#changeditem-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **ChangedBy** | string |  |
| **ChangedTime** | DateTime |  |
| **Id** | Guid |  |
| **ItemType** | [ChangedItemType](#changeditemtype-enum) |  |
| **Operation** | [ChangedOperationType](#changedoperationtype-enum) |  |
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
| **ChangedGroup(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ChangedItem Class

Namespace: Microsoft.SharePoint.Client.Taxonomy

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ChangedBy** | string |  |
| **ChangedTime** | DateTime |  |
| **Id** | Guid |  |
| **ItemType** | [ChangedItemType](#changeditemtype-enum) |  |
| **Operation** | [ChangedOperationType](#changedoperationtype-enum) |  |
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
| **ChangedItem(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ChangedItemCollection Class

Namespace: Microsoft.SharePoint.Client.Taxonomy

Base class: ClientObjectCollection<[ChangedItem](#changeditem-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [ChangedItem](#changeditem-class) |  |
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
| **ChangedItemCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ChangedItemPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Taxonomy


## Fields

| Name | Type | Summary |
|---|---|---|
| **ChangedBy** | string |  |
| **ChangedTime** | string |  |
| **Id** | string |  |
| **ItemType** | string |  |
| **Operation** | string |  |
# ChangedItemType Enum

Namespace: Microsoft.SharePoint.Client.Taxonomy


## Values

| Name | Summary |
|---|---|
| **Unknown** |  |
| **Term** |  |
| **TermSet** |  |
| **Group** |  |
| **TermStore** |  |
| **Site** |  |
# ChangedOperationType Enum

Namespace: Microsoft.SharePoint.Client.Taxonomy


## Values

| Name | Summary |
|---|---|
| **Unknown** |  |
| **Add** |  |
| **Edit** |  |
| **DeleteObject** |  |
| **Move** |  |
| **Copy** |  |
| **PathChange** |  |
| **Merge** |  |
| **ImportObject** |  |
| **Restore** |  |
# ChangedSite Class

Namespace: Microsoft.SharePoint.Client.Taxonomy

Base class: [ChangedItem](#changeditem-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **SiteId** | Guid |  |
| **TermId** | Guid |  |
| **TermSetId** | Guid |  |
| **ChangedBy** | string |  |
| **ChangedTime** | DateTime |  |
| **Id** | Guid |  |
| **ItemType** | [ChangedItemType](#changeditemtype-enum) |  |
| **Operation** | [ChangedOperationType](#changedoperationtype-enum) |  |
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
| **ChangedSite(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ChangedSitePropertyNames Class

Namespace: Microsoft.SharePoint.Client.Taxonomy


## Fields

| Name | Type | Summary |
|---|---|---|
| **SiteId** | string |  |
| **TermId** | string |  |
| **TermSetId** | string |  |
# ChangedTerm Class

Namespace: Microsoft.SharePoint.Client.Taxonomy

Base class: [ChangedItem](#changeditem-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **ChangedCustomProperties** | IEnumerable\<string\> |  |
| **ChangedLocalCustomProperties** | IEnumerable\<string\> |  |
| **GroupId** | Guid |  |
| **LcidsForChangedDescriptions** | IEnumerable\<int\> |  |
| **LcidsForChangedLabels** | IEnumerable\<int\> |  |
| **TermSetId** | Guid |  |
| **ChangedBy** | string |  |
| **ChangedTime** | DateTime |  |
| **Id** | Guid |  |
| **ItemType** | [ChangedItemType](#changeditemtype-enum) |  |
| **Operation** | [ChangedOperationType](#changedoperationtype-enum) |  |
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
| **ChangedTerm(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ChangedTermPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Taxonomy


## Fields

| Name | Type | Summary |
|---|---|---|
| **ChangedCustomProperties** | string |  |
| **ChangedLocalCustomProperties** | string |  |
| **GroupId** | string |  |
| **LcidsForChangedDescriptions** | string |  |
| **LcidsForChangedLabels** | string |  |
| **TermSetId** | string |  |
# ChangedTermSet Class

Namespace: Microsoft.SharePoint.Client.Taxonomy

Base class: [ChangedItem](#changeditem-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **FromGroupId** | Guid |  |
| **GroupId** | Guid |  |
| **ChangedBy** | string |  |
| **ChangedTime** | DateTime |  |
| **Id** | Guid |  |
| **ItemType** | [ChangedItemType](#changeditemtype-enum) |  |
| **Operation** | [ChangedOperationType](#changedoperationtype-enum) |  |
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
| **ChangedTermSet(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ChangedTermSetPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Taxonomy


## Fields

| Name | Type | Summary |
|---|---|---|
| **FromGroupId** | string |  |
| **GroupId** | string |  |
# ChangedTermStore Class

Namespace: Microsoft.SharePoint.Client.Taxonomy

Base class: [ChangedItem](#changeditem-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **ChangedLanguage** | int |  |
| **IsDefaultLanguageChanged** | bool |  |
| **IsFullFarmRestore** | bool |  |
| **ChangedBy** | string |  |
| **ChangedTime** | DateTime |  |
| **Id** | Guid |  |
| **ItemType** | [ChangedItemType](#changeditemtype-enum) |  |
| **Operation** | [ChangedOperationType](#changedoperationtype-enum) |  |
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
| **ChangedTermStore(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ChangedTermStorePropertyNames Class

Namespace: Microsoft.SharePoint.Client.Taxonomy


## Fields

| Name | Type | Summary |
|---|---|---|
| **ChangedLanguage** | string |  |
| **IsDefaultLanguageChanged** | string |  |
| **IsFullFarmRestore** | string |  |
# ChangeInformation Class

Namespace: Microsoft.SharePoint.Client.Taxonomy

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ItemType** | [ChangedItemType](#changeditemtype-enum) |  |
| **OperationType** | [ChangedOperationType](#changedoperationtype-enum) |  |
| **StartTime** | DateTime |  |
| **WithinTimeSpan** | TimeSpan |  |
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
| **ChangeInformation(ClientRuntimeContext context)** |  |
| **ChangeInformation(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ChangeInformationPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Taxonomy


## Fields

| Name | Type | Summary |
|---|---|---|
| **ItemType** | string |  |
| **OperationType** | string |  |
| **StartTime** | string |  |
| **WithinTimeSpan** | string |  |
# CustomPropertyMatchInformation Class

Namespace: Microsoft.SharePoint.Client.Taxonomy

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **CustomPropertyName** | string |  |
| **CustomPropertyValue** | string |  |
| **ResultCollectionSize** | int |  |
| **StringMatchOption** | [StringMatchOption](#stringmatchoption-enum) |  |
| **TrimUnavailable** | bool |  |
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
| **CustomPropertyMatchInformation(ClientRuntimeContext context)** |  |
| **CustomPropertyMatchInformation(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# CustomPropertyMatchInformationPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Taxonomy


## Fields

| Name | Type | Summary |
|---|---|---|
| **CustomPropertyName** | string |  |
| **CustomPropertyValue** | string |  |
| **ResultCollectionSize** | string |  |
| **StringMatchOption** | string |  |
| **TrimUnavailable** | string |  |
# Label Class

Namespace: Microsoft.SharePoint.Client.Taxonomy

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **IsDefaultForLanguage** | bool |  |
| **Language** | int |  |
| **Term** | [Term](#term-class) |  |
| **Value** | string |  |
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
| **Label(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
| **SetAsDefaultForLanguage()** | void |  |
# LabelCollection Class

Namespace: Microsoft.SharePoint.Client.Taxonomy

Base class: ClientObjectCollection<[Label](#label-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [Label](#label-class) |  |
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
| **LabelCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetByValue(string index)** | [Label](#label-class) |  |
# LabelMatchInformation Class

Namespace: Microsoft.SharePoint.Client.Taxonomy

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **DefaultLabelOnly** | bool |  |
| **ExcludeKeyword** | bool |  |
| **Lcid** | int |  |
| **ResultCollectionSize** | int |  |
| **StringMatchOption** | [StringMatchOption](#stringmatchoption-enum) |  |
| **TermLabel** | string |  |
| **TrimDeprecated** | bool |  |
| **TrimUnavailable** | bool |  |
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
| **LabelMatchInformation(ClientRuntimeContext context)** |  |
| **LabelMatchInformation(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# LabelMatchInformationPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Taxonomy


## Fields

| Name | Type | Summary |
|---|---|---|
| **DefaultLabelOnly** | string |  |
| **ExcludeKeyword** | string |  |
| **Lcid** | string |  |
| **ResultCollectionSize** | string |  |
| **StringMatchOption** | string |  |
| **TermLabel** | string |  |
| **TrimDeprecated** | string |  |
| **TrimUnavailable** | string |  |
# LabelObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Taxonomy


## Fields

| Name | Type | Summary |
|---|---|---|
| **Term** | string |  |
# LabelPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Taxonomy


## Fields

| Name | Type | Summary |
|---|---|---|
| **IsDefaultForLanguage** | string |  |
| **Language** | string |  |
| **Value** | string |  |
# MobileTaxonomyField Class

Namespace: Microsoft.SharePoint.Client.Taxonomy

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ReadOnly** | bool |  |
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
| **MobileTaxonomyField(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# MobileTaxonomyFieldPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Taxonomy


## Fields

| Name | Type | Summary |
|---|---|---|
| **ReadOnly** | string |  |
# ScriptTypeFactory Class

Namespace: Microsoft.SharePoint.Client.Taxonomy


## Methods

| Name | Returns | Summary |
|---|---|---|
| **CreateObjectFromScriptType(string scriptType, ClientRuntimeContext context)** | IFromJson |  |
# StringMatchOption Enum

Namespace: Microsoft.SharePoint.Client.Taxonomy


## Values

| Name | Summary |
|---|---|
| **StartsWith** |  |
| **ExactMatch** |  |
# TaxonomyField Class

Namespace: Microsoft.SharePoint.Client.Taxonomy

Base class: FieldLookup


## Properties

| Name | Type | Summary |
|---|---|---|
| **AnchorId** | Guid |  |
| **CreateValuesInEditForm** | bool |  |
| **IsAnchorValid** | bool |  |
| **IsDocTagsEnabled** | bool |  |
| **IsEnhancedImageTaggingEnabled** | bool |  |
| **IsKeyword** | bool |  |
| **IsPathRendered** | bool |  |
| **IsTermSetValid** | bool |  |
| **Open** | bool |  |
| **SspId** | Guid |  |
| **TargetTemplate** | string |  |
| **TermSetId** | Guid |  |
| **TextField** | Guid |  |
| **UserCreated** | bool |  |
| **AllowMultipleValues** | bool |  |
| **DependentLookupInternalNames** | IList\<string\> |  |
| **IsDependentLookup** | bool |  |
| **IsRelationship** | bool |  |
| **LookupField** | string |  |
| **LookupList** | string |  |
| **LookupWebId** | Guid |  |
| **PrimaryFieldId** | string |  |
| **RelationshipDeleteBehavior** | RelationshipDeleteBehaviorType |  |
| **UnlimitedLengthInDocumentLibrary** | bool |  |
| **AutoIndexed** | bool |  |
| **CanBeDeleted** | bool |  |
| **ClientSideComponentId** | Guid |  |
| **ClientSideComponentProperties** | string |  |
| **ClientValidationFormula** | string |  |
| **ClientValidationMessage** | string |  |
| **CustomFormatter** | string |  |
| **DefaultFormula** | string |  |
| **DefaultValue** | string |  |
| **Description** | string |  |
| **DescriptionResource** | UserResource |  |
| **Direction** | string |  |
| **EnforceUniqueValues** | bool |  |
| **EntityPropertyName** | string |  |
| **Filterable** | bool |  |
| **FromBaseType** | bool |  |
| **Group** | string |  |
| **Hidden** | bool |  |
| **Id** | Guid |  |
| **Indexed** | bool |  |
| **IndexStatus** | FieldIndexStatus |  |
| **InternalName** | string |  |
| **IsModern** | bool |  |
| **JSLink** | string |  |
| **NoCrawl** | bool |  |
| **PinnedToFiltersPane** | bool |  |
| **ReadOnlyField** | bool |  |
| **Required** | bool |  |
| **SchemaXml** | string |  |
| **SchemaXmlWithResourceTokens** | string |  |
| **Scope** | string |  |
| **Sealed** | bool |  |
| **ShowInFiltersPane** | ShowInFiltersPaneStatus |  |
| **Sortable** | bool |  |
| **StaticName** | string |  |
| **Title** | string |  |
| **TitleResource** | UserResource |  |
| **FieldTypeKind** | FieldType |  |
| **TypeAsString** | string |  |
| **TypeDisplayName** | string |  |
| **TypeShortDescription** | string |  |
| **ValidationFormula** | string |  |
| **ValidationMessage** | string |  |
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
| **TaxonomyField(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetFieldValueAsHtml(Object value)** | ClientResult\<string\> |  |
| **GetFieldValueAsTaxonomyFieldValue(string value)** | ClientResult\<[TaxonomyFieldValue](#taxonomyfieldvalue-class)\> |  |
| **GetFieldValueAsTaxonomyFieldValueCollection(string value)** | [TaxonomyFieldValueCollection](#taxonomyfieldvaluecollection-class) |  |
| **GetFieldValueAsText(Object value)** | ClientResult\<string\> |  |
| **GetValidatedString(Object value)** | ClientResult\<string\> |  |
| **SetFieldValueByCollection(ListItem item, Collection\<Term\> terms, int lcid)** | void |  |
| **SetFieldValueByTerm(ListItem item, Term term, int lcid)** | void |  |
| **SetFieldValueByTermCollection(ListItem item, TermCollection terms, int lcid)** | void |  |
| **SetFieldValueByValue(ListItem item, TaxonomyFieldValue taxValue)** | void |  |
| **SetFieldValueByValueCollection(ListItem item, TaxonomyFieldValueCollection taxValueCollection)** | void |  |
# TaxonomyFieldPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Taxonomy


## Fields

| Name | Type | Summary |
|---|---|---|
| **AnchorId** | string |  |
| **CreateValuesInEditForm** | string |  |
| **IsAnchorValid** | string |  |
| **IsDocTagsEnabled** | string |  |
| **IsEnhancedImageTaggingEnabled** | string |  |
| **IsKeyword** | string |  |
| **IsPathRendered** | string |  |
| **IsTermSetValid** | string |  |
| **Open** | string |  |
| **SspId** | string |  |
| **TargetTemplate** | string |  |
| **TermSetId** | string |  |
| **TextField** | string |  |
| **UserCreated** | string |  |
# TaxonomyFieldValue Class

Namespace: Microsoft.SharePoint.Client.Taxonomy

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Label** | string |  |
| **TermGuid** | string |  |
| **WssId** | int |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# TaxonomyFieldValueCollection Class

Namespace: Microsoft.SharePoint.Client.Taxonomy

Base class: ClientObjectCollection<[TaxonomyFieldValue](#taxonomyfieldvalue-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [TaxonomyFieldValue](#taxonomyfieldvalue-class) |  |
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
| **TaxonomyFieldValueCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
| **TaxonomyFieldValueCollection(ClientRuntimeContext context, string fieldValue, Field creatingField)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **PopulateFromLabelGuidPairs(string text)** | void |  |
# TaxonomyItem Class

Namespace: Microsoft.SharePoint.Client.Taxonomy

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **CreatedDate** | DateTime |  |
| **Id** | Guid |  |
| **LastModifiedDate** | DateTime |  |
| **Name** | string |  |
| **TermStore** | [TermStore](#termstore-class) |  |
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
| **TaxonomyItem(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
| **NormalizeName(ClientRuntimeContext context, string name)** | ClientResult\<string\> |  |
# TaxonomyItemObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Taxonomy


## Fields

| Name | Type | Summary |
|---|---|---|
| **TermStore** | string |  |
# TaxonomyItemPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Taxonomy


## Fields

| Name | Type | Summary |
|---|---|---|
| **CreatedDate** | string |  |
| **Id** | string |  |
| **LastModifiedDate** | string |  |
| **Name** | string |  |
# TaxonomySession Class

Namespace: Microsoft.SharePoint.Client.Taxonomy

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **OfflineTermStoreNames** | string[] |  |
| **TermStores** | [TermStoreCollection](#termstorecollection-class) |  |
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
| **TaxonomySession(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetDefaultKeywordsTermStore()** | [TermStore](#termstore-class) |  |
| **GetDefaultSiteCollectionTermStore()** | [TermStore](#termstore-class) |  |
| **GetTaxonomySession(ClientRuntimeContext context)** | [TaxonomySession](#taxonomysession-class) |  |
| **GetTerm(Guid termId)** | [Term](#term-class) |  |
| **GetTerms(LabelMatchInformation labelMatchInformation)** | [TermCollection](#termcollection-class) |  |
| **GetTermsById(Guid[] termIds)** | [TermCollection](#termcollection-class) |  |
| **GetTermSetsByName(string termSetName, int lcid)** | [TermSetCollection](#termsetcollection-class) |  |
| **GetTermSetsByTermLabel(string[] requiredTermLabels, int lcid)** | [TermSetCollection](#termsetcollection-class) |  |
| **GetTermsInDefaultLanguage(string termLabel, bool defaultLabelOnly, StringMatchOption stringMatchOption, int resultCollectionSize, bool trimUnavailable, bool trimDeprecated)** | [TermCollection](#termcollection-class) |  |
| **GetTermsInWorkingLocale(string termLabel, bool defaultLabelOnly, StringMatchOption stringMatchOption, int resultCollectionSize, bool trimUnavailable, bool trimDeprecated)** | [TermCollection](#termcollection-class) |  |
| **GetTermsWithCustomProperty(CustomPropertyMatchInformation customPropertyMatchInformation)** | [TermCollection](#termcollection-class) |  |
| **UpdateCache()** | void |  |
# TaxonomySessionObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Taxonomy


## Fields

| Name | Type | Summary |
|---|---|---|
| **TermStores** | string |  |
# TaxonomySessionPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Taxonomy


## Fields

| Name | Type | Summary |
|---|---|---|
| **OfflineTermStoreNames** | string |  |
# Term Class

Namespace: Microsoft.SharePoint.Client.Taxonomy

Base class: [TermSetItem](#termsetitem-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **Description** | string |  |
| **IsDeprecated** | bool |  |
| **IsKeyword** | bool |  |
| **IsPinned** | bool |  |
| **IsPinnedRoot** | bool |  |
| **IsReused** | bool |  |
| **IsRoot** | bool |  |
| **IsSourceTerm** | bool |  |
| **Labels** | [LabelCollection](#labelcollection-class) |  |
| **LocalCustomProperties** | IDictionary\<string, string\> |  |
| **MergedTermIds** | IEnumerable\<Guid\> |  |
| **Parent** | [Term](#term-class) |  |
| **PathOfTerm** | string |  |
| **PinSourceTermSet** | [TermSet](#termset-class) |  |
| **ReusedTerms** | [TermCollection](#termcollection-class) |  |
| **SourceTerm** | [Term](#term-class) |  |
| **TermsCount** | int |  |
| **TermSet** | [TermSet](#termset-class) |  |
| **TermSets** | [TermSetCollection](#termsetcollection-class) |  |
| **CustomProperties** | IDictionary\<string, string\> |  |
| **CustomSortOrder** | string |  |
| **IsAvailableForTagging** | bool |  |
| **Owner** | string |  |
| **Terms** | [TermCollection](#termcollection-class) |  |
| **CreatedDate** | DateTime |  |
| **Id** | Guid |  |
| **LastModifiedDate** | DateTime |  |
| **Name** | string |  |
| **TermStore** | [TermStore](#termstore-class) |  |
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
| **Term(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Copy(bool doCopyChildren)** | [Term](#term-class) |  |
| **CreateLabel(string labelName, int lcid, bool isDefault)** | [Label](#label-class) |  |
| **DeleteAllLocalCustomProperties()** | void |  |
| **DeleteLocalCustomProperty(string name)** | void |  |
| **Deprecate(bool doDeprecate)** | void |  |
| **GetAllLabels(int lcid)** | [LabelCollection](#labelcollection-class) |  |
| **GetDefaultLabel(int lcid)** | ClientResult\<string\> |  |
| **GetDescription(int lcid)** | ClientResult\<string\> |  |
| **GetIsDescendantOf(Term ancestorTerm)** | ClientResult\<bool\> |  |
| **GetPath(int lcid)** | ClientResult\<string\> |  |
| **Merge(Term termToMerge)** | [Term](#term-class) |  |
| **Move(TermSetItem newParent)** | void |  |
| **ReassignSourceTerm(Term reusedTerm)** | void |  |
| **SetDescription(string description, int lcid)** | void |  |
| **SetLocalCustomProperty(string name, string value)** | void |  |
# TermCollection Class

Namespace: Microsoft.SharePoint.Client.Taxonomy

Base class: ClientObjectCollection<[Term](#term-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [Term](#term-class) |  |
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
| **TermCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetById(Guid index)** | [Term](#term-class) |  |
| **GetByName(string index)** | [Term](#term-class) |  |
# TermGroup Class

Namespace: Microsoft.SharePoint.Client.Taxonomy

Base class: [TaxonomyItem](#taxonomyitem-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **ContributorPrincipalNames** | IEnumerable\<string\> |  |
| **Description** | string |  |
| **GroupManagerPrincipalNames** | IEnumerable\<string\> |  |
| **IsSiteCollectionGroup** | bool |  |
| **IsSystemGroup** | bool |  |
| **TermSets** | [TermSetCollection](#termsetcollection-class) |  |
| **CreatedDate** | DateTime |  |
| **Id** | Guid |  |
| **LastModifiedDate** | DateTime |  |
| **Name** | string |  |
| **TermStore** | [TermStore](#termstore-class) |  |
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
| **TermGroup(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **AddContributor(string principalName)** | void |  |
| **AddGroupManager(string principalName)** | void |  |
| **CreateTermSet(string name, Guid newTermSetId, int lcid)** | [TermSet](#termset-class) |  |
| **ExportObject()** | ClientResult\<string\> |  |
| **GetChanges(ChangeInformation changeInformation)** | [ChangedItemCollection](#changeditemcollection-class) |  |
| **GetTermSetsWithCustomProperty(CustomPropertyMatchInformation customPropertyMatchInformation)** | [TermSetCollection](#termsetcollection-class) |  |
# TermGroupCollection Class

Namespace: Microsoft.SharePoint.Client.Taxonomy

Base class: ClientObjectCollection<[TermGroup](#termgroup-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [TermGroup](#termgroup-class) |  |
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
| **TermGroupCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetById(Guid index)** | [TermGroup](#termgroup-class) |  |
| **GetByName(string index)** | [TermGroup](#termgroup-class) |  |
# TermGroupObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Taxonomy


## Fields

| Name | Type | Summary |
|---|---|---|
| **TermSets** | string |  |
# TermGroupPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Taxonomy


## Fields

| Name | Type | Summary |
|---|---|---|
| **ContributorPrincipalNames** | string |  |
| **Description** | string |  |
| **GroupManagerPrincipalNames** | string |  |
| **IsSiteCollectionGroup** | string |  |
| **IsSystemGroup** | string |  |
# TermObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Taxonomy


## Fields

| Name | Type | Summary |
|---|---|---|
| **Labels** | string |  |
| **Parent** | string |  |
| **PinSourceTermSet** | string |  |
| **ReusedTerms** | string |  |
| **SourceTerm** | string |  |
| **TermSet** | string |  |
| **TermSets** | string |  |
# TermPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Taxonomy


## Fields

| Name | Type | Summary |
|---|---|---|
| **Description** | string |  |
| **IsDeprecated** | string |  |
| **IsKeyword** | string |  |
| **IsPinned** | string |  |
| **IsPinnedRoot** | string |  |
| **IsReused** | string |  |
| **IsRoot** | string |  |
| **IsSourceTerm** | string |  |
| **LocalCustomProperties** | string |  |
| **MergedTermIds** | string |  |
| **PathOfTerm** | string |  |
| **TermsCount** | string |  |
# TermSet Class

Namespace: Microsoft.SharePoint.Client.Taxonomy

Base class: [TermSetItem](#termsetitem-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **Contact** | string |  |
| **Description** | string |  |
| **Group** | [TermGroup](#termgroup-class) |  |
| **IsOpenForTermCreation** | bool |  |
| **Names** | IDictionary\<string, string\> |  |
| **Stakeholders** | IEnumerable\<string\> |  |
| **CustomProperties** | IDictionary\<string, string\> |  |
| **CustomSortOrder** | string |  |
| **IsAvailableForTagging** | bool |  |
| **Owner** | string |  |
| **Terms** | [TermCollection](#termcollection-class) |  |
| **CreatedDate** | DateTime |  |
| **Id** | Guid |  |
| **LastModifiedDate** | DateTime |  |
| **Name** | string |  |
| **TermStore** | [TermStore](#termstore-class) |  |
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
| **TermSet(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **AddStakeholder(string stakeholderName)** | void |  |
| **Copy()** | [TermSet](#termset-class) |  |
| **DeleteStakeholder(string stakeholderName)** | void |  |
| **ExportObject()** | ClientResult\<string\> |  |
| **GetAllTerms()** | [TermCollection](#termcollection-class) |  |
| **GetAllTermsIncludeDeprecated()** | [TermCollection](#termcollection-class) |  |
| **GetChanges(ChangeInformation changeInformation)** | [ChangedItemCollection](#changeditemcollection-class) |  |
| **GetTerm(Guid termId)** | [Term](#term-class) |  |
| **GetTerms(LabelMatchInformation labelMatchInformation)** | [TermCollection](#termcollection-class) |  |
| **GetTermsWithCustomProperty(CustomPropertyMatchInformation customPropertyMatchInformation)** | [TermCollection](#termcollection-class) |  |
| **Move(TermGroup targetGroup)** | void |  |
# TermSetCollection Class

Namespace: Microsoft.SharePoint.Client.Taxonomy

Base class: ClientObjectCollection<[TermSet](#termset-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [TermSet](#termset-class) |  |
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
| **TermSetCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetById(Guid index)** | [TermSet](#termset-class) |  |
| **GetByName(string index)** | [TermSet](#termset-class) |  |
# TermSetItem Class

Namespace: Microsoft.SharePoint.Client.Taxonomy

Base class: [TaxonomyItem](#taxonomyitem-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **CustomProperties** | IDictionary\<string, string\> |  |
| **CustomSortOrder** | string |  |
| **IsAvailableForTagging** | bool |  |
| **Owner** | string |  |
| **Terms** | [TermCollection](#termcollection-class) |  |
| **CreatedDate** | DateTime |  |
| **Id** | Guid |  |
| **LastModifiedDate** | DateTime |  |
| **Name** | string |  |
| **TermStore** | [TermStore](#termstore-class) |  |
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
| **TermSetItem(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **CreateTerm(string name, int lcid, Guid newTermId)** | [Term](#term-class) |  |
| **DeleteAllCustomProperties()** | void |  |
| **DeleteCustomProperty(string name)** | void |  |
| **GetTerms(int pagingLimit)** | [TermCollection](#termcollection-class) |  |
| **ReuseTerm(Term sourceTerm, bool reuseBranch)** | [Term](#term-class) |  |
| **ReuseTermWithPinning(Term sourceTerm)** | [Term](#term-class) |  |
| **SetCustomProperty(string name, string value)** | void |  |
# TermSetItemObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Taxonomy


## Fields

| Name | Type | Summary |
|---|---|---|
| **Terms** | string |  |
# TermSetItemPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Taxonomy


## Fields

| Name | Type | Summary |
|---|---|---|
| **CustomProperties** | string |  |
| **CustomSortOrder** | string |  |
| **IsAvailableForTagging** | string |  |
| **Owner** | string |  |
# TermSetObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Taxonomy


## Fields

| Name | Type | Summary |
|---|---|---|
| **Group** | string |  |
# TermSetPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Taxonomy


## Fields

| Name | Type | Summary |
|---|---|---|
| **Contact** | string |  |
| **Description** | string |  |
| **IsOpenForTermCreation** | string |  |
| **Names** | string |  |
| **Stakeholders** | string |  |
# TermStore Class

Namespace: Microsoft.SharePoint.Client.Taxonomy

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ContentTypePublishingHub** | string |  |
| **DefaultLanguage** | int |  |
| **Groups** | [TermGroupCollection](#termgroupcollection-class) |  |
| **HashTagsTermSet** | [TermSet](#termset-class) |  |
| **Id** | Guid |  |
| **IsOnline** | bool |  |
| **KeywordsTermSet** | [TermSet](#termset-class) |  |
| **Languages** | IEnumerable\<int\> |  |
| **Name** | string |  |
| **OrphanedTermsTermSet** | [TermSet](#termset-class) |  |
| **SystemGroup** | [TermGroup](#termgroup-class) |  |
| **WorkingLanguage** | int |  |
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
| **TermStore(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **AddLanguage(int lcid)** | void |  |
| **CommitAll()** | void |  |
| **CreateGroup(string name, Guid groupId)** | [TermGroup](#termgroup-class) |  |
| **DeleteLanguage(int lcid)** | void |  |
| **GetChanges(ChangeInformation changeInformation)** | [ChangedItemCollection](#changeditemcollection-class) |  |
| **GetGroup(Guid id)** | [TermGroup](#termgroup-class) |  |
| **GetPackage(string packageId, Guid packageType, string farmVersion, int siteCompatibilityLevel)** | ClientResult\<Stream\> |  |
| **GetPackagesUpdateInformation(DateTime lastUpdateTime)** | ClientResult\<Stream\> |  |
| **GetPackagesUpdateInformationByIds(DateTime lastUpdateTime, string[] strContentTypeIds)** | ClientResult\<Stream\> |  |
| **GetSiteCollectionGroup(Site currentSite, bool createIfMissing)** | [TermGroup](#termgroup-class) |  |
| **GetTerm(Guid termId)** | [Term](#term-class) |  |
| **GetTermInTermSet(Guid termSetId, Guid termId)** | [Term](#term-class) |  |
| **GetTerms(LabelMatchInformation labelMatchInformation)** | [TermCollection](#termcollection-class) |  |
| **GetTermsById(Guid[] termIds)** | [TermCollection](#termcollection-class) |  |
| **GetTermSet(Guid termSetId)** | [TermSet](#termset-class) |  |
| **GetTermSetsByName(string termSetName, int lcid)** | [TermSetCollection](#termsetcollection-class) |  |
| **GetTermSetsByTermLabel(string[] requiredTermLabels, int lcid)** | [TermSetCollection](#termsetcollection-class) |  |
| **GetTermSetsWithCustomProperty(CustomPropertyMatchInformation customPropertyMatchInformation)** | [TermSetCollection](#termsetcollection-class) |  |
| **GetTermsWithCustomProperty(CustomPropertyMatchInformation customPropertyMatchInformation)** | [TermCollection](#termcollection-class) |  |
| **RollbackAll()** | void |  |
| **UpdateCache()** | void |  |
| **UpdateUsedTermsOnSite(Site site)** | void |  |
| **UploadPackages(string packageId, Stream stream, string farmVersion, int siteCompatibilityLevel)** | void |  |
# TermStoreCollection Class

Namespace: Microsoft.SharePoint.Client.Taxonomy

Base class: ClientObjectCollection<[TermStore](#termstore-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [TermStore](#termstore-class) |  |
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
| **TermStoreCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetById(Guid index)** | [TermStore](#termstore-class) |  |
| **GetByName(string index)** | [TermStore](#termstore-class) |  |
# TermStoreObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Taxonomy


## Fields

| Name | Type | Summary |
|---|---|---|
| **Groups** | string |  |
| **HashTagsTermSet** | string |  |
| **KeywordsTermSet** | string |  |
| **OrphanedTermsTermSet** | string |  |
| **SystemGroup** | string |  |
# TermStorePropertyNames Class

Namespace: Microsoft.SharePoint.Client.Taxonomy


## Fields

| Name | Type | Summary |
|---|---|---|
| **ContentTypePublishingHub** | string |  |
| **DefaultLanguage** | string |  |
| **Id** | string |  |
| **IsOnline** | string |  |
| **Languages** | string |  |
| **Name** | string |  |
| **WorkingLanguage** | string |  |
# ContentTypeInfo Class

Namespace: Microsoft.SharePoint.Client.Taxonomy.ContentTypeSync

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Description** | string |  |
| **Group** | string |  |
| **Id** | string |  |
| **IsHidden** | bool |  |
| **IsSealed** | bool |  |
| **Name** | string |  |
| **ParentName** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# ContentTypePublisher Class

Namespace: Microsoft.SharePoint.Client.Taxonomy.ContentTypeSync

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
| **ContentTypePublisher(ClientRuntimeContext context, Site hubSite)** |  |
| **ContentTypePublisher(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **IsPublished(ContentType contentType)** | ClientResult\<bool\> |  |
| **Publish(ContentType contentType, bool republish)** | void |  |
| **Unpublish(ContentType contentType)** | void |  |
# ContentTypeSubscriber Class

Namespace: Microsoft.SharePoint.Client.Taxonomy.ContentTypeSync

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
| **ContentTypeSubscriber(ClientRuntimeContext context)** |  |
| **ContentTypeSubscriber(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetCompatibleHubContentTypes(string webUrl, string listUrl)** | IList\<[ContentTypeInfo](#contenttypeinfo-class)\> |  |
| **SyncContentTypesFromHubSite(string siteUrl, IList\<ContentTypeId\> contentTypeIdsToSync)** | ClientResult\<[ContentTypeSyndicationResult](#contenttypesyndicationresult-class)\> |  |
| **SyncContentTypesFromHubSite2(string siteUrl, IList\<string\> contentTypeIdsToSync)** | ClientResult\<[ContentTypeSyndicationResult](#contenttypesyndicationresult-class)\> |  |
# ContentTypeSyndicationResult Class

Namespace: Microsoft.SharePoint.Client.Taxonomy.ContentTypeSync

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **FailedContentTypeErrors** | IList\<string\> |  |
| **FailedContentTypeIDs** | IList\<string\> |  |
| **FailedReason** | [eFailedReason](#efailedreason-enum) |  |
| **IsPassed** | bool |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# eFailedReason Enum

Namespace: Microsoft.SharePoint.Client.Taxonomy.ContentTypeSync


## Values

| Name | Summary |
|---|---|
| **Unknown** |  |
| **InvalidSubscriptionID** |  |
| **InvalidSiteID** |  |
| **Readonly** |  |
| **FailedAccess** |  |
| **TaxonomyDisabled** |  |
| **TemplateNotSupported** |  |
| **FewContentTypesFailedToSync** |  |
| **PreCheckFailedColumn** |  |
| **PreCheckFailedContentTypeName** |  |
| **PreCheckFailedFeatures** |  |
| **PackageRetrievingFailed** |  |
