# Microsoft.SharePoint.Client.UserProfiles.dll v.16.1.0.0 API documentation

Created by 
[mddox](https://github.com/loxsmoke/mddox) on 2025-05-12

# All types

|   |   |   |
|---|---|---|
| [Reputation Class](#reputation-class) | [SocialActorType Enum](#socialactortype-enum) | [SocialThread Class](#socialthread-class) |
| [IdentifierEncoding Enum](#identifierencoding-enum) | [SocialActorTypes Enum](#socialactortypes-enum) | [SocialThreadAttributes Enum](#socialthreadattributes-enum) |
| [MicroBlogEntity Class](#microblogentity-class) | [SocialAnnouncementManager Class](#socialannouncementmanager-class) | [SocialThreadType Enum](#socialthreadtype-enum) |
| [MicroBlogEntityCollection Class](#microblogentitycollection-class) | [SocialAttachment Class](#socialattachment-class) | [ChangeTypes Enum](#changetypes-enum) |
| [MicroBlogEntityType Enum](#microblogentitytype-enum) | [SocialAttachmentAction Class](#socialattachmentaction-class) | [CrossGeoSync Class](#crossgeosync-class) |
| [MicroBlogType Enum](#microblogtype-enum) | [SocialAttachmentActionKind Enum](#socialattachmentactionkind-enum) | [CrossGeoSyncUserDataBatch Class](#crossgeosyncuserdatabatch-class) |
| [MicrofeedAttachmentStore Class](#microfeedattachmentstore-class) | [SocialAttachmentKind Enum](#socialattachmentkind-enum) | [CrossGeoSyncUserProperty Class](#crossgeosyncuserproperty-class) |
| [MicrofeedContentFormattingOptions Enum](#microfeedcontentformattingoptions-enum) | [SocialDataItem Class](#socialdataitem-class) | [FollowedContent Class](#followedcontent-class) |
| [MicrofeedData Class](#microfeeddata-class) | [SocialDataItemType Enum](#socialdataitemtype-enum) | [FollowedContentExceptionCode Enum](#followedcontentexceptioncode-enum) |
| [MicrofeedDataCollection Class](#microfeeddatacollection-class) | [SocialDataOverlay Class](#socialdataoverlay-class) | [FollowedContentPropertyNames Class](#followedcontentpropertynames-class) |
| [MicrofeedDataCollectionPropertyNames Class](#microfeeddatacollectionpropertynames-class) | [SocialDataOverlayType Enum](#socialdataoverlaytype-enum) | [FollowedContentQueryOptions Enum](#followedcontentqueryoptions-enum) |
| [MicrofeedDataLink Class](#microfeeddatalink-class) | [SocialExceptionDetails Class](#socialexceptiondetails-class) | [FollowedItem Class](#followeditem-class) |
| [MicrofeedDataLinkCollection Class](#microfeeddatalinkcollection-class) | [SocialFeed Class](#socialfeed-class) | [FollowedItemData Class](#followeditemdata-class) |
| [MicrofeedDataLinkType Enum](#microfeeddatalinktype-enum) | [SocialFeedAttributes Enum](#socialfeedattributes-enum) | [FollowedItemDataPropertyNames Class](#followeditemdatapropertynames-class) |
| [MicrofeedDataPropertyNames Class](#microfeeddatapropertynames-class) | [SocialFeedManager Class](#socialfeedmanager-class) | [FollowedItemType Enum](#followeditemtype-enum) |
| [MicrofeedDataQuery Class](#microfeeddataquery-class) | [SocialFeedManagerPropertyNames Class](#socialfeedmanagerpropertynames-class) | [FollowedStatus Enum](#followedstatus-enum) |
| [MicrofeedLink Class](#microfeedlink-class) | [SocialFeedOptions Class](#socialfeedoptions-class) | [FollowResult Class](#followresult-class) |
| [MicrofeedLinkAction Class](#microfeedlinkaction-class) | [SocialFeedSortOrder Enum](#socialfeedsortorder-enum) | [FollowResultType Enum](#followresulttype-enum) |
| [MicrofeedLinkActionKind Enum](#microfeedlinkactionkind-enum) | [SocialFeedType Enum](#socialfeedtype-enum) | [HashTag Class](#hashtag-class) |
| [MicrofeedLinkType Enum](#microfeedlinktype-enum) | [SocialFollowingManager Class](#socialfollowingmanager-class) | [HashTagCollection Class](#hashtagcollection-class) |
| [MicrofeedManager Class](#microfeedmanager-class) | [SocialFollowingManagerPropertyNames Class](#socialfollowingmanagerpropertynames-class) | [ObjectTypes Enum](#objecttypes-enum) |
| [MicrofeedManagerPropertyNames Class](#microfeedmanagerpropertynames-class) | [SocialFollowResult Enum](#socialfollowresult-enum) | [PeopleManager Class](#peoplemanager-class) |
| [MicrofeedPost Class](#microfeedpost-class) | [SocialLink Class](#sociallink-class) | [PeopleManagerPropertyNames Class](#peoplemanagerpropertynames-class) |
| [MicrofeedPostAttributes Enum](#microfeedpostattributes-enum) | [SocialPost Class](#socialpost-class) | [PersonalCache Class](#personalcache-class) |
| [MicrofeedPostCollection Class](#microfeedpostcollection-class) | [SocialPostActorInfo Class](#socialpostactorinfo-class) | [PersonalCacheExceptionCode Enum](#personalcacheexceptioncode-enum) |
| [MicrofeedPostDefinition Class](#microfeedpostdefinition-class) | [SocialPostAttributes Enum](#socialpostattributes-enum) | [PersonalCacheItem Class](#personalcacheitem-class) |
| [MicrofeedPostDefinitionManager Class](#microfeedpostdefinitionmanager-class) | [SocialPostCreationData Class](#socialpostcreationdata-class) | [PersonalCachePropertyNames Class](#personalcachepropertynames-class) |
| [MicrofeedPostDefinitionNameCollection Class](#microfeedpostdefinitionnamecollection-class) | [SocialPostDefinitionData Class](#socialpostdefinitiondata-class) | [PersonalSiteCapabilities Enum](#personalsitecapabilities-enum) |
| [MicrofeedPostDefinitionNames Class](#microfeedpostdefinitionnames-class) | [SocialPostDefinitionDataItem Class](#socialpostdefinitiondataitem-class) | [PersonalSiteCreationPriority Enum](#personalsitecreationpriority-enum) |
| [MicrofeedPostOptionCollection Class](#microfeedpostoptioncollection-class) | [SocialPostDefinitionDataItemType Enum](#socialpostdefinitiondataitemtype-enum) | [PersonalSiteInstantiationState Enum](#personalsiteinstantiationstate-enum) |
| [MicrofeedPostOptions Class](#microfeedpostoptions-class) | [SocialPostReference Class](#socialpostreference-class) | [PersonProperties Class](#personproperties-class) |
| [MicrofeedPostSecurityAttributes Enum](#microfeedpostsecurityattributes-enum) | [SocialPostType Enum](#socialposttype-enum) | [PersonPropertiesPropertyNames Class](#personpropertiespropertynames-class) |
| [MicrofeedPublishedFeedType Enum](#microfeedpublishedfeedtype-enum) | [SocialRestActor Class](#socialrestactor-class) | [ProfileImageStore Class](#profileimagestore-class) |
| [MicrofeedRetrievalOptions Class](#microfeedretrievaloptions-class) | [SocialRestActorPropertyNames Class](#socialrestactorpropertynames-class) | [ProfileLoader Class](#profileloader-class) |
| [MicrofeedSortOrder Enum](#microfeedsortorder-enum) | [SocialRestFeed Class](#socialrestfeed-class) | [ScriptTypeFactory Class](#scripttypefactory-class) |
| [MicrofeedStatusCode Enum](#microfeedstatuscode-enum) | [SocialRestFeedManager Class](#socialrestfeedmanager-class) | [SocialDataStoreExceptionCode Enum](#socialdatastoreexceptioncode-enum) |
| [MicrofeedStore Class](#microfeedstore-class) | [SocialRestFeedPropertyNames Class](#socialrestfeedpropertynames-class) | [UserProfile Class](#userprofile-class) |
| [MicrofeedThread Class](#microfeedthread-class) | [SocialRestFollowingManager Class](#socialrestfollowingmanager-class) | [UserProfileObjectPropertyNames Class](#userprofileobjectpropertynames-class) |
| [MicrofeedThreadCollection Class](#microfeedthreadcollection-class) | [SocialRestFollowingManagerPropertyNames Class](#socialrestfollowingmanagerpropertynames-class) | [UserProfilePropertiesForUser Class](#userprofilepropertiesforuser-class) |
| [MicrofeedUserPostCollection Class](#microfeeduserpostcollection-class) | [SocialRestPostCreationData Class](#socialrestpostcreationdata-class) | [UserProfilePropertiesForUserPropertyNames Class](#userprofilepropertiesforuserpropertynames-class) |
| [MicrofeedUserPosts Class](#microfeeduserposts-class) | [SocialRestThread Class](#socialrestthread-class) | [UserProfilePropertyNames Class](#userprofilepropertynames-class) |
| [SocialActor Class](#socialactor-class) | [SocialRestThreadPropertyNames Class](#socialrestthreadpropertynames-class) |   |
| [SocialActorInfo Class](#socialactorinfo-class) | [SocialStatusCode Enum](#socialstatuscode-enum) |   |
# Reputation Class

Namespace: Microsoft.Office.Server.ReputationModel


## Methods

| Name | Returns | Summary |
|---|---|---|
| **SetLike(ClientRuntimeContext context, string listID, int itemID, bool like)** | ClientResult\<int\> |  |
| **SetRating(ClientRuntimeContext context, string listID, int itemID, int rating)** | ClientResult\<double\> |  |
# IdentifierEncoding Enum

Namespace: Microsoft.SharePoint.Client.Microfeed


## Values

| Name | Summary |
|---|---|
| **CacheEncoding** |  |
| **UserEncoding** |  |
# MicroBlogEntity Class

Namespace: Microsoft.SharePoint.Client.Microfeed

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AccountName** | string |  |
| **CanFollow** | bool |  |
| **Description** | string |  |
| **DisplayName** | string |  |
| **Email** | string |  |
| **EntityType** | [MicroBlogEntityType](#microblogentitytype-enum) |  |
| **EntityURI** | string |  |
| **FollowedContentURI** | string |  |
| **Identifier** | string |  |
| **IsFollowedByMe** | bool |  |
| **LatestPost** | string |  |
| **LibraryName** | string |  |
| **LibraryUri** | string |  |
| **PersonalURI** | string |  |
| **PictureURI** | string |  |
| **Status** | [MicrofeedStatusCode](#microfeedstatuscode-enum) |  |
| **Title** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# MicroBlogEntityCollection Class

Namespace: Microsoft.SharePoint.Client.Microfeed

Base class: ClientValueObjectCollection<[MicroBlogEntity](#microblogentity-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **TypeId** | string |  |
| **ChildItemsName** | string |  |
| **Count** | int |  |
| **Item** | [MicroBlogEntity](#microblogentity-class) |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# MicroBlogEntityType Enum

Namespace: Microsoft.SharePoint.Client.Microfeed


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **User** |  |
| **Document** |  |
| **Site** |  |
| **Tag** |  |
# MicroBlogType Enum

Namespace: Microsoft.SharePoint.Client.Microfeed


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **MBEProfile** |  |
| **RootPost** |  |
| **ReplyPost** |  |
| **RefLike** |  |
| **RefMention** |  |
| **RefReply** |  |
| **ActivityEventRootPost** |  |
| **NonRefPosts** |  |
| **RefTag** |  |
| **Reference** |  |
| **RefPosts** |  |
| **TheirRootPosts** |  |
| **TheirAllPosts** |  |
| **MyRootPosts** |  |
| **MyAllPosts** |  |
| **All** |  |
# MicrofeedAttachmentStore Class

Namespace: Microsoft.SharePoint.Client.Microfeed

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
| **MicrofeedAttachmentStore(ClientRuntimeContext context)** |  |
| **MicrofeedAttachmentStore(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeletePreProcessedAttachment(string attachmentUri)** | void |  |
| **GetImage(string imageUrl, string key, string iv)** | ClientResult\<Stream\> |  |
| **PreProcessAttachment(MicrofeedLink link)** | ClientResult\<[MicrofeedLink](#microfeedlink-class)\> |  |
| **PutFile(string originalFileName, Stream fileData)** | ClientArrayResult\<string\> |  |
| **PutImage(Stream imageData)** | ClientArrayResult\<string\> |  |
# MicrofeedContentFormattingOptions Enum

Namespace: Microsoft.SharePoint.Client.Microfeed


## Values

| Name | Summary |
|---|---|
| **ReplaceTemplateVariablesWithPlaceHolders** |  |
| **None** |  |
| **ReplaceTemplateVariablesWithValues** |  |
| **ReplaceTemplateVariablesWithValues_NoHrefs** |  |
# MicrofeedData Class

Namespace: Microsoft.SharePoint.Client.Microfeed

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Created** | DateTime |  |
| **Data** | IDictionary\<string, Object\> |  |
| **DefinitionId** | int |  |
| **ItemType** | [MicroBlogType](#microblogtype-enum) |  |
| **Modified** | DateTime |  |
| **TargetIdentifier** | string |  |
| **Version** | string |  |
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
| **MicrofeedData(ClientRuntimeContext context, ObjectPath objectPath)** |  |
| **MicrofeedData(ClientRuntimeContext context, MicrofeedStore store, IDictionary\<string, Object\> props)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **AddAttachment(string name, byte[] bytes)** | void |  |
| **SystemUpdate()** | void |  |
| **Update()** | void |  |
# MicrofeedDataCollection Class

Namespace: Microsoft.SharePoint.Client.Microfeed

Base class: ClientObjectCollection<[MicrofeedData](#microfeeddata-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **LastItemDeletedDate** | DateTime |  |
| **Item** | [MicrofeedData](#microfeeddata-class) |  |
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
| **MicrofeedDataCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteAll()** | void |  |
# MicrofeedDataCollectionPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Microfeed


## Fields

| Name | Type | Summary |
|---|---|---|
| **LastItemDeletedDate** | string |  |
# MicrofeedDataLink Class

Namespace: Microsoft.SharePoint.Client.Microfeed

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **DataLinkType** | [MicrofeedDataLinkType](#microfeeddatalinktype-enum) |  |
| **DateTimeValue** | DateTime |  |
| **Name** | string |  |
| **PlaceHolderName** | string |  |
| **StringValue** | string |  |
| **UniqueId** | Guid |  |
| **UriValue** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# MicrofeedDataLinkCollection Class

Namespace: Microsoft.SharePoint.Client.Microfeed

Base class: ClientValueObjectCollection<[MicrofeedDataLink](#microfeeddatalink-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **TypeId** | string |  |
| **ChildItemsName** | string |  |
| **Count** | int |  |
| **Item** | [MicrofeedDataLink](#microfeeddatalink-class) |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# MicrofeedDataLinkType Enum

Namespace: Microsoft.SharePoint.Client.Microfeed


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **Uri** |  |
| **String** |  |
| **DocumentLibrary** |  |
| **FollowedContentUri** |  |
| **DateTime** |  |
| **NumericString** |  |
| **Document** |  |
| **Tag** |  |
| **Interest** |  |
| **User** |  |
# MicrofeedDataPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Microfeed


## Fields

| Name | Type | Summary |
|---|---|---|
| **Created** | string |  |
| **Data** | string |  |
| **DefinitionId** | string |  |
| **ItemType** | string |  |
| **Modified** | string |  |
| **TargetIdentifier** | string |  |
| **Version** | string |  |
# MicrofeedDataQuery Class

Namespace: Microsoft.SharePoint.Client.Microfeed

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ItemLimit** | uint |  |
| **Query** | string |  |
| **ViewFields** | string[] |  |
| **ViewFieldsOnly** | bool |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# MicrofeedLink Class

Namespace: Microsoft.SharePoint.Client.Microfeed

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ClickAction** | [MicrofeedLinkAction](#microfeedlinkaction-class) |  |
| **ContentUri** | string |  |
| **Description** | string |  |
| **Height** | uint |  |
| **Href** | string |  |
| **Length** | uint |  |
| **LinkType** | [MicrofeedLinkType](#microfeedlinktype-enum) |  |
| **Name** | string |  |
| **PreviewHeight** | uint |  |
| **PreviewPictureUrl** | string |  |
| **PreviewWidth** | uint |  |
| **Status** | [MicrofeedStatusCode](#microfeedstatuscode-enum) |  |
| **Width** | uint |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# MicrofeedLinkAction Class

Namespace: Microsoft.SharePoint.Client.Microfeed

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ActionUri** | string |  |
| **Height** | uint |  |
| **Kind** | [MicrofeedLinkActionKind](#microfeedlinkactionkind-enum) |  |
| **Width** | uint |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# MicrofeedLinkActionKind Enum

Namespace: Microsoft.SharePoint.Client.Microfeed


## Values

| Name | Summary |
|---|---|
| **Navigate** |  |
| **AdHocAction** |  |
# MicrofeedLinkType Enum

Namespace: Microsoft.SharePoint.Client.Microfeed


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **Image** |  |
| **Webpage** |  |
| **Movie** |  |
| **Audio** |  |
| **CustomAction** |  |
| **Document** |  |
# MicrofeedManager Class

Namespace: Microsoft.SharePoint.Client.Microfeed

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **CurrentUser** | [MicroBlogEntity](#microblogentity-class) |  |
| **IsFeedActivityPublic** | bool |  |
| **StaticThreadLink** | string |  |
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
| **MicrofeedManager(ClientRuntimeContext context)** |  |
| **MicrofeedManager(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **AddUserToPostPeopleList(string postIdentifier, string UserLoginName)** | ClientResult\<[MicrofeedStatusCode](#microfeedstatuscode-enum)\> |  |
| **ClearUnreadMentionsCount()** | ClientResult\<[MicrofeedStatusCode](#microfeedstatuscode-enum)\> |  |
| **DeleteById(string postIdentifier)** | ClientResult\<[MicrofeedThread](#microfeedthread-class)\> |  |
| **DeleteUserFromPostPeopleList(string postIdentifier, string UserLoginName)** | ClientResult\<[MicrofeedStatusCode](#microfeedstatuscode-enum)\> |  |
| **GetMyCategoricalFeed(MicrofeedRetrievalOptions feedOptions)** | ClientResult\<[MicrofeedThreadCollection](#microfeedthreadcollection-class)\> |  |
| **GetMyConsolidatedFeed(MicrofeedRetrievalOptions feedOptions)** | ClientResult\<[MicrofeedThreadCollection](#microfeedthreadcollection-class)\> |  |
| **GetMyPublishedFeed(MicrofeedRetrievalOptions feedOptions, MicrofeedPublishedFeedType typeOfPubFeed, bool ShowPublicView)** | ClientResult\<[MicrofeedThreadCollection](#microfeedthreadcollection-class)\> |  |
| **GetPublishedFeed(string feedOwner, MicrofeedRetrievalOptions feedOptions, MicrofeedPublishedFeedType typeOfPubFeed)** | ClientResult\<[MicrofeedThreadCollection](#microfeedthreadcollection-class)\> |  |
| **GetThread(string postIdentifier)** | ClientResult\<[MicrofeedThread](#microfeedthread-class)\> |  |
| **GetUnreadMentionsCount()** | ClientResult\<int\> |  |
| **Like(string postIdentifier)** | ClientResult\<[MicrofeedThread](#microfeedthread-class)\> |  |
| **LockThreadById(string threadIdentifier)** | ClientResult\<[MicrofeedThread](#microfeedthread-class)\> |  |
| **Post(MicrofeedPostOptions postOptions)** | ClientResult\<[MicrofeedThread](#microfeedthread-class)\> |  |
| **PostReply(string postIdentifier, MicrofeedPostOptions postReplyOptions)** | ClientResult\<[MicrofeedThread](#microfeedthread-class)\> |  |
| **RepopulateLMT(DateTime timeStamp, string secureHash)** | ClientResult\<[MicrofeedStatusCode](#microfeedstatuscode-enum)\> |  |
| **UnLike(string postIdentifier)** | ClientResult\<[MicrofeedThread](#microfeedthread-class)\> |  |
| **UnLockThreadById(string threadIdentifier)** | ClientResult\<[MicrofeedThread](#microfeedthread-class)\> |  |
| **UnsubscribeFromEMail(string postIdentifier)** | void |  |
# MicrofeedManagerPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Microfeed


## Fields

| Name | Type | Summary |
|---|---|---|
| **CurrentUser** | string |  |
| **IsFeedActivityPublic** | string |  |
| **StaticThreadLink** | string |  |
# MicrofeedPost Class

Namespace: Microsoft.SharePoint.Client.Microfeed

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AuthorIndex** | int |  |
| **BreadCrumb** | string |  |
| **CanDelete** | bool |  |
| **CanFollowUp** | bool |  |
| **CanHaveAttachments** | bool |  |
| **CanLike** | bool |  |
| **CanLock** | bool |  |
| **CanReply** | bool |  |
| **Content** | string |  |
| **Created** | DateTime |  |
| **Footer** | string |  |
| **ID** | string |  |
| **ILikeIt** | bool |  |
| **LikersList** | IList\<int\> |  |
| **Locked** | bool |  |
| **MediaLink** | [MicrofeedLink](#microfeedlink-class) |  |
| **MicroBlogType** | [MicroBlogType](#microblogtype-enum) |  |
| **Modified** | DateTime |  |
| **PeopleCount** | int |  |
| **PostImageUri** | string |  |
| **PostSource** | string |  |
| **PostSourceUri** | string |  |
| **ReferenceID** | string |  |
| **RenderPostAuthorImage** | bool |  |
| **ReplyCount** | int |  |
| **SmallImageSizePreferred** | bool |  |
| **Title** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# MicrofeedPostAttributes Enum

Namespace: Microsoft.SharePoint.Client.Microfeed


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **IsPrivate** |  |
| **IsDefault** |  |
| **IsEnabled** |  |
| **IsUserPost** |  |
| **CanReply** |  |
| **CanDelete** |  |
| **CanLike** |  |
| **EnablePeopleList** |  |
| **CanLock** |  |
| **CanHaveAttachments** |  |
| **RenderPostAuthorImage** |  |
| **SmallImageSizePreferred** |  |
| **PersistToPublishedFeed** |  |
| **PersistToCache** |  |
| **IsNotification** |  |
| **CanFollowUp** |  |
# MicrofeedPostCollection Class

Namespace: Microsoft.SharePoint.Client.Microfeed

Base class: ClientValueObjectCollection<[MicrofeedPost](#microfeedpost-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **TypeId** | string |  |
| **ChildItemsName** | string |  |
| **Count** | int |  |
| **Item** | [MicrofeedPost](#microfeedpost-class) |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# MicrofeedPostDefinition Class

Namespace: Microsoft.SharePoint.Client.Microfeed

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **CanDelete** | bool |  |
| **CanFollowUp** | bool |  |
| **CanHaveAttachments** | bool |  |
| **CanLike** | bool |  |
| **CanLock** | bool |  |
| **CanReply** | bool |  |
| **CreationTime** | DateTime |  |
| **DefinitionId** | long |  |
| **DefinitionName** | string |  |
| **DefinitionVersion** | int |  |
| **EnablePeopleList** | bool |  |
| **IsDefault** | bool |  |
| **IsEnabled** | bool |  |
| **IsNotification** | bool |  |
| **IsPrivate** | bool |  |
| **IsUserPost** | bool |  |
| **LastUpdateTime** | DateTime |  |
| **PartitionId** | Guid |  |
| **PersistToCache** | bool |  |
| **PersistToPrivateFolder** | bool |  |
| **PersistToPublishedFeed** | bool |  |
| **ReferenceLikePostName** | string |  |
| **ReferenceMentionPostName** | string |  |
| **ReferenceReplyPostName** | string |  |
| **RenderPostAuthorImage** | bool |  |
| **ResourceFileName** | string |  |
| **SecurityTrimContentUrl** | bool |  |
| **SmallImageSizePreferred** | bool |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# MicrofeedPostDefinitionManager Class

Namespace: Microsoft.SharePoint.Client.Microfeed

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
| **MicrofeedPostDefinitionManager(ClientRuntimeContext context)** |  |
| **MicrofeedPostDefinitionManager(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteMicrofeedPostDefinition(MicrofeedPostDefinition postDefinition)** | ClientResult\<bool\> |  |
| **GetMicrofeedPostDefinition(string definitionName)** | ClientResult\<[MicrofeedPostDefinition](#microfeedpostdefinition-class)\> |  |
| **GetMicrofeedPostDefinitions()** | IList\<[MicrofeedPostDefinition](#microfeedpostdefinition-class)\> |  |
| **NewMicrofeedPostDefinition(string definitionName)** | ClientResult\<[MicrofeedPostDefinition](#microfeedpostdefinition-class)\> |  |
| **UpdateMicrofeedPostDefinition(MicrofeedPostDefinition postDefinition)** | ClientResult\<[MicrofeedPostDefinition](#microfeedpostdefinition-class)\> |  |
# MicrofeedPostDefinitionNameCollection Class

Namespace: Microsoft.SharePoint.Client.Microfeed

Base class: ClientValueObjectCollection<string>


## Properties

| Name | Type | Summary |
|---|---|---|
| **TypeId** | string |  |
| **ChildItemsName** | string |  |
| **Count** | int |  |
| **Item** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# MicrofeedPostDefinitionNames Class

Namespace: Microsoft.SharePoint.Client.Microfeed

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# MicrofeedPostOptionCollection Class

Namespace: Microsoft.SharePoint.Client.Microfeed

Base class: ClientObjectCollection<[MicrofeedPostOptions](#microfeedpostoptions-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [MicrofeedPostOptions](#microfeedpostoptions-class) |  |
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
| **MicrofeedPostOptionCollection(ClientRuntimeContext context)** |  |
| **MicrofeedPostOptionCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# MicrofeedPostOptions Class

Namespace: Microsoft.SharePoint.Client.Microfeed

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Content** | string |  |
| **ContentFormattingOption** | [MicrofeedContentFormattingOptions](#microfeedcontentformattingoptions-enum) |  |
| **DataLinks** | [MicrofeedDataLinkCollection](#microfeeddatalinkcollection-class) |  |
| **DefinitionName** | string |  |
| **MediaLink** | [MicrofeedLink](#microfeedlink-class) |  |
| **PeopleList** | IList\<string\> |  |
| **PostSource** | string |  |
| **PostSourceUri** | string |  |
| **RefThread_ReferenceID** | string |  |
| **RefThread_RefReply** | string |  |
| **RefThread_RefRoot** | string |  |
| **TargetActor** | string |  |
| **UpdateStatusText** | bool |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# MicrofeedPostSecurityAttributes Enum

Namespace: Microsoft.SharePoint.Client.Microfeed


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **PersistToPrivateFolder** |  |
| **SecurityTrimContentUrl** |  |
# MicrofeedPublishedFeedType Enum

Namespace: Microsoft.SharePoint.Client.Microfeed


## Values

| Name | Summary |
|---|---|
| **Recent** |  |
| **Full** |  |
# MicrofeedRetrievalOptions Class

Namespace: Microsoft.SharePoint.Client.Microfeed

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ContentFormattingOption** | [MicrofeedContentFormattingOptions](#microfeedcontentformattingoptions-enum) |  |
| **ContentOnly** | bool |  |
| **DropAllSecurityTrimmablePosts** | bool |  |
| **GatherUnreadMentionCountForUser** | bool |  |
| **IncludedTypes** | [MicroBlogType](#microblogtype-enum) |  |
| **NewerThan** | DateTime |  |
| **OlderThan** | DateTime |  |
| **PostDefinitionFilter** | IList\<string\> |  |
| **ResultSortOrder** | [MicrofeedSortOrder](#microfeedsortorder-enum) |  |
| **ThreadCount** | int |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# MicrofeedSortOrder Enum

Namespace: Microsoft.SharePoint.Client.Microfeed


## Values

| Name | Summary |
|---|---|
| **ModifiedTime** |  |
| **CreatedTime** |  |
# MicrofeedStatusCode Enum

Namespace: Microsoft.SharePoint.Client.Microfeed


## Values

| Name | Summary |
|---|---|
| **Success** |  |
| **ServerError** |  |
| **InsufficientPermissions** |  |
| **InterimPlaceholderEntity** |  |
| **InvalidItemId** |  |
| **InvalidThreadId** |  |
| **InvalidUriInPostOptions** |  |
| **InvalidMediaLinkName** |  |
| **InvalidMediaLinkURI** |  |
| **InvalidMediaLinkSnippetURI** |  |
| **MediaLinkAddFailure** |  |
| **NoServiceContext** |  |
| **Invalid_MicroBlogType_Requested** |  |
| **Only_One_ContentUri_Allowed_Per_Post** |  |
| **Invalid_Content_Null_Or_Empty** |  |
| **Invalid_Content_Length_Greater_Than_512_Chars** |  |
| **Invalid_KeyWord_Found_In_Content** |  |
| **Invalid_MediaLinks_SerializedString** |  |
| **Invalid_MicroBlogPost_SerializedString** |  |
| **MicroBlogEntity_Error_PublishedFeedList_NotFound** |  |
| **MicroBlogEntity_Invalid_GetPublishedFeed** |  |
| **MicroBlogPost_Error_SavingToPublishedFeed** |  |
| **MicroBlogPost_Error_PublishingToCache** |  |
| **MicroBlogPost_Error_DeletingFromCache** |  |
| **MicroBLogList_Error_FetchingList** |  |
| **MicroBlogList_Error_ExecutingQuery** |  |
| **MicroBlogList_Error_FetchingItem** |  |
| **MicroBlogList_Error_AddingItem** |  |
| **MicroBlogList_Error_Updating_Item** |  |
| **MicroBlogList_Error_FetchMBProfileItem** |  |
| **MicroBlogList_Error_AccessingProperty** |  |
| **InvalidRequest** |  |
| **InvalidLikeRequest** |  |
| **InvalidLockRequest** |  |
| **InvalidRootPost** |  |
| **InvalidReplyRequest** |  |
| **InvalidReplyRequest_MaxRepliesPerRootPost_LimitReached** |  |
| **InvalidLikeRequest_AlreadyMarkedAsLiked** |  |
| **InvalidUnLikeRequest_AlreadyMarkedAsUnLike** |  |
| **InvalidEMailSubscriptionRequest_AlreadyUnsubscribed** |  |
| **InvalidEMailSubscriptionRequest_AlreadySubscribed** |  |
| **InvalidEMailSubscriptionRequest_NotThread** |  |
| **InvalidLockRequest_AlreadyMarkedAsLocked** |  |
| **InvalidUnLockRequest_AlreadyMarkedAsUnLocked** |  |
| **InvalidLockRequest_LockingNonRootPost** |  |
| **ServerErrorCanReplyIsFalse** |  |
| **ServerErrorFeatureDisabled** |  |
| **ServerErrorSiteNotFound** |  |
| **ServerErrorMicroBlogListNotFound** |  |
| **ServerErrorRootPostNotFound** |  |
| **ServerErrorPublishedFeedListNotFound** |  |
| **ServerErrorPublishedFeedListItemNotFound** |  |
| **ServerErrorSavingListItemField** |  |
| **ServerErrorInvalidFeedRequest** |  |
| **ServerErrorFetchingPublishedFeed** |  |
| **ServerErrorFetchingConsolidatedFeed** |  |
| **ServerErrorFetchingCategoricalFeed** |  |
| **ServerErrorFetchingActivityFeed** |  |
| **ServerErrorSecurityTrimmer** |  |
| **ServerErrorDuplicateMessageId** |  |
| **ServerErrorOpeningPersonalSite** |  |
| **ServerError_Initialization** |  |
| **ServerErrorInvalidContentURI** |  |
| **ServerErrorInvalidFollowedItemType** |  |
| **ServerErrorPublishingToList** |  |
| **ServerErrorPublishingToCache** |  |
| **MicroBlogDeletionError_NotOwner** |  |
| **ServerCacheError_CacheNotFound** |  |
| **ServerCacheError_NotAuthorized** |  |
| **ServerCacheError_ThreadNotFound** |  |
| **IncorrectTenantPartition** |  |
| **InvalidUserAccount** |  |
| **InvalidKeywordTag** |  |
| **Taxonomy_TagNotAvailabelForTagging** |  |
| **Taxonomy_TermStoreNotFound** |  |
| **InvalidEntityIdentifier** |  |
| **UnexpectedEntityType** |  |
| **WarningPersonalSiteNotFoundCannotCreate** |  |
| **WarningPersonalSiteNotFoundCanCreate** |  |
| **WarningPersonalSiteNotFoundCanCreateNoPermissions** |  |
| **WarningPersonalSiteNotFoundCanCreateError** |  |
| **ErrorPersonalSiteNotFound** |  |
| **GuidStringConversionError** |  |
| **ServerErrorUnableToFetchUserProfile** |  |
| **SP_MFPD_DataBase_Exception** |  |
| **SP_MFPD_DataBase_DefinitionNotFound** |  |
| **SP_MFPD_Invalid_Operation** |  |
| **SP_MFPD_Invalid_Value** |  |
| **SP_MFPD_Partition_Mismatch** |  |
| **SP_MFPD_Definition_Disabled** |  |
| **Invalid_MicroBlogPost_DefinitionNameIsRequired** |  |
| **Invalid_MicroBlogPost_InvalidDefinitionName** |  |
| **InvalidRequest_PostIsLocked** |  |
| **ServerErrorUnableToAttachPicture** |  |
| **InvalidFeedCacheEntity_UserMissingURI** |  |
| **InvalidFeedCacheEntity_DocMissingURI** |  |
| **RestrictedListStorageCompromised** |  |
| **InvalidPostTarget** |  |
| **WarningSiteStorageQuotaExceeded** |  |
| **ServerErrorCannotAccessDatabase** |  |
# MicrofeedStore Class

Namespace: Microsoft.SharePoint.Client.Microfeed

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
| **MicrofeedStore(ClientRuntimeContext context)** |  |
| **MicrofeedStore(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **AddData(string name, byte[] data)** | void |  |
| **AddDataAsStream(string name, Stream data)** | void |  |
| **ExecutePendingOperations()** | void |  |
| **GetItem(string storeIdentifier)** | [MicrofeedData](#microfeeddata-class) |  |
| **GetSocialFeedManagerForUser(ClientRuntimeContext context, string accountName)** | [SocialFeedManager](#socialfeedmanager-class) |  |
| **GetSocialProperties(string accountName)** | ClientResult\<string\> |  |
| **IncrementUnreadAtMentionCount(string accountName)** | void |  |
| **NewItem(string storeIdentifier)** | [MicrofeedData](#microfeeddata-class) |  |
| **Query(string storeIdentifier, MicrofeedDataQuery query)** | [MicrofeedDataCollection](#microfeeddatacollection-class) |  |
| **SetPostLikeStatus(string accountName, string postId, bool like)** | void |  |
# MicrofeedThread Class

Namespace: Microsoft.SharePoint.Client.Microfeed

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **CanFollowUp** | bool |  |
| **CanHaveAttachments** | bool |  |
| **CanLike** | bool |  |
| **CanReply** | bool |  |
| **DataLinks** | IList\<[MicrofeedDataLink](#microfeeddatalink-class)\> |  |
| **DefinitionId** | long |  |
| **DefinitionName** | string |  |
| **Identifier** | string |  |
| **Locked** | bool |  |
| **MicrofeedEntities** | IList\<[MicroBlogEntity](#microblogentity-class)\> |  |
| **OwnerIndex** | int |  |
| **RefReply** | [MicrofeedPost](#microfeedpost-class) |  |
| **RefRoot** | [MicrofeedPost](#microfeedpost-class) |  |
| **RenderPostAuthorImage** | bool |  |
| **Replies** | [MicrofeedPostCollection](#microfeedpostcollection-class) |  |
| **ReplyCount** | int |  |
| **RootPost** | [MicrofeedPost](#microfeedpost-class) |  |
| **SmallImageSizePreferred** | bool |  |
| **Status** | [MicrofeedStatusCode](#microfeedstatuscode-enum) |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# MicrofeedThreadCollection Class

Namespace: Microsoft.SharePoint.Client.Microfeed

Base class: ClientValueObjectCollection<[MicrofeedThread](#microfeedthread-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **CurrentUserUnreadMentionCount** | int |  |
| **NewestProcessed** | DateTime |  |
| **OldestProcessed** | DateTime |  |
| **TypeId** | string |  |
| **ChildItemsName** | string |  |
| **Count** | int |  |
| **Item** | [MicrofeedThread](#microfeedthread-class) |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# MicrofeedUserPostCollection Class

Namespace: Microsoft.SharePoint.Client.Microfeed

Base class: ClientValueObjectCollection<[MicrofeedUserPosts](#microfeeduserposts-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **TypeId** | string |  |
| **ChildItemsName** | string |  |
| **Count** | int |  |
| **Item** | [MicrofeedUserPosts](#microfeeduserposts-class) |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# MicrofeedUserPosts Class

Namespace: Microsoft.SharePoint.Client.Microfeed

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AccountName** | string |  |
| **PostOptions** | [MicrofeedPostOptionCollection](#microfeedpostoptioncollection-class) |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SocialActor Class

Namespace: Microsoft.SharePoint.Client.Social

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AccountName** | string |  |
| **ActorType** | [SocialActorType](#socialactortype-enum) |  |
| **CanFollow** | bool |  |
| **ContentUri** | string |  |
| **EmailAddress** | string |  |
| **FollowedContentUri** | string |  |
| **GroupId** | Guid |  |
| **Id** | string |  |
| **ImageUri** | string |  |
| **IsFollowed** | bool |  |
| **LibraryUri** | string |  |
| **Name** | string |  |
| **PersonalSiteUri** | string |  |
| **Status** | [SocialStatusCode](#socialstatuscode-enum) |  |
| **StatusText** | string |  |
| **TagGuid** | Guid |  |
| **Title** | string |  |
| **Uri** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SocialActorInfo Class

Namespace: Microsoft.SharePoint.Client.Social

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AccountName** | string |  |
| **ActorType** | [SocialActorType](#socialactortype-enum) |  |
| **ContentUri** | string |  |
| **Id** | string |  |
| **TagGuid** | Guid |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SocialActorType Enum

Namespace: Microsoft.SharePoint.Client.Social


## Values

| Name | Summary |
|---|---|
| **User** |  |
| **Document** |  |
| **Site** |  |
| **Tag** |  |
# SocialActorTypes Enum

Namespace: Microsoft.SharePoint.Client.Social


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **Users** |  |
| **Documents** |  |
| **Sites** |  |
| **Tags** |  |
| **All** |  |
| **ExcludeContentWithoutFeeds** |  |
| **IncludeGroupsSites** |  |
| **WithinLast24Hours** |  |
# SocialAnnouncementManager Class

Namespace: Microsoft.SharePoint.Client.Social


## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetCurrentAnnouncements(ClientRuntimeContext context, string url)** | IList\<TileData\> |  |
# SocialAttachment Class

Namespace: Microsoft.SharePoint.Client.Social

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AttachmentKind** | [SocialAttachmentKind](#socialattachmentkind-enum) |  |
| **ClickAction** | [SocialAttachmentAction](#socialattachmentaction-class) |  |
| **ContentUri** | string |  |
| **Description** | string |  |
| **Height** | uint |  |
| **Length** | uint |  |
| **Name** | string |  |
| **PreviewHeight** | uint |  |
| **PreviewUri** | string |  |
| **PreviewWidth** | uint |  |
| **Uri** | string |  |
| **Width** | uint |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SocialAttachmentAction Class

Namespace: Microsoft.SharePoint.Client.Social

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ActionKind** | [SocialAttachmentActionKind](#socialattachmentactionkind-enum) |  |
| **ActionUri** | string |  |
| **Height** | uint |  |
| **Width** | uint |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SocialAttachmentActionKind Enum

Namespace: Microsoft.SharePoint.Client.Social


## Values

| Name | Summary |
|---|---|
| **Navigate** |  |
| **AdHocAction** |  |
# SocialAttachmentKind Enum

Namespace: Microsoft.SharePoint.Client.Social


## Values

| Name | Summary |
|---|---|
| **Image** |  |
| **Video** |  |
| **Document** |  |
# SocialDataItem Class

Namespace: Microsoft.SharePoint.Client.Social

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AccountName** | string |  |
| **ItemType** | [SocialDataItemType](#socialdataitemtype-enum) |  |
| **TagGuid** | Guid |  |
| **Text** | string |  |
| **Uri** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SocialDataItemType Enum

Namespace: Microsoft.SharePoint.Client.Social


## Values

| Name | Summary |
|---|---|
| **User** |  |
| **Document** |  |
| **Site** |  |
| **Tag** |  |
| **Link** |  |
# SocialDataOverlay Class

Namespace: Microsoft.SharePoint.Client.Social

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ActorIndexes** | int[] |  |
| **Index** | int |  |
| **Length** | int |  |
| **LinkUri** | string |  |
| **OverlayType** | [SocialDataOverlayType](#socialdataoverlaytype-enum) |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SocialDataOverlayType Enum

Namespace: Microsoft.SharePoint.Client.Social


## Values

| Name | Summary |
|---|---|
| **Link** |  |
| **Actors** |  |
# SocialExceptionDetails Class

Namespace: Microsoft.SharePoint.Client.Social

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **InternalErrorCode** | int |  |
| **InternalMessage** | string |  |
| **InternalStackTrace** | string |  |
| **InternalTypeName** | string |  |
| **Status** | [SocialStatusCode](#socialstatuscode-enum) |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SocialFeed Class

Namespace: Microsoft.SharePoint.Client.Social

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Attributes** | [SocialFeedAttributes](#socialfeedattributes-enum) |  |
| **NewestProcessed** | DateTime |  |
| **OldestProcessed** | DateTime |  |
| **Threads** | [SocialThread](#socialthread-class)[] |  |
| **UnreadMentionCount** | int |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SocialFeedAttributes Enum

Namespace: Microsoft.SharePoint.Client.Social


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **MoreThreadsAvailable** |  |
| **ValidTimeRange** |  |
| **MovedToYammer** |  |
# SocialFeedManager Class

Namespace: Microsoft.SharePoint.Client.Social

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Owner** | [SocialActor](#socialactor-class) |  |
| **PersonalSitePortalUri** | string |  |
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
| **SocialFeedManager(ClientRuntimeContext context)** |  |
| **SocialFeedManager(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **CreateFileAttachment(string name, string description, Stream fileData)** | ClientResult\<[SocialAttachment](#socialattachment-class)\> |  |
| **CreateImageAttachment(string name, string description, Stream imageData)** | ClientResult\<[SocialAttachment](#socialattachment-class)\> |  |
| **CreatePost(string targetId, SocialPostCreationData creationData)** | ClientResult\<[SocialThread](#socialthread-class)\> |  |
| **DeletePost(string postId)** | ClientResult\<[SocialThread](#socialthread-class)\> |  |
| **GetAllLikers(string postId)** | ClientResult\<[SocialActor](#socialactor-class)[]\> |  |
| **GetFeed(SocialFeedType type, SocialFeedOptions options)** | ClientResult\<[SocialFeed](#socialfeed-class)\> |  |
| **GetFeedFor(string actorId, SocialFeedOptions options)** | ClientResult\<[SocialFeed](#socialfeed-class)\> |  |
| **GetFullThread(string threadId)** | ClientResult\<[SocialThread](#socialthread-class)\> |  |
| **GetMentions(bool clearUnreadMentions, SocialFeedOptions options)** | ClientResult\<[SocialFeed](#socialfeed-class)\> |  |
| **GetPreview(string itemUrl)** | ClientResult\<[SocialAttachment](#socialattachment-class)\> |  |
| **GetPreviewImage(string url, string key, string iv)** | ClientResult\<Stream\> |  |
| **GetUnreadMentionCount()** | ClientResult\<int\> |  |
| **LikePost(string postId)** | ClientResult\<[SocialThread](#socialthread-class)\> |  |
| **LockThread(string threadId)** | ClientResult\<[SocialThread](#socialthread-class)\> |  |
| **SuppressThreadNotifications(string threadId)** | void |  |
| **UnlikePost(string postId)** | ClientResult\<[SocialThread](#socialthread-class)\> |  |
| **UnlockThread(string threadId)** | ClientResult\<[SocialThread](#socialthread-class)\> |  |
# SocialFeedManagerPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Social


## Fields

| Name | Type | Summary |
|---|---|---|
| **Owner** | string |  |
| **PersonalSitePortalUri** | string |  |
# SocialFeedOptions Class

Namespace: Microsoft.SharePoint.Client.Social

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **MaxThreadCount** | int |  |
| **NewerThan** | DateTime |  |
| **OlderThan** | DateTime |  |
| **SortOrder** | [SocialFeedSortOrder](#socialfeedsortorder-enum) |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SocialFeedSortOrder Enum

Namespace: Microsoft.SharePoint.Client.Social


## Values

| Name | Summary |
|---|---|
| **ByModifiedTime** |  |
| **ByCreatedTime** |  |
# SocialFeedType Enum

Namespace: Microsoft.SharePoint.Client.Social


## Values

| Name | Summary |
|---|---|
| **Personal** |  |
| **News** |  |
| **Timeline** |  |
| **Likes** |  |
| **Everyone** |  |
# SocialFollowingManager Class

Namespace: Microsoft.SharePoint.Client.Social

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **FollowedDocumentsUri** | string |  |
| **FollowedSitesUri** | string |  |
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
| **SocialFollowingManager(ClientRuntimeContext context)** |  |
| **SocialFollowingManager(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Follow(SocialActorInfo actor)** | ClientResult\<[SocialFollowResult](#socialfollowresult-enum)\> |  |
| **GetFollowed(SocialActorTypes types)** | ClientResult\<[SocialActor](#socialactor-class)[]\> |  |
| **GetFollowedCount(SocialActorTypes types)** | ClientResult\<int\> |  |
| **GetFollowers()** | ClientResult\<[SocialActor](#socialactor-class)[]\> |  |
| **GetSuggestions()** | ClientResult\<[SocialActor](#socialactor-class)[]\> |  |
| **IsFollowed(SocialActorInfo actor)** | ClientResult\<bool\> |  |
| **MergeFollowedSites(string followedSites)** | ClientResult\<string\> |  |
| **StopFollowing(SocialActorInfo actor)** | ClientResult\<bool\> |  |
# SocialFollowingManagerPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Social


## Fields

| Name | Type | Summary |
|---|---|---|
| **FollowedDocumentsUri** | string |  |
| **FollowedSitesUri** | string |  |
# SocialFollowResult Enum

Namespace: Microsoft.SharePoint.Client.Social


## Values

| Name | Summary |
|---|---|
| **OK** |  |
| **AlreadyFollowing** |  |
| **LimitReached** |  |
| **InternalError** |  |
| **ExpectedFailure** |  |
# SocialLink Class

Namespace: Microsoft.SharePoint.Client.Social

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Text** | string |  |
| **Uri** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SocialPost Class

Namespace: Microsoft.SharePoint.Client.Social

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Attachment** | [SocialAttachment](#socialattachment-class) |  |
| **Attributes** | [SocialPostAttributes](#socialpostattributes-enum) |  |
| **AuthorIndex** | int |  |
| **CreatedTime** | DateTime |  |
| **Id** | string |  |
| **LikerInfo** | [SocialPostActorInfo](#socialpostactorinfo-class) |  |
| **ModifiedTime** | DateTime |  |
| **Overlays** | [SocialDataOverlay](#socialdataoverlay-class)[] |  |
| **PostType** | [SocialPostType](#socialposttype-enum) |  |
| **PreferredImageUri** | string |  |
| **Source** | [SocialLink](#sociallink-class) |  |
| **Text** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SocialPostActorInfo Class

Namespace: Microsoft.SharePoint.Client.Social

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **IncludesCurrentUser** | bool |  |
| **Indexes** | int[] |  |
| **TotalCount** | int |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SocialPostAttributes Enum

Namespace: Microsoft.SharePoint.Client.Social


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **CanLike** |  |
| **CanDelete** |  |
| **UseAuthorImage** |  |
| **UseSmallImage** |  |
| **CanFollowUp** |  |
# SocialPostCreationData Class

Namespace: Microsoft.SharePoint.Client.Social

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Attachment** | [SocialAttachment](#socialattachment-class) |  |
| **ContentItems** | [SocialDataItem](#socialdataitem-class)[] |  |
| **ContentText** | string |  |
| **DefinitionData** | [SocialPostDefinitionData](#socialpostdefinitiondata-class) |  |
| **SecurityUris** | string[] |  |
| **Source** | [SocialLink](#sociallink-class) |  |
| **UpdateStatusText** | bool |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SocialPostDefinitionData Class

Namespace: Microsoft.SharePoint.Client.Social

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Items** | [SocialPostDefinitionDataItem](#socialpostdefinitiondataitem-class)[] |  |
| **Name** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SocialPostDefinitionDataItem Class

Namespace: Microsoft.SharePoint.Client.Social

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AccountName** | string |  |
| **ItemType** | [SocialPostDefinitionDataItemType](#socialpostdefinitiondataitemtype-enum) |  |
| **PlaceholderName** | string |  |
| **TagGuid** | Guid |  |
| **Text** | string |  |
| **Uri** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SocialPostDefinitionDataItemType Enum

Namespace: Microsoft.SharePoint.Client.Social


## Values

| Name | Summary |
|---|---|
| **Text** |  |
| **User** |  |
| **Document** |  |
| **Site** |  |
| **Tag** |  |
| **Link** |  |
# SocialPostReference Class

Namespace: Microsoft.SharePoint.Client.Social

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Digest** | [SocialThread](#socialthread-class) |  |
| **Post** | [SocialPost](#socialpost-class) |  |
| **ThreadId** | string |  |
| **ThreadOwnerIndex** | int |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SocialPostType Enum

Namespace: Microsoft.SharePoint.Client.Social


## Values

| Name | Summary |
|---|---|
| **Root** |  |
| **Reply** |  |
# SocialRestActor Class

Namespace: Microsoft.SharePoint.Client.Social

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **FollowableItem** | string |  |
| **FollowableItemActor** | [SocialActor](#socialactor-class) |  |
| **Me** | [SocialActor](#socialactor-class) |  |
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
| **SocialRestActor(ClientRuntimeContext context)** |  |
| **SocialRestActor(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# SocialRestActorPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Social


## Fields

| Name | Type | Summary |
|---|---|---|
| **FollowableItem** | string |  |
| **FollowableItemActor** | string |  |
| **Me** | string |  |
# SocialRestFeed Class

Namespace: Microsoft.SharePoint.Client.Social

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **SocialFeed** | [SocialFeed](#socialfeed-class) |  |
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
| **SocialRestFeed(ClientRuntimeContext context)** |  |
| **SocialRestFeed(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# SocialRestFeedManager Class

Namespace: Microsoft.SharePoint.Client.Social

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
| **SocialRestFeedManager(ClientRuntimeContext context)** |  |
| **SocialRestFeedManager(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# SocialRestFeedPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Social


## Fields

| Name | Type | Summary |
|---|---|---|
| **SocialFeed** | string |  |
# SocialRestFollowingManager Class

Namespace: Microsoft.SharePoint.Client.Social

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **FollowedDocumentsUri** | string |  |
| **FollowedSitesUri** | string |  |
| **MyFollowedDocumentsUri** | string |  |
| **MyFollowedSitesUri** | string |  |
| **SocialActor** | [SocialActor](#socialactor-class) |  |
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
| **SocialRestFollowingManager(ClientRuntimeContext context)** |  |
| **SocialRestFollowingManager(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# SocialRestFollowingManagerPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Social


## Fields

| Name | Type | Summary |
|---|---|---|
| **FollowedDocumentsUri** | string |  |
| **FollowedSitesUri** | string |  |
| **MyFollowedDocumentsUri** | string |  |
| **MyFollowedSitesUri** | string |  |
| **SocialActor** | string |  |
# SocialRestPostCreationData Class

Namespace: Microsoft.SharePoint.Client.Social

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ID** | string |  |
| **creationData** | [SocialPostCreationData](#socialpostcreationdata-class) |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SocialRestThread Class

Namespace: Microsoft.SharePoint.Client.Social

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ID** | string |  |
| **SocialThread** | [SocialThread](#socialthread-class) |  |
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
| **SocialRestThread(ClientRuntimeContext context)** |  |
| **SocialRestThread(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# SocialRestThreadPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Social


## Fields

| Name | Type | Summary |
|---|---|---|
| **ID** | string |  |
| **SocialThread** | string |  |
# SocialStatusCode Enum

Namespace: Microsoft.SharePoint.Client.Social


## Values

| Name | Summary |
|---|---|
| **OK** |  |
| **InvalidRequest** |  |
| **AccessDenied** |  |
| **ItemNotFound** |  |
| **InvalidOperation** |  |
| **ItemNotModified** |  |
| **InternalError** |  |
| **CacheReadError** |  |
| **CacheUpdateError** |  |
| **PersonalSiteNotFound** |  |
| **FailedToCreatePersonalSite** |  |
| **NotAuthorizedToCreatePersonalSite** |  |
| **CannotCreatePersonalSite** |  |
| **LimitReached** |  |
| **AttachmentError** |  |
| **PartialData** |  |
| **FeatureDisabled** |  |
| **StorageQuotaExceeded** |  |
| **DatabaseError** |  |
# SocialThread Class

Namespace: Microsoft.SharePoint.Client.Social

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Actors** | [SocialActor](#socialactor-class)[] |  |
| **Attributes** | [SocialThreadAttributes](#socialthreadattributes-enum) |  |
| **Id** | string |  |
| **OwnerIndex** | int |  |
| **Permalink** | string |  |
| **PostReference** | [SocialPostReference](#socialpostreference-class) |  |
| **Replies** | [SocialPost](#socialpost-class)[] |  |
| **RootPost** | [SocialPost](#socialpost-class) |  |
| **Status** | [SocialStatusCode](#socialstatuscode-enum) |  |
| **ThreadType** | [SocialThreadType](#socialthreadtype-enum) |  |
| **TotalReplyCount** | int |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SocialThreadAttributes Enum

Namespace: Microsoft.SharePoint.Client.Social


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **IsDigest** |  |
| **CanReply** |  |
| **CanLock** |  |
| **IsLocked** |  |
| **ReplyLimitReached** |  |
# SocialThreadType Enum

Namespace: Microsoft.SharePoint.Client.Social


## Values

| Name | Summary |
|---|---|
| **Normal** |  |
| **LikeReference** |  |
| **ReplyReference** |  |
| **MentionReference** |  |
| **TagReference** |  |
# ChangeTypes Enum

Namespace: Microsoft.SharePoint.Client.UserProfiles


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **Add** |  |
| **Modify** |  |
| **Remove** |  |
| **Metadata** |  |
| **All** |  |
# CrossGeoSync Class

Namespace: Microsoft.SharePoint.Client.UserProfiles

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
| **CrossGeoSync(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# CrossGeoSyncUserDataBatch Class

Namespace: Microsoft.SharePoint.Client.UserProfiles

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **LastEventId** | long |  |
| **LastRecordId** | long |  |
| **Properties** | IList\<[CrossGeoSyncUserProperty](#crossgeosyncuserproperty-class)\> |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# CrossGeoSyncUserProperty Class

Namespace: Microsoft.SharePoint.Client.UserProfiles

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **DsGuid** | Guid |  |
| **IsMultivalue** | bool |  |
| **Privacy** | int |  |
| **PropertyId** | long |  |
| **PropertyVal** | string |  |
| **SecondaryVal** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# FollowedContent Class

Namespace: Microsoft.SharePoint.Client.UserProfiles

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **FollowedDocumentsUrl** | string |  |
| **FollowedSitesUrl** | string |  |
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
| **FollowedContent(ClientRuntimeContext context)** |  |
| **FollowedContent(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **FindAndUpdateFollowedGroup(Guid groupId)** | ClientResult\<[FollowedItem](#followeditem-class)\> |  |
| **FindAndUpdateFollowedItem(string url)** | ClientResult\<[FollowedItem](#followeditem-class)\> |  |
| **Follow(string url, FollowedItemData data)** | ClientResult\<[FollowResult](#followresult-class)\> |  |
| **FollowItem(FollowedItem item)** | ClientResult\<[FollowResult](#followresult-class)\> |  |
| **GetFollowedStatus(string url)** | ClientResult\<[FollowedStatus](#followedstatus-enum)\> |  |
| **GetGroups(int rowLimit)** | ClientResult\<[FollowedItem](#followeditem-class)[]\> |  |
| **GetItem(string url)** | ClientResult\<[FollowedItem](#followeditem-class)\> |  |
| **GetItems(FollowedContentQueryOptions options, int subtype)** | ClientResult\<[FollowedItem](#followeditem-class)[]\> |  |
| **HasGroupMembershipChangedAndSyncChanges()** | ClientResult\<bool\> |  |
| **IsFollowed(string url)** | ClientResult\<bool\> |  |
| **RefreshFollowedItem(FollowedItem item)** | ClientResult\<[FollowedItem](#followeditem-class)\> |  |
| **SetItemPinState(string uri, Guid groupId, int pinState)** | ClientResult\<[FollowResult](#followresult-class)\> |  |
| **StopFollowing(string url)** | void |  |
| **UpdateData(string url, FollowedItemData data)** | void |  |
| **UpdateFollowedGroupForUser(string contextUri, Guid groupId, string loginName)** | void |  |
# FollowedContentExceptionCode Enum

Namespace: Microsoft.SharePoint.Client.UserProfiles


## Values

| Name | Summary |
|---|---|
| **ItemAlreadyExists** |  |
| **ItemDoesNotExist** |  |
| **InvalidQueryString** |  |
| **InvalidSubtypeValue** |  |
| **UnsupportedItemType** |  |
| **FollowLimitReached** |  |
| **UntrustedSource** |  |
| **UnsupportedSite** |  |
| **InternalError** |  |
| **ItemNotFound** |  |
# FollowedContentPropertyNames Class

Namespace: Microsoft.SharePoint.Client.UserProfiles


## Fields

| Name | Type | Summary |
|---|---|---|
| **FollowedDocumentsUrl** | string |  |
| **FollowedSitesUrl** | string |  |
# FollowedContentQueryOptions Enum

Namespace: Microsoft.SharePoint.Client.UserProfiles


## Values

| Name | Summary |
|---|---|
| **Unset** |  |
| **Sites** |  |
| **Documents** |  |
| **Hidden** |  |
| **NonFeed** |  |
| **DefaultOptions** |  |
| **All** |  |
| **IncludeGroupsSites** |  |
| **WithinLast24Hours** |  |
# FollowedItem Class

Namespace: Microsoft.SharePoint.Client.UserProfiles

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Data** | IDictionary\<string, Object\> |  |
| **FileType** | string |  |
| **FileTypeProgid** | string |  |
| **Flags** | string |  |
| **GroupId** | Guid |  |
| **HasFeed** | bool |  |
| **Hidden** | bool |  |
| **IconUrl** | string |  |
| **ItemId** | int |  |
| **ItemType** | [FollowedItemType](#followeditemtype-enum) |  |
| **ListId** | Guid |  |
| **ParentUrl** | string |  |
| **Pinned** | int |  |
| **ServerUrlProgid** | string |  |
| **SiteId** | Guid |  |
| **Subtype** | int |  |
| **Title** | string |  |
| **UniqueId** | Guid |  |
| **Url** | string |  |
| **WebId** | Guid |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# FollowedItemData Class

Namespace: Microsoft.SharePoint.Client.UserProfiles

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Properties** | IDictionary\<string, Object\> |  |
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
| **FollowedItemData(ClientRuntimeContext context, IDictionary\<string, Object\> props)** |  |
| **FollowedItemData(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# FollowedItemDataPropertyNames Class

Namespace: Microsoft.SharePoint.Client.UserProfiles


## Fields

| Name | Type | Summary |
|---|---|---|
| **Properties** | string |  |
# FollowedItemType Enum

Namespace: Microsoft.SharePoint.Client.UserProfiles


## Values

| Name | Summary |
|---|---|
| **Unknown** |  |
| **Document** |  |
| **Site** |  |
| **All** |  |
# FollowedStatus Enum

Namespace: Microsoft.SharePoint.Client.UserProfiles


## Values

| Name | Summary |
|---|---|
| **Followed** |  |
| **NotFollowed** |  |
| **NotFollowable** |  |
# FollowResult Class

Namespace: Microsoft.SharePoint.Client.UserProfiles

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [FollowedItem](#followeditem-class) |  |
| **ResultType** | [FollowResultType](#followresulttype-enum) |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# FollowResultType Enum

Namespace: Microsoft.SharePoint.Client.UserProfiles


## Values

| Name | Summary |
|---|---|
| **Unknown** |  |
| **Followed** |  |
| **Refollowed** |  |
| **HitFollowLimit** |  |
| **Failed** |  |
# HashTag Class

Namespace: Microsoft.SharePoint.Client.UserProfiles

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Name** | string |  |
| **UseCount** | uint |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# HashTagCollection Class

Namespace: Microsoft.SharePoint.Client.UserProfiles

Base class: ClientObjectCollection<[HashTag](#hashtag-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [HashTag](#hashtag-class) |  |
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
| **HashTagCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ObjectTypes Enum

Namespace: Microsoft.SharePoint.Client.UserProfiles


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **SingleValueProperty** |  |
| **MultiValueProperty** |  |
| **Anniversary** |  |
| **DLMembership** |  |
| **SiteMembership** |  |
| **QuickLink** |  |
| **Colleague** |  |
| **PersonalizationSite** |  |
| **UserProfile** |  |
| **WebLog** |  |
| **Custom** |  |
| **OrganizationProfile** |  |
| **OrganizationMembership** |  |
| **All** |  |
# PeopleManager Class

Namespace: Microsoft.SharePoint.Client.UserProfiles

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **EditProfileLink** | string |  |
| **IsMyPeopleListPublic** | bool |  |
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
| **PeopleManager(ClientRuntimeContext context)** |  |
| **PeopleManager(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **AmIFollowedBy(string accountName)** | ClientResult\<bool\> |  |
| **AmIFollowing(string accountName)** | ClientResult\<bool\> |  |
| **Follow(string accountName)** | void |  |
| **FollowTag(Guid value)** | void |  |
| **GetDefaultDocumentLibrary(string accountName, bool createSiteIfNotExists, PersonalSiteCreationPriority siteCreationPriority)** | ClientResult\<string\> |  |
| **GetFollowedTags(int cTagsToFetch)** | ClientArrayResult\<string\> |  |
| **GetFollowersFor(string accountName)** | ClientObjectList\<[PersonProperties](#personproperties-class)\> |  |
| **GetMyFollowers()** | ClientObjectList\<[PersonProperties](#personproperties-class)\> |  |
| **GetMyProperties()** | [PersonProperties](#personproperties-class) |  |
| **GetMySuggestions()** | ClientObjectList\<[PersonProperties](#personproperties-class)\> |  |
| **GetPeopleFollowedBy(string accountName)** | ClientObjectList\<[PersonProperties](#personproperties-class)\> |  |
| **GetPeopleFollowedByMe()** | ClientObjectList\<[PersonProperties](#personproperties-class)\> |  |
| **GetPropertiesFor(string accountName)** | [PersonProperties](#personproperties-class) |  |
| **GetSPUserInformation(string accountName, Guid siteId)** | ClientResult\<IDictionary\<string, string\>\> |  |
| **GetTrendingTags(ClientRuntimeContext context)** | [HashTagCollection](#hashtagcollection-class) |  |
| **GetUserOneDriveQuotaMax(string accountName)** | ClientResult\<long\> |  |
| **GetUserProfileProperties(string accountName)** | ClientResult\<IDictionary\<string, string\>\> |  |
| **GetUserProfilePropertiesFor(UserProfilePropertiesForUser propertiesForUser)** | IEnumerable\<string\> |  |
| **GetUserProfilePropertyFor(string accountName, string propertyName)** | ClientResult\<string\> |  |
| **HardDeleteUserProfile(string accountName, Guid userId)** | ClientResult\<bool\> |  |
| **HideSuggestion(string accountName)** | void |  |
| **IsFollowing(ClientRuntimeContext context, string possibleFollowerAccountName, string possibleFolloweeAccountName)** | ClientResult\<bool\> |  |
| **RemoveSPUserInformation(string accountName, Guid siteId, string redactName)** | ClientResult\<IDictionary\<string, string\>\> |  |
| **ResetUserOneDriveQuotaToDefault(string accountName)** | ClientResult\<string\> |  |
| **SetMultiValuedProfileProperty(string accountName, string propertyName, IList\<string\> propertyValues)** | void |  |
| **SetMyProfilePicture(Stream picture)** | void |  |
| **SetSingleValueProfileProperty(string accountName, string propertyName, string propertyValue)** | void |  |
| **SetUserOneDriveQuota(string accountName, long newQuota, long newQuotaWarning)** | ClientResult\<string\> |  |
| **StopFollowing(string accountName)** | void |  |
| **StopFollowingTag(Guid value)** | void |  |
# PeopleManagerPropertyNames Class

Namespace: Microsoft.SharePoint.Client.UserProfiles


## Fields

| Name | Type | Summary |
|---|---|---|
| **EditProfileLink** | string |  |
| **IsMyPeopleListPublic** | string |  |
# PersonalCache Class

Namespace: Microsoft.SharePoint.Client.UserProfiles

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **CacheName** | string |  |
| **MySiteUrl** | string |  |
| **RequireHtmlStorage** | bool |  |
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
| **PersonalCache(ClientRuntimeContext context)** |  |
| **PersonalCache(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteCacheItemsAsync(PersonalCacheItem[] cacheItems)** | void |  |
| **DeleteCacheItemsAsync2(PersonalCacheItem[] cacheItems, string mySiteUrl)** | void |  |
| **Dispose()** | void |  |
| **ReadCache(string folderPath)** | ClientResult\<[PersonalCacheItem](#personalcacheitem-class)[]\> |  |
| **ReadCache2(string folderPath, string mySiteUrl)** | ClientResult\<[PersonalCacheItem](#personalcacheitem-class)[]\> |  |
| **ReadCacheOrCreate(ResourcePath folderPath, string[] requiredCacheKeys, bool createIfMissing)** | ClientResult\<[PersonalCacheItem](#personalcacheitem-class)[]\> |  |
| **ReadCacheOrCreate2(ResourcePath folderPath, string[] requiredCacheKeys, bool createIfMissing, string mySiteUrl)** | ClientResult\<[PersonalCacheItem](#personalcacheitem-class)[]\> |  |
| **ReadCacheOrCreateOrderById(ResourcePath folderPath, string[] requiredCacheKeys, bool createIfMissing)** | ClientResult\<[PersonalCacheItem](#personalcacheitem-class)[]\> |  |
| **ReadCacheOrCreateOrderById2(ResourcePath folderPath, string[] requiredCacheKeys, bool createIfMissing, string mySiteUrl)** | ClientResult\<[PersonalCacheItem](#personalcacheitem-class)[]\> |  |
| **WriteCache(PersonalCacheItem[] cacheItems)** | void |  |
| **WriteCache2(PersonalCacheItem[] cacheItems, string mySiteUrl)** | void |  |
# PersonalCacheExceptionCode Enum

Namespace: Microsoft.SharePoint.Client.UserProfiles


## Values

| Name | Summary |
|---|---|
| **PersonalSiteNotFound** |  |
| **PersonalCacheListNotFound** |  |
| **PersonalCacheListProvisionFailed** |  |
| **PersonalCacheItemProvisionFailed** |  |
| **FailedToRetrieveCacheListItems** |  |
| **PersonalCacheItemInvalidListItemId** |  |
| **FailedToUpdateCacheListItem** |  |
| **ProfileNotFound** |  |
| **RootFolderNotFound** |  |
| **FolderProvisionFailed** |  |
| **FolderNotFound** |  |
| **InvalidCacheKeys** |  |
| **InvalidCacheItems** |  |
| **WriteConflict** |  |
| **ReadFailure** |  |
| **FailedToDeleteCacheListItems** |  |
| **FileStoreBusy** |  |
| **FileFound** |  |
# PersonalCacheItem Class

Namespace: Microsoft.SharePoint.Client.UserProfiles

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AltTitle** | string |  |
| **CacheKey** | string |  |
| **CacheName** | string |  |
| **CacheValue** | string |  |
| **CacheValueHash** | string |  |
| **CacheValueHtml** | string |  |
| **CacheVersion** | string |  |
| **ContainerUrl** | string |  |
| **ListItemId** | int |  |
| **ListItemUniqueId** | string |  |
| **ModifiedTimeUtc** | DateTime |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# PersonalCachePropertyNames Class

Namespace: Microsoft.SharePoint.Client.UserProfiles


## Fields

| Name | Type | Summary |
|---|---|---|
| **CacheName** | string |  |
| **MySiteUrl** | string |  |
| **RequireHtmlStorage** | string |  |
# PersonalSiteCapabilities Enum

Namespace: Microsoft.SharePoint.Client.UserProfiles


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **Profile** |  |
| **Social** |  |
| **Storage** |  |
| **MyTasksDashboard** |  |
| **Education** |  |
| **Guest** |  |
# PersonalSiteCreationPriority Enum

Namespace: Microsoft.SharePoint.Client.UserProfiles


## Values

| Name | Summary |
|---|---|
| **Low** |  |
| **Medium** |  |
| **High** |  |
# PersonalSiteInstantiationState Enum

Namespace: Microsoft.SharePoint.Client.UserProfiles


## Values

| Name | Summary |
|---|---|
| **Uninitialized** |  |
| **Enqueued** |  |
| **Created** |  |
| **Deleted** |  |
| **PermissionsGeneralFailure** |  |
| **PermissionsUPANotGranted** |  |
| **PermissionsUserNotLicensed** |  |
| **PermissionsSelfServiceSiteCreationDisabled** |  |
| **PermissionsNoMySitesInPeopleLight** |  |
| **PermissionsEmptyHostUrl** |  |
| **PermissionsHostFailedToInitializePersonalSiteContext** |  |
| **ErrorGeneralFailure** |  |
| **ErrorManagedPathDoesNotExist** |  |
| **ErrorLanguageNotInstalled** |  |
| **ErrorPartialCreate** |  |
| **ErrorPersonalSiteAlreadyExists** |  |
| **ErrorRootSiteNotPresent** |  |
| **ErrorSelfServiceSiteCreateCallFailed** |  |
# PersonProperties Class

Namespace: Microsoft.SharePoint.Client.UserProfiles

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AccountName** | string |  |
| **DirectReports** | IEnumerable\<string\> |  |
| **DisplayName** | string |  |
| **Email** | string |  |
| **ExtendedManagers** | IEnumerable\<string\> |  |
| **ExtendedReports** | IEnumerable\<string\> |  |
| **IsFollowed** | bool |  |
| **LatestPost** | string |  |
| **Peers** | IEnumerable\<string\> |  |
| **PersonalSiteHostUrl** | string |  |
| **PersonalUrl** | string |  |
| **PictureUrl** | string |  |
| **Title** | string |  |
| **UserProfileProperties** | IDictionary\<string, string\> |  |
| **UserUrl** | string |  |
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
| **PersonProperties(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# PersonPropertiesPropertyNames Class

Namespace: Microsoft.SharePoint.Client.UserProfiles


## Fields

| Name | Type | Summary |
|---|---|---|
| **AccountName** | string |  |
| **DirectReports** | string |  |
| **DisplayName** | string |  |
| **Email** | string |  |
| **ExtendedManagers** | string |  |
| **ExtendedReports** | string |  |
| **IsFollowed** | string |  |
| **LatestPost** | string |  |
| **Peers** | string |  |
| **PersonalSiteHostUrl** | string |  |
| **PersonalUrl** | string |  |
| **PictureUrl** | string |  |
| **Title** | string |  |
| **UserProfileProperties** | string |  |
| **UserUrl** | string |  |
# ProfileImageStore Class

Namespace: Microsoft.SharePoint.Client.UserProfiles

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
| **ProfileImageStore(ClientRuntimeContext context)** |  |
| **ProfileImageStore(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **SaveUploadedFile(int profileType, string fileNamePrefix, bool isFeedAttachment, string clientFilePath, int fileSize, Stream fileStream)** | ClientArrayResult\<string\> |  |
# ProfileLoader Class

Namespace: Microsoft.SharePoint.Client.UserProfiles

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
| **ProfileLoader(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **CreatePersonalSiteEnqueueBulk(string[] emailIDs)** | IEnumerable\<string\> |  |
| **GetOwnerUserProfile(ClientRuntimeContext context)** | [UserProfile](#userprofile-class) |  |
| **GetProfileLoader(ClientRuntimeContext context)** | [ProfileLoader](#profileloader-class) |  |
| **GetUserProfile()** | [UserProfile](#userprofile-class) |  |
# ScriptTypeFactory Class

Namespace: Microsoft.SharePoint.Client.UserProfiles


## Methods

| Name | Returns | Summary |
|---|---|---|
| **CreateObjectFromScriptType(string scriptType, ClientRuntimeContext context)** | IFromJson |  |
# SocialDataStoreExceptionCode Enum

Namespace: Microsoft.SharePoint.Client.UserProfiles


## Values

| Name | Summary |
|---|---|
| **SocialListNotFound** |  |
| **PersonalSiteNotFound** |  |
| **CannotCreatePersonalSite** |  |
| **NoSocialFeatures** |  |
# UserProfile Class

Namespace: Microsoft.SharePoint.Client.UserProfiles

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AccountName** | string |  |
| **DisplayName** | string |  |
| **FollowedContent** | [FollowedContent](#followedcontent-class) |  |
| **FollowPersonalSiteUrl** | string |  |
| **IsDefaultDocumentLibraryBlocked** | bool |  |
| **IsPeopleListPublic** | bool |  |
| **IsPrivacySettingOn** | bool |  |
| **IsSelf** | bool |  |
| **JobTitle** | string |  |
| **MySiteFirstRunExperience** | int |  |
| **MySiteHostUrl** | string |  |
| **O15FirstRunExperience** | int |  |
| **PersonalSite** | Site |  |
| **PersonalSiteCapabilities** | [PersonalSiteCapabilities](#personalsitecapabilities-enum) |  |
| **PersonalSiteFirstCreationError** | string |  |
| **PersonalSiteFirstCreationTime** | DateTime |  |
| **PersonalSiteInstantiationState** | [PersonalSiteInstantiationState](#personalsiteinstantiationstate-enum) |  |
| **PersonalSiteLastCreationTime** | DateTime |  |
| **PersonalSiteNumberOfRetries** | int |  |
| **PictureImportEnabled** | bool |  |
| **PictureUrl** | string |  |
| **PublicUrl** | string |  |
| **SipAddress** | string |  |
| **UrlToCreatePersonalSite** | string |  |
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
| **UserProfile(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **CreatePersonalSite()** | void |  |
| **CreatePersonalSite(int lcid)** | void |  |
| **CreatePersonalSiteEnque()** | void |  |
| **CreatePersonalSiteEnque(bool isInteractive)** | void |  |
| **CreatePersonalSiteFromWorkItem(Guid workItemType)** | ClientResult\<int\> |  |
| **CreatePersonalSiteSyncFromWorkItem(ClientRuntimeContext context, Guid workItemType)** | ClientResult\<int\> |  |
| **SetMySiteFirstRunExperience(int value)** | void |  |
| **ShareAllSocialData(bool shareAll)** | void |  |
# UserProfileObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client.UserProfiles


## Fields

| Name | Type | Summary |
|---|---|---|
| **FollowedContent** | string |  |
| **PersonalSite** | string |  |
# UserProfilePropertiesForUser Class

Namespace: Microsoft.SharePoint.Client.UserProfiles

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AccountName** | string |  |
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
| **UserProfilePropertiesForUser(ClientRuntimeContext context, ObjectPath objectPath)** |  |
| **UserProfilePropertiesForUser(ClientRuntimeContext context, string accountName, string[] propertyNames)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetPropertyNames()** | ClientArrayResult\<string\> |  |
# UserProfilePropertiesForUserPropertyNames Class

Namespace: Microsoft.SharePoint.Client.UserProfiles


## Fields

| Name | Type | Summary |
|---|---|---|
| **AccountName** | string |  |
# UserProfilePropertyNames Class

Namespace: Microsoft.SharePoint.Client.UserProfiles


## Fields

| Name | Type | Summary |
|---|---|---|
| **AccountName** | string |  |
| **DisplayName** | string |  |
| **FollowPersonalSiteUrl** | string |  |
| **IsDefaultDocumentLibraryBlocked** | string |  |
| **IsPeopleListPublic** | string |  |
| **IsPrivacySettingOn** | string |  |
| **IsSelf** | string |  |
| **JobTitle** | string |  |
| **MySiteFirstRunExperience** | string |  |
| **MySiteHostUrl** | string |  |
| **O15FirstRunExperience** | string |  |
| **PersonalSiteCapabilities** | string |  |
| **PersonalSiteFirstCreationError** | string |  |
| **PersonalSiteFirstCreationTime** | string |  |
| **PersonalSiteInstantiationState** | string |  |
| **PersonalSiteLastCreationTime** | string |  |
| **PersonalSiteNumberOfRetries** | string |  |
| **PictureImportEnabled** | string |  |
| **PictureUrl** | string |  |
| **PublicUrl** | string |  |
| **SipAddress** | string |  |
| **UrlToCreatePersonalSite** | string |  |
