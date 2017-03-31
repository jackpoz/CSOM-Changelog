# Microsoft.SharePoint.Client.DocumentManagement.dll v.16.1.0.0 API documentation

Created by 
[mddox](https://github.com/loxsmoke/mddox) on 06/04/2023

# All types

|   |   |   |
|---|---|---|
| [MetadataDefaults Class](#metadatadefaults-class) | [DocumentSet Class](#documentset-class) | [ConfiguredMetadataNavigationItemCollection Class](#configuredmetadatanavigationitemcollection-class) |
| [ScriptTypeFactory Class](#scripttypefactory-class) | [DocumentSetTemplate Class](#documentsettemplate-class) | [MetadataNavigationSettings Class](#metadatanavigationsettings-class) |
| [AllowedContentTypeCollection Class](#allowedcontenttypecollection-class) | [DocumentSetTemplateObjectPropertyNames Class](#documentsettemplateobjectpropertynames-class) | [EmbedCodeConfiguration Class](#embedcodeconfiguration-class) |
| [DefaultDocument Class](#defaultdocument-class) | [SharedFieldCollection Class](#sharedfieldcollection-class) | [VideoSet Class](#videoset-class) |
| [DefaultDocumentCollection Class](#defaultdocumentcollection-class) | [WelcomePageFieldCollection Class](#welcomepagefieldcollection-class) |   |
| [DefaultDocumentPropertyNames Class](#defaultdocumentpropertynames-class) | [ConfiguredMetadataNavigationItem Class](#configuredmetadatanavigationitem-class) |   |
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
