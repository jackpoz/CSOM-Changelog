# Microsoft.Online.SharePoint.Client.Tenant.dll v.16.1.0.0 API documentation

Created by 
[mddox](https://github.com/loxsmoke/mddox) on 07/04/2023

# All types

|   |   |   |
|---|---|---|
| [ScriptTypeFactory Class](#scripttypefactory-class) | [SpoOperationPropertyNames Class](#spooperationpropertynames-class) | [TenantTemplateDesignType Enum](#tenanttemplatedesigntype-enum) |
| [ConnectionStatus Enum](#connectionstatus-enum) | [SPOPortalLaunchValidationResult Class](#spoportallaunchvalidationresult-class) | [UserInfo Class](#userinfo-class) |
| [CredentialsType Enum](#credentialstype-enum) | [SPOPortalLaunchValidationResultPropertyNames Class](#spoportallaunchvalidationresultpropertynames-class) | [UserMigrationProperties Class](#usermigrationproperties-class) |
| [DeviceActionId Enum](#deviceactionid-enum) | [SPOPortalLaunchValidationResultTypes Enum](#spoportallaunchvalidationresulttypes-enum) | [UserMigrationPropertiesEnumerable Class](#usermigrationpropertiesenumerable-class) |
| [DeviceStatus Enum](#devicestatus-enum) | [SPOPortalLaunchValidator Class](#spoportallaunchvalidator-class) | [UserMigrationPropertiesEnumerableFilter Class](#usermigrationpropertiesenumerablefilter-class) |
| [MigrationTaskStatus Enum](#migrationtaskstatus-enum) | [SPOSitePropertiesEnumerable Class](#spositepropertiesenumerable-class) | [UserMigrationPropertiesEnumerablePropertyNames Class](#usermigrationpropertiesenumerablepropertynames-class) |
| [SourceType Enum](#sourcetype-enum) | [SPOSitePropertiesEnumerableFilter Class](#spositepropertiesenumerablefilter-class) | [UserMigrationPropertiesPropertyNames Class](#usermigrationpropertiespropertynames-class) |
| [StorageActionId Enum](#storageactionid-enum) | [SPOSitePropertiesEnumerablePropertyNames Class](#spositepropertiesenumerablepropertynames-class) | [SPO3rdPartyAADPermissionGrant Class](#spo3rdpartyaadpermissiongrant-class) |
| [TaskActionId Enum](#taskactionid-enum) | [SPOTenantCdnPolicy Class](#spotenantcdnpolicy-class) | [SPO3rdPartyAADPermissionGrantManager Class](#spo3rdpartyaadpermissiongrantmanager-class) |
| [TaskErrorCode Enum](#taskerrorcode-enum) | [SPOTenantCdnPolicyPropertyNames Class](#spotenantcdnpolicypropertynames-class) | [SPO3rdPartyAADPermissionGrantPropertyNames Class](#spo3rdpartyaadpermissiongrantpropertynames-class) |
| [TaskFailure Enum](#taskfailure-enum) | [SPOTenantCdnPolicyType Enum](#spotenantcdnpolicytype-enum) | [SPOWebAppServicePrincipal Class](#spowebappserviceprincipal-class) |
| [TaskManagementStatus Enum](#taskmanagementstatus-enum) | [SPOTenantCdnType Enum](#spotenantcdntype-enum) | [SPOWebAppServicePrincipalObjectPropertyNames Class](#spowebappserviceprincipalobjectpropertynames-class) |
| [LogExport Class](#logexport-class) | [SPOTenantGroupIdentityMapping Class](#spotenantgroupidentitymapping-class) | [SPOWebAppServicePrincipalPermissionGrant Class](#spowebappserviceprincipalpermissiongrant-class) |
| [LogFileInfo Class](#logfileinfo-class) | [SPOTenantGroupIdentityMappingPropertyNames Class](#spotenantgroupidentitymappingpropertynames-class) | [SPOWebAppServicePrincipalPermissionGrantCollection Class](#spowebappserviceprincipalpermissiongrantcollection-class) |
| [LogFileInfoPropertyNames Class](#logfileinfopropertynames-class) | [SPOTenantInstance Class](#spotenantinstance-class) | [SPOWebAppServicePrincipalPermissionGrantPropertyNames Class](#spowebappserviceprincipalpermissiongrantpropertynames-class) |
| [DDIAdapter Class](#ddiadapter-class) | [SPOTenantInstancePropertyNames Class](#spotenantinstancepropertynames-class) | [SPOWebAppServicePrincipalPermissionRequest Class](#spowebappserviceprincipalpermissionrequest-class) |
| [AppErrorEntry Class](#apperrorentry-class) | [SPOTenantSiteUserInvitation Class](#spotenantsiteuserinvitation-class) | [SPOWebAppServicePrincipalPermissionRequestCollection Class](#spowebappserviceprincipalpermissionrequestcollection-class) |
| [AppErrorEntryPropertyNames Class](#apperrorentrypropertynames-class) | [SPOTenantSiteUserInvitationPropertyNames Class](#spotenantsiteuserinvitationpropertynames-class) | [SPOWebAppServicePrincipalPermissionRequestPropertyNames Class](#spowebappserviceprincipalpermissionrequestpropertynames-class) |
| [AppErrorType Enum](#apperrortype-enum) | [SPOTenantUserIdentityMapping Class](#spotenantuseridentitymapping-class) | [SPOWebAppServicePrincipalPropertyNames Class](#spowebappserviceprincipalpropertynames-class) |
| [AppInfo Class](#appinfo-class) | [SPOTenantUserIdentityMappingPropertyNames Class](#spotenantuseridentitymappingpropertynames-class) | [BlockDownloadLinksFileTypes Enum](#blockdownloadlinksfiletypes-enum) |
| [AppInfoPropertyNames Class](#appinfopropertynames-class) | [SPOTenantWebTemplate Class](#spotenantwebtemplate-class) | [ExternalUser Class](#externaluser-class) |
| [AppSource Enum](#appsource-enum) | [SPOTenantWebTemplateCollection Class](#spotenantwebtemplatecollection-class) | [ExternalUserCollection Class](#externalusercollection-class) |
| [AppViewsPolicy Enum](#appviewspolicy-enum) | [Tenant Class](#tenant-class) | [ExternalUserPropertyNames Class](#externaluserpropertynames-class) |
| [CompanyWideSharingLinksPolicy Enum](#companywidesharinglinkspolicy-enum) | [TenantBrowseUserInfoPolicyValue Enum](#tenantbrowseuserinfopolicyvalue-enum) | [GetExternalUsersResults Class](#getexternalusersresults-class) |
| [DeletedSiteProperties Class](#deletedsiteproperties-class) | [TenantListDesign Class](#tenantlistdesign-class) | [GetExternalUsersResultsObjectPropertyNames Class](#getexternalusersresultsobjectpropertynames-class) |
| [DeletedSitePropertiesPropertyNames Class](#deletedsitepropertiespropertynames-class) | [TenantListDesignColor Enum](#tenantlistdesigncolor-enum) | [GetExternalUsersResultsPropertyNames Class](#getexternalusersresultspropertynames-class) |
| [DenyAddAndCustomizePagesStatus Enum](#denyaddandcustomizepagesstatus-enum) | [TenantListDesignCreationInfo Class](#tenantlistdesigncreationinfo-class) | [GroupCreationParams Class](#groupcreationparams-class) |
| [FlowsPolicy Enum](#flowspolicy-enum) | [TenantListDesignIcon Enum](#tenantlistdesignicon-enum) | [GroupCreationParamsPropertyNames Class](#groupcreationparamspropertynames-class) |
| [GroupInfo Class](#groupinfo-class) | [TenantListDesignPropertyNames Class](#tenantlistdesignpropertynames-class) | [ImageTaggingChoice Enum](#imagetaggingchoice-enum) |
| [HubSitePermission Class](#hubsitepermission-class) | [TenantLog Class](#tenantlog-class) | [ImportProfilePropertiesJobError Enum](#importprofilepropertiesjoberror-enum) |
| [HubSiteProperties Class](#hubsiteproperties-class) | [TenantLogEntry Class](#tenantlogentry-class) | [ImportProfilePropertiesJobInfo Class](#importprofilepropertiesjobinfo-class) |
| [HubSitePropertiesPropertyNames Class](#hubsitepropertiespropertynames-class) | [TenantLogEntryPropertyNames Class](#tenantlogentrypropertynames-class) | [ImportProfilePropertiesJobInfoPropertyNames Class](#importprofilepropertiesjobinfopropertynames-class) |
| [ISPOPortalLaunchValidator Class](#ispoportallaunchvalidator-class) | [TenantLogPropertyNames Class](#tenantlogpropertynames-class) | [ImportProfilePropertiesJobState Enum](#importprofilepropertiesjobstate-enum) |
| [MessagesFieldsData Class](#messagesfieldsdata-class) | [TenantPropertyNames Class](#tenantpropertynames-class) | [ImportProfilePropertiesJobStatusCollection Class](#importprofilepropertiesjobstatuscollection-class) |
| [OdbMigrationStatus Enum](#odbmigrationstatus-enum) | [TenantSiteDesign Class](#tenantsitedesign-class) | [ImportProfilePropertiesUserIdType Enum](#importprofilepropertiesuseridtype-enum) |
| [PersonalSiteFilter Enum](#personalsitefilter-enum) | [TenantSiteDesignCreationInfo Class](#tenantsitedesigncreationinfo-class) | [Office365Tenant Class](#office365tenant-class) |
| [PowerAppsEnvironment Class](#powerappsenvironment-class) | [TenantSiteDesignPrincipal Class](#tenantsitedesignprincipal-class) | [Office365TenantPropertyNames Class](#office365tenantpropertynames-class) |
| [PWAEnabledStatus Enum](#pwaenabledstatus-enum) | [TenantSiteDesignPrincipalPropertyNames Class](#tenantsitedesignprincipalpropertynames-class) | [RemoveExternalUsersResults Class](#removeexternalusersresults-class) |
| [RestrictedToRegion Enum](#restrictedtoregion-enum) | [TenantSiteDesignPrincipalRights Enum](#tenantsitedesignprincipalrights-enum) | [RemoveExternalUsersResultsPropertyNames Class](#removeexternalusersresultspropertynames-class) |
| [SandboxedCodeActivationCapabilities Enum](#sandboxedcodeactivationcapabilities-enum) | [TenantSiteDesignPropertyNames Class](#tenantsitedesignpropertynames-class) | [SensitiveByDefaultState Enum](#sensitivebydefaultstate-enum) |
| [SecondaryAdministratorsFieldsData Class](#secondaryadministratorsfieldsdata-class) | [TenantSiteDesignRun Class](#tenantsitedesignrun-class) | [SharingCapabilities Enum](#sharingcapabilities-enum) |
| [SecondaryAdministratorsInfo Class](#secondaryadministratorsinfo-class) | [TenantSiteDesignRunPropertyNames Class](#tenantsitedesignrunpropertynames-class) | [SharingDomainRestrictionModes Enum](#sharingdomainrestrictionmodes-enum) |
| [SiteCreationProperties Class](#sitecreationproperties-class) | [TenantSiteDesignTask Class](#tenantsitedesigntask-class) | [SharingLinkType Enum](#sharinglinktype-enum) |
| [SiteInfoForSitePicker Class](#siteinfoforsitepicker-class) | [TenantSiteDesignTaskPropertyNames Class](#tenantsitedesigntaskpropertynames-class) | [SharingPermissionType Enum](#sharingpermissiontype-enum) |
| [SiteProperties Class](#siteproperties-class) | [TenantSiteScript Class](#tenantsitescript-class) | [SortOrder Enum](#sortorder-enum) |
| [SitePropertiesPropertyNames Class](#sitepropertiespropertynames-class) | [TenantSiteScriptActionOutcome Enum](#tenantsitescriptactionoutcome-enum) | [SpecialCharactersState Enum](#specialcharactersstate-enum) |
| [SiteRenameStatesInTenantRename Enum](#siterenamestatesintenantrename-enum) | [TenantSiteScriptActionResult Class](#tenantsitescriptactionresult-class) | [SPOConditionalAccessPolicyType Enum](#spoconditionalaccesspolicytype-enum) |
| [SiteUserGroupInfo Class](#siteusergroupinfo-class) | [TenantSiteScriptActionResultPropertyNames Class](#tenantsitescriptactionresultpropertynames-class) | [SPOLimitedAccessFileType Enum](#spolimitedaccessfiletype-enum) |
| [SiteUserGroupsData Class](#siteusergroupsdata-class) | [TenantSiteScriptActionStatus Class](#tenantsitescriptactionstatus-class) | [SPOUserSessionRevocationResult Class](#spousersessionrevocationresult-class) |
| [SiteUserInfoVisibilityPolicyValue Enum](#siteuserinfovisibilitypolicyvalue-enum) | [TenantSiteScriptActionStatusPropertyNames Class](#tenantsitescriptactionstatuspropertynames-class) | [SPOUserSessionRevocationResultPropertyNames Class](#spousersessionrevocationresultpropertynames-class) |
| [SPODeletedSitePropertiesEnumerable Class](#spodeletedsitepropertiesenumerable-class) | [TenantSiteScriptCreationInfo Class](#tenantsitescriptcreationinfo-class) | [SPOUserSessionRevocationState Enum](#spousersessionrevocationstate-enum) |
| [SPODeletedSitePropertiesEnumerablePropertyNames Class](#spodeletedsitepropertiesenumerablepropertynames-class) | [TenantSiteScriptPropertyNames Class](#tenantsitescriptpropertynames-class) | [ThemeProperties Class](#themeproperties-class) |
| [SPOHubSiteUserRights Enum](#spohubsiteuserrights-enum) | [TenantSiteScriptSerializationInfo Class](#tenantsitescriptserializationinfo-class) | [ThemePropertiesPropertyNames Class](#themepropertiespropertynames-class) |
| [SpoOperation Class](#spooperation-class) | [TenantSiteScriptSerializationResult Class](#tenantsitescriptserializationresult-class) | [Workflows2013State Enum](#workflows2013state-enum) |
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
| **Scheduled** |  |
| **Working** |  |
| **Upgrading** |  |
| **Disabling** |  |
| **Disabled** |  |
| **Enabling** |  |
| **Disconnected** |  |
| **NotAccessible** |  |
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
| **ScheduleTask** |  |
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
| **Scheduled** |  |
| **Running** |  |
| **Pausing** |  |
| **Paused** |  |
| **Resuming** |  |
| **Cancelling** |  |
| **Completed** |  |
| **Failed** |  |
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
# CompanyWideSharingLinksPolicy Enum

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Values

| Name | Summary |
|---|---|
| **Unknown** |  |
| **Disabled** |  |
| **NotDisabled** |  |
# DeletedSiteProperties Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
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
# PWAEnabledStatus Enum

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Values

| Name | Summary |
|---|---|
| **Unknown** |  |
| **Disabled** |  |
| **Enabled** |  |
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
| **AuthContextStrength** | string |  |
| **AverageResourceUsage** | double |  |
| **BlockDownloadLinksFileType** | [BlockDownloadLinksFileTypes](#blockdownloadlinksfiletypes-enum) |  |
| **CommentsOnSitePagesDisabled** | bool |  |
| **CompatibilityLevel** | int |  |
| **ConditionalAccessPolicy** | [SPOConditionalAccessPolicyType](#spoconditionalaccesspolicytype-enum) |  |
| **CurrentResourceUsage** | double |  |
| **DefaultLinkPermission** | [SharingPermissionType](#sharingpermissiontype-enum) |  |
| **DefaultLinkToExistingAccess** | bool |  |
| **DefaultLinkToExistingAccessReset** | bool |  |
| **DefaultSharingLinkType** | [SharingLinkType](#sharinglinktype-enum) |  |
| **DenyAddAndCustomizePages** | [DenyAddAndCustomizePagesStatus](#denyaddandcustomizepagesstatus-enum) |  |
| **Description** | string |  |
| **DisableAppViews** | [AppViewsPolicy](#appviewspolicy-enum) |  |
| **DisableCompanyWideSharingLinks** | [CompanyWideSharingLinksPolicy](#companywidesharinglinkspolicy-enum) |  |
| **DisableFlows** | [FlowsPolicy](#flowspolicy-enum) |  |
| **ExternalUserExpirationInDays** | int |  |
| **GroupId** | Guid |  |
| **GroupOwnerLoginName** | string |  |
| **HasHolds** | bool |  |
| **HubSiteId** | Guid |  |
| **IBSegments** | Guid[] |  |
| **IBSegmentsToAdd** | Guid[] |  |
| **IBSegmentsToRemove** | Guid[] |  |
| **IsGroupOwnerSiteAdmin** | bool |  |
| **IsHubSite** | bool |  |
| **LastContentModifiedDate** | DateTime |  |
| **Lcid** | uint |  |
| **LimitedAccessFileType** | [SPOLimitedAccessFileType](#spolimitedaccessfiletype-enum) |  |
| **LockIssue** | string |  |
| **LockState** | string |  |
| **OverrideBlockUserInfoVisibility** | [SiteUserInfoVisibilityPolicyValue](#siteuserinfovisibilitypolicyvalue-enum) |  |
| **OverrideTenantAnonymousLinkExpirationPolicy** | bool |  |
| **OverrideTenantExternalUserExpirationPolicy** | bool |  |
| **Owner** | string |  |
| **OwnerEmail** | string |  |
| **OwnerLoginName** | string |  |
| **OwnerName** | string |  |
| **PWAEnabled** | [PWAEnabledStatus](#pwaenabledstatus-enum) |  |
| **RelatedGroupId** | Guid |  |
| **RestrictedToRegion** | [RestrictedToRegion](#restrictedtoregion-enum) |  |
| **SandboxedCodeActivationCapability** | [SandboxedCodeActivationCapabilities](#sandboxedcodeactivationcapabilities-enum) |  |
| **SensitivityLabel** | Guid |  |
| **SensitivityLabel2** | string |  |
| **SetOwnerWithoutUpdatingSecondaryAdmin** | bool |  |
| **SharingAllowedDomainList** | string |  |
| **SharingBlockedDomainList** | string |  |
| **SharingCapability** | [SharingCapabilities](#sharingcapabilities-enum) |  |
| **SharingDomainRestrictionMode** | [SharingDomainRestrictionModes](#sharingdomainrestrictionmodes-enum) |  |
| **ShowPeoplePickerSuggestionsForGuestUsers** | bool |  |
| **SiteDefinedSharingCapability** | [SharingCapabilities](#sharingcapabilities-enum) |  |
| **SocialBarOnSitePagesDisabled** | bool |  |
| **Status** | string |  |
| **StorageMaximumLevel** | long |  |
| **StorageQuotaType** | string |  |
| **StorageUsage** | long |  |
| **StorageWarningLevel** | long |  |
| **Template** | string |  |
| **TimeZoneId** | int |  |
| **Title** | string |  |
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
| **AuthContextStrength** | string |  |
| **AverageResourceUsage** | string |  |
| **BlockDownloadLinksFileType** | string |  |
| **CommentsOnSitePagesDisabled** | string |  |
| **CompatibilityLevel** | string |  |
| **ConditionalAccessPolicy** | string |  |
| **CurrentResourceUsage** | string |  |
| **DefaultLinkPermission** | string |  |
| **DefaultLinkToExistingAccess** | string |  |
| **DefaultLinkToExistingAccessReset** | string |  |
| **DefaultSharingLinkType** | string |  |
| **DenyAddAndCustomizePages** | string |  |
| **Description** | string |  |
| **DisableAppViews** | string |  |
| **DisableCompanyWideSharingLinks** | string |  |
| **DisableFlows** | string |  |
| **ExternalUserExpirationInDays** | string |  |
| **GroupId** | string |  |
| **GroupOwnerLoginName** | string |  |
| **HasHolds** | string |  |
| **HubSiteId** | string |  |
| **IBSegments** | string |  |
| **IBSegmentsToAdd** | string |  |
| **IBSegmentsToRemove** | string |  |
| **IsGroupOwnerSiteAdmin** | string |  |
| **IsHubSite** | string |  |
| **LastContentModifiedDate** | string |  |
| **Lcid** | string |  |
| **LimitedAccessFileType** | string |  |
| **LockIssue** | string |  |
| **LockState** | string |  |
| **OverrideBlockUserInfoVisibility** | string |  |
| **OverrideTenantAnonymousLinkExpirationPolicy** | string |  |
| **OverrideTenantExternalUserExpirationPolicy** | string |  |
| **Owner** | string |  |
| **OwnerEmail** | string |  |
| **OwnerLoginName** | string |  |
| **OwnerName** | string |  |
| **PWAEnabled** | string |  |
| **RelatedGroupId** | string |  |
| **RestrictedToRegion** | string |  |
| **SandboxedCodeActivationCapability** | string |  |
| **SensitivityLabel** | string |  |
| **SensitivityLabel2** | string |  |
| **SetOwnerWithoutUpdatingSecondaryAdmin** | string |  |
| **SharingAllowedDomainList** | string |  |
| **SharingBlockedDomainList** | string |  |
| **SharingCapability** | string |  |
| **SharingDomainRestrictionMode** | string |  |
| **ShowPeoplePickerSuggestionsForGuestUsers** | string |  |
| **SiteDefinedSharingCapability** | string |  |
| **SocialBarOnSitePagesDisabled** | string |  |
| **Status** | string |  |
| **StorageMaximumLevel** | string |  |
| **StorageQuotaType** | string |  |
| **StorageUsage** | string |  |
| **StorageWarningLevel** | string |  |
| **Template** | string |  |
| **TimeZoneId** | string |  |
| **Title** | string |  |
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
# Tenant Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AddressbarLinkPermission** | Role |  |
| **AIBuilderDefaultPowerAppsEnvironment** | string |  |
| **AIBuilderEnabled** | bool |  |
| **AIBuilderSiteInfoList** | IEnumerable\<[SiteInfoForSitePicker](#siteinfoforsitepicker-class)\> |  |
| **AIBuilderSiteList** | IEnumerable\<Guid\> |  |
| **AIBuilderSiteListFileName** | string |  |
| **AllowCommentsTextOnEmailEnabled** | bool |  |
| **AllowDownloadingNonWebViewableFiles** | bool |  |
| **AllowedDomainListForSyncClient** | IList\<Guid\> |  |
| **AllowEditing** | bool |  |
| **AllowGuestUserShareToUsersNotInSiteCollection** | bool |  |
| **AllowLimitedAccessOnUnmanagedDevices** | bool |  |
| **AllowOverrideForBlockUserInfoVisibility** | bool |  |
| **AllowSelectSGsInODBListInTenant** | IList\<string\> |  |
| **AnyoneLinkTrackUsers** | bool |  |
| **ApplyAppEnforcedRestrictionsToAdHocRecipients** | bool |  |
| **BccExternalSharingInvitations** | bool |  |
| **BccExternalSharingInvitationsList** | string |  |
| **BlockAccessOnUnmanagedDevices** | bool |  |
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
| **CommentsOnFilesDisabled** | bool |  |
| **CommentsOnListItemsDisabled** | bool |  |
| **CommentsOnSitePagesDisabled** | bool |  |
| **CompatibilityRange** | string |  |
| **ConditionalAccessPolicy** | [SPOConditionalAccessPolicyType](#spoconditionalaccesspolicytype-enum) |  |
| **ConditionalAccessPolicyErrorHelpLink** | string |  |
| **ContentTypeSyncSiteTemplatesList** | IEnumerable\<string\> |  |
| **CustomizedExternalSharingServiceUrl** | string |  |
| **DefaultContentCenterSite** | [SiteInfoForSitePicker](#siteinfoforsitepicker-class) |  |
| **DefaultLinkPermission** | [SharingPermissionType](#sharingpermissiontype-enum) |  |
| **DefaultSharingLinkType** | [SharingLinkType](#sharinglinktype-enum) |  |
| **DisableAddToOneDrive** | bool |  |
| **DisableCustomAppAuthentication** | bool |  |
| **DisabledModernListTemplateIds** | Guid[] |  |
| **DisabledWebPartIds** | Guid[] |  |
| **DisablePersonalListCreation** | bool |  |
| **DisableReportProblemDialog** | bool |  |
| **DisableSpacesActivation** | bool |  |
| **DisallowInfectedFileDownload** | bool |  |
| **DisplayNamesOfFileViewers** | bool |  |
| **DisplayNamesOfFileViewersInSpo** | bool |  |
| **DisplayStartASiteOption** | bool |  |
| **EmailAttestationEnabled** | bool |  |
| **EmailAttestationReAuthDays** | int |  |
| **EmailAttestationRequired** | bool |  |
| **EnableAIPIntegration** | bool |  |
| **EnableAutoNewsDigest** | bool |  |
| **EnableAzureADB2BIntegration** | bool |  |
| **EnableGuestSignInAcceleration** | bool |  |
| **EnableMinimumVersionRequirement** | bool |  |
| **EnableMipSiteLabel** | bool |  |
| **EnablePromotedFileHandlers** | bool |  |
| **ExcludedFileExtensionsForSyncClient** | IList\<string\> |  |
| **ExternalServicesEnabled** | bool |  |
| **ExternalUserExpirationRequired** | bool |  |
| **ExternalUserExpireInDays** | int |  |
| **FileAnonymousLinkType** | AnonymousLinkType |  |
| **FilePickerExternalImageSearchEnabled** | bool |  |
| **FolderAnonymousLinkType** | AnonymousLinkType |  |
| **GuestSharingGroupAllowListInTenant** | string |  |
| **GuestSharingGroupAllowListInTenantByPrincipalIdentity** | IList\<string\> |  |
| **HasAdminCompletedCUConfiguration** | bool |  |
| **HasIntelligentContentServicesCapability** | bool |  |
| **HasTopicExperiencesCapability** | bool |  |
| **HideDefaultThemes** | bool |  |
| **HideSyncButtonOnDocLib** | bool |  |
| **HideSyncButtonOnODB** | bool |  |
| **ImageTaggingOption** | [ImageTaggingChoice](#imagetaggingchoice-enum) |  |
| **IncludeAtAGlanceInShareEmails** | bool |  |
| **IPAddressAllowList** | string |  |
| **IPAddressEnforcement** | bool |  |
| **IPAddressWACTokenLifetime** | int |  |
| **IsAppBarTemporarilyDisabled** | bool |  |
| **IsFluidEnabled** | bool |  |
| **IsHubSitesMultiGeoFlightEnabled** | bool |  |
| **IsMnAFlightEnabled** | bool |  |
| **IsMultiGeo** | bool |  |
| **IsUnmanagedSyncClientForTenantRestricted** | bool |  |
| **IsUnmanagedSyncClientRestrictionFlightEnabled** | bool |  |
| **LabelMismatchEmailHelpLink** | string |  |
| **LegacyAuthProtocolsEnabled** | bool |  |
| **LimitedAccessFileType** | [SPOLimitedAccessFileType](#spolimitedaccessfiletype-enum) |  |
| **MachineLearningCaptureEnabled** | bool |  |
| **MarkNewFilesSensitiveByDefault** | [SensitiveByDefaultState](#sensitivebydefaultstate-enum) |  |
| **MobileFriendlyUrlEnabledInTenant** | bool |  |
| **NoAccessRedirectUrl** | string |  |
| **NotificationsInOneDriveForBusinessEnabled** | bool |  |
| **NotificationsInSharePointEnabled** | bool |  |
| **NotifyOwnersWhenInvitationsAccepted** | bool |  |
| **NotifyOwnersWhenItemsReshared** | bool |  |
| **ODBAccessRequests** | SharingState |  |
| **ODBMembersCanShare** | SharingState |  |
| **ODBSharingCapability** | [SharingCapabilities](#sharingcapabilities-enum) |  |
| **OfficeClientADALDisabled** | bool |  |
| **OneDriveForGuestsEnabled** | bool |  |
| **OneDriveStorageQuota** | long |  |
| **OptOutOfGrooveBlock** | bool |  |
| **OptOutOfGrooveSoftBlock** | bool |  |
| **OrgNewsSiteUrl** | string |  |
| **OrphanedPersonalSitesRetentionPeriod** | int |  |
| **OwnerAnonymousNotification** | bool |  |
| **PermissiveBrowserFileHandlingOverride** | bool |  |
| **PreventExternalUsersFromResharing** | bool |  |
| **ProvisionSharedWithEveryoneFolder** | bool |  |
| **PublicCdnAllowedFileTypes** | string |  |
| **PublicCdnEnabled** | bool |  |
| **PublicCdnOrigins** | IList\<string\> |  |
| **RequireAcceptingAccountMatchInvitedAccount** | bool |  |
| **RequireAnonymousLinksExpireInDays** | int |  |
| **ResourceQuota** | double |  |
| **ResourceQuotaAllocated** | double |  |
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
| **ShowPeoplePickerSuggestionsForGuestUsers** | bool |  |
| **SignInAccelerationDomain** | string |  |
| **SocialBarOnSitePagesDisabled** | bool |  |
| **SpecialCharactersStateInFileFolderNames** | [SpecialCharactersState](#specialcharactersstate-enum) |  |
| **StartASiteFormUrl** | string |  |
| **StopNew2010Workflows** | bool |  |
| **StorageQuota** | long |  |
| **StorageQuotaAllocated** | long |  |
| **SyncAadB2BManagementPolicy** | bool |  |
| **SyncPrivacyProfileProperties** | bool |  |
| **UseFindPeopleInPeoplePicker** | bool |  |
| **UsePersistentCookiesForExplorerView** | bool |  |
| **UserVoiceForFeedbackEnabled** | bool |  |
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
| **AddOrUpdateTenantIdentityMap(string[] mapItems)** | IList\<string\> |  |
| **AddOrUpdateTenantSingleGroupIdentityMappingItem(Guid sourceTenantCompanyId, Guid sourceGroupObjectId, Guid targetGroupObjectId, string targetGroupName, TenantIdentityMappingGroupType groupType)** | void |  |
| **AddOrUpdateTenantSingleUserIdentityMappingItem(Guid sourceTenantCompanyId, string sourceUserKey, string targetUserPuid, string targetUserUpn, string targetUserEmail, TenantIdentityMappingUserType userType)** | void |  |
| **AddPublicCdnOrigin(string origin)** | void |  |
| **AddSdnProvider(string identifier, string license)** | void |  |
| **AddSiteDesignTask(ClientRuntimeContext context, string webUrl, Guid siteDesignId)** | [TenantSiteDesignTask](#tenantsitedesigntask-class) |  |
| **AddTenantCdnOrigin(SPOTenantCdnType cdnType, string originUrl)** | void |  |
| **AddTenantTheme(string name, string themeJson)** | ClientResult\<bool\> |  |
| **AddToOrgAssetsLibAndCdn(SPOTenantCdnType cdnType, string libUrl, string thumbnailUrl)** | void |  |
| **AddToOrgAssetsLibAndCdnV2(SPOTenantCdnType cdnType, string libUrl, string thumbnailUrl, OrgAssetType orgAssetType, bool defaultOriginAdded)** | void |  |
| **AddToOrgAssetsLibAndCdnWithType(SPOTenantCdnType cdnType, string libUrl, string thumbnailUrl, OrgAssetType orgAssetType)** | void |  |
| **ApplySiteDesign(string webUrl, Guid siteDesignId)** | ClientObjectList\<[TenantSiteScriptActionResult](#tenantsitescriptactionresult-class)\> |  |
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
| **DeleteTenantTheme(string name)** | void |  |
| **DisableSpacesActivationOnSite(string siteUrl, bool disable)** | void |  |
| **DisconnectSiteFromHubSite(string siteUrl)** | void |  |
| **EnableCommunicationSite(string siteUrl, Guid designPackageId)** | ClientResult\<string\> |  |
| **EncodeClaim(string identifier)** | ClientResult\<string\> |  |
| **EncodeClaims(IList\<string\> identifiers)** | IList\<string\> |  |
| **GetAllDeletedPersonalSitesPropertiesAllVersions(int startIndex)** | [SPODeletedSitePropertiesEnumerable](#spodeletedsitepropertiesenumerable-class) |  |
| **GetAllPortalLaunchWaves()** | ClientResult\<string\> |  |
| **GetAllTenantThemes()** | ClientObjectList\<[ThemeProperties](#themeproperties-class)\> |  |
| **GetAppErrors(Guid productId, DateTime timeStart, DateTime timeEnd)** | ClientObjectList\<[AppErrorEntry](#apperrorentry-class)\> |  |
| **GetAppInfoByName(string name)** | ClientObjectList\<[AppInfo](#appinfo-class)\> |  |
| **GetAppInfoByProductId(Guid productId)** | ClientObjectList\<[AppInfo](#appinfo-class)\> |  |
| **GetDeletedPersonalSitePropertiesAllVersions(string url)** | [SPODeletedSitePropertiesEnumerable](#spodeletedsitepropertiesenumerable-class) |  |
| **GetDeletedSiteProperties(int startIndex)** | [SPODeletedSitePropertiesEnumerable](#spodeletedsitepropertiesenumerable-class) |  |
| **GetDeletedSitePropertiesByUrl(string siteUrl)** | [DeletedSiteProperties](#deletedsiteproperties-class) |  |
| **GetDeletedSitePropertiesFromSharePoint(string startIndex)** | [SPODeletedSitePropertiesEnumerable](#spodeletedsitepropertiesenumerable-class) |  |
| **GetHiddenBuiltInDesignPackages(ClientRuntimeContext context)** | ClientResult\<DesignPackageType\> |  |
| **GetHubSitePropertiesById(Guid hubSiteId)** | [HubSiteProperties](#hubsiteproperties-class) |  |
| **GetHubSitePropertiesByUrl(string siteUrl)** | [HubSiteProperties](#hubsiteproperties-class) |  |
| **GetHubSitesProperties()** | ClientObjectList\<[HubSiteProperties](#hubsiteproperties-class)\> |  |
| **GetIdleSessionSignOutForUnmanagedDevices()** | ClientResult\<string\> |  |
| **GetKnowledgeHubSite()** | ClientResult\<string\> |  |
| **GetListDesign(ClientRuntimeContext context, Guid id)** | [TenantListDesign](#tenantlistdesign-class) |  |
| **GetListDesigns()** | ClientObjectList\<[TenantListDesign](#tenantlistdesign-class)\> |  |
| **GetMySiteHostUrl()** | ClientResult\<string\> |  |
| **GetOrgAssets()** | ClientResult\<OrgAssets\> |  |
| **GetOrgNewsSites()** | IEnumerable\<string\> |  |
| **GetOrgRelationTargetGroupManagedPath(string targetMySiteHostUrl)** | ClientResult\<string\> |  |
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
| **GetSiteScripts()** | ClientObjectList\<[TenantSiteScript](#tenantsitescript-class)\> |  |
| **GetSPHSiteUrl()** | ClientResult\<string\> |  |
| **GetSPOAllWebTemplates(string cultureName, int compatibilityLevel)** | [SPOTenantWebTemplateCollection](#spotenantwebtemplatecollection-class) |  |
| **GetSPOStructuralNavigationCacheSiteState(string siteUrl)** | ClientResult\<bool\> |  |
| **GetSPOStructuralNavigationCacheWebState(string webUrl)** | ClientResult\<bool\> |  |
| **GetSPOTenantAllWebTemplates()** | [SPOTenantWebTemplateCollection](#spotenantwebtemplatecollection-class) |  |
| **GetSPOTenantOrgRelationAll()** | ClientResult\<string\> |  |
| **GetSPOTenantOrgRelationByPartner(string partnerMySiteHostUrl)** | ClientResult\<string\> |  |
| **GetSPOTenantOrgRelationByScenario(OrgRelationScenario scenario, OrgRelationRole partnerRole)** | ClientResult\<string\> |  |
| **GetSPOTenantSiteUserInvitations(string siteUrl, string emailAddress)** | ClientObjectList\<[SPOTenantSiteUserInvitation](#spotenantsiteuserinvitation-class)\> |  |
| **GetSPOTenantWebTemplates(uint localeId, int compatibilityLevel)** | [SPOTenantWebTemplateCollection](#spotenantwebtemplatecollection-class) |  |
| **GetTenantCdnEnabled(SPOTenantCdnType cdnType)** | ClientResult\<bool\> |  |
| **GetTenantCdnOrigins(SPOTenantCdnType cdnType)** | IList\<string\> |  |
| **GetTenantCdnPolicies(SPOTenantCdnType cdnType)** | IList\<string\> |  |
| **GetTenantGroupIdentityMappingItem(TenantIdentityMappingGroupField field, string value)** | ClientObjectList\<[SPOTenantGroupIdentityMapping](#spotenantgroupidentitymapping-class)\> |  |
| **GetTenantInstances()** | ClientObjectList\<[SPOTenantInstance](#spotenantinstance-class)\> |  |
| **GetTenantTheme(string name)** | [ThemeProperties](#themeproperties-class) |  |
| **GetTenantUserIdentityMappingItem(TenantIdentityMappingUserField field, string value)** | ClientObjectList\<[SPOTenantUserIdentityMapping](#spotenantuseridentitymapping-class)\> |  |
| **GetUserMigrationProperties(string userPrincipalName)** | [UserMigrationProperties](#usermigrationproperties-class) |  |
| **GetUserMigrationPropertiesByFilter(UserMigrationPropertiesEnumerableFilter userMigrationPropertiesEnumerableFilter)** | [UserMigrationPropertiesEnumerable](#usermigrationpropertiesenumerable-class) |  |
| **GrantHubSiteRights(string hubSiteUrl, string[] principals, SPOHubSiteUserRights grantedRights)** | [HubSiteProperties](#hubsiteproperties-class) |  |
| **GrantHubSiteRightsById(Guid hubSiteId, string[] principals, SPOHubSiteUserRights grantedRights)** | [HubSiteProperties](#hubsiteproperties-class) |  |
| **GrantSiteDesignRights(Guid id, string[] principalNames, TenantSiteDesignPrincipalRights grantedRights)** | void |  |
| **IsTenantReadyForIdentityChange()** | ClientResult\<bool\> |  |
| **IsValidCommSite(string spSiteUrl)** | ClientResult\<bool\> |  |
| **NewSPOTenantOrgRelation(OrgRelationScenario scenario, OrgRelationRole partnerRole, string partnerMySiteHostUrl)** | void |  |
| **RegisterHubSite(string siteUrl)** | [HubSiteProperties](#hubsiteproperties-class) |  |
| **RegisterHubSiteWithCreationInformation(string siteUrl, HubSiteCreationInformation creationInformation)** | [HubSiteProperties](#hubsiteproperties-class) |  |
| **RemoveDeletedSite(string siteUrl)** | [SpoOperation](#spooperation-class) |  |
| **RemoveDeletedSitePreferId(string siteUrl, Guid siteId)** | [SpoOperation](#spooperation-class) |  |
| **RemoveFromOrgAssets(string libUrl, Guid listId)** | void |  |
| **RemoveFromOrgAssetsAndCdn(bool remove, SPOTenantCdnType cdnType, string libUrl)** | void |  |
| **RemoveKnowledgeHubSite()** | ClientResult\<string\> |  |
| **RemoveListDesign(Guid id)** | void |  |
| **RemoveOrgNewsSite(string orgNewsSiteUrl)** | ClientResult\<string\> |  |
| **RemovePortalLaunchWaves(string siteUrl, bool deletionConfirmed)** | [SPOPortalLaunchValidationResult](#spoportallaunchvalidationresult-class) |  |
| **RemovePublicCdnOrigin(string originId)** | void |  |
| **RemoveSdnProvider()** | void |  |
| **RemoveSite(string siteUrl)** | [SpoOperation](#spooperation-class) |  |
| **RemoveSiteDesignTask(ClientRuntimeContext context, Guid taskId)** | void |  |
| **RemoveSiteSharingReportJobForTenantAdmin(string siteUrl)** | ClientResult\<string\> |  |
| **RemoveSPHSite()** | ClientResult\<string\> |  |
| **RemoveSPOTenantOrgRelation(OrgRelationScenario scenario, OrgRelationRole partnerRole, string partnerMySiteHostUrl)** | void |  |
| **RemoveSPOTenantSiteUserInvitations(string siteUrl, string emailAddress, bool countOnly)** | ClientResult\<int\> |  |
| **RemoveTenantCdnOrigin(SPOTenantCdnType cdnType, string originUrl)** | void |  |
| **RemoveTenantGroupIdentityMappingItem(TenantIdentityMappingGroupField field, string value)** | void |  |
| **RemoveTenantUserIdentityMappingItem(TenantIdentityMappingUserField field, string value)** | void |  |
| **RequestPersonalSites(string[] userIds)** | [SpoOperation](#spooperation-class) |  |
| **RestoreDeletedSite(string siteUrl)** | [SpoOperation](#spooperation-class) |  |
| **RestoreDeletedSitePreferId(string siteUrl, Guid siteId)** | [SpoOperation](#spooperation-class) |  |
| **RevokeHubSiteRights(string hubSiteUrl, string[] principals)** | [HubSiteProperties](#hubsiteproperties-class) |  |
| **RevokeHubSiteRightsById(Guid hubSiteId, string[] principals)** | [HubSiteProperties](#hubsiteproperties-class) |  |
| **RevokeSiteDesignRights(ClientRuntimeContext context, Guid id, string[] principalNames)** | void |  |
| **SavePortalLaunchWaves(string portalLaunchWaveSetupString, bool isTesting, bool changeConfirmed)** | [SPOPortalLaunchValidationResult](#spoportallaunchvalidationresult-class) |  |
| **SetBuiltInDesignPackageVisibility(ClientRuntimeContext context, DesignPackageType designPackageType, bool isVisible)** | void |  |
| **SetIdleSessionSignOutForUnmanagedDevices(bool enabled, TimeSpan warnAfter, TimeSpan signOutAfter)** | ClientResult\<bool\> |  |
| **SetKnowledgeHubSite(string knowledgeHubSiteUrl)** | ClientResult\<string\> |  |
| **SetOrgAssets(string libUrl, string thumbnailUrl)** | void |  |
| **SetOrgAssetsWithType(string libUrl, string thumbnailUrl, OrgAssetType orgAssetType)** | void |  |
| **SetOrgNewsSite(string orgNewsSiteUrl)** | ClientResult\<string\> |  |
| **SetPortalLaunchWaves(string siteUrl, string status, bool walkBack, bool isWhatIf, bool updateConfirmed)** | [SPOPortalLaunchValidationResult](#spoportallaunchvalidationresult-class) |  |
| **SetSiteAdmin(string siteUrl, string loginName, bool isSiteAdmin)** | User |  |
| **SetSPHSite(string sphSiteUrl)** | ClientResult\<string\> |  |
| **SetSPOStructuralNavigationCacheSiteState(string siteUrl, bool isEnabled)** | void |  |
| **SetSPOStructuralNavigationCacheWebState(string webUrl, bool isEnabled)** | void |  |
| **SetTenantCdnEnabled(SPOTenantCdnType cdnType, bool isEnabled)** | void |  |
| **SetTenantCdnPolicy(SPOTenantCdnType cdnType, SPOTenantCdnPolicyType policyType, string policyValue)** | void |  |
| **SetTenantIdentityMigrationState(TenantIdentityMigrationState state)** | void |  |
| **SetWebTheme(string themeName, string webUrl)** | ClientResult\<string\> |  |
| **SetWorkflows2013Enabled(bool enabled)** | void |  |
| **SwapSite(string sourceUrl, string targetUrl, string archiveUrl)** | [SpoOperation](#spooperation-class) |  |
| **SwapSiteWithSmartGestureOption(string sourceUrl, string targetUrl, string archiveUrl, bool includeSmartGestures)** | [SpoOperation](#spooperation-class) |  |
| **SwapSiteWithSmartGestureOptionForce(string sourceUrl, string targetUrl, string archiveUrl, bool includeSmartGestures, bool force)** | [SpoOperation](#spooperation-class) |  |
| **UnlockSensitivityLabelEncryptedFile(string fileUrl, string justificationText)** | void |  |
| **UnregisterHubSite(string siteUrl)** | void |  |
| **UnregisterHubSiteById(Guid hubSiteId)** | void |  |
| **Update()** | void |  |
| **UpdatePortalLaunchWaves(string siteUrl, string status, bool walkBack)** | [SPOPortalLaunchValidationResult](#spoportallaunchvalidationresult-class) |  |
| **UpdateSiteDesign(TenantSiteDesign updateInfo)** | [TenantSiteDesign](#tenantsitedesign-class) |  |
| **UpdateSiteScript(TenantSiteScript updateInfo)** | [TenantSiteScript](#tenantsitescript-class) |  |
| **UpdateSiteScriptPackage(TenantSiteScript updateInfo)** | [TenantSiteScript](#tenantsitescript-class) |  |
| **UpdateTenantTheme(string name, string themeJson)** | ClientResult\<bool\> |  |
| **UpdateUserTypeFromAzureAD(string siteUrl, string loginName)** | User |  |
| **UpdateUserTypeFromAzureADForAllSites(string loginName)** | [SPOSitePropertiesEnumerable](#spositepropertiesenumerable-class) |  |
| **UpdateUserTypesFromAzureADForSite(string siteUrl)** | ClientObjectList\<User\> |  |
| **VerifySPOTenantOrgRelation(OrgRelationScenario scenario, OrgRelationRole partnerRole, string partnerMySiteHostUrl)** | ClientResult\<OrgRelationVerificationStatus\> |  |
# TenantBrowseUserInfoPolicyValue Enum

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Values

| Name | Summary |
|---|---|
| **ApplyToNoUsers** |  |
| **ApplyToGuestAndExternalUsers** |  |
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
| **LogoUrl** | string |  |
| **SiteScriptIds** | Guid[] |  |
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
| **LogoUrl** | string |  |
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
| **LogoUrl** | string |  |
| **SiteScriptIds** | string |  |
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
# TenantPropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantAdministration


## Fields

| Name | Type | Summary |
|---|---|---|
| **AddressbarLinkPermission** | string |  |
| **AIBuilderDefaultPowerAppsEnvironment** | string |  |
| **AIBuilderEnabled** | string |  |
| **AIBuilderSiteInfoList** | string |  |
| **AIBuilderSiteList** | string |  |
| **AIBuilderSiteListFileName** | string |  |
| **AllowCommentsTextOnEmailEnabled** | string |  |
| **AllowDownloadingNonWebViewableFiles** | string |  |
| **AllowedDomainListForSyncClient** | string |  |
| **AllowEditing** | string |  |
| **AllowGuestUserShareToUsersNotInSiteCollection** | string |  |
| **AllowLimitedAccessOnUnmanagedDevices** | string |  |
| **AllowOverrideForBlockUserInfoVisibility** | string |  |
| **AllowSelectSGsInODBListInTenant** | string |  |
| **AnyoneLinkTrackUsers** | string |  |
| **ApplyAppEnforcedRestrictionsToAdHocRecipients** | string |  |
| **BccExternalSharingInvitations** | string |  |
| **BccExternalSharingInvitationsList** | string |  |
| **BlockAccessOnUnmanagedDevices** | string |  |
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
| **CommentsOnFilesDisabled** | string |  |
| **CommentsOnListItemsDisabled** | string |  |
| **CommentsOnSitePagesDisabled** | string |  |
| **CompatibilityRange** | string |  |
| **ConditionalAccessPolicy** | string |  |
| **ConditionalAccessPolicyErrorHelpLink** | string |  |
| **ContentTypeSyncSiteTemplatesList** | string |  |
| **CustomizedExternalSharingServiceUrl** | string |  |
| **DefaultContentCenterSite** | string |  |
| **DefaultLinkPermission** | string |  |
| **DefaultSharingLinkType** | string |  |
| **DisableAddToOneDrive** | string |  |
| **DisableCustomAppAuthentication** | string |  |
| **DisabledModernListTemplateIds** | string |  |
| **DisabledWebPartIds** | string |  |
| **DisablePersonalListCreation** | string |  |
| **DisableReportProblemDialog** | string |  |
| **DisableSpacesActivation** | string |  |
| **DisallowInfectedFileDownload** | string |  |
| **DisplayNamesOfFileViewers** | string |  |
| **DisplayNamesOfFileViewersInSpo** | string |  |
| **DisplayStartASiteOption** | string |  |
| **EmailAttestationEnabled** | string |  |
| **EmailAttestationReAuthDays** | string |  |
| **EmailAttestationRequired** | string |  |
| **EnableAIPIntegration** | string |  |
| **EnableAutoNewsDigest** | string |  |
| **EnableAzureADB2BIntegration** | string |  |
| **EnableGuestSignInAcceleration** | string |  |
| **EnableMinimumVersionRequirement** | string |  |
| **EnableMipSiteLabel** | string |  |
| **EnablePromotedFileHandlers** | string |  |
| **ExcludedFileExtensionsForSyncClient** | string |  |
| **ExternalServicesEnabled** | string |  |
| **ExternalUserExpirationRequired** | string |  |
| **ExternalUserExpireInDays** | string |  |
| **FileAnonymousLinkType** | string |  |
| **FilePickerExternalImageSearchEnabled** | string |  |
| **FolderAnonymousLinkType** | string |  |
| **GuestSharingGroupAllowListInTenant** | string |  |
| **GuestSharingGroupAllowListInTenantByPrincipalIdentity** | string |  |
| **HasAdminCompletedCUConfiguration** | string |  |
| **HasIntelligentContentServicesCapability** | string |  |
| **HasTopicExperiencesCapability** | string |  |
| **HideDefaultThemes** | string |  |
| **HideSyncButtonOnDocLib** | string |  |
| **HideSyncButtonOnODB** | string |  |
| **ImageTaggingOption** | string |  |
| **IncludeAtAGlanceInShareEmails** | string |  |
| **IPAddressAllowList** | string |  |
| **IPAddressEnforcement** | string |  |
| **IPAddressWACTokenLifetime** | string |  |
| **IsAppBarTemporarilyDisabled** | string |  |
| **IsFluidEnabled** | string |  |
| **IsHubSitesMultiGeoFlightEnabled** | string |  |
| **IsMnAFlightEnabled** | string |  |
| **IsMultiGeo** | string |  |
| **IsUnmanagedSyncClientForTenantRestricted** | string |  |
| **IsUnmanagedSyncClientRestrictionFlightEnabled** | string |  |
| **LabelMismatchEmailHelpLink** | string |  |
| **LegacyAuthProtocolsEnabled** | string |  |
| **LimitedAccessFileType** | string |  |
| **MachineLearningCaptureEnabled** | string |  |
| **MarkNewFilesSensitiveByDefault** | string |  |
| **MobileFriendlyUrlEnabledInTenant** | string |  |
| **NoAccessRedirectUrl** | string |  |
| **NotificationsInOneDriveForBusinessEnabled** | string |  |
| **NotificationsInSharePointEnabled** | string |  |
| **NotifyOwnersWhenInvitationsAccepted** | string |  |
| **NotifyOwnersWhenItemsReshared** | string |  |
| **ODBAccessRequests** | string |  |
| **ODBMembersCanShare** | string |  |
| **ODBSharingCapability** | string |  |
| **OfficeClientADALDisabled** | string |  |
| **OneDriveForGuestsEnabled** | string |  |
| **OneDriveStorageQuota** | string |  |
| **OptOutOfGrooveBlock** | string |  |
| **OptOutOfGrooveSoftBlock** | string |  |
| **OrgNewsSiteUrl** | string |  |
| **OrphanedPersonalSitesRetentionPeriod** | string |  |
| **OwnerAnonymousNotification** | string |  |
| **PermissiveBrowserFileHandlingOverride** | string |  |
| **PreventExternalUsersFromResharing** | string |  |
| **ProvisionSharedWithEveryoneFolder** | string |  |
| **PublicCdnAllowedFileTypes** | string |  |
| **PublicCdnEnabled** | string |  |
| **PublicCdnOrigins** | string |  |
| **RequireAcceptingAccountMatchInvitedAccount** | string |  |
| **RequireAnonymousLinksExpireInDays** | string |  |
| **ResourceQuota** | string |  |
| **ResourceQuotaAllocated** | string |  |
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
| **ShowPeoplePickerSuggestionsForGuestUsers** | string |  |
| **SignInAccelerationDomain** | string |  |
| **SocialBarOnSitePagesDisabled** | string |  |
| **SpecialCharactersStateInFileFolderNames** | string |  |
| **StartASiteFormUrl** | string |  |
| **StopNew2010Workflows** | string |  |
| **StorageQuota** | string |  |
| **StorageQuotaAllocated** | string |  |
| **SyncAadB2BManagementPolicy** | string |  |
| **SyncPrivacyProfileProperties** | string |  |
| **UseFindPeopleInPeoplePicker** | string |  |
| **UsePersistentCookiesForExplorerView** | string |  |
| **UserVoiceForFeedbackEnabled** | string |  |
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
| **Update()** | void |  |
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
| **Id** | Guid |  |
| **IsDomainIsolated** | bool |  |
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
| **Id** | string |  |
| **IsDomainIsolated** | string |  |
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
# Office365Tenant Class

Namespace: Microsoft.Online.SharePoint.TenantManagement

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AddressbarLinkPermission** | Role |  |
| **AIBuilderDefaultPowerAppsEnvironment** | string |  |
| **AIBuilderEnabled** | bool |  |
| **AIBuilderSiteInfoList** | IEnumerable\<[SiteInfoForSitePicker](#siteinfoforsitepicker-class)\> |  |
| **AIBuilderSiteList** | IEnumerable\<Guid\> |  |
| **AIBuilderSiteListFileName** | string |  |
| **AllowCommentsTextOnEmailEnabled** | bool |  |
| **AllowDownloadingNonWebViewableFiles** | bool |  |
| **AllowedDomainListForSyncClient** | IList\<Guid\> |  |
| **AllowEditing** | bool |  |
| **AllowGuestUserShareToUsersNotInSiteCollection** | bool |  |
| **AllowLimitedAccessOnUnmanagedDevices** | bool |  |
| **AllowOverrideForBlockUserInfoVisibility** | bool |  |
| **AllowSelectSGsInODBList** | IList\<string\> |  |
| **AnyoneLinkTrackUsers** | bool |  |
| **ApplyAppEnforcedRestrictionsToAdHocRecipients** | bool |  |
| **BccExternalSharingInvitations** | bool |  |
| **BccExternalSharingInvitationsList** | string |  |
| **BlockAccessOnUnmanagedDevices** | bool |  |
| **BlockDownloadLinksFileType** | [BlockDownloadLinksFileTypes](#blockdownloadlinksfiletypes-enum) |  |
| **BlockDownloadOfAllFilesForGuests** | bool |  |
| **BlockDownloadOfAllFilesOnUnmanagedDevices** | bool |  |
| **BlockDownloadOfViewableFilesForGuests** | bool |  |
| **BlockDownloadOfViewableFilesOnUnmanagedDevices** | bool |  |
| **BlockMacSync** | bool |  |
| **BlockUserInfoVisibility** | string |  |
| **BlockUserInfoVisibilityInOneDrive** | [TenantBrowseUserInfoPolicyValue](#tenantbrowseuserinfopolicyvalue-enum) |  |
| **BlockUserInfoVisibilityInSharePoint** | [TenantBrowseUserInfoPolicyValue](#tenantbrowseuserinfopolicyvalue-enum) |  |
| **CommentsOnFilesDisabled** | bool |  |
| **CommentsOnListItemsDisabled** | bool |  |
| **CommentsOnSitePagesDisabled** | bool |  |
| **ConditionalAccessPolicy** | [SPOConditionalAccessPolicyType](#spoconditionalaccesspolicytype-enum) |  |
| **ConditionalAccessPolicyErrorHelpLink** | string |  |
| **ContentTypeSyncSiteTemplatesList** | IEnumerable\<string\> |  |
| **CustomizedExternalSharingServiceUrl** | string |  |
| **DefaultContentCenterSite** | [SiteInfoForSitePicker](#siteinfoforsitepicker-class) |  |
| **DefaultLinkPermission** | [SharingPermissionType](#sharingpermissiontype-enum) |  |
| **DefaultSharingLinkType** | [SharingLinkType](#sharinglinktype-enum) |  |
| **DisableAddToOneDrive** | bool |  |
| **DisableCustomAppAuthentication** | bool |  |
| **DisabledModernListTemplateIds** | Guid[] |  |
| **DisablePersonalListCreation** | bool |  |
| **DisableSpacesActivation** | bool |  |
| **DisplayStartASiteOption** | bool |  |
| **EmailAttestationEnabled** | bool |  |
| **EmailAttestationReAuthDays** | int |  |
| **EmailAttestationRequired** | bool |  |
| **EnableAutoNewsDigest** | bool |  |
| **EnableAzureADB2BIntegration** | bool |  |
| **EnableGuestSignInAcceleration** | bool |  |
| **EnablePromotedFileHandlers** | bool |  |
| **ExcludedFileExtensionsForSyncClient** | IList\<string\> |  |
| **ExternalServicesEnabled** | bool |  |
| **ExternalUserExpirationRequired** | bool |  |
| **ExternalUserExpireInDays** | int |  |
| **FileAnonymousLinkType** | AnonymousLinkType |  |
| **FilePickerExternalImageSearchEnabled** | bool |  |
| **FolderAnonymousLinkType** | AnonymousLinkType |  |
| **GetOrgAssets** | OrgAssets |  |
| **GuestSharingGroupAllowList** | string |  |
| **HasAdminCompletedCUConfiguration** | bool |  |
| **HideSyncButtonOnDocLib** | bool |  |
| **HideSyncButtonOnODB** | bool |  |
| **ImageTaggingOption** | [ImageTaggingChoice](#imagetaggingchoice-enum) |  |
| **IncludeAtAGlanceInShareEmails** | bool |  |
| **IPAddressAllowList** | string |  |
| **IPAddressEnforcement** | bool |  |
| **IPAddressWACTokenLifetime** | int |  |
| **IsUnmanagedSyncClientForTenantRestricted** | bool |  |
| **IsUnmanagedSyncClientRestrictionFlightEnabled** | bool |  |
| **LegacyAuthProtocolsEnabled** | bool |  |
| **LimitedAccessFileType** | [SPOLimitedAccessFileType](#spolimitedaccessfiletype-enum) |  |
| **MachineLearningCaptureEnabled** | bool |  |
| **MobileFriendlyUrlEnabled** | bool |  |
| **MySitesPublicEnabled** | bool |  |
| **NotificationsInOneDriveForBusinessEnabled** | bool |  |
| **NotificationsInSharePointEnabled** | bool |  |
| **NotifyOwnersWhenInvitationsAccepted** | bool |  |
| **NotifyOwnersWhenItemsReshared** | bool |  |
| **ODBAccessRequests** | SharingState |  |
| **ODBMembersCanShare** | SharingState |  |
| **ODBSharingCapability** | [SharingCapabilities](#sharingcapabilities-enum) |  |
| **OfficeClientADALDisabled** | bool |  |
| **OneDriveForGuestsEnabled** | bool |  |
| **OwnerAnonymousNotification** | bool |  |
| **PreventExternalUsersFromResharing** | bool |  |
| **ProvisionSharedWithEveryoneFolder** | bool |  |
| **PublicCdnAllowedFileTypes** | string |  |
| **PublicCdnEnabled** | bool |  |
| **PublicCdnOrigins** | IList\<string\> |  |
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
| **ShowPeoplePickerSuggestionsForGuestUsers** | bool |  |
| **SignInAccelerationDomain** | string |  |
| **SocialBarOnSitePagesDisabled** | bool |  |
| **StartASiteFormUrl** | string |  |
| **StopNew2010Workflows** | bool |  |
| **SyncAadB2BManagementPolicy** | bool |  |
| **SyncPrivacyProfileProperties** | bool |  |
| **UseFindPeopleInPeoplePicker** | bool |  |
| **UsePersistentCookiesForExplorerView** | bool |  |
| **UserVoiceForFeedbackEnabled** | bool |  |
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
| **IsSharingDisabledForNonOwnersOfSite(string siteUrl)** | ClientResult\<bool\> |  |
| **QueueImportProfileProperties(ImportProfilePropertiesUserIdType idType, string sourceDataIdProperty, IDictionary\<string, string\> propertyMap, string sourceUri)** | ClientResult\<Guid\> |  |
| **RemoveExternalUsers(string[] uniqueIds)** | [RemoveExternalUsersResults](#removeexternalusersresults-class) |  |
| **RemoveFromOrgAssets(ResourcePath libUrl, Guid listId)** | void |  |
| **RemoveFromOrgAssetsAndCdn(bool remove, SPOTenantCdnType cdnType, ResourcePath libUrl)** | void |  |
| **RemovePublicCdnOrigin(string originId)** | void |  |
| **RemoveSdnProvider()** | void |  |
| **RemoveTenantCdnOrigin(SPOTenantCdnType cdnType, string originUrl)** | void |  |
| **RevokeAllUserSessions(string userName)** | [SPOUserSessionRevocationResult](#spousersessionrevocationresult-class) |  |
| **RevokeAllUserSessionsByPuid(IList\<string\> puidList)** | ClientObjectList\<[SPOUserSessionRevocationResult](#spousersessionrevocationresult-class)\> |  |
| **SetHideDefaultThemes(bool hideDefaultThemes)** | ClientResult\<bool\> |  |
| **SetIdleSessionSignOutForUnmanagedDevices(bool enabled, TimeSpan warnAfter, TimeSpan signOutAfter)** | ClientResult\<bool\> |  |
| **SetOrgAssetsLib(ResourcePath libUrl, ResourcePath thumbnailUrl, OrgAssetType orgAssetType)** | void |  |
| **SetTenantCdnEnabled(SPOTenantCdnType cdnType, bool isEnabled)** | void |  |
| **SetTenantCdnPolicy(SPOTenantCdnType cdnType, SPOTenantCdnPolicyType policy, string policyValue)** | void |  |
| **UpdateTenantTheme(string name, string themeJson)** | ClientResult\<bool\> |  |
# Office365TenantPropertyNames Class

Namespace: Microsoft.Online.SharePoint.TenantManagement


## Fields

| Name | Type | Summary |
|---|---|---|
| **AddressbarLinkPermission** | string |  |
| **AIBuilderDefaultPowerAppsEnvironment** | string |  |
| **AIBuilderEnabled** | string |  |
| **AIBuilderSiteInfoList** | string |  |
| **AIBuilderSiteList** | string |  |
| **AIBuilderSiteListFileName** | string |  |
| **AllowCommentsTextOnEmailEnabled** | string |  |
| **AllowDownloadingNonWebViewableFiles** | string |  |
| **AllowedDomainListForSyncClient** | string |  |
| **AllowEditing** | string |  |
| **AllowGuestUserShareToUsersNotInSiteCollection** | string |  |
| **AllowLimitedAccessOnUnmanagedDevices** | string |  |
| **AllowOverrideForBlockUserInfoVisibility** | string |  |
| **AllowSelectSGsInODBList** | string |  |
| **AnyoneLinkTrackUsers** | string |  |
| **ApplyAppEnforcedRestrictionsToAdHocRecipients** | string |  |
| **BccExternalSharingInvitations** | string |  |
| **BccExternalSharingInvitationsList** | string |  |
| **BlockAccessOnUnmanagedDevices** | string |  |
| **BlockDownloadLinksFileType** | string |  |
| **BlockDownloadOfAllFilesForGuests** | string |  |
| **BlockDownloadOfAllFilesOnUnmanagedDevices** | string |  |
| **BlockDownloadOfViewableFilesForGuests** | string |  |
| **BlockDownloadOfViewableFilesOnUnmanagedDevices** | string |  |
| **BlockMacSync** | string |  |
| **BlockUserInfoVisibility** | string |  |
| **BlockUserInfoVisibilityInOneDrive** | string |  |
| **BlockUserInfoVisibilityInSharePoint** | string |  |
| **CommentsOnFilesDisabled** | string |  |
| **CommentsOnListItemsDisabled** | string |  |
| **CommentsOnSitePagesDisabled** | string |  |
| **ConditionalAccessPolicy** | string |  |
| **ConditionalAccessPolicyErrorHelpLink** | string |  |
| **ContentTypeSyncSiteTemplatesList** | string |  |
| **CustomizedExternalSharingServiceUrl** | string |  |
| **DefaultContentCenterSite** | string |  |
| **DefaultLinkPermission** | string |  |
| **DefaultSharingLinkType** | string |  |
| **DisableAddToOneDrive** | string |  |
| **DisableCustomAppAuthentication** | string |  |
| **DisabledModernListTemplateIds** | string |  |
| **DisablePersonalListCreation** | string |  |
| **DisableSpacesActivation** | string |  |
| **DisplayStartASiteOption** | string |  |
| **EmailAttestationEnabled** | string |  |
| **EmailAttestationReAuthDays** | string |  |
| **EmailAttestationRequired** | string |  |
| **EnableAutoNewsDigest** | string |  |
| **EnableAzureADB2BIntegration** | string |  |
| **EnableGuestSignInAcceleration** | string |  |
| **EnablePromotedFileHandlers** | string |  |
| **ExcludedFileExtensionsForSyncClient** | string |  |
| **ExternalServicesEnabled** | string |  |
| **ExternalUserExpirationRequired** | string |  |
| **ExternalUserExpireInDays** | string |  |
| **FileAnonymousLinkType** | string |  |
| **FilePickerExternalImageSearchEnabled** | string |  |
| **FolderAnonymousLinkType** | string |  |
| **GetOrgAssets** | string |  |
| **GuestSharingGroupAllowList** | string |  |
| **HasAdminCompletedCUConfiguration** | string |  |
| **HideSyncButtonOnDocLib** | string |  |
| **HideSyncButtonOnODB** | string |  |
| **ImageTaggingOption** | string |  |
| **IncludeAtAGlanceInShareEmails** | string |  |
| **IPAddressAllowList** | string |  |
| **IPAddressEnforcement** | string |  |
| **IPAddressWACTokenLifetime** | string |  |
| **IsUnmanagedSyncClientForTenantRestricted** | string |  |
| **IsUnmanagedSyncClientRestrictionFlightEnabled** | string |  |
| **LegacyAuthProtocolsEnabled** | string |  |
| **LimitedAccessFileType** | string |  |
| **MachineLearningCaptureEnabled** | string |  |
| **MobileFriendlyUrlEnabled** | string |  |
| **MySitesPublicEnabled** | string |  |
| **NotificationsInOneDriveForBusinessEnabled** | string |  |
| **NotificationsInSharePointEnabled** | string |  |
| **NotifyOwnersWhenInvitationsAccepted** | string |  |
| **NotifyOwnersWhenItemsReshared** | string |  |
| **ODBAccessRequests** | string |  |
| **ODBMembersCanShare** | string |  |
| **ODBSharingCapability** | string |  |
| **OfficeClientADALDisabled** | string |  |
| **OneDriveForGuestsEnabled** | string |  |
| **OwnerAnonymousNotification** | string |  |
| **PreventExternalUsersFromResharing** | string |  |
| **ProvisionSharedWithEveryoneFolder** | string |  |
| **PublicCdnAllowedFileTypes** | string |  |
| **PublicCdnEnabled** | string |  |
| **PublicCdnOrigins** | string |  |
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
| **ShowPeoplePickerSuggestionsForGuestUsers** | string |  |
| **SignInAccelerationDomain** | string |  |
| **SocialBarOnSitePagesDisabled** | string |  |
| **StartASiteFormUrl** | string |  |
| **StopNew2010Workflows** | string |  |
| **SyncAadB2BManagementPolicy** | string |  |
| **SyncPrivacyProfileProperties** | string |  |
| **UseFindPeopleInPeoplePicker** | string |  |
| **UsePersistentCookiesForExplorerView** | string |  |
| **UserVoiceForFeedbackEnabled** | string |  |
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
