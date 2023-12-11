# Microsoft.SharePoint.Client.Publishing.dll v.16.1.0.0 API documentation

Created by 
[mddox](https://github.com/loxsmoke/mddox) on 2023-12-11

# All types

|   |   |   |
|---|---|---|
| [EmailPublishingStatus Class](#emailpublishingstatus-class) | [ScheduledItemObjectPropertyNames Class](#scheduleditemobjectpropertynames-class) | [VideoPermissionGroup Class](#videopermissiongroup-class) |
| [PrePublishValidationsErrorCodesForEmail Class](#prepublishvalidationserrorcodesforemail-class) | [ScheduledItemPropertyNames Class](#scheduleditempropertynames-class) | [VideoPermissionGroupObjectPropertyNames Class](#videopermissiongroupobjectpropertynames-class) |
| [PrePublishValidationsErrorCodesForSharePointSite Class](#prepublishvalidationserrorcodesforsharepointsite-class) | [ScriptTypeFactory Class](#scripttypefactory-class) | [VideoPermissionGroupPropertyNames Class](#videopermissiongrouppropertynames-class) |
| [PrePublishValidationsErrorCodesForTeams Class](#prepublishvalidationserrorcodesforteams-class) | [Search Class](#search-class) | [VideoPlaybackMetadata Class](#videoplaybackmetadata-class) |
| [PrePublishValidationsResponse Class](#prepublishvalidationsresponse-class) | [SearchPropertyNames Class](#searchpropertynames-class) | [VideoPlaybackMetadataPropertyNames Class](#videoplaybackmetadatapropertynames-class) |
| [PublishingStatus Enum](#publishingstatus-enum) | [SharePagePreviewByEmailFieldsData Class](#sharepagepreviewbyemailfieldsdata-class) | [VideoPlaybackOrigin Enum](#videoplaybackorigin-enum) |
| [PublishingStatusResponse Class](#publishingstatusresponse-class) | [SiteImageRenditions Class](#siteimagerenditions-class) | [VideoProcessingStatus Enum](#videoprocessingstatus-enum) |
| [PublishPublicationResponse Class](#publishpublicationresponse-class) | [SitePage3DFieldsData Class](#sitepage3dfieldsdata-class) | [VideoStreamingFormat Enum](#videostreamingformat-enum) |
| [SchedulePublicationResponse Class](#schedulepublicationresponse-class) | [SitePageAuthoringMetadata Class](#sitepageauthoringmetadata-class) | [VideoThumbnail Class](#videothumbnail-class) |
| [SendTestEmailResponse Class](#sendtestemailresponse-class) | [SitePageAuthoringMetadataPropertyNames Class](#sitepageauthoringmetadatapropertynames-class) | [VideoThumbnailChoices Enum](#videothumbnailchoices-enum) |
| [SendTestTeamsMessageResponse Class](#sendtestteamsmessageresponse-class) | [SitePageCoAuthAction Enum](#sitepagecoauthaction-enum) | [VideoThumbnailCollection Class](#videothumbnailcollection-class) |
| [SharePointPublishingStatus Class](#sharepointpublishingstatus-class) | [SitePageCoAuthLockAction Enum](#sitepagecoauthlockaction-enum) | [VideoThumbnailPropertyNames Class](#videothumbnailpropertynames-class) |
| [SharePointPublishingStatusResponse Class](#sharepointpublishingstatusresponse-class) | [SitePageCoAuthState Class](#sitepagecoauthstate-class) | [ViewControlState Enum](#viewcontrolstate-enum) |
| [TeamsPublishingStatus Class](#teamspublishingstatus-class) | [SitePageFieldsData Class](#sitepagefieldsdata-class) | [NavigationLinkType Enum](#navigationlinktype-enum) |
| [TeamsPublishingStatusResponse Class](#teamspublishingstatusresponse-class) | [SitePageVersionInfo Class](#sitepageversioninfo-class) | [NavigationTerm Class](#navigationterm-class) |
| [VivaEngagePublishingStatus Class](#vivaengagepublishingstatus-class) | [SitePageVersionInfoCollection Class](#sitepageversioninfocollection-class) | [NavigationTermCollection Class](#navigationtermcollection-class) |
| [AcronymInformation Class](#acronyminformation-class) | [SiteServicesAddins Class](#siteservicesaddins-class) | [NavigationTermObjectPropertyNames Class](#navigationtermobjectpropertynames-class) |
| [AddinPlugin Class](#addinplugin-class) | [SiteSharingEmailContext Class](#sitesharingemailcontext-class) | [NavigationTermPropertyNames Class](#navigationtermpropertynames-class) |
| [AddinPluginPropertyNames Class](#addinpluginpropertynames-class) | [SpotlightChannel Class](#spotlightchannel-class) | [NavigationTermProviderNameCollection Class](#navigationtermprovidernamecollection-class) |
| [AddinSettings Class](#addinsettings-class) | [SpotlightChannelCollection Class](#spotlightchannelcollection-class) | [NavigationTermSet Class](#navigationtermset-class) |
| [AddinSettingsPropertyNames Class](#addinsettingspropertynames-class) | [SpotlightChannelObjectPropertyNames Class](#spotlightchannelobjectpropertynames-class) | [NavigationTermSetItem Class](#navigationtermsetitem-class) |
| [BoostFieldsData Class](#boostfieldsdata-class) | [SpotlightChannelPropertyNames Class](#spotlightchannelpropertynames-class) | [NavigationTermSetItemObjectPropertyNames Class](#navigationtermsetitemobjectpropertynames-class) |
| [CampaignPublicationFieldsData Class](#campaignpublicationfieldsdata-class) | [SpotlightVideo Class](#spotlightvideo-class) | [NavigationTermSetItemPropertyNames Class](#navigationtermsetitempropertynames-class) |
| [CampaignPublicationMailDraftData Class](#campaignpublicationmaildraftdata-class) | [SpotlightVideoCollection Class](#spotlightvideocollection-class) | [NavigationTermSetPropertyNames Class](#navigationtermsetpropertynames-class) |
| [ChannelPermission Enum](#channelpermission-enum) | [SpotlightVideoObjectPropertyNames Class](#spotlightvideoobjectpropertynames-class) | [NavigationTermSetView Class](#navigationtermsetview-class) |
| [CustomizableString Class](#customizablestring-class) | [SpotlightVideoPropertyNames Class](#spotlightvideopropertynames-class) | [NavigationTermSetViewPropertyNames Class](#navigationtermsetviewpropertynames-class) |
| [CustomizableStringPropertyNames Class](#customizablestringpropertynames-class) | [SubtitleCollection Class](#subtitlecollection-class) | [PortalNavigationCacheState Enum](#portalnavigationcachestate-enum) |
| [DesignPackage Class](#designpackage-class) | [SubtitleFile Class](#subtitlefile-class) | [StandardNavigationSettings Class](#standardnavigationsettings-class) |
| [DesignPackageInfo Class](#designpackageinfo-class) | [SubtitleFilePropertyNames Class](#subtitlefilepropertynames-class) | [StandardNavigationSettingsPropertyNames Class](#standardnavigationsettingspropertynames-class) |
| [EnumerateOnlyVideoCollection Class](#enumerateonlyvideocollection-class) | [TextValueWithLanguage Class](#textvaluewithlanguage-class) | [StandardNavigationSource Enum](#standardnavigationsource-enum) |
| [FeedVideoPageFieldsData Class](#feedvideopagefieldsdata-class) | [TopicPageFieldsData Class](#topicpagefieldsdata-class) | [TaxonomyNavigation Class](#taxonomynavigation-class) |
| [ImageRendition Class](#imagerendition-class) | [VariationLabel Class](#variationlabel-class) | [WebNavigationSettings Class](#webnavigationsettings-class) |
| [PageLayoutCreationInformation Class](#pagelayoutcreationinformation-class) | [VariationLabelPropertyNames Class](#variationlabelpropertynames-class) | [WebNavigationSettingsObjectPropertyNames Class](#webnavigationsettingsobjectpropertynames-class) |
| [PortalPermission Enum](#portalpermission-enum) | [Variations Class](#variations-class) | [WebNavigationSettingsPropertyNames Class](#webnavigationsettingspropertynames-class) |
| [PublicationStatus Enum](#publicationstatus-enum) | [VideoChannel Class](#videochannel-class) | [PortalLaunchRedirectionType Enum](#portallaunchredirectiontype-enum) |
| [PublishingPage Class](#publishingpage-class) | [VideoChannelCollection Class](#videochannelcollection-class) | [PortalLaunchSetupWrapper Class](#portallaunchsetupwrapper-class) |
| [PublishingPageInformation Class](#publishingpageinformation-class) | [VideoChannelObjectPropertyNames Class](#videochannelobjectpropertynames-class) | [PortalLaunchStatus Enum](#portallaunchstatus-enum) |
| [PublishingSite Class](#publishingsite-class) | [VideoChannelPropertyNames Class](#videochannelpropertynames-class) | [PortalLaunchUsersSizeType Enum](#portallaunchuserssizetype-enum) |
| [PublishingWeb Class](#publishingweb-class) | [VideoCollection Class](#videocollection-class) | [PortalLaunchWave Class](#portallaunchwave-class) |
| [PublishingWebObjectPropertyNames Class](#publishingwebobjectpropertynames-class) | [VideoItem Class](#videoitem-class) | [PortalLaunchWaveGroup Class](#portallaunchwavegroup-class) |
| [RepostPageFieldsData Class](#repostpagefieldsdata-class) | [VideoItemObjectPropertyNames Class](#videoitemobjectpropertynames-class) | [PortalLaunchWaveSetup Class](#portallaunchwavesetup-class) |
| [ScheduledItem Class](#scheduleditem-class) | [VideoItemPropertyNames Class](#videoitempropertynames-class) |   |
# EmailPublishingStatus Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **DestinationURL** | string |  |
| **ErrorCode** | int |  |
| **Status** | [PublishingStatus](#publishingstatus-enum) |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# PrePublishValidationsErrorCodesForEmail Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **EmailAddress** | string |  |
| **ErrorCodes** | IList\<int\> |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# PrePublishValidationsErrorCodesForSharePointSite Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ErrorCodes** | IList\<int\> |  |
| **SiteId** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# PrePublishValidationsErrorCodesForTeams Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AudienceId** | string |  |
| **ErrorCodes** | IList\<int\> |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# PrePublishValidationsResponse Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ErrorCodes** | IEnumerable\<int\> |  |
| **PrePublishValidationsErrorCodesForEmails** | IList\<[PrePublishValidationsErrorCodesForEmail](#prepublishvalidationserrorcodesforemail-class)\> |  |
| **PrePublishValidationsErrorCodesForSharePointSites** | IList\<[PrePublishValidationsErrorCodesForSharePointSite](#prepublishvalidationserrorcodesforsharepointsite-class)\> |  |
| **PrePublishValidationsErrorCodesForTeams** | IList\<[PrePublishValidationsErrorCodesForTeams](#prepublishvalidationserrorcodesforteams-class)\> |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# PublishingStatus Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **Publishing** |  |
| **Failed** |  |
| **Successful** |  |
# PublishingStatusResponse Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **EmailPublishingStatus** | [EmailPublishingStatus](#emailpublishingstatus-class) |  |
| **LastTriedAt** | DateTime |  |
| **PrePublishValidationErrorCode** | int |  |
| **PublishingStatus** | [PublishingStatus](#publishingstatus-enum) |  |
| **SharePointPublishingStatus** | IList\<[SharePointPublishingStatusResponse](#sharepointpublishingstatusresponse-class)\> |  |
| **TeamsPublishingStatus** | IList\<[TeamsPublishingStatusResponse](#teamspublishingstatusresponse-class)\> |  |
| **VivaEngagePublishingStatus** | [VivaEngagePublishingStatus](#vivaengagepublishingstatus-class) |  |
| **YammerPublishingStatus** | IDictionary\<string, string\> |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# PublishPublicationResponse Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ErrorCode** | int |  |
| **Message** | string |  |
| **Status** | bool |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SchedulePublicationResponse Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **PublicationStatus** | [PublicationStatus](#publicationstatus-enum) |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SendTestEmailResponse Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ErrorCode** | int |  |
| **Response** | bool |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SendTestTeamsMessageResponse Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ErrorCode** | int |  |
| **Response** | bool |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SharePointPublishingStatus Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **DestinationPageURL** | string |  |
| **ErrorCode** | int |  |
| **Status** | [PublishingStatus](#publishingstatus-enum) |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SharePointPublishingStatusResponse Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **SiteId** | string |  |
| **Status** | [SharePointPublishingStatus](#sharepointpublishingstatus-class) |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# TeamsPublishingStatus Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AudienceId** | string |  |
| **ErrorCode** | int |  |
| **ErrorMessage** | string |  |
| **HttpStatusCode** | int |  |
| **Status** | [PublishingStatus](#publishingstatus-enum) |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# TeamsPublishingStatusResponse Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AudienceId** | string |  |
| **Status** | [TeamsPublishingStatus](#teamspublishingstatus-class) |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# VivaEngagePublishingStatus Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **DestinationId** | string |  |
| **ErrorCode** | int |  |
| **ErrorMessage** | string |  |
| **Status** | [PublishingStatus](#publishingstatus-enum) |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# AcronymInformation Class

Namespace: Microsoft.SharePoint.Client.Publishing

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Acronym** | string |  |
| **Color** | string |  |
| **Lcid** | int |  |
| **Text** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
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
# BoostFieldsData Class

Namespace: Microsoft.SharePoint.Client.Publishing

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **BoostOrderType** | [BoostFieldsData](#boostfieldsdata-class) |  |
| **BoostUntilSeen** | bool |  |
| **Expiry** | DateTime |  |
| **Impressions** | uint |  |
| **NextItemId** | int |  |
| **NextItemVersion** | int |  |
| **PreviousItemId** | int |  |
| **PreviousItemVersion** | int |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# CampaignPublicationFieldsData Class

Namespace: Microsoft.SharePoint.Client.Publishing

Base class: [SitePageFieldsData](#sitepagefieldsdata-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **EndpointEmail** | string |  |
| **EndpointSharePoint** | string |  |
| **EndpointTeams** | string |  |
| **EndpointVivaEngage** | string |  |
| **EndpointYammer** | string |  |
| **PublicationMetadata** | string |  |
| **PublicationStatus** | [PublicationStatus](#publicationstatus-enum) |  |
| **TypeId** | string |  |
| **AuthorByline** | string[] |  |
| **AuthoringMetadata** | [SitePageAuthoringMetadata](#sitepageauthoringmetadata-class) |  |
| **BannerImageUrl** | string |  |
| **CallToAction** | string |  |
| **CanvasContent1** | string |  |
| **CanvasJson1** | string |  |
| **Categories** | string |  |
| **CoAuthState** | [SitePageCoAuthState](#sitepagecoauthstate-class) |  |
| **Description** | string |  |
| **EmailTranspileContent** | string |  |
| **HiddenHighlightsMetadata** | string |  |
| **HideListEditorMetadata** | string |  |
| **LayoutWebpartsContent** | string |  |
| **Modified** | DateTime |  |
| **PublishStartDate** | DateTime |  |
| **TeamsTranspileContent** | string |  |
| **Title** | string |  |
| **TopicHeader** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# CampaignPublicationMailDraftData Class

Namespace: Microsoft.SharePoint.Client.Publishing

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **DraftId** | string |  |
| **GroupUpn** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
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
# FeedVideoPageFieldsData Class

Namespace: Microsoft.SharePoint.Client.Publishing

Base class: [RepostPageFieldsData](#repostpagefieldsdata-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **TypeId** | string |  |
| **AuthorByline** | string[] |  |
| **AuthoringMetadata** | [SitePageAuthoringMetadata](#sitepageauthoringmetadata-class) |  |
| **BannerImageUrl** | string |  |
| **CallToAction** | string |  |
| **CanvasContent1** | string |  |
| **CanvasJson1** | string |  |
| **Categories** | string |  |
| **CoAuthState** | [SitePageCoAuthState](#sitepagecoauthstate-class) |  |
| **Description** | string |  |
| **EmailTranspileContent** | string |  |
| **HiddenHighlightsMetadata** | string |  |
| **HideListEditorMetadata** | string |  |
| **LayoutWebpartsContent** | string |  |
| **Modified** | DateTime |  |
| **PublishStartDate** | DateTime |  |
| **TeamsTranspileContent** | string |  |
| **Title** | string |  |
| **TopicHeader** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
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
# PublicationStatus Enum

Namespace: Microsoft.SharePoint.Client.Publishing


## Values

| Name | Summary |
|---|---|
| **Draft** |  |
| **Publishing** |  |
| **Published** |  |
| **NeedsAttention** |  |
| **PendingApproval** |  |
| **Rejected** |  |
| **ReadyToPublish** |  |
| **Scheduled** |  |
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
# RepostPageFieldsData Class

Namespace: Microsoft.SharePoint.Client.Publishing

Base class: [SitePageFieldsData](#sitepagefieldsdata-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **TypeId** | string |  |
| **AuthorByline** | string[] |  |
| **AuthoringMetadata** | [SitePageAuthoringMetadata](#sitepageauthoringmetadata-class) |  |
| **BannerImageUrl** | string |  |
| **CallToAction** | string |  |
| **CanvasContent1** | string |  |
| **CanvasJson1** | string |  |
| **Categories** | string |  |
| **CoAuthState** | [SitePageCoAuthState](#sitepagecoauthstate-class) |  |
| **Description** | string |  |
| **EmailTranspileContent** | string |  |
| **HiddenHighlightsMetadata** | string |  |
| **HideListEditorMetadata** | string |  |
| **LayoutWebpartsContent** | string |  |
| **Modified** | DateTime |  |
| **PublishStartDate** | DateTime |  |
| **TeamsTranspileContent** | string |  |
| **Title** | string |  |
| **TopicHeader** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
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
| **QueryLanguages** | int[] |  |
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
# SearchPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Publishing


## Fields

| Name | Type | Summary |
|---|---|---|
| **QueryLanguages** | string |  |
# SharePagePreviewByEmailFieldsData Class

Namespace: Microsoft.SharePoint.Client.Publishing

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **message** | string |  |
| **recipientEmails** | string[] |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SiteImageRenditions Class

Namespace: Microsoft.SharePoint.Client.Publishing


## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetRenditions(ClientRuntimeContext context)** | IList\<[ImageRendition](#imagerendition-class)\> |  |
| **SetRenditions(ClientRuntimeContext context, IList\<ImageRendition\> renditions)** | void |  |
# SitePage3DFieldsData Class

Namespace: Microsoft.SharePoint.Client.Publishing

Base class: [SitePageFieldsData](#sitepagefieldsdata-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **SpaceContent** | string |  |
| **TypeId** | string |  |
| **AuthorByline** | string[] |  |
| **AuthoringMetadata** | [SitePageAuthoringMetadata](#sitepageauthoringmetadata-class) |  |
| **BannerImageUrl** | string |  |
| **CallToAction** | string |  |
| **CanvasContent1** | string |  |
| **CanvasJson1** | string |  |
| **Categories** | string |  |
| **CoAuthState** | [SitePageCoAuthState](#sitepagecoauthstate-class) |  |
| **Description** | string |  |
| **EmailTranspileContent** | string |  |
| **HiddenHighlightsMetadata** | string |  |
| **HideListEditorMetadata** | string |  |
| **LayoutWebpartsContent** | string |  |
| **Modified** | DateTime |  |
| **PublishStartDate** | DateTime |  |
| **TeamsTranspileContent** | string |  |
| **Title** | string |  |
| **TopicHeader** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SitePageAuthoringMetadata Class

Namespace: Microsoft.SharePoint.Client.Publishing

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **SequenceId** | string |  |
| **SessionId** | string |  |
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
| **SitePageAuthoringMetadata(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# SitePageAuthoringMetadataPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Publishing


## Fields

| Name | Type | Summary |
|---|---|---|
| **SequenceId** | string |  |
| **SessionId** | string |  |
# SitePageCoAuthAction Enum

Namespace: Microsoft.SharePoint.Client.Publishing


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **Save** |  |
| **SaveNew** |  |
# SitePageCoAuthLockAction Enum

Namespace: Microsoft.SharePoint.Client.Publishing


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **Refresh** |  |
| **Release** |  |
# SitePageCoAuthState Class

Namespace: Microsoft.SharePoint.Client.Publishing

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Action** | [SitePageCoAuthAction](#sitepagecoauthaction-enum) |  |
| **HasReachedMinorVersionsLimit** | bool |  |
| **IsNewSession** | bool |  |
| **LockAction** | [SitePageCoAuthLockAction](#sitepagecoauthlockaction-enum) |  |
| **LockDuration** | int |  |
| **OverwriteExistingVersion** | bool |  |
| **SharedLockId** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SitePageFieldsData Class

Namespace: Microsoft.SharePoint.Client.Publishing

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AuthorByline** | string[] |  |
| **AuthoringMetadata** | [SitePageAuthoringMetadata](#sitepageauthoringmetadata-class) |  |
| **BannerImageUrl** | string |  |
| **CallToAction** | string |  |
| **CanvasContent1** | string |  |
| **CanvasJson1** | string |  |
| **Categories** | string |  |
| **CoAuthState** | [SitePageCoAuthState](#sitepagecoauthstate-class) |  |
| **Description** | string |  |
| **EmailTranspileContent** | string |  |
| **HiddenHighlightsMetadata** | string |  |
| **HideListEditorMetadata** | string |  |
| **LayoutWebpartsContent** | string |  |
| **Modified** | DateTime |  |
| **PublishStartDate** | DateTime |  |
| **TeamsTranspileContent** | string |  |
| **Title** | string |  |
| **TopicHeader** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SitePageVersionInfo Class

Namespace: Microsoft.SharePoint.Client.Publishing

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **LastVersionCreated** | DateTime |  |
| **LastVersionCreatedBy** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SitePageVersionInfoCollection Class

Namespace: Microsoft.SharePoint.Client.Publishing

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Created** | DateTime |  |
| **CreatedBy** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
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
# SiteSharingEmailContext Class

Namespace: Microsoft.SharePoint.Client.Publishing

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **CustomDescription** | string |  |
| **CustomTitle** | string |  |
| **Message** | string |  |
| **Url** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
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
# SubtitleCollection Class

Namespace: Microsoft.SharePoint.Client.Publishing

Base class: ClientObjectCollection<[SubtitleFile](#subtitlefile-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [SubtitleFile](#subtitlefile-class) |  |
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
| **SubtitleCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetSubtitleFile(string name)** | ClientResult\<Stream\> |  |
# SubtitleFile Class

Namespace: Microsoft.SharePoint.Client.Publishing

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Language** | string |  |
| **NativeLanguageName** | string |  |
| **Url** | string |  |
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
| **SubtitleFile(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# SubtitleFilePropertyNames Class

Namespace: Microsoft.SharePoint.Client.Publishing


## Fields

| Name | Type | Summary |
|---|---|---|
| **Language** | string |  |
| **NativeLanguageName** | string |  |
| **Url** | string |  |
# TextValueWithLanguage Class

Namespace: Microsoft.SharePoint.Client.Publishing

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ColorSeed** | string |  |
| **Lcid** | int |  |
| **Text** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# TopicPageFieldsData Class

Namespace: Microsoft.SharePoint.Client.Publishing

Base class: [SitePageFieldsData](#sitepagefieldsdata-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **EntityId** | string |  |
| **EntityRelations** | string |  |
| **EntityType** | string |  |
| **VerifiedTopicAllowedEditors** | string |  |
| **TypeId** | string |  |
| **AuthorByline** | string[] |  |
| **AuthoringMetadata** | [SitePageAuthoringMetadata](#sitepageauthoringmetadata-class) |  |
| **BannerImageUrl** | string |  |
| **CallToAction** | string |  |
| **CanvasContent1** | string |  |
| **CanvasJson1** | string |  |
| **Categories** | string |  |
| **CoAuthState** | [SitePageCoAuthState](#sitepagecoauthstate-class) |  |
| **Description** | string |  |
| **EmailTranspileContent** | string |  |
| **HiddenHighlightsMetadata** | string |  |
| **HideListEditorMetadata** | string |  |
| **LayoutWebpartsContent** | string |  |
| **Modified** | DateTime |  |
| **PublishStartDate** | DateTime |  |
| **TeamsTranspileContent** | string |  |
| **Title** | string |  |
| **TopicHeader** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
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
| **CanAdministrateByCurrent** | bool |  |
| **CanEditByCurrent** | bool |  |
| **CanViewByCurrent** | bool |  |
| **ChannelPageUrl** | string |  |
| **Description** | string |  |
| **DownloadUrlVisibleMinPermission** | [ChannelPermission](#channelpermission-enum) |  |
| **FullUrl** | string |  |
| **Id** | Guid |  |
| **Search** | [Search](#search-class) |  |
| **ServerRelativeUrl** | string |  |
| **ShareByEmailEnabled** | bool |  |
| **SpotlightVideos** | [SpotlightVideoCollection](#spotlightvideocollection-class) |  |
| **TileHtmlColor** | string |  |
| **Title** | string |  |
| **Videos** | [VideoCollection](#videocollection-class) |  |
| **YammerDefaultGroupId** | int |  |
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
| **CanAdministrateByCurrent** | string |  |
| **CanEditByCurrent** | string |  |
| **CanViewByCurrent** | string |  |
| **ChannelPageUrl** | string |  |
| **Description** | string |  |
| **DownloadUrlVisibleMinPermission** | string |  |
| **FullUrl** | string |  |
| **Id** | string |  |
| **ServerRelativeUrl** | string |  |
| **ShareByEmailEnabled** | string |  |
| **TileHtmlColor** | string |  |
| **Title** | string |  |
| **YammerDefaultGroupId** | string |  |
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
| **DefaultEmbedCode** | string |  |
| **Description** | string |  |
| **DisplayFormUrl** | string |  |
| **FileName** | string |  |
| **Owner** | User |  |
| **OwnerName** | string |  |
| **PeopleInMedia** | UserCollection |  |
| **PlayerPageUrl** | string |  |
| **ServerRelativeUrl** | string |  |
| **ThumbnailSelection** | [VideoThumbnailChoices](#videothumbnailchoices-enum) |  |
| **ThumbnailUrl** | string |  |
| **Title** | string |  |
| **ID** | Guid |  |
| **Url** | string |  |
| **VideoDownloadUrl** | string |  |
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
| **GetPlaybackMetadata(string sdnConfiguration)** | [VideoPlaybackMetadata](#videoplaybackmetadata-class) |  |
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
| **DefaultEmbedCode** | string |  |
| **Description** | string |  |
| **DisplayFormUrl** | string |  |
| **FileName** | string |  |
| **OwnerName** | string |  |
| **PlayerPageUrl** | string |  |
| **ServerRelativeUrl** | string |  |
| **ThumbnailSelection** | string |  |
| **ThumbnailUrl** | string |  |
| **Title** | string |  |
| **ID** | string |  |
| **Url** | string |  |
| **VideoDownloadUrl** | string |  |
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
# VideoPlaybackMetadata Class

Namespace: Microsoft.SharePoint.Client.Publishing

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **HLSUrl** | string |  |
| **SdnPlaybackMetadata** | string |  |
| **StreamingUrl** | string |  |
| **Token** | string |  |
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
| **VideoPlaybackMetadata(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# VideoPlaybackMetadataPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Publishing


## Fields

| Name | Type | Summary |
|---|---|---|
| **HLSUrl** | string |  |
| **SdnPlaybackMetadata** | string |  |
| **StreamingUrl** | string |  |
| **Token** | string |  |
# VideoPlaybackOrigin Enum

Namespace: Microsoft.SharePoint.Client.Publishing


## Values

| Name | Summary |
|---|---|
| **Other** |  |
| **VideoPortal** |  |
| **EmbeddedPlayer** |  |
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
| **CorruptedFile** |  |
# VideoStreamingFormat Enum

Namespace: Microsoft.SharePoint.Client.Publishing


## Values

| Name | Summary |
|---|---|
| **HLS** |  |
| **Streaming** |  |
# VideoThumbnail Class

Namespace: Microsoft.SharePoint.Client.Publishing

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Choice** | [VideoThumbnailChoices](#videothumbnailchoices-enum) |  |
| **IsSelected** | bool |  |
| **Url** | string |  |
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
| **VideoThumbnail(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# VideoThumbnailChoices Enum

Namespace: Microsoft.SharePoint.Client.Publishing


## Values

| Name | Summary |
|---|---|
| **First** |  |
| **Second** |  |
| **Third** |  |
| **Fourth** |  |
| **Fifth** |  |
| **Custom** |  |
# VideoThumbnailCollection Class

Namespace: Microsoft.SharePoint.Client.Publishing

Base class: ClientObjectCollection<[VideoThumbnail](#videothumbnail-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [VideoThumbnail](#videothumbnail-class) |  |
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
| **VideoThumbnailCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetByIndex(VideoThumbnailChoices choice)** | [VideoThumbnail](#videothumbnail-class) |  |
# VideoThumbnailPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Publishing


## Fields

| Name | Type | Summary |
|---|---|---|
| **Choice** | string |  |
| **IsSelected** | string |  |
| **Url** | string |  |
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
| **TargetSiteId** | [CustomizableString](#customizablestring-class) |  |
| **TargetTermSetId** | [CustomizableString](#customizablestring-class) |  |
| **TargetUrl** | [CustomizableString](#customizablestring-class) |  |
| **TargetUrlListId** | [CustomizableString](#customizablestring-class) |  |
| **TargetUrlListItemId** | [CustomizableString](#customizablestring-class) |  |
| **TargetUrlWebId** | [CustomizableString](#customizablestring-class) |  |
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
| **TargetSiteId** | string |  |
| **TargetTermSetId** | string |  |
| **TargetUrl** | string |  |
| **TargetUrlListId** | string |  |
| **TargetUrlListItemId** | string |  |
| **TargetUrlWebId** | string |  |
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
# PortalNavigationCacheState Enum

Namespace: Microsoft.SharePoint.Client.Publishing.Navigation


## Values

| Name | Summary |
|---|---|
| **Enabled** |  |
| **PendingEnable** |  |
| **Refreshing** |  |
| **PendingOptOut** |  |
| **OptedOut** |  |
| **EnabledGlobal** |  |
| **EnabledCurrent** |  |
| **EnabledBoth** |  |
| **NotNeeded** |  |
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
| **CachedHierarchyDepth** | int |  |
| **CacheSchemaVersion** | int |  |
| **CachingRetryAttemptLeft** | int |  |
| **CachingState** | [PortalNavigationCacheState](#portalnavigationcachestate-enum) |  |
| **CreateFriendlyUrlsForNewPages** | bool |  |
| **CurrentNavigation** | [StandardNavigationSettings](#standardnavigationsettings-class) |  |
| **GlobalNavigation** | [StandardNavigationSettings](#standardnavigationsettings-class) |  |
| **LastCachingRefreshAttempted** | DateTime |  |
| **PortalNavigationSuccessfulRefreshID** | Guid |  |
| **PortalNavigationSuccessfulRefreshTime** | DateTime |  |
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
| **CachedHierarchyDepth** | string |  |
| **CacheSchemaVersion** | string |  |
| **CachingRetryAttemptLeft** | string |  |
| **CachingState** | string |  |
| **CreateFriendlyUrlsForNewPages** | string |  |
| **LastCachingRefreshAttempted** | string |  |
| **PortalNavigationSuccessfulRefreshID** | string |  |
| **PortalNavigationSuccessfulRefreshTime** | string |  |
# PortalLaunchRedirectionType Enum

Namespace: Microsoft.SharePoint.Client.Publishing.PortalLaunch


## Values

| Name | Summary |
|---|---|
| **Bidirectional** |  |
| **ToTemporaryPage** |  |
| **SiteBased** |  |
# PortalLaunchSetupWrapper Class

Namespace: Microsoft.SharePoint.Client.Publishing.PortalLaunch

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **SPPortalLaunchWaveSetups** | IDictionary\<string, [PortalLaunchWaveSetup](#portallaunchwavesetup-class)\> |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# PortalLaunchStatus Enum

Namespace: Microsoft.SharePoint.Client.Publishing.PortalLaunch


## Values

| Name | Summary |
|---|---|
| **Created** |  |
| **Started** |  |
| **Paused** |  |
| **Canceled** |  |
| **Completed** |  |
| **Deleted** |  |
# PortalLaunchUsersSizeType Enum

Namespace: Microsoft.SharePoint.Client.Publishing.PortalLaunch


## Values

| Name | Summary |
|---|---|
| **LessThan10kUsers** |  |
| **From10kTo30kUsers** |  |
| **From30kTo100KUsers** |  |
| **MoreThan100kUsers** |  |
# PortalLaunchWave Class

Namespace: Microsoft.SharePoint.Client.Publishing.PortalLaunch

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Groups** | IList\<[PortalLaunchWaveGroup](#portallaunchwavegroup-class)\> |  |
| **LaunchDateUtc** | DateTime |  |
| **Name** | string |  |
| **Order** | int |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# PortalLaunchWaveGroup Class

Namespace: Microsoft.SharePoint.Client.Publishing.PortalLaunch

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Id** | Guid |  |
| **SiteUrl** | string |  |
| **UserGroupName** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# PortalLaunchWaveSetup Class

Namespace: Microsoft.SharePoint.Client.Publishing.PortalLaunch

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AlternativeUrlsOfNewSite** | string |  |
| **AlternativeUrlsOfOldSite** | string |  |
| **CreatedOn** | DateTime |  |
| **ExpectedUsersSize** | [PortalLaunchUsersSizeType](#portallaunchuserssizetype-enum) |  |
| **IsPaused** | bool |  |
| **ModifiedOn** | DateTime |  |
| **NewSiteUrl** | string |  |
| **OwnersAndEditors** | IDictionary\<string, string\> |  |
| **PauseAtWave** | int |  |
| **RedirectionType** | [PortalLaunchRedirectionType](#portallaunchredirectiontype-enum) |  |
| **RedirectUrl** | string |  |
| **SiteId** | Guid |  |
| **Status** | [PortalLaunchStatus](#portallaunchstatus-enum) |  |
| **WaveOverrideUsers** | string |  |
| **Waves** | IList\<[PortalLaunchWave](#portallaunchwave-class)\> |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
