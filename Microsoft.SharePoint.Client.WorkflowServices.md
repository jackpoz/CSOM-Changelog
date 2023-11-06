# Microsoft.SharePoint.Client.WorkflowServices.dll v.16.1.0.0 API documentation

Created by 
[mddox](https://github.com/loxsmoke/mddox) on 2023-11-06

# All types

|   |   |   |
|---|---|---|
| [InteropService Class](#interopservice-class) | [WorkflowInstanceCollection Class](#workflowinstancecollection-class) | [WorkflowStatus Enum](#workflowstatus-enum) |
| [WorkflowDefinition Class](#workflowdefinition-class) | [WorkflowInstancePropertyNames Class](#workflowinstancepropertynames-class) | [WorkflowSubscription Class](#workflowsubscription-class) |
| [WorkflowDefinitionCollection Class](#workflowdefinitioncollection-class) | [WorkflowInstanceService Class](#workflowinstanceservice-class) | [WorkflowSubscriptionCollection Class](#workflowsubscriptioncollection-class) |
| [WorkflowDefinitionPropertyNames Class](#workflowdefinitionpropertynames-class) | [WorkflowServiceHealthStatus Enum](#workflowservicehealthstatus-enum) | [WorkflowSubscriptionPropertyNames Class](#workflowsubscriptionpropertynames-class) |
| [WorkflowDeploymentService Class](#workflowdeploymentservice-class) | [WorkflowServicesManager Class](#workflowservicesmanager-class) | [WorkflowSubscriptionService Class](#workflowsubscriptionservice-class) |
| [WorkflowInstance Class](#workflowinstance-class) | [WorkflowServicesManagerPropertyNames Class](#workflowservicesmanagerpropertynames-class) | [ScriptTypeFactory Class](#scripttypefactory-class) |
# InteropService Class

Namespace: Microsoft.SharePoint.Client.WorkflowServices

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
| **InteropService(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **CancelWorkflow(Guid instanceId)** | void |  |
| **DisableEvents(Guid listId, Guid itemGuid)** | void |  |
| **EnableEvents(Guid listId, Guid itemGuid)** | void |  |
| **GetCurrent(ClientRuntimeContext Context)** | [InteropService](#interopservice-class) |  |
| **StartWorkflow(string associationName, Guid correlationId, Guid listId, Guid itemGuid, IDictionary\<string, Object\> workflowParameters)** | ClientResult\<Guid\> |  |
# WorkflowDefinition Class

Namespace: Microsoft.SharePoint.Client.WorkflowServices

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AssociationUrl** | string |  |
| **Description** | string |  |
| **DisplayName** | string |  |
| **DraftVersion** | string |  |
| **FormField** | string |  |
| **Id** | Guid |  |
| **InitiationUrl** | string |  |
| **Properties** | IDictionary\<string, string\> |  |
| **Published** | bool |  |
| **RequiresAssociationForm** | bool |  |
| **RequiresInitiationForm** | bool |  |
| **RestrictToScope** | string |  |
| **RestrictToType** | string |  |
| **Xaml** | string |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **WorkflowDefinition(ClientRuntimeContext context)** |  |
| **WorkflowDefinition(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **SetProperty(string propertyName, string value)** | void |  |
# WorkflowDefinitionCollection Class

Namespace: Microsoft.SharePoint.Client.WorkflowServices

Base class: ClientObjectCollection<[WorkflowDefinition](#workflowdefinition-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [WorkflowDefinition](#workflowdefinition-class) |  |
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
| **WorkflowDefinitionCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Sort()** | void |  |
# WorkflowDefinitionPropertyNames Class

Namespace: Microsoft.SharePoint.Client.WorkflowServices


## Fields

| Name | Type | Summary |
|---|---|---|
| **AssociationUrl** | string |  |
| **Description** | string |  |
| **DisplayName** | string |  |
| **DraftVersion** | string |  |
| **FormField** | string |  |
| **Id** | string |  |
| **InitiationUrl** | string |  |
| **Properties** | string |  |
| **Published** | string |  |
| **RequiresAssociationForm** | string |  |
| **RequiresInitiationForm** | string |  |
| **RestrictToScope** | string |  |
| **RestrictToType** | string |  |
| **Xaml** | string |  |
# WorkflowDeploymentService Class

Namespace: Microsoft.SharePoint.Client.WorkflowServices

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
| **WorkflowDeploymentService(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteCollateral(Guid workflowDefinitionId, string leafFileName)** | void |  |
| **DeleteDefinition(Guid definitionId)** | void |  |
| **DeprecateDefinition(Guid definitionId)** | void |  |
| **EnumerateDefinitions(bool publishedOnly)** | [WorkflowDefinitionCollection](#workflowdefinitioncollection-class) |  |
| **EnumerateIntegratedApps()** | ClientObjectList\<AppInstance\> |  |
| **GetActivitySignatures(DateTime lastChanged)** | ClientResult\<IDictionary\<string, string\>\> |  |
| **GetCollateralUri(Guid workflowDefinitionId, string leafFileName)** | ClientResult\<string\> |  |
| **GetDefinition(Guid definitionId)** | [WorkflowDefinition](#workflowdefinition-class) |  |
| **GetDesignerActions(Web web)** | ClientResult\<string\> |  |
| **IsIntegratedApp()** | ClientResult\<bool\> |  |
| **PackageDefinition(Guid definitionId, string packageDefaultFilename, string packageTitle, string packageDescription)** | ClientResult\<string\> |  |
| **PublishDefinition(Guid definitionId)** | void |  |
| **SaveCollateral(Guid workflowDefinitionId, string leafFileName, Stream fileContent)** | void |  |
| **SaveDefinition(WorkflowDefinition definition)** | ClientResult\<Guid\> |  |
| **ValidateActivity(string activityXaml)** | ClientResult\<string\> |  |
# WorkflowInstance Class

Namespace: Microsoft.SharePoint.Client.WorkflowServices

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **FaultInfo** | string |  |
| **Id** | Guid |  |
| **InstanceCreated** | DateTime |  |
| **LastUpdated** | DateTime |  |
| **Properties** | IDictionary\<string, string\> |  |
| **Status** | [WorkflowStatus](#workflowstatus-enum) |  |
| **UserStatus** | string |  |
| **WorkflowSubscriptionId** | Guid |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **WorkflowInstance(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# WorkflowInstanceCollection Class

Namespace: Microsoft.SharePoint.Client.WorkflowServices

Base class: ClientObjectCollection<[WorkflowInstance](#workflowinstance-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [WorkflowInstance](#workflowinstance-class) |  |
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
| **WorkflowInstanceCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# WorkflowInstancePropertyNames Class

Namespace: Microsoft.SharePoint.Client.WorkflowServices


## Fields

| Name | Type | Summary |
|---|---|---|
| **FaultInfo** | string |  |
| **Id** | string |  |
| **InstanceCreated** | string |  |
| **LastUpdated** | string |  |
| **Properties** | string |  |
| **Status** | string |  |
| **UserStatus** | string |  |
| **WorkflowSubscriptionId** | string |  |
# WorkflowInstanceService Class

Namespace: Microsoft.SharePoint.Client.WorkflowServices

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
| **WorkflowInstanceService(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **CancelWorkflow(WorkflowInstance instance)** | void |  |
| **CountInstances(WorkflowSubscription parentSubscription)** | ClientResult\<int\> |  |
| **CountInstancesWithStatus(WorkflowSubscription parentSubscription, WorkflowStatus status)** | ClientResult\<int\> |  |
| **Enumerate(WorkflowSubscription parentSubscription)** | [WorkflowInstanceCollection](#workflowinstancecollection-class) |  |
| **EnumerateInstancesForListItem(Guid listId, int itemId)** | [WorkflowInstanceCollection](#workflowinstancecollection-class) |  |
| **EnumerateInstancesForListItemWithOffset(Guid listId, int itemId, int offset)** | [WorkflowInstanceCollection](#workflowinstancecollection-class) |  |
| **EnumerateInstancesForSite()** | [WorkflowInstanceCollection](#workflowinstancecollection-class) |  |
| **EnumerateInstancesForSiteWithOffset(int offset)** | [WorkflowInstanceCollection](#workflowinstancecollection-class) |  |
| **EnumerateWithOffset(WorkflowSubscription parentSubscription, int offset)** | [WorkflowInstanceCollection](#workflowinstancecollection-class) |  |
| **GetCurrent(ClientRuntimeContext Context)** | [WorkflowInstanceService](#workflowinstanceservice-class) |  |
| **GetDebugInfo(WorkflowInstance instance)** | ClientResult\<string\> |  |
| **GetInstance(Guid instanceId)** | [WorkflowInstance](#workflowinstance-class) |  |
| **PublishCustomEvent(WorkflowInstance instance, string eventName, string payload)** | void |  |
| **ResumeWorkflow(WorkflowInstance instance)** | void |  |
| **StartWorkflow(WorkflowSubscription subscription, IDictionary\<string, Object\> payload)** | ClientResult\<Guid\> |  |
| **StartWorkflowOnListItem(WorkflowSubscription subscription, int itemId, IDictionary\<string, Object\> payload)** | ClientResult\<Guid\> |  |
| **SuspendWorkflow(WorkflowInstance instance)** | void |  |
| **TerminateWorkflow(WorkflowInstance instance)** | void |  |
# WorkflowServiceHealthStatus Enum

Namespace: Microsoft.SharePoint.Client.WorkflowServices


## Values

| Name | Summary |
|---|---|
| **Active** |  |
| **NoScope** |  |
| **NotConnected** |  |
| **Suspended** |  |
| **Throttled** |  |
| **Unknown** |  |
| **Unregistered** |  |
# WorkflowServicesManager Class

Namespace: Microsoft.SharePoint.Client.WorkflowServices

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AppId** | string |  |
| **IsConnected** | bool |  |
| **IsRegistered** | bool |  |
| **ScopePath** | string |  |
| **ServiceHealthStatus** | [WorkflowServiceHealthStatus](#workflowservicehealthstatus-enum) |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **WorkflowServicesManager(ClientRuntimeContext context, Web web)** |  |
| **WorkflowServicesManager(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetWorkflowDeploymentService()** | [WorkflowDeploymentService](#workflowdeploymentservice-class) |  |
| **GetWorkflowInstanceService()** | [WorkflowInstanceService](#workflowinstanceservice-class) |  |
| **GetWorkflowInteropService()** | [InteropService](#interopservice-class) |  |
| **GetWorkflowSubscriptionService()** | [WorkflowSubscriptionService](#workflowsubscriptionservice-class) |  |
| **IsIntegratedApp()** | ClientResult\<bool\> |  |
# WorkflowServicesManagerPropertyNames Class

Namespace: Microsoft.SharePoint.Client.WorkflowServices


## Fields

| Name | Type | Summary |
|---|---|---|
| **AppId** | string |  |
| **IsConnected** | string |  |
| **IsRegistered** | string |  |
| **ScopePath** | string |  |
| **ServiceHealthStatus** | string |  |
# WorkflowStatus Enum

Namespace: Microsoft.SharePoint.Client.WorkflowServices


## Values

| Name | Summary |
|---|---|
| **NotStarted** |  |
| **Started** |  |
| **Suspended** |  |
| **Canceling** |  |
| **Canceled** |  |
| **Terminated** |  |
| **Completed** |  |
| **NotSpecified** |  |
| **Invalid** |  |
# WorkflowSubscription Class

Namespace: Microsoft.SharePoint.Client.WorkflowServices

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **DefinitionId** | Guid |  |
| **Enabled** | bool |  |
| **EventSourceId** | Guid |  |
| **EventTypes** | IList\<string\> |  |
| **Id** | Guid |  |
| **ManualStartBypassesActivationLimit** | bool |  |
| **Name** | string |  |
| **ParentContentTypeId** | string |  |
| **PropertyDefinitions** | IDictionary\<string, string\> |  |
| **StatusFieldName** | string |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **WorkflowSubscription(ClientRuntimeContext context)** |  |
| **WorkflowSubscription(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetExternalVariable(string name)** | ClientResult\<string\> |  |
| **SetExternalVariable(string name, string value)** | void |  |
| **SetProperty(string name, string value)** | void |  |
# WorkflowSubscriptionCollection Class

Namespace: Microsoft.SharePoint.Client.WorkflowServices

Base class: ClientObjectCollection<[WorkflowSubscription](#workflowsubscription-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [WorkflowSubscription](#workflowsubscription-class) |  |
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
| **WorkflowSubscriptionCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Sort()** | void |  |
# WorkflowSubscriptionPropertyNames Class

Namespace: Microsoft.SharePoint.Client.WorkflowServices


## Fields

| Name | Type | Summary |
|---|---|---|
| **DefinitionId** | string |  |
| **Enabled** | string |  |
| **EventSourceId** | string |  |
| **EventTypes** | string |  |
| **Id** | string |  |
| **ManualStartBypassesActivationLimit** | string |  |
| **Name** | string |  |
| **ParentContentTypeId** | string |  |
| **PropertyDefinitions** | string |  |
| **StatusFieldName** | string |  |
# WorkflowSubscriptionService Class

Namespace: Microsoft.SharePoint.Client.WorkflowServices

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
| **WorkflowSubscriptionService(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteSubscription(Guid subscriptionId)** | void |  |
| **EnumerateSubscriptions()** | [WorkflowSubscriptionCollection](#workflowsubscriptioncollection-class) |  |
| **EnumerateSubscriptionsByDefinition(Guid definitionId)** | [WorkflowSubscriptionCollection](#workflowsubscriptioncollection-class) |  |
| **EnumerateSubscriptionsByEventSource(Guid eventSourceId)** | [WorkflowSubscriptionCollection](#workflowsubscriptioncollection-class) |  |
| **EnumerateSubscriptionsByList(Guid listId)** | [WorkflowSubscriptionCollection](#workflowsubscriptioncollection-class) |  |
| **EnumerateSubscriptionsByListAndParentContentType(Guid listId, ContentTypeId parentContentTypeId, bool includeNoContentTypeSpecified)** | [WorkflowSubscriptionCollection](#workflowsubscriptioncollection-class) |  |
| **EnumerateSubscriptionsByListWithContentType(Guid listId, bool includeContentTypeSpecified)** | [WorkflowSubscriptionCollection](#workflowsubscriptioncollection-class) |  |
| **GetCurrent(ClientRuntimeContext Context)** | [WorkflowSubscriptionService](#workflowsubscriptionservice-class) |  |
| **GetSubscription(Guid subscriptionId)** | [WorkflowSubscription](#workflowsubscription-class) |  |
| **PublishSubscription(WorkflowSubscription subscription)** | ClientResult\<Guid\> |  |
| **PublishSubscriptionForList(WorkflowSubscription subscription, Guid listId)** | ClientResult\<Guid\> |  |
| **RegisterInterestInHostWebList(Guid listId, string eventName)** | void |  |
| **RegisterInterestInList(Guid listId, string eventName)** | void |  |
| **UnregisterInterestInHostWebList(Guid listId, string eventName)** | void |  |
| **UnregisterInterestInList(Guid listId, string eventName)** | void |  |
# ScriptTypeFactory Class

Namespace: Microsoft.SharePoint.WorkflowServices


## Methods

| Name | Returns | Summary |
|---|---|---|
| **CreateObjectFromScriptType(string scriptType, ClientRuntimeContext context)** | IFromJson |  |
