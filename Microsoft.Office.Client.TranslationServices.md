# Microsoft.Office.Client.TranslationServices.dll v.16.1.0.0 API documentation

Created by 
[mddox](https://github.com/loxsmoke/mddox) on 06/04/2023

# All types

|   |   |   |
|---|---|---|
| [ItemTypes Enum](#itemtypes-enum) | [TranslationItemInfo Class](#translationiteminfo-class) | [TranslationJobStatusPropertyNames Class](#translationjobstatuspropertynames-class) |
| [SaveBehavior Enum](#savebehavior-enum) | [TranslationJob Class](#translationjob-class) | [TranslationResult Enum](#translationresult-enum) |
| [ScriptTypeFactory Class](#scripttypefactory-class) | [TranslationJobInfo Class](#translationjobinfo-class) | [VariationsTranslationTimerJob Class](#variationstranslationtimerjob-class) |
| [SyncTranslator Class](#synctranslator-class) | [TranslationJobPropertyNames Class](#translationjobpropertynames-class) |   |
| [SyncTranslatorPropertyNames Class](#synctranslatorpropertynames-class) | [TranslationJobStatus Class](#translationjobstatus-class) |   |
# ItemTypes Enum

Namespace: Microsoft.Office.Client.TranslationServices


## Values

| Name | Summary |
|---|---|
| **Succeeded** |  |
| **InProgress** |  |
| **NotStarted** |  |
| **Failed** |  |
| **Canceled** |  |
# SaveBehavior Enum

Namespace: Microsoft.Office.Client.TranslationServices


## Values

| Name | Summary |
|---|---|
| **AppendIfPossible** |  |
| **AlwaysOverwrite** |  |
| **AppendOnly** |  |
| **NeverOverwrite** |  |
# ScriptTypeFactory Class

Namespace: Microsoft.Office.Client.TranslationServices


## Methods

| Name | Returns | Summary |
|---|---|---|
| **CreateObjectFromScriptType(string scriptType, ClientRuntimeContext context)** | IFromJson |  |
# SyncTranslator Class

Namespace: Microsoft.Office.Client.TranslationServices

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **OutputSaveBehavior** | [SaveBehavior](#savebehavior-enum) |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **SyncTranslator(ClientRuntimeContext context, string targetLanguage)** |  |
| **SyncTranslator(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Translate(string inputFile, string outputFile)** | ClientResult\<[TranslationItemInfo](#translationiteminfo-class)\> |  |
| **TranslateStream(Stream inputFile, string fileExtension)** | ClientResult\<Stream\> |  |
# SyncTranslatorPropertyNames Class

Namespace: Microsoft.Office.Client.TranslationServices


## Fields

| Name | Type | Summary |
|---|---|---|
| **OutputSaveBehavior** | string |  |
# TranslationItemInfo Class

Namespace: Microsoft.Office.Client.TranslationServices

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Canceled** | bool |  |
| **ErrorMessage** | string |  |
| **Failed** | bool |  |
| **InProgress** | bool |  |
| **InputFile** | string |  |
| **NotStarted** | bool |  |
| **OutputFile** | string |  |
| **Result** | [TranslationResult](#translationresult-enum) |  |
| **Succeeded** | bool |  |
| **TranslationId** | Guid |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# TranslationJob Class

Namespace: Microsoft.Office.Client.TranslationServices

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **JobId** | Guid |  |
| **Name** | string |  |
| **OutputSaveBehavior** | [SaveBehavior](#savebehavior-enum) |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **TranslationJob(ClientRuntimeContext context, string targetLanguage)** |  |
| **TranslationJob(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **AddFile(string inputFile, string outputFile)** | void |  |
| **AddFolder(Folder inputFolder, Folder outputFolder, bool recursion)** | ClientResult\<bool\> |  |
| **AddLibrary(List inputList, List outputList)** | ClientResult\<bool\> |  |
| **CancelJob(ClientRuntimeContext context, Guid jobId)** | void |  |
| **EnumerateSupportedFileExtensions(ClientRuntimeContext context)** | IEnumerable\<string\> |  |
| **EnumerateSupportedLanguages(ClientRuntimeContext context)** | IEnumerable\<string\> |  |
| **GetMaximumFileSize(ClientRuntimeContext context, string extension)** | ClientResult\<int\> |  |
| **IsFileExtensionSupported(ClientRuntimeContext context, string extension)** | ClientResult\<bool\> |  |
| **IsLanguageSupported(ClientRuntimeContext context, string language)** | ClientResult\<bool\> |  |
| **IsServiceEnabled(ClientRuntimeContext context)** | ClientResult\<bool\> |  |
| **Start()** | void |  |
# TranslationJobInfo Class

Namespace: Microsoft.Office.Client.TranslationServices

Base class: ClientValueObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Canceled** | bool |  |
| **CancelTime** | DateTime |  |
| **JobId** | Guid |  |
| **Name** | string |  |
| **PartiallySubmitted** | bool |  |
| **SubmittedTime** | DateTime |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# TranslationJobPropertyNames Class

Namespace: Microsoft.Office.Client.TranslationServices


## Fields

| Name | Type | Summary |
|---|---|---|
| **JobId** | string |  |
| **Name** | string |  |
| **OutputSaveBehavior** | string |  |
# TranslationJobStatus Class

Namespace: Microsoft.Office.Client.TranslationServices

Base class: ClientObject


## Properties

| Name | Type | Summary |
|---|---|---|
| **Canceled** | int |  |
| **Count** | int |  |
| **Failed** | int |  |
| **InProgress** | int |  |
| **Name** | string |  |
| **NotStarted** | int |  |
| **Succeeded** | int |  |
| **Context** | ClientRuntimeContext |  |
| **Tag** | Object |  |
| **Path** | ObjectPath |  |
| **ObjectVersion** | string |  |
| **ObjectData** | ClientObjectData |  |
| **Query** | ClientQueryInternal |  |
| **ParentCollection** | ClientObjectCollection |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | ClientObject |  |
## Constructors

| Name | Summary |
|---|---|
| **TranslationJobStatus(ClientRuntimeContext context, Guid jobId)** |  |
| **TranslationJobStatus(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetAllActiveJobs(ClientRuntimeContext context)** | IEnumerable\<[TranslationJobInfo](#translationjobinfo-class)\> |  |
| **GetAllItems()** | IEnumerable\<[TranslationItemInfo](#translationiteminfo-class)\> |  |
| **GetAllJobs(ClientRuntimeContext context)** | IEnumerable\<[TranslationJobInfo](#translationjobinfo-class)\> |  |
| **GetItems(ItemTypes types)** | IEnumerable\<[TranslationItemInfo](#translationiteminfo-class)\> |  |
| **Refresh()** | void |  |
# TranslationJobStatusPropertyNames Class

Namespace: Microsoft.Office.Client.TranslationServices


## Fields

| Name | Type | Summary |
|---|---|---|
| **Canceled** | string |  |
| **Count** | string |  |
| **Failed** | string |  |
| **InProgress** | string |  |
| **Name** | string |  |
| **NotStarted** | string |  |
| **Succeeded** | string |  |
# TranslationResult Enum

Namespace: Microsoft.Office.Client.TranslationServices


## Values

| Name | Summary |
|---|---|
| **Succeeded** |  |
| **InputFileNotFound** |  |
| **UnauthorizedAccessToInputFile** |  |
| **InputFileUserTokenExpired** |  |
| **UnauthorizedAccessToOutputFile** |  |
| **OutputFileUserTokenExpired** |  |
| **InputFileReadError** |  |
| **OutputFileWriteError** |  |
| **NotAssignedToWorker** |  |
| **WorkerFailed** |  |
| **Timeout** |  |
| **SyncTranslationLimitExceeded** |  |
| **SyncTranslationDisabled** |  |
| **OutputFileReadOnly** |  |
| **InputFileTooLarge** |  |
| **InputFileTooLong** |  |
| **InputFileCorrupt** |  |
| **InputFileIRMProtected** |  |
| **InputFileEncrypted** |  |
| **InputFileTypeBlocked** |  |
| **InputFileTypeNotSupported** |  |
| **InputFileHasActiveXControls** |  |
| **InputFileCannotBeTranslated** |  |
| **TranslationServiceUnavailable** |  |
| **UnknownFailure** |  |
# VariationsTranslationTimerJob Class

Namespace: Microsoft.Office.Client.TranslationServices


## Methods

| Name | Returns | Summary |
|---|---|---|
| **ExportItems(ClientRuntimeContext context, string list, int[] itemIds, string[] addressesToEmail)** | void |  |
| **ExportItemsRequiringTranslation(ClientRuntimeContext context, string list, string[] addressesToEmail)** | void |  |
| **ImportTranslationPackage(ClientRuntimeContext context, string translatorName, int packageId, string[] addressesToEmail)** | void |  |
| **MachineTranslateItems(ClientRuntimeContext context, string list, int[] itemIds, string[] addressesToEmail)** | void |  |
| **MachineTranslateItemsRequiringTranslation(ClientRuntimeContext context, string list, string[] addressesToEmail)** | void |  |
