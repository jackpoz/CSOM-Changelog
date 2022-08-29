# Microsoft.SharePoint.Client.dll v.16.1.0.0 API documentation

Created by 
[mddox](https://github.com/loxsmoke/mddox) on 07/04/2023

# All types

|   |   |   |
|---|---|---|
| [EntityInstanceIdEncoder Class](#entityinstanceidencoder-class) | [FieldComputedPropertyNames Class](#fieldcomputedpropertynames-class) | [ServerSettings Class](#serversettings-class) |
| [ExternalSubscriptionStore Class](#externalsubscriptionstore-class) | [FieldCurrency Class](#fieldcurrency-class) | [SharedWithMeItemCollection Class](#sharedwithmeitemcollection-class) |
| [AppBdcCatalog Class](#appbdccatalog-class) | [FieldCurrencyPropertyNames Class](#fieldcurrencypropertynames-class) | [SharedWithUser Class](#sharedwithuser-class) |
| [Entity Class](#entity-class) | [FieldDateTime Class](#fielddatetime-class) | [SharedWithUserCollection Class](#sharedwithusercollection-class) |
| [EntityField Class](#entityfield-class) | [FieldDateTimePropertyNames Class](#fielddatetimepropertynames-class) | [SharePointSharingSettings Class](#sharepointsharingsettings-class) |
| [EntityFieldPropertyNames Class](#entityfieldpropertynames-class) | [FieldGeolocation Class](#fieldgeolocation-class) | [SharePointSharingSettingsObjectPropertyNames Class](#sharepointsharingsettingsobjectpropertynames-class) |
| [EntityIdentifier Class](#entityidentifier-class) | [FieldGeolocationValue Class](#fieldgeolocationvalue-class) | [SharePointSharingSettingsPropertyNames Class](#sharepointsharingsettingspropertynames-class) |
| [EntityIdentifierPropertyNames Class](#entityidentifierpropertynames-class) | [FieldGuid Class](#fieldguid-class) | [SharingLinkData Class](#sharinglinkdata-class) |
| [EntityPropertyNames Class](#entitypropertynames-class) | [FieldIndexStatus Enum](#fieldindexstatus-enum) | [SharingLinkInfo Class](#sharinglinkinfo-class) |
| [EntityView Class](#entityview-class) | [FieldLink Class](#fieldlink-class) | [SharingLinkKind Enum](#sharinglinkkind-enum) |
| [EntityViewObjectPropertyNames Class](#entityviewobjectpropertynames-class) | [FieldLinkCollection Class](#fieldlinkcollection-class) | [SharingLinkStatus Enum](#sharinglinkstatus-enum) |
| [EntityViewPropertyNames Class](#entityviewpropertynames-class) | [FieldLinkCreationInformation Class](#fieldlinkcreationinformation-class) | [SharingOperationStatusCode Enum](#sharingoperationstatuscode-enum) |
| [Filter Class](#filter-class) | [FieldLinkPropertyNames Class](#fieldlinkpropertynames-class) | [SharingPermissionInformation Class](#sharingpermissioninformation-class) |
| [FilterPropertyNames Class](#filterpropertynames-class) | [FieldLocation Class](#fieldlocation-class) | [SharingPermissionInformationCollection Class](#sharingpermissioninformationcollection-class) |
| [LobSystem Class](#lobsystem-class) | [FieldLookup Class](#fieldlookup-class) | [SharingPermissionInformationPropertyNames Class](#sharingpermissioninformationpropertynames-class) |
| [LobSystemInstance Class](#lobsysteminstance-class) | [FieldLookupPropertyNames Class](#fieldlookuppropertynames-class) | [SharingPermissionKind Enum](#sharingpermissionkind-enum) |
| [LobSystemInstancePropertyNames Class](#lobsysteminstancepropertynames-class) | [FieldLookupValue Class](#fieldlookupvalue-class) | [SharingResult Class](#sharingresult-class) |
| [LobSystemPropertyNames Class](#lobsystempropertynames-class) | [FieldMultiChoice Class](#fieldmultichoice-class) | [SharingResultObjectPropertyNames Class](#sharingresultobjectpropertynames-class) |
| [MethodExecutionResult Class](#methodexecutionresult-class) | [FieldMultiChoicePropertyNames Class](#fieldmultichoicepropertynames-class) | [SharingResultPropertyNames Class](#sharingresultpropertynames-class) |
| [MethodExecutionResultObjectPropertyNames Class](#methodexecutionresultobjectpropertynames-class) | [FieldMultiLineText Class](#fieldmultilinetext-class) | [SharingState Enum](#sharingstate-enum) |
| [ReturnParameterCollection Class](#returnparametercollection-class) | [FieldMultiLineTextPropertyNames Class](#fieldmultilinetextpropertynames-class) | [SharingUserCollection Class](#sharingusercollection-class) |
| [TypeDescriptor Class](#typedescriptor-class) | [FieldNumber Class](#fieldnumber-class) | [ShowInFiltersPaneStatus Enum](#showinfilterspanestatus-enum) |
| [TypeDescriptorPropertyNames Class](#typedescriptorpropertynames-class) | [FieldNumberPropertyNames Class](#fieldnumberpropertynames-class) | [Site Class](#site-class) |
| [EntityFieldCollection Class](#entityfieldcollection-class) | [FieldObjectPropertyNames Class](#fieldobjectpropertynames-class) | [SiteArchiveFlags Enum](#sitearchiveflags-enum) |
| [EntityIdentifierCollection Class](#entityidentifiercollection-class) | [FieldPropertyNames Class](#fieldpropertynames-class) | [SiteObjectPropertyNames Class](#siteobjectpropertynames-class) |
| [EntityInstanceCollection Class](#entityinstancecollection-class) | [FieldRatingScale Class](#fieldratingscale-class) | [SitePropertyNames Class](#sitepropertynames-class) |
| [FilterCollection Class](#filtercollection-class) | [FieldRatingScalePropertyNames Class](#fieldratingscalepropertynames-class) | [SiteUrl Class](#siteurl-class) |
| [LobSystemInstanceCollection Class](#lobsysteminstancecollection-class) | [FieldRatingScaleQuestionAnswer Class](#fieldratingscalequestionanswer-class) | [SmartCache Class](#smartcache-class) |
| [TypeDescriptorCollection Class](#typedescriptorcollection-class) | [FieldStringValues Class](#fieldstringvalues-class) | [SmartTemplateContentType Class](#smarttemplatecontenttype-class) |
| [EntityEventType Enum](#entityeventtype-enum) | [FieldText Class](#fieldtext-class) | [SPAIPLabelExtractionStatus Enum](#spaiplabelextractionstatus-enum) |
| [EntityFieldValueDictionary Class](#entityfieldvaluedictionary-class) | [FieldTextPropertyNames Class](#fieldtextpropertynames-class) | [SPChangeActivityType Enum](#spchangeactivitytype-enum) |
| [EntityIdentity Class](#entityidentity-class) | [FieldThumbnail Class](#fieldthumbnail-class) | [SPClientUtility Class](#spclientutility-class) |
| [EntityIdentityPropertyNames Class](#entityidentitypropertynames-class) | [FieldType Enum](#fieldtype-enum) | [SPDataLeakagePreventionStatusInfo Class](#spdataleakagepreventionstatusinfo-class) |
| [EntityInstance Class](#entityinstance-class) | [FieldUrl Class](#fieldurl-class) | [SPDataLeakagePreventionStatusInfoPropertyNames Class](#spdataleakagepreventionstatusinfopropertynames-class) |
| [NotificationCallback Class](#notificationcallback-class) | [FieldUrlPropertyNames Class](#fieldurlpropertynames-class) | [SpecialFolderType Enum](#specialfoldertype-enum) |
| [NotificationCallbackPropertyNames Class](#notificationcallbackpropertynames-class) | [FieldUrlValue Class](#fieldurlvalue-class) | [SPEffectiveInformationRightsManagementSettingsSource Enum](#speffectiveinformationrightsmanagementsettingssource-enum) |
| [Subscription Class](#subscription-class) | [FieldUser Class](#fielduser-class) | [SPHSite Class](#sphsite-class) |
| [SubscriptionPropertyNames Class](#subscriptionpropertynames-class) | [FieldUserPropertyNames Class](#fielduserpropertynames-class) | [SPHSiteReference Class](#sphsitereference-class) |
| [SPActivityResponseStatus Enum](#spactivityresponsestatus-enum) | [FieldUserSelectionMode Enum](#fielduserselectionmode-enum) | [SPImageItem Class](#spimageitem-class) |
| [AtoScenario Enum](#atoscenario-enum) | [FieldUserValue Class](#fielduservalue-class) | [SPInvitationCreationResult Class](#spinvitationcreationresult-class) |
| [AppSource Enum](#appsource-enum) | [File Class](#file-class) | [SPListRule Class](#splistrule-class) |
| [CustomFontsResource Class](#customfontsresource-class) | [FileCollection Class](#filecollection-class) | [SPMigrationJobStatus Class](#spmigrationjobstatus-class) |
| [CustomFontsResourceType Enum](#customfontsresourcetype-enum) | [FileCollectionAddParameters Class](#filecollectionaddparameters-class) | [SPMigrationJobStatusCollection Class](#spmigrationjobstatuscollection-class) |
| [DesignPackageType Enum](#designpackagetype-enum) | [FileCreationInformation Class](#filecreationinformation-class) | [SPMigrationJobStatusPropertyNames Class](#spmigrationjobstatuspropertynames-class) |
| [OrgAssets Class](#orgassets-class) | [FileDeleteParameters Class](#filedeleteparameters-class) | [SPMoveAndShareFileInfo Class](#spmoveandsharefileinfo-class) |
| [OrgAssetsLibrary Class](#orgassetslibrary-class) | [FileLevel Enum](#filelevel-enum) | [SPNavigationFlags Enum](#spnavigationflags-enum) |
| [OrgAssetsLibraryCollection Class](#orgassetslibrarycollection-class) | [FileObjectPropertyNames Class](#fileobjectpropertynames-class) | [SPOpenBinaryOptions Enum](#spopenbinaryoptions-enum) |
| [OrgAssetType Enum](#orgassettype-enum) | [FilePropertyNames Class](#filepropertynames-class) | [SPResourceEntry Class](#spresourceentry-class) |
| [SPEnterpriseContentTypeSyncTrigger Enum](#spenterprisecontenttypesynctrigger-enum) | [FileSaveBinaryInformation Class](#filesavebinaryinformation-class) | [SPResourceLCIDSource Enum](#spresourcelcidsource-enum) |
| [SPResilienceModeType Enum](#spresiliencemodetype-enum) | [FileSystemObjectType Enum](#filesystemobjecttype-enum) | [SPRuleAction Class](#spruleaction-class) |
| [CollaborationInsightsCounts Class](#collaborationinsightscounts-class) | [FileVersion Class](#fileversion-class) | [SPScriptSafeDomainsCollection Class](#spscriptsafedomainscollection-class) |
| [CollaborationInsightsData Class](#collaborationinsightsdata-class) | [FileVersionCollection Class](#fileversioncollection-class) | [SPSensivityLabelAssignmentMethod Enum](#spsensivitylabelassignmentmethod-enum) |
| [CollaborativeUsers Class](#collaborativeusers-class) | [FileVersionEvent Class](#fileversionevent-class) | [SPTeamsChannelType Enum](#spteamschanneltype-enum) |
| [OneDriveCollaborativeUsers Class](#onedrivecollaborativeusers-class) | [FileVersionEventCollection Class](#fileversioneventcollection-class) | [SPVariantThemeType Enum](#spvariantthemetype-enum) |
| [OneDriveSharePointCollaborativeUsers Class](#onedrivesharepointcollaborativeusers-class) | [FileVersionEventPropertyNames Class](#fileversioneventpropertynames-class) | [SPVirusCheckStatus Enum](#spviruscheckstatus-enum) |
| [PolicyDefinitionColumn Enum](#policydefinitioncolumn-enum) | [FileVersionEventType Enum](#fileversioneventtype-enum) | [StorageMetrics Class](#storagemetrics-class) |
| [PolicyFrequencyUnits Enum](#policyfrequencyunits-enum) | [FileVersionObjectPropertyNames Class](#fileversionobjectpropertynames-class) | [StorageMetricsPropertyNames Class](#storagemetricspropertynames-class) |
| [PolicyState Enum](#policystate-enum) | [FileVersionPropertyNames Class](#fileversionpropertynames-class) | [SubwebQuery Class](#subwebquery-class) |
| [PolicyStatus Enum](#policystatus-enum) | [FlowSynchronizationResult Class](#flowsynchronizationresult-class) | [TeamChannel Class](#teamchannel-class) |
| [PolicyTemplate Enum](#policytemplate-enum) | [FlowSynchronizationResultPropertyNames Class](#flowsynchronizationresultpropertynames-class) | [TeamChannelManager Class](#teamchannelmanager-class) |
| [PolicyTypes Enum](#policytypes-enum) | [FlowSynchronizationStatus Enum](#flowsynchronizationstatus-enum) | [TeamChannelPropertyNames Class](#teamchannelpropertynames-class) |
| [PolicyWorkItemType Enum](#policyworkitemtype-enum) | [Folder Class](#folder-class) | [TeamSiteData Class](#teamsitedata-class) |
| [RecentAdminActionReport Class](#recentadminactionreport-class) | [FolderCollection Class](#foldercollection-class) | [TeamSiteDataPropertyNames Class](#teamsitedatapropertynames-class) |
| [RecentAdminActionReportStatus Enum](#recentadminactionreportstatus-enum) | [FolderCollectionAddParameters Class](#foldercollectionaddparameters-class) | [TemplateFileType Enum](#templatefiletype-enum) |
| [TenantAdminActionSource Enum](#tenantadminactionsource-enum) | [FolderDeleteParameters Class](#folderdeleteparameters-class) | [TemplateMetaData Class](#templatemetadata-class) |
| [TenantAdminActionStatus Enum](#tenantadminactionstatus-enum) | [FolderObjectPropertyNames Class](#folderobjectpropertynames-class) | [TemplatizationMetaData Class](#templatizationmetadata-class) |
| [TenantAdminActionType Enum](#tenantadminactiontype-enum) | [FolderPropertyNames Class](#folderpropertynames-class) | [TemporaryFolderFileInfo Class](#temporaryfolderfileinfo-class) |
| [TenantAdminListItemColumnValue Class](#tenantadminlistitemcolumnvalue-class) | [FooterLayoutType Enum](#footerlayouttype-enum) | [TenantAppInformation Class](#tenantappinformation-class) |
| [TenantAdminPolicyAutomationExecutionHistory Class](#tenantadminpolicyautomationexecutionhistory-class) | [FooterVariantThemeType Enum](#footervariantthemetype-enum) | [TenantAppInstance Class](#tenantappinstance-class) |
| [TenantAdminPolicyDefinition Class](#tenantadminpolicydefinition-class) | [Form Class](#form-class) | [TenantAppInstancePropertyNames Class](#tenantappinstancepropertynames-class) |
| [TenantAdminRecentAction Class](#tenantadminrecentaction-class) | [FormCollection Class](#formcollection-class) | [TenantAppUtility Class](#tenantapputility-class) |
| [TenantAdminRecentActionPayload Class](#tenantadminrecentactionpayload-class) | [FormDigestInfo Class](#formdigestinfo-class) | [TenantSettings Class](#tenantsettings-class) |
| [ClientPeoplePickerQueryParameters Class](#clientpeoplepickerqueryparameters-class) | [FormPropertyNames Class](#formpropertynames-class) | [TenantSettingsPropertyNames Class](#tenantsettingspropertynames-class) |
| [ClientPeoplePickerWebServiceInterface Class](#clientpeoplepickerwebserviceinterface-class) | [GetListItemVersionsParameters Class](#getlistitemversionsparameters-class) | [ThemeInfo Class](#themeinfo-class) |
| [PeoplePickerQuerySettings Class](#peoplepickerquerysettings-class) | [GetListsParameters Class](#getlistsparameters-class) | [ThemeInfoPropertyNames Class](#themeinfopropertynames-class) |
| [PickerEntityInformation Class](#pickerentityinformation-class) | [Group Class](#group-class) | [TimeZone Class](#timezone-class) |
| [PickerEntityInformationPropertyNames Class](#pickerentityinformationpropertynames-class) | [GroupCollection Class](#groupcollection-class) | [TimeZoneCollection Class](#timezonecollection-class) |
| [PickerEntityInformationRequest Class](#pickerentityinformationrequest-class) | [GroupCreationInformation Class](#groupcreationinformation-class) | [TimeZoneInformation Class](#timezoneinformation-class) |
| [SPACSServicePrincipalInfo Class](#spacsserviceprincipalinfo-class) | [GroupObjectPropertyNames Class](#groupobjectpropertynames-class) | [TimeZonePropertyNames Class](#timezonepropertynames-class) |
| [BusinessAppMigrationOperationStatus Enum](#businessappmigrationoperationstatus-enum) | [GroupPropertyNames Class](#grouppropertynames-class) | [UpdateTemplateInfo Class](#updatetemplateinfo-class) |
| [AccessRequests Class](#accessrequests-class) | [Hashtag Class](#hashtag-class) | [UpdateTemplateInfoV2 Class](#updatetemplateinfov2-class) |
| [AddFieldOptions Enum](#addfieldoptions-enum) | [HeaderLayoutType Enum](#headerlayouttype-enum) | [UpgradeInfo Class](#upgradeinfo-class) |
| [Alert Class](#alert-class) | [HomeSiteNavConfiguration Class](#homesitenavconfiguration-class) | [UpgradeStatus Enum](#upgradestatus-enum) |
| [AlertCollection Class](#alertcollection-class) | [HomeSitesDetails Class](#homesitesdetails-class) | [UpgradeType Enum](#upgradetype-enum) |
| [AlertCreationInformation Class](#alertcreationinformation-class) | [HubSiteCreationInformation Class](#hubsitecreationinformation-class) | [UrlFieldFormatType Enum](#urlfieldformattype-enum) |
| [AlertDeliveryChannel Enum](#alertdeliverychannel-enum) | [InformationRightsManagementFileSettings Class](#informationrightsmanagementfilesettings-class) | [UrlTarget Enum](#urltarget-enum) |
| [AlertEventType Enum](#alerteventtype-enum) | [InformationRightsManagementFileSettingsPropertyNames Class](#informationrightsmanagementfilesettingspropertynames-class) | [UrlZone Enum](#urlzone-enum) |
| [AlertFrequency Enum](#alertfrequency-enum) | [InformationRightsManagementSettings Class](#informationrightsmanagementsettings-class) | [UsageInfo Class](#usageinfo-class) |
| [AlertObjectPropertyNames Class](#alertobjectpropertynames-class) | [InformationRightsManagementSettingsPropertyNames Class](#informationrightsmanagementsettingspropertynames-class) | [User Class](#user-class) |
| [AlertPropertyNames Class](#alertpropertynames-class) | [IngestionTaskKey Class](#ingestiontaskkey-class) | [UserCollection Class](#usercollection-class) |
| [AlertStatus Enum](#alertstatus-enum) | [KnowledgeHub Class](#knowledgehub-class) | [UserCreationInformation Class](#usercreationinformation-class) |
| [AlertType Enum](#alerttype-enum) | [KnowledgeHubSiteReference Class](#knowledgehubsitereference-class) | [UserCustomAction Class](#usercustomaction-class) |
| [AlternateUrl Class](#alternateurl-class) | [Language Class](#language-class) | [UserCustomActionCollection Class](#usercustomactioncollection-class) |
| [AlternateUrlPropertyNames Class](#alternateurlpropertynames-class) | [LanguageCollection Class](#languagecollection-class) | [UserCustomActionObjectPropertyNames Class](#usercustomactionobjectpropertynames-class) |
| [AnonymousLinkType Enum](#anonymouslinktype-enum) | [List Class](#list-class) | [UserCustomActionPropertyNames Class](#usercustomactionpropertynames-class) |
| [App Class](#app-class) | [ListBloomFilter Class](#listbloomfilter-class) | [UserCustomActionRegistrationType Enum](#usercustomactionregistrationtype-enum) |
| [AppCatalog Class](#appcatalog-class) | [ListBloomFilterPropertyNames Class](#listbloomfilterpropertynames-class) | [UserCustomActionScope Enum](#usercustomactionscope-enum) |
| [AppConfiguration Class](#appconfiguration-class) | [ListCollection Class](#listcollection-class) | [UserIdInfo Class](#useridinfo-class) |
| [AppConfigurationPropertyNames Class](#appconfigurationpropertynames-class) | [ListCollectionPosition Class](#listcollectionposition-class) | [UserObjectPropertyNames Class](#userobjectpropertynames-class) |
| [AppInstance Class](#appinstance-class) | [ListCollectionPropertyNames Class](#listcollectionpropertynames-class) | [UserPropertyNames Class](#userpropertynames-class) |
| [AppInstanceErrorDetails Class](#appinstanceerrordetails-class) | [ListCreationInformation Class](#listcreationinformation-class) | [UserResource Class](#userresource-class) |
| [AppInstanceErrorDetailsPropertyNames Class](#appinstanceerrordetailspropertynames-class) | [ListDataSource Class](#listdatasource-class) | [UserResourceScope Enum](#userresourcescope-enum) |
| [AppInstanceErrorSource Enum](#appinstanceerrorsource-enum) | [ListDataValidationExceptionValue Class](#listdatavalidationexceptionvalue-class) | [UserResourceType Enum](#userresourcetype-enum) |
| [AppInstanceErrorType Enum](#appinstanceerrortype-enum) | [ListDataValidationFailure Class](#listdatavalidationfailure-class) | [UserSharingCapabilities Enum](#usersharingcapabilities-enum) |
| [AppInstancePropertyNames Class](#appinstancepropertynames-class) | [ListDataValidationFailureReason Enum](#listdatavalidationfailurereason-enum) | [ValidationActionType Enum](#validationactiontype-enum) |
| [AppInstanceStatus Enum](#appinstancestatus-enum) | [ListDataValidationType Enum](#listdatavalidationtype-enum) | [View Class](#view-class) |
| [AppLicense Class](#applicense-class) | [ListExperience Enum](#listexperience-enum) | [ViewCollection Class](#viewcollection-class) |
| [AppLicenseCollection Class](#applicensecollection-class) | [ListHomeItem Class](#listhomeitem-class) | [ViewCreationInformation Class](#viewcreationinformation-class) |
| [AppLicenseType Enum](#applicensetype-enum) | [ListHomeItem2 Class](#listhomeitem2-class) | [ViewFieldCollection Class](#viewfieldcollection-class) |
| [AppPrincipal Class](#appprincipal-class) | [ListHomeItem2PropertyNames Class](#listhomeitem2propertynames-class) | [ViewFieldCollectionPropertyNames Class](#viewfieldcollectionpropertynames-class) |
| [AppPrincipalConfiguration Class](#appprincipalconfiguration-class) | [ListHomeItemCollection Class](#listhomeitemcollection-class) | [ViewObjectPropertyNames Class](#viewobjectpropertynames-class) |
| [AppPrincipalCredential Class](#appprincipalcredential-class) | [ListItem Class](#listitem-class) | [ViewPropertyNames Class](#viewpropertynames-class) |
| [AppPrincipalCredentialReference Class](#appprincipalcredentialreference-class) | [ListItemCollection Class](#listitemcollection-class) | [ViewScope Enum](#viewscope-enum) |
| [AppPrincipalIdentityProvider Class](#appprincipalidentityprovider-class) | [ListItemCollectionPosition Class](#listitemcollectionposition-class) | [ViewType Enum](#viewtype-enum) |
| [AppPrincipalManager Class](#appprincipalmanager-class) | [ListItemCollectionPropertyNames Class](#listitemcollectionpropertynames-class) | [VinciAnalyticsDimensionsRequest Class](#vincianalyticsdimensionsrequest-class) |
| [AppPrincipalName Class](#appprincipalname-class) | [ListItemComplianceInfo Class](#listitemcomplianceinfo-class) | [VinciAnalyticsReportRequest Class](#vincianalyticsreportrequest-class) |
| [AppPrincipalPropertyNames Class](#appprincipalpropertynames-class) | [ListItemCreationInformation Class](#listitemcreationinformation-class) | [VinciAnalyticsReportTableElement Class](#vincianalyticsreporttableelement-class) |
| [AppProperties Class](#appproperties-class) | [ListItemCreationInformationUsingPath Class](#listitemcreationinformationusingpath-class) | [VinciAnalyticsReportTableRow Class](#vincianalyticsreporttablerow-class) |
| [AppPropertyNames Class](#apppropertynames-class) | [ListItemDeleteParameters Class](#listitemdeleteparameters-class) | [Visualization Class](#visualization-class) |
| [ApprovalRequest Class](#approvalrequest-class) | [ListItemEntityCollection Class](#listitementitycollection-class) | [VisualizationAppInfo Class](#visualizationappinfo-class) |
| [ApprovalRequestPropertyNames Class](#approvalrequestpropertynames-class) | [ListItemFormUpdateValue Class](#listitemformupdatevalue-class) | [VisualizationAppMappedViewCollection Class](#visualizationappmappedviewcollection-class) |
| [Approvals Class](#approvals-class) | [ListItemObjectPropertyNames Class](#listitemobjectpropertynames-class) | [VisualizationAppSynchronizationResult Class](#visualizationappsynchronizationresult-class) |
| [ApprovalsCreateRequestParameters Class](#approvalscreaterequestparameters-class) | [ListItemPropertyNames Class](#listitempropertynames-class) | [VisualizationAppSynchronizationResultObjectPropertyNames Class](#visualizationappsynchronizationresultobjectpropertynames-class) |
| [ApprovalsManager Class](#approvalsmanager-class) | [ListItemUpdateParameters Class](#listitemupdateparameters-class) | [VisualizationAppSynchronizationResultPropertyNames Class](#visualizationappsynchronizationresultpropertynames-class) |
| [ApprovalsProperties Class](#approvalsproperties-class) | [ListItemUpdateResults Class](#listitemupdateresults-class) | [VisualizationAppSynchronizationStatus Enum](#visualizationappsynchronizationstatus-enum) |
| [ApproverSource Enum](#approversource-enum) | [ListItemVersion Class](#listitemversion-class) | [VisualizationAppTarget Enum](#visualizationapptarget-enum) |
| [AppSiteContext Class](#appsitecontext-class) | [ListItemVersionCollection Class](#listitemversioncollection-class) | [VisualizationField Class](#visualizationfield-class) |
| [AppSiteContextUtility Class](#appsitecontextutility-class) | [ListItemVersionCollectionPosition Class](#listitemversioncollectionposition-class) | [VisualizationStyleSet Class](#visualizationstyleset-class) |
| [AppStatus Enum](#appstatus-enum) | [ListItemVersionCollectionPropertyNames Class](#listitemversioncollectionpropertynames-class) | [VisualizationType Enum](#visualizationtype-enum) |
| [AppTile Class](#apptile-class) | [ListItemVersionObjectPropertyNames Class](#listitemversionobjectpropertynames-class) | [VivaConnectionsUrlConfiguration Class](#vivaconnectionsurlconfiguration-class) |
| [AppTileCollection Class](#apptilecollection-class) | [ListItemVersionPropertyNames Class](#listitemversionpropertynames-class) | [Web Class](#web-class) |
| [AppTileProperties Class](#apptileproperties-class) | [ListObjectPropertyNames Class](#listobjectpropertynames-class) | [WebCollection Class](#webcollection-class) |
| [AppTilePropertyNames Class](#apptilepropertynames-class) | [ListPageRenderType Enum](#listpagerendertype-enum) | [WebCreationInformation Class](#webcreationinformation-class) |
| [AppType Enum](#apptype-enum) | [ListPropertyNames Class](#listpropertynames-class) | [WebInformation Class](#webinformation-class) |
| [AppViewCreationInfo Class](#appviewcreationinfo-class) | [ListTemplate Class](#listtemplate-class) | [WebInformationPropertyNames Class](#webinformationpropertynames-class) |
| [ArchiveState Enum](#archivestate-enum) | [ListTemplateCollection Class](#listtemplatecollection-class) | [WebObjectPropertyNames Class](#webobjectpropertynames-class) |
| [AsyncReadJobInfo Class](#asyncreadjobinfo-class) | [ListTemplatePropertyNames Class](#listtemplatepropertynames-class) | [WebPropertyNames Class](#webpropertynames-class) |
| [AsyncReadOptions Class](#asyncreadoptions-class) | [ListTemplateType Enum](#listtemplatetype-enum) | [WebProxy Class](#webproxy-class) |
| [Attachment Class](#attachment-class) | [LockFileData Class](#lockfiledata-class) | [WebRequestInfo Class](#webrequestinfo-class) |
| [AttachmentCollection Class](#attachmentcollection-class) | [LogoAlignment Enum](#logoalignment-enum) | [WebResponseInfo Class](#webresponseinfo-class) |
| [AttachmentCreationInformation Class](#attachmentcreationinformation-class) | [MachineLearningSampleMeta Class](#machinelearningsamplemeta-class) | [WebTemplate Class](#webtemplate-class) |
| [AttachmentPropertyNames Class](#attachmentpropertynames-class) | [MediaServiceUpdateParameters Class](#mediaserviceupdateparameters-class) | [WebTemplateCollection Class](#webtemplatecollection-class) |
| [Audit Class](#audit-class) | [MicroServiceManager Class](#microservicemanager-class) | [WebTemplatePropertyNames Class](#webtemplatepropertynames-class) |
| [AuditMaskType Enum](#auditmasktype-enum) | [MicroServiceUtilities Class](#microserviceutilities-class) | [FeatureScope Enum](#featurescope-enum) |
| [AuditPropertyNames Class](#auditpropertynames-class) | [MicroServiceWorkItemProperties Class](#microserviceworkitemproperties-class) | [OrgRelationRole Enum](#orgrelationrole-enum) |
| [AutoLabellingWorkInformation Class](#autolabellingworkinformation-class) | [MigrationJobState Enum](#migrationjobstate-enum) | [OrgRelationScenario Enum](#orgrelationscenario-enum) |
| [BasePermissions Class](#basepermissions-class) | [MigrationNameConflictBehavior Enum](#migrationnameconflictbehavior-enum) | [OrgRelationState Enum](#orgrelationstate-enum) |
| [BaseType Enum](#basetype-enum) | [ModernizeHomepageResult Class](#modernizehomepageresult-class) | [OrgRelationVerificationStatus Enum](#orgrelationverificationstatus-enum) |
| [BrowserFileHandling Enum](#browserfilehandling-enum) | [ModernizeHomepageResultPropertyNames Class](#modernizehomepageresultpropertynames-class) | [SPBlockDownloadFileTypeId Enum](#spblockdownloadfiletypeid-enum) |
| [CalendarType Enum](#calendartype-enum) | [MountedFolderInfo Class](#mountedfolderinfo-class) | [TenantIdentityMapItemType Enum](#tenantidentitymapitemtype-enum) |
| [CamlQuery Class](#camlquery-class) | [MountedFolderInfoPropertyNames Class](#mountedfolderinfopropertynames-class) | [TenantIdentityMappingGroupField Enum](#tenantidentitymappinggroupfield-enum) |
| [CampaignCommunicationEntity Class](#campaigncommunicationentity-class) | [MountPoint Class](#mountpoint-class) | [TenantIdentityMappingGroupType Enum](#tenantidentitymappinggrouptype-enum) |
| [CampaignEntity Class](#campaignentity-class) | [MountPointInfo Class](#mountpointinfo-class) | [TenantIdentityMappingUserField Enum](#tenantidentitymappinguserfield-enum) |
| [Campaigns Class](#campaigns-class) | [MountPointInfoPropertyNames Class](#mountpointinfopropertynames-class) | [TenantIdentityMappingUserType Enum](#tenantidentitymappingusertype-enum) |
| [CampaignSummary Class](#campaignsummary-class) | [MoveCopyOptions Class](#movecopyoptions-class) | [TenantIdentityMigrationState Enum](#tenantidentitymigrationstate-enum) |
| [CampaignUserInfo Class](#campaignuserinfo-class) | [MoveCopyUtil Class](#movecopyutil-class) | [TenantIdentityMigrationStatus Enum](#tenantidentitymigrationstatus-enum) |
| [CampainAnalytics Class](#campainanalytics-class) | [MoveOperations Enum](#moveoperations-enum) | [TenantStoreIdentityMigrationProperty Enum](#tenantstoreidentitymigrationproperty-enum) |
| [Change Class](#change-class) | [MultiGeoCopyParameters Class](#multigeocopyparameters-class) | [AnalyticsUsageEntry Class](#analyticsusageentry-class) |
| [ChangeAlert Class](#changealert-class) | [Navigation Class](#navigation-class) | [EventTypeId Enum](#eventtypeid-enum) |
| [ChangeAlertPropertyNames Class](#changealertpropertynames-class) | [NavigationNode Class](#navigationnode-class) | [NativeClient Class](#nativeclient-class) |
| [ChangeCollection Class](#changecollection-class) | [NavigationNodeCollection Class](#navigationnodecollection-class) | [ClickManager Class](#clickmanager-class) |
| [ChangeCollectionPropertyNames Class](#changecollectionpropertynames-class) | [NavigationNodeCreationInformation Class](#navigationnodecreationinformation-class) | [PageImpressionClient Class](#pageimpressionclient-class) |
| [ChangeContentType Class](#changecontenttype-class) | [NavigationNodeObjectPropertyNames Class](#navigationnodeobjectpropertynames-class) | [BlockDownloadLinksFileType Enum](#blockdownloadlinksfiletype-enum) |
| [ChangeContentTypePropertyNames Class](#changecontenttypepropertynames-class) | [NavigationNodePropertyNames Class](#navigationnodepropertynames-class) | [DocumentSharingManager Class](#documentsharingmanager-class) |
| [ChangeField Class](#changefield-class) | [NavigationObjectPropertyNames Class](#navigationobjectpropertynames-class) | [RemoveItemsFromSharedWithMeViewErrorCode Enum](#removeitemsfromsharedwithmeviewerrorcode-enum) |
| [ChangeFieldPropertyNames Class](#changefieldpropertynames-class) | [NavigationPropertyNames Class](#navigationpropertynames-class) | [Role Enum](#role-enum) |
| [ChangeFile Class](#changefile-class) | [NewsCollection Class](#newscollection-class) | [SharedObjectType Enum](#sharedobjecttype-enum) |
| [ChangeFilePropertyNames Class](#changefilepropertynames-class) | [ObjectSharingInformation Class](#objectsharinginformation-class) | [SharedWithMeViewItemRemovalResult Class](#sharedwithmeviewitemremovalresult-class) |
| [ChangeFolder Class](#changefolder-class) | [ObjectSharingInformationObjectPropertyNames Class](#objectsharinginformationobjectpropertynames-class) | [SharingDomainRestrictionMode Enum](#sharingdomainrestrictionmode-enum) |
| [ChangeFolderPropertyNames Class](#changefolderpropertynames-class) | [ObjectSharingInformationPropertyNames Class](#objectsharinginformationpropertynames-class) | [SharingLinkExpressOptions Enum](#sharinglinkexpressoptions-enum) |
| [ChangeGroup Class](#changegroup-class) | [ObjectSharingInformationUser Class](#objectsharinginformationuser-class) | [SharingScope Enum](#sharingscope-enum) |
| [ChangeGroupPropertyNames Class](#changegrouppropertynames-class) | [ObjectSharingInformationUserCollection Class](#objectsharinginformationusercollection-class) | [UserRoleAssignment Class](#userroleassignment-class) |
| [ChangeItem Class](#changeitem-class) | [ObjectSharingInformationUserObjectPropertyNames Class](#objectsharinginformationuserobjectpropertynames-class) | [UserSharingResult Class](#usersharingresult-class) |
| [ChangeItemPropertyNames Class](#changeitempropertynames-class) | [ObjectSharingInformationUserPropertyNames Class](#objectsharinginformationuserpropertynames-class) | [WebSharingManager Class](#websharingmanager-class) |
| [ChangeList Class](#changelist-class) | [ObjectSharingSettings Class](#objectsharingsettings-class) | [SiteHealthResult Class](#sitehealthresult-class) |
| [ChangeListObjectPropertyNames Class](#changelistobjectpropertynames-class) | [ObjectSharingSettingsObjectPropertyNames Class](#objectsharingsettingsobjectpropertynames-class) | [SiteHealthStatusType Enum](#sitehealthstatustype-enum) |
| [ChangeListPropertyNames Class](#changelistpropertynames-class) | [ObjectSharingSettingsPropertyNames Class](#objectsharingsettingspropertynames-class) | [SiteHealthSummary Class](#sitehealthsummary-class) |
| [ChangeLogItemQuery Class](#changelogitemquery-class) | [OpenWebOptions Enum](#openweboptions-enum) | [SiteHealthSummaryPropertyNames Class](#sitehealthsummarypropertynames-class) |
| [ChangePropertyNames Class](#changepropertynames-class) | [OpenWebParameters Class](#openwebparameters-class) | [DateTimeFormat Enum](#datetimeformat-enum) |
| [ChangeQuery Class](#changequery-class) | [OrganizationNews Class](#organizationnews-class) | [EmailProperties Class](#emailproperties-class) |
| [ChangeSite Class](#changesite-class) | [OrganizationNewsSiteReference Class](#organizationnewssitereference-class) | [FileHandlerWopiProperties Class](#filehandlerwopiproperties-class) |
| [ChangeToken Class](#changetoken-class) | [OutputFileFormat Enum](#outputfileformat-enum) | [FileHandlerWopiPropertiesPropertyNames Class](#filehandlerwopipropertiespropertynames-class) |
| [ChangeType Enum](#changetype-enum) | [PageType Enum](#pagetype-enum) | [IconSize Enum](#iconsize-enum) |
| [ChangeUser Class](#changeuser-class) | [PermissionKind Enum](#permissionkind-enum) | [JsonTheme Class](#jsontheme-class) |
| [ChangeUserPropertyNames Class](#changeuserpropertynames-class) | [PickerSettings Class](#pickersettings-class) | [LogAppErrorResult Enum](#logapperrorresult-enum) |
| [ChangeView Class](#changeview-class) | [PickerSettingsPropertyNames Class](#pickersettingspropertynames-class) | [PrincipalInfo Class](#principalinfo-class) |
| [ChangeViewPropertyNames Class](#changeviewpropertynames-class) | [PinnedItems Class](#pinneditems-class) | [PrincipalSource Enum](#principalsource-enum) |
| [ChangeWeb Class](#changeweb-class) | [PivotItem Class](#pivotitem-class) | [PrincipalType Enum](#principaltype-enum) |
| [ChangeWebPropertyNames Class](#changewebpropertynames-class) | [Placeholder Class](#placeholder-class) | [SPSocialSwitch Class](#spsocialswitch-class) |
| [CheckedOutFile Class](#checkedoutfile-class) | [PlaceholderV2 Class](#placeholderv2-class) | [SPWOPIFrameAction Enum](#spwopiframeaction-enum) |
| [CheckedOutFileCollection Class](#checkedoutfilecollection-class) | [PolicyTipUserAction Enum](#policytipuseraction-enum) | [ThemingOptions Class](#themingoptions-class) |
| [CheckedOutFileObjectPropertyNames Class](#checkedoutfileobjectpropertynames-class) | [PolicyTipUserActionResult Enum](#policytipuseractionresult-enum) | [UploadStatus Class](#uploadstatus-class) |
| [CheckedOutFilePropertyNames Class](#checkedoutfilepropertynames-class) | [PortalAndOrgNewsSiteReference Class](#portalandorgnewssitereference-class) | [UploadStatusPropertyNames Class](#uploadstatuspropertynames-class) |
| [CheckinType Enum](#checkintype-enum) | [Principal Class](#principal-class) | [Utility Class](#utility-class) |
| [CheckOutType Enum](#checkouttype-enum) | [PrincipalPropertyNames Class](#principalpropertynames-class) | [WebAppExtUrlPair Class](#webappexturlpair-class) |
| [ChoiceFormatType Enum](#choiceformattype-enum) | [PropertyValues Class](#propertyvalues-class) | [WebAppUrlsByAction Class](#webappurlsbyaction-class) |
| [ClassificationResult Class](#classificationresult-class) | [ProvisionedMigrationContainersInfo Class](#provisionedmigrationcontainersinfo-class) | [WikiPageCreationInformation Class](#wikipagecreationinformation-class) |
| [ClientContext Class](#clientcontext-class) | [ProvisionedMigrationQueueInfo Class](#provisionedmigrationqueueinfo-class) | [WopiHostUtility Class](#wopihostutility-class) |
| [CompatibilityRange Class](#compatibilityrange-class) | [ProvisionedTemporaryAzureContainerInfo Class](#provisionedtemporaryazurecontainerinfo-class) | [WopiProperties Class](#wopiproperties-class) |
| [ConfigurationData Class](#configurationdata-class) | [PushNotificationSubscriber Class](#pushnotificationsubscriber-class) | [WopiPropertiesPropertyNames Class](#wopipropertiespropertynames-class) |
| [ContentAssemblyFileInfo Class](#contentassemblyfileinfo-class) | [PushNotificationSubscriberCollection Class](#pushnotificationsubscribercollection-class) | [WopiWebAppProperties Class](#wopiwebappproperties-class) |
| [ContentAssemblyFormAnswer Class](#contentassemblyformanswer-class) | [PushNotificationSubscriberObjectPropertyNames Class](#pushnotificationsubscriberobjectpropertynames-class) | [LimitedWebPartManager Class](#limitedwebpartmanager-class) |
| [ContentControlInfo Class](#contentcontrolinfo-class) | [PushNotificationSubscriberPropertyNames Class](#pushnotificationsubscriberpropertynames-class) | [LimitedWebPartManagerObjectPropertyNames Class](#limitedwebpartmanagerobjectpropertynames-class) |
| [ContentType Class](#contenttype-class) | [QuickAccessItemCollection Class](#quickaccessitemcollection-class) | [LimitedWebPartManagerPropertyNames Class](#limitedwebpartmanagerpropertynames-class) |
| [ContentTypeCollection Class](#contenttypecollection-class) | [QuickLaunchOptions Enum](#quicklaunchoptions-enum) | [PersonalizationScope Enum](#personalizationscope-enum) |
| [ContentTypeCreationInformation Class](#contenttypecreationinformation-class) | [RecentFileCollection Class](#recentfilecollection-class) | [TileData Class](#tiledata-class) |
| [ContentTypeId Class](#contenttypeid-class) | [RecentList Class](#recentlist-class) | [WebPart Class](#webpart-class) |
| [ContentTypeObjectPropertyNames Class](#contenttypeobjectpropertynames-class) | [RecentListCollection Class](#recentlistcollection-class) | [WebPartDefinition Class](#webpartdefinition-class) |
| [ContentTypePropertyNames Class](#contenttypepropertynames-class) | [RecentListPropertyNames Class](#recentlistpropertynames-class) | [WebPartDefinitionCollection Class](#webpartdefinitioncollection-class) |
| [CopyJobProgress Class](#copyjobprogress-class) | [RecentListProxy Class](#recentlistproxy-class) | [WebPartDefinitionObjectPropertyNames Class](#webpartdefinitionobjectpropertynames-class) |
| [CopyMigrationInfo Class](#copymigrationinfo-class) | [RecycleBinItem Class](#recyclebinitem-class) | [WebPartDefinitionPropertyNames Class](#webpartdefinitionpropertynames-class) |
| [CopyMigrationOptions Class](#copymigrationoptions-class) | [RecycleBinItemCollection Class](#recyclebinitemcollection-class) | [WebPartExportMode Enum](#webpartexportmode-enum) |
| [CopySourceInfo Class](#copysourceinfo-class) | [RecycleBinItemObjectPropertyNames Class](#recyclebinitemobjectpropertynames-class) | [WebPartObjectPropertyNames Class](#webpartobjectpropertynames-class) |
| [CountByDate Class](#countbydate-class) | [RecycleBinItemPropertyNames Class](#recyclebinitempropertynames-class) | [WebPartPropertyNames Class](#webpartpropertynames-class) |
| [CreatableItemInfo Class](#creatableiteminfo-class) | [RecycleBinItemState Enum](#recyclebinitemstate-enum) | [WorkflowAssociation Class](#workflowassociation-class) |
| [CreatableItemInfoCollection Class](#creatableiteminfocollection-class) | [RecycleBinItemType Enum](#recyclebinitemtype-enum) | [WorkflowAssociationCollection Class](#workflowassociationcollection-class) |
| [CreatablesInfo Class](#creatablesinfo-class) | [RecycleBinOrderBy Enum](#recyclebinorderby-enum) | [WorkflowAssociationCreationInformation Class](#workflowassociationcreationinformation-class) |
| [CreatablesInfoPropertyNames Class](#creatablesinfopropertynames-class) | [RecycleBinQueryInformation Class](#recyclebinqueryinformation-class) | [WorkflowAssociationPropertyNames Class](#workflowassociationpropertynames-class) |
| [CurrencyInformation Class](#currencyinformation-class) | [RegionalSettings Class](#regionalsettings-class) | [WorkflowTemplate Class](#workflowtemplate-class) |
| [CurrencyInformationCollection Class](#currencyinformationcollection-class) | [RegionalSettingsObjectPropertyNames Class](#regionalsettingsobjectpropertynames-class) | [WorkflowTemplateCollection Class](#workflowtemplatecollection-class) |
| [CurrencyList Class](#currencylist-class) | [RegionalSettingsPropertyNames Class](#regionalsettingspropertynames-class) | [WorkflowTemplatePropertyNames Class](#workflowtemplatepropertynames-class) |
| [CustomActionElement Class](#customactionelement-class) | [RelatedField Class](#relatedfield-class) | [HostedApp Class](#hostedapp-class) |
| [CustomActionElementCollection Class](#customactionelementcollection-class) | [RelatedFieldCollection Class](#relatedfieldcollection-class) | [HostedAppAddResponse Class](#hostedappaddresponse-class) |
| [CustomerKeyInfo Class](#customerkeyinfo-class) | [RelatedFieldObjectPropertyNames Class](#relatedfieldobjectpropertynames-class) | [HostedAppAddResponsePropertyNames Class](#hostedappaddresponsepropertynames-class) |
| [CustomerKeyStatus Enum](#customerkeystatus-enum) | [RelatedFieldPropertyNames Class](#relatedfieldpropertynames-class) | [HostedAppsManager Class](#hostedappsmanager-class) |
| [CustomerKeyStatusInfo Class](#customerkeystatusinfo-class) | [RelatedItem Class](#relateditem-class) | [StorageEntity Class](#storageentity-class) |
| [CustomerKeyVaultInfo Class](#customerkeyvaultinfo-class) | [RelatedItemManager Class](#relateditemmanager-class) | [StorageEntityPropertyNames Class](#storageentitypropertynames-class) |
| [CustomerKeyVaultKeyType Enum](#customerkeyvaultkeytype-enum) | [RelationshipDeleteBehaviorType Enum](#relationshipdeletebehaviortype-enum) | [CommentsDisabledScope Enum](#commentsdisabledscope-enum) |
| [CustomerRecoveryKeyMode Enum](#customerrecoverykeymode-enum) | [RemoteWeb Class](#remoteweb-class) | [ShortcutInformation Class](#shortcutinformation-class) |
| [CustomizedFormsPage Class](#customizedformspage-class) | [RemoteWebObjectPropertyNames Class](#remotewebobjectpropertynames-class) | [GroupSiteRelationship Enum](#groupsiterelationship-enum) |
| [CustomizedFormsPageCollection Class](#customizedformspagecollection-class) | [RemoteWebPropertyNames Class](#remotewebpropertynames-class) | [SiteCollectionAppCatalogAllowedCollection Class](#sitecollectionappcatalogallowedcollection-class) |
| [CustomizedPageStatus Enum](#customizedpagestatus-enum) | [RenderListContextMenuDataParameters Class](#renderlistcontextmenudataparameters-class) | [SiteCollectionAppCatalogAllowedItem Class](#sitecollectionappcatalogalloweditem-class) |
| [DashboardItem Class](#dashboarditem-class) | [RenderListDataOptions Enum](#renderlistdataoptions-enum) | [SiteCollectionAppCatalogAllowedItemPropertyNames Class](#sitecollectionappcatalogalloweditempropertynames-class) |
| [DashboardItemInfo Class](#dashboarditeminfo-class) | [RenderListDataOverrideParameters Class](#renderlistdataoverrideparameters-class) | [SiteCollectionCorporateCatalogAccessor Class](#sitecollectioncorporatecatalogaccessor-class) |
| [DateTimeFieldFormatType Enum](#datetimefieldformattype-enum) | [RenderListDataParameters Class](#renderlistdataparameters-class) | [SPAppInstallationInfo Class](#spappinstallationinfo-class) |
| [DateTimeFieldFriendlyFormatType Enum](#datetimefieldfriendlyformattype-enum) | [RenderListFilterDataParameters Class](#renderlistfilterdataparameters-class) | [SPStoreAppCreateByIdInformation Class](#spstoreappcreatebyidinformation-class) |
| [DimensionsResponse Class](#dimensionsresponse-class) | [RenderListFormDataOptions Enum](#renderlistformdataoptions-enum) | [SPStoreAppRequestInformation Class](#spstoreapprequestinformation-class) |
| [DlpPolicyTip Class](#dlppolicytip-class) | [ReportResponse Class](#reportresponse-class) | [SPStoreAppResponseInformation Class](#spstoreappresponseinformation-class) |
| [DlpPolicyTipPropertyNames Class](#dlppolicytippropertynames-class) | [RequestContext Class](#requestcontext-class) | [StoreAppCreationInformation Class](#storeappcreationinformation-class) |
| [DocumentGenerationInfo Class](#documentgenerationinfo-class) | [RequestContextObjectPropertyNames Class](#requestcontextobjectpropertynames-class) | [TeamsPackageDownload Class](#teamspackagedownload-class) |
| [DocumentLibraryInformation Class](#documentlibraryinformation-class) | [RequestResourceConstants Class](#requestresourceconstants-class) | [TenantCorporateCatalogAccessor Class](#tenantcorporatecatalogaccessor-class) |
| [DocumentTemplateType Enum](#documenttemplatetype-enum) | [RequestResources Class](#requestresources-class) | [TenantCorporateCatalogAccessorObjectPropertyNames Class](#tenantcorporatecatalogaccessorobjectpropertynames-class) |
| [DraftVisibilityType Enum](#draftvisibilitytype-enum) | [RequestType Enum](#requesttype-enum) | [NavigationSource Enum](#navigationsource-enum) |
| [EffectiveInformationRightsManagementSettings Class](#effectiveinformationrightsmanagementsettings-class) | [RequestUserContext Class](#requestusercontext-class) | [Document Class](#document-class) |
| [EffectiveInformationRightsManagementSettingsPropertyNames Class](#effectiveinformationrightsmanagementsettingspropertynames-class) | [RequestUserContextObjectPropertyNames Class](#requestusercontextobjectpropertynames-class) | [DocumentReference Class](#documentreference-class) |
| [EmployeeEngagement Class](#employeeengagement-class) | [RequestVariable Class](#requestvariable-class) | [Folder Class](#folder-class) |
| [EncryptionOption Class](#encryptionoption-class) | [RequestVariablePropertyNames Class](#requestvariablepropertynames-class) | [Item Class](#item-class) |
| [EnqueueJobInformation Class](#enqueuejobinformation-class) | [ResourcePath Class](#resourcepath-class) | [ItemReference Class](#itemreference-class) |
| [EnqueueJobStatus Enum](#enqueuejobstatus-enum) | [RoleAssignment Class](#roleassignment-class) | [ItemsList Class](#itemslist-class) |
| [EventReceiverDefinition Class](#eventreceiverdefinition-class) | [RoleAssignmentCollection Class](#roleassignmentcollection-class) | [Library Class](#library-class) |
| [EventReceiverDefinitionCollection Class](#eventreceiverdefinitioncollection-class) | [RoleAssignmentCollectionObjectPropertyNames Class](#roleassignmentcollectionobjectpropertynames-class) | [NavigatableItem Class](#navigatableitem-class) |
| [EventReceiverDefinitionCreationInformation Class](#eventreceiverdefinitioncreationinformation-class) | [RoleAssignmentObjectPropertyNames Class](#roleassignmentobjectpropertynames-class) | [NewsArticle Class](#newsarticle-class) |
| [EventReceiverDefinitionPropertyNames Class](#eventreceiverdefinitionpropertynames-class) | [RoleAssignmentPropertyNames Class](#roleassignmentpropertynames-class) | [NewsSourceType Enum](#newssourcetype-enum) |
| [EventReceiverSynchronization Enum](#eventreceiversynchronization-enum) | [RoleDefinition Class](#roledefinition-class) | [NewsType Enum](#newstype-enum) |
| [EventReceiverType Enum](#eventreceivertype-enum) | [RoleDefinitionBindingCollection Class](#roledefinitionbindingcollection-class) | [Person Class](#person-class) |
| [ExternalAppPrincipalCreationParameters Class](#externalappprincipalcreationparameters-class) | [RoleDefinitionCollection Class](#roledefinitioncollection-class) | [PersonReference Class](#personreference-class) |
| [FavoriteListHomeItem Class](#favoritelisthomeitem-class) | [RoleDefinitionCreationInformation Class](#roledefinitioncreationinformation-class) | [SerializableType Class](#serializabletype-class) |
| [FavoriteLists Class](#favoritelists-class) | [RoleDefinitionPropertyNames Class](#roledefinitionpropertynames-class) | [SPOSite Class](#sposite-class) |
| [FavoriteListsSubstrate Class](#favoritelistssubstrate-class) | [RoleType Enum](#roletype-enum) | [SPOSiteReference Class](#spositereference-class) |
| [Feature Class](#feature-class) | [RuleOverrideOptions Enum](#ruleoverrideoptions-enum) | [AppDetails Class](#appdetails-class) |
| [FeatureCollection Class](#featurecollection-class) | [SandboxedCodeActivationCapabilities Enum](#sandboxedcodeactivationcapabilities-enum) | [AppDetailsPropertyNames Class](#appdetailspropertynames-class) |
| [FeatureDefinitionScope Enum](#featuredefinitionscope-enum) | [ScriptSafeDomain Class](#scriptsafedomain-class) | [AppIconInfo Class](#appiconinfo-class) |
| [FeaturePropertyNames Class](#featurepropertynames-class) | [ScriptSafeDomainEntityData Class](#scriptsafedomainentitydata-class) | [AppIconInfoPropertyNames Class](#appiconinfopropertynames-class) |
| [Field Class](#field-class) | [ScriptSafeExternalEmbedding Enum](#scriptsafeexternalembedding-enum) | [OperationType Enum](#operationtype-enum) |
| [FieldCalculated Class](#fieldcalculated-class) | [ScriptTypeFactory Class](#scripttypefactory-class) | [SmartCacheItem Class](#smartcacheitem-class) |
| [FieldCalculatedErrorValue Class](#fieldcalculatederrorvalue-class) | [SearchBoxInNavBarType Enum](#searchboxinnavbartype-enum) | [SmartCacheItemPropertyNames Class](#smartcacheitempropertynames-class) |
| [FieldCalculatedPropertyNames Class](#fieldcalculatedpropertynames-class) | [SearchScopeType Enum](#searchscopetype-enum) | [TenantCdnUrl Class](#tenantcdnurl-class) |
| [FieldChoice Class](#fieldchoice-class) | [SecurableObject Class](#securableobject-class) | [SiteScriptStore Enum](#sitescriptstore-enum) |
| [FieldChoicePropertyNames Class](#fieldchoicepropertynames-class) | [SecurableObjectObjectPropertyNames Class](#securableobjectobjectpropertynames-class) | [ModuleLink Class](#modulelink-class) |
| [FieldCollection Class](#fieldcollection-class) | [SecurableObjectPropertyNames Class](#securableobjectpropertynames-class) | [ResourceManifestInformation Class](#resourcemanifestinformation-class) |
| [FieldCollectionPropertyNames Class](#fieldcollectionpropertynames-class) | [SensitivityLabelInfo Class](#sensitivitylabelinfo-class) | [ResourceManifestInformationPropertyNames Class](#resourcemanifestinformationpropertynames-class) |
| [FieldComputed Class](#fieldcomputed-class) | [SensitivityLabelWorkItemType Enum](#sensitivitylabelworkitemtype-enum) |   |
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
# SPActivityResponseStatus Enum

Namespace: Microsoft.SharePoint.Activities


## Values

| Name | Summary |
|---|---|
| **Success** |  |
| **UnknownError** |  |
| **BadRequest** |  |
| **AccessDenied** |  |
| **ActivityNotFound** |  |
| **ActivityAlreadyExists** |  |
| **Disabled** |  |
| **InternalError** |  |
# AtoScenario Enum

Namespace: Microsoft.SharePoint.AddToOneDrive


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **Vault** |  |
| **AlbumPhoto** |  |
# AppSource Enum

Namespace: Microsoft.SharePoint.Administration


## Values

| Name | Summary |
|---|---|
| **InvalidSource** |  |
| **Marketplace** |  |
| **CorporateCatalog** |  |
| **DeveloperSite** |  |
| **ObjectModel** |  |
| **RemoteObjectModel** |  |
| **SiteCollectionCorporateCatalog** |  |
# CustomFontsResource Class

Namespace: Microsoft.SharePoint.Administration

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **byteArray** | byte[] |  |
| **fileName** | string |  |
| **fullPath** | string |  |
| **MajVer** | int |  |
| **type** | [CustomFontsResourceType](#customfontsresourcetype-enum) |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# CustomFontsResourceType Enum

Namespace: Microsoft.SharePoint.Administration


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **Catalog** |  |
| **Font** |  |
# DesignPackageType Enum

Namespace: Microsoft.SharePoint.Administration


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **Topic** |  |
| **Showcase** |  |
| **Blank** |  |
| **TeamSite** |  |
# OrgAssets Class

Namespace: Microsoft.SharePoint.Administration

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **CentralAssetRepositoryLibraries** | [OrgAssetsLibraryCollection](#orgassetslibrarycollection-class) |  |
| **Domain** | [ResourcePath](#resourcepath-class) |  |
| **OrgAssetsLibraries** | [OrgAssetsLibraryCollection](#orgassetslibrarycollection-class) |  |
| **SiteId** | Guid |  |
| **Url** | [ResourcePath](#resourcepath-class) |  |
| **WebId** | Guid |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# OrgAssetsLibrary Class

Namespace: Microsoft.SharePoint.Administration

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **DisplayName** | string |  |
| **FileType** | string |  |
| **LibraryUrl** | [ResourcePath](#resourcepath-class) |  |
| **ListId** | Guid |  |
| **OrgAssetType** | [OrgAssetType](#orgassettype-enum) |  |
| **ThumbnailUrl** | [ResourcePath](#resourcepath-class) |  |
| **UniqueId** | Guid |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# OrgAssetsLibraryCollection Class

Namespace: Microsoft.SharePoint.Administration

Base class: ClientValueObjectCollection<[OrgAssetsLibrary](#orgassetslibrary-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **TypeId** | string |  |
| **ChildItemsName** | string |  |
| **Count** | int |  |
| **Item** | [OrgAssetsLibrary](#orgassetslibrary-class) |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# OrgAssetType Enum

Namespace: Microsoft.SharePoint.Administration


## Values

| Name | Summary |
|---|---|
| **Undefined** |  |
| **ImageDocumentLibrary** |  |
| **OfficeTemplateLibrary** |  |
| **OfficeFontLibrary** |  |
# SPEnterpriseContentTypeSyncTrigger Enum

Namespace: Microsoft.SharePoint.Administration


## Values

| Name | Summary |
|---|---|
| **UserTriggeredForRefresh** |  |
| **RefreshECTsOnSiteRestore** |  |
| **RefreshStaleContentType** |  |
| **AddCopyContentTypeAsync** |  |
| **BackfillContentTypesUsage** |  |
# SPResilienceModeType Enum

Namespace: Microsoft.SharePoint.Administration


## Values

| Name | Summary |
|---|---|
| **DefaultAAD** |  |
| **Enabled** |  |
| **Disabled** |  |
# CollaborationInsightsCounts Class

Namespace: Microsoft.SharePoint.Administration.TenantAdmin

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **totalGuests** | int |  |
| **totalInternalUsers** | int |  |
| **totalOneDrives** | int |  |
| **totalSites** | int |  |
| **totalUsers** | int |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# CollaborationInsightsData Class

Namespace: Microsoft.SharePoint.Administration.TenantAdmin

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **collaborativeUsers** | [CollaborativeUsers](#collaborativeusers-class) |  |
| **lastReportDate** | DateTime |  |
| **tenantInsights** | [CollaborationInsightsCounts](#collaborationinsightscounts-class) |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# CollaborativeUsers Class

Namespace: Microsoft.SharePoint.Administration.TenantAdmin

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **oneDrive** | IList\<[OneDriveCollaborativeUsers](#onedrivecollaborativeusers-class)\> |  |
| **oneDriveSharePoint** | IList\<[OneDriveSharePointCollaborativeUsers](#onedrivesharepointcollaborativeusers-class)\> |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# OneDriveCollaborativeUsers Class

Namespace: Microsoft.SharePoint.Administration.TenantAdmin

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **displayName** | string |  |
| **oneDriveFilesSharedExternally** | int |  |
| **userPrincipalName** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# OneDriveSharePointCollaborativeUsers Class

Namespace: Microsoft.SharePoint.Administration.TenantAdmin

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **displayName** | string |  |
| **totalFilesSharedExternally** | int |  |
| **totalFilesSharedInternally** | int |  |
| **userPrincipalName** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# PolicyDefinitionColumn Enum

Namespace: Microsoft.SharePoint.Administration.TenantAdmin


## Values

| Name | Summary |
|---|---|
| **Unknown** |  |
| **CreatedBy** |  |
| **CreatedTime** |  |
| **LastUpdatedTime** |  |
| **PolicyCustomName** |  |
| **PolicyDefinitionDetails** |  |
| **PolicyFrequencyUnit** |  |
| **PolicyFrequencyValue** |  |
| **PolicyId** |  |
| **PolicyState** |  |
| **PolicyTemplate** |  |
| **PolicyType** |  |
| **PolicyVersion** |  |
| **UpdatedBy** |  |
# PolicyFrequencyUnits Enum

Namespace: Microsoft.SharePoint.Administration.TenantAdmin


## Values

| Name | Summary |
|---|---|
| **Unknown** |  |
| **Daily** |  |
| **Weekly** |  |
| **Monthly** |  |
# PolicyState Enum

Namespace: Microsoft.SharePoint.Administration.TenantAdmin


## Values

| Name | Summary |
|---|---|
| **Unknown** |  |
| **Enabled** |  |
| **Disabled** |  |
| **Deleted** |  |
# PolicyStatus Enum

Namespace: Microsoft.SharePoint.Administration.TenantAdmin


## Values

| Name | Summary |
|---|---|
| **Unknown** |  |
| **Scheduled** |  |
| **Running** |  |
| **Success** |  |
| **Failure** |  |
| **Abandoned** |  |
# PolicyTemplate Enum

Namespace: Microsoft.SharePoint.Administration.TenantAdmin


## Values

| Name | Summary |
|---|---|
| **Unknown** |  |
| **InactivePolicy** |  |
# PolicyTypes Enum

Namespace: Microsoft.SharePoint.Administration.TenantAdmin


## Values

| Name | Summary |
|---|---|
| **Unknown** |  |
| **Custom** |  |
| **Internal** |  |
# PolicyWorkItemType Enum

Namespace: Microsoft.SharePoint.Administration.TenantAdmin


## Values

| Name | Summary |
|---|---|
| **Unknown** |  |
| **Parent** |  |
| **Child** |  |
# RecentAdminActionReport Class

Namespace: Microsoft.SharePoint.Administration.TenantAdmin

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **actions** | string |  |
| **createdByEmail** | string |  |
| **createdByName** | string |  |
| **createdDate** | DateTime |  |
| **downloadLink** | string |  |
| **name** | string |  |
| **numberOfRecords** | long |  |
| **progressPercentage** | double |  |
| **queryEndDate** | DateTime |  |
| **queryStartDate** | DateTime |  |
| **requestId** | Guid |  |
| **sites** | string |  |
| **sPOCorrelationId** | Guid |  |
| **status** | [RecentAdminActionReportStatus](#recentadminactionreportstatus-enum) |  |
| **uALCorrelationId** | Guid |  |
| **users** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# RecentAdminActionReportStatus Enum

Namespace: Microsoft.SharePoint.Administration.TenantAdmin


## Values

| Name | Summary |
|---|---|
| **Unknown** |  |
| **Cancelled** |  |
| **Completed** |  |
| **Created** |  |
| **Failed** |  |
| **InProgress** |  |
| **PreparingForDownload** |  |
| **Queued** |  |
# TenantAdminActionSource Enum

Namespace: Microsoft.SharePoint.Administration.TenantAdmin


## Values

| Name | Summary |
|---|---|
| **Unknown** |  |
| **AzureActiveDirectory** |  |
| **ExchangeAdminCenter** |  |
| **Microsoft365AdminCenter** |  |
| **SecurityAndComplianceAdminCenter** |  |
| **SharePointAdminCenter** |  |
| **SharePointOnlineManagementShell** |  |
| **TeamsAdminCenter** |  |
# TenantAdminActionStatus Enum

Namespace: Microsoft.SharePoint.Administration.TenantAdmin


## Values

| Name | Summary |
|---|---|
| **Unknown** |  |
| **Failed** |  |
| **InProgress** |  |
| **PartialSuccess** |  |
| **Success** |  |
| **Timeout** |  |
# TenantAdminActionType Enum

Namespace: Microsoft.SharePoint.Administration.TenantAdmin


## Values

| Name | Summary |
|---|---|
| **Unknown** |  |
| **ClassicSiteCreation** |  |
| **HubSiteAssociation** |  |
| **ModernSiteCreation** |  |
| **RootSiteRestore** |  |
| **SitePurgeDeletion** |  |
| **SiteRestore** |  |
| **SiteSoftDeletion** |  |
| **SwappingSite** |  |
| **UpdateAdmins** |  |
| **UpdateGroupUsers** |  |
| **UpdateHubSettings** |  |
| **UpdateIBMode** |  |
| **UpdateIBSegments** |  |
| **UpdatePrimaryAdmin** |  |
| **UpdateSecondaryAdmins** |  |
| **UpdateSiteAddress** |  |
| **UpdateSiteSensitivity** |  |
| **UpdateSiteSharing** |  |
| **UpdateSiteStorage** |  |
| **UpdateSiteTitle** |  |
| **UpdateSiteUserGroups** |  |
# TenantAdminListItemColumnValue Class

Namespace: Microsoft.SharePoint.Administration.TenantAdmin

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **columnName** | string |  |
| **columnValue** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# TenantAdminPolicyAutomationExecutionHistory Class

Namespace: Microsoft.SharePoint.Administration.TenantAdmin

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **CorrelationId** | Guid |  |
| **EndTime** | DateTime |  |
| **ExecutionDetails** | string |  |
| **ExpectedStartTime** | DateTime |  |
| **FailureReason** | string |  |
| **ImpactedDataFileURL** | string |  |
| **ParentExecutionId** | Guid |  |
| **PolicyFrequency** | [PolicyFrequencyUnits](#policyfrequencyunits-enum) |  |
| **PolicyId** | Guid |  |
| **PolicyName** | string |  |
| **PolicyTemplate** | [PolicyTemplate](#policytemplate-enum) |  |
| **PolicyVersion** | int |  |
| **RetryCount** | int |  |
| **StartTime** | DateTime |  |
| **Status** | [PolicyStatus](#policystatus-enum) |  |
| **WorkItemId** | Guid |  |
| **PolicyWorkItemType** | [PolicyWorkItemType](#policyworkitemtype-enum) |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# TenantAdminPolicyDefinition Class

Namespace: Microsoft.SharePoint.Administration.TenantAdmin

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **createdBy** | string |  |
| **lastUpdatedTime** | DateTime |  |
| **policyCreatedTime** | DateTime |  |
| **policyCustomName** | string |  |
| **policyDefinitionDetails** | string |  |
| **policyFrequencyUnit** | [PolicyFrequencyUnits](#policyfrequencyunits-enum) |  |
| **policyFrequencyValue** | int |  |
| **policyId** | Guid |  |
| **policyState** | [PolicyState](#policystate-enum) |  |
| **policyTemplate** | [PolicyTemplate](#policytemplate-enum) |  |
| **policyType** | [PolicyTypes](#policytypes-enum) |  |
| **policyVersion** | int |  |
| **updatedBy** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# TenantAdminRecentAction Class

Namespace: Microsoft.SharePoint.Administration.TenantAdmin

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **adminActionId** | string |  |
| **adminActionSource** | [TenantAdminActionSource](#tenantadminactionsource-enum) |  |
| **adminActionStatus** | [TenantAdminActionStatus](#tenantadminactionstatus-enum) |  |
| **adminActionType** | [TenantAdminActionType](#tenantadminactiontype-enum) |  |
| **correlationId** | Guid |  |
| **createdTime** | DateTime |  |
| **isPartOfBulkUpdate** | bool |  |
| **key** | string |  |
| **name** | string |  |
| **newValue** | string |  |
| **oldValue** | string |  |
| **url** | string |  |
| **userEmail** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# TenantAdminRecentActionPayload Class

Namespace: Microsoft.SharePoint.Administration.TenantAdmin

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **adminActionId** | string |  |
| **adminActionSource** | string |  |
| **adminActionStatus** | string |  |
| **adminActionType** | string |  |
| **correlationId** | Guid |  |
| **createdTime** | DateTime |  |
| **isPartOfBulkUpdate** | bool |  |
| **key** | string |  |
| **name** | string |  |
| **newValue** | string |  |
| **oldValue** | string |  |
| **url** | string |  |
| **userEmail** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
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
| **QuerySettings** | [PeoplePickerQuerySettings](#peoplepickerquerysettings-class) |  |
| **QueryString** | string |  |
| **Required** | bool |  |
| **SharePointGroupID** | int |  |
| **UrlZone** | [UrlZone](#urlzone-enum) |  |
| **UrlZoneSpecified** | bool |  |
| **UseSubstrateSearch** | bool |  |
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
| **GetPickerEntityInformation(ClientRuntimeContext context, PickerEntityInformationRequest entityInformationRequest)** | [PickerEntityInformation](#pickerentityinformation-class) |  |
# PeoplePickerQuerySettings Class

Namespace: Microsoft.SharePoint.ApplicationPages.ClientPickerQuery

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ExcludeAllUsersOnTenantClaim** | bool |  |
| **IsSharing** | bool |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# PickerEntityInformation Class

Namespace: Microsoft.SharePoint.ApplicationPages.ClientPickerQuery

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Entity** | [PickerEntityInformationRequest](#pickerentityinformationrequest-class) |  |
| **TotalMemberCount** | int |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **PickerEntityInformation(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# PickerEntityInformationPropertyNames Class

Namespace: Microsoft.SharePoint.ApplicationPages.ClientPickerQuery


## Fields

| Name | Type | Summary |
|---|---|---|
| **Entity** | string |  |
| **TotalMemberCount** | string |  |
# PickerEntityInformationRequest Class

Namespace: Microsoft.SharePoint.ApplicationPages.ClientPickerQuery

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **EmailAddress** | string |  |
| **GroupId** | int |  |
| **Key** | string |  |
| **PrincipalType** | [PrincipalType](#principaltype-enum) |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SPACSServicePrincipalInfo Class

Namespace: Microsoft.SharePoint.Authentication

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ApplicationEndpointAuthorities** | IList\<string\> |  |
| **ApplicationPrincipalNames** | IList\<string\> |  |
| **DisplayName** | string |  |
| **NameIdentifier** | string |  |
| **RedirectAddresses** | IList\<string\> |  |
| **TrustedForDelegation** | bool |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# BusinessAppMigrationOperationStatus Enum

Namespace: Microsoft.SharePoint.BusinessApps


## Values

| Name | Summary |
|---|---|
| **Running** |  |
| **Succeeded** |  |
| **UserInteractionRequired** |  |
| **Failed** |  |
| **Invalid** |  |
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
# Alert Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AlertFrequency** | [AlertFrequency](#alertfrequency-enum) |  |
| **AlertTemplateName** | string |  |
| **AlertTime** | DateTime |  |
| **AlertType** | [AlertType](#alerttype-enum) |  |
| **AllProperties** | [PropertyValues](#propertyvalues-class) |  |
| **AlwaysNotify** | bool |  |
| **DeliveryChannels** | [AlertDeliveryChannel](#alertdeliverychannel-enum) |  |
| **EventType** | [AlertEventType](#alerteventtype-enum) |  |
| **Filter** | string |  |
| **ID** | Guid |  |
| **Item** | [ListItem](#listitem-class) |  |
| **ItemID** | int |  |
| **List** | [List](#list-class) |  |
| **ListID** | Guid |  |
| **ListUrl** | string |  |
| **Properties** | IDictionary\<string, string\> |  |
| **Status** | [AlertStatus](#alertstatus-enum) |  |
| **Title** | string |  |
| **User** | [User](#user-class) |  |
| **UserId** | int |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **Alert(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **UpdateAlert()** | void |  |
# AlertCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObjectCollection<[Alert](#alert-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [Alert](#alert-class) |  |
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
| **AlertCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(AlertCreationInformation alertCreationInformation)** | ClientResult\<Guid\> |  |
| **Contains(Guid idAlert)** | ClientResult\<bool\> |  |
| **DeleteAlert(Guid idAlert)** | void |  |
| **DeleteAlertAtIndex(int index)** | void |  |
| **GetById(Guid idAlert)** | [Alert](#alert-class) |  |
# AlertCreationInformation Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AlertFrequency** | [AlertFrequency](#alertfrequency-enum) |  |
| **AlertTemplateName** | string |  |
| **AlertTime** | DateTime |  |
| **AlertType** | [AlertType](#alerttype-enum) |  |
| **AlwaysNotify** | bool |  |
| **DeliveryChannels** | [AlertDeliveryChannel](#alertdeliverychannel-enum) |  |
| **EventType** | [AlertEventType](#alerteventtype-enum) |  |
| **EventTypeBitmask** | int |  |
| **Filter** | string |  |
| **Item** | [ListItem](#listitem-class) |  |
| **List** | [List](#list-class) |  |
| **Properties** | IDictionary\<string, string\> |  |
| **Status** | [AlertStatus](#alertstatus-enum) |  |
| **Title** | string |  |
| **User** | [User](#user-class) |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# AlertDeliveryChannel Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Email** |  |
| **Sms** |  |
| **Content** |  |
# AlertEventType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **AddObject** |  |
| **ModifyObject** |  |
| **DeleteObject** |  |
| **Discussion** |  |
| **All** |  |
# AlertFrequency Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Immediate** |  |
| **Daily** |  |
| **Weekly** |  |
# AlertObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **AllProperties** | string |  |
| **Item** | string |  |
| **List** | string |  |
| **User** | string |  |
# AlertPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **AlertFrequency** | string |  |
| **AlertTemplateName** | string |  |
| **AlertTime** | string |  |
| **AlertType** | string |  |
| **AlwaysNotify** | string |  |
| **DeliveryChannels** | string |  |
| **EventType** | string |  |
| **Filter** | string |  |
| **ID** | string |  |
| **ItemID** | string |  |
| **ListID** | string |  |
| **ListUrl** | string |  |
| **Properties** | string |  |
| **Status** | string |  |
| **Title** | string |  |
| **UserId** | string |  |
# AlertStatus Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **On** |  |
| **Off** |  |
| **Error** |  |
# AlertType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **List** |  |
| **Item** |  |
| **Custom** |  |
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
# AnonymousLinkType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **View** |  |
| **Edit** |  |
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
# AppConfiguration Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **DashboardItems** | IList\<[DashboardItem](#dashboarditem-class)\> |  |
| **PivotItems** | IList\<[PivotItem](#pivotitem-class)\> |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **AppConfiguration(ClientRuntimeContext context)** |  |
| **AppConfiguration(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Update()** | void |  |
# AppConfigurationPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **DashboardItems** | string |  |
| **PivotItems** | string |  |
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
| **isClientSideComponent(Web web)** | ClientResult\<bool\> |  |
| **Recycle()** | ClientResult\<Guid\> |  |
| **Restore()** | ClientResult\<Guid\> |  |
| **RetrieveAppDatabaseConnectionString(ClientRuntimeContext context)** | ClientResult\<string\> |  |
| **RetryAllJobs()** | void |  |
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
# AppProperties Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AppSettingsEnabled** | bool |  |
| **Description** | string |  |
| **EulaUrl** | string |  |
| **IsAnonymous** | bool |  |
| **IsDisabled** | bool |  |
| **ManagedDeploymentEnabled** | bool |  |
| **ManagePermissionsEnabled** | bool |  |
| **ManageSeatsEnabled** | bool |  |
| **MonitoringEnabled** | bool |  |
| **Publisher** | string |  |
| **RemoveEnabled** | bool |  |
| **SideLoadEnabled** | bool |  |
| **SupportUrl** | string |  |
| **ViewInMarketPlaceEnabled** | bool |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# AppPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **AssetId** | string |  |
| **ContentMarket** | string |  |
| **VersionString** | string |  |
# ApprovalRequest Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AllowCancel** | bool |  |
| **AllowRespond** | bool |  |
| **AwaitAll** | bool |  |
| **Details** | string |  |
| **Id** | string |  |
| **Status** | int |  |
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
| **ApprovalRequest(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ApprovalRequestPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **AllowCancel** | string |  |
| **AllowRespond** | string |  |
| **AwaitAll** | string |  |
| **Details** | string |  |
| **Id** | string |  |
| **Status** | string |  |
| **Title** | string |  |
# Approvals Class

Namespace: Microsoft.SharePoint.Client


## Methods

| Name | Returns | Summary |
|---|---|---|
| **ApproveItemRequest(ClientRuntimeContext context, string listId, int itemId, string etag, string approvalId, string comments)** | void |  |
| **CancelItemRequest(ClientRuntimeContext context, string listId, int itemId, string etag, string approvalId)** | void |  |
| **CreateItemRequest(ClientRuntimeContext context, ApprovalsCreateRequestParameters creationInfo)** | ClientResult\<string\> |  |
| **Disable(ClientRuntimeContext context, string listId)** | void |  |
| **Enable(ClientRuntimeContext context, string listId, bool addFieldsToDefaultView)** | void |  |
| **GetItemRequest(ClientRuntimeContext context, string listId, int itemId, string etag)** | [ApprovalRequest](#approvalrequest-class) |  |
| **GetProperties(ClientRuntimeContext context, string listId)** | ClientResult\<[ApprovalsProperties](#approvalsproperties-class)\> |  |
| **RejectItemRequest(ClientRuntimeContext context, string listId, int itemId, string etag, string approvalId, string comments)** | void |  |
| **SetProperties(ClientRuntimeContext context, string listId, ApprovalsProperties properties)** | void |  |
# ApprovalsCreateRequestParameters Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **approvers** | string |  |
| **awaitAll** | bool |  |
| **details** | string |  |
| **etag** | string |  |
| **itemId** | int |  |
| **listId** | string |  |
| **title** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# ApprovalsManager Class

Namespace: Microsoft.SharePoint.Client


## Methods

| Name | Returns | Summary |
|---|---|---|
| **OnRequestUpdated(ClientRuntimeContext context)** | void |  |
# ApprovalsProperties Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ApproversAwaitAll** | bool |  |
| **ApproversAwaitAllFixed** | bool |  |
| **ApproversFixed** | bool |  |
| **ApproverSourceType** | [ApproverSource](#approversource-enum) |  |
| **ApproverSourceValue** | string |  |
| **ProvisioningError** | string |  |
| **ProvisioningStatus** | int |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# ApproverSource Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **UserList** |  |
| **Field** |  |
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
# AppStatus Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **InvalidStatus** |  |
| **Installing** |  |
| **Canceling** |  |
| **Uninstalling** |  |
| **Installed** |  |
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
# AppTile Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AppId** | Guid |  |
| **AppPrincipalId** | string |  |
| **AppSource** | [AppSource](#appsource-enum) |  |
| **AppStatus** | [AppStatus](#appstatus-enum) |  |
| **AppType** | [AppType](#apptype-enum) |  |
| **AssetId** | string |  |
| **BaseTemplate** | [ListTemplateType](#listtemplatetype-enum) |  |
| **ChildCount** | int |  |
| **ContentMarket** | string |  |
| **CustomSettingsUrl** | string |  |
| **Description** | string |  |
| **IsCorporateCatalogSite** | bool |  |
| **LastModified** | string |  |
| **LastModifiedDate** | DateTime |  |
| **ProductId** | Guid |  |
| **Target** | string |  |
| **Thumbnail** | string |  |
| **Title** | string |  |
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
# AppTileProperties Class

Namespace: Microsoft.SharePoint.Client


## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetAppProperties(ClientRuntimeContext context, Guid appId, AppType appType, Guid productId, AppSource appSource, string assetId, string contentMarket, bool isTenantApp)** | ClientResult\<[AppProperties](#appproperties-class)\> |  |
# AppTilePropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **AppId** | string |  |
| **AppPrincipalId** | string |  |
| **AppSource** | string |  |
| **AppStatus** | string |  |
| **AppType** | string |  |
| **AssetId** | string |  |
| **BaseTemplate** | string |  |
| **ChildCount** | string |  |
| **ContentMarket** | string |  |
| **CustomSettingsUrl** | string |  |
| **Description** | string |  |
| **IsCorporateCatalogSite** | string |  |
| **LastModified** | string |  |
| **LastModifiedDate** | string |  |
| **ProductId** | string |  |
| **Target** | string |  |
| **Thumbnail** | string |  |
| **Title** | string |  |
| **Version** | string |  |
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
# AppViewCreationInfo Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AppId** | Guid |  |
| **IsPrivate** | bool |  |
| **Title** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# ArchiveState Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **Hydrating** |  |
| **Archiving** |  |
| **Archived** |  |
# AsyncReadJobInfo Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **CurrentChangeToken** | string |  |
| **JobId** | Guid |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# AsyncReadOptions Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **IncludeDirectDescendantsOnly** | bool |  |
| **IncludeExtendedMetadata** | bool |  |
| **IncludePermission** | bool |  |
| **IncludeSecurity** | bool |  |
| **IncludeVersions** | bool |  |
| **StartChangeToken** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# Attachment Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **FileName** | string |  |
| **FileNameAsPath** | [ResourcePath](#resourcepath-class) |  |
| **ServerRelativePath** | [ResourcePath](#resourcepath-class) |  |
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
| **RecycleObject()** | void |  |
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
| **AddUsingPath(ResourcePath filename, Stream contentStream)** | [Attachment](#attachment-class) |  |
| **GetByFileName(string fileName)** | [Attachment](#attachment-class) |  |
| **GetByFileNameAsPath(ResourcePath fileName)** | [Attachment](#attachment-class) |  |
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
| **FileNameAsPath** | string |  |
| **ServerRelativePath** | string |  |
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
# AutoLabellingWorkInformation Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **RoutingHint** | string |  |
| **ScaleUnitId** | Guid |  |
| **Watermark** | string |  |
| **WorkItemType** | [SensitivityLabelWorkItemType](#sensitivitylabelworkitemtype-enum) |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
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
| **AllowIncrementalResults** | bool |  |
| **DatesInUtc** | bool |  |
| **FolderServerRelativePath** | [ResourcePath](#resourcepath-class) |  |
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
# CampaignCommunicationEntity Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **campaignId** | string |  |
| **channels** | IList\<string\> |  |
| **communicationId** | string |  |
| **createdBy** | [CampaignUserInfo](#campaignuserinfo-class) |  |
| **lastEditedDateTime** | DateTime |  |
| **page** | string |  |
| **publishingDateTime** | DateTime |  |
| **state** | string |  |
| **title** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# CampaignEntity Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **campaignId** | string |  |
| **channels** | IList\<string\> |  |
| **contributors** | IList\<[CampaignUserInfo](#campaignuserinfo-class)\> |  |
| **description** | string |  |
| **endDate** | DateTime |  |
| **objectives** | IList\<string\> |  |
| **owner** | [CampaignUserInfo](#campaignuserinfo-class) |  |
| **startDate** | DateTime |  |
| **status** | string |  |
| **tags** | IList\<string\> |  |
| **title** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# Campaigns Class

Namespace: Microsoft.SharePoint.Client


## Methods

| Name | Returns | Summary |
|---|---|---|
| **CreateCampaign(ClientRuntimeContext context, CampaignEntity campaign)** | ClientResult\<[CampaignEntity](#campaignentity-class)\> |  |
| **CreateCommunication(ClientRuntimeContext context, CampaignCommunicationEntity communication)** | ClientResult\<[CampaignCommunicationEntity](#campaigncommunicationentity-class)\> |  |
| **GetCampaign(ClientRuntimeContext context, string campaignId)** | ClientResult\<[CampaignEntity](#campaignentity-class)\> |  |
| **GetCampaignsSummary(ClientRuntimeContext context)** | IEnumerable\<[CampaignSummary](#campaignsummary-class)\> |  |
| **GetCommunication(ClientRuntimeContext context, string communicationId)** | ClientResult\<[CampaignCommunicationEntity](#campaigncommunicationentity-class)\> |  |
| **GetCommunications(ClientRuntimeContext context, string campaignId)** | IEnumerable\<[CampaignCommunicationEntity](#campaigncommunicationentity-class)\> |  |
| **UpdateCampaign(ClientRuntimeContext context, CampaignEntity campaign)** | ClientResult\<[CampaignEntity](#campaignentity-class)\> |  |
| **UpdateCommunication(ClientRuntimeContext context, CampaignCommunicationEntity communication)** | ClientResult\<[CampaignCommunicationEntity](#campaigncommunicationentity-class)\> |  |
# CampaignSummary Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **campaignId** | string |  |
| **endDate** | DateTime |  |
| **owner** | [CampaignUserInfo](#campaignuserinfo-class) |  |
| **startDate** | DateTime |  |
| **status** | string |  |
| **tags** | IList\<string\> |  |
| **title** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# CampaignUserInfo Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **email** | string |  |
| **id** | int |  |
| **isExternal** | bool |  |
| **loginName** | string |  |
| **name** | string |  |
| **principalType** | [PrincipalType](#principaltype-enum) |  |
| **userId** | [UserIdInfo](#useridinfo-class) |  |
| **userPrincipalName** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# CampainAnalytics Class

Namespace: Microsoft.SharePoint.Client


## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetDimensions(ClientRuntimeContext context, VinciAnalyticsDimensionsRequest request)** | ClientResult\<[DimensionsResponse](#dimensionsresponse-class)\> |  |
| **GetReport(ClientRuntimeContext context, VinciAnalyticsReportRequest request)** | ClientResult\<[ReportResponse](#reportresponse-class)\> |  |
# Change Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ChangeToken** | [ChangeToken](#changetoken-class) |  |
| **ChangeType** | [ChangeType](#changetype-enum) |  |
| **RelativeTime** | string |  |
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
| **RelativeTime** | string |  |
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
| **HasMoreChanges** | bool |  |
| **LastChangeToken** | [ChangeToken](#changetoken-class) |  |
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
# ChangeCollectionPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **HasMoreChanges** | string |  |
| **LastChangeToken** | string |  |
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
| **RelativeTime** | string |  |
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
| **RelativeTime** | string |  |
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
| **RelativeTime** | string |  |
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
| **IsRecycleBinOperation** | bool |  |
| **UniqueId** | Guid |  |
| **WebId** | Guid |  |
| **ChangeToken** | [ChangeToken](#changetoken-class) |  |
| **ChangeType** | [ChangeType](#changetype-enum) |  |
| **RelativeTime** | string |  |
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
| **IsRecycleBinOperation** | string |  |
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
| **RelativeTime** | string |  |
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
| **ActivityType** | [SPChangeActivityType](#spchangeactivitytype-enum) |  |
| **ContentTypeId** | [ContentTypeId](#contenttypeid-class) |  |
| **Editor** | string |  |
| **EditorEmailHint** | string |  |
| **EditorLoginName** | string |  |
| **FileSystemObjectType** | [FileSystemObjectType](#filesystemobjecttype-enum) |  |
| **FileType** | string |  |
| **Hashtag** | string |  |
| **Hidden** | bool |  |
| **ItemId** | int |  |
| **IsRecycleBinOperation** | bool |  |
| **ListId** | Guid |  |
| **ListTemplate** | [ListTemplateType](#listtemplatetype-enum) |  |
| **ListTitle** | string |  |
| **MoveWasForRecycle** | bool |  |
| **MoveWasForRestore** | bool |  |
| **ServerRelativeUrl** | string |  |
| **SharedByUser** | [SharedWithUser](#sharedwithuser-class) |  |
| **SharedWithUsers** | [SharedWithUserCollection](#sharedwithusercollection-class) |  |
| **Title** | string |  |
| **UniqueId** | Guid |  |
| **WebId** | Guid |  |
| **ChangeToken** | [ChangeToken](#changetoken-class) |  |
| **ChangeType** | [ChangeType](#changetype-enum) |  |
| **RelativeTime** | string |  |
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
| **ActivityType** | string |  |
| **ContentTypeId** | string |  |
| **Editor** | string |  |
| **EditorEmailHint** | string |  |
| **EditorLoginName** | string |  |
| **FileSystemObjectType** | string |  |
| **FileType** | string |  |
| **Hashtag** | string |  |
| **Hidden** | string |  |
| **ItemId** | string |  |
| **IsRecycleBinOperation** | string |  |
| **ListId** | string |  |
| **ListTemplate** | string |  |
| **ListTitle** | string |  |
| **MoveWasForRecycle** | string |  |
| **MoveWasForRestore** | string |  |
| **ServerRelativeUrl** | string |  |
| **SharedByUser** | string |  |
| **SharedWithUsers** | string |  |
| **Title** | string |  |
| **UniqueId** | string |  |
| **WebId** | string |  |
# ChangeList Class

Namespace: Microsoft.SharePoint.Client

Base class: [Change](#change-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **BaseTemplate** | [ListTemplateType](#listtemplatetype-enum) |  |
| **Creator** | [User](#user-class) |  |
| **Editor** | string |  |
| **Hidden** | bool |  |
| **ListId** | Guid |  |
| **IsRecycleBinOperation** | bool |  |
| **RootFolderUrl** | string |  |
| **Title** | string |  |
| **WebId** | Guid |  |
| **ChangeToken** | [ChangeToken](#changetoken-class) |  |
| **ChangeType** | [ChangeType](#changetype-enum) |  |
| **RelativeTime** | string |  |
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
# ChangeListObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Creator** | string |  |
# ChangeListPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **BaseTemplate** | string |  |
| **Editor** | string |  |
| **Hidden** | string |  |
| **ListId** | string |  |
| **IsRecycleBinOperation** | string |  |
| **RootFolderUrl** | string |  |
| **Title** | string |  |
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
| **RelativeTime** | string |  |
| **SiteId** | string |  |
| **Time** | string |  |
# ChangeQuery Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Activity** | bool |  |
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
| **IgnoreStartTokenNotFoundError** | bool |  |
| **Item** | bool |  |
| **LatestFirst** | bool |  |
| **List** | bool |  |
| **Move** | bool |  |
| **Navigation** | bool |  |
| **RecursiveAll** | bool |  |
| **Rename** | bool |  |
| **RequireSecurityTrim** | bool |  |
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
| **RelativeTime** | string |  |
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
| **Activity** |  |
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
| **RelativeTime** | string |  |
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
| **RelativeTime** | string |  |
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
| **RelativeTime** | string |  |
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
# CheckedOutFile Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **CheckedOutBy** | [User](#user-class) |  |
| **CheckedOutById** | int |  |
| **ServerRelativePath** | [ResourcePath](#resourcepath-class) |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **CheckedOutFile(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **TakeOverCheckOut()** | void |  |
# CheckedOutFileCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObjectCollection<[CheckedOutFile](#checkedoutfile-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [CheckedOutFile](#checkedoutfile-class) |  |
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
| **CheckedOutFileCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetByPath(ResourcePath path)** | [CheckedOutFile](#checkedoutfile-class) |  |
# CheckedOutFileObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **CheckedOutBy** | string |  |
# CheckedOutFilePropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **CheckedOutById** | string |  |
| **ServerRelativePath** | string |  |
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
# ClassificationResult Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ConfidenceScore** | double |  |
| **ContentTypeId** | string |  |
| **Metas** | IDictionary\<string, string\> |  |
| **ModelId** | string |  |
| **ModelVersion** | string |  |
| **RetentionLabelFlags** | int |  |
| **RetentionLabelName** | string |  |
| **RetryCount** | int |  |
| **SensitivityLabel** | string |  |
| **TableMetas** | IDictionary\<string, string\> |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
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
| **ServerVersion** | Version |  |
| **NamespaceManager** | XmlNamespaceManager |  |
| **NextSequenceId** | long |  |
| **ServiceRelativeUrl** | string |  |
| **Url** | string |  |
| **ApplicationName** | string |  |
| **ClientTag** | string |  |
| **DisableReturnValueCache** | bool |  |
| **ValidateOnClient** | bool |  |
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
| **ExecuteQueryAsync()** | Task |  |
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
# ConfigurationData Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **BridgeAbsolutePath** | [ResourcePath](#resourcepath-class) |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# ContentAssemblyFileInfo Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **FileUrl** | string |  |
| **ServerRedirectedEmbedUrl** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# ContentAssemblyFormAnswer Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Answer** | string |  |
| **ContentControlTagName** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# ContentControlInfo Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ContentControlTagName** | string |  |
| **EndIndex** | int |  |
| **IsSingleParargaph** | bool |  |
| **ParagraphIds** | IList\<string\> |  |
| **StartIndex** | int |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# ContentType Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ClientFormCustomFormatter** | string |  |
| **Description** | string |  |
| **DescriptionResource** | [UserResource](#userresource-class) |  |
| **DisplayFormClientSideComponentId** | string |  |
| **DisplayFormClientSideComponentProperties** | string |  |
| **DisplayFormTarget** | [UrlTarget](#urltarget-enum) |  |
| **DisplayFormTemplateName** | string |  |
| **DisplayFormUrl** | string |  |
| **DocumentTemplate** | string |  |
| **DocumentTemplateUrl** | string |  |
| **EditFormClientSideComponentId** | string |  |
| **EditFormClientSideComponentProperties** | string |  |
| **EditFormTarget** | [UrlTarget](#urltarget-enum) |  |
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
| **NewFormClientSideComponentId** | string |  |
| **NewFormClientSideComponentProperties** | string |  |
| **NewFormTarget** | [UrlTarget](#urltarget-enum) |  |
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
| **ClientFormCustomFormatter** | string |  |
| **Description** | string |  |
| **DisplayFormClientSideComponentId** | string |  |
| **DisplayFormClientSideComponentProperties** | string |  |
| **DisplayFormTarget** | string |  |
| **DisplayFormTemplateName** | string |  |
| **DisplayFormUrl** | string |  |
| **DocumentTemplate** | string |  |
| **DocumentTemplateUrl** | string |  |
| **EditFormClientSideComponentId** | string |  |
| **EditFormClientSideComponentProperties** | string |  |
| **EditFormTarget** | string |  |
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
| **NewFormClientSideComponentId** | string |  |
| **NewFormClientSideComponentProperties** | string |  |
| **NewFormTarget** | string |  |
| **NewFormTemplateName** | string |  |
| **NewFormUrl** | string |  |
| **ReadOnly** | string |  |
| **SchemaXml** | string |  |
| **SchemaXmlWithResourceTokens** | string |  |
| **Scope** | string |  |
| **Sealed** | string |  |
| **StringId** | string |  |
# CopyJobProgress Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **JobState** | [MigrationJobState](#migrationjobstate-enum) |  |
| **Logs** | IList\<string\> |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# CopyMigrationInfo Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **EncryptionKey** | byte[] |  |
| **JobId** | Guid |  |
| **JobQueueUri** | string |  |
| **SourceListItemUniqueIds** | IList\<Guid\> |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# CopyMigrationOptions Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AllowSchemaMismatch** | bool |  |
| **AllowSmallerVersionLimitOnDestination** | bool |  |
| **BypassSharedLock** | bool |  |
| **ClientEtags** | string[] |  |
| **CustomizedItemName** | string[] |  |
| **ExcludeChildren** | bool |  |
| **IgnoreVersionHistory** | bool |  |
| **IncludeItemPermissions** | bool |  |
| **IsMoveMode** | bool |  |
| **MoveAndShareFileInfo** | [SPMoveAndShareFileInfo](#spmoveandsharefileinfo-class) |  |
| **MoveButKeepSource** | bool |  |
| **NameConflictBehavior** | [MigrationNameConflictBehavior](#migrationnameconflictbehavior-enum) |  |
| **SameWebCopyMoveOptimization** | bool |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# CopySourceInfo Class

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
| **CopySourceInfo(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# CountByDate Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **count** | int |  |
| **date** | int |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
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
# CurrencyInformation Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **DisplayString** | string |  |
| **LanguageCultureName** | string |  |
| **LCID** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# CurrencyInformationCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObjectCollection<[CurrencyInformation](#currencyinformation-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **TypeId** | string |  |
| **ChildItemsName** | string |  |
| **Count** | int |  |
| **Item** | [CurrencyInformation](#currencyinformation-class) |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# CurrencyList Class

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
| **CurrencyList(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetList(ClientRuntimeContext context)** | ClientResult\<[CurrencyInformationCollection](#currencyinformationcollection-class)\> |  |
# CustomActionElement Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ClientSideComponentId** | Guid |  |
| **ClientSideComponentProperties** | string |  |
| **CommandUIExtension** | string |  |
| **Id** | string |  |
| **EnabledScript** | string |  |
| **HostProperties** | string |  |
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
# CustomerKeyInfo Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AvailabilityKeyVault** | [CustomerKeyVaultInfo](#customerkeyvaultinfo-class) |  |
| **PrimaryKeyVault** | [CustomerKeyVaultInfo](#customerkeyvaultinfo-class) |  |
| **SecondaryKeyVault** | [CustomerKeyVaultInfo](#customerkeyvaultinfo-class) |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# CustomerKeyStatus Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Unregistered** |  |
| **Registering** |  |
| **Registered** |  |
| **Rolling** |  |
| **Recovering** |  |
# CustomerKeyStatusInfo Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AvailabilityKeyVaultUri** | string |  |
| **PrimaryKeyVaultUri** | string |  |
| **RecoveryEnabled** | bool |  |
| **RegistrationProgress** | double |  |
| **SecondaryKeyVaultUri** | string |  |
| **Status** | [CustomerKeyStatus](#customerkeystatus-enum) |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# CustomerKeyVaultInfo Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **KeyName** | string |  |
| **KeyVersion** | Guid |  |
| **ResourceGroupName** | string |  |
| **SubscriptionId** | Guid |  |
| **Uri** | string |  |
| **VaultName** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# CustomerKeyVaultKeyType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Primary** |  |
| **Secondary** |  |
| **Availability** |  |
# CustomerRecoveryKeyMode Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Standard** |  |
| **NoRecoveryKey** |  |
| **CustomerControlled** |  |
# CustomizedFormsPage Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **formType** | [PageType](#pagetype-enum) |  |
| **pageId** | Guid |  |
| **Url** | string |  |
| **webpartId** | Guid |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# CustomizedFormsPageCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObjectCollection<[CustomizedFormsPage](#customizedformspage-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **TypeId** | string |  |
| **ChildItemsName** | string |  |
| **Count** | int |  |
| **Item** | [CustomizedFormsPage](#customizedformspage-class) |  |
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
# DashboardItem Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **WebAbsolutePath** | [ResourcePath](#resourcepath-class) |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# DashboardItemInfo Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ItemId** | int |  |
| **ListId** | Guid |  |
| **SiteId** | Guid |  |
| **WebId** | Guid |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
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
# DimensionsResponse Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **application** | IList\<string\> |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
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
# DocumentGenerationInfo Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ContentAssemblyFormAnswers** | IList\<[ContentAssemblyFormAnswer](#contentassemblyformanswer-class)\> |  |
| **FileName** | string |  |
| **FolderUrl** | string |  |
| **Format** | [OutputFileFormat](#outputfileformat-enum) |  |
| **IsTempFile** | bool |  |
| **TempFileUrl** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# DocumentLibraryInformation Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AbsoluteUrl** | string |  |
| **DriveId** | string |  |
| **FromCrossFarm** | bool |  |
| **Id** | Guid |  |
| **IsDefaultDocumentLibrary** | bool |  |
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
| **Visio** |  |
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
# EmployeeEngagement Class

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
| **EmployeeEngagement(ClientRuntimeContext context)** |  |
| **EmployeeEngagement(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DashboardItem(ClientRuntimeContext context, string siteUrl)** | ClientResult\<[DashboardItemInfo](#dashboarditeminfo-class)\> |  |
| **GetEEConfigurationXGeo(ClientRuntimeContext context, Guid siteId)** | ClientResult\<[ConfigurationData](#configurationdata-class)\> |  |
| **GetTenantDashboardContentXGeo(ClientRuntimeContext context, string overrideLanguageCode)** | ClientResult\<string\> |  |
| **GetVivaConnectionsUrlConfigurationXGeo(ClientRuntimeContext context, string adminConfiguredUrl)** | ClientResult\<[VivaConnectionsUrlConfiguration](#vivaconnectionsurlconfiguration-class)\> |  |
| **VivaHomeConfigurationXGeo(ClientRuntimeContext context)** | ClientResult\<IDictionary\<string, string\>\> |  |
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
# EnqueueJobInformation Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **EnqueueJobStatus** | [EnqueueJobStatus](#enqueuejobstatus-enum) |  |
| **Message** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# EnqueueJobStatus Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Failed** |  |
| **Success** |  |
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
| **SiteMovingFromGeoLocation** |  |
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
| **ItemQuotaExceeded** |  |
| **FieldAdded** |  |
| **FieldUpdated** |  |
| **FieldDeleted** |  |
| **ListAdded** |  |
| **ListDeleted** |  |
| **ListRestored** |  |
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
# FavoriteListHomeItem Class

Namespace: Microsoft.SharePoint.Client

Base class: [ListHomeItem](#listhomeitem-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **favoritesOrder** | float |  |
| **lastPolled** | float |  |
| **order** | long |  |
| **TypeId** | string |  |
| **color** | string |  |
| **icon** | string |  |
| **isDefaultDocumentLibrary** | bool |  |
| **isDocLib** | bool |  |
| **listId** | string |  |
| **listUrl** | string |  |
| **siteAcronym** | string |  |
| **siteColor** | string |  |
| **siteIconUrl** | string |  |
| **siteId** | string |  |
| **siteTitle** | string |  |
| **siteUrl** | string |  |
| **title** | string |  |
| **webId** | string |  |
| **webTemplateConfiguration** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# FavoriteLists Class

Namespace: Microsoft.SharePoint.Client


## Methods

| Name | Returns | Summary |
|---|---|---|
| **AddList(ClientRuntimeContext context, FavoriteListHomeItem favoriteList)** | void |  |
| **GetListsBy(ClientRuntimeContext context, string siteId, string listId, int page)** | ClientResult\<[FavoriteListHomeItem](#favoritelisthomeitem-class)[]\> |  |
| **RemoveList(ClientRuntimeContext context, string siteId, string listId, string webId)** | void |  |
| **ReorderList(ClientRuntimeContext context, FavoriteListHomeItem listToReorder, FavoriteListHomeItem listBefore, FavoriteListHomeItem listAfter)** | void |  |
| **UpdateList(ClientRuntimeContext context, FavoriteListHomeItem favoriteList)** | void |  |
# FavoriteListsSubstrate Class

Namespace: Microsoft.SharePoint.Client


## Methods

| Name | Returns | Summary |
|---|---|---|
| **AddList(ClientRuntimeContext context, FavoriteListHomeItem list)** | void |  |
| **GetListsBy(ClientRuntimeContext context, string siteId, string listId, int page)** | ClientResult\<string\> |  |
| **RemoveList(ClientRuntimeContext context, string siteId, string listId, string webId)** | void |  |
| **UpdateList(ClientRuntimeContext context, FavoriteListHomeItem list)** | void |  |
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
| **ClientSideComponentId** | Guid |  |
| **ClientSideComponentProperties** | string |  |
| **ClientValidationFormula** | string |  |
| **ClientValidationMessage** | string |  |
| **CustomFormatter** | string |  |
| **DefaultFormula** | string |  |
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
| **IndexStatus** | [FieldIndexStatus](#fieldindexstatus-enum) |  |
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
| **ShowInFiltersPane** | [ShowInFiltersPaneStatus](#showinfilterspanestatus-enum) |  |
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
| **DisableIndex()** | ClientResult\<[FieldIndexStatus](#fieldindexstatus-enum)\> |  |
| **EnableIndex()** | ClientResult\<[FieldIndexStatus](#fieldindexstatus-enum)\> |  |
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
| **CurrencyLocaleId** | int |  |
| **DateFormat** | [DateTimeFieldFormatType](#datetimefieldformattype-enum) |  |
| **DisplayFormat** | int |  |
| **Formula** | string |  |
| **OutputType** | [FieldType](#fieldtype-enum) |  |
| **ShowAsPercentage** | bool |  |
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
| **IndexStatus** | [FieldIndexStatus](#fieldindexstatus-enum) |  |
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
| **ShowInFiltersPane** | [ShowInFiltersPaneStatus](#showinfilterspanestatus-enum) |  |
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
| **CurrencyLocaleId** | string |  |
| **DateFormat** | string |  |
| **DisplayFormat** | string |  |
| **Formula** | string |  |
| **OutputType** | string |  |
| **ShowAsPercentage** | string |  |
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
| **ClientSideComponentId** | Guid |  |
| **ClientSideComponentProperties** | string |  |
| **ClientValidationFormula** | string |  |
| **ClientValidationMessage** | string |  |
| **CustomFormatter** | string |  |
| **DefaultFormula** | string |  |
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
| **IndexStatus** | [FieldIndexStatus](#fieldindexstatus-enum) |  |
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
| **ShowInFiltersPane** | [ShowInFiltersPaneStatus](#showinfilterspanestatus-enum) |  |
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
| **ClientSideComponentId** | Guid |  |
| **ClientSideComponentProperties** | string |  |
| **ClientValidationFormula** | string |  |
| **ClientValidationMessage** | string |  |
| **CustomFormatter** | string |  |
| **DefaultFormula** | string |  |
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
| **IndexStatus** | [FieldIndexStatus](#fieldindexstatus-enum) |  |
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
| **ShowInFiltersPane** | [ShowInFiltersPaneStatus](#showinfilterspanestatus-enum) |  |
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
| **CommaSeparator** | bool |  |
| **CustomUnitName** | string |  |
| **CustomUnitOnRight** | bool |  |
| **DisplayFormat** | int |  |
| **MaximumValue** | double |  |
| **MinimumValue** | double |  |
| **ShowAsPercentage** | bool |  |
| **Unit** | string |  |
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
| **IndexStatus** | [FieldIndexStatus](#fieldindexstatus-enum) |  |
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
| **ShowInFiltersPane** | [ShowInFiltersPaneStatus](#showinfilterspanestatus-enum) |  |
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
| **DateFormat** | string |  |
| **DisplayFormat** | [DateTimeFieldFormatType](#datetimefieldformattype-enum) |  |
| **FriendlyDisplayFormat** | [DateTimeFieldFriendlyFormatType](#datetimefieldfriendlyformattype-enum) |  |
| **TimeFormat** | string |  |
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
| **IndexStatus** | [FieldIndexStatus](#fieldindexstatus-enum) |  |
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
| **ShowInFiltersPane** | [ShowInFiltersPaneStatus](#showinfilterspanestatus-enum) |  |
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
| **DateFormat** | string |  |
| **DisplayFormat** | string |  |
| **FriendlyDisplayFormat** | string |  |
| **TimeFormat** | string |  |
# FieldGeolocation Class

Namespace: Microsoft.SharePoint.Client

Base class: [Field](#field-class)


## Properties

| Name | Type | Summary |
|---|---|---|
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
| **IndexStatus** | [FieldIndexStatus](#fieldindexstatus-enum) |  |
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
| **ShowInFiltersPane** | [ShowInFiltersPaneStatus](#showinfilterspanestatus-enum) |  |
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
| **ClientSideComponentId** | Guid |  |
| **ClientSideComponentProperties** | string |  |
| **ClientValidationFormula** | string |  |
| **ClientValidationMessage** | string |  |
| **CustomFormatter** | string |  |
| **DefaultFormula** | string |  |
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
| **IndexStatus** | [FieldIndexStatus](#fieldindexstatus-enum) |  |
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
| **ShowInFiltersPane** | [ShowInFiltersPaneStatus](#showinfilterspanestatus-enum) |  |
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
# FieldIndexStatus Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **Indexed** |  |
| **Enabling** |  |
| **Disabling** |  |
# FieldLink Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **DisplayName** | string |  |
| **Hidden** | bool |  |
| **Id** | Guid |  |
| **Name** | string |  |
| **ReadOnly** | bool |  |
| **Required** | bool |  |
| **ShowInDisplayForm** | bool |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
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
| **DisplayName** | string |  |
| **Hidden** | string |  |
| **Id** | string |  |
| **Name** | string |  |
| **ReadOnly** | string |  |
| **Required** | string |  |
| **ShowInDisplayForm** | string |  |
# FieldLocation Class

Namespace: Microsoft.SharePoint.Client

Base class: [FieldMultiLineText](#fieldmultilinetext-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **AllowHyperlink** | bool |  |
| **AppendOnly** | bool |  |
| **IsLongHyperlink** | bool |  |
| **NumberOfLines** | int |  |
| **RestrictedMode** | bool |  |
| **RichText** | bool |  |
| **UnlimitedLengthInDocumentLibrary** | bool |  |
| **WikiLinking** | bool |  |
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
| **IndexStatus** | [FieldIndexStatus](#fieldindexstatus-enum) |  |
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
| **ShowInFiltersPane** | [ShowInFiltersPaneStatus](#showinfilterspanestatus-enum) |  |
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
| **FieldLocation(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# FieldLookup Class

Namespace: Microsoft.SharePoint.Client

Base class: [Field](#field-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **AllowMultipleValues** | bool |  |
| **DependentLookupInternalNames** | IList\<string\> |  |
| **IsDependentLookup** | bool |  |
| **IsRelationship** | bool |  |
| **LookupField** | string |  |
| **LookupList** | string |  |
| **LookupWebId** | Guid |  |
| **PrimaryFieldId** | string |  |
| **RelationshipDeleteBehavior** | [RelationshipDeleteBehaviorType](#relationshipdeletebehaviortype-enum) |  |
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
| **IndexStatus** | [FieldIndexStatus](#fieldindexstatus-enum) |  |
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
| **ShowInFiltersPane** | [ShowInFiltersPaneStatus](#showinfilterspanestatus-enum) |  |
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
| **DependentLookupInternalNames** | string |  |
| **IsDependentLookup** | string |  |
| **IsRelationship** | string |  |
| **LookupField** | string |  |
| **LookupList** | string |  |
| **LookupWebId** | string |  |
| **PrimaryFieldId** | string |  |
| **RelationshipDeleteBehavior** | string |  |
| **UnlimitedLengthInDocumentLibrary** | string |  |
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
| **ClientSideComponentId** | Guid |  |
| **ClientSideComponentProperties** | string |  |
| **ClientValidationFormula** | string |  |
| **ClientValidationMessage** | string |  |
| **CustomFormatter** | string |  |
| **DefaultFormula** | string |  |
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
| **IndexStatus** | [FieldIndexStatus](#fieldindexstatus-enum) |  |
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
| **ShowInFiltersPane** | [ShowInFiltersPaneStatus](#showinfilterspanestatus-enum) |  |
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
| **IsLongHyperlink** | bool |  |
| **NumberOfLines** | int |  |
| **RestrictedMode** | bool |  |
| **RichText** | bool |  |
| **UnlimitedLengthInDocumentLibrary** | bool |  |
| **WikiLinking** | bool |  |
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
| **IndexStatus** | [FieldIndexStatus](#fieldindexstatus-enum) |  |
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
| **ShowInFiltersPane** | [ShowInFiltersPaneStatus](#showinfilterspanestatus-enum) |  |
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
| **IsLongHyperlink** | string |  |
| **NumberOfLines** | string |  |
| **RestrictedMode** | string |  |
| **RichText** | string |  |
| **UnlimitedLengthInDocumentLibrary** | string |  |
| **WikiLinking** | string |  |
# FieldNumber Class

Namespace: Microsoft.SharePoint.Client

Base class: [Field](#field-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **CommaSeparator** | bool |  |
| **CustomUnitName** | string |  |
| **CustomUnitOnRight** | bool |  |
| **DisplayFormat** | int |  |
| **MaximumValue** | double |  |
| **MinimumValue** | double |  |
| **ShowAsPercentage** | bool |  |
| **Unit** | string |  |
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
| **IndexStatus** | [FieldIndexStatus](#fieldindexstatus-enum) |  |
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
| **ShowInFiltersPane** | [ShowInFiltersPaneStatus](#showinfilterspanestatus-enum) |  |
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
| **CommaSeparator** | string |  |
| **CustomUnitName** | string |  |
| **CustomUnitOnRight** | string |  |
| **DisplayFormat** | string |  |
| **MaximumValue** | string |  |
| **MinimumValue** | string |  |
| **ShowAsPercentage** | string |  |
| **Unit** | string |  |
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
| **ClientSideComponentId** | string |  |
| **ClientSideComponentProperties** | string |  |
| **ClientValidationFormula** | string |  |
| **ClientValidationMessage** | string |  |
| **CustomFormatter** | string |  |
| **DefaultFormula** | string |  |
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
| **IndexStatus** | string |  |
| **InternalName** | string |  |
| **IsModern** | string |  |
| **JSLink** | string |  |
| **NoCrawl** | string |  |
| **PinnedToFiltersPane** | string |  |
| **ReadOnlyField** | string |  |
| **Required** | string |  |
| **SchemaXml** | string |  |
| **SchemaXmlWithResourceTokens** | string |  |
| **Scope** | string |  |
| **Sealed** | string |  |
| **ShowInFiltersPane** | string |  |
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
| **ClientSideComponentId** | Guid |  |
| **ClientSideComponentProperties** | string |  |
| **ClientValidationFormula** | string |  |
| **ClientValidationMessage** | string |  |
| **CustomFormatter** | string |  |
| **DefaultFormula** | string |  |
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
| **IndexStatus** | [FieldIndexStatus](#fieldindexstatus-enum) |  |
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
| **ShowInFiltersPane** | [ShowInFiltersPaneStatus](#showinfilterspanestatus-enum) |  |
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
| **ClientSideComponentId** | Guid |  |
| **ClientSideComponentProperties** | string |  |
| **ClientValidationFormula** | string |  |
| **ClientValidationMessage** | string |  |
| **CustomFormatter** | string |  |
| **DefaultFormula** | string |  |
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
| **IndexStatus** | [FieldIndexStatus](#fieldindexstatus-enum) |  |
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
| **ShowInFiltersPane** | [ShowInFiltersPaneStatus](#showinfilterspanestatus-enum) |  |
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
# FieldThumbnail Class

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
| **FieldThumbnail(ClientRuntimeContext context, ObjectPath objectPath)** |  |
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
| **Location** |  |
| **Thumbnail** |  |
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
| **ClientSideComponentId** | Guid |  |
| **ClientSideComponentProperties** | string |  |
| **ClientValidationFormula** | string |  |
| **ClientValidationMessage** | string |  |
| **CustomFormatter** | string |  |
| **DefaultFormula** | string |  |
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
| **IndexStatus** | [FieldIndexStatus](#fieldindexstatus-enum) |  |
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
| **ShowInFiltersPane** | [ShowInFiltersPaneStatus](#showinfilterspanestatus-enum) |  |
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
| **UserDisplayOptions** | string |  |
| **AllowMultipleValues** | bool |  |
| **DependentLookupInternalNames** | IList\<string\> |  |
| **IsDependentLookup** | bool |  |
| **IsRelationship** | bool |  |
| **LookupField** | string |  |
| **LookupList** | string |  |
| **LookupWebId** | Guid |  |
| **PrimaryFieldId** | string |  |
| **RelationshipDeleteBehavior** | [RelationshipDeleteBehaviorType](#relationshipdeletebehaviortype-enum) |  |
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
| **IndexStatus** | [FieldIndexStatus](#fieldindexstatus-enum) |  |
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
| **ShowInFiltersPane** | [ShowInFiltersPaneStatus](#showinfilterspanestatus-enum) |  |
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
| **UserDisplayOptions** | string |  |
# FieldUserSelectionMode Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **PeopleOnly** |  |
| **PeopleAndGroups** |  |
| **GroupsOnly** |  |
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
| **ComplianceInfo** | [ListItemComplianceInfo](#listitemcomplianceinfo-class) |  |
| **ContentTag** | string |  |
| **CustomizedPageStatus** | [CustomizedPageStatus](#customizedpagestatus-enum) |  |
| **ListId** | Guid |  |
| **EffectiveInformationRightsManagementSettings** | [EffectiveInformationRightsManagementSettings](#effectiveinformationrightsmanagementsettings-class) |  |
| **ETag** | string |  |
| **Exists** | bool |  |
| **ExpirationDate** | DateTime |  |
| **HasAlternateContentStreams** | bool |  |
| **InformationRightsManagementSettings** | [InformationRightsManagementFileSettings](#informationrightsmanagementfilesettings-class) |  |
| **IrmEnabled** | bool |  |
| **Length** | long |  |
| **Level** | [FileLevel](#filelevel-enum) |  |
| **LinkingUri** | string |  |
| **LinkingUrl** | string |  |
| **ListItemAllFields** | [ListItem](#listitem-class) |  |
| **LockedByUser** | [User](#user-class) |  |
| **MajorVersion** | int |  |
| **MinorVersion** | int |  |
| **ModifiedBy** | [User](#user-class) |  |
| **Name** | string |  |
| **PageRenderType** | [ListPageRenderType](#listpagerendertype-enum) |  |
| **Properties** | [PropertyValues](#propertyvalues-class) |  |
| **ServerRedirectedUrl** | string |  |
| **ServerRelativePath** | [ResourcePath](#resourcepath-class) |  |
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
| **VroomDriveID** | string |  |
| **VroomItemID** | string |  |
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
| **ChangeContentStorageSchema(string desiredSchema)** | ClientResult\<bool\> |  |
| **CheckAccessAndPostViewAuditEvent()** | ClientResult\<bool\> |  |
| **CheckIn(string comment, CheckinType checkInType)** | void |  |
| **CheckOut()** | void |  |
| **ContinueUpload(Guid uploadId, long fileOffset, Stream stream)** | ClientResult\<long\> |  |
| **CopyTo(string strNewUrl, bool bOverWrite)** | void |  |
| **CopyToUsingPath(ResourcePath newPath, bool bOverWrite)** | void |  |
| **DeleteObject()** | void |  |
| **DeleteWithParameters(FileDeleteParameters parameters)** | void |  |
| **Deny(string comment)** | void |  |
| **ExecuteCobaltRequest(Stream inputStream)** | ClientResult\<Stream\> |  |
| **FinishUpload(Guid uploadId, long fileOffset, Stream stream)** | [File](#file-class) |  |
| **FinishUploadWithChecksum(Guid uploadId, long fileOffset, string checksum, Stream stream)** | [File](#file-class) |  |
| **GetContentVerFromTag(ClientRuntimeContext context, string contentTag)** | ClientResult\<int\> |  |
| **GetImagePreviewUri(int width, int height, string clientType)** | ClientResult\<string\> |  |
| **GetImagePreviewUrl(int width, int height, string clientType)** | ClientResult\<string\> |  |
| **GetLimitedWebPartManager(PersonalizationScope scope)** | [LimitedWebPartManager](#limitedwebpartmanager-class) |  |
| **GetMediaServiceMetadata()** | ClientResult\<[MediaServiceUpdateParameters](#mediaserviceupdateparameters-class)\> |  |
| **GetPreAuthorizedAccessUrl(int expirationHours)** | ClientResult\<string\> |  |
| **GetPreAuthorizedAccessUrl2(int expirationHours, int expirationMinuites)** | ClientResult\<string\> |  |
| **GetUploadStatus(Guid uploadId)** | [UploadStatus](#uploadstatus-class) |  |
| **GetWOPIFrameUrl(SPWOPIFrameAction action)** | ClientResult\<string\> |  |
| **MoveTo(string newUrl, MoveOperations flags)** | void |  |
| **MoveToUsingPath(ResourcePath newPath, MoveOperations moveOperations)** | void |  |
| **OpenBinaryStream()** | ClientResult\<Stream\> |  |
| **OpenBinaryStreamWithOptions(SPOpenBinaryOptions openOptions)** | ClientResult\<Stream\> |  |
| **Publish(string comment)** | void |  |
| **Recycle()** | ClientResult\<Guid\> |  |
| **RecycleWithETag(string etagMatch)** | ClientResult\<Guid\> |  |
| **RecycleWithParameters(FileDeleteParameters parameters)** | ClientResult\<Guid\> |  |
| **SaveBinary(FileSaveBinaryInformation parameters)** | void |  |
| **SetExpirationDate(DateTime expirationDate)** | void |  |
| **SetMediaServiceMetadata(MediaServiceUpdateParameters parameters)** | void |  |
| **StartUpload(Guid uploadId, Stream stream)** | ClientResult\<long\> |  |
| **StartUploadFile(Guid uploadId, Stream stream)** | [File](#file-class) |  |
| **UndoCheckOut()** | void |  |
| **UnPublish(string comment)** | void |  |
| **Update()** | void |  |
| **Upload(Guid uploadId, Stream stream)** | [File](#file-class) |  |
| **UploadWithChecksum(Guid uploadId, byte[] checksum, Stream stream)** | [File](#file-class) |  |
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
| **AddUsingPath(ResourcePath path, FileCollectionAddParameters parameters, Stream contentStream)** | [File](#file-class) |  |
| **GetByUrl(string url)** | [File](#file-class) |  |
# FileCollectionAddParameters Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AutoCheckoutOnInvalidData** | bool |  |
| **EnsureUniqueFileName** | bool |  |
| **Overwrite** | bool |  |
| **XorHash** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
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
| **XorHash** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# FileDeleteParameters Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **BypassSharedLock** | bool |  |
| **ETagMatch** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
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
| **ComplianceInfo** | string |  |
| **ContentTag** | string |  |
| **CustomizedPageStatus** | string |  |
| **ListId** | string |  |
| **ETag** | string |  |
| **Exists** | string |  |
| **ExpirationDate** | string |  |
| **HasAlternateContentStreams** | string |  |
| **IrmEnabled** | string |  |
| **Length** | string |  |
| **Level** | string |  |
| **LinkingUri** | string |  |
| **LinkingUrl** | string |  |
| **MajorVersion** | string |  |
| **MinorVersion** | string |  |
| **Name** | string |  |
| **PageRenderType** | string |  |
| **ServerRedirectedUrl** | string |  |
| **ServerRelativePath** | string |  |
| **ServerRelativeUrl** | string |  |
| **SiteId** | string |  |
| **TimeCreated** | string |  |
| **TimeLastModified** | string |  |
| **Title** | string |  |
| **UIVersion** | string |  |
| **UIVersionLabel** | string |  |
| **UniqueId** | string |  |
| **VroomDriveID** | string |  |
| **VroomItemID** | string |  |
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
| **OpenBinaryStreamWithOptions(SPOpenBinaryOptions openOptions)** | ClientResult\<Stream\> |  |
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
| **RecycleByID(int vid)** | void |  |
| **RecycleByLabel(string versionlabel)** | void |  |
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
# FlowSynchronizationResult Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **SynchronizationData** | string |  |
| **SynchronizationStatus** | [FlowSynchronizationStatus](#flowsynchronizationstatus-enum) |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **FlowSynchronizationResult(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# FlowSynchronizationResultPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **SynchronizationData** | string |  |
| **SynchronizationStatus** | string |  |
# FlowSynchronizationStatus Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Success** |  |
| **NotFound** |  |
| **Forbidden** |  |
| **TimeOut** |  |
| **UnexpectedError** |  |
| **BadRequest** |  |
| **Suspended** |  |
| **Running** |  |
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
| **ServerRelativePath** | [ResourcePath](#resourcepath-class) |  |
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
| **AddSubFolder(string leafName, ListItemUpdateParameters updateParams)** | void |  |
| **AddSubFolderUsingPath(ResourcePath leafPath)** | void |  |
| **DeleteObject()** | void |  |
| **DeleteWithParameters(FolderDeleteParameters parameters)** | void |  |
| **GetChanges(ChangeQuery query)** | [ChangeCollection](#changecollection-class) |  |
| **GetListItemChanges(ChangeQuery query)** | [ChangeCollection](#changecollection-class) |  |
| **MoveTo(string newUrl)** | void |  |
| **MoveToUsingPath(ResourcePath newPath)** | void |  |
| **Recycle()** | ClientResult\<Guid\> |  |
| **RecycleWithParameters(FolderDeleteParameters parameters)** | ClientResult\<Guid\> |  |
| **StartDelete()** | ClientResult\<Guid\> |  |
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
| **AddUsingPath(ResourcePath path, FolderCollectionAddParameters parameters)** | [Folder](#folder-class) |  |
| **AddWithOverwrite(string url, bool overwrite)** | [Folder](#folder-class) |  |
| **GetByPath(ResourcePath path)** | [Folder](#folder-class) |  |
| **GetByUrl(string url)** | [Folder](#folder-class) |  |
# FolderCollectionAddParameters Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **EnsureUniqueFileName** | bool |  |
| **Overwrite** | bool |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# FolderDeleteParameters Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **BypassSharedLock** | bool |  |
| **DeleteIfEmpty** | bool |  |
| **ETagMatch** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
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
| **ServerRelativePath** | string |  |
| **ServerRelativeUrl** | string |  |
| **TimeCreated** | string |  |
| **TimeLastModified** | string |  |
| **UniqueContentTypeOrder** | string |  |
| **UniqueId** | string |  |
| **WelcomePage** | string |  |
# FooterLayoutType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Simple** |  |
| **Extended** |  |
| **Stacked** |  |
# FooterVariantThemeType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Strong** |  |
| **Neutral** |  |
| **Soft** |  |
| **None** |  |
# Form Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Id** | Guid |  |
| **ResourcePath** | [ResourcePath](#resourcepath-class) |  |
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
| **ResourcePath** | string |  |
| **ServerRelativeUrl** | string |  |
| **FormType** | string |  |
# GetListItemVersionsParameters Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ListItemVersionCollectionPosition** | [ListItemVersionCollectionPosition](#listitemversioncollectionposition-class) |  |
| **RowLimit** | uint |  |
| **SortDescending** | bool |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# GetListsParameters Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ListCollectionPosition** | [ListCollectionPosition](#listcollectionposition-class) |  |
| **RowLimit** | int |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
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
# Hashtag Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Actor** | string |  |
| **Application** | string |  |
| **Label** | string |  |
| **Timestamp** | DateTime |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# HeaderLayoutType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **Standard** |  |
| **Compact** |  |
| **Minimal** |  |
| **Extended** |  |
# HomeSiteNavConfiguration Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **IsEnabled** | bool |  |
| **LogoHash** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# HomeSitesDetails Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Audiences** | IList\<Guid\> |  |
| **MatchingAudiences** | IList\<Guid\> |  |
| **SiteId** | Guid |  |
| **Title** | string |  |
| **Url** | string |  |
| **WebId** | Guid |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# HubSiteCreationInformation Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Description** | string |  |
| **EnablePermissionsSync** | bool |  |
| **EnforcedECTs** | string |  |
| **EnforcedECTsVersion** | int |  |
| **HideNameInNavigation** | bool |  |
| **LogoUrl** | string |  |
| **ParentHubSiteId** | Guid |  |
| **PermissionsSyncTag** | int |  |
| **RequiresJoinApproval** | bool |  |
| **SiteDesignId** | Guid |  |
| **SiteId** | Guid |  |
| **SiteUrl** | string |  |
| **Targets** | string |  |
| **TenantInstanceId** | Guid |  |
| **Title** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
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
# KnowledgeHub Class

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
| **KnowledgeHub(ClientRuntimeContext context)** |  |
| **KnowledgeHub(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# KnowledgeHubSiteReference Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **SiteId** | Guid |  |
| **Url** | string |  |
| **WebId** | Guid |  |
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
# LanguageCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObjectCollection<[Language](#language-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [Language](#language-class) |  |
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
| **LanguageCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetById(int id)** | ClientResult\<[Language](#language-class)\> |  |
# List Class

Namespace: Microsoft.SharePoint.Client

Base class: [SecurableObject](#securableobject-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **AdditionalUXProperties** | string |  |
| **AllowContentTypes** | bool |  |
| **AllowDeletion** | bool |  |
| **Author** | [User](#user-class) |  |
| **BaseTemplate** | int |  |
| **BaseType** | [BaseType](#basetype-enum) |  |
| **BrowserFileHandling** | [BrowserFileHandling](#browserfilehandling-enum) |  |
| **Color** | string |  |
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
| **DefaultItemOpenInBrowser** | bool |  |
| **DefaultItemOpenUseListSetting** | bool |  |
| **DefaultNewFormUrl** | string |  |
| **DefaultView** | [View](#view-class) |  |
| **DefaultViewPath** | [ResourcePath](#resourcepath-class) |  |
| **DefaultViewUrl** | string |  |
| **Description** | string |  |
| **DescriptionResource** | [UserResource](#userresource-class) |  |
| **Direction** | string |  |
| **DisableCommenting** | bool |  |
| **DisableGridEditing** | bool |  |
| **DocumentTemplateUrl** | string |  |
| **DraftVersionVisibility** | [DraftVisibilityType](#draftvisibilitytype-enum) |  |
| **EffectiveBasePermissions** | [BasePermissions](#basepermissions-class) |  |
| **EffectiveBasePermissionsForUI** | [BasePermissions](#basepermissions-class) |  |
| **EnableAssignToEmail** | bool |  |
| **EnableAttachments** | bool |  |
| **EnableFolderCreation** | bool |  |
| **EnableMinorVersions** | bool |  |
| **EnableModeration** | bool |  |
| **EnableRequestSignOff** | bool |  |
| **EnableVersioning** | bool |  |
| **EntityTypeName** | string |  |
| **EventReceivers** | [EventReceiverDefinitionCollection](#eventreceiverdefinitioncollection-class) |  |
| **ExcludeFromOfflineClient** | bool |  |
| **ExemptFromBlockDownloadOfNonViewableFiles** | bool |  |
| **Fields** | [FieldCollection](#fieldcollection-class) |  |
| **FileSavePostProcessingEnabled** | bool |  |
| **ForceCheckout** | bool |  |
| **Forms** | [FormCollection](#formcollection-class) |  |
| **HasExternalDataSource** | bool |  |
| **Hidden** | bool |  |
| **HighPriorityMediaProcessing** | bool |  |
| **Icon** | string |  |
| **Id** | Guid |  |
| **ImagePath** | [ResourcePath](#resourcepath-class) |  |
| **ImageUrl** | string |  |
| **InformationRightsManagementSettings** | [InformationRightsManagementSettings](#informationrightsmanagementsettings-class) |  |
| **DefaultSensitivityLabelForLibrary** | string |  |
| **IrmEnabled** | bool |  |
| **IrmExpire** | bool |  |
| **IrmReject** | bool |  |
| **IsApplicationList** | bool |  |
| **IsCatalog** | bool |  |
| **IsDefaultDocumentLibrary** | bool |  |
| **IsEnterpriseGalleryLibrary** | bool |  |
| **IsPredictionModelApplied** | bool |  |
| **IsPrivate** | bool |  |
| **IsSiteAssetsLibrary** | bool |  |
| **IsSystemList** | bool |  |
| **ItemCount** | int |  |
| **LastItemDeletedDate** | DateTime |  |
| **LastItemModifiedDate** | DateTime |  |
| **LastItemUserModifiedDate** | DateTime |  |
| **ListExperienceOptions** | [ListExperience](#listexperience-enum) |  |
| **ListFormCustomized** | bool |  |
| **ListItemEntityTypeFullName** | string |  |
| **ListSchemaVersion** | int |  |
| **MajorVersionLimit** | int |  |
| **MajorWithMinorVersionsLimit** | int |  |
| **MultipleDataList** | bool |  |
| **NoCrawl** | bool |  |
| **OnQuickLaunch** | bool |  |
| **PageRenderType** | [ListPageRenderType](#listpagerendertype-enum) |  |
| **ParentWeb** | [Web](#web-class) |  |
| **ParentWebPath** | [ResourcePath](#resourcepath-class) |  |
| **ParentWebUrl** | string |  |
| **ParserDisabled** | bool |  |
| **ReadSecurity** | int |  |
| **RootFolder** | [Folder](#folder-class) |  |
| **SchemaXml** | string |  |
| **ServerTemplateCanCreateFolders** | bool |  |
| **ShowHiddenFieldsInModernForm** | bool |  |
| **TemplateFeatureId** | Guid |  |
| **TemplateTypeId** | string |  |
| **Title** | string |  |
| **TitleResource** | [UserResource](#userresource-class) |  |
| **UserCustomActions** | [UserCustomActionCollection](#usercustomactioncollection-class) |  |
| **ValidationFormula** | string |  |
| **ValidationMessage** | string |  |
| **Views** | [ViewCollection](#viewcollection-class) |  |
| **WorkflowAssociations** | [WorkflowAssociationCollection](#workflowassociationcollection-class) |  |
| **WriteSecurity** | int |  |
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
| **AddItemUsingPath(ListItemCreationInformationUsingPath parameters)** | [ListItem](#listitem-class) |  |
| **CAAECreateTempFolder()** | ClientResult\<string\> |  |
| **CAAERenameFileInTemporaryFolder(string Path, string UpdatedName)** | ClientResult\<string\> |  |
| **CopyTemplateAndGetMetadata(string Id)** | ClientResult\<[TemplatizationMetaData](#templatizationmetadata-class)\> |  |
| **CreateDocument(string fileName, Folder targetFolder, DocumentTemplateType templateType)** | [ListItem](#listitem-class) |  |
| **CreateDocumentAndGetEditLink(string fileName, string folderPath, int documentTemplateType, string templateUrl)** | ClientResult\<string\> |  |
| **CreateDocumentFromCAAETemplate(string ContentTypeName, DocumentGenerationInfo documentGenerationInfo)** | ClientResult\<[ContentAssemblyFileInfo](#contentassemblyfileinfo-class)\> |  |
| **CreateDocumentFromCAAETemplateV2(string Id, DocumentGenerationInfo documentGenerationInfo)** | ClientResult\<[ContentAssemblyFileInfo](#contentassemblyfileinfo-class)\> |  |
| **CreateDocumentFromTemplate(string fileName, Folder targetFolder, string templateUrl)** | [ListItem](#listitem-class) |  |
| **CreateDocumentFromTemplateBytes(string fileName, Folder targetFolder, byte[] templateBytes, string extension)** | [ListItem](#listitem-class) |  |
| **CreateDocumentFromTemplateStream(string fileName, Folder targetFolder, string extension, Stream templateStream)** | [ListItem](#listitem-class) |  |
| **CreateDocumentFromTemplateUsingPath(ResourcePath filePath, Folder targetFolder, ResourcePath templatePath)** | [ListItem](#listitem-class) |  |
| **CreateDocumentWithDefaultName(string folderPath, string extension)** | ClientResult\<string\> |  |
| **CreateMappedView(AppViewCreationInfo appViewCreationInfo, VisualizationAppTarget visualizationTarget)** | [View](#view-class) |  |
| **CreateSmartTemplateContentTypeAndAddToList(string Name, string Description)** | [ContentType](#contenttype-class) |  |
| **CreateSmartTemplateContentTypeAndAddToListV2(string Name, string Description, string TemplatePath, string Status)** | [ContentType](#contenttype-class) |  |
| **DeleteObject()** | void |  |
| **EnqueueAsyncActionTaskById(Guid id, IDictionary\<string, string\> parameters)** | ClientResult\<bool\> |  |
| **GetAsyncActionConfig(Guid id)** | ClientResult\<IDictionary\<string, string\>\> |  |
| **GetAsyncActionTaskIds()** | IList\<Guid\> |  |
| **GetBloomFilter(int startItemId)** | [ListBloomFilter](#listbloomfilter-class) |  |
| **GetBloomFilterWithCustomFields(int listItemStartingID, IList\<string\> internalFieldNames)** | [ListBloomFilter](#listbloomfilter-class) |  |
| **GetCAAETemplateMetadata(string Name, bool Published)** | ClientResult\<[TemplateMetaData](#templatemetadata-class)\> |  |
| **GetCAAETemplateMetadataV2(string Id)** | IEnumerable\<[PlaceholderV2](#placeholderv2-class)\> |  |
| **GetChanges(ChangeQuery query)** | [ChangeCollection](#changecollection-class) |  |
| **GetCheckedOutFiles()** | [CheckedOutFileCollection](#checkedoutfilecollection-class) |  |
| **GetItemById(int id)** | [ListItem](#listitem-class) |  |
| **GetItemById(string id)** | [ListItem](#listitem-class) |  |
| **GetItemByUniqueId(Guid uniqueId)** | [ListItem](#listitem-class) |  |
| **GetItems(CamlQuery query)** | [ListItemCollection](#listitemcollection-class) |  |
| **GetListDataAsStream(ClientRuntimeContext context, string listFullUrl, RenderListDataParameters parameters, RenderListDataOverrideParameters overrideParameters)** | ClientResult\<Stream\> |  |
| **GetLookupFieldChoices(string targetFieldName, string pagingInfo)** | ClientResult\<string\> |  |
| **GetMappedApp(Guid appId, VisualizationAppTarget visualizationAppTarget)** | [VisualizationAppSynchronizationResult](#visualizationappsynchronizationresult-class) |  |
| **GetMappedApps(VisualizationAppTarget visualizationAppTarget)** | [VisualizationAppSynchronizationResult](#visualizationappsynchronizationresult-class) |  |
| **GetOneDriveListDataAsStream(ClientRuntimeContext context, RenderListDataParameters parameters, RenderListDataOverrideParameters overrideParameters)** | ClientResult\<Stream\> |  |
| **GetRelatedFields()** | [RelatedFieldCollection](#relatedfieldcollection-class) |  |
| **GetSpecialFolderUrl(SpecialFolderType type, bool bForceCreate, Guid existingFolderGuid)** | ClientResult\<string\> |  |
| **GetUserEffectivePermissions(string userName)** | ClientResult\<[BasePermissions](#basepermissions-class)\> |  |
| **GetView(Guid viewGuid)** | [View](#view-class) |  |
| **GetWebDavUrl(string sourceUrl)** | ClientResult\<string\> |  |
| **LockSmartTemplate(string Id)** | ClientResult\<[LockFileData](#lockfiledata-class)\> |  |
| **ParseDocumentTemplate(string Name)** | ClientResult\<string\> |  |
| **PublishMappedView(Guid appId, VisualizationAppTarget visualizationTarget)** | [View](#view-class) |  |
| **Recycle()** | ClientResult\<Guid\> |  |
| **RefreshLockSmartTemplate(string Id, string LockId)** | ClientResult\<[LockFileData](#lockfiledata-class)\> |  |
| **RenderExtendedListFormData(int itemId, string formId, int mode, RenderListFormDataOptions options, int cutoffVersion)** | ClientResult\<string\> |  |
| **RenderListContextMenuData(RenderListContextMenuDataParameters parameters)** | ClientResult\<Stream\> |  |
| **RenderListData(string viewXml)** | ClientResult\<string\> |  |
| **RenderListDataAsStream(RenderListDataParameters parameters, RenderListDataOverrideParameters overrideParameters)** | ClientResult\<Stream\> |  |
| **RenderListFilterData(RenderListFilterDataParameters parameters)** | ClientResult\<Stream\> |  |
| **RenderListFormData(int itemId, string formId, int mode)** | ClientResult\<string\> |  |
| **ReserveListItemId()** | ClientResult\<int\> |  |
| **SaveAsNewView(string oldName, string newName, bool privateView, string uri)** | ClientResult\<string\> |  |
| **SaveAsTemplate(string strFileName, string strName, string strDescription, bool bSaveData)** | void |  |
| **SearchLookupFieldChoices(string targetFieldName, string beginsWithSearchString, string pagingInfo)** | ClientResult\<string\> |  |
| **SetExemptFromBlockDownloadOfNonViewableFiles(bool value)** | void |  |
| **SyncFlowCallbackUrl(string flowId)** | [FlowSynchronizationResult](#flowsynchronizationresult-class) |  |
| **SyncFlowInstance(Guid flowID)** | [FlowSynchronizationResult](#flowsynchronizationresult-class) |  |
| **SyncFlowInstances(bool retrieveGroupFlows)** | [FlowSynchronizationResult](#flowsynchronizationresult-class) |  |
| **SyncFlowTemplates(string category)** | [FlowSynchronizationResult](#flowsynchronizationresult-class) |  |
| **UnlockSmartTemplate(string Id, string LockId)** | void |  |
| **UnpublishMappedView(Guid appId, VisualizationAppTarget visualizationTarget)** | [View](#view-class) |  |
| **Update()** | void |  |
| **UpdateCAAETemplate(string Name, UpdateTemplateInfo updateTemplateInfo)** | void |  |
| **UpdateCAAETemplateV2(string Id, UpdateTemplateInfoV2 updateTemplateInfo)** | void |  |
| **ValidateAppName(string appDisplayName)** | [VisualizationAppSynchronizationResult](#visualizationappsynchronizationresult-class) |  |
# ListBloomFilter Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **BloomFilterSize** | int |  |
| **FalsePositiveRate** | double |  |
| **HashedValueSet** | IList\<string\> |  |
| **IndexMap** | IList\<int\> |  |
| **ItemProcessedCount** | int |  |
| **K** | int |  |
| **LastListItemIdProcessed** | int |  |
| **MaxItemCount** | int |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **ListBloomFilter(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ListBloomFilterPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **BloomFilterSize** | string |  |
| **FalsePositiveRate** | string |  |
| **HashedValueSet** | string |  |
| **IndexMap** | string |  |
| **ItemProcessedCount** | string |  |
| **K** | string |  |
| **LastListItemIdProcessed** | string |  |
| **MaxItemCount** | string |  |
# ListCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObjectCollection<[List](#list-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **ListCollectionPosition** | [ListCollectionPosition](#listcollectionposition-class) |  |
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
| **EnsureClientRenderedSitePagesLibrary()** | [List](#list-class) |  |
| **EnsureSiteAssetsLibrary()** | [List](#list-class) |  |
| **EnsureSitePagesLibrary()** | [List](#list-class) |  |
| **GetById(Guid id)** | [List](#list-class) |  |
| **GetByTitle(string title)** | [List](#list-class) |  |
# ListCollectionPosition Class

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
# ListCollectionPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **ListCollectionPosition** | string |  |
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
| **ListTemplate** | [ListTemplate](#listtemplate-class) |  |
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
# ListExperience Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Auto** |  |
| **NewExperience** |  |
| **ClassicExperience** |  |
# ListHomeItem Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **color** | string |  |
| **icon** | string |  |
| **isDefaultDocumentLibrary** | bool |  |
| **isDocLib** | bool |  |
| **listId** | string |  |
| **listUrl** | string |  |
| **siteAcronym** | string |  |
| **siteColor** | string |  |
| **siteIconUrl** | string |  |
| **siteId** | string |  |
| **siteTitle** | string |  |
| **siteUrl** | string |  |
| **title** | string |  |
| **webId** | string |  |
| **webTemplateConfiguration** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# ListHomeItem2 Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **color** | string |  |
| **createdByName** | string |  |
| **createdByUpn** | string |  |
| **createdDate** | string |  |
| **icon** | string |  |
| **lastModifiedDate** | string |  |
| **lastViewDate** | string |  |
| **lastviewDateTime** | string |  |
| **listId** | string |  |
| **listTitle** | string |  |
| **listUrl** | string |  |
| **listViewCounts** | IEnumerable\<[CountByDate](#countbydate-class)\> |  |
| **shouldRemove** | bool |  |
| **siteColor** | string |  |
| **siteId** | string |  |
| **siteTitle** | string |  |
| **siteUrl** | string |  |
| **TemplateTypeId** | string |  |
| **webId** | string |  |
| **webTemplateConfiguration** | string |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **ListHomeItem2(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ListHomeItem2PropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **color** | string |  |
| **createdByName** | string |  |
| **createdByUpn** | string |  |
| **createdDate** | string |  |
| **icon** | string |  |
| **lastModifiedDate** | string |  |
| **lastViewDate** | string |  |
| **lastviewDateTime** | string |  |
| **listId** | string |  |
| **listTitle** | string |  |
| **listUrl** | string |  |
| **listViewCounts** | string |  |
| **shouldRemove** | string |  |
| **siteColor** | string |  |
| **siteId** | string |  |
| **siteTitle** | string |  |
| **siteUrl** | string |  |
| **TemplateTypeId** | string |  |
| **webId** | string |  |
| **webTemplateConfiguration** | string |  |
# ListHomeItemCollection Class

Namespace: Microsoft.SharePoint.Client


## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetListHomeItems(ClientRuntimeContext context, int sortBy)** | ClientResult\<Stream\> |  |
| **GetListHomeItemsWithPageContextInfo(ClientRuntimeContext context, int sortBy)** | ClientResult\<Stream\> |  |
| **GetListHomePersonalLists(ClientRuntimeContext context, int sortBy, string templateTypeId)** | ClientObjectList\<[ListHomeItem2](#listhomeitem2-class)\> |  |
| **GetRecommendLists(ClientRuntimeContext context)** | ClientResult\<string\> |  |
| **RemoveRecentLists(ClientRuntimeContext context, string recentListsJson)** | void |  |
| **RemoveRecommendLists(ClientRuntimeContext context, string recommendListsJson)** | void |  |
# ListItem Class

Namespace: Microsoft.SharePoint.Client

Base class: [SecurableObject](#securableobject-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **FieldValues** | Dictionary\<string, Object\> |  |
| **Item** | Object |  |
| **AttachmentFiles** | [AttachmentCollection](#attachmentcollection-class) |  |
| **CommentsDisabled** | bool |  |
| **CommentsDisabledScope** | [CommentsDisabledScope](#commentsdisabledscope-enum) |  |
| **ComplianceInfo** | [ListItemComplianceInfo](#listitemcomplianceinfo-class) |  |
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
| **IconOverlay** | string |  |
| **Id** | int |  |
| **ParentList** | [List](#list-class) |  |
| **Properties** | [PropertyValues](#propertyvalues-class) |  |
| **ServerRedirectedEmbedUri** | string |  |
| **ServerRedirectedEmbedUrl** | string |  |
| **Client_Title** | string |  |
| **Versions** | [ListItemVersionCollection](#listitemversioncollection-class) |  |
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
| **DeleteObject()** | void |  |
| **DeleteWithParameters(ListItemDeleteParameters parameters)** | void |  |
| **GetChanges(ChangeQuery query)** | [ChangeCollection](#changecollection-class) |  |
| **GetUserEffectivePermissions(string userName)** | ClientResult\<[BasePermissions](#basepermissions-class)\> |  |
| **GetVersions(GetListItemVersionsParameters getVersionsParams)** | [ListItemVersionCollection](#listitemversioncollection-class) |  |
| **GetWOPIFrameUrl(SPWOPIFrameAction action)** | ClientResult\<string\> |  |
| **MediaServiceUpdate(MediaServiceUpdateParameters parameters)** | void |  |
| **MediaServiceUpdateV2(MediaServiceUpdateParameters parameters, bool eventFiringEnabled)** | void |  |
| **OverridePolicyTip(PolicyTipUserAction userAction, string justification)** | ClientResult\<[PolicyTipUserActionResult](#policytipuseractionresult-enum)\> |  |
| **ParseAndSetFieldValue(string fieldName, string value)** | void |  |
| **Recycle()** | ClientResult\<Guid\> |  |
| **RecycleWithParameters(ListItemDeleteParameters parameters)** | ClientResult\<Guid\> |  |
| **RefreshLoad()** | void |  |
| **SetCommentsDisabled(bool value)** | void |  |
| **SetComplianceTag(string complianceTag, bool isTagPolicyHold, bool isTagPolicyRecord, bool isEventBasedTag, bool isTagSuperLock, bool isUnlockedAsDefault)** | void |  |
| **SetComplianceTagWithExplicitMetasUpdate(string complianceTag, int complianceFlags, DateTime complianceTagWrittenTime, string userEmailAddress)** | void |  |
| **SetComplianceTagWithHold(string complianceTag)** | void |  |
| **SetComplianceTagWithMetaInfo(string complianceTag, bool blockDelete, bool blockEdit, DateTime complianceTagWrittenTime, string userEmailAddress, bool isTagSuperLock, bool isRecordUnlockedAsDefault)** | void |  |
| **SetComplianceTagWithNoHold(string complianceTag)** | void |  |
| **SetComplianceTagWithRecord(string complianceTag)** | void |  |
| **SystemUpdate()** | void |  |
| **Update()** | void |  |
| **UpdateEx(ListItemUpdateParameters parameters)** | void |  |
| **UpdateOverwriteVersion()** | void |  |
| **ValidateUpdateFetchListItem(IList\<ListItemFormUpdateValue\> formValues, bool bNewDocumentUpdate, string checkInComment, bool datesInUTC, bool numberInInvariantCulture)** | ClientResult\<[ListItemUpdateResults](#listitemupdateresults-class)\> |  |
| **ValidateUpdateListItem(IList\<ListItemFormUpdateValue\> formValues, bool bNewDocumentUpdate, string checkInComment, bool datesInUTC, bool numberInInvariantCulture)** | IList\<[ListItemFormUpdateValue](#listitemformupdatevalue-class)\> |  |
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
# ListItemComplianceInfo Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ComplianceTag** | string |  |
| **TagPolicyEventBased** | bool |  |
| **TagPolicyHold** | bool |  |
| **TagPolicyRecord** | bool |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
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
# ListItemCreationInformationUsingPath Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **FolderPath** | [ResourcePath](#resourcepath-class) |  |
| **LeafName** | [ResourcePath](#resourcepath-class) |  |
| **UnderlyingObjectType** | [FileSystemObjectType](#filesystemobjecttype-enum) |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# ListItemDeleteParameters Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **BypassSharedLock** | bool |  |
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
| **ErrorCode** | int |  |
| **ErrorMessage** | string |  |
| **FieldName** | string |  |
| **FieldValue** | string |  |
| **HasException** | bool |  |
| **ItemId** | int |  |
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
| **Properties** | string |  |
| **Versions** | string |  |
# ListItemPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **CommentsDisabled** | string |  |
| **CommentsDisabledScope** | string |  |
| **ComplianceInfo** | string |  |
| **DisplayName** | string |  |
| **EffectiveBasePermissions** | string |  |
| **EffectiveBasePermissionsForUI** | string |  |
| **FileSystemObjectType** | string |  |
| **IconOverlay** | string |  |
| **Id** | string |  |
| **ServerRedirectedEmbedUri** | string |  |
| **ServerRedirectedEmbedUrl** | string |  |
| **Client_Title** | string |  |
# ListItemUpdateParameters Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **BypassQuotaCheck** | bool |  |
| **BypassSharedLock** | bool |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# ListItemUpdateResults Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **UpdatedData** | string |  |
| **UpdateResults** | IList\<[ListItemFormUpdateValue](#listitemformupdatevalue-class)\> |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# ListItemVersion Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **FieldValues** | Dictionary\<string, Object\> |  |
| **Item** | Object |  |
| **Created** | DateTime |  |
| **CreatedBy** | [User](#user-class) |  |
| **Fields** | [FieldCollection](#fieldcollection-class) |  |
| **FileVersion** | [FileVersion](#fileversion-class) |  |
| **IsCurrentVersion** | bool |  |
| **VersionId** | int |  |
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
| **ListItemVersion(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
| **RefreshLoad()** | void |  |
# ListItemVersionCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObjectCollection<[ListItemVersion](#listitemversion-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **ListItemVersionCollectionPosition** | [ListItemVersionCollectionPosition](#listitemversioncollectionposition-class) |  |
| **Item** | [ListItemVersion](#listitemversion-class) |  |
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
| **ListItemVersionCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetById(int versionId)** | [ListItemVersion](#listitemversion-class) |  |
# ListItemVersionCollectionPosition Class

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
# ListItemVersionCollectionPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **ListItemVersionCollectionPosition** | string |  |
# ListItemVersionObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **CreatedBy** | string |  |
| **Fields** | string |  |
| **FileVersion** | string |  |
# ListItemVersionPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Created** | string |  |
| **IsCurrentVersion** | string |  |
| **VersionId** | string |  |
| **VersionLabel** | string |  |
# ListObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Author** | string |  |
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
# ListPageRenderType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Undefined** |  |
| **MultipeWePart** |  |
| **JSLinkCustomization** |  |
| **XslLinkCustomization** |  |
| **NoSPList** |  |
| **HasBusinessDataField** |  |
| **HasTaskOutcomeField** |  |
| **HasPublishingfield** |  |
| **HasGeolocationField** |  |
| **HasCustomActionWithCode** |  |
| **HasMetadataNavFeature** |  |
| **SpecialViewType** |  |
| **ListTypeNoSupportForModernMode** |  |
| **AnonymousUser** |  |
| **ListSettingOff** |  |
| **SiteSettingOff** |  |
| **WebSettingOff** |  |
| **TenantSettingOff** |  |
| **CustomizedForm** |  |
| **DocLibNewForm** |  |
| **UnsupportedFieldTypeInForm** |  |
| **InvalidFieldTypeInForm** |  |
| **InvalidControModeInForm** |  |
| **CustomizedPage** |  |
| **ListTemplateNotSupported** |  |
| **WikiPage** |  |
| **DropOffLibrary** |  |
| **IsUnghosted** |  |
| **Modern** |  |
# ListPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **AdditionalUXProperties** | string |  |
| **AllowContentTypes** | string |  |
| **AllowDeletion** | string |  |
| **BaseTemplate** | string |  |
| **BaseType** | string |  |
| **BrowserFileHandling** | string |  |
| **Color** | string |  |
| **ContentTypesEnabled** | string |  |
| **CrawlNonDefaultViews** | string |  |
| **Created** | string |  |
| **CurrentChangeToken** | string |  |
| **CustomActionElements** | string |  |
| **DataSource** | string |  |
| **DefaultContentApprovalWorkflowId** | string |  |
| **DefaultDisplayFormUrl** | string |  |
| **DefaultEditFormUrl** | string |  |
| **DefaultItemOpenInBrowser** | string |  |
| **DefaultItemOpenUseListSetting** | string |  |
| **DefaultNewFormUrl** | string |  |
| **DefaultViewPath** | string |  |
| **DefaultViewUrl** | string |  |
| **Description** | string |  |
| **Direction** | string |  |
| **DisableCommenting** | string |  |
| **DisableGridEditing** | string |  |
| **DocumentTemplateUrl** | string |  |
| **DraftVersionVisibility** | string |  |
| **EffectiveBasePermissions** | string |  |
| **EffectiveBasePermissionsForUI** | string |  |
| **EnableAssignToEmail** | string |  |
| **EnableAttachments** | string |  |
| **EnableFolderCreation** | string |  |
| **EnableMinorVersions** | string |  |
| **EnableModeration** | string |  |
| **EnableRequestSignOff** | string |  |
| **EnableVersioning** | string |  |
| **EntityTypeName** | string |  |
| **ExcludeFromOfflineClient** | string |  |
| **ExemptFromBlockDownloadOfNonViewableFiles** | string |  |
| **FileSavePostProcessingEnabled** | string |  |
| **ForceCheckout** | string |  |
| **HasExternalDataSource** | string |  |
| **Hidden** | string |  |
| **HighPriorityMediaProcessing** | string |  |
| **Icon** | string |  |
| **Id** | string |  |
| **ImagePath** | string |  |
| **ImageUrl** | string |  |
| **DefaultSensitivityLabelForLibrary** | string |  |
| **IrmEnabled** | string |  |
| **IrmExpire** | string |  |
| **IrmReject** | string |  |
| **IsApplicationList** | string |  |
| **IsCatalog** | string |  |
| **IsDefaultDocumentLibrary** | string |  |
| **IsEnterpriseGalleryLibrary** | string |  |
| **IsPredictionModelApplied** | string |  |
| **IsPrivate** | string |  |
| **IsSiteAssetsLibrary** | string |  |
| **IsSystemList** | string |  |
| **ItemCount** | string |  |
| **LastItemDeletedDate** | string |  |
| **LastItemModifiedDate** | string |  |
| **LastItemUserModifiedDate** | string |  |
| **ListExperienceOptions** | string |  |
| **ListFormCustomized** | string |  |
| **ListItemEntityTypeFullName** | string |  |
| **ListSchemaVersion** | string |  |
| **MajorVersionLimit** | string |  |
| **MajorWithMinorVersionsLimit** | string |  |
| **MultipleDataList** | string |  |
| **NoCrawl** | string |  |
| **OnQuickLaunch** | string |  |
| **PageRenderType** | string |  |
| **ParentWebPath** | string |  |
| **ParentWebUrl** | string |  |
| **ParserDisabled** | string |  |
| **ReadSecurity** | string |  |
| **SchemaXml** | string |  |
| **ServerTemplateCanCreateFolders** | string |  |
| **ShowHiddenFieldsInModernForm** | string |  |
| **TemplateFeatureId** | string |  |
| **TemplateTypeId** | string |  |
| **Title** | string |  |
| **ValidationFormula** | string |  |
| **ValidationMessage** | string |  |
| **WriteSecurity** | string |  |
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
| **AppFilesCatalog** |  |
| **DataConnectionLibrary** |  |
| **WorkflowHistory** |  |
| **GanttTasks** |  |
| **HelpLibrary** |  |
| **AccessRequest** |  |
| **PromotedLinks** |  |
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
| **RecordCenterRecordLibrary** |  |
| **ContentCenterModelLibrary** |  |
| **ContentCenterPrimeLibrary** |  |
| **ContentCenterSampleLibrary** |  |
| **AccessApp** |  |
| **AlchemyMobileForm** |  |
| **AlchemyApprovalWorkflow** |  |
| **SharingLinks** |  |
| **HashtagStore** |  |
| **RecipesTable** |  |
| **FormulasTable** |  |
| **WebTemplateExtensionsList** |  |
| **TemplatesTable** |  |
| **ItemReferenceCollection** |  |
| **ItemReferenceReference** |  |
| **ItemReferenceReferenceCollection** |  |
| **InvalidType** |  |
# LockFileData Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **lockExpireTimeStamp** | DateTime |  |
| **lockId** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# LogoAlignment Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Left** |  |
| **Middle** |  |
| **Right** |  |
# MachineLearningSampleMeta Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ExtractedText** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# MediaServiceUpdateParameters Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AIPLabelExtractionStatus** | [SPAIPLabelExtractionStatus](#spaiplabelextractionstatus-enum) |  |
| **ClassificationResult** | [ClassificationResult](#classificationresult-class) |  |
| **ContentVersion** | int |  |
| **ETag** | string |  |
| **MachineLearningSampleMeta** | [MachineLearningSampleMeta](#machinelearningsamplemeta-class) |  |
| **MediaLengthInSeconds** | int |  |
| **MediaServiceAutoKeyPoints** | string |  |
| **MediaServiceAutoTags** | string |  |
| **MediaServiceDateTaken** | string |  |
| **MediaServiceDocTags** | string |  |
| **MediaServiceEventHashCode** | string |  |
| **MediaServiceFastMetadata** | string |  |
| **MediaServiceGenerationTime** | string |  |
| **MediaServiceImageHeight** | int |  |
| **MediaServiceImageTags** | string |  |
| **MediaServiceImageWidth** | int |  |
| **MediaServiceKeyPoints** | string |  |
| **MediaServiceLocation** | string |  |
| **MediaServiceMetadata** | string |  |
| **MediaServiceOCR** | string |  |
| **MediaServiceTranscript** | string |  |
| **MostRecentGenerationTime** | string |  |
| **SensitivityLabel** | string |  |
| **SensitivityLabelAssignmentMethod** | [SPSensivityLabelAssignmentMethod](#spsensivitylabelassignmentmethod-enum) |  |
| **XTenantLabelInfo** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# MicroServiceManager Class

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
| **MicroServiceManager(ClientRuntimeContext context)** |  |
| **MicroServiceManager(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **AddMicroserviceWorkItem(byte[] payLoad, int minutes, MicroServiceWorkItemProperties properties)** | ClientResult\<Guid\> |  |
| **DeleteMicroserviceWorkItem(Guid workItemId)** | ClientResult\<bool\> |  |
| **DeleteMicroserviceWorkItemByContentDbId(Guid contentDatabaseId, Guid siteId, Guid workItemId)** | ClientResult\<bool\> |  |
# MicroServiceUtilities Class

Namespace: Microsoft.SharePoint.Client


# MicroServiceWorkItemProperties Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ApiPath** | string |  |
| **CustomProperties** | IDictionary\<string, Object\> |  |
| **HttpHeaders** | IDictionary\<string, string\> |  |
| **MicroServiceName** | string |  |
| **RequestType** | [RequestType](#requesttype-enum) |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# MigrationJobState Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **Queued** |  |
| **Processing** |  |
# MigrationNameConflictBehavior Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Fail** |  |
| **Replace** |  |
| **Rename** |  |
# ModernizeHomepageResult Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **CanModernizeHomepage** | bool |  |
| **Reason** | string |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **ModernizeHomepageResult(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ModernizeHomepageResultPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **CanModernizeHomepage** | string |  |
| **Reason** | string |  |
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
# MoveCopyOptions Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **KeepBoth** | bool |  |
| **ResetAuthorAndCreatedOnCopy** | bool |  |
| **RetainEditorAndModifiedOnMove** | bool |  |
| **ShouldBypassSharedLocks** | bool |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# MoveCopyUtil Class

Namespace: Microsoft.SharePoint.Client


## Methods

| Name | Returns | Summary |
|---|---|---|
| **CopyFile(ClientRuntimeContext context, string srcUrl, string destUrl, bool overwrite, MoveCopyOptions options)** | void |  |
| **CopyFileByPath(ClientRuntimeContext context, ResourcePath srcPath, ResourcePath destPath, bool overwrite, MoveCopyOptions options)** | void |  |
| **CopyFolder(ClientRuntimeContext context, string srcUrl, string destUrl, MoveCopyOptions options)** | void |  |
| **CopyFolderByPath(ClientRuntimeContext context, ResourcePath srcPath, ResourcePath destPath, MoveCopyOptions options)** | void |  |
| **MoveFile(ClientRuntimeContext context, string srcUrl, string destUrl, bool overwrite, MoveCopyOptions options)** | void |  |
| **MoveFileByPath(ClientRuntimeContext context, ResourcePath srcPath, ResourcePath destPath, bool overwrite, MoveCopyOptions options)** | void |  |
| **MoveFolder(ClientRuntimeContext context, string srcUrl, string destUrl, MoveCopyOptions options)** | void |  |
| **MoveFolderByPath(ClientRuntimeContext context, ResourcePath srcPath, ResourcePath destPath, MoveCopyOptions options)** | void |  |
# MoveOperations Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **Overwrite** |  |
| **AllowBrokenThickets** |  |
| **BypassApprovePermission** |  |
| **BypassSharedLock** |  |
| **RetainEditorAndModifiedOnMove** |  |
# MultiGeoCopyParameters Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **binaryPayload** | byte[] |  |
| **jobId** | Guid |  |
| **userId** | int |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
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
| **AudienceIds** | IList\<Guid\> |  |
| **Children** | [NavigationNodeCollection](#navigationnodecollection-class) |  |
| **CurrentLCID** | int |  |
| **Id** | int |  |
| **IsDocLib** | bool |  |
| **IsExternal** | bool |  |
| **IsVisible** | bool |  |
| **ListTemplateType** | [ListTemplateType](#listtemplatetype-enum) |  |
| **Title** | string |  |
| **TitleResource** | [UserResource](#userresource-class) |  |
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
| **TitleResource** | string |  |
# NavigationNodePropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **AudienceIds** | string |  |
| **CurrentLCID** | string |  |
| **Id** | string |  |
| **IsDocLib** | string |  |
| **IsExternal** | string |  |
| **IsVisible** | string |  |
| **ListTemplateType** | string |  |
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
# NewsCollection Class

Namespace: Microsoft.SharePoint.Client


## Methods

| Name | Returns | Summary |
|---|---|---|
| **HubNews(ClientRuntimeContext context, Guid departmentId, int start, int count, bool filterByAudience, string languageOverride)** | ClientResult\<[ItemsList](#itemslist-class)\> |  |
| **MultiHubNews(ClientRuntimeContext context, string multiHubJson, int start, int count, bool filterByAudience, string languageOverride)** | ClientResult\<[ItemsList](#itemslist-class)\> |  |
| **MultiSiteNews(ClientRuntimeContext context, string multiSiteJson, int start, int count, bool filterByAudience, string languageOverride)** | ClientResult\<[ItemsList](#itemslist-class)\> |  |
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
| **IsFolder** | bool |  |
| **IsSharedWithCurrentUser** | bool |  |
| **IsSharedWithGuest** | bool |  |
| **IsSharedWithMany** | bool |  |
| **IsSharedWithSecurityGroup** | bool |  |
| **PendingAccessRequestsLink** | string |  |
| **SharedWithUsersCollection** | [ObjectSharingInformationUserCollection](#objectsharinginformationusercollection-class) |  |
| **SharingLinks** | IEnumerable\<[SharingLinkInfo](#sharinglinkinfo-class)\> |  |
| **TotalFileCount** | ulong |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
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
| **IsFolder** | string |  |
| **IsSharedWithCurrentUser** | string |  |
| **IsSharedWithGuest** | string |  |
| **IsSharedWithMany** | string |  |
| **IsSharedWithSecurityGroup** | string |  |
| **PendingAccessRequestsLink** | string |  |
| **SharingLinks** | string |  |
| **TotalFileCount** | string |  |
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
| **HasReviewPermission** | bool |  |
| **HasViewPermission** | bool |  |
| **Id** | int |  |
| **IsDomainGroup** | bool |  |
| **IsExternalUser** | bool |  |
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
| **HasReviewPermission** | string |  |
| **HasViewPermission** | string |  |
| **Id** | string |  |
| **IsDomainGroup** | string |  |
| **IsExternalUser** | string |  |
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
| **BlockPeoplePickerAndSharing** | bool |  |
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
| **DefaultShareLinkPermission** | [Role](#role-enum) |  |
| **DefaultShareLinkType** | [SharingLinkKind](#sharinglinkkind-enum) |  |
| **EnforceIBSegmentFiltering** | bool |  |
| **EnforceSPOSearch** | bool |  |
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
| **SiteIBMode** | string |  |
| **SiteIBSegmentIDs** | string[] |  |
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
| **BlockPeoplePickerAndSharing** | string |  |
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
| **DefaultShareLinkPermission** | string |  |
| **DefaultShareLinkType** | string |  |
| **EnforceIBSegmentFiltering** | string |  |
| **EnforceSPOSearch** | string |  |
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
| **SiteIBMode** | string |  |
| **SiteIBSegmentIDs** | string |  |
| **SupportsAclPropagation** | string |  |
| **WebUrl** | string |  |
# OpenWebOptions Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **InitNavigationCache** |  |
| **InitExtendedWebProperties** |  |
# OpenWebParameters Class

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
| **OpenWebParameters(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# OrganizationNews Class

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
| **OrganizationNews(ClientRuntimeContext context)** |  |
| **OrganizationNews(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetSiteReference(ClientRuntimeContext context, string orgNewsSiteUrl, bool validate)** | ClientResult\<[OrganizationNewsSiteReference](#organizationnewssitereference-class)\> |  |
# OrganizationNewsSiteReference Class

Namespace: Microsoft.SharePoint.Client

Base class: [PortalAndOrgNewsSiteReference](#portalandorgnewssitereference-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **TypeId** | string |  |
| **SiteId** | Guid |  |
| **WebId** | Guid |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# OutputFileFormat Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Docx** |  |
| **Pdf** |  |
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
| **QuerySettings** | [PeoplePickerQuerySettings](#peoplepickerquerysettings-class) |  |
| **UseSubstrateSearch** | bool |  |
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
| **QuerySettings** | string |  |
| **UseSubstrateSearch** | string |  |
| **VisibleSuggestions** | string |  |
# PinnedItems Class

Namespace: Microsoft.SharePoint.Client


## Methods

| Name | Returns | Summary |
|---|---|---|
| **AddItem(ClientRuntimeContext context, FavoriteListHomeItem pinnedItem)** | void |  |
| **GetItemsBy(ClientRuntimeContext context, string siteId, string listId)** | ClientResult\<[FavoriteListHomeItem](#favoritelisthomeitem-class)[]\> |  |
| **RemoveItem(ClientRuntimeContext context, string siteId, string listId, string webId)** | void |  |
| **ReorderList(ClientRuntimeContext context, FavoriteListHomeItem itemToReorder, FavoriteListHomeItem itemBefore, FavoriteListHomeItem itemAfter)** | void |  |
| **UpdateItem(ClientRuntimeContext context, FavoriteListHomeItem pinnedItem)** | void |  |
# PivotItem Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Audiences** | string[] |  |
| **Name** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# Placeholder Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **DataType** | string |  |
| **EndPosition** | int |  |
| **Id** | string |  |
| **Name** | string |  |
| **ParagraphId** | string |  |
| **QuestionTitle** | string |  |
| **Source** | string |  |
| **StartPosition** | int |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# PlaceholderV2 Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AdditionalFieldsData** | string |  |
| **DataType** | string |  |
| **Id** | string |  |
| **Name** | string |  |
| **QuestionTitle** | string |  |
| **Source** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
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
# PortalAndOrgNewsSiteReference Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **SiteId** | Guid |  |
| **WebId** | Guid |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
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
# ProvisionedMigrationContainersInfo Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **DataContainerUri** | string |  |
| **EncryptionKey** | byte[] |  |
| **MetadataContainerUri** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# ProvisionedMigrationQueueInfo Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **JobQueueUri** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# ProvisionedTemporaryAzureContainerInfo Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **EncryptionKey** | byte[] |  |
| **Uri** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
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
# QuickAccessItemCollection Class

Namespace: Microsoft.SharePoint.Client


## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetQuickAccessItems(ClientRuntimeContext context)** | ClientResult\<string\> |  |
| **GetSubstrateQuickAccessItems(ClientRuntimeContext context)** | ClientResult\<string\> |  |
# QuickLaunchOptions Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Off** |  |
| **On** |  |
| **DefaultValue** |  |
# RecentFileCollection Class

Namespace: Microsoft.SharePoint.Client


## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetRecentFiles(ClientRuntimeContext context)** | ClientResult\<string\> |  |
# RecentList Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **color** | string |  |
| **createdByName** | string |  |
| **createdByUpn** | string |  |
| **createdDate** | string |  |
| **icon** | string |  |
| **lastModifiedDate** | string |  |
| **lastViewDate** | int |  |
| **lastviewDateTime** | string |  |
| **listId** | string |  |
| **listTitle** | string |  |
| **listUrl** | string |  |
| **listViewCounts** | IEnumerable\<[CountByDate](#countbydate-class)\> |  |
| **shouldRemove** | bool |  |
| **siteColor** | string |  |
| **siteId** | string |  |
| **siteTitle** | string |  |
| **siteUrl** | string |  |
| **templateTypeId** | string |  |
| **webId** | string |  |
| **webTemplateConfiguration** | string |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **RecentList(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# RecentListCollection Class

Namespace: Microsoft.SharePoint.Client


## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetRecentLists(ClientRuntimeContext context, int sortBy, string templateTypeId)** | ClientObjectList\<[RecentList](#recentlist-class)\> |  |
| **GetRecentListsWithPageContextInfo(ClientRuntimeContext context, int sortBy, string templateTypeId)** | ClientResult\<Stream\> |  |
| **UpdateRecentLists(ClientRuntimeContext context, string recentListsJson)** | void |  |
| **UpdateRecentListsRemote(ClientRuntimeContext context, string recentListsJson)** | void |  |
# RecentListPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **color** | string |  |
| **createdByName** | string |  |
| **createdByUpn** | string |  |
| **createdDate** | string |  |
| **icon** | string |  |
| **lastModifiedDate** | string |  |
| **lastViewDate** | string |  |
| **lastviewDateTime** | string |  |
| **listId** | string |  |
| **listTitle** | string |  |
| **listUrl** | string |  |
| **listViewCounts** | string |  |
| **shouldRemove** | string |  |
| **siteColor** | string |  |
| **siteId** | string |  |
| **siteTitle** | string |  |
| **siteUrl** | string |  |
| **templateTypeId** | string |  |
| **webId** | string |  |
| **webTemplateConfiguration** | string |  |
# RecentListProxy Class

Namespace: Microsoft.SharePoint.Client


## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetRecentListsProxy(ClientRuntimeContext context, int sortBy, string templateTypeId)** | ClientResult\<Stream\> |  |
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
| **DirNamePath** | [ResourcePath](#resourcepath-class) |  |
| **Id** | Guid |  |
| **ItemState** | [RecycleBinItemState](#recyclebinitemstate-enum) |  |
| **ItemType** | [RecycleBinItemType](#recyclebinitemtype-enum) |  |
| **LeafName** | string |  |
| **LeafNamePath** | [ResourcePath](#resourcepath-class) |  |
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
| **DirNamePath** | string |  |
| **Id** | string |  |
| **ItemState** | string |  |
| **ItemType** | string |  |
| **LeafName** | string |  |
| **LeafNamePath** | string |  |
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
# RecycleBinQueryInformation Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **IsAscending** | bool |  |
| **ItemState** | [RecycleBinItemState](#recyclebinitemstate-enum) |  |
| **OrderBy** | [RecycleBinOrderBy](#recyclebinorderby-enum) |  |
| **PagingInfo** | string |  |
| **RowLimit** | int |  |
| **ShowOnlyMyItems** | bool |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
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
| **InstalledLanguages** | [LanguageCollection](#languagecollection-class) |  |
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
| **InstalledLanguages** | string |  |
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
| **RemoteWeb(ClientRuntimeContext context, string requestUrl)** |  |
| **RemoteWeb(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetFileByServerRelativePath(ResourcePath serverRelatvieFilePath)** | [File](#file-class) |  |
| **GetFileByServerRelativeUrl(string serverRelativeFileUrl)** | [File](#file-class) |  |
| **GetFileByUrl(string fileUrl)** | [File](#file-class) |  |
| **GetFolderByServerRelativeUrl(string serverRelativeUrl)** | [Folder](#folder-class) |  |
| **GetGroupById(int groupId)** | [Group](#group-class) |  |
| **GetListById(Guid listGuid)** | [List](#list-class) |  |
| **GetListByServerRelativeUrl(string serverRelativeUrl)** | [List](#list-class) |  |
# RemoteWebObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Web** | string |  |
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
| **ViewMetadata** |  |
| **DisableAutoHyperlink** |  |
| **EnableMediaTAUrls** |  |
| **ParentInfo** |  |
| **PageContextInfo** |  |
| **ClientSideComponentManifest** |  |
| **ListAvailableContentTypes** |  |
| **FolderContentTypeOrder** |  |
| **GridInitInfo** |  |
| **SiteUrlAsMediaTASPItemHost** |  |
| **AddToOneDrive** |  |
| **SPFXCustomActions** |  |
| **CustomActions** |  |
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
| **OverrideRowLimit** | string |  |
| **OverrideScope** | string |  |
| **OverrideSelectCommand** | string |  |
| **PageFirstRow** | string |  |
| **PageLastRow** | string |  |
| **QueryParams** | IDictionary\<string, string\> |  |
| **RootFolder** | string |  |
| **RootFolderUniqueId** | string |  |
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
| **ViewPath** | string |  |
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
| **AddAllFields** | bool |  |
| **AddAllViewFields** | bool |  |
| **AddRegionalSettings** | bool |  |
| **AddRequiredFields** | bool |  |
| **AllowMultipleValueFilterForTaxonomyFields** | bool |  |
| **AudienceTarget** | bool |  |
| **DatesInUtc** | bool |  |
| **ExpandGroups** | bool |  |
| **ExpandUserField** | bool |  |
| **FilterOutChannelFoldersInDefaultDocLib** | bool |  |
| **FirstGroupOnly** | bool |  |
| **FolderServerRelativeUrl** | string |  |
| **ImageFieldsToTryRewriteToCdnUrls** | string |  |
| **MergeDefaultView** | bool |  |
| **ModernListBoot** | bool |  |
| **OriginalDate** | bool |  |
| **OverrideViewXml** | string |  |
| **Paging** | string |  |
| **RenderOptions** | [RenderListDataOptions](#renderlistdataoptions-enum) |  |
| **RenderURLFieldInJSON** | bool |  |
| **ReplaceGroup** | bool |  |
| **ShowStubFile** | bool |  |
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
| **ExcludeFieldFilteringHtml** | bool |  |
| **FieldInternalName** | string |  |
| **OverrideScope** | string |  |
| **ProcessQStringToCAML** | string |  |
| **ViewId** | string |  |
| **ViewXml** | string |  |
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
| **IncludeAppendOnlyData** |  |
| **ListSchemaGroupedByContentType** |  |
| **IncludeSiteAssetsThumbnailMetadata** |  |
# ReportResponse Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **dimensions** | IList\<[VinciAnalyticsReportTableElement](#vincianalyticsreporttableelement-class)\> |  |
| **metrics** | IList\<[VinciAnalyticsReportTableElement](#vincianalyticsreporttableelement-class)\> |  |
| **rows** | [VinciAnalyticsReportTableRow](#vincianalyticsreporttablerow-class)[] |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
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
# RequestType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **GET** |  |
| **POST** |  |
| **PUT** |  |
| **DELETE** |  |
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
# ResourcePath Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **DecodedUrl** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **FromDecodedUrl(string decodedUrl)** | [ResourcePath](#resourcepath-class) |  |
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
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
| **Reviewer** |  |
| **RestrictedReader** |  |
| **RestrictedGuest** |  |
| **System** |  |
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
# ScriptSafeDomain Class

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
| **ScriptSafeDomain(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
# ScriptSafeDomainEntityData Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **DomainName** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# ScriptSafeExternalEmbedding Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **AllowedDomains** |  |
| **All** |  |
# ScriptTypeFactory Class

Namespace: Microsoft.SharePoint.Client


## Methods

| Name | Returns | Summary |
|---|---|---|
| **CreateObjectFromScriptType(string scriptType, ClientRuntimeContext context)** | IFromJson |  |
# SearchBoxInNavBarType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Inherit** |  |
| **AllPages** |  |
| **ModernOnly** |  |
| **Hidden** |  |
# SearchScopeType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **DefaultScope** |  |
| **Tenant** |  |
| **Hub** |  |
| **Site** |  |
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
# SensitivityLabelInfo Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **DisplayName** | string |  |
| **Id** | string |  |
| **MembersCanShare** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SensitivityLabelWorkItemType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **InteractiveAutolabel** |  |
| **NonInteractiveAutolabel** |  |
# ServerSettings Class

Namespace: Microsoft.SharePoint.Client


## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetAlternateUrls(ClientRuntimeContext context)** | ClientObjectList\<[AlternateUrl](#alternateurl-class)\> |  |
| **GetGlobalInstalledLanguages(ClientRuntimeContext context, int compatibilityLevel)** | ClientResult\<[Language](#language-class)[]\> |  |
| **IsSharePointOnline(ClientRuntimeContext context)** | ClientResult\<bool\> |  |
# SharedWithMeItemCollection Class

Namespace: Microsoft.SharePoint.Client


## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetSharedWithMeItems(ClientRuntimeContext context, int top, string skiptoken, bool includeSharingHistory)** | ClientResult\<string\> |  |
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
# SharingLinkData Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **BlocksDownload** | bool |  |
| **Description** | string |  |
| **Embeddable** | bool |  |
| **Expiration** | string |  |
| **HasExternalGuestInvitees** | bool |  |
| **IsAnonymous** | bool |  |
| **IsCreateOnlyLink** | bool |  |
| **IsFormsLink** | bool |  |
| **IsManageListLink** | bool |  |
| **IsOriginatedFromSharingFlow** | bool |  |
| **IsReviewLink** | bool |  |
| **IsSharingLink** | bool |  |
| **IsWritable** | bool |  |
| **LinkKind** | [SharingLinkKind](#sharinglinkkind-enum) |  |
| **ObjectType** | [SharedObjectType](#sharedobjecttype-enum) |  |
| **ObjectUniqueId** | Guid |  |
| **RequiresPassword** | bool |  |
| **RestrictedShareMembership** | bool |  |
| **ShareId** | Guid |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SharingLinkInfo Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AllowsAnonymousAccess** | bool |  |
| **ApplicationId** | string |  |
| **BlocksDownload** | bool |  |
| **Created** | string |  |
| **Description** | string |  |
| **Embeddable** | bool |  |
| **Expiration** | string |  |
| **HasExternalGuestInvitees** | bool |  |
| **IsActive** | bool |  |
| **IsAddressBarLink** | bool |  |
| **IsCreateOnlyLink** | bool |  |
| **IsDefault** | bool |  |
| **IsEditLink** | bool |  |
| **IsFormsLink** | bool |  |
| **IsManageListLink** | bool |  |
| **IsReviewLink** | bool |  |
| **IsUnhealthy** | bool |  |
| **LastModified** | string |  |
| **LimitUseToApplication** | bool |  |
| **LinkKind** | [SharingLinkKind](#sharinglinkkind-enum) |  |
| **PasswordLastModified** | string |  |
| **RequiresPassword** | bool |  |
| **RestrictedShareMembership** | bool |  |
| **Scope** | [SharingScope](#sharingscope-enum) |  |
| **ShareId** | Guid |  |
| **ShareTokenString** | string |  |
| **SharingLinkStatus** | [SharingLinkStatus](#sharinglinkstatus-enum) |  |
| **TrackLinkUsers** | bool |  |
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
| **Flexible** |  |
# SharingLinkStatus Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Uninitialized** |  |
| **Created** |  |
| **Updated** |  |
# SharingOperationStatusCode Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **CompletedSuccessfully** |  |
| **AccessRequestsQueued** |  |
| **ParentListIsNull** |  |
| **NavParameterIsNotBase64UrlEncoded** |  |
| **NavParameterExceedsLengthLimit** |  |
| **ObjectLocked** |  |
| **NumUsersOverlimit** |  |
| **NumInvitationsOverlimit** |  |
| **ExternalInviteeNotAllowedForFluidComponent** |  |
| **SharingWebBlockedForChannelSite** |  |
| **MembersCannotShareNonListItem** |  |
| **InvalidPermissionLevel** |  |
| **SharingToBlockedUserOnODB** |  |
| **SharingToUnresolvedEntity** |  |
| **SharingToInvalidEmail** |  |
| **SharingToBlockedDomain** |  |
| **SharingAnonymousLink** |  |
| **ClaimNotAllowed** |  |
| **InvitationNotSent** |  |
| **UpdateSPShareFailed** |  |
| **SharingBlockedByVirusCheckStatus** |  |
| **SharingBlockedBySiteIBMode** |  |
| **StubFileSharingNotAllowed** |  |
| **AnyoneLinkDisabledForFileType** |  |
| **ExternalInvitationFailedUnexpected** |  |
| **AnonymousLinkDisallowedFileType** |  |
| **WebNotShareableByLink** |  |
| **ListNotShareableByLink** |  |
| **WebNotFound** |  |
| **ListNotFound** |  |
| **AnonymousLinkBlockedBySiteIB** |  |
| **AddressBarLinkNotUpdateable** |  |
| **LimitedAccessLockdownModeEnabled** |  |
| **DuplicateValuesInSharingList** |  |
| **ExternalInvitationFailed** |  |
| **UserIsInBlockedSecurityGroupForODB** |  |
| **SecurableNotFound** |  |
| **ExternalInviteeNotAllowed** |  |
| **ShareDoesNotExist** |  |
| **UserBlockedByWhoCanShareSettings** |  |
| **AnonymousEditLinkNotAllowedByTenant** |  |
| **DocumentIsProtectedByDLP** |  |
| **AccessDeniedNotEnoughPermissions** |  |
| **AccessDeniedToAnonGuest** |  |
| **ObjectNotShareableByLink** |  |
| **RoledefinitionNotFound** |  |
| **NonClaimsWebapp** |  |
| **IRMIsEnabled** |  |
| **DocLibIsCatalog** |  |
| **ParentListIsPrivate** |  |
| **ListItemNotFound** |  |
| **NotSupportedByWOPI** |  |
| **ShareByLinkDisabled** |  |
| **ForceCheckoutEditLink** |  |
| **FileNotFound** |  |
| **RequestThrottled** |  |
| **MountPointSharingNotAllowed** |  |
| **InvalidObjectStatus** |  |
| **SharingBufferExceeded** |  |
| **OperationCancelled** |  |
| **TooManyChildItemsWithUniqueScopes** |  |
| **UserDoesNotExist** |  |
| **InvalidValue** |  |
| **QuotaExceeded** |  |
| **NestedGroupsNotSupported** |  |
| **ObjectNotSupported** |  |
| **CapabilityDisabled** |  |
| **ListUniqueScopesExceeded** |  |
| **EmailBodyTooLong** |  |
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
# SharingState Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Unspecified** |  |
| **On** |  |
| **Off** |  |
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
# ShowInFiltersPaneStatus Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Auto** |  |
| **Pinned** |  |
| **Removed** |  |
# Site Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AllowCreateDeclarativeWorkflow** | bool |  |
| **AllowDesigner** | bool |  |
| **AllowExternalEmbeddingWrapper** | [ScriptSafeExternalEmbedding](#scriptsafeexternalembedding-enum) |  |
| **AllowMasterPageEditing** | bool |  |
| **AllowRevertFromTemplate** | bool |  |
| **AllowSaveDeclarativeWorkflowAsTemplate** | bool |  |
| **AllowSavePublishDeclarativeWorkflow** | bool |  |
| **AllowSelfServiceUpgrade** | bool |  |
| **AllowSelfServiceUpgradeEvaluation** | bool |  |
| **Audit** | [Audit](#audit-class) |  |
| **AuditLogTrimmingRetention** | int |  |
| **CanSyncHubSitePermissions** | bool |  |
| **CanUpgrade** | bool |  |
| **ChannelGroupId** | Guid |  |
| **Classification** | string |  |
| **CommentsOnSitePagesDisabled** | bool |  |
| **CompatibilityLevel** | int |  |
| **ComplianceAttribute** | string |  |
| **CurrentChangeToken** | [ChangeToken](#changetoken-class) |  |
| **CustomizedFormsPages** | [CustomizedFormsPageCollection](#customizedformspagecollection-class) |  |
| **CustomScriptSafeDomains** | [SPScriptSafeDomainsCollection](#spscriptsafedomainscollection-class) |  |
| **DisableAppViews** | bool |  |
| **DisableCompanyWideSharingLinks** | bool |  |
| **DisableFlows** | bool |  |
| **EventReceivers** | [EventReceiverDefinitionCollection](#eventreceiverdefinitioncollection-class) |  |
| **ExternalSharingTipsEnabled** | bool |  |
| **ExternalUserExpirationInDays** | int |  |
| **Features** | [FeatureCollection](#featurecollection-class) |  |
| **GeoLocation** | string |  |
| **GroupId** | Guid |  |
| **HubSiteId** | Guid |  |
| **HubSiteSynchronizableVisitorGroup** | [Group](#group-class) |  |
| **Id** | Guid |  |
| **SensitivityLabelId** | string |  |
| **SensitivityLabel** | Guid |  |
| **IsHubSite** | bool |  |
| **LockIssue** | string |  |
| **MaxItemsPerThrottledOperation** | uint |  |
| **MediaTranscriptionDisabled** | bool |  |
| **NeedsB2BUpgrade** | bool |  |
| **Owner** | [User](#user-class) |  |
| **ResourcePath** | [ResourcePath](#resourcepath-class) |  |
| **PrimaryUri** | string |  |
| **ReadOnly** | bool |  |
| **RecycleBin** | [RecycleBinItemCollection](#recyclebinitemcollection-class) |  |
| **RelatedGroupId** | Guid |  |
| **RequiredDesignerVersion** | string |  |
| **RootWeb** | [Web](#web-class) |  |
| **SandboxedCodeActivationCapability** | [SandboxedCodeActivationCapabilities](#sandboxedcodeactivationcapabilities-enum) |  |
| **SearchBoxInNavBar** | [SearchBoxInNavBarType](#searchboxinnavbartype-enum) |  |
| **SearchBoxPlaceholderText** | string |  |
| **SecondaryContact** | [User](#user-class) |  |
| **SensitivityLabelInfo** | [SensitivityLabelInfo](#sensitivitylabelinfo-class) |  |
| **ServerRelativePath** | [ResourcePath](#resourcepath-class) |  |
| **ServerRelativeUrl** | string |  |
| **ShareByEmailEnabled** | bool |  |
| **ShareByLinkEnabled** | bool |  |
| **ShowPeoplePickerSuggestionsForGuestUsers** | bool |  |
| **ShowUrlStructure** | bool |  |
| **SitePolicyEnabled** | bool |  |
| **SocialBarOnSitePagesDisabled** | bool |  |
| **StatusBarLink** | string |  |
| **StatusBarText** | string |  |
| **ThicketSupportDisabled** | bool |  |
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
| **WriteLocked** | bool |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
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
| **CreateCopyJob(string[] exportObjectUris, string destinationUri, CopyMigrationOptions options)** | ClientResult\<[CopyMigrationInfo](#copymigrationinfo-class)\> |  |
| **CreateCopyJobs(string[] exportObjectUris, string destinationUri, CopyMigrationOptions options)** | IList\<[CopyMigrationInfo](#copymigrationinfo-class)\> |  |
| **CreateMigrationIngestionJob(Guid gWebId, string azureContainerSourceUri, string azureContainerManifestUri, string azureQueueReportUri, IngestionTaskKey ingestionTaskKey)** | ClientResult\<Guid\> |  |
| **CreateMigrationJob(Guid gWebId, string azureContainerSourceUri, string azureContainerManifestUri, string azureQueueReportUri)** | ClientResult\<Guid\> |  |
| **CreateMigrationJobEncrypted(Guid gWebId, string azureContainerSourceUri, string azureContainerManifestUri, string azureQueueReportUri, EncryptionOption options)** | ClientResult\<Guid\> |  |
| **CreatePreviewSPSite(bool upgrade, bool sendemail)** | void |  |
| **CreateSPAsyncReadJob(string url, AsyncReadOptions readOptions, EncryptionOption encryptionOption, string azureContainerManifestUri, string azureQueueReportUri)** | ClientResult\<[AsyncReadJobInfo](#asyncreadjobinfo-class)\> |  |
| **CreateSPAsyncReadJobWithMultiUrl(string[] urls, AsyncReadOptions readOptions, EncryptionOption encryptionOption, string azureContainerManifestUri, string azureQueueReportUri)** | ClientResult\<[AsyncReadJobInfo](#asyncreadjobinfo-class)\> |  |
| **DeleteMigrationJob(Guid id)** | ClientResult\<bool\> |  |
| **EnqueueApplySensitivityLabelWork(AutoLabellingWorkInformation workItemInformation)** | ClientResult\<[EnqueueJobInformation](#enqueuejobinformation-class)\> |  |
| **Exists(ClientRuntimeContext context, string url)** | ClientResult\<bool\> |  |
| **ExtendUpgradeReminderDate()** | void |  |
| **GetBringYourOwnKeyRecoveryKeyMode()** | ClientResult\<[CustomerRecoveryKeyMode](#customerrecoverykeymode-enum)\> |  |
| **GetBringYourOwnKeySiteStatus()** | ClientResult\<[CustomerKeyStatusInfo](#customerkeystatusinfo-class)\> |  |
| **GetBringYourOwnKeyTenantStatus()** | ClientResult\<[CustomerKeyStatusInfo](#customerkeystatusinfo-class)\> |  |
| **GetCatalog(int typeCatalog)** | [List](#list-class) |  |
| **GetChanges(ChangeQuery query)** | [ChangeCollection](#changecollection-class) |  |
| **GetCopyJobProgress(CopyMigrationInfo copyJobInfo)** | ClientResult\<[CopyJobProgress](#copyjobprogress-class)\> |  |
| **GetCustomListTemplates(Web web)** | [ListTemplateCollection](#listtemplatecollection-class) |  |
| **GetMigrationJobStatus(Guid id)** | ClientResult\<[MigrationJobState](#migrationjobstate-enum)\> |  |
| **GetMigrationStatus()** | [SPMigrationJobStatusCollection](#spmigrationjobstatuscollection-class) |  |
| **GetRecycleBinItems(string pagingInfo, int rowLimit, bool isAscending, RecycleBinOrderBy orderBy, RecycleBinItemState itemState)** | [RecycleBinItemCollection](#recyclebinitemcollection-class) |  |
| **GetUrlById(ClientRuntimeContext context, Guid id, bool stopRedirect)** | ClientResult\<string\> |  |
| **GetUrlByIdForWeb(ClientRuntimeContext context, Guid id, bool stopRedirect, Guid webId)** | ClientResult\<string\> |  |
| **GetWebPath(Guid siteId, Guid webId)** | ClientResult\<[ResourcePath](#resourcepath-class)\> |  |
| **GetWebTemplates(uint LCID, int overrideCompatLevel)** | [WebTemplateCollection](#webtemplatecollection-class) |  |
| **Invalidate()** | void |  |
| **NeedsUpgradeByType(bool versionUpgrade, bool recursive)** | ClientResult\<bool\> |  |
| **OnboardTenantForBringYourOwnKey(CustomerKeyInfo keyInfo)** | ClientResult\<[CustomerKeyStatusInfo](#customerkeystatusinfo-class)\> |  |
| **OpenWeb(string strUrl)** | [Web](#web-class) |  |
| **OpenWebById(Guid gWebId)** | [Web](#web-class) |  |
| **OpenWebUsingPath(ResourcePath path)** | [Web](#web-class) |  |
| **ProvisionMigrationContainers()** | ClientResult\<[ProvisionedMigrationContainersInfo](#provisionedmigrationcontainersinfo-class)\> |  |
| **ProvisionMigrationQueue()** | ClientResult\<[ProvisionedMigrationQueueInfo](#provisionedmigrationqueueinfo-class)\> |  |
| **ProvisionTemporaryAzureContainer()** | ClientResult\<[ProvisionedTemporaryAzureContainerInfo](#provisionedtemporaryazurecontainerinfo-class)\> |  |
| **RecoverTenantForBringYourOwnKey(CustomerKeyInfo keyInfo)** | ClientResult\<[CustomerKeyStatusInfo](#customerkeystatusinfo-class)\> |  |
| **RollTenantBringYourOwnKey(CustomerKeyVaultKeyType keyType, CustomerKeyVaultInfo keyVaultInfo)** | ClientResult\<[CustomerKeyStatusInfo](#customerkeystatusinfo-class)\> |  |
| **RunHealthCheck(Guid ruleId, bool bRepair, bool bRunAlways)** | [SiteHealthSummary](#sitehealthsummary-class) |  |
| **RunUpgradeSiteSession(bool versionUpgrade, bool queueOnly, bool sendEmail)** | void |  |
| **SetIsContributorOwnerEnabledPropertyForDefaultDocLib(bool propertyValue, bool forceDocLibActivation, bool deleteIfDocLibAlreadyExists)** | ClientResult\<bool\> |  |
| **UpdateClientObjectModelUseRemoteAPIsPermissionSetting(bool requireUseRemoteAPIs)** | void |  |
# SiteArchiveFlags Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **SingleSidedArchive** |  |
| **BlockAccess** |  |
# SiteObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Audit** | string |  |
| **CustomScriptSafeDomains** | string |  |
| **EventReceivers** | string |  |
| **Features** | string |  |
| **HubSiteSynchronizableVisitorGroup** | string |  |
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
| **AllowExternalEmbeddingWrapper** | string |  |
| **AllowMasterPageEditing** | string |  |
| **AllowRevertFromTemplate** | string |  |
| **AllowSaveDeclarativeWorkflowAsTemplate** | string |  |
| **AllowSavePublishDeclarativeWorkflow** | string |  |
| **AllowSelfServiceUpgrade** | string |  |
| **AllowSelfServiceUpgradeEvaluation** | string |  |
| **AuditLogTrimmingRetention** | string |  |
| **CanSyncHubSitePermissions** | string |  |
| **CanUpgrade** | string |  |
| **ChannelGroupId** | string |  |
| **Classification** | string |  |
| **CommentsOnSitePagesDisabled** | string |  |
| **CompatibilityLevel** | string |  |
| **ComplianceAttribute** | string |  |
| **CurrentChangeToken** | string |  |
| **CustomizedFormsPages** | string |  |
| **DisableAppViews** | string |  |
| **DisableCompanyWideSharingLinks** | string |  |
| **DisableFlows** | string |  |
| **ExternalSharingTipsEnabled** | string |  |
| **ExternalUserExpirationInDays** | string |  |
| **GeoLocation** | string |  |
| **GroupId** | string |  |
| **HubSiteId** | string |  |
| **Id** | string |  |
| **SensitivityLabelId** | string |  |
| **SensitivityLabel** | string |  |
| **IsHubSite** | string |  |
| **LockIssue** | string |  |
| **MaxItemsPerThrottledOperation** | string |  |
| **MediaTranscriptionDisabled** | string |  |
| **NeedsB2BUpgrade** | string |  |
| **ResourcePath** | string |  |
| **PrimaryUri** | string |  |
| **ReadOnly** | string |  |
| **RelatedGroupId** | string |  |
| **RequiredDesignerVersion** | string |  |
| **SandboxedCodeActivationCapability** | string |  |
| **SearchBoxInNavBar** | string |  |
| **SearchBoxPlaceholderText** | string |  |
| **SensitivityLabelInfo** | string |  |
| **ServerRelativePath** | string |  |
| **ServerRelativeUrl** | string |  |
| **ShareByEmailEnabled** | string |  |
| **ShareByLinkEnabled** | string |  |
| **ShowPeoplePickerSuggestionsForGuestUsers** | string |  |
| **ShowUrlStructure** | string |  |
| **SitePolicyEnabled** | string |  |
| **SocialBarOnSitePagesDisabled** | string |  |
| **StatusBarLink** | string |  |
| **StatusBarText** | string |  |
| **ThicketSupportDisabled** | string |  |
| **TrimAuditLog** | string |  |
| **UIVersionConfigurationEnabled** | string |  |
| **UpgradeInfo** | string |  |
| **UpgradeReminderDate** | string |  |
| **UpgradeScheduled** | string |  |
| **UpgradeScheduledDate** | string |  |
| **Upgrading** | string |  |
| **Url** | string |  |
| **Usage** | string |  |
| **WriteLocked** | string |  |
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
# SmartCache Class

Namespace: Microsoft.SharePoint.Client


## Methods

| Name | Returns | Summary |
|---|---|---|
| **Update(ClientRuntimeContext context, string smartCacheJson)** | void |  |
# SmartTemplateContentType Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Id** | string |  |
| **Name** | string |  |
| **PublishStatus** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SPAIPLabelExtractionStatus Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **Extracted** |  |
| **NotExtracted** |  |
| **Error** |  |
# SPChangeActivityType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **NoActivity** |  |
| **Hashtag** |  |
| **Spotlight** |  |
| **Comment** |  |
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
| **Desktop** |  |
| **Documents** |  |
| **ScreenShots** |  |
| **Templates** |  |
| **OfficeScripts** |  |
| **Recordings** |  |
| **Meetings** |  |
| **Storyline** |  |
| **Downloads** |  |
| **Videos** |  |
| **Playlists** |  |
| **Remix** |  |
| **SavedPictures** |  |
| **CameraImports** |  |
| **SamsungGallery** |  |
| **SDCard** |  |
| **SamsungCloudDrive** |  |
# SPEffectiveInformationRightsManagementSettingsSource Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **File** |  |
| **List** |  |
| **Rule** |  |
# SPHSite Class

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
| **SPHSite(ClientRuntimeContext context)** |  |
| **SPHSite(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **AddOrgNewsSite(ClientRuntimeContext context, string siteUrl)** | ClientResult\<Guid\> |  |
| **AddSPHomeNavNode(ClientRuntimeContext context, Guid siteId)** | ClientResult\<bool\> |  |
| **GetSiteReferenceXgeo(ClientRuntimeContext context, string siteUrl)** | ClientResult\<[PortalAndOrgNewsSiteReference](#portalandorgnewssitereference-class)\> |  |
| **GetSiteTitleXgeo(ClientRuntimeContext context, string siteUrl)** | ClientResult\<string\> |  |
| **GetSPHSiteXGeo(ClientRuntimeContext context)** | ClientResult\<[SPHSiteReference](#sphsitereference-class)\> |  |
| **GetXgeoHomeSiteDetail(ClientRuntimeContext context, Guid siteId, string siteUrl)** | ClientResult\<[HomeSitesDetails](#homesitesdetails-class)\> |  |
| **IsCommSite(ClientRuntimeContext context, string siteUrl)** | ClientResult\<bool\> |  |
| **IsModernSiteWithHorizontalNav(ClientRuntimeContext context, string siteUrl)** | ClientResult\<bool\> |  |
| **IsValidHomeSite(ClientRuntimeContext context, string siteUrl)** | ClientResult\<bool\> |  |
| **SetSPHSite(string siteUrl)** | ClientResult\<Guid\> |  |
| **ValidateHomeSite(ClientRuntimeContext context, ValidationActionType validationActionType, string siteUrl)** | void |  |
# SPHSiteReference Class

Namespace: Microsoft.SharePoint.Client

Base class: [PortalAndOrgNewsSiteReference](#portalandorgnewssitereference-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **LogoUrl** | string |  |
| **Title** | string |  |
| **Url** | string |  |
| **TypeId** | string |  |
| **SiteId** | Guid |  |
| **WebId** | Guid |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SPImageItem Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Name** | string |  |
| **ServerRelativeUrl** | string |  |
| **UniqueId** | Guid |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
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
# SPListRule Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ActionType** | int |  |
| **Condition** | string |  |
| **CreateDate** | DateTime |  |
| **ID** | Guid |  |
| **IsActive** | bool |  |
| **LastModifiedDate** | DateTime |  |
| **Outcome** | string |  |
| **Owner** | string |  |
| **RuleTemplateId** | Guid |  |
| **TargetLibraryUrl** | string |  |
| **Title** | string |  |
| **TriggerType** | int |  |
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
# SPMoveAndShareFileInfo Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ItemPermissionableUserIds** | IList\<int\> |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SPNavigationFlags Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **OpenInNewWindow** |  |
| **IsOpenInNewWindowSet** |  |
# SPOpenBinaryOptions Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **MinimizeProcessing** |  |
| **Unprotected** |  |
| **SkipVirusScan** |  |
| **GetAsZipWithAltStreamsIfAvailable** |  |
| **ForceAVScanIfPreviouslyUnscanned** |  |
| **GetAsZipStreamBundleFriendly** |  |
| **SkipDisallowInfectedFileDownloadCheck** |  |
# SPResourceEntry Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **LCID** | int |  |
| **Value** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SPResourceLCIDSource Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Invalid** |  |
| **Web** |  |
| **User** |  |
# SPRuleAction Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ActionParams** | IDictionary\<string, string\> |  |
| **ActionType** | int |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SPScriptSafeDomainsCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObjectCollection<[ScriptSafeDomain](#scriptsafedomain-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [ScriptSafeDomain](#scriptsafedomain-class) |  |
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
| **SPScriptSafeDomainsCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Create(ScriptSafeDomainEntityData parameters)** | [ScriptSafeDomain](#scriptsafedomain-class) |  |
| **GetByDomainName(string domainName)** | [ScriptSafeDomain](#scriptsafedomain-class) |  |
# SPSensivityLabelAssignmentMethod Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **Standard** |  |
| **Privileged** |  |
| **Auto** |  |
# SPTeamsChannelType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **PrivateChannel** |  |
| **SharedChannel** |  |
| **StandardChannel** |  |
# SPVariantThemeType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **Neutral** |  |
| **Soft** |  |
| **Strong** |  |
# SPVirusCheckStatus Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Clean** |  |
| **Infected** |  |
| **InfectedCleanable** |  |
| **Cleaned** |  |
| **CleanFailed** |  |
| **Deleted** |  |
| **Timeout** |  |
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
# TeamChannel Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **folderId** | Guid |  |
| **groupId** | int |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **TeamChannel(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# TeamChannelManager Class

Namespace: Microsoft.SharePoint.Client


## Methods

| Name | Returns | Summary |
|---|---|---|
| **AddTeamChannel(ClientRuntimeContext context, ResourcePath parentFolderPath, ResourcePath newFolderPath, string teamChannelUrl, bool privateChannel, int privateChannelGroupOwner)** | [TeamChannel](#teamchannel-class) |  |
| **DemoteTeamChannelById(ClientRuntimeContext context, Guid folderId)** | ClientResult\<bool\> |  |
| **DemoteTeamChannelByPath(ClientRuntimeContext context, ResourcePath folderPath)** | ClientResult\<bool\> |  |
| **GetConversations(ClientRuntimeContext context, string listUrl, int listItemId)** | ClientResult\<string\> |  |
| **PromoteToTeamChannelById(ClientRuntimeContext context, Guid folderId, string teamChannelUrl, string channelName)** | ClientResult\<bool\> |  |
| **PromoteToTeamChannelByPath(ClientRuntimeContext context, ResourcePath folderPath, string teamChannelUrl, string channelName)** | ClientResult\<bool\> |  |
| **SaveConversations(ClientRuntimeContext context, string listUrl, int listItemId, string updatedConversationsObject)** | void |  |
# TeamChannelPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **folderId** | string |  |
| **groupId** | string |  |
# TeamSiteData Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ErrorTag** | uint |  |
| **HeaderEmphasis** | [SPVariantThemeType](#spvariantthemetype-enum) |  |
| **HubSiteId** | Guid |  |
| **SiteUrl** | string |  |
| **TenantInstanceId** | Guid |  |
| **ThemeToken** | string |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **TeamSiteData(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# TeamSiteDataPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **ErrorTag** | string |  |
| **HeaderEmphasis** | string |  |
| **HubSiteId** | string |  |
| **SiteUrl** | string |  |
| **TenantInstanceId** | string |  |
| **ThemeToken** | string |  |
# TemplateFileType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **StandardPage** |  |
| **WikiPage** |  |
| **FormPage** |  |
| **ClientSidePage** |  |
| **Invalid** |  |
# TemplateMetaData Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Placeholders** | IEnumerable\<[Placeholder](#placeholder-class)\> |  |
| **ServerRedirectedEmbedUrl** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# TemplatizationMetaData Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **FileInfo** | [ContentAssemblyFileInfo](#contentassemblyfileinfo-class) |  |
| **Placeholders** | IEnumerable\<[PlaceholderV2](#placeholderv2-class)\> |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# TemporaryFolderFileInfo Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **DummyFileUrl** | string |  |
| **ServerRedirectedEmbedUrl** | string |  |
| **TemporaryFileUrl** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
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
| **ClearCorporateCatalog()** | void |  |
| **GetCurrent(ClientRuntimeContext Context)** | [TenantSettings](#tenantsettings-class) |  |
| **SetCorporateCatalog(string url)** | void |  |
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
| **SetId(int id)** | void |  |
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
# UpdateTemplateInfo Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **NewName** | string |  |
| **Operation** | int |  |
| **Placeholders** | IEnumerable\<[Placeholder](#placeholder-class)\> |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# UpdateTemplateInfoV2 Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **NewName** | string |  |
| **Operation** | int |  |
| **Placeholders** | IEnumerable\<[PlaceholderV2](#placeholderv2-class)\> |  |
| **Url** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
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
# UrlTarget Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **NewWindow** |  |
| **CurrentWindow** |  |
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
| **AadObjectId** | [UserIdInfo](#useridinfo-class) |  |
| **Alerts** | [AlertCollection](#alertcollection-class) |  |
| **Email** | string |  |
| **EmailWithFallback** | string |  |
| **Expiration** | string |  |
| **Groups** | [GroupCollection](#groupcollection-class) |  |
| **IsEmailAuthenticationGuestUser** | bool |  |
| **IsShareByEmailGuestUser** | bool |  |
| **IsSiteAdmin** | bool |  |
| **UserId** | [UserIdInfo](#useridinfo-class) |  |
| **UserPrincipalName** | string |  |
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
| **Expire()** | void |  |
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
| **GetByObjectId(Guid objectId)** | [User](#user-class) |  |
| **GetByPuid(string puid)** | [User](#user-class) |  |
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
| **ClientSideComponentId** | Guid |  |
| **ClientSideComponentProperties** | string |  |
| **CommandUIExtension** | string |  |
| **Description** | string |  |
| **DescriptionResource** | [UserResource](#userresource-class) |  |
| **Group** | string |  |
| **HostProperties** | string |  |
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
| **ClientSideComponentId** | string |  |
| **ClientSideComponentProperties** | string |  |
| **CommandUIExtension** | string |  |
| **Description** | string |  |
| **Group** | string |  |
| **HostProperties** | string |  |
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
| **Alerts** | string |  |
| **Groups** | string |  |
# UserPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **AadObjectId** | string |  |
| **Email** | string |  |
| **EmailWithFallback** | string |  |
| **Expiration** | string |  |
| **IsEmailAuthenticationGuestUser** | string |  |
| **IsShareByEmailGuestUser** | string |  |
| **IsSiteAdmin** | string |  |
| **UserId** | string |  |
| **UserPrincipalName** | string |  |
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
| **GetResourceEntries()** | IList\<[SPResourceEntry](#spresourceentry-class)\> |  |
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
| **CanUsePeopleSharingReadonlyLink** |  |
| **CanManagePeopleSharingReadonlyLink** |  |
| **CanUsePeopleSharingReadWriteLink** |  |
| **CanManagePeopleSharingReadWriteLink** |  |
| **CanUseManageListLink** |  |
| **CanManageManageListLink** |  |
| **CanUseOrganizationManageListLink** |  |
| **CanManageOrganizationManageListLink** |  |
| **CanUsePeopleSharingManageListLink** |  |
| **CanManagePeopleSharingManageListLink** |  |
| **CanDeleteReadonlyLink** |  |
| **CanDeleteReadWriteLink** |  |
| **CanDeleteManageListLink** |  |
| **CanDeleteOrganizationReadonlyLink** |  |
| **CanDeleteOrganizationReadWriteLink** |  |
| **CanDeleteOrganizationManageListLink** |  |
| **CanDeletePeopleSharingReadonlyLink** |  |
| **CanDeletePeopleSharingReadWriteLink** |  |
| **CanDeletePeopleSharingManageListLink** |  |
# ValidationActionType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Add** |  |
| **Edit** |  |
# View Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Aggregations** | string |  |
| **AggregationsStatus** | string |  |
| **AssociatedContentTypeId** | string |  |
| **BaseViewId** | string |  |
| **CalendarViewStyles** | string |  |
| **ColumnWidth** | string |  |
| **ContentTypeId** | [ContentTypeId](#contenttypeid-class) |  |
| **CustomFormatter** | string |  |
| **CustomOrder** | string |  |
| **DefaultView** | bool |  |
| **DefaultViewForContentType** | bool |  |
| **EditorModified** | bool |  |
| **Formats** | string |  |
| **GridLayout** | string |  |
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
| **NewDocumentTemplates** | string |  |
| **OrderedView** | bool |  |
| **Paged** | bool |  |
| **PageRenderType** | [ListPageRenderType](#listpagerendertype-enum) |  |
| **PersonalView** | bool |  |
| **ViewProjectedFields** | string |  |
| **ViewQuery** | string |  |
| **ReadOnlyView** | bool |  |
| **RequiresClientIntegration** | bool |  |
| **RowLimit** | uint |  |
| **Scope** | [ViewScope](#viewscope-enum) |  |
| **ServerRelativePath** | [ResourcePath](#resourcepath-class) |  |
| **ServerRelativeUrl** | string |  |
| **StyleId** | string |  |
| **TabularView** | bool |  |
| **Threaded** | bool |  |
| **Title** | string |  |
| **Toolbar** | string |  |
| **ToolbarTemplateName** | string |  |
| **ViewType** | string |  |
| **ViewData** | string |  |
| **ViewFields** | [ViewFieldCollection](#viewfieldcollection-class) |  |
| **ViewType2** | string |  |
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
| **AssociatedContentTypeId** | string |  |
| **baseViewId** | int |  |
| **CalendarViewStyles** | string |  |
| **ColumnWidth** | string |  |
| **Paged** | bool |  |
| **PersonalView** | bool |  |
| **Query** | string |  |
| **RowLimit** | uint |  |
| **SetAsDefaultView** | bool |  |
| **Title** | string |  |
| **ViewData** | string |  |
| **ViewFields** | string[] |  |
| **ViewTypeKind** | [ViewType](#viewtype-enum) |  |
| **ViewType2** | string |  |
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
| **AssociatedContentTypeId** | string |  |
| **BaseViewId** | string |  |
| **CalendarViewStyles** | string |  |
| **ColumnWidth** | string |  |
| **ContentTypeId** | string |  |
| **CustomFormatter** | string |  |
| **CustomOrder** | string |  |
| **DefaultView** | string |  |
| **DefaultViewForContentType** | string |  |
| **EditorModified** | string |  |
| **Formats** | string |  |
| **GridLayout** | string |  |
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
| **NewDocumentTemplates** | string |  |
| **OrderedView** | string |  |
| **Paged** | string |  |
| **PageRenderType** | string |  |
| **PersonalView** | string |  |
| **ViewProjectedFields** | string |  |
| **ViewQuery** | string |  |
| **ReadOnlyView** | string |  |
| **RequiresClientIntegration** | string |  |
| **RowLimit** | string |  |
| **Scope** | string |  |
| **ServerRelativePath** | string |  |
| **ServerRelativeUrl** | string |  |
| **StyleId** | string |  |
| **TabularView** | string |  |
| **Threaded** | string |  |
| **Title** | string |  |
| **Toolbar** | string |  |
| **ToolbarTemplateName** | string |  |
| **ViewType** | string |  |
| **ViewData** | string |  |
| **ViewType2** | string |  |
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
# VinciAnalyticsDimensionsRequest Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **campaignId** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# VinciAnalyticsReportRequest Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **campaignId** | string |  |
| **communicationId** | string |  |
| **dimensions** | IList\<[VinciAnalyticsReportTableElement](#vincianalyticsreporttableelement-class)\> |  |
| **metrics** | IList\<[VinciAnalyticsReportTableElement](#vincianalyticsreporttableelement-class)\> |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# VinciAnalyticsReportTableElement Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **name** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# VinciAnalyticsReportTableRow Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **dimensionReport** | string |  |
| **metricReport** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# Visualization Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **DefaultScreen** | [VisualizationStyleSet](#visualizationstyleset-class) |  |
| **DetailView** | [VisualizationStyleSet](#visualizationstyleset-class) |  |
| **MediumScreen** | [VisualizationStyleSet](#visualizationstyleset-class) |  |
| **SmallScreen** | [VisualizationStyleSet](#visualizationstyleset-class) |  |
| **VisualizationAppInfo** | [VisualizationAppInfo](#visualizationappinfo-class) |  |
| **VisualizationType** | [VisualizationType](#visualizationtype-enum) |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# VisualizationAppInfo Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **DesignUri** | string |  |
| **Id** | Guid |  |
| **RuntimeUri** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# VisualizationAppMappedViewCollection Class

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
| **VisualizationAppMappedViewCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# VisualizationAppSynchronizationResult Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AppMappedViews** | [VisualizationAppMappedViewCollection](#visualizationappmappedviewcollection-class) |  |
| **SynchronizationData** | string |  |
| **SynchronizationStatus** | [VisualizationAppSynchronizationStatus](#visualizationappsynchronizationstatus-enum) |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **VisualizationAppSynchronizationResult(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# VisualizationAppSynchronizationResultObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **AppMappedViews** | string |  |
# VisualizationAppSynchronizationResultPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **SynchronizationData** | string |  |
| **SynchronizationStatus** | string |  |
# VisualizationAppSynchronizationStatus Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Success** |  |
| **NotFound** |  |
| **Forbidden** |  |
| **TimeOut** |  |
| **UnexpectedError** |  |
| **BadRequest** |  |
| **Suspended** |  |
| **JobFinish** |  |
# VisualizationAppTarget Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **RichClient** |  |
| **Browser** |  |
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
# VisualizationType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Standard** |  |
| **Custom** |  |
| **VisualizationApp** |  |
# VivaConnectionsUrlConfiguration Class

Namespace: Microsoft.SharePoint.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ContentUrl** | string |  |
| **DashboardNotConfiguredWarning** | string |  |
| **GlobalNavNotConfiguredWarning** | string |  |
| **NotHomeSiteUrlWarning** | string |  |
| **SearchUrl** | string |  |
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
| **AccessRequestListUrl** | string |  |
| **AccessRequestSiteDescription** | string |  |
| **Acronym** | string |  |
| **Alerts** | [AlertCollection](#alertcollection-class) |  |
| **AllowAutomaticASPXPageIndexing** | bool |  |
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
| **Author** | [User](#user-class) |  |
| **AvailableContentTypes** | [ContentTypeCollection](#contenttypecollection-class) |  |
| **AvailableFields** | [FieldCollection](#fieldcollection-class) |  |
| **CanModernizeHomepage** | [ModernizeHomepageResult](#modernizehomepageresult-class) |  |
| **ClassicWelcomePage** | string |  |
| **CommentsOnSitePagesDisabled** | bool |  |
| **Configuration** | short |  |
| **ContainsConfidentialInfo** | bool |  |
| **ContentTypes** | [ContentTypeCollection](#contenttypecollection-class) |  |
| **Created** | DateTime |  |
| **CurrentChangeToken** | [ChangeToken](#changetoken-class) |  |
| **CurrentUser** | [User](#user-class) |  |
| **CustomMasterUrl** | string |  |
| **CustomSiteActionsDisabled** | bool |  |
| **DataLeakagePreventionStatusInfo** | [SPDataLeakagePreventionStatusInfo](#spdataleakagepreventionstatusinfo-class) |  |
| **Description** | string |  |
| **DescriptionForExistingLanguage** | string |  |
| **DescriptionResource** | [UserResource](#userresource-class) |  |
| **DescriptionTranslations** | IEnumerable\<[SPResourceEntry](#spresourceentry-class)\> |  |
| **DesignerDownloadUrlForCurrentUser** | string |  |
| **DesignPackageId** | Guid |  |
| **DisableAppViews** | bool |  |
| **DisableFlows** | bool |  |
| **DisableRecommendedItems** | bool |  |
| **DocumentLibraryCalloutOfficeWebAppPreviewersDisabled** | bool |  |
| **EffectiveBasePermissions** | [BasePermissions](#basepermissions-class) |  |
| **EnableMinimalDownload** | bool |  |
| **EventReceivers** | [EventReceiverDefinitionCollection](#eventreceiverdefinitioncollection-class) |  |
| **ExcludeFromOfflineClient** | bool |  |
| **Features** | [FeatureCollection](#featurecollection-class) |  |
| **Fields** | [FieldCollection](#fieldcollection-class) |  |
| **Folders** | [FolderCollection](#foldercollection-class) |  |
| **FooterEmphasis** | [FooterVariantThemeType](#footervariantthemetype-enum) |  |
| **FooterEnabled** | bool |  |
| **FooterLayout** | [FooterLayoutType](#footerlayouttype-enum) |  |
| **HasWebTemplateExtension** | bool |  |
| **HeaderEmphasis** | [SPVariantThemeType](#spvariantthemetype-enum) |  |
| **HeaderLayout** | [HeaderLayoutType](#headerlayouttype-enum) |  |
| **HideTitleInHeader** | bool |  |
| **HorizontalQuickLaunch** | bool |  |
| **HostedApps** | [HostedAppsManager](#hostedappsmanager-class) |  |
| **Id** | Guid |  |
| **IsEduClass** | bool |  |
| **IsEduClassProvisionChecked** | bool |  |
| **IsEduClassProvisionPending** | bool |  |
| **IsHomepageModernized** | bool |  |
| **IsMultilingual** | bool |  |
| **IsProvisioningComplete** | bool |  |
| **IsRevertHomepageLinkHidden** | bool |  |
| **Language** | uint |  |
| **LastItemModifiedDate** | DateTime |  |
| **LastItemUserModifiedDate** | DateTime |  |
| **Lists** | [ListCollection](#listcollection-class) |  |
| **ListTemplates** | [ListTemplateCollection](#listtemplatecollection-class) |  |
| **LogoAlignment** | [LogoAlignment](#logoalignment-enum) |  |
| **MasterUrl** | string |  |
| **MegaMenuEnabled** | bool |  |
| **MembersCanShare** | bool |  |
| **NavAudienceTargetingEnabled** | bool |  |
| **Navigation** | [Navigation](#navigation-class) |  |
| **NextStepsFirstRunEnabled** | bool |  |
| **NoCrawl** | bool |  |
| **NotificationsInOneDriveForBusinessEnabled** | bool |  |
| **NotificationsInSharePointEnabled** | bool |  |
| **ObjectCacheEnabled** | bool |  |
| **OverwriteTranslationsOnChange** | bool |  |
| **ParentWeb** | [WebInformation](#webinformation-class) |  |
| **ResourcePath** | [ResourcePath](#resourcepath-class) |  |
| **PreviewFeaturesEnabled** | bool |  |
| **PrimaryColor** | string |  |
| **PushNotificationSubscribers** | [PushNotificationSubscriberCollection](#pushnotificationsubscribercollection-class) |  |
| **QuickLaunchEnabled** | bool |  |
| **RecycleBin** | [RecycleBinItemCollection](#recyclebinitemcollection-class) |  |
| **RecycleBinEnabled** | bool |  |
| **RegionalSettings** | [RegionalSettings](#regionalsettings-class) |  |
| **RequestAccessEmail** | string |  |
| **RoleDefinitions** | [RoleDefinitionCollection](#roledefinitioncollection-class) |  |
| **RootFolder** | [Folder](#folder-class) |  |
| **SaveSiteAsTemplateEnabled** | bool |  |
| **SearchBoxInNavBar** | [SearchBoxInNavBarType](#searchboxinnavbartype-enum) |  |
| **SearchBoxPlaceholderText** | string |  |
| **SearchScope** | [SearchScopeType](#searchscopetype-enum) |  |
| **ServerRelativePath** | [ResourcePath](#resourcepath-class) |  |
| **ServerRelativeUrl** | string |  |
| **ShowUrlStructureForCurrentUser** | bool |  |
| **SiteCollectionAppCatalog** | [SiteCollectionCorporateCatalogAccessor](#sitecollectioncorporatecatalogaccessor-class) |  |
| **SiteGroups** | [GroupCollection](#groupcollection-class) |  |
| **SiteLogoDescription** | string |  |
| **SiteLogoUrl** | string |  |
| **SiteUserInfoList** | [List](#list-class) |  |
| **SiteUsers** | [UserCollection](#usercollection-class) |  |
| **SupportedUILanguageIds** | IEnumerable\<int\> |  |
| **SyndicationEnabled** | bool |  |
| **TenantAdminMembersCanShare** | [SharingState](#sharingstate-enum) |  |
| **TenantAppCatalog** | [TenantCorporateCatalogAccessor](#tenantcorporatecatalogaccessor-class) |  |
| **TenantTagPolicyEnabled** | bool |  |
| **ThemedCssFolderUrl** | string |  |
| **ThemeInfo** | [ThemeInfo](#themeinfo-class) |  |
| **ThirdPartyMdmEnabled** | bool |  |
| **Title** | string |  |
| **TitleForExistingLanguage** | string |  |
| **TitleResource** | [UserResource](#userresource-class) |  |
| **TitleTranslations** | IEnumerable\<[SPResourceEntry](#spresourceentry-class)\> |  |
| **TreeViewEnabled** | bool |  |
| **UIVersion** | int |  |
| **UIVersionConfigurationEnabled** | bool |  |
| **Url** | string |  |
| **UseAccessRequestDefault** | bool |  |
| **UserCustomActions** | [UserCustomActionCollection](#usercustomactioncollection-class) |  |
| **Webs** | [WebCollection](#webcollection-class) |  |
| **WebTemplate** | string |  |
| **WebTemplateConfiguration** | string |  |
| **WebTemplatesGalleryFirstRunEnabled** | bool |  |
| **WelcomePage** | string |  |
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
| **AddPlaceholderUser(string listId, string placeholderText)** | ClientResult\<Guid\> |  |
| **AddSupportedUILanguage(int lcid)** | void |  |
| **ApplyTheme(string colorPaletteUrl, string fontSchemeUrl, string backgroundImageUrl, bool shareGenerated)** | void |  |
| **ApplyWebTemplate(string webTemplate)** | void |  |
| **CreateAnonymousLink(ClientRuntimeContext context, string url, bool isEditLink)** | ClientResult\<string\> |  |
| **CreateAnonymousLinkWithExpiration(ClientRuntimeContext context, string url, bool isEditLink, string expirationString)** | ClientResult\<string\> |  |
| **CreateDefaultAssociatedGroups(string userLogin, string userLogin2, string groupNameSeed)** | void |  |
| **CreateOrganizationSharingLink(ClientRuntimeContext context, string url, bool isEditLink)** | ClientResult\<string\> |  |
| **CreateSitePage(string pageMetaData)** | ClientResult\<string\> |  |
| **DefaultDocumentLibrary()** | [List](#list-class) |  |
| **DefaultDocumentLibraryUrl(ClientRuntimeContext context, string webUrl)** | ClientResult\<[DocumentLibraryInformation](#documentlibraryinformation-class)\> |  |
| **DeleteAllAnonymousLinksForObject(ClientRuntimeContext context, string url)** | void |  |
| **DeleteAnonymousLinkForObject(ClientRuntimeContext context, string url, bool isEditLink, bool removeAssociatedSharingLinkGroup)** | void |  |
| **DeleteObject()** | void |  |
| **DestroyOrganizationSharingLink(ClientRuntimeContext context, string url, bool isEditLink, bool removeAssociatedSharingLinkGroup)** | void |  |
| **DoesPushNotificationSubscriberExist(Guid deviceAppInstanceId)** | ClientResult\<bool\> |  |
| **DoesUserHavePermissions(BasePermissions permissionMask)** | ClientResult\<bool\> |  |
| **EnsureTenantAppCatalog(string callerId)** | ClientResult\<bool\> |  |
| **EnsureUser(string logonName)** | [User](#user-class) |  |
| **EnsureUserByObjectId(Guid objectId, Guid tenantId, PrincipalType principalType)** | [User](#user-class) |  |
| **ForwardObjectLink(ClientRuntimeContext context, string url, string peoplePickerInput, string emailSubject, string emailBody)** | [SharingResult](#sharingresult-class) |  |
| **GetAppBdcCatalog()** | [AppBdcCatalog](#appbdccatalog-class) |  |
| **GetAppBdcCatalogForAppInstance(Guid appInstanceId)** | [AppBdcCatalog](#appbdccatalog-class) |  |
| **GetAppInstanceById(Guid appInstanceId)** | [AppInstance](#appinstance-class) |  |
| **GetAppInstancesByProductId(Guid productId)** | ClientObjectList\<[AppInstance](#appinstance-class)\> |  |
| **GetAvailableWebTemplates(uint lcid, bool doIncludeCrossLanguage)** | [WebTemplateCollection](#webtemplatecollection-class) |  |
| **GetCatalog(int typeCatalog)** | [List](#list-class) |  |
| **GetChanges(ChangeQuery query)** | [ChangeCollection](#changecollection-class) |  |
| **GetDocumentAndMediaLibraries(ClientRuntimeContext context, string webFullUrl, bool includePageLibraries)** | IList\<[DocumentLibraryInformation](#documentlibraryinformation-class)\> |  |
| **GetDocumentLibraries(ClientRuntimeContext context, string webFullUrl)** | IList\<[DocumentLibraryInformation](#documentlibraryinformation-class)\> |  |
| **GetEntity(string namespace, string name)** | [Entity](#entity-class) |  |
| **GetFileByGuestUrl(string guestUrl)** | [File](#file-class) |  |
| **GetFileByGuestUrlEnsureAccess(string guestUrl, bool ensureAccess)** | [File](#file-class) |  |
| **GetFileById(Guid uniqueId)** | [File](#file-class) |  |
| **GetFileByLinkingUrl(string linkingUrl)** | [File](#file-class) |  |
| **GetFileByServerRelativePath(ResourcePath serverRelativePath)** | [File](#file-class) |  |
| **GetFileByServerRelativeUrl(string serverRelativeUrl)** | [File](#file-class) |  |
| **GetFileByUrl(string fileUrl)** | [File](#file-class) |  |
| **GetFileByWOPIFrameUrl(string wopiFrameUrl)** | [File](#file-class) |  |
| **GetFolderById(Guid uniqueId)** | [Folder](#folder-class) |  |
| **GetFolderByServerRelativePath(ResourcePath serverRelativePath)** | [Folder](#folder-class) |  |
| **GetFolderByServerRelativeUrl(string serverRelativeUrl)** | [Folder](#folder-class) |  |
| **GetList(string strUrl)** | [List](#list-class) |  |
| **GetListItem(string strUrl)** | [ListItem](#listitem-class) |  |
| **GetListItemByResourceId(string resourceId)** | [ListItem](#listitem-class) |  |
| **GetListItemUsingPath(ResourcePath path)** | [ListItem](#listitem-class) |  |
| **GetLists(GetListsParameters getListsParams)** | [ListCollection](#listcollection-class) |  |
| **GetListUsingPath(ResourcePath path)** | [List](#list-class) |  |
| **GetObjectSharingSettings(ClientRuntimeContext context, string objectUrl, int groupId, bool useSimplifiedRoles)** | [ObjectSharingSettings](#objectsharingsettings-class) |  |
| **GetPushNotificationSubscriber(Guid deviceAppInstanceId)** | [PushNotificationSubscriber](#pushnotificationsubscriber-class) |  |
| **GetPushNotificationSubscribersByArgs(string customArgs)** | [PushNotificationSubscriberCollection](#pushnotificationsubscribercollection-class) |  |
| **GetPushNotificationSubscribersByUser(string userName)** | [PushNotificationSubscriberCollection](#pushnotificationsubscribercollection-class) |  |
| **GetRecycleBinItems(string pagingInfo, int rowLimit, bool isAscending, RecycleBinOrderBy orderBy, RecycleBinItemState itemState)** | [RecycleBinItemCollection](#recyclebinitemcollection-class) |  |
| **GetRecycleBinItemsByQueryInfo(RecycleBinQueryInformation queryInfo)** | [RecycleBinItemCollection](#recyclebinitemcollection-class) |  |
| **GetSharingLinkData(string linkUrl)** | ClientResult\<[SharingLinkData](#sharinglinkdata-class)\> |  |
| **GetSharingLinkKind(ClientRuntimeContext context, string fileUrl)** | ClientResult\<[SharingLinkKind](#sharinglinkkind-enum)\> |  |
| **GetSiteUserIncludingDeletedByPuid(string puid)** | [User](#user-class) |  |
| **GetSPAppContextAsStream()** | ClientResult\<Stream\> |  |
| **GetStorageEntity(string key)** | [StorageEntity](#storageentity-class) |  |
| **GetSubwebsForCurrentUser(SubwebQuery query)** | [WebCollection](#webcollection-class) |  |
| **GetUserById(int userId)** | [User](#user-class) |  |
| **GetUserEffectivePermissions(string userName)** | ClientResult\<[BasePermissions](#basepermissions-class)\> |  |
| **GetViewFromPath(ResourcePath listPath)** | [View](#view-class) |  |
| **GetViewFromUrl(string listUrl)** | [View](#view-class) |  |
| **GetWebUrlFromPageUrl(ClientRuntimeContext context, string pageFullUrl)** | ClientResult\<string\> |  |
| **IncrementSiteClientTag()** | void |  |
| **LoadAndInstallApp(Stream appPackageStream)** | [AppInstance](#appinstance-class) |  |
| **LoadAndInstallAppInSpecifiedLocale(Stream appPackageStream, int installationLocaleLCID)** | [AppInstance](#appinstance-class) |  |
| **LoadApp(Stream appPackageStream, int installationLocaleLCID)** | [AppInstance](#appinstance-class) |  |
| **MapToIcon(string fileName, string progId, IconSize size)** | ClientResult\<string\> |  |
| **PageContextCore()** | ClientResult\<Stream\> |  |
| **PageContextInfo(bool includeODBSettings, bool emitNavigationInfo)** | ClientResult\<Stream\> |  |
| **RegisterPushNotificationSubscriber(Guid deviceAppInstanceId, string serviceToken)** | [PushNotificationSubscriber](#pushnotificationsubscriber-class) |  |
| **RemoveStorageEntity(string key)** | void |  |
| **RemoveSupportedUILanguage(int lcid)** | void |  |
| **SetAccessRequestSiteDescriptionAndUpdate(string description)** | void |  |
| **SetStorageEntity(string key, string value, string description, string comments)** | void |  |
| **SetUseAccessRequestDefaultAndUpdate(bool useAccessRequestDefault)** | void |  |
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
| **LastItemUserModifiedDate** | DateTime |  |
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
| **LastItemUserModifiedDate** | string |  |
| **ServerRelativeUrl** | string |  |
| **Title** | string |  |
| **WebTemplate** | string |  |
| **WebTemplateId** | string |  |
# WebObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Alerts** | string |  |
| **AllProperties** | string |  |
| **AppTiles** | string |  |
| **AssociatedMemberGroup** | string |  |
| **AssociatedOwnerGroup** | string |  |
| **AssociatedVisitorGroup** | string |  |
| **Author** | string |  |
| **AvailableContentTypes** | string |  |
| **AvailableFields** | string |  |
| **CanModernizeHomepage** | string |  |
| **ContentTypes** | string |  |
| **CurrentUser** | string |  |
| **DataLeakagePreventionStatusInfo** | string |  |
| **DescriptionResource** | string |  |
| **EventReceivers** | string |  |
| **Features** | string |  |
| **Fields** | string |  |
| **Folders** | string |  |
| **HostedApps** | string |  |
| **Lists** | string |  |
| **ListTemplates** | string |  |
| **Navigation** | string |  |
| **ParentWeb** | string |  |
| **PushNotificationSubscribers** | string |  |
| **RecycleBin** | string |  |
| **RegionalSettings** | string |  |
| **RoleDefinitions** | string |  |
| **RootFolder** | string |  |
| **SiteCollectionAppCatalog** | string |  |
| **SiteGroups** | string |  |
| **SiteUserInfoList** | string |  |
| **SiteUsers** | string |  |
| **TenantAppCatalog** | string |  |
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
| **AccessRequestListUrl** | string |  |
| **AccessRequestSiteDescription** | string |  |
| **Acronym** | string |  |
| **AllowAutomaticASPXPageIndexing** | string |  |
| **AllowCreateDeclarativeWorkflowForCurrentUser** | string |  |
| **AllowDesignerForCurrentUser** | string |  |
| **AllowMasterPageEditingForCurrentUser** | string |  |
| **AllowRevertFromTemplateForCurrentUser** | string |  |
| **AllowRssFeeds** | string |  |
| **AllowSaveDeclarativeWorkflowAsTemplateForCurrentUser** | string |  |
| **AllowSavePublishDeclarativeWorkflowForCurrentUser** | string |  |
| **AlternateCssUrl** | string |  |
| **AppInstanceId** | string |  |
| **ClassicWelcomePage** | string |  |
| **CommentsOnSitePagesDisabled** | string |  |
| **Configuration** | string |  |
| **ContainsConfidentialInfo** | string |  |
| **Created** | string |  |
| **CurrentChangeToken** | string |  |
| **CustomMasterUrl** | string |  |
| **CustomSiteActionsDisabled** | string |  |
| **Description** | string |  |
| **DescriptionForExistingLanguage** | string |  |
| **DescriptionTranslations** | string |  |
| **DesignerDownloadUrlForCurrentUser** | string |  |
| **DesignPackageId** | string |  |
| **DisableAppViews** | string |  |
| **DisableFlows** | string |  |
| **DisableRecommendedItems** | string |  |
| **DocumentLibraryCalloutOfficeWebAppPreviewersDisabled** | string |  |
| **EffectiveBasePermissions** | string |  |
| **EnableMinimalDownload** | string |  |
| **ExcludeFromOfflineClient** | string |  |
| **FooterEmphasis** | string |  |
| **FooterEnabled** | string |  |
| **FooterLayout** | string |  |
| **HasWebTemplateExtension** | string |  |
| **HeaderEmphasis** | string |  |
| **HeaderLayout** | string |  |
| **HideTitleInHeader** | string |  |
| **HorizontalQuickLaunch** | string |  |
| **Id** | string |  |
| **IsEduClass** | string |  |
| **IsEduClassProvisionChecked** | string |  |
| **IsEduClassProvisionPending** | string |  |
| **IsHomepageModernized** | string |  |
| **IsMultilingual** | string |  |
| **IsProvisioningComplete** | string |  |
| **IsRevertHomepageLinkHidden** | string |  |
| **Language** | string |  |
| **LastItemModifiedDate** | string |  |
| **LastItemUserModifiedDate** | string |  |
| **LogoAlignment** | string |  |
| **MasterUrl** | string |  |
| **MegaMenuEnabled** | string |  |
| **MembersCanShare** | string |  |
| **NavAudienceTargetingEnabled** | string |  |
| **NextStepsFirstRunEnabled** | string |  |
| **NoCrawl** | string |  |
| **NotificationsInOneDriveForBusinessEnabled** | string |  |
| **NotificationsInSharePointEnabled** | string |  |
| **ObjectCacheEnabled** | string |  |
| **OverwriteTranslationsOnChange** | string |  |
| **ResourcePath** | string |  |
| **PreviewFeaturesEnabled** | string |  |
| **PrimaryColor** | string |  |
| **QuickLaunchEnabled** | string |  |
| **RecycleBinEnabled** | string |  |
| **RequestAccessEmail** | string |  |
| **SaveSiteAsTemplateEnabled** | string |  |
| **SearchBoxInNavBar** | string |  |
| **SearchBoxPlaceholderText** | string |  |
| **SearchScope** | string |  |
| **ServerRelativePath** | string |  |
| **ServerRelativeUrl** | string |  |
| **ShowUrlStructureForCurrentUser** | string |  |
| **SiteLogoDescription** | string |  |
| **SiteLogoUrl** | string |  |
| **SupportedUILanguageIds** | string |  |
| **SyndicationEnabled** | string |  |
| **TenantAdminMembersCanShare** | string |  |
| **TenantTagPolicyEnabled** | string |  |
| **ThemedCssFolderUrl** | string |  |
| **ThirdPartyMdmEnabled** | string |  |
| **Title** | string |  |
| **TitleForExistingLanguage** | string |  |
| **TitleTranslations** | string |  |
| **TreeViewEnabled** | string |  |
| **UIVersion** | string |  |
| **UIVersionConfigurationEnabled** | string |  |
| **Url** | string |  |
| **UseAccessRequestDefault** | string |  |
| **WebTemplate** | string |  |
| **WebTemplateConfiguration** | string |  |
| **WebTemplatesGalleryFirstRunEnabled** | string |  |
| **WelcomePage** | string |  |
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
# FeatureScope Enum

Namespace: Microsoft.SharePoint.Client.Administration


## Values

| Name | Summary |
|---|---|
| **Site** |  |
| **Web** |  |
# OrgRelationRole Enum

Namespace: Microsoft.SharePoint.Client.Administration


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **Source** |  |
| **Target** |  |
# OrgRelationScenario Enum

Namespace: Microsoft.SharePoint.Client.Administration


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **MnA** |  |
# OrgRelationState Enum

Namespace: Microsoft.SharePoint.Client.Administration


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **MergeContentDefined** |  |
| **IdentityMappingInProgress** |  |
| **IdentityMappingCompleted** |  |
| **ContentMergeInProgress** |  |
| **ContentMergeCompleted** |  |
# OrgRelationVerificationStatus Enum

Namespace: Microsoft.SharePoint.Client.Administration


## Values

| Name | Summary |
|---|---|
| **NotEstablished** |  |
| **NotEstablishedByPartner** |  |
| **Dormant** |  |
| **DormantByPartner** |  |
| **GoodToProceed** |  |
| **CouldNotContactPartner** |  |
# SPBlockDownloadFileTypeId Enum

Namespace: Microsoft.SharePoint.Client.Administration


## Values

| Name | Summary |
|---|---|
| **TeamsMeetingRecording** |  |
# TenantIdentityMapItemType Enum

Namespace: Microsoft.SharePoint.Client.Administration


## Values

| Name | Summary |
|---|---|
| **User** |  |
| **Group** |  |
# TenantIdentityMappingGroupField Enum

Namespace: Microsoft.SharePoint.Client.Administration


## Values

| Name | Summary |
|---|---|
| **SourceGroupObjectId** |  |
| **TargetGroupObjectId** |  |
| **TargetGroupName** |  |
# TenantIdentityMappingGroupType Enum

Namespace: Microsoft.SharePoint.Client.Administration


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **RegularGroup** |  |
| **AdminGroup** |  |
| **O365Group** |  |
# TenantIdentityMappingUserField Enum

Namespace: Microsoft.SharePoint.Client.Administration


## Values

| Name | Summary |
|---|---|
| **SourceUserKey** |  |
| **TargetUserPuid** |  |
| **TargetUserUpn** |  |
| **TargetUserEmail** |  |
# TenantIdentityMappingUserType Enum

Namespace: Microsoft.SharePoint.Client.Administration


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **RegularUser** |  |
| **AdminUser** |  |
| **GuestUser** |  |
# TenantIdentityMigrationState Enum

Namespace: Microsoft.SharePoint.Client.Administration


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **ReadyForMigration** |  |
| **MigrationInProgress** |  |
| **MigrationCompleted** |  |
| **MigrationSuspended** |  |
# TenantIdentityMigrationStatus Enum

Namespace: Microsoft.SharePoint.Client.Administration


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **Succeeded** |  |
| **UnexceptedFailure** |  |
| **MigratorInternalFailure** |  |
| **UserMigrationSucceeded_GroupMigrationSucceeded** |  |
| **UserMigrationSucceeded_GroupMigrationInternalFailure** |  |
| **UserMigrationInternalFailure_GroupMigrationSucceeded** |  |
| **UserMigrationInternalFailure_GroupMigrationInternalFailure** |  |
# TenantStoreIdentityMigrationProperty Enum

Namespace: Microsoft.SharePoint.Client.Administration


## Values

| Name | Summary |
|---|---|
| **IdentityMigrationState** |  |
| **IdentityMigrationStatus** |  |
| **IdentityMigrationStatusLastUpdated** |  |
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
# BlockDownloadLinksFileType Enum

Namespace: Microsoft.SharePoint.Client.Sharing


## Values

| Name | Summary |
|---|---|
| **WebPreviewableFiles** |  |
| **ServerRenderedFilesOnly** |  |
# DocumentSharingManager Class

Namespace: Microsoft.SharePoint.Client.Sharing


## Methods

| Name | Returns | Summary |
|---|---|---|
| **CanMemberShare(ClientRuntimeContext context, List list)** | ClientResult\<bool\> |  |
| **GetRoleDefinition(ClientRuntimeContext context, Role role)** | [RoleDefinition](#roledefinition-class) |  |
| **IsDocumentSharingEnabled(ClientRuntimeContext context, List list)** | ClientResult\<bool\> |  |
| **RemoveItemsFromSharedWithMeView(ClientRuntimeContext context, IList\<string\> itemUrls)** | IEnumerable\<[SharedWithMeViewItemRemovalResult](#sharedwithmeviewitemremovalresult-class)\> |  |
| **RemoveItemsFromSharedWithMeViewByPath(ClientRuntimeContext context, IList\<ResourcePath\> itemPaths)** | IEnumerable\<[SharedWithMeViewItemRemovalResult](#sharedwithmeviewitemremovalresult-class)\> |  |
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
| **LimitedView** |  |
| **LimitedEdit** |  |
| **Review** |  |
| **RestrictedView** |  |
| **Submit** |  |
| **ManageList** |  |
# SharedObjectType Enum

Namespace: Microsoft.SharePoint.Client.Sharing


## Values

| Name | Summary |
|---|---|
| **Unknown** |  |
| **File** |  |
| **Folder** |  |
| **Item** |  |
| **List** |  |
| **Web** |  |
| **Max** |  |
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
# SharingDomainRestrictionMode Enum

Namespace: Microsoft.SharePoint.Client.Sharing


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **AllowList** |  |
| **BlockList** |  |
# SharingLinkExpressOptions Enum

Namespace: Microsoft.SharePoint.Client.Sharing


## Values

| Name | Summary |
|---|---|
| **AddressBarLink** |  |
# SharingScope Enum

Namespace: Microsoft.SharePoint.Client.Sharing


## Values

| Name | Summary |
|---|---|
| **Anyone** |  |
| **Organization** |  |
| **SpecificPeople** |  |
| **Uninitialized** |  |
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
# FileHandlerWopiProperties Class

Namespace: Microsoft.SharePoint.Client.Utilities

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **FileGetUrl** | string |  |
| **FileId** | string |  |
| **FilePutUrl** | string |  |
| **ResourceId** | string |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **FileHandlerWopiProperties(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# FileHandlerWopiPropertiesPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Utilities


## Fields

| Name | Type | Summary |
|---|---|---|
| **FileGetUrl** | string |  |
| **FileId** | string |  |
| **FilePutUrl** | string |  |
| **ResourceId** | string |  |
# IconSize Enum

Namespace: Microsoft.SharePoint.Client.Utilities


## Values

| Name | Summary |
|---|---|
| **Size16** |  |
| **Size32** |  |
| **Size256** |  |
# JsonTheme Class

Namespace: Microsoft.SharePoint.Client.Utilities

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **name** | string |  |
| **themeJson** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
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
# SPSocialSwitch Class

Namespace: Microsoft.SharePoint.Client.Utilities


## Methods

| Name | Returns | Summary |
|---|---|---|
| **IsFollowingFeatureEnabled(ClientRuntimeContext context)** | ClientResult\<bool\> |  |
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
# ThemingOptions Class

Namespace: Microsoft.SharePoint.Client.Utilities

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **hideDefaultThemes** | bool |  |
| **themePreviews** | [JsonTheme](#jsontheme-class)[] |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# UploadStatus Class

Namespace: Microsoft.SharePoint.Client.Utilities

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ExpectedContentRange** | string |  |
| **ExpirationDateTime** | DateTime |  |
| **UploadId** | Guid |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **UploadStatus(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# UploadStatusPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Utilities


## Fields

| Name | Type | Summary |
|---|---|---|
| **ExpectedContentRange** | string |  |
| **ExpirationDateTime** | string |  |
| **UploadId** | string |  |
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
# WebAppExtUrlPair Class

Namespace: Microsoft.SharePoint.Client.Utilities

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Ext** | string |  |
| **WacUrl** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# WebAppUrlsByAction Class

Namespace: Microsoft.SharePoint.Client.Utilities

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Action** | string |  |
| **UrlsByExt** | IList\<[WebAppExtUrlPair](#webappexturlpair-class)\> |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
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
| **GenerateFileBundle(ClientRuntimeContext context)** | ClientResult\<string\> |  |
| **GetFileHandlerWopiTargetPropertiesByUrl(ClientRuntimeContext context, string fileUrl, string appId)** | [FileHandlerWopiProperties](#filehandlerwopiproperties-class) |  |
| **GetWebApplicationUrls(ClientRuntimeContext context, string appNames, string actions)** | IList\<[WopiWebAppProperties](#wopiwebappproperties-class)\> |  |
| **GetWopiOrigins(ClientRuntimeContext context)** | IList\<string\> |  |
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
# WopiWebAppProperties Class

Namespace: Microsoft.SharePoint.Client.Utilities

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **App** | string |  |
| **BootstrapperUrl** | string |  |
| **ListByAction** | IList\<[WebAppUrlsByAction](#webappurlsbyaction-class)\> |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# LimitedWebPartManager Class

Namespace: Microsoft.SharePoint.Client.WebParts

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **HasPersonalizedParts** | bool |  |
| **HasWebPartConnections** | bool |  |
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
| **ExportWebPart(Guid webPartId)** | ClientResult\<string\> |  |
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
| **HasWebPartConnections** | string |  |
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
| **ExportMode** | [WebPartExportMode](#webpartexportmode-enum) |  |
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
# WebPartExportMode Enum

Namespace: Microsoft.SharePoint.Client.WebParts


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **All** |  |
| **NonSensitiveData** |  |
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
| **ExportMode** | string |  |
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
| **RunningInstances** | int |  |
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
| **RunningInstances** | string |  |
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
# HostedApp Class

Namespace: Microsoft.SharePoint.ClientSideComponent

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
| **HostedApp(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# HostedAppAddResponse Class

Namespace: Microsoft.SharePoint.ClientSideComponent

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **itemId** | int |  |
| **shareLinkUrl** | string |  |
| **shareWebPath** | string |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **HostedAppAddResponse(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# HostedAppAddResponsePropertyNames Class

Namespace: Microsoft.SharePoint.ClientSideComponent


## Fields

| Name | Type | Summary |
|---|---|---|
| **itemId** | string |  |
| **shareLinkUrl** | string |  |
| **shareWebPath** | string |  |
# HostedAppsManager Class

Namespace: Microsoft.SharePoint.ClientSideComponent

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
| **HostedAppsManager(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# StorageEntity Class

Namespace: Microsoft.SharePoint.ClientSideComponent

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Comment** | string |  |
| **Description** | string |  |
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
| **StorageEntity(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# StorageEntityPropertyNames Class

Namespace: Microsoft.SharePoint.ClientSideComponent


## Fields

| Name | Type | Summary |
|---|---|---|
| **Comment** | string |  |
| **Description** | string |  |
| **Value** | string |  |
# CommentsDisabledScope Enum

Namespace: Microsoft.SharePoint.Comments


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **Item** |  |
| **Web** |  |
| **Tenant** |  |
| **Site** |  |
# ShortcutInformation Class

Namespace: Microsoft.SharePoint.Deployment

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AddedById** | int |  |
| **Id** | Guid |  |
| **Name** | string |  |
| **Scenario** | [AtoScenario](#atoscenario-enum) |  |
| **TimeCreated** | DateTime |  |
| **TimeLastModified** | DateTime |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# GroupSiteRelationship Enum

Namespace: Microsoft.SharePoint.Groups


## Values

| Name | Summary |
|---|---|
| **Healthy** |  |
| **DuplicateSite** |  |
| **GroupNotFound** |  |
| **Disconnected** |  |
# SiteCollectionAppCatalogAllowedCollection Class

Namespace: Microsoft.SharePoint.Marketplace.CorporateCuratedGallery

Base class: ClientObjectCollection<[SiteCollectionAppCatalogAllowedItem](#sitecollectionappcatalogalloweditem-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [SiteCollectionAppCatalogAllowedItem](#sitecollectionappcatalogalloweditem-class) |  |
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
| **SiteCollectionAppCatalogAllowedCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(string absolutePath)** | [SiteCollectionAppCatalogAllowedItem](#sitecollectionappcatalogalloweditem-class) |  |
| **GetById(Guid siteId)** | [SiteCollectionAppCatalogAllowedItem](#sitecollectionappcatalogalloweditem-class) |  |
| **Remove(string absolutePath)** | void |  |
| **RemoveById(Guid siteId)** | void |  |
# SiteCollectionAppCatalogAllowedItem Class

Namespace: Microsoft.SharePoint.Marketplace.CorporateCuratedGallery

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AbsoluteUrl** | string |  |
| **ErrorMessage** | string |  |
| **SiteID** | Guid |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **SiteCollectionAppCatalogAllowedItem(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# SiteCollectionAppCatalogAllowedItemPropertyNames Class

Namespace: Microsoft.SharePoint.Marketplace.CorporateCuratedGallery


## Fields

| Name | Type | Summary |
|---|---|---|
| **AbsoluteUrl** | string |  |
| **ErrorMessage** | string |  |
| **SiteID** | string |  |
# SiteCollectionCorporateCatalogAccessor Class

Namespace: Microsoft.SharePoint.Marketplace.CorporateCuratedGallery

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
| **SiteCollectionCorporateCatalogAccessor(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# SPAppInstallationInfo Class

Namespace: Microsoft.SharePoint.Marketplace.CorporateCuratedGallery

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AppPrincipalId** | string |  |
| **AppSource** | string |  |
| **AppWebFullUrl** | string |  |
| **AppWebId** | Guid |  |
| **AppWebName** | string |  |
| **AssetId** | string |  |
| **CreationTimeUtc** | DateTime |  |
| **Id** | Guid |  |
| **InstalledBy** | string |  |
| **LaunchUrl** | string |  |
| **LicensePurchaseTime** | DateTime |  |
| **Locale** | string |  |
| **ProductId** | Guid |  |
| **PurchaserIdentity** | string |  |
| **SiteId** | Guid |  |
| **Status** | string |  |
| **TenantAppData** | string |  |
| **TenantAppDataUpdateTime** | DateTime |  |
| **Title** | string |  |
| **WebId** | Guid |  |
| **WebName** | string |  |
| **WebUrl** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SPStoreAppCreateByIdInformation Class

Namespace: Microsoft.SharePoint.Marketplace.CorporateCuratedGallery

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **CMU** | string |  |
| **isUpdatingApp** | bool |  |
| **Overwrite** | bool |  |
| **SkipFeatureDeployment** | bool |  |
| **StoreAssetId** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SPStoreAppRequestInformation Class

Namespace: Microsoft.SharePoint.Marketplace.CorporateCuratedGallery

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AssetId** | string |  |
| **BillingMarket** | string |  |
| **ContentMarket** | string |  |
| **InstallationSiteId** | Guid |  |
| **InstallationWebId** | Guid |  |
| **Justification** | string |  |
| **RequestType** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SPStoreAppResponseInformation Class

Namespace: Microsoft.SharePoint.Marketplace.CorporateCuratedGallery

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ItemId** | string |  |
| **ListId** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# StoreAppCreationInformation Class

Namespace: Microsoft.SharePoint.Marketplace.CorporateCuratedGallery

Base class: [FileCreationInformation](#filecreationinformation-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **IconUrl** | string |  |
| **Publisher** | string |  |
| **ShortDescription** | string |  |
| **StoreAssetId** | string |  |
| **TypeId** | string |  |
| **Content** | byte[] |  |
| **ContentStream** | Stream |  |
| **Overwrite** | bool |  |
| **Url** | string |  |
| **XorHash** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# TeamsPackageDownload Class

Namespace: Microsoft.SharePoint.Marketplace.CorporateCuratedGallery

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
| **TeamsPackageDownload(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# TenantCorporateCatalogAccessor Class

Namespace: Microsoft.SharePoint.Marketplace.CorporateCuratedGallery

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **SiteCollectionAppCatalogsSites** | [SiteCollectionAppCatalogAllowedCollection](#sitecollectionappcatalogallowedcollection-class) |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **TenantCorporateCatalogAccessor(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# TenantCorporateCatalogAccessorObjectPropertyNames Class

Namespace: Microsoft.SharePoint.Marketplace.CorporateCuratedGallery


## Fields

| Name | Type | Summary |
|---|---|---|
| **SiteCollectionAppCatalogsSites** | string |  |
# NavigationSource Enum

Namespace: Microsoft.SharePoint.Navigation.REST


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **TopOrHub** |  |
| **QuickLaunch** |  |
# Document Class

Namespace: Microsoft.SharePoint.News.DataModel

Base class: [NavigatableItem](#navigatableitem-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **comments** | long |  |
| **contentClass** | string |  |
| **contentTypeId** | string |  |
| **fileExtension** | string |  |
| **folder** | [Folder](#folder-class) |  |
| **itemReference** | [DocumentReference](#documentreference-class) |  |
| **lastModifiedBy** | [Person](#person-class) |  |
| **lastModifiedTime** | string |  |
| **library** | [Library](#library-class) |  |
| **liked** | bool |  |
| **likes** | long |  |
| **savedForLater** | bool |  |
| **site** | [SPOSite](#sposite-class) |  |
| **size** | long |  |
| **staticTeaser** | string |  |
| **views** | long |  |
| **TypeId** | string |  |
| **id** | string |  |
| **originalUrl** | string |  |
| **serverRedirectedUrl** | string |  |
| **url** | string |  |
| **title** | string |  |
| **type** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# DocumentReference Class

Namespace: Microsoft.SharePoint.News.DataModel

Base class: [ItemReference](#itemreference-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **uniqueId** | Guid |  |
| **TypeId** | string |  |
| **exchangeId** | string |  |
| **siteId** | Guid |  |
| **type** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# Folder Class

Namespace: Microsoft.SharePoint.News.DataModel

Base class: [NavigatableItem](#navigatableitem-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **folderId** | Guid |  |
| **TypeId** | string |  |
| **id** | string |  |
| **originalUrl** | string |  |
| **serverRedirectedUrl** | string |  |
| **url** | string |  |
| **title** | string |  |
| **type** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# Item Class

Namespace: Microsoft.SharePoint.News.DataModel

Base class: [SerializableType](#serializabletype-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **title** | string |  |
| **TypeId** | string |  |
| **type** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# ItemReference Class

Namespace: Microsoft.SharePoint.News.DataModel

Base class: [SerializableType](#serializabletype-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **exchangeId** | string |  |
| **siteId** | Guid |  |
| **TypeId** | string |  |
| **type** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# ItemsList Class

Namespace: Microsoft.SharePoint.News.DataModel

Base class: [SerializableType](#serializabletype-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **items** | IList\<[Item](#item-class)\> |  |
| **TypeId** | string |  |
| **type** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# Library Class

Namespace: Microsoft.SharePoint.News.DataModel

Base class: [NavigatableItem](#navigatableitem-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **listId** | Guid |  |
| **TypeId** | string |  |
| **id** | string |  |
| **originalUrl** | string |  |
| **serverRedirectedUrl** | string |  |
| **url** | string |  |
| **title** | string |  |
| **type** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# NavigatableItem Class

Namespace: Microsoft.SharePoint.News.DataModel

Base class: [Item](#item-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **id** | string |  |
| **originalUrl** | string |  |
| **serverRedirectedUrl** | string |  |
| **url** | string |  |
| **TypeId** | string |  |
| **title** | string |  |
| **type** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# NewsArticle Class

Namespace: Microsoft.SharePoint.News.DataModel

Base class: [Document](#document-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **author** | [Person](#person-class) |  |
| **description** | string |  |
| **firstPublishedDate** | DateTime |  |
| **imageUrl** | string |  |
| **isAuthoritativeNews** | bool |  |
| **listItemId** | string |  |
| **newsSourceType** | [NewsSourceType](#newssourcetype-enum) |  |
| **newsType** | [NewsType](#newstype-enum) |  |
| **relativeAuthorRank** | int |  |
| **TypeId** | string |  |
| **comments** | long |  |
| **contentClass** | string |  |
| **contentTypeId** | string |  |
| **fileExtension** | string |  |
| **folder** | [Folder](#folder-class) |  |
| **itemReference** | [DocumentReference](#documentreference-class) |  |
| **lastModifiedBy** | [Person](#person-class) |  |
| **lastModifiedTime** | string |  |
| **library** | [Library](#library-class) |  |
| **liked** | bool |  |
| **likes** | long |  |
| **savedForLater** | bool |  |
| **site** | [SPOSite](#sposite-class) |  |
| **size** | long |  |
| **staticTeaser** | string |  |
| **views** | long |  |
| **id** | string |  |
| **originalUrl** | string |  |
| **serverRedirectedUrl** | string |  |
| **url** | string |  |
| **title** | string |  |
| **type** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# NewsSourceType Enum

Namespace: Microsoft.SharePoint.News.DataModel


## Values

| Name | Summary |
|---|---|
| **Unknown** |  |
# NewsType Enum

Namespace: Microsoft.SharePoint.News.DataModel


## Values

| Name | Summary |
|---|---|
| **News** |  |
| **InternalNewsLink** |  |
| **ExternalNewsLink** |  |
# Person Class

Namespace: Microsoft.SharePoint.News.DataModel

Base class: [NavigatableItem](#navigatableitem-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **accountName** | string |  |
| **acronym** | string |  |
| **bannerColor** | string |  |
| **itemReference** | [PersonReference](#personreference-class) |  |
| **workEmail** | string |  |
| **TypeId** | string |  |
| **id** | string |  |
| **originalUrl** | string |  |
| **serverRedirectedUrl** | string |  |
| **url** | string |  |
| **title** | string |  |
| **type** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# PersonReference Class

Namespace: Microsoft.SharePoint.News.DataModel

Base class: [ItemReference](#itemreference-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **TypeId** | string |  |
| **exchangeId** | string |  |
| **siteId** | Guid |  |
| **type** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SerializableType Class

Namespace: Microsoft.SharePoint.News.DataModel

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **type** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SPOSite Class

Namespace: Microsoft.SharePoint.News.DataModel

Base class: [NavigatableItem](#navigatableitem-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **acronym** | string |  |
| **bannerColor** | string |  |
| **bannerImageUrl** | string |  |
| **contentTypeId** | string |  |
| **departmentId** | Guid |  |
| **isExternalContent** | bool |  |
| **itemReference** | [SPOSiteReference](#spositereference-class) |  |
| **language** | string |  |
| **lastModifiedTime** | DateTime |  |
| **webTemplate** | string |  |
| **TypeId** | string |  |
| **id** | string |  |
| **originalUrl** | string |  |
| **serverRedirectedUrl** | string |  |
| **url** | string |  |
| **title** | string |  |
| **type** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SPOSiteReference Class

Namespace: Microsoft.SharePoint.News.DataModel

Base class: [ItemReference](#itemreference-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **webId** | Guid |  |
| **TypeId** | string |  |
| **exchangeId** | string |  |
| **siteId** | Guid |  |
| **type** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
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
# OperationType Enum

Namespace: Microsoft.SharePoint.SmartCache


## Values

| Name | Summary |
|---|---|
| **Update** |  |
| **Add** |  |
| **Remove** |  |
# SmartCacheItem Class

Namespace: Microsoft.SharePoint.SmartCache

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **accessUrl** | string |  |
| **containerTitle** | string |  |
| **contentClass** | string |  |
| **isDefaultDocumentLibrary** | bool |  |
| **isTeamsChannelSite** | bool |  |
| **isTeamsConnectedSite** | bool |  |
| **lastAccessDateTime** | DateTime |  |
| **listId** | Guid |  |
| **listItemId** | int |  |
| **operation** | [OperationType](#operationtype-enum) |  |
| **pinOrder** | long |  |
| **properties** | string |  |
| **siteAcronym** | string |  |
| **siteColor** | string |  |
| **siteId** | Guid |  |
| **siteLogoUrl** | string |  |
| **spoId** | string |  |
| **title** | string |  |
| **uniqueId** | Guid |  |
| **webId** | Guid |  |
| **webUrl** | string |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **SmartCacheItem(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# SmartCacheItemPropertyNames Class

Namespace: Microsoft.SharePoint.SmartCache


## Fields

| Name | Type | Summary |
|---|---|---|
| **accessUrl** | string |  |
| **containerTitle** | string |  |
| **contentClass** | string |  |
| **isDefaultDocumentLibrary** | string |  |
| **isTeamsChannelSite** | string |  |
| **isTeamsConnectedSite** | string |  |
| **lastAccessDateTime** | string |  |
| **listId** | string |  |
| **listItemId** | string |  |
| **operation** | string |  |
| **pinOrder** | string |  |
| **properties** | string |  |
| **siteAcronym** | string |  |
| **siteColor** | string |  |
| **siteId** | string |  |
| **siteLogoUrl** | string |  |
| **spoId** | string |  |
| **title** | string |  |
| **uniqueId** | string |  |
| **webId** | string |  |
| **webUrl** | string |  |
# TenantCdnUrl Class

Namespace: Microsoft.SharePoint.TenantCdn

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **CdnUrl** | string |  |
| **ExpirationTimeUtc** | DateTime |  |
| **IsCdnUrlAvailable** | bool |  |
| **ItemUrl** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SiteScriptStore Enum

Namespace: Microsoft.SharePoint.Utilities.WebTemplateExtensions


## Values

| Name | Summary |
|---|---|
| **Tenant** |  |
| **OutOfBox** |  |
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
