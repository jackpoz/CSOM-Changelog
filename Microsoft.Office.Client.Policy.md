# Microsoft.Office.Client.Policy.dll v.16.1.0.0 API documentation

Created by 
[mddox](https://github.com/loxsmoke/mddox) on 06/04/2023

# All types

|   |   |   |
|---|---|---|
| [ScriptTypeFactory Class](#scripttypefactory-class) | [SPContainerType Enum](#spcontainertype-enum) | [SPScsTenantEndPointInfo Class](#spscstenantendpointinfo-class) |
| [ComplianceTag Class](#compliancetag-class) | [SPPolicyAssociation Class](#sppolicyassociation-class) | [SPScsTenantEndPointInfoPropertyNames Class](#spscstenantendpointinfopropertynames-class) |
| [DlpAccessScope Enum](#dlpaccessscope-enum) | [SPPolicyAssociationPropertyNames Class](#sppolicyassociationpropertynames-class) | [SPSyncNotificationEndpointInfo Class](#spsyncnotificationendpointinfo-class) |
| [DlpClassificationResult Class](#dlpclassificationresult-class) | [SPPolicyBinding Class](#sppolicybinding-class) | [SPSyncNotificationEndpointInfoPropertyNames Class](#spsyncnotificationendpointinfopropertynames-class) |
| [PolicyEvaluationInfo Class](#policyevaluationinfo-class) | [SPPolicyBindingPropertyNames Class](#sppolicybindingpropertynames-class) | [Case Class](#case-class) |
| [PolicyEvaluationInfoEnums Enum](#policyevaluationinfoenums-enum) | [SPPolicyDefinition Class](#sppolicydefinition-class) | [Export Class](#export-class) |
| [PolicyEvaluationInfoPropertyNames Class](#policyevaluationinfopropertynames-class) | [SPPolicyDefinitionPropertyNames Class](#sppolicydefinitionpropertynames-class) | [ExportPropertyNames Class](#exportpropertynames-class) |
| [PolicyScenario Enum](#policyscenario-enum) | [SPPolicyRule Class](#sppolicyrule-class) | [ExportStatus Enum](#exportstatus-enum) |
| [PolicyTipOverrideResult Enum](#policytipoverrideresult-enum) | [SPPolicyRulePropertyNames Class](#sppolicyrulepropertynames-class) | [ProjectPolicy Class](#projectpolicy-class) |
| [PolicyTipOverrideUserAction Enum](#policytipoverrideuseraction-enum) | [SPPolicyStore Class](#sppolicystore-class) | [ProjectPolicyPropertyNames Class](#projectpolicypropertynames-class) |
| [SPContainerId Class](#spcontainerid-class) | [SPPolicyStoreProxy Class](#sppolicystoreproxy-class) | [Records Class](#records-class) |
| [SPContainerIdPropertyNames Class](#spcontaineridpropertynames-class) | [SPPolicyStoreProxyPropertyNames Class](#sppolicystoreproxypropertynames-class) |   |
# ScriptTypeFactory Class

Namespace: Microsoft.Office.Client.Policy


## Methods

| Name | Returns | Summary |
|---|---|---|
| **CreateObjectFromScriptType(string scriptType, ClientRuntimeContext context)** | IFromJson |  |
# ComplianceTag Class

Namespace: Microsoft.SharePoint.Client.CompliancePolicy

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **BlockDelete** | bool |  |
| **TagDuration** | int |  |
| **TagId** | Guid |  |
| **TagName** | string |  |
| **TagRetentionBasedOn** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# DlpAccessScope Enum

Namespace: Microsoft.SharePoint.Client.CompliancePolicy


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **InternalUsersOnly** |  |
| **IncludeExternalUsers** |  |
# DlpClassificationResult Class

Namespace: Microsoft.SharePoint.Client.CompliancePolicy

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ClassificationId** | string |  |
| **Confidence** | int |  |
| **Count** | int |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# PolicyEvaluationInfo Class

Namespace: Microsoft.SharePoint.Client.CompliancePolicy

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ApplicablePolicies** | string[] |  |
| **DlpAccessScope** | [DlpAccessScope](#dlpaccessscope-enum) |  |
| **MatchedRules** | string[] |  |
| **OverriddenRules** | string[] |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **PolicyEvaluationInfo(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# PolicyEvaluationInfoEnums Enum

Namespace: Microsoft.SharePoint.Client.CompliancePolicy


## Values

| Name | Summary |
|---|---|
| **DlpAccessScope** |  |
| **ApplicablePolicies** |  |
| **OverriddenRules** |  |
| **MatchedRules** |  |
# PolicyEvaluationInfoPropertyNames Class

Namespace: Microsoft.SharePoint.Client.CompliancePolicy


## Fields

| Name | Type | Summary |
|---|---|---|
| **ApplicablePolicies** | string |  |
| **DlpAccessScope** | string |  |
| **MatchedRules** | string |  |
| **OverriddenRules** | string |  |
# PolicyScenario Enum

Namespace: Microsoft.SharePoint.Client.CompliancePolicy


## Values

| Name | Summary |
|---|---|
| **Retention** |  |
| **Hold** |  |
| **Dlp** |  |
| **DeviceSettings** |  |
| **AuditSettings** |  |
| **DeviceConditionalAccess** |  |
| **DeviceTenantConditionalAccess** |  |
| **AuditAlert** |  |
| **CaseHold** |  |
# PolicyTipOverrideResult Enum

Namespace: Microsoft.SharePoint.Client.CompliancePolicy


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **FalsePositiveReported** |  |
| **Overridden** |  |
| **FalsePositiveReportedAndOverridden** |  |
# PolicyTipOverrideUserAction Enum

Namespace: Microsoft.SharePoint.Client.CompliancePolicy


## Values

| Name | Summary |
|---|---|
| **Override** |  |
| **ReportFalsePositive** |  |
| **ReportFalsePositiveAndOverride** |  |
# SPContainerId Class

Namespace: Microsoft.SharePoint.Client.CompliancePolicy

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ContainerType** | [SPContainerType](#spcontainertype-enum) |  |
| **ListId** | Guid |  |
| **SiteId** | Guid |  |
| **SiteUrl** | string |  |
| **TenantId** | Guid |  |
| **Title** | string |  |
| **Version** | int |  |
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
| **SPContainerId(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Create(ClientRuntimeContext context, string containerId)** | [SPContainerId](#spcontainerid-class) |  |
| **CreateFromList(ClientRuntimeContext context, List list)** | [SPContainerId](#spcontainerid-class) |  |
| **CreateFromSite(ClientRuntimeContext context, Site site)** | [SPContainerId](#spcontainerid-class) |  |
| **CreateFromWeb(ClientRuntimeContext context, Web web)** | [SPContainerId](#spcontainerid-class) |  |
| **Serialize()** | ClientResult\<string\> |  |
# SPContainerIdPropertyNames Class

Namespace: Microsoft.SharePoint.Client.CompliancePolicy


## Fields

| Name | Type | Summary |
|---|---|---|
| **ContainerType** | string |  |
| **ListId** | string |  |
| **SiteId** | string |  |
| **SiteUrl** | string |  |
| **TenantId** | string |  |
| **Title** | string |  |
| **Version** | string |  |
| **WebId** | string |  |
# SPContainerType Enum

Namespace: Microsoft.SharePoint.Client.CompliancePolicy


## Values

| Name | Summary |
|---|---|
| **Site** |  |
| **Web** |  |
| **List** |  |
# SPPolicyAssociation Class

Namespace: Microsoft.SharePoint.Client.CompliancePolicy

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AllowOverride** | bool |  |
| **Comment** | string |  |
| **DefaultPolicyDefinitionConfigId** | Guid |  |
| **Description** | string |  |
| **Identity** | Guid |  |
| **Name** | string |  |
| **PolicyApplyStatus** | int |  |
| **PolicyDefinitionConfigIds** | IEnumerable\<Guid\> |  |
| **Scope** | string |  |
| **Source** | int |  |
| **Version** | Guid |  |
| **WhenAppliedUTC** | DateTime |  |
| **WhenChangedUTC** | DateTime |  |
| **WhenCreatedUTC** | DateTime |  |
| **Workload** | int |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **SPPolicyAssociation(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# SPPolicyAssociationPropertyNames Class

Namespace: Microsoft.SharePoint.Client.CompliancePolicy


## Fields

| Name | Type | Summary |
|---|---|---|
| **AllowOverride** | string |  |
| **Comment** | string |  |
| **DefaultPolicyDefinitionConfigId** | string |  |
| **Description** | string |  |
| **Identity** | string |  |
| **Name** | string |  |
| **PolicyApplyStatus** | string |  |
| **PolicyDefinitionConfigIds** | string |  |
| **Scope** | string |  |
| **Source** | string |  |
| **Version** | string |  |
| **WhenAppliedUTC** | string |  |
| **WhenChangedUTC** | string |  |
| **WhenCreatedUTC** | string |  |
| **Workload** | string |  |
# SPPolicyBinding Class

Namespace: Microsoft.SharePoint.Client.CompliancePolicy

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **BindingType** | int |  |
| **Identity** | Guid |  |
| **IsExempt** | bool |  |
| **Mode** | int |  |
| **Name** | string |  |
| **PolicyApplyStatus** | int |  |
| **PolicyAssociationConfigId** | Guid |  |
| **PolicyDefinitionConfigId** | Guid |  |
| **PolicyRuleConfigId** | Guid |  |
| **Scope** | string |  |
| **Source** | int |  |
| **Version** | Guid |  |
| **WhenAppliedUTC** | DateTime |  |
| **WhenChangedUTC** | DateTime |  |
| **WhenCreatedUTC** | DateTime |  |
| **Workload** | int |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **SPPolicyBinding(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# SPPolicyBindingPropertyNames Class

Namespace: Microsoft.SharePoint.Client.CompliancePolicy


## Fields

| Name | Type | Summary |
|---|---|---|
| **BindingType** | string |  |
| **Identity** | string |  |
| **IsExempt** | string |  |
| **Mode** | string |  |
| **Name** | string |  |
| **PolicyApplyStatus** | string |  |
| **PolicyAssociationConfigId** | string |  |
| **PolicyDefinitionConfigId** | string |  |
| **PolicyRuleConfigId** | string |  |
| **Scope** | string |  |
| **Source** | string |  |
| **Version** | string |  |
| **WhenAppliedUTC** | string |  |
| **WhenChangedUTC** | string |  |
| **WhenCreatedUTC** | string |  |
| **Workload** | string |  |
# SPPolicyDefinition Class

Namespace: Microsoft.SharePoint.Client.CompliancePolicy

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Comment** | string |  |
| **CreatedBy** | string |  |
| **DefaultPolicyRuleConfigId** | Guid |  |
| **Description** | string |  |
| **Enabled** | bool |  |
| **Identity** | Guid |  |
| **LastModifiedBy** | string |  |
| **Mode** | int |  |
| **Name** | string |  |
| **Priority** | int |  |
| **Scenario** | int |  |
| **Source** | int |  |
| **Version** | Guid |  |
| **WhenChangedUTC** | DateTime |  |
| **WhenCreatedUTC** | DateTime |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **SPPolicyDefinition(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# SPPolicyDefinitionPropertyNames Class

Namespace: Microsoft.SharePoint.Client.CompliancePolicy


## Fields

| Name | Type | Summary |
|---|---|---|
| **Comment** | string |  |
| **CreatedBy** | string |  |
| **DefaultPolicyRuleConfigId** | string |  |
| **Description** | string |  |
| **Enabled** | string |  |
| **Identity** | string |  |
| **LastModifiedBy** | string |  |
| **Mode** | string |  |
| **Name** | string |  |
| **Priority** | string |  |
| **Scenario** | string |  |
| **Source** | string |  |
| **Version** | string |  |
| **WhenChangedUTC** | string |  |
| **WhenCreatedUTC** | string |  |
# SPPolicyRule Class

Namespace: Microsoft.SharePoint.Client.CompliancePolicy

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Comment** | string |  |
| **CreatedBy** | string |  |
| **Description** | string |  |
| **Enabled** | bool |  |
| **Identity** | Guid |  |
| **LastModifiedBy** | string |  |
| **Mode** | int |  |
| **Name** | string |  |
| **PolicyDefinitionConfigId** | Guid |  |
| **Priority** | int |  |
| **RuleBlob** | string |  |
| **Scenario** | int |  |
| **Source** | int |  |
| **Version** | Guid |  |
| **WhenChangedUTC** | DateTime |  |
| **WhenCreatedUTC** | DateTime |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **SPPolicyRule(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# SPPolicyRulePropertyNames Class

Namespace: Microsoft.SharePoint.Client.CompliancePolicy


## Fields

| Name | Type | Summary |
|---|---|---|
| **Comment** | string |  |
| **CreatedBy** | string |  |
| **Description** | string |  |
| **Enabled** | string |  |
| **Identity** | string |  |
| **LastModifiedBy** | string |  |
| **Mode** | string |  |
| **Name** | string |  |
| **PolicyDefinitionConfigId** | string |  |
| **Priority** | string |  |
| **RuleBlob** | string |  |
| **Scenario** | string |  |
| **Source** | string |  |
| **Version** | string |  |
| **WhenChangedUTC** | string |  |
| **WhenCreatedUTC** | string |  |
# SPPolicyStore Class

Namespace: Microsoft.SharePoint.Client.CompliancePolicy

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
| **SPPolicyStore(ClientRuntimeContext context, Web web)** |  |
| **SPPolicyStore(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **CreatePolicyAssociation(ClientRuntimeContext context)** | [SPPolicyAssociation](#sppolicyassociation-class) |  |
| **CreatePolicyBinding(ClientRuntimeContext context)** | [SPPolicyBinding](#sppolicybinding-class) |  |
| **CreatePolicyDefinition(ClientRuntimeContext context)** | [SPPolicyDefinition](#sppolicydefinition-class) |  |
| **CreatePolicyRule(ClientRuntimeContext context)** | [SPPolicyRule](#sppolicyrule-class) |  |
| **DeletePolicyAssociation(Guid policyAssociationId)** | void |  |
| **DeletePolicyBinding(Guid policyBindingId)** | void |  |
| **DeletePolicyDefinition(Guid policyDefinitionId)** | void |  |
| **DeletePolicyRule(Guid policyRuleId)** | void |  |
| **GetPolicyAssociation(Guid policyAssociationId)** | [SPPolicyAssociation](#sppolicyassociation-class) |  |
| **GetPolicyAssociationForContainer(string containerId)** | [SPPolicyAssociation](#sppolicyassociation-class) |  |
| **GetPolicyBinding(Guid policyBindingId)** | [SPPolicyBinding](#sppolicybinding-class) |  |
| **GetPolicyDefinition(Guid policyDefinitionId)** | [SPPolicyDefinition](#sppolicydefinition-class) |  |
| **GetPolicyDefinitions(int scenario)** | ClientObjectList\<[SPPolicyDefinition](#sppolicydefinition-class)\> |  |
| **GetPolicyRule(Guid policyRuleId, bool throwIfNull)** | [SPPolicyRule](#sppolicyrule-class) |  |
| **GetSPScsTenantEndPointInfo(string eopCorrelationId)** | [SPScsTenantEndPointInfo](#spscstenantendpointinfo-class) |  |
| **NotifyUnifiedFileSyncForSPTenant(int syncFileType, Guid notificationId)** | ClientResult\<bool\> |  |
| **NotifyUnifiedPolicySyncForLogicalWorkload(string notificationId, string syncSvcUrl, string[] changeInfos, bool syncNow, bool fullSyncForTenant, int workload)** | [SPSyncNotificationEndpointInfo](#spsyncnotificationendpointinfo-class) |  |
| **UpdatePolicyAssociation(SPPolicyAssociation policyAssociation)** | void |  |
| **UpdatePolicyBinding(SPPolicyBinding policyBinding)** | void |  |
| **UpdatePolicyDefinition(SPPolicyDefinition policyDefinition)** | void |  |
| **UpdatePolicyRule(SPPolicyRule policyRule)** | void |  |
# SPPolicyStoreProxy Class

Namespace: Microsoft.SharePoint.Client.CompliancePolicy

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **PolicyStoreUrl** | string |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **SPPolicyStoreProxy(ClientRuntimeContext context, Web web)** |  |
| **SPPolicyStoreProxy(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetAvailableTagsForSite(ClientRuntimeContext context, string siteUrl)** | IList\<[ComplianceTag](#compliancetag-class)\> |  |
| **GetPolicyEvaluationInfo(ClientRuntimeContext context, string itemUrl, PolicyScenario policyScenario, PolicyEvaluationInfoEnums infos)** | [PolicyEvaluationInfo](#policyevaluationinfo-class) |  |
| **OverridePolicyTip(ClientRuntimeContext context, string itemUrl, PolicyTipOverrideUserAction userAction, string justification, string[] rules, DlpClassificationResult[] classificationResults)** | ClientResult\<[PolicyTipOverrideResult](#policytipoverrideresult-enum)\> |  |
# SPPolicyStoreProxyPropertyNames Class

Namespace: Microsoft.SharePoint.Client.CompliancePolicy


## Fields

| Name | Type | Summary |
|---|---|---|
| **PolicyStoreUrl** | string |  |
# SPScsTenantEndPointInfo Class

Namespace: Microsoft.SharePoint.Client.CompliancePolicy

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **FarmLabel** | string |  |
| **ScsEndPointUrl** | string |  |
| **SearchFarmId** | string |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **SPScsTenantEndPointInfo(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# SPScsTenantEndPointInfoPropertyNames Class

Namespace: Microsoft.SharePoint.Client.CompliancePolicy


## Fields

| Name | Type | Summary |
|---|---|---|
| **FarmLabel** | string |  |
| **ScsEndPointUrl** | string |  |
| **SearchFarmId** | string |  |
# SPSyncNotificationEndpointInfo Class

Namespace: Microsoft.SharePoint.Client.CompliancePolicy

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **IsNotifySuccess** | bool |  |
| **MasterCorrelationId** | string |  |
| **ServerBuild** | string |  |
| **ServerName** | string |  |
| **WorkloadCorrelationId** | string |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **SPSyncNotificationEndpointInfo(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# SPSyncNotificationEndpointInfoPropertyNames Class

Namespace: Microsoft.SharePoint.Client.CompliancePolicy


## Fields

| Name | Type | Summary |
|---|---|---|
| **IsNotifySuccess** | string |  |
| **MasterCorrelationId** | string |  |
| **ServerBuild** | string |  |
| **ServerName** | string |  |
| **WorkloadCorrelationId** | string |  |
# Case Class

Namespace: Microsoft.SharePoint.Client.Discovery

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
| **Case(ClientRuntimeContext context, Web web)** |  |
| **Case(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetExportContent(IList\<int\> sourceIds)** | ClientResult\<string\> |  |
# Export Class

Namespace: Microsoft.SharePoint.Client.Discovery

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Status** | [ExportStatus](#exportstatus-enum) |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **Export(ClientRuntimeContext context, ListItem item)** |  |
| **Export(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetExportContent()** | ClientResult\<string\> |  |
| **Update()** | void |  |
# ExportPropertyNames Class

Namespace: Microsoft.SharePoint.Client.Discovery


## Fields

| Name | Type | Summary |
|---|---|---|
| **Status** | string |  |
# ExportStatus Enum

Namespace: Microsoft.SharePoint.Client.Discovery


## Values

| Name | Summary |
|---|---|
| **NotStarted** |  |
| **Started** |  |
| **Complete** |  |
| **Failed** |  |
# ProjectPolicy Class

Namespace: Microsoft.SharePoint.Client.InformationPolicy

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Description** | string |  |
| **EmailBody** | string |  |
| **EmailBodyWithTeamMailbox** | string |  |
| **EmailSubject** | string |  |
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
| **ProjectPolicy(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **ApplyProjectPolicy(ClientRuntimeContext context, Web web, ProjectPolicy projectPolicy)** | void |  |
| **CloseProject(ClientRuntimeContext context, Web web)** | void |  |
| **DoesProjectHavePolicy(ClientRuntimeContext context, Web web)** | ClientResult\<bool\> |  |
| **GetCurrentlyAppliedProjectPolicyOnWeb(ClientRuntimeContext context, Web web)** | [ProjectPolicy](#projectpolicy-class) |  |
| **GetProjectCloseDate(ClientRuntimeContext context, Web web)** | ClientResult\<DateTime\> |  |
| **GetProjectExpirationDate(ClientRuntimeContext context, Web web)** | ClientResult\<DateTime\> |  |
| **GetProjectPolicies(ClientRuntimeContext context, Web web)** | ClientObjectList\<[ProjectPolicy](#projectpolicy-class)\> |  |
| **IsProjectClosed(ClientRuntimeContext context, Web web)** | ClientResult\<bool\> |  |
| **OpenProject(ClientRuntimeContext context, Web web)** | void |  |
| **PostponeProject(ClientRuntimeContext context, Web web)** | void |  |
| **SavePolicy()** | void |  |
# ProjectPolicyPropertyNames Class

Namespace: Microsoft.SharePoint.Client.InformationPolicy


## Fields

| Name | Type | Summary |
|---|---|---|
| **Description** | string |  |
| **EmailBody** | string |  |
| **EmailBodyWithTeamMailbox** | string |  |
| **EmailSubject** | string |  |
| **Name** | string |  |
# Records Class

Namespace: Microsoft.SharePoint.Client.RecordsRepository


## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeclareItemAsRecord(ClientRuntimeContext context, ListItem itemToDeclare)** | void |  |
| **IsRecord(ClientRuntimeContext context, ListItem item)** | ClientResult\<bool\> |  |
| **UndeclareItemAsRecord(ClientRuntimeContext context, ListItem item)** | void |  |
