# Microsoft.SharePoint.Client.dll v.16.1.0.0 API documentation

Created by 
[mddox](https://github.com/loxsmoke/mddox) on 06/04/2023

# All types

|   |   |   |
|---|---|---|
| [__StaticArrayInitTypeSize=128 Struct](#staticarrayinittypesize128-struct) | [FieldLink Class](#fieldlink-class) | [RoleDefinitionPropertyNames Class](#roledefinitionpropertynames-class) |
| [__StaticArrayInitTypeSize=192 Struct](#staticarrayinittypesize192-struct) | [FieldLinkCollection Class](#fieldlinkcollection-class) | [RoleType Enum](#roletype-enum) |
| [EntityInstanceIdEncoder Class](#entityinstanceidencoder-class) | [FieldLinkCreationInformation Class](#fieldlinkcreationinformation-class) | [RuleOverrideOptions Enum](#ruleoverrideoptions-enum) |
| [ExternalSubscriptionStore Class](#externalsubscriptionstore-class) | [FieldLinkPropertyNames Class](#fieldlinkpropertynames-class) | [SandboxedCodeActivationCapabilities Enum](#sandboxedcodeactivationcapabilities-enum) |
| [AppBdcCatalog Class](#appbdccatalog-class) | [FieldLookup Class](#fieldlookup-class) | [SaveBinaryCheckMode Enum](#savebinarycheckmode-enum) |
| [Entity Class](#entity-class) | [FieldLookupPropertyNames Class](#fieldlookuppropertynames-class) | [ScriptTypeFactory Class](#scripttypefactory-class) |
| [EntityField Class](#entityfield-class) | [FieldLookupValue Class](#fieldlookupvalue-class) | [SecurableObject Class](#securableobject-class) |
| [EntityFieldPropertyNames Class](#entityfieldpropertynames-class) | [FieldMultiChoice Class](#fieldmultichoice-class) | [SecurableObjectObjectPropertyNames Class](#securableobjectobjectpropertynames-class) |
| [EntityIdentifier Class](#entityidentifier-class) | [FieldMultiChoicePropertyNames Class](#fieldmultichoicepropertynames-class) | [SecurableObjectPropertyNames Class](#securableobjectpropertynames-class) |
| [EntityIdentifierPropertyNames Class](#entityidentifierpropertynames-class) | [FieldMultiLineText Class](#fieldmultilinetext-class) | [ServerSettings Class](#serversettings-class) |
| [EntityPropertyNames Class](#entitypropertynames-class) | [FieldMultiLineTextPropertyNames Class](#fieldmultilinetextpropertynames-class) | [SharedWithUser Class](#sharedwithuser-class) |
| [EntityView Class](#entityview-class) | [FieldNumber Class](#fieldnumber-class) | [SharedWithUserCollection Class](#sharedwithusercollection-class) |
| [EntityViewObjectPropertyNames Class](#entityviewobjectpropertynames-class) | [FieldNumberPropertyNames Class](#fieldnumberpropertynames-class) | [SharePointSharingSettings Class](#sharepointsharingsettings-class) |
| [EntityViewPropertyNames Class](#entityviewpropertynames-class) | [FieldObjectPropertyNames Class](#fieldobjectpropertynames-class) | [SharePointSharingSettingsObjectPropertyNames Class](#sharepointsharingsettingsobjectpropertynames-class) |
| [Filter Class](#filter-class) | [FieldPropertyNames Class](#fieldpropertynames-class) | [SharePointSharingSettingsPropertyNames Class](#sharepointsharingsettingspropertynames-class) |
| [FilterPropertyNames Class](#filterpropertynames-class) | [FieldRatingScale Class](#fieldratingscale-class) | [SharingLinkInfo Class](#sharinglinkinfo-class) |
| [LobSystem Class](#lobsystem-class) | [FieldRatingScalePropertyNames Class](#fieldratingscalepropertynames-class) | [SharingLinkKind Enum](#sharinglinkkind-enum) |
| [LobSystemInstance Class](#lobsysteminstance-class) | [FieldRatingScaleQuestionAnswer Class](#fieldratingscalequestionanswer-class) | [SharingOperationStatusCode Enum](#sharingoperationstatuscode-enum) |
| [LobSystemInstancePropertyNames Class](#lobsysteminstancepropertynames-class) | [FieldStringValues Class](#fieldstringvalues-class) | [SharingPermissionInformation Class](#sharingpermissioninformation-class) |
| [LobSystemPropertyNames Class](#lobsystempropertynames-class) | [FieldText Class](#fieldtext-class) | [SharingPermissionInformationCollection Class](#sharingpermissioninformationcollection-class) |
| [MethodExecutionResult Class](#methodexecutionresult-class) | [FieldTextPropertyNames Class](#fieldtextpropertynames-class) | [SharingPermissionInformationPropertyNames Class](#sharingpermissioninformationpropertynames-class) |
| [MethodExecutionResultObjectPropertyNames Class](#methodexecutionresultobjectpropertynames-class) | [FieldType Enum](#fieldtype-enum) | [SharingPermissionKind Enum](#sharingpermissionkind-enum) |
| [ReturnParameterCollection Class](#returnparametercollection-class) | [FieldUrl Class](#fieldurl-class) | [SharingResult Class](#sharingresult-class) |
| [TypeDescriptor Class](#typedescriptor-class) | [FieldUrlPropertyNames Class](#fieldurlpropertynames-class) | [SharingResultObjectPropertyNames Class](#sharingresultobjectpropertynames-class) |
| [TypeDescriptorPropertyNames Class](#typedescriptorpropertynames-class) | [FieldUrlValue Class](#fieldurlvalue-class) | [SharingResultPropertyNames Class](#sharingresultpropertynames-class) |
| [EntityFieldCollection Class](#entityfieldcollection-class) | [FieldUser Class](#fielduser-class) | [SharingUserCollection Class](#sharingusercollection-class) |
| [EntityIdentifierCollection Class](#entityidentifiercollection-class) | [FieldUserPropertyNames Class](#fielduserpropertynames-class) | [Site Class](#site-class) |
| [EntityInstanceCollection Class](#entityinstancecollection-class) | [FieldUserSelectionMode Enum](#fielduserselectionmode-enum) | [SiteObjectPropertyNames Class](#siteobjectpropertynames-class) |
| [FilterCollection Class](#filtercollection-class) | [FieldUserValue Class](#fielduservalue-class) | [SitePropertyNames Class](#sitepropertynames-class) |
| [LobSystemInstanceCollection Class](#lobsysteminstancecollection-class) | [File Class](#file-class) | [SiteUrl Class](#siteurl-class) |
| [TypeDescriptorCollection Class](#typedescriptorcollection-class) | [FileCollection Class](#filecollection-class) | [SPClientUtility Class](#spclientutility-class) |
| [EntityEventType Enum](#entityeventtype-enum) | [FileCreationInformation Class](#filecreationinformation-class) | [SPDataLeakagePreventionStatusInfo Class](#spdataleakagepreventionstatusinfo-class) |
| [EntityFieldValueDictionary Class](#entityfieldvaluedictionary-class) | [FileInformation Class](#fileinformation-class) | [SPDataLeakagePreventionStatusInfoPropertyNames Class](#spdataleakagepreventionstatusinfopropertynames-class) |
| [EntityIdentity Class](#entityidentity-class) | [FileLevel Enum](#filelevel-enum) | [SpecialFolderType Enum](#specialfoldertype-enum) |
| [EntityIdentityPropertyNames Class](#entityidentitypropertynames-class) | [FileObjectPropertyNames Class](#fileobjectpropertynames-class) | [SPEffectiveInformationRightsManagementSettingsSource Enum](#speffectiveinformationrightsmanagementsettingssource-enum) |
| [EntityInstance Class](#entityinstance-class) | [FilePropertyNames Class](#filepropertynames-class) | [SPInvitationCreationResult Class](#spinvitationcreationresult-class) |
| [NotificationCallback Class](#notificationcallback-class) | [FileSaveBinaryInformation Class](#filesavebinaryinformation-class) | [SPMigrationJobStatus Class](#spmigrationjobstatus-class) |
| [NotificationCallbackPropertyNames Class](#notificationcallbackpropertynames-class) | [FileSystemObjectType Enum](#filesystemobjecttype-enum) | [SPMigrationJobStatusCollection Class](#spmigrationjobstatuscollection-class) |
| [Subscription Class](#subscription-class) | [FileVersion Class](#fileversion-class) | [SPMigrationJobStatusPropertyNames Class](#spmigrationjobstatuspropertynames-class) |
| [SubscriptionPropertyNames Class](#subscriptionpropertynames-class) | [FileVersionCollection Class](#fileversioncollection-class) | [StorageMetrics Class](#storagemetrics-class) |
| [ClientPeoplePickerQueryParameters Class](#clientpeoplepickerqueryparameters-class) | [FileVersionEvent Class](#fileversionevent-class) | [StorageMetricsPropertyNames Class](#storagemetricspropertynames-class) |
| [ClientPeoplePickerWebServiceInterface Class](#clientpeoplepickerwebserviceinterface-class) | [FileVersionEventCollection Class](#fileversioneventcollection-class) | [SubwebQuery Class](#subwebquery-class) |
| [AccessRequests Class](#accessrequests-class) | [FileVersionEventPropertyNames Class](#fileversioneventpropertynames-class) | [TemplateFileType Enum](#templatefiletype-enum) |
| [AddFieldOptions Enum](#addfieldoptions-enum) | [FileVersionEventType Enum](#fileversioneventtype-enum) | [TenantAppInformation Class](#tenantappinformation-class) |
| [AlternateUrl Class](#alternateurl-class) | [FileVersionObjectPropertyNames Class](#fileversionobjectpropertynames-class) | [TenantAppInstance Class](#tenantappinstance-class) |
| [AlternateUrlPropertyNames Class](#alternateurlpropertynames-class) | [FileVersionPropertyNames Class](#fileversionpropertynames-class) | [TenantAppInstancePropertyNames Class](#tenantappinstancepropertynames-class) |
| [App Class](#app-class) | [Folder Class](#folder-class) | [TenantAppUtility Class](#tenantapputility-class) |
| [AppCatalog Class](#appcatalog-class) | [FolderCollection Class](#foldercollection-class) | [TenantSettings Class](#tenantsettings-class) |
| [AppInstance Class](#appinstance-class) | [FolderObjectPropertyNames Class](#folderobjectpropertynames-class) | [TenantSettingsPropertyNames Class](#tenantsettingspropertynames-class) |
| [AppInstanceErrorDetails Class](#appinstanceerrordetails-class) | [FolderPropertyNames Class](#folderpropertynames-class) | [ThemeInfo Class](#themeinfo-class) |
| [AppInstanceErrorDetailsPropertyNames Class](#appinstanceerrordetailspropertynames-class) | [Form Class](#form-class) | [ThemeInfoPropertyNames Class](#themeinfopropertynames-class) |
| [AppInstanceErrorSource Enum](#appinstanceerrorsource-enum) | [FormCollection Class](#formcollection-class) | [TimeZone Class](#timezone-class) |
| [AppInstanceErrorType Enum](#appinstanceerrortype-enum) | [FormDigestInfo Class](#formdigestinfo-class) | [TimeZoneCollection Class](#timezonecollection-class) |
| [AppInstancePropertyNames Class](#appinstancepropertynames-class) | [FormPropertyNames Class](#formpropertynames-class) | [TimeZoneInformation Class](#timezoneinformation-class) |
| [AppInstanceStatus Enum](#appinstancestatus-enum) | [Group Class](#group-class) | [TimeZonePropertyNames Class](#timezonepropertynames-class) |
| [AppLicense Class](#applicense-class) | [GroupCollection Class](#groupcollection-class) | [UpgradeInfo Class](#upgradeinfo-class) |
| [AppLicenseCollection Class](#applicensecollection-class) | [GroupCreationInformation Class](#groupcreationinformation-class) | [UpgradeStatus Enum](#upgradestatus-enum) |
| [AppLicenseType Enum](#applicensetype-enum) | [GroupObjectPropertyNames Class](#groupobjectpropertynames-class) | [UpgradeType Enum](#upgradetype-enum) |
| [AppPrincipal Class](#appprincipal-class) | [GroupPropertyNames Class](#grouppropertynames-class) | [UrlFieldFormatType Enum](#urlfieldformattype-enum) |
| [AppPrincipalConfiguration Class](#appprincipalconfiguration-class) | [InformationRightsManagementFileSettings Class](#informationrightsmanagementfilesettings-class) | [UrlZone Enum](#urlzone-enum) |
| [AppPrincipalCredential Class](#appprincipalcredential-class) | [InformationRightsManagementFileSettingsPropertyNames Class](#informationrightsmanagementfilesettingspropertynames-class) | [UsageInfo Class](#usageinfo-class) |
| [AppPrincipalCredentialReference Class](#appprincipalcredentialreference-class) | [InformationRightsManagementSettings Class](#informationrightsmanagementsettings-class) | [User Class](#user-class) |
| [AppPrincipalIdentityProvider Class](#appprincipalidentityprovider-class) | [InformationRightsManagementSettingsPropertyNames Class](#informationrightsmanagementsettingspropertynames-class) | [UserCollection Class](#usercollection-class) |
| [AppPrincipalManager Class](#appprincipalmanager-class) | [IngestionTaskKey Class](#ingestiontaskkey-class) | [UserCreationInformation Class](#usercreationinformation-class) |
| [AppPrincipalName Class](#appprincipalname-class) | [Language Class](#language-class) | [UserCustomAction Class](#usercustomaction-class) |
| [AppPrincipalPropertyNames Class](#appprincipalpropertynames-class) | [List Class](#list-class) | [UserCustomActionCollection Class](#usercustomactioncollection-class) |
| [AppPropertyNames Class](#apppropertynames-class) | [ListCollection Class](#listcollection-class) | [UserCustomActionObjectPropertyNames Class](#usercustomactionobjectpropertynames-class) |
| [AppSiteContext Class](#appsitecontext-class) | [ListCreationInformation Class](#listcreationinformation-class) | [UserCustomActionPropertyNames Class](#usercustomactionpropertynames-class) |
| [AppSiteContextUtility Class](#appsitecontextutility-class) | [ListDataSource Class](#listdatasource-class) | [UserCustomActionRegistrationType Enum](#usercustomactionregistrationtype-enum) |
| [AppTile Class](#apptile-class) | [ListDataValidationExceptionValue Class](#listdatavalidationexceptionvalue-class) | [UserCustomActionScope Enum](#usercustomactionscope-enum) |
| [AppTileCollection Class](#apptilecollection-class) | [ListDataValidationFailure Class](#listdatavalidationfailure-class) | [UserIdInfo Class](#useridinfo-class) |
| [AppTilePropertyNames Class](#apptilepropertynames-class) | [ListDataValidationFailureReason Enum](#listdatavalidationfailurereason-enum) | [UserObjectPropertyNames Class](#userobjectpropertynames-class) |
| [AppType Enum](#apptype-enum) | [ListDataValidationType Enum](#listdatavalidationtype-enum) | [UserPropertyNames Class](#userpropertynames-class) |
| [Attachment Class](#attachment-class) | [ListItem Class](#listitem-class) | [UserResource Class](#userresource-class) |
| [AttachmentCollection Class](#attachmentcollection-class) | [ListItemCollection Class](#listitemcollection-class) | [UserResourceScope Enum](#userresourcescope-enum) |
| [AttachmentCreationInformation Class](#attachmentcreationinformation-class) | [ListItemCollectionPosition Class](#listitemcollectionposition-class) | [UserResourceType Enum](#userresourcetype-enum) |
| [AttachmentPropertyNames Class](#attachmentpropertynames-class) | [ListItemCollectionPropertyNames Class](#listitemcollectionpropertynames-class) | [UserSharingCapabilities Enum](#usersharingcapabilities-enum) |
| [Audit Class](#audit-class) | [ListItemCreationInformation Class](#listitemcreationinformation-class) | [View Class](#view-class) |
| [AuditMaskType Enum](#auditmasktype-enum) | [ListItemEntityCollection Class](#listitementitycollection-class) | [ViewCollection Class](#viewcollection-class) |
| [AuditPropertyNames Class](#auditpropertynames-class) | [ListItemFormUpdateValue Class](#listitemformupdatevalue-class) | [ViewCreationInformation Class](#viewcreationinformation-class) |
| [BasePermissions Class](#basepermissions-class) | [ListItemObjectPropertyNames Class](#listitemobjectpropertynames-class) | [ViewFieldCollection Class](#viewfieldcollection-class) |
| [BaseType Enum](#basetype-enum) | [ListItemPropertyNames Class](#listitempropertynames-class) | [ViewFieldCollectionPropertyNames Class](#viewfieldcollectionpropertynames-class) |
| [BrowserFileHandling Enum](#browserfilehandling-enum) | [ListObjectPropertyNames Class](#listobjectpropertynames-class) | [ViewObjectPropertyNames Class](#viewobjectpropertynames-class) |
| [CalendarType Enum](#calendartype-enum) | [ListPropertyNames Class](#listpropertynames-class) | [ViewPropertyNames Class](#viewpropertynames-class) |
| [CamlQuery Class](#camlquery-class) | [ListTemplate Class](#listtemplate-class) | [ViewScope Enum](#viewscope-enum) |
| [Change Class](#change-class) | [ListTemplateCollection Class](#listtemplatecollection-class) | [ViewType Enum](#viewtype-enum) |
| [ChangeAlert Class](#changealert-class) | [ListTemplatePropertyNames Class](#listtemplatepropertynames-class) | [Visualization Class](#visualization-class) |
| [ChangeAlertPropertyNames Class](#changealertpropertynames-class) | [ListTemplateType Enum](#listtemplatetype-enum) | [VisualizationField Class](#visualizationfield-class) |
| [ChangeCollection Class](#changecollection-class) | [MigrationJobState Enum](#migrationjobstate-enum) | [VisualizationStyleSet Class](#visualizationstyleset-class) |
| [ChangeContentType Class](#changecontenttype-class) | [MountedFolderInfo Class](#mountedfolderinfo-class) | [Web Class](#web-class) |
| [ChangeContentTypePropertyNames Class](#changecontenttypepropertynames-class) | [MountedFolderInfoPropertyNames Class](#mountedfolderinfopropertynames-class) | [WebCollection Class](#webcollection-class) |
| [ChangeField Class](#changefield-class) | [MountPoint Class](#mountpoint-class) | [WebCreationInformation Class](#webcreationinformation-class) |
| [ChangeFieldPropertyNames Class](#changefieldpropertynames-class) | [MountPointInfo Class](#mountpointinfo-class) | [WebInformation Class](#webinformation-class) |
| [ChangeFile Class](#changefile-class) | [MountPointInfoPropertyNames Class](#mountpointinfopropertynames-class) | [WebInformationPropertyNames Class](#webinformationpropertynames-class) |
| [ChangeFilePropertyNames Class](#changefilepropertynames-class) | [MoveCopyUtil Class](#movecopyutil-class) | [WebObjectPropertyNames Class](#webobjectpropertynames-class) |
| [ChangeFolder Class](#changefolder-class) | [MoveOperations Enum](#moveoperations-enum) | [WebPropertyNames Class](#webpropertynames-class) |
| [ChangeFolderPropertyNames Class](#changefolderpropertynames-class) | [Navigation Class](#navigation-class) | [WebProxy Class](#webproxy-class) |
| [ChangeGroup Class](#changegroup-class) | [NavigationNode Class](#navigationnode-class) | [WebRequestInfo Class](#webrequestinfo-class) |
| [ChangeGroupPropertyNames Class](#changegrouppropertynames-class) | [NavigationNodeCollection Class](#navigationnodecollection-class) | [WebResponseInfo Class](#webresponseinfo-class) |
| [ChangeItem Class](#changeitem-class) | [NavigationNodeCreationInformation Class](#navigationnodecreationinformation-class) | [WebTemplate Class](#webtemplate-class) |
| [ChangeItemPropertyNames Class](#changeitempropertynames-class) | [NavigationNodeObjectPropertyNames Class](#navigationnodeobjectpropertynames-class) | [WebTemplateCollection Class](#webtemplatecollection-class) |
| [ChangeList Class](#changelist-class) | [NavigationNodePropertyNames Class](#navigationnodepropertynames-class) | [WebTemplatePropertyNames Class](#webtemplatepropertynames-class) |
| [ChangeListPropertyNames Class](#changelistpropertynames-class) | [NavigationObjectPropertyNames Class](#navigationobjectpropertynames-class) | [AnalyticsUsageEntry Class](#analyticsusageentry-class) |
| [ChangeLogItemQuery Class](#changelogitemquery-class) | [NavigationPropertyNames Class](#navigationpropertynames-class) | [EventTypeId Enum](#eventtypeid-enum) |
| [ChangePropertyNames Class](#changepropertynames-class) | [ObjectSharingInformation Class](#objectsharinginformation-class) | [IRemoteEventService Class](#iremoteeventservice-class) |
| [ChangeQuery Class](#changequery-class) | [ObjectSharingInformationObjectPropertyNames Class](#objectsharinginformationobjectpropertynames-class) | [SPRemoteAppEventProperties Class](#spremoteappeventproperties-class) |
| [ChangeSite Class](#changesite-class) | [ObjectSharingInformationPropertyNames Class](#objectsharinginformationpropertynames-class) | [SPRemoteEntityInstanceEventProperties Class](#spremoteentityinstanceeventproperties-class) |
| [ChangeToken Class](#changetoken-class) | [ObjectSharingInformationUser Class](#objectsharinginformationuser-class) | [SPRemoteEventProperties Class](#spremoteeventproperties-class) |
| [ChangeType Enum](#changetype-enum) | [ObjectSharingInformationUserCollection Class](#objectsharinginformationusercollection-class) | [SPRemoteEventResult Class](#spremoteeventresult-class) |
| [ChangeUser Class](#changeuser-class) | [ObjectSharingInformationUserObjectPropertyNames Class](#objectsharinginformationuserobjectpropertynames-class) | [SPRemoteEventServiceStatus Enum](#spremoteeventservicestatus-enum) |
| [ChangeUserPropertyNames Class](#changeuserpropertynames-class) | [ObjectSharingInformationUserPropertyNames Class](#objectsharinginformationuserpropertynames-class) | [SPRemoteEventType Enum](#spremoteeventtype-enum) |
| [ChangeView Class](#changeview-class) | [ObjectSharingSettings Class](#objectsharingsettings-class) | [SPRemoteItemEventProperties Class](#spremoteitemeventproperties-class) |
| [ChangeViewPropertyNames Class](#changeviewpropertynames-class) | [ObjectSharingSettingsObjectPropertyNames Class](#objectsharingsettingsobjectpropertynames-class) | [SPRemoteListEventProperties Class](#spremotelisteventproperties-class) |
| [ChangeWeb Class](#changeweb-class) | [ObjectSharingSettingsPropertyNames Class](#objectsharingsettingspropertynames-class) | [SPRemoteSecurityEventProperties Class](#spremotesecurityeventproperties-class) |
| [ChangeWebPropertyNames Class](#changewebpropertynames-class) | [OpenWebOptions Enum](#openweboptions-enum) | [SPRemoteWebEventProperties Class](#spremotewebeventproperties-class) |
| [CheckinType Enum](#checkintype-enum) | [PageType Enum](#pagetype-enum) | [NativeClient Class](#nativeclient-class) |
| [CheckOutType Enum](#checkouttype-enum) | [PermissionKind Enum](#permissionkind-enum) | [ClickManager Class](#clickmanager-class) |
| [ChoiceFormatType Enum](#choiceformattype-enum) | [PickerSettings Class](#pickersettings-class) | [PageImpressionClient Class](#pageimpressionclient-class) |
| [ClientContext Class](#clientcontext-class) | [PickerSettingsPropertyNames Class](#pickersettingspropertynames-class) | [DocumentSharingManager Class](#documentsharingmanager-class) |
| [CompatibilityRange Class](#compatibilityrange-class) | [PolicyTipUserAction Enum](#policytipuseraction-enum) | [RemoveItemsFromSharedWithMeViewErrorCode Enum](#removeitemsfromsharedwithmeviewerrorcode-enum) |
| [ContentType Class](#contenttype-class) | [PolicyTipUserActionResult Enum](#policytipuseractionresult-enum) | [Role Enum](#role-enum) |
| [ContentTypeCollection Class](#contenttypecollection-class) | [Principal Class](#principal-class) | [SharedWithMeViewItemRemovalResult Class](#sharedwithmeviewitemremovalresult-class) |
| [ContentTypeCreationInformation Class](#contenttypecreationinformation-class) | [PrincipalPropertyNames Class](#principalpropertynames-class) | [UserRoleAssignment Class](#userroleassignment-class) |
| [ContentTypeId Class](#contenttypeid-class) | [PropertyValues Class](#propertyvalues-class) | [UserSharingResult Class](#usersharingresult-class) |
| [ContentTypeObjectPropertyNames Class](#contenttypeobjectpropertynames-class) | [PushNotificationSubscriber Class](#pushnotificationsubscriber-class) | [WebSharingManager Class](#websharingmanager-class) |
| [ContentTypePropertyNames Class](#contenttypepropertynames-class) | [PushNotificationSubscriberCollection Class](#pushnotificationsubscribercollection-class) | [SiteHealthResult Class](#sitehealthresult-class) |
| [CreatableItemInfo Class](#creatableiteminfo-class) | [PushNotificationSubscriberObjectPropertyNames Class](#pushnotificationsubscriberobjectpropertynames-class) | [SiteHealthStatusType Enum](#sitehealthstatustype-enum) |
| [CreatableItemInfoCollection Class](#creatableiteminfocollection-class) | [PushNotificationSubscriberPropertyNames Class](#pushnotificationsubscriberpropertynames-class) | [SiteHealthSummary Class](#sitehealthsummary-class) |
| [CreatablesInfo Class](#creatablesinfo-class) | [QuickLaunchOptions Enum](#quicklaunchoptions-enum) | [SiteHealthSummaryPropertyNames Class](#sitehealthsummarypropertynames-class) |
| [CreatablesInfoPropertyNames Class](#creatablesinfopropertynames-class) | [RecycleBinItem Class](#recyclebinitem-class) | [DateTimeFormat Enum](#datetimeformat-enum) |
| [CustomActionElement Class](#customactionelement-class) | [RecycleBinItemCollection Class](#recyclebinitemcollection-class) | [EmailProperties Class](#emailproperties-class) |
| [CustomActionElementCollection Class](#customactionelementcollection-class) | [RecycleBinItemObjectPropertyNames Class](#recyclebinitemobjectpropertynames-class) | [HtmlStrings Class](#htmlstrings-class) |
| [CustomizedPageStatus Enum](#customizedpagestatus-enum) | [RecycleBinItemPropertyNames Class](#recyclebinitempropertynames-class) | [HttpUtility Class](#httputility-class) |
| [DateTimeFieldFormatType Enum](#datetimefieldformattype-enum) | [RecycleBinItemState Enum](#recyclebinitemstate-enum) | [IconSize Enum](#iconsize-enum) |
| [DateTimeFieldFriendlyFormatType Enum](#datetimefieldfriendlyformattype-enum) | [RecycleBinItemType Enum](#recyclebinitemtype-enum) | [LogAppErrorResult Enum](#logapperrorresult-enum) |
| [DlpPolicyTip Class](#dlppolicytip-class) | [RecycleBinOrderBy Enum](#recyclebinorderby-enum) | [PrincipalInfo Class](#principalinfo-class) |
| [DlpPolicyTipPropertyNames Class](#dlppolicytippropertynames-class) | [RegionalSettings Class](#regionalsettings-class) | [PrincipalSource Enum](#principalsource-enum) |
| [DocumentLibraryInformation Class](#documentlibraryinformation-class) | [RegionalSettingsObjectPropertyNames Class](#regionalsettingsobjectpropertynames-class) | [PrincipalType Enum](#principaltype-enum) |
| [DocumentTemplateType Enum](#documenttemplatetype-enum) | [RegionalSettingsPropertyNames Class](#regionalsettingspropertynames-class) | [SPWOPIFrameAction Enum](#spwopiframeaction-enum) |
| [DraftVisibilityType Enum](#draftvisibilitytype-enum) | [RelatedField Class](#relatedfield-class) | [UrlUtility Class](#urlutility-class) |
| [EffectiveInformationRightsManagementSettings Class](#effectiveinformationrightsmanagementsettings-class) | [RelatedFieldCollection Class](#relatedfieldcollection-class) | [Utility Class](#utility-class) |
| [EffectiveInformationRightsManagementSettingsPropertyNames Class](#effectiveinformationrightsmanagementsettingspropertynames-class) | [RelatedFieldObjectPropertyNames Class](#relatedfieldobjectpropertynames-class) | [WikiPageCreationInformation Class](#wikipagecreationinformation-class) |
| [EncryptionOption Class](#encryptionoption-class) | [RelatedFieldPropertyNames Class](#relatedfieldpropertynames-class) | [WopiHostUtility Class](#wopihostutility-class) |
| [EventReceiverDefinition Class](#eventreceiverdefinition-class) | [RelatedItem Class](#relateditem-class) | [WopiProperties Class](#wopiproperties-class) |
| [EventReceiverDefinitionCollection Class](#eventreceiverdefinitioncollection-class) | [RelatedItemManager Class](#relateditemmanager-class) | [WopiPropertiesPropertyNames Class](#wopipropertiespropertynames-class) |
| [EventReceiverDefinitionCreationInformation Class](#eventreceiverdefinitioncreationinformation-class) | [RelationshipDeleteBehaviorType Enum](#relationshipdeletebehaviortype-enum) | [LimitedWebPartManager Class](#limitedwebpartmanager-class) |
| [EventReceiverDefinitionPropertyNames Class](#eventreceiverdefinitionpropertynames-class) | [RemoteWeb Class](#remoteweb-class) | [LimitedWebPartManagerObjectPropertyNames Class](#limitedwebpartmanagerobjectpropertynames-class) |
| [EventReceiverSynchronization Enum](#eventreceiversynchronization-enum) | [RemoteWebPropertyNames Class](#remotewebpropertynames-class) | [LimitedWebPartManagerPropertyNames Class](#limitedwebpartmanagerpropertynames-class) |
| [EventReceiverType Enum](#eventreceivertype-enum) | [RenderListContextMenuDataParameters Class](#renderlistcontextmenudataparameters-class) | [PersonalizationScope Enum](#personalizationscope-enum) |
| [ExternalApplicationRequestToken Class](#externalapplicationrequesttoken-class) | [RenderListDataOptions Enum](#renderlistdataoptions-enum) | [TileData Class](#tiledata-class) |
| [ExternalAppPrincipalCreationParameters Class](#externalappprincipalcreationparameters-class) | [RenderListDataOverrideParameters Class](#renderlistdataoverrideparameters-class) | [WebPart Class](#webpart-class) |
| [Feature Class](#feature-class) | [RenderListDataParameters Class](#renderlistdataparameters-class) | [WebPartDefinition Class](#webpartdefinition-class) |
| [FeatureCollection Class](#featurecollection-class) | [RenderListFilterDataParameters Class](#renderlistfilterdataparameters-class) | [WebPartDefinitionCollection Class](#webpartdefinitioncollection-class) |
| [FeatureDefinitionScope Enum](#featuredefinitionscope-enum) | [RenderListFormDataOptions Enum](#renderlistformdataoptions-enum) | [WebPartDefinitionObjectPropertyNames Class](#webpartdefinitionobjectpropertynames-class) |
| [FeaturePropertyNames Class](#featurepropertynames-class) | [RequestContext Class](#requestcontext-class) | [WebPartDefinitionPropertyNames Class](#webpartdefinitionpropertynames-class) |
| [Field Class](#field-class) | [RequestContextObjectPropertyNames Class](#requestcontextobjectpropertynames-class) | [WebPartObjectPropertyNames Class](#webpartobjectpropertynames-class) |
| [FieldCalculated Class](#fieldcalculated-class) | [RequestForwarder Class](#requestforwarder-class) | [WebPartPropertyNames Class](#webpartpropertynames-class) |
| [FieldCalculatedErrorValue Class](#fieldcalculatederrorvalue-class) | [RequestResourceConstants Class](#requestresourceconstants-class) | [WorkflowAssociation Class](#workflowassociation-class) |
| [FieldCalculatedPropertyNames Class](#fieldcalculatedpropertynames-class) | [RequestResources Class](#requestresources-class) | [WorkflowAssociationCollection Class](#workflowassociationcollection-class) |
| [FieldChoice Class](#fieldchoice-class) | [RequestUserContext Class](#requestusercontext-class) | [WorkflowAssociationCreationInformation Class](#workflowassociationcreationinformation-class) |
| [FieldChoicePropertyNames Class](#fieldchoicepropertynames-class) | [RequestUserContextObjectPropertyNames Class](#requestusercontextobjectpropertynames-class) | [WorkflowAssociationPropertyNames Class](#workflowassociationpropertynames-class) |
| [FieldCollection Class](#fieldcollection-class) | [RequestVariable Class](#requestvariable-class) | [WorkflowTemplate Class](#workflowtemplate-class) |
| [FieldCollectionPropertyNames Class](#fieldcollectionpropertynames-class) | [RequestVariablePropertyNames Class](#requestvariablepropertynames-class) | [WorkflowTemplateCollection Class](#workflowtemplatecollection-class) |
| [FieldComputed Class](#fieldcomputed-class) | [RoleAssignment Class](#roleassignment-class) | [WorkflowTemplatePropertyNames Class](#workflowtemplatepropertynames-class) |
| [FieldComputedPropertyNames Class](#fieldcomputedpropertynames-class) | [RoleAssignmentCollection Class](#roleassignmentcollection-class) | [AppDetails Class](#appdetails-class) |
| [FieldCurrency Class](#fieldcurrency-class) | [RoleAssignmentCollectionObjectPropertyNames Class](#roleassignmentcollectionobjectpropertynames-class) | [AppDetailsPropertyNames Class](#appdetailspropertynames-class) |
| [FieldCurrencyPropertyNames Class](#fieldcurrencypropertynames-class) | [RoleAssignmentObjectPropertyNames Class](#roleassignmentobjectpropertynames-class) | [AppIconInfo Class](#appiconinfo-class) |
| [FieldDateTime Class](#fielddatetime-class) | [RoleAssignmentPropertyNames Class](#roleassignmentpropertynames-class) | [AppIconInfoPropertyNames Class](#appiconinfopropertynames-class) |
| [FieldDateTimePropertyNames Class](#fielddatetimepropertynames-class) | [RoleDefinition Class](#roledefinition-class) | [ModuleLink Class](#modulelink-class) |
| [FieldGeolocation Class](#fieldgeolocation-class) | [RoleDefinitionBindingCollection Class](#roledefinitionbindingcollection-class) | [ResourceManifestInformation Class](#resourcemanifestinformation-class) |
| [FieldGeolocationValue Class](#fieldgeolocationvalue-class) | [RoleDefinitionCollection Class](#roledefinitioncollection-class) | [ResourceManifestInformationPropertyNames Class](#resourcemanifestinformationpropertynames-class) |
| [FieldGuid Class](#fieldguid-class) | [RoleDefinitionCreationInformation Class](#roledefinitioncreationinformation-class) |   |
# __StaticArrayInitTypeSize=128 Struct

Namespace: 


# __StaticArrayInitTypeSize=192 Struct

Namespace: 


# EntityInstanceIdEncoder Class

Namespace: Microsoft.BusinessData.Infrastructure


## Methods

| Name | Returns | Summary |
|---|---|---|
| **EncodeEntityInstanceId(ClientRuntimeContext context, Object[] subIdentifiers)** | ClientResult\<string\> |  |
# ExternalSubscriptionStore Class

Namespace: Microsoft.BusinessData.Infrastructure

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
| **ExternalSubscriptionStore(ClientRuntimeContext context, Web web)** |  |
| **ExternalSubscriptionStore(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **IndexStore()** | void |  |
# AppBdcCatalog Class

Namespace: Microsoft.BusinessData.MetadataModel

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
| **AppBdcCatalog(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetConnectionId(string lobSystemName, string lobSystemInstanceName)** | ClientResult\<string\> |  |
| **GetEntity(string namespace, string name)** | [Entity](#entity-class) |  |
| **GetLobSystemInstanceProperty(string lobSystemName, string lobSystemInstanceName, string propertyName)** | ClientResult\<string\> |  |
| **GetLobSystemProperty(string lobSystemName, string propertyName)** | ClientResult\<string\> |  |
| **GetPermissibleConnections()** | ClientArrayResult\<string\> |  |
| **SetConnectionId(string lobSystemName, string lobSystemInstanceName, string connectionId)** | void |  |
| **SetLobSystemInstanceProperty(string lobSystemName, string lobSystemInstanceName, string propertyName, string propertyValue)** | void |  |
| **SetLobSystemProperty(string lobSystemName, string propertyName, string propertyValue)** | void |  |
# Entity Class

Namespace: Microsoft.BusinessData.MetadataModel

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **EstimatedInstanceCount** | long |  |
| **Name** | string |  |
| **Namespace** | string |  |
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
| **Entity(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Create(EntityFieldValueDictionary fieldValues, LobSystemInstance lobSystemInstance)** | [EntityIdentity](#entityidentity-class) |  |
| **Execute(string methodInstanceName, LobSystemInstance lobSystemInstance, Object[] inputParams)** | [MethodExecutionResult](#methodexecutionresult-class) |  |
| **FindAssociated(EntityInstance entityInstance, string associationName, FilterCollection filterList, LobSystemInstance lobSystemInstance)** | [EntityInstanceCollection](#entityinstancecollection-class) |  |
| **FindFiltered(FilterCollection filterList, string nameOfFinder, LobSystemInstance lobSystemInstance)** | [EntityInstanceCollection](#entityinstancecollection-class) |  |
| **FindSpecific(EntityIdentity identity, string specificFinderName, LobSystemInstance lobSystemInstance)** | [EntityInstance](#entityinstance-class) |  |
| **FindSpecificByBdcId(string bdcIdentity, string specificFinderName, LobSystemInstance lobSystemInstance)** | [EntityInstance](#entityinstance-class) |  |
| **FindSpecificDefault(EntityIdentity identity, LobSystemInstance lobSystemInstance)** | [EntityInstance](#entityinstance-class) |  |
| **FindSpecificDefaultByBdcId(string bdcIdentity, LobSystemInstance lobSystemInstance)** | [EntityInstance](#entityinstance-class) |  |
| **GetAssociationView(string associationName)** | [EntityView](#entityview-class) |  |
| **GetCreatorView(string methodInstanceName)** | [EntityView](#entityview-class) |  |
| **GetDefaultSpecificFinderView()** | [EntityView](#entityview-class) |  |
| **GetFilters(string methodInstanceName)** | [FilterCollection](#filtercollection-class) |  |
| **GetFinderView(string methodInstanceName)** | [EntityView](#entityview-class) |  |
| **GetIdentifierCount()** | ClientResult\<int\> |  |
| **GetIdentifiers()** | [EntityIdentifierCollection](#entityidentifiercollection-class) |  |
| **GetLobSystem()** | [LobSystem](#lobsystem-class) |  |
| **GetSpecificFinderView(string specificFinderName)** | [EntityView](#entityview-class) |  |
| **GetUpdaterView(string updaterName)** | [EntityView](#entityview-class) |  |
| **Subscribe(EntityEventType eventType, NotificationCallback notificationCallback, string onBehalfOfUser, string subscriberName, LobSystemInstance lobSystemInstance)** | [Subscription](#subscription-class) |  |
| **Unsubscribe(Subscription subscription, string onBehalfOfUser, string unsubscriberName, LobSystemInstance lobSystemInstance)** | void |  |
# EntityField Class

Namespace: Microsoft.BusinessData.MetadataModel

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ContainsLocalizedDisplayName** | bool |  |
| **DefaultDisplayName** | string |  |
| **LocalizedDisplayName** | string |  |
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
| **EntityField(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# EntityFieldPropertyNames Class

Namespace: Microsoft.BusinessData.MetadataModel


## Fields

| Name | Type | Summary |
|---|---|---|
| **ContainsLocalizedDisplayName** | string |  |
| **DefaultDisplayName** | string |  |
| **LocalizedDisplayName** | string |  |
| **Name** | string |  |
# EntityIdentifier Class

Namespace: Microsoft.BusinessData.MetadataModel

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **IdentifierType** | string |  |
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
| **EntityIdentifier(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **ContainsLocalizedDisplayName()** | ClientResult\<bool\> |  |
| **GetDefaultDisplayName()** | ClientResult\<string\> |  |
| **GetLocalizedDisplayName()** | ClientResult\<string\> |  |
# EntityIdentifierPropertyNames Class

Namespace: Microsoft.BusinessData.MetadataModel


## Fields

| Name | Type | Summary |
|---|---|---|
| **IdentifierType** | string |  |
| **Name** | string |  |
# EntityPropertyNames Class

Namespace: Microsoft.BusinessData.MetadataModel


## Fields

| Name | Type | Summary |
|---|---|---|
| **EstimatedInstanceCount** | string |  |
| **Name** | string |  |
| **Namespace** | string |  |
# EntityView Class

Namespace: Microsoft.BusinessData.MetadataModel

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Fields** | [EntityFieldCollection](#entityfieldcollection-class) |  |
| **Name** | string |  |
| **RelatedSpecificFinderName** | string |  |
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
| **EntityView(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetDefaultValues()** | [EntityFieldValueDictionary](#entityfieldvaluedictionary-class) |  |
| **GetType(string fieldDotNotation)** | ClientResult\<string\> |  |
| **GetTypeDescriptor(string fieldDotNotation)** | [TypeDescriptor](#typedescriptor-class) |  |
| **GetXmlSchema()** | ClientResult\<string\> |  |
# EntityViewObjectPropertyNames Class

Namespace: Microsoft.BusinessData.MetadataModel


## Fields

| Name | Type | Summary |
|---|---|---|
| **Fields** | string |  |
# EntityViewPropertyNames Class

Namespace: Microsoft.BusinessData.MetadataModel


## Fields

| Name | Type | Summary |
|---|---|---|
| **Name** | string |  |
| **RelatedSpecificFinderName** | string |  |
# Filter Class

Namespace: Microsoft.BusinessData.MetadataModel

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **DefaultDisplayName** | string |  |
| **FilterField** | string |  |
| **FilterType** | string |  |
| **LocalizedDisplayName** | string |  |
| **Name** | string |  |
| **ValueCount** | int |  |
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
| **Filter(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# FilterPropertyNames Class

Namespace: Microsoft.BusinessData.MetadataModel


## Fields

| Name | Type | Summary |
|---|---|---|
| **DefaultDisplayName** | string |  |
| **FilterField** | string |  |
| **FilterType** | string |  |
| **LocalizedDisplayName** | string |  |
| **Name** | string |  |
| **ValueCount** | string |  |
# LobSystem Class

Namespace: Microsoft.BusinessData.MetadataModel

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
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
| **LobSystem(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetLobSystemInstances()** | [LobSystemInstanceCollection](#lobsysteminstancecollection-class) |  |
# LobSystemInstance Class

Namespace: Microsoft.BusinessData.MetadataModel

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
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
| **LobSystemInstance(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# LobSystemInstancePropertyNames Class

Namespace: Microsoft.BusinessData.MetadataModel


## Fields

| Name | Type | Summary |
|---|---|---|
| **Name** | string |  |
# LobSystemPropertyNames Class

Namespace: Microsoft.BusinessData.MetadataModel


## Fields

| Name | Type | Summary |
|---|---|---|
| **Name** | string |  |
# MethodExecutionResult Class

Namespace: Microsoft.BusinessData.MetadataModel

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ReturnParameterCollection** | [ReturnParameterCollection](#returnparametercollection-class) |  |
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
| **MethodExecutionResult(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# MethodExecutionResultObjectPropertyNames Class

Namespace: Microsoft.BusinessData.MetadataModel


## Fields

| Name | Type | Summary |
|---|---|---|
| **ReturnParameterCollection** | string |  |
# ReturnParameterCollection Class

Namespace: Microsoft.BusinessData.MetadataModel

Base class: ClientObjectCollection<[EntityFieldValueDictionary](#entityfieldvaluedictionary-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [EntityFieldValueDictionary](#entityfieldvaluedictionary-class) |  |
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
| **ReturnParameterCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# TypeDescriptor Class

Namespace: Microsoft.BusinessData.MetadataModel

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ContainsReadOnly** | bool |  |
| **IsCollection** | bool |  |
| **IsReadOnly** | bool |  |
| **Name** | string |  |
| **TypeName** | string |  |
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
| **TypeDescriptor(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **ContainsLocalizedDisplayName()** | ClientResult\<bool\> |  |
| **GetChildTypeDescriptors()** | [TypeDescriptorCollection](#typedescriptorcollection-class) |  |
| **GetDefaultDisplayName()** | ClientResult\<string\> |  |
| **GetLocalizedDisplayName()** | ClientResult\<string\> |  |
| **GetParentTypeDescriptor()** | [TypeDescriptor](#typedescriptor-class) |  |
| **IsLeaf()** | ClientResult\<bool\> |  |
| **IsRoot()** | ClientResult\<bool\> |  |
# TypeDescriptorPropertyNames Class

Namespace: Microsoft.BusinessData.MetadataModel


## Fields

| Name | Type | Summary |
|---|---|---|
| **ContainsReadOnly** | string |  |
| **IsCollection** | string |  |
| **IsReadOnly** | string |  |
| **Name** | string |  |
| **TypeName** | string |  |
# EntityFieldCollection Class

Namespace: Microsoft.BusinessData.MetadataModel.Collections

Base class: ClientObjectCollection<[EntityField](#entityfield-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [EntityField](#entityfield-class) |  |
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
| **EntityFieldCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# EntityIdentifierCollection Class

Namespace: Microsoft.BusinessData.MetadataModel.Collections

Base class: ClientObjectCollection<[EntityIdentifier](#entityidentifier-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [EntityIdentifier](#entityidentifier-class) |  |
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
| **EntityIdentifierCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# EntityInstanceCollection Class

Namespace: Microsoft.BusinessData.MetadataModel.Collections

Base class: ClientObjectCollection<[EntityInstance](#entityinstance-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [EntityInstance](#entityinstance-class) |  |
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
| **EntityInstanceCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# FilterCollection Class

Namespace: Microsoft.BusinessData.MetadataModel.Collections

Base class: ClientObjectCollection<[Filter](#filter-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [Filter](#filter-class) |  |
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
| **FilterCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **SetFilterValue(string inputFilterName, int valueIndex, Object value)** | void |  |
# LobSystemInstanceCollection Class

Namespace: Microsoft.BusinessData.MetadataModel.Collections

Base class: ClientObjectCollection<[LobSystemInstance](#lobsysteminstance-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [LobSystemInstance](#lobsysteminstance-class) |  |
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
| **LobSystemInstanceCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# TypeDescriptorCollection Class

Namespace: Microsoft.BusinessData.MetadataModel.Collections

Base class: ClientObjectCollection<[TypeDescriptor](#typedescriptor-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [TypeDescriptor](#typedescriptor-class) |  |
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
| **TypeDescriptorCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# EntityEventType Enum

Namespace: Microsoft.BusinessData.Runtime


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **ItemAdded** |  |
| **ItemUpdated** |  |
| **ItemDeleted** |  |
# EntityFieldValueDictionary Class

Namespace: Microsoft.BusinessData.Runtime

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **FieldValues** | Dictionary\<string, Object\> |  |
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
| **EntityFieldValueDictionary(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **CreateCollectionInstance(string fieldDotNotation, int size)** | void |  |
| **CreateInstance(string fieldInstanceDotNotation, string fieldDotNotation)** | void |  |
| **FromXml(string xml)** | void |  |
| **GetCollectionSize(string fieldDotNotation)** | ClientResult\<int\> |  |
| **RefreshLoad()** | void |  |
| **ToXml()** | ClientResult\<string\> |  |
# EntityIdentity Class

Namespace: Microsoft.BusinessData.Runtime

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **FieldValues** | Dictionary\<string, Object\> |  |
| **Item** | Object |  |
| **IdentifierCount** | int |  |
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
| **EntityIdentity(ClientRuntimeContext context, Object[] identifierValues)** |  |
| **EntityIdentity(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **RefreshLoad()** | void |  |
# EntityIdentityPropertyNames Class

Namespace: Microsoft.BusinessData.Runtime


## Fields

| Name | Type | Summary |
|---|---|---|
| **IdentifierCount** | string |  |
# EntityInstance Class

Namespace: Microsoft.BusinessData.Runtime

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **FieldValues** | Dictionary\<string, Object\> |  |
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
| **EntityInstance(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **CreateCollectionInstance(string fieldDotNotation, int size)** | void |  |
| **CreateInstance(string fieldInstanceDotNotation, string fieldDotNotation)** | void |  |
| **DeleteObject()** | void |  |
| **FromXml(string xml)** | void |  |
| **GetIdentity()** | [EntityIdentity](#entityidentity-class) |  |
| **RefreshLoad()** | void |  |
| **ToXml()** | ClientResult\<string\> |  |
| **Update()** | void |  |
# NotificationCallback Class

Namespace: Microsoft.BusinessData.Runtime

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **NotificationContext** | string |  |
| **NotificationEndpoint** | string |  |
| **NotificationForwarderType** | string |  |
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
| **NotificationCallback(ClientRuntimeContext context, string notificationEndpoint)** |  |
| **NotificationCallback(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# NotificationCallbackPropertyNames Class

Namespace: Microsoft.BusinessData.Runtime


## Fields

| Name | Type | Summary |
|---|---|---|
| **NotificationContext** | string |  |
| **NotificationEndpoint** | string |  |
| **NotificationForwarderType** | string |  |
# Subscription Class

Namespace: Microsoft.BusinessData.Runtime

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Hash** | string |  |
| **ID** | IDictionary\<string, Object\> |  |
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
| **Subscription(ClientRuntimeContext context, ObjectPath objectPath)** |  |
| **Subscription(ClientRuntimeContext context, IDictionary\<string, Object\> id, string hash)** |  |
# SubscriptionPropertyNames Class

Namespace: Microsoft.BusinessData.Runtime


## Fields

| Name | Type | Summary |
|---|---|---|
| **Hash** | string |  |
| **ID** | string |  |
# ClientPeoplePickerQueryParameters Class

Namespace: Microsoft.SharePoint.ApplicationPages.ClientPickerQuery

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AllowEmailAddresses** | bool |  |
| **AllowMultipleEntities** | bool |  |
| **AllowOnlyEmailAddresses** | bool |  |
| **AllUrlZones** | bool |  |
| **EnabledClaimProviders** | string |  |
| **ForceClaims** | bool |  |
| **MaximumEntitySuggestions** | int |  |
| **PrincipalSource** | [PrincipalSource](#principalsource-enum) |  |
| **PrincipalType** | [PrincipalType](#principaltype-enum) |  |
| **QueryString** | string |  |
| **Required** | bool |  |
| **SharePointGroupID** | int |  |
| **UrlZone** | [UrlZone](#urlzone-enum) |  |
| **UrlZoneSpecified** | bool |  |
| **Web** | [Web](#web-class) |  |
| **WebApplicationID** | Guid |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# ClientPeoplePickerWebServiceInterface Class

Namespace: Microsoft.SharePoint.ApplicationPages.ClientPickerQuery


## Methods

| Name | Returns | Summary |
|---|---|---|
| **ClientPeoplePickerResolveUser(ClientRuntimeContext context, ClientPeoplePickerQueryParameters queryParams)** | ClientResult\<string\> |  |
| **ClientPeoplePickerSearchUser(ClientRuntimeContext context, ClientPeoplePickerQueryParameters queryParams)** | ClientResult\<string\> |  |
# AccessRequests Class

Namespace: Microsoft.SharePoint.Client


## Methods

| Name | Returns | Summary |
|---|---|---|
| **ChangeRequestStatus(ClientRuntimeContext context, int itemId, int newStatus, string convStr, string permType, int permissionLevel)** | void |  |
| **ChangeRequestStatusBulk(ClientRuntimeContext context, IList\<int\> requestIds, int newStatus)** | void |  |
| **UpdateConversation(ClientRuntimeContext context, int itemId, string convStr, Web web)** | void |  |
# AddFieldOptions Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **DefaultValue** |  |
| **AddToDefaultContentType** |  |
| **AddToNoContentType** |  |
| **AddToAllContentTypes** |  |
| **AddFieldInternalNameHint** |  |
| **AddFieldToDefaultView** |  |
| **AddFieldCheckDisplayName** |  |
# AlternateUrl Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Uri** | string |  |
| **UrlZone** | [UrlZone](#urlzone-enum) |  |
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
| **AlternateUrl(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# AlternateUrlPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Uri** | string |  |
| **UrlZone** | string |  |
# App Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AssetId** | string |  |
| **ContentMarket** | string |  |
| **VersionString** | string |  |
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
| **App(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# AppCatalog Class

Namespace: Microsoft.SharePoint.Client


## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetAppDetails(ClientRuntimeContext context, Web web, AppInstance appInstance)** | [AppDetails](#appdetails-class) |  |
| **GetAppInstance(ClientRuntimeContext context, Web web, Guid appInstanceId)** | [AppInstance](#appinstance-class) |  |
| **GetAppInstances(ClientRuntimeContext context, Web web)** | ClientObjectList\<[AppInstance](#appinstance-class)\> |  |
| **GetAppPermissionDescriptions(ClientRuntimeContext context, Web web, AppInstance appInstance)** | ClientArrayResult\<string\> |  |
| **GetDeveloperSiteAppInstancesByIds(ClientRuntimeContext context, Site site, Guid[] appInstanceIds)** | ClientObjectList\<[AppInstance](#appinstance-class)\> |  |
| **IsAppSideloadingEnabled(ClientRuntimeContext context)** | ClientResult\<bool\> |  |
# AppInstance Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AppPrincipalId** | string |  |
| **AppWebFullUrl** | string |  |
| **Id** | Guid |  |
| **ImageFallbackUrl** | string |  |
| **ImageUrl** | string |  |
| **InError** | bool |  |
| **StartPage** | string |  |
| **PackageFingerprint** | byte[] |  |
| **ProductId** | Guid |  |
| **RemoteAppUrl** | string |  |
| **SettingsPageUrl** | string |  |
| **SiteId** | Guid |  |
| **Status** | [AppInstanceStatus](#appinstancestatus-enum) |  |
| **Title** | string |  |
| **WebId** | Guid |  |
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
| **AppInstance(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **CancelAllJobs()** | ClientResult\<bool\> |  |
| **GetAppIcon(ClientRuntimeContext context, Web hostWeb, Guid appinstanceId, byte[] packageFingerprint)** | [AppIconInfo](#appiconinfo-class) |  |
| **GetErrorDetails()** | ClientObjectList\<[AppInstanceErrorDetails](#appinstanceerrordetails-class)\> |  |
| **GetPreviousAppVersion()** | [App](#app-class) |  |
| **Install()** | ClientResult\<Guid\> |  |
| **Recycle()** | ClientResult\<Guid\> |  |
| **Restore()** | ClientResult\<Guid\> |  |
| **RetrieveAppDatabaseConnectionString(ClientRuntimeContext context)** | ClientResult\<string\> |  |
| **RetryAllJobs()** | void |  |
| **TryGetAppDatabaseConnectionDirect(ClientRuntimeContext context, out SqlConnection connection, out bool isReadOnly)** | bool |  |
| **TryGetAppDatabaseConnectionDirect(ClientRuntimeContext context, SqlConnectionStringBuilder template, out SqlConnection connection, out bool isReadOnly)** | bool |  |
| **Uninstall()** | ClientResult\<Guid\> |  |
| **Upgrade(Stream appPackageStream)** | void |  |
# AppInstanceErrorDetails Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **CorrelationId** | Guid |  |
| **ErrorDetail** | string |  |
| **ErrorType** | [AppInstanceErrorType](#appinstanceerrortype-enum) |  |
| **ErrorTypeName** | string |  |
| **ExceptionMessage** | string |  |
| **Source** | [AppInstanceErrorSource](#appinstanceerrorsource-enum) |  |
| **SourceName** | string |  |
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
| **AppInstanceErrorDetails(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# AppInstanceErrorDetailsPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **CorrelationId** | string |  |
| **ErrorDetail** | string |  |
| **ErrorType** | string |  |
| **ErrorTypeName** | string |  |
| **ExceptionMessage** | string |  |
| **Source** | string |  |
| **SourceName** | string |  |
# AppInstanceErrorSource Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Common** |  |
| **AppWeb** |  |
| **ParentWeb** |  |
| **RemoteWebSite** |  |
| **Database** |  |
| **OfficeExtension** |  |
| **EventCallouts** |  |
| **Finalization** |  |
# AppInstanceErrorType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Transient** |  |
| **Configuration** |  |
| **App** |  |
# AppInstancePropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **AppPrincipalId** | string |  |
| **AppWebFullUrl** | string |  |
| **Id** | string |  |
| **ImageFallbackUrl** | string |  |
| **ImageUrl** | string |  |
| **InError** | string |  |
| **StartPage** | string |  |
| **PackageFingerprint** | string |  |
| **ProductId** | string |  |
| **RemoteAppUrl** | string |  |
| **SettingsPageUrl** | string |  |
| **SiteId** | string |  |
| **Status** | string |  |
| **Title** | string |  |
| **WebId** | string |  |
# AppInstanceStatus Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **InvalidStatus** |  |
| **Installing** |  |
| **Uninstalling** |  |
| **Installed** |  |
| **Canceling** |  |
| **Upgrading** |  |
| **Initialized** |  |
| **UpgradeCanceling** |  |
| **Disabling** |  |
| **Disabled** |  |
| **SecretRolling** |  |
| **Recycling** |  |
| **Recycled** |  |
| **Restoring** |  |
| **RestoreCanceling** |  |
# AppLicense Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **RawXMLLicenseToken** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# AppLicenseCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObjectCollection<[AppLicense](#applicense-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **TypeId** | string |  |
| **ChildItemsName** | string |  |
| **Count** | int |  |
| **Item** | [AppLicense](#applicense-class) |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# AppLicenseType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **PerpetualMultiUser** |  |
| **PerpetualAllUsers** |  |
| **TrialMultiUser** |  |
| **TrialAllUsers** |  |
# AppPrincipal Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **DisplayName** | string |  |
| **EndpointAuthorities** | IEnumerable\<string\> |  |
| **NameIdentifier** | string |  |
| **RedirectAddresses** | IEnumerable\<string\> |  |
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
| **AppPrincipal(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# AppPrincipalConfiguration Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ApplicationEndpointAuthorities** | IList\<string\> |  |
| **ApplicationPrincipalNames** | IList\<string\> |  |
| **NameIdentifier** | string |  |
| **RedirectAddresses** | IList\<string\> |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# AppPrincipalCredential Class

Namespace: Microsoft.SharePoint.Client

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
| **AppPrincipalCredential(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **CreateFromKeyGroup(ClientRuntimeContext context, Guid keyGroupIdentifier)** | [AppPrincipalCredential](#appprincipalcredential-class) |  |
| **CreateFromSymmetricKey(ClientRuntimeContext context, string symmetricKey, DateTime notBefore, DateTime notAfter)** | [AppPrincipalCredential](#appprincipalcredential-class) |  |
# AppPrincipalCredentialReference Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Id** | Guid |  |
| **NameIdentifier** | string |  |
| **NotAfter** | DateTime |  |
| **NotBefore** | DateTime |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# AppPrincipalIdentityProvider Class

Namespace: Microsoft.SharePoint.Client

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
| **AppPrincipalIdentityProvider(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetExternal(ClientRuntimeContext Context)** | [AppPrincipalIdentityProvider](#appprincipalidentityprovider-class) |  |
# AppPrincipalManager Class

Namespace: Microsoft.SharePoint.Client

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
| **AppPrincipalManager(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **AddAppPrincipalCredential(AppPrincipal appPrincipal, AppPrincipalCredential credential)** | void |  |
| **CreateAppPrincipal(ExternalAppPrincipalCreationParameters parameters)** | [AppPrincipal](#appprincipal-class) |  |
| **DeleteAppPrincipal(AppPrincipal appPrincipal)** | void |  |
| **DeleteAppPrincipalCredential(AppPrincipalCredentialReference credentialReference)** | void |  |
| **GetAppPrincipalConfiguration(AppPrincipal appPrincipal)** | ClientResult\<[AppPrincipalConfiguration](#appprincipalconfiguration-class)\> |  |
| **GetAppPrincipalCredentials(AppPrincipal appPrincipal)** | IEnumerable\<[AppPrincipalCredentialReference](#appprincipalcredentialreference-class)\> |  |
| **GetManager(ClientRuntimeContext context, Web web)** | [AppPrincipalManager](#appprincipalmanager-class) |  |
| **LookupAppPrincipal(AppPrincipalIdentityProvider identityProvider, AppPrincipalName appPrincipalName)** | [AppPrincipal](#appprincipal-class) |  |
| **SetAppPrincipalConfiguration(AppPrincipalConfiguration appPrincipalConfiguration)** | void |  |
# AppPrincipalName Class

Namespace: Microsoft.SharePoint.Client

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
| **AppPrincipalName(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **CreateFromAppPrincipalIdentifier(ClientRuntimeContext context, string appPrincipalIdentifier)** | [AppPrincipalName](#appprincipalname-class) |  |
| **CreateFromNameIdentifier(ClientRuntimeContext context, string nameIdentifier)** | [AppPrincipalName](#appprincipalname-class) |  |
# AppPrincipalPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **DisplayName** | string |  |
| **EndpointAuthorities** | string |  |
| **NameIdentifier** | string |  |
| **RedirectAddresses** | string |  |
# AppPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **AssetId** | string |  |
| **ContentMarket** | string |  |
| **VersionString** | string |  |
# AppSiteContext Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **SiteUrl** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# AppSiteContextUtility Class

Namespace: Microsoft.SharePoint.Client


## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetAppSiteContextCollection(ClientRuntimeContext context)** | IList\<[AppSiteContext](#appsitecontext-class)\> |  |
# AppTile Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AppType** | [AppType](#apptype-enum) |  |
| **ChildCount** | int |  |
| **LastModified** | string |  |
| **Target** | string |  |
| **Thumbnail** | string |  |
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
| **AppTile(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# AppTileCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObjectCollection<[AppTile](#apptile-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [AppTile](#apptile-class) |  |
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
| **AppTileCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# AppTilePropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **AppType** | string |  |
| **ChildCount** | string |  |
| **LastModified** | string |  |
| **Target** | string |  |
| **Thumbnail** | string |  |
| **Title** | string |  |
# AppType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Doclib** |  |
| **List** |  |
| **Tenant** |  |
| **Instance** |  |
| **Feature** |  |
| **CommonList** |  |
# Attachment Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **FileName** | string |  |
| **ServerRelativeUrl** | string |  |
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
| **Attachment(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
# AttachmentCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObjectCollection<[Attachment](#attachment-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [Attachment](#attachment-class) |  |
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
| **AttachmentCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(AttachmentCreationInformation parameters)** | [Attachment](#attachment-class) |  |
| **GetByFileName(string fileName)** | [Attachment](#attachment-class) |  |
# AttachmentCreationInformation Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ContentStream** | Stream |  |
| **FileName** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# AttachmentPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **FileName** | string |  |
| **ServerRelativeUrl** | string |  |
# Audit Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AuditFlags** | [AuditMaskType](#auditmasktype-enum) |  |
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
| **Audit(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Update()** | void |  |
# AuditMaskType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **CheckOut** |  |
| **CheckIn** |  |
| **View** |  |
| **ObjectDelete** |  |
| **Update** |  |
| **ProfileChange** |  |
| **ChildDelete** |  |
| **SchemaChange** |  |
| **SecurityChange** |  |
| **Undelete** |  |
| **Workflow** |  |
| **Copy** |  |
| **Move** |  |
| **Search** |  |
| **All** |  |
# AuditPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **AuditFlags** | string |  |
# BasePermissions Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **High** | uint |  |
| **Low** | uint |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Clear(PermissionKind perm)** | void |  |
| **ClearAll()** | void |  |
| **Equals(Object obj)** | bool |  |
| **GetHashCode()** | int |  |
| **Has(PermissionKind perm)** | bool |  |
| **HasPermissions(uint high, uint low)** | bool |  |
| **Set(PermissionKind perm)** | void |  |
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# BaseType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **GenericList** |  |
| **DocumentLibrary** |  |
| **Unused** |  |
| **DiscussionBoard** |  |
| **Survey** |  |
| **Issue** |  |
| **None** |  |
# BrowserFileHandling Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Permissive** |  |
| **Strict** |  |
# CalendarType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **Gregorian** |  |
| **Japan** |  |
| **Taiwan** |  |
| **Korea** |  |
| **Hijri** |  |
| **Thai** |  |
| **Hebrew** |  |
| **GregorianMEFrench** |  |
| **GregorianArabic** |  |
| **GregorianXLITEnglish** |  |
| **GregorianXLITFrench** |  |
| **KoreaJapanLunar** |  |
| **ChineseLunar** |  |
| **SakaEra** |  |
| **UmAlQura** |  |
# CamlQuery Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **DatesInUtc** | bool |  |
| **FolderServerRelativeUrl** | string |  |
| **ListItemCollectionPosition** | [ListItemCollectionPosition](#listitemcollectionposition-class) |  |
| **ViewXml** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **CreateAllFoldersQuery()** | [CamlQuery](#camlquery-class) |  |
| **CreateAllItemsQuery()** | [CamlQuery](#camlquery-class) |  |
| **CreateAllItemsQuery(int rowLimit, string[] viewFields)** | [CamlQuery](#camlquery-class) |  |
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# Change Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ChangeToken** | [ChangeToken](#changetoken-class) |  |
| **ChangeType** | [ChangeType](#changetype-enum) |  |
| **SiteId** | Guid |  |
| **Time** | DateTime |  |
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
| **Change(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ChangeAlert Class

Namespace: Microsoft.SharePoint.Client

Base class: [Change](#change-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **AlertId** | Guid |  |
| **WebId** | Guid |  |
| **ChangeToken** | [ChangeToken](#changetoken-class) |  |
| **ChangeType** | [ChangeType](#changetype-enum) |  |
| **SiteId** | Guid |  |
| **Time** | DateTime |  |
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
| **ChangeAlert(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ChangeAlertPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **AlertId** | string |  |
| **WebId** | string |  |
# ChangeCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObjectCollection<[Change](#change-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [Change](#change-class) |  |
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
| **ChangeCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ChangeContentType Class

Namespace: Microsoft.SharePoint.Client

Base class: [Change](#change-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **ContentTypeId** | [ContentTypeId](#contenttypeid-class) |  |
| **WebId** | Guid |  |
| **ChangeToken** | [ChangeToken](#changetoken-class) |  |
| **ChangeType** | [ChangeType](#changetype-enum) |  |
| **SiteId** | Guid |  |
| **Time** | DateTime |  |
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
| **ChangeContentType(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ChangeContentTypePropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **ContentTypeId** | string |  |
| **WebId** | string |  |
# ChangeField Class

Namespace: Microsoft.SharePoint.Client

Base class: [Change](#change-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **FieldId** | Guid |  |
| **WebId** | Guid |  |
| **ChangeToken** | [ChangeToken](#changetoken-class) |  |
| **ChangeType** | [ChangeType](#changetype-enum) |  |
| **SiteId** | Guid |  |
| **Time** | DateTime |  |
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
| **ChangeField(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ChangeFieldPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **FieldId** | string |  |
| **WebId** | string |  |
# ChangeFile Class

Namespace: Microsoft.SharePoint.Client

Base class: [Change](#change-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **UniqueId** | Guid |  |
| **WebId** | Guid |  |
| **ChangeToken** | [ChangeToken](#changetoken-class) |  |
| **ChangeType** | [ChangeType](#changetype-enum) |  |
| **SiteId** | Guid |  |
| **Time** | DateTime |  |
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
| **ChangeFile(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ChangeFilePropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **UniqueId** | string |  |
| **WebId** | string |  |
# ChangeFolder Class

Namespace: Microsoft.SharePoint.Client

Base class: [Change](#change-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **UniqueId** | Guid |  |
| **WebId** | Guid |  |
| **ChangeToken** | [ChangeToken](#changetoken-class) |  |
| **ChangeType** | [ChangeType](#changetype-enum) |  |
| **SiteId** | Guid |  |
| **Time** | DateTime |  |
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
| **ChangeFolder(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ChangeFolderPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **UniqueId** | string |  |
| **WebId** | string |  |
# ChangeGroup Class

Namespace: Microsoft.SharePoint.Client

Base class: [Change](#change-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **GroupId** | int |  |
| **ChangeToken** | [ChangeToken](#changetoken-class) |  |
| **ChangeType** | [ChangeType](#changetype-enum) |  |
| **SiteId** | Guid |  |
| **Time** | DateTime |  |
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
| **ChangeGroup(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ChangeGroupPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **GroupId** | string |  |
# ChangeItem Class

Namespace: Microsoft.SharePoint.Client

Base class: [Change](#change-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **Editor** | string |  |
| **EditorEmailHint** | string |  |
| **ItemId** | int |  |
| **ListId** | Guid |  |
| **ServerRelativeUrl** | string |  |
| **SharedByUser** | [SharedWithUser](#sharedwithuser-class) |  |
| **SharedWithUsers** | [SharedWithUserCollection](#sharedwithusercollection-class) |  |
| **WebId** | Guid |  |
| **ChangeToken** | [ChangeToken](#changetoken-class) |  |
| **ChangeType** | [ChangeType](#changetype-enum) |  |
| **SiteId** | Guid |  |
| **Time** | DateTime |  |
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
| **ChangeItem(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ChangeItemPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Editor** | string |  |
| **EditorEmailHint** | string |  |
| **ItemId** | string |  |
| **ListId** | string |  |
| **ServerRelativeUrl** | string |  |
| **SharedByUser** | string |  |
| **SharedWithUsers** | string |  |
| **WebId** | string |  |
# ChangeList Class

Namespace: Microsoft.SharePoint.Client

Base class: [Change](#change-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **ListId** | Guid |  |
| **WebId** | Guid |  |
| **ChangeToken** | [ChangeToken](#changetoken-class) |  |
| **ChangeType** | [ChangeType](#changetype-enum) |  |
| **SiteId** | Guid |  |
| **Time** | DateTime |  |
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
| **ChangeList(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ChangeListPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **ListId** | string |  |
| **WebId** | string |  |
# ChangeLogItemQuery Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ChangeToken** | string |  |
| **Contains** | string |  |
| **Query** | string |  |
| **QueryOptions** | string |  |
| **RowLimit** | string |  |
| **ViewFields** | string |  |
| **ViewName** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# ChangePropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **ChangeToken** | string |  |
| **ChangeType** | string |  |
| **SiteId** | string |  |
| **Time** | string |  |
# ChangeQuery Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Add** | bool |  |
| **Alert** | bool |  |
| **ChangeTokenEnd** | [ChangeToken](#changetoken-class) |  |
| **ChangeTokenStart** | [ChangeToken](#changetoken-class) |  |
| **ContentType** | bool |  |
| **DeleteObject** | bool |  |
| **FetchLimit** | long |  |
| **Field** | bool |  |
| **File** | bool |  |
| **Folder** | bool |  |
| **Group** | bool |  |
| **GroupMembershipAdd** | bool |  |
| **GroupMembershipDelete** | bool |  |
| **Item** | bool |  |
| **LatestFirst** | bool |  |
| **List** | bool |  |
| **Move** | bool |  |
| **Navigation** | bool |  |
| **RecursiveAll** | bool |  |
| **Rename** | bool |  |
| **Restore** | bool |  |
| **RoleAssignmentAdd** | bool |  |
| **RoleAssignmentDelete** | bool |  |
| **RoleDefinitionAdd** | bool |  |
| **RoleDefinitionDelete** | bool |  |
| **RoleDefinitionUpdate** | bool |  |
| **SecurityPolicy** | bool |  |
| **Site** | bool |  |
| **SystemUpdate** | bool |  |
| **Update** | bool |  |
| **User** | bool |  |
| **View** | bool |  |
| **Web** | bool |  |
| **TypeId** | string |  |
## Constructors

| Name | Summary |
|---|---|
| **ChangeQuery(bool allChangeObjectTypes, bool allChangeTypes)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# ChangeSite Class

Namespace: Microsoft.SharePoint.Client

Base class: [Change](#change-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **ChangeToken** | [ChangeToken](#changetoken-class) |  |
| **ChangeType** | [ChangeType](#changetype-enum) |  |
| **SiteId** | Guid |  |
| **Time** | DateTime |  |
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
| **ChangeSite(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ChangeToken Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **StringValue** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# ChangeType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **NoChange** |  |
| **Add** |  |
| **Update** |  |
| **DeleteObject** |  |
| **Rename** |  |
| **MoveAway** |  |
| **MoveInto** |  |
| **Restore** |  |
| **RoleAdd** |  |
| **RoleDelete** |  |
| **RoleUpdate** |  |
| **AssignmentAdd** |  |
| **AssignmentDelete** |  |
| **MemberAdd** |  |
| **MemberDelete** |  |
| **SystemUpdate** |  |
| **Navigation** |  |
| **ScopeAdd** |  |
| **ScopeDelete** |  |
| **ListContentTypeAdd** |  |
| **ListContentTypeDelete** |  |
| **Dirty** |  |
# ChangeUser Class

Namespace: Microsoft.SharePoint.Client

Base class: [Change](#change-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **Activate** | bool |  |
| **UserId** | int |  |
| **ChangeToken** | [ChangeToken](#changetoken-class) |  |
| **ChangeType** | [ChangeType](#changetype-enum) |  |
| **SiteId** | Guid |  |
| **Time** | DateTime |  |
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
| **ChangeUser(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ChangeUserPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Activate** | string |  |
| **UserId** | string |  |
# ChangeView Class

Namespace: Microsoft.SharePoint.Client

Base class: [Change](#change-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **ViewId** | Guid |  |
| **ListId** | Guid |  |
| **WebId** | Guid |  |
| **ChangeToken** | [ChangeToken](#changetoken-class) |  |
| **ChangeType** | [ChangeType](#changetype-enum) |  |
| **SiteId** | Guid |  |
| **Time** | DateTime |  |
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
| **ChangeView(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ChangeViewPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **ViewId** | string |  |
| **ListId** | string |  |
| **WebId** | string |  |
# ChangeWeb Class

Namespace: Microsoft.SharePoint.Client

Base class: [Change](#change-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **WebId** | Guid |  |
| **ChangeToken** | [ChangeToken](#changetoken-class) |  |
| **ChangeType** | [ChangeType](#changetype-enum) |  |
| **SiteId** | Guid |  |
| **Time** | DateTime |  |
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
| **ChangeWeb(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ChangeWebPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **WebId** | string |  |
# CheckinType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **MinorCheckIn** |  |
| **MajorCheckIn** |  |
| **OverwriteCheckIn** |  |
# CheckOutType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Online** |  |
| **Offline** |  |
| **None** |  |
# ChoiceFormatType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Dropdown** |  |
| **RadioButtons** |  |
# ClientContext Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientRuntimeContext


## Properties

| Name | Type | Summary |
|---|---|---|
| **Web** | [Web](#web-class) |  |
| **Site** | [Site](#site-class) |  |
| **RequestResources** | [RequestResources](#requestresources-class) |  |
| **RequestResourceHeaderValue** | string |  |
| **FormDigestHandlingEnabled** | bool |  |
| **ServerVersion** | Version |  |
| **NamespaceManager** | XmlNamespaceManager |  |
| **ServiceRelativeUrl** | string |  |
| **Url** | string |  |
| **ApplicationName** | string |  |
| **ClientTag** | string |  |
| **DisableReturnValueCache** | bool |  |
| **ValidateOnClient** | bool |  |
| **AuthenticationMode** | ClientAuthenticationMode |  |
| **FormsAuthenticationLoginInfo** | FormsAuthenticationLoginInfo |  |
| **Credentials** | ICredentials |  |
| **WebRequestExecutorFactory** | WebRequestExecutorFactory |  |
| **PendingRequest** | ClientRequest |  |
| **HasPendingRequest** | bool |  |
| **ProcessingResponse** | bool |  |
| **Tag** | Object |  |
| **RequestTimeout** | int |  |
| **StaticObjects** | Dictionary\<string, Object\> |  |
| **ObjectPaths** | Dictionary\<long, ObjectPath\> |  |
| **QueryProvider** | ClientQueryProvider |  |
| **ServerSchemaVersion** | Version |  |
| **ServerLibraryVersion** | Version |  |
| **RequestSchemaVersion** | Version |  |
| **TraceCorrelationId** | string |  |
## Constructors

| Name | Summary |
|---|---|
| **ClientContext(string webFullUrl)** |  |
| **ClientContext(Uri webFullUrl)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **ExecuteQuery()** | void |  |
| **GetFormDigestDirect()** | [FormDigestInfo](#formdigestinfo-class) |  |
# CompatibilityRange Class

Namespace: Microsoft.SharePoint.Client

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
| **CompatibilityRange(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ContentType Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Description** | string |  |
| **DescriptionResource** | [UserResource](#userresource-class) |  |
| **DisplayFormTemplateName** | string |  |
| **DisplayFormUrl** | string |  |
| **DocumentTemplate** | string |  |
| **DocumentTemplateUrl** | string |  |
| **EditFormTemplateName** | string |  |
| **EditFormUrl** | string |  |
| **FieldLinks** | [FieldLinkCollection](#fieldlinkcollection-class) |  |
| **Fields** | [FieldCollection](#fieldcollection-class) |  |
| **Group** | string |  |
| **Hidden** | bool |  |
| **Id** | [ContentTypeId](#contenttypeid-class) |  |
| **JSLink** | string |  |
| **MobileDisplayFormUrl** | string |  |
| **MobileEditFormUrl** | string |  |
| **MobileNewFormUrl** | string |  |
| **Name** | string |  |
| **NameResource** | [UserResource](#userresource-class) |  |
| **NewFormTemplateName** | string |  |
| **NewFormUrl** | string |  |
| **Parent** | [ContentType](#contenttype-class) |  |
| **ReadOnly** | bool |  |
| **SchemaXml** | string |  |
| **SchemaXmlWithResourceTokens** | string |  |
| **Scope** | string |  |
| **Sealed** | bool |  |
| **StringId** | string |  |
| **WorkflowAssociations** | [WorkflowAssociationCollection](#workflowassociationcollection-class) |  |
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
| **ContentType(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
| **Update(bool updateChildren)** | void |  |
# ContentTypeCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObjectCollection<[ContentType](#contenttype-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [ContentType](#contenttype-class) |  |
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
| **ContentTypeCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(ContentTypeCreationInformation parameters)** | [ContentType](#contenttype-class) |  |
| **AddExistingContentType(ContentType contentType)** | [ContentType](#contenttype-class) |  |
| **GetById(string contentTypeId)** | [ContentType](#contenttype-class) |  |
# ContentTypeCreationInformation Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Description** | string |  |
| **Group** | string |  |
| **Id** | string |  |
| **Name** | string |  |
| **ParentContentType** | [ContentType](#contenttype-class) |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# ContentTypeId Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **StringValue** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **ToString()** | string |  |
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# ContentTypeObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **DescriptionResource** | string |  |
| **FieldLinks** | string |  |
| **Fields** | string |  |
| **NameResource** | string |  |
| **Parent** | string |  |
| **WorkflowAssociations** | string |  |
# ContentTypePropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Description** | string |  |
| **DisplayFormTemplateName** | string |  |
| **DisplayFormUrl** | string |  |
| **DocumentTemplate** | string |  |
| **DocumentTemplateUrl** | string |  |
| **EditFormTemplateName** | string |  |
| **EditFormUrl** | string |  |
| **Group** | string |  |
| **Hidden** | string |  |
| **Id** | string |  |
| **JSLink** | string |  |
| **MobileDisplayFormUrl** | string |  |
| **MobileEditFormUrl** | string |  |
| **MobileNewFormUrl** | string |  |
| **Name** | string |  |
| **NewFormTemplateName** | string |  |
| **NewFormUrl** | string |  |
| **ReadOnly** | string |  |
| **SchemaXml** | string |  |
| **SchemaXmlWithResourceTokens** | string |  |
| **Scope** | string |  |
| **Sealed** | string |  |
| **StringId** | string |  |
# CreatableItemInfo Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **DocumentTemplate** | int |  |
| **FileExtension** | string |  |
| **ItemType** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# CreatableItemInfoCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObjectCollection<[CreatableItemInfo](#creatableiteminfo-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **TypeId** | string |  |
| **ChildItemsName** | string |  |
| **Count** | int |  |
| **Item** | [CreatableItemInfo](#creatableiteminfo-class) |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# CreatablesInfo Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **CanCreateFolders** | bool |  |
| **CanCreateItems** | bool |  |
| **CanUploadFiles** | bool |  |
| **CreatablesCollection** | [CreatableItemInfoCollection](#creatableiteminfocollection-class) |  |
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
| **CreatablesInfo(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# CreatablesInfoPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **CanCreateFolders** | string |  |
| **CanCreateItems** | string |  |
| **CanUploadFiles** | string |  |
| **CreatablesCollection** | string |  |
# CustomActionElement Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **CommandUIExtension** | string |  |
| **EnabledScript** | string |  |
| **ImageUrl** | string |  |
| **Location** | string |  |
| **RegistrationId** | string |  |
| **RegistrationType** | [UserCustomActionRegistrationType](#usercustomactionregistrationtype-enum) |  |
| **RequireSiteAdministrator** | bool |  |
| **Rights** | [BasePermissions](#basepermissions-class) |  |
| **Title** | string |  |
| **UrlAction** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# CustomActionElementCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObjectCollection<[CustomActionElement](#customactionelement-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **TypeId** | string |  |
| **ChildItemsName** | string |  |
| **Count** | int |  |
| **Item** | [CustomActionElement](#customactionelement-class) |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# CustomizedPageStatus Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **Uncustomized** |  |
| **Customized** |  |
# DateTimeFieldFormatType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **DateOnly** |  |
| **DateTime** |  |
# DateTimeFieldFriendlyFormatType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Unspecified** |  |
| **Disabled** |  |
| **Relative** |  |
# DlpPolicyTip Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AppliedActionsText** | string |  |
| **ComplianceUrl** | string |  |
| **GeneralText** | string |  |
| **LastProcessedTime** | DateTime |  |
| **MatchedConditionDescriptions** | IEnumerable\<string\> |  |
| **OverrideOptions** | [RuleOverrideOptions](#ruleoverrideoptions-enum) |  |
| **TwoLetterISOLanguageName** | string |  |
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
| **DlpPolicyTip(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# DlpPolicyTipPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **AppliedActionsText** | string |  |
| **ComplianceUrl** | string |  |
| **GeneralText** | string |  |
| **LastProcessedTime** | string |  |
| **MatchedConditionDescriptions** | string |  |
| **OverrideOptions** | string |  |
| **TwoLetterISOLanguageName** | string |  |
# DocumentLibraryInformation Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Modified** | DateTime |  |
| **ModifiedFriendlyDisplay** | string |  |
| **ServerRelativeUrl** | string |  |
| **Title** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# DocumentTemplateType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Invalid** |  |
| **Word** |  |
| **Excel** |  |
| **PowerPoint** |  |
| **OneNote** |  |
| **ExcelForm** |  |
| **Max** |  |
# DraftVisibilityType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Reader** |  |
| **Author** |  |
| **Approver** |  |
# EffectiveInformationRightsManagementSettings Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AllowPrint** | bool |  |
| **AllowScript** | bool |  |
| **AllowWriteCopy** | bool |  |
| **DisableDocumentBrowserView** | bool |  |
| **DocumentAccessExpireDays** | int |  |
| **DocumentLibraryProtectionExpireDate** | DateTime |  |
| **EnableDocumentAccessExpire** | bool |  |
| **EnableDocumentBrowserPublishingView** | bool |  |
| **EnableGroupProtection** | bool |  |
| **EnableLicenseCacheExpire** | bool |  |
| **GroupName** | string |  |
| **IrmEnabled** | bool |  |
| **LicenseCacheExpireDays** | int |  |
| **PolicyDescription** | string |  |
| **PolicyTitle** | string |  |
| **SettingSource** | [SPEffectiveInformationRightsManagementSettingsSource](#speffectiveinformationrightsmanagementsettingssource-enum) |  |
| **TemplateId** | string |  |
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
| **EffectiveInformationRightsManagementSettings(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# EffectiveInformationRightsManagementSettingsPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **AllowPrint** | string |  |
| **AllowScript** | string |  |
| **AllowWriteCopy** | string |  |
| **DisableDocumentBrowserView** | string |  |
| **DocumentAccessExpireDays** | string |  |
| **DocumentLibraryProtectionExpireDate** | string |  |
| **EnableDocumentAccessExpire** | string |  |
| **EnableDocumentBrowserPublishingView** | string |  |
| **EnableGroupProtection** | string |  |
| **EnableLicenseCacheExpire** | string |  |
| **GroupName** | string |  |
| **IrmEnabled** | string |  |
| **LicenseCacheExpireDays** | string |  |
| **PolicyDescription** | string |  |
| **PolicyTitle** | string |  |
| **SettingSource** | string |  |
| **TemplateId** | string |  |
# EncryptionOption Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AES256CBCKey** | byte[] |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# EventReceiverDefinition Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ReceiverAssembly** | string |  |
| **ReceiverClass** | string |  |
| **ReceiverId** | Guid |  |
| **ReceiverName** | string |  |
| **SequenceNumber** | int |  |
| **Synchronization** | [EventReceiverSynchronization](#eventreceiversynchronization-enum) |  |
| **EventType** | [EventReceiverType](#eventreceivertype-enum) |  |
| **ReceiverUrl** | string |  |
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
| **EventReceiverDefinition(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
| **Update()** | void |  |
# EventReceiverDefinitionCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObjectCollection<[EventReceiverDefinition](#eventreceiverdefinition-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [EventReceiverDefinition](#eventreceiverdefinition-class) |  |
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
| **EventReceiverDefinitionCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(EventReceiverDefinitionCreationInformation eventReceiverCreationInformation)** | [EventReceiverDefinition](#eventreceiverdefinition-class) |  |
| **GetById(Guid eventReceiverId)** | [EventReceiverDefinition](#eventreceiverdefinition-class) |  |
# EventReceiverDefinitionCreationInformation Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ReceiverAssembly** | string |  |
| **ReceiverClass** | string |  |
| **ReceiverName** | string |  |
| **SequenceNumber** | int |  |
| **Synchronization** | [EventReceiverSynchronization](#eventreceiversynchronization-enum) |  |
| **EventType** | [EventReceiverType](#eventreceivertype-enum) |  |
| **ReceiverUrl** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# EventReceiverDefinitionPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **ReceiverAssembly** | string |  |
| **ReceiverClass** | string |  |
| **ReceiverId** | string |  |
| **ReceiverName** | string |  |
| **SequenceNumber** | string |  |
| **Synchronization** | string |  |
| **EventType** | string |  |
| **ReceiverUrl** | string |  |
# EventReceiverSynchronization Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **DefaultSynchronization** |  |
| **Synchronous** |  |
| **Asynchronous** |  |
# EventReceiverType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **ItemAdding** |  |
| **ItemUpdating** |  |
| **ItemDeleting** |  |
| **ItemCheckingIn** |  |
| **ItemCheckingOut** |  |
| **ItemUncheckingOut** |  |
| **ItemAttachmentAdding** |  |
| **ItemAttachmentDeleting** |  |
| **ItemFileMoving** |  |
| **ItemVersionDeleting** |  |
| **FieldAdding** |  |
| **FieldUpdating** |  |
| **FieldDeleting** |  |
| **ListAdding** |  |
| **ListDeleting** |  |
| **SiteDeleting** |  |
| **WebDeleting** |  |
| **WebMoving** |  |
| **WebAdding** |  |
| **GroupAdding** |  |
| **GroupUpdating** |  |
| **GroupDeleting** |  |
| **GroupUserAdding** |  |
| **GroupUserDeleting** |  |
| **RoleDefinitionAdding** |  |
| **RoleDefinitionUpdating** |  |
| **RoleDefinitionDeleting** |  |
| **RoleAssignmentAdding** |  |
| **RoleAssignmentDeleting** |  |
| **InheritanceBreaking** |  |
| **InheritanceResetting** |  |
| **WorkflowStarting** |  |
| **ItemAdded** |  |
| **ItemUpdated** |  |
| **ItemDeleted** |  |
| **ItemCheckedIn** |  |
| **ItemCheckedOut** |  |
| **ItemUncheckedOut** |  |
| **ItemAttachmentAdded** |  |
| **ItemAttachmentDeleted** |  |
| **ItemFileMoved** |  |
| **ItemFileConverted** |  |
| **ItemVersionDeleted** |  |
| **FieldAdded** |  |
| **FieldUpdated** |  |
| **FieldDeleted** |  |
| **ListAdded** |  |
| **ListDeleted** |  |
| **SiteDeleted** |  |
| **WebDeleted** |  |
| **WebMoved** |  |
| **WebProvisioned** |  |
| **WebRestored** |  |
| **GroupAdded** |  |
| **GroupUpdated** |  |
| **GroupDeleted** |  |
| **GroupUserAdded** |  |
| **GroupUserDeleted** |  |
| **RoleDefinitionAdded** |  |
| **RoleDefinitionUpdated** |  |
| **RoleDefinitionDeleted** |  |
| **RoleAssignmentAdded** |  |
| **RoleAssignmentDeleted** |  |
| **InheritanceBroken** |  |
| **InheritanceReset** |  |
| **WorkflowStarted** |  |
| **WorkflowPostponed** |  |
| **WorkflowCompleted** |  |
| **EntityInstanceAdded** |  |
| **EntityInstanceUpdated** |  |
| **EntityInstanceDeleted** |  |
| **AppInstalled** |  |
| **AppUpgraded** |  |
| **AppUninstalling** |  |
| **EmailReceived** |  |
| **ContextEvent** |  |
| **InvalidReceiver** |  |
# ExternalApplicationRequestToken Class

Namespace: Microsoft.SharePoint.Client


## Properties

| Name | Type | Summary |
|---|---|---|
| **Version** | int |  |
| **SiteId** | Guid |  |
| **UserId** | int |  |
| **ApplicationId** | Guid |  |
| **ApplicationPrincipalLogOnName** | string |  |
| **DateTime** | DateTime |  |
| **ClientHash** | byte[] |  |
| **ServerHash** | byte[] |  |
| **TokenPrefix** | string |  |
| **TokenString** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **ToString()** | string |  |
| **TryParse(string str)** | [ExternalApplicationRequestToken](#externalapplicationrequesttoken-class) |  |
# ExternalAppPrincipalCreationParameters Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AppIdentifier** | string |  |
| **ApplicationEndpointAuthorities** | IList\<string\> |  |
| **Credential** | [AppPrincipalCredential](#appprincipalcredential-class) |  |
| **DisplayName** | string |  |
| **RedirectAddresses** | IList\<string\> |  |
| **TrustedForDelegation** | bool |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# Feature Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **DefinitionId** | Guid |  |
| **DisplayName** | string |  |
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
| **Feature(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# FeatureCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObjectCollection<[Feature](#feature-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [Feature](#feature-class) |  |
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
| **FeatureCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(Guid featureId, bool force, FeatureDefinitionScope featdefScope)** | [Feature](#feature-class) |  |
| **GetById(Guid featureId)** | [Feature](#feature-class) |  |
| **Remove(Guid featureId, bool force)** | void |  |
# FeatureDefinitionScope Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **Farm** |  |
| **Site** |  |
| **Web** |  |
# FeaturePropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **DefinitionId** | string |  |
| **DisplayName** | string |  |
# Field Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AutoIndexed** | bool |  |
| **CanBeDeleted** | bool |  |
| **DefaultValue** | string |  |
| **Description** | string |  |
| **DescriptionResource** | [UserResource](#userresource-class) |  |
| **Direction** | string |  |
| **EnforceUniqueValues** | bool |  |
| **EntityPropertyName** | string |  |
| **Filterable** | bool |  |
| **FromBaseType** | bool |  |
| **Group** | string |  |
| **Hidden** | bool |  |
| **Id** | Guid |  |
| **Indexed** | bool |  |
| **InternalName** | string |  |
| **JSLink** | string |  |
| **ReadOnlyField** | bool |  |
| **Required** | bool |  |
| **SchemaXml** | string |  |
| **SchemaXmlWithResourceTokens** | string |  |
| **Scope** | string |  |
| **Sealed** | bool |  |
| **Sortable** | bool |  |
| **StaticName** | string |  |
| **Title** | string |  |
| **TitleResource** | [UserResource](#userresource-class) |  |
| **FieldTypeKind** | [FieldType](#fieldtype-enum) |  |
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
| **Field(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
| **SetShowInDisplayForm(bool value)** | void |  |
| **SetShowInEditForm(bool value)** | void |  |
| **SetShowInNewForm(bool value)** | void |  |
| **Update()** | void |  |
| **UpdateAndPushChanges(bool pushChangesToLists)** | void |  |
| **ValidateSetValue(ListItem item, string value)** | void |  |
# FieldCalculated Class

Namespace: Microsoft.SharePoint.Client

Base class: [Field](#field-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **DateFormat** | [DateTimeFieldFormatType](#datetimefieldformattype-enum) |  |
| **Formula** | string |  |
| **OutputType** | [FieldType](#fieldtype-enum) |  |
| **AutoIndexed** | bool |  |
| **CanBeDeleted** | bool |  |
| **DefaultValue** | string |  |
| **Description** | string |  |
| **DescriptionResource** | [UserResource](#userresource-class) |  |
| **Direction** | string |  |
| **EnforceUniqueValues** | bool |  |
| **EntityPropertyName** | string |  |
| **Filterable** | bool |  |
| **FromBaseType** | bool |  |
| **Group** | string |  |
| **Hidden** | bool |  |
| **Id** | Guid |  |
| **Indexed** | bool |  |
| **InternalName** | string |  |
| **JSLink** | string |  |
| **ReadOnlyField** | bool |  |
| **Required** | bool |  |
| **SchemaXml** | string |  |
| **SchemaXmlWithResourceTokens** | string |  |
| **Scope** | string |  |
| **Sealed** | bool |  |
| **Sortable** | bool |  |
| **StaticName** | string |  |
| **Title** | string |  |
| **TitleResource** | [UserResource](#userresource-class) |  |
| **FieldTypeKind** | [FieldType](#fieldtype-enum) |  |
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
| **FieldCalculated(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# FieldCalculatedErrorValue Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ErrorMessage** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# FieldCalculatedPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **DateFormat** | string |  |
| **Formula** | string |  |
| **OutputType** | string |  |
# FieldChoice Class

Namespace: Microsoft.SharePoint.Client

Base class: [FieldMultiChoice](#fieldmultichoice-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **EditFormat** | [ChoiceFormatType](#choiceformattype-enum) |  |
| **FillInChoice** | bool |  |
| **Mappings** | string |  |
| **Choices** | string[] |  |
| **AutoIndexed** | bool |  |
| **CanBeDeleted** | bool |  |
| **DefaultValue** | string |  |
| **Description** | string |  |
| **DescriptionResource** | [UserResource](#userresource-class) |  |
| **Direction** | string |  |
| **EnforceUniqueValues** | bool |  |
| **EntityPropertyName** | string |  |
| **Filterable** | bool |  |
| **FromBaseType** | bool |  |
| **Group** | string |  |
| **Hidden** | bool |  |
| **Id** | Guid |  |
| **Indexed** | bool |  |
| **InternalName** | string |  |
| **JSLink** | string |  |
| **ReadOnlyField** | bool |  |
| **Required** | bool |  |
| **SchemaXml** | string |  |
| **SchemaXmlWithResourceTokens** | string |  |
| **Scope** | string |  |
| **Sealed** | bool |  |
| **Sortable** | bool |  |
| **StaticName** | string |  |
| **Title** | string |  |
| **TitleResource** | [UserResource](#userresource-class) |  |
| **FieldTypeKind** | [FieldType](#fieldtype-enum) |  |
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
| **FieldChoice(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# FieldChoicePropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **EditFormat** | string |  |
# FieldCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObjectCollection<[Field](#field-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **SchemaXml** | string |  |
| **Item** | [Field](#field-class) |  |
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
| **FieldCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(Field field)** | [Field](#field-class) |  |
| **AddDependentLookup(string displayName, Field primaryLookupField, string lookupField)** | [Field](#field-class) |  |
| **AddFieldAsXml(string schemaXml, bool addToDefaultView, AddFieldOptions options)** | [Field](#field-class) |  |
| **GetById(Guid id)** | [Field](#field-class) |  |
| **GetByInternalNameOrTitle(string strName)** | [Field](#field-class) |  |
| **GetByTitle(string title)** | [Field](#field-class) |  |
# FieldCollectionPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **SchemaXml** | string |  |
# FieldComputed Class

Namespace: Microsoft.SharePoint.Client

Base class: [Field](#field-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **EnableLookup** | bool |  |
| **AutoIndexed** | bool |  |
| **CanBeDeleted** | bool |  |
| **DefaultValue** | string |  |
| **Description** | string |  |
| **DescriptionResource** | [UserResource](#userresource-class) |  |
| **Direction** | string |  |
| **EnforceUniqueValues** | bool |  |
| **EntityPropertyName** | string |  |
| **Filterable** | bool |  |
| **FromBaseType** | bool |  |
| **Group** | string |  |
| **Hidden** | bool |  |
| **Id** | Guid |  |
| **Indexed** | bool |  |
| **InternalName** | string |  |
| **JSLink** | string |  |
| **ReadOnlyField** | bool |  |
| **Required** | bool |  |
| **SchemaXml** | string |  |
| **SchemaXmlWithResourceTokens** | string |  |
| **Scope** | string |  |
| **Sealed** | bool |  |
| **Sortable** | bool |  |
| **StaticName** | string |  |
| **Title** | string |  |
| **TitleResource** | [UserResource](#userresource-class) |  |
| **FieldTypeKind** | [FieldType](#fieldtype-enum) |  |
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
| **FieldComputed(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# FieldComputedPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **EnableLookup** | string |  |
# FieldCurrency Class

Namespace: Microsoft.SharePoint.Client

Base class: [FieldNumber](#fieldnumber-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **CurrencyLocaleId** | int |  |
| **MaximumValue** | double |  |
| **MinimumValue** | double |  |
| **AutoIndexed** | bool |  |
| **CanBeDeleted** | bool |  |
| **DefaultValue** | string |  |
| **Description** | string |  |
| **DescriptionResource** | [UserResource](#userresource-class) |  |
| **Direction** | string |  |
| **EnforceUniqueValues** | bool |  |
| **EntityPropertyName** | string |  |
| **Filterable** | bool |  |
| **FromBaseType** | bool |  |
| **Group** | string |  |
| **Hidden** | bool |  |
| **Id** | Guid |  |
| **Indexed** | bool |  |
| **InternalName** | string |  |
| **JSLink** | string |  |
| **ReadOnlyField** | bool |  |
| **Required** | bool |  |
| **SchemaXml** | string |  |
| **SchemaXmlWithResourceTokens** | string |  |
| **Scope** | string |  |
| **Sealed** | bool |  |
| **Sortable** | bool |  |
| **StaticName** | string |  |
| **Title** | string |  |
| **TitleResource** | [UserResource](#userresource-class) |  |
| **FieldTypeKind** | [FieldType](#fieldtype-enum) |  |
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
| **FieldCurrency(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# FieldCurrencyPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **CurrencyLocaleId** | string |  |
# FieldDateTime Class

Namespace: Microsoft.SharePoint.Client

Base class: [Field](#field-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **DateTimeCalendarType** | [CalendarType](#calendartype-enum) |  |
| **DisplayFormat** | [DateTimeFieldFormatType](#datetimefieldformattype-enum) |  |
| **FriendlyDisplayFormat** | [DateTimeFieldFriendlyFormatType](#datetimefieldfriendlyformattype-enum) |  |
| **AutoIndexed** | bool |  |
| **CanBeDeleted** | bool |  |
| **DefaultValue** | string |  |
| **Description** | string |  |
| **DescriptionResource** | [UserResource](#userresource-class) |  |
| **Direction** | string |  |
| **EnforceUniqueValues** | bool |  |
| **EntityPropertyName** | string |  |
| **Filterable** | bool |  |
| **FromBaseType** | bool |  |
| **Group** | string |  |
| **Hidden** | bool |  |
| **Id** | Guid |  |
| **Indexed** | bool |  |
| **InternalName** | string |  |
| **JSLink** | string |  |
| **ReadOnlyField** | bool |  |
| **Required** | bool |  |
| **SchemaXml** | string |  |
| **SchemaXmlWithResourceTokens** | string |  |
| **Scope** | string |  |
| **Sealed** | bool |  |
| **Sortable** | bool |  |
| **StaticName** | string |  |
| **Title** | string |  |
| **TitleResource** | [UserResource](#userresource-class) |  |
| **FieldTypeKind** | [FieldType](#fieldtype-enum) |  |
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
| **FieldDateTime(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# FieldDateTimePropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **DateTimeCalendarType** | string |  |
| **DisplayFormat** | string |  |
| **FriendlyDisplayFormat** | string |  |
# FieldGeolocation Class

Namespace: Microsoft.SharePoint.Client

Base class: [Field](#field-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **AutoIndexed** | bool |  |
| **CanBeDeleted** | bool |  |
| **DefaultValue** | string |  |
| **Description** | string |  |
| **DescriptionResource** | [UserResource](#userresource-class) |  |
| **Direction** | string |  |
| **EnforceUniqueValues** | bool |  |
| **EntityPropertyName** | string |  |
| **Filterable** | bool |  |
| **FromBaseType** | bool |  |
| **Group** | string |  |
| **Hidden** | bool |  |
| **Id** | Guid |  |
| **Indexed** | bool |  |
| **InternalName** | string |  |
| **JSLink** | string |  |
| **ReadOnlyField** | bool |  |
| **Required** | bool |  |
| **SchemaXml** | string |  |
| **SchemaXmlWithResourceTokens** | string |  |
| **Scope** | string |  |
| **Sealed** | bool |  |
| **Sortable** | bool |  |
| **StaticName** | string |  |
| **Title** | string |  |
| **TitleResource** | [UserResource](#userresource-class) |  |
| **FieldTypeKind** | [FieldType](#fieldtype-enum) |  |
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
| **FieldGeolocation(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# FieldGeolocationValue Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Altitude** | double |  |
| **Latitude** | double |  |
| **Longitude** | double |  |
| **Measure** | double |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# FieldGuid Class

Namespace: Microsoft.SharePoint.Client

Base class: [Field](#field-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **AutoIndexed** | bool |  |
| **CanBeDeleted** | bool |  |
| **DefaultValue** | string |  |
| **Description** | string |  |
| **DescriptionResource** | [UserResource](#userresource-class) |  |
| **Direction** | string |  |
| **EnforceUniqueValues** | bool |  |
| **EntityPropertyName** | string |  |
| **Filterable** | bool |  |
| **FromBaseType** | bool |  |
| **Group** | string |  |
| **Hidden** | bool |  |
| **Id** | Guid |  |
| **Indexed** | bool |  |
| **InternalName** | string |  |
| **JSLink** | string |  |
| **ReadOnlyField** | bool |  |
| **Required** | bool |  |
| **SchemaXml** | string |  |
| **SchemaXmlWithResourceTokens** | string |  |
| **Scope** | string |  |
| **Sealed** | bool |  |
| **Sortable** | bool |  |
| **StaticName** | string |  |
| **Title** | string |  |
| **TitleResource** | [UserResource](#userresource-class) |  |
| **FieldTypeKind** | [FieldType](#fieldtype-enum) |  |
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
| **FieldGuid(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# FieldLink Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Hidden** | bool |  |
| **Id** | Guid |  |
| **Name** | string |  |
| **Required** | bool |  |
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
| **FieldLink(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
# FieldLinkCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObjectCollection<[FieldLink](#fieldlink-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [FieldLink](#fieldlink-class) |  |
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
| **FieldLinkCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(FieldLinkCreationInformation parameters)** | [FieldLink](#fieldlink-class) |  |
| **GetById(Guid id)** | [FieldLink](#fieldlink-class) |  |
| **Reorder(string[] internalNames)** | void |  |
# FieldLinkCreationInformation Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Field** | [Field](#field-class) |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# FieldLinkPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Hidden** | string |  |
| **Id** | string |  |
| **Name** | string |  |
| **Required** | string |  |
# FieldLookup Class

Namespace: Microsoft.SharePoint.Client

Base class: [Field](#field-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **AllowMultipleValues** | bool |  |
| **IsRelationship** | bool |  |
| **LookupField** | string |  |
| **LookupList** | string |  |
| **LookupWebId** | Guid |  |
| **PrimaryFieldId** | string |  |
| **RelationshipDeleteBehavior** | [RelationshipDeleteBehaviorType](#relationshipdeletebehaviortype-enum) |  |
| **AutoIndexed** | bool |  |
| **CanBeDeleted** | bool |  |
| **DefaultValue** | string |  |
| **Description** | string |  |
| **DescriptionResource** | [UserResource](#userresource-class) |  |
| **Direction** | string |  |
| **EnforceUniqueValues** | bool |  |
| **EntityPropertyName** | string |  |
| **Filterable** | bool |  |
| **FromBaseType** | bool |  |
| **Group** | string |  |
| **Hidden** | bool |  |
| **Id** | Guid |  |
| **Indexed** | bool |  |
| **InternalName** | string |  |
| **JSLink** | string |  |
| **ReadOnlyField** | bool |  |
| **Required** | bool |  |
| **SchemaXml** | string |  |
| **SchemaXmlWithResourceTokens** | string |  |
| **Scope** | string |  |
| **Sealed** | bool |  |
| **Sortable** | bool |  |
| **StaticName** | string |  |
| **Title** | string |  |
| **TitleResource** | [UserResource](#userresource-class) |  |
| **FieldTypeKind** | [FieldType](#fieldtype-enum) |  |
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
| **FieldLookup(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# FieldLookupPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **AllowMultipleValues** | string |  |
| **IsRelationship** | string |  |
| **LookupField** | string |  |
| **LookupList** | string |  |
| **LookupWebId** | string |  |
| **PrimaryFieldId** | string |  |
| **RelationshipDeleteBehavior** | string |  |
# FieldLookupValue Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **LookupId** | int |  |
| **LookupValue** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# FieldMultiChoice Class

Namespace: Microsoft.SharePoint.Client

Base class: [Field](#field-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **FillInChoice** | bool |  |
| **Mappings** | string |  |
| **Choices** | string[] |  |
| **AutoIndexed** | bool |  |
| **CanBeDeleted** | bool |  |
| **DefaultValue** | string |  |
| **Description** | string |  |
| **DescriptionResource** | [UserResource](#userresource-class) |  |
| **Direction** | string |  |
| **EnforceUniqueValues** | bool |  |
| **EntityPropertyName** | string |  |
| **Filterable** | bool |  |
| **FromBaseType** | bool |  |
| **Group** | string |  |
| **Hidden** | bool |  |
| **Id** | Guid |  |
| **Indexed** | bool |  |
| **InternalName** | string |  |
| **JSLink** | string |  |
| **ReadOnlyField** | bool |  |
| **Required** | bool |  |
| **SchemaXml** | string |  |
| **SchemaXmlWithResourceTokens** | string |  |
| **Scope** | string |  |
| **Sealed** | bool |  |
| **Sortable** | bool |  |
| **StaticName** | string |  |
| **Title** | string |  |
| **TitleResource** | [UserResource](#userresource-class) |  |
| **FieldTypeKind** | [FieldType](#fieldtype-enum) |  |
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
| **FieldMultiChoice(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# FieldMultiChoicePropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **FillInChoice** | string |  |
| **Mappings** | string |  |
| **Choices** | string |  |
# FieldMultiLineText Class

Namespace: Microsoft.SharePoint.Client

Base class: [Field](#field-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **AllowHyperlink** | bool |  |
| **AppendOnly** | bool |  |
| **NumberOfLines** | int |  |
| **RestrictedMode** | bool |  |
| **RichText** | bool |  |
| **WikiLinking** | bool |  |
| **AutoIndexed** | bool |  |
| **CanBeDeleted** | bool |  |
| **DefaultValue** | string |  |
| **Description** | string |  |
| **DescriptionResource** | [UserResource](#userresource-class) |  |
| **Direction** | string |  |
| **EnforceUniqueValues** | bool |  |
| **EntityPropertyName** | string |  |
| **Filterable** | bool |  |
| **FromBaseType** | bool |  |
| **Group** | string |  |
| **Hidden** | bool |  |
| **Id** | Guid |  |
| **Indexed** | bool |  |
| **InternalName** | string |  |
| **JSLink** | string |  |
| **ReadOnlyField** | bool |  |
| **Required** | bool |  |
| **SchemaXml** | string |  |
| **SchemaXmlWithResourceTokens** | string |  |
| **Scope** | string |  |
| **Sealed** | bool |  |
| **Sortable** | bool |  |
| **StaticName** | string |  |
| **Title** | string |  |
| **TitleResource** | [UserResource](#userresource-class) |  |
| **FieldTypeKind** | [FieldType](#fieldtype-enum) |  |
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
| **FieldMultiLineText(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# FieldMultiLineTextPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **AllowHyperlink** | string |  |
| **AppendOnly** | string |  |
| **NumberOfLines** | string |  |
| **RestrictedMode** | string |  |
| **RichText** | string |  |
| **WikiLinking** | string |  |
# FieldNumber Class

Namespace: Microsoft.SharePoint.Client

Base class: [Field](#field-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **MaximumValue** | double |  |
| **MinimumValue** | double |  |
| **AutoIndexed** | bool |  |
| **CanBeDeleted** | bool |  |
| **DefaultValue** | string |  |
| **Description** | string |  |
| **DescriptionResource** | [UserResource](#userresource-class) |  |
| **Direction** | string |  |
| **EnforceUniqueValues** | bool |  |
| **EntityPropertyName** | string |  |
| **Filterable** | bool |  |
| **FromBaseType** | bool |  |
| **Group** | string |  |
| **Hidden** | bool |  |
| **Id** | Guid |  |
| **Indexed** | bool |  |
| **InternalName** | string |  |
| **JSLink** | string |  |
| **ReadOnlyField** | bool |  |
| **Required** | bool |  |
| **SchemaXml** | string |  |
| **SchemaXmlWithResourceTokens** | string |  |
| **Scope** | string |  |
| **Sealed** | bool |  |
| **Sortable** | bool |  |
| **StaticName** | string |  |
| **Title** | string |  |
| **TitleResource** | [UserResource](#userresource-class) |  |
| **FieldTypeKind** | [FieldType](#fieldtype-enum) |  |
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
| **FieldNumber(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# FieldNumberPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **MaximumValue** | string |  |
| **MinimumValue** | string |  |
# FieldObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **DescriptionResource** | string |  |
| **TitleResource** | string |  |
# FieldPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **AutoIndexed** | string |  |
| **CanBeDeleted** | string |  |
| **DefaultValue** | string |  |
| **Description** | string |  |
| **Direction** | string |  |
| **EnforceUniqueValues** | string |  |
| **EntityPropertyName** | string |  |
| **Filterable** | string |  |
| **FromBaseType** | string |  |
| **Group** | string |  |
| **Hidden** | string |  |
| **Id** | string |  |
| **Indexed** | string |  |
| **InternalName** | string |  |
| **JSLink** | string |  |
| **ReadOnlyField** | string |  |
| **Required** | string |  |
| **SchemaXml** | string |  |
| **SchemaXmlWithResourceTokens** | string |  |
| **Scope** | string |  |
| **Sealed** | string |  |
| **Sortable** | string |  |
| **StaticName** | string |  |
| **Title** | string |  |
| **FieldTypeKind** | string |  |
| **TypeAsString** | string |  |
| **TypeDisplayName** | string |  |
| **TypeShortDescription** | string |  |
| **ValidationFormula** | string |  |
| **ValidationMessage** | string |  |
# FieldRatingScale Class

Namespace: Microsoft.SharePoint.Client

Base class: [FieldMultiChoice](#fieldmultichoice-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **GridEndNumber** | int |  |
| **GridNAOptionText** | string |  |
| **GridStartNumber** | int |  |
| **GridTextRangeAverage** | string |  |
| **GridTextRangeHigh** | string |  |
| **GridTextRangeLow** | string |  |
| **RangeCount** | int |  |
| **FillInChoice** | bool |  |
| **Mappings** | string |  |
| **Choices** | string[] |  |
| **AutoIndexed** | bool |  |
| **CanBeDeleted** | bool |  |
| **DefaultValue** | string |  |
| **Description** | string |  |
| **DescriptionResource** | [UserResource](#userresource-class) |  |
| **Direction** | string |  |
| **EnforceUniqueValues** | bool |  |
| **EntityPropertyName** | string |  |
| **Filterable** | bool |  |
| **FromBaseType** | bool |  |
| **Group** | string |  |
| **Hidden** | bool |  |
| **Id** | Guid |  |
| **Indexed** | bool |  |
| **InternalName** | string |  |
| **JSLink** | string |  |
| **ReadOnlyField** | bool |  |
| **Required** | bool |  |
| **SchemaXml** | string |  |
| **SchemaXmlWithResourceTokens** | string |  |
| **Scope** | string |  |
| **Sealed** | bool |  |
| **Sortable** | bool |  |
| **StaticName** | string |  |
| **Title** | string |  |
| **TitleResource** | [UserResource](#userresource-class) |  |
| **FieldTypeKind** | [FieldType](#fieldtype-enum) |  |
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
| **FieldRatingScale(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# FieldRatingScalePropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **GridEndNumber** | string |  |
| **GridNAOptionText** | string |  |
| **GridStartNumber** | string |  |
| **GridTextRangeAverage** | string |  |
| **GridTextRangeHigh** | string |  |
| **GridTextRangeLow** | string |  |
| **RangeCount** | string |  |
# FieldRatingScaleQuestionAnswer Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Answer** | int |  |
| **Question** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# FieldStringValues Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **FieldValues** | Dictionary\<string, string\> |  |
| **Item** | string |  |
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
| **FieldStringValues(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **RefreshLoad()** | void |  |
# FieldText Class

Namespace: Microsoft.SharePoint.Client

Base class: [Field](#field-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **MaxLength** | int |  |
| **AutoIndexed** | bool |  |
| **CanBeDeleted** | bool |  |
| **DefaultValue** | string |  |
| **Description** | string |  |
| **DescriptionResource** | [UserResource](#userresource-class) |  |
| **Direction** | string |  |
| **EnforceUniqueValues** | bool |  |
| **EntityPropertyName** | string |  |
| **Filterable** | bool |  |
| **FromBaseType** | bool |  |
| **Group** | string |  |
| **Hidden** | bool |  |
| **Id** | Guid |  |
| **Indexed** | bool |  |
| **InternalName** | string |  |
| **JSLink** | string |  |
| **ReadOnlyField** | bool |  |
| **Required** | bool |  |
| **SchemaXml** | string |  |
| **SchemaXmlWithResourceTokens** | string |  |
| **Scope** | string |  |
| **Sealed** | bool |  |
| **Sortable** | bool |  |
| **StaticName** | string |  |
| **Title** | string |  |
| **TitleResource** | [UserResource](#userresource-class) |  |
| **FieldTypeKind** | [FieldType](#fieldtype-enum) |  |
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
| **FieldText(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# FieldTextPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **MaxLength** | string |  |
# FieldType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Invalid** |  |
| **Integer** |  |
| **Text** |  |
| **Note** |  |
| **DateTime** |  |
| **Counter** |  |
| **Choice** |  |
| **Lookup** |  |
| **Boolean** |  |
| **Number** |  |
| **Currency** |  |
| **URL** |  |
| **Computed** |  |
| **Threading** |  |
| **Guid** |  |
| **MultiChoice** |  |
| **GridChoice** |  |
| **Calculated** |  |
| **File** |  |
| **Attachments** |  |
| **User** |  |
| **Recurrence** |  |
| **CrossProjectLink** |  |
| **ModStat** |  |
| **Error** |  |
| **ContentTypeId** |  |
| **PageSeparator** |  |
| **ThreadIndex** |  |
| **WorkflowStatus** |  |
| **AllDayEvent** |  |
| **WorkflowEventType** |  |
| **Geolocation** |  |
| **OutcomeChoice** |  |
| **MaxItems** |  |
# FieldUrl Class

Namespace: Microsoft.SharePoint.Client

Base class: [Field](#field-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **DisplayFormat** | [UrlFieldFormatType](#urlfieldformattype-enum) |  |
| **AutoIndexed** | bool |  |
| **CanBeDeleted** | bool |  |
| **DefaultValue** | string |  |
| **Description** | string |  |
| **DescriptionResource** | [UserResource](#userresource-class) |  |
| **Direction** | string |  |
| **EnforceUniqueValues** | bool |  |
| **EntityPropertyName** | string |  |
| **Filterable** | bool |  |
| **FromBaseType** | bool |  |
| **Group** | string |  |
| **Hidden** | bool |  |
| **Id** | Guid |  |
| **Indexed** | bool |  |
| **InternalName** | string |  |
| **JSLink** | string |  |
| **ReadOnlyField** | bool |  |
| **Required** | bool |  |
| **SchemaXml** | string |  |
| **SchemaXmlWithResourceTokens** | string |  |
| **Scope** | string |  |
| **Sealed** | bool |  |
| **Sortable** | bool |  |
| **StaticName** | string |  |
| **Title** | string |  |
| **TitleResource** | [UserResource](#userresource-class) |  |
| **FieldTypeKind** | [FieldType](#fieldtype-enum) |  |
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
| **FieldUrl(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# FieldUrlPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **DisplayFormat** | string |  |
# FieldUrlValue Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Description** | string |  |
| **Url** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# FieldUser Class

Namespace: Microsoft.SharePoint.Client

Base class: [FieldLookup](#fieldlookup-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **AllowDisplay** | bool |  |
| **Presence** | bool |  |
| **SelectionGroup** | int |  |
| **SelectionMode** | [FieldUserSelectionMode](#fielduserselectionmode-enum) |  |
| **AllowMultipleValues** | bool |  |
| **IsRelationship** | bool |  |
| **LookupField** | string |  |
| **LookupList** | string |  |
| **LookupWebId** | Guid |  |
| **PrimaryFieldId** | string |  |
| **RelationshipDeleteBehavior** | [RelationshipDeleteBehaviorType](#relationshipdeletebehaviortype-enum) |  |
| **AutoIndexed** | bool |  |
| **CanBeDeleted** | bool |  |
| **DefaultValue** | string |  |
| **Description** | string |  |
| **DescriptionResource** | [UserResource](#userresource-class) |  |
| **Direction** | string |  |
| **EnforceUniqueValues** | bool |  |
| **EntityPropertyName** | string |  |
| **Filterable** | bool |  |
| **FromBaseType** | bool |  |
| **Group** | string |  |
| **Hidden** | bool |  |
| **Id** | Guid |  |
| **Indexed** | bool |  |
| **InternalName** | string |  |
| **JSLink** | string |  |
| **ReadOnlyField** | bool |  |
| **Required** | bool |  |
| **SchemaXml** | string |  |
| **SchemaXmlWithResourceTokens** | string |  |
| **Scope** | string |  |
| **Sealed** | bool |  |
| **Sortable** | bool |  |
| **StaticName** | string |  |
| **Title** | string |  |
| **TitleResource** | [UserResource](#userresource-class) |  |
| **FieldTypeKind** | [FieldType](#fieldtype-enum) |  |
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
| **FieldUser(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# FieldUserPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **AllowDisplay** | string |  |
| **Presence** | string |  |
| **SelectionGroup** | string |  |
| **SelectionMode** | string |  |
# FieldUserSelectionMode Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **PeopleOnly** |  |
| **PeopleAndGroups** |  |
# FieldUserValue Class

Namespace: Microsoft.SharePoint.Client

Base class: [FieldLookupValue](#fieldlookupvalue-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **Email** | string |  |
| **TypeId** | string |  |
| **LookupId** | int |  |
| **LookupValue** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **FromUser(string userName)** | [FieldUserValue](#fielduservalue-class) |  |
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# File Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Author** | [User](#user-class) |  |
| **CheckedOutByUser** | [User](#user-class) |  |
| **CheckInComment** | string |  |
| **CheckOutType** | [CheckOutType](#checkouttype-enum) |  |
| **ContentTag** | string |  |
| **CustomizedPageStatus** | [CustomizedPageStatus](#customizedpagestatus-enum) |  |
| **ListId** | Guid |  |
| **EffectiveInformationRightsManagementSettings** | [EffectiveInformationRightsManagementSettings](#effectiveinformationrightsmanagementsettings-class) |  |
| **ETag** | string |  |
| **Exists** | bool |  |
| **InformationRightsManagementSettings** | [InformationRightsManagementFileSettings](#informationrightsmanagementfilesettings-class) |  |
| **IrmEnabled** | bool |  |
| **Length** | long |  |
| **Level** | [FileLevel](#filelevel-enum) |  |
| **LinkingUrl** | string |  |
| **ListItemAllFields** | [ListItem](#listitem-class) |  |
| **LockedByUser** | [User](#user-class) |  |
| **MajorVersion** | int |  |
| **MinorVersion** | int |  |
| **ModifiedBy** | [User](#user-class) |  |
| **Name** | string |  |
| **Properties** | [PropertyValues](#propertyvalues-class) |  |
| **ServerRelativeUrl** | string |  |
| **SiteId** | Guid |  |
| **TimeCreated** | DateTime |  |
| **TimeLastModified** | DateTime |  |
| **Title** | string |  |
| **UIVersion** | int |  |
| **UIVersionLabel** | string |  |
| **UniqueId** | Guid |  |
| **VersionEvents** | [FileVersionEventCollection](#fileversioneventcollection-class) |  |
| **Versions** | [FileVersionCollection](#fileversioncollection-class) |  |
| **WebId** | Guid |  |
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
| **File(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Approve(string comment)** | void |  |
| **CancelUpload(Guid uploadId)** | void |  |
| **CheckIn(string comment, CheckinType checkInType)** | void |  |
| **CheckOut()** | void |  |
| **ContinueUpload(Guid uploadId, long fileOffset, Stream stream)** | ClientResult\<long\> |  |
| **CopyTo(string strNewUrl, bool bOverWrite)** | void |  |
| **DeleteObject()** | void |  |
| **Deny(string comment)** | void |  |
| **ExecuteCobaltRequest(Stream inputStream)** | ClientResult\<Stream\> |  |
| **FinishUpload(Guid uploadId, long fileOffset, Stream stream)** | [File](#file-class) |  |
| **GetContentVerFromTag(ClientRuntimeContext context, string contentTag)** | ClientResult\<int\> |  |
| **GetImagePreviewUrl(int width, int height, string clientType)** | ClientResult\<string\> |  |
| **GetLimitedWebPartManager(PersonalizationScope scope)** | [LimitedWebPartManager](#limitedwebpartmanager-class) |  |
| **GetPreAuthorizedAccessUrl(int expirationHours)** | ClientResult\<string\> |  |
| **GetWOPIFrameUrl(SPWOPIFrameAction action)** | ClientResult\<string\> |  |
| **MoveTo(string newUrl, MoveOperations flags)** | void |  |
| **OpenBinaryDirect(ClientContext context, string serverRelativeUrl)** | [FileInformation](#fileinformation-class) |  |
| **OpenBinaryStream()** | ClientResult\<Stream\> |  |
| **Publish(string comment)** | void |  |
| **Recycle()** | ClientResult\<Guid\> |  |
| **SaveBinary(FileSaveBinaryInformation parameters)** | void |  |
| **SaveBinaryDirect(ClientContext context, string serverRelativeUrl, Stream stream, bool overwriteIfExists)** | void |  |
| **SaveBinaryDirect(ClientContext context, string serverRelativeUrl, Stream stream, string etag)** | void |  |
| **StartUpload(Guid uploadId, Stream stream)** | ClientResult\<long\> |  |
| **UndoCheckOut()** | void |  |
| **UnPublish(string comment)** | void |  |
| **Update()** | void |  |
# FileCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObjectCollection<[File](#file-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [File](#file-class) |  |
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
| **FileCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(FileCreationInformation parameters)** | [File](#file-class) |  |
| **AddTemplateFile(string urlOfFile, TemplateFileType templateFileType)** | [File](#file-class) |  |
| **GetByUrl(string url)** | [File](#file-class) |  |
# FileCreationInformation Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Content** | byte[] |  |
| **ContentStream** | Stream |  |
| **Overwrite** | bool |  |
| **Url** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# FileInformation Class

Namespace: Microsoft.SharePoint.Client


## Properties

| Name | Type | Summary |
|---|---|---|
| **Stream** | Stream |  |
| **ETag** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Dispose()** | void |  |
# FileLevel Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Published** |  |
| **Draft** |  |
| **Checkout** |  |
# FileObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Author** | string |  |
| **CheckedOutByUser** | string |  |
| **EffectiveInformationRightsManagementSettings** | string |  |
| **InformationRightsManagementSettings** | string |  |
| **ListItemAllFields** | string |  |
| **LockedByUser** | string |  |
| **ModifiedBy** | string |  |
| **Properties** | string |  |
| **VersionEvents** | string |  |
| **Versions** | string |  |
# FilePropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **CheckInComment** | string |  |
| **CheckOutType** | string |  |
| **ContentTag** | string |  |
| **CustomizedPageStatus** | string |  |
| **ListId** | string |  |
| **ETag** | string |  |
| **Exists** | string |  |
| **IrmEnabled** | string |  |
| **Length** | string |  |
| **Level** | string |  |
| **LinkingUrl** | string |  |
| **MajorVersion** | string |  |
| **MinorVersion** | string |  |
| **Name** | string |  |
| **ServerRelativeUrl** | string |  |
| **SiteId** | string |  |
| **TimeCreated** | string |  |
| **TimeLastModified** | string |  |
| **Title** | string |  |
| **UIVersion** | string |  |
| **UIVersionLabel** | string |  |
| **UniqueId** | string |  |
| **WebId** | string |  |
# FileSaveBinaryInformation Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **CheckRequiredFields** | bool |  |
| **Content** | byte[] |  |
| **ContentStream** | Stream |  |
| **ETag** | string |  |
| **FieldValues** | IDictionary\<string, Object\> |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# FileSystemObjectType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **File** |  |
| **Folder** |  |
| **Web** |  |
| **Invalid** |  |
# FileVersion Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **CheckInComment** | string |  |
| **Created** | DateTime |  |
| **CreatedBy** | [User](#user-class) |  |
| **ID** | int |  |
| **IsCurrentVersion** | bool |  |
| **Length** | long |  |
| **Size** | int |  |
| **Url** | string |  |
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
| **FileVersion(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
| **OpenBinaryStream()** | ClientResult\<Stream\> |  |
# FileVersionCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObjectCollection<[FileVersion](#fileversion-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [FileVersion](#fileversion-class) |  |
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
| **FileVersionCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteAll()** | void |  |
| **DeleteByID(int vid)** | void |  |
| **DeleteByLabel(string versionlabel)** | void |  |
| **GetById(int versionid)** | [FileVersion](#fileversion-class) |  |
| **RestoreByLabel(string versionlabel)** | void |  |
# FileVersionEvent Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Editor** | string |  |
| **EditorEmail** | string |  |
| **SharedByUser** | [SharedWithUser](#sharedwithuser-class) |  |
| **SharedWithUsers** | [SharedWithUserCollection](#sharedwithusercollection-class) |  |
| **Time** | DateTime |  |
| **EventType** | [FileVersionEventType](#fileversioneventtype-enum) |  |
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
| **FileVersionEvent(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# FileVersionEventCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObjectCollection<[FileVersionEvent](#fileversionevent-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [FileVersionEvent](#fileversionevent-class) |  |
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
| **FileVersionEventCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# FileVersionEventPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Editor** | string |  |
| **EditorEmail** | string |  |
| **SharedByUser** | string |  |
| **SharedWithUsers** | string |  |
| **Time** | string |  |
| **EventType** | string |  |
# FileVersionEventType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Share** |  |
| **Rename** |  |
| **Restore** |  |
| **MaxServerType** |  |
| **FromClient** |  |
# FileVersionObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **CreatedBy** | string |  |
# FileVersionPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **CheckInComment** | string |  |
| **Created** | string |  |
| **ID** | string |  |
| **IsCurrentVersion** | string |  |
| **Length** | string |  |
| **Size** | string |  |
| **Url** | string |  |
| **VersionLabel** | string |  |
# Folder Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ContentTypeOrder** | IList\<[ContentTypeId](#contenttypeid-class)\> |  |
| **Exists** | bool |  |
| **Files** | [FileCollection](#filecollection-class) |  |
| **IsWOPIEnabled** | bool |  |
| **ListItemAllFields** | [ListItem](#listitem-class) |  |
| **ItemCount** | int |  |
| **Name** | string |  |
| **ParentFolder** | [Folder](#folder-class) |  |
| **ProgID** | string |  |
| **Properties** | [PropertyValues](#propertyvalues-class) |  |
| **ServerRelativeUrl** | string |  |
| **StorageMetrics** | [StorageMetrics](#storagemetrics-class) |  |
| **Folders** | [FolderCollection](#foldercollection-class) |  |
| **TimeCreated** | DateTime |  |
| **TimeLastModified** | DateTime |  |
| **UniqueContentTypeOrder** | IList\<[ContentTypeId](#contenttypeid-class)\> |  |
| **UniqueId** | Guid |  |
| **WelcomePage** | string |  |
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
| **Folder(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
| **GetListItemChanges(ChangeQuery query)** | [ChangeCollection](#changecollection-class) |  |
| **MoveTo(string newUrl)** | void |  |
| **Recycle()** | ClientResult\<Guid\> |  |
| **Update()** | void |  |
# FolderCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObjectCollection<[Folder](#folder-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [Folder](#folder-class) |  |
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
| **FolderCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(string url)** | [Folder](#folder-class) |  |
| **AddWithOverwrite(string url, bool overwrite)** | [Folder](#folder-class) |  |
| **GetByUrl(string url)** | [Folder](#folder-class) |  |
# FolderObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Files** | string |  |
| **ListItemAllFields** | string |  |
| **ParentFolder** | string |  |
| **Properties** | string |  |
| **StorageMetrics** | string |  |
| **Folders** | string |  |
# FolderPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **ContentTypeOrder** | string |  |
| **Exists** | string |  |
| **IsWOPIEnabled** | string |  |
| **ItemCount** | string |  |
| **Name** | string |  |
| **ProgID** | string |  |
| **ServerRelativeUrl** | string |  |
| **TimeCreated** | string |  |
| **TimeLastModified** | string |  |
| **UniqueContentTypeOrder** | string |  |
| **UniqueId** | string |  |
| **WelcomePage** | string |  |
# Form Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Id** | Guid |  |
| **ServerRelativeUrl** | string |  |
| **FormType** | [PageType](#pagetype-enum) |  |
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
| **Form(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# FormCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObjectCollection<[Form](#form-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [Form](#form-class) |  |
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
| **FormCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetById(Guid id)** | [Form](#form-class) |  |
| **GetByPageType(PageType formType)** | [Form](#form-class) |  |
# FormDigestInfo Class

Namespace: Microsoft.SharePoint.Client


## Properties

| Name | Type | Summary |
|---|---|---|
| **DigestValue** | string |  |
| **Expiration** | DateTime |  |
| **RequestSchemaVersion** | Version |  |
# FormPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Id** | string |  |
| **ServerRelativeUrl** | string |  |
| **FormType** | string |  |
# Group Class

Namespace: Microsoft.SharePoint.Client

Base class: [Principal](#principal-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **AllowMembersEditMembership** | bool |  |
| **AllowRequestToJoinLeave** | bool |  |
| **AutoAcceptRequestToJoinLeave** | bool |  |
| **CanCurrentUserEditMembership** | bool |  |
| **CanCurrentUserManageGroup** | bool |  |
| **CanCurrentUserViewMembership** | bool |  |
| **Description** | string |  |
| **OnlyAllowMembersViewMembership** | bool |  |
| **Owner** | [Principal](#principal-class) |  |
| **OwnerTitle** | string |  |
| **RequestToJoinLeaveEmailSetting** | string |  |
| **Users** | [UserCollection](#usercollection-class) |  |
| **Id** | int |  |
| **IsHiddenInUI** | bool |  |
| **LoginName** | string |  |
| **Title** | string |  |
| **PrincipalType** | [PrincipalType](#principaltype-enum) |  |
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
| **Group(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Update()** | void |  |
# GroupCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObjectCollection<[Group](#group-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [Group](#group-class) |  |
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
| **GroupCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(GroupCreationInformation parameters)** | [Group](#group-class) |  |
| **GetById(int id)** | [Group](#group-class) |  |
| **GetByName(string name)** | [Group](#group-class) |  |
| **Remove(Group group)** | void |  |
| **RemoveById(int id)** | void |  |
| **RemoveByLoginName(string loginName)** | void |  |
# GroupCreationInformation Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Description** | string |  |
| **Title** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# GroupObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Owner** | string |  |
| **Users** | string |  |
# GroupPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **AllowMembersEditMembership** | string |  |
| **AllowRequestToJoinLeave** | string |  |
| **AutoAcceptRequestToJoinLeave** | string |  |
| **CanCurrentUserEditMembership** | string |  |
| **CanCurrentUserManageGroup** | string |  |
| **CanCurrentUserViewMembership** | string |  |
| **Description** | string |  |
| **OnlyAllowMembersViewMembership** | string |  |
| **OwnerTitle** | string |  |
| **RequestToJoinLeaveEmailSetting** | string |  |
# InformationRightsManagementFileSettings Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AllowPrint** | bool |  |
| **AllowScript** | bool |  |
| **AllowWriteCopy** | bool |  |
| **DisableDocumentBrowserView** | bool |  |
| **DocumentAccessExpireDays** | int |  |
| **EnableDocumentAccessExpire** | bool |  |
| **EnableDocumentBrowserPublishingView** | bool |  |
| **EnableGroupProtection** | bool |  |
| **EnableLicenseCacheExpire** | bool |  |
| **GroupName** | string |  |
| **IrmEnabled** | bool |  |
| **LicenseCacheExpireDays** | int |  |
| **PolicyDescription** | string |  |
| **PolicyTitle** | string |  |
| **TemplateId** | string |  |
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
| **InformationRightsManagementFileSettings(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Reset()** | void |  |
| **Update()** | void |  |
# InformationRightsManagementFileSettingsPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **AllowPrint** | string |  |
| **AllowScript** | string |  |
| **AllowWriteCopy** | string |  |
| **DisableDocumentBrowserView** | string |  |
| **DocumentAccessExpireDays** | string |  |
| **EnableDocumentAccessExpire** | string |  |
| **EnableDocumentBrowserPublishingView** | string |  |
| **EnableGroupProtection** | string |  |
| **EnableLicenseCacheExpire** | string |  |
| **GroupName** | string |  |
| **IrmEnabled** | string |  |
| **LicenseCacheExpireDays** | string |  |
| **PolicyDescription** | string |  |
| **PolicyTitle** | string |  |
| **TemplateId** | string |  |
# InformationRightsManagementSettings Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AllowPrint** | bool |  |
| **AllowScript** | bool |  |
| **AllowWriteCopy** | bool |  |
| **DisableDocumentBrowserView** | bool |  |
| **DocumentAccessExpireDays** | int |  |
| **DocumentLibraryProtectionExpireDate** | DateTime |  |
| **EnableDocumentAccessExpire** | bool |  |
| **EnableDocumentBrowserPublishingView** | bool |  |
| **EnableGroupProtection** | bool |  |
| **EnableLicenseCacheExpire** | bool |  |
| **GroupName** | string |  |
| **LicenseCacheExpireDays** | int |  |
| **PolicyDescription** | string |  |
| **PolicyTitle** | string |  |
| **TemplateId** | string |  |
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
| **InformationRightsManagementSettings(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Reset()** | void |  |
| **Update()** | void |  |
# InformationRightsManagementSettingsPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **AllowPrint** | string |  |
| **AllowScript** | string |  |
| **AllowWriteCopy** | string |  |
| **DisableDocumentBrowserView** | string |  |
| **DocumentAccessExpireDays** | string |  |
| **DocumentLibraryProtectionExpireDate** | string |  |
| **EnableDocumentAccessExpire** | string |  |
| **EnableDocumentBrowserPublishingView** | string |  |
| **EnableGroupProtection** | string |  |
| **EnableLicenseCacheExpire** | string |  |
| **GroupName** | string |  |
| **LicenseCacheExpireDays** | string |  |
| **PolicyDescription** | string |  |
| **PolicyTitle** | string |  |
| **TemplateId** | string |  |
# IngestionTaskKey Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **IngestionTableAccountKey** | string |  |
| **IngestionTableAccountName** | string |  |
| **JobId** | string |  |
| **TaskId** | string |  |
| **TenantName** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# Language Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **DisplayName** | string |  |
| **LanguageTag** | string |  |
| **Lcid** | int |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# List Class

Namespace: Microsoft.SharePoint.Client

Base class: [SecurableObject](#securableobject-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **AllowContentTypes** | bool |  |
| **BaseTemplate** | int |  |
| **BaseType** | [BaseType](#basetype-enum) |  |
| **BrowserFileHandling** | [BrowserFileHandling](#browserfilehandling-enum) |  |
| **ContentTypes** | [ContentTypeCollection](#contenttypecollection-class) |  |
| **ContentTypesEnabled** | bool |  |
| **CrawlNonDefaultViews** | bool |  |
| **CreatablesInfo** | [CreatablesInfo](#creatablesinfo-class) |  |
| **Created** | DateTime |  |
| **CurrentChangeToken** | [ChangeToken](#changetoken-class) |  |
| **CustomActionElements** | [CustomActionElementCollection](#customactionelementcollection-class) |  |
| **DataSource** | [ListDataSource](#listdatasource-class) |  |
| **DefaultContentApprovalWorkflowId** | Guid |  |
| **DefaultDisplayFormUrl** | string |  |
| **DefaultEditFormUrl** | string |  |
| **DefaultNewFormUrl** | string |  |
| **DefaultView** | [View](#view-class) |  |
| **DefaultViewUrl** | string |  |
| **Description** | string |  |
| **DescriptionResource** | [UserResource](#userresource-class) |  |
| **Direction** | string |  |
| **DocumentTemplateUrl** | string |  |
| **DraftVersionVisibility** | [DraftVisibilityType](#draftvisibilitytype-enum) |  |
| **EffectiveBasePermissions** | [BasePermissions](#basepermissions-class) |  |
| **EffectiveBasePermissionsForUI** | [BasePermissions](#basepermissions-class) |  |
| **EnableAttachments** | bool |  |
| **EnableFolderCreation** | bool |  |
| **EnableMinorVersions** | bool |  |
| **EnableModeration** | bool |  |
| **EnableVersioning** | bool |  |
| **EntityTypeName** | string |  |
| **EventReceivers** | [EventReceiverDefinitionCollection](#eventreceiverdefinitioncollection-class) |  |
| **Fields** | [FieldCollection](#fieldcollection-class) |  |
| **FileSavePostProcessingEnabled** | bool |  |
| **ForceCheckout** | bool |  |
| **Forms** | [FormCollection](#formcollection-class) |  |
| **HasExternalDataSource** | bool |  |
| **Hidden** | bool |  |
| **Id** | Guid |  |
| **ImageUrl** | string |  |
| **InformationRightsManagementSettings** | [InformationRightsManagementSettings](#informationrightsmanagementsettings-class) |  |
| **IrmEnabled** | bool |  |
| **IrmExpire** | bool |  |
| **IrmReject** | bool |  |
| **IsApplicationList** | bool |  |
| **IsCatalog** | bool |  |
| **IsPrivate** | bool |  |
| **IsSiteAssetsLibrary** | bool |  |
| **ItemCount** | int |  |
| **LastItemDeletedDate** | DateTime |  |
| **LastItemModifiedDate** | DateTime |  |
| **ListItemEntityTypeFullName** | string |  |
| **MajorVersionLimit** | int |  |
| **MajorWithMinorVersionsLimit** | int |  |
| **MultipleDataList** | bool |  |
| **NoCrawl** | bool |  |
| **OnQuickLaunch** | bool |  |
| **ParentWeb** | [Web](#web-class) |  |
| **ParentWebUrl** | string |  |
| **ParserDisabled** | bool |  |
| **RootFolder** | [Folder](#folder-class) |  |
| **SchemaXml** | string |  |
| **ServerTemplateCanCreateFolders** | bool |  |
| **TemplateFeatureId** | Guid |  |
| **Title** | string |  |
| **TitleResource** | [UserResource](#userresource-class) |  |
| **UserCustomActions** | [UserCustomActionCollection](#usercustomactioncollection-class) |  |
| **ValidationFormula** | string |  |
| **ValidationMessage** | string |  |
| **Views** | [ViewCollection](#viewcollection-class) |  |
| **WorkflowAssociations** | [WorkflowAssociationCollection](#workflowassociationcollection-class) |  |
| **FirstUniqueAncestorSecurableObject** | [SecurableObject](#securableobject-class) |  |
| **HasUniqueRoleAssignments** | bool |  |
| **RoleAssignments** | [RoleAssignmentCollection](#roleassignmentcollection-class) |  |
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
| **List(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **AddItem(ListItemCreationInformation parameters)** | [ListItem](#listitem-class) |  |
| **CreateDocument(string fileName, Folder targetFolder, DocumentTemplateType templateType)** | [ListItem](#listitem-class) |  |
| **CreateDocumentAndGetEditLink(string fileName, string folderPath, int documentTemplateType)** | ClientResult\<string\> |  |
| **CreateDocumentFromTemplate(string fileName, Folder targetFolder, string templateUrl)** | [ListItem](#listitem-class) |  |
| **CreateDocumentFromTemplateBytes(string fileName, Folder targetFolder, byte[] templateBytes, string extension)** | [ListItem](#listitem-class) |  |
| **CreateDocumentFromTemplateStream(string fileName, Folder targetFolder, string extension, Stream templateStream)** | [ListItem](#listitem-class) |  |
| **CreateDocumentWithDefaultName(string folderPath, string extension)** | ClientResult\<string\> |  |
| **DeleteObject()** | void |  |
| **GetChanges(ChangeQuery query)** | [ChangeCollection](#changecollection-class) |  |
| **GetItemById(int id)** | [ListItem](#listitem-class) |  |
| **GetItemById(string id)** | [ListItem](#listitem-class) |  |
| **GetItems(CamlQuery query)** | [ListItemCollection](#listitemcollection-class) |  |
| **GetRelatedFields()** | [RelatedFieldCollection](#relatedfieldcollection-class) |  |
| **GetSpecialFolderUrl(SpecialFolderType type, bool bForceCreate, Guid existingFolderGuid)** | ClientResult\<string\> |  |
| **GetUserEffectivePermissions(string userName)** | ClientResult\<[BasePermissions](#basepermissions-class)\> |  |
| **GetView(Guid viewGuid)** | [View](#view-class) |  |
| **GetWebDavUrl(string sourceUrl)** | ClientResult\<string\> |  |
| **Recycle()** | ClientResult\<Guid\> |  |
| **RenderExtendedListFormData(int itemId, string formId, int mode, RenderListFormDataOptions options)** | ClientResult\<string\> |  |
| **RenderListContextMenuData(RenderListContextMenuDataParameters parameters)** | ClientResult\<Stream\> |  |
| **RenderListData(string viewXml)** | ClientResult\<string\> |  |
| **RenderListDataAsStream(RenderListDataParameters parameters, RenderListDataOverrideParameters overrideParameters)** | ClientResult\<Stream\> |  |
| **RenderListFilterData(RenderListFilterDataParameters parameters)** | ClientResult\<Stream\> |  |
| **RenderListFormData(int itemId, string formId, int mode)** | ClientResult\<string\> |  |
| **ReserveListItemId()** | ClientResult\<int\> |  |
| **SaveAsNewView(string oldName, string newName, bool privateView, string uri)** | ClientResult\<string\> |  |
| **Update()** | void |  |
# ListCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObjectCollection<[List](#list-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [List](#list-class) |  |
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
| **ListCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(ListCreationInformation parameters)** | [List](#list-class) |  |
| **EnsureSiteAssetsLibrary()** | [List](#list-class) |  |
| **EnsureSitePagesLibrary()** | [List](#list-class) |  |
| **GetById(Guid id)** | [List](#list-class) |  |
| **GetByTitle(string title)** | [List](#list-class) |  |
# ListCreationInformation Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **CustomSchemaXml** | string |  |
| **DataSourceProperties** | IDictionary\<string, string\> |  |
| **Description** | string |  |
| **DocumentTemplateType** | int |  |
| **QuickLaunchOption** | [QuickLaunchOptions](#quicklaunchoptions-enum) |  |
| **TemplateFeatureId** | Guid |  |
| **TemplateType** | int |  |
| **Title** | string |  |
| **Url** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# ListDataSource Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Properties** | IDictionary\<string, string\> |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# ListDataValidationExceptionValue Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **FieldFailures** | IList\<[ListDataValidationFailure](#listdatavalidationfailure-class)\> |  |
| **ItemFailure** | [ListDataValidationFailure](#listdatavalidationfailure-class) |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# ListDataValidationFailure Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **DisplayName** | string |  |
| **Message** | string |  |
| **Name** | string |  |
| **Reason** | [ListDataValidationFailureReason](#listdatavalidationfailurereason-enum) |  |
| **ValidationType** | [ListDataValidationType](#listdatavalidationtype-enum) |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# ListDataValidationFailureReason Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **DataFailure** |  |
| **FormulaError** |  |
# ListDataValidationType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **UserFormulaField** |  |
| **UserFormulaItem** |  |
| **RequiredField** |  |
| **ChoiceField** |  |
| **MinMaxField** |  |
| **TextField** |  |
# ListItem Class

Namespace: Microsoft.SharePoint.Client

Base class: [SecurableObject](#securableobject-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **FieldValues** | Dictionary\<string, Object\> |  |
| **Item** | Object |  |
| **AttachmentFiles** | [AttachmentCollection](#attachmentcollection-class) |  |
| **ContentType** | [ContentType](#contenttype-class) |  |
| **DisplayName** | string |  |
| **GetDlpPolicyTip** | [DlpPolicyTip](#dlppolicytip-class) |  |
| **EffectiveBasePermissions** | [BasePermissions](#basepermissions-class) |  |
| **EffectiveBasePermissionsForUI** | [BasePermissions](#basepermissions-class) |  |
| **FieldValuesAsHtml** | [FieldStringValues](#fieldstringvalues-class) |  |
| **FieldValuesAsText** | [FieldStringValues](#fieldstringvalues-class) |  |
| **FieldValuesForEdit** | [FieldStringValues](#fieldstringvalues-class) |  |
| **File** | [File](#file-class) |  |
| **FileSystemObjectType** | [FileSystemObjectType](#filesystemobjecttype-enum) |  |
| **Folder** | [Folder](#folder-class) |  |
| **Id** | int |  |
| **ParentList** | [List](#list-class) |  |
| **Client_Title** | string |  |
| **FirstUniqueAncestorSecurableObject** | [SecurableObject](#securableobject-class) |  |
| **HasUniqueRoleAssignments** | bool |  |
| **RoleAssignments** | [RoleAssignmentCollection](#roleassignmentcollection-class) |  |
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
| **ListItem(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **AddHashTag(string hashTag)** | void |  |
| **DeleteObject()** | void |  |
| **GetChanges(ChangeQuery query)** | [ChangeCollection](#changecollection-class) |  |
| **GetUserEffectivePermissions(string userName)** | ClientResult\<[BasePermissions](#basepermissions-class)\> |  |
| **GetWOPIFrameUrl(SPWOPIFrameAction action)** | ClientResult\<string\> |  |
| **OverridePolicyTip(PolicyTipUserAction userAction, string justification)** | ClientResult\<[PolicyTipUserActionResult](#policytipuseractionresult-enum)\> |  |
| **ParseAndSetFieldValue(string fieldName, string value)** | void |  |
| **Recycle()** | ClientResult\<Guid\> |  |
| **RefreshLoad()** | void |  |
| **Update()** | void |  |
| **ValidateUpdateListItem(IList\<ListItemFormUpdateValue\> formValues, bool bNewDocumentUpdate, string checkInComment)** | IList\<[ListItemFormUpdateValue](#listitemformupdatevalue-class)\> |  |
# ListItemCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObjectCollection<[ListItem](#listitem-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **ListItemCollectionPosition** | [ListItemCollectionPosition](#listitemcollectionposition-class) |  |
| **Item** | [ListItem](#listitem-class) |  |
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
| **ListItemCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetById(string id)** | [ListItem](#listitem-class) |  |
| **GetById(int id)** | [ListItem](#listitem-class) |  |
# ListItemCollectionPosition Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **PagingInfo** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# ListItemCollectionPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **ListItemCollectionPosition** | string |  |
# ListItemCreationInformation Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **FolderUrl** | string |  |
| **LeafName** | string |  |
| **UnderlyingObjectType** | [FileSystemObjectType](#filesystemobjecttype-enum) |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# ListItemEntityCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObjectCollection<[ListItem](#listitem-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [ListItem](#listitem-class) |  |
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
| **ListItemEntityCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ListItemFormUpdateValue Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ErrorMessage** | string |  |
| **FieldName** | string |  |
| **FieldValue** | string |  |
| **HasException** | bool |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# ListItemObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **AttachmentFiles** | string |  |
| **ContentType** | string |  |
| **GetDlpPolicyTip** | string |  |
| **FieldValuesAsHtml** | string |  |
| **FieldValuesAsText** | string |  |
| **FieldValuesForEdit** | string |  |
| **File** | string |  |
| **Folder** | string |  |
| **ParentList** | string |  |
# ListItemPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **DisplayName** | string |  |
| **EffectiveBasePermissions** | string |  |
| **EffectiveBasePermissionsForUI** | string |  |
| **FileSystemObjectType** | string |  |
| **Id** | string |  |
| **Client_Title** | string |  |
# ListObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **ContentTypes** | string |  |
| **CreatablesInfo** | string |  |
| **DefaultView** | string |  |
| **DescriptionResource** | string |  |
| **EventReceivers** | string |  |
| **Fields** | string |  |
| **Forms** | string |  |
| **InformationRightsManagementSettings** | string |  |
| **ParentWeb** | string |  |
| **RootFolder** | string |  |
| **TitleResource** | string |  |
| **UserCustomActions** | string |  |
| **Views** | string |  |
| **WorkflowAssociations** | string |  |
# ListPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **AllowContentTypes** | string |  |
| **BaseTemplate** | string |  |
| **BaseType** | string |  |
| **BrowserFileHandling** | string |  |
| **ContentTypesEnabled** | string |  |
| **CrawlNonDefaultViews** | string |  |
| **Created** | string |  |
| **CurrentChangeToken** | string |  |
| **CustomActionElements** | string |  |
| **DataSource** | string |  |
| **DefaultContentApprovalWorkflowId** | string |  |
| **DefaultDisplayFormUrl** | string |  |
| **DefaultEditFormUrl** | string |  |
| **DefaultNewFormUrl** | string |  |
| **DefaultViewUrl** | string |  |
| **Description** | string |  |
| **Direction** | string |  |
| **DocumentTemplateUrl** | string |  |
| **DraftVersionVisibility** | string |  |
| **EffectiveBasePermissions** | string |  |
| **EffectiveBasePermissionsForUI** | string |  |
| **EnableAttachments** | string |  |
| **EnableFolderCreation** | string |  |
| **EnableMinorVersions** | string |  |
| **EnableModeration** | string |  |
| **EnableVersioning** | string |  |
| **EntityTypeName** | string |  |
| **FileSavePostProcessingEnabled** | string |  |
| **ForceCheckout** | string |  |
| **HasExternalDataSource** | string |  |
| **Hidden** | string |  |
| **Id** | string |  |
| **ImageUrl** | string |  |
| **IrmEnabled** | string |  |
| **IrmExpire** | string |  |
| **IrmReject** | string |  |
| **IsApplicationList** | string |  |
| **IsCatalog** | string |  |
| **IsPrivate** | string |  |
| **IsSiteAssetsLibrary** | string |  |
| **ItemCount** | string |  |
| **LastItemDeletedDate** | string |  |
| **LastItemModifiedDate** | string |  |
| **ListItemEntityTypeFullName** | string |  |
| **MajorVersionLimit** | string |  |
| **MajorWithMinorVersionsLimit** | string |  |
| **MultipleDataList** | string |  |
| **NoCrawl** | string |  |
| **OnQuickLaunch** | string |  |
| **ParentWebUrl** | string |  |
| **ParserDisabled** | string |  |
| **SchemaXml** | string |  |
| **ServerTemplateCanCreateFolders** | string |  |
| **TemplateFeatureId** | string |  |
| **Title** | string |  |
| **ValidationFormula** | string |  |
| **ValidationMessage** | string |  |
# ListTemplate Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AllowsFolderCreation** | bool |  |
| **BaseType** | [BaseType](#basetype-enum) |  |
| **Description** | string |  |
| **FeatureId** | Guid |  |
| **Hidden** | bool |  |
| **ImageUrl** | string |  |
| **InternalName** | string |  |
| **IsCustomTemplate** | bool |  |
| **Name** | string |  |
| **OnQuickLaunch** | bool |  |
| **ListTemplateTypeKind** | int |  |
| **Unique** | bool |  |
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
| **ListTemplate(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetGlobalSchemaXml()** | ClientResult\<Stream\> |  |
# ListTemplateCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObjectCollection<[ListTemplate](#listtemplate-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [ListTemplate](#listtemplate-class) |  |
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
| **ListTemplateCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetByName(string name)** | [ListTemplate](#listtemplate-class) |  |
# ListTemplatePropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **AllowsFolderCreation** | string |  |
| **BaseType** | string |  |
| **Description** | string |  |
| **FeatureId** | string |  |
| **Hidden** | string |  |
| **ImageUrl** | string |  |
| **InternalName** | string |  |
| **IsCustomTemplate** | string |  |
| **Name** | string |  |
| **OnQuickLaunch** | string |  |
| **ListTemplateTypeKind** | string |  |
| **Unique** | string |  |
# ListTemplateType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **NoListTemplate** |  |
| **GenericList** |  |
| **DocumentLibrary** |  |
| **Survey** |  |
| **Links** |  |
| **Announcements** |  |
| **Contacts** |  |
| **Events** |  |
| **Tasks** |  |
| **DiscussionBoard** |  |
| **PictureLibrary** |  |
| **DataSources** |  |
| **WebTemplateCatalog** |  |
| **UserInformation** |  |
| **WebPartCatalog** |  |
| **ListTemplateCatalog** |  |
| **XMLForm** |  |
| **MasterPageCatalog** |  |
| **NoCodeWorkflows** |  |
| **WorkflowProcess** |  |
| **WebPageLibrary** |  |
| **CustomGrid** |  |
| **SolutionCatalog** |  |
| **NoCodePublic** |  |
| **ThemeCatalog** |  |
| **DesignCatalog** |  |
| **AppDataCatalog** |  |
| **DataConnectionLibrary** |  |
| **WorkflowHistory** |  |
| **GanttTasks** |  |
| **HelpLibrary** |  |
| **AccessRequest** |  |
| **TasksWithTimelineAndHierarchy** |  |
| **MaintenanceLogs** |  |
| **Meetings** |  |
| **Agenda** |  |
| **MeetingUser** |  |
| **Decision** |  |
| **MeetingObjective** |  |
| **TextBox** |  |
| **ThingsToBring** |  |
| **HomePageLibrary** |  |
| **Posts** |  |
| **Comments** |  |
| **Categories** |  |
| **Facility** |  |
| **Whereabouts** |  |
| **CallTrack** |  |
| **Circulation** |  |
| **Timecard** |  |
| **Holidays** |  |
| **IMEDic** |  |
| **ExternalList** |  |
| **MySiteDocumentLibrary** |  |
| **IssueTracking** |  |
| **AdminTasks** |  |
| **HealthRules** |  |
| **HealthReports** |  |
| **DeveloperSiteDraftApps** |  |
| **AccessApp** |  |
| **AlchemyMobileForm** |  |
| **AlchemyApprovalWorkflow** |  |
| **SharingLinks** |  |
| **InvalidType** |  |
# MigrationJobState Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **Queued** |  |
| **Processing** |  |
# MountedFolderInfo Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **FolderUrl** | string |  |
| **HasEditPermission** | bool |  |
| **ItemId** | int |  |
| **ListTemplateType** | [ListTemplateType](#listtemplatetype-enum) |  |
| **ListViewUrl** | string |  |
| **WebUrl** | string |  |
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
| **MountedFolderInfo(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# MountedFolderInfoPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **FolderUrl** | string |  |
| **HasEditPermission** | string |  |
| **ItemId** | string |  |
| **ListTemplateType** | string |  |
| **ListViewUrl** | string |  |
| **WebUrl** | string |  |
# MountPoint Class

Namespace: Microsoft.SharePoint.Client


## Methods

| Name | Returns | Summary |
|---|---|---|
| **CreateMountPoint(ClientRuntimeContext context, Folder folder, string name, Guid targetSiteId, Guid targetWebId, Guid targetUniqueId)** | void |  |
| **GetMountedFolderInfo(ClientRuntimeContext context, Guid targetSiteId, Guid targetWebId, Guid targetUniqueId)** | [MountedFolderInfo](#mountedfolderinfo-class) |  |
| **GetMountedFolderUrls(ClientRuntimeContext context, List list)** | IEnumerable\<string\> |  |
# MountPointInfo Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Name** | string |  |
| **RedirectUrl** | string |  |
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
| **MountPointInfo(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# MountPointInfoPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Name** | string |  |
| **RedirectUrl** | string |  |
# MoveCopyUtil Class

Namespace: Microsoft.SharePoint.Client


## Methods

| Name | Returns | Summary |
|---|---|---|
| **CopyFile(ClientRuntimeContext context, string srcUrl, string destUrl, bool overwrite)** | void |  |
| **CopyFolder(ClientRuntimeContext context, string srcUrl, string destUrl)** | void |  |
| **MoveFile(ClientRuntimeContext context, string srcUrl, string destUrl, bool overwrite)** | void |  |
| **MoveFolder(ClientRuntimeContext context, string srcUrl, string destUrl)** | void |  |
# MoveOperations Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **Overwrite** |  |
| **AllowBrokenThickets** |  |
| **BypassApprovePermission** |  |
# Navigation Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **QuickLaunch** | [NavigationNodeCollection](#navigationnodecollection-class) |  |
| **TopNavigationBar** | [NavigationNodeCollection](#navigationnodecollection-class) |  |
| **UseShared** | bool |  |
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
| **Navigation(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetNodeById(int id)** | [NavigationNode](#navigationnode-class) |  |
# NavigationNode Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Children** | [NavigationNodeCollection](#navigationnodecollection-class) |  |
| **Id** | int |  |
| **IsDocLib** | bool |  |
| **IsExternal** | bool |  |
| **IsVisible** | bool |  |
| **Title** | string |  |
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
| **NavigationNode(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
| **Update()** | void |  |
# NavigationNodeCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObjectCollection<[NavigationNode](#navigationnode-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [NavigationNode](#navigationnode-class) |  |
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
| **NavigationNodeCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(NavigationNodeCreationInformation parameters)** | [NavigationNode](#navigationnode-class) |  |
# NavigationNodeCreationInformation Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AsLastNode** | bool |  |
| **IsExternal** | bool |  |
| **PreviousNode** | [NavigationNode](#navigationnode-class) |  |
| **Title** | string |  |
| **Url** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# NavigationNodeObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Children** | string |  |
# NavigationNodePropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Id** | string |  |
| **IsDocLib** | string |  |
| **IsExternal** | string |  |
| **IsVisible** | string |  |
| **Title** | string |  |
| **Url** | string |  |
# NavigationObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **QuickLaunch** | string |  |
| **TopNavigationBar** | string |  |
# NavigationPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **UseShared** | string |  |
# ObjectSharingInformation Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AnonymousEditLink** | string |  |
| **AnonymousViewLink** | string |  |
| **CanBeShared** | bool |  |
| **CanBeUnshared** | bool |  |
| **CanManagePermissions** | bool |  |
| **HasPendingAccessRequests** | bool |  |
| **HasPermissionLevels** | bool |  |
| **IsSharedWithCurrentUser** | bool |  |
| **IsSharedWithGuest** | bool |  |
| **IsSharedWithMany** | bool |  |
| **IsSharedWithSecurityGroup** | bool |  |
| **PendingAccessRequestsLink** | string |  |
| **SharedWithUsersCollection** | [ObjectSharingInformationUserCollection](#objectsharinginformationusercollection-class) |  |
| **SharingLinks** | IEnumerable\<[SharingLinkInfo](#sharinglinkinfo-class)\> |  |
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
| **ObjectSharingInformation(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **CanCurrentUserShare(ClientRuntimeContext context, string docId)** | ClientResult\<[UserSharingCapabilities](#usersharingcapabilities-enum)\> |  |
| **CanCurrentUserShareRemote(ClientRuntimeContext context, string docId)** | ClientResult\<[UserSharingCapabilities](#usersharingcapabilities-enum)\> |  |
| **GetListItemSharingInformation(ClientRuntimeContext context, Guid listID, int itemID, bool excludeCurrentUser, bool excludeSiteAdmin, bool excludeSecurityGroups, bool retrieveAnonymousLinks, bool retrieveUserInfoDetails, bool checkForAccessRequests)** | [ObjectSharingInformation](#objectsharinginformation-class) |  |
| **GetObjectSharingInformation(ClientRuntimeContext context, SecurableObject securableObject, bool excludeCurrentUser, bool excludeSiteAdmin, bool excludeSecurityGroups, bool retrieveAnonymousLinks, bool retrieveUserInfoDetails, bool checkForAccessRequests, bool retrievePermissionLevels)** | [ObjectSharingInformation](#objectsharinginformation-class) |  |
| **GetObjectSharingInformation2(ClientRuntimeContext context, SecurableObject securableObject, bool excludeCurrentUser, bool excludeSiteAdmin, bool excludeSecurityGroups, bool retrieveAnonymousLinks, bool retrieveUserInfoDetails, bool checkForAccessRequests, bool retrievePermissionLevels, bool forceRetrievePermissionLevels)** | [ObjectSharingInformation](#objectsharinginformation-class) |  |
| **GetObjectSharingInformationByUrl(ClientRuntimeContext context, string objectUrl, bool excludeCurrentUser, bool excludeSiteAdmin, bool excludeSecurityGroups, bool retrieveAnonymousLinks, bool retrieveUserInfoDetails, bool checkForAccessRequests, bool retrievePermissionLevels)** | [ObjectSharingInformation](#objectsharinginformation-class) |  |
| **GetSharedWithUsers()** | ClientObjectList\<[ObjectSharingInformationUser](#objectsharinginformationuser-class)\> |  |
| **GetWebSharingInformation(ClientRuntimeContext context, bool excludeCurrentUser, bool excludeSiteAdmin, bool excludeSecurityGroups, bool retrieveAnonymousLinks, bool retrieveUserInfoDetails, bool checkForAccessRequests)** | [ObjectSharingInformation](#objectsharinginformation-class) |  |
# ObjectSharingInformationObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **SharedWithUsersCollection** | string |  |
# ObjectSharingInformationPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **AnonymousEditLink** | string |  |
| **AnonymousViewLink** | string |  |
| **CanBeShared** | string |  |
| **CanBeUnshared** | string |  |
| **CanManagePermissions** | string |  |
| **HasPendingAccessRequests** | string |  |
| **HasPermissionLevels** | string |  |
| **IsSharedWithCurrentUser** | string |  |
| **IsSharedWithGuest** | string |  |
| **IsSharedWithMany** | string |  |
| **IsSharedWithSecurityGroup** | string |  |
| **PendingAccessRequestsLink** | string |  |
| **SharingLinks** | string |  |
# ObjectSharingInformationUser Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **CustomRoleNames** | string |  |
| **Department** | string |  |
| **Email** | string |  |
| **HasEditPermission** | bool |  |
| **HasViewPermission** | bool |  |
| **Id** | int |  |
| **IsDomainGroup** | bool |  |
| **IsMemberOfGroup** | bool |  |
| **IsSiteAdmin** | bool |  |
| **JobTitle** | string |  |
| **LoginName** | string |  |
| **Name** | string |  |
| **Picture** | string |  |
| **Principal** | [Principal](#principal-class) |  |
| **SipAddress** | string |  |
| **User** | [User](#user-class) |  |
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
| **ObjectSharingInformationUser(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ObjectSharingInformationUserCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObjectCollection<[ObjectSharingInformationUser](#objectsharinginformationuser-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [ObjectSharingInformationUser](#objectsharinginformationuser-class) |  |
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
| **ObjectSharingInformationUserCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ObjectSharingInformationUserObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Principal** | string |  |
| **User** | string |  |
# ObjectSharingInformationUserPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **CustomRoleNames** | string |  |
| **Department** | string |  |
| **Email** | string |  |
| **HasEditPermission** | string |  |
| **HasViewPermission** | string |  |
| **Id** | string |  |
| **IsDomainGroup** | string |  |
| **IsMemberOfGroup** | string |  |
| **IsSiteAdmin** | string |  |
| **JobTitle** | string |  |
| **LoginName** | string |  |
| **Name** | string |  |
| **Picture** | string |  |
| **SipAddress** | string |  |
# ObjectSharingSettings Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AccessRequestMode** | bool |  |
| **CanCurrentUserManageOrganizationReadonlyLink** | bool |  |
| **CanCurrentUserManageOrganizationReadWriteLink** | bool |  |
| **CanCurrentUserManageReadonlyLink** | bool |  |
| **CanCurrentUserManageReadWriteLink** | bool |  |
| **CanCurrentUserRetrieveOrganizationReadonlyLink** | bool |  |
| **CanCurrentUserRetrieveOrganizationReadWriteLink** | bool |  |
| **CanCurrentUserRetrieveReadonlyLink** | bool |  |
| **CanCurrentUserRetrieveReadWriteLink** | bool |  |
| **CanCurrentUserShareExternally** | bool |  |
| **CanCurrentUserShareInternally** | bool |  |
| **CanSendEmail** | bool |  |
| **CanSendLink** | bool |  |
| **CanShareFolder** | bool |  |
| **GroupsList** | IDictionary\<string, string\> |  |
| **HasEditRole** | bool |  |
| **HasReadRole** | bool |  |
| **InheritingWebLink** | string |  |
| **IsGuestUser** | bool |  |
| **IsPictureLibrary** | bool |  |
| **IsUserSiteAdmin** | bool |  |
| **ItemId** | string |  |
| **ItemName** | string |  |
| **ItemUrl** | string |  |
| **ListId** | Guid |  |
| **ObjectSharingInformation** | [ObjectSharingInformation](#objectsharinginformation-class) |  |
| **PermissionsOnlyMode** | bool |  |
| **RequiredAnonymousLinkExpirationInDays** | int |  |
| **Roles** | IDictionary\<string, string\> |  |
| **ShareByEmailEnabled** | bool |  |
| **SharePointSettings** | [SharePointSharingSettings](#sharepointsharingsettings-class) |  |
| **SharingPermissions** | [SharingPermissionInformationCollection](#sharingpermissioninformationcollection-class) |  |
| **ShowExternalSharingWarning** | bool |  |
| **SimplifiedRoles** | IDictionary\<string, string\> |  |
| **SupportsAclPropagation** | bool |  |
| **WebUrl** | string |  |
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
| **ObjectSharingSettings(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ObjectSharingSettingsObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **ObjectSharingInformation** | string |  |
| **SharePointSettings** | string |  |
| **SharingPermissions** | string |  |
# ObjectSharingSettingsPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **AccessRequestMode** | string |  |
| **CanCurrentUserManageOrganizationReadonlyLink** | string |  |
| **CanCurrentUserManageOrganizationReadWriteLink** | string |  |
| **CanCurrentUserManageReadonlyLink** | string |  |
| **CanCurrentUserManageReadWriteLink** | string |  |
| **CanCurrentUserRetrieveOrganizationReadonlyLink** | string |  |
| **CanCurrentUserRetrieveOrganizationReadWriteLink** | string |  |
| **CanCurrentUserRetrieveReadonlyLink** | string |  |
| **CanCurrentUserRetrieveReadWriteLink** | string |  |
| **CanCurrentUserShareExternally** | string |  |
| **CanCurrentUserShareInternally** | string |  |
| **CanSendEmail** | string |  |
| **CanSendLink** | string |  |
| **CanShareFolder** | string |  |
| **GroupsList** | string |  |
| **HasEditRole** | string |  |
| **HasReadRole** | string |  |
| **InheritingWebLink** | string |  |
| **IsGuestUser** | string |  |
| **IsPictureLibrary** | string |  |
| **IsUserSiteAdmin** | string |  |
| **ItemId** | string |  |
| **ItemName** | string |  |
| **ItemUrl** | string |  |
| **ListId** | string |  |
| **PermissionsOnlyMode** | string |  |
| **RequiredAnonymousLinkExpirationInDays** | string |  |
| **Roles** | string |  |
| **ShareByEmailEnabled** | string |  |
| **ShowExternalSharingWarning** | string |  |
| **SimplifiedRoles** | string |  |
| **SupportsAclPropagation** | string |  |
| **WebUrl** | string |  |
# OpenWebOptions Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **InitNavigationCache** |  |
# PageType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **DefaultView** |  |
| **NormalView** |  |
| **DialogView** |  |
| **View** |  |
| **DisplayForm** |  |
| **DisplayFormDialog** |  |
| **EditForm** |  |
| **EditFormDialog** |  |
| **NewForm** |  |
| **NewFormDialog** |  |
| **SolutionForm** |  |
| **PAGE_MAXITEMS** |  |
| **Invalid** |  |
# PermissionKind Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **EmptyMask** |  |
| **ViewListItems** |  |
| **AddListItems** |  |
| **EditListItems** |  |
| **DeleteListItems** |  |
| **ApproveItems** |  |
| **OpenItems** |  |
| **ViewVersions** |  |
| **DeleteVersions** |  |
| **CancelCheckout** |  |
| **ManagePersonalViews** |  |
| **ManageLists** |  |
| **ViewFormPages** |  |
| **AnonymousSearchAccessList** |  |
| **Open** |  |
| **ViewPages** |  |
| **AddAndCustomizePages** |  |
| **ApplyThemeAndBorder** |  |
| **ApplyStyleSheets** |  |
| **ViewUsageData** |  |
| **CreateSSCSite** |  |
| **ManageSubwebs** |  |
| **CreateGroups** |  |
| **ManagePermissions** |  |
| **BrowseDirectories** |  |
| **BrowseUserInfo** |  |
| **AddDelPrivateWebParts** |  |
| **UpdatePersonalWebParts** |  |
| **ManageWeb** |  |
| **AnonymousSearchAccessWebLists** |  |
| **UseClientIntegration** |  |
| **UseRemoteAPIs** |  |
| **ManageAlerts** |  |
| **CreateAlerts** |  |
| **EditMyUserInfo** |  |
| **EnumeratePermissions** |  |
| **FullMask** |  |
# PickerSettings Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AllowEmailAddresses** | bool |  |
| **AllowOnlyEmailAddresses** | bool |  |
| **PrincipalAccountType** | string |  |
| **PrincipalSource** | [PrincipalSource](#principalsource-enum) |  |
| **VisibleSuggestions** | int |  |
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
| **PickerSettings(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# PickerSettingsPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **AllowEmailAddresses** | string |  |
| **AllowOnlyEmailAddresses** | string |  |
| **PrincipalAccountType** | string |  |
| **PrincipalSource** | string |  |
| **VisibleSuggestions** | string |  |
# PolicyTipUserAction Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Override** |  |
| **ReportFalsePositive** |  |
# PolicyTipUserActionResult Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **FalsePositiveReported** |  |
| **Overridden** |  |
| **FalsePositiveReportedAndOverridden** |  |
# Principal Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Id** | int |  |
| **IsHiddenInUI** | bool |  |
| **LoginName** | string |  |
| **Title** | string |  |
| **PrincipalType** | [PrincipalType](#principaltype-enum) |  |
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
| **Principal(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# PrincipalPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Id** | string |  |
| **IsHiddenInUI** | string |  |
| **LoginName** | string |  |
| **Title** | string |  |
| **PrincipalType** | string |  |
# PropertyValues Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **FieldValues** | Dictionary\<string, Object\> |  |
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
| **PropertyValues(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **RefreshLoad()** | void |  |
# PushNotificationSubscriber Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **CustomArgs** | string |  |
| **DeviceAppInstanceId** | Guid |  |
| **LastModifiedTimeStamp** | DateTime |  |
| **RegistrationTimeStamp** | DateTime |  |
| **ServiceToken** | string |  |
| **SubscriberType** | string |  |
| **User** | [User](#user-class) |  |
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
| **PushNotificationSubscriber(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Update()** | void |  |
# PushNotificationSubscriberCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObjectCollection<[PushNotificationSubscriber](#pushnotificationsubscriber-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [PushNotificationSubscriber](#pushnotificationsubscriber-class) |  |
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
| **PushNotificationSubscriberCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetByStoreId(string id)** | [PushNotificationSubscriber](#pushnotificationsubscriber-class) |  |
# PushNotificationSubscriberObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **User** | string |  |
# PushNotificationSubscriberPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **CustomArgs** | string |  |
| **DeviceAppInstanceId** | string |  |
| **LastModifiedTimeStamp** | string |  |
| **RegistrationTimeStamp** | string |  |
| **ServiceToken** | string |  |
| **SubscriberType** | string |  |
# QuickLaunchOptions Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Off** |  |
| **On** |  |
| **DefaultValue** |  |
# RecycleBinItem Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Author** | [User](#user-class) |  |
| **AuthorEmail** | string |  |
| **AuthorName** | string |  |
| **DeletedBy** | [User](#user-class) |  |
| **DeletedByEmail** | string |  |
| **DeletedByName** | string |  |
| **DeletedDate** | DateTime |  |
| **DeletedDateLocalFormatted** | string |  |
| **DirName** | string |  |
| **Id** | Guid |  |
| **ItemState** | [RecycleBinItemState](#recyclebinitemstate-enum) |  |
| **ItemType** | [RecycleBinItemType](#recyclebinitemtype-enum) |  |
| **LeafName** | string |  |
| **Size** | long |  |
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
| **RecycleBinItem(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
| **MoveToSecondStage()** | void |  |
| **Restore()** | void |  |
# RecycleBinItemCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObjectCollection<[RecycleBinItem](#recyclebinitem-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [RecycleBinItem](#recyclebinitem-class) |  |
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
| **RecycleBinItemCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteAll()** | void |  |
| **DeleteAllSecondStageItems()** | void |  |
| **GetById(Guid id)** | [RecycleBinItem](#recyclebinitem-class) |  |
| **MoveAllToSecondStage()** | void |  |
| **RestoreAll()** | void |  |
# RecycleBinItemObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Author** | string |  |
| **DeletedBy** | string |  |
# RecycleBinItemPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **AuthorEmail** | string |  |
| **AuthorName** | string |  |
| **DeletedByEmail** | string |  |
| **DeletedByName** | string |  |
| **DeletedDate** | string |  |
| **DeletedDateLocalFormatted** | string |  |
| **DirName** | string |  |
| **Id** | string |  |
| **ItemState** | string |  |
| **ItemType** | string |  |
| **LeafName** | string |  |
| **Size** | string |  |
| **Title** | string |  |
# RecycleBinItemState Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **FirstStageRecycleBin** |  |
| **SecondStageRecycleBin** |  |
# RecycleBinItemType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **File** |  |
| **FileVersion** |  |
| **ListItem** |  |
| **List** |  |
| **Folder** |  |
| **FolderWithLists** |  |
| **Attachment** |  |
| **ListItemVersion** |  |
| **CascadeParent** |  |
| **Web** |  |
| **App** |  |
# RecycleBinOrderBy Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Min** |  |
| **DefaultOrderBy** |  |
| **Title** |  |
| **DirName** |  |
| **Author** |  |
| **DeletedDate** |  |
| **Size** |  |
| **DeletedBy** |  |
| **None** |  |
| **Max** |  |
# RegionalSettings Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AdjustHijriDays** | short |  |
| **AlternateCalendarType** | short |  |
| **AM** | string |  |
| **CalendarType** | short |  |
| **Collation** | short |  |
| **CollationLCID** | uint |  |
| **DateFormat** | uint |  |
| **DateSeparator** | string |  |
| **DecimalSeparator** | string |  |
| **DigitGrouping** | string |  |
| **FirstDayOfWeek** | uint |  |
| **FirstWeekOfYear** | short |  |
| **IsEastAsia** | bool |  |
| **IsRightToLeft** | bool |  |
| **IsUIRightToLeft** | bool |  |
| **ListSeparator** | string |  |
| **LocaleId** | uint |  |
| **NegativeSign** | string |  |
| **NegNumberMode** | uint |  |
| **PM** | string |  |
| **PositiveSign** | string |  |
| **ShowWeeks** | bool |  |
| **ThousandSeparator** | string |  |
| **Time24** | bool |  |
| **TimeMarkerPosition** | uint |  |
| **TimeSeparator** | string |  |
| **TimeZone** | [TimeZone](#timezone-class) |  |
| **TimeZones** | [TimeZoneCollection](#timezonecollection-class) |  |
| **WorkDayEndHour** | short |  |
| **WorkDays** | short |  |
| **WorkDayStartHour** | short |  |
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
| **RegionalSettings(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Update()** | void |  |
# RegionalSettingsObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **TimeZone** | string |  |
| **TimeZones** | string |  |
# RegionalSettingsPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **AdjustHijriDays** | string |  |
| **AlternateCalendarType** | string |  |
| **AM** | string |  |
| **CalendarType** | string |  |
| **Collation** | string |  |
| **CollationLCID** | string |  |
| **DateFormat** | string |  |
| **DateSeparator** | string |  |
| **DecimalSeparator** | string |  |
| **DigitGrouping** | string |  |
| **FirstDayOfWeek** | string |  |
| **FirstWeekOfYear** | string |  |
| **IsEastAsia** | string |  |
| **IsRightToLeft** | string |  |
| **IsUIRightToLeft** | string |  |
| **ListSeparator** | string |  |
| **LocaleId** | string |  |
| **NegativeSign** | string |  |
| **NegNumberMode** | string |  |
| **PM** | string |  |
| **PositiveSign** | string |  |
| **ShowWeeks** | string |  |
| **ThousandSeparator** | string |  |
| **Time24** | string |  |
| **TimeMarkerPosition** | string |  |
| **TimeSeparator** | string |  |
| **WorkDayEndHour** | string |  |
| **WorkDays** | string |  |
| **WorkDayStartHour** | string |  |
# RelatedField Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **FieldId** | Guid |  |
| **ListId** | Guid |  |
| **LookupList** | [List](#list-class) |  |
| **RelationshipDeleteBehavior** | [RelationshipDeleteBehaviorType](#relationshipdeletebehaviortype-enum) |  |
| **WebId** | Guid |  |
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
| **RelatedField(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# RelatedFieldCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObjectCollection<[RelatedField](#relatedfield-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [RelatedField](#relatedfield-class) |  |
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
| **RelatedFieldCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# RelatedFieldObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **LookupList** | string |  |
# RelatedFieldPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **FieldId** | string |  |
| **ListId** | string |  |
| **RelationshipDeleteBehavior** | string |  |
| **WebId** | string |  |
# RelatedItem Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **IconUrl** | string |  |
| **ItemId** | int |  |
| **ListId** | string |  |
| **Title** | string |  |
| **Url** | string |  |
| **WebId** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# RelatedItemManager Class

Namespace: Microsoft.SharePoint.Client

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
| **RelatedItemManager(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **AddSingleLink(ClientRuntimeContext context, string SourceListName, int SourceItemID, string SourceWebUrl, string TargetListName, int TargetItemID, string TargetWebUrl, bool TryAddReverseLink)** | void |  |
| **AddSingleLinkFromUrl(ClientRuntimeContext context, string SourceItemUrl, string TargetListName, int TargetItemID, bool TryAddReverseLink)** | void |  |
| **AddSingleLinkToUrl(ClientRuntimeContext context, string SourceListName, int SourceItemID, string TargetItemUrl, bool TryAddReverseLink)** | void |  |
| **DeleteSingleLink(ClientRuntimeContext context, string SourceListName, int SourceItemID, string SourceWebUrl, string TargetListName, int TargetItemID, string TargetWebUrl, bool TryDeleteReverseLink)** | void |  |
| **GetPageOneRelatedItems(ClientRuntimeContext context, string SourceListName, int SourceItemID)** | ClientResult\<[RelatedItem](#relateditem-class)[]\> |  |
| **GetRelatedItems(ClientRuntimeContext context, string SourceListName, int SourceItemID)** | ClientResult\<[RelatedItem](#relateditem-class)[]\> |  |
# RelationshipDeleteBehaviorType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **Cascade** |  |
| **Restrict** |  |
# RemoteWeb Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **CanSendEmail** | bool |  |
| **ShareByEmailEnabled** | bool |  |
| **ShareByLinkEnabled** | bool |  |
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
| **RemoteWeb(ClientRuntimeContext context, string requestUrl)** |  |
| **RemoteWeb(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetFileByServerRelativeUrl(string serverRelativeFileUrl)** | [File](#file-class) |  |
| **GetFolderByServerRelativeUrl(string serverRelativeUrl)** | [Folder](#folder-class) |  |
| **GetGroupById(int groupId)** | [Group](#group-class) |  |
| **GetListById(Guid listGuid)** | [List](#list-class) |  |
| **GetListByServerRelativeUrl(string serverRelativeUrl)** | [List](#list-class) |  |
# RemoteWebPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **CanSendEmail** | string |  |
| **ShareByEmailEnabled** | string |  |
| **ShareByLinkEnabled** | string |  |
# RenderListContextMenuDataParameters Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **CascDelWarnMessage** | string |  |
| **CustomAction** | string |  |
| **Field** | string |  |
| **ID** | string |  |
| **InplaceFullListSearch** | string |  |
| **InplaceSearchQuery** | string |  |
| **IsCSR** | string |  |
| **IsXslView** | string |  |
| **ItemId** | string |  |
| **ListViewPageUrl** | string |  |
| **OverrideScope** | string |  |
| **RootFolder** | string |  |
| **View** | string |  |
| **ViewCount** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# RenderListDataOptions Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **ContextInfo** |  |
| **ListData** |  |
| **ListSchema** |  |
| **MenuView** |  |
| **ListContentType** |  |
| **FileSystemItemId** |  |
| **ClientFormSchema** |  |
| **QuickLaunch** |  |
| **Spotlight** |  |
| **Visualization** |  |
# RenderListDataOverrideParameters Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **CascDelWarnMessage** | string |  |
| **CustomAction** | string |  |
| **DrillDown** | string |  |
| **Field** | string |  |
| **FieldInternalName** | string |  |
| **Filter** | string |  |
| **FilterData** | string |  |
| **FilterData1** | string |  |
| **FilterData10** | string |  |
| **FilterData2** | string |  |
| **FilterData3** | string |  |
| **FilterData4** | string |  |
| **FilterData5** | string |  |
| **FilterData6** | string |  |
| **FilterData7** | string |  |
| **FilterData8** | string |  |
| **FilterData9** | string |  |
| **FilterField** | string |  |
| **FilterField1** | string |  |
| **FilterField10** | string |  |
| **FilterField2** | string |  |
| **FilterField3** | string |  |
| **FilterField4** | string |  |
| **FilterField5** | string |  |
| **FilterField6** | string |  |
| **FilterField7** | string |  |
| **FilterField8** | string |  |
| **FilterField9** | string |  |
| **FilterFields** | string |  |
| **FilterFields1** | string |  |
| **FilterFields10** | string |  |
| **FilterFields2** | string |  |
| **FilterFields3** | string |  |
| **FilterFields4** | string |  |
| **FilterFields5** | string |  |
| **FilterFields6** | string |  |
| **FilterFields7** | string |  |
| **FilterFields8** | string |  |
| **FilterFields9** | string |  |
| **FilterLookupId** | string |  |
| **FilterLookupId1** | string |  |
| **FilterLookupId10** | string |  |
| **FilterLookupId2** | string |  |
| **FilterLookupId3** | string |  |
| **FilterLookupId4** | string |  |
| **FilterLookupId5** | string |  |
| **FilterLookupId6** | string |  |
| **FilterLookupId7** | string |  |
| **FilterLookupId8** | string |  |
| **FilterLookupId9** | string |  |
| **FilterOp** | string |  |
| **FilterOp1** | string |  |
| **FilterOp10** | string |  |
| **FilterOp2** | string |  |
| **FilterOp3** | string |  |
| **FilterOp4** | string |  |
| **FilterOp5** | string |  |
| **FilterOp6** | string |  |
| **FilterOp7** | string |  |
| **FilterOp8** | string |  |
| **FilterOp9** | string |  |
| **FilterValue** | string |  |
| **FilterValue1** | string |  |
| **FilterValue10** | string |  |
| **FilterValue2** | string |  |
| **FilterValue3** | string |  |
| **FilterValue4** | string |  |
| **FilterValue5** | string |  |
| **FilterValue6** | string |  |
| **FilterValue7** | string |  |
| **FilterValue8** | string |  |
| **FilterValue9** | string |  |
| **FilterValues** | string |  |
| **FilterValues1** | string |  |
| **FilterValues10** | string |  |
| **FilterValues2** | string |  |
| **FilterValues3** | string |  |
| **FilterValues4** | string |  |
| **FilterValues5** | string |  |
| **FilterValues6** | string |  |
| **FilterValues7** | string |  |
| **FilterValues8** | string |  |
| **FilterValues9** | string |  |
| **GroupString** | string |  |
| **HasOverrideSelectCommand** | string |  |
| **ID** | string |  |
| **InplaceFullListSearch** | string |  |
| **InplaceSearchQuery** | string |  |
| **IsCSR** | string |  |
| **IsGroupRender** | string |  |
| **IsXslView** | string |  |
| **ListViewPageUrl** | string |  |
| **OverrideScope** | string |  |
| **OverrideSelectCommand** | string |  |
| **PageFirstRow** | string |  |
| **PageLastRow** | string |  |
| **RootFolder** | string |  |
| **SortDir** | string |  |
| **SortDir1** | string |  |
| **SortDir10** | string |  |
| **SortDir2** | string |  |
| **SortDir3** | string |  |
| **SortDir4** | string |  |
| **SortDir5** | string |  |
| **SortDir6** | string |  |
| **SortDir7** | string |  |
| **SortDir8** | string |  |
| **SortDir9** | string |  |
| **SortField** | string |  |
| **SortField1** | string |  |
| **SortField10** | string |  |
| **SortField2** | string |  |
| **SortField3** | string |  |
| **SortField4** | string |  |
| **SortField5** | string |  |
| **SortField6** | string |  |
| **SortField7** | string |  |
| **SortField8** | string |  |
| **SortField9** | string |  |
| **SortFields** | string |  |
| **SortFieldValues** | string |  |
| **View** | string |  |
| **ViewCount** | string |  |
| **ViewId** | string |  |
| **WebPartId** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# RenderListDataParameters Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **DatesInUtc** | bool |  |
| **FirstGroupOnly** | bool |  |
| **FolderServerRelativeUrl** | string |  |
| **OverrideViewXml** | string |  |
| **Paging** | string |  |
| **RenderOptions** | [RenderListDataOptions](#renderlistdataoptions-enum) |  |
| **ViewXml** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# RenderListFilterDataParameters Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **FieldInternalName** | string |  |
| **OverrideScope** | string |  |
| **ProcessQStringToCAML** | string |  |
| **ViewId** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# RenderListFormDataOptions Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **ExcludeListSchema** |  |
| **IncludeAttachments** |  |
| **IncludeListViewData** |  |
# RequestContext Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **List** | [List](#list-class) |  |
| **Site** | [Site](#site-class) |  |
| **Web** | [Web](#web-class) |  |
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
| **RequestContext(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetCurrent(ClientRuntimeContext Context)** | [RequestContext](#requestcontext-class) |  |
| **GetRemoteContext()** | [RequestContext](#requestcontext-class) |  |
# RequestContextObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **List** | string |  |
| **Site** | string |  |
| **Web** | string |  |
# RequestForwarder Class

Namespace: Microsoft.SharePoint.Client


## Properties

| Name | Type | Summary |
|---|---|---|
| **Url** | string |  |
| **RequestToken** | [ExternalApplicationRequestToken](#externalapplicationrequesttoken-class) |  |
| **WebRequest** | HttpWebRequest |  |
## Constructors

| Name | Summary |
|---|---|
| **RequestForwarder(HttpContext context)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **ProcessRequest()** | void |  |
# RequestResourceConstants Class

Namespace: Microsoft.SharePoint.Client


# RequestResources Class

Namespace: Microsoft.SharePoint.Client


## Properties

| Name | Type | Summary |
|---|---|---|
| **ListId** | Guid |  |
| **UserInformationList** | bool |  |
| **WebProperties** | bool |  |
| **Features** | bool |  |
| **NavigationStructure** | bool |  |
| **ViewId** | Guid |  |
# RequestUserContext Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **User** | [User](#user-class) |  |
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
| **RequestUserContext(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetCurrent(ClientRuntimeContext Context)** | [RequestUserContext](#requestusercontext-class) |  |
# RequestUserContextObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **User** | string |  |
# RequestVariable Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
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
| **RequestVariable(ClientRuntimeContext context)** |  |
| **RequestVariable(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Append(string value)** | void |  |
| **Set(string value)** | void |  |
# RequestVariablePropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Value** | string |  |
# RoleAssignment Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Member** | [Principal](#principal-class) |  |
| **PrincipalId** | int |  |
| **RoleDefinitionBindings** | [RoleDefinitionBindingCollection](#roledefinitionbindingcollection-class) |  |
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
| **RoleAssignment(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
| **ImportRoleDefinitionBindings(RoleDefinitionBindingCollection roleDefinitionBindings)** | void |  |
| **Update()** | void |  |
# RoleAssignmentCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObjectCollection<[RoleAssignment](#roleassignment-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Groups** | [GroupCollection](#groupcollection-class) |  |
| **Item** | [RoleAssignment](#roleassignment-class) |  |
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
| **RoleAssignmentCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(Principal principal, RoleDefinitionBindingCollection roleBindings)** | [RoleAssignment](#roleassignment-class) |  |
| **GetByPrincipal(Principal principalToFind)** | [RoleAssignment](#roleassignment-class) |  |
| **GetByPrincipalId(int principalId)** | [RoleAssignment](#roleassignment-class) |  |
# RoleAssignmentCollectionObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Groups** | string |  |
# RoleAssignmentObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Member** | string |  |
| **RoleDefinitionBindings** | string |  |
# RoleAssignmentPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **PrincipalId** | string |  |
# RoleDefinition Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **BasePermissions** | [BasePermissions](#basepermissions-class) |  |
| **Description** | string |  |
| **Hidden** | bool |  |
| **Id** | int |  |
| **Name** | string |  |
| **Order** | int |  |
| **RoleTypeKind** | [RoleType](#roletype-enum) |  |
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
| **RoleDefinition(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
| **Update()** | void |  |
# RoleDefinitionBindingCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObjectCollection<[RoleDefinition](#roledefinition-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [RoleDefinition](#roledefinition-class) |  |
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
| **RoleDefinitionBindingCollection(ClientRuntimeContext context)** |  |
| **RoleDefinitionBindingCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(RoleDefinition roleDefinition)** | void |  |
| **Remove(RoleDefinition roleDefinition)** | void |  |
| **RemoveAll()** | void |  |
# RoleDefinitionCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObjectCollection<[RoleDefinition](#roledefinition-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [RoleDefinition](#roledefinition-class) |  |
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
| **RoleDefinitionCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(RoleDefinitionCreationInformation parameters)** | [RoleDefinition](#roledefinition-class) |  |
| **GetById(int id)** | [RoleDefinition](#roledefinition-class) |  |
| **GetByName(string name)** | [RoleDefinition](#roledefinition-class) |  |
| **GetByType(RoleType roleType)** | [RoleDefinition](#roledefinition-class) |  |
| **RecreateMissingDefaultRoleDefinitions()** | void |  |
# RoleDefinitionCreationInformation Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **BasePermissions** | [BasePermissions](#basepermissions-class) |  |
| **Description** | string |  |
| **Name** | string |  |
| **Order** | int |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# RoleDefinitionPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **BasePermissions** | string |  |
| **Description** | string |  |
| **Hidden** | string |  |
| **Id** | string |  |
| **Name** | string |  |
| **Order** | string |  |
| **RoleTypeKind** | string |  |
# RoleType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **Guest** |  |
| **Reader** |  |
| **Contributor** |  |
| **WebDesigner** |  |
| **Administrator** |  |
| **Editor** |  |
# RuleOverrideOptions Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **Allow** |  |
| **AllowWithJustification** |  |
# SandboxedCodeActivationCapabilities Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Check** |  |
| **Disabled** |  |
| **Enabled** |  |
# SaveBinaryCheckMode Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **ETag** |  |
| **Overwrite** |  |
# ScriptTypeFactory Class

Namespace: Microsoft.SharePoint.Client


## Methods

| Name | Returns | Summary |
|---|---|---|
| **CreateObjectFromScriptType(string scriptType, ClientRuntimeContext context)** | IFromJson |  |
# SecurableObject Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **FirstUniqueAncestorSecurableObject** | [SecurableObject](#securableobject-class) |  |
| **HasUniqueRoleAssignments** | bool |  |
| **RoleAssignments** | [RoleAssignmentCollection](#roleassignmentcollection-class) |  |
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
| **SecurableObject(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **BreakRoleInheritance(bool copyRoleAssignments, bool clearSubscopes)** | void |  |
| **ResetRoleInheritance()** | void |  |
# SecurableObjectObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **FirstUniqueAncestorSecurableObject** | string |  |
| **RoleAssignments** | string |  |
# SecurableObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **HasUniqueRoleAssignments** | string |  |
# ServerSettings Class

Namespace: Microsoft.SharePoint.Client


## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetAlternateUrls(ClientRuntimeContext context)** | ClientObjectList\<[AlternateUrl](#alternateurl-class)\> |  |
| **GetGlobalInstalledLanguages(ClientRuntimeContext context, int compatibilityLevel)** | ClientResult\<[Language](#language-class)[]\> |  |
| **IsSharePointOnline(ClientRuntimeContext context)** | ClientResult\<bool\> |  |
# SharedWithUser Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Email** | string |  |
| **Name** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SharedWithUserCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObjectCollection<[SharedWithUser](#sharedwithuser-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **TypeId** | string |  |
| **ChildItemsName** | string |  |
| **Count** | int |  |
| **Item** | [SharedWithUser](#sharedwithuser-class) |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SharePointSharingSettings Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AddToGroupModeName** | string |  |
| **GroupNameLines** | IEnumerable\<string\> |  |
| **GroupRoleDefinitionNamesLines** | IEnumerable\<string\> |  |
| **IsMobileView** | bool |  |
| **PanelGivePermissionsVisible** | bool |  |
| **PanelShowHideMoreOptionsVisible** | bool |  |
| **PanelSimplifiedRoleSelectorVisible** | bool |  |
| **PickerProperties** | [PickerSettings](#pickersettings-class) |  |
| **RequiredScriptFileLinks** | IEnumerable\<string\> |  |
| **RoleDefinitionNameLines** | IEnumerable\<string\> |  |
| **SelectedGroup** | string |  |
| **SharedWithEnabled** | bool |  |
| **SharingCssLink** | string |  |
| **TabbedDialogEnabled** | bool |  |
| **TabToShow** | int |  |
| **txtEmailSubjectText** | string |  |
| **UserDisplayUrl** | string |  |
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
| **SharePointSharingSettings(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# SharePointSharingSettingsObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **PickerProperties** | string |  |
# SharePointSharingSettingsPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **AddToGroupModeName** | string |  |
| **GroupNameLines** | string |  |
| **GroupRoleDefinitionNamesLines** | string |  |
| **IsMobileView** | string |  |
| **PanelGivePermissionsVisible** | string |  |
| **PanelShowHideMoreOptionsVisible** | string |  |
| **PanelSimplifiedRoleSelectorVisible** | string |  |
| **RequiredScriptFileLinks** | string |  |
| **RoleDefinitionNameLines** | string |  |
| **SelectedGroup** | string |  |
| **SharedWithEnabled** | string |  |
| **SharingCssLink** | string |  |
| **TabbedDialogEnabled** | string |  |
| **TabToShow** | string |  |
| **txtEmailSubjectText** | string |  |
| **UserDisplayUrl** | string |  |
# SharingLinkInfo Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **IsActive** | bool |  |
| **LinkKind** | [SharingLinkKind](#sharinglinkkind-enum) |  |
| **Url** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SharingLinkKind Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Uninitialized** |  |
| **Direct** |  |
| **OrganizationView** |  |
| **OrganizationEdit** |  |
| **AnonymousView** |  |
| **AnonymousEdit** |  |
# SharingOperationStatusCode Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **CompletedSuccessfully** |  |
| **AccessRequestsQueued** |  |
| **UnknowError** |  |
| **CrossSiteRequestNotSupported** |  |
| **AccessDenied** |  |
| **NoResolvedUsers** |  |
# SharingPermissionInformation Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **IsDefaultPermission** | bool |  |
| **PermissionDescription** | string |  |
| **PermissionId** | string |  |
| **PermissionKind** | [SharingPermissionKind](#sharingpermissionkind-enum) |  |
| **PermissionName** | string |  |
| **PermissionRoleType** | [RoleType](#roletype-enum) |  |
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
| **SharingPermissionInformation(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# SharingPermissionInformationCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObjectCollection<[SharingPermissionInformation](#sharingpermissioninformation-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [SharingPermissionInformation](#sharingpermissioninformation-class) |  |
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
| **SharingPermissionInformationCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# SharingPermissionInformationPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **IsDefaultPermission** | string |  |
| **PermissionDescription** | string |  |
| **PermissionId** | string |  |
| **PermissionKind** | string |  |
| **PermissionName** | string |  |
| **PermissionRoleType** | string |  |
# SharingPermissionKind Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Group** |  |
| **Role** |  |
# SharingResult Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ErrorMessage** | string |  |
| **GroupsSharedWith** | [GroupCollection](#groupcollection-class) |  |
| **GroupUsersAddedTo** | [Group](#group-class) |  |
| **IconUrl** | string |  |
| **InvitedUsers** | IList\<[SPInvitationCreationResult](#spinvitationcreationresult-class)\> |  |
| **Name** | string |  |
| **PermissionsPageRelativeUrl** | string |  |
| **StatusCode** | [SharingOperationStatusCode](#sharingoperationstatuscode-enum) |  |
| **UniquelyPermissionedUsers** | IList\<[UserSharingResult](#usersharingresult-class)\> |  |
| **Url** | string |  |
| **UsersAddedToGroup** | IList\<[UserSharingResult](#usersharingresult-class)\> |  |
| **UsersWithAccessRequests** | [SharingUserCollection](#sharingusercollection-class) |  |
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
| **SharingResult(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# SharingResultObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **GroupsSharedWith** | string |  |
| **GroupUsersAddedTo** | string |  |
| **UsersWithAccessRequests** | string |  |
# SharingResultPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **ErrorMessage** | string |  |
| **IconUrl** | string |  |
| **InvitedUsers** | string |  |
| **Name** | string |  |
| **PermissionsPageRelativeUrl** | string |  |
| **StatusCode** | string |  |
| **UniquelyPermissionedUsers** | string |  |
| **Url** | string |  |
| **UsersAddedToGroup** | string |  |
# SharingUserCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObjectCollection<[User](#user-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [User](#user-class) |  |
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
| **SharingUserCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# Site Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AllowCreateDeclarativeWorkflow** | bool |  |
| **AllowDesigner** | bool |  |
| **AllowMasterPageEditing** | bool |  |
| **AllowRevertFromTemplate** | bool |  |
| **AllowSaveDeclarativeWorkflowAsTemplate** | bool |  |
| **AllowSavePublishDeclarativeWorkflow** | bool |  |
| **AllowSelfServiceUpgrade** | bool |  |
| **AllowSelfServiceUpgradeEvaluation** | bool |  |
| **Audit** | [Audit](#audit-class) |  |
| **AuditLogTrimmingRetention** | int |  |
| **CanUpgrade** | bool |  |
| **CompatibilityLevel** | int |  |
| **CurrentChangeToken** | [ChangeToken](#changetoken-class) |  |
| **DisableCompanyWideSharingLinks** | bool |  |
| **EventReceivers** | [EventReceiverDefinitionCollection](#eventreceiverdefinitioncollection-class) |  |
| **ExternalSharingTipsEnabled** | bool |  |
| **Features** | [FeatureCollection](#featurecollection-class) |  |
| **Id** | Guid |  |
| **LockIssue** | string |  |
| **MaxItemsPerThrottledOperation** | uint |  |
| **NeedsB2BUpgrade** | bool |  |
| **Owner** | [User](#user-class) |  |
| **PrimaryUri** | string |  |
| **ReadOnly** | bool |  |
| **RecycleBin** | [RecycleBinItemCollection](#recyclebinitemcollection-class) |  |
| **RequiredDesignerVersion** | string |  |
| **RootWeb** | [Web](#web-class) |  |
| **SandboxedCodeActivationCapability** | [SandboxedCodeActivationCapabilities](#sandboxedcodeactivationcapabilities-enum) |  |
| **SecondaryContact** | [User](#user-class) |  |
| **ServerRelativeUrl** | string |  |
| **ShareByEmailEnabled** | bool |  |
| **ShareByLinkEnabled** | bool |  |
| **ShowUrlStructure** | bool |  |
| **TrimAuditLog** | bool |  |
| **UIVersionConfigurationEnabled** | bool |  |
| **UpgradeInfo** | [UpgradeInfo](#upgradeinfo-class) |  |
| **UpgradeReminderDate** | DateTime |  |
| **UpgradeScheduled** | bool |  |
| **UpgradeScheduledDate** | DateTime |  |
| **Upgrading** | bool |  |
| **Url** | string |  |
| **Usage** | [UsageInfo](#usageinfo-class) |  |
| **UserCustomActions** | [UserCustomActionCollection](#usercustomactioncollection-class) |  |
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
| **Site(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **CreateMigrationIngestionJob(Guid gWebId, string azureContainerSourceUri, string azureContainerManifestUri, string azureQueueReportUri, IngestionTaskKey ingestionTaskKey)** | ClientResult\<Guid\> |  |
| **CreateMigrationJob(Guid gWebId, string azureContainerSourceUri, string azureContainerManifestUri, string azureQueueReportUri)** | ClientResult\<Guid\> |  |
| **CreateMigrationJobEncrypted(Guid gWebId, string azureContainerSourceUri, string azureContainerManifestUri, string azureQueueReportUri, EncryptionOption options)** | ClientResult\<Guid\> |  |
| **CreatePreviewSPSite(bool upgrade, bool sendemail)** | void |  |
| **DeleteMigrationJob(Guid id)** | ClientResult\<bool\> |  |
| **ExtendUpgradeReminderDate()** | void |  |
| **GetCatalog(int typeCatalog)** | [List](#list-class) |  |
| **GetChanges(ChangeQuery query)** | [ChangeCollection](#changecollection-class) |  |
| **GetCustomListTemplates(Web web)** | [ListTemplateCollection](#listtemplatecollection-class) |  |
| **GetMigrationJobStatus(Guid id)** | ClientResult\<[MigrationJobState](#migrationjobstate-enum)\> |  |
| **GetMigrationStatus()** | [SPMigrationJobStatusCollection](#spmigrationjobstatuscollection-class) |  |
| **GetRecycleBinItems(string pagingInfo, int rowLimit, bool isAscending, RecycleBinOrderBy orderBy, RecycleBinItemState itemState)** | [RecycleBinItemCollection](#recyclebinitemcollection-class) |  |
| **GetWebTemplates(uint LCID, int overrideCompatLevel)** | [WebTemplateCollection](#webtemplatecollection-class) |  |
| **Invalidate()** | void |  |
| **NeedsUpgradeByType(bool versionUpgrade, bool recursive)** | ClientResult\<bool\> |  |
| **OpenWeb(string strUrl)** | [Web](#web-class) |  |
| **OpenWebById(Guid gWebId)** | [Web](#web-class) |  |
| **RunHealthCheck(Guid ruleId, bool bRepair, bool bRunAlways)** | [SiteHealthSummary](#sitehealthsummary-class) |  |
| **RunUpgradeSiteSession(bool versionUpgrade, bool queueOnly, bool sendEmail)** | void |  |
| **UpdateClientObjectModelUseRemoteAPIsPermissionSetting(bool requireUseRemoteAPIs)** | void |  |
# SiteObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Audit** | string |  |
| **EventReceivers** | string |  |
| **Features** | string |  |
| **Owner** | string |  |
| **RecycleBin** | string |  |
| **RootWeb** | string |  |
| **SecondaryContact** | string |  |
| **UserCustomActions** | string |  |
# SitePropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **AllowCreateDeclarativeWorkflow** | string |  |
| **AllowDesigner** | string |  |
| **AllowMasterPageEditing** | string |  |
| **AllowRevertFromTemplate** | string |  |
| **AllowSaveDeclarativeWorkflowAsTemplate** | string |  |
| **AllowSavePublishDeclarativeWorkflow** | string |  |
| **AllowSelfServiceUpgrade** | string |  |
| **AllowSelfServiceUpgradeEvaluation** | string |  |
| **AuditLogTrimmingRetention** | string |  |
| **CanUpgrade** | string |  |
| **CompatibilityLevel** | string |  |
| **CurrentChangeToken** | string |  |
| **DisableCompanyWideSharingLinks** | string |  |
| **ExternalSharingTipsEnabled** | string |  |
| **Id** | string |  |
| **LockIssue** | string |  |
| **MaxItemsPerThrottledOperation** | string |  |
| **NeedsB2BUpgrade** | string |  |
| **PrimaryUri** | string |  |
| **ReadOnly** | string |  |
| **RequiredDesignerVersion** | string |  |
| **SandboxedCodeActivationCapability** | string |  |
| **ServerRelativeUrl** | string |  |
| **ShareByEmailEnabled** | string |  |
| **ShareByLinkEnabled** | string |  |
| **ShowUrlStructure** | string |  |
| **TrimAuditLog** | string |  |
| **UIVersionConfigurationEnabled** | string |  |
| **UpgradeInfo** | string |  |
| **UpgradeReminderDate** | string |  |
| **UpgradeScheduled** | string |  |
| **UpgradeScheduledDate** | string |  |
| **Upgrading** | string |  |
| **Url** | string |  |
| **Usage** | string |  |
# SiteUrl Class

Namespace: Microsoft.SharePoint.Client

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
| **SiteUrl(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# SPClientUtility Class

Namespace: Microsoft.SharePoint.Client


## Properties

| Name | Type | Summary |
|---|---|---|
| **ODataNamespaceManager** | XmlNamespaceManager |  |
# SPDataLeakagePreventionStatusInfo Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ContainsConfidentialInfo** | bool |  |
| **ContainsConfidentialInfoLearnMoreUrl** | string |  |
| **ExternalSharingTipsEnabled** | bool |  |
| **ExternalSharingTipsLearnMoreUrl** | string |  |
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
| **SPDataLeakagePreventionStatusInfo(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# SPDataLeakagePreventionStatusInfoPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **ContainsConfidentialInfo** | string |  |
| **ContainsConfidentialInfoLearnMoreUrl** | string |  |
| **ExternalSharingTipsEnabled** | string |  |
| **ExternalSharingTipsLearnMoreUrl** | string |  |
# SpecialFolderType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Attachment** |  |
| **Photos** |  |
| **CameraRoll** |  |
| **Music** |  |
| **Apps** |  |
| **AppRoot** |  |
# SPEffectiveInformationRightsManagementSettingsSource Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **File** |  |
| **List** |  |
| **Rule** |  |
# SPInvitationCreationResult Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Email** | string |  |
| **InvitationLink** | string |  |
| **Succeeded** | bool |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SPMigrationJobStatus Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **JobId** | Guid |  |
| **JobState** | [MigrationJobState](#migrationjobstate-enum) |  |
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
| **SPMigrationJobStatus(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# SPMigrationJobStatusCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObjectCollection<[SPMigrationJobStatus](#spmigrationjobstatus-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [SPMigrationJobStatus](#spmigrationjobstatus-class) |  |
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
| **SPMigrationJobStatusCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# SPMigrationJobStatusPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **JobId** | string |  |
| **JobState** | string |  |
# StorageMetrics Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **LastModified** | DateTime |  |
| **TotalFileCount** | long |  |
| **TotalFileStreamSize** | long |  |
| **TotalSize** | long |  |
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
| **StorageMetrics(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# StorageMetricsPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **LastModified** | string |  |
| **TotalFileCount** | string |  |
| **TotalFileStreamSize** | string |  |
| **TotalSize** | string |  |
# SubwebQuery Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ConfigurationFilter** | int |  |
| **WebTemplateFilter** | int |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# TemplateFileType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **StandardPage** |  |
| **WikiPage** |  |
| **FormPage** |  |
# TenantAppInformation Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AppPrincipalId** | string |  |
| **AppWebFullUrl** | string |  |
| **CreationTime** | DateTime |  |
| **IconAbsoluteUrl** | string |  |
| **IconFallbackAbsoluteUrl** | string |  |
| **Id** | Guid |  |
| **LaunchUrl** | string |  |
| **PackageFingerprint** | byte[] |  |
| **ProductId** | Guid |  |
| **RemoteAppUrl** | string |  |
| **Status** | [AppInstanceStatus](#appinstancestatus-enum) |  |
| **Title** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# TenantAppInstance Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Id** | Guid |  |
| **SiteId** | Guid |  |
| **WebId** | Guid |  |
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
| **TenantAppInstance(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# TenantAppInstancePropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Id** | string |  |
| **SiteId** | string |  |
| **WebId** | string |  |
# TenantAppUtility Class

Namespace: Microsoft.SharePoint.Client


## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetAppDetails(ClientRuntimeContext context, Web web, TenantAppInstance tenantAppInstance)** | [AppDetails](#appdetails-class) |  |
| **GetAppIcon(ClientRuntimeContext context, Web web, Guid appInstanceId, byte[] packageFingerprint)** | [AppIconInfo](#appiconinfo-class) |  |
| **GetAppPermissionDescriptions(ClientRuntimeContext context, Web web, TenantAppInstance tenantAppInstance)** | ClientArrayResult\<string\> |  |
| **GetTenantAppInformationCollection(ClientRuntimeContext context, Web web, int lcid)** | IList\<[TenantAppInformation](#tenantappinformation-class)\> |  |
| **GetTenantAppInstance(ClientRuntimeContext context, Web web, Guid appInstance)** | [TenantAppInstance](#tenantappinstance-class) |  |
# TenantSettings Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **CorporateCatalogUrl** | string |  |
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
| **TenantSettings(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetCurrent(ClientRuntimeContext Context)** | [TenantSettings](#tenantsettings-class) |  |
# TenantSettingsPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **CorporateCatalogUrl** | string |  |
# ThemeInfo Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AccessibleDescription** | string |  |
| **ThemeBackgroundImageUri** | string |  |
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
| **ThemeInfo(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetThemeFontByName(string name, uint lcid)** | ClientResult\<string\> |  |
| **GetThemeShadeByName(string name)** | ClientResult\<string\> |  |
# ThemeInfoPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **AccessibleDescription** | string |  |
| **ThemeBackgroundImageUri** | string |  |
# TimeZone Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Description** | string |  |
| **Id** | int |  |
| **Information** | [TimeZoneInformation](#timezoneinformation-class) |  |
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
| **TimeZone(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **LocalTimeToUTC(DateTime date)** | ClientResult\<DateTime\> |  |
| **UTCToLocalTime(DateTime date)** | ClientResult\<DateTime\> |  |
# TimeZoneCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObjectCollection<[TimeZone](#timezone-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [TimeZone](#timezone-class) |  |
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
| **TimeZoneCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetById(int id)** | [TimeZone](#timezone-class) |  |
# TimeZoneInformation Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Bias** | int |  |
| **DaylightBias** | int |  |
| **StandardBias** | int |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# TimeZonePropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Description** | string |  |
| **Id** | string |  |
| **Information** | string |  |
# UpgradeInfo Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ErrorFile** | string |  |
| **Errors** | int |  |
| **LastUpdated** | DateTime |  |
| **LogFile** | string |  |
| **RequestDate** | DateTime |  |
| **RetryCount** | int |  |
| **StartTime** | DateTime |  |
| **Status** | [UpgradeStatus](#upgradestatus-enum) |  |
| **UpgradeType** | [UpgradeType](#upgradetype-enum) |  |
| **Warnings** | int |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# UpgradeStatus Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **InProgress** |  |
| **Failed** |  |
| **Completed** |  |
# UpgradeType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **BuildUpgrade** |  |
| **VersionUpgrade** |  |
# UrlFieldFormatType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Hyperlink** |  |
| **Image** |  |
# UrlZone Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **DefaultZone** |  |
| **Intranet** |  |
| **Internet** |  |
| **Custom** |  |
| **Extranet** |  |
# UsageInfo Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Bandwidth** | long |  |
| **DiscussionStorage** | long |  |
| **Hits** | long |  |
| **Storage** | long |  |
| **StoragePercentageUsed** | double |  |
| **Visits** | long |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# User Class

Namespace: Microsoft.SharePoint.Client

Base class: [Principal](#principal-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **Email** | string |  |
| **Groups** | [GroupCollection](#groupcollection-class) |  |
| **IsShareByEmailGuestUser** | bool |  |
| **IsSiteAdmin** | bool |  |
| **UserId** | [UserIdInfo](#useridinfo-class) |  |
| **Id** | int |  |
| **IsHiddenInUI** | bool |  |
| **LoginName** | string |  |
| **Title** | string |  |
| **PrincipalType** | [PrincipalType](#principaltype-enum) |  |
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
| **User(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Update()** | void |  |
# UserCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObjectCollection<[User](#user-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [User](#user-class) |  |
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
| **UserCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(UserCreationInformation parameters)** | [User](#user-class) |  |
| **AddUser(User user)** | [User](#user-class) |  |
| **GetByEmail(string emailAddress)** | [User](#user-class) |  |
| **GetById(int id)** | [User](#user-class) |  |
| **GetByLoginName(string loginName)** | [User](#user-class) |  |
| **Remove(User user)** | void |  |
| **RemoveById(int id)** | void |  |
| **RemoveByLoginName(string loginName)** | void |  |
# UserCreationInformation Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Email** | string |  |
| **LoginName** | string |  |
| **Title** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# UserCustomAction Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **CommandUIExtension** | string |  |
| **Description** | string |  |
| **DescriptionResource** | [UserResource](#userresource-class) |  |
| **Group** | string |  |
| **Id** | Guid |  |
| **ImageUrl** | string |  |
| **Location** | string |  |
| **Name** | string |  |
| **RegistrationId** | string |  |
| **RegistrationType** | [UserCustomActionRegistrationType](#usercustomactionregistrationtype-enum) |  |
| **Rights** | [BasePermissions](#basepermissions-class) |  |
| **Scope** | [UserCustomActionScope](#usercustomactionscope-enum) |  |
| **ScriptBlock** | string |  |
| **ScriptSrc** | string |  |
| **Sequence** | int |  |
| **Title** | string |  |
| **TitleResource** | [UserResource](#userresource-class) |  |
| **Url** | string |  |
| **VersionOfUserCustomAction** | string |  |
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
| **UserCustomAction(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
| **Update()** | void |  |
# UserCustomActionCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObjectCollection<[UserCustomAction](#usercustomaction-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [UserCustomAction](#usercustomaction-class) |  |
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
| **UserCustomActionCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add()** | [UserCustomAction](#usercustomaction-class) |  |
| **Clear()** | void |  |
| **GetById(Guid id)** | [UserCustomAction](#usercustomaction-class) |  |
# UserCustomActionObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **DescriptionResource** | string |  |
| **TitleResource** | string |  |
# UserCustomActionPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **CommandUIExtension** | string |  |
| **Description** | string |  |
| **Group** | string |  |
| **Id** | string |  |
| **ImageUrl** | string |  |
| **Location** | string |  |
| **Name** | string |  |
| **RegistrationId** | string |  |
| **RegistrationType** | string |  |
| **Rights** | string |  |
| **Scope** | string |  |
| **ScriptBlock** | string |  |
| **ScriptSrc** | string |  |
| **Sequence** | string |  |
| **Title** | string |  |
| **Url** | string |  |
| **VersionOfUserCustomAction** | string |  |
# UserCustomActionRegistrationType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **List** |  |
| **ContentType** |  |
| **ProgId** |  |
| **FileType** |  |
# UserCustomActionScope Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Unknown** |  |
| **Site** |  |
| **Web** |  |
| **List** |  |
# UserIdInfo Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **NameId** | string |  |
| **NameIdIssuer** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# UserObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Groups** | string |  |
# UserPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Email** | string |  |
| **IsShareByEmailGuestUser** | string |  |
| **IsSiteAdmin** | string |  |
| **UserId** | string |  |
# UserResource Class

Namespace: Microsoft.SharePoint.Client

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
| **UserResource(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetValueForUICulture(string cultureName)** | ClientResult\<string\> |  |
| **SetValueForUICulture(string cultureName, string value)** | void |  |
# UserResourceScope Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Web** |  |
| **List** |  |
# UserResourceType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **SingleLine** |  |
| **MultiLine** |  |
# UserSharingCapabilities Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **CanShareInternally** |  |
| **CanShareExternally** |  |
| **CanUseReadonlyLink** |  |
| **CanManageReadonlyLink** |  |
| **CanUseReadWriteLink** |  |
| **CanManageReadWriteLink** |  |
| **CanUseOrganizationReadonlyLink** |  |
| **CanManageOrganizationReadonlyLink** |  |
| **CanUseOrganizationReadWriteLink** |  |
| **CanManageOrganizationReadWriteLink** |  |
# View Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Aggregations** | string |  |
| **AggregationsStatus** | string |  |
| **BaseViewId** | string |  |
| **ContentTypeId** | [ContentTypeId](#contenttypeid-class) |  |
| **DefaultView** | bool |  |
| **DefaultViewForContentType** | bool |  |
| **EditorModified** | bool |  |
| **Formats** | string |  |
| **Hidden** | bool |  |
| **HtmlSchemaXml** | string |  |
| **Id** | Guid |  |
| **ImageUrl** | string |  |
| **IncludeRootFolder** | bool |  |
| **ViewJoins** | string |  |
| **JSLink** | string |  |
| **ListViewXml** | string |  |
| **Method** | string |  |
| **MobileDefaultView** | bool |  |
| **MobileView** | bool |  |
| **ModerationType** | string |  |
| **OrderedView** | bool |  |
| **Paged** | bool |  |
| **PersonalView** | bool |  |
| **ViewProjectedFields** | string |  |
| **ViewQuery** | string |  |
| **ReadOnlyView** | bool |  |
| **RequiresClientIntegration** | bool |  |
| **RowLimit** | uint |  |
| **Scope** | [ViewScope](#viewscope-enum) |  |
| **ServerRelativeUrl** | string |  |
| **StyleId** | string |  |
| **Threaded** | bool |  |
| **Title** | string |  |
| **Toolbar** | string |  |
| **ToolbarTemplateName** | string |  |
| **ViewType** | string |  |
| **ViewData** | string |  |
| **ViewFields** | [ViewFieldCollection](#viewfieldcollection-class) |  |
| **VisualizationInfo** | [Visualization](#visualization-class) |  |
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
| **View(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
| **RenderAsHtml()** | ClientResult\<string\> |  |
| **Update()** | void |  |
# ViewCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObjectCollection<[View](#view-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [View](#view-class) |  |
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
| **ViewCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(ViewCreationInformation parameters)** | [View](#view-class) |  |
| **GetById(Guid guidId)** | [View](#view-class) |  |
| **GetByTitle(string strTitle)** | [View](#view-class) |  |
# ViewCreationInformation Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Paged** | bool |  |
| **PersonalView** | bool |  |
| **Query** | string |  |
| **RowLimit** | uint |  |
| **SetAsDefaultView** | bool |  |
| **Title** | string |  |
| **ViewFields** | string[] |  |
| **ViewTypeKind** | [ViewType](#viewtype-enum) |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# ViewFieldCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObjectCollection<string>


## Properties

| Name | Type | Summary |
|---|---|---|
| **SchemaXml** | string |  |
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
| **ViewFieldCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(string strField)** | void |  |
| **MoveFieldTo(string field, int index)** | void |  |
| **Remove(string strField)** | void |  |
| **RemoveAll()** | void |  |
# ViewFieldCollectionPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **SchemaXml** | string |  |
# ViewObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **ViewFields** | string |  |
# ViewPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Aggregations** | string |  |
| **AggregationsStatus** | string |  |
| **BaseViewId** | string |  |
| **ContentTypeId** | string |  |
| **DefaultView** | string |  |
| **DefaultViewForContentType** | string |  |
| **EditorModified** | string |  |
| **Formats** | string |  |
| **Hidden** | string |  |
| **HtmlSchemaXml** | string |  |
| **Id** | string |  |
| **ImageUrl** | string |  |
| **IncludeRootFolder** | string |  |
| **ViewJoins** | string |  |
| **JSLink** | string |  |
| **ListViewXml** | string |  |
| **Method** | string |  |
| **MobileDefaultView** | string |  |
| **MobileView** | string |  |
| **ModerationType** | string |  |
| **OrderedView** | string |  |
| **Paged** | string |  |
| **PersonalView** | string |  |
| **ViewProjectedFields** | string |  |
| **ViewQuery** | string |  |
| **ReadOnlyView** | string |  |
| **RequiresClientIntegration** | string |  |
| **RowLimit** | string |  |
| **Scope** | string |  |
| **ServerRelativeUrl** | string |  |
| **StyleId** | string |  |
| **Threaded** | string |  |
| **Title** | string |  |
| **Toolbar** | string |  |
| **ToolbarTemplateName** | string |  |
| **ViewType** | string |  |
| **ViewData** | string |  |
| **VisualizationInfo** | string |  |
# ViewScope Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **DefaultValue** |  |
| **Recursive** |  |
| **RecursiveAll** |  |
| **FilesOnly** |  |
# ViewType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **Html** |  |
| **Grid** |  |
| **Recurrence** |  |
| **Chart** |  |
| **Calendar** |  |
| **Gantt** |  |
# Visualization Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **DefaultScreen** | [VisualizationStyleSet](#visualizationstyleset-class) |  |
| **MediumScreen** | [VisualizationStyleSet](#visualizationstyleset-class) |  |
| **SmallScreen** | [VisualizationStyleSet](#visualizationstyleset-class) |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# VisualizationField Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **InternalName** | string |  |
| **Style** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# VisualizationStyleSet Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AspectRatio** | string |  |
| **BackgroundColor** | string |  |
| **Fields** | IList\<[VisualizationField](#visualizationfield-class)\> |  |
| **MinHeight** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# Web Class

Namespace: Microsoft.SharePoint.Client

Base class: [SecurableObject](#securableobject-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **AllowCreateDeclarativeWorkflowForCurrentUser** | bool |  |
| **AllowDesignerForCurrentUser** | bool |  |
| **AllowMasterPageEditingForCurrentUser** | bool |  |
| **AllowRevertFromTemplateForCurrentUser** | bool |  |
| **AllowRssFeeds** | bool |  |
| **AllowSaveDeclarativeWorkflowAsTemplateForCurrentUser** | bool |  |
| **AllowSavePublishDeclarativeWorkflowForCurrentUser** | bool |  |
| **AllProperties** | [PropertyValues](#propertyvalues-class) |  |
| **AlternateCssUrl** | string |  |
| **AppInstanceId** | Guid |  |
| **AppTiles** | [AppTileCollection](#apptilecollection-class) |  |
| **AssociatedMemberGroup** | [Group](#group-class) |  |
| **AssociatedOwnerGroup** | [Group](#group-class) |  |
| **AssociatedVisitorGroup** | [Group](#group-class) |  |
| **AvailableContentTypes** | [ContentTypeCollection](#contenttypecollection-class) |  |
| **AvailableFields** | [FieldCollection](#fieldcollection-class) |  |
| **Configuration** | short |  |
| **ContainsConfidentialInfo** | bool |  |
| **ContentTypes** | [ContentTypeCollection](#contenttypecollection-class) |  |
| **Created** | DateTime |  |
| **CurrentChangeToken** | [ChangeToken](#changetoken-class) |  |
| **CurrentUser** | [User](#user-class) |  |
| **CustomMasterUrl** | string |  |
| **DataLeakagePreventionStatusInfo** | [SPDataLeakagePreventionStatusInfo](#spdataleakagepreventionstatusinfo-class) |  |
| **Description** | string |  |
| **DescriptionResource** | [UserResource](#userresource-class) |  |
| **DesignerDownloadUrlForCurrentUser** | string |  |
| **DocumentLibraryCalloutOfficeWebAppPreviewersDisabled** | bool |  |
| **EffectiveBasePermissions** | [BasePermissions](#basepermissions-class) |  |
| **EnableMinimalDownload** | bool |  |
| **EventReceivers** | [EventReceiverDefinitionCollection](#eventreceiverdefinitioncollection-class) |  |
| **Features** | [FeatureCollection](#featurecollection-class) |  |
| **Fields** | [FieldCollection](#fieldcollection-class) |  |
| **Folders** | [FolderCollection](#foldercollection-class) |  |
| **Id** | Guid |  |
| **IsMultilingual** | bool |  |
| **Language** | uint |  |
| **LastItemModifiedDate** | DateTime |  |
| **Lists** | [ListCollection](#listcollection-class) |  |
| **ListTemplates** | [ListTemplateCollection](#listtemplatecollection-class) |  |
| **MasterUrl** | string |  |
| **MembersCanShare** | bool |  |
| **Navigation** | [Navigation](#navigation-class) |  |
| **NoCrawl** | bool |  |
| **OverwriteTranslationsOnChange** | bool |  |
| **ParentWeb** | [WebInformation](#webinformation-class) |  |
| **PushNotificationSubscribers** | [PushNotificationSubscriberCollection](#pushnotificationsubscribercollection-class) |  |
| **QuickLaunchEnabled** | bool |  |
| **RecycleBin** | [RecycleBinItemCollection](#recyclebinitemcollection-class) |  |
| **RecycleBinEnabled** | bool |  |
| **RegionalSettings** | [RegionalSettings](#regionalsettings-class) |  |
| **RequestAccessEmail** | string |  |
| **RoleDefinitions** | [RoleDefinitionCollection](#roledefinitioncollection-class) |  |
| **RootFolder** | [Folder](#folder-class) |  |
| **SaveSiteAsTemplateEnabled** | bool |  |
| **ServerRelativeUrl** | string |  |
| **ShowUrlStructureForCurrentUser** | bool |  |
| **SiteGroups** | [GroupCollection](#groupcollection-class) |  |
| **SiteLogoUrl** | string |  |
| **SiteUserInfoList** | [List](#list-class) |  |
| **SiteUsers** | [UserCollection](#usercollection-class) |  |
| **SupportedUILanguageIds** | IEnumerable\<int\> |  |
| **SyndicationEnabled** | bool |  |
| **ThemeInfo** | [ThemeInfo](#themeinfo-class) |  |
| **ThirdPartyMdmEnabled** | bool |  |
| **Title** | string |  |
| **TitleResource** | [UserResource](#userresource-class) |  |
| **TreeViewEnabled** | bool |  |
| **UIVersion** | int |  |
| **UIVersionConfigurationEnabled** | bool |  |
| **Url** | string |  |
| **UserCustomActions** | [UserCustomActionCollection](#usercustomactioncollection-class) |  |
| **Webs** | [WebCollection](#webcollection-class) |  |
| **WebTemplate** | string |  |
| **WorkflowAssociations** | [WorkflowAssociationCollection](#workflowassociationcollection-class) |  |
| **WorkflowTemplates** | [WorkflowTemplateCollection](#workflowtemplatecollection-class) |  |
| **FirstUniqueAncestorSecurableObject** | [SecurableObject](#securableobject-class) |  |
| **HasUniqueRoleAssignments** | bool |  |
| **RoleAssignments** | [RoleAssignmentCollection](#roleassignmentcollection-class) |  |
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
| **Web(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **AddSupportedUILanguage(int lcid)** | void |  |
| **ApplyTheme(string colorPaletteUrl, string fontSchemeUrl, string backgroundImageUrl, bool shareGenerated)** | void |  |
| **ApplyWebTemplate(string webTemplate)** | void |  |
| **CreateAnonymousLink(ClientRuntimeContext context, string url, bool isEditLink)** | ClientResult\<string\> |  |
| **CreateAnonymousLinkWithExpiration(ClientRuntimeContext context, string url, bool isEditLink, string expirationString)** | ClientResult\<string\> |  |
| **CreateOrganizationSharingLink(ClientRuntimeContext context, string url, bool isEditLink)** | ClientResult\<string\> |  |
| **DefaultDocumentLibrary()** | [List](#list-class) |  |
| **DeleteAllAnonymousLinksForObject(ClientRuntimeContext context, string url)** | void |  |
| **DeleteAnonymousLinkForObject(ClientRuntimeContext context, string url, bool isEditLink, bool removeAssociatedSharingLinkGroup)** | void |  |
| **DeleteObject()** | void |  |
| **DestroyOrganizationSharingLink(ClientRuntimeContext context, string url, bool isEditLink, bool removeAssociatedSharingLinkGroup)** | void |  |
| **DoesPushNotificationSubscriberExist(Guid deviceAppInstanceId)** | ClientResult\<bool\> |  |
| **DoesUserHavePermissions(BasePermissions permissionMask)** | ClientResult\<bool\> |  |
| **EnsureUser(string logonName)** | [User](#user-class) |  |
| **ForwardObjectLink(ClientRuntimeContext context, string url, string peoplePickerInput, string emailSubject, string emailBody)** | [SharingResult](#sharingresult-class) |  |
| **GetAppBdcCatalog()** | [AppBdcCatalog](#appbdccatalog-class) |  |
| **GetAppBdcCatalogForAppInstance(Guid appInstanceId)** | [AppBdcCatalog](#appbdccatalog-class) |  |
| **GetAppInstanceById(Guid appInstanceId)** | [AppInstance](#appinstance-class) |  |
| **GetAppInstancesByProductId(Guid productId)** | ClientObjectList\<[AppInstance](#appinstance-class)\> |  |
| **GetAvailableWebTemplates(uint lcid, bool doIncludeCrossLanguage)** | [WebTemplateCollection](#webtemplatecollection-class) |  |
| **GetCatalog(int typeCatalog)** | [List](#list-class) |  |
| **GetChanges(ChangeQuery query)** | [ChangeCollection](#changecollection-class) |  |
| **GetDocumentLibraries(ClientRuntimeContext context, string webFullUrl)** | IList\<[DocumentLibraryInformation](#documentlibraryinformation-class)\> |  |
| **GetEntity(string namespace, string name)** | [Entity](#entity-class) |  |
| **GetFileByGuestUrl(string guestUrl)** | [File](#file-class) |  |
| **GetFileByGuestUrlEnsureAccess(string guestUrl, bool ensureAccess)** | [File](#file-class) |  |
| **GetFileById(Guid uniqueId)** | [File](#file-class) |  |
| **GetFileByLinkingUrl(string linkingUrl)** | [File](#file-class) |  |
| **GetFileByServerRelativeUrl(string serverRelativeUrl)** | [File](#file-class) |  |
| **GetFileByUrl(string fileUrl)** | [File](#file-class) |  |
| **GetFileByWOPIFrameUrl(string wopiFrameUrl)** | [File](#file-class) |  |
| **GetFolderById(Guid uniqueId)** | [Folder](#folder-class) |  |
| **GetFolderByServerRelativeUrl(string serverRelativeUrl)** | [Folder](#folder-class) |  |
| **GetList(string strUrl)** | [List](#list-class) |  |
| **GetObjectSharingSettings(ClientRuntimeContext context, string objectUrl, int groupId, bool useSimplifiedRoles)** | [ObjectSharingSettings](#objectsharingsettings-class) |  |
| **GetPushNotificationSubscriber(Guid deviceAppInstanceId)** | [PushNotificationSubscriber](#pushnotificationsubscriber-class) |  |
| **GetPushNotificationSubscribersByArgs(string customArgs)** | [PushNotificationSubscriberCollection](#pushnotificationsubscribercollection-class) |  |
| **GetPushNotificationSubscribersByUser(string userName)** | [PushNotificationSubscriberCollection](#pushnotificationsubscribercollection-class) |  |
| **GetRecycleBinItems(string pagingInfo, int rowLimit, bool isAscending, RecycleBinOrderBy orderBy, RecycleBinItemState itemState)** | [RecycleBinItemCollection](#recyclebinitemcollection-class) |  |
| **GetSharingLinkKind(ClientRuntimeContext context, string fileUrl)** | ClientResult\<[SharingLinkKind](#sharinglinkkind-enum)\> |  |
| **GetSubwebsForCurrentUser(SubwebQuery query)** | [WebCollection](#webcollection-class) |  |
| **GetUserById(int userId)** | [User](#user-class) |  |
| **GetUserEffectivePermissions(string userName)** | ClientResult\<[BasePermissions](#basepermissions-class)\> |  |
| **GetWebUrlFromPageUrl(ClientRuntimeContext context, string pageFullUrl)** | ClientResult\<string\> |  |
| **IncrementSiteClientTag()** | void |  |
| **LoadAndInstallApp(Stream appPackageStream)** | [AppInstance](#appinstance-class) |  |
| **LoadAndInstallAppInSpecifiedLocale(Stream appPackageStream, int installationLocaleLCID)** | [AppInstance](#appinstance-class) |  |
| **LoadApp(Stream appPackageStream, int installationLocaleLCID)** | [AppInstance](#appinstance-class) |  |
| **MapToIcon(string fileName, string progId, IconSize size)** | ClientResult\<string\> |  |
| **RegisterPushNotificationSubscriber(Guid deviceAppInstanceId, string serviceToken)** | [PushNotificationSubscriber](#pushnotificationsubscriber-class) |  |
| **RemoveSupportedUILanguage(int lcid)** | void |  |
| **ShareObject(ClientRuntimeContext context, string url, string peoplePickerInput, string roleValue, int groupId, bool propagateAcl, bool sendEmail, bool includeAnonymousLinkInEmail, string emailSubject, string emailBody, bool useSimplifiedRoles)** | [SharingResult](#sharingresult-class) |  |
| **UnregisterPushNotificationSubscriber(Guid deviceAppInstanceId)** | void |  |
| **UnshareObject(ClientRuntimeContext context, string url)** | [SharingResult](#sharingresult-class) |  |
| **Update()** | void |  |
| **WebUrlFromFolderUrlDirect(ClientContext context, Uri folderFullUrl)** | Uri |  |
| **WebUrlFromPageUrlDirect(ClientContext context, Uri pageFullUrl)** | Uri |  |
# WebCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObjectCollection<[Web](#web-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [Web](#web-class) |  |
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
| **WebCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(WebCreationInformation parameters)** | [Web](#web-class) |  |
# WebCreationInformation Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Description** | string |  |
| **Language** | int |  |
| **Title** | string |  |
| **Url** | string |  |
| **UseSamePermissionsAsParentSite** | bool |  |
| **WebTemplate** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# WebInformation Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Configuration** | short |  |
| **Created** | DateTime |  |
| **Description** | string |  |
| **Id** | Guid |  |
| **Language** | uint |  |
| **LastItemModifiedDate** | DateTime |  |
| **ServerRelativeUrl** | string |  |
| **Title** | string |  |
| **WebTemplate** | string |  |
| **WebTemplateId** | int |  |
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
| **WebInformation(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# WebInformationPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Configuration** | string |  |
| **Created** | string |  |
| **Description** | string |  |
| **Id** | string |  |
| **Language** | string |  |
| **LastItemModifiedDate** | string |  |
| **ServerRelativeUrl** | string |  |
| **Title** | string |  |
| **WebTemplate** | string |  |
| **WebTemplateId** | string |  |
# WebObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **AllProperties** | string |  |
| **AppTiles** | string |  |
| **AssociatedMemberGroup** | string |  |
| **AssociatedOwnerGroup** | string |  |
| **AssociatedVisitorGroup** | string |  |
| **AvailableContentTypes** | string |  |
| **AvailableFields** | string |  |
| **ContentTypes** | string |  |
| **CurrentUser** | string |  |
| **DataLeakagePreventionStatusInfo** | string |  |
| **DescriptionResource** | string |  |
| **EventReceivers** | string |  |
| **Features** | string |  |
| **Fields** | string |  |
| **Folders** | string |  |
| **Lists** | string |  |
| **ListTemplates** | string |  |
| **Navigation** | string |  |
| **ParentWeb** | string |  |
| **PushNotificationSubscribers** | string |  |
| **RecycleBin** | string |  |
| **RegionalSettings** | string |  |
| **RoleDefinitions** | string |  |
| **RootFolder** | string |  |
| **SiteGroups** | string |  |
| **SiteUserInfoList** | string |  |
| **SiteUsers** | string |  |
| **ThemeInfo** | string |  |
| **TitleResource** | string |  |
| **UserCustomActions** | string |  |
| **Webs** | string |  |
| **WorkflowAssociations** | string |  |
| **WorkflowTemplates** | string |  |
# WebPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **AllowCreateDeclarativeWorkflowForCurrentUser** | string |  |
| **AllowDesignerForCurrentUser** | string |  |
| **AllowMasterPageEditingForCurrentUser** | string |  |
| **AllowRevertFromTemplateForCurrentUser** | string |  |
| **AllowRssFeeds** | string |  |
| **AllowSaveDeclarativeWorkflowAsTemplateForCurrentUser** | string |  |
| **AllowSavePublishDeclarativeWorkflowForCurrentUser** | string |  |
| **AlternateCssUrl** | string |  |
| **AppInstanceId** | string |  |
| **Configuration** | string |  |
| **ContainsConfidentialInfo** | string |  |
| **Created** | string |  |
| **CurrentChangeToken** | string |  |
| **CustomMasterUrl** | string |  |
| **Description** | string |  |
| **DesignerDownloadUrlForCurrentUser** | string |  |
| **DocumentLibraryCalloutOfficeWebAppPreviewersDisabled** | string |  |
| **EffectiveBasePermissions** | string |  |
| **EnableMinimalDownload** | string |  |
| **Id** | string |  |
| **IsMultilingual** | string |  |
| **Language** | string |  |
| **LastItemModifiedDate** | string |  |
| **MasterUrl** | string |  |
| **MembersCanShare** | string |  |
| **NoCrawl** | string |  |
| **OverwriteTranslationsOnChange** | string |  |
| **QuickLaunchEnabled** | string |  |
| **RecycleBinEnabled** | string |  |
| **RequestAccessEmail** | string |  |
| **SaveSiteAsTemplateEnabled** | string |  |
| **ServerRelativeUrl** | string |  |
| **ShowUrlStructureForCurrentUser** | string |  |
| **SiteLogoUrl** | string |  |
| **SupportedUILanguageIds** | string |  |
| **SyndicationEnabled** | string |  |
| **ThirdPartyMdmEnabled** | string |  |
| **Title** | string |  |
| **TreeViewEnabled** | string |  |
| **UIVersion** | string |  |
| **UIVersionConfigurationEnabled** | string |  |
| **Url** | string |  |
| **WebTemplate** | string |  |
# WebProxy Class

Namespace: Microsoft.SharePoint.Client


## Methods

| Name | Returns | Summary |
|---|---|---|
| **Invoke(ClientRuntimeContext context, WebRequestInfo requestInfo)** | ClientResult\<[WebResponseInfo](#webresponseinfo-class)\> |  |
# WebRequestInfo Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Body** | string |  |
| **Headers** | IDictionary\<string, string\> |  |
| **Method** | string |  |
| **Url** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# WebResponseInfo Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Body** | string |  |
| **Headers** | IDictionary\<string, string\> |  |
| **StatusCode** | int |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# WebTemplate Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Description** | string |  |
| **DisplayCategory** | string |  |
| **Id** | int |  |
| **ImageUrl** | string |  |
| **IsHidden** | bool |  |
| **IsRootWebOnly** | bool |  |
| **IsSubWebOnly** | bool |  |
| **Lcid** | uint |  |
| **Name** | string |  |
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
| **WebTemplate(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# WebTemplateCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObjectCollection<[WebTemplate](#webtemplate-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [WebTemplate](#webtemplate-class) |  |
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
| **WebTemplateCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetByName(string name)** | [WebTemplate](#webtemplate-class) |  |
# WebTemplatePropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Description** | string |  |
| **DisplayCategory** | string |  |
| **Id** | string |  |
| **ImageUrl** | string |  |
| **IsHidden** | string |  |
| **IsRootWebOnly** | string |  |
| **IsSubWebOnly** | string |  |
| **Lcid** | string |  |
| **Name** | string |  |
| **Title** | string |  |
# AnalyticsUsageEntry Class

Namespace: Microsoft.SharePoint.Client.Analytics

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
| **AnalyticsUsageEntry(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **LogAnalyticsAppEvent(ClientRuntimeContext context, Guid appEventTypeId, string itemId)** | void |  |
| **LogAnalyticsAppEvent2(ClientRuntimeContext context, Guid appEventTypeId, string itemId, Guid rollupScopeId, Guid siteId, string userId)** | void |  |
| **LogAnalyticsEvent(ClientRuntimeContext context, int eventTypeId, string itemId)** | void |  |
| **LogAnalyticsEvent2(ClientRuntimeContext context, int eventTypeId, string itemId, Guid rollupScopeId, Guid siteId, string userId)** | void |  |
# EventTypeId Enum

Namespace: Microsoft.SharePoint.Client.Analytics


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **First** |  |
| **View** |  |
| **RecommendationView** |  |
| **RecommendationClick** |  |
| **Last** |  |
# IRemoteEventService Class

Namespace: Microsoft.SharePoint.Client.EventReceivers


## Methods

| Name | Returns | Summary |
|---|---|---|
| **ProcessEvent(SPRemoteEventProperties properties)** | [SPRemoteEventResult](#spremoteeventresult-class) |  |
| **ProcessOneWayEvent(SPRemoteEventProperties properties)** | void |  |
# SPRemoteAppEventProperties Class

Namespace: Microsoft.SharePoint.Client.EventReceivers


## Properties

| Name | Type | Summary |
|---|---|---|
| **HostWebFullUrl** | Uri |  |
| **AppWebFullUrl** | Uri |  |
| **Version** | Version |  |
| **PreviousVersion** | Version |  |
| **ProductId** | Guid |  |
| **AssetId** | string |  |
| **ContentMarket** | string |  |
# SPRemoteEntityInstanceEventProperties Class

Namespace: Microsoft.SharePoint.Client.EventReceivers


## Properties

| Name | Type | Summary |
|---|---|---|
| **EntityName** | string |  |
| **EntityNamespace** | string |  |
| **NotificationContext** | string |  |
| **LobSystemInstanceName** | string |  |
| **NotificationMessage** | byte[] |  |
# SPRemoteEventProperties Class

Namespace: Microsoft.SharePoint.Client.EventReceivers


## Properties

| Name | Type | Summary |
|---|---|---|
| **EventType** | [SPRemoteEventType](#spremoteeventtype-enum) |  |
| **CorrelationId** | Guid |  |
| **ContextToken** | string |  |
| **CultureLCID** | int |  |
| **UICultureLCID** | int |  |
| **ErrorCode** | string |  |
| **ErrorMessage** | string |  |
| **ItemEventProperties** | [SPRemoteItemEventProperties](#spremoteitemeventproperties-class) |  |
| **ListEventProperties** | [SPRemoteListEventProperties](#spremotelisteventproperties-class) |  |
| **WebEventProperties** | [SPRemoteWebEventProperties](#spremotewebeventproperties-class) |  |
| **SecurityEventProperties** | [SPRemoteSecurityEventProperties](#spremotesecurityeventproperties-class) |  |
| **AppEventProperties** | [SPRemoteAppEventProperties](#spremoteappeventproperties-class) |  |
| **EntityInstanceEventProperties** | [SPRemoteEntityInstanceEventProperties](#spremoteentityinstanceeventproperties-class) |  |
# SPRemoteEventResult Class

Namespace: Microsoft.SharePoint.Client.EventReceivers


## Properties

| Name | Type | Summary |
|---|---|---|
| **Status** | [SPRemoteEventServiceStatus](#spremoteeventservicestatus-enum) |  |
| **ErrorMessage** | string |  |
| **RedirectUrl** | string |  |
| **ChangedItemProperties** | Dictionary\<string, Object\> |  |
# SPRemoteEventServiceStatus Enum

Namespace: Microsoft.SharePoint.Client.EventReceivers


## Values

| Name | Summary |
|---|---|
| **Continue** |  |
| **CancelNoError** |  |
| **CancelWithError** |  |
| **CancelWithRedirectUrl** |  |
# SPRemoteEventType Enum

Namespace: Microsoft.SharePoint.Client.EventReceivers


## Values

| Name | Summary |
|---|---|
| **ItemAdding** |  |
| **ItemUpdating** |  |
| **ItemDeleting** |  |
| **ItemCheckingIn** |  |
| **ItemCheckingOut** |  |
| **ItemUncheckingOut** |  |
| **ItemAttachmentAdding** |  |
| **ItemAttachmentDeleting** |  |
| **ItemFileMoving** |  |
| **ItemVersionDeleting** |  |
| **FieldAdding** |  |
| **FieldUpdating** |  |
| **FieldDeleting** |  |
| **ListAdding** |  |
| **ListDeleting** |  |
| **SiteDeleting** |  |
| **WebDeleting** |  |
| **WebMoving** |  |
| **WebAdding** |  |
| **GroupAdding** |  |
| **GroupUpdating** |  |
| **GroupDeleting** |  |
| **GroupUserAdding** |  |
| **GroupUserDeleting** |  |
| **RoleDefinitionAdding** |  |
| **RoleDefinitionUpdating** |  |
| **RoleDefinitionDeleting** |  |
| **RoleAssignmentAdding** |  |
| **RoleAssignmentDeleting** |  |
| **InheritanceBreaking** |  |
| **InheritanceResetting** |  |
| **ItemAdded** |  |
| **ItemUpdated** |  |
| **ItemDeleted** |  |
| **ItemCheckedIn** |  |
| **ItemCheckedOut** |  |
| **ItemUncheckedOut** |  |
| **ItemAttachmentAdded** |  |
| **ItemAttachmentDeleted** |  |
| **ItemFileMoved** |  |
| **ItemFileConverted** |  |
| **ItemVersionDeleted** |  |
| **FieldAdded** |  |
| **FieldUpdated** |  |
| **FieldDeleted** |  |
| **ListAdded** |  |
| **ListDeleted** |  |
| **SiteDeleted** |  |
| **WebDeleted** |  |
| **WebMoved** |  |
| **WebProvisioned** |  |
| **WebRestored** |  |
| **GroupAdded** |  |
| **GroupUpdated** |  |
| **GroupDeleted** |  |
| **GroupUserAdded** |  |
| **GroupUserDeleted** |  |
| **RoleDefinitionAdded** |  |
| **RoleDefinitionUpdated** |  |
| **RoleDefinitionDeleted** |  |
| **RoleAssignmentAdded** |  |
| **RoleAssignmentDeleted** |  |
| **InheritanceBroken** |  |
| **InheritanceReset** |  |
| **EntityInstanceAdded** |  |
| **EntityInstanceUpdated** |  |
| **EntityInstanceDeleted** |  |
| **AppInstalled** |  |
| **AppUpgraded** |  |
| **AppUninstalling** |  |
# SPRemoteItemEventProperties Class

Namespace: Microsoft.SharePoint.Client.EventReceivers


## Properties

| Name | Type | Summary |
|---|---|---|
| **WebUrl** | string |  |
| **ListId** | Guid |  |
| **ListTitle** | string |  |
| **ListItemId** | int |  |
| **Versionless** | bool |  |
| **UserDisplayName** | string |  |
| **UserLoginName** | string |  |
| **IsBackgroundSave** | bool |  |
| **CurrentUserId** | int |  |
| **BeforeUrl** | string |  |
| **AfterUrl** | string |  |
| **ExternalNotificationMessage** | byte[] |  |
| **BeforeProperties** | Dictionary\<string, Object\> |  |
| **AfterProperties** | Dictionary\<string, Object\> |  |
# SPRemoteListEventProperties Class

Namespace: Microsoft.SharePoint.Client.EventReceivers


## Properties

| Name | Type | Summary |
|---|---|---|
| **WebUrl** | string |  |
| **ListId** | Guid |  |
| **ListTitle** | string |  |
| **FieldName** | string |  |
| **FieldXml** | string |  |
| **TemplateId** | int |  |
| **FeatureId** | Guid |  |
# SPRemoteSecurityEventProperties Class

Namespace: Microsoft.SharePoint.Client.EventReceivers


## Properties

| Name | Type | Summary |
|---|---|---|
| **UserDisplayName** | string |  |
| **UserLoginName** | string |  |
| **WebId** | Guid |  |
| **WebFullUrl** | string |  |
| **GroupName** | string |  |
| **GroupId** | int |  |
| **GroupOwnerId** | int |  |
| **GroupNewOwnerId** | int |  |
| **GroupUserId** | int |  |
| **GroupUserLoginName** | string |  |
| **RoleDefinitionName** | string |  |
| **RoleDefinitionPermissions** | ulong |  |
| **RoleDefinitionId** | int |  |
| **ObjectType** | int |  |
| **ScopeUrl** | string |  |
| **PrincipalId** | int |  |
# SPRemoteWebEventProperties Class

Namespace: Microsoft.SharePoint.Client.EventReceivers


## Properties

| Name | Type | Summary |
|---|---|---|
| **FullUrl** | string |  |
| **ServerRelativeUrl** | string |  |
| **NewServerRelativeUrl** | string |  |
# NativeClient Class

Namespace: Microsoft.SharePoint.Client.OAuth

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
| **NativeClient(ClientRuntimeContext context)** |  |
| **NativeClient(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Authenticate()** | void |  |
# ClickManager Class

Namespace: Microsoft.SharePoint.Client.PageInstrumentation


## Methods

| Name | Returns | Summary |
|---|---|---|
| **RecordClick(ClientRuntimeContext context, string pageCorrelationId, string clickType, string clickData, DateTime clickUTCTime)** | void |  |
# PageImpressionClient Class

Namespace: Microsoft.SharePoint.Client.PageInstrumentation

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **BasePageCorrelationId** | string |  |
| **ClientIdToClickInfoMap** | IDictionary\<string, string\> |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# DocumentSharingManager Class

Namespace: Microsoft.SharePoint.Client.Sharing


## Methods

| Name | Returns | Summary |
|---|---|---|
| **CanMemberShare(ClientRuntimeContext context, List list)** | ClientResult\<bool\> |  |
| **GetRoleDefinition(ClientRuntimeContext context, Role role)** | [RoleDefinition](#roledefinition-class) |  |
| **IsDocumentSharingEnabled(ClientRuntimeContext context, List list)** | ClientResult\<bool\> |  |
| **RemoveItemsFromSharedWithMeView(ClientRuntimeContext context, IList\<string\> itemUrls)** | IEnumerable\<[SharedWithMeViewItemRemovalResult](#sharedwithmeviewitemremovalresult-class)\> |  |
| **UpdateDocumentSharingInfo(ClientRuntimeContext context, string resourceAddress, IList\<UserRoleAssignment\> userRoleAssignments, bool validateExistingPermissions, bool additiveMode, bool sendServerManagedNotification, string customMessage, bool includeAnonymousLinksInNotification, bool propagateAcl)** | IList\<[UserSharingResult](#usersharingresult-class)\> |  |
# RemoveItemsFromSharedWithMeViewErrorCode Enum

Namespace: Microsoft.SharePoint.Client.Sharing


## Values

| Name | Summary |
|---|---|
| **Success** |  |
| **UnableToRemoveItem** |  |
| **InvalidItemSharing** |  |
| **InvalidListItem** |  |
# Role Enum

Namespace: Microsoft.SharePoint.Client.Sharing


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **View** |  |
| **Edit** |  |
| **Owner** |  |
# SharedWithMeViewItemRemovalResult Class

Namespace: Microsoft.SharePoint.Client.Sharing

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ErrorCode** | [RemoveItemsFromSharedWithMeViewErrorCode](#removeitemsfromsharedwithmeviewerrorcode-enum) |  |
| **ErrorMessage** | string |  |
| **Success** | bool |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# UserRoleAssignment Class

Namespace: Microsoft.SharePoint.Client.Sharing

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Role** | [Role](#role-enum) |  |
| **UserId** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# UserSharingResult Class

Namespace: Microsoft.SharePoint.Client.Sharing

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AllowedRoles** | IEnumerable\<[Role](#role-enum)\> |  |
| **CurrentRole** | [Role](#role-enum) |  |
| **DisplayName** | string |  |
| **Email** | string |  |
| **InvitationLink** | string |  |
| **IsUserKnown** | bool |  |
| **Message** | string |  |
| **Status** | bool |  |
| **User** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# WebSharingManager Class

Namespace: Microsoft.SharePoint.Client.Sharing


## Methods

| Name | Returns | Summary |
|---|---|---|
| **CanMemberShare(ClientRuntimeContext context, Web web)** | ClientResult\<bool\> |  |
| **UpdateWebSharingInformation(ClientRuntimeContext context, Web web, IList\<UserRoleAssignment\> userRoleAssignments, bool sendServerManagedNotification, string customMessage, bool additivePermission, bool allowExternalSharing)** | IList\<[UserSharingResult](#usersharingresult-class)\> |  |
# SiteHealthResult Class

Namespace: Microsoft.SharePoint.Client.SiteHealth

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **MessageAsText** | string |  |
| **RuleHelpLink** | string |  |
| **RuleId** | Guid |  |
| **RuleIsRepairable** | bool |  |
| **RuleName** | string |  |
| **Status** | [SiteHealthStatusType](#sitehealthstatustype-enum) |  |
| **TimeStamp** | DateTime |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SiteHealthStatusType Enum

Namespace: Microsoft.SharePoint.Client.SiteHealth


## Values

| Name | Summary |
|---|---|
| **Passed** |  |
| **FailedWarning** |  |
| **FailedError** |  |
# SiteHealthSummary Class

Namespace: Microsoft.SharePoint.Client.SiteHealth

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **FailedErrorCount** | int |  |
| **FailedWarningCount** | int |  |
| **PassedCount** | int |  |
| **Results** | IList\<[SiteHealthResult](#sitehealthresult-class)\> |  |
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
| **SiteHealthSummary(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# SiteHealthSummaryPropertyNames Class

Namespace: Microsoft.SharePoint.Client.SiteHealth


## Fields

| Name | Type | Summary |
|---|---|---|
| **FailedErrorCount** | string |  |
| **FailedWarningCount** | string |  |
| **PassedCount** | string |  |
| **Results** | string |  |
# DateTimeFormat Enum

Namespace: Microsoft.SharePoint.Client.Utilities


## Values

| Name | Summary |
|---|---|
| **DateTime** |  |
| **DateOnly** |  |
| **TimeOnly** |  |
| **ISO8601** |  |
| **MonthDayOnly** |  |
| **MonthYearOnly** |  |
| **LongDate** |  |
| **UnknownFormat** |  |
# EmailProperties Class

Namespace: Microsoft.SharePoint.Client.Utilities

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AdditionalHeaders** | IDictionary\<string, string\> |  |
| **BCC** | IEnumerable\<string\> |  |
| **Body** | string |  |
| **CC** | IEnumerable\<string\> |  |
| **From** | string |  |
| **Subject** | string |  |
| **To** | IEnumerable\<string\> |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# HtmlStrings Class

Namespace: Microsoft.SharePoint.Client.Utilities


## Fields

| Name | Type | Summary |
|---|---|---|
| **Empty** | string |  |
| **Quot** | string |  |
| **Amp** | string |  |
| **Apostrophe** | string |  |
| **Lt** | string |  |
| **Gt** | string |  |
| **Space** | string |  |
| **Br** | string |  |
| **Nbsp** | string |  |
| **B** | string |  |
| **I** | string |  |
| **U** | string |  |
| **BClose** | string |  |
| **IClose** | string |  |
| **UClose** | string |  |
| **Wbr** | string |  |
| **Style** | string |  |
| **StyleClose** | string |  |
| **Cdata** | string |  |
| **CdataClose** | string |  |
# HttpUtility Class

Namespace: Microsoft.SharePoint.Client.Utilities


## Methods

| Name | Returns | Summary |
|---|---|---|
| **EcmaScriptStringLiteralEncode(string scriptLiteralToEncode)** | string |  |
| **EcmaScriptStringLiteralEncode(string scriptLiteralToEncode, TextWriter output)** | void |  |
| **HtmlEncode(string valueToEncode)** | string |  |
| **HtmlEncode(string valueToEncode, TextWriter output)** | void |  |
| **HtmlUrlAttributeEncode(string urlAttributeToEncode)** | string |  |
| **HtmlUrlAttributeEncode(string urlAttributeToEncode, TextWriter output)** | void |  |
| **UrlKeyValueDecode(string keyOrValueToDecode)** | string |  |
| **UrlKeyValueEncode(string keyOrValueToEncode)** | string |  |
| **UrlKeyValueEncode(Guid guidKeyOrValueToEncode)** | string |  |
| **UrlKeyValueEncode(int keyOrValueToEncode)** | string |  |
| **UrlKeyValueEncode(string keyToEncode, string valueToEncode)** | string |  |
| **UrlKeyValueEncode(string keyOrValueToEncode, TextWriter output)** | void |  |
| **UrlKeyValueEncode(string keyToEncode, string valueToEncode, TextWriter output)** | void |  |
| **UrlPathEncode(string urlToEncode, bool allowHashParameter)** | string |  |
| **UrlPathEncode(string urlToEncode, bool allowHashParameter, bool encodeUnicodeCharacters)** | string |  |
| **UrlPathEncode(string urlToEncode, bool allowHashParameter, TextWriter output)** | void |  |
| **UrlPathEncode(string urlToEncode, bool allowHashParameter, bool encodeUnicodeCharacters, bool rfcCompliant)** | string |  |
| **UrlPathEncode(string urlToEncode, bool allowHashParameter, bool encodeUnicodeCharacters, TextWriter output)** | void |  |
# IconSize Enum

Namespace: Microsoft.SharePoint.Client.Utilities


## Values

| Name | Summary |
|---|---|
| **Size16** |  |
| **Size32** |  |
| **Size256** |  |
# LogAppErrorResult Enum

Namespace: Microsoft.SharePoint.Client.Utilities


## Values

| Name | Summary |
|---|---|
| **Success** |  |
| **AccessDenied** |  |
| **ErrorsThrottled** |  |
# PrincipalInfo Class

Namespace: Microsoft.SharePoint.Client.Utilities

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Department** | string |  |
| **DisplayName** | string |  |
| **Email** | string |  |
| **JobTitle** | string |  |
| **LoginName** | string |  |
| **Mobile** | string |  |
| **PrincipalId** | int |  |
| **PrincipalType** | [PrincipalType](#principaltype-enum) |  |
| **SIPAddress** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# PrincipalSource Enum

Namespace: Microsoft.SharePoint.Client.Utilities


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **UserInfoList** |  |
| **Windows** |  |
| **MembershipProvider** |  |
| **RoleProvider** |  |
| **All** |  |
# PrincipalType Enum

Namespace: Microsoft.SharePoint.Client.Utilities


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **User** |  |
| **DistributionList** |  |
| **SecurityGroup** |  |
| **SharePointGroup** |  |
| **All** |  |
# SPWOPIFrameAction Enum

Namespace: Microsoft.SharePoint.Client.Utilities


## Values

| Name | Summary |
|---|---|
| **View** |  |
| **Edit** |  |
| **MobileView** |  |
| **InteractivePreview** |  |
| **Syndicate** |  |
| **LegacyWebService** |  |
# UrlUtility Class

Namespace: Microsoft.SharePoint.Client.Utilities


## Properties

| Name | Type | Summary |
|---|---|---|
| **AllowedProtocols** | string[] |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **CombineUrl(string baseUrlPath, string additionalNodes)** | string |  |
| **IsProtocolAllowed(string fullOrRelativeUrl)** | bool |  |
| **IsProtocolAllowed(string fullOrRelativeUrl, bool allowRelativeUrl)** | bool |  |
| **IsUrlFull(string url)** | bool |  |
| **IsUrlRelative(string url)** | bool |  |
# Utility Class

Namespace: Microsoft.SharePoint.Client.Utilities


## Methods

| Name | Returns | Summary |
|---|---|---|
| **CreateEmailBodyForInvitation(ClientRuntimeContext context, string pageAddress)** | ClientResult\<string\> |  |
| **CreateNewDiscussion(ClientRuntimeContext context, List list, string title)** | [ListItem](#listitem-class) |  |
| **CreateNewDiscussionReply(ClientRuntimeContext context, ListItem parent)** | [ListItem](#listitem-class) |  |
| **CreateWikiPageInContextWeb(ClientRuntimeContext context, WikiPageCreationInformation parameters)** | [File](#file-class) |  |
| **FormatDateTime(ClientRuntimeContext context, Web web, DateTime datetime, DateTimeFormat format)** | ClientResult\<string\> |  |
| **GetAppLicenseDeploymentId(ClientRuntimeContext context)** | ClientResult\<Guid\> |  |
| **GetAppLicenseInformation(ClientRuntimeContext context, Guid productId)** | ClientResult\<[AppLicenseCollection](#applicensecollection-class)\> |  |
| **GetCurrentUserEmailAddresses(ClientRuntimeContext context)** | ClientResult\<string\> |  |
| **GetLocalizedString(ClientRuntimeContext context, string source, string defaultResourceFile, int language)** | ClientResult\<string\> |  |
| **GetLowerCaseString(ClientRuntimeContext context, string sourceValue, int lcid)** | ClientResult\<string\> |  |
| **GetPeoplePickerURL(ClientRuntimeContext context, Web web, FieldUser fieldUser)** | ClientResult\<string\> |  |
| **GetUserPermissionLevels(ClientRuntimeContext context)** | IList\<string\> |  |
| **ImportAppLicense(ClientRuntimeContext context, string licenseTokenToImport, string contentMarket, string billingMarket, string appName, string iconUrl, string providerName, int appSubtype)** | void |  |
| **IsEmailServerSet(ClientRuntimeContext context, Web web)** | ClientResult\<bool\> |  |
| **IsUserLicensedForEntityInContext(ClientRuntimeContext context, string licensableEntity)** | ClientResult\<bool\> |  |
| **LocalizeWebPartGallery(ClientRuntimeContext context, ListItemCollection items)** | ClientObjectList\<[ListItem](#listitem-class)\> |  |
| **LogCustomAppError(ClientRuntimeContext context, string error)** | ClientResult\<[LogAppErrorResult](#logapperrorresult-enum)\> |  |
| **LogCustomRemoteAppError(ClientRuntimeContext context, Guid productId, string error)** | ClientResult\<[LogAppErrorResult](#logapperrorresult-enum)\> |  |
| **MarkDiscussionAsFeatured(ClientRuntimeContext context, string listID, string topicIDs)** | void |  |
| **ResolvePrincipal(ClientRuntimeContext context, Web web, string input, PrincipalType scopes, PrincipalSource sources, UserCollection usersContainer, bool inputIsEmailOnly)** | ClientResult\<[PrincipalInfo](#principalinfo-class)\> |  |
| **SearchPrincipals(ClientRuntimeContext context, Web web, string input, PrincipalType scopes, PrincipalSource sources, UserCollection usersContainer, int maxCount)** | IList\<[PrincipalInfo](#principalinfo-class)\> |  |
| **SendEmail(ClientRuntimeContext context, EmailProperties properties)** | void |  |
| **UnmarkDiscussionAsFeatured(ClientRuntimeContext context, string listID, string topicIDs)** | void |  |
# WikiPageCreationInformation Class

Namespace: Microsoft.SharePoint.Client.Utilities

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ServerRelativeUrl** | string |  |
| **WikiHtmlContent** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# WopiHostUtility Class

Namespace: Microsoft.SharePoint.Client.Utilities


## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetWopiTargetPropertiesByUrl(ClientRuntimeContext context, string fileUrl, SPWOPIFrameAction requestedAction)** | [WopiProperties](#wopiproperties-class) |  |
# WopiProperties Class

Namespace: Microsoft.SharePoint.Client.Utilities

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AccessToken** | string |  |
| **AccessTokenTtl** | long |  |
| **AppIconUrl** | string |  |
| **ErrorMessageToDisplay** | string |  |
| **RedirectUrl** | string |  |
| **WebApplicationUrl** | string |  |
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
| **WopiProperties(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# WopiPropertiesPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Utilities


## Fields

| Name | Type | Summary |
|---|---|---|
| **AccessToken** | string |  |
| **AccessTokenTtl** | string |  |
| **AppIconUrl** | string |  |
| **ErrorMessageToDisplay** | string |  |
| **RedirectUrl** | string |  |
| **WebApplicationUrl** | string |  |
# LimitedWebPartManager Class

Namespace: Microsoft.SharePoint.Client.WebParts

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **HasPersonalizedParts** | bool |  |
| **Scope** | [PersonalizationScope](#personalizationscope-enum) |  |
| **WebParts** | [WebPartDefinitionCollection](#webpartdefinitioncollection-class) |  |
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
| **LimitedWebPartManager(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **AddWebPart(WebPart webPart, string zoneId, int zoneIndex)** | [WebPartDefinition](#webpartdefinition-class) |  |
| **ImportWebPart(string webPartXml)** | [WebPartDefinition](#webpartdefinition-class) |  |
# LimitedWebPartManagerObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client.WebParts


## Fields

| Name | Type | Summary |
|---|---|---|
| **WebParts** | string |  |
# LimitedWebPartManagerPropertyNames Class

Namespace: Microsoft.SharePoint.Client.WebParts


## Fields

| Name | Type | Summary |
|---|---|---|
| **HasPersonalizedParts** | string |  |
| **Scope** | string |  |
# PersonalizationScope Enum

Namespace: Microsoft.SharePoint.Client.WebParts


## Values

| Name | Summary |
|---|---|
| **User** |  |
| **Shared** |  |
# TileData Class

Namespace: Microsoft.SharePoint.Client.WebParts

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **BackgroundCollageImageLocations** | IEnumerable\<string\> |  |
| **BackgroundImageLocation** | string |  |
| **BackgroundImageRendersAsIcon** | bool |  |
| **BodyText** | string |  |
| **Description** | string |  |
| **HoverDisabled** | bool |  |
| **ID** | int |  |
| **IsWide** | bool |  |
| **LinkLocation** | string |  |
| **TileOrder** | int |  |
| **Title** | string |  |
| **TransparentOverlay** | bool |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# WebPart Class

Namespace: Microsoft.SharePoint.Client.WebParts

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Hidden** | bool |  |
| **IsClosed** | bool |  |
| **Properties** | [PropertyValues](#propertyvalues-class) |  |
| **Subtitle** | string |  |
| **Title** | string |  |
| **TitleUrl** | string |  |
| **ZoneIndex** | int |  |
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
| **WebPart(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# WebPartDefinition Class

Namespace: Microsoft.SharePoint.Client.WebParts

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Id** | Guid |  |
| **WebPart** | [WebPart](#webpart-class) |  |
| **ZoneId** | string |  |
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
| **WebPartDefinition(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **CloseWebPart()** | void |  |
| **DeleteWebPart()** | void |  |
| **MoveWebPartTo(string zoneID, int zoneIndex)** | void |  |
| **OpenWebPart()** | void |  |
| **SaveWebPartChanges()** | void |  |
# WebPartDefinitionCollection Class

Namespace: Microsoft.SharePoint.Client.WebParts

Base class: ClientObjectCollection<[WebPartDefinition](#webpartdefinition-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [WebPartDefinition](#webpartdefinition-class) |  |
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
| **WebPartDefinitionCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetByControlId(string controlId)** | [WebPartDefinition](#webpartdefinition-class) |  |
| **GetById(Guid id)** | [WebPartDefinition](#webpartdefinition-class) |  |
# WebPartDefinitionObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client.WebParts


## Fields

| Name | Type | Summary |
|---|---|---|
| **WebPart** | string |  |
# WebPartDefinitionPropertyNames Class

Namespace: Microsoft.SharePoint.Client.WebParts


## Fields

| Name | Type | Summary |
|---|---|---|
| **Id** | string |  |
| **ZoneId** | string |  |
# WebPartObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client.WebParts


## Fields

| Name | Type | Summary |
|---|---|---|
| **Properties** | string |  |
# WebPartPropertyNames Class

Namespace: Microsoft.SharePoint.Client.WebParts


## Fields

| Name | Type | Summary |
|---|---|---|
| **Hidden** | string |  |
| **IsClosed** | string |  |
| **Subtitle** | string |  |
| **Title** | string |  |
| **TitleUrl** | string |  |
| **ZoneIndex** | string |  |
# WorkflowAssociation Class

Namespace: Microsoft.SharePoint.Client.Workflow

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AllowManual** | bool |  |
| **AssociationData** | string |  |
| **AutoStartChange** | bool |  |
| **AutoStartCreate** | bool |  |
| **BaseId** | Guid |  |
| **Created** | DateTime |  |
| **Description** | string |  |
| **Enabled** | bool |  |
| **HistoryListTitle** | string |  |
| **Id** | Guid |  |
| **InstantiationUrl** | string |  |
| **InternalName** | string |  |
| **IsDeclarative** | bool |  |
| **ListId** | Guid |  |
| **Modified** | DateTime |  |
| **Name** | string |  |
| **TaskListTitle** | string |  |
| **WebId** | Guid |  |
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
| **WorkflowAssociation(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
| **Update()** | void |  |
# WorkflowAssociationCollection Class

Namespace: Microsoft.SharePoint.Client.Workflow

Base class: ClientObjectCollection<[WorkflowAssociation](#workflowassociation-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [WorkflowAssociation](#workflowassociation-class) |  |
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
| **WorkflowAssociationCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(WorkflowAssociationCreationInformation parameters)** | [WorkflowAssociation](#workflowassociation-class) |  |
| **GetById(Guid associationId)** | [WorkflowAssociation](#workflowassociation-class) |  |
| **GetByName(string name)** | [WorkflowAssociation](#workflowassociation-class) |  |
# WorkflowAssociationCreationInformation Class

Namespace: Microsoft.SharePoint.Client.Workflow

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ContentTypeAssociationHistoryListName** | string |  |
| **ContentTypeAssociationTaskListName** | string |  |
| **HistoryList** | [List](#list-class) |  |
| **Name** | string |  |
| **TaskList** | [List](#list-class) |  |
| **Template** | [WorkflowTemplate](#workflowtemplate-class) |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# WorkflowAssociationPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Workflow


## Fields

| Name | Type | Summary |
|---|---|---|
| **AllowManual** | string |  |
| **AssociationData** | string |  |
| **AutoStartChange** | string |  |
| **AutoStartCreate** | string |  |
| **BaseId** | string |  |
| **Created** | string |  |
| **Description** | string |  |
| **Enabled** | string |  |
| **HistoryListTitle** | string |  |
| **Id** | string |  |
| **InstantiationUrl** | string |  |
| **InternalName** | string |  |
| **IsDeclarative** | string |  |
| **ListId** | string |  |
| **Modified** | string |  |
| **Name** | string |  |
| **TaskListTitle** | string |  |
| **WebId** | string |  |
# WorkflowTemplate Class

Namespace: Microsoft.SharePoint.Client.Workflow

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AllowManual** | bool |  |
| **AssociationUrl** | string |  |
| **AutoStartChange** | bool |  |
| **AutoStartCreate** | bool |  |
| **Description** | string |  |
| **Id** | Guid |  |
| **IsDeclarative** | bool |  |
| **Name** | string |  |
| **PermissionsManual** | [BasePermissions](#basepermissions-class) |  |
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
| **WorkflowTemplate(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# WorkflowTemplateCollection Class

Namespace: Microsoft.SharePoint.Client.Workflow

Base class: ClientObjectCollection<[WorkflowTemplate](#workflowtemplate-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [WorkflowTemplate](#workflowtemplate-class) |  |
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
| **WorkflowTemplateCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetById(Guid templateId)** | [WorkflowTemplate](#workflowtemplate-class) |  |
| **GetByName(string name)** | [WorkflowTemplate](#workflowtemplate-class) |  |
# WorkflowTemplatePropertyNames Class

Namespace: Microsoft.SharePoint.Client.Workflow


## Fields

| Name | Type | Summary |
|---|---|---|
| **AllowManual** | string |  |
| **AssociationUrl** | string |  |
| **AutoStartChange** | string |  |
| **AutoStartCreate** | string |  |
| **Description** | string |  |
| **Id** | string |  |
| **IsDeclarative** | string |  |
| **Name** | string |  |
| **PermissionsManual** | string |  |
# AppDetails Class

Namespace: Microsoft.SharePoint.Packaging

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **EulaUrl** | string |  |
| **PrivacyUrl** | string |  |
| **Publisher** | string |  |
| **ShortDescription** | string |  |
| **SupportUrl** | string |  |
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
| **AppDetails(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# AppDetailsPropertyNames Class

Namespace: Microsoft.SharePoint.Packaging


## Fields

| Name | Type | Summary |
|---|---|---|
| **EulaUrl** | string |  |
| **PrivacyUrl** | string |  |
| **Publisher** | string |  |
| **ShortDescription** | string |  |
| **SupportUrl** | string |  |
# AppIconInfo Class

Namespace: Microsoft.SharePoint.Packaging

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Content** | byte[] |  |
| **MimeType** | string |  |
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
| **AppIconInfo(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# AppIconInfoPropertyNames Class

Namespace: Microsoft.SharePoint.Packaging


## Fields

| Name | Type | Summary |
|---|---|---|
| **Content** | string |  |
| **MimeType** | string |  |
# ModuleLink Class

Namespace: Microsoft.SharePoint.WebControls

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
| **ModuleLink(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetResourceManifestInformation(ClientRuntimeContext context, Web web, string manifestName)** | [ResourceManifestInformation](#resourcemanifestinformation-class) |  |
# ResourceManifestInformation Class

Namespace: Microsoft.SharePoint.WebControls

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **RequireJsScriptBlock** | string |  |
| **ScenarioMapping** | IDictionary\<string, string\> |  |
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
| **ResourceManifestInformation(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ResourceManifestInformationPropertyNames Class

Namespace: Microsoft.SharePoint.WebControls


## Fields

| Name | Type | Summary |
|---|---|---|
| **RequireJsScriptBlock** | string |  |
| **ScenarioMapping** | string |  |
