# Microsoft.Online.SharePoint.Client.Tenant.dll v.16.1.0.0 API documentation

Created by 
[mddox](https://github.com/loxsmoke/mddox) on 2024-01-29

# All types

|   |   |   |
|---|---|---|
| [ScriptTypeFactory Class](#scripttypefactory-class) | [SPDeletedContainerTypeProperties Class](#spdeletedcontainertypeproperties-class) | [TenantSiteScriptActionOutcome Enum](#tenantsitescriptactionoutcome-enum) |
| [ConnectionStatus Enum](#connectionstatus-enum) | [SPODeletedSitePropertiesEnumerable Class](#spodeletedsitepropertiesenumerable-class) | [TenantSiteScriptActionResult Class](#tenantsitescriptactionresult-class) |
| [CredentialsType Enum](#credentialstype-enum) | [SPODeletedSitePropertiesEnumerablePropertyNames Class](#spodeletedsitepropertiesenumerablepropertynames-class) | [TenantSiteScriptActionResultPropertyNames Class](#tenantsitescriptactionresultpropertynames-class) |
| [DeviceActionId Enum](#deviceactionid-enum) | [SPOHubSiteUserRights Enum](#spohubsiteuserrights-enum) | [TenantSiteScriptActionStatus Class](#tenantsitescriptactionstatus-class) |
| [DeviceStatus Enum](#devicestatus-enum) | [SPOMalwareFile Class](#spomalwarefile-class) | [TenantSiteScriptActionStatusPropertyNames Class](#tenantsitescriptactionstatuspropertynames-class) |
| [EPerfBottleneck Enum](#eperfbottleneck-enum) | [SPOMalwareFileObjectPropertyNames Class](#spomalwarefileobjectpropertynames-class) | [TenantSiteScriptCreationInfo Class](#tenantsitescriptcreationinfo-class) |
| [MigrationTaskStatus Enum](#migrationtaskstatus-enum) | [SPOMalwareFilePropertyNames Class](#spomalwarefilepropertynames-class) | [TenantSiteScriptPropertyNames Class](#tenantsitescriptpropertynames-class) |
| [ScheduleType Enum](#scheduletype-enum) | [SpoOperation Class](#spooperation-class) | [TenantSiteScriptSerializationInfo Class](#tenantsitescriptserializationinfo-class) |
| [SourceType Enum](#sourcetype-enum) | [SpoOperationPropertyNames Class](#spooperationpropertynames-class) | [TenantSiteScriptSerializationResult Class](#tenantsitescriptserializationresult-class) |
| [StorageActionId Enum](#storageactionid-enum) | [SPOPortalLaunchValidationResult Class](#spoportallaunchvalidationresult-class) | [TenantTemplateDesignType Enum](#tenanttemplatedesigntype-enum) |
| [TaskActionId Enum](#taskactionid-enum) | [SPOPortalLaunchValidationResultPropertyNames Class](#spoportallaunchvalidationresultpropertynames-class) | [UpdateGroupSitePropertiesParameters Class](#updategroupsitepropertiesparameters-class) |
| [TaskErrorCode Enum](#taskerrorcode-enum) | [SPOPortalLaunchValidationResultTypes Enum](#spoportallaunchvalidationresulttypes-enum) | [UserInfo Class](#userinfo-class) |
| [TaskFailure Enum](#taskfailure-enum) | [SPOPortalLaunchValidator Class](#spoportallaunchvalidator-class) | [UserMigrationProperties Class](#usermigrationproperties-class) |
| [TaskManagementStatus Enum](#taskmanagementstatus-enum) | [SpoSiteLockState Enum](#spositelockstate-enum) | [UserMigrationPropertiesEnumerable Class](#usermigrationpropertiesenumerable-class) |
| [LogExport Class](#logexport-class) | [SPOSitePropertiesEnumerable Class](#spositepropertiesenumerable-class) | [UserMigrationPropertiesEnumerableFilter Class](#usermigrationpropertiesenumerablefilter-class) |
| [LogFileInfo Class](#logfileinfo-class) | [SPOSitePropertiesEnumerableFilter Class](#spositepropertiesenumerablefilter-class) | [UserMigrationPropertiesEnumerablePropertyNames Class](#usermigrationpropertiesenumerablepropertynames-class) |
| [LogFileInfoPropertyNames Class](#logfileinfopropertynames-class) | [SPOSitePropertiesEnumerablePropertyNames Class](#spositepropertiesenumerablepropertynames-class) | [UserMigrationPropertiesPropertyNames Class](#usermigrationpropertiespropertynames-class) |
| [DDIAdapter Class](#ddiadapter-class) | [SPOTenantCdnPolicy Class](#spotenantcdnpolicy-class) | [SPO3rdPartyAADPermissionGrant Class](#spo3rdpartyaadpermissiongrant-class) |
| [AppErrorEntry Class](#apperrorentry-class) | [SPOTenantCdnPolicyPropertyNames Class](#spotenantcdnpolicypropertynames-class) | [SPO3rdPartyAADPermissionGrantManager Class](#spo3rdpartyaadpermissiongrantmanager-class) |
| [AppErrorEntryPropertyNames Class](#apperrorentrypropertynames-class) | [SPOTenantCdnPolicyType Enum](#spotenantcdnpolicytype-enum) | [SPO3rdPartyAADPermissionGrantPropertyNames Class](#spo3rdpartyaadpermissiongrantpropertynames-class) |
| [AppErrorType Enum](#apperrortype-enum) | [SPOTenantCdnType Enum](#spotenantcdntype-enum) | [SPOWebAppServicePrincipal Class](#spowebappserviceprincipal-class) |
| [AppInfo Class](#appinfo-class) | [SPOTenantGroupIdentityMapping Class](#spotenantgroupidentitymapping-class) | [SPOWebAppServicePrincipalObjectPropertyNames Class](#spowebappserviceprincipalobjectpropertynames-class) |
| [AppInfoPropertyNames Class](#appinfopropertynames-class) | [SPOTenantGroupIdentityMappingPropertyNames Class](#spotenantgroupidentitymappingpropertynames-class) | [SPOWebAppServicePrincipalPermissionGrant Class](#spowebappserviceprincipalpermissiongrant-class) |
| [AppSource Enum](#appsource-enum) | [SPOTenantInstance Class](#spotenantinstance-class) | [SPOWebAppServicePrincipalPermissionGrantCollection Class](#spowebappserviceprincipalpermissiongrantcollection-class) |
| [AppViewsPolicy Enum](#appviewspolicy-enum) | [SPOTenantInstancePropertyNames Class](#spotenantinstancepropertynames-class) | [SPOWebAppServicePrincipalPermissionGrantPropertyNames Class](#spowebappserviceprincipalpermissiongrantpropertynames-class) |
| [AzureSubscriptionState Enum](#azuresubscriptionstate-enum) | [SPOTenantOdbFeature Class](#spotenantodbfeature-class) | [SPOWebAppServicePrincipalPermissionRequest Class](#spowebappserviceprincipalpermissionrequest-class) |
| [CompanyWideSharingLinksPolicy Enum](#companywidesharinglinkspolicy-enum) | [SPOTenantOdbFeaturePropertyNames Class](#spotenantodbfeaturepropertynames-class) | [SPOWebAppServicePrincipalPermissionRequestCollection Class](#spowebappserviceprincipalpermissionrequestcollection-class) |
| [CreatePolicyRequest Class](#createpolicyrequest-class) | [SPOTenantSiteUserInvitation Class](#spotenantsiteuserinvitation-class) | [SPOWebAppServicePrincipalPermissionRequestPropertyNames Class](#spowebappserviceprincipalpermissionrequestpropertynames-class) |
| [DeletedSiteProperties Class](#deletedsiteproperties-class) | [SPOTenantSiteUserInvitationPropertyNames Class](#spotenantsiteuserinvitationpropertynames-class) | [SPOWebAppServicePrincipalPropertyNames Class](#spowebappserviceprincipalpropertynames-class) |
| [DeletedSitePropertiesPropertyNames Class](#deletedsitepropertiespropertynames-class) | [SPOTenantUserIdentityMapping Class](#spotenantuseridentitymapping-class) | [BlockDownloadLinksFileTypes Enum](#blockdownloadlinksfiletypes-enum) |
| [DenyAddAndCustomizePagesStatus Enum](#denyaddandcustomizepagesstatus-enum) | [SPOTenantUserIdentityMappingPropertyNames Class](#spotenantuseridentitymappingpropertynames-class) | [ExternalUser Class](#externaluser-class) |
| [EsignatureThirdPartyProvidersInfo Class](#esignaturethirdpartyprovidersinfo-class) | [SPOTenantWebTemplate Class](#spotenantwebtemplate-class) | [ExternalUserCollection Class](#externalusercollection-class) |
| [FileSensitivityLabelInfo Class](#filesensitivitylabelinfo-class) | [SPOTenantWebTemplateCollection Class](#spotenantwebtemplatecollection-class) | [ExternalUserPropertyNames Class](#externaluserpropertynames-class) |
| [FileSensitivityLabelInfoPropertyNames Class](#filesensitivitylabelinfopropertynames-class) | [SPOWebAppServicePrincipalPublic Class](#spowebappserviceprincipalpublic-class) | [GetExternalUsersResults Class](#getexternalusersresults-class) |
| [FlowsPolicy Enum](#flowspolicy-enum) | [SPSyntexApplicationProperties Class](#spsyntexapplicationproperties-class) | [GetExternalUsersResultsObjectPropertyNames Class](#getexternalusersresultsobjectpropertynames-class) |
| [GroupInfo Class](#groupinfo-class) | [SyntexBillingContext Class](#syntexbillingcontext-class) | [GetExternalUsersResultsPropertyNames Class](#getexternalusersresultspropertynames-class) |
| [HubSitePermission Class](#hubsitepermission-class) | [SyntexConsumptionBillingActivationStatus Enum](#syntexconsumptionbillingactivationstatus-enum) | [GroupCreationParams Class](#groupcreationparams-class) |
| [HubSiteProperties Class](#hubsiteproperties-class) | [SyntexConsumptionBillingEnabledFeatures Enum](#syntexconsumptionbillingenabledfeatures-enum) | [GroupCreationParamsPropertyNames Class](#groupcreationparamspropertynames-class) |
| [HubSitePropertiesPropertyNames Class](#hubsitepropertiespropertynames-class) | [SyntexPowerAppsEnvironmentsContext Class](#syntexpowerappsenvironmentscontext-class) | [ImageTaggingChoice Enum](#imagetaggingchoice-enum) |
| [ISPOPortalLaunchValidator Class](#ispoportallaunchvalidator-class) | [SyntexPremiumFeatureSettings Class](#syntexpremiumfeaturesettings-class) | [ImportProfilePropertiesJobError Enum](#importprofilepropertiesjoberror-enum) |
| [MessagesFieldsData Class](#messagesfieldsdata-class) | [SyntexSiteSpecificFeatureStatus Enum](#syntexsitespecificfeaturestatus-enum) | [ImportProfilePropertiesJobInfo Class](#importprofilepropertiesjobinfo-class) |
| [ObjectCharacterRecognitionMode Enum](#objectcharacterrecognitionmode-enum) | [TeamsChannelTypeValue Enum](#teamschanneltypevalue-enum) | [ImportProfilePropertiesJobInfoPropertyNames Class](#importprofilepropertiesjobinfopropertynames-class) |
| [OdbMigrationStatus Enum](#odbmigrationstatus-enum) | [Tenant Class](#tenant-class) | [ImportProfilePropertiesJobState Enum](#importprofilepropertiesjobstate-enum) |
| [PersonalSiteFilter Enum](#personalsitefilter-enum) | [TenantBrowseUserInfoPolicyValue Enum](#tenantbrowseuserinfopolicyvalue-enum) | [ImportProfilePropertiesJobStatusCollection Class](#importprofilepropertiesjobstatuscollection-class) |
| [PowerAppsEnvironment Class](#powerappsenvironment-class) | [TenantFontPackage Class](#tenantfontpackage-class) | [ImportProfilePropertiesUserIdType Enum](#importprofilepropertiesuseridtype-enum) |
| [PowerAppsEnvironmentContext Class](#powerappsenvironmentcontext-class) | [TenantFontPackageCreationParameters Class](#tenantfontpackagecreationparameters-class) | [MediaTranscriptionAutomaticFeaturesPolicyType Enum](#mediatranscriptionautomaticfeaturespolicytype-enum) |
| [PWAEnabledStatus Enum](#pwaenabledstatus-enum) | [TenantFontPackagePropertyNames Class](#tenantfontpackagepropertynames-class) | [MediaTranscriptionPolicyType Enum](#mediatranscriptionpolicytype-enum) |
| [RecentAdminActionReportPayload Class](#recentadminactionreportpayload-class) | [TenantListDesign Class](#tenantlistdesign-class) | [Office365Tenant Class](#office365tenant-class) |
| [RestrictedToRegion Enum](#restrictedtoregion-enum) | [TenantListDesignColor Enum](#tenantlistdesigncolor-enum) | [Office365TenantPropertyNames Class](#office365tenantpropertynames-class) |
| [SandboxedCodeActivationCapabilities Enum](#sandboxedcodeactivationcapabilities-enum) | [TenantListDesignCreationInfo Class](#tenantlistdesigncreationinfo-class) | [RemoveExternalUsersResults Class](#removeexternalusersresults-class) |
| [SecondaryAdministratorsFieldsData Class](#secondaryadministratorsfieldsdata-class) | [TenantListDesignIcon Enum](#tenantlistdesignicon-enum) | [RemoveExternalUsersResultsPropertyNames Class](#removeexternalusersresultspropertynames-class) |
| [SecondaryAdministratorsInfo Class](#secondaryadministratorsinfo-class) | [TenantListDesignPropertyNames Class](#tenantlistdesignpropertynames-class) | [SensitiveByDefaultState Enum](#sensitivebydefaultstate-enum) |
| [SiteAdministratorsFieldsData Class](#siteadministratorsfieldsdata-class) | [TenantLog Class](#tenantlog-class) | [SharingCapabilities Enum](#sharingcapabilities-enum) |
| [SiteAdministratorsInfo Class](#siteadministratorsinfo-class) | [TenantLogEntry Class](#tenantlogentry-class) | [SharingDomainRestrictionModes Enum](#sharingdomainrestrictionmodes-enum) |
| [SiteCreationProperties Class](#sitecreationproperties-class) | [TenantLogEntryPropertyNames Class](#tenantlogentrypropertynames-class) | [SharingLinkType Enum](#sharinglinktype-enum) |
| [SiteInfoForSitePicker Class](#siteinfoforsitepicker-class) | [TenantLogPropertyNames Class](#tenantlogpropertynames-class) | [SharingPermissionType Enum](#sharingpermissiontype-enum) |
| [SiteProperties Class](#siteproperties-class) | [TenantOutOfBoxSiteTemplateSettings Class](#tenantoutofboxsitetemplatesettings-class) | [SortOrder Enum](#sortorder-enum) |
| [SitePropertiesPropertyNames Class](#sitepropertiespropertynames-class) | [TenantPropertyNames Class](#tenantpropertynames-class) | [SpecialCharactersState Enum](#specialcharactersstate-enum) |
| [SiteRenameStatesInTenantRename Enum](#siterenamestatesintenantrename-enum) | [TenantSiteDesign Class](#tenantsitedesign-class) | [SPOAuthenticationContextPolicyAccessType Enum](#spoauthenticationcontextpolicyaccesstype-enum) |
| [SiteUserGroupInfo Class](#siteusergroupinfo-class) | [TenantSiteDesignCreationInfo Class](#tenantsitedesigncreationinfo-class) | [SPOConditionalAccessPolicyType Enum](#spoconditionalaccesspolicytype-enum) |
| [SiteUserGroupsData Class](#siteusergroupsdata-class) | [TenantSiteDesignPrincipal Class](#tenantsitedesignprincipal-class) | [SPOLimitedAccessFileType Enum](#spolimitedaccessfiletype-enum) |
| [SiteUserInfoVisibilityPolicyValue Enum](#siteuserinfovisibilitypolicyvalue-enum) | [TenantSiteDesignPrincipalPropertyNames Class](#tenantsitedesignprincipalpropertynames-class) | [SPOTlsTokenBindingPolicyValue Enum](#spotlstokenbindingpolicyvalue-enum) |
| [SPContainerCollection Class](#spcontainercollection-class) | [TenantSiteDesignPrincipalRights Enum](#tenantsitedesignprincipalrights-enum) | [SPOUserSessionRevocationResult Class](#spousersessionrevocationresult-class) |
| [SPContainerProperties Class](#spcontainerproperties-class) | [TenantSiteDesignPropertyNames Class](#tenantsitedesignpropertynames-class) | [SPOUserSessionRevocationResultPropertyNames Class](#spousersessionrevocationresultpropertynames-class) |
| [SPContainerTypeBillingClassification Enum](#spcontainertypebillingclassification-enum) | [TenantSiteDesignRun Class](#tenantsitedesignrun-class) | [SPOUserSessionRevocationState Enum](#spousersessionrevocationstate-enum) |
| [SPContainerTypeConfigurationProperties Class](#spcontainertypeconfigurationproperties-class) | [TenantSiteDesignRunPropertyNames Class](#tenantsitedesignrunpropertynames-class) | [StreamLaunchConfigValues Enum](#streamlaunchconfigvalues-enum) |
| [SPContainerTypeProperties Class](#spcontainertypeproperties-class) | [TenantSiteDesignTask Class](#tenantsitedesigntask-class) | [ThemeProperties Class](#themeproperties-class) |
| [SPContainerTypeTenantType Enum](#spcontainertypetenanttype-enum) | [TenantSiteDesignTaskPropertyNames Class](#tenantsitedesigntaskpropertynames-class) | [ThemePropertiesPropertyNames Class](#themepropertiespropertynames-class) |
| [SPDeletedContainerProperties Class](#spdeletedcontainerproperties-class) | [TenantSiteScript Class](#tenantsitescript-class) | [Workflows2013State Enum](#workflows2013state-enum) |
# ScriptTypeFactory Class

Namespace: Microsoft.Online.SharePoint.Client.TenantAdmin


## Methods

| Name | Returns | Summary |
|---|---|---|
| **CreateObjectFromScriptType(string scriptType, ClientRuntimeContext context)** | IFromJson |  |
# ConnectionStatus Enum

Namespace: Microsoft.Online.SharePoint.MigrationCenter.Common


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **Connected** |  |
| **Disconnected** |  |
# CredentialsType Enum

Namespace: Microsoft.Online.SharePoint.MigrationCenter.Common


## Values

| Name | Summary |
|---|---|
| **Source** |  |
| **Target** |  |
# DeviceActionId Enum

Namespace: Microsoft.Online.SharePoint.MigrationCenter.Common


## Values

| Name | Summary |
|---|---|
| **UpdateDeviceInfo** |  |
| **EnableDevice** |  |
| **DisableDevice** |  |
| **UpdateStatus** |  |
| **Heartbeat** |  |
| **Disconnecting** |  |
| **DeleteDevice** |  |
| **UpdateWorkingFolder** |  |
| **ValidateWorkingFolder** |  |
| **Debug** |  |
# DeviceStatus Enum

Namespace: Microsoft.Online.SharePoint.MigrationCenter.Common


## Values

| Name | Summary |
|---|---|
| **Ready** |  |
| **Assigned** |  |
| **Working** |  |
| **Upgrading** |  |
| **Disabling** |  |
| **Disabled** |  |
| **Enabling** |  |
| **Disconnected** |  |
| **NotAccessible** |  |
# EPerfBottleneck Enum

Namespace: Microsoft.Online.SharePoint.MigrationCenter.Common


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **Packing** |  |
| **Packing_SourceReading** |  |
| **Packing_DiskWriting** |  |
| **Uploading** |  |
| **SPOProcessing** |  |
# MigrationTaskStatus Enum

Namespace: Microsoft.Online.SharePoint.MigrationCenter.Common


## Values

| Name | Summary |
|---|---|
| **NoInit** |  |
| **Inited** |  |
| **Scanning** |  |
| **ScanDone** |  |
| **InProgress** |  |
| **Suspended** |  |
| **Pause** |  |
| **Completed** |  |
# ScheduleType Enum

Namespace: Microsoft.Online.SharePoint.MigrationCenter.Common


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **RunOnce** |  |
| **Daily** |  |
| **Weekly** |  |
| **Monthly** |  |
# SourceType Enum

Namespace: Microsoft.Online.SharePoint.MigrationCenter.Common


## Values

| Name | Summary |
|---|---|
| **FileShare** |  |
| **SharePoint** |  |
# StorageActionId Enum

Namespace: Microsoft.Online.SharePoint.MigrationCenter.Common


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **Update** |  |
| **Upgrade** |  |
| **Debug** |  |
# TaskActionId Enum

Namespace: Microsoft.Online.SharePoint.MigrationCenter.Common


## Values

| Name | Summary |
|---|---|
| **UpdateTaskInfo** |  |
| **PauseTask** |  |
| **ResumeTask** |  |
| **CancelTask** |  |
| **RerunTask** |  |
| **UpdateStatus** |  |
| **AssignTask** |  |
| **DeleteTask** |  |
| **AddTask** |  |
| **Debug** |  |
# TaskErrorCode Enum

Namespace: Microsoft.Online.SharePoint.MigrationCenter.Common


## Values

| Name | Summary |
|---|---|
| **NoError** |  |
| **UnknownError** |  |
| **NoResponse** |  |
| **SourceCredentialsNotFound** |  |
| **SourceCredentialsInvalid** |  |
| **TargetCredentialsNotFound** |  |
| **TargetCredentialsInvalid** |  |
| **InvalidDecryptionKey** |  |
# TaskFailure Enum

Namespace: Microsoft.Online.SharePoint.MigrationCenter.Common


## Values

| Name | Summary |
|---|---|
| **NoFailure** |  |
| **FailedToStartTask** |  |
| **FailedToPauseTask** |  |
| **FailedToResumeTask** |  |
| **FailedToCancelTask** |  |
| **FailedRunningTask** |  |
| **FailedToUploadReport** |  |
# TaskManagementStatus Enum

Namespace: Microsoft.Online.SharePoint.MigrationCenter.Common


## Values

| Name | Summary |
|---|---|
| **Waiting** |  |
| **Assigned** |  |
| **Running** |  |
| **Pausing** |  |
| **Paused** |  |
| **Resuming** |  |
| **Cancelling** |  |
| **Completed** |  |
| **Failed** |  |
| **Scheduled** |  |
# LogExport Class

Namespace: Microsoft.Online.SharePoint.SPLogger

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
| **LogExport(ClientRuntimeContext context)** |  |
| **LogExport(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetFiles(string partitionId, string logType)** | ClientObjectList\<[LogFileInfo](#logfileinfo-class)\> |  |
| **GetLogTypes()** | ClientArrayResult\<string\> |  |
| **GetPartitions(string logType)** | ClientArrayResult\<string\> |  |
# LogFileInfo Class

Namespace: Microsoft.Online.SharePoint.SPLogger

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AlternateUrl** | string |  |
| **DecryptionIV** | byte[] |  |
| **DecryptionKey** | byte[] |  |
| **Exception** | string |  |
| **FileName** | string |  |
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
| **LogFileInfo(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# LogFileInfoPropertyNames Class

Namespace: Microsoft.Online.SharePoint.SPLogger


## Fields

| Name | Type | Summary |
|---|---|---|
| **AlternateUrl** | string |  |
| **DecryptionIV** | string |  |
| **DecryptionKey** | string |  |
| **Exception** | string |  |
| **FileName** | string |  |
| **Url** | string |  |
# DDIAdapter Class

Namespace: Microsoft.Online.SharePoint.TenantAdmin.MiddleTier

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
| **DDIAdapter(ClientRuntimeContext context)** |  |
| **DDIAdapter(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetList(string schema, string workflow, Stream stream)** | ClientResult\<string\> |  |
| **GetObject(string schema, string workflow, Stream stream)** | ClientResult\<string\> |  |
| **MultiObjectExecute(string schema, string workflow, Stream stream)** | ClientResult\<string\> |  |
| **NewObject(string schema, string workflow, Stream stream)** | ClientResult\<string\> |  |
| **RemoveObjects(string schema, string workflow, Stream stream)** | ClientResult\<string\> |  |
| **SetObject(string schema, string workflow, Stream stream)** | ClientResult\<string\> |  |
# AppErrorEntry Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **CorrelationId** | Guid |  |
| **ErrorMessage** | string |  |
| **ErrorType** | [AppErrorType](#apperrortype-enum) |  |
| **InstanceUrl** | string |  |
| **ProductId** | Guid |  |
| **TimeStampInUTC** | DateTime |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **AppErrorEntry(ClientRuntimeContext context)** |  |
| **AppErrorEntry(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# AppErrorEntryPropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Fields

| Name | Type | Summary |
|---|---|---|
| **CorrelationId** | string |  |
| **ErrorMessage** | string |  |
| **ErrorType** | string |  |
| **InstanceUrl** | string |  |
| **ProductId** | string |  |
| **TimeStampInUTC** | string |  |
# AppErrorType Enum

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **InstallError** |  |
| **UpgradeError** |  |
| **RuntimeError** |  |
# AppInfo Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Name** | string |  |
| **ProductId** | Guid |  |
| **Source** | [AppSource](#appsource-enum) |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **AppInfo(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# AppInfoPropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Fields

| Name | Type | Summary |
|---|---|---|
| **Name** | string |  |
| **ProductId** | string |  |
| **Source** | string |  |
# AppSource Enum

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Values

| Name | Summary |
|---|---|
| **CorporateGallery** |  |
| **MarketPlace** |  |
# AppViewsPolicy Enum

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Values

| Name | Summary |
|---|---|
| **Unknown** |  |
| **Disabled** |  |
| **NotDisabled** |  |
# AzureSubscriptionState Enum

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Values

| Name | Summary |
|---|---|
| **Unknown** |  |
| **Active** |  |
| **Deleted** |  |
| **Disabled** |  |
| **Expired** |  |
| **PastDue** |  |
| **Warned** |  |
# CompanyWideSharingLinksPolicy Enum

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Values

| Name | Summary |
|---|---|
| **Unknown** |  |
| **Disabled** |  |
| **NotDisabled** |  |
# CreatePolicyRequest Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **isPreviewRun** | bool |  |
| **policyCustomName** | string |  |
| **policyDefinitionDetails** | string |  |
| **policyDescription** | string |  |
| **policyFrequencyUnit** | PolicyFrequencyUnits |  |
| **policyFrequencyValue** | int |  |
| **policyId** | Guid |  |
| **policyTemplate** | PolicyTemplate |  |
| **policyType** | PolicyTypes |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# DeletedSiteProperties Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ArchiveStatus** | string |  |
| **DaysRemaining** | int |  |
| **DeletionTime** | DateTime |  |
| **SiteId** | Guid |  |
| **Status** | string |  |
| **StorageMaximumLevel** | long |  |
| **Url** | string |  |
| **UserCodeMaximumLevel** | double |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **DeletedSiteProperties(ClientRuntimeContext context, string url)** |  |
| **DeletedSiteProperties(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# DeletedSitePropertiesPropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Fields

| Name | Type | Summary |
|---|---|---|
| **ArchiveStatus** | string |  |
| **DaysRemaining** | string |  |
| **DeletionTime** | string |  |
| **SiteId** | string |  |
| **Status** | string |  |
| **StorageMaximumLevel** | string |  |
| **Url** | string |  |
| **UserCodeMaximumLevel** | string |  |
# DenyAddAndCustomizePagesStatus Enum

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Values

| Name | Summary |
|---|---|
| **Unknown** |  |
| **Disabled** |  |
| **Enabled** |  |
# EsignatureThirdPartyProvidersInfo Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **IsEnabled** | bool |  |
| **ProviderName** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# FileSensitivityLabelInfo Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **DisplayName** | string |  |
| **LabelId** | string |  |
| **ParentLabelId** | string |  |
| **ProtectionEnabled** | bool |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **FileSensitivityLabelInfo(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# FileSensitivityLabelInfoPropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Fields

| Name | Type | Summary |
|---|---|---|
| **DisplayName** | string |  |
| **LabelId** | string |  |
| **ParentLabelId** | string |  |
| **ProtectionEnabled** | string |  |
# FlowsPolicy Enum

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Values

| Name | Summary |
|---|---|
| **Unknown** |  |
| **Disabled** |  |
| **NotDisabled** |  |
# GroupInfo Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **GroupStatusInAAD** | int |  |
| **SiteUrl** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# HubSitePermission Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **DisplayName** | string |  |
| **PrincipalName** | string |  |
| **Rights** | [SPOHubSiteUserRights](#spohubsiteuserrights-enum) |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# HubSiteProperties Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Description** | string |  |
| **EnablePermissionsSync** | bool |  |
| **HideNameInNavigation** | bool |  |
| **ID** | Guid |  |
| **LogoUrl** | string |  |
| **ParentHubSiteId** | Guid |  |
| **Permissions** | IList\<[HubSitePermission](#hubsitepermission-class)\> |  |
| **RequiresJoinApproval** | bool |  |
| **SiteDesignId** | Guid |  |
| **SiteId** | Guid |  |
| **SiteUrl** | string |  |
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
| **HubSiteProperties(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Update()** | void |  |
# HubSitePropertiesPropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Fields

| Name | Type | Summary |
|---|---|---|
| **Description** | string |  |
| **EnablePermissionsSync** | string |  |
| **HideNameInNavigation** | string |  |
| **ID** | string |  |
| **LogoUrl** | string |  |
| **ParentHubSiteId** | string |  |
| **Permissions** | string |  |
| **RequiresJoinApproval** | string |  |
| **SiteDesignId** | string |  |
| **SiteId** | string |  |
| **SiteUrl** | string |  |
| **Title** | string |  |
# ISPOPortalLaunchValidator Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration


# MessagesFieldsData Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **bearToken** | string |  |
| **environment** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# ObjectCharacterRecognitionMode Enum

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Values

| Name | Summary |
|---|---|
| **Disabled** |  |
| **InclusionList** |  |
| **ExclusionList** |  |
# OdbMigrationStatus Enum

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Values

| Name | Summary |
|---|---|
| **NotStarted** |  |
| **InProgress** |  |
| **Completed** |  |
| **Failed** |  |
| **Invalid** |  |
# PersonalSiteFilter Enum

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Values

| Name | Summary |
|---|---|
| **UseServerDefault** |  |
| **Include** |  |
| **Exclude** |  |
# PowerAppsEnvironment Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# PowerAppsEnvironmentContext Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **DataverseInstanceUrl** | string |  |
| **DisplayName** | string |  |
| **IsTestEnvironment** | bool |  |
| **LastGetEnvironmentError** | string |  |
| **Name** | string |  |
| **UpdatedUTC** | DateTime |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# PWAEnabledStatus Enum

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Values

| Name | Summary |
|---|---|
| **Unknown** |  |
| **Disabled** |  |
| **Enabled** |  |
# RecentAdminActionReportPayload Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **actions** | string |  |
| **name** | string |  |
| **queryEndDate** | DateTime |  |
| **queryStartDate** | DateTime |  |
| **reportType** | ChangeHistoryReportType |  |
| **sites** | string |  |
| **users** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# RestrictedToRegion Enum

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Values

| Name | Summary |
|---|---|
| **NoRestriction** |  |
| **BlockMoveOnly** |  |
| **BlockFull** |  |
| **Unknown** |  |
# SandboxedCodeActivationCapabilities Enum

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Values

| Name | Summary |
|---|---|
| **Unknown** |  |
| **Check** |  |
| **Disabled** |  |
| **Enabled** |  |
# SecondaryAdministratorsFieldsData Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **secondaryAdministratorEmails** | string[] |  |
| **secondaryAdministratorLoginNames** | string[] |  |
| **siteId** | Guid |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SecondaryAdministratorsInfo Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **email** | string |  |
| **loginName** | string |  |
| **name** | string |  |
| **userPrincipalName** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SiteAdministratorsFieldsData Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **siteAdministrators** | string[] |  |
| **siteId** | Guid |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SiteAdministratorsInfo Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **email** | string |  |
| **loginName** | string |  |
| **name** | string |  |
| **userPrincipalName** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SiteCreationProperties Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **CompatibilityLevel** | int |  |
| **Lcid** | uint |  |
| **Owner** | string |  |
| **StorageMaximumLevel** | long |  |
| **StorageWarningLevel** | long |  |
| **Template** | string |  |
| **TimeZoneId** | int |  |
| **Title** | string |  |
| **Url** | string |  |
| **UserCodeMaximumLevel** | double |  |
| **UserCodeWarningLevel** | double |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SiteInfoForSitePicker Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Error** | string |  |
| **SiteId** | Guid |  |
| **SiteName** | string |  |
| **Url** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SiteProperties Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AllowDownloadingNonWebViewableFiles** | bool |  |
| **AllowEditing** | bool |  |
| **AllowSelfServiceUpgrade** | bool |  |
| **AnonymousLinkExpirationInDays** | int |  |
| **ArchiveStatus** | string |  |
| **AuthContextStrength** | string |  |
| **AuthenticationContextLimitedAccess** | bool |  |
| **AuthenticationContextName** | string |  |
| **AverageResourceUsage** | double |  |
| **BlockDownloadLinksFileType** | [BlockDownloadLinksFileTypes](#blockdownloadlinksfiletypes-enum) |  |
| **BlockDownloadMicrosoft365GroupIds** | Guid[] |  |
| **BlockDownloadPolicy** | bool |  |
| **BlockGuestsAsSiteAdmin** | SharingState |  |
| **BonusDiskQuota** | long |  |
| **ClearRestrictedAccessControl** | bool |  |
| **CommentsOnSitePagesDisabled** | bool |  |
| **CompatibilityLevel** | int |  |
| **ConditionalAccessPolicy** | [SPOConditionalAccessPolicyType](#spoconditionalaccesspolicytype-enum) |  |
| **CurrentResourceUsage** | double |  |
| **DefaultLinkPermission** | [SharingPermissionType](#sharingpermissiontype-enum) |  |
| **DefaultLinkToExistingAccess** | bool |  |
| **DefaultLinkToExistingAccessReset** | bool |  |
| **DefaultShareLinkRole** | Role |  |
| **DefaultShareLinkScope** | SharingScope |  |
| **DefaultSharingLinkType** | [SharingLinkType](#sharinglinktype-enum) |  |
| **DenyAddAndCustomizePages** | [DenyAddAndCustomizePagesStatus](#denyaddandcustomizepagesstatus-enum) |  |
| **Description** | string |  |
| **DisableAppViews** | [AppViewsPolicy](#appviewspolicy-enum) |  |
| **DisableCompanyWideSharingLinks** | [CompanyWideSharingLinksPolicy](#companywidesharinglinkspolicy-enum) |  |
| **DisableFlows** | [FlowsPolicy](#flowspolicy-enum) |  |
| **ExcludeBlockDownloadPolicySiteOwners** | bool |  |
| **ExcludeBlockDownloadSharePointGroups** | string[] |  |
| **ExcludedBlockDownloadGroupIds** | Guid[] |  |
| **ExternalUserExpirationInDays** | int |  |
| **GroupId** | Guid |  |
| **GroupOwnerLoginName** | string |  |
| **HasHolds** | bool |  |
| **HubSiteId** | Guid |  |
| **IBMode** | string |  |
| **IBSegments** | Guid[] |  |
| **IBSegmentsToAdd** | Guid[] |  |
| **IBSegmentsToRemove** | Guid[] |  |
| **IsGroupOwnerSiteAdmin** | bool |  |
| **IsHubSite** | bool |  |
| **IsTeamsChannelConnected** | bool |  |
| **IsTeamsConnected** | bool |  |
| **LastContentModifiedDate** | DateTime |  |
| **Lcid** | uint |  |
| **LimitedAccessFileType** | [SPOLimitedAccessFileType](#spolimitedaccessfiletype-enum) |  |
| **ListsShowHeaderAndNavigation** | bool |  |
| **LockIssue** | string |  |
| **LockState** | string |  |
| **LoopDefaultSharingLinkRole** | Role |  |
| **LoopDefaultSharingLinkScope** | SharingScope |  |
| **LoopOverrideSharingCapability** | bool |  |
| **LoopSharingCapability** | [SharingCapabilities](#sharingcapabilities-enum) |  |
| **MediaTranscription** | [MediaTranscriptionPolicyType](#mediatranscriptionpolicytype-enum) |  |
| **OverrideBlockUserInfoVisibility** | [SiteUserInfoVisibilityPolicyValue](#siteuserinfovisibilitypolicyvalue-enum) |  |
| **OverrideSharingCapability** | bool |  |
| **OverrideTenantAnonymousLinkExpirationPolicy** | bool |  |
| **OverrideTenantExternalUserExpirationPolicy** | bool |  |
| **Owner** | string |  |
| **OwnerEmail** | string |  |
| **OwnerLoginName** | string |  |
| **OwnerName** | string |  |
| **PWAEnabled** | [PWAEnabledStatus](#pwaenabledstatus-enum) |  |
| **ReadOnlyAccessPolicy** | bool |  |
| **ReadOnlyForBlockDownloadPolicy** | bool |  |
| **ReadOnlyForUnmanagedDevices** | bool |  |
| **RelatedGroupId** | Guid |  |
| **RequestFilesLinkEnabled** | bool |  |
| **RequestFilesLinkExpirationInDays** | int |  |
| **RestrictedAccessControl** | bool |  |
| **RestrictedAccessControlGroups** | Guid[] |  |
| **RestrictedAccessControlGroupsToAdd** | Guid[] |  |
| **RestrictedAccessControlGroupsToRemove** | Guid[] |  |
| **RestrictedToRegion** | [RestrictedToRegion](#restrictedtoregion-enum) |  |
| **SandboxedCodeActivationCapability** | [SandboxedCodeActivationCapabilities](#sandboxedcodeactivationcapabilities-enum) |  |
| **SensitivityLabel** | Guid |  |
| **SensitivityLabel2** | string |  |
| **SetOwnerWithoutUpdatingSecondaryAdmin** | bool |  |
| **SharingAllowedDomainList** | string |  |
| **SharingBlockedDomainList** | string |  |
| **SharingCapability** | [SharingCapabilities](#sharingcapabilities-enum) |  |
| **SharingDomainRestrictionMode** | [SharingDomainRestrictionModes](#sharingdomainrestrictionmodes-enum) |  |
| **SharingLockDownCanBeCleared** | bool |  |
| **SharingLockDownEnabled** | bool |  |
| **ShowPeoplePickerSuggestionsForGuestUsers** | bool |  |
| **SiteDefinedSharingCapability** | [SharingCapabilities](#sharingcapabilities-enum) |  |
| **SiteId** | Guid |  |
| **SocialBarOnSitePagesDisabled** | bool |  |
| **Status** | string |  |
| **StorageMaximumLevel** | long |  |
| **StorageQuotaType** | string |  |
| **StorageUsage** | long |  |
| **StorageWarningLevel** | long |  |
| **TeamsChannelType** | [TeamsChannelTypeValue](#teamschanneltypevalue-enum) |  |
| **Template** | string |  |
| **TimeZoneId** | int |  |
| **Title** | string |  |
| **TitleTranslations** | IEnumerable\<SPResourceEntry\> |  |
| **Url** | string |  |
| **UserCodeMaximumLevel** | double |  |
| **UserCodeWarningLevel** | double |  |
| **WebsCount** | int |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **SiteProperties(ClientRuntimeContext context, string url)** |  |
| **SiteProperties(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **ClearSharingLockDown(ClientRuntimeContext context, string siteUrl)** | void |  |
| **Update()** | [SpoOperation](#spooperation-class) |  |
# SitePropertiesPropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Fields

| Name | Type | Summary |
|---|---|---|
| **AllowDownloadingNonWebViewableFiles** | string |  |
| **AllowEditing** | string |  |
| **AllowSelfServiceUpgrade** | string |  |
| **AnonymousLinkExpirationInDays** | string |  |
| **ArchiveStatus** | string |  |
| **AuthContextStrength** | string |  |
| **AuthenticationContextLimitedAccess** | string |  |
| **AuthenticationContextName** | string |  |
| **AverageResourceUsage** | string |  |
| **BlockDownloadLinksFileType** | string |  |
| **BlockDownloadMicrosoft365GroupIds** | string |  |
| **BlockDownloadPolicy** | string |  |
| **BlockGuestsAsSiteAdmin** | string |  |
| **BonusDiskQuota** | string |  |
| **ClearRestrictedAccessControl** | string |  |
| **CommentsOnSitePagesDisabled** | string |  |
| **CompatibilityLevel** | string |  |
| **ConditionalAccessPolicy** | string |  |
| **CurrentResourceUsage** | string |  |
| **DefaultLinkPermission** | string |  |
| **DefaultLinkToExistingAccess** | string |  |
| **DefaultLinkToExistingAccessReset** | string |  |
| **DefaultShareLinkRole** | string |  |
| **DefaultShareLinkScope** | string |  |
| **DefaultSharingLinkType** | string |  |
| **DenyAddAndCustomizePages** | string |  |
| **Description** | string |  |
| **DisableAppViews** | string |  |
| **DisableCompanyWideSharingLinks** | string |  |
| **DisableFlows** | string |  |
| **ExcludeBlockDownloadPolicySiteOwners** | string |  |
| **ExcludeBlockDownloadSharePointGroups** | string |  |
| **ExcludedBlockDownloadGroupIds** | string |  |
| **ExternalUserExpirationInDays** | string |  |
| **GroupId** | string |  |
| **GroupOwnerLoginName** | string |  |
| **HasHolds** | string |  |
| **HubSiteId** | string |  |
| **IBMode** | string |  |
| **IBSegments** | string |  |
| **IBSegmentsToAdd** | string |  |
| **IBSegmentsToRemove** | string |  |
| **IsGroupOwnerSiteAdmin** | string |  |
| **IsHubSite** | string |  |
| **IsTeamsChannelConnected** | string |  |
| **IsTeamsConnected** | string |  |
| **LastContentModifiedDate** | string |  |
| **Lcid** | string |  |
| **LimitedAccessFileType** | string |  |
| **ListsShowHeaderAndNavigation** | string |  |
| **LockIssue** | string |  |
| **LockState** | string |  |
| **LoopDefaultSharingLinkRole** | string |  |
| **LoopDefaultSharingLinkScope** | string |  |
| **LoopOverrideSharingCapability** | string |  |
| **LoopSharingCapability** | string |  |
| **MediaTranscription** | string |  |
| **OverrideBlockUserInfoVisibility** | string |  |
| **OverrideSharingCapability** | string |  |
| **OverrideTenantAnonymousLinkExpirationPolicy** | string |  |
| **OverrideTenantExternalUserExpirationPolicy** | string |  |
| **Owner** | string |  |
| **OwnerEmail** | string |  |
| **OwnerLoginName** | string |  |
| **OwnerName** | string |  |
| **PWAEnabled** | string |  |
| **ReadOnlyAccessPolicy** | string |  |
| **ReadOnlyForBlockDownloadPolicy** | string |  |
| **ReadOnlyForUnmanagedDevices** | string |  |
| **RelatedGroupId** | string |  |
| **RequestFilesLinkEnabled** | string |  |
| **RequestFilesLinkExpirationInDays** | string |  |
| **RestrictedAccessControl** | string |  |
| **RestrictedAccessControlGroups** | string |  |
| **RestrictedAccessControlGroupsToAdd** | string |  |
| **RestrictedAccessControlGroupsToRemove** | string |  |
| **RestrictedToRegion** | string |  |
| **SandboxedCodeActivationCapability** | string |  |
| **SensitivityLabel** | string |  |
| **SensitivityLabel2** | string |  |
| **SetOwnerWithoutUpdatingSecondaryAdmin** | string |  |
| **SharingAllowedDomainList** | string |  |
| **SharingBlockedDomainList** | string |  |
| **SharingCapability** | string |  |
| **SharingDomainRestrictionMode** | string |  |
| **SharingLockDownCanBeCleared** | string |  |
| **SharingLockDownEnabled** | string |  |
| **ShowPeoplePickerSuggestionsForGuestUsers** | string |  |
| **SiteDefinedSharingCapability** | string |  |
| **SiteId** | string |  |
| **SocialBarOnSitePagesDisabled** | string |  |
| **Status** | string |  |
| **StorageMaximumLevel** | string |  |
| **StorageQuotaType** | string |  |
| **StorageUsage** | string |  |
| **StorageWarningLevel** | string |  |
| **TeamsChannelType** | string |  |
| **Template** | string |  |
| **TimeZoneId** | string |  |
| **Title** | string |  |
| **TitleTranslations** | string |  |
| **Url** | string |  |
| **UserCodeMaximumLevel** | string |  |
| **UserCodeWarningLevel** | string |  |
| **WebsCount** | string |  |
# SiteRenameStatesInTenantRename Enum

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Values

| Name | Summary |
|---|---|
| **NotStarted** |  |
| **InProgress** |  |
| **Success** |  |
| **AttentionRequired** |  |
# SiteUserGroupInfo Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **userGroup** | IList\<[UserInfo](#userinfo-class)\> |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SiteUserGroupsData Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **members** | [UserInfo](#userinfo-class)[] |  |
| **owners** | [UserInfo](#userinfo-class)[] |  |
| **siteId** | Guid |  |
| **visitors** | [UserInfo](#userinfo-class)[] |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SiteUserInfoVisibilityPolicyValue Enum

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Values

| Name | Summary |
|---|---|
| **OrganizationDefault** |  |
| **ApplyToNoUsers** |  |
| **ApplyToGuestAndExternalUsers** |  |
| **ApplyToInternalUsers** |  |
| **ApplyToAllUsers** |  |
# SPContainerCollection Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ContainerCollection** | IList\<[SPContainerProperties](#spcontainerproperties-class)\> |  |
| **PagingToken** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SPContainerProperties Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AllowEditing** | bool |  |
| **AuthenticationContextName** | string |  |
| **BlockDownloadPolicy** | bool |  |
| **ConditionalAccessPolicy** | [SPOConditionalAccessPolicyType](#spoconditionalaccesspolicytype-enum) |  |
| **ContainerApiUrl** | string |  |
| **ContainerId** | string |  |
| **ContainerName** | string |  |
| **ContainerSiteUrl** | string |  |
| **ContainerTypeId** | Guid |  |
| **CreatedBy** | string |  |
| **CreatedOn** | DateTime |  |
| **Description** | string |  |
| **ExcludeBlockDownloadPolicyContainerOwners** | bool |  |
| **LimitedAccessFileType** | [SPOLimitedAccessFileType](#spolimitedaccessfiletype-enum) |  |
| **Managers** | IList\<string\> |  |
| **Owners** | IList\<string\> |  |
| **OwningApplicationId** | Guid |  |
| **OwningApplicationName** | string |  |
| **Readers** | IList\<string\> |  |
| **ReadOnlyForBlockDownloadPolicy** | bool |  |
| **ReadOnlyForUnmanagedDevices** | bool |  |
| **SensitivityLabel** | string |  |
| **SharingAllowedDomainList** | string |  |
| **SharingBlockedDomainList** | string |  |
| **SharingDomainRestrictionMode** | [SharingDomainRestrictionModes](#sharingdomainrestrictionmodes-enum) |  |
| **Status** | string |  |
| **StorageUsed** | long |  |
| **Writers** | IList\<string\> |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SPContainerTypeBillingClassification Enum

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Values

| Name | Summary |
|---|---|
| **Standard** |  |
| **Trial** |  |
# SPContainerTypeConfigurationProperties Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ApplicationRedirectUrl** | string |  |
| **Classification** | [SPContainerTypeBillingClassification](#spcontainertypebillingclassification-enum) |  |
| **ContainerTypeId** | Guid |  |
| **ContainerTypeName** | string |  |
| **IsDiscoverablilityDisabled** | bool |  |
| **IsMoveDisabled** | bool |  |
| **IsRenameDisabled** | bool |  |
| **IsSharingRestricted** | bool |  |
| **OwningAppId** | Guid |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SPContainerTypeProperties Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AzureSubscriptionId** | Guid |  |
| **ContainerTypeId** | Guid |  |
| **CreationDate** | string |  |
| **DisplayName** | string |  |
| **ExpiryDate** | string |  |
| **IsBillingProfileRequired** | bool |  |
| **OwningAppId** | Guid |  |
| **OwningTenantId** | Guid |  |
| **Region** | string |  |
| **ResourceGroup** | string |  |
| **SPContainerTypeBillingClassification** | [SPContainerTypeBillingClassification](#spcontainertypebillingclassification-enum) |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SPContainerTypeTenantType Enum

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Values

| Name | Summary |
|---|---|
| **OwningTenant** |  |
| **ConsumingTenant** |  |
# SPDeletedContainerProperties Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ContainerId** | string |  |
| **ContainerName** | string |  |
| **CreatedOn** | DateTime |  |
| **DeletedOn** | DateTime |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SPDeletedContainerTypeProperties Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ContainerTypeId** | Guid |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SPODeletedSitePropertiesEnumerable Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientObjectCollection<[DeletedSiteProperties](#deletedsiteproperties-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **NextStartIndex** | int |  |
| **NextStartIndexFromSharePoint** | string |  |
| **Item** | [DeletedSiteProperties](#deletedsiteproperties-class) |  |
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
| **SPODeletedSitePropertiesEnumerable(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# SPODeletedSitePropertiesEnumerablePropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Fields

| Name | Type | Summary |
|---|---|---|
| **NextStartIndex** | string |  |
| **NextStartIndexFromSharePoint** | string |  |
# SPOHubSiteUserRights Enum

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **Join** |  |
# SPOMalwareFile Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **File** | File |  |
| **FilePath** | ResourcePath |  |
| **MalwareInfo** | string |  |
| **MalwareStatus** | SPVirusCheckStatus |  |
| **SiteURL** | string |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **SPOMalwareFile(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetMalwareFileStream()** | ClientResult\<Stream\> |  |
# SPOMalwareFileObjectPropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Fields

| Name | Type | Summary |
|---|---|---|
| **File** | string |  |
# SPOMalwareFilePropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Fields

| Name | Type | Summary |
|---|---|---|
| **FilePath** | string |  |
| **MalwareInfo** | string |  |
| **MalwareStatus** | string |  |
| **SiteURL** | string |  |
# SpoOperation Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **HasTimedout** | bool |  |
| **IsComplete** | bool |  |
| **PollingInterval** | int |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **SpoOperation(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# SpoOperationPropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Fields

| Name | Type | Summary |
|---|---|---|
| **HasTimedout** | string |  |
| **IsComplete** | string |  |
| **PollingInterval** | string |  |
# SPOPortalLaunchValidationResult Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Message** | string |  |
| **ResultType** | [SPOPortalLaunchValidationResultTypes](#spoportallaunchvalidationresulttypes-enum) |  |
| **Warnings** | string[] |  |
| **WaveSetupContent** | string |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **SPOPortalLaunchValidationResult(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# SPOPortalLaunchValidationResultPropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Fields

| Name | Type | Summary |
|---|---|---|
| **Message** | string |  |
| **ResultType** | string |  |
| **Warnings** | string |  |
| **WaveSetupContent** | string |  |
# SPOPortalLaunchValidationResultTypes Enum

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Values

| Name | Summary |
|---|---|
| **Passed** |  |
| **ConfirmDefaultPage** |  |
| **ConfirmChange** |  |
| **Warning** |  |
| **Failed** |  |
# SPOPortalLaunchValidator Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

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
| **SPOPortalLaunchValidator(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# SpoSiteLockState Enum

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Values

| Name | Summary |
|---|---|
| **Unlock** |  |
| **NoAdditions** |  |
| **ReadOnly** |  |
| **NoAccess** |  |
# SPOSitePropertiesEnumerable Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientObjectCollection<[SiteProperties](#siteproperties-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **NextStartIndex** | int |  |
| **NextStartIndexFromSharePoint** | string |  |
| **Item** | [SiteProperties](#siteproperties-class) |  |
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
| **SPOSitePropertiesEnumerable(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# SPOSitePropertiesEnumerableFilter Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ArchiveStatus** | string |  |
| **Filter** | string |  |
| **GroupIdDefined** | int |  |
| **IncludeDetail** | bool |  |
| **IncludePersonalSite** | [PersonalSiteFilter](#personalsitefilter-enum) |  |
| **StartIndex** | string |  |
| **Template** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SPOSitePropertiesEnumerablePropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Fields

| Name | Type | Summary |
|---|---|---|
| **NextStartIndex** | string |  |
| **NextStartIndexFromSharePoint** | string |  |
# SPOTenantCdnPolicy Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **PolicyType** | [SPOTenantCdnPolicyType](#spotenantcdnpolicytype-enum) |  |
| **PolicyValue** | string |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **SPOTenantCdnPolicy(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# SPOTenantCdnPolicyPropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Fields

| Name | Type | Summary |
|---|---|---|
| **PolicyType** | string |  |
| **PolicyValue** | string |  |
# SPOTenantCdnPolicyType Enum

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Values

| Name | Summary |
|---|---|
| **IncludeFileExtensions** |  |
| **ExcludeRestrictedSiteClassifications** |  |
| **ExcludeIfNoScriptDisabled** |  |
| **ExcludeRestrictedSiteClassificationsFileExtensions** |  |
# SPOTenantCdnType Enum

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Values

| Name | Summary |
|---|---|
| **Public** |  |
| **Private** |  |
# SPOTenantGroupIdentityMapping Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **GroupType** | TenantIdentityMappingGroupType |  |
| **SourceGroupObjectId** | Guid |  |
| **SourceTenantCompanyId** | Guid |  |
| **TargetGroupName** | string |  |
| **TargetGroupObjectId** | Guid |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **SPOTenantGroupIdentityMapping(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# SPOTenantGroupIdentityMappingPropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Fields

| Name | Type | Summary |
|---|---|---|
| **GroupType** | string |  |
| **SourceGroupObjectId** | string |  |
| **SourceTenantCompanyId** | string |  |
| **TargetGroupName** | string |  |
| **TargetGroupObjectId** | string |  |
# SPOTenantInstance Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **DataLocation** | string |  |
| **IsDefaultDataLocation** | bool |  |
| **MySiteHostUrl** | string |  |
| **PortalUrl** | string |  |
| **RootSiteUrl** | string |  |
| **TenantAdminUrl** | string |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **SPOTenantInstance(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# SPOTenantInstancePropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Fields

| Name | Type | Summary |
|---|---|---|
| **DataLocation** | string |  |
| **IsDefaultDataLocation** | string |  |
| **MySiteHostUrl** | string |  |
| **PortalUrl** | string |  |
| **RootSiteUrl** | string |  |
| **TenantAdminUrl** | string |  |
# SPOTenantOdbFeature Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **FeatureDescription** | string |  |
| **FeatureId** | Guid |  |
| **FeatureName** | string |  |
| **Message** | string |  |
| **Scope** | FeatureScope |  |
| **UserPrincipleName** | string |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **SPOTenantOdbFeature(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# SPOTenantOdbFeaturePropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Fields

| Name | Type | Summary |
|---|---|---|
| **FeatureDescription** | string |  |
| **FeatureId** | string |  |
| **FeatureName** | string |  |
| **Message** | string |  |
| **Scope** | string |  |
| **UserPrincipleName** | string |  |
# SPOTenantSiteUserInvitation Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **DocId** | Guid |  |
| **EmailAddress** | string |  |
| **ShareId** | Guid |  |
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
| **SPOTenantSiteUserInvitation(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# SPOTenantSiteUserInvitationPropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Fields

| Name | Type | Summary |
|---|---|---|
| **DocId** | string |  |
| **EmailAddress** | string |  |
| **ShareId** | string |  |
| **SiteId** | string |  |
| **WebId** | string |  |
# SPOTenantUserIdentityMapping Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **SourceTenantCompanyId** | Guid |  |
| **SourceUserKey** | string |  |
| **TargetUserEmail** | string |  |
| **TargetUserPuid** | string |  |
| **TargetUserUpn** | string |  |
| **UserType** | TenantIdentityMappingUserType |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **SPOTenantUserIdentityMapping(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# SPOTenantUserIdentityMappingPropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Fields

| Name | Type | Summary |
|---|---|---|
| **SourceTenantCompanyId** | string |  |
| **SourceUserKey** | string |  |
| **TargetUserEmail** | string |  |
| **TargetUserPuid** | string |  |
| **TargetUserUpn** | string |  |
| **UserType** | string |  |
# SPOTenantWebTemplate Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **CompatibilityLevel** | int |  |
| **Description** | string |  |
| **DisplayCategory** | string |  |
| **Id** | int |  |
| **Lcid** | uint |  |
| **Name** | string |  |
| **Title** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SPOTenantWebTemplateCollection Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientObjectCollection<[SPOTenantWebTemplate](#spotenantwebtemplate-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [SPOTenantWebTemplate](#spotenantwebtemplate-class) |  |
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
| **SPOTenantWebTemplateCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# SPOWebAppServicePrincipalPublic Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

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
| **SPOWebAppServicePrincipalPublic(ClientRuntimeContext context)** |  |
| **SPOWebAppServicePrincipalPublic(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **AddCustomSpfx3rdPartyAppPrincipal(string appId, string appUri, string clientSecret)** | void |  |
| **GetCustomSpfx3rdPartyAppPrincipal()** | Spfx3rdPartyCustomPrincipalInfo |  |
| **RemoveCustomSpfx3rdPartyAppPrincipal()** | void |  |
| **UpdateCustomSpfx3rdPartyAppPrincipalClientSecret(string clientSecret)** | void |  |
# SPSyntexApplicationProperties Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ApplicationId** | Guid |  |
| **ApplicationName** | string |  |
| **Applications** | IList\<Guid\> |  |
| **AppOnlyPermissions** | IList\<string\> |  |
| **DelegatedPermissions** | IList\<string\> |  |
| **OwningApplicationId** | Guid |  |
| **OwningApplicationName** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SyntexBillingContext Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ActivationStatus** | [SyntexConsumptionBillingActivationStatus](#syntexconsumptionbillingactivationstatus-enum) |  |
| **AzureResourceId** | string |  |
| **AzureSubscriptionState** | [AzureSubscriptionState](#azuresubscriptionstate-enum) |  |
| **EnabledFeatures** | [SyntexConsumptionBillingEnabledFeatures](#syntexconsumptionbillingenabledfeatures-enum) |  |
| **Location** | string |  |
| **Updated** | DateTime |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SyntexConsumptionBillingActivationStatus Enum

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Values

| Name | Summary |
|---|---|
| **Unknown** |  |
| **None** |  |
| **Active** |  |
# SyntexConsumptionBillingEnabledFeatures Enum

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **DocumentUnderstanding** |  |
| **ContentAssembly** |  |
# SyntexPowerAppsEnvironmentsContext Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Environments** | IEnumerable\<[PowerAppsEnvironmentContext](#powerappsenvironmentcontext-class)\> |  |
| **TimerJobSyncDisabled** | bool |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SyntexPremiumFeatureSettings Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **SiteList** | IEnumerable\<Guid\> |  |
| **SiteListFileName** | string |  |
| **Status** | [SyntexSiteSpecificFeatureStatus](#syntexsitespecificfeaturestatus-enum) |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# SyntexSiteSpecificFeatureStatus Enum

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Values

| Name | Summary |
|---|---|
| **Disabled** |  |
| **Enabled** |  |
| **EnabledWithNoSites** |  |
| **DisabledWithNoSites** |  |
# TeamsChannelTypeValue Enum

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **PrivateChannel** |  |
| **SharedChannel** |  |
| **StandardChannel** |  |
# Tenant Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AddressbarLinkPermission** | Role |  |
| **AIBuilderDefaultPowerAppsEnvironment** | string |  |
| **AIBuilderEnabled** | bool |  |
| **AIBuilderEnabledInContentCenter** | int |  |
| **AIBuilderSiteInfoList** | IEnumerable\<[SiteInfoForSitePicker](#siteinfoforsitepicker-class)\> |  |
| **AIBuilderSiteList** | IEnumerable\<Guid\> |  |
| **AIBuilderSiteListFileName** | string |  |
| **AllowAnonymousMeetingParticipantsToAccessWhiteboards** | SharingState |  |
| **AllowCommentsTextOnEmailEnabled** | bool |  |
| **AllowDownloadingNonWebViewableFiles** | bool |  |
| **AllowedDomainListForSyncClient** | IList\<Guid\> |  |
| **AllowEditing** | bool |  |
| **AllowEveryoneExceptExternalUsersClaimInPrivateSite** | bool |  |
| **AllowGuestUserShareToUsersNotInSiteCollection** | bool |  |
| **AllowLimitedAccessOnUnmanagedDevices** | bool |  |
| **AllowOverrideForBlockUserInfoVisibility** | bool |  |
| **AllowSelectSecurityGroupsInSPSitesList** | IList\<string\> |  |
| **AllowSelectSGsInODBListInTenant** | IList\<string\> |  |
| **AllowSensitivityLabelOnRecords** | bool |  |
| **AmplifyAdminSettings** | string |  |
| **AnyoneLinkTrackUsers** | bool |  |
| **AppBypassInformationBarriers** | bool |  |
| **ApplyAppEnforcedRestrictionsToAdHocRecipients** | bool |  |
| **AppOnlyBypassPeoplePickerPolicies** | bool |  |
| **ArchiveRedirectUrl** | string |  |
| **AuthContextResilienceMode** | SPResilienceModeType |  |
| **BccExternalSharingInvitations** | bool |  |
| **BccExternalSharingInvitationsList** | string |  |
| **BlockAccessOnUnmanagedDevices** | bool |  |
| **BlockAppAccessWithAuthenticationContext** | bool |  |
| **BlockDownloadFileTypeIds** | SPBlockDownloadFileTypeId[] |  |
| **BlockDownloadFileTypePolicy** | bool |  |
| **BlockDownloadLinksFileType** | [BlockDownloadLinksFileTypes](#blockdownloadlinksfiletypes-enum) |  |
| **BlockDownloadOfAllFilesForGuests** | bool |  |
| **BlockDownloadOfAllFilesOnUnmanagedDevices** | bool |  |
| **BlockDownloadOfViewableFilesForGuests** | bool |  |
| **BlockDownloadOfViewableFilesOnUnmanagedDevices** | bool |  |
| **BlockMacSync** | bool |  |
| **BlockSendLabelMismatchEmail** | bool |  |
| **BlockUserInfoVisibility** | string |  |
| **BlockUserInfoVisibilityInOneDrive** | [TenantBrowseUserInfoPolicyValue](#tenantbrowseuserinfopolicyvalue-enum) |  |
| **BlockUserInfoVisibilityInSharePoint** | [TenantBrowseUserInfoPolicyValue](#tenantbrowseuserinfopolicyvalue-enum) |  |
| **BonusStorageQuotaMB** | long |  |
| **BusinessConnectivityServiceDisabled** | bool |  |
| **CommentsOnFilesDisabled** | bool |  |
| **CommentsOnListItemsDisabled** | bool |  |
| **CommentsOnSitePagesDisabled** | bool |  |
| **CompatibilityRange** | string |  |
| **ConditionalAccessPolicy** | [SPOConditionalAccessPolicyType](#spoconditionalaccesspolicytype-enum) |  |
| **ConditionalAccessPolicyErrorHelpLink** | string |  |
| **ContainerDefaultLinkToExistingAccess** | bool |  |
| **ContainerDefaultShareLinkRole** | Role |  |
| **ContainerDefaultShareLinkScope** | SharingScope |  |
| **ContainerLoopDefaultShareLinkRole** | Role |  |
| **ContainerLoopDefaultShareLinkScope** | SharingScope |  |
| **ContainerSharingCapability** | [SharingCapabilities](#sharingcapabilities-enum) |  |
| **ContentTypeSyncSiteTemplatesList** | IEnumerable\<string\> |  |
| **CoreBlockGuestsAsSiteAdmin** | SharingState |  |
| **CoreDefaultLinkToExistingAccess** | bool |  |
| **CoreDefaultShareLinkRole** | Role |  |
| **CoreDefaultShareLinkScope** | SharingScope |  |
| **CoreLoopDefaultSharingLinkRole** | Role |  |
| **CoreLoopDefaultSharingLinkScope** | SharingScope |  |
| **CoreLoopSharingCapability** | [SharingCapabilities](#sharingcapabilities-enum) |  |
| **CoreRequestFilesLinkEnabled** | bool |  |
| **CoreRequestFilesLinkExpirationInDays** | int |  |
| **CoreSharingCapability** | [SharingCapabilities](#sharingcapabilities-enum) |  |
| **CustomizedExternalSharingServiceUrl** | string |  |
| **DefaultContentCenterSite** | [SiteInfoForSitePicker](#siteinfoforsitepicker-class) |  |
| **DefaultLinkPermission** | [SharingPermissionType](#sharingpermissiontype-enum) |  |
| **DefaultODBMode** | string |  |
| **DefaultSharingLinkType** | [SharingLinkType](#sharinglinktype-enum) |  |
| **DelayDenyAddAndCustomizePagesEnforcement** | bool |  |
| **DenySelectSecurityGroupsInSPSitesList** | IList\<string\> |  |
| **DenySelectSGsInODBListInTenant** | IList\<string\> |  |
| **DisableAddToOneDrive** | bool |  |
| **DisableBackToClassic** | bool |  |
| **DisableCustomAppAuthentication** | bool |  |
| **DisabledModernListTemplateIds** | Guid[] |  |
| **DisableDocumentLibraryDefaultLabeling** | bool |  |
| **DisabledWebPartIds** | Guid[] |  |
| **DisableOutlookPSTVersionTrimming** | bool |  |
| **DisablePersonalListCreation** | bool |  |
| **DisableReportProblemDialog** | bool |  |
| **DisableSpacesActivation** | bool |  |
| **DisableVivaConnectionsAnalytics** | bool |  |
| **DisallowInfectedFileDownload** | bool |  |
| **DisplayNamesOfFileViewers** | bool |  |
| **DisplayNamesOfFileViewersInSpo** | bool |  |
| **DisplayStartASiteOption** | bool |  |
| **DocumentUnderstandingEnabled** | bool |  |
| **DocumentUnderstandingSiteInfoList** | IEnumerable\<[SiteInfoForSitePicker](#siteinfoforsitepicker-class)\> |  |
| **DocumentUnderstandingSiteList** | IEnumerable\<Guid\> |  |
| **DocumentUnderstandingSiteListFileName** | string |  |
| **EmailAttestationEnabled** | bool |  |
| **EmailAttestationReAuthDays** | int |  |
| **EmailAttestationRequired** | bool |  |
| **EnableAIPIntegration** | bool |  |
| **EnableAutoExpirationVersionTrim** | bool |  |
| **EnableAutoNewsDigest** | bool |  |
| **EnableAzureADB2BIntegration** | bool |  |
| **EnabledFlightAllowAADB2BSkipCheckingOTP** | bool |  |
| **EnableGuestSignInAcceleration** | bool |  |
| **EnableMinimumVersionRequirement** | bool |  |
| **EnableMipSiteLabel** | bool |  |
| **EnablePromotedFileHandlers** | bool |  |
| **EnableRestrictedAccessControl** | bool |  |
| **EnableSensitivityLabelForPDF** | bool |  |
| **EnableSiteArchive** | bool |  |
| **EnableTenantRestrictionsInsights** | bool |  |
| **ESignatureEnabled** | bool |  |
| **ESignatureSiteInfoList** | IEnumerable\<[SiteInfoForSitePicker](#siteinfoforsitepicker-class)\> |  |
| **ESignatureSiteList** | IEnumerable\<Guid\> |  |
| **ESignatureSiteListFileName** | string |  |
| **ESignatureThirdPartyProviderInfoList** | IEnumerable\<[EsignatureThirdPartyProvidersInfo](#esignaturethirdpartyprovidersinfo-class)\> |  |
| **ESignatureThirdPartyProviderList** | IEnumerable\<string\> |  |
| **ESignatureThirdPartyProviderListFileName** | string |  |
| **ExcludedBlockDownloadGroupIds** | Guid[] |  |
| **ExcludedFileExtensionsForSyncClient** | IList\<string\> |  |
| **ExemptNativeUsersFromTenantLevelRestricedAccessControl** | bool |  |
| **ExpireVersionsAfterDays** | int |  |
| **ExternalServicesEnabled** | bool |  |
| **ExternalUserExpirationRequired** | bool |  |
| **ExternalUserExpireInDays** | int |  |
| **FileAnonymousLinkType** | AnonymousLinkType |  |
| **FilePickerExternalImageSearchEnabled** | bool |  |
| **FileVersionPolicyXml** | string |  |
| **FolderAnonymousLinkType** | AnonymousLinkType |  |
| **GuestSharingGroupAllowListInTenant** | string |  |
| **GuestSharingGroupAllowListInTenantByPrincipalIdentity** | IList\<string\> |  |
| **HasAdminCompletedCUConfiguration** | bool |  |
| **HasIntelligentContentServicesCapability** | bool |  |
| **HasTopicExperiencesCapability** | bool |  |
| **HideDefaultThemes** | bool |  |
| **HideSyncButtonOnDocLib** | bool |  |
| **HideSyncButtonOnODB** | bool |  |
| **IBImplicitGroupBased** | bool |  |
| **ImageTaggingOption** | [ImageTaggingChoice](#imagetaggingchoice-enum) |  |
| **IncludeAtAGlanceInShareEmails** | bool |  |
| **InformationBarriersSuspension** | bool |  |
| **IPAddressAllowList** | string |  |
| **IPAddressEnforcement** | bool |  |
| **IPAddressWACTokenLifetime** | int |  |
| **IsAppBarTemporarilyDisabled** | bool |  |
| **IsCollabMeetingNotesFluidEnabled** | bool |  |
| **IsDataAccessInCardDesignerEnabled** | bool |  |
| **IsEnableAppAuthPopUpEnabled** | bool |  |
| **IsFluidEnabled** | bool |  |
| **IsHubSitesMultiGeoFlightEnabled** | bool |  |
| **IsLoopEnabled** | bool |  |
| **IsMnAFlightEnabled** | bool |  |
| **IsMultiGeo** | bool |  |
| **IsMultipleHomeSitesFlightEnabled** | bool |  |
| **IsMultipleVivaConnectionsFlightEnabled** | bool |  |
| **IsRansomwareProtectionEnabled** | bool |  |
| **IsUnmanagedSyncClientForTenantRestricted** | bool |  |
| **IsUnmanagedSyncClientRestrictionFlightEnabled** | bool |  |
| **IsVivaHomeFlightEnabled** | bool |  |
| **IsVivaHomeGAFlightEnabled** | bool |  |
| **IsWBFluidEnabled** | bool |  |
| **LabelMismatchEmailHelpLink** | string |  |
| **LegacyAuthProtocolsEnabled** | bool |  |
| **LegacyBrowserAuthProtocolsEnabled** | bool |  |
| **LimitedAccessFileType** | [SPOLimitedAccessFileType](#spolimitedaccessfiletype-enum) |  |
| **MachineLearningCaptureEnabled** | bool |  |
| **MajorVersionLimit** | int |  |
| **MarkAllFilesAsSensitiveByDefault** | bool |  |
| **MarkNewFilesSensitiveByDefault** | [SensitiveByDefaultState](#sensitivebydefaultstate-enum) |  |
| **MassDeleteNotificationDisabled** | bool |  |
| **MediaTranscription** | [MediaTranscriptionPolicyType](#mediatranscriptionpolicytype-enum) |  |
| **MediaTranscriptionAutomaticFeatures** | [MediaTranscriptionAutomaticFeaturesPolicyType](#mediatranscriptionautomaticfeaturespolicytype-enum) |  |
| **MobileFriendlyUrlEnabledInTenant** | bool |  |
| **NoAccessRedirectUrl** | string |  |
| **NotificationsInOneDriveForBusinessEnabled** | bool |  |
| **NotificationsInSharePointEnabled** | bool |  |
| **NotifyOwnersWhenInvitationsAccepted** | bool |  |
| **NotifyOwnersWhenItemsReshared** | bool |  |
| **OCRAdminSiteInfoList** | IEnumerable\<[SiteInfoForSitePicker](#siteinfoforsitepicker-class)\> |  |
| **OCRAdminSiteList** | IEnumerable\<Guid\> |  |
| **OCRAdminSiteListFileName** | string |  |
| **OCRComplianceSiteInfoList** | IEnumerable\<[SiteInfoForSitePicker](#siteinfoforsitepicker-class)\> |  |
| **OCRComplianceSiteList** | IEnumerable\<Guid\> |  |
| **OCRComplianceSiteListFileName** | string |  |
| **OCRModeForAdminSites** | [ObjectCharacterRecognitionMode](#objectcharacterrecognitionmode-enum) |  |
| **OCRModeForComplianceODBs** | [ObjectCharacterRecognitionMode](#objectcharacterrecognitionmode-enum) |  |
| **OCRModeForComplianceSites** | [ObjectCharacterRecognitionMode](#objectcharacterrecognitionmode-enum) |  |
| **ODBAccessRequests** | SharingState |  |
| **ODBMembersCanShare** | SharingState |  |
| **ODBSensitivityRefreshWindowInHours** | ushort |  |
| **ODBSharingCapability** | [SharingCapabilities](#sharingcapabilities-enum) |  |
| **OfficeClientADALDisabled** | bool |  |
| **OneDriveBlockGuestsAsSiteAdmin** | SharingState |  |
| **OneDriveDefaultLinkToExistingAccess** | bool |  |
| **OneDriveDefaultShareLinkRole** | Role |  |
| **OneDriveDefaultShareLinkScope** | SharingScope |  |
| **OneDriveForGuestsEnabled** | bool |  |
| **OneDriveLoopDefaultSharingLinkRole** | Role |  |
| **OneDriveLoopDefaultSharingLinkScope** | SharingScope |  |
| **OneDriveLoopSharingCapability** | [SharingCapabilities](#sharingcapabilities-enum) |  |
| **OneDriveRequestFilesLinkEnabled** | bool |  |
| **OneDriveRequestFilesLinkExpirationInDays** | int |  |
| **OneDriveStorageQuota** | long |  |
| **OptOutOfGrooveBlock** | bool |  |
| **OptOutOfGrooveSoftBlock** | bool |  |
| **OrgNewsSiteUrl** | string |  |
| **OrphanedPersonalSitesRetentionPeriod** | int |  |
| **OwnerAnonymousNotification** | bool |  |
| **PermissiveBrowserFileHandlingOverride** | bool |  |
| **PrebuiltEnabled** | bool |  |
| **PrebuiltSiteInfoList** | IEnumerable\<[SiteInfoForSitePicker](#siteinfoforsitepicker-class)\> |  |
| **PrebuiltSiteList** | IEnumerable\<Guid\> |  |
| **PrebuiltSiteListFileName** | string |  |
| **PreventExternalUsersFromResharing** | bool |  |
| **ProvisionSharedWithEveryoneFolder** | bool |  |
| **PublicCdnAllowedFileTypes** | string |  |
| **PublicCdnEnabled** | bool |  |
| **PublicCdnOrigins** | IList\<string\> |  |
| **RecycleBinRetentionPeriod** | int |  |
| **ReduceTempTokenLifetimeEnabled** | bool |  |
| **ReduceTempTokenLifetimeValue** | int |  |
| **RequireAcceptingAccountMatchInvitedAccount** | bool |  |
| **RequireAnonymousLinksExpireInDays** | int |  |
| **ResourceQuota** | double |  |
| **ResourceQuotaAllocated** | double |  |
| **RestrictedOneDriveLicense** | bool |  |
| **RestrictedSharePointLicense** | bool |  |
| **RootSiteUrl** | string |  |
| **SearchResolveExactEmailOrUPN** | bool |  |
| **SharingAllowedDomainList** | string |  |
| **SharingBlockedDomainList** | string |  |
| **SharingCapability** | [SharingCapabilities](#sharingcapabilities-enum) |  |
| **SharingDomainRestrictionMode** | [SharingDomainRestrictionModes](#sharingdomainrestrictionmodes-enum) |  |
| **ShowAllUsersClaim** | bool |  |
| **ShowEveryoneClaim** | bool |  |
| **ShowEveryoneExceptExternalUsersClaim** | bool |  |
| **ShowNGSCDialogForSyncOnODB** | bool |  |
| **ShowOpenInDesktopOptionForSyncedFiles** | bool |  |
| **ShowPeoplePickerGroupSuggestionsForIB** | bool |  |
| **ShowPeoplePickerSuggestionsForGuestUsers** | bool |  |
| **SignInAccelerationDomain** | string |  |
| **SiteOwnerManageLegacyServicePrincipalEnabled** | bool |  |
| **SocialBarOnSitePagesDisabled** | bool |  |
| **SpecialCharactersStateInFileFolderNames** | [SpecialCharactersState](#specialcharactersstate-enum) |  |
| **StartASiteFormUrl** | string |  |
| **StopNew2010Workflows** | bool |  |
| **StopNew2013Workflows** | bool |  |
| **StorageQuota** | long |  |
| **StorageQuotaAllocated** | long |  |
| **StreamLaunchConfig** | int |  |
| **StreamLaunchConfigLastUpdated** | DateTime |  |
| **StreamLaunchConfigUpdateCount** | int |  |
| **SyncPrivacyProfileProperties** | bool |  |
| **SyntexBillingSubscriptionSettings** | [SyntexBillingContext](#syntexbillingcontext-class) |  |
| **SyntexExternalVideoSharingSettings** | [SyntexPremiumFeatureSettings](#syntexpremiumfeaturesettings-class) |  |
| **SyntexHighResolutionPlaybackSettings** | [SyntexPremiumFeatureSettings](#syntexpremiumfeaturesettings-class) |  |
| **SyntexInternalFeatureFlags** | IDictionary\<string, bool\> |  |
| **SyntexMediaAnalyticsSettings** | [SyntexPremiumFeatureSettings](#syntexpremiumfeaturesettings-class) |  |
| **SyntexPaygFeatureActivations** | IDictionary\<string, string\> |  |
| **SyntexPlaybackTranscriptTranslationSettings** | [SyntexPremiumFeatureSettings](#syntexpremiumfeaturesettings-class) |  |
| **SyntexPowerAppsEnvironmentsContext** | [SyntexPowerAppsEnvironmentsContext](#syntexpowerappsenvironmentscontext-class) |  |
| **TaxonomyTaggingEnabled** | bool |  |
| **TaxonomyTaggingSiteInfoList** | IEnumerable\<[SiteInfoForSitePicker](#siteinfoforsitepicker-class)\> |  |
| **TaxonomyTaggingSiteList** | IEnumerable\<Guid\> |  |
| **TaxonomyTaggingSiteListFileName** | string |  |
| **TlsTokenBindingPolicyValue** | [SPOTlsTokenBindingPolicyValue](#spotlstokenbindingpolicyvalue-enum) |  |
| **TranslationEnabled** | bool |  |
| **TranslationSiteInfoList** | IEnumerable\<[SiteInfoForSitePicker](#siteinfoforsitepicker-class)\> |  |
| **TranslationSiteList** | IEnumerable\<Guid\> |  |
| **TranslationSiteListFileName** | string |  |
| **UseFindPeopleInPeoplePicker** | bool |  |
| **UsePersistentCookiesForExplorerView** | bool |  |
| **UserVoiceForFeedbackEnabled** | bool |  |
| **ViewersCanCommentOnMediaDisabled** | bool |  |
| **ViewInFileExplorerEnabled** | bool |  |
| **WhoCanShareAllowListInTenant** | string |  |
| **WhoCanShareAllowListInTenantByPrincipalIdentity** | IList\<string\> |  |
| **Workflow2010Disabled** | bool |  |
| **Workflows2013State** | [Workflows2013State](#workflows2013state-enum) |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **Tenant(ClientRuntimeContext context)** |  |
| **Tenant(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **AddBrandTenantFontPackage(TenantFontPackageCreationParameters tenantFontPackageCreationParams)** | [TenantFontPackage](#tenantfontpackage-class) |  |
| **AddHomeSite(string homeSiteUrl, int order, Guid[] audiences)** | ClientResult\<TargetedSiteDetails\> |  |
| **AddOrUpdateTenantIdentityMap(string[] mapItems)** | IList\<string\> |  |
| **AddOrUpdateTenantSingleGroupIdentityMappingItem(Guid sourceTenantCompanyId, Guid sourceGroupObjectId, Guid targetGroupObjectId, string targetGroupName, TenantIdentityMappingGroupType groupType)** | void |  |
| **AddOrUpdateTenantSingleUserIdentityMappingItem(Guid sourceTenantCompanyId, string sourceUserKey, string targetUserPuid, string targetUserUpn, string targetUserEmail, TenantIdentityMappingUserType userType)** | void |  |
| **AddPublicCdnOrigin(string origin)** | void |  |
| **AddSdnProvider(string identifier, string license)** | void |  |
| **AddSiteDesignTask(ClientRuntimeContext context, string webUrl, Guid siteDesignId)** | [TenantSiteDesignTask](#tenantsitedesigntask-class) |  |
| **AddTenantCdnOrigin(SPOTenantCdnType cdnType, string originUrl)** | void |  |
| **AddTenantOdbFeature(IList\<string\> userPrincipleNames, FeatureScope scope, IList\<Guid\> featureIds)** | ClientObjectList\<[SPOTenantOdbFeature](#spotenantodbfeature-class)\> |  |
| **AddTenantSingleUserOdbFeature(string userPrincipleName, FeatureScope scope, IList\<Guid\> featureIds)** | ClientObjectList\<[SPOTenantOdbFeature](#spotenantodbfeature-class)\> |  |
| **AddTenantTheme(string name, string themeJson)** | ClientResult\<bool\> |  |
| **AddToOrgAssetsLibAndCdn(SPOTenantCdnType cdnType, string libUrl, string thumbnailUrl)** | void |  |
| **AddToOrgAssetsLibAndCdnV2(SPOTenantCdnType cdnType, string libUrl, string thumbnailUrl, OrgAssetType orgAssetType, bool defaultOriginAdded)** | void |  |
| **AddToOrgAssetsLibAndCdnWithType(SPOTenantCdnType cdnType, string libUrl, string thumbnailUrl, OrgAssetType orgAssetType)** | void |  |
| **ApplyBrandFontPackageById(Guid fontPackageID, string targetWebUrl)** | void |  |
| **ApplyListDesign(string webUrl, Guid listDesignId)** | ClientObjectList\<[TenantSiteScriptActionResult](#tenantsitescriptactionresult-class)\> |  |
| **ApplySiteDesign(string webUrl, Guid siteDesignId)** | ClientObjectList\<[TenantSiteScriptActionResult](#tenantsitescriptactionresult-class)\> |  |
| **ArchiveSiteById(Guid siteId)** | [SpoOperation](#spooperation-class) |  |
| **ArchiveSiteByUrl(string siteUrl)** | [SpoOperation](#spooperation-class) |  |
| **CheckMnATenantIdentityMapCallCorrectness()** | ClientResult\<MnATenantIdentityMapCallCorrectnessCheckResult\> |  |
| **ConnectSiteToHubSite(string siteUrl, string hubSiteUrl)** | void |  |
| **ConnectSiteToHubSiteById(string siteUrl, Guid hubSiteId)** | void |  |
| **CreateGroupForSite(string siteUrl, string displayName, string alias, bool isPublic, GroupCreationParams optionalParams)** | void |  |
| **CreateListDesign(TenantListDesignCreationInfo info)** | [TenantListDesign](#tenantlistdesign-class) |  |
| **CreatePortalLaunchWaves(string portalLaunchWaveSetupString, bool isWhatIf, bool isTesting, bool changeConfirmed)** | [SPOPortalLaunchValidationResult](#spoportallaunchvalidationresult-class) |  |
| **CreateSite(SiteCreationProperties siteCreationProperties)** | [SpoOperation](#spooperation-class) |  |
| **CreateSiteDesign(TenantSiteDesignCreationInfo info)** | [TenantSiteDesign](#tenantsitedesign-class) |  |
| **CreateSiteScript(TenantSiteScriptCreationInfo info)** | [TenantSiteScript](#tenantsitescript-class) |  |
| **CreateSiteScriptPackage(TenantSiteScriptCreationInfo info)** | [TenantSiteScript](#tenantsitescript-class) |  |
| **CreateSiteSharingReportJobForTenantAdmin(string siteUrl, string reportWebUrl, string reportFolderUrl)** | ClientResult\<string\> |  |
| **CreateTenantCdnDefaultOrigins(SPOTenantCdnType cdnType)** | void |  |
| **DecodeClaim(string identifier)** | ClientResult\<string\> |  |
| **DecodeClaims(IList\<string\> claims)** | IList\<string\> |  |
| **DeleteSiteDesign(Guid id)** | void |  |
| **DeleteSiteScript(Guid id)** | void |  |
| **DeleteSPOContainerTypeById(Guid containerTypeId)** | void |  |
| **DeleteTenantTheme(string name)** | void |  |
| **DisableSpacesActivationOnSite(string siteUrl, bool disable)** | void |  |
| **DisconnectSiteFromHubSite(string siteUrl)** | void |  |
| **EnableCommunicationSite(string siteUrl, Guid designPackageId)** | ClientResult\<string\> |  |
| **EncodeClaim(string identifier)** | ClientResult\<string\> |  |
| **EncodeClaims(IList\<string\> identifiers)** | IList\<string\> |  |
| **GetAllDeletedPersonalSitesPropertiesAllVersions(int startIndex)** | [SPODeletedSitePropertiesEnumerable](#spodeletedsitepropertiesenumerable-class) |  |
| **GetAllOutOfBoxSiteTemplateSettings()** | IList\<[TenantOutOfBoxSiteTemplateSettings](#tenantoutofboxsitetemplatesettings-class)\> |  |
| **GetAllPortalLaunchWaves()** | ClientResult\<string\> |  |
| **GetAllTenantThemes()** | ClientObjectList\<[ThemeProperties](#themeproperties-class)\> |  |
| **GetAppErrors(Guid productId, DateTime timeStart, DateTime timeEnd)** | ClientObjectList\<[AppErrorEntry](#apperrorentry-class)\> |  |
| **GetAppInfoByName(string name)** | ClientObjectList\<[AppInfo](#appinfo-class)\> |  |
| **GetAppInfoByProductId(Guid productId)** | ClientObjectList\<[AppInfo](#appinfo-class)\> |  |
| **GetBrandTenantFontPackageById(Guid fontPackageID)** | [TenantFontPackage](#tenantfontpackage-class) |  |
| **GetBrandTenantFontPackages()** | ClientObjectList\<[TenantFontPackage](#tenantfontpackage-class)\> |  |
| **GetCustomFontsMinorVersion(string libUrl)** | ClientResult\<int\> |  |
| **GetDeletedPersonalSitePropertiesAllVersions(string url)** | [SPODeletedSitePropertiesEnumerable](#spodeletedsitepropertiesenumerable-class) |  |
| **GetDeletedSiteProperties(int startIndex)** | [SPODeletedSitePropertiesEnumerable](#spodeletedsitepropertiesenumerable-class) |  |
| **GetDeletedSitePropertiesByUrl(string siteUrl)** | [DeletedSiteProperties](#deletedsiteproperties-class) |  |
| **GetDeletedSitePropertiesFromSharePoint(string startIndex)** | [SPODeletedSitePropertiesEnumerable](#spodeletedsitepropertiesenumerable-class) |  |
| **GetFileSensitivityLabelInfo(string fileUrl)** | [FileSensitivityLabelInfo](#filesensitivitylabelinfo-class) |  |
| **GetHiddenBuiltInDesignPackages(ClientRuntimeContext context)** | ClientResult\<DesignPackageType\> |  |
| **GetHomeSites()** | IList\<HomeSitesDetails\> |  |
| **GetHomeSitesDetails()** | IList\<HomeSitesDetails\> |  |
| **GetHubSitePropertiesById(Guid hubSiteId)** | [HubSiteProperties](#hubsiteproperties-class) |  |
| **GetHubSitePropertiesByUrl(string siteUrl)** | [HubSiteProperties](#hubsiteproperties-class) |  |
| **GetHubSitesProperties()** | ClientObjectList\<[HubSiteProperties](#hubsiteproperties-class)\> |  |
| **GetIdleSessionSignOutForUnmanagedDevices()** | ClientResult\<string\> |  |
| **GetKnowledgeHubSite()** | ClientResult\<string\> |  |
| **GetLandingSites(string userId)** | IList\<TargetedSiteDetails\> |  |
| **GetListDesign(ClientRuntimeContext context, Guid id)** | [TenantListDesign](#tenantlistdesign-class) |  |
| **GetListDesigns()** | ClientObjectList\<[TenantListDesign](#tenantlistdesign-class)\> |  |
| **GetMalwareInfectedFileInfo(string fileUri)** | [SPOMalwareFile](#spomalwarefile-class) |  |
| **GetMySiteHostUrl()** | ClientResult\<string\> |  |
| **GetOrgAssets()** | ClientResult\<OrgAssets\> |  |
| **GetOrgNewsSites()** | IEnumerable\<string\> |  |
| **GetOrgRelationTargetGroupManagedPath(string targetMySiteHostUrl)** | ClientResult\<string\> |  |
| **GetOutOfBoxSiteTemplateSettings(ClientRuntimeContext context, Guid id)** | ClientResult\<[TenantOutOfBoxSiteTemplateSettings](#tenantoutofboxsitetemplatesettings-class)\> |  |
| **GetPersonalSiteUrl(string userPrincipalName)** | ClientResult\<string\> |  |
| **GetPortalLaunchWaves(string siteUrl)** | ClientResult\<string\> |  |
| **GetRootSiteUrl()** | ClientResult\<string\> |  |
| **GetSiteByUrl(string url)** | Site |  |
| **GetSiteDesign(ClientRuntimeContext context, Guid id)** | [TenantSiteDesign](#tenantsitedesign-class) |  |
| **GetSiteDesignRights(ClientRuntimeContext context, Guid id)** | ClientObjectList\<[TenantSiteDesignPrincipal](#tenantsitedesignprincipal-class)\> |  |
| **GetSiteDesignRun(string webUrl, Guid siteDesignId)** | ClientObjectList\<[TenantSiteDesignRun](#tenantsitedesignrun-class)\> |  |
| **GetSiteDesignRunStatus(Guid siteId, Guid webId, Guid runId)** | ClientObjectList\<[TenantSiteScriptActionStatus](#tenantsitescriptactionstatus-class)\> |  |
| **GetSiteDesigns()** | ClientObjectList\<[TenantSiteDesign](#tenantsitedesign-class)\> |  |
| **GetSiteDesignTask(ClientRuntimeContext context, Guid id)** | [TenantSiteDesignTask](#tenantsitedesigntask-class) |  |
| **GetSiteDesignTasks(string webUrl)** | ClientObjectList\<[TenantSiteDesignTask](#tenantsitedesigntask-class)\> |  |
| **GetSiteProperties(int startIndex, bool includeDetail)** | [SPOSitePropertiesEnumerable](#spositepropertiesenumerable-class) |  |
| **GetSitePropertiesByFilter(string filter, int startIndex, bool includeDetail)** | [SPOSitePropertiesEnumerable](#spositepropertiesenumerable-class) |  |
| **GetSitePropertiesByUrl(string url, bool includeDetail)** | [SiteProperties](#siteproperties-class) |  |
| **GetSitePropertiesFromSharePoint(string startIndex, bool includeDetail)** | [SPOSitePropertiesEnumerable](#spositepropertiesenumerable-class) |  |
| **GetSitePropertiesFromSharePointByFilter(string filter, string startIndex, bool includeDetail)** | [SPOSitePropertiesEnumerable](#spositepropertiesenumerable-class) |  |
| **GetSitePropertiesFromSharePointByFilters(SPOSitePropertiesEnumerableFilter speFilter)** | [SPOSitePropertiesEnumerable](#spositepropertiesenumerable-class) |  |
| **GetSiteScript(ClientRuntimeContext context, Guid id)** | [TenantSiteScript](#tenantsitescript-class) |  |
| **GetSiteScriptFromList(ClientRuntimeContext context, string listUrl)** | ClientResult\<string\> |  |
| **GetSiteScriptFromSite(string webUrl, TenantSiteScriptSerializationInfo info)** | ClientResult\<[TenantSiteScriptSerializationResult](#tenantsitescriptserializationresult-class)\> |  |
| **GetSiteScriptPackageFile(Guid id)** | ClientResult\<Stream\> |  |
| **GetSiteScriptPackageFromSite(string webUrl, TenantSiteScriptSerializationInfo info)** | ClientResult\<[TenantSiteScriptSerializationResult](#tenantsitescriptserializationresult-class)\> |  |
| **GetSiteScripts()** | ClientObjectList\<[TenantSiteScript](#tenantsitescript-class)\> |  |
| **GetSPHSiteUrl()** | ClientResult\<string\> |  |
| **GetSPOAllWebTemplates(string cultureName, int compatibilityLevel)** | [SPOTenantWebTemplateCollection](#spotenantwebtemplatecollection-class) |  |
| **GetSPOContainerByContainerId(string containerId)** | ClientResult\<[SPContainerProperties](#spcontainerproperties-class)\> |  |
| **GetSPOContainerByContainerSiteUrl(string containerSiteUrl)** | ClientResult\<[SPContainerProperties](#spcontainerproperties-class)\> |  |
| **GetSPOContainersByApplicationId(Guid owningApplicationId, bool paged, string pagingToken)** | ClientResult\<[SPContainerCollection](#spcontainercollection-class)\> |  |
| **GetSPOContainerTypeById(Guid containerTypeId, SPContainerTypeTenantType containerTenantType)** | ClientResult\<[SPContainerTypeProperties](#spcontainertypeproperties-class)\> |  |
| **GetSPOContainerTypeConfigurationByContainerTypeId(Guid containerTypeId)** | ClientResult\<[SPContainerTypeConfigurationProperties](#spcontainertypeconfigurationproperties-class)\> |  |
| **GetSPOContainerTypes(SPContainerTypeTenantType containerTenantType)** | IList\<[SPContainerTypeProperties](#spcontainertypeproperties-class)\> |  |
| **GetSPODeletedContainers()** | IList\<[SPDeletedContainerProperties](#spdeletedcontainerproperties-class)\> |  |
| **GetSPOStructuralNavigationCacheSiteState(string siteUrl)** | ClientResult\<bool\> |  |
| **GetSPOStructuralNavigationCacheWebState(string webUrl)** | ClientResult\<bool\> |  |
| **GetSPOSyntexApplications()** | IList\<[SPSyntexApplicationProperties](#spsyntexapplicationproperties-class)\> |  |
| **GetSPOSyntexConsumingApplications(Guid owningApplicationId, Guid applicationId)** | ClientResult\<[SPSyntexApplicationProperties](#spsyntexapplicationproperties-class)\> |  |
| **GetSPOTenantAllWebTemplates()** | [SPOTenantWebTemplateCollection](#spotenantwebtemplatecollection-class) |  |
| **GetSPOTenantOrgRelationAll()** | ClientResult\<string\> |  |
| **GetSPOTenantOrgRelationByPartner(string partnerMySiteHostUrl)** | ClientResult\<string\> |  |
| **GetSPOTenantOrgRelationByScenario(OrgRelationScenario scenario, OrgRelationRole partnerRole)** | ClientResult\<string\> |  |
| **GetSPOTenantSiteUserInvitations(string siteUrl, string emailAddress)** | ClientObjectList\<[SPOTenantSiteUserInvitation](#spotenantsiteuserinvitation-class)\> |  |
| **GetSPOTenantWebTemplates(uint localeId, int compatibilityLevel)** | [SPOTenantWebTemplateCollection](#spotenantwebtemplatecollection-class) |  |
| **GetTargetedSitesDetails()** | IList\<TargetedSiteDetails\> |  |
| **GetTargetedSitesDetailsByUserId(string userId)** | IList\<TargetedSiteDetails\> |  |
| **GetTenantCdnEnabled(SPOTenantCdnType cdnType)** | ClientResult\<bool\> |  |
| **GetTenantCdnOrigins(SPOTenantCdnType cdnType)** | IList\<string\> |  |
| **GetTenantCdnPolicies(SPOTenantCdnType cdnType)** | IList\<string\> |  |
| **GetTenantGroupIdentityMappingItem(TenantIdentityMappingGroupField field, string value)** | ClientObjectList\<[SPOTenantGroupIdentityMapping](#spotenantgroupidentitymapping-class)\> |  |
| **GetTenantInstances()** | ClientObjectList\<[SPOTenantInstance](#spotenantinstance-class)\> |  |
| **GetTenantTheme(string name)** | [ThemeProperties](#themeproperties-class) |  |
| **GetTenantUserIdentityMappingItem(TenantIdentityMappingUserField field, string value)** | ClientObjectList\<[SPOTenantUserIdentityMapping](#spotenantuseridentitymapping-class)\> |  |
| **GetUserMigrationProperties(string userPrincipalName)** | [UserMigrationProperties](#usermigrationproperties-class) |  |
| **GetUserMigrationPropertiesByFilter(UserMigrationPropertiesEnumerableFilter userMigrationPropertiesEnumerableFilter)** | [UserMigrationPropertiesEnumerable](#usermigrationpropertiesenumerable-class) |  |
| **GetVivaConnectionsLicense()** | ClientResult\<VivaConnectionsLicense\> |  |
| **GrantHubSiteRights(string hubSiteUrl, string[] principals, SPOHubSiteUserRights grantedRights)** | [HubSiteProperties](#hubsiteproperties-class) |  |
| **GrantHubSiteRightsById(Guid hubSiteId, string[] principals, SPOHubSiteUserRights grantedRights)** | [HubSiteProperties](#hubsiteproperties-class) |  |
| **GrantSiteDesignRights(Guid id, string[] principalNames, TenantSiteDesignPrincipalRights grantedRights)** | void |  |
| **IncrementCustomFontsMinorVersion(string libUrl)** | void |  |
| **IsCustomFontsOAuthEnabled()** | ClientResult\<bool\> |  |
| **IsDraftModeForCompanyPortalSiteEnabled()** | ClientResult\<bool\> |  |
| **IsMnACmdletCorrectnessCheckEnabled()** | ClientResult\<bool\> |  |
| **IsMnALicensingEnabledForTenant(MnALicenseType licenseType, string partnerMySiteHostUrl)** | ClientResult\<bool\> |  |
| **IsMnALicensingEnabledForUser(string sourceUserUPN, string targetUserUPN, string partnerMySiteHostUrl)** | ClientResult\<MnAUserLicenseCheckResult\> |  |
| **IsMnALicensingFlightEnabled()** | ClientResult\<bool\> |  |
| **IsOfficeFontLibraryOrgAssetFlightEnabled(OrgAssetType orgAssetType)** | void |  |
| **IsTenantReadyForIdentityChange()** | ClientResult\<bool\> |  |
| **IsValidCommSite(string spSiteUrl)** | ClientResult\<bool\> |  |
| **IsVivaConnectionsDefaultStartForCompanyPortalSiteEnabled()** | ClientResult\<bool\> |  |
| **LogCustomFontsLargeUpload(int numCatalogs, int numFonts, int totalExpectedFiles)** | void |  |
| **MnAGroupConnectedPreValidation(string sourceGroupObjectId, string targetGroupAlias, string partnerMySiteHostUrl)** | ClientResult\<MnAGroupConnectedPreValidationCheckResult\> |  |
| **NewSPOContainerType(SPContainerTypeProperties containerTypeProperties)** | ClientResult\<[SPContainerTypeProperties](#spcontainertypeproperties-class)\> |  |
| **NewSPOTenantOrgRelation(OrgRelationScenario scenario, OrgRelationRole partnerRole, string partnerMySiteHostUrl)** | void |  |
| **PurgeSPODeletedContainerByContainerId(string containerId)** | ClientResult\<bool\> |  |
| **PurgeSPODeletedContainerByContainerSiteUrl(string containerSiteUrl)** | ClientResult\<bool\> |  |
| **RegisterHubSite(string siteUrl)** | [HubSiteProperties](#hubsiteproperties-class) |  |
| **RegisterHubSiteWithCreationInformation(string siteUrl, HubSiteCreationInformation creationInformation)** | [HubSiteProperties](#hubsiteproperties-class) |  |
| **RemoveBrandFontPackageById(Guid fontPackageID)** | void |  |
| **RemoveDeletedSite(string siteUrl)** | [SpoOperation](#spooperation-class) |  |
| **RemoveDeletedSitePreferId(string siteUrl, Guid siteId)** | [SpoOperation](#spooperation-class) |  |
| **RemoveFromOrgAssets(string libUrl, Guid listId)** | void |  |
| **RemoveFromOrgAssetsAndCdn(bool remove, SPOTenantCdnType cdnType, string libUrl)** | void |  |
| **RemoveHomeSite(string homeSiteUrl)** | void |  |
| **RemoveKnowledgeHubSite()** | ClientResult\<string\> |  |
| **RemoveListDesign(Guid id)** | void |  |
| **RemoveOrgNewsSite(string orgNewsSiteUrl)** | ClientResult\<string\> |  |
| **RemovePortalLaunchWaves(string siteUrl, bool deletionConfirmed)** | [SPOPortalLaunchValidationResult](#spoportallaunchvalidationresult-class) |  |
| **RemovePreviousCustomFontUpload(IList\<string\> majVersions, string libUrl)** | void |  |
| **RemovePublicCdnOrigin(string originId)** | void |  |
| **RemoveSdnProvider()** | void |  |
| **RemoveSite(string siteUrl)** | [SpoOperation](#spooperation-class) |  |
| **RemoveSiteDesignTask(ClientRuntimeContext context, Guid taskId)** | void |  |
| **RemoveSiteSharingReportJobForTenantAdmin(string siteUrl)** | ClientResult\<string\> |  |
| **RemoveSPHSite()** | ClientResult\<string\> |  |
| **RemoveSPOContainerByContainerId(string containerId)** | void |  |
| **RemoveSPOContainerByContainerSiteUrl(string containerSiteUrl)** | void |  |
| **RemoveSPOContainerType(SPDeletedContainerTypeProperties spDeletedContainerTypeProperties)** | void |  |
| **RemoveSPOTenantOrgRelation(OrgRelationScenario scenario, OrgRelationRole partnerRole, string partnerMySiteHostUrl)** | void |  |
| **RemoveSPOTenantSiteUserInvitations(string siteUrl, string emailAddress, bool countOnly)** | ClientResult\<int\> |  |
| **RemoveTargetedSite(Guid siteId)** | void |  |
| **RemoveTenantCdnOrigin(SPOTenantCdnType cdnType, string originUrl)** | void |  |
| **RemoveTenantGroupIdentityMappingItem(TenantIdentityMappingGroupField field, string value)** | void |  |
| **RemoveTenantUserIdentityMappingItem(TenantIdentityMappingUserField field, string value)** | void |  |
| **ReorderTargetedSites(Guid[] siteIds)** | IList\<TargetedSiteDetails\> |  |
| **RequestPersonalSites(string[] userIds)** | [SpoOperation](#spooperation-class) |  |
| **RestoreDeletedSite(string siteUrl)** | [SpoOperation](#spooperation-class) |  |
| **RestoreDeletedSiteById(Guid siteId)** | [SpoOperation](#spooperation-class) |  |
| **RestoreDeletedSitePreferId(string siteUrl, Guid siteId)** | [SpoOperation](#spooperation-class) |  |
| **RestoreSPODeletedContainerByContainerId(string containerId)** | ClientResult\<bool\> |  |
| **RestoreSPODeletedContainerByContainerSiteUrl(string containerSiteUrl)** | ClientResult\<bool\> |  |
| **RevokeHubSiteRights(string hubSiteUrl, string[] principals)** | [HubSiteProperties](#hubsiteproperties-class) |  |
| **RevokeHubSiteRightsById(Guid hubSiteId, string[] principals)** | [HubSiteProperties](#hubsiteproperties-class) |  |
| **RevokeSiteDesignRights(ClientRuntimeContext context, Guid id, string[] principalNames)** | void |  |
| **SavePortalLaunchWaves(string portalLaunchWaveSetupString, bool isTesting, bool changeConfirmed)** | [SPOPortalLaunchValidationResult](#spoportallaunchvalidationresult-class) |  |
| **SetBlockDownloadFileTypePolicyData(bool blockDownloadFileTypePolicy, SPBlockDownloadFileTypeId[] typeId, Guid[] excludedBlockDownloadGroupIds)** | void |  |
| **SetBlockDownloadFileTypePolicyExclusionList(Guid[] excludedBlockDownloadGroupIds)** | void |  |
| **SetBuiltInDesignPackageVisibility(ClientRuntimeContext context, DesignPackageType designPackageType, bool isVisible)** | void |  |
| **SetFileVersionPolicy(bool isAutoTrimEnabled, int majorVersionLimit, int expireVersionsAfterDays)** | void |  |
| **SetIdleSessionSignOutForUnmanagedDevices(bool enabled, TimeSpan warnAfter, TimeSpan signOutAfter)** | ClientResult\<bool\> |  |
| **SetKnowledgeHubSite(string knowledgeHubSiteUrl)** | ClientResult\<string\> |  |
| **SetOrgAssets(string libUrl, string thumbnailUrl)** | void |  |
| **SetOrgAssetsWithType(string libUrl, string thumbnailUrl, OrgAssetType orgAssetType)** | void |  |
| **SetOrgNewsSite(string orgNewsSiteUrl)** | ClientResult\<string\> |  |
| **SetPortalLaunchWaves(string siteUrl, string status, bool walkBack, bool isWhatIf, bool updateConfirmed)** | [SPOPortalLaunchValidationResult](#spoportallaunchvalidationresult-class) |  |
| **SetSiteAdmin(string siteUrl, string loginName, bool isSiteAdmin)** | User |  |
| **SetSPHSite(string sphSiteUrl)** | ClientResult\<string\> |  |
| **SetSPHSiteWithConfiguration(string sphSiteUrl, HomeSiteConfigurationParam configuration)** | ClientResult\<string\> |  |
| **SetSPHSiteWithConfigurations(string sphSiteUrl, bool vivaConnectionsDefaultStart)** | ClientResult\<string\> |  |
| **SetSPOContainerProperties(SPContainerProperties spContainerProperties)** | void |  |
| **SetSPOContainerType(SPContainerTypeProperties containerTypeProperties)** | ClientResult\<[SPContainerTypeProperties](#spcontainertypeproperties-class)\> |  |
| **SetSPOContainerTypeConfiguration(SPContainerTypeConfigurationProperties spContainerTypeConfigurationProperties)** | ClientResult\<[SPContainerTypeConfigurationProperties](#spcontainertypeconfigurationproperties-class)\> |  |
| **SetSPOStructuralNavigationCacheSiteState(string siteUrl, bool isEnabled)** | void |  |
| **SetSPOStructuralNavigationCacheWebState(string webUrl, bool isEnabled)** | void |  |
| **SetTenantCdnEnabled(SPOTenantCdnType cdnType, bool isEnabled)** | void |  |
| **SetTenantCdnPolicy(SPOTenantCdnType cdnType, SPOTenantCdnPolicyType policyType, string policyValue)** | void |  |
| **SetTenantIdentityMigrationState(TenantIdentityMigrationState state)** | void |  |
| **SetTenantOutOfBoxSiteTemplateSettings(TenantOutOfBoxSiteTemplateSettings updateInfo)** | ClientResult\<[TenantOutOfBoxSiteTemplateSettings](#tenantoutofboxsitetemplatesettings-class)\> |  |
| **SetWebTheme(string themeName, string webUrl)** | ClientResult\<string\> |  |
| **SetWorkflows2013Enabled(bool enabled)** | void |  |
| **SwapSite(string sourceUrl, string targetUrl, string archiveUrl)** | [SpoOperation](#spooperation-class) |  |
| **SwapSiteWithSmartGestureOption(string sourceUrl, string targetUrl, string archiveUrl, bool includeSmartGestures)** | [SpoOperation](#spooperation-class) |  |
| **SwapSiteWithSmartGestureOptionForce(string sourceUrl, string targetUrl, string archiveUrl, bool includeSmartGestures, bool force)** | [SpoOperation](#spooperation-class) |  |
| **SyncAadB2BManagementPolicy()** | void |  |
| **UnarchiveSiteById(Guid siteId)** | [SpoOperation](#spooperation-class) |  |
| **UnarchiveSiteByUrl(string siteUrl)** | [SpoOperation](#spooperation-class) |  |
| **UnlockSensitivityLabelEncryptedFile(string fileUrl, string justificationText)** | void |  |
| **UnregisterHubSite(string siteUrl)** | void |  |
| **UnregisterHubSiteById(Guid hubSiteId)** | void |  |
| **Update()** | void |  |
| **UpdatePortalLaunchWaves(string siteUrl, string status, bool walkBack)** | [SPOPortalLaunchValidationResult](#spoportallaunchvalidationresult-class) |  |
| **UpdateSiteDesign(TenantSiteDesign updateInfo)** | [TenantSiteDesign](#tenantsitedesign-class) |  |
| **UpdateSiteScript(TenantSiteScript updateInfo)** | [TenantSiteScript](#tenantsitescript-class) |  |
| **UpdateSiteScriptPackage(TenantSiteScript updateInfo)** | [TenantSiteScript](#tenantsitescript-class) |  |
| **UpdateTargetedSite(string siteUrl, HomeSiteConfigurationParam configurationParam)** | ClientResult\<TargetedSiteDetails\> |  |
| **UpdateTenantTheme(string name, string themeJson)** | ClientResult\<bool\> |  |
| **UpdateUserTypeFromAzureAD(string siteUrl, string loginName)** | User |  |
| **UpdateUserTypeFromAzureADForAllSites(string loginName)** | [SPOSitePropertiesEnumerable](#spositepropertiesenumerable-class) |  |
| **UpdateUserTypesFromAzureADForSite(string siteUrl)** | ClientObjectList\<User\> |  |
| **UploadCustomFontsAndCatalog(IList\<CustomFontsResource\> customFontFiles, string libUrl)** | ClientResult\<bool\> |  |
| **ValidateHomeSite(ValidationActionType validationActionType, string siteUrl)** | void |  |
| **ValidateMultipleHomeSitesParameterExists(bool hasParameters)** | void |  |
| **ValidateVivaHomeGAParametersExists(bool hasParameters)** | void |  |
| **ValidateVivaHomeParameterExists(bool hasParameters)** | void |  |
| **VerifySPOTenantOrgRelation(OrgRelationScenario scenario, OrgRelationRole partnerRole, string partnerMySiteHostUrl)** | ClientResult\<OrgRelationVerificationStatus\> |  |
# TenantBrowseUserInfoPolicyValue Enum

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Values

| Name | Summary |
|---|---|
| **ApplyToNoUsers** |  |
| **ApplyToGuestAndExternalUsers** |  |
| **ApplyToInternalUsers** |  |
| **ApplyToAllUsers** |  |
# TenantFontPackage Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ID** | Guid |  |
| **IsHidden** | bool |  |
| **IsValid** | bool |  |
| **PackageJson** | string |  |
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
| **TenantFontPackage(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# TenantFontPackageCreationParameters Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **IsHidden** | bool |  |
| **PackageJson** | string |  |
| **Title** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# TenantFontPackagePropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Fields

| Name | Type | Summary |
|---|---|---|
| **ID** | string |  |
| **IsHidden** | string |  |
| **IsValid** | string |  |
| **PackageJson** | string |  |
| **Title** | string |  |
# TenantListDesign Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Description** | string |  |
| **DesignType** | [TenantTemplateDesignType](#tenanttemplatedesigntype-enum) |  |
| **Id** | Guid |  |
| **ListColor** | [TenantListDesignColor](#tenantlistdesigncolor-enum) |  |
| **ListIcon** | [TenantListDesignIcon](#tenantlistdesignicon-enum) |  |
| **SiteScriptIds** | Guid[] |  |
| **TargetPlatforms** | string[] |  |
| **TemplateFeatures** | string[] |  |
| **ThumbnailUrl** | string |  |
| **Title** | string |  |
| **Version** | int |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **TenantListDesign(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# TenantListDesignColor Enum

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Values

| Name | Summary |
|---|---|
| **DarkRed** |  |
| **Red** |  |
| **Orange** |  |
| **Green** |  |
| **DarkGreen** |  |
| **Teal** |  |
| **Blue** |  |
| **NavyBlue** |  |
| **BluePurple** |  |
| **DarkBlue** |  |
| **Lavendar** |  |
| **Pink** |  |
# TenantListDesignCreationInfo Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Description** | string |  |
| **ListColor** | [TenantListDesignColor](#tenantlistdesigncolor-enum) |  |
| **ListIcon** | [TenantListDesignIcon](#tenantlistdesignicon-enum) |  |
| **SiteScriptIds** | Guid[] |  |
| **TemplateFeatures** | string[] |  |
| **ThumbnailUrl** | string |  |
| **Title** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# TenantListDesignIcon Enum

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Values

| Name | Summary |
|---|---|
| **Bug** |  |
| **Calendar** |  |
| **BullseyeTarget** |  |
| **ClipboardList** |  |
| **Airplane** |  |
| **Rocket** |  |
| **Color** |  |
| **Insights** |  |
| **CubeShape** |  |
| **TestBeakerSolid** |  |
| **Robot** |  |
| **Savings** |  |
# TenantListDesignPropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Fields

| Name | Type | Summary |
|---|---|---|
| **Description** | string |  |
| **DesignType** | string |  |
| **Id** | string |  |
| **ListColor** | string |  |
| **ListIcon** | string |  |
| **SiteScriptIds** | string |  |
| **TargetPlatforms** | string |  |
| **TemplateFeatures** | string |  |
| **ThumbnailUrl** | string |  |
| **Title** | string |  |
| **Version** | string |  |
# TenantLog Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **LastAvailableTimeInUtc** | DateTime |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **TenantLog(ClientRuntimeContext context)** |  |
| **TenantLog(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetEntries(DateTime beginDateTimeUtc, DateTime endDateTimeUtc, uint nRows)** | ClientObjectList\<[TenantLogEntry](#tenantlogentry-class)\> |  |
| **GetEntriesByCorrelationId(DateTime beginDateTimeUtc, DateTime endDateTimeUtc, uint nRows, Guid correlationId)** | ClientObjectList\<[TenantLogEntry](#tenantlogentry-class)\> |  |
| **GetEntriesBySource(DateTime beginDateTimeUtc, DateTime endDateTimeUtc, uint nRows, int source)** | ClientObjectList\<[TenantLogEntry](#tenantlogentry-class)\> |  |
| **GetEntriesByUser(DateTime beginDateTimeUtc, DateTime endDateTimeUtc, uint nRows, string user)** | ClientObjectList\<[TenantLogEntry](#tenantlogentry-class)\> |  |
# TenantLogEntry Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **CategoryId** | int |  |
| **CorrelationId** | Guid |  |
| **Message** | string |  |
| **Source** | int |  |
| **TimestampUtc** | DateTime |  |
| **User** | string |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **TenantLogEntry(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# TenantLogEntryPropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Fields

| Name | Type | Summary |
|---|---|---|
| **CategoryId** | string |  |
| **CorrelationId** | string |  |
| **Message** | string |  |
| **Source** | string |  |
| **TimestampUtc** | string |  |
| **User** | string |  |
# TenantLogPropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Fields

| Name | Type | Summary |
|---|---|---|
| **LastAvailableTimeInUtc** | string |  |
# TenantOutOfBoxSiteTemplateSettings Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Id** | Guid |  |
| **IsHidden** | bool |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# TenantPropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Fields

| Name | Type | Summary |
|---|---|---|
| **AddressbarLinkPermission** | string |  |
| **AIBuilderDefaultPowerAppsEnvironment** | string |  |
| **AIBuilderEnabled** | string |  |
| **AIBuilderEnabledInContentCenter** | string |  |
| **AIBuilderSiteInfoList** | string |  |
| **AIBuilderSiteList** | string |  |
| **AIBuilderSiteListFileName** | string |  |
| **AllowAnonymousMeetingParticipantsToAccessWhiteboards** | string |  |
| **AllowCommentsTextOnEmailEnabled** | string |  |
| **AllowDownloadingNonWebViewableFiles** | string |  |
| **AllowedDomainListForSyncClient** | string |  |
| **AllowEditing** | string |  |
| **AllowEveryoneExceptExternalUsersClaimInPrivateSite** | string |  |
| **AllowGuestUserShareToUsersNotInSiteCollection** | string |  |
| **AllowLimitedAccessOnUnmanagedDevices** | string |  |
| **AllowOverrideForBlockUserInfoVisibility** | string |  |
| **AllowSelectSecurityGroupsInSPSitesList** | string |  |
| **AllowSelectSGsInODBListInTenant** | string |  |
| **AllowSensitivityLabelOnRecords** | string |  |
| **AmplifyAdminSettings** | string |  |
| **AnyoneLinkTrackUsers** | string |  |
| **AppBypassInformationBarriers** | string |  |
| **ApplyAppEnforcedRestrictionsToAdHocRecipients** | string |  |
| **AppOnlyBypassPeoplePickerPolicies** | string |  |
| **ArchiveRedirectUrl** | string |  |
| **AuthContextResilienceMode** | string |  |
| **BccExternalSharingInvitations** | string |  |
| **BccExternalSharingInvitationsList** | string |  |
| **BlockAccessOnUnmanagedDevices** | string |  |
| **BlockAppAccessWithAuthenticationContext** | string |  |
| **BlockDownloadFileTypeIds** | string |  |
| **BlockDownloadFileTypePolicy** | string |  |
| **BlockDownloadLinksFileType** | string |  |
| **BlockDownloadOfAllFilesForGuests** | string |  |
| **BlockDownloadOfAllFilesOnUnmanagedDevices** | string |  |
| **BlockDownloadOfViewableFilesForGuests** | string |  |
| **BlockDownloadOfViewableFilesOnUnmanagedDevices** | string |  |
| **BlockMacSync** | string |  |
| **BlockSendLabelMismatchEmail** | string |  |
| **BlockUserInfoVisibility** | string |  |
| **BlockUserInfoVisibilityInOneDrive** | string |  |
| **BlockUserInfoVisibilityInSharePoint** | string |  |
| **BonusStorageQuotaMB** | string |  |
| **BusinessConnectivityServiceDisabled** | string |  |
| **CommentsOnFilesDisabled** | string |  |
| **CommentsOnListItemsDisabled** | string |  |
| **CommentsOnSitePagesDisabled** | string |  |
| **CompatibilityRange** | string |  |
| **ConditionalAccessPolicy** | string |  |
| **ConditionalAccessPolicyErrorHelpLink** | string |  |
| **ContainerDefaultLinkToExistingAccess** | string |  |
| **ContainerDefaultShareLinkRole** | string |  |
| **ContainerDefaultShareLinkScope** | string |  |
| **ContainerLoopDefaultShareLinkRole** | string |  |
| **ContainerLoopDefaultShareLinkScope** | string |  |
| **ContainerSharingCapability** | string |  |
| **ContentTypeSyncSiteTemplatesList** | string |  |
| **CoreBlockGuestsAsSiteAdmin** | string |  |
| **CoreDefaultLinkToExistingAccess** | string |  |
| **CoreDefaultShareLinkRole** | string |  |
| **CoreDefaultShareLinkScope** | string |  |
| **CoreLoopDefaultSharingLinkRole** | string |  |
| **CoreLoopDefaultSharingLinkScope** | string |  |
| **CoreLoopSharingCapability** | string |  |
| **CoreRequestFilesLinkEnabled** | string |  |
| **CoreRequestFilesLinkExpirationInDays** | string |  |
| **CoreSharingCapability** | string |  |
| **CustomizedExternalSharingServiceUrl** | string |  |
| **DefaultContentCenterSite** | string |  |
| **DefaultLinkPermission** | string |  |
| **DefaultODBMode** | string |  |
| **DefaultSharingLinkType** | string |  |
| **DelayDenyAddAndCustomizePagesEnforcement** | string |  |
| **DenySelectSecurityGroupsInSPSitesList** | string |  |
| **DenySelectSGsInODBListInTenant** | string |  |
| **DisableAddToOneDrive** | string |  |
| **DisableBackToClassic** | string |  |
| **DisableCustomAppAuthentication** | string |  |
| **DisabledModernListTemplateIds** | string |  |
| **DisableDocumentLibraryDefaultLabeling** | string |  |
| **DisabledWebPartIds** | string |  |
| **DisableOutlookPSTVersionTrimming** | string |  |
| **DisablePersonalListCreation** | string |  |
| **DisableReportProblemDialog** | string |  |
| **DisableSpacesActivation** | string |  |
| **DisableVivaConnectionsAnalytics** | string |  |
| **DisallowInfectedFileDownload** | string |  |
| **DisplayNamesOfFileViewers** | string |  |
| **DisplayNamesOfFileViewersInSpo** | string |  |
| **DisplayStartASiteOption** | string |  |
| **DocumentUnderstandingEnabled** | string |  |
| **DocumentUnderstandingSiteInfoList** | string |  |
| **DocumentUnderstandingSiteList** | string |  |
| **DocumentUnderstandingSiteListFileName** | string |  |
| **EmailAttestationEnabled** | string |  |
| **EmailAttestationReAuthDays** | string |  |
| **EmailAttestationRequired** | string |  |
| **EnableAIPIntegration** | string |  |
| **EnableAutoExpirationVersionTrim** | string |  |
| **EnableAutoNewsDigest** | string |  |
| **EnableAzureADB2BIntegration** | string |  |
| **EnabledFlightAllowAADB2BSkipCheckingOTP** | string |  |
| **EnableGuestSignInAcceleration** | string |  |
| **EnableMinimumVersionRequirement** | string |  |
| **EnableMipSiteLabel** | string |  |
| **EnablePromotedFileHandlers** | string |  |
| **EnableRestrictedAccessControl** | string |  |
| **EnableSensitivityLabelForPDF** | string |  |
| **EnableSiteArchive** | string |  |
| **EnableTenantRestrictionsInsights** | string |  |
| **ESignatureEnabled** | string |  |
| **ESignatureSiteInfoList** | string |  |
| **ESignatureSiteList** | string |  |
| **ESignatureSiteListFileName** | string |  |
| **ESignatureThirdPartyProviderInfoList** | string |  |
| **ESignatureThirdPartyProviderList** | string |  |
| **ESignatureThirdPartyProviderListFileName** | string |  |
| **ExcludedBlockDownloadGroupIds** | string |  |
| **ExcludedFileExtensionsForSyncClient** | string |  |
| **ExemptNativeUsersFromTenantLevelRestricedAccessControl** | string |  |
| **ExpireVersionsAfterDays** | string |  |
| **ExternalServicesEnabled** | string |  |
| **ExternalUserExpirationRequired** | string |  |
| **ExternalUserExpireInDays** | string |  |
| **FileAnonymousLinkType** | string |  |
| **FilePickerExternalImageSearchEnabled** | string |  |
| **FileVersionPolicyXml** | string |  |
| **FolderAnonymousLinkType** | string |  |
| **GuestSharingGroupAllowListInTenant** | string |  |
| **GuestSharingGroupAllowListInTenantByPrincipalIdentity** | string |  |
| **HasAdminCompletedCUConfiguration** | string |  |
| **HasIntelligentContentServicesCapability** | string |  |
| **HasTopicExperiencesCapability** | string |  |
| **HideDefaultThemes** | string |  |
| **HideSyncButtonOnDocLib** | string |  |
| **HideSyncButtonOnODB** | string |  |
| **IBImplicitGroupBased** | string |  |
| **ImageTaggingOption** | string |  |
| **IncludeAtAGlanceInShareEmails** | string |  |
| **InformationBarriersSuspension** | string |  |
| **IPAddressAllowList** | string |  |
| **IPAddressEnforcement** | string |  |
| **IPAddressWACTokenLifetime** | string |  |
| **IsAppBarTemporarilyDisabled** | string |  |
| **IsCollabMeetingNotesFluidEnabled** | string |  |
| **IsDataAccessInCardDesignerEnabled** | string |  |
| **IsEnableAppAuthPopUpEnabled** | string |  |
| **IsFluidEnabled** | string |  |
| **IsHubSitesMultiGeoFlightEnabled** | string |  |
| **IsLoopEnabled** | string |  |
| **IsMnAFlightEnabled** | string |  |
| **IsMultiGeo** | string |  |
| **IsMultipleHomeSitesFlightEnabled** | string |  |
| **IsMultipleVivaConnectionsFlightEnabled** | string |  |
| **IsRansomwareProtectionEnabled** | string |  |
| **IsUnmanagedSyncClientForTenantRestricted** | string |  |
| **IsUnmanagedSyncClientRestrictionFlightEnabled** | string |  |
| **IsVivaHomeFlightEnabled** | string |  |
| **IsVivaHomeGAFlightEnabled** | string |  |
| **IsWBFluidEnabled** | string |  |
| **LabelMismatchEmailHelpLink** | string |  |
| **LegacyAuthProtocolsEnabled** | string |  |
| **LegacyBrowserAuthProtocolsEnabled** | string |  |
| **LimitedAccessFileType** | string |  |
| **MachineLearningCaptureEnabled** | string |  |
| **MajorVersionLimit** | string |  |
| **MarkAllFilesAsSensitiveByDefault** | string |  |
| **MarkNewFilesSensitiveByDefault** | string |  |
| **MassDeleteNotificationDisabled** | string |  |
| **MediaTranscription** | string |  |
| **MediaTranscriptionAutomaticFeatures** | string |  |
| **MobileFriendlyUrlEnabledInTenant** | string |  |
| **NoAccessRedirectUrl** | string |  |
| **NotificationsInOneDriveForBusinessEnabled** | string |  |
| **NotificationsInSharePointEnabled** | string |  |
| **NotifyOwnersWhenInvitationsAccepted** | string |  |
| **NotifyOwnersWhenItemsReshared** | string |  |
| **OCRAdminSiteInfoList** | string |  |
| **OCRAdminSiteList** | string |  |
| **OCRAdminSiteListFileName** | string |  |
| **OCRComplianceSiteInfoList** | string |  |
| **OCRComplianceSiteList** | string |  |
| **OCRComplianceSiteListFileName** | string |  |
| **OCRModeForAdminSites** | string |  |
| **OCRModeForComplianceODBs** | string |  |
| **OCRModeForComplianceSites** | string |  |
| **ODBAccessRequests** | string |  |
| **ODBMembersCanShare** | string |  |
| **ODBSensitivityRefreshWindowInHours** | string |  |
| **ODBSharingCapability** | string |  |
| **OfficeClientADALDisabled** | string |  |
| **OneDriveBlockGuestsAsSiteAdmin** | string |  |
| **OneDriveDefaultLinkToExistingAccess** | string |  |
| **OneDriveDefaultShareLinkRole** | string |  |
| **OneDriveDefaultShareLinkScope** | string |  |
| **OneDriveForGuestsEnabled** | string |  |
| **OneDriveLoopDefaultSharingLinkRole** | string |  |
| **OneDriveLoopDefaultSharingLinkScope** | string |  |
| **OneDriveLoopSharingCapability** | string |  |
| **OneDriveRequestFilesLinkEnabled** | string |  |
| **OneDriveRequestFilesLinkExpirationInDays** | string |  |
| **OneDriveStorageQuota** | string |  |
| **OptOutOfGrooveBlock** | string |  |
| **OptOutOfGrooveSoftBlock** | string |  |
| **OrgNewsSiteUrl** | string |  |
| **OrphanedPersonalSitesRetentionPeriod** | string |  |
| **OwnerAnonymousNotification** | string |  |
| **PermissiveBrowserFileHandlingOverride** | string |  |
| **PrebuiltEnabled** | string |  |
| **PrebuiltSiteInfoList** | string |  |
| **PrebuiltSiteList** | string |  |
| **PrebuiltSiteListFileName** | string |  |
| **PreventExternalUsersFromResharing** | string |  |
| **ProvisionSharedWithEveryoneFolder** | string |  |
| **PublicCdnAllowedFileTypes** | string |  |
| **PublicCdnEnabled** | string |  |
| **PublicCdnOrigins** | string |  |
| **RecycleBinRetentionPeriod** | string |  |
| **ReduceTempTokenLifetimeEnabled** | string |  |
| **ReduceTempTokenLifetimeValue** | string |  |
| **RequireAcceptingAccountMatchInvitedAccount** | string |  |
| **RequireAnonymousLinksExpireInDays** | string |  |
| **ResourceQuota** | string |  |
| **ResourceQuotaAllocated** | string |  |
| **RestrictedOneDriveLicense** | string |  |
| **RestrictedSharePointLicense** | string |  |
| **RootSiteUrl** | string |  |
| **SearchResolveExactEmailOrUPN** | string |  |
| **SharingAllowedDomainList** | string |  |
| **SharingBlockedDomainList** | string |  |
| **SharingCapability** | string |  |
| **SharingDomainRestrictionMode** | string |  |
| **ShowAllUsersClaim** | string |  |
| **ShowEveryoneClaim** | string |  |
| **ShowEveryoneExceptExternalUsersClaim** | string |  |
| **ShowNGSCDialogForSyncOnODB** | string |  |
| **ShowOpenInDesktopOptionForSyncedFiles** | string |  |
| **ShowPeoplePickerGroupSuggestionsForIB** | string |  |
| **ShowPeoplePickerSuggestionsForGuestUsers** | string |  |
| **SignInAccelerationDomain** | string |  |
| **SiteOwnerManageLegacyServicePrincipalEnabled** | string |  |
| **SocialBarOnSitePagesDisabled** | string |  |
| **SpecialCharactersStateInFileFolderNames** | string |  |
| **StartASiteFormUrl** | string |  |
| **StopNew2010Workflows** | string |  |
| **StopNew2013Workflows** | string |  |
| **StorageQuota** | string |  |
| **StorageQuotaAllocated** | string |  |
| **StreamLaunchConfig** | string |  |
| **StreamLaunchConfigLastUpdated** | string |  |
| **StreamLaunchConfigUpdateCount** | string |  |
| **SyncPrivacyProfileProperties** | string |  |
| **SyntexBillingSubscriptionSettings** | string |  |
| **SyntexExternalVideoSharingSettings** | string |  |
| **SyntexHighResolutionPlaybackSettings** | string |  |
| **SyntexInternalFeatureFlags** | string |  |
| **SyntexMediaAnalyticsSettings** | string |  |
| **SyntexPaygFeatureActivations** | string |  |
| **SyntexPlaybackTranscriptTranslationSettings** | string |  |
| **SyntexPowerAppsEnvironmentsContext** | string |  |
| **TaxonomyTaggingEnabled** | string |  |
| **TaxonomyTaggingSiteInfoList** | string |  |
| **TaxonomyTaggingSiteList** | string |  |
| **TaxonomyTaggingSiteListFileName** | string |  |
| **TlsTokenBindingPolicyValue** | string |  |
| **TranslationEnabled** | string |  |
| **TranslationSiteInfoList** | string |  |
| **TranslationSiteList** | string |  |
| **TranslationSiteListFileName** | string |  |
| **UseFindPeopleInPeoplePicker** | string |  |
| **UsePersistentCookiesForExplorerView** | string |  |
| **UserVoiceForFeedbackEnabled** | string |  |
| **ViewersCanCommentOnMediaDisabled** | string |  |
| **ViewInFileExplorerEnabled** | string |  |
| **WhoCanShareAllowListInTenant** | string |  |
| **WhoCanShareAllowListInTenantByPrincipalIdentity** | string |  |
| **Workflow2010Disabled** | string |  |
| **Workflows2013State** | string |  |
# TenantSiteDesign Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Description** | string |  |
| **DesignPackageId** | Guid |  |
| **DesignType** | [TenantTemplateDesignType](#tenanttemplatedesigntype-enum) |  |
| **Id** | Guid |  |
| **IsDefault** | bool |  |
| **PreviewImageAltText** | string |  |
| **PreviewImageUrl** | string |  |
| **SiteScriptIds** | Guid[] |  |
| **ThumbnailUrl** | string |  |
| **Title** | string |  |
| **Version** | int |  |
| **WebTemplate** | string |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **TenantSiteDesign(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# TenantSiteDesignCreationInfo Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Description** | string |  |
| **DesignPackageId** | Guid |  |
| **IsDefault** | bool |  |
| **PreviewImageAltText** | string |  |
| **PreviewImageUrl** | string |  |
| **SiteScriptIds** | Guid[] |  |
| **ThumbnailUrl** | string |  |
| **Title** | string |  |
| **WebTemplate** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# TenantSiteDesignPrincipal Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **DisplayName** | string |  |
| **PrincipalName** | string |  |
| **Rights** | [TenantSiteDesignPrincipalRights](#tenantsitedesignprincipalrights-enum) |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **TenantSiteDesignPrincipal(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# TenantSiteDesignPrincipalPropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Fields

| Name | Type | Summary |
|---|---|---|
| **DisplayName** | string |  |
| **PrincipalName** | string |  |
| **Rights** | string |  |
# TenantSiteDesignPrincipalRights Enum

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **View** |  |
# TenantSiteDesignPropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Fields

| Name | Type | Summary |
|---|---|---|
| **Description** | string |  |
| **DesignPackageId** | string |  |
| **DesignType** | string |  |
| **Id** | string |  |
| **IsDefault** | string |  |
| **PreviewImageAltText** | string |  |
| **PreviewImageUrl** | string |  |
| **SiteScriptIds** | string |  |
| **ThumbnailUrl** | string |  |
| **Title** | string |  |
| **Version** | string |  |
| **WebTemplate** | string |  |
# TenantSiteDesignRun Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Id** | Guid |  |
| **SiteDesignId** | Guid |  |
| **SiteDesignTitle** | string |  |
| **SiteDesignVersion** | int |  |
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
| **TenantSiteDesignRun(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# TenantSiteDesignRunPropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Fields

| Name | Type | Summary |
|---|---|---|
| **Id** | string |  |
| **SiteDesignId** | string |  |
| **SiteDesignTitle** | string |  |
| **SiteDesignVersion** | string |  |
| **SiteId** | string |  |
| **WebId** | string |  |
# TenantSiteDesignTask Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Id** | Guid |  |
| **LogonName** | string |  |
| **SiteDesignId** | Guid |  |
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
| **TenantSiteDesignTask(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# TenantSiteDesignTaskPropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Fields

| Name | Type | Summary |
|---|---|---|
| **Id** | string |  |
| **LogonName** | string |  |
| **SiteDesignId** | string |  |
| **SiteId** | string |  |
| **WebId** | string |  |
# TenantSiteScript Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Content** | string |  |
| **ContentStream** | Stream |  |
| **Description** | string |  |
| **Id** | Guid |  |
| **IsSiteScriptPackage** | bool |  |
| **Title** | string |  |
| **Version** | int |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **TenantSiteScript(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# TenantSiteScriptActionOutcome Enum

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Values

| Name | Summary |
|---|---|
| **Success** |  |
| **Failure** |  |
| **NoOp** |  |
| **SucceededWithException** |  |
# TenantSiteScriptActionResult Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Outcome** | [TenantSiteScriptActionOutcome](#tenantsitescriptactionoutcome-enum) |  |
| **OutcomeText** | string |  |
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
| **TenantSiteScriptActionResult(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# TenantSiteScriptActionResultPropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Fields

| Name | Type | Summary |
|---|---|---|
| **Outcome** | string |  |
| **OutcomeText** | string |  |
| **Title** | string |  |
# TenantSiteScriptActionStatus Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ActionIndex** | int |  |
| **ActionKey** | Guid |  |
| **ActionTitle** | string |  |
| **OrdinalIndex** | int |  |
| **OutcomeCode** | [TenantSiteScriptActionOutcome](#tenantsitescriptactionoutcome-enum) |  |
| **OutcomeText** | string |  |
| **SiteScriptID** | Guid |  |
| **SiteScriptIndex** | int |  |
| **SiteScriptTitle** | string |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **TenantSiteScriptActionStatus(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# TenantSiteScriptActionStatusPropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Fields

| Name | Type | Summary |
|---|---|---|
| **ActionIndex** | string |  |
| **ActionKey** | string |  |
| **ActionTitle** | string |  |
| **OrdinalIndex** | string |  |
| **OutcomeCode** | string |  |
| **OutcomeText** | string |  |
| **SiteScriptID** | string |  |
| **SiteScriptIndex** | string |  |
| **SiteScriptTitle** | string |  |
# TenantSiteScriptCreationInfo Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Content** | string |  |
| **ContentStream** | Stream |  |
| **Description** | string |  |
| **Title** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# TenantSiteScriptPropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Fields

| Name | Type | Summary |
|---|---|---|
| **Content** | string |  |
| **ContentStream** | string |  |
| **Description** | string |  |
| **Id** | string |  |
| **IsSiteScriptPackage** | string |  |
| **Title** | string |  |
| **Version** | string |  |
# TenantSiteScriptSerializationInfo Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **IncludeBranding** | bool |  |
| **IncludedLists** | string[] |  |
| **IncludeLinksToExportedItems** | bool |  |
| **IncludeRegionalSettings** | bool |  |
| **IncludeSiteExternalSharingCapability** | bool |  |
| **IncludeTheme** | bool |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# TenantSiteScriptSerializationResult Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **JSON** | string |  |
| **PackageStream** | Stream |  |
| **Warnings** | string[] |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# TenantTemplateDesignType Enum

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Values

| Name | Summary |
|---|---|
| **Site** |  |
| **List** |  |
# UpdateGroupSitePropertiesParameters Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **storageMaximumLevel** | long |  |
| **storageWarningLevel** | long |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# UserInfo Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **email** | string |  |
| **loginName** | string |  |
| **name** | string |  |
| **userPrincipalName** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# UserMigrationProperties Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **OdbMigrationStatus** | [OdbMigrationStatus](#odbmigrationstatus-enum) |  |
| **SourcePuid** | string |  |
| **SourceUpn** | string |  |
| **TargetPuid** | string |  |
| **TargetUpn** | string |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **UserMigrationProperties(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# UserMigrationPropertiesEnumerable Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientObjectCollection<[UserMigrationProperties](#usermigrationproperties-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **NextStartToken** | string |  |
| **Item** | [UserMigrationProperties](#usermigrationproperties-class) |  |
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
| **UserMigrationPropertiesEnumerable(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# UserMigrationPropertiesEnumerableFilter Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **BatchId** | string |  |
| **StartToken** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# UserMigrationPropertiesEnumerablePropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Fields

| Name | Type | Summary |
|---|---|---|
| **NextStartToken** | string |  |
# UserMigrationPropertiesPropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Fields

| Name | Type | Summary |
|---|---|---|
| **OdbMigrationStatus** | string |  |
| **SourcePuid** | string |  |
| **SourceUpn** | string |  |
| **TargetPuid** | string |  |
| **TargetUpn** | string |  |
# SPO3rdPartyAADPermissionGrant Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration.Internal

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ClientId** | string |  |
| **ConsentType** | string |  |
| **IsDomainIsolated** | bool |  |
| **ObjectId** | string |  |
| **PackageName** | string |  |
| **Resource** | string |  |
| **Scope** | string |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **SPO3rdPartyAADPermissionGrant(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# SPO3rdPartyAADPermissionGrantManager Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration.Internal

Base class: ClientObjectCollection<[SPO3rdPartyAADPermissionGrant](#spo3rdpartyaadpermissiongrant-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [SPO3rdPartyAADPermissionGrant](#spo3rdpartyaadpermissiongrant-class) |  |
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
| **SPO3rdPartyAADPermissionGrantManager(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(string servicePrincipalId, string resource, string scope)** | void |  |
| **Remove(string servicePrincipalId, string resource, string scope)** | void |  |
# SPO3rdPartyAADPermissionGrantPropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration.Internal


## Fields

| Name | Type | Summary |
|---|---|---|
| **ClientId** | string |  |
| **ConsentType** | string |  |
| **IsDomainIsolated** | string |  |
| **ObjectId** | string |  |
| **PackageName** | string |  |
| **Resource** | string |  |
| **Scope** | string |  |
# SPOWebAppServicePrincipal Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration.Internal

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AccountEnabled** | bool |  |
| **AppHelperId** | string |  |
| **AppId** | string |  |
| **AppsToDelete** | IList\<string\> |  |
| **GrantManager** | [SPO3rdPartyAADPermissionGrantManager](#spo3rdpartyaadpermissiongrantmanager-class) |  |
| **PermissionGrants** | [SPOWebAppServicePrincipalPermissionGrantCollection](#spowebappserviceprincipalpermissiongrantcollection-class) |  |
| **PermissionRequests** | [SPOWebAppServicePrincipalPermissionRequestCollection](#spowebappserviceprincipalpermissionrequestcollection-class) |  |
| **ReplyUrls** | IEnumerable\<string\> |  |
| **ServicePrincipalObjectIds** | IList\<Guid\> |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **SPOWebAppServicePrincipal(ClientRuntimeContext context)** |  |
| **SPOWebAppServicePrincipal(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetIsolatedAppDomainsByAppId(IList\<string\> appIds)** | ClientResult\<IDictionary\<string, string\>\> |  |
| **RemoveAppsToDelete(IList\<string\> domainsToDelete)** | void |  |
| **Update()** | void |  |
| **UpdateSpfxClientSecret(string secretValue)** | void |  |
| **UpdateSpfxThirdPartyAppId(string appId)** | void |  |
| **UpdateSpfxThirdPartyIsolatedComponentFields(string catalogItemId, string apAppObjectId, string spObjectId, string appId)** | void |  |
| **UpdateSpfxThirdPartyIsolatedSecret(string servicePrincipalId, string secretValue)** | void |  |
# SPOWebAppServicePrincipalObjectPropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration.Internal


## Fields

| Name | Type | Summary |
|---|---|---|
| **GrantManager** | string |  |
| **PermissionGrants** | string |  |
| **PermissionRequests** | string |  |
# SPOWebAppServicePrincipalPermissionGrant Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration.Internal

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ClientId** | string |  |
| **ConsentType** | string |  |
| **IsDomainIsolated** | bool |  |
| **ObjectId** | string |  |
| **PackageName** | string |  |
| **Resource** | string |  |
| **ResourceId** | string |  |
| **Scope** | string |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **SPOWebAppServicePrincipalPermissionGrant(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
# SPOWebAppServicePrincipalPermissionGrantCollection Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration.Internal

Base class: ClientObjectCollection<[SPOWebAppServicePrincipalPermissionGrant](#spowebappserviceprincipalpermissiongrant-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [SPOWebAppServicePrincipalPermissionGrant](#spowebappserviceprincipalpermissiongrant-class) |  |
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
| **SPOWebAppServicePrincipalPermissionGrantCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetByObjectId(string objectId)** | [SPOWebAppServicePrincipalPermissionGrant](#spowebappserviceprincipalpermissiongrant-class) |  |
# SPOWebAppServicePrincipalPermissionGrantPropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration.Internal


## Fields

| Name | Type | Summary |
|---|---|---|
| **ClientId** | string |  |
| **ConsentType** | string |  |
| **IsDomainIsolated** | string |  |
| **ObjectId** | string |  |
| **PackageName** | string |  |
| **Resource** | string |  |
| **ResourceId** | string |  |
| **Scope** | string |  |
# SPOWebAppServicePrincipalPermissionRequest Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration.Internal

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ClientComponentItemUniqueId** | string |  |
| **Id** | Guid |  |
| **IsDomainIsolated** | bool |  |
| **IsolatedDomainUrl** | string |  |
| **MultiTenantAppId** | string |  |
| **MultiTenantAppReplyUrl** | string |  |
| **PackageApproverName** | string |  |
| **PackageName** | string |  |
| **PackageVersion** | string |  |
| **Resource** | string |  |
| **ResourceId** | string |  |
| **Scope** | string |  |
| **TimeRequested** | DateTime |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **SPOWebAppServicePrincipalPermissionRequest(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Approve()** | [SPOWebAppServicePrincipalPermissionGrant](#spowebappserviceprincipalpermissiongrant-class) |  |
| **Deny()** | void |  |
# SPOWebAppServicePrincipalPermissionRequestCollection Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration.Internal

Base class: ClientObjectCollection<[SPOWebAppServicePrincipalPermissionRequest](#spowebappserviceprincipalpermissionrequest-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [SPOWebAppServicePrincipalPermissionRequest](#spowebappserviceprincipalpermissionrequest-class) |  |
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
| **SPOWebAppServicePrincipalPermissionRequestCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Approve(string resource, string scope)** | [SPOWebAppServicePrincipalPermissionGrant](#spowebappserviceprincipalpermissiongrant-class) |  |
| **GetById(Guid id)** | [SPOWebAppServicePrincipalPermissionRequest](#spowebappserviceprincipalpermissionrequest-class) |  |
# SPOWebAppServicePrincipalPermissionRequestPropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration.Internal


## Fields

| Name | Type | Summary |
|---|---|---|
| **ClientComponentItemUniqueId** | string |  |
| **Id** | string |  |
| **IsDomainIsolated** | string |  |
| **IsolatedDomainUrl** | string |  |
| **MultiTenantAppId** | string |  |
| **MultiTenantAppReplyUrl** | string |  |
| **PackageApproverName** | string |  |
| **PackageName** | string |  |
| **PackageVersion** | string |  |
| **Resource** | string |  |
| **ResourceId** | string |  |
| **Scope** | string |  |
| **TimeRequested** | string |  |
# SPOWebAppServicePrincipalPropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration.Internal


## Fields

| Name | Type | Summary |
|---|---|---|
| **AccountEnabled** | string |  |
| **AppHelperId** | string |  |
| **AppId** | string |  |
| **AppsToDelete** | string |  |
| **ReplyUrls** | string |  |
| **ServicePrincipalObjectIds** | string |  |
# BlockDownloadLinksFileTypes Enum

Namespace: Microsoft.Online.SharePoint.TenantManagement


## Values

| Name | Summary |
|---|---|
| **WebPreviewableFiles** |  |
| **ServerRenderedFilesOnly** |  |
# ExternalUser Class

Namespace: Microsoft.Online.SharePoint.TenantManagement

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AcceptedAs** | string |  |
| **DisplayName** | string |  |
| **InvitedAs** | string |  |
| **InvitedBy** | string |  |
| **IsCrossTenant** | bool |  |
| **LoginName** | string |  |
| **UniqueId** | string |  |
| **UserId** | int |  |
| **WhenCreated** | DateTime |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **ExternalUser(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ExternalUserCollection Class

Namespace: Microsoft.Online.SharePoint.TenantManagement

Base class: ClientObjectCollection<[ExternalUser](#externaluser-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [ExternalUser](#externaluser-class) |  |
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
| **ExternalUserCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetById(string uniqueId)** | [ExternalUser](#externaluser-class) |  |
# ExternalUserPropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantManagement


## Fields

| Name | Type | Summary |
|---|---|---|
| **AcceptedAs** | string |  |
| **DisplayName** | string |  |
| **InvitedAs** | string |  |
| **InvitedBy** | string |  |
| **IsCrossTenant** | string |  |
| **LoginName** | string |  |
| **UniqueId** | string |  |
| **UserId** | string |  |
| **WhenCreated** | string |  |
# GetExternalUsersResults Class

Namespace: Microsoft.Online.SharePoint.TenantManagement

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ExternalUserCollection** | [ExternalUserCollection](#externalusercollection-class) |  |
| **TotalUserCount** | int |  |
| **UserCollectionPosition** | int |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **GetExternalUsersResults(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# GetExternalUsersResultsObjectPropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantManagement


## Fields

| Name | Type | Summary |
|---|---|---|
| **ExternalUserCollection** | string |  |
# GetExternalUsersResultsPropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantManagement


## Fields

| Name | Type | Summary |
|---|---|---|
| **TotalUserCount** | string |  |
| **UserCollectionPosition** | string |  |
# GroupCreationParams Class

Namespace: Microsoft.Online.SharePoint.TenantManagement

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Classification** | string |  |
| **CreationOptions** | string[] |  |
| **Description** | string |  |
| **Owners** | string[] |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **GroupCreationParams(ClientRuntimeContext context)** |  |
| **GroupCreationParams(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# GroupCreationParamsPropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantManagement


## Fields

| Name | Type | Summary |
|---|---|---|
| **Classification** | string |  |
| **CreationOptions** | string |  |
| **Description** | string |  |
| **Owners** | string |  |
# ImageTaggingChoice Enum

Namespace: Microsoft.Online.SharePoint.TenantManagement


## Values

| Name | Summary |
|---|---|
| **Disabled** |  |
| **Basic** |  |
| **Enhanced** |  |
# ImportProfilePropertiesJobError Enum

Namespace: Microsoft.Online.SharePoint.TenantManagement


## Values

| Name | Summary |
|---|---|
| **NoError** |  |
| **InternalError** |  |
| **DataFileNotExist** |  |
| **DataFileNotInTenant** |  |
| **DataFileTooBig** |  |
| **InvalidDataFile** |  |
| **ImportCompleteWithError** |  |
# ImportProfilePropertiesJobInfo Class

Namespace: Microsoft.Online.SharePoint.TenantManagement

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Error** | [ImportProfilePropertiesJobError](#importprofilepropertiesjoberror-enum) |  |
| **ErrorMessage** | string |  |
| **JobId** | Guid |  |
| **LogFolderUri** | string |  |
| **SourceUri** | string |  |
| **State** | [ImportProfilePropertiesJobState](#importprofilepropertiesjobstate-enum) |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **ImportProfilePropertiesJobInfo(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ImportProfilePropertiesJobInfoPropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantManagement


## Fields

| Name | Type | Summary |
|---|---|---|
| **Error** | string |  |
| **ErrorMessage** | string |  |
| **JobId** | string |  |
| **LogFolderUri** | string |  |
| **SourceUri** | string |  |
| **State** | string |  |
# ImportProfilePropertiesJobState Enum

Namespace: Microsoft.Online.SharePoint.TenantManagement


## Values

| Name | Summary |
|---|---|
| **Unknown** |  |
| **Submitted** |  |
| **Processing** |  |
| **Queued** |  |
| **Succeeded** |  |
| **Error** |  |
# ImportProfilePropertiesJobStatusCollection Class

Namespace: Microsoft.Online.SharePoint.TenantManagement

Base class: ClientObjectCollection<[ImportProfilePropertiesJobInfo](#importprofilepropertiesjobinfo-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [ImportProfilePropertiesJobInfo](#importprofilepropertiesjobinfo-class) |  |
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
| **ImportProfilePropertiesJobStatusCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ImportProfilePropertiesUserIdType Enum

Namespace: Microsoft.Online.SharePoint.TenantManagement


## Values

| Name | Summary |
|---|---|
| **Email** |  |
| **CloudId** |  |
| **PrincipalName** |  |
# MediaTranscriptionAutomaticFeaturesPolicyType Enum

Namespace: Microsoft.Online.SharePoint.TenantManagement


## Values

| Name | Summary |
|---|---|
| **Enabled** |  |
| **Disabled** |  |
# MediaTranscriptionPolicyType Enum

Namespace: Microsoft.Online.SharePoint.TenantManagement


## Values

| Name | Summary |
|---|---|
| **Enabled** |  |
| **Disabled** |  |
# Office365Tenant Class

Namespace: Microsoft.Online.SharePoint.TenantManagement

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AddressbarLinkPermission** | Role |  |
| **AllowAnonymousMeetingParticipantsToAccessWhiteboards** | SharingState |  |
| **AllowCommentsTextOnEmailEnabled** | bool |  |
| **AllowDownloadingNonWebViewableFiles** | bool |  |
| **AllowedDomainListForSyncClient** | IList\<Guid\> |  |
| **AllowEditing** | bool |  |
| **AllowEveryoneExceptExternalUsersClaimInPrivateSite** | bool |  |
| **AllowGuestUserShareToUsersNotInSiteCollection** | bool |  |
| **AllowLimitedAccessOnUnmanagedDevices** | bool |  |
| **AllowOverrideForBlockUserInfoVisibility** | bool |  |
| **AllowSelectSecurityGroupsInSPSitesList** | IList\<string\> |  |
| **AllowSelectSGsInODBList** | IList\<string\> |  |
| **AnyoneLinkTrackUsers** | bool |  |
| **AppBypassInformationBarriers** | bool |  |
| **ApplyAppEnforcedRestrictionsToAdHocRecipients** | bool |  |
| **AppOnlyBypassPeoplePickerPolicies** | bool |  |
| **AuthContextResilienceMode** | SPResilienceModeType |  |
| **BccExternalSharingInvitations** | bool |  |
| **BccExternalSharingInvitationsList** | string |  |
| **BlockAccessOnUnmanagedDevices** | bool |  |
| **BlockAppAccessWithAuthenticationContext** | bool |  |
| **BlockDownloadFileTypeIds** | SPBlockDownloadFileTypeId[] |  |
| **BlockDownloadFileTypePolicy** | bool |  |
| **BlockDownloadLinksFileType** | [BlockDownloadLinksFileTypes](#blockdownloadlinksfiletypes-enum) |  |
| **BlockDownloadOfAllFilesForGuests** | bool |  |
| **BlockDownloadOfAllFilesOnUnmanagedDevices** | bool |  |
| **BlockDownloadOfViewableFilesForGuests** | bool |  |
| **BlockDownloadOfViewableFilesOnUnmanagedDevices** | bool |  |
| **BlockMacSync** | bool |  |
| **BlockUserInfoVisibility** | string |  |
| **BlockUserInfoVisibilityInOneDrive** | [TenantBrowseUserInfoPolicyValue](#tenantbrowseuserinfopolicyvalue-enum) |  |
| **BlockUserInfoVisibilityInSharePoint** | [TenantBrowseUserInfoPolicyValue](#tenantbrowseuserinfopolicyvalue-enum) |  |
| **BusinessConnectivityServiceDisabled** | bool |  |
| **CommentsOnFilesDisabled** | bool |  |
| **CommentsOnListItemsDisabled** | bool |  |
| **CommentsOnSitePagesDisabled** | bool |  |
| **ConditionalAccessPolicy** | [SPOConditionalAccessPolicyType](#spoconditionalaccesspolicytype-enum) |  |
| **ConditionalAccessPolicyErrorHelpLink** | string |  |
| **ContainerDefaultLinkToExistingAccess** | bool |  |
| **ContainerDefaultShareLinkRole** | Role |  |
| **ContainerDefaultShareLinkScope** | SharingScope |  |
| **ContainerLoopDefaultShareLinkRole** | Role |  |
| **ContainerLoopDefaultShareLinkScope** | SharingScope |  |
| **ContainerSharingCapability** | [SharingCapabilities](#sharingcapabilities-enum) |  |
| **ContentTypeSyncSiteTemplatesList** | IEnumerable\<string\> |  |
| **CoreBlockGuestsAsSiteAdmin** | SharingState |  |
| **CoreDefaultLinkToExistingAccess** | bool |  |
| **CoreDefaultShareLinkRole** | Role |  |
| **CoreDefaultShareLinkScope** | SharingScope |  |
| **CoreLoopDefaultSharingLinkRole** | Role |  |
| **CoreLoopDefaultSharingLinkScope** | SharingScope |  |
| **CoreLoopSharingCapability** | [SharingCapabilities](#sharingcapabilities-enum) |  |
| **CoreRequestFilesLinkEnabled** | bool |  |
| **CoreRequestFilesLinkExpirationInDays** | int |  |
| **CoreSharingCapability** | [SharingCapabilities](#sharingcapabilities-enum) |  |
| **CustomizedExternalSharingServiceUrl** | string |  |
| **DefaultContentCenterSite** | [SiteInfoForSitePicker](#siteinfoforsitepicker-class) |  |
| **DefaultLinkPermission** | [SharingPermissionType](#sharingpermissiontype-enum) |  |
| **DefaultODBMode** | string |  |
| **DefaultSharingLinkType** | [SharingLinkType](#sharinglinktype-enum) |  |
| **DenySelectSecurityGroupsInSPSitesList** | IList\<string\> |  |
| **DenySelectSGsInODBList** | IList\<string\> |  |
| **DisableAddToOneDrive** | bool |  |
| **DisableBackToClassic** | bool |  |
| **DisableCustomAppAuthentication** | bool |  |
| **DisabledModernListTemplateIds** | Guid[] |  |
| **DisableOutlookPSTVersionTrimming** | bool |  |
| **DisablePersonalListCreation** | bool |  |
| **DisableSpacesActivation** | bool |  |
| **DisableVivaConnectionsAnalytics** | bool |  |
| **DisplayStartASiteOption** | bool |  |
| **EmailAttestationEnabled** | bool |  |
| **EmailAttestationReAuthDays** | int |  |
| **EmailAttestationRequired** | bool |  |
| **EnableAutoExpirationVersionTrim** | bool |  |
| **EnableAutoNewsDigest** | bool |  |
| **EnableAzureADB2BIntegration** | bool |  |
| **EnableGuestSignInAcceleration** | bool |  |
| **EnablePromotedFileHandlers** | bool |  |
| **EnableRestrictedAccessControl** | bool |  |
| **ESignatureEnabled** | bool |  |
| **ESignatureSiteInfoList** | IEnumerable\<[SiteInfoForSitePicker](#siteinfoforsitepicker-class)\> |  |
| **ESignatureSiteList** | IEnumerable\<Guid\> |  |
| **ESignatureSiteListFileName** | string |  |
| **ESignatureThirdPartyProviderInfoList** | IEnumerable\<[EsignatureThirdPartyProvidersInfo](#esignaturethirdpartyprovidersinfo-class)\> |  |
| **ESignatureThirdPartyProviderList** | IEnumerable\<string\> |  |
| **ESignatureThirdPartyProviderListFileName** | string |  |
| **ExcludedBlockDownloadGroupIds** | Guid[] |  |
| **ExcludedFileExtensionsForSyncClient** | IList\<string\> |  |
| **ExemptNativeUsersFromTenantLevelRestricedAccessControl** | bool |  |
| **ExpireVersionsAfterDays** | int |  |
| **ExternalServicesEnabled** | bool |  |
| **ExternalUserExpirationRequired** | bool |  |
| **ExternalUserExpireInDays** | int |  |
| **FileAnonymousLinkType** | AnonymousLinkType |  |
| **FilePickerExternalImageSearchEnabled** | bool |  |
| **FileVersionPolicyXml** | string |  |
| **FolderAnonymousLinkType** | AnonymousLinkType |  |
| **GetOrgAssets** | OrgAssets |  |
| **GuestSharingGroupAllowList** | string |  |
| **HasAdminCompletedCUConfiguration** | bool |  |
| **HideSyncButtonOnDocLib** | bool |  |
| **HideSyncButtonOnODB** | bool |  |
| **IBImplicitGroupBased** | bool |  |
| **ImageTaggingOption** | [ImageTaggingChoice](#imagetaggingchoice-enum) |  |
| **IncludeAtAGlanceInShareEmails** | bool |  |
| **InformationBarriersSuspension** | bool |  |
| **IPAddressAllowList** | string |  |
| **IPAddressEnforcement** | bool |  |
| **IPAddressWACTokenLifetime** | int |  |
| **IsUnmanagedSyncClientForTenantRestricted** | bool |  |
| **IsUnmanagedSyncClientRestrictionFlightEnabled** | bool |  |
| **LegacyAuthProtocolsEnabled** | bool |  |
| **LegacyBrowserAuthProtocolsEnabled** | bool |  |
| **LimitedAccessFileType** | [SPOLimitedAccessFileType](#spolimitedaccessfiletype-enum) |  |
| **MachineLearningCaptureEnabled** | bool |  |
| **MajorVersionLimit** | int |  |
| **MarkAllFilesAsSensitiveByDefault** | bool |  |
| **MassDeleteNotificationDisabled** | bool |  |
| **MediaTranscription** | [MediaTranscriptionPolicyType](#mediatranscriptionpolicytype-enum) |  |
| **MediaTranscriptionAutomaticFeatures** | [MediaTranscriptionAutomaticFeaturesPolicyType](#mediatranscriptionautomaticfeaturespolicytype-enum) |  |
| **MobileFriendlyUrlEnabled** | bool |  |
| **MySitesPublicEnabled** | bool |  |
| **NotificationsInOneDriveForBusinessEnabled** | bool |  |
| **NotificationsInSharePointEnabled** | bool |  |
| **NotifyOwnersWhenInvitationsAccepted** | bool |  |
| **NotifyOwnersWhenItemsReshared** | bool |  |
| **ODBAccessRequests** | SharingState |  |
| **ODBMembersCanShare** | SharingState |  |
| **ODBSensitivityRefreshWindowInHours** | ushort |  |
| **ODBSharingCapability** | [SharingCapabilities](#sharingcapabilities-enum) |  |
| **OfficeClientADALDisabled** | bool |  |
| **OneDriveBlockGuestsAsSiteAdmin** | SharingState |  |
| **OneDriveDefaultLinkToExistingAccess** | bool |  |
| **OneDriveDefaultShareLinkRole** | Role |  |
| **OneDriveDefaultShareLinkScope** | SharingScope |  |
| **OneDriveForGuestsEnabled** | bool |  |
| **OneDriveLoopDefaultSharingLinkRole** | Role |  |
| **OneDriveLoopDefaultSharingLinkScope** | SharingScope |  |
| **OneDriveLoopSharingCapability** | [SharingCapabilities](#sharingcapabilities-enum) |  |
| **OneDriveRequestFilesLinkEnabled** | bool |  |
| **OneDriveRequestFilesLinkExpirationInDays** | int |  |
| **OwnerAnonymousNotification** | bool |  |
| **PreventExternalUsersFromResharing** | bool |  |
| **ProvisionSharedWithEveryoneFolder** | bool |  |
| **PublicCdnAllowedFileTypes** | string |  |
| **PublicCdnEnabled** | bool |  |
| **PublicCdnOrigins** | IList\<string\> |  |
| **RecycleBinRetentionPeriod** | int |  |
| **ReduceTempTokenLifetimeEnabled** | bool |  |
| **ReduceTempTokenLifetimeValue** | int |  |
| **RequireAcceptingAccountMatchInvitedAccount** | bool |  |
| **RequireAnonymousLinksExpireInDays** | int |  |
| **SearchResolveExactEmailOrUPN** | bool |  |
| **SharingAllowedDomainList** | string |  |
| **SharingBlockedDomainList** | string |  |
| **SharingCapability** | [SharingCapabilities](#sharingcapabilities-enum) |  |
| **SharingDomainRestrictionMode** | [SharingDomainRestrictionModes](#sharingdomainrestrictionmodes-enum) |  |
| **ShowAllUsersClaim** | bool |  |
| **ShowEveryoneClaim** | bool |  |
| **ShowEveryoneExceptExternalUsersClaim** | bool |  |
| **ShowNGSCDialogForSyncOnODB** | bool |  |
| **ShowOpenInDesktopOptionForSyncedFiles** | bool |  |
| **ShowPeoplePickerGroupSuggestionsForIB** | bool |  |
| **ShowPeoplePickerSuggestionsForGuestUsers** | bool |  |
| **SignInAccelerationDomain** | string |  |
| **SiteOwnerManageLegacyServicePrincipalEnabled** | bool |  |
| **SocialBarOnSitePagesDisabled** | bool |  |
| **StartASiteFormUrl** | string |  |
| **StopNew2010Workflows** | bool |  |
| **StopNew2013Workflows** | bool |  |
| **StreamLaunchConfig** | int |  |
| **StreamLaunchConfigLastUpdated** | DateTime |  |
| **StreamLaunchConfigUpdateCount** | int |  |
| **SyncPrivacyProfileProperties** | bool |  |
| **SyntexBillingSubscriptionSettings** | [SyntexBillingContext](#syntexbillingcontext-class) |  |
| **SyntexExternalVideoSharingSettings** | [SyntexPremiumFeatureSettings](#syntexpremiumfeaturesettings-class) |  |
| **SyntexHighResolutionPlaybackSettings** | [SyntexPremiumFeatureSettings](#syntexpremiumfeaturesettings-class) |  |
| **SyntexInternalFeatureFlags** | IDictionary\<string, bool\> |  |
| **SyntexMediaAnalyticsSettings** | [SyntexPremiumFeatureSettings](#syntexpremiumfeaturesettings-class) |  |
| **SyntexPaygFeatureActivations** | IDictionary\<string, string\> |  |
| **SyntexPlaybackTranscriptTranslationSettings** | [SyntexPremiumFeatureSettings](#syntexpremiumfeaturesettings-class) |  |
| **SyntexPowerAppsEnvironmentsContext** | [SyntexPowerAppsEnvironmentsContext](#syntexpowerappsenvironmentscontext-class) |  |
| **TaxonomyTaggingEnabled** | bool |  |
| **TaxonomyTaggingSiteInfoList** | IEnumerable\<[SiteInfoForSitePicker](#siteinfoforsitepicker-class)\> |  |
| **TaxonomyTaggingSiteList** | IEnumerable\<Guid\> |  |
| **TaxonomyTaggingSiteListFileName** | string |  |
| **TlsTokenBindingPolicyValue** | [SPOTlsTokenBindingPolicyValue](#spotlstokenbindingpolicyvalue-enum) |  |
| **UseFindPeopleInPeoplePicker** | bool |  |
| **UsePersistentCookiesForExplorerView** | bool |  |
| **UserVoiceForFeedbackEnabled** | bool |  |
| **ViewersCanCommentOnMediaDisabled** | bool |  |
| **ViewInFileExplorerEnabled** | bool |  |
| **WhoCanShareAllowList** | string |  |
| **Workflow2010Disabled** | bool |  |
| **Workflows2013State** | [Workflows2013State](#workflows2013state-enum) |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **Office365Tenant(ClientRuntimeContext context)** |  |
| **Office365Tenant(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **AddPublicCdnOrigin(string origin)** | void |  |
| **AddSdnProvider(string identifier, string license)** | void |  |
| **AddTenantCdnOrigin(SPOTenantCdnType cdnType, string originUrl)** | void |  |
| **AddTenantTheme(string name, string themeJson)** | ClientResult\<bool\> |  |
| **AddToOrgAssetsLibAndCdn(SPOTenantCdnType cdnType, ResourcePath libUrl, ResourcePath thumbnailUrl, OrgAssetType orgAssetType, bool defaultOriginAdded)** | void |  |
| **CreateGroupForSite(string siteUrl, string displayName, string alias, bool isPublic, GroupCreationParams optionalParams)** | void |  |
| **CreateTenantCdnDefaultOrigins(SPOTenantCdnType cdnType)** | void |  |
| **DeleteImportProfilePropertiesJob(Guid jobId)** | ClientResult\<bool\> |  |
| **DeleteTenantTheme(string name)** | void |  |
| **DisableSharingForNonOwnersOfSite(string siteUrl)** | void |  |
| **GetAllTenantThemes()** | ClientObjectList\<[ThemeProperties](#themeproperties-class)\> |  |
| **GetCustomFontsMinorVersion(ResourcePath libUrl)** | ClientResult\<int\> |  |
| **GetExternalUsers(int position, int pageSize, string filter, SortOrder sortOrder)** | [GetExternalUsersResults](#getexternalusersresults-class) |  |
| **GetExternalUsersForSite(string siteUrl, int position, int pageSize, string filter, SortOrder sortOrder)** | [GetExternalUsersResults](#getexternalusersresults-class) |  |
| **GetExternalUsersWithSortBy(int position, int pageSize, string filter, string sortPropertyName, SortOrder sortOrder)** | [GetExternalUsersResults](#getexternalusersresults-class) |  |
| **GetHideDefaultThemes()** | ClientResult\<bool\> |  |
| **GetIdleSessionSignOutForUnmanagedDevices()** | ClientResult\<string\> |  |
| **GetImportProfilePropertyJob(Guid jobId)** | [ImportProfilePropertiesJobInfo](#importprofilepropertiesjobinfo-class) |  |
| **GetImportProfilePropertyJobs()** | [ImportProfilePropertiesJobStatusCollection](#importprofilepropertiesjobstatuscollection-class) |  |
| **GetPowerAppsEnvironmentList(Site rootSite)** | IEnumerable\<[PowerAppsEnvironment](#powerappsenvironment-class)\> |  |
| **GetTenantCdnEnabled(SPOTenantCdnType cdnType)** | ClientResult\<bool\> |  |
| **GetTenantCdnOrigins(SPOTenantCdnType cdnType)** | IList\<string\> |  |
| **GetTenantCdnPolicies(SPOTenantCdnType cdnType)** | IList\<string\> |  |
| **GetTenantTheme(string name)** | [ThemeProperties](#themeproperties-class) |  |
| **IncrementCustomFontsMinorVersion(ResourcePath libUrl)** | void |  |
| **IsSharingDisabledForNonOwnersOfSite(string siteUrl)** | ClientResult\<bool\> |  |
| **LogCustomFontsLargeUpload(int numCatalogs, int numFonts, int totalExpectedFiles)** | void |  |
| **QueueImportProfileProperties(ImportProfilePropertiesUserIdType idType, string sourceDataIdProperty, IDictionary\<string, string\> propertyMap, string sourceUri)** | ClientResult\<Guid\> |  |
| **RemoveExternalUsers(string[] uniqueIds)** | [RemoveExternalUsersResults](#removeexternalusersresults-class) |  |
| **RemoveFromOrgAssets(ResourcePath libUrl, Guid listId)** | void |  |
| **RemoveFromOrgAssetsAndCdn(bool remove, SPOTenantCdnType cdnType, ResourcePath libUrl)** | void |  |
| **RemovePreviousCustomFontUpload(IList\<string\> majVersions, ResourcePath libUrl)** | void |  |
| **RemovePublicCdnOrigin(string originId)** | void |  |
| **RemoveSdnProvider()** | void |  |
| **RemoveTenantCdnOrigin(SPOTenantCdnType cdnType, string originUrl)** | void |  |
| **RevokeAllUserSessions(string userName)** | [SPOUserSessionRevocationResult](#spousersessionrevocationresult-class) |  |
| **RevokeAllUserSessionsByPuid(IList\<string\> puidList)** | ClientObjectList\<[SPOUserSessionRevocationResult](#spousersessionrevocationresult-class)\> |  |
| **SetBlockDownloadFileTypePolicyData(bool blockDownloadFileTypePolicy, SPBlockDownloadFileTypeId[] fileTypeIds, Guid[] excludedBlockDownloadGroupIds)** | void |  |
| **SetBlockDownloadFileTypePolicyExclusionList(Guid[] excludedBlockDownloadGroupIds)** | void |  |
| **SetHideDefaultThemes(bool hideDefaultThemes)** | ClientResult\<bool\> |  |
| **SetIdleSessionSignOutForUnmanagedDevices(bool enabled, TimeSpan warnAfter, TimeSpan signOutAfter)** | ClientResult\<bool\> |  |
| **SetJitDlpPolicyData(bool markAllFilesAsSensitiveByDefault, ushort odbSensitivityRefreshWindowInHours)** | void |  |
| **SetOrgAssetsLib(ResourcePath libUrl, ResourcePath thumbnailUrl, OrgAssetType orgAssetType)** | void |  |
| **SetTenantCdnEnabled(SPOTenantCdnType cdnType, bool isEnabled)** | void |  |
| **SetTenantCdnPolicy(SPOTenantCdnType cdnType, SPOTenantCdnPolicyType policy, string policyValue)** | void |  |
| **SyncAadB2BManagementPolicy()** | void |  |
| **UpdateTenantTheme(string name, string themeJson)** | ClientResult\<bool\> |  |
| **UploadCustomFontsAndCatalogLib(IList\<CustomFontsResource\> customFontFiles, ResourcePath libUrl)** | ClientResult\<bool\> |  |
# Office365TenantPropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantManagement


## Fields

| Name | Type | Summary |
|---|---|---|
| **AddressbarLinkPermission** | string |  |
| **AllowAnonymousMeetingParticipantsToAccessWhiteboards** | string |  |
| **AllowCommentsTextOnEmailEnabled** | string |  |
| **AllowDownloadingNonWebViewableFiles** | string |  |
| **AllowedDomainListForSyncClient** | string |  |
| **AllowEditing** | string |  |
| **AllowEveryoneExceptExternalUsersClaimInPrivateSite** | string |  |
| **AllowGuestUserShareToUsersNotInSiteCollection** | string |  |
| **AllowLimitedAccessOnUnmanagedDevices** | string |  |
| **AllowOverrideForBlockUserInfoVisibility** | string |  |
| **AllowSelectSecurityGroupsInSPSitesList** | string |  |
| **AllowSelectSGsInODBList** | string |  |
| **AnyoneLinkTrackUsers** | string |  |
| **AppBypassInformationBarriers** | string |  |
| **ApplyAppEnforcedRestrictionsToAdHocRecipients** | string |  |
| **AppOnlyBypassPeoplePickerPolicies** | string |  |
| **AuthContextResilienceMode** | string |  |
| **BccExternalSharingInvitations** | string |  |
| **BccExternalSharingInvitationsList** | string |  |
| **BlockAccessOnUnmanagedDevices** | string |  |
| **BlockAppAccessWithAuthenticationContext** | string |  |
| **BlockDownloadFileTypeIds** | string |  |
| **BlockDownloadFileTypePolicy** | string |  |
| **BlockDownloadLinksFileType** | string |  |
| **BlockDownloadOfAllFilesForGuests** | string |  |
| **BlockDownloadOfAllFilesOnUnmanagedDevices** | string |  |
| **BlockDownloadOfViewableFilesForGuests** | string |  |
| **BlockDownloadOfViewableFilesOnUnmanagedDevices** | string |  |
| **BlockMacSync** | string |  |
| **BlockUserInfoVisibility** | string |  |
| **BlockUserInfoVisibilityInOneDrive** | string |  |
| **BlockUserInfoVisibilityInSharePoint** | string |  |
| **BusinessConnectivityServiceDisabled** | string |  |
| **CommentsOnFilesDisabled** | string |  |
| **CommentsOnListItemsDisabled** | string |  |
| **CommentsOnSitePagesDisabled** | string |  |
| **ConditionalAccessPolicy** | string |  |
| **ConditionalAccessPolicyErrorHelpLink** | string |  |
| **ContainerDefaultLinkToExistingAccess** | string |  |
| **ContainerDefaultShareLinkRole** | string |  |
| **ContainerDefaultShareLinkScope** | string |  |
| **ContainerLoopDefaultShareLinkRole** | string |  |
| **ContainerLoopDefaultShareLinkScope** | string |  |
| **ContainerSharingCapability** | string |  |
| **ContentTypeSyncSiteTemplatesList** | string |  |
| **CoreBlockGuestsAsSiteAdmin** | string |  |
| **CoreDefaultLinkToExistingAccess** | string |  |
| **CoreDefaultShareLinkRole** | string |  |
| **CoreDefaultShareLinkScope** | string |  |
| **CoreLoopDefaultSharingLinkRole** | string |  |
| **CoreLoopDefaultSharingLinkScope** | string |  |
| **CoreLoopSharingCapability** | string |  |
| **CoreRequestFilesLinkEnabled** | string |  |
| **CoreRequestFilesLinkExpirationInDays** | string |  |
| **CoreSharingCapability** | string |  |
| **CustomizedExternalSharingServiceUrl** | string |  |
| **DefaultContentCenterSite** | string |  |
| **DefaultLinkPermission** | string |  |
| **DefaultODBMode** | string |  |
| **DefaultSharingLinkType** | string |  |
| **DenySelectSecurityGroupsInSPSitesList** | string |  |
| **DenySelectSGsInODBList** | string |  |
| **DisableAddToOneDrive** | string |  |
| **DisableBackToClassic** | string |  |
| **DisableCustomAppAuthentication** | string |  |
| **DisabledModernListTemplateIds** | string |  |
| **DisableOutlookPSTVersionTrimming** | string |  |
| **DisablePersonalListCreation** | string |  |
| **DisableSpacesActivation** | string |  |
| **DisableVivaConnectionsAnalytics** | string |  |
| **DisplayStartASiteOption** | string |  |
| **EmailAttestationEnabled** | string |  |
| **EmailAttestationReAuthDays** | string |  |
| **EmailAttestationRequired** | string |  |
| **EnableAutoExpirationVersionTrim** | string |  |
| **EnableAutoNewsDigest** | string |  |
| **EnableAzureADB2BIntegration** | string |  |
| **EnableGuestSignInAcceleration** | string |  |
| **EnablePromotedFileHandlers** | string |  |
| **EnableRestrictedAccessControl** | string |  |
| **ESignatureEnabled** | string |  |
| **ESignatureSiteInfoList** | string |  |
| **ESignatureSiteList** | string |  |
| **ESignatureSiteListFileName** | string |  |
| **ESignatureThirdPartyProviderInfoList** | string |  |
| **ESignatureThirdPartyProviderList** | string |  |
| **ESignatureThirdPartyProviderListFileName** | string |  |
| **ExcludedBlockDownloadGroupIds** | string |  |
| **ExcludedFileExtensionsForSyncClient** | string |  |
| **ExemptNativeUsersFromTenantLevelRestricedAccessControl** | string |  |
| **ExpireVersionsAfterDays** | string |  |
| **ExternalServicesEnabled** | string |  |
| **ExternalUserExpirationRequired** | string |  |
| **ExternalUserExpireInDays** | string |  |
| **FileAnonymousLinkType** | string |  |
| **FilePickerExternalImageSearchEnabled** | string |  |
| **FileVersionPolicyXml** | string |  |
| **FolderAnonymousLinkType** | string |  |
| **GetOrgAssets** | string |  |
| **GuestSharingGroupAllowList** | string |  |
| **HasAdminCompletedCUConfiguration** | string |  |
| **HideSyncButtonOnDocLib** | string |  |
| **HideSyncButtonOnODB** | string |  |
| **IBImplicitGroupBased** | string |  |
| **ImageTaggingOption** | string |  |
| **IncludeAtAGlanceInShareEmails** | string |  |
| **InformationBarriersSuspension** | string |  |
| **IPAddressAllowList** | string |  |
| **IPAddressEnforcement** | string |  |
| **IPAddressWACTokenLifetime** | string |  |
| **IsUnmanagedSyncClientForTenantRestricted** | string |  |
| **IsUnmanagedSyncClientRestrictionFlightEnabled** | string |  |
| **LegacyAuthProtocolsEnabled** | string |  |
| **LegacyBrowserAuthProtocolsEnabled** | string |  |
| **LimitedAccessFileType** | string |  |
| **MachineLearningCaptureEnabled** | string |  |
| **MajorVersionLimit** | string |  |
| **MarkAllFilesAsSensitiveByDefault** | string |  |
| **MassDeleteNotificationDisabled** | string |  |
| **MediaTranscription** | string |  |
| **MediaTranscriptionAutomaticFeatures** | string |  |
| **MobileFriendlyUrlEnabled** | string |  |
| **MySitesPublicEnabled** | string |  |
| **NotificationsInOneDriveForBusinessEnabled** | string |  |
| **NotificationsInSharePointEnabled** | string |  |
| **NotifyOwnersWhenInvitationsAccepted** | string |  |
| **NotifyOwnersWhenItemsReshared** | string |  |
| **ODBAccessRequests** | string |  |
| **ODBMembersCanShare** | string |  |
| **ODBSensitivityRefreshWindowInHours** | string |  |
| **ODBSharingCapability** | string |  |
| **OfficeClientADALDisabled** | string |  |
| **OneDriveBlockGuestsAsSiteAdmin** | string |  |
| **OneDriveDefaultLinkToExistingAccess** | string |  |
| **OneDriveDefaultShareLinkRole** | string |  |
| **OneDriveDefaultShareLinkScope** | string |  |
| **OneDriveForGuestsEnabled** | string |  |
| **OneDriveLoopDefaultSharingLinkRole** | string |  |
| **OneDriveLoopDefaultSharingLinkScope** | string |  |
| **OneDriveLoopSharingCapability** | string |  |
| **OneDriveRequestFilesLinkEnabled** | string |  |
| **OneDriveRequestFilesLinkExpirationInDays** | string |  |
| **OwnerAnonymousNotification** | string |  |
| **PreventExternalUsersFromResharing** | string |  |
| **ProvisionSharedWithEveryoneFolder** | string |  |
| **PublicCdnAllowedFileTypes** | string |  |
| **PublicCdnEnabled** | string |  |
| **PublicCdnOrigins** | string |  |
| **RecycleBinRetentionPeriod** | string |  |
| **ReduceTempTokenLifetimeEnabled** | string |  |
| **ReduceTempTokenLifetimeValue** | string |  |
| **RequireAcceptingAccountMatchInvitedAccount** | string |  |
| **RequireAnonymousLinksExpireInDays** | string |  |
| **SearchResolveExactEmailOrUPN** | string |  |
| **SharingAllowedDomainList** | string |  |
| **SharingBlockedDomainList** | string |  |
| **SharingCapability** | string |  |
| **SharingDomainRestrictionMode** | string |  |
| **ShowAllUsersClaim** | string |  |
| **ShowEveryoneClaim** | string |  |
| **ShowEveryoneExceptExternalUsersClaim** | string |  |
| **ShowNGSCDialogForSyncOnODB** | string |  |
| **ShowOpenInDesktopOptionForSyncedFiles** | string |  |
| **ShowPeoplePickerGroupSuggestionsForIB** | string |  |
| **ShowPeoplePickerSuggestionsForGuestUsers** | string |  |
| **SignInAccelerationDomain** | string |  |
| **SiteOwnerManageLegacyServicePrincipalEnabled** | string |  |
| **SocialBarOnSitePagesDisabled** | string |  |
| **StartASiteFormUrl** | string |  |
| **StopNew2010Workflows** | string |  |
| **StopNew2013Workflows** | string |  |
| **StreamLaunchConfig** | string |  |
| **StreamLaunchConfigLastUpdated** | string |  |
| **StreamLaunchConfigUpdateCount** | string |  |
| **SyncPrivacyProfileProperties** | string |  |
| **SyntexBillingSubscriptionSettings** | string |  |
| **SyntexExternalVideoSharingSettings** | string |  |
| **SyntexHighResolutionPlaybackSettings** | string |  |
| **SyntexInternalFeatureFlags** | string |  |
| **SyntexMediaAnalyticsSettings** | string |  |
| **SyntexPaygFeatureActivations** | string |  |
| **SyntexPlaybackTranscriptTranslationSettings** | string |  |
| **SyntexPowerAppsEnvironmentsContext** | string |  |
| **TaxonomyTaggingEnabled** | string |  |
| **TaxonomyTaggingSiteInfoList** | string |  |
| **TaxonomyTaggingSiteList** | string |  |
| **TaxonomyTaggingSiteListFileName** | string |  |
| **TlsTokenBindingPolicyValue** | string |  |
| **UseFindPeopleInPeoplePicker** | string |  |
| **UsePersistentCookiesForExplorerView** | string |  |
| **UserVoiceForFeedbackEnabled** | string |  |
| **ViewersCanCommentOnMediaDisabled** | string |  |
| **ViewInFileExplorerEnabled** | string |  |
| **WhoCanShareAllowList** | string |  |
| **Workflow2010Disabled** | string |  |
| **Workflows2013State** | string |  |
# RemoveExternalUsersResults Class

Namespace: Microsoft.Online.SharePoint.TenantManagement

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **RemoveFailed** | string[] |  |
| **RemoveSucceeded** | string[] |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **RemoveExternalUsersResults(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# RemoveExternalUsersResultsPropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantManagement


## Fields

| Name | Type | Summary |
|---|---|---|
| **RemoveFailed** | string |  |
| **RemoveSucceeded** | string |  |
# SensitiveByDefaultState Enum

Namespace: Microsoft.Online.SharePoint.TenantManagement


## Values

| Name | Summary |
|---|---|
| **AllowExternalSharing** |  |
| **BlockExternalSharing** |  |
# SharingCapabilities Enum

Namespace: Microsoft.Online.SharePoint.TenantManagement


## Values

| Name | Summary |
|---|---|
| **Disabled** |  |
| **ExternalUserSharingOnly** |  |
| **ExternalUserAndGuestSharing** |  |
| **ExistingExternalUserSharingOnly** |  |
# SharingDomainRestrictionModes Enum

Namespace: Microsoft.Online.SharePoint.TenantManagement


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **AllowList** |  |
| **BlockList** |  |
# SharingLinkType Enum

Namespace: Microsoft.Online.SharePoint.TenantManagement


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **Direct** |  |
| **Internal** |  |
| **AnonymousAccess** |  |
# SharingPermissionType Enum

Namespace: Microsoft.Online.SharePoint.TenantManagement


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **View** |  |
| **Edit** |  |
# SortOrder Enum

Namespace: Microsoft.Online.SharePoint.TenantManagement


## Values

| Name | Summary |
|---|---|
| **Ascending** |  |
| **Descending** |  |
# SpecialCharactersState Enum

Namespace: Microsoft.Online.SharePoint.TenantManagement


## Values

| Name | Summary |
|---|---|
| **NoPreference** |  |
| **Allowed** |  |
| **Disallowed** |  |
# SPOAuthenticationContextPolicyAccessType Enum

Namespace: Microsoft.Online.SharePoint.TenantManagement


## Values

| Name | Summary |
|---|---|
| **AllowLimitedAccess** |  |
| **BlockAccess** |  |
# SPOConditionalAccessPolicyType Enum

Namespace: Microsoft.Online.SharePoint.TenantManagement


## Values

| Name | Summary |
|---|---|
| **AllowFullAccess** |  |
| **AllowLimitedAccess** |  |
| **BlockAccess** |  |
| **AuthenticationContext** |  |
# SPOLimitedAccessFileType Enum

Namespace: Microsoft.Online.SharePoint.TenantManagement


## Values

| Name | Summary |
|---|---|
| **OfficeOnlineFilesOnly** |  |
| **WebPreviewableFiles** |  |
| **OtherFiles** |  |
# SPOTlsTokenBindingPolicyValue Enum

Namespace: Microsoft.Online.SharePoint.TenantManagement


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **Audit** |  |
| **PassiveEnforcement** |  |
| **StrictEnforcement** |  |
# SPOUserSessionRevocationResult Class

Namespace: Microsoft.Online.SharePoint.TenantManagement

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **State** | [SPOUserSessionRevocationState](#spousersessionrevocationstate-enum) |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **SPOUserSessionRevocationResult(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# SPOUserSessionRevocationResultPropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantManagement


## Fields

| Name | Type | Summary |
|---|---|---|
| **State** | string |  |
# SPOUserSessionRevocationState Enum

Namespace: Microsoft.Online.SharePoint.TenantManagement


## Values

| Name | Summary |
|---|---|
| **FeatureDisabled** |  |
| **UserNotFound** |  |
| **Failure** |  |
| **NonInstantaneousSuccess** |  |
| **InstantaneousSuccess** |  |
# StreamLaunchConfigValues Enum

Namespace: Microsoft.Online.SharePoint.TenantManagement


## Values

| Name | Summary |
|---|---|
| **Classic** |  |
| **LetMSDecide** |  |
| **NewTenant** |  |
| **StreamOnSharepoint** |  |
# ThemeProperties Class

Namespace: Microsoft.Online.SharePoint.TenantManagement

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **IsInverted** | bool |  |
| **Name** | string |  |
| **Palette** | IDictionary\<string, string\> |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **ThemeProperties(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ThemePropertiesPropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantManagement


## Fields

| Name | Type | Summary |
|---|---|---|
| **IsInverted** | string |  |
| **Name** | string |  |
| **Palette** | string |  |
# Workflows2013State Enum

Namespace: Microsoft.Online.SharePoint.TenantManagement


## Values

| Name | Summary |
|---|---|
| **Disabled** |  |
| **Configuring** |  |
| **Enabled** |  |
