# Microsoft.ProjectServer.Client.dll v.16.1.0.0 API documentation

Created by 
[mddox](https://github.com/loxsmoke/mddox) on 06/04/2023

# All types

|   |   |   |
|---|---|---|
| [AccrueAt Enum](#accrueat-enum) | [EventHandlerPropertyNames Class](#eventhandlerpropertynames-class) | [QueueJob Class](#queuejob-class) |
| [Assignment Class](#assignment-class) | [EventPropertyNames Class](#eventpropertynames-class) | [QueueJobCollection Class](#queuejobcollection-class) |
| [AssignmentCreationInformation Class](#assignmentcreationinformation-class) | [FixedCostAccrual Enum](#fixedcostaccrual-enum) | [QueueJobObjectPropertyNames Class](#queuejobobjectpropertynames-class) |
| [AssignmentObjectPropertyNames Class](#assignmentobjectpropertynames-class) | [JobState Enum](#jobstate-enum) | [QueueJobPropertyNames Class](#queuejobpropertynames-class) |
| [AssignmentPropertyNames Class](#assignmentpropertynames-class) | [LookupCost Class](#lookupcost-class) | [QueueMsgType Enum](#queuemsgtype-enum) |
| [BaseCalendarException Class](#basecalendarexception-class) | [LookupCostPropertyNames Class](#lookupcostpropertynames-class) | [ReadyToLeaveProjectStageValue Enum](#readytoleaveprojectstagevalue-enum) |
| [BookingType Enum](#bookingtype-enum) | [LookupDate Class](#lookupdate-class) | [ResourceCalendarException Class](#resourcecalendarexception-class) |
| [Calendar Class](#calendar-class) | [LookupDatePropertyNames Class](#lookupdatepropertynames-class) | [ResourceEngagement Class](#resourceengagement-class) |
| [CalendarCollection Class](#calendarcollection-class) | [LookupDuration Class](#lookupduration-class) | [ResourceEngagementCollection Class](#resourceengagementcollection-class) |
| [CalendarCreationInformation Class](#calendarcreationinformation-class) | [LookupDurationPropertyNames Class](#lookupdurationpropertynames-class) | [ResourceEngagementComment Class](#resourceengagementcomment-class) |
| [CalendarException Class](#calendarexception-class) | [LookupEntry Class](#lookupentry-class) | [ResourceEngagementPropertyNames Class](#resourceengagementpropertynames-class) |
| [CalendarExceptionCollection Class](#calendarexceptioncollection-class) | [LookupEntryCollection Class](#lookupentrycollection-class) | [ResourceEngagementTimephasedCollection Class](#resourceengagementtimephasedcollection-class) |
| [CalendarExceptionCreationInformation Class](#calendarexceptioncreationinformation-class) | [LookupEntryCreationInformation Class](#lookupentrycreationinformation-class) | [ResourceEngagementTimephasedPeriod Class](#resourceengagementtimephasedperiod-class) |
| [CalendarExceptionObjectPropertyNames Class](#calendarexceptionobjectpropertynames-class) | [LookupEntryPropertyNames Class](#lookupentrypropertynames-class) | [ResourcePlan Class](#resourceplan-class) |
| [CalendarExceptionPropertyNames Class](#calendarexceptionpropertynames-class) | [LookupEntryValue Class](#lookupentryvalue-class) | [ResourcePlanObjectPropertyNames Class](#resourceplanobjectpropertynames-class) |
| [CalendarObjectPropertyNames Class](#calendarobjectpropertynames-class) | [LookupMask Class](#lookupmask-class) | [ResourcePlanPropertyNames Class](#resourceplanpropertynames-class) |
| [CalendarPropertyNames Class](#calendarpropertynames-class) | [LookupNumber Class](#lookupnumber-class) | [ResourceType Enum](#resourcetype-enum) |
| [CalendarRecurrenceDays Enum](#calendarrecurrencedays-enum) | [LookupNumberPropertyNames Class](#lookupnumberpropertynames-class) | [ScriptTypeFactory Class](#scripttypefactory-class) |
| [CalendarRecurrenceType Enum](#calendarrecurrencetype-enum) | [LookupTable Class](#lookuptable-class) | [ServiceStatus Class](#servicestatus-class) |
| [CalendarRecurrenceWeek Enum](#calendarrecurrenceweek-enum) | [LookupTableCollection Class](#lookuptablecollection-class) | [ServiceStatusPropertyNames Class](#servicestatuspropertynames-class) |
| [CommittedDecisionResult Enum](#committeddecisionresult-enum) | [LookupTableConstants Enum](#lookuptableconstants-enum) | [Stage Class](#stage-class) |
| [ConstraintType Enum](#constrainttype-enum) | [LookupTableCreationInformation Class](#lookuptablecreationinformation-class) | [StageCollection Class](#stagecollection-class) |
| [CostRateCreationInformation Class](#costratecreationinformation-class) | [LookupTableMaskSequence Enum](#lookuptablemasksequence-enum) | [StageCreationInformation Class](#stagecreationinformation-class) |
| [CostRateTableName Enum](#costratetablename-enum) | [LookupTableObjectPropertyNames Class](#lookuptableobjectpropertynames-class) | [StageCustomField Class](#stagecustomfield-class) |
| [CurrencySymbolPosition Enum](#currencysymbolposition-enum) | [LookupTablePropertyNames Class](#lookuptablepropertynames-class) | [StageCustomFieldCollection Class](#stagecustomfieldcollection-class) |
| [CustomField Class](#customfield-class) | [LookupTables Class](#lookuptables-class) | [StageCustomFieldCreationInformation Class](#stagecustomfieldcreationinformation-class) |
| [CustomFieldCollection Class](#customfieldcollection-class) | [LookupTableSortOrder Enum](#lookuptablesortorder-enum) | [StageCustomFieldObjectPropertyNames Class](#stagecustomfieldobjectpropertynames-class) |
| [CustomFieldCreationInformation Class](#customfieldcreationinformation-class) | [LookupText Class](#lookuptext-class) | [StageCustomFieldPropertyNames Class](#stagecustomfieldpropertynames-class) |
| [CustomFieldObjectPropertyNames Class](#customfieldobjectpropertynames-class) | [LookupTextObjectPropertyNames Class](#lookuptextobjectpropertynames-class) | [StageDetailPage Class](#stagedetailpage-class) |
| [CustomFieldPropertyNames Class](#customfieldpropertynames-class) | [LookupTextPropertyNames Class](#lookuptextpropertynames-class) | [StageDetailPageCollection Class](#stagedetailpagecollection-class) |
| [CustomFieldRollupType Enum](#customfieldrolluptype-enum) | [OvertimeRateFormat Enum](#overtimerateformat-enum) | [StageDetailPageCreationInformation Class](#stagedetailpagecreationinformation-class) |
| [CustomFieldType Enum](#customfieldtype-enum) | [PageSizes Class](#pagesizes-class) | [StageDetailPageObjectPropertyNames Class](#stagedetailpageobjectpropertynames-class) |
| [DeletedPublishedAssignment Class](#deletedpublishedassignment-class) | [PageSizesPropertyNames Class](#pagesizespropertynames-class) | [StageDetailPagePropertyNames Class](#stagedetailpagepropertynames-class) |
| [DeletedPublishedAssignmentCollection Class](#deletedpublishedassignmentcollection-class) | [Phase Class](#phase-class) | [StageObjectPropertyNames Class](#stageobjectpropertynames-class) |
| [DeletedPublishedAssignmentPropertyNames Class](#deletedpublishedassignmentpropertynames-class) | [PhaseCollection Class](#phasecollection-class) | [StagePropertyNames Class](#stagepropertynames-class) |
| [DependencyType Enum](#dependencytype-enum) | [PhaseCreationInformation Class](#phasecreationinformation-class) | [StandardRateFormat Enum](#standardrateformat-enum) |
| [DraftAssignment Class](#draftassignment-class) | [PhaseObjectPropertyNames Class](#phaseobjectpropertynames-class) | [StatusApprovalType Enum](#statusapprovaltype-enum) |
| [DraftAssignmentCollection Class](#draftassignmentcollection-class) | [PhasePropertyNames Class](#phasepropertynames-class) | [StatusAssignment Class](#statusassignment-class) |
| [DraftAssignmentObjectPropertyNames Class](#draftassignmentobjectpropertynames-class) | [PlanAssignment Class](#planassignment-class) | [StatusAssignmentCollection Class](#statusassignmentcollection-class) |
| [DraftAssignmentPropertyNames Class](#draftassignmentpropertynames-class) | [PlanAssignmentCollection Class](#planassignmentcollection-class) | [StatusAssignmentCreationInformation Class](#statusassignmentcreationinformation-class) |
| [DraftProject Class](#draftproject-class) | [PlanAssignmentCreationInformation Class](#planassignmentcreationinformation-class) | [StatusAssignmentHistoryLine Class](#statusassignmenthistoryline-class) |
| [DraftProjectObjectPropertyNames Class](#draftprojectobjectpropertynames-class) | [PlanAssignmentInterval Class](#planassignmentinterval-class) | [StatusAssignmentHistoryLineCollection Class](#statusassignmenthistorylinecollection-class) |
| [DraftProjectPropertyNames Class](#draftprojectpropertynames-class) | [PlanAssignmentIntervalCollection Class](#planassignmentintervalcollection-class) | [StatusAssignmentHistoryLineObjectPropertyNames Class](#statusassignmenthistorylineobjectpropertynames-class) |
| [DraftProjectResource Class](#draftprojectresource-class) | [PlanAssignmentIntervalCreationInformation Class](#planassignmentintervalcreationinformation-class) | [StatusAssignmentHistoryLinePropertyNames Class](#statusassignmenthistorylinepropertynames-class) |
| [DraftProjectResourceCollection Class](#draftprojectresourcecollection-class) | [PlanAssignmentIntervalPropertyNames Class](#planassignmentintervalpropertynames-class) | [StatusAssignmentObjectPropertyNames Class](#statusassignmentobjectpropertynames-class) |
| [DraftProjectResourceObjectPropertyNames Class](#draftprojectresourceobjectpropertynames-class) | [PlanAssignmentObjectPropertyNames Class](#planassignmentobjectpropertynames-class) | [StatusAssignmentPropertyNames Class](#statusassignmentpropertynames-class) |
| [DraftProjectResourcePropertyNames Class](#draftprojectresourcepropertynames-class) | [PlanAssignmentPropertyNames Class](#planassignmentpropertynames-class) | [StatusTask Class](#statustask-class) |
| [DraftTask Class](#drafttask-class) | [Project Class](#project-class) | [StatusTaskCreationInformation Class](#statustaskcreationinformation-class) |
| [DraftTaskCollection Class](#drafttaskcollection-class) | [ProjectCollection Class](#projectcollection-class) | [StatusTaskObjectPropertyNames Class](#statustaskobjectpropertynames-class) |
| [DraftTaskLink Class](#drafttasklink-class) | [ProjectContext Class](#projectcontext-class) | [StatusTaskPropertyNames Class](#statustaskpropertynames-class) |
| [DraftTaskLinkCollection Class](#drafttasklinkcollection-class) | [ProjectCreationInformation Class](#projectcreationinformation-class) | [StatusUpdateType Enum](#statusupdatetype-enum) |
| [DraftTaskLinkObjectPropertyNames Class](#drafttasklinkobjectpropertynames-class) | [ProjectDetailPage Class](#projectdetailpage-class) | [StrategicImpactBehavior Enum](#strategicimpactbehavior-enum) |
| [DraftTaskLinkPropertyNames Class](#drafttasklinkpropertynames-class) | [ProjectDetailPageCollection Class](#projectdetailpagecollection-class) | [Task Class](#task-class) |
| [DraftTaskObjectPropertyNames Class](#drafttaskobjectpropertynames-class) | [ProjectDetailPageCollectionObjectPropertyNames Class](#projectdetailpagecollectionobjectpropertynames-class) | [TaskCreationInformation Class](#taskcreationinformation-class) |
| [DraftTaskPropertyNames Class](#drafttaskpropertynames-class) | [ProjectDetailPageCreationInformation Class](#projectdetailpagecreationinformation-class) | [TaskLink Class](#tasklink-class) |
| [Engagement Class](#engagement-class) | [ProjectDetailPageObjectPropertyNames Class](#projectdetailpageobjectpropertynames-class) | [TaskLinkCreationInformation Class](#tasklinkcreationinformation-class) |
| [EngagementComment Class](#engagementcomment-class) | [ProjectDetailPagePropertyNames Class](#projectdetailpagepropertynames-class) | [TaskLinkPropertyNames Class](#tasklinkpropertynames-class) |
| [EngagementCommentCollection Class](#engagementcommentcollection-class) | [ProjectDetailPageType Enum](#projectdetailpagetype-enum) | [TaskObjectPropertyNames Class](#taskobjectpropertynames-class) |
| [EngagementCommentObjectPropertyNames Class](#engagementcommentobjectpropertynames-class) | [ProjectEngagement Class](#projectengagement-class) | [TaskPropertyNames Class](#taskpropertynames-class) |
| [EngagementCommentPropertyNames Class](#engagementcommentpropertynames-class) | [ProjectEngagementCollection Class](#projectengagementcollection-class) | [TaskType Enum](#tasktype-enum) |
| [EngagementContourType Enum](#engagementcontourtype-enum) | [ProjectEngagementComment Class](#projectengagementcomment-class) | [TimePhase Class](#timephase-class) |
| [EngagementCreationInformation Class](#engagementcreationinformation-class) | [ProjectEngagementCreationInformation Class](#projectengagementcreationinformation-class) | [TimePhaseObjectPropertyNames Class](#timephaseobjectpropertynames-class) |
| [EngagementObjectPropertyNames Class](#engagementobjectpropertynames-class) | [ProjectEngagementPropertyNames Class](#projectengagementpropertynames-class) | [TimePhasePropertyNames Class](#timephasepropertynames-class) |
| [EngagementPropertyNames Class](#engagementpropertynames-class) | [ProjectEngagementTimephasedCollection Class](#projectengagementtimephasedcollection-class) | [TimeScale Enum](#timescale-enum) |
| [EngagementSaveConflictException Class](#engagementsaveconflictexception-class) | [ProjectEngagementTimephasedPeriod Class](#projectengagementtimephasedperiod-class) | [TimeSheet Class](#timesheet-class) |
| [EngagementStatus Enum](#engagementstatus-enum) | [ProjectObjectPropertyNames Class](#projectobjectpropertynames-class) | [TimeSheetEntryMode Enum](#timesheetentrymode-enum) |
| [EngagementTimephasedPeriod Class](#engagementtimephasedperiod-class) | [ProjectPropertyNames Class](#projectpropertynames-class) | [TimeSheetLine Class](#timesheetline-class) |
| [EngagementTimephasedPeriodCreationInformation Class](#engagementtimephasedperiodcreationinformation-class) | [ProjectResource Class](#projectresource-class) | [TimeSheetLineClass Enum](#timesheetlineclass-enum) |
| [EngagementTimephasedPeriodPropertyNames Class](#engagementtimephasedperiodpropertynames-class) | [ProjectResourceCreationInformation Class](#projectresourcecreationinformation-class) | [TimeSheetLineCollection Class](#timesheetlinecollection-class) |
| [EnterpriseProjectType Class](#enterpriseprojecttype-class) | [ProjectResourceObjectPropertyNames Class](#projectresourceobjectpropertynames-class) | [TimeSheetLineCreationInformation Class](#timesheetlinecreationinformation-class) |
| [EnterpriseProjectTypeCollection Class](#enterpriseprojecttypecollection-class) | [ProjectResourcePropertyNames Class](#projectresourcepropertynames-class) | [TimeSheetLineObjectPropertyNames Class](#timesheetlineobjectpropertynames-class) |
| [EnterpriseProjectTypeCreationInformation Class](#enterpriseprojecttypecreationinformation-class) | [ProjectServer Class](#projectserver-class) | [TimeSheetLinePropertyNames Class](#timesheetlinepropertynames-class) |
| [EnterpriseProjectTypeObjectPropertyNames Class](#enterpriseprojecttypeobjectpropertynames-class) | [ProjectServerData Class](#projectserverdata-class) | [TimeSheetLineStatus Enum](#timesheetlinestatus-enum) |
| [EnterpriseProjectTypePropertyNames Class](#enterpriseprojecttypepropertynames-class) | [ProjectServerObjectPropertyNames Class](#projectserverobjectpropertynames-class) | [TimeSheetObjectPropertyNames Class](#timesheetobjectpropertynames-class) |
| [EnterpriseProjectTypeSiteCreationOptions Enum](#enterpriseprojecttypesitecreationoptions-enum) | [ProjectServerPropertyNames Class](#projectserverpropertynames-class) | [TimeSheetPeriod Class](#timesheetperiod-class) |
| [EnterpriseResource Class](#enterpriseresource-class) | [ProjectSummaryTask Class](#projectsummarytask-class) | [TimeSheetPeriodCollection Class](#timesheetperiodcollection-class) |
| [EnterpriseResourceCollection Class](#enterpriseresourcecollection-class) | [ProjectSummaryTaskPropertyNames Class](#projectsummarytaskpropertynames-class) | [TimeSheetPeriodObjectPropertyNames Class](#timesheetperiodobjectpropertynames-class) |
| [EnterpriseResourceCostRate Class](#enterpriseresourcecostrate-class) | [ProjectType Enum](#projecttype-enum) | [TimeSheetPeriodPropertyNames Class](#timesheetperiodpropertynames-class) |
| [EnterpriseResourceCostRateCollection Class](#enterpriseresourcecostratecollection-class) | [ProjectUtilizationType Enum](#projectutilizationtype-enum) | [TimeSheetPropertyNames Class](#timesheetpropertynames-class) |
| [EnterpriseResourceCostRatePropertyNames Class](#enterpriseresourcecostratepropertynames-class) | [PublishedAssignment Class](#publishedassignment-class) | [TimeSheetStatus Enum](#timesheetstatus-enum) |
| [EnterpriseResourceCostRateTable Class](#enterpriseresourcecostratetable-class) | [PublishedAssignmentCollection Class](#publishedassignmentcollection-class) | [TimeSheetValidationType Enum](#timesheetvalidationtype-enum) |
| [EnterpriseResourceCostRateTableCollection Class](#enterpriseresourcecostratetablecollection-class) | [PublishedAssignmentObjectPropertyNames Class](#publishedassignmentobjectpropertynames-class) | [TimeSheetWork Class](#timesheetwork-class) |
| [EnterpriseResourceCostRateTableObjectPropertyNames Class](#enterpriseresourcecostratetableobjectpropertynames-class) | [PublishedAssignmentPropertyNames Class](#publishedassignmentpropertynames-class) | [TimeSheetWorkCollection Class](#timesheetworkcollection-class) |
| [EnterpriseResourceCostRateTablePropertyNames Class](#enterpriseresourcecostratetablepropertynames-class) | [PublishedProject Class](#publishedproject-class) | [TimeSheetWorkCreationInformation Class](#timesheetworkcreationinformation-class) |
| [EnterpriseResourceCreationInformation Class](#enterpriseresourcecreationinformation-class) | [PublishedProjectObjectPropertyNames Class](#publishedprojectobjectpropertynames-class) | [TimeSheetWorkPropertyNames Class](#timesheetworkpropertynames-class) |
| [EnterpriseResourceObjectPropertyNames Class](#enterpriseresourceobjectpropertynames-class) | [PublishedProjectPropertyNames Class](#publishedprojectpropertynames-class) | [TrackingMode Enum](#trackingmode-enum) |
| [EnterpriseResourcePropertyNames Class](#enterpriseresourcepropertynames-class) | [PublishedProjectResource Class](#publishedprojectresource-class) | [UpdateProjectStageStatusFieldValue Enum](#updateprojectstagestatusfieldvalue-enum) |
| [EnterpriseResourceType Enum](#enterpriseresourcetype-enum) | [PublishedProjectResourceCollection Class](#publishedprojectresourcecollection-class) | [UtilizationType Enum](#utilizationtype-enum) |
| [EntityType Class](#entitytype-class) | [PublishedProjectResourceObjectPropertyNames Class](#publishedprojectresourceobjectpropertynames-class) | [WorkContourType Enum](#workcontourtype-enum) |
| [EntityTypePropertyNames Class](#entitytypepropertynames-class) | [PublishedProjectResourcePropertyNames Class](#publishedprojectresourcepropertynames-class) | [WorkflowActivities Class](#workflowactivities-class) |
| [EntityTypes Class](#entitytypes-class) | [PublishedTask Class](#publishedtask-class) | [WorkflowDesigner Class](#workflowdesigner-class) |
| [EntityTypesObjectPropertyNames Class](#entitytypesobjectpropertynames-class) | [PublishedTaskCollection Class](#publishedtaskcollection-class) | [WorkflowDesignerField Class](#workflowdesignerfield-class) |
| [Event Class](#event-class) | [PublishedTaskLink Class](#publishedtasklink-class) | [WorkflowDesignerFieldCollection Class](#workflowdesignerfieldcollection-class) |
| [EventCollection Class](#eventcollection-class) | [PublishedTaskLinkCollection Class](#publishedtasklinkcollection-class) | [WorkflowDesignerFieldObjectPropertyNames Class](#workflowdesignerfieldobjectpropertynames-class) |
| [EventHandler Class](#eventhandler-class) | [PublishedTaskLinkObjectPropertyNames Class](#publishedtasklinkobjectpropertynames-class) | [WorkflowDesignerFieldPropertyNames Class](#workflowdesignerfieldpropertynames-class) |
| [EventHandlerCollection Class](#eventhandlercollection-class) | [PublishedTaskLinkPropertyNames Class](#publishedtasklinkpropertynames-class) | [WorkflowDesignerObjectPropertyNames Class](#workflowdesignerobjectpropertynames-class) |
| [EventHandlerCreationInformation Class](#eventhandlercreationinformation-class) | [PublishedTaskObjectPropertyNames Class](#publishedtaskobjectpropertynames-class) | [WorkFormat Enum](#workformat-enum) |
| [EventHandlerObjectPropertyNames Class](#eventhandlerobjectpropertynames-class) | [PublishedTaskPropertyNames Class](#publishedtaskpropertynames-class) |   |
# AccrueAt Enum

Namespace: Microsoft.ProjectServer.Client


## Values

| Name | Summary |
|---|---|
| **NotSpecified** |  |
| **Start** |  |
| **End** |  |
| **Prorated** |  |
# Assignment Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ActualCostWorkPerformed** | double |  |
| **ActualOvertimeCost** | double |  |
| **BaselineCost** | double |  |
| **BaselineCostPerUse** | double |  |
| **BaselineFinish** | DateTime |  |
| **BaselineStart** | DateTime |  |
| **BaselineWork** | string |  |
| **BaselineWorkTimeSpan** | TimeSpan |  |
| **BudgetedCostWorkPerformed** | double |  |
| **BudgetedCostWorkScheduled** | double |  |
| **CostVariance** | double |  |
| **CostVarianceAtCompletion** | double |  |
| **Created** | DateTime |  |
| **CurrentCostVariance** | double |  |
| **CustomFields** | [CustomFieldCollection](#customfieldcollection-class) |  |
| **Finish** | DateTime |  |
| **FinishVariance** | string |  |
| **FinishVarianceTimeSpan** | TimeSpan |  |
| **Id** | Guid |  |
| **IsConfirmed** | bool |  |
| **IsOverAllocated** | bool |  |
| **IsPublished** | bool |  |
| **IsResponsePending** | bool |  |
| **IsUpdateNeeded** | bool |  |
| **LevelingDelay** | string |  |
| **LevelingDelayTimeSpan** | TimeSpan |  |
| **Modified** | DateTime |  |
| **Notes** | string |  |
| **OvertimeCost** | double |  |
| **RemainingCost** | double |  |
| **RemainingOvertimeCost** | double |  |
| **Resume** | DateTime |  |
| **ScheduleCostVariance** | double |  |
| **Start** | DateTime |  |
| **StartVariance** | string |  |
| **StartVarianceTimeSpan** | TimeSpan |  |
| **Stop** | DateTime |  |
| **WorkContourType** | [WorkContourType](#workcontourtype-enum) |  |
| **WorkVariance** | string |  |
| **WorkVarianceTimeSpan** | TimeSpan |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **Assignment(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# AssignmentCreationInformation Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Finish** | DateTime |  |
| **Id** | Guid |  |
| **Notes** | string |  |
| **ResourceId** | Guid |  |
| **Start** | DateTime |  |
| **TaskId** | Guid |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# AssignmentObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **CustomFields** | string |  |
# AssignmentPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **ActualCostWorkPerformed** | string |  |
| **ActualOvertimeCost** | string |  |
| **BaselineCost** | string |  |
| **BaselineCostPerUse** | string |  |
| **BaselineFinish** | string |  |
| **BaselineStart** | string |  |
| **BaselineWork** | string |  |
| **BaselineWorkTimeSpan** | string |  |
| **BudgetedCostWorkPerformed** | string |  |
| **BudgetedCostWorkScheduled** | string |  |
| **CostVariance** | string |  |
| **CostVarianceAtCompletion** | string |  |
| **Created** | string |  |
| **CurrentCostVariance** | string |  |
| **Finish** | string |  |
| **FinishVariance** | string |  |
| **FinishVarianceTimeSpan** | string |  |
| **Id** | string |  |
| **IsConfirmed** | string |  |
| **IsOverAllocated** | string |  |
| **IsPublished** | string |  |
| **IsResponsePending** | string |  |
| **IsUpdateNeeded** | string |  |
| **LevelingDelay** | string |  |
| **LevelingDelayTimeSpan** | string |  |
| **Modified** | string |  |
| **Notes** | string |  |
| **OvertimeCost** | string |  |
| **RemainingCost** | string |  |
| **RemainingOvertimeCost** | string |  |
| **Resume** | string |  |
| **ScheduleCostVariance** | string |  |
| **Start** | string |  |
| **StartVariance** | string |  |
| **StartVarianceTimeSpan** | string |  |
| **Stop** | string |  |
| **WorkContourType** | string |  |
| **WorkVariance** | string |  |
| **WorkVarianceTimeSpan** | string |  |
# BaseCalendarException Class

Namespace: Microsoft.ProjectServer.Client

Base class: [CalendarException](#calendarexception-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **Calendar** | [Calendar](#calendar-class) |  |
| **Finish** | DateTime |  |
| **Id** | int |  |
| **Name** | string |  |
| **RecurrenceDays** | [CalendarRecurrenceDays](#calendarrecurrencedays-enum) |  |
| **RecurrenceFrequency** | int |  |
| **RecurrenceMonth** | int |  |
| **RecurrenceMonthDay** | int |  |
| **RecurrenceType** | [CalendarRecurrenceType](#calendarrecurrencetype-enum) |  |
| **RecurrenceWeek** | [CalendarRecurrenceWeek](#calendarrecurrenceweek-enum) |  |
| **Shift1Finish** | int |  |
| **Shift1Start** | int |  |
| **Shift2Finish** | int |  |
| **Shift2Start** | int |  |
| **Shift3Finish** | int |  |
| **Shift3Start** | int |  |
| **Shift4Finish** | int |  |
| **Shift4Start** | int |  |
| **Shift5Finish** | int |  |
| **Shift5Start** | int |  |
| **Start** | DateTime |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **BaseCalendarException(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# BookingType Enum

Namespace: Microsoft.ProjectServer.Client


## Values

| Name | Summary |
|---|---|
| **NotSpecified** |  |
| **Committed** |  |
| **Proposed** |  |
# Calendar Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **BaseCalendarExceptions** | [CalendarExceptionCollection](#calendarexceptioncollection-class) |  |
| **Created** | DateTime |  |
| **Id** | Guid |  |
| **IsStandardCalendar** | bool |  |
| **Modified** | DateTime |  |
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
| **Calendar(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **CopyTo(string name)** | [Calendar](#calendar-class) |  |
| **DeleteObject()** | void |  |
# CalendarCollection Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObjectCollection<[Calendar](#calendar-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [Calendar](#calendar-class) |  |
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
| **CalendarCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(CalendarCreationInformation parameters)** | [Calendar](#calendar-class) |  |
| **GetByGuid(Guid uid)** | [Calendar](#calendar-class) |  |
| **GetById(string objectId)** | [Calendar](#calendar-class) |  |
| **Remove(Calendar calendar)** | ClientResult\<bool\> |  |
| **Update()** | void |  |
# CalendarCreationInformation Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Id** | Guid |  |
| **Name** | string |  |
| **OriginalId** | Guid |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# CalendarException Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Calendar** | [Calendar](#calendar-class) |  |
| **Finish** | DateTime |  |
| **Id** | int |  |
| **Name** | string |  |
| **RecurrenceDays** | [CalendarRecurrenceDays](#calendarrecurrencedays-enum) |  |
| **RecurrenceFrequency** | int |  |
| **RecurrenceMonth** | int |  |
| **RecurrenceMonthDay** | int |  |
| **RecurrenceType** | [CalendarRecurrenceType](#calendarrecurrencetype-enum) |  |
| **RecurrenceWeek** | [CalendarRecurrenceWeek](#calendarrecurrenceweek-enum) |  |
| **Shift1Finish** | int |  |
| **Shift1Start** | int |  |
| **Shift2Finish** | int |  |
| **Shift2Start** | int |  |
| **Shift3Finish** | int |  |
| **Shift3Start** | int |  |
| **Shift4Finish** | int |  |
| **Shift4Start** | int |  |
| **Shift5Finish** | int |  |
| **Shift5Start** | int |  |
| **Start** | DateTime |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **CalendarException(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
# CalendarExceptionCollection Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObjectCollection<[CalendarException](#calendarexception-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [CalendarException](#calendarexception-class) |  |
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
| **CalendarExceptionCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(CalendarExceptionCreationInformation parameters)** | [CalendarException](#calendarexception-class) |  |
| **GetById(int id)** | [CalendarException](#calendarexception-class) |  |
| **Remove(CalendarException exception)** | ClientResult\<bool\> |  |
# CalendarExceptionCreationInformation Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Finish** | DateTime |  |
| **Name** | string |  |
| **RecurrenceDays** | [CalendarRecurrenceDays](#calendarrecurrencedays-enum) |  |
| **RecurrenceFrequency** | int |  |
| **RecurrenceMonth** | int |  |
| **RecurrenceMonthDay** | int |  |
| **RecurrenceType** | [CalendarRecurrenceType](#calendarrecurrencetype-enum) |  |
| **RecurrenceWeek** | [CalendarRecurrenceWeek](#calendarrecurrenceweek-enum) |  |
| **Shift1Finish** | int |  |
| **Shift1Start** | int |  |
| **Shift2Finish** | int |  |
| **Shift2Start** | int |  |
| **Shift3Finish** | int |  |
| **Shift3Start** | int |  |
| **Shift4Finish** | int |  |
| **Shift4Start** | int |  |
| **Shift5Finish** | int |  |
| **Shift5Start** | int |  |
| **Start** | DateTime |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# CalendarExceptionObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Calendar** | string |  |
# CalendarExceptionPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Finish** | string |  |
| **Id** | string |  |
| **Name** | string |  |
| **RecurrenceDays** | string |  |
| **RecurrenceFrequency** | string |  |
| **RecurrenceMonth** | string |  |
| **RecurrenceMonthDay** | string |  |
| **RecurrenceType** | string |  |
| **RecurrenceWeek** | string |  |
| **Shift1Finish** | string |  |
| **Shift1Start** | string |  |
| **Shift2Finish** | string |  |
| **Shift2Start** | string |  |
| **Shift3Finish** | string |  |
| **Shift3Start** | string |  |
| **Shift4Finish** | string |  |
| **Shift4Start** | string |  |
| **Shift5Finish** | string |  |
| **Shift5Start** | string |  |
| **Start** | string |  |
# CalendarObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **BaseCalendarExceptions** | string |  |
# CalendarPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Created** | string |  |
| **Id** | string |  |
| **IsStandardCalendar** | string |  |
| **Modified** | string |  |
| **Name** | string |  |
# CalendarRecurrenceDays Enum

Namespace: Microsoft.ProjectServer.Client


## Values

| Name | Summary |
|---|---|
| **NotSpecified** |  |
| **Sunday** |  |
| **Monday** |  |
| **Tuesday** |  |
| **Wednesday** |  |
| **Thursday** |  |
| **Friday** |  |
| **Saturday** |  |
# CalendarRecurrenceType Enum

Namespace: Microsoft.ProjectServer.Client


## Values

| Name | Summary |
|---|---|
| **Daily** |  |
| **DailySkip** |  |
| **Weekly** |  |
| **Monthly** |  |
| **Yearly** |  |
# CalendarRecurrenceWeek Enum

Namespace: Microsoft.ProjectServer.Client


## Values

| Name | Summary |
|---|---|
| **NotSpecified** |  |
| **First** |  |
| **Second** |  |
| **Third** |  |
| **Fourth** |  |
| **Last** |  |
# CommittedDecisionResult Enum

Namespace: Microsoft.ProjectServer.Client


## Values

| Name | Summary |
|---|---|
| **NotSpecified** |  |
| **ForcedIn** |  |
| **ForcedOut** |  |
| **CommittedOut** |  |
| **CommittedIn** |  |
# ConstraintType Enum

Namespace: Microsoft.ProjectServer.Client


## Values

| Name | Summary |
|---|---|
| **NotSpecified** |  |
| **AsSoonAsPossible** |  |
| **AsLateAsPossible** |  |
| **MustStartOn** |  |
| **MustFinishOn** |  |
| **StartNoEarlierThan** |  |
| **StartNoLaterThan** |  |
| **FinishNoEarlierThan** |  |
| **FinishNoLaterThan** |  |
# CostRateCreationInformation Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **CostPerUse** | double |  |
| **EffectiveDate** | DateTime |  |
| **OvertimeRate** | double |  |
| **StandardRate** | double |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# CostRateTableName Enum

Namespace: Microsoft.ProjectServer.Client


## Values

| Name | Summary |
|---|---|
| **A** |  |
| **B** |  |
| **C** |  |
| **D** |  |
| **E** |  |
# CurrencySymbolPosition Enum

Namespace: Microsoft.ProjectServer.Client


## Values

| Name | Summary |
|---|---|
| **NotSpecified** |  |
| **Before** |  |
| **After** |  |
| **BeforeWithSpace** |  |
| **AfterWithSpace** |  |
# CustomField Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AppAlternateId** | Guid |  |
| **Description** | string |  |
| **EntityType** | [EntityType](#entitytype-class) |  |
| **FieldType** | [CustomFieldType](#customfieldtype-enum) |  |
| **Formula** | string |  |
| **Id** | Guid |  |
| **InternalName** | string |  |
| **IsEditableInVisibility** | bool |  |
| **IsMultilineText** | bool |  |
| **IsRequired** | bool |  |
| **IsWorkflowControlled** | bool |  |
| **LookupAllowMultiSelect** | bool |  |
| **LookupDefaultValue** | Guid |  |
| **LookupEntries** | [LookupEntryCollection](#lookupentrycollection-class) |  |
| **LookupTable** | [LookupTable](#lookuptable-class) |  |
| **Name** | string |  |
| **RollsDownToAssignments** | bool |  |
| **RollupType** | [CustomFieldRollupType](#customfieldrolluptype-enum) |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **CustomField(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
# CustomFieldCollection Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObjectCollection<[CustomField](#customfield-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [CustomField](#customfield-class) |  |
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
| **CustomFieldCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(CustomFieldCreationInformation parameters)** | [CustomField](#customfield-class) |  |
| **GetByAppAlternateId(string objectId)** | [CustomField](#customfield-class) |  |
| **GetByGuid(Guid uid)** | [CustomField](#customfield-class) |  |
| **GetById(string objectId)** | [CustomField](#customfield-class) |  |
| **Remove(CustomField field)** | ClientResult\<bool\> |  |
| **Update()** | void |  |
# CustomFieldCreationInformation Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Description** | string |  |
| **EntityType** | [EntityType](#entitytype-class) |  |
| **FieldType** | [CustomFieldType](#customfieldtype-enum) |  |
| **Formula** | string |  |
| **Id** | Guid |  |
| **IsEditableInVisibility** | bool |  |
| **IsMultilineText** | bool |  |
| **IsRequired** | bool |  |
| **IsWorkflowControlled** | bool |  |
| **LookupAllowMultiSelect** | bool |  |
| **LookupDefaultValue** | Guid |  |
| **LookupTable** | [LookupTable](#lookuptable-class) |  |
| **Name** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# CustomFieldObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **EntityType** | string |  |
| **LookupEntries** | string |  |
| **LookupTable** | string |  |
# CustomFieldPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **AppAlternateId** | string |  |
| **Description** | string |  |
| **FieldType** | string |  |
| **Formula** | string |  |
| **Id** | string |  |
| **InternalName** | string |  |
| **IsEditableInVisibility** | string |  |
| **IsMultilineText** | string |  |
| **IsRequired** | string |  |
| **IsWorkflowControlled** | string |  |
| **LookupAllowMultiSelect** | string |  |
| **LookupDefaultValue** | string |  |
| **Name** | string |  |
| **RollsDownToAssignments** | string |  |
| **RollupType** | string |  |
# CustomFieldRollupType Enum

Namespace: Microsoft.ProjectServer.Client


## Values

| Name | Summary |
|---|---|
| **NotSpecified** |  |
| **Max** |  |
| **Min** |  |
| **Count** |  |
| **Sum** |  |
| **Average** |  |
| **AverageSublevel** |  |
| **CountSublevel** |  |
| **CountNonSummary** |  |
| **StdDev** |  |
| **Formula** |  |
| **None** |  |
# CustomFieldType Enum

Namespace: Microsoft.ProjectServer.Client


## Values

| Name | Summary |
|---|---|
| **DATE** |  |
| **DURATION** |  |
| **COST** |  |
| **NUMBER** |  |
| **FLAG** |  |
| **TEXT** |  |
| **FINISHDATE** |  |
# DeletedPublishedAssignment Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **DeletedDate** | DateTime |  |
| **Id** | Guid |  |
| **ProjectId** | Guid |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **DeletedPublishedAssignment(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# DeletedPublishedAssignmentCollection Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObjectCollection<[DeletedPublishedAssignment](#deletedpublishedassignment-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [DeletedPublishedAssignment](#deletedpublishedassignment-class) |  |
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
| **DeletedPublishedAssignmentCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# DeletedPublishedAssignmentPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **DeletedDate** | string |  |
| **Id** | string |  |
| **ProjectId** | string |  |
# DependencyType Enum

Namespace: Microsoft.ProjectServer.Client


## Values

| Name | Summary |
|---|---|
| **FinishFinish** |  |
| **FinishStart** |  |
| **StartFinish** |  |
| **StartStart** |  |
# DraftAssignment Class

Namespace: Microsoft.ProjectServer.Client

Base class: [Assignment](#assignment-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **FieldValues** | Dictionary\<string, Object\> |  |
| **Item** | Object |  |
| **ActualCost** | double |  |
| **ActualFinish** | DateTime |  |
| **ActualOvertimeWork** | string |  |
| **ActualOvertimeWorkTimeSpan** | TimeSpan |  |
| **ActualStart** | DateTime |  |
| **ActualWork** | string |  |
| **ActualWorkTimeSpan** | TimeSpan |  |
| **BudgetedCost** | double |  |
| **BudgetedWork** | string |  |
| **BudgetedWorkTimeSpan** | TimeSpan |  |
| **Cost** | double |  |
| **CostRateTable** | [CostRateTableName](#costratetablename-enum) |  |
| **DefaultBookingType** | [BookingType](#bookingtype-enum) |  |
| **Delay** | string |  |
| **DelayTimeSpan** | TimeSpan |  |
| **IsLockedByManager** | bool |  |
| **IsWorkResource** | bool |  |
| **OvertimeWork** | string |  |
| **OvertimeWorkTimeSpan** | TimeSpan |  |
| **Owner** | User |  |
| **Parent** | [DraftAssignment](#draftassignment-class) |  |
| **PercentWorkComplete** | int |  |
| **RegularWork** | string |  |
| **RegularWorkTimeSpan** | TimeSpan |  |
| **RemainingOvertimeWork** | string |  |
| **RemainingOvertimeWorkTimeSpan** | TimeSpan |  |
| **RemainingWork** | string |  |
| **RemainingWorkTimeSpan** | TimeSpan |  |
| **Resource** | [DraftProjectResource](#draftprojectresource-class) |  |
| **ResourceCapacity** | double |  |
| **Task** | [DraftTask](#drafttask-class) |  |
| **Work** | string |  |
| **WorkTimeSpan** | TimeSpan |  |
| **ActualCostWorkPerformed** | double |  |
| **ActualOvertimeCost** | double |  |
| **BaselineCost** | double |  |
| **BaselineCostPerUse** | double |  |
| **BaselineFinish** | DateTime |  |
| **BaselineStart** | DateTime |  |
| **BaselineWork** | string |  |
| **BaselineWorkTimeSpan** | TimeSpan |  |
| **BudgetedCostWorkPerformed** | double |  |
| **BudgetedCostWorkScheduled** | double |  |
| **CostVariance** | double |  |
| **CostVarianceAtCompletion** | double |  |
| **Created** | DateTime |  |
| **CurrentCostVariance** | double |  |
| **CustomFields** | [CustomFieldCollection](#customfieldcollection-class) |  |
| **Finish** | DateTime |  |
| **FinishVariance** | string |  |
| **FinishVarianceTimeSpan** | TimeSpan |  |
| **Id** | Guid |  |
| **IsConfirmed** | bool |  |
| **IsOverAllocated** | bool |  |
| **IsPublished** | bool |  |
| **IsResponsePending** | bool |  |
| **IsUpdateNeeded** | bool |  |
| **LevelingDelay** | string |  |
| **LevelingDelayTimeSpan** | TimeSpan |  |
| **Modified** | DateTime |  |
| **Notes** | string |  |
| **OvertimeCost** | double |  |
| **RemainingCost** | double |  |
| **RemainingOvertimeCost** | double |  |
| **Resume** | DateTime |  |
| **ScheduleCostVariance** | double |  |
| **Start** | DateTime |  |
| **StartVariance** | string |  |
| **StartVarianceTimeSpan** | TimeSpan |  |
| **Stop** | DateTime |  |
| **WorkContourType** | [WorkContourType](#workcontourtype-enum) |  |
| **WorkVariance** | string |  |
| **WorkVarianceTimeSpan** | TimeSpan |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **DraftAssignment(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
| **RefreshLoad()** | void |  |
# DraftAssignmentCollection Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObjectCollection<[DraftAssignment](#draftassignment-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [DraftAssignment](#draftassignment-class) |  |
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
| **DraftAssignmentCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(AssignmentCreationInformation parameters)** | [DraftAssignment](#draftassignment-class) |  |
| **GetByGuid(Guid uid)** | [DraftAssignment](#draftassignment-class) |  |
| **GetById(string objectId)** | [DraftAssignment](#draftassignment-class) |  |
| **Remove(DraftAssignment assignment)** | ClientResult\<bool\> |  |
# DraftAssignmentObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Owner** | string |  |
| **Parent** | string |  |
| **Resource** | string |  |
| **Task** | string |  |
# DraftAssignmentPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **ActualCost** | string |  |
| **ActualFinish** | string |  |
| **ActualOvertimeWork** | string |  |
| **ActualOvertimeWorkTimeSpan** | string |  |
| **ActualStart** | string |  |
| **ActualWork** | string |  |
| **ActualWorkTimeSpan** | string |  |
| **BudgetedCost** | string |  |
| **BudgetedWork** | string |  |
| **BudgetedWorkTimeSpan** | string |  |
| **Cost** | string |  |
| **CostRateTable** | string |  |
| **DefaultBookingType** | string |  |
| **Delay** | string |  |
| **DelayTimeSpan** | string |  |
| **IsLockedByManager** | string |  |
| **IsWorkResource** | string |  |
| **OvertimeWork** | string |  |
| **OvertimeWorkTimeSpan** | string |  |
| **PercentWorkComplete** | string |  |
| **RegularWork** | string |  |
| **RegularWorkTimeSpan** | string |  |
| **RemainingOvertimeWork** | string |  |
| **RemainingOvertimeWorkTimeSpan** | string |  |
| **RemainingWork** | string |  |
| **RemainingWorkTimeSpan** | string |  |
| **ResourceCapacity** | string |  |
| **Work** | string |  |
| **WorkTimeSpan** | string |  |
# DraftProject Class

Namespace: Microsoft.ProjectServer.Client

Base class: [Project](#project-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **FieldValues** | Dictionary\<string, Object\> |  |
| **Item** | Object |  |
| **Assignments** | [DraftAssignmentCollection](#draftassignmentcollection-class) |  |
| **Calendar** | [Calendar](#calendar-class) |  |
| **CurrencyCode** | string |  |
| **CurrencyDigits** | int |  |
| **CurrencyPosition** | [CurrencySymbolPosition](#currencysymbolposition-enum) |  |
| **CurrencySymbol** | string |  |
| **CurrentDate** | DateTime |  |
| **DaysPerMonth** | short |  |
| **DefaultEffortDriven** | bool |  |
| **DefaultEstimatedDuration** | bool |  |
| **DefaultFixedCostAccrual** | [FixedCostAccrual](#fixedcostaccrual-enum) |  |
| **DefaultOvertimeRate** | double |  |
| **DefaultStandardRate** | double |  |
| **DefaultTaskType** | [TaskType](#tasktype-enum) |  |
| **DefaultWorkFormat** | [WorkFormat](#workformat-enum) |  |
| **Description** | string |  |
| **FinishDate** | DateTime |  |
| **FiscalYearStartMonth** | short |  |
| **IncludeCustomFields** | [DraftProject](#draftproject-class) |  |
| **MinutesPerDay** | int |  |
| **MinutesPerWeek** | int |  |
| **Name** | string |  |
| **NewTasksAreManual** | bool |  |
| **NumberFiscalYearFromStart** | bool |  |
| **Owner** | User |  |
| **ProjectIdentifier** | string |  |
| **ProjectResources** | [DraftProjectResourceCollection](#draftprojectresourcecollection-class) |  |
| **ProtectedActualsSynch** | bool |  |
| **ShowEstimatedDurations** | bool |  |
| **StartDate** | DateTime |  |
| **StatusDate** | DateTime |  |
| **TaskLinks** | [DraftTaskLinkCollection](#drafttasklinkcollection-class) |  |
| **Tasks** | [DraftTaskCollection](#drafttaskcollection-class) |  |
| **TrackingMode** | [TrackingMode](#trackingmode-enum) |  |
| **UtilizationDate** | DateTime |  |
| **UtilizationType** | [ProjectUtilizationType](#projectutilizationtype-enum) |  |
| **WeekStartDay** | short |  |
| **WinprojVersion** | decimal |  |
| **ApprovedEnd** | DateTime |  |
| **ApprovedStart** | DateTime |  |
| **CalculateActualCosts** | bool |  |
| **CalculatesActualCosts** | bool |  |
| **CheckedOutBy** | User |  |
| **CheckedOutDate** | DateTime |  |
| **CheckOutDescription** | string |  |
| **CheckOutId** | Guid |  |
| **CreatedDate** | DateTime |  |
| **CriticalSlackLimit** | int |  |
| **CustomFields** | [CustomFieldCollection](#customfieldcollection-class) |  |
| **DefaultFinishTime** | DateTime |  |
| **DefaultOvertimeRateUnits** | [OvertimeRateFormat](#overtimerateformat-enum) |  |
| **DefaultStandardRateUnits** | [StandardRateFormat](#standardrateformat-enum) |  |
| **DefaultStartTime** | DateTime |  |
| **Engagements** | [ProjectEngagementCollection](#projectengagementcollection-class) |  |
| **EnterpriseProjectType** | [EnterpriseProjectType](#enterpriseprojecttype-class) |  |
| **HasMppPendingImport** | bool |  |
| **HonorConstraints** | bool |  |
| **Id** | Guid |  |
| **IsCheckedOut** | bool |  |
| **LastPublishedDate** | DateTime |  |
| **LastSavedDate** | DateTime |  |
| **MoveActualIfLater** | bool |  |
| **MoveActualToStatus** | bool |  |
| **MoveRemainingIfEarlier** | bool |  |
| **MoveRemainingToStatus** | bool |  |
| **MultipleCriticalPaths** | bool |  |
| **OptimizerDecision** | [CommittedDecisionResult](#committeddecisionresult-enum) |  |
| **PercentComplete** | int |  |
| **Phase** | [Phase](#phase-class) |  |
| **PlannerDecision** | [CommittedDecisionResult](#committeddecisionresult-enum) |  |
| **ProjectSiteUrl** | string |  |
| **ProjectSummaryTask** | [ProjectSummaryTask](#projectsummarytask-class) |  |
| **ProjectType** | [ProjectType](#projecttype-enum) |  |
| **QueueJobs** | [QueueJobCollection](#queuejobcollection-class) |  |
| **ScheduledFromStart** | bool |  |
| **SplitInProgress** | bool |  |
| **SpreadActualCostsToStatus** | bool |  |
| **SpreadPercentCompleteToStatus** | bool |  |
| **Stage** | [Stage](#stage-class) |  |
| **SummaryTaskId** | Guid |  |
| **TaskListId** | Guid |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **DraftProject(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **CheckIn(bool force)** | [QueueJob](#queuejob-class) |  |
| **Publish(bool checkIn)** | [QueueJob](#queuejob-class) |  |
| **RefreshLoad()** | void |  |
| **Update()** | [QueueJob](#queuejob-class) |  |
| **Validate()** | void |  |
# DraftProjectObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Assignments** | string |  |
| **Calendar** | string |  |
| **IncludeCustomFields** | string |  |
| **Owner** | string |  |
| **ProjectResources** | string |  |
| **TaskLinks** | string |  |
| **Tasks** | string |  |
# DraftProjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **CurrencyCode** | string |  |
| **CurrencyDigits** | string |  |
| **CurrencyPosition** | string |  |
| **CurrencySymbol** | string |  |
| **CurrentDate** | string |  |
| **DaysPerMonth** | string |  |
| **DefaultEffortDriven** | string |  |
| **DefaultEstimatedDuration** | string |  |
| **DefaultFixedCostAccrual** | string |  |
| **DefaultOvertimeRate** | string |  |
| **DefaultStandardRate** | string |  |
| **DefaultTaskType** | string |  |
| **DefaultWorkFormat** | string |  |
| **Description** | string |  |
| **FinishDate** | string |  |
| **FiscalYearStartMonth** | string |  |
| **MinutesPerDay** | string |  |
| **MinutesPerWeek** | string |  |
| **Name** | string |  |
| **NewTasksAreManual** | string |  |
| **NumberFiscalYearFromStart** | string |  |
| **ProjectIdentifier** | string |  |
| **ProtectedActualsSynch** | string |  |
| **ShowEstimatedDurations** | string |  |
| **StartDate** | string |  |
| **StatusDate** | string |  |
| **TrackingMode** | string |  |
| **UtilizationDate** | string |  |
| **UtilizationType** | string |  |
| **WeekStartDay** | string |  |
| **WinprojVersion** | string |  |
# DraftProjectResource Class

Namespace: Microsoft.ProjectServer.Client

Base class: [ProjectResource](#projectresource-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **FieldValues** | Dictionary\<string, Object\> |  |
| **Item** | Object |  |
| **Assignments** | [DraftAssignmentCollection](#draftassignmentcollection-class) |  |
| **CanLevel** | bool |  |
| **Code** | string |  |
| **CostAccrual** | [AccrueAt](#accrueat-enum) |  |
| **CostCenter** | string |  |
| **CostPerUse** | double |  |
| **DefaultAssignmentOwner** | User |  |
| **DefaultBookingType** | [BookingType](#bookingtype-enum) |  |
| **Email** | string |  |
| **Group** | string |  |
| **Initials** | string |  |
| **MaterialLabel** | string |  |
| **MaximumCapacity** | double |  |
| **Name** | string |  |
| **OvertimeRate** | double |  |
| **OvertimeRateUnits** | [OvertimeRateFormat](#overtimerateformat-enum) |  |
| **Phonetics** | string |  |
| **StandardRate** | double |  |
| **StandardRateUnits** | [StandardRateFormat](#standardrateformat-enum) |  |
| **ActualCost** | double |  |
| **ActualCostWorkPerformed** | string |  |
| **ActualCostWorkPerformedTimeSpan** | TimeSpan |  |
| **ActualOvertimeCost** | double |  |
| **ActualOvertimeWork** | string |  |
| **ActualOvertimeWorkTimeSpan** | TimeSpan |  |
| **ActualWork** | string |  |
| **ActualWorkTimeSpan** | TimeSpan |  |
| **AvailableFrom** | DateTime |  |
| **AvailableTo** | DateTime |  |
| **BaselineCost** | double |  |
| **BaselineWork** | string |  |
| **BaselineWorkTimeSpan** | TimeSpan |  |
| **BudetCostWorkPerformed** | double |  |
| **BudgetedCost** | double |  |
| **BudgetedCostWorkScheduled** | double |  |
| **BudgetedWork** | string |  |
| **BudgetedWorkTimeSpan** | TimeSpan |  |
| **Cost** | double |  |
| **CostVariance** | double |  |
| **CostVarianceAtCompletion** | double |  |
| **Created** | DateTime |  |
| **CurrentCostVariance** | double |  |
| **CustomFields** | [CustomFieldCollection](#customfieldcollection-class) |  |
| **EnterpriseResource** | [EnterpriseResource](#enterpriseresource-class) |  |
| **Finish** | DateTime |  |
| **Id** | Guid |  |
| **IsBudgeted** | bool |  |
| **IsGenericResource** | bool |  |
| **IsOverAllocated** | bool |  |
| **Modified** | DateTime |  |
| **Notes** | string |  |
| **OvertimeCost** | double |  |
| **OvertimeWork** | string |  |
| **OvertimeWorkTimeSpan** | TimeSpan |  |
| **PeakWork** | string |  |
| **PeakWorkTimeSpan** | TimeSpan |  |
| **PercentWorkComplete** | int |  |
| **RegularWork** | string |  |
| **RegularWorkTimeSpan** | TimeSpan |  |
| **RemainingCost** | double |  |
| **RemainingOvertimeCost** | double |  |
| **RemainingOvertimeWork** | string |  |
| **RemainingOvertimeWorkTimeSpan** | TimeSpan |  |
| **RemainingWork** | string |  |
| **RemainingWorkTimeSpan** | TimeSpan |  |
| **ScheduleCostVariance** | double |  |
| **Start** | DateTime |  |
| **Work** | string |  |
| **WorkTimeSpan** | TimeSpan |  |
| **WorkVariance** | string |  |
| **WorkVarianceTimeSpan** | TimeSpan |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **DraftProjectResource(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
| **RefreshLoad()** | void |  |
# DraftProjectResourceCollection Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObjectCollection<[DraftProjectResource](#draftprojectresource-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [DraftProjectResource](#draftprojectresource-class) |  |
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
| **DraftProjectResourceCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(ProjectResourceCreationInformation parameters)** | [DraftProjectResource](#draftprojectresource-class) |  |
| **AddEnterpriseResource(EnterpriseResource resource)** | [DraftProjectResource](#draftprojectresource-class) |  |
| **GetByGuid(Guid uid)** | [DraftProjectResource](#draftprojectresource-class) |  |
| **GetById(string objectId)** | [DraftProjectResource](#draftprojectresource-class) |  |
| **Remove(DraftProjectResource resource)** | ClientResult\<bool\> |  |
# DraftProjectResourceObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Assignments** | string |  |
| **DefaultAssignmentOwner** | string |  |
# DraftProjectResourcePropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **CanLevel** | string |  |
| **Code** | string |  |
| **CostAccrual** | string |  |
| **CostCenter** | string |  |
| **CostPerUse** | string |  |
| **DefaultBookingType** | string |  |
| **Email** | string |  |
| **Group** | string |  |
| **Initials** | string |  |
| **MaterialLabel** | string |  |
| **MaximumCapacity** | string |  |
| **Name** | string |  |
| **OvertimeRate** | string |  |
| **OvertimeRateUnits** | string |  |
| **Phonetics** | string |  |
| **StandardRate** | string |  |
| **StandardRateUnits** | string |  |
# DraftTask Class

Namespace: Microsoft.ProjectServer.Client

Base class: [Task](#task-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **FieldValues** | Dictionary\<string, Object\> |  |
| **Item** | Object |  |
| **ActualCost** | double |  |
| **ActualFinish** | DateTime |  |
| **ActualStart** | DateTime |  |
| **ActualWork** | string |  |
| **ActualWorkTimeSpan** | TimeSpan |  |
| **Assignments** | [DraftAssignmentCollection](#draftassignmentcollection-class) |  |
| **BudgetWork** | string |  |
| **BudgetWorkTimeSpan** | TimeSpan |  |
| **Calendar** | [Calendar](#calendar-class) |  |
| **Completion** | DateTime |  |
| **ConstraintStartEnd** | DateTime |  |
| **ConstraintType** | [ConstraintType](#constrainttype-enum) |  |
| **Cost** | double |  |
| **Deadline** | DateTime |  |
| **Duration** | string |  |
| **DurationTimeSpan** | TimeSpan |  |
| **Finish** | DateTime |  |
| **FinishText** | string |  |
| **FixedCost** | double |  |
| **IsActive** | bool |  |
| **IsLockedByManager** | bool |  |
| **IsManual** | bool |  |
| **IsMarked** | bool |  |
| **IsMilestone** | bool |  |
| **LevelingAdjustsAssignments** | bool |  |
| **LevelingCanSplit** | bool |  |
| **Name** | string |  |
| **OutlineLevel** | int |  |
| **Parent** | [DraftTask](#drafttask-class) |  |
| **PercentComplete** | int |  |
| **PercentPhysicalWorkComplete** | int |  |
| **Predecessors** | [DraftTaskLinkCollection](#drafttasklinkcollection-class) |  |
| **Priority** | int |  |
| **RemainingDuration** | string |  |
| **RemainingDurationTimeSpan** | TimeSpan |  |
| **Start** | DateTime |  |
| **StartText** | string |  |
| **StatusManager** | User |  |
| **Successors** | [DraftTaskLinkCollection](#drafttasklinkcollection-class) |  |
| **TaskType** | [TaskType](#tasktype-enum) |  |
| **UsePercentPhysicalWorkComplete** | bool |  |
| **Work** | string |  |
| **WorkTimeSpan** | TimeSpan |  |
| **ActualCostWorkPerformed** | double |  |
| **ActualDuration** | string |  |
| **ActualDurationTimeSpan** | TimeSpan |  |
| **ActualOvertimeCost** | double |  |
| **ActualOvertimeWork** | string |  |
| **ActualOvertimeWorkTimeSpan** | TimeSpan |  |
| **BaselineCost** | double |  |
| **BaselineDuration** | string |  |
| **BaselineDurationTimeSpan** | TimeSpan |  |
| **BaselineFinish** | DateTime |  |
| **BaselineStart** | DateTime |  |
| **BaselineWork** | string |  |
| **BaselineWorkTimeSpan** | TimeSpan |  |
| **BudgetCost** | double |  |
| **BudgetedCostWorkPerformed** | double |  |
| **BudgetedCostWorkScheduled** | double |  |
| **Contact** | string |  |
| **CostPerformanceIndex** | double |  |
| **CostVariance** | double |  |
| **CostVarianceAtCompletion** | double |  |
| **CostVariancePercentage** | int |  |
| **Created** | DateTime |  |
| **CurrentCostVariance** | double |  |
| **CustomFields** | [CustomFieldCollection](#customfieldcollection-class) |  |
| **DurationVariance** | string |  |
| **DurationVarianceTimeSpan** | TimeSpan |  |
| **EarliestFinish** | DateTime |  |
| **EarliestStart** | DateTime |  |
| **EstimateAtCompletion** | double |  |
| **FinishSlack** | string |  |
| **FinishSlackTimeSpan** | TimeSpan |  |
| **FinishVariance** | string |  |
| **FinishVarianceTimeSpan** | TimeSpan |  |
| **FixedCostAccrual** | [FixedCostAccrual](#fixedcostaccrual-enum) |  |
| **FreeSlack** | string |  |
| **FreeSlackTimeSpan** | TimeSpan |  |
| **Id** | Guid |  |
| **IgnoreResourceCalendar** | bool |  |
| **IsCritical** | bool |  |
| **IsEffortDriven** | bool |  |
| **IsExternalTask** | bool |  |
| **IsOverAllocated** | bool |  |
| **IsRecurring** | bool |  |
| **IsRecurringSummary** | bool |  |
| **IsRolledUp** | bool |  |
| **IsSubProject** | bool |  |
| **IsSubProjectReadOnly** | bool |  |
| **IsSubProjectScheduledFromFinish** | bool |  |
| **IsSummary** | bool |  |
| **LatestFinish** | DateTime |  |
| **LatestStart** | DateTime |  |
| **LevelingDelay** | string |  |
| **LevelingDelayTimeSpan** | TimeSpan |  |
| **Modified** | DateTime |  |
| **Notes** | string |  |
| **OutlinePosition** | string |  |
| **OvertimeCost** | double |  |
| **OvertimeWork** | string |  |
| **OvertimeWorkTimeSpan** | TimeSpan |  |
| **PercentWorkComplete** | int |  |
| **PreLevelingFinish** | DateTime |  |
| **PreLevelingStart** | DateTime |  |
| **RegularWork** | string |  |
| **RegularWorkTimeSpan** | TimeSpan |  |
| **RemainingCost** | double |  |
| **RemainingOvertimeCost** | double |  |
| **RemainingOvertimeWork** | string |  |
| **RemainingOvertimeWorkTimeSpan** | TimeSpan |  |
| **RemainingWork** | string |  |
| **RemainingWorkTimeSpan** | TimeSpan |  |
| **Resume** | DateTime |  |
| **ScheduleCostVariance** | double |  |
| **ScheduledDuration** | string |  |
| **ScheduledDurationTimeSpan** | TimeSpan |  |
| **ScheduledFinish** | DateTime |  |
| **ScheduledStart** | DateTime |  |
| **SchedulePerformanceIndex** | double |  |
| **ScheduleVariancePercentage** | int |  |
| **StartSlack** | string |  |
| **StartSlackTimeSpan** | TimeSpan |  |
| **StartVariance** | string |  |
| **StartVarianceTimeSpan** | TimeSpan |  |
| **Stop** | DateTime |  |
| **SubProject** | [PublishedProject](#publishedproject-class) |  |
| **ToCompletePerformanceIndex** | double |  |
| **TotalSlack** | string |  |
| **TotalSlackTimeSpan** | TimeSpan |  |
| **WorkBreakdownStructure** | string |  |
| **WorkVariance** | string |  |
| **WorkVarianceTimeSpan** | TimeSpan |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **DraftTask(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
| **RefreshLoad()** | void |  |
# DraftTaskCollection Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObjectCollection<[DraftTask](#drafttask-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [DraftTask](#drafttask-class) |  |
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
| **DraftTaskCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(TaskCreationInformation parameters)** | [DraftTask](#drafttask-class) |  |
| **GetByGuid(Guid uid)** | [DraftTask](#drafttask-class) |  |
| **GetById(string objectId)** | [DraftTask](#drafttask-class) |  |
| **Remove(DraftTask task)** | ClientResult\<bool\> |  |
# DraftTaskLink Class

Namespace: Microsoft.ProjectServer.Client

Base class: [TaskLink](#tasklink-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **DependencyType** | [DependencyType](#dependencytype-enum) |  |
| **End** | [DraftTask](#drafttask-class) |  |
| **Start** | [DraftTask](#drafttask-class) |  |
| **Id** | Guid |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **DraftTaskLink(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
# DraftTaskLinkCollection Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObjectCollection<[DraftTaskLink](#drafttasklink-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [DraftTaskLink](#drafttasklink-class) |  |
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
| **DraftTaskLinkCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(TaskLinkCreationInformation parameters)** | [DraftTaskLink](#drafttasklink-class) |  |
| **GetByGuid(Guid uid)** | [DraftTaskLink](#drafttasklink-class) |  |
| **GetById(string objectId)** | [DraftTaskLink](#drafttasklink-class) |  |
| **Remove(DraftTaskLink TaskLink)** | ClientResult\<bool\> |  |
# DraftTaskLinkObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **End** | string |  |
| **Start** | string |  |
# DraftTaskLinkPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **DependencyType** | string |  |
# DraftTaskObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Assignments** | string |  |
| **Calendar** | string |  |
| **Parent** | string |  |
| **Predecessors** | string |  |
| **StatusManager** | string |  |
| **Successors** | string |  |
# DraftTaskPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **ActualCost** | string |  |
| **ActualFinish** | string |  |
| **ActualStart** | string |  |
| **ActualWork** | string |  |
| **ActualWorkTimeSpan** | string |  |
| **BudgetWork** | string |  |
| **BudgetWorkTimeSpan** | string |  |
| **Completion** | string |  |
| **ConstraintStartEnd** | string |  |
| **ConstraintType** | string |  |
| **Cost** | string |  |
| **Deadline** | string |  |
| **Duration** | string |  |
| **DurationTimeSpan** | string |  |
| **Finish** | string |  |
| **FinishText** | string |  |
| **FixedCost** | string |  |
| **IsActive** | string |  |
| **IsLockedByManager** | string |  |
| **IsManual** | string |  |
| **IsMarked** | string |  |
| **IsMilestone** | string |  |
| **LevelingAdjustsAssignments** | string |  |
| **LevelingCanSplit** | string |  |
| **Name** | string |  |
| **OutlineLevel** | string |  |
| **PercentComplete** | string |  |
| **PercentPhysicalWorkComplete** | string |  |
| **Priority** | string |  |
| **RemainingDuration** | string |  |
| **RemainingDurationTimeSpan** | string |  |
| **Start** | string |  |
| **StartText** | string |  |
| **TaskType** | string |  |
| **UsePercentPhysicalWorkComplete** | string |  |
| **Work** | string |  |
| **WorkTimeSpan** | string |  |
# Engagement Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Comments** | [EngagementCommentCollection](#engagementcommentcollection-class) |  |
| **CreatedDate** | DateTime |  |
| **Description** | string |  |
| **Id** | Guid |  |
| **Modified** | DateTime |  |
| **ModifiedBy** | User |  |
| **Project** | [Project](#project-class) |  |
| **Resource** | [EnterpriseResource](#enterpriseresource-class) |  |
| **ReviewedBy** | User |  |
| **ReviewedDate** | DateTime |  |
| **Status** | [EngagementStatus](#engagementstatus-enum) |  |
| **SubmittedBy** | User |  |
| **SubmittedDate** | DateTime |  |
| **TimephasedEditsOnly** | bool |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **Engagement(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# EngagementComment Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Author** | User |  |
| **Created** | DateTime |  |
| **Id** | Guid |  |
| **Message** | string |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **EngagementComment(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# EngagementCommentCollection Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObjectCollection<[EngagementComment](#engagementcomment-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [EngagementComment](#engagementcomment-class) |  |
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
| **EngagementCommentCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(string comment)** | [EngagementComment](#engagementcomment-class) |  |
# EngagementCommentObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Author** | string |  |
# EngagementCommentPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Created** | string |  |
| **Id** | string |  |
| **Message** | string |  |
# EngagementContourType Enum

Namespace: Microsoft.ProjectServer.Client


## Values

| Name | Summary |
|---|---|
| **Approved** |  |
| **Proposed** |  |
| **Draft** |  |
# EngagementCreationInformation Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Description** | string |  |
| **Finish** | DateTime |  |
| **Id** | Guid |  |
| **MaxUnits** | double |  |
| **Start** | DateTime |  |
| **TimephasedPeriodData** | IEnumerable\<[EngagementTimephasedPeriodCreationInformation](#engagementtimephasedperiodcreationinformation-class)\> |  |
| **Work** | string |  |
| **WorkTimeSpan** | TimeSpan |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# EngagementObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Comments** | string |  |
| **ModifiedBy** | string |  |
| **Project** | string |  |
| **Resource** | string |  |
| **ReviewedBy** | string |  |
| **SubmittedBy** | string |  |
# EngagementPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **CreatedDate** | string |  |
| **Description** | string |  |
| **Id** | string |  |
| **Modified** | string |  |
| **ReviewedDate** | string |  |
| **Status** | string |  |
| **SubmittedDate** | string |  |
| **TimephasedEditsOnly** | string |  |
# EngagementSaveConflictException Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# EngagementStatus Enum

Namespace: Microsoft.ProjectServer.Client


## Values

| Name | Summary |
|---|---|
| **Approved** |  |
| **Proposed** |  |
| **Draft** |  |
| **Rejected** |  |
| **Reproposed** |  |
# EngagementTimephasedPeriod Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **End** | DateTime |  |
| **MaxUnits** | double |  |
| **Start** | DateTime |  |
| **Work** | string |  |
| **WorkTimeSpan** | TimeSpan |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **EngagementTimephasedPeriod(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# EngagementTimephasedPeriodCreationInformation Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **End** | DateTime |  |
| **MaxUnits** | double |  |
| **Start** | DateTime |  |
| **Work** | string |  |
| **WorkTimeSpan** | TimeSpan |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# EngagementTimephasedPeriodPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **End** | string |  |
| **MaxUnits** | string |  |
| **Start** | string |  |
| **Work** | string |  |
| **WorkTimeSpan** | string |  |
# EnterpriseProjectType Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Description** | string |  |
| **Id** | Guid |  |
| **ImageUrl** | string |  |
| **IsDefault** | bool |  |
| **IsManaged** | bool |  |
| **Name** | string |  |
| **Order** | int |  |
| **PermissionSyncEnable** | bool |  |
| **ProjectDetailPages** | [ProjectDetailPageCollection](#projectdetailpagecollection-class) |  |
| **ProjectPlanTemplateId** | Guid |  |
| **SiteCreationOption** | [EnterpriseProjectTypeSiteCreationOptions](#enterpriseprojecttypesitecreationoptions-enum) |  |
| **SiteCreationURL** | string |  |
| **TaskListSyncEnable** | bool |  |
| **WorkflowAssociationId** | Guid |  |
| **WorkflowAssociationName** | string |  |
| **WorkspaceTemplateLCID** | int |  |
| **WorkspaceTemplateName** | string |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **EnterpriseProjectType(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
# EnterpriseProjectTypeCollection Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObjectCollection<[EnterpriseProjectType](#enterpriseprojecttype-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [EnterpriseProjectType](#enterpriseprojecttype-class) |  |
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
| **EnterpriseProjectTypeCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(EnterpriseProjectTypeCreationInformation parameters)** | [EnterpriseProjectType](#enterpriseprojecttype-class) |  |
| **GetByGuid(Guid uid)** | [EnterpriseProjectType](#enterpriseprojecttype-class) |  |
| **GetById(string objectId)** | [EnterpriseProjectType](#enterpriseprojecttype-class) |  |
| **Remove(EnterpriseProjectType ept)** | ClientResult\<bool\> |  |
| **Update()** | void |  |
# EnterpriseProjectTypeCreationInformation Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Description** | string |  |
| **Id** | Guid |  |
| **ImageUrl** | string |  |
| **IsDefault** | bool |  |
| **IsManaged** | bool |  |
| **Name** | string |  |
| **Order** | int |  |
| **PermissionSyncEnable** | bool |  |
| **ProjectDetailPages** | IEnumerable\<[ProjectDetailPageCreationInformation](#projectdetailpagecreationinformation-class)\> |  |
| **ProjectPlanTemplateId** | Guid |  |
| **SiteCreationOption** | [EnterpriseProjectTypeSiteCreationOptions](#enterpriseprojecttypesitecreationoptions-enum) |  |
| **SiteCreationURL** | string |  |
| **TaskListSyncEnable** | bool |  |
| **WorkflowAssociationId** | Guid |  |
| **WorkflowAssociationName** | string |  |
| **WorkspaceTemplateLCID** | uint |  |
| **WorkspaceTemplateName** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# EnterpriseProjectTypeObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **ProjectDetailPages** | string |  |
# EnterpriseProjectTypePropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Description** | string |  |
| **Id** | string |  |
| **ImageUrl** | string |  |
| **IsDefault** | string |  |
| **IsManaged** | string |  |
| **Name** | string |  |
| **Order** | string |  |
| **PermissionSyncEnable** | string |  |
| **ProjectPlanTemplateId** | string |  |
| **SiteCreationOption** | string |  |
| **SiteCreationURL** | string |  |
| **TaskListSyncEnable** | string |  |
| **WorkflowAssociationId** | string |  |
| **WorkflowAssociationName** | string |  |
| **WorkspaceTemplateLCID** | string |  |
| **WorkspaceTemplateName** | string |  |
# EnterpriseProjectTypeSiteCreationOptions Enum

Namespace: Microsoft.ProjectServer.Client


## Values

| Name | Summary |
|---|---|
| **NotSpecified** |  |
| **AskOnPublish** |  |
| **CreateOnFirstPublish** |  |
| **None** |  |
# EnterpriseResource Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **FieldValues** | Dictionary\<string, Object\> |  |
| **Item** | Object |  |
| **Assignments** | [StatusAssignmentCollection](#statusassignmentcollection-class) |  |
| **BaseCalendar** | [Calendar](#calendar-class) |  |
| **CanLevel** | bool |  |
| **Code** | string |  |
| **CostAccrual** | [AccrueAt](#accrueat-enum) |  |
| **CostCenter** | string |  |
| **CostRateTables** | [EnterpriseResourceCostRateTableCollection](#enterpriseresourcecostratetablecollection-class) |  |
| **Created** | DateTime |  |
| **CustomFields** | [CustomFieldCollection](#customfieldcollection-class) |  |
| **DefaultAssignmentOwner** | User |  |
| **DefaultBookingType** | [BookingType](#bookingtype-enum) |  |
| **Email** | string |  |
| **Engagements** | [ResourceEngagementCollection](#resourceengagementcollection-class) |  |
| **ExternalId** | string |  |
| **Group** | string |  |
| **HireDate** | DateTime |  |
| **Id** | Guid |  |
| **Initials** | string |  |
| **IsActive** | bool |  |
| **IsBudget** | bool |  |
| **IsCheckedOut** | bool |  |
| **IsGeneric** | bool |  |
| **IsTeam** | bool |  |
| **MaterialLabel** | string |  |
| **Modified** | DateTime |  |
| **Name** | string |  |
| **Phonetics** | string |  |
| **RequiresEngagements** | bool |  |
| **ResourceCalendarExceptions** | [CalendarExceptionCollection](#calendarexceptioncollection-class) |  |
| **ResourceType** | [EnterpriseResourceType](#enterpriseresourcetype-enum) |  |
| **TerminationDate** | DateTime |  |
| **TimesheetManager** | User |  |
| **User** | User |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **EnterpriseResource(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
| **ForceCheckIn()** | void |  |
| **GetSelf(ClientRuntimeContext Context)** | [EnterpriseResource](#enterpriseresource-class) |  |
| **RefreshLoad()** | void |  |
# EnterpriseResourceCollection Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObjectCollection<[EnterpriseResource](#enterpriseresource-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [EnterpriseResource](#enterpriseresource-class) |  |
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
| **EnterpriseResourceCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(EnterpriseResourceCreationInformation parameters)** | [EnterpriseResource](#enterpriseresource-class) |  |
| **GetByGuid(Guid uid)** | [EnterpriseResource](#enterpriseresource-class) |  |
| **GetById(string objectId)** | [EnterpriseResource](#enterpriseresource-class) |  |
| **GetByUser(User user)** | [EnterpriseResource](#enterpriseresource-class) |  |
| **Remove(EnterpriseResource resource)** | ClientResult\<bool\> |  |
| **Update()** | void |  |
# EnterpriseResourceCostRate Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **CostPerUse** | double |  |
| **EffectiveStarting** | DateTime |  |
| **EffectiveUntil** | DateTime |  |
| **OvertimeRate** | double |  |
| **StandardRate** | double |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **EnterpriseResourceCostRate(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | ClientResult\<bool\> |  |
# EnterpriseResourceCostRateCollection Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObjectCollection<[EnterpriseResourceCostRate](#enterpriseresourcecostrate-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [EnterpriseResourceCostRate](#enterpriseresourcecostrate-class) |  |
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
| **EnterpriseResourceCostRateCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(CostRateCreationInformation parameters)** | [EnterpriseResourceCostRate](#enterpriseresourcecostrate-class) |  |
| **Remove(EnterpriseResourceCostRate costRate)** | ClientResult\<bool\> |  |
# EnterpriseResourceCostRatePropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **CostPerUse** | string |  |
| **EffectiveStarting** | string |  |
| **EffectiveUntil** | string |  |
| **OvertimeRate** | string |  |
| **StandardRate** | string |  |
# EnterpriseResourceCostRateTable Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **CostRates** | [EnterpriseResourceCostRateCollection](#enterpriseresourcecostratecollection-class) |  |
| **Name** | [CostRateTableName](#costratetablename-enum) |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **EnterpriseResourceCostRateTable(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# EnterpriseResourceCostRateTableCollection Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObjectCollection<[EnterpriseResourceCostRateTable](#enterpriseresourcecostratetable-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [EnterpriseResourceCostRateTable](#enterpriseresourcecostratetable-class) |  |
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
| **EnterpriseResourceCostRateTableCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetByName(CostRateTableName name)** | [EnterpriseResourceCostRateTable](#enterpriseresourcecostratetable-class) |  |
# EnterpriseResourceCostRateTableObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **CostRates** | string |  |
# EnterpriseResourceCostRateTablePropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Name** | string |  |
# EnterpriseResourceCreationInformation Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Id** | Guid |  |
| **IsBudget** | bool |  |
| **IsGeneric** | bool |  |
| **IsInactive** | bool |  |
| **Name** | string |  |
| **ResourceType** | [EnterpriseResourceType](#enterpriseresourcetype-enum) |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# EnterpriseResourceObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Assignments** | string |  |
| **BaseCalendar** | string |  |
| **CostRateTables** | string |  |
| **CustomFields** | string |  |
| **DefaultAssignmentOwner** | string |  |
| **Engagements** | string |  |
| **ResourceCalendarExceptions** | string |  |
| **TimesheetManager** | string |  |
| **User** | string |  |
# EnterpriseResourcePropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **CanLevel** | string |  |
| **Code** | string |  |
| **CostAccrual** | string |  |
| **CostCenter** | string |  |
| **Created** | string |  |
| **DefaultBookingType** | string |  |
| **Email** | string |  |
| **ExternalId** | string |  |
| **Group** | string |  |
| **HireDate** | string |  |
| **Id** | string |  |
| **Initials** | string |  |
| **IsActive** | string |  |
| **IsBudget** | string |  |
| **IsCheckedOut** | string |  |
| **IsGeneric** | string |  |
| **IsTeam** | string |  |
| **MaterialLabel** | string |  |
| **Modified** | string |  |
| **Name** | string |  |
| **Phonetics** | string |  |
| **RequiresEngagements** | string |  |
| **ResourceType** | string |  |
| **TerminationDate** | string |  |
# EnterpriseResourceType Enum

Namespace: Microsoft.ProjectServer.Client


## Values

| Name | Summary |
|---|---|
| **NotSpecified** |  |
| **Work** |  |
| **Material** |  |
| **Cost** |  |
# EntityType Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Name** | string |  |
| **ID** | Guid |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **EntityType(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# EntityTypePropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Name** | string |  |
| **ID** | string |  |
# EntityTypes Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AssignmentEntity** | [EntityType](#entitytype-class) |  |
| **ProjectEntity** | [EntityType](#entitytype-class) |  |
| **ResourceEntity** | [EntityType](#entitytype-class) |  |
| **TaskEntity** | [EntityType](#entitytype-class) |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **EntityTypes(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# EntityTypesObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **AssignmentEntity** | string |  |
| **ProjectEntity** | string |  |
| **ResourceEntity** | string |  |
| **TaskEntity** | string |  |
# Event Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **EventName** | string |  |
| **Id** | int |  |
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
| **Event(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# EventCollection Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObjectCollection<[Event](#event-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [Event](#event-class) |  |
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
| **EventCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetById(string objectId)** | [Event](#event-class) |  |
| **GetByInt(int id)** | [Event](#event-class) |  |
# EventHandler Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AssemblyName** | string |  |
| **ClassName** | string |  |
| **Description** | string |  |
| **EndpointUrl** | string |  |
| **Event** | [Event](#event-class) |  |
| **Id** | Guid |  |
| **Name** | string |  |
| **Order** | int |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **EventHandler(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
# EventHandlerCollection Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObjectCollection<[EventHandler](#eventhandler-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [EventHandler](#eventhandler-class) |  |
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
| **EventHandlerCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(EventHandlerCreationInformation parameters)** | [EventHandler](#eventhandler-class) |  |
| **GetByGuid(Guid uid)** | [EventHandler](#eventhandler-class) |  |
| **GetById(string objectId)** | [EventHandler](#eventhandler-class) |  |
| **Remove(EventHandler handler)** | ClientResult\<bool\> |  |
| **Update()** | void |  |
# EventHandlerCreationInformation Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AssemblyName** | string |  |
| **ClassName** | string |  |
| **Description** | string |  |
| **EndpointUrl** | string |  |
| **EventId** | int |  |
| **Id** | Guid |  |
| **Name** | string |  |
| **Order** | int |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# EventHandlerObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Event** | string |  |
# EventHandlerPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **AssemblyName** | string |  |
| **ClassName** | string |  |
| **Description** | string |  |
| **EndpointUrl** | string |  |
| **Id** | string |  |
| **Name** | string |  |
| **Order** | string |  |
# EventPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **EventName** | string |  |
| **Id** | string |  |
| **SourceName** | string |  |
# FixedCostAccrual Enum

Namespace: Microsoft.ProjectServer.Client


## Values

| Name | Summary |
|---|---|
| **NotSpecified** |  |
| **Start** |  |
| **End** |  |
| **Prorated** |  |
# JobState Enum

Namespace: Microsoft.ProjectServer.Client


## Values

| Name | Summary |
|---|---|
| **Unknown** |  |
| **ReadyForProcessing** |  |
| **SendIncomplete** |  |
| **Processing** |  |
| **Success** |  |
| **Failed** |  |
| **FailedNotBlocking** |  |
| **ProcessingDeferred** |  |
| **CorrelationBlocked** |  |
| **Canceled** |  |
| **OnHold** |  |
| **Sleeping** |  |
| **ReadyForLaunch** |  |
| **LastState** |  |
# LookupCost Class

Namespace: Microsoft.ProjectServer.Client

Base class: [LookupEntry](#lookupentry-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **Value** | decimal |  |
| **AppAlternateId** | Guid |  |
| **Description** | string |  |
| **FullValue** | string |  |
| **Id** | Guid |  |
| **InternalName** | string |  |
| **SortIndex** | decimal |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **LookupCost(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# LookupCostPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Value** | string |  |
# LookupDate Class

Namespace: Microsoft.ProjectServer.Client

Base class: [LookupEntry](#lookupentry-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **Value** | DateTime |  |
| **AppAlternateId** | Guid |  |
| **Description** | string |  |
| **FullValue** | string |  |
| **Id** | Guid |  |
| **InternalName** | string |  |
| **SortIndex** | decimal |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **LookupDate(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# LookupDatePropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Value** | string |  |
# LookupDuration Class

Namespace: Microsoft.ProjectServer.Client

Base class: [LookupEntry](#lookupentry-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **Value** | string |  |
| **ValueTimeSpan** | TimeSpan |  |
| **AppAlternateId** | Guid |  |
| **Description** | string |  |
| **FullValue** | string |  |
| **Id** | Guid |  |
| **InternalName** | string |  |
| **SortIndex** | decimal |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **LookupDuration(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# LookupDurationPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Value** | string |  |
| **ValueTimeSpan** | string |  |
# LookupEntry Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AppAlternateId** | Guid |  |
| **Description** | string |  |
| **FullValue** | string |  |
| **Id** | Guid |  |
| **InternalName** | string |  |
| **SortIndex** | decimal |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **LookupEntry(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
# LookupEntryCollection Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObjectCollection<[LookupEntry](#lookupentry-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [LookupEntry](#lookupentry-class) |  |
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
| **LookupEntryCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(LookupEntryCreationInformation parameters)** | [LookupEntry](#lookupentry-class) |  |
| **GetByAppAlternateId(string objectId)** | [LookupEntry](#lookupentry-class) |  |
| **GetByGuid(Guid uid)** | [LookupEntry](#lookupentry-class) |  |
| **GetById(string objectId)** | [LookupEntry](#lookupentry-class) |  |
| **Remove(LookupEntry entry)** | ClientResult\<bool\> |  |
# LookupEntryCreationInformation Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Description** | string |  |
| **Id** | Guid |  |
| **ParentId** | Guid |  |
| **SortIndex** | decimal |  |
| **Value** | [LookupEntryValue](#lookupentryvalue-class) |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# LookupEntryPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **AppAlternateId** | string |  |
| **Description** | string |  |
| **FullValue** | string |  |
| **Id** | string |  |
| **InternalName** | string |  |
| **SortIndex** | string |  |
# LookupEntryValue Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **DateValue** | DateTime |  |
| **DurationValue** | string |  |
| **NumberValue** | decimal |  |
| **TextValue** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# LookupMask Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Length** | int |  |
| **MaskType** | [LookupTableMaskSequence](#lookuptablemasksequence-enum) |  |
| **Separator** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# LookupNumber Class

Namespace: Microsoft.ProjectServer.Client

Base class: [LookupEntry](#lookupentry-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **Value** | decimal |  |
| **AppAlternateId** | Guid |  |
| **Description** | string |  |
| **FullValue** | string |  |
| **Id** | Guid |  |
| **InternalName** | string |  |
| **SortIndex** | decimal |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **LookupNumber(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# LookupNumberPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Value** | string |  |
# LookupTable Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AppAlternateId** | Guid |  |
| **Entries** | [LookupEntryCollection](#lookupentrycollection-class) |  |
| **FieldType** | [CustomFieldType](#customfieldtype-enum) |  |
| **Id** | Guid |  |
| **Masks** | IEnumerable\<[LookupMask](#lookupmask-class)\> |  |
| **Name** | string |  |
| **SortOrder** | [LookupTableSortOrder](#lookuptablesortorder-enum) |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **LookupTable(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
# LookupTableCollection Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObjectCollection<[LookupTable](#lookuptable-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [LookupTable](#lookuptable-class) |  |
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
| **LookupTableCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(LookupTableCreationInformation parameters)** | [LookupTable](#lookuptable-class) |  |
| **GetByAppAlternateId(string objectId)** | [LookupTable](#lookuptable-class) |  |
| **GetByGuid(Guid uid)** | [LookupTable](#lookuptable-class) |  |
| **GetById(string objectId)** | [LookupTable](#lookuptable-class) |  |
| **Remove(LookupTable table)** | ClientResult\<bool\> |  |
| **Update()** | void |  |
# LookupTableConstants Enum

Namespace: Microsoft.ProjectServer.Client


## Values

| Name | Summary |
|---|---|
| **NoSortOrder** |  |
| **AnyLengthSequence** |  |
| **MinValueLength** |  |
| **MinLevel** |  |
| **MaxSeparatorLength** |  |
| **MaxValueLength** |  |
| **MaxLevel** |  |
| **MaxDescriptionLength** |  |
# LookupTableCreationInformation Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Entries** | IEnumerable\<[LookupEntryCreationInformation](#lookupentrycreationinformation-class)\> |  |
| **Id** | Guid |  |
| **Masks** | IEnumerable\<[LookupMask](#lookupmask-class)\> |  |
| **Name** | string |  |
| **SortOrder** | [LookupTableSortOrder](#lookuptablesortorder-enum) |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# LookupTableMaskSequence Enum

Namespace: Microsoft.ProjectServer.Client


## Values

| Name | Summary |
|---|---|
| **NUMBER_TEXT** |  |
| **UPPERCASE** |  |
| **LOWERCASE** |  |
| **CHARACTERS** |  |
| **DATE** |  |
| **COST** |  |
| **DURATION** |  |
| **NUMBER_DECIMAL** |  |
| **FLAG** |  |
# LookupTableObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Entries** | string |  |
# LookupTablePropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **AppAlternateId** | string |  |
| **FieldType** | string |  |
| **Id** | string |  |
| **Masks** | string |  |
| **Name** | string |  |
| **SortOrder** | string |  |
# LookupTables Class

Namespace: Microsoft.ProjectServer.Client

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
| **LookupTables(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **InvalidNameCharacters(ClientRuntimeContext context)** | ClientArrayResult\<char\> |  |
# LookupTableSortOrder Enum

Namespace: Microsoft.ProjectServer.Client


## Values

| Name | Summary |
|---|---|
| **UserDefined** |  |
| **Ascending** |  |
| **Descending** |  |
# LookupText Class

Namespace: Microsoft.ProjectServer.Client

Base class: [LookupEntry](#lookupentry-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **HasChildren** | bool |  |
| **Mask** | [LookupMask](#lookupmask-class) |  |
| **Parent** | [LookupText](#lookuptext-class) |  |
| **Value** | string |  |
| **AppAlternateId** | Guid |  |
| **Description** | string |  |
| **FullValue** | string |  |
| **Id** | Guid |  |
| **InternalName** | string |  |
| **SortIndex** | decimal |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **LookupText(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# LookupTextObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Parent** | string |  |
# LookupTextPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **HasChildren** | string |  |
| **Mask** | string |  |
| **Value** | string |  |
# OvertimeRateFormat Enum

Namespace: Microsoft.ProjectServer.Client


## Values

| Name | Summary |
|---|---|
| **Minute** |  |
| **Hour** |  |
| **Day** |  |
| **Week** |  |
| **Month** |  |
| **Year** |  |
| **Material** |  |
# PageSizes Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **EngagementsTimephased** | int |  |
| **EnterpriseResources** | int |  |
| **Projects** | int |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **PageSizes(ClientRuntimeContext context, ProjectServer server)** |  |
| **PageSizes(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# PageSizesPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **EngagementsTimephased** | string |  |
| **EnterpriseResources** | string |  |
| **Projects** | string |  |
# Phase Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Description** | string |  |
| **Id** | Guid |  |
| **Name** | string |  |
| **Stages** | [StageCollection](#stagecollection-class) |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **Phase(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
# PhaseCollection Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObjectCollection<[Phase](#phase-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [Phase](#phase-class) |  |
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
| **PhaseCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(PhaseCreationInformation parameters)** | [Phase](#phase-class) |  |
| **GetByGuid(Guid uid)** | [Phase](#phase-class) |  |
| **GetById(string objectId)** | [Phase](#phase-class) |  |
| **Remove(Phase phase)** | ClientResult\<bool\> |  |
| **Update()** | void |  |
# PhaseCreationInformation Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Description** | string |  |
| **Id** | Guid |  |
| **Name** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# PhaseObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Stages** | string |  |
# PhasePropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Description** | string |  |
| **Id** | string |  |
| **Name** | string |  |
# PlanAssignment Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **FieldValues** | Dictionary\<string, Object\> |  |
| **Item** | Object |  |
| **BookingType** | [BookingType](#bookingtype-enum) |  |
| **CanLevel** | bool |  |
| **Code** | string |  |
| **CostCenter** | string |  |
| **CustomFields** | [CustomFieldCollection](#customfieldcollection-class) |  |
| **Email** | string |  |
| **Group** | string |  |
| **HireDate** | DateTime |  |
| **Id** | Guid |  |
| **Intervals** | [PlanAssignmentIntervalCollection](#planassignmentintervalcollection-class) |  |
| **IsTeam** | bool |  |
| **Name** | string |  |
| **Phonetics** | string |  |
| **Resource** | [EnterpriseResource](#enterpriseresource-class) |  |
| **ResourceType** | [EnterpriseResourceType](#enterpriseresourcetype-enum) |  |
| **TerminationDate** | DateTime |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **PlanAssignment(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
| **RefreshLoad()** | void |  |
# PlanAssignmentCollection Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObjectCollection<[PlanAssignment](#planassignment-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [PlanAssignment](#planassignment-class) |  |
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
| **PlanAssignmentCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(PlanAssignmentCreationInformation parameters)** | [PlanAssignment](#planassignment-class) |  |
| **GetByGuid(Guid uid)** | [PlanAssignment](#planassignment-class) |  |
| **GetById(string objectId)** | [PlanAssignment](#planassignment-class) |  |
| **Remove(PlanAssignment assignment)** | ClientResult\<bool\> |  |
# PlanAssignmentCreationInformation Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **BookingType** | [BookingType](#bookingtype-enum) |  |
| **Id** | Guid |  |
| **Intervals** | IEnumerable\<[PlanAssignmentIntervalCreationInformation](#planassignmentintervalcreationinformation-class)\> |  |
| **ResourceId** | Guid |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# PlanAssignmentInterval Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Duration** | string |  |
| **DurationTimeSpan** | TimeSpan |  |
| **End** | DateTime |  |
| **Name** | string |  |
| **Start** | DateTime |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **PlanAssignmentInterval(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# PlanAssignmentIntervalCollection Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObjectCollection<[PlanAssignmentInterval](#planassignmentinterval-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [PlanAssignmentInterval](#planassignmentinterval-class) |  |
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
| **PlanAssignmentIntervalCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetById(string id)** | [PlanAssignmentInterval](#planassignmentinterval-class) |  |
| **GetByStart(DateTime start)** | [PlanAssignmentInterval](#planassignmentinterval-class) |  |
# PlanAssignmentIntervalCreationInformation Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Duration** | string |  |
| **Interval** | DateTime |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# PlanAssignmentIntervalPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Duration** | string |  |
| **DurationTimeSpan** | string |  |
| **End** | string |  |
| **Name** | string |  |
| **Start** | string |  |
# PlanAssignmentObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **CustomFields** | string |  |
| **Intervals** | string |  |
| **Resource** | string |  |
# PlanAssignmentPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **BookingType** | string |  |
| **CanLevel** | string |  |
| **Code** | string |  |
| **CostCenter** | string |  |
| **Email** | string |  |
| **Group** | string |  |
| **HireDate** | string |  |
| **Id** | string |  |
| **IsTeam** | string |  |
| **Name** | string |  |
| **Phonetics** | string |  |
| **ResourceType** | string |  |
| **TerminationDate** | string |  |
# Project Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ApprovedEnd** | DateTime |  |
| **ApprovedStart** | DateTime |  |
| **CalculateActualCosts** | bool |  |
| **CalculatesActualCosts** | bool |  |
| **CheckedOutBy** | User |  |
| **CheckedOutDate** | DateTime |  |
| **CheckOutDescription** | string |  |
| **CheckOutId** | Guid |  |
| **CreatedDate** | DateTime |  |
| **CriticalSlackLimit** | int |  |
| **CustomFields** | [CustomFieldCollection](#customfieldcollection-class) |  |
| **DefaultFinishTime** | DateTime |  |
| **DefaultOvertimeRateUnits** | [OvertimeRateFormat](#overtimerateformat-enum) |  |
| **DefaultStandardRateUnits** | [StandardRateFormat](#standardrateformat-enum) |  |
| **DefaultStartTime** | DateTime |  |
| **Engagements** | [ProjectEngagementCollection](#projectengagementcollection-class) |  |
| **EnterpriseProjectType** | [EnterpriseProjectType](#enterpriseprojecttype-class) |  |
| **HasMppPendingImport** | bool |  |
| **HonorConstraints** | bool |  |
| **Id** | Guid |  |
| **IsCheckedOut** | bool |  |
| **LastPublishedDate** | DateTime |  |
| **LastSavedDate** | DateTime |  |
| **MoveActualIfLater** | bool |  |
| **MoveActualToStatus** | bool |  |
| **MoveRemainingIfEarlier** | bool |  |
| **MoveRemainingToStatus** | bool |  |
| **MultipleCriticalPaths** | bool |  |
| **OptimizerDecision** | [CommittedDecisionResult](#committeddecisionresult-enum) |  |
| **PercentComplete** | int |  |
| **Phase** | [Phase](#phase-class) |  |
| **PlannerDecision** | [CommittedDecisionResult](#committeddecisionresult-enum) |  |
| **ProjectSiteUrl** | string |  |
| **ProjectSummaryTask** | [ProjectSummaryTask](#projectsummarytask-class) |  |
| **ProjectType** | [ProjectType](#projecttype-enum) |  |
| **QueueJobs** | [QueueJobCollection](#queuejobcollection-class) |  |
| **ScheduledFromStart** | bool |  |
| **SplitInProgress** | bool |  |
| **SpreadActualCostsToStatus** | bool |  |
| **SpreadPercentCompleteToStatus** | bool |  |
| **Stage** | [Stage](#stage-class) |  |
| **SummaryTaskId** | Guid |  |
| **TaskListId** | Guid |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **Project(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **EnterProjectStage(Stage stage)** | void |  |
| **GetResourcePlan(DateTime start, DateTime end, TimeScale timeScale)** | [ResourcePlan](#resourceplan-class) |  |
| **LeaveProjectStage()** | void |  |
| **ReadyToLeaveProjectStage()** | ClientResult\<[ReadyToLeaveProjectStageValue](#readytoleaveprojectstagevalue-enum)\> |  |
| **SetCustomFieldValue(string fieldName, Object value)** | void |  |
| **UpdateIdeaListItemStatus(string status)** | void |  |
| **UpdateProjectStageStatus(Stage stage, string statusInformation, UpdateProjectStageStatusFieldValue stageStatusValue, bool append)** | void |  |
# ProjectCollection Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObjectCollection<[PublishedProject](#publishedproject-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [PublishedProject](#publishedproject-class) |  |
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
| **ProjectCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(ProjectCreationInformation parameters)** | [PublishedProject](#publishedproject-class) |  |
| **GetByGuid(Guid uid)** | [PublishedProject](#publishedproject-class) |  |
| **GetById(string objectId)** | [PublishedProject](#publishedproject-class) |  |
| **Remove(PublishedProject project)** | ClientResult\<bool\> |  |
| **Update()** | [QueueJob](#queuejob-class) |  |
| **Validate()** | void |  |
# ProjectContext Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientContext


## Properties

| Name | Type | Summary |
|---|---|---|
| **WorkflowActivities** | [WorkflowActivities](#workflowactivities-class) |  |
| **WorkflowDesigner** | [WorkflowDesigner](#workflowdesigner-class) |  |
| **EntityTypes** | [EntityTypes](#entitytypes-class) |  |
| **Projects** | [ProjectCollection](#projectcollection-class) |  |
| **CustomFields** | [CustomFieldCollection](#customfieldcollection-class) |  |
| **LookupTables** | [LookupTableCollection](#lookuptablecollection-class) |  |
| **EnterpriseProjectTypes** | [EnterpriseProjectTypeCollection](#enterpriseprojecttypecollection-class) |  |
| **Phases** | [PhaseCollection](#phasecollection-class) |  |
| **Stages** | [StageCollection](#stagecollection-class) |  |
| **ProjectDetailPages** | [ProjectDetailPageCollection](#projectdetailpagecollection-class) |  |
| **EnterpriseResources** | [EnterpriseResourceCollection](#enterpriseresourcecollection-class) |  |
| **Events** | [EventCollection](#eventcollection-class) |  |
| **EventHandlers** | [EventHandlerCollection](#eventhandlercollection-class) |  |
| **TimeSheetPeriods** | [TimeSheetPeriodCollection](#timesheetperiodcollection-class) |  |
| **Calendars** | [CalendarCollection](#calendarcollection-class) |  |
| **ServiceStatus** | [ServiceStatus](#servicestatus-class) |  |
| **PageSizes** | [PageSizes](#pagesizes-class) |  |
| **Web** | Web |  |
| **Site** | Site |  |
| **RequestResources** | RequestResources |  |
| **FormDigestHandlingEnabled** | bool |  |
| **ServerVersion** | Version |  |
| **NextSequenceId** | long |  |
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
| **ProjectContext(string url)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetDeletedPublishedAssignments(DateTime deletedDate)** | [DeletedPublishedAssignmentCollection](#deletedpublishedassignmentcollection-class) |  |
| **WaitForQueue(QueueJob job, int timeoutSeconds)** | [JobState](#jobstate-enum) |  |
# ProjectCreationInformation Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Description** | string |  |
| **EnterpriseProjectTypeId** | Guid |  |
| **Id** | Guid |  |
| **Name** | string |  |
| **Start** | DateTime |  |
| **TaskList** | List |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# ProjectDetailPage Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Id** | Guid |  |
| **Item** | ListItem |  |
| **Name** | string |  |
| **PageType** | [ProjectDetailPageType](#projectdetailpagetype-enum) |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **ProjectDetailPage(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ProjectDetailPageCollection Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObjectCollection<[ProjectDetailPage](#projectdetailpage-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **List** | List |  |
| **Item** | [ProjectDetailPage](#projectdetailpage-class) |  |
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
| **ProjectDetailPageCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetByGuid(Guid uid)** | [ProjectDetailPage](#projectdetailpage-class) |  |
| **GetById(string objectId)** | [ProjectDetailPage](#projectdetailpage-class) |  |
# ProjectDetailPageCollectionObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **List** | string |  |
# ProjectDetailPageCreationInformation Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Id** | Guid |  |
| **IsCreate** | bool |  |
| **Position** | int |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# ProjectDetailPageObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Item** | string |  |
# ProjectDetailPagePropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Id** | string |  |
| **Name** | string |  |
| **PageType** | string |  |
# ProjectDetailPageType Enum

Namespace: Microsoft.ProjectServer.Client


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **ProjectDefault** |  |
| **NewProject** |  |
| **WorkflowStatus** |  |
# ProjectEngagement Class

Namespace: Microsoft.ProjectServer.Client

Base class: [Engagement](#engagement-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **ApprovedFinish** | DateTime |  |
| **ApprovedMaxUnits** | double |  |
| **ApprovedStart** | DateTime |  |
| **ApprovedWork** | string |  |
| **ApprovedWorkTimeSpan** | TimeSpan |  |
| **HasUnsubmittedChanges** | bool |  |
| **RequestedFinish** | DateTime |  |
| **RequestedMaxUnits** | double |  |
| **RequestedStart** | DateTime |  |
| **RequestedWork** | string |  |
| **RequestedWorkTimeSpan** | TimeSpan |  |
| **Comments** | [EngagementCommentCollection](#engagementcommentcollection-class) |  |
| **CreatedDate** | DateTime |  |
| **Description** | string |  |
| **Id** | Guid |  |
| **Modified** | DateTime |  |
| **ModifiedBy** | User |  |
| **Project** | [Project](#project-class) |  |
| **Resource** | [EnterpriseResource](#enterpriseresource-class) |  |
| **ReviewedBy** | User |  |
| **ReviewedDate** | DateTime |  |
| **Status** | [EngagementStatus](#engagementstatus-enum) |  |
| **SubmittedBy** | User |  |
| **SubmittedDate** | DateTime |  |
| **TimephasedEditsOnly** | bool |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **ProjectEngagement(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
| **GetTimephased(DateTime start, DateTime end, TimeScale timescale, EngagementContourType contourType)** | [ProjectEngagementTimephasedCollection](#projectengagementtimephasedcollection-class) |  |
# ProjectEngagementCollection Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObjectCollection<[ProjectEngagement](#projectengagement-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [ProjectEngagement](#projectengagement-class) |  |
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
| **ProjectEngagementCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(ProjectEngagementCreationInformation parameters)** | [ProjectEngagement](#projectengagement-class) |  |
| **GetByGuid(Guid uid)** | [ProjectEngagement](#projectengagement-class) |  |
| **GetById(string objectId)** | [ProjectEngagement](#projectengagement-class) |  |
| **Remove(Engagement engagement)** | ClientResult\<bool\> |  |
| **Update()** | void |  |
# ProjectEngagementComment Class

Namespace: Microsoft.ProjectServer.Client

Base class: [EngagementComment](#engagementcomment-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **Author** | User |  |
| **Created** | DateTime |  |
| **Id** | Guid |  |
| **Message** | string |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **ProjectEngagementComment(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ProjectEngagementCreationInformation Class

Namespace: Microsoft.ProjectServer.Client

Base class: [EngagementCreationInformation](#engagementcreationinformation-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **Resource** | [EnterpriseResource](#enterpriseresource-class) |  |
| **TypeId** | string |  |
| **Description** | string |  |
| **Finish** | DateTime |  |
| **Id** | Guid |  |
| **MaxUnits** | double |  |
| **Start** | DateTime |  |
| **TimephasedPeriodData** | IEnumerable\<[EngagementTimephasedPeriodCreationInformation](#engagementtimephasedperiodcreationinformation-class)\> |  |
| **Work** | string |  |
| **WorkTimeSpan** | TimeSpan |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# ProjectEngagementPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **ApprovedFinish** | string |  |
| **ApprovedMaxUnits** | string |  |
| **ApprovedStart** | string |  |
| **ApprovedWork** | string |  |
| **ApprovedWorkTimeSpan** | string |  |
| **HasUnsubmittedChanges** | string |  |
| **RequestedFinish** | string |  |
| **RequestedMaxUnits** | string |  |
| **RequestedStart** | string |  |
| **RequestedWork** | string |  |
| **RequestedWorkTimeSpan** | string |  |
# ProjectEngagementTimephasedCollection Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObjectCollection<[ProjectEngagementTimephasedPeriod](#projectengagementtimephasedperiod-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [ProjectEngagementTimephasedPeriod](#projectengagementtimephasedperiod-class) |  |
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
| **ProjectEngagementTimephasedCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetByStart(DateTime date)** | [ProjectEngagementTimephasedPeriod](#projectengagementtimephasedperiod-class) |  |
# ProjectEngagementTimephasedPeriod Class

Namespace: Microsoft.ProjectServer.Client

Base class: [EngagementTimephasedPeriod](#engagementtimephasedperiod-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **End** | DateTime |  |
| **MaxUnits** | double |  |
| **Start** | DateTime |  |
| **Work** | string |  |
| **WorkTimeSpan** | TimeSpan |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **ProjectEngagementTimephasedPeriod(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ProjectObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **CheckedOutBy** | string |  |
| **CustomFields** | string |  |
| **Engagements** | string |  |
| **EnterpriseProjectType** | string |  |
| **Phase** | string |  |
| **ProjectSummaryTask** | string |  |
| **QueueJobs** | string |  |
| **Stage** | string |  |
# ProjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **ApprovedEnd** | string |  |
| **ApprovedStart** | string |  |
| **CalculateActualCosts** | string |  |
| **CalculatesActualCosts** | string |  |
| **CheckedOutDate** | string |  |
| **CheckOutDescription** | string |  |
| **CheckOutId** | string |  |
| **CreatedDate** | string |  |
| **CriticalSlackLimit** | string |  |
| **DefaultFinishTime** | string |  |
| **DefaultOvertimeRateUnits** | string |  |
| **DefaultStandardRateUnits** | string |  |
| **DefaultStartTime** | string |  |
| **HasMppPendingImport** | string |  |
| **HonorConstraints** | string |  |
| **Id** | string |  |
| **IsCheckedOut** | string |  |
| **LastPublishedDate** | string |  |
| **LastSavedDate** | string |  |
| **MoveActualIfLater** | string |  |
| **MoveActualToStatus** | string |  |
| **MoveRemainingIfEarlier** | string |  |
| **MoveRemainingToStatus** | string |  |
| **MultipleCriticalPaths** | string |  |
| **OptimizerDecision** | string |  |
| **PercentComplete** | string |  |
| **PlannerDecision** | string |  |
| **ProjectSiteUrl** | string |  |
| **ProjectType** | string |  |
| **ScheduledFromStart** | string |  |
| **SplitInProgress** | string |  |
| **SpreadActualCostsToStatus** | string |  |
| **SpreadPercentCompleteToStatus** | string |  |
| **SummaryTaskId** | string |  |
| **TaskListId** | string |  |
# ProjectResource Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ActualCost** | double |  |
| **ActualCostWorkPerformed** | string |  |
| **ActualCostWorkPerformedTimeSpan** | TimeSpan |  |
| **ActualOvertimeCost** | double |  |
| **ActualOvertimeWork** | string |  |
| **ActualOvertimeWorkTimeSpan** | TimeSpan |  |
| **ActualWork** | string |  |
| **ActualWorkTimeSpan** | TimeSpan |  |
| **AvailableFrom** | DateTime |  |
| **AvailableTo** | DateTime |  |
| **BaselineCost** | double |  |
| **BaselineWork** | string |  |
| **BaselineWorkTimeSpan** | TimeSpan |  |
| **BudetCostWorkPerformed** | double |  |
| **BudgetedCost** | double |  |
| **BudgetedCostWorkScheduled** | double |  |
| **BudgetedWork** | string |  |
| **BudgetedWorkTimeSpan** | TimeSpan |  |
| **Cost** | double |  |
| **CostVariance** | double |  |
| **CostVarianceAtCompletion** | double |  |
| **Created** | DateTime |  |
| **CurrentCostVariance** | double |  |
| **CustomFields** | [CustomFieldCollection](#customfieldcollection-class) |  |
| **EnterpriseResource** | [EnterpriseResource](#enterpriseresource-class) |  |
| **Finish** | DateTime |  |
| **Id** | Guid |  |
| **IsBudgeted** | bool |  |
| **IsGenericResource** | bool |  |
| **IsOverAllocated** | bool |  |
| **Modified** | DateTime |  |
| **Notes** | string |  |
| **OvertimeCost** | double |  |
| **OvertimeWork** | string |  |
| **OvertimeWorkTimeSpan** | TimeSpan |  |
| **PeakWork** | string |  |
| **PeakWorkTimeSpan** | TimeSpan |  |
| **PercentWorkComplete** | int |  |
| **RegularWork** | string |  |
| **RegularWorkTimeSpan** | TimeSpan |  |
| **RemainingCost** | double |  |
| **RemainingOvertimeCost** | double |  |
| **RemainingOvertimeWork** | string |  |
| **RemainingOvertimeWorkTimeSpan** | TimeSpan |  |
| **RemainingWork** | string |  |
| **RemainingWorkTimeSpan** | TimeSpan |  |
| **ScheduleCostVariance** | double |  |
| **Start** | DateTime |  |
| **Work** | string |  |
| **WorkTimeSpan** | TimeSpan |  |
| **WorkVariance** | string |  |
| **WorkVarianceTimeSpan** | TimeSpan |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **ProjectResource(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ProjectResourceCreationInformation Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Account** | string |  |
| **Email** | string |  |
| **Id** | Guid |  |
| **Name** | string |  |
| **Notes** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# ProjectResourceObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **CustomFields** | string |  |
| **EnterpriseResource** | string |  |
# ProjectResourcePropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **ActualCost** | string |  |
| **ActualCostWorkPerformed** | string |  |
| **ActualCostWorkPerformedTimeSpan** | string |  |
| **ActualOvertimeCost** | string |  |
| **ActualOvertimeWork** | string |  |
| **ActualOvertimeWorkTimeSpan** | string |  |
| **ActualWork** | string |  |
| **ActualWorkTimeSpan** | string |  |
| **AvailableFrom** | string |  |
| **AvailableTo** | string |  |
| **BaselineCost** | string |  |
| **BaselineWork** | string |  |
| **BaselineWorkTimeSpan** | string |  |
| **BudetCostWorkPerformed** | string |  |
| **BudgetedCost** | string |  |
| **BudgetedCostWorkScheduled** | string |  |
| **BudgetedWork** | string |  |
| **BudgetedWorkTimeSpan** | string |  |
| **Cost** | string |  |
| **CostVariance** | string |  |
| **CostVarianceAtCompletion** | string |  |
| **Created** | string |  |
| **CurrentCostVariance** | string |  |
| **Finish** | string |  |
| **Id** | string |  |
| **IsBudgeted** | string |  |
| **IsGenericResource** | string |  |
| **IsOverAllocated** | string |  |
| **Modified** | string |  |
| **Notes** | string |  |
| **OvertimeCost** | string |  |
| **OvertimeWork** | string |  |
| **OvertimeWorkTimeSpan** | string |  |
| **PeakWork** | string |  |
| **PeakWorkTimeSpan** | string |  |
| **PercentWorkComplete** | string |  |
| **RegularWork** | string |  |
| **RegularWorkTimeSpan** | string |  |
| **RemainingCost** | string |  |
| **RemainingOvertimeCost** | string |  |
| **RemainingOvertimeWork** | string |  |
| **RemainingOvertimeWorkTimeSpan** | string |  |
| **RemainingWork** | string |  |
| **RemainingWorkTimeSpan** | string |  |
| **ScheduleCostVariance** | string |  |
| **Start** | string |  |
| **Work** | string |  |
| **WorkTimeSpan** | string |  |
| **WorkVariance** | string |  |
| **WorkVarianceTimeSpan** | string |  |
# ProjectServer Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Calendars** | [CalendarCollection](#calendarcollection-class) |  |
| **CustomFields** | [CustomFieldCollection](#customfieldcollection-class) |  |
| **EngagementsTimephasedPageSize** | int |  |
| **EnterpriseProjectTypes** | [EnterpriseProjectTypeCollection](#enterpriseprojecttypecollection-class) |  |
| **EnterpriseResources** | [EnterpriseResourceCollection](#enterpriseresourcecollection-class) |  |
| **EnterpriseResourcesPageSize** | int |  |
| **EntityTypes** | [EntityTypes](#entitytypes-class) |  |
| **EventHandlers** | [EventHandlerCollection](#eventhandlercollection-class) |  |
| **Events** | [EventCollection](#eventcollection-class) |  |
| **IsDelegate** | bool |  |
| **IsReadOnly** | bool |  |
| **LookupTables** | [LookupTableCollection](#lookuptablecollection-class) |  |
| **Phases** | [PhaseCollection](#phasecollection-class) |  |
| **ProjectDetailPages** | [ProjectDetailPageCollection](#projectdetailpagecollection-class) |  |
| **Projects** | [ProjectCollection](#projectcollection-class) |  |
| **ProjectsPageSize** | int |  |
| **Stages** | [StageCollection](#stagecollection-class) |  |
| **TimeSheetPeriods** | [TimeSheetPeriodCollection](#timesheetperiodcollection-class) |  |
| **WorkflowActivities** | [WorkflowActivities](#workflowactivities-class) |  |
| **WorkflowDesigner** | [WorkflowDesigner](#workflowdesigner-class) |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **ProjectServer(ClientRuntimeContext context)** |  |
| **ProjectServer(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetDeletedPublishedAssignments(DateTime deletedDate)** | [DeletedPublishedAssignmentCollection](#deletedpublishedassignmentcollection-class) |  |
| **StopDelegation()** | void |  |
# ProjectServerData Class

Namespace: Microsoft.ProjectServer.Client

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
| **ProjectServerData(ClientRuntimeContext context)** |  |
| **ProjectServerData(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ProjectServerObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Calendars** | string |  |
| **CustomFields** | string |  |
| **EnterpriseProjectTypes** | string |  |
| **EnterpriseResources** | string |  |
| **EntityTypes** | string |  |
| **EventHandlers** | string |  |
| **Events** | string |  |
| **LookupTables** | string |  |
| **Phases** | string |  |
| **ProjectDetailPages** | string |  |
| **Projects** | string |  |
| **Stages** | string |  |
| **TimeSheetPeriods** | string |  |
| **WorkflowActivities** | string |  |
| **WorkflowDesigner** | string |  |
# ProjectServerPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **EngagementsTimephasedPageSize** | string |  |
| **EnterpriseResourcesPageSize** | string |  |
| **IsDelegate** | string |  |
| **IsReadOnly** | string |  |
| **ProjectsPageSize** | string |  |
# ProjectSummaryTask Class

Namespace: Microsoft.ProjectServer.Client

Base class: [Task](#task-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **FieldValues** | Dictionary\<string, Object\> |  |
| **Item** | Object |  |
| **ActualCost** | double |  |
| **ActualWork** | string |  |
| **ActualWorkTimeSpan** | TimeSpan |  |
| **BudgetWork** | string |  |
| **BudgetWorkTimeSpan** | TimeSpan |  |
| **Cost** | double |  |
| **Duration** | string |  |
| **DurationTimeSpan** | TimeSpan |  |
| **Finish** | DateTime |  |
| **FinishText** | string |  |
| **Name** | string |  |
| **PercentComplete** | int |  |
| **Priority** | int |  |
| **Start** | DateTime |  |
| **StartText** | string |  |
| **Work** | string |  |
| **WorkTimeSpan** | TimeSpan |  |
| **ActualCostWorkPerformed** | double |  |
| **ActualDuration** | string |  |
| **ActualDurationTimeSpan** | TimeSpan |  |
| **ActualOvertimeCost** | double |  |
| **ActualOvertimeWork** | string |  |
| **ActualOvertimeWorkTimeSpan** | TimeSpan |  |
| **BaselineCost** | double |  |
| **BaselineDuration** | string |  |
| **BaselineDurationTimeSpan** | TimeSpan |  |
| **BaselineFinish** | DateTime |  |
| **BaselineStart** | DateTime |  |
| **BaselineWork** | string |  |
| **BaselineWorkTimeSpan** | TimeSpan |  |
| **BudgetCost** | double |  |
| **BudgetedCostWorkPerformed** | double |  |
| **BudgetedCostWorkScheduled** | double |  |
| **Contact** | string |  |
| **CostPerformanceIndex** | double |  |
| **CostVariance** | double |  |
| **CostVarianceAtCompletion** | double |  |
| **CostVariancePercentage** | int |  |
| **Created** | DateTime |  |
| **CurrentCostVariance** | double |  |
| **CustomFields** | [CustomFieldCollection](#customfieldcollection-class) |  |
| **DurationVariance** | string |  |
| **DurationVarianceTimeSpan** | TimeSpan |  |
| **EarliestFinish** | DateTime |  |
| **EarliestStart** | DateTime |  |
| **EstimateAtCompletion** | double |  |
| **FinishSlack** | string |  |
| **FinishSlackTimeSpan** | TimeSpan |  |
| **FinishVariance** | string |  |
| **FinishVarianceTimeSpan** | TimeSpan |  |
| **FixedCostAccrual** | [FixedCostAccrual](#fixedcostaccrual-enum) |  |
| **FreeSlack** | string |  |
| **FreeSlackTimeSpan** | TimeSpan |  |
| **Id** | Guid |  |
| **IgnoreResourceCalendar** | bool |  |
| **IsCritical** | bool |  |
| **IsEffortDriven** | bool |  |
| **IsExternalTask** | bool |  |
| **IsOverAllocated** | bool |  |
| **IsRecurring** | bool |  |
| **IsRecurringSummary** | bool |  |
| **IsRolledUp** | bool |  |
| **IsSubProject** | bool |  |
| **IsSubProjectReadOnly** | bool |  |
| **IsSubProjectScheduledFromFinish** | bool |  |
| **IsSummary** | bool |  |
| **LatestFinish** | DateTime |  |
| **LatestStart** | DateTime |  |
| **LevelingDelay** | string |  |
| **LevelingDelayTimeSpan** | TimeSpan |  |
| **Modified** | DateTime |  |
| **Notes** | string |  |
| **OutlinePosition** | string |  |
| **OvertimeCost** | double |  |
| **OvertimeWork** | string |  |
| **OvertimeWorkTimeSpan** | TimeSpan |  |
| **PercentWorkComplete** | int |  |
| **PreLevelingFinish** | DateTime |  |
| **PreLevelingStart** | DateTime |  |
| **RegularWork** | string |  |
| **RegularWorkTimeSpan** | TimeSpan |  |
| **RemainingCost** | double |  |
| **RemainingOvertimeCost** | double |  |
| **RemainingOvertimeWork** | string |  |
| **RemainingOvertimeWorkTimeSpan** | TimeSpan |  |
| **RemainingWork** | string |  |
| **RemainingWorkTimeSpan** | TimeSpan |  |
| **Resume** | DateTime |  |
| **ScheduleCostVariance** | double |  |
| **ScheduledDuration** | string |  |
| **ScheduledDurationTimeSpan** | TimeSpan |  |
| **ScheduledFinish** | DateTime |  |
| **ScheduledStart** | DateTime |  |
| **SchedulePerformanceIndex** | double |  |
| **ScheduleVariancePercentage** | int |  |
| **StartSlack** | string |  |
| **StartSlackTimeSpan** | TimeSpan |  |
| **StartVariance** | string |  |
| **StartVarianceTimeSpan** | TimeSpan |  |
| **Stop** | DateTime |  |
| **SubProject** | [PublishedProject](#publishedproject-class) |  |
| **ToCompletePerformanceIndex** | double |  |
| **TotalSlack** | string |  |
| **TotalSlackTimeSpan** | TimeSpan |  |
| **WorkBreakdownStructure** | string |  |
| **WorkVariance** | string |  |
| **WorkVarianceTimeSpan** | TimeSpan |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **ProjectSummaryTask(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **RefreshLoad()** | void |  |
# ProjectSummaryTaskPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **ActualCost** | string |  |
| **ActualWork** | string |  |
| **ActualWorkTimeSpan** | string |  |
| **BudgetWork** | string |  |
| **BudgetWorkTimeSpan** | string |  |
| **Cost** | string |  |
| **Duration** | string |  |
| **DurationTimeSpan** | string |  |
| **Finish** | string |  |
| **FinishText** | string |  |
| **Name** | string |  |
| **PercentComplete** | string |  |
| **Priority** | string |  |
| **Start** | string |  |
| **StartText** | string |  |
| **Work** | string |  |
| **WorkTimeSpan** | string |  |
# ProjectType Enum

Namespace: Microsoft.ProjectServer.Client


## Values

| Name | Summary |
|---|---|
| **Project** |  |
| **MinRequestValue** |  |
| **Template** |  |
| **Global** |  |
| **ResGlobal** |  |
| **LightWeightProject** |  |
| **InsertedProject** |  |
| **MasterProject** |  |
| **TimesheetAdminProject** |  |
| **NewOffset** |  |
| **NewProject** |  |
| **NewTemplate** |  |
| **MaxRequestValue** |  |
| **NewGlobal** |  |
| **NewResGlobal** |  |
| **InactiveProject** |  |
| **InactiveOffset** |  |
| **InactiveTemplate** |  |
| **InactiveGlobal** |  |
| **NotSpecified** |  |
# ProjectUtilizationType Enum

Namespace: Microsoft.ProjectServer.Client


## Values

| Name | Summary |
|---|---|
| **ProjectPlan** |  |
| **ResourceEngagements** |  |
| **ProjectPlanUntil** |  |
# PublishedAssignment Class

Namespace: Microsoft.ProjectServer.Client

Base class: [Assignment](#assignment-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **FieldValues** | Dictionary\<string, Object\> |  |
| **Item** | Object |  |
| **ActualCost** | double |  |
| **ActualFinish** | DateTime |  |
| **ActualOvertimeWork** | string |  |
| **ActualOvertimeWorkTimeSpan** | TimeSpan |  |
| **ActualStart** | DateTime |  |
| **ActualWork** | string |  |
| **ActualWorkTimeSpan** | TimeSpan |  |
| **BudgetedCost** | double |  |
| **BudgetedWork** | string |  |
| **BudgetedWorkTimeSpan** | TimeSpan |  |
| **Cost** | double |  |
| **CostRateTable** | [CostRateTableName](#costratetablename-enum) |  |
| **DefaultBookingType** | [BookingType](#bookingtype-enum) |  |
| **Delay** | string |  |
| **DelayTimeSpan** | TimeSpan |  |
| **IsLockedByManager** | bool |  |
| **IsWorkResource** | bool |  |
| **OvertimeWork** | string |  |
| **OvertimeWorkTimeSpan** | TimeSpan |  |
| **Owner** | User |  |
| **Parent** | [PublishedAssignment](#publishedassignment-class) |  |
| **PercentWorkComplete** | int |  |
| **RegularWork** | string |  |
| **RegularWorkTimeSpan** | TimeSpan |  |
| **RemainingOvertimeWork** | string |  |
| **RemainingOvertimeWorkTimeSpan** | TimeSpan |  |
| **RemainingWork** | string |  |
| **RemainingWorkTimeSpan** | TimeSpan |  |
| **Resource** | [PublishedProjectResource](#publishedprojectresource-class) |  |
| **ResourceCapacity** | double |  |
| **Task** | [PublishedTask](#publishedtask-class) |  |
| **Work** | string |  |
| **WorkTimeSpan** | TimeSpan |  |
| **ActualCostWorkPerformed** | double |  |
| **ActualOvertimeCost** | double |  |
| **BaselineCost** | double |  |
| **BaselineCostPerUse** | double |  |
| **BaselineFinish** | DateTime |  |
| **BaselineStart** | DateTime |  |
| **BaselineWork** | string |  |
| **BaselineWorkTimeSpan** | TimeSpan |  |
| **BudgetedCostWorkPerformed** | double |  |
| **BudgetedCostWorkScheduled** | double |  |
| **CostVariance** | double |  |
| **CostVarianceAtCompletion** | double |  |
| **Created** | DateTime |  |
| **CurrentCostVariance** | double |  |
| **CustomFields** | [CustomFieldCollection](#customfieldcollection-class) |  |
| **Finish** | DateTime |  |
| **FinishVariance** | string |  |
| **FinishVarianceTimeSpan** | TimeSpan |  |
| **Id** | Guid |  |
| **IsConfirmed** | bool |  |
| **IsOverAllocated** | bool |  |
| **IsPublished** | bool |  |
| **IsResponsePending** | bool |  |
| **IsUpdateNeeded** | bool |  |
| **LevelingDelay** | string |  |
| **LevelingDelayTimeSpan** | TimeSpan |  |
| **Modified** | DateTime |  |
| **Notes** | string |  |
| **OvertimeCost** | double |  |
| **RemainingCost** | double |  |
| **RemainingOvertimeCost** | double |  |
| **Resume** | DateTime |  |
| **ScheduleCostVariance** | double |  |
| **Start** | DateTime |  |
| **StartVariance** | string |  |
| **StartVarianceTimeSpan** | TimeSpan |  |
| **Stop** | DateTime |  |
| **WorkContourType** | [WorkContourType](#workcontourtype-enum) |  |
| **WorkVariance** | string |  |
| **WorkVarianceTimeSpan** | TimeSpan |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **PublishedAssignment(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **RefreshLoad()** | void |  |
# PublishedAssignmentCollection Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObjectCollection<[PublishedAssignment](#publishedassignment-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [PublishedAssignment](#publishedassignment-class) |  |
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
| **PublishedAssignmentCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetByGuid(Guid uid)** | [PublishedAssignment](#publishedassignment-class) |  |
| **GetById(string objectId)** | [PublishedAssignment](#publishedassignment-class) |  |
# PublishedAssignmentObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Owner** | string |  |
| **Parent** | string |  |
| **Resource** | string |  |
| **Task** | string |  |
# PublishedAssignmentPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **ActualCost** | string |  |
| **ActualFinish** | string |  |
| **ActualOvertimeWork** | string |  |
| **ActualOvertimeWorkTimeSpan** | string |  |
| **ActualStart** | string |  |
| **ActualWork** | string |  |
| **ActualWorkTimeSpan** | string |  |
| **BudgetedCost** | string |  |
| **BudgetedWork** | string |  |
| **BudgetedWorkTimeSpan** | string |  |
| **Cost** | string |  |
| **CostRateTable** | string |  |
| **DefaultBookingType** | string |  |
| **Delay** | string |  |
| **DelayTimeSpan** | string |  |
| **IsLockedByManager** | string |  |
| **IsWorkResource** | string |  |
| **OvertimeWork** | string |  |
| **OvertimeWorkTimeSpan** | string |  |
| **PercentWorkComplete** | string |  |
| **RegularWork** | string |  |
| **RegularWorkTimeSpan** | string |  |
| **RemainingOvertimeWork** | string |  |
| **RemainingOvertimeWorkTimeSpan** | string |  |
| **RemainingWork** | string |  |
| **RemainingWorkTimeSpan** | string |  |
| **ResourceCapacity** | string |  |
| **Work** | string |  |
| **WorkTimeSpan** | string |  |
# PublishedProject Class

Namespace: Microsoft.ProjectServer.Client

Base class: [Project](#project-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **FieldValues** | Dictionary\<string, Object\> |  |
| **Item** | Object |  |
| **Assignments** | [PublishedAssignmentCollection](#publishedassignmentcollection-class) |  |
| **Calendar** | [Calendar](#calendar-class) |  |
| **CurrencyCode** | string |  |
| **CurrencyDigits** | int |  |
| **CurrencyPosition** | [CurrencySymbolPosition](#currencysymbolposition-enum) |  |
| **CurrencySymbol** | string |  |
| **CurrentDate** | DateTime |  |
| **DaysPerMonth** | short |  |
| **DefaultEffortDriven** | bool |  |
| **DefaultEstimatedDuration** | bool |  |
| **DefaultFixedCostAccrual** | [FixedCostAccrual](#fixedcostaccrual-enum) |  |
| **DefaultOvertimeRate** | double |  |
| **DefaultStandardRate** | double |  |
| **DefaultTaskType** | [TaskType](#tasktype-enum) |  |
| **DefaultWorkFormat** | [WorkFormat](#workformat-enum) |  |
| **Description** | string |  |
| **Draft** | [DraftProject](#draftproject-class) |  |
| **FinishDate** | DateTime |  |
| **FiscalYearStartMonth** | short |  |
| **IncludeCustomFields** | [PublishedProject](#publishedproject-class) |  |
| **IsEnterpriseProject** | bool |  |
| **MinutesPerDay** | int |  |
| **MinutesPerWeek** | int |  |
| **Name** | string |  |
| **NewTasksAreManual** | bool |  |
| **NumberFiscalYearFromStart** | bool |  |
| **Owner** | User |  |
| **ProjectIdentifier** | string |  |
| **ProjectResources** | [PublishedProjectResourceCollection](#publishedprojectresourcecollection-class) |  |
| **ProtectedActualsSynch** | bool |  |
| **ShowEstimatedDurations** | bool |  |
| **StartDate** | DateTime |  |
| **StatusDate** | DateTime |  |
| **TaskLinks** | [PublishedTaskLinkCollection](#publishedtasklinkcollection-class) |  |
| **Tasks** | [PublishedTaskCollection](#publishedtaskcollection-class) |  |
| **TrackingMode** | [TrackingMode](#trackingmode-enum) |  |
| **UtilizationDate** | DateTime |  |
| **UtilizationType** | [ProjectUtilizationType](#projectutilizationtype-enum) |  |
| **WeekStartDay** | short |  |
| **WinprojVersion** | decimal |  |
| **ApprovedEnd** | DateTime |  |
| **ApprovedStart** | DateTime |  |
| **CalculateActualCosts** | bool |  |
| **CalculatesActualCosts** | bool |  |
| **CheckedOutBy** | User |  |
| **CheckedOutDate** | DateTime |  |
| **CheckOutDescription** | string |  |
| **CheckOutId** | Guid |  |
| **CreatedDate** | DateTime |  |
| **CriticalSlackLimit** | int |  |
| **CustomFields** | [CustomFieldCollection](#customfieldcollection-class) |  |
| **DefaultFinishTime** | DateTime |  |
| **DefaultOvertimeRateUnits** | [OvertimeRateFormat](#overtimerateformat-enum) |  |
| **DefaultStandardRateUnits** | [StandardRateFormat](#standardrateformat-enum) |  |
| **DefaultStartTime** | DateTime |  |
| **Engagements** | [ProjectEngagementCollection](#projectengagementcollection-class) |  |
| **EnterpriseProjectType** | [EnterpriseProjectType](#enterpriseprojecttype-class) |  |
| **HasMppPendingImport** | bool |  |
| **HonorConstraints** | bool |  |
| **Id** | Guid |  |
| **IsCheckedOut** | bool |  |
| **LastPublishedDate** | DateTime |  |
| **LastSavedDate** | DateTime |  |
| **MoveActualIfLater** | bool |  |
| **MoveActualToStatus** | bool |  |
| **MoveRemainingIfEarlier** | bool |  |
| **MoveRemainingToStatus** | bool |  |
| **MultipleCriticalPaths** | bool |  |
| **OptimizerDecision** | [CommittedDecisionResult](#committeddecisionresult-enum) |  |
| **PercentComplete** | int |  |
| **Phase** | [Phase](#phase-class) |  |
| **PlannerDecision** | [CommittedDecisionResult](#committeddecisionresult-enum) |  |
| **ProjectSiteUrl** | string |  |
| **ProjectSummaryTask** | [ProjectSummaryTask](#projectsummarytask-class) |  |
| **ProjectType** | [ProjectType](#projecttype-enum) |  |
| **QueueJobs** | [QueueJobCollection](#queuejobcollection-class) |  |
| **ScheduledFromStart** | bool |  |
| **SplitInProgress** | bool |  |
| **SpreadActualCostsToStatus** | bool |  |
| **SpreadPercentCompleteToStatus** | bool |  |
| **Stage** | [Stage](#stage-class) |  |
| **SummaryTaskId** | Guid |  |
| **TaskListId** | Guid |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **PublishedProject(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **CheckOut()** | [DraftProject](#draftproject-class) |  |
| **CreateProjectSite(string siteName)** | void |  |
| **DeleteObject()** | [QueueJob](#queuejob-class) |  |
| **RefreshLoad()** | void |  |
| **SubmitToWorkflow()** | void |  |
| **UpdateVisibilityCustomFields()** | [QueueJob](#queuejob-class) |  |
# PublishedProjectObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Assignments** | string |  |
| **Calendar** | string |  |
| **Draft** | string |  |
| **IncludeCustomFields** | string |  |
| **Owner** | string |  |
| **ProjectResources** | string |  |
| **TaskLinks** | string |  |
| **Tasks** | string |  |
# PublishedProjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **CurrencyCode** | string |  |
| **CurrencyDigits** | string |  |
| **CurrencyPosition** | string |  |
| **CurrencySymbol** | string |  |
| **CurrentDate** | string |  |
| **DaysPerMonth** | string |  |
| **DefaultEffortDriven** | string |  |
| **DefaultEstimatedDuration** | string |  |
| **DefaultFixedCostAccrual** | string |  |
| **DefaultOvertimeRate** | string |  |
| **DefaultStandardRate** | string |  |
| **DefaultTaskType** | string |  |
| **DefaultWorkFormat** | string |  |
| **Description** | string |  |
| **FinishDate** | string |  |
| **FiscalYearStartMonth** | string |  |
| **IsEnterpriseProject** | string |  |
| **MinutesPerDay** | string |  |
| **MinutesPerWeek** | string |  |
| **Name** | string |  |
| **NewTasksAreManual** | string |  |
| **NumberFiscalYearFromStart** | string |  |
| **ProjectIdentifier** | string |  |
| **ProtectedActualsSynch** | string |  |
| **ShowEstimatedDurations** | string |  |
| **StartDate** | string |  |
| **StatusDate** | string |  |
| **TrackingMode** | string |  |
| **UtilizationDate** | string |  |
| **UtilizationType** | string |  |
| **WeekStartDay** | string |  |
| **WinprojVersion** | string |  |
# PublishedProjectResource Class

Namespace: Microsoft.ProjectServer.Client

Base class: [ProjectResource](#projectresource-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **FieldValues** | Dictionary\<string, Object\> |  |
| **Item** | Object |  |
| **Assignments** | [PublishedAssignmentCollection](#publishedassignmentcollection-class) |  |
| **CanLevel** | bool |  |
| **Code** | string |  |
| **CostAccrual** | [AccrueAt](#accrueat-enum) |  |
| **CostCenter** | string |  |
| **CostPerUse** | double |  |
| **DefaultAssignmentOwner** | User |  |
| **DefaultBookingType** | [BookingType](#bookingtype-enum) |  |
| **Email** | string |  |
| **Group** | string |  |
| **Initials** | string |  |
| **MaterialLabel** | string |  |
| **MaximumCapacity** | double |  |
| **Name** | string |  |
| **OvertimeRate** | double |  |
| **OvertimeRateUnits** | [OvertimeRateFormat](#overtimerateformat-enum) |  |
| **Phonetics** | string |  |
| **StandardRate** | double |  |
| **StandardRateUnits** | [StandardRateFormat](#standardrateformat-enum) |  |
| **ActualCost** | double |  |
| **ActualCostWorkPerformed** | string |  |
| **ActualCostWorkPerformedTimeSpan** | TimeSpan |  |
| **ActualOvertimeCost** | double |  |
| **ActualOvertimeWork** | string |  |
| **ActualOvertimeWorkTimeSpan** | TimeSpan |  |
| **ActualWork** | string |  |
| **ActualWorkTimeSpan** | TimeSpan |  |
| **AvailableFrom** | DateTime |  |
| **AvailableTo** | DateTime |  |
| **BaselineCost** | double |  |
| **BaselineWork** | string |  |
| **BaselineWorkTimeSpan** | TimeSpan |  |
| **BudetCostWorkPerformed** | double |  |
| **BudgetedCost** | double |  |
| **BudgetedCostWorkScheduled** | double |  |
| **BudgetedWork** | string |  |
| **BudgetedWorkTimeSpan** | TimeSpan |  |
| **Cost** | double |  |
| **CostVariance** | double |  |
| **CostVarianceAtCompletion** | double |  |
| **Created** | DateTime |  |
| **CurrentCostVariance** | double |  |
| **CustomFields** | [CustomFieldCollection](#customfieldcollection-class) |  |
| **EnterpriseResource** | [EnterpriseResource](#enterpriseresource-class) |  |
| **Finish** | DateTime |  |
| **Id** | Guid |  |
| **IsBudgeted** | bool |  |
| **IsGenericResource** | bool |  |
| **IsOverAllocated** | bool |  |
| **Modified** | DateTime |  |
| **Notes** | string |  |
| **OvertimeCost** | double |  |
| **OvertimeWork** | string |  |
| **OvertimeWorkTimeSpan** | TimeSpan |  |
| **PeakWork** | string |  |
| **PeakWorkTimeSpan** | TimeSpan |  |
| **PercentWorkComplete** | int |  |
| **RegularWork** | string |  |
| **RegularWorkTimeSpan** | TimeSpan |  |
| **RemainingCost** | double |  |
| **RemainingOvertimeCost** | double |  |
| **RemainingOvertimeWork** | string |  |
| **RemainingOvertimeWorkTimeSpan** | TimeSpan |  |
| **RemainingWork** | string |  |
| **RemainingWorkTimeSpan** | TimeSpan |  |
| **ScheduleCostVariance** | double |  |
| **Start** | DateTime |  |
| **Work** | string |  |
| **WorkTimeSpan** | TimeSpan |  |
| **WorkVariance** | string |  |
| **WorkVarianceTimeSpan** | TimeSpan |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **PublishedProjectResource(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **RefreshLoad()** | void |  |
# PublishedProjectResourceCollection Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObjectCollection<[PublishedProjectResource](#publishedprojectresource-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [PublishedProjectResource](#publishedprojectresource-class) |  |
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
| **PublishedProjectResourceCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetByGuid(Guid uid)** | [PublishedProjectResource](#publishedprojectresource-class) |  |
| **GetById(string objectId)** | [PublishedProjectResource](#publishedprojectresource-class) |  |
# PublishedProjectResourceObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Assignments** | string |  |
| **DefaultAssignmentOwner** | string |  |
# PublishedProjectResourcePropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **CanLevel** | string |  |
| **Code** | string |  |
| **CostAccrual** | string |  |
| **CostCenter** | string |  |
| **CostPerUse** | string |  |
| **DefaultBookingType** | string |  |
| **Email** | string |  |
| **Group** | string |  |
| **Initials** | string |  |
| **MaterialLabel** | string |  |
| **MaximumCapacity** | string |  |
| **Name** | string |  |
| **OvertimeRate** | string |  |
| **OvertimeRateUnits** | string |  |
| **Phonetics** | string |  |
| **StandardRate** | string |  |
| **StandardRateUnits** | string |  |
# PublishedTask Class

Namespace: Microsoft.ProjectServer.Client

Base class: [Task](#task-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **FieldValues** | Dictionary\<string, Object\> |  |
| **Item** | Object |  |
| **ActualCost** | double |  |
| **ActualFinish** | DateTime |  |
| **ActualStart** | DateTime |  |
| **ActualWork** | string |  |
| **ActualWorkTimeSpan** | TimeSpan |  |
| **Assignments** | [PublishedAssignmentCollection](#publishedassignmentcollection-class) |  |
| **BudgetWork** | string |  |
| **BudgetWorkTimeSpan** | TimeSpan |  |
| **Calendar** | [Calendar](#calendar-class) |  |
| **Completion** | DateTime |  |
| **ConstraintStartEnd** | DateTime |  |
| **ConstraintType** | [ConstraintType](#constrainttype-enum) |  |
| **Cost** | double |  |
| **Deadline** | DateTime |  |
| **Duration** | string |  |
| **DurationTimeSpan** | TimeSpan |  |
| **Finish** | DateTime |  |
| **FinishText** | string |  |
| **FixedCost** | double |  |
| **IsActive** | bool |  |
| **IsLockedByManager** | bool |  |
| **IsManual** | bool |  |
| **IsMarked** | bool |  |
| **IsMilestone** | bool |  |
| **LevelingAdjustsAssignments** | bool |  |
| **LevelingCanSplit** | bool |  |
| **Name** | string |  |
| **OutlineLevel** | int |  |
| **Parent** | [PublishedTask](#publishedtask-class) |  |
| **PercentComplete** | int |  |
| **PercentPhysicalWorkComplete** | int |  |
| **Predecessors** | [PublishedTaskLinkCollection](#publishedtasklinkcollection-class) |  |
| **Priority** | int |  |
| **RemainingDuration** | string |  |
| **RemainingDurationTimeSpan** | TimeSpan |  |
| **Start** | DateTime |  |
| **StartText** | string |  |
| **StatusManager** | User |  |
| **Successors** | [PublishedTaskLinkCollection](#publishedtasklinkcollection-class) |  |
| **TaskType** | [TaskType](#tasktype-enum) |  |
| **UsePercentPhysicalWorkComplete** | bool |  |
| **Work** | string |  |
| **WorkTimeSpan** | TimeSpan |  |
| **ActualCostWorkPerformed** | double |  |
| **ActualDuration** | string |  |
| **ActualDurationTimeSpan** | TimeSpan |  |
| **ActualOvertimeCost** | double |  |
| **ActualOvertimeWork** | string |  |
| **ActualOvertimeWorkTimeSpan** | TimeSpan |  |
| **BaselineCost** | double |  |
| **BaselineDuration** | string |  |
| **BaselineDurationTimeSpan** | TimeSpan |  |
| **BaselineFinish** | DateTime |  |
| **BaselineStart** | DateTime |  |
| **BaselineWork** | string |  |
| **BaselineWorkTimeSpan** | TimeSpan |  |
| **BudgetCost** | double |  |
| **BudgetedCostWorkPerformed** | double |  |
| **BudgetedCostWorkScheduled** | double |  |
| **Contact** | string |  |
| **CostPerformanceIndex** | double |  |
| **CostVariance** | double |  |
| **CostVarianceAtCompletion** | double |  |
| **CostVariancePercentage** | int |  |
| **Created** | DateTime |  |
| **CurrentCostVariance** | double |  |
| **CustomFields** | [CustomFieldCollection](#customfieldcollection-class) |  |
| **DurationVariance** | string |  |
| **DurationVarianceTimeSpan** | TimeSpan |  |
| **EarliestFinish** | DateTime |  |
| **EarliestStart** | DateTime |  |
| **EstimateAtCompletion** | double |  |
| **FinishSlack** | string |  |
| **FinishSlackTimeSpan** | TimeSpan |  |
| **FinishVariance** | string |  |
| **FinishVarianceTimeSpan** | TimeSpan |  |
| **FixedCostAccrual** | [FixedCostAccrual](#fixedcostaccrual-enum) |  |
| **FreeSlack** | string |  |
| **FreeSlackTimeSpan** | TimeSpan |  |
| **Id** | Guid |  |
| **IgnoreResourceCalendar** | bool |  |
| **IsCritical** | bool |  |
| **IsEffortDriven** | bool |  |
| **IsExternalTask** | bool |  |
| **IsOverAllocated** | bool |  |
| **IsRecurring** | bool |  |
| **IsRecurringSummary** | bool |  |
| **IsRolledUp** | bool |  |
| **IsSubProject** | bool |  |
| **IsSubProjectReadOnly** | bool |  |
| **IsSubProjectScheduledFromFinish** | bool |  |
| **IsSummary** | bool |  |
| **LatestFinish** | DateTime |  |
| **LatestStart** | DateTime |  |
| **LevelingDelay** | string |  |
| **LevelingDelayTimeSpan** | TimeSpan |  |
| **Modified** | DateTime |  |
| **Notes** | string |  |
| **OutlinePosition** | string |  |
| **OvertimeCost** | double |  |
| **OvertimeWork** | string |  |
| **OvertimeWorkTimeSpan** | TimeSpan |  |
| **PercentWorkComplete** | int |  |
| **PreLevelingFinish** | DateTime |  |
| **PreLevelingStart** | DateTime |  |
| **RegularWork** | string |  |
| **RegularWorkTimeSpan** | TimeSpan |  |
| **RemainingCost** | double |  |
| **RemainingOvertimeCost** | double |  |
| **RemainingOvertimeWork** | string |  |
| **RemainingOvertimeWorkTimeSpan** | TimeSpan |  |
| **RemainingWork** | string |  |
| **RemainingWorkTimeSpan** | TimeSpan |  |
| **Resume** | DateTime |  |
| **ScheduleCostVariance** | double |  |
| **ScheduledDuration** | string |  |
| **ScheduledDurationTimeSpan** | TimeSpan |  |
| **ScheduledFinish** | DateTime |  |
| **ScheduledStart** | DateTime |  |
| **SchedulePerformanceIndex** | double |  |
| **ScheduleVariancePercentage** | int |  |
| **StartSlack** | string |  |
| **StartSlackTimeSpan** | TimeSpan |  |
| **StartVariance** | string |  |
| **StartVarianceTimeSpan** | TimeSpan |  |
| **Stop** | DateTime |  |
| **SubProject** | [PublishedProject](#publishedproject-class) |  |
| **ToCompletePerformanceIndex** | double |  |
| **TotalSlack** | string |  |
| **TotalSlackTimeSpan** | TimeSpan |  |
| **WorkBreakdownStructure** | string |  |
| **WorkVariance** | string |  |
| **WorkVarianceTimeSpan** | TimeSpan |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **PublishedTask(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **RefreshLoad()** | void |  |
# PublishedTaskCollection Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObjectCollection<[PublishedTask](#publishedtask-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [PublishedTask](#publishedtask-class) |  |
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
| **PublishedTaskCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetByGuid(Guid uid)** | [PublishedTask](#publishedtask-class) |  |
| **GetById(string objectId)** | [PublishedTask](#publishedtask-class) |  |
# PublishedTaskLink Class

Namespace: Microsoft.ProjectServer.Client

Base class: [TaskLink](#tasklink-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **DependencyType** | [DependencyType](#dependencytype-enum) |  |
| **End** | [PublishedTask](#publishedtask-class) |  |
| **Start** | [PublishedTask](#publishedtask-class) |  |
| **Id** | Guid |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **PublishedTaskLink(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# PublishedTaskLinkCollection Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObjectCollection<[PublishedTaskLink](#publishedtasklink-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [PublishedTaskLink](#publishedtasklink-class) |  |
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
| **PublishedTaskLinkCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetByGuid(Guid uid)** | [PublishedTaskLink](#publishedtasklink-class) |  |
| **GetById(string objectId)** | [PublishedTaskLink](#publishedtasklink-class) |  |
# PublishedTaskLinkObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **End** | string |  |
| **Start** | string |  |
# PublishedTaskLinkPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **DependencyType** | string |  |
# PublishedTaskObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Assignments** | string |  |
| **Calendar** | string |  |
| **Parent** | string |  |
| **Predecessors** | string |  |
| **StatusManager** | string |  |
| **Successors** | string |  |
# PublishedTaskPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **ActualCost** | string |  |
| **ActualFinish** | string |  |
| **ActualStart** | string |  |
| **ActualWork** | string |  |
| **ActualWorkTimeSpan** | string |  |
| **BudgetWork** | string |  |
| **BudgetWorkTimeSpan** | string |  |
| **Completion** | string |  |
| **ConstraintStartEnd** | string |  |
| **ConstraintType** | string |  |
| **Cost** | string |  |
| **Deadline** | string |  |
| **Duration** | string |  |
| **DurationTimeSpan** | string |  |
| **Finish** | string |  |
| **FinishText** | string |  |
| **FixedCost** | string |  |
| **IsActive** | string |  |
| **IsLockedByManager** | string |  |
| **IsManual** | string |  |
| **IsMarked** | string |  |
| **IsMilestone** | string |  |
| **LevelingAdjustsAssignments** | string |  |
| **LevelingCanSplit** | string |  |
| **Name** | string |  |
| **OutlineLevel** | string |  |
| **PercentComplete** | string |  |
| **PercentPhysicalWorkComplete** | string |  |
| **Priority** | string |  |
| **RemainingDuration** | string |  |
| **RemainingDurationTimeSpan** | string |  |
| **Start** | string |  |
| **StartText** | string |  |
| **TaskType** | string |  |
| **UsePercentPhysicalWorkComplete** | string |  |
| **Work** | string |  |
| **WorkTimeSpan** | string |  |
# QueueJob Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Id** | Guid |  |
| **JobState** | [JobState](#jobstate-enum) |  |
| **MessageType** | [QueueMsgType](#queuemsgtype-enum) |  |
| **PercentComplete** | int |  |
| **Project** | [Project](#project-class) |  |
| **Submitter** | User |  |
| **WaitTime** | TimeSpan |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **QueueJob(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Cancel()** | void |  |
# QueueJobCollection Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObjectCollection<[QueueJob](#queuejob-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [QueueJob](#queuejob-class) |  |
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
| **QueueJobCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetByGuid(Guid uid)** | [QueueJob](#queuejob-class) |  |
| **GetById(string objectId)** | [QueueJob](#queuejob-class) |  |
# QueueJobObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Project** | string |  |
| **Submitter** | string |  |
# QueueJobPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Id** | string |  |
| **JobState** | string |  |
| **MessageType** | string |  |
| **PercentComplete** | string |  |
| **WaitTime** | string |  |
# QueueMsgType Enum

Namespace: Microsoft.ProjectServer.Client


## Values

| Name | Summary |
|---|---|
| **Unknown** |  |
| **ACProjectSave** |  |
| **AdSyncERP** |  |
| **AdSyncGroup** |  |
| **ArchiveCategories** |  |
| **ArchiveCustomFields** |  |
| **ArchiveGlobalProject** |  |
| **ArchiveResources** |  |
| **ArchiveSystemSettings** |  |
| **ArchiveViews** |  |
| **BumpPriority** |  |
| **CBSProjRendezvous** |  |
| **CBSRequest** |  |
| **CBSTsRendezvous** |  |
| **CreateProposalProject** |  |
| **CreateWssSite** |  |
| **DeleteWssSite** |  |
| **LWPUpgradeToProject** |  |
| **NotificationMessage** |  |
| **ProjectArchive** |  |
| **ProjectArchiveRetentionDelete** |  |
| **ProjectCheckIn** |  |
| **ProjectCreate** |  |
| **ProjectDelete** |  |
| **ProjectPublish** |  |
| **ProjectRename** |  |
| **ProjectRestore** |  |
| **ProjectReversePublish** |  |
| **ProjectUpdate** |  |
| **ProjectUpdateTeam** |  |
| **PublishNotifications** |  |
| **QueueCleanup** |  |
| **ReportingAttributeCubeSettingsSync** |  |
| **ReportingBaseCalendarSync** |  |
| **ReportingCustomFieldMetadataSync** |  |
| **ReportingEntityUserViewRefresh** |  |
| **ReportingFiscalPeriodsSync** |  |
| **ReportingLookupTableSync** |  |
| **ReportingProjectDelete** |  |
| **ReportingProjectPublish** |  |
| **ReportingResourcesCapacityRangeSync** |  |
| **ReportingResourceSync** |  |
| **ReportingTimesheetAdjust** |  |
| **ReportingTimesheetClassSync** |  |
| **ReportingTimesheetDelete** |  |
| **ReportingTimesheetPeriodDelete** |  |
| **ReportingTimesheetPeriodSync** |  |
| **ReportingTimesheetSave** |  |
| **ReportingTimesheetStatusSync** |  |
| **ReportingWSSSync** |  |
| **ResourcePlanCheckIn** |  |
| **ResourcePlanDelete** |  |
| **ResourcePlanPublish** |  |
| **ResourcePlanSave** |  |
| **RestoreCategories** |  |
| **RestoreCustomFields** |  |
| **RestoreGlobalProject** |  |
| **RestoreResources** |  |
| **RestoreSystemSettings** |  |
| **RestoreViews** |  |
| **RulesProcessAll** |  |
| **RulesProcessAllAutoForManager** |  |
| **RulesProcessAllForManager** |  |
| **RulesProcessSingleForManager** |  |
| **StatusApproval** |  |
| **Timer1** |  |
| **Timer10** |  |
| **Timer2** |  |
| **Timer3** |  |
| **Timer4** |  |
| **Timer5** |  |
| **Timer6** |  |
| **Timer7** |  |
| **Timer8** |  |
| **Timer9** |  |
| **TimerMessage** |  |
| **TimerRzNotify** |  |
| **TimerRzProj** |  |
| **TimerRzTS** |  |
| **TimesheetMessage** |  |
| **TimesheetDelete** |  |
| **TimesheetRecall** |  |
| **TimesheetReview** |  |
| **TimesheetSubmit** |  |
| **TimesheetUpdate** |  |
| **ReportingSyncGlobalData** |  |
| **SynchronizeMembershipForWssSite** |  |
| **SynchronizeSingleUserMembershipInWss** |  |
| **ReportingRefresh** |  |
| **UpdateScheduledProject** |  |
| **WorkflowStartWorkflow** |  |
| **AnalysisDelete** |  |
| **AnalysisCreate** |  |
| **AnalysisUpdate** |  |
| **PlannerSolutionCreate** |  |
| **PlannerSolutionDelete** |  |
| **OptimizerSolutionCreate** |  |
| **OptimizerSolutionDelete** |  |
| **TimesheetLineApproval** |  |
| **PeriodicTasks** |  |
| **PDPUpdateProjectImpacts** |  |
| **ExchangeSyncTasks** |  |
| **ReportingAttributeCubeDepartmentSync** |  |
| **ReportingTimesheetProjectAggregation** |  |
| **ReportingTimesheetAssignmentsUpgrade** |  |
| **WorkflowCheckinNotify** |  |
| **WorkflowChangeWorkflow** |  |
| **ProjectPublishSummary** |  |
| **ReportingOlapDatabaseSettingsSync** |  |
| **ReportingWorkflowMetadataSync** |  |
| **ReportWorkflowProjectDataSync** |  |
| **ReportEptSync** |  |
| **ReportingSummaryPublish** |  |
| **ReportingSolutionCommitedDecisionSync** |  |
| **WorkflowCommitNotify** |  |
| **ReportingTimesheetAssignmentsRefresh** |  |
| **UpdateProjectSitePath** |  |
| **AddSingleUserMembershipInWss** |  |
| **DeleteSingleUserMembershipInWss** |  |
| **TimeSheetUpdateResourceNonWorkingTime** |  |
| **SyncProjectEnterpriseEntities** |  |
| **LastMessage** |  |
| **ExchangeCalOofSync** |  |
| **PreparePSPermissionSynchronization** |  |
| **PSPermissionSynchronizePWASite** |  |
| **PSPermissionSynchronizeProjectSite** |  |
| **PreparePSProjectPermissionSynchronization** |  |
| **ScheduleWebPartSave** |  |
| **ProjectImportTaskList** |  |
| **TimesheetUpdateSRAForResource** |  |
| **ActiveMonitorCheck** |  |
| **ManagedModeTaskSynchronization** |  |
| **ResourcePlanMigrate** |  |
| **ReportingWSSIssueSync** |  |
| **ReportingWSSRiskSync** |  |
| **ReportingWSSDocSync** |  |
| **ReportingWSSDeliverableSync** |  |
# ReadyToLeaveProjectStageValue Enum

Namespace: Microsoft.ProjectServer.Client


## Values

| Name | Summary |
|---|---|
| **Ready** |  |
| **RequiresFieldsAndDrivers** |  |
| **RequiresDrivers** |  |
| **RequiresFields** |  |
# ResourceCalendarException Class

Namespace: Microsoft.ProjectServer.Client

Base class: [CalendarException](#calendarexception-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **Calendar** | [Calendar](#calendar-class) |  |
| **Finish** | DateTime |  |
| **Id** | int |  |
| **Name** | string |  |
| **RecurrenceDays** | [CalendarRecurrenceDays](#calendarrecurrencedays-enum) |  |
| **RecurrenceFrequency** | int |  |
| **RecurrenceMonth** | int |  |
| **RecurrenceMonthDay** | int |  |
| **RecurrenceType** | [CalendarRecurrenceType](#calendarrecurrencetype-enum) |  |
| **RecurrenceWeek** | [CalendarRecurrenceWeek](#calendarrecurrenceweek-enum) |  |
| **Shift1Finish** | int |  |
| **Shift1Start** | int |  |
| **Shift2Finish** | int |  |
| **Shift2Start** | int |  |
| **Shift3Finish** | int |  |
| **Shift3Start** | int |  |
| **Shift4Finish** | int |  |
| **Shift4Start** | int |  |
| **Shift5Finish** | int |  |
| **Shift5Start** | int |  |
| **Start** | DateTime |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **ResourceCalendarException(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ResourceEngagement Class

Namespace: Microsoft.ProjectServer.Client

Base class: [Engagement](#engagement-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **ApprovedFinish** | DateTime |  |
| **ApprovedMaxUnits** | double |  |
| **ApprovedStart** | DateTime |  |
| **ApprovedWork** | string |  |
| **ApprovedWorkTimeSpan** | TimeSpan |  |
| **RequestedFinish** | DateTime |  |
| **RequestedMaxUnits** | double |  |
| **RequestedStart** | DateTime |  |
| **RequestedWork** | string |  |
| **RequestedWorkTimeSpan** | TimeSpan |  |
| **Comments** | [EngagementCommentCollection](#engagementcommentcollection-class) |  |
| **CreatedDate** | DateTime |  |
| **Description** | string |  |
| **Id** | Guid |  |
| **Modified** | DateTime |  |
| **ModifiedBy** | User |  |
| **Project** | [Project](#project-class) |  |
| **Resource** | [EnterpriseResource](#enterpriseresource-class) |  |
| **ReviewedBy** | User |  |
| **ReviewedDate** | DateTime |  |
| **Status** | [EngagementStatus](#engagementstatus-enum) |  |
| **SubmittedBy** | User |  |
| **SubmittedDate** | DateTime |  |
| **TimephasedEditsOnly** | bool |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **ResourceEngagement(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
| **GetTimephased(DateTime start, DateTime end, TimeScale timescale, EngagementContourType contourType)** | [ResourceEngagementTimephasedCollection](#resourceengagementtimephasedcollection-class) |  |
# ResourceEngagementCollection Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObjectCollection<[ResourceEngagement](#resourceengagement-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [ResourceEngagement](#resourceengagement-class) |  |
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
| **ResourceEngagementCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetByGuid(Guid uid)** | [ResourceEngagement](#resourceengagement-class) |  |
| **GetById(string objectId)** | [ResourceEngagement](#resourceengagement-class) |  |
| **Remove(Engagement engagement)** | ClientResult\<bool\> |  |
| **Update()** | void |  |
# ResourceEngagementComment Class

Namespace: Microsoft.ProjectServer.Client

Base class: [EngagementComment](#engagementcomment-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **Author** | User |  |
| **Created** | DateTime |  |
| **Id** | Guid |  |
| **Message** | string |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **ResourceEngagementComment(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ResourceEngagementPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **ApprovedFinish** | string |  |
| **ApprovedMaxUnits** | string |  |
| **ApprovedStart** | string |  |
| **ApprovedWork** | string |  |
| **ApprovedWorkTimeSpan** | string |  |
| **RequestedFinish** | string |  |
| **RequestedMaxUnits** | string |  |
| **RequestedStart** | string |  |
| **RequestedWork** | string |  |
| **RequestedWorkTimeSpan** | string |  |
# ResourceEngagementTimephasedCollection Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObjectCollection<[ResourceEngagementTimephasedPeriod](#resourceengagementtimephasedperiod-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [ResourceEngagementTimephasedPeriod](#resourceengagementtimephasedperiod-class) |  |
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
| **ResourceEngagementTimephasedCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetByStart(DateTime date)** | [ResourceEngagementTimephasedPeriod](#resourceengagementtimephasedperiod-class) |  |
# ResourceEngagementTimephasedPeriod Class

Namespace: Microsoft.ProjectServer.Client

Base class: [EngagementTimephasedPeriod](#engagementtimephasedperiod-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **End** | DateTime |  |
| **MaxUnits** | double |  |
| **Start** | DateTime |  |
| **Work** | string |  |
| **WorkTimeSpan** | TimeSpan |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **ResourceEngagementTimephasedPeriod(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# ResourcePlan Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Assignments** | [PlanAssignmentCollection](#planassignmentcollection-class) |  |
| **Finish** | DateTime |  |
| **Id** | Guid |  |
| **Start** | DateTime |  |
| **UtilizationDate** | DateTime |  |
| **UtilizationType** | [UtilizationType](#utilizationtype-enum) |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **ResourcePlan(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | [QueueJob](#queuejob-class) |  |
| **ForceCheckIn()** | [QueueJob](#queuejob-class) |  |
| **Publish()** | [QueueJob](#queuejob-class) |  |
| **Update()** | [QueueJob](#queuejob-class) |  |
# ResourcePlanObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Assignments** | string |  |
# ResourcePlanPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Finish** | string |  |
| **Id** | string |  |
| **Start** | string |  |
| **UtilizationDate** | string |  |
| **UtilizationType** | string |  |
# ResourceType Enum

Namespace: Microsoft.ProjectServer.Client


## Values

| Name | Summary |
|---|---|
| **PureUser** |  |
| **WorkResource** |  |
| **CAN_LOG_IN_MAXIMUM** |  |
| **GenericWorkResource** |  |
| **MaterialResource** |  |
| **GenericMaterialResource** |  |
| **CostResources** |  |
| **GenericCostResources** |  |
| **IS_NONBUDGET_TYPE_MAXIMUM** |  |
| **BudgetWorkResource** |  |
| **BudgetCostResource** |  |
| **BudgetMaterialResource** |  |
| **GenericBudgetWorkResource** |  |
| **GenericBudgetCostResource** |  |
| **GenericBudgetMaterialResource** |  |
| **INACTIVATED_OFFSET** |  |
| **WinProjSummaryResource** |  |
| **WinProjUnassignedResource** |  |
| **WinProjUnknownResource** |  |
| **WinProjScratchpadResource** |  |
# ScriptTypeFactory Class

Namespace: Microsoft.ProjectServer.Client


## Methods

| Name | Returns | Summary |
|---|---|---|
| **CreateObjectFromScriptType(string scriptType, ClientRuntimeContext context)** | IFromJson |  |
# ServiceStatus Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **IsDelegate** | bool |  |
| **IsReadOnly** | bool |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **ServiceStatus(ClientRuntimeContext context, ProjectServer server)** |  |
| **ServiceStatus(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **StopDelegation()** | void |  |
# ServiceStatusPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **IsDelegate** | string |  |
| **IsReadOnly** | string |  |
# Stage Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Behavior** | [StrategicImpactBehavior](#strategicimpactbehavior-enum) |  |
| **CheckInRequired** | bool |  |
| **CustomFields** | [StageCustomFieldCollection](#stagecustomfieldcollection-class) |  |
| **Description** | string |  |
| **Id** | Guid |  |
| **Name** | string |  |
| **Phase** | [Phase](#phase-class) |  |
| **ProjectDetailPages** | [StageDetailPageCollection](#stagedetailpagecollection-class) |  |
| **SubmitDescription** | string |  |
| **WorkflowStatusPage** | [ProjectDetailPage](#projectdetailpage-class) |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **Stage(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
# StageCollection Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObjectCollection<[Stage](#stage-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [Stage](#stage-class) |  |
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
| **StageCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(StageCreationInformation parameters)** | [Stage](#stage-class) |  |
| **GetByGuid(Guid uid)** | [Stage](#stage-class) |  |
| **GetById(string objectId)** | [Stage](#stage-class) |  |
| **Remove(Stage stage)** | ClientResult\<bool\> |  |
| **Update()** | void |  |
# StageCreationInformation Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Behavior** | [StrategicImpactBehavior](#strategicimpactbehavior-enum) |  |
| **CheckInRequired** | bool |  |
| **CustomFields** | IEnumerable\<[StageCustomFieldCreationInformation](#stagecustomfieldcreationinformation-class)\> |  |
| **Description** | string |  |
| **Id** | Guid |  |
| **Name** | string |  |
| **PhaseId** | Guid |  |
| **ProjectDetailPages** | IEnumerable\<[StageDetailPageCreationInformation](#stagedetailpagecreationinformation-class)\> |  |
| **SubmitDescription** | string |  |
| **WorkflowStatusPageId** | Guid |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# StageCustomField Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Id** | Guid |  |
| **Name** | string |  |
| **ReadOnly** | bool |  |
| **Required** | bool |  |
| **Stage** | [Stage](#stage-class) |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **StageCustomField(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
# StageCustomFieldCollection Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObjectCollection<[StageCustomField](#stagecustomfield-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [StageCustomField](#stagecustomfield-class) |  |
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
| **StageCustomFieldCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(StageCustomFieldCreationInformation creationInfo)** | [StageCustomField](#stagecustomfield-class) |  |
| **GetByGuid(Guid uid)** | [StageCustomField](#stagecustomfield-class) |  |
| **GetById(string objectId)** | [StageCustomField](#stagecustomfield-class) |  |
| **Remove(StageCustomField field)** | ClientResult\<bool\> |  |
# StageCustomFieldCreationInformation Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Id** | Guid |  |
| **ReadOnly** | bool |  |
| **Required** | bool |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# StageCustomFieldObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Stage** | string |  |
# StageCustomFieldPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Id** | string |  |
| **Name** | string |  |
| **ReadOnly** | string |  |
| **Required** | string |  |
# StageDetailPage Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Description** | string |  |
| **Id** | Guid |  |
| **Page** | [ProjectDetailPage](#projectdetailpage-class) |  |
| **Position** | int |  |
| **RequiresAttention** | bool |  |
| **Stage** | [Stage](#stage-class) |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **StageDetailPage(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
# StageDetailPageCollection Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObjectCollection<[StageDetailPage](#stagedetailpage-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [StageDetailPage](#stagedetailpage-class) |  |
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
| **StageDetailPageCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(StageDetailPageCreationInformation parameters)** | [StageDetailPage](#stagedetailpage-class) |  |
| **GetByGuid(Guid uid)** | [StageDetailPage](#stagedetailpage-class) |  |
| **GetById(string objectId)** | [StageDetailPage](#stagedetailpage-class) |  |
| **Remove(StageDetailPage pdp)** | ClientResult\<bool\> |  |
# StageDetailPageCreationInformation Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Description** | string |  |
| **Id** | Guid |  |
| **Position** | int |  |
| **RequiresAttention** | bool |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# StageDetailPageObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Page** | string |  |
| **Stage** | string |  |
# StageDetailPagePropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Description** | string |  |
| **Id** | string |  |
| **Position** | string |  |
| **RequiresAttention** | string |  |
# StageObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **CustomFields** | string |  |
| **Phase** | string |  |
| **ProjectDetailPages** | string |  |
| **WorkflowStatusPage** | string |  |
# StagePropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Behavior** | string |  |
| **CheckInRequired** | string |  |
| **Description** | string |  |
| **Id** | string |  |
| **Name** | string |  |
| **SubmitDescription** | string |  |
# StandardRateFormat Enum

Namespace: Microsoft.ProjectServer.Client


## Values

| Name | Summary |
|---|---|
| **Minute** |  |
| **Hour** |  |
| **Day** |  |
| **Week** |  |
| **Month** |  |
| **Year** |  |
| **Material** |  |
# StatusApprovalType Enum

Namespace: Microsoft.ProjectServer.Client


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **Accepted** |  |
| **Rejected** |  |
# StatusAssignment Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **FieldValues** | Dictionary\<string, Object\> |  |
| **Item** | Object |  |
| **ActualFinish** | DateTime |  |
| **ActualOvertime** | string |  |
| **ActualOvertimeTimeSpan** | TimeSpan |  |
| **ActualStart** | DateTime |  |
| **ActualWork** | string |  |
| **ActualWorkTimeSpan** | TimeSpan |  |
| **ApprovalStatus** | [StatusApprovalType](#statusapprovaltype-enum) |  |
| **Comments** | string |  |
| **CustomFields** | [CustomFieldCollection](#customfieldcollection-class) |  |
| **Finish** | DateTime |  |
| **History** | [StatusAssignmentHistoryLineCollection](#statusassignmenthistorylinecollection-class) |  |
| **Id** | Guid |  |
| **IsConfirmed** | bool |  |
| **Modified** | DateTime |  |
| **Name** | string |  |
| **Overtime** | string |  |
| **OvertimeTimeSpan** | TimeSpan |  |
| **PercentComplete** | short |  |
| **Project** | [PublishedProject](#publishedproject-class) |  |
| **RegularWork** | string |  |
| **RegularWorkTimeSpan** | TimeSpan |  |
| **RemainingOvertime** | string |  |
| **RemainingOvertimeTimeSpan** | TimeSpan |  |
| **RemainingWork** | string |  |
| **RemainingWorkTimeSpan** | TimeSpan |  |
| **Resource** | [EnterpriseResource](#enterpriseresource-class) |  |
| **Start** | DateTime |  |
| **Task** | [StatusTask](#statustask-class) |  |
| **Work** | string |  |
| **WorkTimeSpan** | TimeSpan |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **StatusAssignment(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
| **RefreshLoad()** | void |  |
| **SubmitStatusUpdates(string comment)** | void |  |
# StatusAssignmentCollection Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObjectCollection<[StatusAssignment](#statusassignment-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [StatusAssignment](#statusassignment-class) |  |
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
| **StatusAssignmentCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(StatusAssignmentCreationInformation parameters)** | [StatusAssignment](#statusassignment-class) |  |
| **GetByGuid(Guid uid)** | [StatusAssignment](#statusassignment-class) |  |
| **GetById(string objectId)** | [StatusAssignment](#statusassignment-class) |  |
| **GetTimePhase(DateTime start, DateTime end)** | [TimePhase](#timephase-class) |  |
| **Remove(StatusAssignment assignment)** | ClientResult\<bool\> |  |
| **SubmitAllStatusUpdates(string comment)** | void |  |
| **Update()** | void |  |
# StatusAssignmentCreationInformation Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Comment** | string |  |
| **Id** | Guid |  |
| **ProjectId** | Guid |  |
| **Task** | [StatusTaskCreationInformation](#statustaskcreationinformation-class) |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# StatusAssignmentHistoryLine Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Author** | User |  |
| **Comment** | string |  |
| **Decision** | [StatusApprovalType](#statusapprovaltype-enum) |  |
| **Id** | Guid |  |
| **Submitted** | DateTime |  |
| **UpdateType** | [StatusUpdateType](#statusupdatetype-enum) |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **StatusAssignmentHistoryLine(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# StatusAssignmentHistoryLineCollection Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObjectCollection<[StatusAssignmentHistoryLine](#statusassignmenthistoryline-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [StatusAssignmentHistoryLine](#statusassignmenthistoryline-class) |  |
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
| **StatusAssignmentHistoryLineCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetById(string objectId)** | [StatusAssignmentHistoryLine](#statusassignmenthistoryline-class) |  |
# StatusAssignmentHistoryLineObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Author** | string |  |
# StatusAssignmentHistoryLinePropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Comment** | string |  |
| **Decision** | string |  |
| **Id** | string |  |
| **Submitted** | string |  |
| **UpdateType** | string |  |
# StatusAssignmentObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **CustomFields** | string |  |
| **History** | string |  |
| **Project** | string |  |
| **Resource** | string |  |
| **Task** | string |  |
# StatusAssignmentPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **ActualFinish** | string |  |
| **ActualOvertime** | string |  |
| **ActualOvertimeTimeSpan** | string |  |
| **ActualStart** | string |  |
| **ActualWork** | string |  |
| **ActualWorkTimeSpan** | string |  |
| **ApprovalStatus** | string |  |
| **Comments** | string |  |
| **Finish** | string |  |
| **Id** | string |  |
| **IsConfirmed** | string |  |
| **Modified** | string |  |
| **Name** | string |  |
| **Overtime** | string |  |
| **OvertimeTimeSpan** | string |  |
| **PercentComplete** | string |  |
| **RegularWork** | string |  |
| **RegularWorkTimeSpan** | string |  |
| **RemainingOvertime** | string |  |
| **RemainingOvertimeTimeSpan** | string |  |
| **RemainingWork** | string |  |
| **RemainingWorkTimeSpan** | string |  |
| **Start** | string |  |
| **Work** | string |  |
| **WorkTimeSpan** | string |  |
# StatusTask Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **FieldValues** | Dictionary\<string, Object\> |  |
| **Item** | Object |  |
| **ActualWork** | string |  |
| **ActualWorkTimeSpan** | TimeSpan |  |
| **CustomFields** | [CustomFieldCollection](#customfieldcollection-class) |  |
| **Deadline** | DateTime |  |
| **Duration** | string |  |
| **DurationTimeSpan** | TimeSpan |  |
| **Finish** | DateTime |  |
| **Id** | Guid |  |
| **Name** | string |  |
| **Overtime** | string |  |
| **OvertimeTimeSpan** | TimeSpan |  |
| **PercentComplete** | short |  |
| **PercentWorkComplete** | short |  |
| **PhysicalPercentComplete** | short |  |
| **ProjectTaskId** | Guid |  |
| **RegularWork** | string |  |
| **RegularWorkTimeSpan** | TimeSpan |  |
| **RemainingDuration** | string |  |
| **RemainingDurationTimeSpan** | TimeSpan |  |
| **RemainingOvertime** | string |  |
| **RemainingOvertimeTimeSpan** | TimeSpan |  |
| **RemainingWork** | string |  |
| **RemainingWorkTimeSpan** | TimeSpan |  |
| **Resume** | DateTime |  |
| **Start** | DateTime |  |
| **StatusManager** | User |  |
| **Work** | string |  |
| **WorkTimeSpan** | TimeSpan |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **StatusTask(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **RefreshLoad()** | void |  |
# StatusTaskCreationInformation Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Finish** | DateTime |  |
| **Id** | Guid |  |
| **Name** | string |  |
| **ParentId** | Guid |  |
| **Start** | DateTime |  |
| **Work** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# StatusTaskObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **CustomFields** | string |  |
| **StatusManager** | string |  |
# StatusTaskPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **ActualWork** | string |  |
| **ActualWorkTimeSpan** | string |  |
| **Deadline** | string |  |
| **Duration** | string |  |
| **DurationTimeSpan** | string |  |
| **Finish** | string |  |
| **Id** | string |  |
| **Name** | string |  |
| **Overtime** | string |  |
| **OvertimeTimeSpan** | string |  |
| **PercentComplete** | string |  |
| **PercentWorkComplete** | string |  |
| **PhysicalPercentComplete** | string |  |
| **ProjectTaskId** | string |  |
| **RegularWork** | string |  |
| **RegularWorkTimeSpan** | string |  |
| **RemainingDuration** | string |  |
| **RemainingDurationTimeSpan** | string |  |
| **RemainingOvertime** | string |  |
| **RemainingOvertimeTimeSpan** | string |  |
| **RemainingWork** | string |  |
| **RemainingWorkTimeSpan** | string |  |
| **Resume** | string |  |
| **Start** | string |  |
| **Work** | string |  |
| **WorkTimeSpan** | string |  |
# StatusUpdateType Enum

Namespace: Microsoft.ProjectServer.Client


## Values

| Name | Summary |
|---|---|
| **Update** |  |
| **Decline** |  |
| **CreateTask** |  |
| **Delegate** |  |
| **CreateAssignment** |  |
| **TeamDelegate** |  |
| **DeleteTask** |  |
| **DeleteAssignment** |  |
# StrategicImpactBehavior Enum

Namespace: Microsoft.ProjectServer.Client


## Values

| Name | Summary |
|---|---|
| **NotSpecified** |  |
| **ReadOnly** |  |
| **ReadWrite** |  |
| **Required** |  |
# Task Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ActualCostWorkPerformed** | double |  |
| **ActualDuration** | string |  |
| **ActualDurationTimeSpan** | TimeSpan |  |
| **ActualOvertimeCost** | double |  |
| **ActualOvertimeWork** | string |  |
| **ActualOvertimeWorkTimeSpan** | TimeSpan |  |
| **BaselineCost** | double |  |
| **BaselineDuration** | string |  |
| **BaselineDurationTimeSpan** | TimeSpan |  |
| **BaselineFinish** | DateTime |  |
| **BaselineStart** | DateTime |  |
| **BaselineWork** | string |  |
| **BaselineWorkTimeSpan** | TimeSpan |  |
| **BudgetCost** | double |  |
| **BudgetedCostWorkPerformed** | double |  |
| **BudgetedCostWorkScheduled** | double |  |
| **Contact** | string |  |
| **CostPerformanceIndex** | double |  |
| **CostVariance** | double |  |
| **CostVarianceAtCompletion** | double |  |
| **CostVariancePercentage** | int |  |
| **Created** | DateTime |  |
| **CurrentCostVariance** | double |  |
| **CustomFields** | [CustomFieldCollection](#customfieldcollection-class) |  |
| **DurationVariance** | string |  |
| **DurationVarianceTimeSpan** | TimeSpan |  |
| **EarliestFinish** | DateTime |  |
| **EarliestStart** | DateTime |  |
| **EstimateAtCompletion** | double |  |
| **FinishSlack** | string |  |
| **FinishSlackTimeSpan** | TimeSpan |  |
| **FinishVariance** | string |  |
| **FinishVarianceTimeSpan** | TimeSpan |  |
| **FixedCostAccrual** | [FixedCostAccrual](#fixedcostaccrual-enum) |  |
| **FreeSlack** | string |  |
| **FreeSlackTimeSpan** | TimeSpan |  |
| **Id** | Guid |  |
| **IgnoreResourceCalendar** | bool |  |
| **IsCritical** | bool |  |
| **IsEffortDriven** | bool |  |
| **IsExternalTask** | bool |  |
| **IsOverAllocated** | bool |  |
| **IsRecurring** | bool |  |
| **IsRecurringSummary** | bool |  |
| **IsRolledUp** | bool |  |
| **IsSubProject** | bool |  |
| **IsSubProjectReadOnly** | bool |  |
| **IsSubProjectScheduledFromFinish** | bool |  |
| **IsSummary** | bool |  |
| **LatestFinish** | DateTime |  |
| **LatestStart** | DateTime |  |
| **LevelingDelay** | string |  |
| **LevelingDelayTimeSpan** | TimeSpan |  |
| **Modified** | DateTime |  |
| **Notes** | string |  |
| **OutlinePosition** | string |  |
| **OvertimeCost** | double |  |
| **OvertimeWork** | string |  |
| **OvertimeWorkTimeSpan** | TimeSpan |  |
| **PercentWorkComplete** | int |  |
| **PreLevelingFinish** | DateTime |  |
| **PreLevelingStart** | DateTime |  |
| **RegularWork** | string |  |
| **RegularWorkTimeSpan** | TimeSpan |  |
| **RemainingCost** | double |  |
| **RemainingOvertimeCost** | double |  |
| **RemainingOvertimeWork** | string |  |
| **RemainingOvertimeWorkTimeSpan** | TimeSpan |  |
| **RemainingWork** | string |  |
| **RemainingWorkTimeSpan** | TimeSpan |  |
| **Resume** | DateTime |  |
| **ScheduleCostVariance** | double |  |
| **ScheduledDuration** | string |  |
| **ScheduledDurationTimeSpan** | TimeSpan |  |
| **ScheduledFinish** | DateTime |  |
| **ScheduledStart** | DateTime |  |
| **SchedulePerformanceIndex** | double |  |
| **ScheduleVariancePercentage** | int |  |
| **StartSlack** | string |  |
| **StartSlackTimeSpan** | TimeSpan |  |
| **StartVariance** | string |  |
| **StartVarianceTimeSpan** | TimeSpan |  |
| **Stop** | DateTime |  |
| **SubProject** | [PublishedProject](#publishedproject-class) |  |
| **ToCompletePerformanceIndex** | double |  |
| **TotalSlack** | string |  |
| **TotalSlackTimeSpan** | TimeSpan |  |
| **WorkBreakdownStructure** | string |  |
| **WorkVariance** | string |  |
| **WorkVarianceTimeSpan** | TimeSpan |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **Task(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# TaskCreationInformation Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AddAfterId** | Guid |  |
| **Duration** | string |  |
| **Finish** | DateTime |  |
| **Id** | Guid |  |
| **IsManual** | bool |  |
| **Name** | string |  |
| **Notes** | string |  |
| **ParentId** | Guid |  |
| **Start** | DateTime |  |
| **StatusManager** | User |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# TaskLink Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Id** | Guid |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **TaskLink(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# TaskLinkCreationInformation Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **DependencyType** | [DependencyType](#dependencytype-enum) |  |
| **EndId** | Guid |  |
| **Id** | Guid |  |
| **StartId** | Guid |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# TaskLinkPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Id** | string |  |
# TaskObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **CustomFields** | string |  |
| **SubProject** | string |  |
# TaskPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **ActualCostWorkPerformed** | string |  |
| **ActualDuration** | string |  |
| **ActualDurationTimeSpan** | string |  |
| **ActualOvertimeCost** | string |  |
| **ActualOvertimeWork** | string |  |
| **ActualOvertimeWorkTimeSpan** | string |  |
| **BaselineCost** | string |  |
| **BaselineDuration** | string |  |
| **BaselineDurationTimeSpan** | string |  |
| **BaselineFinish** | string |  |
| **BaselineStart** | string |  |
| **BaselineWork** | string |  |
| **BaselineWorkTimeSpan** | string |  |
| **BudgetCost** | string |  |
| **BudgetedCostWorkPerformed** | string |  |
| **BudgetedCostWorkScheduled** | string |  |
| **Contact** | string |  |
| **CostPerformanceIndex** | string |  |
| **CostVariance** | string |  |
| **CostVarianceAtCompletion** | string |  |
| **CostVariancePercentage** | string |  |
| **Created** | string |  |
| **CurrentCostVariance** | string |  |
| **DurationVariance** | string |  |
| **DurationVarianceTimeSpan** | string |  |
| **EarliestFinish** | string |  |
| **EarliestStart** | string |  |
| **EstimateAtCompletion** | string |  |
| **FinishSlack** | string |  |
| **FinishSlackTimeSpan** | string |  |
| **FinishVariance** | string |  |
| **FinishVarianceTimeSpan** | string |  |
| **FixedCostAccrual** | string |  |
| **FreeSlack** | string |  |
| **FreeSlackTimeSpan** | string |  |
| **Id** | string |  |
| **IgnoreResourceCalendar** | string |  |
| **IsCritical** | string |  |
| **IsEffortDriven** | string |  |
| **IsExternalTask** | string |  |
| **IsOverAllocated** | string |  |
| **IsRecurring** | string |  |
| **IsRecurringSummary** | string |  |
| **IsRolledUp** | string |  |
| **IsSubProject** | string |  |
| **IsSubProjectReadOnly** | string |  |
| **IsSubProjectScheduledFromFinish** | string |  |
| **IsSummary** | string |  |
| **LatestFinish** | string |  |
| **LatestStart** | string |  |
| **LevelingDelay** | string |  |
| **LevelingDelayTimeSpan** | string |  |
| **Modified** | string |  |
| **Notes** | string |  |
| **OutlinePosition** | string |  |
| **OvertimeCost** | string |  |
| **OvertimeWork** | string |  |
| **OvertimeWorkTimeSpan** | string |  |
| **PercentWorkComplete** | string |  |
| **PreLevelingFinish** | string |  |
| **PreLevelingStart** | string |  |
| **RegularWork** | string |  |
| **RegularWorkTimeSpan** | string |  |
| **RemainingCost** | string |  |
| **RemainingOvertimeCost** | string |  |
| **RemainingOvertimeWork** | string |  |
| **RemainingOvertimeWorkTimeSpan** | string |  |
| **RemainingWork** | string |  |
| **RemainingWorkTimeSpan** | string |  |
| **Resume** | string |  |
| **ScheduleCostVariance** | string |  |
| **ScheduledDuration** | string |  |
| **ScheduledDurationTimeSpan** | string |  |
| **ScheduledFinish** | string |  |
| **ScheduledStart** | string |  |
| **SchedulePerformanceIndex** | string |  |
| **ScheduleVariancePercentage** | string |  |
| **StartSlack** | string |  |
| **StartSlackTimeSpan** | string |  |
| **StartVariance** | string |  |
| **StartVarianceTimeSpan** | string |  |
| **Stop** | string |  |
| **ToCompletePerformanceIndex** | string |  |
| **TotalSlack** | string |  |
| **TotalSlackTimeSpan** | string |  |
| **WorkBreakdownStructure** | string |  |
| **WorkVariance** | string |  |
| **WorkVarianceTimeSpan** | string |  |
# TaskType Enum

Namespace: Microsoft.ProjectServer.Client


## Values

| Name | Summary |
|---|---|
| **FixedUnits** |  |
| **FixedDuration** |  |
| **FixedWork** |  |
| **Dummy** |  |
# TimePhase Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Assignments** | [StatusAssignmentCollection](#statusassignmentcollection-class) |  |
| **End** | DateTime |  |
| **Start** | DateTime |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **TimePhase(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# TimePhaseObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Assignments** | string |  |
# TimePhasePropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **End** | string |  |
| **Start** | string |  |
# TimeScale Enum

Namespace: Microsoft.ProjectServer.Client


## Values

| Name | Summary |
|---|---|
| **Days** |  |
| **Weeks** |  |
| **Months** |  |
| **Quarters** |  |
| **Years** |  |
# TimeSheet Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Comments** | string |  |
| **Creator** | User |  |
| **EntryMode** | [TimeSheetEntryMode](#timesheetentrymode-enum) |  |
| **Id** | Guid |  |
| **IsControlledByOwner** | bool |  |
| **IsProcessed** | bool |  |
| **Lines** | [TimeSheetLineCollection](#timesheetlinecollection-class) |  |
| **Manager** | User |  |
| **Name** | string |  |
| **Period** | [TimeSheetPeriod](#timesheetperiod-class) |  |
| **Status** | [TimeSheetStatus](#timesheetstatus-enum) |  |
| **TotalActualWork** | string |  |
| **TotalActualWorkTimeSpan** | TimeSpan |  |
| **TotalNonBillableOvertimeWork** | string |  |
| **TotalNonBillableOvertimeWorkTimeSpan** | TimeSpan |  |
| **TotalNonBillableWork** | string |  |
| **TotalNonBillableWorkTimeSpan** | TimeSpan |  |
| **TotalOvertimeWork** | string |  |
| **TotalOvertimeWorkTimeSpan** | TimeSpan |  |
| **TotalWork** | string |  |
| **TotalWorkTimeSpan** | TimeSpan |  |
| **WeekStartsOn** | byte |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **TimeSheet(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
| **Recall()** | void |  |
| **Submit(string comment)** | void |  |
| **Update()** | void |  |
# TimeSheetEntryMode Enum

Namespace: Microsoft.ProjectServer.Client


## Values

| Name | Summary |
|---|---|
| **NotSpecified** |  |
| **Daily** |  |
| **Weekly** |  |
# TimeSheetLine Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Assignment** | [PublishedAssignment](#publishedassignment-class) |  |
| **Comment** | string |  |
| **Id** | Guid |  |
| **LineClass** | [TimeSheetLineClass](#timesheetlineclass-enum) |  |
| **ProjectName** | string |  |
| **Status** | [TimeSheetLineStatus](#timesheetlinestatus-enum) |  |
| **TaskName** | string |  |
| **TimeSheet** | [TimeSheet](#timesheet-class) |  |
| **TotalWork** | string |  |
| **TotalWorkTimeSpan** | TimeSpan |  |
| **ValidationType** | [TimeSheetValidationType](#timesheetvalidationtype-enum) |  |
| **Work** | [TimeSheetWorkCollection](#timesheetworkcollection-class) |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **TimeSheetLine(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
| **Submit(string comment)** | void |  |
# TimeSheetLineClass Enum

Namespace: Microsoft.ProjectServer.Client


## Values

| Name | Summary |
|---|---|
| **StandardLine** |  |
| **SickTimeLine** |  |
| **VacationLine** |  |
| **AdministrativeLine** |  |
# TimeSheetLineCollection Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObjectCollection<[TimeSheetLine](#timesheetline-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [TimeSheetLine](#timesheetline-class) |  |
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
| **TimeSheetLineCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(TimeSheetLineCreationInformation parameters)** | [TimeSheetLine](#timesheetline-class) |  |
| **GetByGuid(Guid uid)** | [TimeSheetLine](#timesheetline-class) |  |
| **GetById(string objectId)** | [TimeSheetLine](#timesheetline-class) |  |
| **Remove(TimeSheetLine line)** | ClientResult\<bool\> |  |
# TimeSheetLineCreationInformation Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **AssignmentId** | Guid |  |
| **Comment** | string |  |
| **Id** | Guid |  |
| **LineClass** | [TimeSheetLineClass](#timesheetlineclass-enum) |  |
| **ProjectId** | Guid |  |
| **TaskName** | string |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# TimeSheetLineObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Assignment** | string |  |
| **TimeSheet** | string |  |
| **Work** | string |  |
# TimeSheetLinePropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Comment** | string |  |
| **Id** | string |  |
| **LineClass** | string |  |
| **ProjectName** | string |  |
| **Status** | string |  |
| **TaskName** | string |  |
| **TotalWork** | string |  |
| **TotalWorkTimeSpan** | string |  |
| **ValidationType** | string |  |
# TimeSheetLineStatus Enum

Namespace: Microsoft.ProjectServer.Client


## Values

| Name | Summary |
|---|---|
| **NotSpecified** |  |
| **Pending** |  |
| **Approved** |  |
| **Rejected** |  |
| **NotApplicable** |  |
| **PendingApproval** |  |
# TimeSheetObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Creator** | string |  |
| **Lines** | string |  |
| **Manager** | string |  |
| **Period** | string |  |
# TimeSheetPeriod Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **End** | DateTime |  |
| **Id** | Guid |  |
| **Name** | string |  |
| **Start** | DateTime |  |
| **TimeSheet** | [TimeSheet](#timesheet-class) |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **TimeSheetPeriod(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **CreateTimeSheet()** | [TimeSheet](#timesheet-class) |  |
# TimeSheetPeriodCollection Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObjectCollection<[TimeSheetPeriod](#timesheetperiod-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [TimeSheetPeriod](#timesheetperiod-class) |  |
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
| **TimeSheetPeriodCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetByGuid(Guid uid)** | [TimeSheetPeriod](#timesheetperiod-class) |  |
| **GetById(string objectId)** | [TimeSheetPeriod](#timesheetperiod-class) |  |
# TimeSheetPeriodObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **TimeSheet** | string |  |
# TimeSheetPeriodPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **End** | string |  |
| **Id** | string |  |
| **Name** | string |  |
| **Start** | string |  |
# TimeSheetPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Comments** | string |  |
| **EntryMode** | string |  |
| **Id** | string |  |
| **IsControlledByOwner** | string |  |
| **IsProcessed** | string |  |
| **Name** | string |  |
| **Status** | string |  |
| **TotalActualWork** | string |  |
| **TotalActualWorkTimeSpan** | string |  |
| **TotalNonBillableOvertimeWork** | string |  |
| **TotalNonBillableOvertimeWorkTimeSpan** | string |  |
| **TotalNonBillableWork** | string |  |
| **TotalNonBillableWorkTimeSpan** | string |  |
| **TotalOvertimeWork** | string |  |
| **TotalOvertimeWorkTimeSpan** | string |  |
| **TotalWork** | string |  |
| **TotalWorkTimeSpan** | string |  |
| **WeekStartsOn** | string |  |
# TimeSheetStatus Enum

Namespace: Microsoft.ProjectServer.Client


## Values

| Name | Summary |
|---|---|
| **NotSpecified** |  |
| **InProgress** |  |
| **Submitted** |  |
| **Acceptable** |  |
| **Approved** |  |
| **Rejected** |  |
| **PendingSubmit** |  |
# TimeSheetValidationType Enum

Namespace: Microsoft.ProjectServer.Client


## Values

| Name | Summary |
|---|---|
| **Unverified** |  |
| **Verified** |  |
| **ProjectLevel** |  |
# TimeSheetWork Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ActualWork** | string |  |
| **ActualWorkTimeSpan** | TimeSpan |  |
| **Comment** | string |  |
| **End** | DateTime |  |
| **Id** | Guid |  |
| **NonBillableOvertimeWork** | string |  |
| **NonBillableOvertimeWorkTimeSpan** | TimeSpan |  |
| **NonBillableWork** | string |  |
| **NonBillableWorkTimeSpan** | TimeSpan |  |
| **OvertimeWork** | string |  |
| **OvertimeWorkTimeSpan** | TimeSpan |  |
| **PlannedWork** | string |  |
| **PlannedWorkTimeSpan** | TimeSpan |  |
| **Start** | DateTime |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **TimeSheetWork(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **DeleteObject()** | void |  |
# TimeSheetWorkCollection Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObjectCollection<[TimeSheetWork](#timesheetwork-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [TimeSheetWork](#timesheetwork-class) |  |
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
| **TimeSheetWorkCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(TimeSheetWorkCreationInformation parameters)** | [TimeSheetWork](#timesheetwork-class) |  |
| **GetById(string objectId)** | [TimeSheetWork](#timesheetwork-class) |  |
| **GetByStartDate(DateTime start)** | [TimeSheetWork](#timesheetwork-class) |  |
| **Remove(TimeSheetWork work)** | ClientResult\<bool\> |  |
# TimeSheetWorkCreationInformation Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **ActualWork** | string |  |
| **Comment** | string |  |
| **End** | DateTime |  |
| **NonBillableOvertimeWork** | string |  |
| **NonBillableWork** | string |  |
| **OvertimeWork** | string |  |
| **PlannedWork** | string |  |
| **Start** | DateTime |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# TimeSheetWorkPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **ActualWork** | string |  |
| **ActualWorkTimeSpan** | string |  |
| **Comment** | string |  |
| **End** | string |  |
| **Id** | string |  |
| **NonBillableOvertimeWork** | string |  |
| **NonBillableOvertimeWorkTimeSpan** | string |  |
| **NonBillableWork** | string |  |
| **NonBillableWorkTimeSpan** | string |  |
| **OvertimeWork** | string |  |
| **OvertimeWorkTimeSpan** | string |  |
| **PlannedWork** | string |  |
| **PlannedWorkTimeSpan** | string |  |
| **Start** | string |  |
# TrackingMode Enum

Namespace: Microsoft.ProjectServer.Client


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **TimePhased** |  |
| **PercentComplete** |  |
| **ActualHours** |  |
# UpdateProjectStageStatusFieldValue Enum

Namespace: Microsoft.ProjectServer.Client


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **WaitingForInput** |  |
| **WaitingForApproval** |  |
| **WorkflowProcessing** |  |
# UtilizationType Enum

Namespace: Microsoft.ProjectServer.Client


## Values

| Name | Summary |
|---|---|
| **FromProjectPlan** |  |
| **FromResourcePlan** |  |
| **FromProjectPlanThenResourcePlan** |  |
# WorkContourType Enum

Namespace: Microsoft.ProjectServer.Client


## Values

| Name | Summary |
|---|---|
| **Flat** |  |
| **BackLoaded** |  |
| **FrontLoaded** |  |
| **DoublePeak** |  |
| **EarlyPeak** |  |
| **LatePeak** |  |
| **Bell** |  |
| **Turtle** |  |
| **UserDefined** |  |
# WorkflowActivities Class

Namespace: Microsoft.ProjectServer.Client

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
| **WorkflowActivities(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **CreateProjectFromListItem(Guid webId, Guid listId, int itemId, Guid eptId)** | ClientResult\<Guid\> |  |
| **EnterProjectStage(Guid projectId, Guid stageId)** | void |  |
| **LeaveProjectStage(Guid projectId)** | void |  |
| **ReadBooleanProperty(Guid projectId, string propertyId)** | ClientResult\<bool\> |  |
| **ReadCurrencyProperty(Guid projectId, string propertyId)** | ClientResult\<double\> |  |
| **ReadDateTimeProperty(Guid projectId, string propertyId)** | ClientResult\<DateTime\> |  |
| **ReadGuidProperty(Guid projectId, string propertyId)** | ClientResult\<Guid\> |  |
| **ReadIntegerProperty(Guid projectId, string propertyId)** | ClientResult\<int\> |  |
| **ReadNumberProperty(Guid projectId, string propertyId)** | ClientResult\<double\> |  |
| **ReadProjectProperty(Guid projectId, string propertyId)** | ClientResult\<string\> |  |
| **ReadTextProperty(Guid projectId, string propertyId)** | ClientResult\<string\> |  |
| **ReadyToLeaveProjectStage(Guid projectId)** | ClientResult\<[ReadyToLeaveProjectStageValue](#readytoleaveprojectstagevalue-enum)\> |  |
| **UpdateBooleanProperty(Guid projectId, string propertyId, bool value)** | void |  |
| **UpdateCurrencyProperty(Guid projectId, string propertyId, double value)** | void |  |
| **UpdateDateTimeProperty(Guid projectId, string propertyId, DateTime value)** | void |  |
| **UpdateGuidProperty(Guid projectId, string propertyId, Guid value)** | void |  |
| **UpdateIdeaListItemStatus(Guid projectId, string status)** | void |  |
| **UpdateIntegerProperty(Guid projectId, string propertyId, int value)** | void |  |
| **UpdateNumberProperty(Guid projectId, string propertyId, double value)** | void |  |
| **UpdateProjectStageStatus(Guid projectId, Guid stageId, string statusInformation, UpdateProjectStageStatusFieldValue stageStatusValue, bool append)** | void |  |
| **UpdateTextProperty(Guid projectId, string propertyId, string value)** | void |  |
# WorkflowDesigner Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Fields** | [WorkflowDesignerFieldCollection](#workflowdesignerfieldcollection-class) |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **WorkflowDesigner(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# WorkflowDesignerField Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **DisplayName** | string |  |
| **Id** | string |  |
| **IsLookupField** | bool |  |
| **IsReadOnly** | bool |  |
| **LookupEntries** | [LookupEntryCollection](#lookupentrycollection-class) |  |
| **SPFieldType** | FieldType |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **WorkflowDesignerField(ClientRuntimeContext context, ObjectPath objectPath)** |  |
# WorkflowDesignerFieldCollection Class

Namespace: Microsoft.ProjectServer.Client

Base class: ClientObjectCollection<[WorkflowDesignerField](#workflowdesignerfield-class)>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | [WorkflowDesignerField](#workflowdesignerfield-class) |  |
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
| **WorkflowDesignerFieldCollection(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetById(string objectId)** | [WorkflowDesignerField](#workflowdesignerfield-class) |  |
# WorkflowDesignerFieldObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **LookupEntries** | string |  |
# WorkflowDesignerFieldPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **DisplayName** | string |  |
| **Id** | string |  |
| **IsLookupField** | string |  |
| **IsReadOnly** | string |  |
| **SPFieldType** | string |  |
# WorkflowDesignerObjectPropertyNames Class

Namespace: Microsoft.ProjectServer.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Fields** | string |  |
# WorkFormat Enum

Namespace: Microsoft.ProjectServer.Client


## Values

| Name | Summary |
|---|---|
| **Minute** |  |
| **Hour** |  |
| **Day** |  |
| **Week** |  |
| **Month** |  |
