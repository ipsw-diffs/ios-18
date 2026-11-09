## AirPlayReceiver

> `/System/Library/PrivateFrameworks/AirPlayReceiver.framework/AirPlayReceiver`

```diff

-870.14.1.0.0
-  __TEXT.__text: 0x147b70
+870.14.21.1.0
+  __TEXT.__text: 0x147c10
   __TEXT.__auth_stubs: 0x36e0
   __TEXT.__objc_methlist: 0xa94
   __TEXT.__const: 0x322d5
   __TEXT.__dlopen_cstrs: 0xad
   __TEXT.__gcc_except_tab: 0x7bc
-  __TEXT.__cstring: 0x2cea1
-  __TEXT.__unwind_info: 0x16e8
+  __TEXT.__cstring: 0x2cef0
+  __TEXT.__unwind_info: 0x16f0
   __TEXT.__eh_frame: 0x1b28
   __TEXT.__objc_classname: 0x144
   __TEXT.__objc_methname: 0x2653

   __DATA_CONST.__objc_arraydata: 0x10
   __AUTH_CONST.__auth_got: 0x1b80
   __AUTH_CONST.__const: 0xadc8
-  __AUTH_CONST.__cfstring: 0xa740
+  __AUTH_CONST.__cfstring: 0xa760
   __AUTH_CONST.__objc_const: 0x14f0
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH.__objc_data: 0x370

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1564
-  Symbols:   3562
-  CStrings:  5219
+  Functions: 1565
+  Symbols:   3563
+  CStrings:  5222
 
Symbols:
+ GCC_except_table1020
+ GCC_except_table1039
+ GCC_except_table1090
+ GCC_except_table1094
+ GCC_except_table1147
+ GCC_except_table1155
+ GCC_except_table1157
+ _airplayReqProcessor_ensurePairingServices
- GCC_except_table1019
- GCC_except_table1038
- GCC_except_table1089
- GCC_except_table1093
- GCC_except_table1146
- GCC_except_table1154
- GCC_except_table1156
CStrings:
+ "870.14.21.1"
+ "CoreUtils"
+ "OSStatus airplayReqProcessor_ensurePairingServices(APReceiverRequestProcessorRef, Boolean, APSTransportMessageProcessingStatus *)"
+ "OSStatus coreUtilsPairing_HandleSetup(APPairingServicesRef, CFStringRef, CFDataRef, CFDataRef *, Boolean *)"
+ "[%{ptr}] Created %s pairing services [%{ptr}]\n"
+ "airplayReqProcessor_ensurePairingServices"
+ "disablePairSetupThrottling"
+ "legacy"
- "870.14.1"
- "OSStatus coreUtilsPairing_HandleSetup(APPairingServicesRef, CFStringRef, APSecurityMode, CFDataRef, CFDataRef *, Boolean *)"
- "[%{ptr}] Created legacy pairing services [%{ptr}]\n"
- "[%{ptr}] Created pairing services [%{ptr}] for pair-setup.\n"
- "[%{ptr}] Created pairing services [%{ptr}] for pair-verify\n"
```
