# Microsoft.SharePoint.Client.Runtime.dll v.16.1.0.0 API documentation

Created by 
[mddox](https://github.com/loxsmoke/mddox) on 07/04/2023

# All types

|   |   |   |
|---|---|---|
| [AttachmentStreamFromServer Class](#attachmentstreamfromserver-class) | [ExceptionHandlingExecutionScope Class](#exceptionhandlingexecutionscope-class) | [TextPeekReader Class](#textpeekreader-class) |
| [ChunkStreamBuilder Class](#chunkstreambuilder-class) | [ExceptionHandlingScope Class](#exceptionhandlingscope-class) | [Token Class](#token-class) |
| [ChunkStringBuilder Class](#chunkstringbuilder-class) | [ExecuteQueryMimeInfo Class](#executequerymimeinfo-class) | [UTF8ReadonlyStream Class](#utf8readonlystream-class) |
| [ChunkStringReader Class](#chunkstringreader-class) | [ExecutionScope Class](#executionscope-class) | [WebRequestEventArgs Class](#webrequesteventargs-class) |
| [ChunkStringWriter Class](#chunkstringwriter-class) | [ExecutionScopeDisposingCallback Class](#executionscopedisposingcallback-class) | [WebRequestExecutor Class](#webrequestexecutor-class) |
| [ClientAction Class](#clientaction-class) | [ExpressionEvaluator Class](#expressionevaluator-class) | [WebRequestExecutorFactory Class](#webrequestexecutorfactory-class) |
| [ClientActionExecutionScopeEnd Class](#clientactionexecutionscopeend-class) | [ExpressionUtility Class](#expressionutility-class) | [WriteValueHandler Class](#writevaluehandler-class) |
| [ClientActionExecutionScopeStart Class](#clientactionexecutionscopestart-class) | [ExpressionVisitor Class](#expressionvisitor-class) | [Authentication Class](#authentication-class) |
| [ClientActionInstantiateObjectPath Class](#clientactioninstantiateobjectpath-class) | [FormsAuthenticationLoginInfo Class](#formsauthenticationlogininfo-class) | [AuthenticationMode Enum](#authenticationmode-enum) |
| [ClientActionInstantiateObjectPathResult Class](#clientactioninstantiateobjectpathresult-class) | [IdcrlException Class](#idcrlexception-class) | [LoginCompletedEventArgs Class](#logincompletedeventargs-class) |
| [ClientActionInvokeMethod Class](#clientactioninvokemethod-class) | [IFromJson Class](#ifromjson-class) | [LoginCompletedEventHandler Class](#logincompletedeventhandler-class) |
| [ClientActionInvokeStaticMethod Class](#clientactioninvokestaticmethod-class) | [InvalidQueryExpressionException Class](#invalidqueryexpressionexception-class) | [LoginErrorCode Enum](#loginerrorcode-enum) |
| [ClientActionSetProperty Class](#clientactionsetproperty-class) | [IScriptTypeFactory Class](#iscripttypefactory-class) | [LoginResult Class](#loginresult-class) |
| [ClientActionSetStaticProperty Class](#clientactionsetstaticproperty-class) | [ISharePointOnlineAuthenticationProvider Class](#isharepointonlineauthenticationprovider-class) | [ModeCompletedEventArgs Class](#modecompletedeventargs-class) |
| [ClientArrayResult\<T\> Class](#clientarrayresultt-class) | [JsonReader Class](#jsonreader-class) | [ModeCompletedEventHandler Class](#modecompletedeventhandler-class) |
| [ClientAuthenticationMode Enum](#clientauthenticationmode-enum) | [JsonReaderOptions Enum](#jsonreaderoptions-enum) | [FederationProviderInfo Class](#federationproviderinfo-class) |
| [ClientConstants Class](#clientconstants-class) | [JsonTokenType Enum](#jsontokentype-enum) | [FederationProviderInfoCache Class](#federationproviderinfocache-class) |
| [ClientDictionaryResultHandler\<T\> Class](#clientdictionaryresulthandlert-class) | [Nominator Class](#nominator-class) | [FederationProviderInfoCacheEntry Class](#federationproviderinfocacheentry-class) |
| [ClientErrorCodes Class](#clienterrorcodes-class) | [NotSupportedExpressionChecker Class](#notsupportedexpressionchecker-class) | [IdcrlAuth Class](#idcrlauth-class) |
| [ClientListResultHandler\<T\> Class](#clientlistresulthandlert-class) | [ObjectIdentityQuery Class](#objectidentityquery-class) | [IdcrlConstants Class](#idcrlconstants-class) |
| [ClientObject Class](#clientobject-class) | [ObjectPath Class](#objectpath-class) | [IdcrlEnvironment Enum](#idcrlenvironment-enum) |
| [ClientObjectCollection Class](#clientobjectcollection-class) | [ObjectPathConstructor Class](#objectpathconstructor-class) | [IdcrlErrorCodes Class](#idcrlerrorcodes-class) |
| [ClientObjectCollection\<T\> Class](#clientobjectcollectiont-class) | [ObjectPathIdentity Class](#objectpathidentity-class) | [IdcrlHeader Class](#idcrlheader-class) |
| [ClientObjectCollectionPrototype\<ItemType\> Class](#clientobjectcollectionprototypeitemtype-class) | [ObjectPathMethod Class](#objectpathmethod-class) | [IdcrlMessageConstants Class](#idcrlmessageconstants-class) |
| [ClientObjectData Class](#clientobjectdata-class) | [ObjectPathProperty Class](#objectpathproperty-class) | [IdcrlUtility Class](#idcrlutility-class) |
| [ClientObjectList\<T\> Class](#clientobjectlistt-class) | [ObjectPathStaticMethod Class](#objectpathstaticmethod-class) | [SharePointOnlineAuthenticationProvider Class](#sharepointonlineauthenticationprovider-class) |
| [ClientObjectPrototype Class](#clientobjectprototype-class) | [ObjectPathStaticProperty Class](#objectpathstaticproperty-class) | [STSSoapFaultCodes Class](#stssoapfaultcodes-class) |
| [ClientObjectPrototype\<T\> Class](#clientobjectprototypet-class) | [OfficeVersion Class](#officeversion-class) | [UserRealmInfo Class](#userrealminfo-class) |
| [ClientObjectQueryableExtension Class](#clientobjectqueryableextension-class) | [PropertyOrFieldNotInitializedException Class](#propertyorfieldnotinitializedexception-class) | [BufferedReadStream Class](#bufferedreadstream-class) |
| [ClientQueryable\<T\> Class](#clientqueryablet-class) | [PseudoRemoteAttribute Class](#pseudoremoteattribute-class) | [BufferedWrite Class](#bufferedwrite-class) |
| [ClientQueryableResult\<T\> Class](#clientqueryableresultt-class) | [QueryMethodAggregator Class](#querymethodaggregator-class) | [Constants Class](#constants-class) |
| [ClientQueryInternal Class](#clientqueryinternal-class) | [QueryProcessInfo Class](#queryprocessinfo-class) | [ContentIDHeader Class](#contentidheader-class) |
| [ClientQueryProperty Class](#clientqueryproperty-class) | [ReadObjectHandler Class](#readobjecthandler-class) | [ContentLengthHeader Class](#contentlengthheader-class) |
| [ClientQueryProvider Class](#clientqueryprovider-class) | [ReadObjectHandlers Class](#readobjecthandlers-class) | [ContentTransferEncoding Enum](#contenttransferencoding-enum) |
| [ClientRequest Class](#clientrequest-class) | [ReadonlyChunkStream Class](#readonlychunkstream-class) | [ContentTransferEncodingHeader Class](#contenttransferencodingheader-class) |
| [ClientRequestException Class](#clientrequestexception-class) | [ReadonlyWrapStream Class](#readonlywrapstream-class) | [ContentTypeHeader Class](#contenttypeheader-class) |
| [ClientRequestStatus Enum](#clientrequeststatus-enum) | [RemoteAttribute Class](#remoteattribute-class) | [DelimittedReadStream Class](#delimittedreadstream-class) |
| [ClientResult\<T\> Class](#clientresultt-class) | [ReplaceQueryableCollectionWithEnumerableCollectionExpressionVisitor Class](#replacequeryablecollectionwithenumerablecollectionexpressionvisitor-class) | [DelimittedStreamReader Class](#delimittedstreamreader-class) |
| [ClientRuntimeConfigurationSection Class](#clientruntimeconfigurationsection-class) | [Resources Class](#resources-class) | [DiagnosticUtility Class](#diagnosticutility-class) |
| [ClientRuntimeContext Class](#clientruntimecontext-class) | [ResourceStrings Class](#resourcestrings-class) | [ExceptionUtility Class](#exceptionutility-class) |
| [ClientSchemaVersions Class](#clientschemaversions-class) | [Scope Class](#scope-class) | [MailBnfHelper Class](#mailbnfhelper-class) |
| [ClientTraceCategory Enum](#clienttracecategory-enum) | [ScopeType Enum](#scopetype-enum) | [MatchState Enum](#matchstate-enum) |
| [ClientTraceLevel Enum](#clienttracelevel-enum) | [ScriptTypeAttribute Class](#scripttypeattribute-class) | [MergedStream Class](#mergedstream-class) |
| [ClientTypeAssemblyAttribute Class](#clienttypeassemblyattribute-class) | [ScriptTypeInfo Class](#scripttypeinfo-class) | [MimeGlobals Class](#mimeglobals-class) |
| [ClientULS Class](#clientuls-class) | [ScriptTypeMap Class](#scripttypemap-class) | [MimeHeader Class](#mimeheader-class) |
| [ClientUtility Class](#clientutility-class) | [SerializationContext Class](#serializationcontext-class) | [MimeHeaderReader Class](#mimeheaderreader-class) |
| [ClientValueObject Class](#clientvalueobject-class) | [ServerException Class](#serverexception-class) | [MimeHeaders Class](#mimeheaders-class) |
| [ClientValueObjectCollection\<T\> Class](#clientvalueobjectcollectiont-class) | [ServerInfo Class](#serverinfo-class) | [MimeMergedStream Class](#mimemergedstream-class) |
| [CollectionNotInitializedException Class](#collectionnotinitializedexception-class) | [ServerObjectNullReferenceException Class](#serverobjectnullreferenceexception-class) | [MimeMessageReader Class](#mimemessagereader-class) |
| [ConditionalExecutionScope Class](#conditionalexecutionscope-class) | [ServerUnauthorizedAccessException Class](#serverunauthorizedaccessexception-class) | [MimePart Class](#mimepart-class) |
| [ConditionalExpressionToXmlConverter Class](#conditionalexpressiontoxmlconverter-class) | [SharePointOnlineAuthenticationModule Class](#sharepointonlineauthenticationmodule-class) | [MimeReader Class](#mimereader-class) |
| [ConditionalScope Class](#conditionalscope-class) | [SharePointOnlineAuthenticationProviderHelper Class](#sharepointonlineauthenticationproviderhelper-class) | [MimeUtility Class](#mimeutility-class) |
| [ConditionalScopeBase Class](#conditionalscopebase-class) | [SharePointOnlineCredentials Class](#sharepointonlinecredentials-class) | [MimeVersionHeader Class](#mimeversionheader-class) |
| [CookieCacheEntry Class](#cookiecacheentry-class) | [SharePointOnlineCredentialsWebRequestEventArgs Class](#sharepointonlinecredentialswebrequesteventargs-class) | [MimeWriter Class](#mimewriter-class) |
| [CookieInfo Class](#cookieinfo-class) | [SimpleDataTable Class](#simpledatatable-class) | [MimeWriterState Enum](#mimewriterstate-enum) |
| [DataConvert Class](#dataconvert-class) | [SPResourceManager Class](#spresourcemanager-class) | [MtomGlobals Class](#mtomglobals-class) |
| [DataRetrieval Class](#dataretrieval-class) | [SPWebRequestExecutor Class](#spwebrequestexecutor-class) | [ReadState Enum](#readstate-enum) |
| [DefaultWebRequestExecutorFactory Class](#defaultwebrequestexecutorfactory-class) | [StreamInfo Class](#streaminfo-class) | [SR Class](#sr-class) |
| [EnumerableClientObjectCollection\<T\> Class](#enumerableclientobjectcollectiont-class) | [SubtreeEvaluator Class](#subtreeevaluator-class) |   |
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
# ClientAuthenticationMode Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Default** |  |
| **FormsAuthentication** |  |
| **Anonymous** |  |
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
| **Message** | string |  |
| **Data** | IDictionary |  |
| **InnerException** | Exception |  |
| **TargetSite** | MethodBase |  |
| **StackTrace** | string |  |
| **HelpLink** | string |  |
| **Source** | string |  |
| **IPForWatsonBuckets** | UIntPtr |  |
| **WatsonBuckets** | Object |  |
| **RemoteStackTrace** | string |  |
| **HResult** | int |  |
| **IsTransient** | bool |  |
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
# ClientResult\<T\> Class

Namespace: Microsoft.SharePoint.Client


## Properties

| Name | Type | Summary |
|---|---|---|
| **Value** | T |  |
# ClientRuntimeConfigurationSection Class

Namespace: Microsoft.SharePoint.Client

Base class: ConfigurationSection


## Properties

| Name | Type | Summary |
|---|---|---|
| **TypeAssemblies** | AssemblyCollection |  |
| **SectionInformation** | SectionInformation |  |
| **DataToWriteInternal** | bool |  |
| **ElementPresent** | bool |  |
| **ElementTagName** | string |  |
| **LockedAttributesList** | ConfigurationLockCollection |  |
| **LockedAllExceptAttributesList** | ConfigurationLockCollection |  |
| **ItemLocked** | ConfigurationValueFlags |  |
| **LockAttributes** | ConfigurationLockCollection |  |
| **LockAllAttributesExcept** | ConfigurationLockCollection |  |
| **LockElements** | ConfigurationLockCollection |  |
| **LockAllElementsExcept** | ConfigurationLockCollection |  |
| **LockItem** | bool |  |
| **Item** | Object |  |
| **Item** | Object |  |
| **Properties** | ConfigurationPropertyCollection |  |
| **Values** | ConfigurationValues |  |
| **ElementInformation** | ElementInformation |  |
| **EvaluationContext** | ContextInformation |  |
| **ElementProperty** | ConfigurationElementProperty |  |
| **HasContext** | bool |  |
| **CurrentConfiguration** | Configuration |  |
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
| **AuthenticationMode** | [ClientAuthenticationMode](#clientauthenticationmode-enum) |  |
| **FormsAuthenticationLoginInfo** | [FormsAuthenticationLoginInfo](#formsauthenticationlogininfo-class) |  |
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
| **SetupRequestCredential(ClientRuntimeContext context, HttpWebRequest request)** | void |  |
# ClientSchemaVersions Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Version14** | Version |  |
| **Version15** | Version |  |
| **CurrentVersion** | Version |  |
# ClientTraceCategory Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **General** |  |
| **Request** |  |
| **Authentication** |  |
# ClientTraceLevel Enum

Namespace: Microsoft.SharePoint.Client


## Values

| Name | Summary |
|---|---|
| **Verbose** |  |
| **Medium** |  |
| **High** |  |
# ClientTypeAssemblyAttribute Class

Namespace: Microsoft.SharePoint.Client

Base class: Attribute


## Properties

| Name | Type | Summary |
|---|---|---|
| **ScriptTypeFactory** | Type |  |
| **TypeId** | Object |  |
# ClientULS Class

Namespace: Microsoft.SharePoint.Client


## Properties

| Name | Type | Summary |
|---|---|---|
| **AuthTraceSource** | TraceSource |  |
| **RequestTraceSource** | TraceSource |  |
| **GeneralTraceSource** | TraceSource |  |
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
| **Message** | string |  |
| **Data** | IDictionary |  |
| **InnerException** | Exception |  |
| **TargetSite** | MethodBase |  |
| **StackTrace** | string |  |
| **HelpLink** | string |  |
| **Source** | string |  |
| **IPForWatsonBuckets** | UIntPtr |  |
| **WatsonBuckets** | Object |  |
| **RemoteStackTrace** | string |  |
| **HResult** | int |  |
| **IsTransient** | bool |  |
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
# CookieCacheEntry Class

Namespace: Microsoft.SharePoint.Client


## Properties

| Name | Type | Summary |
|---|---|---|
| **IsValid** | bool |  |
## Fields

| Name | Type | Summary |
|---|---|---|
| **Cookie** | string |  |
| **Expires** | DateTime |  |
# CookieInfo Class

Namespace: Microsoft.SharePoint.Client


## Fields

| Name | Type | Summary |
|---|---|---|
| **Cookies** | CookieCollection |  |
| **Expires** | DateTime |  |
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
| **Method** | MethodInfo |  |
| **Target** | Object |  |
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
# FormsAuthenticationLoginInfo Class

Namespace: Microsoft.SharePoint.Client


## Properties

| Name | Type | Summary |
|---|---|---|
| **LoginName** | string |  |
| **Password** | string |  |
| **CookieContainer** | CookieContainer |  |
| **AuthenticationServiceUrl** | Uri |  |
## Constructors

| Name | Summary |
|---|---|
| **FormsAuthenticationLoginInfo(string loginName, string password)** |  |
# IdcrlException Class

Namespace: Microsoft.SharePoint.Client

Base class: Exception


## Properties

| Name | Type | Summary |
|---|---|---|
| **ErrorCode** | int |  |
| **Message** | string |  |
| **Data** | IDictionary |  |
| **InnerException** | Exception |  |
| **TargetSite** | MethodBase |  |
| **StackTrace** | string |  |
| **HelpLink** | string |  |
| **Source** | string |  |
| **IPForWatsonBuckets** | UIntPtr |  |
| **WatsonBuckets** | Object |  |
| **RemoteStackTrace** | string |  |
| **HResult** | int |  |
| **IsTransient** | bool |  |
## Constructors

| Name | Summary |
|---|---|
| **IdcrlException(string message)** |  |
| **IdcrlException(string message, Exception innerException)** |  |
| **IdcrlException(string message, int errorcode)** |  |
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
| **Message** | string |  |
| **Data** | IDictionary |  |
| **InnerException** | Exception |  |
| **TargetSite** | MethodBase |  |
| **StackTrace** | string |  |
| **HelpLink** | string |  |
| **Source** | string |  |
| **IPForWatsonBuckets** | UIntPtr |  |
| **WatsonBuckets** | Object |  |
| **RemoteStackTrace** | string |  |
| **HResult** | int |  |
| **IsTransient** | bool |  |
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
# ISharePointOnlineAuthenticationProvider Class

Namespace: Microsoft.SharePoint.Client


## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetAuthenticationCookie(Uri url, string userName, SecureString password, bool alwaysThrowOnFailure, EventHandler\<SharePointOnlineCredentialsWebRequestEventArgs\> executingWebRequest)** | string |  |
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
| **Message** | string |  |
| **Data** | IDictionary |  |
| **InnerException** | Exception |  |
| **TargetSite** | MethodBase |  |
| **StackTrace** | string |  |
| **HelpLink** | string |  |
| **Source** | string |  |
| **IPForWatsonBuckets** | UIntPtr |  |
| **WatsonBuckets** | Object |  |
| **RemoteStackTrace** | string |  |
| **HResult** | int |  |
| **IsTransient** | bool |  |
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
| **Method** | MethodInfo |  |
| **Target** | Object |  |
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
| **CannotFindPlatformLibrary** | string |  |
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
| **Message** | string |  |
| **Data** | IDictionary |  |
| **InnerException** | Exception |  |
| **TargetSite** | MethodBase |  |
| **StackTrace** | string |  |
| **HelpLink** | string |  |
| **Source** | string |  |
| **IPForWatsonBuckets** | UIntPtr |  |
| **WatsonBuckets** | Object |  |
| **RemoteStackTrace** | string |  |
| **HResult** | int |  |
| **IsTransient** | bool |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **ToString()** | string |  |
# ServerInfo Class

Namespace: Microsoft.SharePoint.Client


## Properties

| Name | Type | Summary |
|---|---|---|
| **AuthenticationMode** | AuthenticationMode |  |
## Constructors

| Name | Summary |
|---|---|
| **ServerInfo(Uri url)** |  |
# ServerObjectNullReferenceException Class

Namespace: Microsoft.SharePoint.Client

Base class: InvalidOperationException


## Properties

| Name | Type | Summary |
|---|---|---|
| **Message** | string |  |
| **Data** | IDictionary |  |
| **InnerException** | Exception |  |
| **TargetSite** | MethodBase |  |
| **StackTrace** | string |  |
| **HelpLink** | string |  |
| **Source** | string |  |
| **IPForWatsonBuckets** | UIntPtr |  |
| **WatsonBuckets** | Object |  |
| **RemoteStackTrace** | string |  |
| **HResult** | int |  |
| **IsTransient** | bool |  |
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
| **Message** | string |  |
| **Data** | IDictionary |  |
| **InnerException** | Exception |  |
| **TargetSite** | MethodBase |  |
| **StackTrace** | string |  |
| **HelpLink** | string |  |
| **Source** | string |  |
| **IPForWatsonBuckets** | UIntPtr |  |
| **WatsonBuckets** | Object |  |
| **RemoteStackTrace** | string |  |
| **HResult** | int |  |
| **IsTransient** | bool |  |
# SharePointOnlineAuthenticationModule Class

Namespace: Microsoft.SharePoint.Client


## Properties

| Name | Type | Summary |
|---|---|---|
| **AuthenticationType** | string |  |
| **CanPreAuthenticate** | bool |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **Authenticate(string challenge, WebRequest request, ICredentials credentials)** | Authorization |  |
| **PreAuthenticate(WebRequest request, ICredentials credentials)** | Authorization |  |
# SharePointOnlineAuthenticationProviderHelper Class

Namespace: Microsoft.SharePoint.Client


# SharePointOnlineCredentials Class

Namespace: Microsoft.SharePoint.Client


## Properties

| Name | Type | Summary |
|---|---|---|
| **UserName** | string |  |
| **Password** | SecureString |  |
## Constructors

| Name | Summary |
|---|---|
| **SharePointOnlineCredentials(string username, SecureString password)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetAuthenticationCookie(Uri url)** | string |  |
| **GetAuthenticationCookie(Uri url, bool alwaysThrowOnFailure)** | string |  |
| **GetCredential(Uri uri, string authType)** | NetworkCredential |  |
# SharePointOnlineCredentialsWebRequestEventArgs Class

Namespace: Microsoft.SharePoint.Client

Base class: EventArgs


## Properties

| Name | Type | Summary |
|---|---|---|
| **WebRequest** | HttpWebRequest |  |
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
| **Method** | MethodInfo |  |
| **Target** | Object |  |
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
# Authentication Class

Namespace: Microsoft.SharePoint.Client.Application

Base class: SoapHttpClientProtocol


## Properties

| Name | Type | Summary |
|---|---|---|
| **SoapVersion** | SoapProtocolVersion |  |
| **AllowAutoRedirect** | bool |  |
| **CookieContainer** | CookieContainer |  |
| **ClientCertificates** | X509CertificateCollection |  |
| **EnableDecompression** | bool |  |
| **UserAgent** | string |  |
| **Proxy** | IWebProxy |  |
| **UnsafeAuthenticatedConnectionSharing** | bool |  |
| **Credentials** | ICredentials |  |
| **UseDefaultCredentials** | bool |  |
| **ConnectionGroupName** | string |  |
| **PendingSyncRequest** | WebRequest |  |
| **PreAuthenticate** | bool |  |
| **Url** | string |  |
| **AsyncInvokes** | Hashtable |  |
| **NullToken** | Object |  |
| **Uri** | Uri |  |
| **RequestEncoding** | Encoding |  |
| **Timeout** | int |  |
| **CanRaiseEvents** | bool |  |
| **CanRaiseEventsInternal** | bool |  |
| **Events** | EventHandlerList |  |
| **Site** | ISite |  |
| **Container** | IContainer |  |
| **DesignMode** | bool |  |
## Constructors

| Name | Summary |
|---|---|
| **Authentication(Uri uri)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **BeginLogin(string username, string password, AsyncCallback callback, Object asyncState)** | IAsyncResult |  |
| **BeginMode(AsyncCallback callback, Object asyncState)** | IAsyncResult |  |
| **CancelAsync(Object userState)** | void |  |
| **EndLogin(IAsyncResult asyncResult)** | [LoginResult](#loginresult-class) |  |
| **EndMode(IAsyncResult asyncResult)** | [AuthenticationMode](#authenticationmode-enum) |  |
| **Login(string username, string password)** | [LoginResult](#loginresult-class) |  |
| **LoginAsync(string username, string password)** | void |  |
| **LoginAsync(string username, string password, Object userState)** | void |  |
| **Mode()** | [AuthenticationMode](#authenticationmode-enum) |  |
| **ModeAsync()** | void |  |
| **ModeAsync(Object userState)** | void |  |
# AuthenticationMode Enum

Namespace: Microsoft.SharePoint.Client.Application


## Values

| Name | Summary |
|---|---|
| **None** |  |
| **Windows** |  |
| **Passport** |  |
| **Forms** |  |
# LoginCompletedEventArgs Class

Namespace: Microsoft.SharePoint.Client.Application

Base class: AsyncCompletedEventArgs


## Properties

| Name | Type | Summary |
|---|---|---|
| **Result** | [LoginResult](#loginresult-class) |  |
| **Cancelled** | bool |  |
| **Error** | Exception |  |
| **UserState** | Object |  |
# LoginCompletedEventHandler Class

Namespace: Microsoft.SharePoint.Client.Application

Base class: MulticastDelegate


## Properties

| Name | Type | Summary |
|---|---|---|
| **Method** | MethodInfo |  |
| **Target** | Object |  |
## Constructors

| Name | Summary |
|---|---|
| **LoginCompletedEventHandler(Object object, IntPtr method)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **BeginInvoke(Object sender, LoginCompletedEventArgs e, AsyncCallback callback, Object object)** | IAsyncResult |  |
| **EndInvoke(IAsyncResult result)** | void |  |
| **Invoke(Object sender, LoginCompletedEventArgs e)** | void |  |
# LoginErrorCode Enum

Namespace: Microsoft.SharePoint.Client.Application


## Values

| Name | Summary |
|---|---|
| **NoError** |  |
| **NotInFormsAuthenticationMode** |  |
| **PasswordNotMatch** |  |
# LoginResult Class

Namespace: Microsoft.SharePoint.Client.Application


## Properties

| Name | Type | Summary |
|---|---|---|
| **CookieName** | string |  |
| **ErrorCode** | [LoginErrorCode](#loginerrorcode-enum) |  |
| **TimeoutSeconds** | int |  |
# ModeCompletedEventArgs Class

Namespace: Microsoft.SharePoint.Client.Application

Base class: AsyncCompletedEventArgs


## Properties

| Name | Type | Summary |
|---|---|---|
| **Result** | [AuthenticationMode](#authenticationmode-enum) |  |
| **Cancelled** | bool |  |
| **Error** | Exception |  |
| **UserState** | Object |  |
# ModeCompletedEventHandler Class

Namespace: Microsoft.SharePoint.Client.Application

Base class: MulticastDelegate


## Properties

| Name | Type | Summary |
|---|---|---|
| **Method** | MethodInfo |  |
| **Target** | Object |  |
## Constructors

| Name | Summary |
|---|---|
| **ModeCompletedEventHandler(Object object, IntPtr method)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **BeginInvoke(Object sender, ModeCompletedEventArgs e, AsyncCallback callback, Object object)** | IAsyncResult |  |
| **EndInvoke(IAsyncResult result)** | void |  |
| **Invoke(Object sender, ModeCompletedEventArgs e)** | void |  |
# FederationProviderInfo Class

Namespace: Microsoft.SharePoint.Client.Idcrl


## Properties

| Name | Type | Summary |
|---|---|---|
| **UserRealmServiceUrl** | string |  |
| **SecurityTokenServiceUrl** | string |  |
| **FederationTokenIssuer** | string |  |
# FederationProviderInfoCache Class

Namespace: Microsoft.SharePoint.Client.Idcrl


## Methods

| Name | Returns | Summary |
|---|---|---|
| **Put(string domainname, FederationProviderInfo value)** | void |  |
| **TryGetValue(string domainname, out FederationProviderInfo value)** | bool |  |
# FederationProviderInfoCacheEntry Class

Namespace: Microsoft.SharePoint.Client.Idcrl


## Fields

| Name | Type | Summary |
|---|---|---|
| **Value** | [FederationProviderInfo](#federationproviderinfo-class) |  |
| **Expires** | DateTime |  |
# IdcrlAuth Class

Namespace: Microsoft.SharePoint.Client.Idcrl


## Properties

| Name | Type | Summary |
|---|---|---|
| **UserRealmServiceUrl** | string |  |
| **ServiceTokenUrl** | string |  |
| **FederationTokenIssuer** | string |  |
## Constructors

| Name | Summary |
|---|---|
| **IdcrlAuth(IdcrlEnvironment env, EventHandler\<SharePointOnlineCredentialsWebRequestEventArgs\> executingWebRequest)** |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetServiceToken(string username, string password, string serviceTarget, string servicePolicy)** | string |  |
# IdcrlConstants Class

Namespace: Microsoft.SharePoint.Client.Idcrl


## Fields

| Name | Type | Summary |
|---|---|---|
| **HEADER_IDCRL_AUTH_ACCEPTED** | string |  |
| **HEADER_FORMS_BASED_AUTH_ACCEPTED** | string |  |
| **HEADER_IDCRL_AUTH_PARAMS_V1** | string |  |
| **True** | string |  |
| **False** | string |  |
| **REGKEY_MSOIdentityCRL** | string |  |
| **REGVAL_ServiceEnvironment** | string |  |
| **ENV_INT_MSO** | string |  |
| **ENV_PPE_MSO** | string |  |
| **ENV_PRODUCTION** | string |  |
| **BPOSIDCRL_AUTHORIZATION_HEADER_PREFIX** | string |  |
| **IDCRLTYPE_BPOSIDRL** | string |  |
| **IDCRL_PARAM_IDCRL_TYPE** | string |  |
| **IDCRL_PARAM_ENDPOINT** | string |  |
| **IDCRL_PARAM_ROOTDOMAIN** | string |  |
| **IDCRL_PARAM_POLICY** | string |  |
# IdcrlEnvironment Enum

Namespace: Microsoft.SharePoint.Client.Idcrl


## Values

| Name | Summary |
|---|---|
| **Production** |  |
| **Int** |  |
| **Ppe** |  |
# IdcrlErrorCodes Class

Namespace: Microsoft.SharePoint.Client.Idcrl


## Fields

| Name | Type | Summary |
|---|---|---|
| **PPCRL_AUTHSTATE_S_AUTHENTICATED_OFFLINE** | int |  |
| **PPCRL_AUTHSTATE_S_AUTHENTICATED_PASSWORD** | int |  |
| **PPCRL_AUTHSTATE_S_AUTHENTICATED_PARTNER** | int |  |
| **PPCRL_REQUEST_S_IO_PENDING** | int |  |
| **PPCRL_S_NO_MORE_IDENTITIES** | int |  |
| **PPCRL_S_TOKEN_TYPE_DOES_NOT_SUPPORT_SESSION_KEY** | int |  |
| **PPCRL_S_NO_SUCH_CREDENTIAL** | int |  |
| **PPCRL_S_NO_AUTHENTICATION_REQUIRED** | int |  |
| **PPCRL_S_OK_CLIENTTIME** | int |  |
| **PPCRL_REQUEST_S_OK_NO_SLC** | int |  |
| **PPCRL_REQUEST_S_IO_PENDING_NO_SLC** | int |  |
| **PPCRL_AUTHSTATE_E_UNAUTHENTICATED** | int |  |
| **PPCRL_AUTHSTATE_E_EXPIRED** | int |  |
| **PPCRL_AUTHREQUIRED_E_PASSWORD** | int |  |
| **PPCRL_AUTHREQUIRED_E_UNKNOWN** | int |  |
| **PPCRL_REQUEST_E_AUTH_SERVER_ERROR** | int |  |
| **PPCRL_REQUEST_E_BAD_MEMBER_NAME_OR_PASSWORD** | int |  |
| **PPCRL_REQUEST_E_PASSWORD_LOCKED_OUT** | int |  |
| **PPCRL_REQUEST_E_PASSWORD_LOCKED_OUT_BAD_PASSWORD_OR_HIP** | int |  |
| **PPCRL_REQUEST_E_FORCE_RENAME_REQUIRED** | int |  |
| **PPCRL_REQUEST_E_FORCE_CHANGE_PASSWORD_REQUIRED** | int |  |
| **PPCRL_REQUEST_E_STRONG_PASSWORD_REQUIRED** | int |  |
| **PPCRL_REQUEST_E_PARTNER_NOT_FOUND** | int |  |
| **PPCRL_REQUEST_E_PARTNER_HAS_NO_ASYMMETRIC_KEY** | int |  |
| **PPCRL_REQUEST_E_INVALID_POLICY** | int |  |
| **PPCRL_REQUEST_E_INVALID_MEMBER_NAME** | int |  |
| **PPCRL_REQUEST_E_MISSING_PRIMARY_CREDENTIAL** | int |  |
| **PPCRL_REQUEST_E_PENDING_NETWORK_REQUEST** | int |  |
| **PPCRL_REQUEST_E_FORCE_CHANGE_SQSA** | int |  |
| **PPCRL_REQUEST_E_PASSWORD_EXPIRED** | int |  |
| **PPCRL_REQUEST_E_PROFILE_ACCRUE_REQUIRED** | int |  |
| **PPCRL_REQUEST_E_EMAIL_VALIDATION_REQUIRED** | int |  |
| **PPCRL_REQUEST_E_PARTNER_NEED_STRONGPW** | int |  |
| **PPCRL_REQUEST_E_PARTNER_NEED_STRONGPW_EXPIRY** | int |  |
| **PPCRL_REQUEST_E_AUTH_EXPIRED** | int |  |
| **PPCRL_REQUEST_E_USER_FORGOT_PASSWORD** | int |  |
| **PPCRL_REQUEST_E_USER_CANCELED** | int |  |
| **PPCRL_REQUEST_E_NO_NETWORK** | int |  |
| **PPCRL_REQUEST_E_UNKNOWN** | int |  |
| **PPCRL_REQUEST_E_KID_HAS_NO_CONSENT** | int |  |
| **PPCRL_REQUEST_E_RSTR_FAULT** | int |  |
| **PPCRL_REQUEST_E_RSTR_MISSING_BASE64CERT** | int |  |
| **PPCRL_REQUEST_E_RSTR_MISSING_TOKENTYPE** | int |  |
| **PPCRL_REQUEST_E_RSTR_MISSING_PRIVATE_KEY** | int |  |
| **PPCRL_REQUEST_E_INVALID_SERVICE_TIMESTAMP** | int |  |
| **PPCRL_REQUEST_E_INVALID_PKCS10_TIMESTAMP** | int |  |
| **PPCRL_REQUEST_E_INVALID_PKCS10** | int |  |
| **PPCRL_E_IDENTITY_NOT_AUTHENTICATED** | int |  |
| **PPCRL_E_UNABLE_TO_RETRIEVE_SERVICE_TOKEN** | int |  |
| **PPCRL_E_AUTH_SERVICE_UNAVAILABLE** | int |  |
| **PPCRL_E_INVALID_AUTH_SERVICE_RESPONSE** | int |  |
| **PPCRL_E_UNABLE_TO_INITIALIZE_CRYPTO_PROVIDER** | int |  |
| **PPCRL_E_NO_MEMBER_NAME_SET** | int |  |
| **PPCRL_E_CALLBACK_REQUIRED** | int |  |
| **PPCRL_E_INVALIDFLAGS** | int |  |
| **PPCRL_E_UNABLE_TO_RETRIEVE_CERT** | int |  |
| **PPCRL_E_INVALID_RSTPARAMS** | int |  |
| **PPCRL_E_MISSING_FILE** | int |  |
| **PPCRL_E_ILLEGAL_LOGONIDENTITY_FLAG** | int |  |
| **PPCRL_E_CERT_NOT_VALID_FOR_MINTTL** | int |  |
| **PPCRL_E_CERT_INVALID_ISSUER** | int |  |
| **PPCRL_E_NO_CERTSTORE_FOR_ISSUERS** | int |  |
| **PPCRL_E_OFFLINE_AUTH** | int |  |
| **PPCRL_E_SIGN_POP_FAILED** | int |  |
| **PPCRL_E_CERT_INVALID_POP** | int |  |
| **PPCRL_E_CALLER_NOT_SIGNED** | int |  |
| **PPCRL_E_BUSY** | int |  |
| **PPCRL_E_DOWNLOAD_FILE_FAILED** | int |  |
| **PPCRL_E_BUILD_CERT_REQUEST_FAILED** | int |  |
| **PPCRL_E_CERTIFICATE_NOT_FOUND** | int |  |
| **PPCRL_E_AUTHBLOB_TOO_LARGE** | int |  |
| **PPCRL_E_AUTHBLOB_NOT_FOUND** | int |  |
| **PPCRL_E_AUTHBLOB_INVALID** | int |  |
| **PPCRL_E_EXTPROP_NOTFOUND** | int |  |
| **PPCRL_E_RESPONSE_TOO_LARGE** | int |  |
| **PPCRL_E_USER_NOTFOUND** | int |  |
| **PPCRL_E_SIGCHECK_FAILED** | int |  |
| **PPCRL_E_CREDTARGETNAME_INVALID** | int |  |
| **PPCRL_E_CREDINFO_CORRUPTED** | int |  |
| **PPCRL_E_CREDPROP_NOTFOUND** | int |  |
| **PPCRL_E_NO_LINKEDACCOUNTS** | int |  |
| **PPCRL_E_NO_LINKEDHANDLE** | int |  |
| **PPCRL_E_CERT_CA_ROLLOVER** | int |  |
| **PPCRL_E_REALM_LOOKUP** | int |  |
| **PPCRL_E_FORBIDDEN_NAMESPACE** | int |  |
| **PPCRL_E_IDENTITY_NOCID** | int |  |
| **PPCRL_E_IE_MISCONFIGURED** | int |  |
| **PPCRL_E_NO_UI** | int |  |
| **PPCRL_E_INVALID_RPS_TOKEN** | int |  |
| **PPCRL_E_NOT_UI_ERROR** | int |  |
| **PPCRL_E_INVALID_URL** | int |  |
| **PPCRL_REQUEST_E_PARTNER_INVALID_REQUEST** | int |  |
| **PPCRL_REQUEST_E_PARTNER_REQUEST_FAILED** | int |  |
| **PPCRL_REQUEST_E_PARTNER_INVALID_SECURITY_TOKEN** | int |  |
| **PPCRL_REQUEST_E_PARTNER_AUTHENTICATION_BAD_ELEMENTS** | int |  |
| **PPCRL_REQUEST_E_PARTNER_BAD_REQUEST** | int |  |
| **PPCRL_REQUEST_E_PARTNER_EXPIRED_DATA** | int |  |
| **PPCRL_REQUEST_E_PARTNER_INVALID_TIME_RANGE** | int |  |
| **PPCRL_REQUEST_E_PARTNER_INVALID_SCOPE** | int |  |
| **PPCRL_REQUEST_E_PARTNER_RENEW_NEEDED** | int |  |
| **PPCRL_REQUEST_E_PARTNER_UNABLE_TO_RENEW** | int |  |
| **PPCRL_REQUEST_E_MISSING_HASHED_PASSWORD** | int |  |
| **PPCRL_REQUEST_E_CLIENT_DEPRECATED** | int |  |
| **PPCRL_REQUEST_E_CANCELLED** | int |  |
| **PPCRL_REQUEST_E_INVALID_PKCS10_KEYLEN** | int |  |
| **PPCRL_REQUEST_E_DUPLICATE_SERVICETARGET** | int |  |
| **PPCRL_REQUEST_E_FORCE_SIGNIN** | int |  |
| **PPCRL_REQUEST_E_PARTNER_NEED_CERTIFICATE** | int |  |
| **PPCRL_REQUEST_E_PARTNER_NEED_PIN** | int |  |
| **PPCRL_REQUEST_E_PARTNER_NEED_PASSWORD** | int |  |
| **PPCRL_REQUEST_E_SCHANNEL_ERROR** | int |  |
| **PPCRL_REQUEST_E_CERT_PARSE_ERROR** | int |  |
| **PPCRL_REQUEST_E_PARTNER_SERVER_ERROR** | int |  |
| **PPCRL_REQUEST_E_PARTNER_LOGIN** | int |  |
| **PPCRL_REQUEST_E_FLOWDISABLED** | int |  |
| **PPCRL_REQUEST_E_USER_NOT_LINKED** | int |  |
| **PPCRL_REQUEST_E_ACCOUNT_CONVERSION_NEEDED** | int |  |
| **PPCRL_REQUEST_E_PARTNER_BAD_MEMBER_NAME_OR_PASSWORD** | int |  |
| **PPCRL_REQUEST_E_BAD_MEMBER_NAME_OR_PASSWORD_FED** | int |  |
| **PPCRL_REQUEST_E_HIP_ON_FIRST_LOGIN** | int |  |
| **PPCRL_REQUEST_E_INVALID_CARDSPACE_TOKEN** | int |  |
# IdcrlHeader Class

Namespace: Microsoft.SharePoint.Client.Idcrl


## Fields

| Name | Type | Summary |
|---|---|---|
| **IdcrlType** | string |  |
| **ServiceTarget** | string |  |
| **ServicePolicy** | string |  |
| **Endpoint** | string |  |
# IdcrlMessageConstants Class

Namespace: Microsoft.SharePoint.Client.Idcrl


## Fields

| Name | Type | Summary |
|---|---|---|
| **FPUrlFullUrlFormat** | string |  |
| **FPListFullUrlFormat** | string |  |
| **UserRealmServiceUrl_Prod** | string |  |
| **UserRealmServiceUrl_Int** | string |  |
| **UserRealmServiceUrl_Ppe** | string |  |
| **SecurityTokenServiceUrl_Prod** | string |  |
| **SecurityTokenServiceUrl_Int** | string |  |
| **SecurityTokenServiceUrl_Ppe** | string |  |
| **FederationTokenIssuer_Prod** | string |  |
| **FederationTokenIssuer_Int** | string |  |
| **FederationTokenIssuer_Ppe** | string |  |
| **FederationProvider** | string |  |
| **FPDOMAINNAME** | string |  |
| **FPList** | string |  |
| **FP** | string |  |
| **DomainName** | string |  |
| **URL** | string |  |
| **GETUSERREALM** | string |  |
| **RST2** | string |  |
| **ENTITYID** | string |  |
| **AuthURL** | string |  |
| **NameSpaceType** | string |  |
| **Federated** | string |  |
| **Managed** | string |  |
| **Success** | string |  |
| **STSAuthURL** | string |  |
| **GetUserRealmMessage** | string |  |
| **GetUserRealmContentType** | string |  |
| **SoapContentType** | string |  |
| **SoapNamespace** | string |  |
| **EnvelopeElementFullName** | string |  |
| **BodyElementFullName** | string |  |
| **TrustNamespace** | string |  |
| **RequestSecurityTokenResponseFullName** | string |  |
| **RequestedSecurityTokenFullName** | string |  |
| **SamlNamespace** | string |  |
| **AssertionFullName** | string |  |
| **WsSecurityNamespace** | string |  |
| **BinarySecurityTokenFullName** | string |  |
| **FaultFullName** | string |  |
| **DetailFullName** | string |  |
| **CodeFullName** | string |  |
| **ValueFullName** | string |  |
| **SubcodeFullName** | string |  |
| **ReasonFullName** | string |  |
| **TextFullName** | string |  |
| **PassportNamespace** | string |  |
| **PassportErrorFullName** | string |  |
| **PassportValueFullName** | string |  |
| **PassportInternalErrorFullName** | string |  |
| **PassportCodeFullName** | string |  |
| **PassportTextFullName** | string |  |
| **AdfsAuthMessage** | string |  |
| **PolicyReferenceFragment** | string |  |
| **AuthMessage** | string |  |
| **UsernameTokenSecurityFragment** | string |  |
# IdcrlUtility Class

Namespace: Microsoft.SharePoint.Client.Idcrl


## Methods

| Name | Returns | Summary |
|---|---|---|
| **XmlValueEncode(string value)** | string |  |
# SharePointOnlineAuthenticationProvider Class

Namespace: Microsoft.SharePoint.Client.Idcrl


## Properties

| Name | Type | Summary |
|---|---|---|
| **IdcrlServiceEnvironment** | string |  |
## Methods

| Name | Returns | Summary |
|---|---|---|
| **GetAuthenticationCookie(Uri url, string username, SecureString password, bool alwaysThrowOnFailure, EventHandler\<SharePointOnlineCredentialsWebRequestEventArgs\> executingWebRequest)** | string |  |
# STSSoapFaultCodes Class

Namespace: Microsoft.SharePoint.Client.Idcrl


## Fields

| Name | Type | Summary |
|---|---|---|
| **InvalidRequest** | string |  |
| **FailedAuthentication** | string |  |
| **RequestFailed** | string |  |
| **InvalidSecurityToken** | string |  |
| **AuthenticationBadElements** | string |  |
| **BadRequest** | string |  |
| **ExpiredData** | string |  |
| **InvalidTimeRange** | string |  |
| **InvalidScope** | string |  |
| **RenewNeeded** | string |  |
| **UnableToRenew** | string |  |
# UserRealmInfo Class

Namespace: Microsoft.SharePoint.Client.Idcrl


## Properties

| Name | Type | Summary |
|---|---|---|
| **STSAuthUrl** | string |  |
| **IsFederated** | bool |  |
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
