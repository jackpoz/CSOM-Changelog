# Microsoft.Online.SharePoint.Client.Tenant.dll v.16.1.0.0 API documentation

Created by 
[mddox](https://github.com/loxsmoke/mddox) on 07/04/2023

# All types

|   |   |   |
|---|---|---|
| [ScriptTypeFactory Class](#scripttypefactory-class) | [SPOPortalLaunchValidationResult Class](#spoportallaunchvalidationresult-class) | [UserMigrationPropertiesEnumerablePropertyNames Class](#usermigrationpropertiesenumerablepropertynames-class) |
| [ConnectionStatus Enum](#connectionstatus-enum) | [SPOPortalLaunchValidationResultPropertyNames Class](#spoportallaunchvalidationresultpropertynames-class) | [UserMigrationPropertiesPropertyNames Class](#usermigrationpropertiespropertynames-class) |
| [CredentialsType Enum](#credentialstype-enum) | [SPOPortalLaunchValidationResultTypes Enum](#spoportallaunchvalidationresulttypes-enum) | [SPO3rdPartyAADPermissionGrant Class](#spo3rdpartyaadpermissiongrant-class) |
| [DeviceActionId Enum](#deviceactionid-enum) | [SPOPortalLaunchValidator Class](#spoportallaunchvalidator-class) | [SPO3rdPartyAADPermissionGrantManager Class](#spo3rdpartyaadpermissiongrantmanager-class) |
| [DeviceStatus Enum](#devicestatus-enum) | [SPOSitePropertiesEnumerable Class](#spositepropertiesenumerable-class) | [SPO3rdPartyAADPermissionGrantPropertyNames Class](#spo3rdpartyaadpermissiongrantpropertynames-class) |
| [MigrationTaskStatus Enum](#migrationtaskstatus-enum) | [SPOSitePropertiesEnumerableFilter Class](#spositepropertiesenumerablefilter-class) | [SPOWebAppServicePrincipal Class](#spowebappserviceprincipal-class) |
| [SourceType Enum](#sourcetype-enum) | [SPOSitePropertiesEnumerablePropertyNames Class](#spositepropertiesenumerablepropertynames-class) | [SPOWebAppServicePrincipalObjectPropertyNames Class](#spowebappserviceprincipalobjectpropertynames-class) |
| [StorageActionId Enum](#storageactionid-enum) | [SPOTenantCdnPolicy Class](#spotenantcdnpolicy-class) | [SPOWebAppServicePrincipalPermissionGrant Class](#spowebappserviceprincipalpermissiongrant-class) |
| [TaskActionId Enum](#taskactionid-enum) | [SPOTenantCdnPolicyPropertyNames Class](#spotenantcdnpolicypropertynames-class) | [SPOWebAppServicePrincipalPermissionGrantCollection Class](#spowebappserviceprincipalpermissiongrantcollection-class) |
| [TaskErrorCode Enum](#taskerrorcode-enum) | [SPOTenantCdnPolicyType Enum](#spotenantcdnpolicytype-enum) | [SPOWebAppServicePrincipalPermissionGrantPropertyNames Class](#spowebappserviceprincipalpermissiongrantpropertynames-class) |
| [TaskFailure Enum](#taskfailure-enum) | [SPOTenantCdnType Enum](#spotenantcdntype-enum) | [SPOWebAppServicePrincipalPermissionRequest Class](#spowebappserviceprincipalpermissionrequest-class) |
| [TaskManagementStatus Enum](#taskmanagementstatus-enum) | [SPOTenantGroupIdentityMapping Class](#spotenantgroupidentitymapping-class) | [SPOWebAppServicePrincipalPermissionRequestCollection Class](#spowebappserviceprincipalpermissionrequestcollection-class) |
| [LogExport Class](#logexport-class) | [SPOTenantGroupIdentityMappingPropertyNames Class](#spotenantgroupidentitymappingpropertynames-class) | [SPOWebAppServicePrincipalPermissionRequestPropertyNames Class](#spowebappserviceprincipalpermissionrequestpropertynames-class) |
| [LogFileInfo Class](#logfileinfo-class) | [SPOTenantInstance Class](#spotenantinstance-class) | [SPOWebAppServicePrincipalPropertyNames Class](#spowebappserviceprincipalpropertynames-class) |
| [LogFileInfoPropertyNames Class](#logfileinfopropertynames-class) | [SPOTenantInstancePropertyNames Class](#spotenantinstancepropertynames-class) | [BlockDownloadLinksFileTypes Enum](#blockdownloadlinksfiletypes-enum) |
| [DDIAdapter Class](#ddiadapter-class) | [SPOTenantSiteUserInvitation Class](#spotenantsiteuserinvitation-class) | [ExternalUser Class](#externaluser-class) |
| [AppErrorEntry Class](#apperrorentry-class) | [SPOTenantSiteUserInvitationPropertyNames Class](#spotenantsiteuserinvitationpropertynames-class) | [ExternalUserCollection Class](#externalusercollection-class) |
| [AppErrorEntryPropertyNames Class](#apperrorentrypropertynames-class) | [SPOTenantUserIdentityMapping Class](#spotenantuseridentitymapping-class) | [ExternalUserPropertyNames Class](#externaluserpropertynames-class) |
| [AppErrorType Enum](#apperrortype-enum) | [SPOTenantUserIdentityMappingPropertyNames Class](#spotenantuseridentitymappingpropertynames-class) | [GetExternalUsersResults Class](#getexternalusersresults-class) |
| [AppInfo Class](#appinfo-class) | [SPOTenantWebTemplate Class](#spotenantwebtemplate-class) | [GetExternalUsersResultsObjectPropertyNames Class](#getexternalusersresultsobjectpropertynames-class) |
| [AppInfoPropertyNames Class](#appinfopropertynames-class) | [SPOTenantWebTemplateCollection Class](#spotenantwebtemplatecollection-class) | [GetExternalUsersResultsPropertyNames Class](#getexternalusersresultspropertynames-class) |
| [AppSource Enum](#appsource-enum) | [Tenant Class](#tenant-class) | [GroupCreationParams Class](#groupcreationparams-class) |
| [AppViewsPolicy Enum](#appviewspolicy-enum) | [TenantLog Class](#tenantlog-class) | [GroupCreationParamsPropertyNames Class](#groupcreationparamspropertynames-class) |
| [CompanyWideSharingLinksPolicy Enum](#companywidesharinglinkspolicy-enum) | [TenantLogEntry Class](#tenantlogentry-class) | [ImageTaggingChoice Enum](#imagetaggingchoice-enum) |
| [DeletedSiteProperties Class](#deletedsiteproperties-class) | [TenantLogEntryPropertyNames Class](#tenantlogentrypropertynames-class) | [ImportProfilePropertiesJobError Enum](#importprofilepropertiesjoberror-enum) |
| [DeletedSitePropertiesPropertyNames Class](#deletedsitepropertiespropertynames-class) | [TenantLogPropertyNames Class](#tenantlogpropertynames-class) | [ImportProfilePropertiesJobInfo Class](#importprofilepropertiesjobinfo-class) |
| [DenyAddAndCustomizePagesStatus Enum](#denyaddandcustomizepagesstatus-enum) | [TenantPropertyNames Class](#tenantpropertynames-class) | [ImportProfilePropertiesJobInfoPropertyNames Class](#importprofilepropertiesjobinfopropertynames-class) |
| [FlowsPolicy Enum](#flowspolicy-enum) | [TenantSiteDesign Class](#tenantsitedesign-class) | [ImportProfilePropertiesJobState Enum](#importprofilepropertiesjobstate-enum) |
| [GroupInfo Class](#groupinfo-class) | [TenantSiteDesignCreationInfo Class](#tenantsitedesigncreationinfo-class) | [ImportProfilePropertiesJobStatusCollection Class](#importprofilepropertiesjobstatuscollection-class) |
| [HubSitePermission Class](#hubsitepermission-class) | [TenantSiteDesignPrincipal Class](#tenantsitedesignprincipal-class) | [ImportProfilePropertiesUserIdType Enum](#importprofilepropertiesuseridtype-enum) |
| [HubSiteProperties Class](#hubsiteproperties-class) | [TenantSiteDesignPrincipalPropertyNames Class](#tenantsitedesignprincipalpropertynames-class) | [Office365Tenant Class](#office365tenant-class) |
| [HubSitePropertiesPropertyNames Class](#hubsitepropertiespropertynames-class) | [TenantSiteDesignPrincipalRights Enum](#tenantsitedesignprincipalrights-enum) | [Office365TenantPropertyNames Class](#office365tenantpropertynames-class) |
| [ISPOPortalLaunchValidator Class](#ispoportallaunchvalidator-class) | [TenantSiteDesignPropertyNames Class](#tenantsitedesignpropertynames-class) | [RemoveExternalUsersResults Class](#removeexternalusersresults-class) |
| [MessagesFieldsData Class](#messagesfieldsdata-class) | [TenantSiteDesignRun Class](#tenantsitedesignrun-class) | [RemoveExternalUsersResultsPropertyNames Class](#removeexternalusersresultspropertynames-class) |
| [OdbMigrationStatus Enum](#odbmigrationstatus-enum) | [TenantSiteDesignRunPropertyNames Class](#tenantsitedesignrunpropertynames-class) | [SensitiveByDefaultState Enum](#sensitivebydefaultstate-enum) |
| [PersonalSiteFilter Enum](#personalsitefilter-enum) | [TenantSiteDesignTask Class](#tenantsitedesigntask-class) | [SharingCapabilities Enum](#sharingcapabilities-enum) |
| [PWAEnabledStatus Enum](#pwaenabledstatus-enum) | [TenantSiteDesignTaskPropertyNames Class](#tenantsitedesigntaskpropertynames-class) | [SharingDomainRestrictionModes Enum](#sharingdomainrestrictionmodes-enum) |
| [RestrictedToRegion Enum](#restrictedtoregion-enum) | [TenantSiteScript Class](#tenantsitescript-class) | [SharingLinkType Enum](#sharinglinktype-enum) |
| [SandboxedCodeActivationCapabilities Enum](#sandboxedcodeactivationcapabilities-enum) | [TenantSiteScriptActionOutcome Enum](#tenantsitescriptactionoutcome-enum) | [SharingPermissionType Enum](#sharingpermissiontype-enum) |
| [SecondaryAdministratorsFieldsData Class](#secondaryadministratorsfieldsdata-class) | [TenantSiteScriptActionResult Class](#tenantsitescriptactionresult-class) | [SortOrder Enum](#sortorder-enum) |
| [SecondaryAdministratorsInfo Class](#secondaryadministratorsinfo-class) | [TenantSiteScriptActionResultPropertyNames Class](#tenantsitescriptactionresultpropertynames-class) | [SpecialCharactersState Enum](#specialcharactersstate-enum) |
| [SiteCreationProperties Class](#sitecreationproperties-class) | [TenantSiteScriptActionStatus Class](#tenantsitescriptactionstatus-class) | [SPOConditionalAccessPolicyType Enum](#spoconditionalaccesspolicytype-enum) |
| [SiteInfoForSitePicker Class](#siteinfoforsitepicker-class) | [TenantSiteScriptActionStatusPropertyNames Class](#tenantsitescriptactionstatuspropertynames-class) | [SPOLimitedAccessFileType Enum](#spolimitedaccessfiletype-enum) |
| [SiteProperties Class](#siteproperties-class) | [TenantSiteScriptCreationInfo Class](#tenantsitescriptcreationinfo-class) | [SPOUserSessionRevocationResult Class](#spousersessionrevocationresult-class) |
| [SitePropertiesPropertyNames Class](#sitepropertiespropertynames-class) | [TenantSiteScriptPropertyNames Class](#tenantsitescriptpropertynames-class) | [SPOUserSessionRevocationResultPropertyNames Class](#spousersessionrevocationresultpropertynames-class) |
| [SiteUserGroupInfo Class](#siteusergroupinfo-class) | [TenantSiteScriptSerializationInfo Class](#tenantsitescriptserializationinfo-class) | [SPOUserSessionRevocationState Enum](#spousersessionrevocationstate-enum) |
| [SPODeletedSitePropertiesEnumerable Class](#spodeletedsitepropertiesenumerable-class) | [TenantSiteScriptSerializationResult Class](#tenantsitescriptserializationresult-class) | [ThemeProperties Class](#themeproperties-class) |
| [SPODeletedSitePropertiesEnumerablePropertyNames Class](#spodeletedsitepropertiesenumerablepropertynames-class) | [UserInfo Class](#userinfo-class) | [ThemePropertiesPropertyNames Class](#themepropertiespropertynames-class) |
| [SPOHubSiteUserRights Enum](#spohubsiteuserrights-enum) | [UserMigrationProperties Class](#usermigrationproperties-class) | [Workflows2013State Enum](#workflows2013state-enum) |
| [SpoOperation Class](#spooperation-class) | [UserMigrationPropertiesEnumerable Class](#usermigrationpropertiesenumerable-class) |   |
| [SpoOperationPropertyNames Class](#spooperationpropertynames-class) | [UserMigrationPropertiesEnumerableFilter Class](#usermigrationpropertiesenumerablefilter-class) |   |
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
| **IBSegmentDisplayNames** | string |  |
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
| **IBSegmentDisplayNames** | string |  |
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
| **SourceUserPuid** | string |  |
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
| **SourceUserPuid** | string |  |
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
| **AIBuilderEnabled** | bool |  |
| **AIBuilderSiteInfoList** | IEnumerable\<[SiteInfoForSitePicker](#siteinfoforsitepicker-class)\> |  |
| **AIBuilderSiteList** | IEnumerable\<Guid\> |  |
| **AllowCommentsTextOnEmailEnabled** | bool |  |
| **AllowDownloadingNonWebViewableFiles** | bool |  |
| **AllowedDomainListForSyncClient** | IList\<Guid\> |  |
| **AllowEditing** | bool |  |
| **AllowGuestUserShareToUsersNotInSiteCollection** | bool |  |
| **AllowLimitedAccessOnUnmanagedDevices** | bool |  |
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
| **CommentsOnFilesDisabled** | bool |  |
| **CommentsOnSitePagesDisabled** | bool |  |
| **CompatibilityRange** | string |  |
| **ConditionalAccessPolicy** | [SPOConditionalAccessPolicyType](#spoconditionalaccesspolicytype-enum) |  |
| **ConditionalAccessPolicyErrorHelpLink** | string |  |
| **ContentTypeSyncSiteTemplatesList** | IEnumerable\<string\> |  |
| **CortexLicenseEnabled** | bool |  |
| **CustomizedExternalSharingServiceUrl** | string |  |
| **DefaultContentCenterSite** | [SiteInfoForSitePicker](#siteinfoforsitepicker-class) |  |
| **DefaultLinkPermission** | [SharingPermissionType](#sharingpermissiontype-enum) |  |
| **DefaultSharingLinkType** | [SharingLinkType](#sharinglinktype-enum) |  |
| **DisableAddToOneDrive** | bool |  |
| **DisabledWebPartIds** | Guid[] |  |
| **DisableReportProblemDialog** | bool |  |
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
| **HideDefaultThemes** | bool |  |
| **HideSyncButtonOnODB** | bool |  |
| **ImageTaggingOption** | [ImageTaggingChoice](#imagetaggingchoice-enum) |  |
| **IncludeAtAGlanceInShareEmails** | bool |  |
| **IPAddressAllowList** | string |  |
| **IPAddressEnforcement** | bool |  |
| **IPAddressWACTokenLifetime** | int |  |
| **IsFluidEnabled** | bool |  |
| **IsHubSitesMultiGeoFlightEnabled** | bool |  |
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
| **AddOrUpdateTenantSingleGroupIdentityMappingItem(Guid sourceTenantCompanyId, Guid sourceGroupObjectId, Guid targetGroupObjectId, string targetGroupName, TenantIdentityMappingGroupType groupType)** | void |  |
| **AddOrUpdateTenantSingleUserIdentityMappingItem(Guid sourceTenantCompanyId, string sourceUserPuid, string targetUserPuid, string targetUserUpn, string targetUserEmail, TenantIdentityMappingUserType userType)** | void |  |
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
| **DisconnectSiteFromHubSite(string siteUrl)** | void |  |
| **EnableCommSite(string siteUrl, Guid designPackageId)** | void |  |
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
| **GetOrgAssets()** | ClientResult\<OrgAssets\> |  |
| **GetOrgNewsSites()** | IEnumerable\<string\> |  |
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
| **AIBuilderEnabled** | string |  |
| **AIBuilderSiteInfoList** | string |  |
| **AIBuilderSiteList** | string |  |
| **AllowCommentsTextOnEmailEnabled** | string |  |
| **AllowDownloadingNonWebViewableFiles** | string |  |
| **AllowedDomainListForSyncClient** | string |  |
| **AllowEditing** | string |  |
| **AllowGuestUserShareToUsersNotInSiteCollection** | string |  |
| **AllowLimitedAccessOnUnmanagedDevices** | string |  |
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
| **CommentsOnFilesDisabled** | string |  |
| **CommentsOnSitePagesDisabled** | string |  |
| **CompatibilityRange** | string |  |
| **ConditionalAccessPolicy** | string |  |
| **ConditionalAccessPolicyErrorHelpLink** | string |  |
| **ContentTypeSyncSiteTemplatesList** | string |  |
| **CortexLicenseEnabled** | string |  |
| **CustomizedExternalSharingServiceUrl** | string |  |
| **DefaultContentCenterSite** | string |  |
| **DefaultLinkPermission** | string |  |
| **DefaultSharingLinkType** | string |  |
| **DisableAddToOneDrive** | string |  |
| **DisabledWebPartIds** | string |  |
| **DisableReportProblemDialog** | string |  |
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
| **HideDefaultThemes** | string |  |
| **HideSyncButtonOnODB** | string |  |
| **ImageTaggingOption** | string |  |
| **IncludeAtAGlanceInShareEmails** | string |  |
| **IPAddressAllowList** | string |  |
| **IPAddressEnforcement** | string |  |
| **IPAddressWACTokenLifetime** | string |  |
| **IsFluidEnabled** | string |  |
| **IsHubSitesMultiGeoFlightEnabled** | string |  |
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
| **Id** | Guid |  |
| **IsDefault** | bool |  |
| **PreviewImageAltText** | string |  |
| **PreviewImageUrl** | string |  |
| **SiteScriptIds** | Guid[] |  |
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
| **Id** | string |  |
| **IsDefault** | string |  |
| **PreviewImageAltText** | string |  |
| **PreviewImageUrl** | string |  |
| **SiteScriptIds** | string |  |
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
| **AIBuilderEnabled** | bool |  |
| **AIBuilderSiteInfoList** | IEnumerable\<[SiteInfoForSitePicker](#siteinfoforsitepicker-class)\> |  |
| **AIBuilderSiteList** | IEnumerable\<Guid\> |  |
| **AllowCommentsTextOnEmailEnabled** | bool |  |
| **AllowDownloadingNonWebViewableFiles** | bool |  |
| **AllowedDomainListForSyncClient** | IList\<Guid\> |  |
| **AllowEditing** | bool |  |
| **AllowGuestUserShareToUsersNotInSiteCollection** | bool |  |
| **AllowLimitedAccessOnUnmanagedDevices** | bool |  |
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
| **CommentsOnFilesDisabled** | bool |  |
| **CommentsOnSitePagesDisabled** | bool |  |
| **ConditionalAccessPolicy** | [SPOConditionalAccessPolicyType](#spoconditionalaccesspolicytype-enum) |  |
| **ConditionalAccessPolicyErrorHelpLink** | string |  |
| **ContentTypeSyncSiteTemplatesList** | IEnumerable\<string\> |  |
| **CustomizedExternalSharingServiceUrl** | string |  |
| **DefaultContentCenterSite** | [SiteInfoForSitePicker](#siteinfoforsitepicker-class) |  |
| **DefaultLinkPermission** | [SharingPermissionType](#sharingpermissiontype-enum) |  |
| **DefaultSharingLinkType** | [SharingLinkType](#sharinglinktype-enum) |  |
| **DisableAddToOneDrive** | bool |  |
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
| **AIBuilderEnabled** | string |  |
| **AIBuilderSiteInfoList** | string |  |
| **AIBuilderSiteList** | string |  |
| **AllowCommentsTextOnEmailEnabled** | string |  |
| **AllowDownloadingNonWebViewableFiles** | string |  |
| **AllowedDomainListForSyncClient** | string |  |
| **AllowEditing** | string |  |
| **AllowGuestUserShareToUsersNotInSiteCollection** | string |  |
| **AllowLimitedAccessOnUnmanagedDevices** | string |  |
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
| **CommentsOnFilesDisabled** | string |  |
| **CommentsOnSitePagesDisabled** | string |  |
| **ConditionalAccessPolicy** | string |  |
| **ConditionalAccessPolicyErrorHelpLink** | string |  |
| **ContentTypeSyncSiteTemplatesList** | string |  |
| **CustomizedExternalSharingServiceUrl** | string |  |
| **DefaultContentCenterSite** | string |  |
| **DefaultLinkPermission** | string |  |
| **DefaultSharingLinkType** | string |  |
| **DisableAddToOneDrive** | string |  |
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
| **ProtectionLevel** |  |
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
