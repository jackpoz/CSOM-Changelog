# Microsoft.SharePoint.Client.DocumentManagement.dll v.16.1.0.0 API documentation

Created by 
[mddox](https://github.com/loxsmoke/mddox) on 2025-05-12

# All types

|   |   |   |
|---|---|---|
| [DocumentId Class](#documentid-class) | [DocumentSetObjectPropertyNames Class](#documentsetobjectpropertynames-class) | [DocumentSetVersionPropertyNames Class](#documentsetversionpropertynames-class) |
| [MetadataDefaults Class](#metadatadefaults-class) | [DocumentSetTemplate Class](#documentsettemplate-class) | [SharedFieldCollection Class](#sharedfieldcollection-class) |
| [ScriptTypeFactory Class](#scripttypefactory-class) | [DocumentSetTemplateObjectPropertyNames Class](#documentsettemplateobjectpropertynames-class) | [WelcomePageFieldCollection Class](#welcomepagefieldcollection-class) |
| [AllowedContentTypeCollection Class](#allowedcontenttypecollection-class) | [DocumentSetVersion Class](#documentsetversion-class) | [ConfiguredMetadataNavigationItem Class](#configuredmetadatanavigationitem-class) |
| [DefaultDocument Class](#defaultdocument-class) | [DocumentSetVersionCollection Class](#documentsetversioncollection-class) | [ConfiguredMetadataNavigationItemCollection Class](#configuredmetadatanavigationitemcollection-class) |
| [DefaultDocumentCollection Class](#defaultdocumentcollection-class) | [DocumentSetVersionField Class](#documentsetversionfield-class) | [MetadataNavigationSettings Class](#metadatanavigationsettings-class) |
| [DefaultDocumentPropertyNames Class](#defaultdocumentpropertynames-class) | [DocumentSetVersionItem Class](#documentsetversionitem-class) | [EmbedCodeConfiguration Class](#embedcodeconfiguration-class) |
| [DocumentSet Class](#documentset-class) | [DocumentSetVersionObjectPropertyNames Class](#documentsetversionobjectpropertynames-class) | [VideoSet Class](#videoset-class) |
# DocumentId Class

Namespace: Microsoft.SharePoint.Client.DocumentManagement

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
| **DocumentId(ClientRuntimeContext context)** |  |
| **DocumentId(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **SetDocIdSitePrefix(string prefix, bool scheduleAssignment, bool overwriteExistingIds)** | void |  |
# MetadataDefaults Class

Namespace: Microsoft.SharePoint.Client.DocumentManagement

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
| **MetadataDefaults(ClientRuntimeContext context, List list)** |  |
| **MetadataDefaults(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **SetFieldDefault(Folder folder, string fieldName, string value)** | ClientResult\<bool\> |  |
| **Update()** | void |  |
# ScriptTypeFactory Class

Namespace: Microsoft.SharePoint.Client.DocumentManagement


## Methods

| Name | Returns | Summary |
|---|---|---|
| **CreateObjectFromScriptType(string scriptType, ClientRuntimeContext context)** | IFromJson |  |
# AllowedContentTypeCollection Class

Namespace: Microsoft.SharePoint.Client.DocumentSet

Base class: ClientObjectCollection<ContentTypeId>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | ContentTypeId |  |
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
| **AllowedContentTypeCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(ContentTypeId ctId)** | void |  |
| **Remove(ContentTypeId ctId)** | void |  |
# DefaultDocument Class

Namespace: Microsoft.SharePoint.Client.DocumentSet

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ContentTypeId** | ContentTypeId |  |
| **DocumentPath** | ResourcePath |  |
| **Name** | string |  |
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
| **DefaultDocument(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# DefaultDocumentCollection Class

Namespace: Microsoft.SharePoint.Client.DocumentSet

Base class: ClientObjectCollection<[DefaultDocument](#defaultdocument-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [DefaultDocument](#defaultdocument-class) |  |
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
| **DefaultDocumentCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(string name, ContentTypeId ctId, byte[] content)** | [DefaultDocument](#defaultdocument-class) |  |
| **ChangeContentTypeForDocument(string name, ContentTypeId contentTypeId)** | ClientResult\<bool\> |  |
| **Remove(string name)** | void |  |
# DefaultDocumentPropertyNames Class

Namespace: Microsoft.SharePoint.Client.DocumentSet


## Fields

| Name | Type | Summary |
|---|---|---|
| **ContentTypeId** | string |  |
| **DocumentPath** | string |  |
| **Name** | string |  |
# DocumentSet Class

Namespace: Microsoft.SharePoint.Client.DocumentSet

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **VersionCollection** | [DocumentSetVersionCollection](#documentsetversioncollection-class) |  |
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
| **DocumentSet(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Create(ClientRuntimeContext context, Folder parentFolder, string name, ContentTypeId ctid)** | ClientResult\<string\> |  |
| **ExportDocumentSet()** | ClientResult\<Stream\> |  |
| **GetDocumentSet(ClientRuntimeContext context, Folder folder)** | [DocumentSet](#documentset-class) |  |
| **ImportDocumentSet(ClientRuntimeContext context, Stream archiveStream, string archiveName, Folder parentFolder, ContentTypeId docsetContentTypeId)** | [DocumentSet](#documentset-class) |  |
# DocumentSetObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client.DocumentSet


## Fields

| Name | Type | Summary |
|---|---|---|
| **VersionCollection** | string |  |
# DocumentSetTemplate Class

Namespace: Microsoft.SharePoint.Client.DocumentSet

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AllowedContentTypes** | [AllowedContentTypeCollection](#allowedcontenttypecollection-class) |  |
| **DefaultDocuments** | [DefaultDocumentCollection](#defaultdocumentcollection-class) |  |
| **SharedFields** | [SharedFieldCollection](#sharedfieldcollection-class) |  |
| **WelcomePageFields** | [WelcomePageFieldCollection](#welcomepagefieldcollection-class) |  |
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
| **DocumentSetTemplate(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetContentTypeId(ClientRuntimeContext context)** | ClientResult\<ContentTypeId\> |  |
| **GetDocumentSetTemplate(ClientRuntimeContext context, ContentType ct)** | [DocumentSetTemplate](#documentsettemplate-class) |  |
| **IsChildOfDocumentSetContentType(ClientRuntimeContext context, ContentType ct)** | ClientResult\<bool\> |  |
| **Update(bool bPushDown)** | void |  |
# DocumentSetTemplateObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client.DocumentSet


## Fields

| Name | Type | Summary |
|---|---|---|
| **AllowedContentTypes** | string |  |
| **DefaultDocuments** | string |  |
| **SharedFields** | string |  |
| **WelcomePageFields** | string |  |
# DocumentSetVersion Class

Namespace: Microsoft.SharePoint.Client.DocumentSet

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Comments** | string |  |
| **Created** | DateTime |  |
| **CreatedBy** | string |  |
| **ParentCollection** | [DocumentSetVersionCollection](#documentsetversioncollection-class) |  |
| **VersionLabel** | string |  |
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
| **DocumentSetVersion(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetDisplayContents()** | IList\<[DocumentSetVersionItem](#documentsetversionitem-class)\> |  |
| **GetDisplayFields()** | IList\<[DocumentSetVersionField](#documentsetversionfield-class)\> |  |
# DocumentSetVersionCollection Class

Namespace: Microsoft.SharePoint.Client.DocumentSet

Base class: ClientObjectCollection<[DocumentSetVersion](#documentsetversion-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [DocumentSetVersion](#documentsetversion-class) |  |
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
| **DocumentSetVersionCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(bool isLastMajor, string comments)** | void |  |
# DocumentSetVersionField Class

Namespace: Microsoft.SharePoint.Client.DocumentSet

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **FormattedValue** | string |  |
| **Id** | Guid |  |
| **IsFieldFound** | bool |  |
| **Title** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# DocumentSetVersionItem Class

Namespace: Microsoft.SharePoint.Client.DocumentSet

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **InternalId** | int |  |
| **IsItemFound** | bool |  |
| **ItemUrl** | string |  |
| **LinkToDocumentUrl** | string |  |
| **Title** | string |  |
| **VersionLabel** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# DocumentSetVersionObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client.DocumentSet


## Fields

| Name | Type | Summary |
|---|---|---|
| **ParentCollection** | string |  |
# DocumentSetVersionPropertyNames Class

Namespace: Microsoft.SharePoint.Client.DocumentSet


## Fields

| Name | Type | Summary |
|---|---|---|
| **Comments** | string |  |
| **Created** | string |  |
| **CreatedBy** | string |  |
| **VersionLabel** | string |  |
# SharedFieldCollection Class

Namespace: Microsoft.SharePoint.Client.DocumentSet

Base class: ClientObjectCollection<Field>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | Field |  |
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
| **SharedFieldCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(Field fld)** | void |  |
| **Remove(Field fld)** | void |  |
# WelcomePageFieldCollection Class

Namespace: Microsoft.SharePoint.Client.DocumentSet

Base class: ClientObjectCollection<Field>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | Field |  |
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
| **WelcomePageFieldCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(Field fld)** | void |  |
| **Remove(Guid fieldId)** | void |  |
# ConfiguredMetadataNavigationItem Class

Namespace: Microsoft.SharePoint.Client.MetadataNavigation

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **FieldDisplayName** | string |  |
| **FieldTitle** | string |  |
| **FieldTypeAsString** | string |  |
| **IsContentTypeField** | bool |  |
| **IsFolderHierarchy** | bool |  |
| **IsHierarchy** | bool |  |
| **IsMultiValueLookup** | bool |  |
| **IsTaxonomyField** | bool |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# ConfiguredMetadataNavigationItemCollection Class

Namespace: Microsoft.SharePoint.Client.MetadataNavigation

Base class: ClientValueObjectCollection<[ConfiguredMetadataNavigationItem](#configuredmetadatanavigationitem-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **TypeId** | string |  |
| **ChildItemsName** | string |  |
| **Count** | int |  |
| **Item** | [ConfiguredMetadataNavigationItem](#configuredmetadatanavigationitem-class) |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# MetadataNavigationSettings Class

Namespace: Microsoft.SharePoint.Client.MetadataNavigation

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
| **MetadataNavigationSettings(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetConfiguredSettings(ClientRuntimeContext context, ResourcePath listPath)** | ClientResult\<[ConfiguredMetadataNavigationItemCollection](#configuredmetadatanavigationitemcollection-class)\> |  |
# EmbedCodeConfiguration Class

Namespace: Microsoft.SharePoint.Client.Video

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AutoPlay** | bool |  |
| **DisplayTitle** | bool |  |
| **LinkToOwnerProfilePage** | bool |  |
| **LinkToVideoHomePage** | bool |  |
| **Loop** | bool |  |
| **PixelHeight** | uint |  |
| **PixelWidth** | uint |  |
| **PreviewImagePath** | string |  |
| **StartTime** | uint |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# VideoSet Class

Namespace: Microsoft.SharePoint.Client.Video

Base class: [DocumentSet](#documentset-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **VersionCollection** | [DocumentSetVersionCollection](#documentsetversioncollection-class) |  |
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
| **VideoSet(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **CreateVideo(ClientRuntimeContext context, Folder parentFolder, string name, ContentTypeId ctid)** | ClientResult\<string\> |  |
| **GetEmbedCode(ClientRuntimeContext context, string videoPath, EmbedCodeConfiguration properties)** | ClientResult\<string\> |  |
| **MigrateVideo(ClientRuntimeContext context, File videoFile)** | ListItem |  |
| **UploadVideo(ClientRuntimeContext context, List list, string fileName, Stream file, bool overwriteIfExists, string parentFolderPath)** | ClientResult\<string\> |  |
