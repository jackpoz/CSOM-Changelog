# Microsoft.SharePoint.Client.Runtime.dll v.16.1.0.0 API documentation

Created by 
[mddox](https://github.com/loxsmoke/mddox) on 2024-05-13

# All types

|   |   |   |
|---|---|---|
| [AttachmentStreamFromServer Class](#attachmentstreamfromserver-class) | [ConditionalScope Class](#conditionalscope-class) | [ScriptTypeMap Class](#scripttypemap-class) |
| [ChunkStreamBuilder Class](#chunkstreambuilder-class) | [ConditionalScopeBase Class](#conditionalscopebase-class) | [SerializationContext Class](#serializationcontext-class) |
| [ChunkStringBuilder Class](#chunkstringbuilder-class) | [DataConvert Class](#dataconvert-class) | [ServerException Class](#serverexception-class) |
| [ChunkStringReader Class](#chunkstringreader-class) | [DataRetrieval Class](#dataretrieval-class) | [ServerObjectNullReferenceException Class](#serverobjectnullreferenceexception-class) |
| [ChunkStringWriter Class](#chunkstringwriter-class) | [DefaultWebRequestExecutorFactory Class](#defaultwebrequestexecutorfactory-class) | [ServerUnauthorizedAccessException Class](#serverunauthorizedaccessexception-class) |
| [ClientAction Class](#clientaction-class) | [EnumerableClientObjectCollection\<T\> Class](#enumerableclientobjectcollectiont-class) | [SimpleDataTable Class](#simpledatatable-class) |
| [ClientActionExecutionScopeEnd Class](#clientactionexecutionscopeend-class) | [ExceptionHandlingExecutionScope Class](#exceptionhandlingexecutionscope-class) | [SPResourceManager Class](#spresourcemanager-class) |
| [ClientActionExecutionScopeStart Class](#clientactionexecutionscopestart-class) | [ExceptionHandlingScope Class](#exceptionhandlingscope-class) | [SPWebRequestExecutor Class](#spwebrequestexecutor-class) |
| [ClientActionInstantiateObjectPath Class](#clientactioninstantiateobjectpath-class) | [ExecuteQueryMimeInfo Class](#executequerymimeinfo-class) | [StreamInfo Class](#streaminfo-class) |
| [ClientActionInstantiateObjectPathResult Class](#clientactioninstantiateobjectpathresult-class) | [ExecutionScope Class](#executionscope-class) | [SubtreeEvaluator Class](#subtreeevaluator-class) |
| [ClientActionInvokeMethod Class](#clientactioninvokemethod-class) | [ExecutionScopeDisposingCallback Class](#executionscopedisposingcallback-class) | [TextPeekReader Class](#textpeekreader-class) |
| [ClientActionInvokeStaticMethod Class](#clientactioninvokestaticmethod-class) | [ExpressionEvaluator Class](#expressionevaluator-class) | [Token Class](#token-class) |
| [ClientActionSetProperty Class](#clientactionsetproperty-class) | [ExpressionUtility Class](#expressionutility-class) | [UTF8ReadonlyStream Class](#utf8readonlystream-class) |
| [ClientActionSetStaticProperty Class](#clientactionsetstaticproperty-class) | [ExpressionVisitor Class](#expressionvisitor-class) | [WebRequestEventArgs Class](#webrequesteventargs-class) |
| [ClientArrayResult\<T\> Class](#clientarrayresultt-class) | [IFromJson Class](#ifromjson-class) | [WebRequestExecutor Class](#webrequestexecutor-class) |
| [ClientConstants Class](#clientconstants-class) | [InvalidQueryExpressionException Class](#invalidqueryexpressionexception-class) | [WebRequestExecutorFactory Class](#webrequestexecutorfactory-class) |
| [ClientDictionaryResultHandler\<T\> Class](#clientdictionaryresulthandlert-class) | [IScriptTypeFactory Class](#iscripttypefactory-class) | [WriteValueHandler Class](#writevaluehandler-class) |
| [ClientErrorCodes Class](#clienterrorcodes-class) | [JsonReader Class](#jsonreader-class) | [BufferedReadStream Class](#bufferedreadstream-class) |
| [ClientListResultHandler\<T\> Class](#clientlistresulthandlert-class) | [JsonReaderOptions Enum](#jsonreaderoptions-enum) | [BufferedWrite Class](#bufferedwrite-class) |
| [ClientObject Class](#clientobject-class) | [JsonTokenType Enum](#jsontokentype-enum) | [Constants Class](#constants-class) |
| [ClientObjectCollection Class](#clientobjectcollection-class) | [Nominator Class](#nominator-class) | [ContentIDHeader Class](#contentidheader-class) |
| [ClientObjectCollection\<T\> Class](#clientobjectcollectiont-class) | [NotSupportedExpressionChecker Class](#notsupportedexpressionchecker-class) | [ContentLengthHeader Class](#contentlengthheader-class) |
| [ClientObjectCollectionPrototype\<ItemType\> Class](#clientobjectcollectionprototypeitemtype-class) | [ObjectIdentityQuery Class](#objectidentityquery-class) | [ContentTransferEncoding Enum](#contenttransferencoding-enum) |
| [ClientObjectData Class](#clientobjectdata-class) | [ObjectPath Class](#objectpath-class) | [ContentTransferEncodingHeader Class](#contenttransferencodingheader-class) |
| [ClientObjectList\<T\> Class](#clientobjectlistt-class) | [ObjectPathConstructor Class](#objectpathconstructor-class) | [ContentTypeHeader Class](#contenttypeheader-class) |
| [ClientObjectPrototype Class](#clientobjectprototype-class) | [ObjectPathIdentity Class](#objectpathidentity-class) | [DelimittedReadStream Class](#delimittedreadstream-class) |
| [ClientObjectPrototype\<T\> Class](#clientobjectprototypet-class) | [ObjectPathMethod Class](#objectpathmethod-class) | [DelimittedStreamReader Class](#delimittedstreamreader-class) |
| [ClientObjectQueryableExtension Class](#clientobjectqueryableextension-class) | [ObjectPathProperty Class](#objectpathproperty-class) | [DiagnosticUtility Class](#diagnosticutility-class) |
| [ClientQueryable\<T\> Class](#clientqueryablet-class) | [ObjectPathStaticMethod Class](#objectpathstaticmethod-class) | [ExceptionUtility Class](#exceptionutility-class) |
| [ClientQueryableResult\<T\> Class](#clientqueryableresultt-class) | [ObjectPathStaticProperty Class](#objectpathstaticproperty-class) | [MailBnfHelper Class](#mailbnfhelper-class) |
| [ClientQueryInternal Class](#clientqueryinternal-class) | [OfficeVersion Class](#officeversion-class) | [MatchState Enum](#matchstate-enum) |
| [ClientQueryProperty Class](#clientqueryproperty-class) | [PropertyOrFieldNotInitializedException Class](#propertyorfieldnotinitializedexception-class) | [MergedStream Class](#mergedstream-class) |
| [ClientQueryProvider Class](#clientqueryprovider-class) | [PseudoRemoteAttribute Class](#pseudoremoteattribute-class) | [MimeGlobals Class](#mimeglobals-class) |
| [ClientRequest Class](#clientrequest-class) | [QueryMethodAggregator Class](#querymethodaggregator-class) | [MimeHeader Class](#mimeheader-class) |
| [ClientRequestException Class](#clientrequestexception-class) | [QueryProcessInfo Class](#queryprocessinfo-class) | [MimeHeaderReader Class](#mimeheaderreader-class) |
| [ClientRequestStatus Enum](#clientrequeststatus-enum) | [ReadObjectHandler Class](#readobjecthandler-class) | [MimeHeaders Class](#mimeheaders-class) |
| [ClientRequestWrapper Class](#clientrequestwrapper-class) | [ReadObjectHandlers Class](#readobjecthandlers-class) | [MimeMergedStream Class](#mimemergedstream-class) |
| [ClientResult\<T\> Class](#clientresultt-class) | [ReadonlyChunkStream Class](#readonlychunkstream-class) | [MimeMessageReader Class](#mimemessagereader-class) |
| [ClientRuntimeContext Class](#clientruntimecontext-class) | [ReadonlyWrapStream Class](#readonlywrapstream-class) | [MimePart Class](#mimepart-class) |
| [ClientSchemaVersions Class](#clientschemaversions-class) | [RemoteAttribute Class](#remoteattribute-class) | [MimeReader Class](#mimereader-class) |
| [ClientTypeAssemblyAttribute Class](#clienttypeassemblyattribute-class) | [ReplaceQueryableCollectionWithEnumerableCollectionExpressionVisitor Class](#replacequeryablecollectionwithenumerablecollectionexpressionvisitor-class) | [MimeUtility Class](#mimeutility-class) |
| [ClientUtility Class](#clientutility-class) | [Resources Class](#resources-class) | [MimeVersionHeader Class](#mimeversionheader-class) |
| [ClientValueObject Class](#clientvalueobject-class) | [ResourceStrings Class](#resourcestrings-class) | [MimeWriter Class](#mimewriter-class) |
| [ClientValueObjectCollection\<T\> Class](#clientvalueobjectcollectiont-class) | [Scope Class](#scope-class) | [MimeWriterState Enum](#mimewriterstate-enum) |
| [CollectionNotInitializedException Class](#collectionnotinitializedexception-class) | [ScopeType Enum](#scopetype-enum) | [MtomGlobals Class](#mtomglobals-class) |
| [ConditionalExecutionScope Class](#conditionalexecutionscope-class) | [ScriptTypeAttribute Class](#scripttypeattribute-class) | [ReadState Enum](#readstate-enum) |
| [ConditionalExpressionToXmlConverter Class](#conditionalexpressiontoxmlconverter-class) | [ScriptTypeInfo Class](#scripttypeinfo-class) | [SR Class](#sr-class) |
# AttachmentStreamFromServer Class

Namespace: Microsoft.SharePoint.Client

Base class: [ReadonlyWrapStream](#readonlywrapstream-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **UnderlyingStream** | Stream |  |
| **OwnUnderlyingStream** | bool |  |
| **TotalReadCountAction** | Action\<long\> |  |
| **CanRead** | bool |  |
| **CanSeek** | bool |  |
| **CanWrite** | bool |  |
| **Length** | long |  |
| **Position** | long |  |
| **CanTimeout** | bool |  |
| **ReadTimeout** | int |  |
| **WriteTimeout** | int |  |
# ChunkStreamBuilder Class

Namespace: Microsoft.SharePoint.Client


## Properties

| Name | Type | Summary |
|---|---|---|
| **ChunkCount** | int |  |
| **Length** | long |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Close()** | void |  |
| **CopyFrom(Stream stream)** | void |  |
| **CreateReadonlyStream()** | Stream |  |
| **Write(byte[] buffer)** | void |  |
| **Write(byte[] buffer, int offset, int count)** | void |  |
| **WriteByte(byte value)** | void |  |
| **WriteTo(Stream stream)** | void |  |
# ChunkStringBuilder Class

Namespace: Microsoft.SharePoint.Client


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | char |  |
| **Length** | int |  |
## Constructors

| Name | Summary |
|---|---|
| **ChunkStringBuilder(string value)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Append(bool value)** | [ChunkStringBuilder](#chunkstringbuilder-class) |  |
| **Append(byte value)** | [ChunkStringBuilder](#chunkstringbuilder-class) |  |
| **Append(char value)** | [ChunkStringBuilder](#chunkstringbuilder-class) |  |
| **Append(decimal value)** | [ChunkStringBuilder](#chunkstringbuilder-class) |  |
| **Append(double value)** | [ChunkStringBuilder](#chunkstringbuilder-class) |  |
| **Append(char[] value)** | [ChunkStringBuilder](#chunkstringbuilder-class) |  |
| **Append(short value)** | [ChunkStringBuilder](#chunkstringbuilder-class) |  |
| **Append(int value)** | [ChunkStringBuilder](#chunkstringbuilder-class) |  |
| **Append(long value)** | [ChunkStringBuilder](#chunkstringbuilder-class) |  |
| **Append(sbyte value)** | [ChunkStringBuilder](#chunkstringbuilder-class) |  |
| **Append(float value)** | [ChunkStringBuilder](#chunkstringbuilder-class) |  |
| **Append(string value)** | [ChunkStringBuilder](#chunkstringbuilder-class) |  |
| **Append(ushort value)** | [ChunkStringBuilder](#chunkstringbuilder-class) |  |
| **Append(uint value)** | [ChunkStringBuilder](#chunkstringbuilder-class) |  |
| **Append(ulong value)** | [ChunkStringBuilder](#chunkstringbuilder-class) |  |
| **Append(char value, int repeatCount)** | [ChunkStringBuilder](#chunkstringbuilder-class) |  |
| **Append(string value, int startIndex, int count)** | [ChunkStringBuilder](#chunkstringbuilder-class) |  |
| **Append(char[] value, int startIndex, int count)** | [ChunkStringBuilder](#chunkstringbuilder-class) |  |
| **AppendLine()** | [ChunkStringBuilder](#chunkstringbuilder-class) |  |
| **AppendLine(string value)** | [ChunkStringBuilder](#chunkstringbuilder-class) |  |
| **CreateTextReader()** | TextReader |  |
| **CreateTextWriter(IFormatProvider formatProvider)** | TextWriter |  |
| **CreateUTF8ReadonlyStream()** | Stream |  |
| **CreateXmlWriter()** | XmlWriter |  |
| **WriteContentAsRawXml(XmlWriter writer)** | void |  |
| **WriteContentAsUTF8(Stream stream)** | void |  |
| **WriteContentTo(TextWriter writer)** | void |  |
# ChunkStringReader Class

Namespace: Microsoft.SharePoint.Client

Base class: TextReader


## Constructors

| Name | Summary |
|---|---|
| **ChunkStringReader(ChunkStringBuilder s)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Close()** | void |  |
| **Peek()** | int |  |
| **Read()** | int |  |
| **Read(char[] buffer, int index, int count)** | int |  |
# ChunkStringWriter Class

Namespace: Microsoft.SharePoint.Client

Base class: TextWriter


## Properties

| Name | Type | Summary |
|---|---|---|
| **Encoding** | Encoding |  |
| **FormatProvider** | IFormatProvider |  |
| **NewLine** | string |  |
## Constructors

| Name | Summary |
|---|---|
| **ChunkStringWriter(ChunkStringBuilder sb, IFormatProvider formatProvider)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Close()** | void |  |
| **Write(char value)** | void |  |
| **Write(string value)** | void |  |
| **Write(char[] buffer, int index, int count)** | void |  |
# ClientAction Class

Namespace: Microsoft.SharePoint.Client


## Properties

| Name | Type | Summary |
|---|---|---|
| **Id** | long |  |
| **Path** | [ObjectPath](#objectpath-class) |  |
| **Name** | string |  |
# ClientActionExecutionScopeEnd Class

Namespace: Microsoft.SharePoint.Client

Base class: [ClientAction](#clientaction-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **Scope** | [ExecutionScope](#executionscope-class) |  |
| **Id** | long |  |
| **Path** | [ObjectPath](#objectpath-class) |  |
| **Name** | string |  |
## Constructors

| Name | Summary |
|---|---|
| **ClientActionExecutionScopeEnd(ExecutionScope scope, string name)** |  |
# ClientActionExecutionScopeStart Class

Namespace: Microsoft.SharePoint.Client

Base class: [ClientAction](#clientaction-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **Scope** | [ExecutionScope](#executionscope-class) |  |
| **Id** | long |  |
| **Path** | [ObjectPath](#objectpath-class) |  |
| **Name** | string |  |
## Constructors

| Name | Summary |
|---|---|
| **ClientActionExecutionScopeStart(ExecutionScope scope, string name)** |  |
# ClientActionInstantiateObjectPath Class

Namespace: Microsoft.SharePoint.Client

Base class: [ClientAction](#clientaction-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **Id** | long |  |
| **Path** | [ObjectPath](#objectpath-class) |  |
| **Name** | string |  |
## Constructors

| Name | Summary |
|---|---|
| **ClientActionInstantiateObjectPath(ObjectPath path)** |  |
# ClientActionInstantiateObjectPathResult Class

Namespace: Microsoft.SharePoint.Client


## Constructors

| Name | Summary |
|---|---|
| **ClientActionInstantiateObjectPathResult(ObjectPath path)** |  |
# ClientActionInvokeMethod Class

Namespace: Microsoft.SharePoint.Client

Base class: [ClientAction](#clientaction-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **Id** | long |  |
| **Path** | [ObjectPath](#objectpath-class) |  |
| **Name** | string |  |
## Constructors

| Name | Summary |
|---|---|
| **ClientActionInvokeMethod(ClientObject obj, string methodName, Object[] parameters)** |  |
# ClientActionInvokeStaticMethod Class

Namespace: Microsoft.SharePoint.Client

Base class: [ClientAction](#clientaction-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **Id** | long |  |
| **Path** | [ObjectPath](#objectpath-class) |  |
| **Name** | string |  |
## Constructors

| Name | Summary |
|---|---|
| **ClientActionInvokeStaticMethod(ClientRuntimeContext context, string typeId, string methodName, Object[] parameters)** |  |
# ClientActionSetProperty Class

Namespace: Microsoft.SharePoint.Client

Base class: [ClientAction](#clientaction-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **Id** | long |  |
| **Path** | [ObjectPath](#objectpath-class) |  |
| **Name** | string |  |
## Constructors

| Name | Summary |
|---|---|
| **ClientActionSetProperty(ClientObject obj, string propName, Object propValue)** |  |
# ClientActionSetStaticProperty Class

Namespace: Microsoft.SharePoint.Client

Base class: [ClientAction](#clientaction-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **Id** | long |  |
| **Path** | [ObjectPath](#objectpath-class) |  |
| **Name** | string |  |
## Constructors

| Name | Summary |
|---|---|
| **ClientActionSetStaticProperty(ClientRuntimeContext context, string typeId, string propName, Object propValue)** |  |
# ClientArrayResult\<T\> Class

Namespace: Microsoft.SharePoint.Client


## Properties

| Name | Type | Summary |
|---|---|---|
| **Value** | T[] |  |
# ClientConstants Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **AddExpandoFieldTypeSuffix** | string |  |
| **Actions** | string |  |
| **ApplicationName** | string |  |
| **Body** | string |  |
| **CatchScope** | string |  |
| **ChildItemQuery** | string |  |
| **ChildItems** | string |  |
| **ConditionalScope** | string |  |
| **Constructor** | string |  |
| **Context** | string |  |
| **ErrorInfo** | string |  |
| **ErrorMessage** | string |  |
| **ErrorStackTrace** | string |  |
| **ErrorCode** | string |  |
| **ErrorTypeName** | string |  |
| **ErrorValue** | string |  |
| **ErrorDetails** | string |  |
| **ErrorTraceCorrelationId** | string |  |
| **ExceptionHandlingScope** | string |  |
| **ExceptionHandlingScopeSimple** | string |  |
| **QueryableExpression** | string |  |
| **FinallyScope** | string |  |
| **HasException** | string |  |
| **Id** | string |  |
| **Identity** | string |  |
| **IfFalseScope** | string |  |
| **IfTrueScope** | string |  |
| **IsNull** | string |  |
| **LibraryVersion** | string |  |
| **TraceCorrelationId** | string |  |
| **Count** | string |  |
| **Method** | string |  |
| **Methods** | string |  |
| **Name** | string |  |
| **Object** | string |  |
| **ObjectPathId** | string |  |
| **ObjectPath** | string |  |
| **ObjectPaths** | string |  |
| **ObjectType** | string |  |
| **ObjectIdentity** | string |  |
| **ObjectIdentityQuery** | string |  |
| **ObjectVersion** | string |  |
| **Parameter** | string |  |
| **Parameters** | string |  |
| **ParentId** | string |  |
| **Processed** | string |  |
| **Property** | string |  |
| **Properties** | string |  |
| **Query** | string |  |
| **QueryResult** | string |  |
| **Request** | string |  |
| **Results** | string |  |
| **ScalarProperty** | string |  |
| **SchemaVersion** | string |  |
| **ScopeId** | string |  |
| **SelectAll** | string |  |
| **SelectAllProperties** | string |  |
| **SetProperty** | string |  |
| **SetStaticProperty** | string |  |
| **StaticMethod** | string |  |
| **StaticProperty** | string |  |
| **SuffixChar** | string |  |
| **SuffixByte** | string |  |
| **SuffixInt16** | string |  |
| **SuffixUInt16** | string |  |
| **SuffixInt32** | string |  |
| **SuffixUInt32** | string |  |
| **SuffixInt64** | string |  |
| **SuffixUInt64** | string |  |
| **SuffixSingle** | string |  |
| **SuffixDouble** | string |  |
| **SuffixDecimal** | string |  |
| **SuffixTimeSpan** | string |  |
| **SuffixArray** | string |  |
| **Test** | string |  |
| **TryScope** | string |  |
| **Type** | string |  |
| **TypeId** | string |  |
| **Update** | string |  |
| **Version** | string |  |
| **XmlElementName** | string |  |
| **XmlElementAttributes** | string |  |
| **XmlElementChildren** | string |  |
| **XmlNamespace** | string |  |
| **FieldValuesMethodName** | string |  |
| **RequestTokenHeader** | string |  |
| **FormDigestHeader** | string |  |
| **UseWebLanguageHeader** | string |  |
| **UseWebLanguageHeaderValue** | string |  |
| **ClientTagHeader** | string |  |
| **ForceAuthenticationHeader** | string |  |
| **ForceAuthenticationHeaderValue** | string |  |
| **TraceCorrelationIdRequestHeader** | string |  |
| **TraceCorrelationIdResponseHeader** | string |  |
| **GreaterThan** | string |  |
| **LessThan** | string |  |
| **Equal** | string |  |
| **NotEqual** | string |  |
| **GreaterThanOrEqual** | string |  |
| **LessThanOrEqual** | string |  |
| **AndAlso** | string |  |
| **OrElse** | string |  |
| **Not** | string |  |
| **ExpressionParameter** | string |  |
| **ExpressionProperty** | string |  |
| **ExpressionStaticProperty** | string |  |
| **ExpressionMethod** | string |  |
| **ExpressionStaticMethod** | string |  |
| **ExpressionConstant** | string |  |
| **ExpressionConvert** | string |  |
| **ExpressionTypeIs** | string |  |
| **OfType** | string |  |
| **Take** | string |  |
| **Where** | string |  |
| **OrderBy** | string |  |
| **OrderByDescending** | string |  |
| **ThenBy** | string |  |
| **ThenByDescending** | string |  |
| **QueryableObject** | string |  |
| **ServiceFileName** | string |  |
| **ServiceMethodName** | string |  |
| **FluidApplicationInitParamUrl** | string |  |
| **FluidApplicationInitParamViaUrl** | string |  |
| **FluidApplicationInitParamRequestToken** | string |  |
| **FluidApplicationInitParamFormDigestTimeoutSeconds** | string |  |
| **FluidApplicationInitParamFormDigest** | string |  |
# ClientDictionaryResultHandler\<T\> Class

Namespace: Microsoft.SharePoint.Client


## Constructors

| Name | Summary |
|---|---|
| **ClientDictionaryResultHandler\<T\>(IDictionary\<string, T\> dict)** |  |
# ClientErrorCodes Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **GenericError** | int |  |
| **AccessDenied** | int |  |
| **DocAlreadyExists** | int |  |
| **VersionConflict** | int |  |
| **ListItemDeleted** | int |  |
| **InvalidFieldValue** | int |  |
| **NotSupported** | int |  |
| **Redirect** | int |  |
| **NotSupportedRequestVersion** | int |  |
| **FieldValueFailedValidation** | int |  |
| **ItemValueFailedValidation** | int |  |
# ClientListResultHandler\<T\> Class

Namespace: Microsoft.SharePoint.Client


## Constructors

| Name | Summary |
|---|---|
| **ClientListResultHandler\<T\>(IList\<T\> list)** |  |
# ClientObject Class

Namespace: Microsoft.SharePoint.Client


## Properties

| Name | Type | Summary |
|---|---|---|
| **Context** | [ClientRuntimeContext](#clientruntimecontext-class) |  |
| **Tag** | Object |  |
| **Path** | [ObjectPath](#objectpath-class) |  |
| **ObjectVersion** | string |  |
| **ObjectData** | [ClientObjectData](#clientobjectdata-class) |  |
| **Query** | [ClientQueryInternal](#clientqueryinternal-class) |  |
| **ParentCollection** | [ClientObjectCollection](#clientobjectcollection-class) |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | [ClientObject](#clientobject-class) |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **CustomFromJson(JsonReader reader)** | bool |  |
| **FromJson(JsonReader reader)** | void |  |
| **IsObjectPropertyInstantiated(string propertyName)** | bool |  |
| **IsPropertyAvailable(string propertyName)** | bool |  |
| **RefreshLoad()** | void |  |
| **Retrieve()** | void |  |
| **Retrieve(string[] propertyNames)** | void |  |
# ClientObjectCollection Class

Namespace: Microsoft.SharePoint.Client

Base class: [ClientObject](#clientobject-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **AreItemsAvailable** | bool |  |
| **Count** | int |  |
| **DataInited** | bool |  |
| **Data** | List\<Object\> |  |
| **Context** | [ClientRuntimeContext](#clientruntimecontext-class) |  |
| **Tag** | Object |  |
| **Path** | [ObjectPath](#objectpath-class) |  |
| **ObjectVersion** | string |  |
| **ObjectData** | [ClientObjectData](#clientobjectdata-class) |  |
| **Query** | [ClientQueryInternal](#clientqueryinternal-class) |  |
| **ParentCollection** | [ClientObjectCollection](#clientobjectcollection-class) |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | [ClientObject](#clientobject-class) |  |
# ClientObjectCollection\<T\> Class

Namespace: Microsoft.SharePoint.Client

Base class: [ClientObjectCollection](#clientobjectcollection-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | T |  |
| **ElementType** | Type |  |
| **Expression** | Expression |  |
| **Provider** | IQueryProvider |  |
| **AreItemsAvailable** | bool |  |
| **Count** | int |  |
| **Data** | List\<Object\> |  |
| **Context** | [ClientRuntimeContext](#clientruntimecontext-class) |  |
| **Tag** | Object |  |
| **Path** | [ObjectPath](#objectpath-class) |  |
| **ObjectVersion** | string |  |
| **ObjectData** | [ClientObjectData](#clientobjectdata-class) |  |
| **Query** | [ClientQueryInternal](#clientqueryinternal-class) |  |
| **ParentCollection** | [ClientObjectCollection](#clientobjectcollection-class) |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | [ClientObject](#clientobject-class) |  |
## Constructors

| Name | Summary |
|---|---|
| **ClientObjectCollection\<T\>(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetEnumerator()** | IEnumerator\<T\> |  |
| **RetrieveItems()** | [ClientObjectPrototype](#clientobjectprototypet-class)\<T\> |  |
# ClientObjectCollectionPrototype\<ItemType\> Class

Namespace: Microsoft.SharePoint.Client

Base class: [ClientObjectPrototype](#clientobjectprototype-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **Query** | [ClientQueryInternal](#clientqueryinternal-class) |  |
| **ChildItemPrototype** | bool |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **RetrieveItems()** | [ClientObjectPrototype](#clientobjectprototypet-class)\<ItemType\> |  |
# ClientObjectData Class

Namespace: Microsoft.SharePoint.Client


## Properties

| Name | Type | Summary |
|---|---|---|
| **Version** | string |  |
| **Properties** | Dictionary\<string, Object\> |  |
| **ClientObjectProperties** | Dictionary\<string, Object\> |  |
| **MethodReturnObjects** | Dictionary\<string, Object\> |  |
| **Query** | [ClientQueryInternal](#clientqueryinternal-class) |  |
| **TypedObject** | [ClientObject](#clientobject-class) |  |
| **AssociatedObject** | [ClientObject](#clientobject-class) |  |
| **Path** | [ObjectPath](#objectpath-class) |  |
| **CollectionDataInited** | bool |  |
| **CollectionData** | List\<Object\> |  |
# ClientObjectList\<T\> Class

Namespace: Microsoft.SharePoint.Client

Base class: [ClientObjectCollection](#clientobjectcollectiont-class)<T>


## Properties

| Name | Type | Summary |
|---|---|---|
| **Item** | T |  |
| **ElementType** | Type |  |
| **Expression** | Expression |  |
| **Provider** | IQueryProvider |  |
| **AreItemsAvailable** | bool |  |
| **Count** | int |  |
| **Data** | List\<Object\> |  |
| **Context** | [ClientRuntimeContext](#clientruntimecontext-class) |  |
| **Tag** | Object |  |
| **Path** | [ObjectPath](#objectpath-class) |  |
| **ObjectVersion** | string |  |
| **ObjectData** | [ClientObjectData](#clientobjectdata-class) |  |
| **Query** | [ClientQueryInternal](#clientqueryinternal-class) |  |
| **ParentCollection** | [ClientObjectCollection](#clientobjectcollection-class) |  |
| **ServerObjectIsNull** | bool? |  |
| **TypedObject** | [ClientObject](#clientobject-class) |  |
## Constructors

| Name | Summary |
|---|---|
| **ClientObjectList\<T\>(ClientRuntimeContext context, ObjectPath objectPath)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **CustomFromJson(JsonReader reader)** | bool |  |
| **FromJson(JsonReader reader)** | void |  |
# ClientObjectPrototype Class

Namespace: Microsoft.SharePoint.Client


## Properties

| Name | Type | Summary |
|---|---|---|
| **Query** | [ClientQueryInternal](#clientqueryinternal-class) |  |
| **ChildItemPrototype** | bool |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Retrieve()** | void |  |
| **Retrieve(string[] propertyNames)** | void |  |
| **RetrieveCollectionObject(string propertyName)** | [ClientObjectCollectionPrototype](#clientobjectcollectionprototypeitemtype-class)\<ItemType\> |  |
| **RetrieveObject(string propertyName)** | [ClientObjectPrototype](#clientobjectprototypet-class)\<PropertyType\> |  |
# ClientObjectPrototype\<T\> Class

Namespace: Microsoft.SharePoint.Client

Base class: [ClientObjectPrototype](#clientobjectprototype-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **Query** | [ClientQueryInternal](#clientqueryinternal-class) |  |
| **ChildItemPrototype** | bool |  |
# ClientObjectQueryableExtension Class

Namespace: Microsoft.SharePoint.Client


## Methods

| Name | Returns | Summary |
|---|---|---|
| **Include(IQueryable\<TSource\> clientObjects, Expression\<Func\<TSource, Object\>\>[] retrievals)** | IQueryable\<TSource\> |  |
| **IncludeWithDefaultProperties(IQueryable\<TSource\> clientObjects, Expression\<Func\<TSource, Object\>\>[] retrievals)** | IQueryable\<TSource\> |  |
# ClientQueryable\<T\> Class

Namespace: Microsoft.SharePoint.Client


## Properties

| Name | Type | Summary |
|---|---|---|
| **ElementType** | Type |  |
| **Expression** | Expression |  |
| **Provider** | IQueryProvider |  |
## Constructors

| Name | Summary |
|---|---|
| **ClientQueryable\<T\>(ClientQueryProvider provider, Expression exp)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetEnumerator()** | IEnumerator\<T\> |  |
# ClientQueryableResult\<T\> Class

Namespace: Microsoft.SharePoint.Client


## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetEnumerator()** | IEnumerator\<T\> |  |
# ClientQueryInternal Class

Namespace: Microsoft.SharePoint.Client

Base class: [ClientAction](#clientaction-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **Context** | [ClientRuntimeContext](#clientruntimecontext-class) |  |
| **RootQuery** | [ClientQueryInternal](#clientqueryinternal-class) |  |
| **IsChildItemQuery** | bool |  |
| **HasChildItemQuery** | bool |  |
| **ChildItemQuery** | [ClientQueryInternal](#clientqueryinternal-class) |  |
| **ChildItemFilterSet** | bool |  |
| **ChildItemExpressionSerializationContext** | [SerializationContext](#serializationcontext-class) |  |
| **Id** | long |  |
| **Path** | [ObjectPath](#objectpath-class) |  |
| **Name** | string |  |
## Constructors

| Name | Summary |
|---|---|
| **ClientQueryInternal(ClientObject obj, string name, bool subQuery, ClientQueryInternal parentQuery)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Equals(Object obj)** | bool |  |
| **Equals(ClientQueryInternal query)** | bool |  |
| **GetHashCode()** | int |  |
| **Select(string propertyName)** | [ClientQueryInternal](#clientqueryinternal-class) |  |
| **SelectAllProperties()** | [ClientQueryInternal](#clientqueryinternal-class) |  |
| **SelectSubQuery(ClientQueryInternal subQuery)** | [ClientQueryInternal](#clientqueryinternal-class) |  |
| **SelectWithAll(string propertyName)** | [ClientQueryInternal](#clientqueryinternal-class) |  |
# ClientQueryProperty Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **ScalarProperty** | bool |  |
| **ScalarPropertySet** | bool |  |
| **SelectAll** | bool |  |
| **SelectAllSet** | bool |  |
| **Query** | [ClientQueryInternal](#clientqueryinternal-class) |  |
# ClientQueryProvider Class

Namespace: Microsoft.SharePoint.Client


# ClientRequest Class

Namespace: Microsoft.SharePoint.Client


## Properties

| Name | Type | Summary |
|---|---|---|
| **NextSequenceId** | long |  |
| **Context** | [ClientRuntimeContext](#clientruntimecontext-class) |  |
| **RequestExecutor** | [WebRequestExecutor](#webrequestexecutor-class) |  |
| **SoapPageUrl** | string |  |
| **RequestStatus** | [ClientRequestStatus](#clientrequeststatus-enum) |  |
| **Actions** | List\<[ClientAction](#clientaction-class)\> |  |
| **QueryBuilder** | [ChunkStringBuilder](#chunkstringbuilder-class) |  |
| **LastAction** | [ClientAction](#clientaction-class) |  |
| **ExecutionScopes** | Stack\<[ExecutionScope](#executionscope-class)\> |  |
| **SerializationContext** | [SerializationContext](#serializationcontext-class) |  |
| **QueryIdToObjectMap** | Dictionary\<string, Object\> |  |
# ClientRequestException Class

Namespace: Microsoft.SharePoint.Client

Base class: Exception


## Properties

| Name | Type | Summary |
|---|---|---|
| **TargetSite** | MethodBase |  |
| **StackTrace** | string |  |
| **Message** | string |  |
| **Data** | IDictionary |  |
| **InnerException** | Exception |  |
| **HelpLink** | string |  |
| **Source** | string |  |
| **HResult** | int |  |
## Constructors

| Name | Summary |
|---|---|
| **ClientRequestException(string message)** |  |
| **ClientRequestException(string message, Exception innerException)** |  |
# ClientRequestStatus Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Active** |  |
| **InProgress** |  |
| **CompletedSuccess** |  |
| **CompletedException** |  |
# ClientRequestWrapper Class

Namespace: Microsoft.SharePoint.Client


## Properties

| Name | Type | Summary |
|---|---|---|
| **Value** | [ClientRequest](#clientrequest-class) |  |
# ClientResult\<T\> Class

Namespace: Microsoft.SharePoint.Client


## Properties

| Name | Type | Summary |
|---|---|---|
| **Value** | T |  |
# ClientRuntimeContext Class

Namespace: Microsoft.SharePoint.Client


## Properties

| Name | Type | Summary |
|---|---|---|
| **NextSequenceId** | long |  |
| **ServiceRelativeUrl** | string |  |
| **Url** | string |  |
| **ApplicationName** | string |  |
| **ClientTag** | string |  |
| **DisableReturnValueCache** | bool |  |
| **ValidateOnClient** | bool |  |
| **Credentials** | ICredentials |  |
| **WebRequestExecutorFactory** | [WebRequestExecutorFactory](#webrequestexecutorfactory-class) |  |
| **PendingRequest** | [ClientRequest](#clientrequest-class) |  |
| **HasPendingRequest** | bool |  |
| **ProcessingResponse** | bool |  |
| **Tag** | Object |  |
| **RequestTimeout** | int |  |
| **StaticObjects** | Dictionary\<string, Object\> |  |
| **ObjectPaths** | Dictionary\<long, [ObjectPath](#objectpath-class)\> |  |
| **QueryProvider** | [ClientQueryProvider](#clientqueryprovider-class) |  |
| **ServerSchemaVersion** | Version |  |
| **ServerLibraryVersion** | Version |  |
| **RequestSchemaVersion** | Version |  |
| **TraceCorrelationId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **AddClientTypeAssembly(Assembly assembly)** | void |  |
| **AddQuery(ClientAction query)** | void |  |
| **AddQueryIdAndResultObject(long id, Object obj)** | void |  |
| **CastTo(ClientObject obj)** | T |  |
| **Dispose()** | void |  |
| **ExecuteQuery()** | void |  |
| **ExecuteQueryAsync()** | Task |  |
| **Load(T clientObject, Expression\<Func\<T, Object\>\>[] retrievals)** | void |  |
| **LoadQuery(ClientObjectCollection\<T\> clientObjects)** | IEnumerable\<T\> |  |
| **LoadQuery(IQueryable\<T\> clientObjects)** | IEnumerable\<T\> |  |
| **ParseObjectFromJsonString(string json)** | Object |  |
| **RetryQuery(ClientRequest request)** | void |  |
| **RetryQueryAsync(ClientRequest request)** | Task |  |
# ClientSchemaVersions Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Version14** | Version |  |
| **Version15** | Version |  |
| **CurrentVersion** | Version |  |
# ClientTypeAssemblyAttribute Class

Namespace: Microsoft.SharePoint.Client

Base class: Attribute


## Properties

| Name | Type | Summary |
|---|---|---|
| **ScriptTypeFactory** | Type |  |
| **TypeId** | Object |  |
# ClientUtility Class

Namespace: Microsoft.SharePoint.Client


## Methods

| Name | Returns | Summary |
|---|---|---|
| **CreateArgumentException(string argumentName)** | Exception |  |
| **CreateArgumentNullException(string argumentName)** | Exception |  |
# ClientValueObject Class

Namespace: Microsoft.SharePoint.Client


## Properties

| Name | Type | Summary |
|---|---|---|
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **CustomFromJson(JsonReader reader)** | bool |  |
| **CustomWriteToXml(XmlWriter writer, SerializationContext serializationContext)** | bool |  |
| **FromJson(JsonReader reader)** | void |  |
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# ClientValueObjectCollection\<T\> Class

Namespace: Microsoft.SharePoint.Client

Base class: [ClientValueObject](#clientvalueobject-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **ChildItemsName** | string |  |
| **Count** | int |  |
| **Item** | T |  |
| **TypeId** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(T item)** | void |  |
| **GetEnumerator()** | IEnumerator\<T\> |  |
| **WriteToXml(XmlWriter writer, SerializationContext serializationContext)** | void |  |
# CollectionNotInitializedException Class

Namespace: Microsoft.SharePoint.Client

Base class: InvalidOperationException


## Properties

| Name | Type | Summary |
|---|---|---|
| **TargetSite** | MethodBase |  |
| **StackTrace** | string |  |
| **Message** | string |  |
| **Data** | IDictionary |  |
| **InnerException** | Exception |  |
| **HelpLink** | string |  |
| **Source** | string |  |
| **HResult** | int |  |
## Constructors

| Name | Summary |
|---|---|
| **CollectionNotInitializedException(string message)** |  |
| **CollectionNotInitializedException(string message, Exception innerException)** |  |
# ConditionalExecutionScope Class

Namespace: Microsoft.SharePoint.Client

Base class: [ExecutionScope](#executionscope-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **Context** | [ClientRuntimeContext](#clientruntimecontext-class) |  |
| **ClientActionExecutionScopeStart** | [ClientActionExecutionScopeStart](#clientactionexecutionscopestart-class) |  |
| **Id** | long |  |
| **Name** | string |  |
| **Disposed** | bool |  |
# ConditionalExpressionToXmlConverter Class

Namespace: Microsoft.SharePoint.Client


## Constructors

| Name | Summary |
|---|---|
| **ConditionalExpressionToXmlConverter(Expression condition, XmlWriter writer, Dictionary\<string, Type\> allowedParameters, SerializationContext serializationContext)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Convert()** | void |  |
# ConditionalScope Class

Namespace: Microsoft.SharePoint.Client

Base class: [ConditionalScopeBase](#conditionalscopebase-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **TestExpression** | [ChunkStringBuilder](#chunkstringbuilder-class) |  |
| **TestExpressionSerializationContext** | [SerializationContext](#serializationcontext-class) |  |
| **TrueScope** | [ExecutionScope](#executionscope-class) |  |
| **FalseScope** | [ExecutionScope](#executionscope-class) |  |
| **TestResult** | bool? |  |
## Constructors

| Name | Summary |
|---|---|
| **ConditionalScope(ClientRuntimeContext context, Expression\<Func\<bool\>\> condition)** |  |
| **ConditionalScope(ClientRuntimeContext context, Expression\<Func\<bool\>\> condition, bool allowAllActions)** |  |
# ConditionalScopeBase Class

Namespace: Microsoft.SharePoint.Client


## Properties

| Name | Type | Summary |
|---|---|---|
| **TestExpression** | [ChunkStringBuilder](#chunkstringbuilder-class) |  |
| **TestExpressionSerializationContext** | [SerializationContext](#serializationcontext-class) |  |
| **TrueScope** | [ExecutionScope](#executionscope-class) |  |
| **FalseScope** | [ExecutionScope](#executionscope-class) |  |
| **TestResult** | bool? |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **CustomFromJson(JsonReader reader)** | bool |  |
| **FromJson(JsonReader reader)** | void |  |
| **StartIfFalse()** | IDisposable |  |
| **StartIfTrue()** | IDisposable |  |
| **StartScope()** | IDisposable |  |
# DataConvert Class

Namespace: Microsoft.SharePoint.Client


## Properties

| Name | Type | Summary |
|---|---|---|
| **StrongTypedArrayElementTypeNames** | Dictionary\<string, Type\> |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **WriteDictionaryToXml(XmlWriter writer, Dictionary\<string, Object\> dict, string topLevelElementTagName, string[] keys, SerializationContext serializationContext)** | void |  |
| **WriteValueToXmlElement(XmlWriter writer, Object objValue, SerializationContext serializationContext)** | void |  |
# DataRetrieval Class

Namespace: Microsoft.SharePoint.Client


# DefaultWebRequestExecutorFactory Class

Namespace: Microsoft.SharePoint.Client

Base class: [WebRequestExecutorFactory](#webrequestexecutorfactory-class)


## Methods

| Name | Returns | Summary |
|---|---|---|
| **CreateWebRequestExecutor(ClientRuntimeContext context, string requestUrl)** | [WebRequestExecutor](#webrequestexecutor-class) |  |
# EnumerableClientObjectCollection\<T\> Class

Namespace: Microsoft.SharePoint.Client


## Constructors

| Name | Summary |
|---|---|
| **EnumerableClientObjectCollection\<T\>(ClientObjectCollection\<T\> collection)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetEnumerator()** | IEnumerator\<T\> |  |
# ExceptionHandlingExecutionScope Class

Namespace: Microsoft.SharePoint.Client

Base class: [ExecutionScope](#executionscope-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **Context** | [ClientRuntimeContext](#clientruntimecontext-class) |  |
| **ClientActionExecutionScopeStart** | [ClientActionExecutionScopeStart](#clientactionexecutionscopestart-class) |  |
| **Id** | long |  |
| **Name** | string |  |
| **Disposed** | bool |  |
# ExceptionHandlingScope Class

Namespace: Microsoft.SharePoint.Client


## Properties

| Name | Type | Summary |
|---|---|---|
| **IsSimpleForm** | bool |  |
| **Processed** | bool |  |
| **HasException** | bool |  |
| **ErrorMessage** | string |  |
| **ServerStackTrace** | string |  |
| **ServerErrorCode** | int |  |
| **ServerErrorValue** | string |  |
| **ServerErrorTypeName** | string |  |
| **ServerErrorDetails** | Object |  |
## Constructors

| Name | Summary |
|---|---|
| **ExceptionHandlingScope(ClientRuntimeContext context)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **StartCatch()** | IDisposable |  |
| **StartFinally()** | IDisposable |  |
| **StartScope()** | IDisposable |  |
| **StartTry()** | IDisposable |  |
# ExecuteQueryMimeInfo Class

Namespace: Microsoft.SharePoint.Client


## Properties

| Name | Type | Summary |
|---|---|---|
| **Boundary** | string |  |
| **MainPartCid** | string |  |
| **ContentType** | string |  |
# ExecutionScope Class

Namespace: Microsoft.SharePoint.Client


## Properties

| Name | Type | Summary |
|---|---|---|
| **Context** | [ClientRuntimeContext](#clientruntimecontext-class) |  |
| **ClientActionExecutionScopeStart** | [ClientActionExecutionScopeStart](#clientactionexecutionscopestart-class) |  |
| **Id** | long |  |
| **Name** | string |  |
| **Disposed** | bool |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Dispose()** | void |  |
# ExecutionScopeDisposingCallback Class

Namespace: Microsoft.SharePoint.Client

Base class: MulticastDelegate


## Properties

| Name | Type | Summary |
|---|---|---|
| **Target** | Object |  |
| **Method** | MethodInfo |  |
## Constructors

| Name | Summary |
|---|---|
| **ExecutionScopeDisposingCallback(Object object, IntPtr method)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **BeginInvoke(AsyncCallback callback, Object object)** | IAsyncResult |  |
| **EndInvoke(IAsyncResult result)** | void |  |
| **Invoke()** | void |  |
# ExpressionEvaluator Class

Namespace: Microsoft.SharePoint.Client


## Methods

| Name | Returns | Summary |
|---|---|---|
| **PartialEvaluate(Expression exp, Func\<Expression, bool\> fnCanBeEvaluated)** | Expression |  |
# ExpressionUtility Class

Namespace: Microsoft.SharePoint.Client


## Methods

| Name | Returns | Summary |
|---|---|---|
| **IsGetFieldValueMethod(MethodInfo method)** | bool |  |
| **StripConverts(Expression exp)** | Expression |  |
| **StripQuotes(Expression exp)** | Expression |  |
# ExpressionVisitor Class

Namespace: Microsoft.SharePoint.Client


## Methods

| Name | Returns | Summary |
|---|---|---|
| **Visit(Expression exp)** | Expression |  |
| **VisitBinary(BinaryExpression exp)** | Expression |  |
| **VisitBinding(MemberBinding binding)** | MemberBinding |  |
| **VisitBindingList(ReadOnlyCollection\<MemberBinding\> original)** | IEnumerable\<MemberBinding\> |  |
| **VisitConditional(ConditionalExpression exp)** | Expression |  |
| **VisitConstant(ConstantExpression exp)** | Expression |  |
| **VisitElementInitializer(ElementInit initializer)** | ElementInit |  |
| **VisitElementInitializerList(ReadOnlyCollection\<ElementInit\> original)** | IEnumerable\<ElementInit\> |  |
| **VisitExpressionList(ReadOnlyCollection\<Expression\> original)** | ReadOnlyCollection\<Expression\> |  |
| **VisitInvocation(InvocationExpression iv)** | Expression |  |
| **VisitLambda(LambdaExpression exp)** | Expression |  |
| **VisitListInit(ListInitExpression init)** | Expression |  |
| **VisitMemberAccess(MemberExpression m)** | Expression |  |
| **VisitMemberAssignment(MemberAssignment assignment)** | MemberAssignment |  |
| **VisitMemberInit(MemberInitExpression init)** | Expression |  |
| **VisitMemberListBinding(MemberListBinding binding)** | MemberListBinding |  |
| **VisitMemberMemberBinding(MemberMemberBinding binding)** | MemberMemberBinding |  |
| **VisitMethodCall(MethodCallExpression m)** | Expression |  |
| **VisitNew(NewExpression nex)** | NewExpression |  |
| **VisitNewArray(NewArrayExpression na)** | Expression |  |
| **VisitParameter(ParameterExpression p)** | Expression |  |
| **VisitTypeIs(TypeBinaryExpression b)** | Expression |  |
| **VisitUnary(UnaryExpression u)** | Expression |  |
# IFromJson Class

Namespace: Microsoft.SharePoint.Client


## Methods

| Name | Returns | Summary |
|---|---|---|
| **CustomFromJson(JsonReader reader)** | bool |  |
| **FromJson(JsonReader reader)** | void |  |
# InvalidQueryExpressionException Class

Namespace: Microsoft.SharePoint.Client

Base class: [ClientRequestException](#clientrequestexception-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **TargetSite** | MethodBase |  |
| **StackTrace** | string |  |
| **Message** | string |  |
| **Data** | IDictionary |  |
| **InnerException** | Exception |  |
| **HelpLink** | string |  |
| **Source** | string |  |
| **HResult** | int |  |
## Constructors

| Name | Summary |
|---|---|
| **InvalidQueryExpressionException(string message)** |  |
| **InvalidQueryExpressionException(string message, Exception innerException)** |  |
# IScriptTypeFactory Class

Namespace: Microsoft.SharePoint.Client


## Methods

| Name | Returns | Summary |
|---|---|---|
| **CreateObjectFromScriptType(string scriptTypeName, ClientRuntimeContext context)** | [IFromJson](#ifromjson-class) |  |
# JsonReader Class

Namespace: Microsoft.SharePoint.Client


## Properties

| Name | Type | Summary |
|---|---|---|
| **Context** | [ClientRuntimeContext](#clientruntimecontext-class) |  |
| **ReadDictionaryMethod** | MethodInfo |  |
## Constructors

| Name | Summary |
|---|---|
| **JsonReader(TextReader reader, ClientRuntimeContext runtimeContext)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Dispose()** | void |  |
| **PeekName()** | string |  |
| **PeekTokenType()** | [JsonTokenType](#jsontokentype-enum) |  |
| **Read()** | T |  |
| **ReadArray()** | T[] |  |
| **ReadArrayEnd()** | void |  |
| **ReadArrayStart()** | void |  |
| **ReadBoolean()** | bool |  |
| **ReadBooleanArray()** | bool[] |  |
| **ReadByte()** | byte |  |
| **ReadByteArray()** | byte[] |  |
| **ReadChar()** | char |  |
| **ReadDateTime()** | DateTime |  |
| **ReadDateTimeArray()** | DateTime[] |  |
| **ReadDecimal()** | decimal |  |
| **ReadDecimalArray()** | decimal[] |  |
| **ReadDictionary()** | Dictionary\<string, T\> |  |
| **ReadDictionary()** | Dictionary\<string, Object\> |  |
| **ReadDouble()** | double |  |
| **ReadDoubleArray()** | double[] |  |
| **ReadEnum()** | T |  |
| **ReadEnumArray()** | T[] |  |
| **ReadGuid()** | Guid |  |
| **ReadGuidArray()** | Guid[] |  |
| **ReadInt16()** | short |  |
| **ReadInt16Array()** | short[] |  |
| **ReadInt32()** | int |  |
| **ReadInt32Array()** | int[] |  |
| **ReadInt64()** | long |  |
| **ReadInt64Array()** | long[] |  |
| **ReadKeyValue()** | KeyValuePair\<string, Object\> |  |
| **ReadList()** | List\<T\> |  |
| **ReadName()** | string |  |
| **ReadObject()** | Object |  |
| **ReadObjectArray()** | Object[] |  |
| **ReadObjectEnd()** | void |  |
| **ReadObjectStart()** | void |  |
| **ReadSingle()** | float |  |
| **ReadSingleArray()** | float[] |  |
| **ReadStream()** | Stream |  |
| **ReadString()** | string |  |
| **ReadStringArray()** | string[] |  |
| **ReadStringCollection()** | StringCollection |  |
| **ReadTimeSpan()** | TimeSpan |  |
| **ReadTimeSpanArray()** | TimeSpan[] |  |
| **ReadUInt16()** | ushort |  |
| **ReadUInt16Array()** | ushort[] |  |
| **ReadUInt32()** | uint |  |
| **ReadUInt32Array()** | uint[] |  |
| **ReadUInt64()** | ulong |  |
| **ReadUInt64Array()** | ulong[] |  |
# JsonReaderOptions Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **DoNotUseEscapedToken** |  |
| **IgnoreStringValue** |  |
# JsonTokenType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **ObjectStart** |  |
| **ObjectEnd** |  |
| **ArrayStart** |  |
| **ArrayEnd** |  |
| **String** |  |
| **Long** |  |
| **ULong** |  |
| **Double** |  |
| **Boolean** |  |
| **DateTime** |  |
| **Guid** |  |
| **Null** |  |
| **Name** |  |
| **ByteArray** |  |
| **StreamLink** |  |
# Nominator Class

Namespace: Microsoft.SharePoint.Client

Base class: [ExpressionVisitor](#expressionvisitor-class)


## Methods

| Name | Returns | Summary |
|---|---|---|
| **Visit(Expression expr)** | Expression |  |
# NotSupportedExpressionChecker Class

Namespace: Microsoft.SharePoint.Client

Base class: [ExpressionVisitor](#expressionvisitor-class)


## Constructors

| Name | Summary |
|---|---|
| **NotSupportedExpressionChecker(Dictionary\<string, Type\> allowedParameters)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **VisitMemberAccess(MemberExpression m)** | Expression |  |
| **VisitMethodCall(MethodCallExpression m)** | Expression |  |
| **VisitParameter(ParameterExpression p)** | Expression |  |
# ObjectIdentityQuery Class

Namespace: Microsoft.SharePoint.Client

Base class: [ClientAction](#clientaction-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **Id** | long |  |
| **Path** | [ObjectPath](#objectpath-class) |  |
| **Name** | string |  |
## Constructors

| Name | Summary |
|---|---|
| **ObjectIdentityQuery(ObjectPath objectPath)** |  |
# ObjectPath Class

Namespace: Microsoft.SharePoint.Client


## Properties

| Name | Type | Summary |
|---|---|---|
| **Context** | [ClientRuntimeContext](#clientruntimecontext-class) |  |
| **Parent** | [ObjectPath](#objectpath-class) |  |
| **Id** | long |  |
| **ServerObjectIsNull** | bool? |  |
| **IsValid** | bool |  |
| **ObjectName** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **SetPendingReplace()** | void |  |
# ObjectPathConstructor Class

Namespace: Microsoft.SharePoint.Client

Base class: [ObjectPath](#objectpath-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **ObjectName** | string |  |
| **Context** | [ClientRuntimeContext](#clientruntimecontext-class) |  |
| **Parent** | [ObjectPath](#objectpath-class) |  |
| **Id** | long |  |
| **ServerObjectIsNull** | bool? |  |
| **IsValid** | bool |  |
## Constructors

| Name | Summary |
|---|---|
| **ObjectPathConstructor(ClientRuntimeContext context, string typeId, Object[] parameters)** |  |
# ObjectPathIdentity Class

Namespace: Microsoft.SharePoint.Client

Base class: [ObjectPath](#objectpath-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **Identity** | string |  |
| **ObjectName** | string |  |
| **Context** | [ClientRuntimeContext](#clientruntimecontext-class) |  |
| **Parent** | [ObjectPath](#objectpath-class) |  |
| **Id** | long |  |
| **ServerObjectIsNull** | bool? |  |
| **IsValid** | bool |  |
## Constructors

| Name | Summary |
|---|---|
| **ObjectPathIdentity(ClientRuntimeContext context, string identity)** |  |
# ObjectPathMethod Class

Namespace: Microsoft.SharePoint.Client

Base class: [ObjectPath](#objectpath-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **ObjectName** | string |  |
| **Context** | [ClientRuntimeContext](#clientruntimecontext-class) |  |
| **Parent** | [ObjectPath](#objectpath-class) |  |
| **Id** | long |  |
| **ServerObjectIsNull** | bool? |  |
| **IsValid** | bool |  |
## Constructors

| Name | Summary |
|---|---|
| **ObjectPathMethod(ClientRuntimeContext context, ObjectPath parent, string methodName, Object[] parameters)** |  |
# ObjectPathProperty Class

Namespace: Microsoft.SharePoint.Client

Base class: [ObjectPath](#objectpath-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **ObjectName** | string |  |
| **Context** | [ClientRuntimeContext](#clientruntimecontext-class) |  |
| **Parent** | [ObjectPath](#objectpath-class) |  |
| **Id** | long |  |
| **ServerObjectIsNull** | bool? |  |
| **IsValid** | bool |  |
## Constructors

| Name | Summary |
|---|---|
| **ObjectPathProperty(ClientRuntimeContext context, ObjectPath parent, string propertyName)** |  |
# ObjectPathStaticMethod Class

Namespace: Microsoft.SharePoint.Client

Base class: [ObjectPath](#objectpath-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **ObjectName** | string |  |
| **Context** | [ClientRuntimeContext](#clientruntimecontext-class) |  |
| **Parent** | [ObjectPath](#objectpath-class) |  |
| **Id** | long |  |
| **ServerObjectIsNull** | bool? |  |
| **IsValid** | bool |  |
## Constructors

| Name | Summary |
|---|---|
| **ObjectPathStaticMethod(ClientRuntimeContext context, string typeId, string methodName, Object[] parameters)** |  |
# ObjectPathStaticProperty Class

Namespace: Microsoft.SharePoint.Client

Base class: [ObjectPath](#objectpath-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **ObjectName** | string |  |
| **Context** | [ClientRuntimeContext](#clientruntimecontext-class) |  |
| **Parent** | [ObjectPath](#objectpath-class) |  |
| **Id** | long |  |
| **ServerObjectIsNull** | bool? |  |
| **IsValid** | bool |  |
## Constructors

| Name | Summary |
|---|---|
| **ObjectPathStaticProperty(ClientRuntimeContext context, string typeId, string propertyName)** |  |
# OfficeVersion Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **FullBuildVersion** | string |  |
| **FullBuildBase** | string |  |
| **MajorBuildVersion** | int |  |
| **PreviousMajorBuildVersion** | int |  |
| **MaxCompatibilityLevel** | int |  |
| **MajorVersion** | string |  |
| **PreviousVersion** | string |  |
| **MaxCompatibility** | string |  |
| **MajorVersionDotZero** | string |  |
| **PreviousVersionDotZero** | string |  |
| **AssemblyVersion** | string |  |
| **WssMajorVersion** | string |  |
# PropertyOrFieldNotInitializedException Class

Namespace: Microsoft.SharePoint.Client

Base class: InvalidOperationException


## Properties

| Name | Type | Summary |
|---|---|---|
| **TargetSite** | MethodBase |  |
| **StackTrace** | string |  |
| **Message** | string |  |
| **Data** | IDictionary |  |
| **InnerException** | Exception |  |
| **HelpLink** | string |  |
| **Source** | string |  |
| **HResult** | int |  |
## Constructors

| Name | Summary |
|---|---|
| **PropertyOrFieldNotInitializedException(string message)** |  |
| **PropertyOrFieldNotInitializedException(string message, Exception innerException)** |  |
# PseudoRemoteAttribute Class

Namespace: Microsoft.SharePoint.Client

Base class: Attribute


## Properties

| Name | Type | Summary |
|---|---|---|
| **Name** | string |  |
| **TypeId** | Object |  |
# QueryMethodAggregator Class

Namespace: Microsoft.SharePoint.Client


## Properties

| Name | Type | Summary |
|---|---|---|
| **IsEmpty** | bool |  |
## Constructors

| Name | Summary |
|---|---|
| **QueryMethodAggregator(Expression exp)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Check()** | void |  |
## Fields

| Name | Type | Summary |
|---|---|---|
| **Where** | int |  |
| **Include** | int |  |
| **Take** | int |  |
| **Select** | int |  |
| **Member** | int |  |
| **OrderBy** | int |  |
| **OrderByDescending** | int |  |
# QueryProcessInfo Class

Namespace: Microsoft.SharePoint.Client


## Methods

| Name | Returns | Summary |
|---|---|---|
| **FinalProcess()** | void |  |
## Fields

| Name | Type | Summary |
|---|---|---|
| **BySelect** | Dictionary\<long, [ClientQueryInternal](#clientqueryinternal-class)\> |  |
| **ByInclude** | Dictionary\<long, [ClientQueryInternal](#clientqueryinternal-class)\> |  |
| **Expression** | Dictionary\<[ClientQueryInternal](#clientqueryinternal-class), [ChunkStringBuilder](#chunkstringbuilder-class)\> |  |
# ReadObjectHandler Class

Namespace: Microsoft.SharePoint.Client

Base class: MulticastDelegate


## Properties

| Name | Type | Summary |
|---|---|---|
| **Target** | Object |  |
| **Method** | MethodInfo |  |
## Constructors

| Name | Summary |
|---|---|
| **ReadObjectHandler(Object object, IntPtr method)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **BeginInvoke(JsonReader reader, AsyncCallback callback, Object object)** | IAsyncResult |  |
| **EndInvoke(IAsyncResult result)** | Object |  |
| **Invoke(JsonReader reader)** | Object |  |
# ReadObjectHandlers Class

Namespace: Microsoft.SharePoint.Client


## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetReadObjectHandler(Type type)** | [ReadObjectHandler](#readobjecthandler-class) |  |
# ReadonlyChunkStream Class

Namespace: Microsoft.SharePoint.Client

Base class: Stream


## Properties

| Name | Type | Summary |
|---|---|---|
| **CanRead** | bool |  |
| **CanSeek** | bool |  |
| **CanWrite** | bool |  |
| **Length** | long |  |
| **Position** | long |  |
| **CanTimeout** | bool |  |
| **ReadTimeout** | int |  |
| **WriteTimeout** | int |  |
## Constructors

| Name | Summary |
|---|---|
| **ReadonlyChunkStream(ChunkStreamBuilder sb, bool owner)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Flush()** | void |  |
| **Read(byte[] buffer, int offset, int count)** | int |  |
| **ReadByte()** | int |  |
| **Seek(long offset, SeekOrigin loc)** | long |  |
| **SetLength(long value)** | void |  |
| **Write(byte[] buffer, int offset, int count)** | void |  |
| **WriteByte(byte value)** | void |  |
# ReadonlyWrapStream Class

Namespace: Microsoft.SharePoint.Client

Base class: Stream


## Properties

| Name | Type | Summary |
|---|---|---|
| **UnderlyingStream** | Stream |  |
| **OwnUnderlyingStream** | bool |  |
| **TotalReadCountAction** | Action\<long\> |  |
| **CanRead** | bool |  |
| **CanSeek** | bool |  |
| **CanWrite** | bool |  |
| **Length** | long |  |
| **Position** | long |  |
| **CanTimeout** | bool |  |
| **ReadTimeout** | int |  |
| **WriteTimeout** | int |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Flush()** | void |  |
| **Read(byte[] buffer, int offset, int count)** | int |  |
| **ReadByte()** | int |  |
| **Seek(long offset, SeekOrigin origin)** | long |  |
| **SetLength(long value)** | void |  |
| **Write(byte[] buffer, int offset, int count)** | void |  |
# RemoteAttribute Class

Namespace: Microsoft.SharePoint.Client

Base class: Attribute


## Properties

| Name | Type | Summary |
|---|---|---|
| **Name** | string |  |
| **TypeId** | Object |  |
# ReplaceQueryableCollectionWithEnumerableCollectionExpressionVisitor Class

Namespace: Microsoft.SharePoint.Client

Base class: [ExpressionVisitor](#expressionvisitor-class)


## Methods

| Name | Returns | Summary |
|---|---|---|
| **VisitConstant(ConstantExpression exp)** | Expression |  |
# Resources Class

Namespace: Microsoft.SharePoint.Client


## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetString(string resourceId)** | string |  |
| **GetString(string resourceId, Object[] args)** | string |  |
# ResourceStrings Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **ArgumentExceptionMessage** | string |  |
| **ArgumentNullExceptionMessage** | string |  |
| **CannotContactSite** | string |  |
| **CannotContactSiteWithDetails** | string |  |
| **CannotFindContextWebServerRelativeUrl** | string |  |
| **CannotGetCookie** | string |  |
| **CannotHandleServerResponseSchema** | string |  |
| **CollectionHasNotBeenInitialized** | string |  |
| **CollectionModified** | string |  |
| **ETagNotMatch** | string |  |
| **FileAlreadyExists** | string |  |
| **FormsAuthenticationCannotLogin** | string |  |
| **InvalidIdcrlHeader** | string |  |
| **InvalidQueryExecution** | string |  |
| **InvalidUsageOfConditionalScope** | string |  |
| **InvalidUsageOfConditionalScopeNowAllowedAction** | string |  |
| **InvalidUsageOfExceptionHandlingScope** | string |  |
| **JsonDataTypeNotMatch** | string |  |
| **JsonNotWellFormated** | string |  |
| **JsonReachTheEndOfStream** | string |  |
| **JsonUnknownData** | string |  |
| **MimeContentLengthHeaderInvalid** | string |  |
| **MimeContentTypeHeaderInvalid** | string |  |
| **MimeHeaderInvalidCharacter** | string |  |
| **MimeMessageGetContentStreamCalledAlready** | string |  |
| **MimeReaderHeaderAlreadyExists** | string |  |
| **MimeReaderMalformedHeader** | string |  |
| **MimeReaderResetCalledBeforeEOF** | string |  |
| **MimeReaderTruncated** | string |  |
| **MimeVersionHeaderInvalid** | string |  |
| **MimeWriterInvalidStateForClose** | string |  |
| **MimeWriterInvalidStateForContent** | string |  |
| **MimeWriterInvalidStateForHeader** | string |  |
| **MimeWriterInvalidStateForStartPart** | string |  |
| **MimeWriterInvalidStateForStartPreface** | string |  |
| **MissedFormsAuthLoginInfo** | string |  |
| **MtomBufferQuotaExceeded** | string |  |
| **MtomExceededMaxSizeInBytes** | string |  |
| **NamedPropertyHasNotBeenInitialized** | string |  |
| **NamedServerObjectIsNull** | string |  |
| **NoDirectHttpRequest** | string |  |
| **NoDirectRequest** | string |  |
| **NoObjectPathAssociatedWithObject** | string |  |
| **NonAllowedInUIThread** | string |  |
| **NotSameClientContext** | string |  |
| **NotSupportedExpression** | string |  |
| **NotSupportedMemberInExpression** | string |  |
| **NotSupportedQueryExpression** | string |  |
| **NotSupportedQueryExpressionWithExpressionDetail** | string |  |
| **NotSupportedQueryExpressionWithExpressionValue** | string |  |
| **ObjectNameIdentity** | string |  |
| **ObjectNameMethod** | string |  |
| **ObjectNameProperty** | string |  |
| **ObjectNameType** | string |  |
| **PropertyHasNotBeenInitialized** | string |  |
| **QueryableResultNotAvailable** | string |  |
| **RequestAbortedOrTimedOut** | string |  |
| **RequestEmptyQueryName** | string |  |
| **RequestHasBeenExecuted** | string |  |
| **RequestUnexpectedResponse** | string |  |
| **RequestUnexpectedResponseWithContentTypeAndStatus** | string |  |
| **RequestUnexpectedResponseWithStatus** | string |  |
| **RequestUnknownResponse** | string |  |
| **ServerNotInFormsAuthenticationMode** | string |  |
| **ServerObjectIsNull** | string |  |
| **SharePointClientCredentialsNotSupported** | string |  |
| **UnknownError** | string |  |
| **UnknownResponseData** | string |  |
| **WriteBufferOverflow** | string |  |
# Scope Class

Namespace: Microsoft.SharePoint.Client


## Properties

| Name | Type | Summary |
|---|---|---|
| **ObjectCount** | int |  |
| **Type** | [ScopeType](#scopetype-enum) |  |
## Constructors

| Name | Summary |
|---|---|
| **Scope(ScopeType type)** |  |
# ScopeType Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Array** |  |
| **Object** |  |
# ScriptTypeAttribute Class

Namespace: Microsoft.SharePoint.Client

Base class: Attribute


## Properties

| Name | Type | Summary |
|---|---|---|
| **ScriptType** | string |  |
| **TypeAlias** | string |  |
| **ValueObject** | bool |  |
| **ServerTypeId** | string |  |
| **TypeId** | Object |  |
## Constructors

| Name | Summary |
|---|---|
| **ScriptTypeAttribute(string scriptType)** |  |
# ScriptTypeInfo Class

Namespace: Microsoft.SharePoint.Client


## Constructors

| Name | Summary |
|---|---|
| **ScriptTypeInfo(Type type, bool valueObject)** |  |
## Fields

| Name | Type | Summary |
|---|---|---|
| **Type** | Type |  |
| **ValueObject** | bool |  |
# ScriptTypeMap Class

Namespace: Microsoft.SharePoint.Client


## Properties

| Name | Type | Summary |
|---|---|---|
| **IsInited** | bool |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **CreateObjectFromFallbackScriptType(Type fallbackType, ClientRuntimeContext context)** | [IFromJson](#ifromjson-class) |  |
| **CreateObjectFromScriptType(string scriptType, ClientRuntimeContext context)** | [IFromJson](#ifromjson-class) |  |
| **GetTypeFromScriptType(string scriptType)** | Type |  |
# SerializationContext Class

Namespace: Microsoft.SharePoint.Client


## Properties

| Name | Type | Summary |
|---|---|---|
| **Context** | [ClientRuntimeContext](#clientruntimecontext-class) |  |
| **Streams** | List\<[StreamInfo](#streaminfo-class)\> |  |
| **Paths** | Dictionary\<long, [ObjectPath](#objectpath-class)\> |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **AddClientObject(ClientObject obj)** | void |  |
| **AddObjectPath(ObjectPath path)** | void |  |
# ServerException Class

Namespace: Microsoft.SharePoint.Client

Base class: Exception


## Properties

| Name | Type | Summary |
|---|---|---|
| **ServerStackTrace** | string |  |
| **ServerErrorCode** | int |  |
| **ServerErrorValue** | string |  |
| **ServerErrorTypeName** | string |  |
| **ServerErrorDetails** | Object |  |
| **ServerErrorTraceCorrelationId** | string |  |
| **TargetSite** | MethodBase |  |
| **StackTrace** | string |  |
| **Message** | string |  |
| **Data** | IDictionary |  |
| **InnerException** | Exception |  |
| **HelpLink** | string |  |
| **Source** | string |  |
| **HResult** | int |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **ToString()** | string |  |
# ServerObjectNullReferenceException Class

Namespace: Microsoft.SharePoint.Client

Base class: InvalidOperationException


## Properties

| Name | Type | Summary |
|---|---|---|
| **TargetSite** | MethodBase |  |
| **StackTrace** | string |  |
| **Message** | string |  |
| **Data** | IDictionary |  |
| **InnerException** | Exception |  |
| **HelpLink** | string |  |
| **Source** | string |  |
| **HResult** | int |  |
## Constructors

| Name | Summary |
|---|---|
| **ServerObjectNullReferenceException(string message)** |  |
| **ServerObjectNullReferenceException(string message, Exception innerException)** |  |
# ServerUnauthorizedAccessException Class

Namespace: Microsoft.SharePoint.Client

Base class: [ServerException](#serverexception-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **ServerStackTrace** | string |  |
| **ServerErrorCode** | int |  |
| **ServerErrorValue** | string |  |
| **ServerErrorTypeName** | string |  |
| **ServerErrorDetails** | Object |  |
| **ServerErrorTraceCorrelationId** | string |  |
| **TargetSite** | MethodBase |  |
| **StackTrace** | string |  |
| **Message** | string |  |
| **Data** | IDictionary |  |
| **InnerException** | Exception |  |
| **HelpLink** | string |  |
| **Source** | string |  |
| **HResult** | int |  |
# SimpleDataTable Class

Namespace: Microsoft.SharePoint.Client


## Properties

| Name | Type | Summary |
|---|---|---|
| **Rows** | Collection\<Dictionary\<string, Object\>\> |  |
# SPResourceManager Class

Namespace: Microsoft.SharePoint.Client

Base class: ResourceManager


## Properties

| Name | Type | Summary |
|---|---|---|
| **BaseName** | string |  |
| **IgnoreCase** | bool |  |
| **ResourceSetType** | Type |  |
| **FallbackLocation** | UltimateResourceFallbackLocation |  |
## Constructors

| Name | Summary |
|---|---|
| **SPResourceManager(string baseName, Assembly assembly)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetObject(string name, CultureInfo culture)** | Object |  |
| **GetString(string name, CultureInfo culture)** | string |  |
# SPWebRequestExecutor Class

Namespace: Microsoft.SharePoint.Client

Base class: [WebRequestExecutor](#webrequestexecutor-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **WebRequest** | HttpWebRequest |  |
| **RequestContentType** | string |  |
| **RequestMethod** | string |  |
| **RequestKeepAlive** | bool |  |
| **RequestHeaders** | WebHeaderCollection |  |
| **StatusCode** | HttpStatusCode |  |
| **ResponseContentType** | string |  |
| **ResponseHeaders** | WebHeaderCollection |  |
## Constructors

| Name | Summary |
|---|---|
| **SPWebRequestExecutor(ClientRuntimeContext context, string requestUrl)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Dispose()** | void |  |
| **Execute()** | void |  |
| **ExecuteAsync()** | Task |  |
| **GetRequestStream()** | Stream |  |
| **GetResponseStream()** | Stream |  |
# StreamInfo Class

Namespace: Microsoft.SharePoint.Client


## Properties

| Name | Type | Summary |
|---|---|---|
| **Id** | string |  |
| **Stream** | Stream |  |
## Constructors

| Name | Summary |
|---|---|
| **StreamInfo(string streamId, Stream stream)** |  |
# SubtreeEvaluator Class

Namespace: Microsoft.SharePoint.Client

Base class: [ExpressionVisitor](#expressionvisitor-class)


## Methods

| Name | Returns | Summary |
|---|---|---|
| **Evaluate(Expression exp)** | Expression |  |
| **Visit(Expression expr)** | Expression |  |
# TextPeekReader Class

Namespace: Microsoft.SharePoint.Client

Base class: TextReader


## Properties

| Name | Type | Summary |
|---|---|---|
| **BufferSize** | int |  |
| **Offset** | int |  |
## Constructors

| Name | Summary |
|---|---|
| **TextPeekReader(TextReader reader)** |  |
| **TextPeekReader(TextReader reader, int bufferSize)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Close()** | void |  |
| **Peek()** | int |  |
| **Peek(int position)** | int |  |
| **Peek(char[] buffer, int count)** | int |  |
| **Read()** | int |  |
| **Read(char[] buffer, int count)** | int |  |
| **Read(char[] buffer, int offset, int count)** | int |  |
| **Skip()** | int |  |
| **Skip(int count)** | int |  |
# Token Class

Namespace: Microsoft.SharePoint.Client


## Properties

| Name | Type | Summary |
|---|---|---|
| **Type** | [JsonTokenType](#jsontokentype-enum) |  |
| **Position** | int |  |
| **StringValue** | string |  |
| **LongValue** | long |  |
| **ULongValue** | ulong |  |
| **DoubleValue** | double |  |
| **BoolValue** | bool |  |
| **DateTimeValue** | DateTime |  |
| **GuidValue** | Guid |  |
| **ByteArrayValue** | byte[] |  |
## Constructors

| Name | Summary |
|---|---|
| **Token(JsonTokenType tokenType, int position)** |  |
# UTF8ReadonlyStream Class

Namespace: Microsoft.SharePoint.Client

Base class: Stream


## Properties

| Name | Type | Summary |
|---|---|---|
| **CanRead** | bool |  |
| **CanWrite** | bool |  |
| **CanSeek** | bool |  |
| **Length** | long |  |
| **Position** | long |  |
| **CanTimeout** | bool |  |
| **ReadTimeout** | int |  |
| **WriteTimeout** | int |  |
## Constructors

| Name | Summary |
|---|---|
| **UTF8ReadonlyStream(ChunkStringBuilder sb)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Flush()** | void |  |
| **Read(byte[] buffer, int offset, int count)** | int |  |
| **ReadByte()** | int |  |
| **Seek(long offset, SeekOrigin origin)** | long |  |
| **SetLength(long value)** | void |  |
| **Write(byte[] buffer, int offset, int count)** | void |  |
| **WriteByte(byte value)** | void |  |
# WebRequestEventArgs Class

Namespace: Microsoft.SharePoint.Client

Base class: EventArgs


## Properties

| Name | Type | Summary |
|---|---|---|
| **WebRequestExecutor** | [WebRequestExecutor](#webrequestexecutor-class) |  |
## Constructors

| Name | Summary |
|---|---|
| **WebRequestEventArgs(WebRequestExecutor webRequestExecutor)** |  |
# WebRequestExecutor Class

Namespace: Microsoft.SharePoint.Client


## Properties

| Name | Type | Summary |
|---|---|---|
| **WebRequest** | HttpWebRequest |  |
| **RequestContentType** | string |  |
| **RequestHeaders** | WebHeaderCollection |  |
| **RequestMethod** | string |  |
| **RequestKeepAlive** | bool |  |
| **StatusCode** | HttpStatusCode |  |
| **ResponseContentType** | string |  |
| **ResponseHeaders** | WebHeaderCollection |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Dispose()** | void |  |
| **Execute()** | void |  |
| **ExecuteAsync()** | Task |  |
| **GetRequestStream()** | Stream |  |
| **GetResponseStream()** | Stream |  |
# WebRequestExecutorFactory Class

Namespace: Microsoft.SharePoint.Client


## Methods

| Name | Returns | Summary |
|---|---|---|
| **CreateWebRequestExecutor(ClientRuntimeContext context, string requestUrl)** | [WebRequestExecutor](#webrequestexecutor-class) |  |
# WriteValueHandler Class

Namespace: Microsoft.SharePoint.Client

Base class: MulticastDelegate


## Properties

| Name | Type | Summary |
|---|---|---|
| **Target** | Object |  |
| **Method** | MethodInfo |  |
## Constructors

| Name | Summary |
|---|---|
| **WriteValueHandler(Object object, IntPtr method)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **BeginInvoke(XmlWriter writer, Object objValue, AsyncCallback callback, Object object)** | IAsyncResult |  |
| **EndInvoke(IAsyncResult result)** | void |  |
| **Invoke(XmlWriter writer, Object objValue)** | void |  |
# BufferedReadStream Class

Namespace: Microsoft.SharePoint.Client.Mime

Base class: Stream


## Properties

| Name | Type | Summary |
|---|---|---|
| **CanWrite** | bool |  |
| **CanSeek** | bool |  |
| **CanRead** | bool |  |
| **Length** | long |  |
| **Position** | long |  |
| **CanTimeout** | bool |  |
| **ReadTimeout** | int |  |
| **WriteTimeout** | int |  |
## Constructors

| Name | Summary |
|---|---|
| **BufferedReadStream(Stream stream)** |  |
| **BufferedReadStream(Stream stream, bool readMore)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **BeginRead(byte[] buffer, int offset, int count, AsyncCallback callback, Object state)** | IAsyncResult |  |
| **BeginWrite(byte[] buffer, int offset, int count, AsyncCallback callback, Object state)** | IAsyncResult |  |
| **Close()** | void |  |
| **EndRead(IAsyncResult asyncResult)** | int |  |
| **EndWrite(IAsyncResult asyncResult)** | void |  |
| **Flush()** | void |  |
| **Push(byte[] buffer, int offset, int count)** | void |  |
| **Read(byte[] buffer, int offset, int count)** | int |  |
| **ReadBlock(byte[] buffer, int offset, int count)** | int |  |
| **ReadByte()** | int |  |
| **Seek(long offset, SeekOrigin origin)** | long |  |
| **SetLength(long value)** | void |  |
| **Write(byte[] buffer, int offset, int count)** | void |  |
# BufferedWrite Class

Namespace: Microsoft.SharePoint.Client.Mime


## Properties

| Name | Type | Summary |
|---|---|---|
| **Length** | int |  |
# Constants Class

Namespace: Microsoft.SharePoint.Client.Mime


## Fields

| Name | Type | Summary |
|---|---|---|
| **ContentTransferEncoding** | string |  |
| **ContentID** | string |  |
| **ContentType** | string |  |
| **ContentLength** | string |  |
| **MimeVersion** | string |  |
# ContentIDHeader Class

Namespace: Microsoft.SharePoint.Client.Mime

Base class: [MimeHeader](#mimeheader-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **Name** | string |  |
| **Value** | string |  |
## Constructors

| Name | Summary |
|---|---|
| **ContentIDHeader(string name, string value)** |  |
# ContentLengthHeader Class

Namespace: Microsoft.SharePoint.Client.Mime

Base class: [MimeHeader](#mimeheader-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **Length** | int |  |
| **Name** | string |  |
| **Value** | string |  |
## Constructors

| Name | Summary |
|---|---|
| **ContentLengthHeader(string name, string value)** |  |
# ContentTransferEncoding Enum

Namespace: Microsoft.SharePoint.Client.Mime


## Values

| Name | Summary |
|---|---|
| **SevenBit** |  |
| **EightBit** |  |
| **Binary** |  |
| **Other** |  |
| **Unspecified** |  |
# ContentTransferEncodingHeader Class

Namespace: Microsoft.SharePoint.Client.Mime

Base class: [MimeHeader](#mimeheader-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **ContentTransferEncoding** | [ContentTransferEncoding](#contenttransferencoding-enum) |  |
| **ContentTransferEncodingValue** | string |  |
| **Name** | string |  |
| **Value** | string |  |
## Constructors

| Name | Summary |
|---|---|
| **ContentTransferEncodingHeader(string value)** |  |
| **ContentTransferEncodingHeader(ContentTransferEncoding contentTransferEncoding, string value)** |  |
## Fields

| Name | Type | Summary |
|---|---|---|
| **Binary** | [ContentTransferEncodingHeader](#contenttransferencodingheader-class) |  |
| **EightBit** | [ContentTransferEncodingHeader](#contenttransferencodingheader-class) |  |
| **SevenBit** | [ContentTransferEncodingHeader](#contenttransferencodingheader-class) |  |
# ContentTypeHeader Class

Namespace: Microsoft.SharePoint.Client.Mime

Base class: [MimeHeader](#mimeheader-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **MediaType** | string |  |
| **MediaSubtype** | string |  |
| **Parameters** | Dictionary\<string, string\> |  |
| **Name** | string |  |
| **Value** | string |  |
## Constructors

| Name | Summary |
|---|---|
| **ContentTypeHeader(string value)** |  |
## Fields

| Name | Type | Summary |
|---|---|---|
| **Default** | [ContentTypeHeader](#contenttypeheader-class) |  |
# DelimittedReadStream Class

Namespace: Microsoft.SharePoint.Client.Mime

Base class: Stream


## Properties

| Name | Type | Summary |
|---|---|---|
| **CanRead** | bool |  |
| **CanSeek** | bool |  |
| **CanWrite** | bool |  |
| **Length** | long |  |
| **Position** | long |  |
| **CanTimeout** | bool |  |
| **ReadTimeout** | int |  |
| **WriteTimeout** | int |  |
## Constructors

| Name | Summary |
|---|---|
| **DelimittedReadStream(DelimittedStreamReader reader, int? contentLength)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **BeginWrite(byte[] buffer, int offset, int count, AsyncCallback callback, Object state)** | IAsyncResult |  |
| **Close()** | void |  |
| **EndWrite(IAsyncResult asyncResult)** | void |  |
| **Flush()** | void |  |
| **Read(byte[] buffer, int offset, int count)** | int |  |
| **Seek(long offset, SeekOrigin origin)** | long |  |
| **SetLength(long value)** | void |  |
| **Write(byte[] buffer, int offset, int count)** | void |  |
# DelimittedStreamReader Class

Namespace: Microsoft.SharePoint.Client.Mime


## Constructors

| Name | Summary |
|---|---|
| **DelimittedStreamReader(Stream stream)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Close()** | void |  |
| **GetNextStream(byte[] delimitterValue)** | Stream |  |
| **GetNextStream(byte[] delimitterValue, int? contentLength)** | Stream |  |
# DiagnosticUtility Class

Namespace: Microsoft.SharePoint.Client.Mime


# ExceptionUtility Class

Namespace: Microsoft.SharePoint.Client.Mime


## Methods

| Name | Returns | Summary |
|---|---|---|
| **ThrowHelperArgumentNull(string argumentName)** | Exception |  |
| **ThrowHelperError(Exception ex)** | Exception |  |
# MailBnfHelper Class

Namespace: Microsoft.SharePoint.Client.Mime


## Methods

| Name | Returns | Summary |
|---|---|---|
| **IsValidMimeBoundary(string data)** | bool |  |
| **ReadDigits(string data, ref int offset, StringBuilder builder)** | string |  |
| **ReadParameterAttribute(string data, ref int offset, StringBuilder builder)** | string |  |
| **ReadParameterValue(string data, ref int offset, StringBuilder builder)** | string |  |
| **ReadQuotedString(string data, ref int offset, StringBuilder builder)** | string |  |
| **ReadToken(string data, ref int offset, StringBuilder builder)** | string |  |
| **SkipCFWS(string data, ref int offset)** | bool |  |
# MatchState Enum

Namespace: Microsoft.SharePoint.Client.Mime


## Values

| Name | Summary |
|---|---|
| **True** |  |
| **False** |  |
| **InsufficientData** |  |
# MergedStream Class

Namespace: Microsoft.SharePoint.Client.Mime

Base class: Stream


## Properties

| Name | Type | Summary |
|---|---|---|
| **CanRead** | bool |  |
| **CanSeek** | bool |  |
| **CanWrite** | bool |  |
| **Length** | long |  |
| **Position** | long |  |
| **CanTimeout** | bool |  |
| **ReadTimeout** | int |  |
| **WriteTimeout** | int |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Flush()** | void |  |
| **Read(byte[] buffer, int offset, int count)** | int |  |
| **ReadByte()** | int |  |
| **Seek(long offset, SeekOrigin origin)** | long |  |
| **SetLength(long value)** | void |  |
| **Write(byte[] buffer, int offset, int count)** | void |  |
# MimeGlobals Class

Namespace: Microsoft.SharePoint.Client.Mime


# MimeHeader Class

Namespace: Microsoft.SharePoint.Client.Mime


## Properties

| Name | Type | Summary |
|---|---|---|
| **Name** | string |  |
| **Value** | string |  |
## Constructors

| Name | Summary |
|---|---|
| **MimeHeader(string name, string value)** |  |
# MimeHeaderReader Class

Namespace: Microsoft.SharePoint.Client.Mime


## Properties

| Name | Type | Summary |
|---|---|---|
| **Value** | string |  |
| **Name** | string |  |
## Constructors

| Name | Summary |
|---|---|
| **MimeHeaderReader(Stream stream)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Close()** | void |  |
| **Read(int maxBuffer, ref int remaining)** | bool |  |
| **Reset(Stream inputStream)** | void |  |
# MimeHeaders Class

Namespace: Microsoft.SharePoint.Client.Mime


## Properties

| Name | Type | Summary |
|---|---|---|
| **ContentType** | [ContentTypeHeader](#contenttypeheader-class) |  |
| **ContentLength** | [ContentLengthHeader](#contentlengthheader-class) |  |
| **ContentID** | [ContentIDHeader](#contentidheader-class) |  |
| **ContentTransferEncoding** | [ContentTransferEncodingHeader](#contenttransferencodingheader-class) |  |
| **MimeVersion** | [MimeVersionHeader](#mimeversionheader-class) |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Add(MimeHeader header)** | void |  |
| **Add(string name, string value, ref int remaining)** | void |  |
| **Release(ref int remaining)** | void |  |
# MimeMergedStream Class

Namespace: Microsoft.SharePoint.Client.Mime

Base class: [MergedStream](#mergedstream-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **CanRead** | bool |  |
| **CanSeek** | bool |  |
| **CanWrite** | bool |  |
| **Length** | long |  |
| **Position** | long |  |
| **CanTimeout** | bool |  |
| **ReadTimeout** | int |  |
| **WriteTimeout** | int |  |
## Constructors

| Name | Summary |
|---|---|
| **MimeMergedStream(string boundary, IEnumerable\<MimePart\> parts)** |  |
# MimeMessageReader Class

Namespace: Microsoft.SharePoint.Client.Mime


## Constructors

| Name | Summary |
|---|---|
| **MimeMessageReader(Stream stream)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetContentStream()** | Stream |  |
| **ReadHeaders(int maxBuffer, ref int remaining)** | [MimeHeaders](#mimeheaders-class) |  |
# MimePart Class

Namespace: Microsoft.SharePoint.Client.Mime


## Properties

| Name | Type | Summary |
|---|---|---|
| **ContentId** | string |  |
| **ContentType** | string |  |
| **ContentTransferEncoding** | [ContentTransferEncoding](#contenttransferencoding-enum) |  |
| **Stream** | Stream |  |
# MimeReader Class

Namespace: Microsoft.SharePoint.Client.Mime


## Properties

| Name | Type | Summary |
|---|---|---|
| **Preface** | string |  |
## Constructors

| Name | Summary |
|---|---|
| **MimeReader(Stream stream, string boundary)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Close()** | void |  |
| **GetContentStream()** | Stream |  |
| **GetContentStream(int? contentLength)** | Stream |  |
| **ReadHeaders(int maxBuffer, ref int remaining)** | [MimeHeaders](#mimeheaders-class) |  |
| **ReadNextPart()** | bool |  |
# MimeUtility Class

Namespace: Microsoft.SharePoint.Client.Mime


## Methods

| Name | Returns | Summary |
|---|---|---|
| **CreateBoundary()** | string |  |
| **GetBoundary(string contentType)** | string |  |
# MimeVersionHeader Class

Namespace: Microsoft.SharePoint.Client.Mime

Base class: [MimeHeader](#mimeheader-class)


## Properties

| Name | Type | Summary |
|---|---|---|
| **Version** | string |  |
| **Name** | string |  |
| **Value** | string |  |
## Constructors

| Name | Summary |
|---|---|
| **MimeVersionHeader(string value)** |  |
## Fields

| Name | Type | Summary |
|---|---|---|
| **Default** | [MimeVersionHeader](#mimeversionheader-class) |  |
# MimeWriter Class

Namespace: Microsoft.SharePoint.Client.Mime


# MimeWriterState Enum

Namespace: Microsoft.SharePoint.Client.Mime


## Values

| Name | Summary |
|---|---|
| **Start** |  |
| **StartPreface** |  |
| **StartPart** |  |
| **Header** |  |
| **Content** |  |
| **Closed** |  |
# MtomGlobals Class

Namespace: Microsoft.SharePoint.Client.Mime


# ReadState Enum

Namespace: Microsoft.SharePoint.Client.Mime


## Values

| Name | Summary |
|---|---|
| **ReadName** |  |
| **SkipWS** |  |
| **ReadValue** |  |
| **ReadLF** |  |
| **ReadWS** |  |
| **EOF** |  |
# SR Class

Namespace: Microsoft.SharePoint.Client.Mime


## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetString(string resourceId, Object[] args)** | string |  |
## Fields

| Name | Type | Summary |
|---|---|---|
| **MimeWriterInvalidStateForStartPart** | string |  |
| **MimeWriterInvalidStateForClose** | string |  |
| **MimeWriterInvalidStateForStartPreface** | string |  |
| **MimeWriterInvalidStateForHeader** | string |  |
| **MimeWriterInvalidStateForContent** | string |  |
| **MimeVersionHeaderInvalid** | string |  |
| **MimeContentLengthHeaderInvalid** | string |  |
| **MimeHeaderInvalidCharacter** | string |  |
| **MimeReaderMalformedHeader** | string |  |
| **MimeContentTypeHeaderInvalid** | string |  |
| **MimeReaderHeaderAlreadyExists** | string |  |
| **MimeMessageGetContentStreamCalledAlready** | string |  |
| **MimeReaderResetCalledBeforeEOF** | string |  |
| **WriteBufferOverflow** | string |  |
| **MimeReaderTruncated** | string |  |
| **MtomExceededMaxSizeInBytes** | string |  |
| **MtomBufferQuotaExceeded** | string |  |
