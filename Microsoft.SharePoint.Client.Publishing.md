# Microsoft.SharePoint.Client.Publishing.dll v.16.1.3912.1204 API documentation

Created by 
[mddox](https://github.com/loxsmoke/mddox) on 06/04/2023

# All types

|   |   |   |
|---|---|---|
| [AddinPlugin Class](#addinplugin-class) | [SiteServicesAddins Class](#siteservicesaddins-class) | [VideoStreamingFormat Enum](#videostreamingformat-enum) |
| [AddinPluginPropertyNames Class](#addinpluginpropertynames-class) | [SpotlightChannel Class](#spotlightchannel-class) | [ViewControlState Enum](#viewcontrolstate-enum) |
| [AddinSettings Class](#addinsettings-class) | [SpotlightChannelCollection Class](#spotlightchannelcollection-class) | [NavigationLinkType Enum](#navigationlinktype-enum) |
| [AddinSettingsPropertyNames Class](#addinsettingspropertynames-class) | [SpotlightChannelObjectPropertyNames Class](#spotlightchannelobjectpropertynames-class) | [NavigationTerm Class](#navigationterm-class) |
| [ChannelPermission Enum](#channelpermission-enum) | [SpotlightChannelPropertyNames Class](#spotlightchannelpropertynames-class) | [NavigationTermCollection Class](#navigationtermcollection-class) |
| [CustomizableString Class](#customizablestring-class) | [SpotlightVideo Class](#spotlightvideo-class) | [NavigationTermObjectPropertyNames Class](#navigationtermobjectpropertynames-class) |
| [CustomizableStringPropertyNames Class](#customizablestringpropertynames-class) | [SpotlightVideoCollection Class](#spotlightvideocollection-class) | [NavigationTermPropertyNames Class](#navigationtermpropertynames-class) |
| [DesignPackage Class](#designpackage-class) | [SpotlightVideoObjectPropertyNames Class](#spotlightvideoobjectpropertynames-class) | [NavigationTermProviderNameCollection Class](#navigationtermprovidernamecollection-class) |
| [DesignPackageInfo Class](#designpackageinfo-class) | [SpotlightVideoPropertyNames Class](#spotlightvideopropertynames-class) | [NavigationTermSet Class](#navigationtermset-class) |
| [EnumerateOnlyVideoCollection Class](#enumerateonlyvideocollection-class) | [VariationLabel Class](#variationlabel-class) | [NavigationTermSetItem Class](#navigationtermsetitem-class) |
| [ImageRendition Class](#imagerendition-class) | [VariationLabelPropertyNames Class](#variationlabelpropertynames-class) | [NavigationTermSetItemObjectPropertyNames Class](#navigationtermsetitemobjectpropertynames-class) |
| [PageLayoutCreationInformation Class](#pagelayoutcreationinformation-class) | [Variations Class](#variations-class) | [NavigationTermSetItemPropertyNames Class](#navigationtermsetitempropertynames-class) |
| [PortalPermission Enum](#portalpermission-enum) | [VideoChannel Class](#videochannel-class) | [NavigationTermSetPropertyNames Class](#navigationtermsetpropertynames-class) |
| [PublishingPage Class](#publishingpage-class) | [VideoChannelCollection Class](#videochannelcollection-class) | [NavigationTermSetView Class](#navigationtermsetview-class) |
| [PublishingPageInformation Class](#publishingpageinformation-class) | [VideoChannelObjectPropertyNames Class](#videochannelobjectpropertynames-class) | [NavigationTermSetViewPropertyNames Class](#navigationtermsetviewpropertynames-class) |
| [PublishingSite Class](#publishingsite-class) | [VideoChannelPropertyNames Class](#videochannelpropertynames-class) | [StandardNavigationSettings Class](#standardnavigationsettings-class) |
| [PublishingWeb Class](#publishingweb-class) | [VideoCollection Class](#videocollection-class) | [StandardNavigationSettingsPropertyNames Class](#standardnavigationsettingspropertynames-class) |
| [PublishingWebObjectPropertyNames Class](#publishingwebobjectpropertynames-class) | [VideoItem Class](#videoitem-class) | [StandardNavigationSource Enum](#standardnavigationsource-enum) |
| [ScheduledItem Class](#scheduleditem-class) | [VideoItemObjectPropertyNames Class](#videoitemobjectpropertynames-class) | [TaxonomyNavigation Class](#taxonomynavigation-class) |
| [ScheduledItemObjectPropertyNames Class](#scheduleditemobjectpropertynames-class) | [VideoItemPropertyNames Class](#videoitempropertynames-class) | [WebNavigationSettings Class](#webnavigationsettings-class) |
| [ScheduledItemPropertyNames Class](#scheduleditempropertynames-class) | [VideoPermissionGroup Class](#videopermissiongroup-class) | [WebNavigationSettingsObjectPropertyNames Class](#webnavigationsettingsobjectpropertynames-class) |
| [ScriptTypeFactory Class](#scripttypefactory-class) | [VideoPermissionGroupObjectPropertyNames Class](#videopermissiongroupobjectpropertynames-class) | [WebNavigationSettingsPropertyNames Class](#webnavigationsettingspropertynames-class) |
| [Search Class](#search-class) | [VideoPermissionGroupPropertyNames Class](#videopermissiongrouppropertynames-class) |   |
| [SiteImageRenditions Class](#siteimagerenditions-class) | [VideoProcessingStatus Enum](#videoprocessingstatus-enum) |   |
# AddinPlugin Class

Namespace: Microsoft.SharePoint.Client.Publishing

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Description** | string |  |
| **Markup** | string |  |
| **Title** | string |  |
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
| **AddinPlugin(ClientRuntimeContext context)** |  |
| **AddinPlugin(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# AddinPluginPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Publishing


## Fields

| Name | Type | Summary |
|---|---|---|
| **Description** | string |  |
| **Markup** | string |  |
| **Title** | string |  |
# AddinSettings Class

Namespace: Microsoft.SharePoint.Client.Publishing

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Description** | string |  |
| **Enabled** | bool |  |
| **HeadScript** | string |  |
| **HtmlEndBody** | string |  |
| **HtmlStartBody** | string |  |
| **Id** | Guid |  |
| **MetaTagPagePropertyMappings** | IDictionary\<string, string\> |  |
| **Namespace** | string |  |
| **Title** | string |  |
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
| **AddinSettings(ClientRuntimeContext context, Guid id)** |  |
| **AddinSettings(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# AddinSettingsPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Publishing


## Fields

| Name | Type | Summary |
|---|---|---|
| **Description** | string |  |
| **Enabled** | string |  |
| **HeadScript** | string |  |
| **HtmlEndBody** | string |  |
| **HtmlStartBody** | string |  |
| **Id** | string |  |
| **MetaTagPagePropertyMappings** | string |  |
| **Namespace** | string |  |
| **Title** | string |  |
# ChannelPermission Enum

Namespace: Microsoft.SharePoint.Client.Publishing


## Values

| Name | Summary |
|---|---|
| **Contributor** |  |
| **Viewer** |  |
| **Owner** |  |
# CustomizableString Class

Namespace: Microsoft.SharePoint.Client.Publishing

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **DefaultValue** | string |  |
| **UsesDefaultValue** | bool |  |
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
| **CustomizableString(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# CustomizableStringPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Publishing


## Fields

| Name | Type | Summary |
|---|---|---|
| **DefaultValue** | string |  |
| **UsesDefaultValue** | string |  |
| **Value** | string |  |
# DesignPackage Class

Namespace: Microsoft.SharePoint.Client.Publishing


## Methods

| Name | Returns | Summary |
|---|---|---|
| **Apply(ClientRuntimeContext context, Site site, DesignPackageInfo info)** | void |  |
| **ExportEnterprise(ClientRuntimeContext context, Site site, bool includeSearchConfiguration)** | ClientResult\<[DesignPackageInfo](#designpackageinfo-class)\> |  |
| **ExportSmallBusiness(ClientRuntimeContext context, Site site, string packageName, bool includeSearchConfiguration)** | ClientResult\<[DesignPackageInfo](#designpackageinfo-class)\> |  |
| **Install(ClientRuntimeContext context, Site site, DesignPackageInfo info, string path)** | void |  |
| **UnInstall(ClientRuntimeContext context, Site site, DesignPackageInfo info)** | void |  |
# DesignPackageInfo Class

Namespace: Microsoft.SharePoint.Client.Publishing

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **MajorVersion** | int |  |
| **MinorVersion** | int |  |
| **PackageGuid** | Guid |  |
| **PackageName** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# EnumerateOnlyVideoCollection Class

Namespace: Microsoft.SharePoint.Client.Publishing

Base class: ClientObjectCollection<[VideoItem](#videoitem-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [VideoItem](#videoitem-class) |  |
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
| **EnumerateOnlyVideoCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ImageRendition Class

Namespace: Microsoft.SharePoint.Client.Publishing

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Group** | string |  |
| **Height** | int |  |
| **Id** | int |  |
| **IdCsom** | int |  |
| **Name** | string |  |
| **Version** | int |  |
| **Width** | int |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# PageLayoutCreationInformation Class

Namespace: Microsoft.SharePoint.Client.Publishing

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AssociatedContentTypeId** | string |  |
| **MasterPageUrl** | string |  |
| **NewPageLayoutEditablePath** | string |  |
| **NewPageLayoutNameWithoutExtension** | string |  |
| **Web** | Web |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# PortalPermission Enum

Namespace: Microsoft.SharePoint.Client.Publishing


## Values

| Name | Summary |
|---|---|
| **HubContributor** |  |
| **ChannelCreator** |  |
| **HubViewer** |  |
# PublishingPage Class

Namespace: Microsoft.SharePoint.Client.Publishing

Base class: [ScheduledItem](#scheduleditem-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **EndDate** | DateTime |  |
| **ListItem** | ListItem |  |
| **StartDate** | DateTime |  |
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
| **PublishingPage(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **AddFriendlyUrl(string friendlyUrlSegment, NavigationTermSetItem editableParent, bool doAddToNavigation)** | ClientResult\<string\> |  |
| **GetPublishingPage(ClientRuntimeContext context, ListItem sourceListItem)** | [PublishingPage](#publishingpage-class) |  |
# PublishingPageInformation Class

Namespace: Microsoft.SharePoint.Client.Publishing

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Folder** | Folder |  |
| **Name** | string |  |
| **PageLayoutListItem** | ListItem |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# PublishingSite Class

Namespace: Microsoft.SharePoint.Client.Publishing

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
| **PublishingSite(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **CreatePageLayout(ClientRuntimeContext context, PageLayoutCreationInformation parameters)** | void |  |
# PublishingWeb Class

Namespace: Microsoft.SharePoint.Client.Publishing

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Web** | Web |  |
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
| **PublishingWeb(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **AddPublishingPage(PublishingPageInformation pageInformation)** | [PublishingPage](#publishingpage-class) |  |
| **GetPublishingWeb(ClientRuntimeContext context, Web web)** | [PublishingWeb](#publishingweb-class) |  |
# PublishingWebObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Publishing


## Fields

| Name | Type | Summary |
|---|---|---|
| **Web** | string |  |
# ScheduledItem Class

Namespace: Microsoft.SharePoint.Client.Publishing

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **EndDate** | DateTime |  |
| **ListItem** | ListItem |  |
| **StartDate** | DateTime |  |
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
| **ScheduledItem(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Schedule(string approvalComment)** | void |  |
# ScheduledItemObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Publishing


## Fields

| Name | Type | Summary |
|---|---|---|
| **ListItem** | string |  |
# ScheduledItemPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Publishing


## Fields

| Name | Type | Summary |
|---|---|---|
| **EndDate** | string |  |
| **StartDate** | string |  |
# ScriptTypeFactory Class

Namespace: Microsoft.SharePoint.Client.Publishing


## Methods

| Name | Returns | Summary |
|---|---|---|
| **CreateObjectFromScriptType(string scriptType, ClientRuntimeContext context)** | IFromJson |  |
# Search Class

Namespace: Microsoft.SharePoint.Client.Publishing

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
| **Search(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# SiteImageRenditions Class

Namespace: Microsoft.SharePoint.Client.Publishing


## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetRenditions(ClientRuntimeContext context)** | IList\<[ImageRendition](#imagerendition-class)\> |  |
| **SetRenditions(ClientRuntimeContext context, IList\<ImageRendition\> renditions)** | void |  |
# SiteServicesAddins Class

Namespace: Microsoft.SharePoint.Client.Publishing


## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeletePlugin(ClientRuntimeContext context, string pluginName)** | void |  |
| **DeleteSettings(ClientRuntimeContext context, Guid addinId)** | void |  |
| **GetPlugin(ClientRuntimeContext context, string pluginName)** | [AddinPlugin](#addinplugin-class) |  |
| **GetSettings(ClientRuntimeContext context, Guid addinId)** | [AddinSettings](#addinsettings-class) |  |
| **SetPlugin(ClientRuntimeContext context, AddinPlugin plugin)** | void |  |
| **SetSettings(ClientRuntimeContext context, AddinSettings addin)** | void |  |
# SpotlightChannel Class

Namespace: Microsoft.SharePoint.Client.Publishing

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Channel** | [VideoChannel](#videochannel-class) |  |
| **ChannelId** | Guid |  |
| **Id** | int |  |
| **TileHtmlColor** | string |  |
| **Title** | string |  |
| **VideoLibraryServerRelativeUrl** | string |  |
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
| **SpotlightChannel(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
| **Update()** | void |  |
# SpotlightChannelCollection Class

Namespace: Microsoft.SharePoint.Client.Publishing

Base class: ClientObjectCollection<[SpotlightChannel](#spotlightchannel-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [SpotlightChannel](#spotlightchannel-class) |  |
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
| **SpotlightChannelCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetById(int id)** | [SpotlightChannel](#spotlightchannel-class) |  |
# SpotlightChannelObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Publishing


## Fields

| Name | Type | Summary |
|---|---|---|
| **Channel** | string |  |
# SpotlightChannelPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Publishing


## Fields

| Name | Type | Summary |
|---|---|---|
| **ChannelId** | string |  |
| **Id** | string |  |
| **TileHtmlColor** | string |  |
| **Title** | string |  |
| **VideoLibraryServerRelativeUrl** | string |  |
# SpotlightVideo Class

Namespace: Microsoft.SharePoint.Client.Publishing

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Id** | int |  |
| **ServerRelativeUrl** | string |  |
| **Url** | string |  |
| **Video** | [VideoItem](#videoitem-class) |  |
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
| **SpotlightVideo(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
| **Update()** | void |  |
# SpotlightVideoCollection Class

Namespace: Microsoft.SharePoint.Client.Publishing

Base class: ClientObjectCollection<[SpotlightVideo](#spotlightvideo-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [SpotlightVideo](#spotlightvideo-class) |  |
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
| **SpotlightVideoCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetById(int id)** | [SpotlightVideo](#spotlightvideo-class) |  |
# SpotlightVideoObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Publishing


## Fields

| Name | Type | Summary |
|---|---|---|
| **Video** | string |  |
# SpotlightVideoPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Publishing


## Fields

| Name | Type | Summary |
|---|---|---|
| **Id** | string |  |
| **ServerRelativeUrl** | string |  |
| **Url** | string |  |
# VariationLabel Class

Namespace: Microsoft.SharePoint.Client.Publishing

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **DisplayName** | string |  |
| **IsSource** | bool |  |
| **Language** | string |  |
| **Locale** | string |  |
| **Title** | string |  |
| **TopWebUrl** | string |  |
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
| **VariationLabel(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# VariationLabelPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Publishing


## Fields

| Name | Type | Summary |
|---|---|---|
| **DisplayName** | string |  |
| **IsSource** | string |  |
| **Language** | string |  |
| **Locale** | string |  |
| **Title** | string |  |
| **TopWebUrl** | string |  |
# Variations Class

Namespace: Microsoft.SharePoint.Client.Publishing

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
| **Variations(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetLabels(ClientRuntimeContext context)** | ClientObjectList\<[VariationLabel](#variationlabel-class)\> |  |
| **GetPeerUrl(ClientRuntimeContext context, string currentUrl, string labelTitle)** | ClientResult\<string\> |  |
| **UpdateListItems(ClientRuntimeContext context, Guid listId, int[] itemIds)** | void |  |
# VideoChannel Class

Namespace: Microsoft.SharePoint.Client.Publishing

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ChannelPageUrl** | string |  |
| **Description** | string |  |
| **Id** | Guid |  |
| **Search** | [Search](#search-class) |  |
| **SpotlightVideos** | [SpotlightVideoCollection](#spotlightvideocollection-class) |  |
| **TileHtmlColor** | string |  |
| **Title** | string |  |
| **Videos** | [VideoCollection](#videocollection-class) |  |
| **YammerEnabled** | bool |  |
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
| **VideoChannel(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetChannelPageUrl(ViewControlState viewMode)** | ClientResult\<string\> |  |
| **GetVideoCount()** | ClientResult\<int\> |  |
| **Update()** | void |  |
# VideoChannelCollection Class

Namespace: Microsoft.SharePoint.Client.Publishing

Base class: ClientObjectCollection<[VideoChannel](#videochannel-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [VideoChannel](#videochannel-class) |  |
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
| **VideoChannelCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetById(Guid id)** | [VideoChannel](#videochannel-class) |  |
# VideoChannelObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Publishing


## Fields

| Name | Type | Summary |
|---|---|---|
| **Search** | string |  |
| **SpotlightVideos** | string |  |
| **Videos** | string |  |
# VideoChannelPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Publishing


## Fields

| Name | Type | Summary |
|---|---|---|
| **ChannelPageUrl** | string |  |
| **Description** | string |  |
| **Id** | string |  |
| **TileHtmlColor** | string |  |
| **Title** | string |  |
| **YammerEnabled** | string |  |
# VideoCollection Class

Namespace: Microsoft.SharePoint.Client.Publishing

Base class: ClientObjectCollection<[VideoItem](#videoitem-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [VideoItem](#videoitem-class) |  |
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
| **VideoCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetById(Guid id)** | [VideoItem](#videoitem-class) |  |
# VideoItem Class

Namespace: Microsoft.SharePoint.Client.Publishing

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Author** | User |  |
| **ChannelID** | Guid |  |
| **CreatedDate** | DateTime |  |
| **Description** | string |  |
| **DisplayFormUrl** | string |  |
| **FileName** | string |  |
| **Owner** | User |  |
| **OwnerName** | string |  |
| **PeopleInMedia** | UserCollection |  |
| **PlayerPageUrl** | string |  |
| **ServerRelativeUrl** | string |  |
| **ThumbnailUrl** | string |  |
| **Title** | string |  |
| **ID** | Guid |  |
| **Url** | string |  |
| **VideoDurationInSeconds** | int |  |
| **VideoProcessingStatus** | [VideoProcessingStatus](#videoprocessingstatus-enum) |  |
| **ViewCount** | int |  |
| **YammerObjectUrl** | string |  |
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
| **VideoItem(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
| **GetPlaybackUrl(VideoStreamingFormat videoFormat)** | ClientResult\<string\> |  |
| **GetStreamingKeyAccessToken()** | ClientResult\<string\> |  |
| **Update()** | void |  |
# VideoItemObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Publishing


## Fields

| Name | Type | Summary |
|---|---|---|
| **Author** | string |  |
| **Owner** | string |  |
| **PeopleInMedia** | string |  |
# VideoItemPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Publishing


## Fields

| Name | Type | Summary |
|---|---|---|
| **ChannelID** | string |  |
| **CreatedDate** | string |  |
| **Description** | string |  |
| **DisplayFormUrl** | string |  |
| **FileName** | string |  |
| **OwnerName** | string |  |
| **PlayerPageUrl** | string |  |
| **ServerRelativeUrl** | string |  |
| **ThumbnailUrl** | string |  |
| **Title** | string |  |
| **ID** | string |  |
| **Url** | string |  |
| **VideoDurationInSeconds** | string |  |
| **VideoProcessingStatus** | string |  |
| **ViewCount** | string |  |
| **YammerObjectUrl** | string |  |
# VideoPermissionGroup Class

Namespace: Microsoft.SharePoint.Client.Publishing

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Id** | int |  |
| **Users** | UserCollection |  |
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
| **VideoPermissionGroup(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# VideoPermissionGroupObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Publishing


## Fields

| Name | Type | Summary |
|---|---|---|
| **Users** | string |  |
# VideoPermissionGroupPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Publishing


## Fields

| Name | Type | Summary |
|---|---|---|
| **Id** | string |  |
# VideoProcessingStatus Enum

Namespace: Microsoft.SharePoint.Client.Publishing


## Values

| Name | Summary |
|---|---|
| **PendingProcessing** |  |
| **Processing** |  |
| **ReadyForPlay** |  |
| **ErrorOnUploading** |  |
| **ErrorOnProcessing** |  |
| **Timeout** |  |
| **UnsupportedFormat** |  |
# VideoStreamingFormat Enum

Namespace: Microsoft.SharePoint.Client.Publishing


## Values

| Name | Summary |
|---|---|
| **HLS** |  |
| **Streaming** |  |
# ViewControlState Enum

Namespace: Microsoft.SharePoint.Client.Publishing


## Values

| Name | Summary |
|---|---|
| **DefaultState** |  |
| **Popular** |  |
| **Newest** |  |
| **MyVideos** |  |
# NavigationLinkType Enum

Namespace: Microsoft.SharePoint.Client.Publishing.Navigation


## Values

| Name | Summary |
|---|---|
| **Root** |  |
| **FriendlyUrl** |  |
| **SimpleLink** |  |
# NavigationTerm Class

Namespace: Microsoft.SharePoint.Client.Publishing.Navigation

Base class: [NavigationTermSetItem](#navigationtermsetitem-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **AssociatedFolderUrl** | string |  |
| **CatalogTargetUrl** | [CustomizableString](#customizablestring-class) |  |
| **CategoryImageUrl** | string |  |
| **ExcludedProviders** | [NavigationTermProviderNameCollection](#navigationtermprovidernamecollection-class) |  |
| **ExcludeFromCurrentNavigation** | bool |  |
| **ExcludeFromGlobalNavigation** | bool |  |
| **FriendlyUrlSegment** | [CustomizableString](#customizablestring-class) |  |
| **HoverText** | string |  |
| **IsDeprecated** | bool |  |
| **IsPinned** | bool |  |
| **IsPinnedRoot** | bool |  |
| **Parent** | [NavigationTerm](#navigationterm-class) |  |
| **SimpleLinkUrl** | string |  |
| **TargetUrl** | [CustomizableString](#customizablestring-class) |  |
| **TermSet** | [NavigationTermSet](#navigationtermset-class) |  |
| **CatalogTargetUrlForChildTerms** | [CustomizableString](#customizablestring-class) |  |
| **Id** | Guid |  |
| **IsReadOnly** | bool |  |
| **LinkType** | [NavigationLinkType](#navigationlinktype-enum) |  |
| **TargetUrlForChildTerms** | [CustomizableString](#customizablestring-class) |  |
| **TaxonomyName** | string |  |
| **Terms** | [NavigationTermCollection](#navigationtermcollection-class) |  |
| **Title** | [CustomizableString](#customizablestring-class) |  |
| **View** | [NavigationTermSetView](#navigationtermsetview-class) |  |
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
| **NavigationTerm(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
| **GetAllParentTerms()** | [NavigationTermCollection](#navigationtermcollection-class) |  |
| **GetAsEditable(TaxonomySession taxonomySession)** | [NavigationTerm](#navigationterm-class) |  |
| **GetAsResolvedByView(ClientRuntimeContext context, Term term, NavigationTermSetView view)** | [NavigationTerm](#navigationterm-class) |  |
| **GetAsResolvedByWeb(ClientRuntimeContext context, Term term, Web web, string siteMapProviderName)** | [NavigationTerm](#navigationterm-class) |  |
| **GetResolvedAssociatedFolderUrl()** | ClientResult\<string\> |  |
| **GetResolvedTargetUrl(string browserQueryString, string[] remainingUrlSegments)** | ClientResult\<string\> |  |
| **GetResolvedTargetUrlWithoutQuery()** | ClientResult\<string\> |  |
| **GetTaxonomyTerm()** | Term |  |
| **GetWebRelativeFriendlyUrl()** | ClientResult\<string\> |  |
| **GetWithNewView(NavigationTermSetView newView)** | [NavigationTerm](#navigationterm-class) |  |
| **Move(NavigationTermSetItem newParent)** | void |  |
# NavigationTermCollection Class

Namespace: Microsoft.SharePoint.Client.Publishing.Navigation

Base class: ClientObjectCollection<[NavigationTerm](#navigationterm-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [NavigationTerm](#navigationterm-class) |  |
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
| **NavigationTermCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# NavigationTermObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Publishing.Navigation


## Fields

| Name | Type | Summary |
|---|---|---|
| **CatalogTargetUrl** | string |  |
| **ExcludedProviders** | string |  |
| **FriendlyUrlSegment** | string |  |
| **Parent** | string |  |
| **TargetUrl** | string |  |
| **TermSet** | string |  |
# NavigationTermPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Publishing.Navigation


## Fields

| Name | Type | Summary |
|---|---|---|
| **AssociatedFolderUrl** | string |  |
| **CategoryImageUrl** | string |  |
| **ExcludeFromCurrentNavigation** | string |  |
| **ExcludeFromGlobalNavigation** | string |  |
| **HoverText** | string |  |
| **IsDeprecated** | string |  |
| **IsPinned** | string |  |
| **IsPinnedRoot** | string |  |
| **SimpleLinkUrl** | string |  |
# NavigationTermProviderNameCollection Class

Namespace: Microsoft.SharePoint.Client.Publishing.Navigation

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
| **NavigationTermProviderNameCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(string item)** | void |  |
| **Clear()** | void |  |
| **Remove(string item)** | ClientResult\<bool\> |  |
# NavigationTermSet Class

Namespace: Microsoft.SharePoint.Client.Publishing.Navigation

Base class: [NavigationTermSetItem](#navigationtermsetitem-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **IsNavigationTermSet** | bool |  |
| **Lcid** | int |  |
| **LoadedFromPersistedData** | bool |  |
| **TermGroupId** | Guid |  |
| **TermStoreId** | Guid |  |
| **CatalogTargetUrlForChildTerms** | [CustomizableString](#customizablestring-class) |  |
| **Id** | Guid |  |
| **IsReadOnly** | bool |  |
| **LinkType** | [NavigationLinkType](#navigationlinktype-enum) |  |
| **TargetUrlForChildTerms** | [CustomizableString](#customizablestring-class) |  |
| **TaxonomyName** | string |  |
| **Terms** | [NavigationTermCollection](#navigationtermcollection-class) |  |
| **Title** | [CustomizableString](#customizablestring-class) |  |
| **View** | [NavigationTermSetView](#navigationtermsetview-class) |  |
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
| **NavigationTermSet(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **FindTermForUrl(string url)** | [NavigationTerm](#navigationterm-class) |  |
| **GetAllTerms()** | [NavigationTermCollection](#navigationtermcollection-class) |  |
| **GetAsEditable(TaxonomySession taxonomySession)** | [NavigationTermSet](#navigationtermset-class) |  |
| **GetAsResolvedByView(ClientRuntimeContext context, TermSet termSet, NavigationTermSetView view)** | [NavigationTermSet](#navigationtermset-class) |  |
| **GetAsResolvedByWeb(ClientRuntimeContext context, TermSet termSet, Web web, string siteMapProviderName)** | [NavigationTermSet](#navigationtermset-class) |  |
| **GetTaxonomyTermSet()** | TermSet |  |
| **GetWithNewView(NavigationTermSetView newView)** | [NavigationTermSet](#navigationtermset-class) |  |
# NavigationTermSetItem Class

Namespace: Microsoft.SharePoint.Client.Publishing.Navigation

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **CatalogTargetUrlForChildTerms** | [CustomizableString](#customizablestring-class) |  |
| **Id** | Guid |  |
| **IsReadOnly** | bool |  |
| **LinkType** | [NavigationLinkType](#navigationlinktype-enum) |  |
| **TargetUrlForChildTerms** | [CustomizableString](#customizablestring-class) |  |
| **TaxonomyName** | string |  |
| **Terms** | [NavigationTermCollection](#navigationtermcollection-class) |  |
| **Title** | [CustomizableString](#customizablestring-class) |  |
| **View** | [NavigationTermSetView](#navigationtermsetview-class) |  |
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
| **NavigationTermSetItem(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **CreateTerm(string termName, NavigationLinkType linkType, Guid termId)** | [NavigationTerm](#navigationterm-class) |  |
| **GetResolvedDisplayUrl(string browserQueryString)** | ClientResult\<string\> |  |
| **GetTaxonomyTermStore()** | TermStore |  |
# NavigationTermSetItemObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Publishing.Navigation


## Fields

| Name | Type | Summary |
|---|---|---|
| **CatalogTargetUrlForChildTerms** | string |  |
| **TargetUrlForChildTerms** | string |  |
| **Terms** | string |  |
| **Title** | string |  |
| **View** | string |  |
# NavigationTermSetItemPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Publishing.Navigation


## Fields

| Name | Type | Summary |
|---|---|---|
| **Id** | string |  |
| **IsReadOnly** | string |  |
| **LinkType** | string |  |
| **TaxonomyName** | string |  |
# NavigationTermSetPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Publishing.Navigation


## Fields

| Name | Type | Summary |
|---|---|---|
| **IsNavigationTermSet** | string |  |
| **Lcid** | string |  |
| **LoadedFromPersistedData** | string |  |
| **TermGroupId** | string |  |
| **TermStoreId** | string |  |
# NavigationTermSetView Class

Namespace: Microsoft.SharePoint.Client.Publishing.Navigation

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ExcludeDeprecatedTerms** | bool |  |
| **ExcludeTermsByPermissions** | bool |  |
| **ExcludeTermsByProvider** | bool |  |
| **ServerRelativeSiteUrl** | string |  |
| **ServerRelativeWebUrl** | string |  |
| **SiteMapProviderName** | string |  |
| **WebId** | Guid |  |
| **WebTitle** | string |  |
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
| **NavigationTermSetView(ClientRuntimeContext context, ObjectPath objectPath)** |  |
| **NavigationTermSetView(ClientRuntimeContext context, Web web, string siteMapProviderName)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **CreateEmptyInstance(ClientRuntimeContext context)** | [NavigationTermSetView](#navigationtermsetview-class) |  |
| **GetCopy()** | [NavigationTermSetView](#navigationtermsetview-class) |  |
# NavigationTermSetViewPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Publishing.Navigation


## Fields

| Name | Type | Summary |
|---|---|---|
| **ExcludeDeprecatedTerms** | string |  |
| **ExcludeTermsByPermissions** | string |  |
| **ExcludeTermsByProvider** | string |  |
| **ServerRelativeSiteUrl** | string |  |
| **ServerRelativeWebUrl** | string |  |
| **SiteMapProviderName** | string |  |
| **WebId** | string |  |
| **WebTitle** | string |  |
# StandardNavigationSettings Class

Namespace: Microsoft.SharePoint.Client.Publishing.Navigation

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Source** | [StandardNavigationSource](#standardnavigationsource-enum) |  |
| **TermSetId** | Guid |  |
| **TermStoreId** | Guid |  |
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
| **StandardNavigationSettings(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# StandardNavigationSettingsPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Publishing.Navigation


## Fields

| Name | Type | Summary |
|---|---|---|
| **Source** | string |  |
| **TermSetId** | string |  |
| **TermStoreId** | string |  |
# StandardNavigationSource Enum

Namespace: Microsoft.SharePoint.Client.Publishing.Navigation


## Values

| Name | Summary |
|---|---|
| **Unknown** |  |
| **PortalProvider** |  |
| **TaxonomyProvider** |  |
| **InheritFromParentWeb** |  |
# TaxonomyNavigation Class

Namespace: Microsoft.SharePoint.Client.Publishing.Navigation


## Methods

| Name | Returns | Summary |
|---|---|---|
| **FlushSiteFromCache(ClientRuntimeContext context, Site site)** | void |  |
| **FlushTermSetFromCache(ClientRuntimeContext context, Web webForPermissions, Guid termStoreId, Guid termSetId)** | void |  |
| **FlushWebFromCache(ClientRuntimeContext context, Web web)** | void |  |
| **GetNavigationLcidForWeb(ClientRuntimeContext context, Web web)** | ClientResult\<int\> |  |
| **GetTermSetForWeb(ClientRuntimeContext context, Web web, string siteMapProviderName, bool includeInheritedSettings)** | [NavigationTermSet](#navigationtermset-class) |  |
| **GetWebNavigationSettings(ClientRuntimeContext context, Web web)** | [WebNavigationSettings](#webnavigationsettings-class) |  |
| **SetCrawlAsFriendlyUrlPage(ClientRuntimeContext context, NavigationTerm navigationTerm, bool crawlAsFriendlyUrlPage)** | ClientResult\<bool\> |  |
# WebNavigationSettings Class

Namespace: Microsoft.SharePoint.Client.Publishing.Navigation

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AddNewPagesToNavigation** | bool |  |
| **CreateFriendlyUrlsForNewPages** | bool |  |
| **CurrentNavigation** | [StandardNavigationSettings](#standardnavigationsettings-class) |  |
| **GlobalNavigation** | [StandardNavigationSettings](#standardnavigationsettings-class) |  |
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
| **WebNavigationSettings(ClientRuntimeContext context, Web web)** |  |
| **WebNavigationSettings(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **ResetToDefaults()** | void |  |
| **Update(TaxonomySession taxonomySession)** | void |  |
# WebNavigationSettingsObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Publishing.Navigation


## Fields

| Name | Type | Summary |
|---|---|---|
| **CurrentNavigation** | string |  |
| **GlobalNavigation** | string |  |
# WebNavigationSettingsPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Publishing.Navigation


## Fields

| Name | Type | Summary |
|---|---|---|
| **AddNewPagesToNavigation** | string |  |
| **CreateFriendlyUrlsForNewPages** | string |  |
