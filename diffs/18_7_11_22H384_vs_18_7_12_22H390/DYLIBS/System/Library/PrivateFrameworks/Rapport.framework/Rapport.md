## Rapport

> `/System/Library/PrivateFrameworks/Rapport.framework/Rapport`

```diff

-680.1.1.0.0
-  __TEXT.__text: 0x905a0
-  __TEXT.__auth_stubs: 0x19d0
-  __TEXT.__objc_methlist: 0x8b8c
-  __TEXT.__const: 0x2f48
-  __TEXT.__cstring: 0x14054
-  __TEXT.__gcc_except_tab: 0x16d0
-  __TEXT.__oslogstring: 0x588
-  __TEXT.__swift5_typeref: 0x4db
-  __TEXT.__constg_swiftt: 0x4e8
-  __TEXT.__swift5_reflstr: 0x1bc
-  __TEXT.__swift5_fieldmd: 0x4cc
-  __TEXT.__swift5_proto: 0xd4
-  __TEXT.__swift5_types: 0x6c
-  __TEXT.__swift5_assocty: 0x40
-  __TEXT.__swift5_builtin: 0x14
+680.1.2.0.0
+  __TEXT.__text: 0xc8558
+  __TEXT.__auth_stubs: 0x1f30
+  __TEXT.__objc_methlist: 0x986c
+  __TEXT.__const: 0x3278
+  __TEXT.__cstring: 0x12d04
+  __TEXT.__gcc_except_tab: 0x1484
+  __TEXT.__oslogstring: 0x1e72
+  __TEXT.__swift5_typeref: 0x93b
+  __TEXT.__swift5_capture: 0x7f4
+  __TEXT.__swift5_reflstr: 0x73c
+  __TEXT.__swift5_assocty: 0x88
+  __TEXT.__constg_swiftt: 0xb40
+  __TEXT.__swift5_fieldmd: 0x7cc
+  __TEXT.__swift5_builtin: 0x3c
+  __TEXT.__swift5_proto: 0xf0
+  __TEXT.__swift5_types: 0x80
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__swift5_capture: 0x10
   __TEXT.__swift5_protos: 0x4
-  __TEXT.__unwind_info: 0x22a0
-  __TEXT.__eh_frame: 0x4e8
-  __TEXT.__objc_classname: 0xa63
-  __TEXT.__objc_methname: 0x10772
-  __TEXT.__objc_methtype: 0x2b36
-  __TEXT.__objc_stubs: 0x8d40
-  __DATA_CONST.__got: 0x360
-  __DATA_CONST.__const: 0x25f8
-  __DATA_CONST.__objc_classlist: 0x278
+  __TEXT.__unwind_info: 0x29b0
+  __TEXT.__eh_frame: 0x608
+  __TEXT.__objc_classname: 0xa73
+  __TEXT.__objc_methname: 0x11d76
+  __TEXT.__objc_methtype: 0x2c9a
+  __TEXT.__objc_stubs: 0x8e00
+  __DATA_CONST.__got: 0x3e0
+  __DATA_CONST.__const: 0x2628
+  __DATA_CONST.__objc_classlist: 0x280
   __DATA_CONST.__objc_catlist: 0x10
-  __DATA_CONST.__objc_protolist: 0x108
+  __DATA_CONST.__objc_protolist: 0x118
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3920
-  __DATA_CONST.__objc_protorefs: 0xa8
+  __DATA_CONST.__objc_selrefs: 0x4148
+  __DATA_CONST.__objc_protorefs: 0xb0
   __DATA_CONST.__objc_superrefs: 0x1d0
   __DATA_CONST.__objc_arraydata: 0xb0
-  __AUTH_CONST.__auth_got: 0xcf8
-  __AUTH_CONST.__const: 0xaf0
-  __AUTH_CONST.__cfstring: 0x4f80
-  __AUTH_CONST.__objc_const: 0x100e8
-  __AUTH_CONST.__objc_intobj: 0x2b8
+  __AUTH_CONST.__auth_got: 0xfa8
+  __AUTH_CONST.__const: 0x1e78
+  __AUTH_CONST.__cfstring: 0x4be0
+  __AUTH_CONST.__objc_const: 0x10490
+  __AUTH_CONST.__objc_intobj: 0x228
   __AUTH_CONST.__objc_arrayobj: 0x30
   __AUTH_CONST.__objc_dictobj: 0x78
-  __AUTH.__objc_data: 0x4b8
-  __AUTH.__data: 0x780
-  __DATA.__objc_ivar: 0x1110
-  __DATA.__data: 0x1bc0
-  __DATA.__bss: 0x1e60
-  __DATA.__common: 0x30
+  __AUTH.__objc_data: 0xc48
+  __AUTH.__data: 0x7a8
+  __DATA.__objc_ivar: 0x1084
+  __DATA.__data: 0x1e50
+  __DATA.__bss: 0x21f0
+  __DATA.__common: 0x50
   __DATA_DIRTY.__objc_data: 0x14a0
   __DATA_DIRTY.__data: 0x198
   __DATA_DIRTY.__bss: 0x18

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 4179
-  Symbols:   7287
-  CStrings:  6078
+  Functions: 5210
+  Symbols:   7469
+  CStrings:  6267
 
Symbols:
+ +[RPConnection _makeIdentityWithPublicKey:identifier:type:]
+ +[RPConnection _sepPrivateKeyOfPairingIdentity:]
+ +[RPConnection _setPairingIdentity:sepPrivateKey:]
+ +[RPConnection _updateIdentity:withSEPPrivateKey:]
+ +[RPConnection _updateIdentity:withSecretKey:]
+ -[RPConnection _abortSendEntry:withError:]
+ -[RPConnection _addInUseProcess:]
+ -[RPConnection _addSelfIdentityInfoToMessage:flags:]
+ -[RPConnection _addSharedHomeIdentityWithMessage:]
+ -[RPConnection _bonjourFlagsFromLocalDeviceFlags]
+ -[RPConnection _btPipeHighPriorityConnected]
+ -[RPConnection _btPipeHighPriorityRequestable]
+ -[RPConnection _btPipeSelfIdentifier]
+ -[RPConnection _buildFrameHeaderData:length:]
+ -[RPConnection _callAuthCompletionHandler:]
+ -[RPConnection _callPairVerifyCompletion:]
+ -[RPConnection _canPeerDecode128bit:major:minor:patch:]
+ -[RPConnection _cloudDaemonIDSDeviceIDSelf]
+ -[RPConnection _cloudDaemonOSVersionForID:]
+ -[RPConnection _companionLinkFlagsString]
+ -[RPConnection _companionLinkFlagsSyncedMask]
+ -[RPConnection _completeRequestMetricsInOptions:responseSize:replyTime:hasReplyTime:]
+ -[RPConnection _completeSendMetrics:error:]
+ -[RPConnection _controlFlagsString]
+ -[RPConnection _controlFlagsSyncedMask]
+ -[RPConnection _createBleConnectTimer]
+ -[RPConnection _createOneShotTimer:handler:]
+ -[RPConnection _createRetryTimerWithDelay:]
+ -[RPConnection _createServerStartTimer]
+ -[RPConnection _createStartTimer]
+ -[RPConnection _decodeNSError:]
+ -[RPConnection _disableResolvedIdentityForSeconds:]
+ -[RPConnection _encodeNSError:intoDict:]
+ -[RPConnection _eventIDIsChatty:]
+ -[RPConnection _forgetBleConnectTimer]
+ -[RPConnection _forgetRetryTimer]
+ -[RPConnection _forgetStartTimer]
+ -[RPConnection _generatePeerIdentifierIfNeeded]
+ -[RPConnection _gestaltDeviceClassForModel:]
+ -[RPConnection _gestaltUserAssignedDeviceName]
+ -[RPConnection _getCanDecode128bit]
+ -[RPConnection _getCompanionLinkFlags]
+ -[RPConnection _getPeerStatusFlags]
+ -[RPConnection _getStatusFlags]
+ -[RPConnection _hasBtPipeHighPriority]
+ -[RPConnection _hasBtPipe]
+ -[RPConnection _hasIdentityDaemon]
+ -[RPConnection _homeKitIdentityIdentifierFromDaemon]
+ -[RPConnection _identityDaemonAddSessionPairedIdentity:]
+ -[RPConnection _identityDaemonIdentitiesOfType:error:]
+ -[RPConnection _identityDaemonIdentityOfSelfAndReturnError:]
+ -[RPConnection _identityDaemonResolveIdentityForSignature:data:typeFlags:error:]
+ -[RPConnection _identityDaemonSessionPairingIdentifier]
+ -[RPConnection _inUseProcessesToString]
+ -[RPConnection _insertBits32:newBits:mask:]
+ -[RPConnection _insertBits64:newBits:mask:]
+ -[RPConnection _isLocalDeviceCommunal]
+ -[RPConnection _linkTypeString]
+ -[RPConnection _localDeviceInfoPassword]
+ -[RPConnection _logRequestMetricsOnLinkType:length:rtt:]
+ -[RPConnection _logSendMetricsForLength:]
+ -[RPConnection _osVersionToString:]
+ -[RPConnection _pairingAppFlagsString:]
+ -[RPConnection _peerDeviceInfoSetTransportFlag:]
+ -[RPConnection _requestIDIsHighVolume:messageIsChatty:]
+ -[RPConnection _saveIdentityWithIDSDeviceID:message:]
+ -[RPConnection _scrubPskData]
+ -[RPConnection _sendFrameType:bodyObject:]
+ -[RPConnection _sendFrameType:dictionaryObject:]
+ -[RPConnection _setAppInfoPeer:]
+ -[RPConnection _setCanDecode128bit:]
+ -[RPConnection _setCompanionLinkFlags:]
+ -[RPConnection _setPeerAccountAltDSID:]
+ -[RPConnection _setPeerAccountID:]
+ -[RPConnection _setPeerActiveUserAltDSID:]
+ -[RPConnection _setPeerActivityLevel:]
+ -[RPConnection _setPeerCompanionLinkFlags:]
+ -[RPConnection _setPeerDeviceCapabilityFlags:]
+ -[RPConnection _setPeerDeviceColor:]
+ -[RPConnection _setPeerHomeKitIdentifier:]
+ -[RPConnection _setPeerIDSCorrelationIdentifier:]
+ -[RPConnection _setPeerIDSDeviceIdentifier:]
+ -[RPConnection _setPeerListeningPort:]
+ -[RPConnection _setPeerMediaRemoteIdentifier:]
+ -[RPConnection _setPeerMediaRouteIdentifier:]
+ -[RPConnection _setPeerMediaSystemIdentifier:]
+ -[RPConnection _setPeerMediaSystemName:]
+ -[RPConnection _setPeerMediaSystemRole:]
+ -[RPConnection _setPeerMediaSystemState:]
+ -[RPConnection _setPeerModel:]
+ -[RPConnection _setPeerName:]
+ -[RPConnection _setPeerOperatingSystemVersion:]
+ -[RPConnection _setPeerPublicIdentifier:]
+ -[RPConnection _setPeerRole:]
+ -[RPConnection _setPeerRoomName:]
+ -[RPConnection _setPeerServiceTypes:]
+ -[RPConnection _setPeerSiriInfo:]
+ -[RPConnection _setPeerSourceVersion:]
+ -[RPConnection _setPeerStatusFlags:]
+ -[RPConnection _setPeerVerifiedIdentity:]
+ -[RPConnection _setStatusFlags:]
+ -[RPConnection _signpostBeginClientResponse:requestID:]
+ -[RPConnection _signpostBeginSendRequest:requestID:length:linkType:highPriority:]
+ -[RPConnection _signpostEndClientResponse:length:linkType:highPriority:]
+ -[RPConnection _signpostEndSendRequest:rtt:requestSize:responseSize:]
+ -[RPConnection _signpostEndSendRequestTimeout:]
+ -[RPConnection _sourceVersionString]
+ -[RPConnection _startEventMessageMetrics:length:]
+ -[RPConnection _startReceivingFrames]
+ -[RPConnection _startRequestMessageMetrics:length:]
+ -[RPConnection _startResponseMessageMetrics:]
+ -[RPConnection _statusFlagsAccessFlagsMask]
+ -[RPConnection _statusFlagsAuthenticatedMask]
+ -[RPConnection _statusFlagsMeDeviceIsMe]
+ -[RPConnection _statusFlagsString]
+ -[RPConnection _statusFlagsSyncedMask]
+ -[RPConnection _stringToOSVersion:]
+ -[RPConnection _submitEventMetrics:length:]
+ -[RPConnection _updateBonjourFlagsOnPeerDevice:]
+ -[RPConnection _updateSessionPairedIdentityWithVerifiedIdentity:model:name:]
+ -[RPConnection isGuest]
+ -[RPConnection setValue:forUndefinedKey:]
+ -[RPConnection valueForUndefinedKey:]
+ -[RPEventRegistration registrationID]
+ -[RPEventRegistration setRegistrationID:]
+ -[RPRequestRegistration registrationID]
+ -[RPRequestRegistration setRegistrationID:]
+ GCC_except_table265
+ GCC_except_table73
+ GCC_except_table92
+ _OBJC_CLASS_$_OS_dispatch_source
+ _OBJC_CLASS_$__TtC7Rapport16RPConnectionCore
+ _OBJC_IVAR_$_RPConnection._core
+ _OBJC_IVAR_$_RPEventRegistration._registrationID
+ _OBJC_IVAR_$_RPRequestRegistration._registrationID
+ _OBJC_METACLASS_$__TtC7Rapport16RPConnectionCore
+ _OPACKDecodeNSData
+ _OPACKEncoderCreateNSData
+ _RPAuthenticationTypeToString
+ _RPPasswordTypeToString
+ __DATA__TtC7Rapport16RPConnectionCore
+ __INSTANCE_METHODS__TtC7Rapport16RPConnectionCore
+ __IVARS__TtC7Rapport16RPConnectionCore
+ __METACLASS_DATA__TtC7Rapport16RPConnectionCore
+ __OBJC_$_CLASS_METHODS_RPConnection
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CUReadWriteRequestable
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CUReadWriteRequestable
+ __OBJC_LABEL_PROTOCOL_$_CUReadWriteRequestable
+ __OBJC_PROTOCOL_$_CUReadWriteRequestable
+ __PROPERTIES__TtC7Rapport16RPConnectionCore
+ ___33-[RPConnection _createStartTimer]_block_invoke
+ ___38-[RPConnection _createBleConnectTimer]_block_invoke
+ ___39-[RPConnection _createServerStartTimer]_block_invoke
+ ___43-[RPConnection _createRetryTimerWithDelay:]_block_invoke
+ ___block_descriptor_40_e8_32w_e5_v8?0lw32l8
+ ___block_descriptor_48_e8_32s40w_e5_v8?0lw40l8s32l8
+ ___swift_allocate_boxed_opaque_existential_0
+ ___swift_destroy_boxed_opaque_existential_0
+ ___swift_instantiateConcreteTypeFromMangledNameAbstract
+ __swiftEmptyArrayStorage
+ __swift_stdlib_bridgeErrorToNSError
+ __swift_stdlib_malloc_size
+ _associated conformance 7Rapport25RPConnectionInternalStateOSHAASQ
+ _block_copy_helper
+ _block_descriptor
+ _block_destroy_helper
+ _bzero
+ _flat unique So22CUReadWriteRequestable_p
+ _malloc_size
+ _memmove
+ _objc_copyWeak
+ _objc_initWeak
+ _objc_msgSend$_abortSendEntry:withError:
+ _objc_msgSend$_scrubPskData
+ _objc_msgSend$_sendFrameBodyImpl:body:
+ _objc_msgSend$_sendFrameObjectImpl:unencryptedObject:
+ _objc_msgSend$abortRequestsWithError:
+ _objc_msgSend$abortSendEntry:withError:
+ _objc_msgSend$activateCalled
+ _objc_msgSend$activatedTicks
+ _objc_msgSend$buildSystemInfo
+ _objc_msgSend$clientConnectCompleted:
+ _objc_msgSend$clientConnectStart
+ _objc_msgSend$clientConnectStartBLE
+ _objc_msgSend$clientConnectStartBTPipe
+ _objc_msgSend$clientConnectStartTCP
+ _objc_msgSend$clientError:
+ _objc_msgSend$clientNetworkError:label:
+ _objc_msgSend$clientPairSetupCompleted:
+ _objc_msgSend$clientPairSetupStart
+ _objc_msgSend$clientPairSetupWithData:
+ _objc_msgSend$clientPairVerifyCompleted:
+ _objc_msgSend$clientPairVerifyStart
+ _objc_msgSend$clientPairVerifyWithData:
+ _objc_msgSend$clientPreAuthResponseWithData:
+ _objc_msgSend$clientPreAuthStart
+ _objc_msgSend$clientRetryFired
+ _objc_msgSend$clientRetryStart
+ _objc_msgSend$clientRun
+ _objc_msgSend$clientStartSession
+ _objc_msgSend$clientStarted
+ _objc_msgSend$configureForSessionPairing:
+ _objc_msgSend$doubleValue
+ _objc_msgSend$highPriorityStream
+ _objc_msgSend$homeKitIdentityIdentifier
+ _objc_msgSend$homeKitIdentitySignature
+ _objc_msgSend$identityKeyData
+ _objc_msgSend$identitySignature
+ _objc_msgSend$identityVerified
+ _objc_msgSend$initiator
+ _objc_msgSend$internalState
+ _objc_msgSend$invalidateCalled
+ _objc_msgSend$invalidateDone
+ _objc_msgSend$mainStream
+ _objc_msgSend$pairSetupInvalidate
+ _objc_msgSend$pairSetupSession
+ _objc_msgSend$pairVerifyAuthType
+ _objc_msgSend$pairVerifyCompleted
+ _objc_msgSend$pairVerifyFailed
+ _objc_msgSend$pairVerifyInvalidate
+ _objc_msgSend$pairVerifySession
+ _objc_msgSend$pairVerifySign:flags:error:
+ _objc_msgSend$pairVerifyUsedIdentity
+ _objc_msgSend$pairVerifyVerifySignature:data:flags:error:
+ _objc_msgSend$peerAddrStr
+ _objc_msgSend$peerHKUserID
+ _objc_msgSend$processSendsUsingConnection:
+ _objc_msgSend$pskPrepareWithIsClient:
+ _objc_msgSend$receivedEvent:length:moreComing:
+ _objc_msgSend$receivedFrameCountCurrent
+ _objc_msgSend$receivedFrameCountLast
+ _objc_msgSend$receivedObject:length:moreComing:
+ _objc_msgSend$receivedRequest:length:moreComing:
+ _objc_msgSend$receivedResponse:length:moreComing:
+ _objc_msgSend$receivedSystemInfo:xid:
+ _objc_msgSend$requestable
+ _objc_msgSend$requests
+ _objc_msgSend$retryCount
+ _objc_msgSend$sendArray
+ _objc_msgSend$serverAccept
+ _objc_msgSend$serverAcceptBLE
+ _objc_msgSend$serverAcceptBTPipe
+ _objc_msgSend$serverAcceptTCP
+ _objc_msgSend$serverError:
+ _objc_msgSend$serverNetworkError:label:
+ _objc_msgSend$serverPairSetupCompleted:
+ _objc_msgSend$serverPairSetupWithData:start:
+ _objc_msgSend$serverPairVerifyCompleted:
+ _objc_msgSend$serverPairVerifyWithData:start:
+ _objc_msgSend$serverPreAuthRequestWithData:
+ _objc_msgSend$serverRun
+ _objc_msgSend$serverStarted
+ _objc_msgSend$setActivateCalled:
+ _objc_msgSend$setActivatedTicks:
+ _objc_msgSend$setHighPriorityStream:
+ _objc_msgSend$setHomeKitIdentityIdentifier:
+ _objc_msgSend$setHomeKitIdentitySignature:
+ _objc_msgSend$setIdentityKeyData:
+ _objc_msgSend$setIdentitySignature:
+ _objc_msgSend$setInitiator:
+ _objc_msgSend$setInternalState:
+ _objc_msgSend$setInvalidateCalled:
+ _objc_msgSend$setInvalidateDone:
+ _objc_msgSend$setMainStream:
+ _objc_msgSend$setPairSetupSession:
+ _objc_msgSend$setPairVerifyAuthType:
+ _objc_msgSend$setPairVerifyCompleted:
+ _objc_msgSend$setPairVerifyFailed:
+ _objc_msgSend$setPairVerifySession:
+ _objc_msgSend$setPeerAddrStr:
+ _objc_msgSend$setPeerHKUserID:
+ _objc_msgSend$setReceivedFrameCountCurrent:
+ _objc_msgSend$setReceivedFrameCountLast:
+ _objc_msgSend$setRequestable:
+ _objc_msgSend$setRequests:
+ _objc_msgSend$setRetryCount:
+ _objc_msgSend$setRetryTicks:
+ _objc_msgSend$setSelfAddrString:
+ _objc_msgSend$setSendArray:
+ _objc_msgSend$setShowPasswordCalled:
+ _objc_msgSend$setStartTimeoutSeconds:
+ _objc_msgSend$setStepDone:
+ _objc_msgSend$setStepError:
+ _objc_msgSend$setXidLast:
+ _objc_msgSend$showPasswordCalled
+ _objc_msgSend$startTimeoutSeconds
+ _objc_msgSend$stepDone
+ _objc_msgSend$stepError
+ _objc_msgSend$updateExternalState
+ _objc_msgSend$xidLast
+ _objectdestroy.114Tm
+ _objectdestroy.146Tm
+ _objectdestroy.212Tm
+ _objectdestroy.220Tm
+ _objectdestroy.24Tm
+ _objectdestroy.84Tm
+ _swift_arrayDestroy
+ _swift_arrayInitWithCopy
+ _swift_beginAccess
+ _swift_bridgeObjectRelease_n
+ _swift_bridgeObjectRetain_n
+ _swift_dynamicCast
+ _swift_dynamicCastClass
+ _swift_endAccess
+ _swift_getErrorValue
+ _swift_getForeignTypeMetadata
+ _swift_getObjCClassMetadata
+ _swift_getObjectType
+ _swift_getTypeByMangledNameInContextInMetadataState2
+ _swift_isEscapingClosureAtFileLocation
+ _swift_isUniquelyReferenced_nonNull_native
+ _swift_release_n
+ _swift_retain_n
+ _swift_slowDealloc
+ _swift_unknownObjectRelease
+ _swift_unknownObjectRelease_n
+ _swift_unknownObjectRetain
+ _swift_unknownObjectRetain_n
+ _swift_unknownObjectUnownedDestroy
+ _swift_unknownObjectUnownedInit
+ _swift_unknownObjectUnownedLoadStrong
+ _swift_unknownObjectWeakDestroy
+ _swift_unknownObjectWeakInit
+ _swift_unknownObjectWeakLoadStrong
+ _symbolic $sSY
+ _symbolic SDy_____ypG s11AnyHashableV
+ _symbolic SDy_____ypGSg s11AnyHashableV
+ _symbolic SSIego_
+ _symbolic SSSg
+ _symbolic Say_____G 10Foundation4UUIDV
+ _symbolic Say_____G 8Dispatch0A13WorkItemFlagsV
+ _symbolic Sb
+ _symbolic Sd
+ _symbolic Si
+ _symbolic So10RPIdentityCSg
+ _symbolic So11RPSendEntryC
+ _symbolic So12NSDictionaryCSgACSo7NSErrorCSgIeyByyy_
+ _symbolic So12RPConnectionC
+ _symbolic So12RPConnectionCSgXw
+ _symbolic So12RPConnectionCSgXwz_Xx
+ _symbolic So12RPConnectionCXo
+ _symbolic So14CUWriteRequestCIegg_
+ _symbolic So14CUWriteRequestCSgXw
+ _symbolic So14CUWriteRequestCSgXwz_Xx
+ _symbolic So14NSMutableArrayC
+ _symbolic So14RPRequestEntryC
+ _symbolic So15CUBLEConnectionC
+ _symbolic So15CUPairingStreamCSg
+ _symbolic So15CUTCPConnectionC
+ _symbolic So16CUPairingSessionCSg
+ _symbolic So17OS_dispatch_queueC
+ _symbolic So19NSMutableDictionaryCSg
+ _symbolic So7NSErrorC
+ _symbolic So7NSErrorCSg
+ _symbolic So7NSErrorCSgIegg_
+ _symbolic So7NSErrorCSgIeyBy_
+ _symbolic So8NSNumberC
+ _symbolic So8NSObjectCIego_
+ _symbolic So8NSObjectCSg
+ _symbolic So8NSObjectCSgIego_
+ _symbolic SsIegr_
+ _symbolic _____ 7Rapport16RPConnectionCoreC
+ _symbolic _____ 7Rapport21RPConnectionConstantsO
+ _symbolic _____ 7Rapport25RPConnectionInternalStateO
+ _symbolic _____ So14RPIdentityTypeV
+ _symbolic _____ So20RPAuthenticationTypeV
+ _symbolic _____ s5Int32V
+ _symbolic _____ s5UInt8V
+ _symbolic _____ s6UInt32V
+ _symbolic _____ s6UInt64V
+ _symbolic _____Iegy_Sg s6UInt32V
+ _symbolic _____IeyBy_ s6UInt32V
+ _symbolic _____SSIegyg_Sg s6UInt32V
+ _symbolic _____Sg 10Foundation4UUIDV
+ _symbolic _____SgXw 7Rapport16RPConnectionCoreC
+ _symbolic _____SgXwz_Xx 7Rapport16RPConnectionCoreC
+ _symbolic _____So8NSStringCIeyByy_ s6UInt32V
+ _symbolic _____XDXMT 7Rapport16RPConnectionCoreC
+ _symbolic __________Iegyy_ s6UInt32V s5Int32V
+ _symbolic __________IeyByy_ s6UInt32V s5Int32V
+ _symbolic ______pSg So22CUReadWriteRequestableP
+ _symbolic ______pSg s5ErrorP
+ _symbolic ______pSgIegg_Sg s5ErrorP
+ _symbolic ______ypt s11AnyHashableV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 10Foundation4DataV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 10Foundation4UUIDV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC s5UInt8V
+ _symbolic _____y______yptG s23_ContiguousArrayStorageC s11AnyHashableV
+ _symbolic _____y_____ypG s18_DictionaryStorageC s11AnyHashableV
+ _symbolic _____yySpy_____Gz_SpySo8NSObjectCSgGSgzSpyypGSgztcG s23_ContiguousArrayStorageC s5UInt8V
+ _symbolic _____yyp_yptG s23_ContiguousArrayStorageC
+ _symbolic yXlSg
+ _symbolic yXlSgz_Xx
+ _symbolic ypSg
+ _symbolic ypypSpy_____GIgnny_ 10ObjectiveC8ObjCBoolV
- GCC_except_table133
- GCC_except_table140
- GCC_except_table144
- _OBJC_IVAR_$_RPConnection._activateCalled
- _OBJC_IVAR_$_RPConnection._activatedTicks
- _OBJC_IVAR_$_RPConnection._highPriorityAuthTagLength
- _OBJC_IVAR_$_RPConnection._highPriorityStream
- _OBJC_IVAR_$_RPConnection._homeKitIdentityIdentifier
- _OBJC_IVAR_$_RPConnection._homeKitIdentitySignature
- _OBJC_IVAR_$_RPConnection._identityKeyData
- _OBJC_IVAR_$_RPConnection._identitySignature
- _OBJC_IVAR_$_RPConnection._identityVerified
- _OBJC_IVAR_$_RPConnection._initiator
- _OBJC_IVAR_$_RPConnection._internalState
- _OBJC_IVAR_$_RPConnection._invalidateCalled
- _OBJC_IVAR_$_RPConnection._invalidateDone
- _OBJC_IVAR_$_RPConnection._mainAuthTagLength
- _OBJC_IVAR_$_RPConnection._mainStream
- _OBJC_IVAR_$_RPConnection._pairSetupAuthType
- _OBJC_IVAR_$_RPConnection._pairSetupSession
- _OBJC_IVAR_$_RPConnection._pairVerifyAuthType
- _OBJC_IVAR_$_RPConnection._pairVerifyCompleted
- _OBJC_IVAR_$_RPConnection._pairVerifyFailed
- _OBJC_IVAR_$_RPConnection._pairVerifyIdentityType
- _OBJC_IVAR_$_RPConnection._pairVerifySession
- _OBJC_IVAR_$_RPConnection._pairVerifyUsedIdentity
- _OBJC_IVAR_$_RPConnection._peerAddrString
- _OBJC_IVAR_$_RPConnection._peerHomeKitUserIdentifier
- _OBJC_IVAR_$_RPConnection._receivedFrameCountCurrent
- _OBJC_IVAR_$_RPConnection._receivedFrameCountLast
- _OBJC_IVAR_$_RPConnection._requestable
- _OBJC_IVAR_$_RPConnection._requests
- _OBJC_IVAR_$_RPConnection._retryCount
- _OBJC_IVAR_$_RPConnection._retryFired
- _OBJC_IVAR_$_RPConnection._retryTicks
- _OBJC_IVAR_$_RPConnection._selfAddrString
- _OBJC_IVAR_$_RPConnection._sendArray
- _OBJC_IVAR_$_RPConnection._showPasswordCalled
- _OBJC_IVAR_$_RPConnection._stepDone
- _OBJC_IVAR_$_RPConnection._stepError
- _OBJC_IVAR_$_RPConnection._xidLast
- _RPFrameTypeToString
- __StateToString
- ___104-[RPConnection _sendEncryptedResponse:options:error:xid:requestID:highPriority:isChatty:replyStartTime:]_block_invoke
- ___29-[RPConnection _serverAccept]_block_invoke
- ___32-[RPConnection _serverAcceptBLE]_block_invoke
- ___32-[RPConnection _serverAcceptBLE]_block_invoke_2
- ___32-[RPConnection _serverAcceptTCP]_block_invoke
- ___32-[RPConnection _serverAcceptTCP]_block_invoke_2
- ___32-[RPConnection _serverAcceptTCP]_block_invoke_3
- ___33-[RPConnection _clientRetryStart]_block_invoke
- ___35-[RPConnection _clientStartSession]_block_invoke
- ___37-[RPConnection _clientPairSetupStart]_block_invoke
- ___37-[RPConnection _clientPairSetupStart]_block_invoke_2
- ___37-[RPConnection _clientPairSetupStart]_block_invoke_3
- ___37-[RPConnection _receivedRequest:ctx:]_block_invoke
- ___38-[RPConnection _clientConnectStartBLE]_block_invoke
- ___38-[RPConnection _clientConnectStartBLE]_block_invoke_2
- ___38-[RPConnection _clientConnectStartBLE]_block_invoke_3
- ___38-[RPConnection _clientConnectStartBLE]_block_invoke_4
- ___38-[RPConnection _clientConnectStartTCP]_block_invoke
- ___38-[RPConnection _clientConnectStartTCP]_block_invoke_2
- ___38-[RPConnection _clientConnectStartTCP]_block_invoke_3
- ___38-[RPConnection _clientConnectStartTCP]_block_invoke_4
- ___38-[RPConnection _clientPairVerifyStart]_block_invoke
- ___38-[RPConnection _clientPairVerifyStart]_block_invoke_2
- ___38-[RPConnection _clientPairVerifyStart]_block_invoke_3
- ___38-[RPConnection _clientPairVerifyStart]_block_invoke_4
- ___40-[RPConnection _abortRequestsWithError:]_block_invoke
- ___40-[RPConnection _clientConnectCompleted:]_block_invoke
- ___40-[RPConnection _receivedSystemInfo:xid:]_block_invoke
- ___41-[RPConnection _clientConnectStartBTPipe]_block_invoke
- ___44-[RPConnection _configureForSessionPairing:]_block_invoke
- ___44-[RPConnection _configureForSessionPairing:]_block_invoke_2
- ___44-[RPConnection _configureForSessionPairing:]_block_invoke_3
- ___47-[RPConnection _serverPairSetupWithData:start:]_block_invoke
- ___47-[RPConnection _serverPairSetupWithData:start:]_block_invoke_2
- ___47-[RPConnection _serverPairSetupWithData:start:]_block_invoke_3
- ___47-[RPConnection _serverPairSetupWithData:start:]_block_invoke_4
- ___48-[RPConnection _serverPairVerifyWithData:start:]_block_invoke
- ___48-[RPConnection _serverPairVerifyWithData:start:]_block_invoke_2
- ___48-[RPConnection _serverPairVerifyWithData:start:]_block_invoke_3
- ___48-[RPConnection _serverPairVerifyWithData:start:]_block_invoke_4
- ___66-[RPConnection _sendEncryptedEventID:data:xid:options:completion:]_block_invoke
- ___66-[RPConnection _sendEncryptedEventID:data:xid:options:completion:]_block_invoke_2
- ___77-[RPConnection sendEncryptedRequestID:request:xpcID:options:responseHandler:]_block_invoke
- ___88-[RPConnection _sendEncryptedRequestID:request:xpcID:options:sendEntry:responseHandler:]_block_invoke
- ___block_descriptor_40_e8_32s_e19_v20?0I8"NSData"12ls32l8
- ___block_descriptor_40_e8_32s_e21_v20?0I8"NSString"12ls32l8
- ___block_descriptor_40_e8_32s_e31_"NSData"28?0I8"NSData"12^20ls32l8
- ___block_descriptor_40_e8_32s_e34_B36?0I8"NSData"12"NSData"20^28ls32l8
- ___block_descriptor_44_e8_32s_e19_v20?0I8"NSData"12ls32l8
- ___block_descriptor_48_e8_32bs40r_e17_v16?0"NSError"8lr40l8s32l8
- ___block_descriptor_48_e8_32s40bs_e11_v16?0I8i12ls32l8s40l8
- ___block_descriptor_48_e8_32s40s_e29_B32?0"CUPairedPeer"8Q16^24ls32l8s40l8
- ___block_descriptor_48_e8_32s40s_e31_"CUPairingIdentity"24?0Q8^16ls32l8s40l8
- ___block_descriptor_48_e8_32s40s_e41_v32?0"NSNumber"8"RPRequestEntry"16^B24ls32l8s40l8
- ___block_descriptor_48_e8_32s40s_e43_"CUPairedPeer"32?0"CUPairedPeer"8Q16^24ls32l8s40l8
- ___block_descriptor_60_e8_32s40s48s_e5_v8?0ls32l8s40l8s48l8
- ___block_descriptor_66_e8_32s40s48s56s_e51_v32?0"NSDictionary"8"NSDictionary"16"NSError"24ls32l8s40l8s48l8s56l8
- _objc_msgSend$_clientConnectStart
- _objc_msgSend$_clientConnectStartBLE
- _objc_msgSend$_clientConnectStartBTPipe
- _objc_msgSend$_clientConnectStartTCP
- _objc_msgSend$_clientNetworkError:label:
- _objc_msgSend$_clientPairSetupCompleted:
- _objc_msgSend$_clientPairSetupPromptWithFlags:throttleSeconds:handler:
- _objc_msgSend$_clientPairSetupStart
- _objc_msgSend$_clientPairVerifyCompleted:
- _objc_msgSend$_clientPairVerifyStart
- _objc_msgSend$_clientPreAuthStart
- _objc_msgSend$_clientRetryStart
- _objc_msgSend$_clientRun
- _objc_msgSend$_clientStartSession
- _objc_msgSend$_clientStarted
- _objc_msgSend$_configureForSessionPairing:
- _objc_msgSend$_identityProofsAddWithHomeKitUUID:
- _objc_msgSend$_identityProofsVerify:
- _objc_msgSend$_pairVerifySignData:flags:error:
- _objc_msgSend$_pairVerifyVerifySignature:data:flags:error:
- _objc_msgSend$_pskPrepare:
- _objc_msgSend$_receivedEvent:ctx:
- _objc_msgSend$_receivedRequest:ctx:
- _objc_msgSend$_receivedResponse:ctx:
- _objc_msgSend$_receivedSystemInfo:xid:
- _objc_msgSend$_serverAccept
- _objc_msgSend$_serverAcceptBLE
- _objc_msgSend$_serverAcceptBTPipe
- _objc_msgSend$_serverAcceptTCP
- _objc_msgSend$_serverNetworkError:label:
- _objc_msgSend$_serverPairSetupCompleted:
- _objc_msgSend$_serverPairVerifyCompleted:
- _objc_msgSend$_serverPairingAllowed
- _objc_msgSend$_serverRun
- _objc_msgSend$_serverStarted
- _objc_msgSend$_systeminfo
- _objc_msgSend$_updateExternalState
- _objc_msgSend$aclActual
- _objc_msgSend$activeUserAltDSID
- _objc_msgSend$authTagLength
- _objc_msgSend$clientBundleID
- _objc_msgSend$clientUseCase
- _objc_msgSend$completion
- _objc_msgSend$copyIdentityHandler
- _objc_msgSend$dictionaryWithObjectsAndKeys:
- _objc_msgSend$encryptData:aadData:error:
- _objc_msgSend$eventData
- _objc_msgSend$homeKitUserIdentifiers
- _objc_msgSend$idsCorrelationIdentifier
- _objc_msgSend$indexOfObject:
- _objc_msgSend$initWithPairedPeer:type:
- _objc_msgSend$listeningPort
- _objc_msgSend$openStreamWithName:error:
- _objc_msgSend$openStreamWithName:type:error:
- _objc_msgSend$peerAppFlags
- _objc_msgSend$peerHostState
- _objc_msgSend$prepareWithName:isClient:pskData:error:
- _objc_msgSend$proxyDeviceUpdateHandler
- _objc_msgSend$queueTicks
- _objc_msgSend$receivedData:
- _objc_msgSend$reconfirm
- _objc_msgSend$request
- _objc_msgSend$role
- _objc_msgSend$secretKey
- _objc_msgSend$selfAppFlags
- _objc_msgSend$sendTicks
- _objc_msgSend$setAcl:
- _objc_msgSend$setAdditionalPeerInfo:
- _objc_msgSend$setAllowedMACAddresses:
- _objc_msgSend$setAltIRK:
- _objc_msgSend$setClientBundleID:
- _objc_msgSend$setClientUseCase:
- _objc_msgSend$setConnectTimeoutSecs:
- _objc_msgSend$setCopyIdentityHandler:
- _objc_msgSend$setDataArray:
- _objc_msgSend$setDataTimeoutSecs:
- _objc_msgSend$setDestinationBonjour:
- _objc_msgSend$setDestinationPSM:
- _objc_msgSend$setDestinationUUID:
- _objc_msgSend$setDeviceIRKData:
- _objc_msgSend$setEventData:
- _objc_msgSend$setFindPeerHandler:
- _objc_msgSend$setFixedPIN:
- _objc_msgSend$setFlowControlChangedHandler:
- _objc_msgSend$setHidePINHandler:
- _objc_msgSend$setHomeKitUserIdentifiers:
- _objc_msgSend$setKeepAliveIdleSeconds:
- _objc_msgSend$setKeepAliveIntervalSeconds:
- _objc_msgSend$setKeepAliveMaxCount:
- _objc_msgSend$setLength:
- _objc_msgSend$setPinType:
- _objc_msgSend$setPublicKey:
- _objc_msgSend$setQueueTicks:
- _objc_msgSend$setRequest:
- _objc_msgSend$setSavePeerHandler:
- _objc_msgSend$setSecretKey:
- _objc_msgSend$setSelfAppFlags:
- _objc_msgSend$setSendDataHandler:
- _objc_msgSend$setSendTicks:
- _objc_msgSend$setSessionType:
- _objc_msgSend$setShowPINHandlerEx:
- _objc_msgSend$setSignDataHandler:
- _objc_msgSend$setTimer:
- _objc_msgSend$setVerifySignatureHandler:
- _objc_msgSend$setXid:
- _objc_msgSend$setXidObj:
- _objc_msgSend$setXpcID:
- _objc_msgSend$timer
- _objc_msgSend$writeWithRequest:
- _objc_msgSend$xid
- _objc_msgSend$xidObj
- _objc_msgSend$xpcID
- _objc_release_x3
CStrings:
+ "### Abort queued ID '%{public}s': %{public}@"
+ "### Abort request XID 0x%{public}s: %{public}@"
+ "### Client error: %{public}@"
+ "### Connect failed: %{public}@"
+ "### Failed to get self identity: %{public}@"
+ "### Ignoring call to send event ID '%{public}s' when invalidating"
+ "### Ignoring received PreAuthResponse when not expected: %@"
+ "### Ignoring response to requestID '%{public}s' after invalidation"
+ "### Ignoring send request ID '%{public}s' when invalidating"
+ "### PSK prepare failed: %{public}@"
+ "### PairSetup client completion failed: %{public}@"
+ "### PairSetup server completion failed: %{public}@"
+ "### PairSetup server receive failed: %{public}@"
+ "### PairVerify client completion failed: %{public}@"
+ "### PairVerify client failed: %{public}@"
+ "### PairVerify server completion failed: %{public}s, %{public}@"
+ "### PairVerify server receive failed: %{public}@"
+ "### PairVerifyVerify failed: %{public}@"
+ "### PreAuthRequest decode failed"
+ "### PreAuthRequest failed, unexpected state"
+ "### PreAuthResponse decode failed: %{public}d"
+ "### Process unsupported request"
+ "### Received event with no ID from %s"
+ "### Received event with no content from %s"
+ "### Received request XID 0x%{public}s with no ID from %s"
+ "### Received request with no XID from %s"
+ "### Received requestID '%{public}s', XID 0x%{public}s with no content from %s"
+ "### Received requestID '%{public}s', XID 0x%{public}s, from %s with no handler"
+ "### Received response XID 0x%{public}s with no content from %s"
+ "### Received response XID 0x%{public}s with no request from %s"
+ "### Received response XID 0x%{public}s, error %{public}@, from %s, %{public}llu ms"
+ "### Received response with no XID from %s"
+ "### Request timeout '%{public}s' not found, %{public}f seconds"
+ "### Request timeout '%{public}s', %{public}f seconds"
+ "### Request timeout XID 0x%{public}s, %{public}f seconds"
+ "### Send encrypted data (%{public}ld bytes) failed: '%{public}s', %{public}@"
+ "### Send encrypted requestID '%{public}s' failed: %{public}@"
+ "### Send encrypted response XID 0x%{public}s failed: %{public}@"
+ "### Send frame 0x%{public}s encode failed: %{public}d"
+ "### Send frame type 0x%{public}s failed: %{public}@"
+ "### Sending response XID 0x%{public}s, error: %{public}@"
+ "### Server error: %{public}@"
+ "### Timeout for XID 0x%{public}s with no request"
+ "### Unknown message type: %{public}d"
+ "### Unsupported send attempt"
+ "%#ll{flags}"
+ "%#{flags}"
+ "-[RPConnection _startReceivingFrames]"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/Rapport/Rapport/RPIRKRatchet.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/Rapport/Rapport/Swift/RPUtilities.swift"
+ "@\"_TtC7Rapport16RPConnectionCore\""
+ "@24@0:8Q16"
+ "@28@0:8C16Q20"
+ "@28@0:8i16^@20"
+ "@32@0:8d16@?24"
+ "@36@0:8@16@24i32"
+ "@40@0:8{?=qqq}16"
+ "@44@0:8@16@24I32^@36"
+ "AirPlay restrictions ignored"
+ "B28@0:8@16B24"
+ "B44@0:8i16q20q28q36"
+ "BLE client connection invalidated"
+ "BLE client connection with bundleID: %s and clientUseCase: %{public}ld"
+ "BLE server connection invalidated"
+ "Backwards compatibility authType -> sessionPaired"
+ "Backwards compatibility change authType sessionPaired -> rpIdentity"
+ "CUReadWriteRequestable"
+ "Client PairSetup retry"
+ "Client connect start: %@"
+ "Client immediate non-RPIdentity retry"
+ "Client state: %{public}s -> %{public}s"
+ "Configuring for session pairing"
+ "Enabling FitnessPairing"
+ "External state changed: %{public}s -> %{public}s"
+ "Failed to open main stream"
+ "Find paired peer handler for peer %@ options %llu"
+ "I28@0:8I16I20I24"
+ "In use processes updated to: %{public}s"
+ "OnDemand connection failed, invalidating"
+ "PairSetup completed client."
+ "PairSetup next (%ld bytes)"
+ "PairSetup response error: '"
+ "PairSetup server rejecting when not allowed"
+ "PairSetup server rejecting when not allowing non-Home devices"
+ "PairVerify completed client %{public}s, %{public}s, %{public}s, RPI %@"
+ "PairVerify completed server: %{public}s, %{public}s, %{public}s, RPI %@"
+ "PairVerify next (%ld bytes)"
+ "PairVerify start client: AT %{public}s, CF %{public}s, FL %{public}s, PWT %{public}s"
+ "PairVerifySign success: CF %{public}s, AF %{public}s"
+ "PairVerifySign: Not using RPI"
+ "PairVerifySign: Not using RPI: CF %{public}s, AF %{public}s"
+ "PairVerifyVerify resolve identity failed"
+ "PairVerifyVerify success: %{public}d, CF %{public}s, AF %{public}s"
+ "PairVerifyVerify: Not using RPI"
+ "PairVerifyVerify: Not using RPI: CF %{public}s, AF %{public}s"
+ "Peer appears missing, invalidating"
+ "Peer appears present, retrying"
+ "Peer is blocking access, invalidating"
+ "Peer may be unreachable, sending reachability probe (%{public}s)"
+ "Peer missing after retry timer, invalidating"
+ "Q40@0:8Q16Q24Q32"
+ "Queuing send event ID '%{public}s', XID 0x%{public}s (%{public}ld send(s) pending)"
+ "Queuing send request ID '%{public}s' (%{public}ld send(s) pending)"
+ "Rapport.RPConnectionCore"
+ "Received PreAuthRequest"
+ "Received PreAuthResponse: %@"
+ "Received SharedHome identity: ID '%s'"
+ "Received client service type %{public}s"
+ "Received event ID '%{public}s', XID 0x%{public}s, %{public}ld keys, from %s"
+ "Received identity from IDS '%s'"
+ "Received requestID '%{public}s', XID 0x%{public}s, %{public}ld keys, from %s"
+ "Received response XID 0x%{public}s, %{public}ld keys, from %s, %{public}llu ms request size %{public}ld response size %{public}llu"
+ "Rejected in unexpected state"
+ "Retrying delayed: %.*f seconds"
+ "Retrying immediately: %lds since last retry"
+ "Retrying immediately: first retry"
+ "Save paired peer handler for peer %@ options %llu"
+ "Send PreAuthRequest: %@"
+ "Send PreAuthResponse"
+ "Send SharedHome identity"
+ "Send encrypted event failed: '%{public}s', %{public}@"
+ "Send encrypted requestID '%{public}s' failed: %{public}@"
+ "Send frame 0x%{public}s, (%{public}ld bytes)"
+ "Send identity"
+ "Send request ID '%{public}s', XID 0x%{public}s, (%{public}ld bytes) on link type %{public}s %{public}s"
+ "Send response XID 0x%{public}s, (%{public}ld bytes) on link type %{public}s%{public}s"
+ "SendEventID '%{public}s', XID 0x%{public}s, (%{public}ld bytes) on link type %{public}s %{public}s"
+ "Sending client service type %{public}s"
+ "Server state: %{public}s -> %{public}s"
+ "T@\"<CUReadWriteRequestable>\",N,&,Vrequestable"
+ "T@\"CUPairingSession\",N,&,VpairSetupSession"
+ "T@\"CUPairingSession\",N,&,VpairVerifySession"
+ "T@\"CUPairingStream\",N,&,VhighPriorityStream"
+ "T@\"CUPairingStream\",N,&,VmainStream"
+ "T@\"NSData\",N,C"
+ "T@\"NSError\",N,&,VstepError"
+ "T@\"NSMutableArray\",N,&,VsendArray"
+ "T@\"NSMutableDictionary\",N,&,Vrequests"
+ "T@\"NSString\",N,C"
+ "T@\"NSString\",R,D,N"
+ "T@\"NSUUID\",&,N,V_registrationID"
+ "T@\"RPIdentity\",N,&,VidentityVerified"
+ "T@\"RPIdentity\",R,D,N"
+ "TB,N,VactivateCalled"
+ "TB,N,VinvalidateCalled"
+ "TB,N,VinvalidateDone"
+ "TB,N,VpairVerifyCompleted"
+ "TB,N,VpairVerifyFailed"
+ "TB,N,VpairVerifyUsedIdentity"
+ "TB,N,VretryFired"
+ "TB,N,VshowPasswordCalled"
+ "TB,N,VstepDone"
+ "TB,R,N,GisGuest"
+ "TCP client connection invalidated"
+ "TCP server connection invalidated"
+ "TI,N,VxidLast"
+ "TQ,N,VactivatedTicks"
+ "TQ,N,VreceivedFrameCountCurrent"
+ "TQ,N,VreceivedFrameCountLast"
+ "TQ,N,VretryTicks"
+ "Td,N,VstartTimeoutSeconds"
+ "Ti,N,VinternalState"
+ "Ti,N,VpairSetupAuthType"
+ "Ti,N,VpairVerifyAuthType"
+ "Ti,N,VpairVerifyIdentityType"
+ "Ti,N,VretryCount"
+ "Ti,R,D,N"
+ "Too many retries, invalidating: retries %d, %@"
+ "Tq,N,VhighPriorityAuthTagLength"
+ "Tq,N,VmainAuthTagLength"
+ "Transferring event ID %{public}s to connection %{public}s"
+ "Transferring request ID %{public}s to connection %{public}s with timeout %{public}f"
+ "Unsupported password type or auth type"
+ "^{__SecKey=}24@0:8@16"
+ "_TtC7Rapport16RPConnectionCore"
+ "__swift_objectForKeyedSubscript:"
+ "__swift_setObject:forKeyedSubscript:"
+ "_abortSendEntry:withError:"
+ "_addInUseProcess:"
+ "_addSelfIdentityInfoToMessage:flags:"
+ "_addSharedHomeIdentityWithMessage:"
+ "_bonjourFlagsFromLocalDeviceFlags"
+ "_btPipeHighPriorityConnected"
+ "_btPipeHighPriorityRequestable"
+ "_btPipeSelfIdentifier"
+ "_buildFrameHeaderData:length:"
+ "_callAuthCompletionHandler:"
+ "_callPairVerifyCompletion:"
+ "_canPeerDecode128bit:major:minor:patch:"
+ "_cloudDaemonIDSDeviceIDSelf"
+ "_cloudDaemonOSVersionForID:"
+ "_companionLinkFlagsString"
+ "_companionLinkFlagsSyncedMask"
+ "_completeRequestMetricsInOptions:responseSize:replyTime:hasReplyTime:"
+ "_completeSendMetrics:error:"
+ "_controlFlagsString"
+ "_controlFlagsSyncedMask"
+ "_core"
+ "_createBleConnectTimer"
+ "_createOneShotTimer:handler:"
+ "_createRetryTimerWithDelay:"
+ "_createServerStartTimer"
+ "_createStartTimer"
+ "_decodeNSError:"
+ "_disableResolvedIdentityForSeconds:"
+ "_encodeNSError:intoDict:"
+ "_eventIDIsChatty:"
+ "_forgetBleConnectTimer"
+ "_forgetRetryTimer"
+ "_forgetStartTimer"
+ "_generatePeerIdentifierIfNeeded"
+ "_gestaltDeviceClassForModel:"
+ "_gestaltUserAssignedDeviceName"
+ "_getCanDecode128bit"
+ "_getCompanionLinkFlags"
+ "_getPeerStatusFlags"
+ "_getStatusFlags"
+ "_hasBtPipe"
+ "_hasBtPipeHighPriority"
+ "_hasIdentityDaemon"
+ "_homeKitIdentityIdentifierFromDaemon"
+ "_identityDaemonAddSessionPairedIdentity:"
+ "_identityDaemonIdentitiesOfType:error:"
+ "_identityDaemonIdentityOfSelfAndReturnError:"
+ "_identityDaemonResolveIdentityForSignature:data:typeFlags:error:"
+ "_identityDaemonSessionPairingIdentifier"
+ "_inUseProcessesToString"
+ "_insertBits32:newBits:mask:"
+ "_insertBits64:newBits:mask:"
+ "_isLocalDeviceCommunal"
+ "_linkTypeString"
+ "_localDeviceInfoPassword"
+ "_logRequestMetricsOnLinkType:length:rtt:"
+ "_logSendMetricsForLength:"
+ "_makeIdentityWithPublicKey:identifier:type:"
+ "_osVersionToString:"
+ "_pairingAppFlagsString:"
+ "_peerDeviceInfoSetTransportFlag:"
+ "_registrationID"
+ "_requestIDIsHighVolume:messageIsChatty:"
+ "_saveIdentityWithIDSDeviceID:message:"
+ "_scrubPskData"
+ "_sendFrameBodyImpl:body:"
+ "_sendFrameObjectImpl:unencryptedObject:"
+ "_sendFrameType:bodyObject:"
+ "_sendFrameType:dictionaryObject:"
+ "_sepPrivateKeyOfPairingIdentity:"
+ "_setAppInfoPeer:"
+ "_setCanDecode128bit:"
+ "_setCompanionLinkFlags:"
+ "_setPairingIdentity:sepPrivateKey:"
+ "_setPeerAccountAltDSID:"
+ "_setPeerAccountID:"
+ "_setPeerActiveUserAltDSID:"
+ "_setPeerActivityLevel:"
+ "_setPeerCompanionLinkFlags:"
+ "_setPeerDeviceCapabilityFlags:"
+ "_setPeerDeviceColor:"
+ "_setPeerHomeKitIdentifier:"
+ "_setPeerIDSCorrelationIdentifier:"
+ "_setPeerIDSDeviceIdentifier:"
+ "_setPeerListeningPort:"
+ "_setPeerMediaRemoteIdentifier:"
+ "_setPeerMediaRouteIdentifier:"
+ "_setPeerMediaSystemIdentifier:"
+ "_setPeerMediaSystemName:"
+ "_setPeerMediaSystemRole:"
+ "_setPeerMediaSystemState:"
+ "_setPeerModel:"
+ "_setPeerName:"
+ "_setPeerOperatingSystemVersion:"
+ "_setPeerPublicIdentifier:"
+ "_setPeerRole:"
+ "_setPeerRoomName:"
+ "_setPeerServiceTypes:"
+ "_setPeerSiriInfo:"
+ "_setPeerSourceVersion:"
+ "_setPeerStatusFlags:"
+ "_setPeerVerifiedIdentity:"
+ "_setStatusFlags:"
+ "_signpostBeginClientResponse:requestID:"
+ "_signpostBeginSendRequest:requestID:length:linkType:highPriority:"
+ "_signpostEndClientResponse:length:linkType:highPriority:"
+ "_signpostEndSendRequest:rtt:requestSize:responseSize:"
+ "_signpostEndSendRequestTimeout:"
+ "_sourceVersionString"
+ "_startEventMessageMetrics:length:"
+ "_startReceivingFrames"
+ "_startRequestMessageMetrics:length:"
+ "_startResponseMessageMetrics:"
+ "_startTimeoutSeconds"
+ "_statusFlagsAccessFlagsMask"
+ "_statusFlagsAuthenticatedMask"
+ "_statusFlagsMeDeviceIsMe"
+ "_statusFlagsString"
+ "_statusFlagsSyncedMask"
+ "_stringToOSVersion:"
+ "_submitEventMetrics:length:"
+ "_updateBonjourFlagsOnPeerDevice:"
+ "_updateIdentity:withSEPPrivateKey:"
+ "_updateIdentity:withSecretKey:"
+ "_updateSessionPairedIdentityWithVerifiedIdentity:model:name:"
+ "abortRequestsWithError:"
+ "abortSendEntry:withError:"
+ "activateCalled"
+ "activatedTicks"
+ "buildSystemInfo"
+ "clientConnectCompleted:"
+ "clientConnectStart"
+ "clientConnectStartBLE"
+ "clientConnectStartBTPipe"
+ "clientConnectStartTCP"
+ "clientError:"
+ "clientNetworkError:label:"
+ "clientPairSetupCompleted:"
+ "clientPairSetupStart"
+ "clientPairSetupWithData:"
+ "clientPairVerifyCompleted:"
+ "clientPairVerifyStart"
+ "clientPairVerifyWithData:"
+ "clientPreAuthResponseWithData:"
+ "clientPreAuthStart"
+ "clientRetryFired"
+ "clientRetryStart"
+ "clientRun"
+ "clientStartSession"
+ "clientStarted"
+ "configureForSessionPairing:"
+ "connection"
+ "doubleValue"
+ "highPriorityAuthTagLength"
+ "highPriorityStream"
+ "homeKitIdentityIdentifier"
+ "homeKitIdentitySignature"
+ "i24@0:8@16"
+ "identityKeyData"
+ "identitySignature"
+ "initWithBool:"
+ "initWithDouble:"
+ "initWithInt:"
+ "initWithInteger:"
+ "initWithUnsignedInt:"
+ "initWithUnsignedInteger:"
+ "initWithUnsignedLongLong:"
+ "internalState"
+ "invalidateCalled"
+ "invalidateDone"
+ "isGuest"
+ "mainAuthTagLength"
+ "mainStream"
+ "pairSetupAuthType"
+ "pairSetupInvalidate"
+ "pairSetupSession"
+ "pairVerifyCompleted"
+ "pairVerifyFailed"
+ "pairVerifyIdentityType"
+ "pairVerifyInvalidate"
+ "pairVerifySession"
+ "pairVerifySign:flags:error:"
+ "pairVerifyUsedIdentity"
+ "pairVerifyVerifySignature:data:flags:error:"
+ "peerAddrStr"
+ "peerHKUserID"
+ "pskPrepareWithIsClient:"
+ "receivedEvent:length:moreComing:"
+ "receivedFrameCountCurrent"
+ "receivedFrameCountLast"
+ "receivedObject:length:moreComing:"
+ "receivedRequest:length:moreComing:"
+ "receivedResponse:length:moreComing:"
+ "receivedSystemInfo:xid:"
+ "registrationID"
+ "requestable"
+ "requests"
+ "retryCount"
+ "retryFired"
+ "retryTicks"
+ "selfAddrString"
+ "sendArray"
+ "serverAccept"
+ "serverAcceptBLE"
+ "serverAcceptBTPipe"
+ "serverAcceptTCP"
+ "serverError:"
+ "serverNetworkError:label:"
+ "serverPairSetupCompleted:"
+ "serverPairSetupWithData:start:"
+ "serverPairVerifyCompleted:"
+ "serverPairVerifyWithData:start:"
+ "serverPreAuthRequestWithData:"
+ "serverRun"
+ "serverStarted"
+ "setActivateCalled:"
+ "setActivatedTicks:"
+ "setHighPriorityAuthTagLength:"
+ "setHighPriorityStream:"
+ "setHomeKitIdentityIdentifier:"
+ "setHomeKitIdentitySignature:"
+ "setIdentityKeyData:"
+ "setIdentitySignature:"
+ "setIdentityVerified:"
+ "setInitiator:"
+ "setInternalState:"
+ "setInvalidateCalled:"
+ "setInvalidateDone:"
+ "setMainAuthTagLength:"
+ "setMainStream:"
+ "setPairSetupAuthType:"
+ "setPairSetupSession:"
+ "setPairVerifyAuthType:"
+ "setPairVerifyCompleted:"
+ "setPairVerifyFailed:"
+ "setPairVerifyIdentityType:"
+ "setPairVerifySession:"
+ "setPairVerifyUsedIdentity:"
+ "setPeerAddrStr:"
+ "setPeerHKUserID:"
+ "setReceivedFrameCountCurrent:"
+ "setReceivedFrameCountLast:"
+ "setRegistrationID:"
+ "setRequestable:"
+ "setRequests:"
+ "setRetryCount:"
+ "setRetryFired:"
+ "setRetryTicks:"
+ "setSelfAddrString:"
+ "setSendArray:"
+ "setShowPasswordCalled:"
+ "setStartTimeoutSeconds:"
+ "setStepDone:"
+ "setStepError:"
+ "setValue:forUndefinedKey:"
+ "setXidLast:"
+ "showPasswordCalled"
+ "startTimeoutSeconds"
+ "stepDone"
+ "stepError"
+ "updateExternalState"
+ "updatePairVerifyFlags"
+ "v24@0:8@\"CUReadRequest\"16"
+ "v24@0:8@\"CUWriteRequest\"16"
+ "v32@0:8@16^{__SecKey=}24"
+ "v32@?0@8@16^B24"
+ "v36@0:8@16Q24B32"
+ "v36@0:8I16Q20i28B32"
+ "v44@0:8@16Q24Q32B40"
+ "v44@0:8I16@20Q28i36B40"
+ "v44@0:8I16Q20Q28Q36"
+ "valueForUndefinedKey:"
+ "xidLast"
+ "{?=qqq}24@0:8@16"
- "### Abort queued ID '%@': %{error}\n"
- "### Abort request XID 0x%X: %{error}\n"
- "### Client error: %{error}\n"
- "### Connect failed: %{error}\n"
- "### Failed to get self identity: %@\n."
- "### Ignoring call to send event ID '%@' when invalidating\n"
- "### Ignoring received PreAuthResponse when not expected: %##@\n"
- "### Ignoring response to requestID '%@' from %@ after invalidation\n"
- "### Ignoring send request ID '%@' when invalidating\n"
- "### PSK prepare failed: %{error}\n"
- "### PairSetup client completion failed: %{error}\n"
- "### PairSetup client receive failed: %{error}\n"
- "### PairSetup server completion failed: %s, %{error}\n"
- "### PairSetup server receive failed: %{error}\n"
- "### PairVerify client completion failed: %{error}\n"
- "### PairVerify client failed: %{error}\n"
- "### PairVerify client receive failed: %{error}\n"
- "### PairVerify server completion failed: %s, %{error}\n"
- "### PairVerify server receive failed: %{error}\n"
- "### PairVerifySign failed: %{error}\n"
- "### PairVerifySign get self identity failed: %{error}\n"
- "### PairVerifyVerify failed: %{error}\n"
- "### PreAuthRequest bad type\n"
- "### PreAuthRequest decode failed: %#m\n"
- "### PreAuthResponse bad type\n"
- "### PreAuthResponse decode failed: %#m\n"
- "### Process unsupported request\n"
- "### Received event with no ID from %@: %#m\n"
- "### Received event with no content from %@: %#m\n"
- "### Received request XID 0x%X with no ID from %@: %#m\n"
- "### Received request with no XID from %@: %#m\n"
- "### Received requestID '%@', XID 0x%X with no content from %@: %#m\n"
- "### Received requestID '%@', XID 0x%X, from %@ with no handler\n"
- "### Received response XID 0x%X with no content from %@: %#m\n"
- "### Received response XID 0x%X with no request from %@\n"
- "### Received response XID 0x%X, error %{error}, from %@, %llu ms\n"
- "### Received response with no XID from %@: %#m\n"
- "### Request timeout '%@' not found, %.3f seconds\n"
- "### Request timeout '%@', %.3f seconds\n"
- "### Request timeout XID 0x%X, %.3f seconds\n"
- "### Send %s encode failed: %#m\n"
- "### Send encrypted data (%zu bytes) failed: '%@', %{error}\n"
- "### Send encrypted requestID '%@' failed: %{error}\n"
- "### Send encrypted response XID 0x%X failed: %{error}\n"
- "### Send frame type 0x%X failed: %{error}\n"
- "### Sending response XID 0x%X, error: %{error}\n"
- "### Server error: %{error}\n"
- "### Timeout for XID 0x%X with no request\n"
- "### Unknown message type: %d\n"
- "### Unsupported send attempt\n"
- "(HK)"
- "(RPI-?)"
- "(RPI-AdHocPaired)"
- "(RPI-Family)"
- "(RPI-Friend)"
- "(RPI-Owner)"
- "(RPI-SessionPaired)"
- "(RPI-SharedTVUser)"
- "-[RPConnection _abortRequestsWithError:]_block_invoke"
- "-[RPConnection _clientConnectCompleted:]"
- "-[RPConnection _clientConnectStartBLE]"
- "-[RPConnection _clientConnectStartBLE]_block_invoke_2"
- "-[RPConnection _clientConnectStartTCP]_block_invoke_3"
- "-[RPConnection _clientConnectStart]"
- "-[RPConnection _clientError:]"
- "-[RPConnection _clientPairSetupCompleted:]"
- "-[RPConnection _clientPairSetupStart]"
- "-[RPConnection _clientPairSetupWithData:]"
- "-[RPConnection _clientPairVerifyCompleted:]"
- "-[RPConnection _clientPairVerifyStart]"
- "-[RPConnection _clientPairVerifyWithData:]"
- "-[RPConnection _clientPreAuthResponseWithData:]"
- "-[RPConnection _clientPreAuthStart]"
- "-[RPConnection _clientRetryFired]"
- "-[RPConnection _clientRetryStart]"
- "-[RPConnection _clientRun]"
- "-[RPConnection _clientStartSession]"
- "-[RPConnection _configureForSessionPairing:]"
- "-[RPConnection _configureForSessionPairing:]_block_invoke"
- "-[RPConnection _configureForSessionPairing:]_block_invoke_2"
- "-[RPConnection _configureForSessionPairing:]_block_invoke_3"
- "-[RPConnection _pairVerifySignData:flags:error:]"
- "-[RPConnection _pairVerifyVerifySignature:data:flags:error:]"
- "-[RPConnection _processSends]"
- "-[RPConnection _pskPrepare:]"
- "-[RPConnection _receivedEvent:ctx:]"
- "-[RPConnection _receivedObject:ctx:]"
- "-[RPConnection _receivedRequest:ctx:]"
- "-[RPConnection _receivedRequest:ctx:]_block_invoke"
- "-[RPConnection _receivedResponse:ctx:]"
- "-[RPConnection _receivedSystemInfo:xid:]"
- "-[RPConnection _receivedSystemInfo:xid:]_block_invoke"
- "-[RPConnection _sendEncryptedEventID:data:xid:options:completion:]"
- "-[RPConnection _sendEncryptedRequestID:request:xpcID:options:sendEntry:responseHandler:]"
- "-[RPConnection _sendEncryptedResponse:options:error:xid:requestID:highPriority:isChatty:replyStartTime:]"
- "-[RPConnection _sendFrameType:body:]"
- "-[RPConnection _sendFrameType:unencryptedObject:]"
- "-[RPConnection _serverAcceptBLE]_block_invoke_2"
- "-[RPConnection _serverAcceptBTPipe]"
- "-[RPConnection _serverAcceptTCP]_block_invoke_3"
- "-[RPConnection _serverError:]"
- "-[RPConnection _serverPairSetupCompleted:]"
- "-[RPConnection _serverPairSetupWithData:start:]"
- "-[RPConnection _serverPairVerifyCompleted:]"
- "-[RPConnection _serverPairVerifyWithData:start:]"
- "-[RPConnection _serverPreAuthRequestWithData:]"
- "-[RPConnection _serverRun]"
- "-[RPConnection _systeminfo]"
- "-[RPConnection _timeoutForSendEntry:]"
- "-[RPConnection _timeoutForXID:]"
- "-[RPConnection _updateExternalState]"
- "-[RPConnection processSendsUsingConnection:]"
- "-[RPConnection sendEncryptedEventID:data:xid:options:completion:]"
- "-[RPConnection sendEncryptedRequestID:request:xpcID:options:responseHandler:]"
- "-[RPConnection sendReachabilityProbe:]"
- "/Library/Caches/com.apple.xbs/Sources/Rapport/Rapport/RPIRKRatchet.swift"
- "/Library/Caches/com.apple.xbs/Sources/Rapport/Rapport/Swift/RPUtilities.swift"
- "@\"<CUReadWriteRequestable>\""
- "@\"CUPairingSession\""
- "@\"CUPairingStream\""
- "AirPlay restrictions ignored\n"
- "BLE client connection invalidated\n"
- "BLE client connection with bundleID: %@ and clientUseCase: %@\n"
- "BLE server connection invalidated\n"
- "Backwards compatibility authType (%s) -> (%s)"
- "Backwards compatibility change authType (%s) -> (%s)"
- "Bad PairSetup request object type %@"
- "Bad PairVerify request object type %@"
- "Client PairSetup retry\n"
- "Client connect start: %@\n"
- "Client error"
- "Client immediate non-RPIdentity retry\n"
- "Client state: %s -> %s\n"
- "Configuring for session pairing\n"
- "Connect failed"
- "Enabling FitnessPairing \n"
- "External state changed: %s -> %s\n"
- "Find paired peer handler for peer %@ options %lu\n"
- "Frame too big (%zu vs %u)"
- "In use processes updated to: %@\n"
- "No PairSetup client session"
- "No PairVerify client session"
- "OnDemand connection failed, invalidating\n"
- "PairSetup completed client.\n"
- "PairSetup completed server: %s\n"
- "PairSetup next (%d bytes)\n"
- "PairSetup response error: '%@'"
- "PairSetup server rejecting when not allowed\n"
- "PairSetup server rejecting when not allowing non-Home devices\n"
- "PairVerify completed client %s, %#{flags}, %#ll{flags}, RPI %@\n"
- "PairVerify completed server: %s, %#{flags}, %#ll{flags}, RPI %@\n"
- "PairVerify next (%d bytes)\n"
- "PairVerify start client: AT %s, CF %#ll{flags}, FL %#{flags}, PWT %s\n"
- "PairVerifySign success: CF %#ll{flags}, AF %#ll{flags}\n"
- "PairVerifySign: Not using RPI: CF %#ll{flags}, AF %#ll{flags}\n"
- "PairVerifyVerify success: %s, CF %#ll{flags}, AF %#ll{flags}\n"
- "PairVerifyVerify: Not using RPI: CF %#ll{flags}, AF %#ll{flags}\n"
- "Peer appears missing, invalidating\n"
- "Peer appears present, retrying\n"
- "Peer is blocking access, invalidating\n"
- "Peer may be unreachable, sending reachability probe (%s)\n"
- "Peer missing after retry timer, invalidating\n"
- "Queuing send event ID '%@', XID 0x%X (%d send(s) pending)\n"
- "Queuing send request ID '%@' (%d send(s) pending)\n"
- "Received PreAuthRequest: %##@\n"
- "Received PreAuthResponse: %##@\n"
- "Received SharedHome identity: ID '%.8@'\n"
- "Received client service type %@\n"
- "Received event ID '%@', XID 0x%X, %d keys, from %@\n"
- "Received identity from IDS '%.8@'\n"
- "Received requestID '%@', XID 0x%X, %d keys, from %@\n"
- "Received response XID 0x%X, %d keys, from %@, %llu ms request size %llu response size %llu\n"
- "Requested password type: %s auth type: %s\n"
- "Retrying delayed: %.3f seconds\n"
- "Retrying immediately: %{dur} since last retry\n"
- "Retrying immediately: first retry\n"
- "Save paired peer handler for peer %@ options %lu\n"
- "Send PreAuthRequest: %##@\n"
- "Send PreAuthResponse: %##@\n"
- "Send SharedHome identity\n"
- "Send encrypted event failed: '%@', %{error}\n"
- "Send encrypted requestID '%@' failed: %{error}\n"
- "Send frame 0x%02X (%s), <%.16@> (%zu bytes)\n"
- "Send identity\n"
- "Send request ID '%@', XID 0x%X, <%.16@> (%zu bytes) on link type %s %s\n"
- "Send response XID 0x%X, <%.16@> (%zu bytes) on link type %s%s, %#m\n"
- "SendEventID '%@', XID 0x%X, <%.16@> (%zu bytes) on link type %s %s\n"
- "Sending client service type %@\n"
- "Server state: %s -> %s\n"
- "T@\"NSString\",R,N,V_peerAddrString"
- "T@\"NSString\",R,N,V_peerHomeKitUserIdentifier"
- "T@\"RPIdentity\",R,N,V_identityVerified"
- "TCP client connection invalidated\n"
- "TCP server connection invalidated\n"
- "Ti,R,N,V_pairVerifyAuthType"
- "Too many retries, invalidating: retries %d, %@\n"
- "Transferring event ID %@ to connection %@"
- "Transferring request ID %@ to connection %@ with timeout %f\n"
- "_aaltDSID"
- "_accAltDSID"
- "_accID"
- "_actLvl"
- "_activatedTicks"
- "_appInfo"
- "_auTy"
- "_bf"
- "_btHP"
- "_c"
- "_cf"
- "_cht"
- "_clFl"
- "_clSrv"
- "_dC"
- "_dCapF"
- "_forcedRole"
- "_highPriorityAuthTagLength"
- "_hkID"
- "_hkUID"
- "_homeKitIdentityIdentifier"
- "_homeKitIdentitySignature"
- "_identityKeyData"
- "_identitySignature"
- "_identityVerified"
- "_idsCID"
- "_inUseProc"
- "_lP"
- "_mRtID"
- "_mainAuthTagLength"
- "_mrID"
- "_msId"
- "_msNm"
- "_msRo"
- "_msSt"
- "_osV"
- "_pairSetupAuthType"
- "_pairVerifyIdentityType"
- "_pairVerifyUsedIdentity"
- "_pd"
- "_peerAddrString"
- "_peerHomeKitUserIdentifier"
- "_ping"
- "_pubID"
- "_pwTy"
- "_rT"
- "_receivedFrameCountCurrent"
- "_receivedFrameCountLast"
- "_requestable"
- "_retryFired"
- "_retryTicks"
- "_selfAddrString"
- "_sf"
- "_stA"
- "_sv"
- "_t"
- "_x"
- "com.apple.admin"
- "dictionaryWithObjectsAndKeys:"
- "hipri"
- "ids-message"
- "main"
- "public"
- "v32@?0@\"NSNumber\"8@\"RPRequestEntry\"16^B24"
```
