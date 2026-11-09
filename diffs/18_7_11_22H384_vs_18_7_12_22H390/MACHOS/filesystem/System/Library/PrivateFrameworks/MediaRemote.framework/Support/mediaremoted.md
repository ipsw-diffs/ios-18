## mediaremoted

> `/System/Library/PrivateFrameworks/MediaRemote.framework/Support/mediaremoted`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_doubleobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-4024.700.3.1.0
-  __TEXT.__text: 0x33f560
-  __TEXT.__auth_stubs: 0x54e0
-  __TEXT.__objc_stubs: 0x22aa0
-  __TEXT.__objc_methlist: 0x13814
-  __TEXT.__objc_methname: 0x37621
+4024.700.3.2.0
+  __TEXT.__text: 0x340280
+  __TEXT.__auth_stubs: 0x5500
+  __TEXT.__objc_stubs: 0x22ae0
+  __TEXT.__objc_methlist: 0x1382c
+  __TEXT.__objc_methname: 0x37658
   __TEXT.__cstring: 0x1b163
   __TEXT.__objc_classname: 0x2afa
   __TEXT.__objc_methtype: 0x695d
   __TEXT.__const: 0x87ea
   __TEXT.__gcc_except_tab: 0x60b8
-  __TEXT.__oslogstring: 0x1dc48
+  __TEXT.__oslogstring: 0x1dee8
   __TEXT.__dlopen_cstrs: 0x9a
   __TEXT.__swift5_typeref: 0x3b82
   __TEXT.__swift5_capture: 0x4758

   __TEXT.__swift_as_entry: 0x190
   __TEXT.__swift_as_ret: 0x1c0
   __TEXT.__swift5_assocty: 0x3e0
-  __TEXT.__unwind_info: 0xa5b8
+  __TEXT.__unwind_info: 0xa5e8
   __TEXT.__eh_frame: 0x5974
-  __DATA_CONST.__auth_got: 0x2a80
+  __DATA_CONST.__auth_got: 0x2a90
   __DATA_CONST.__got: 0x2728
   __DATA_CONST.__auth_ptr: 0xb98
-  __DATA_CONST.__const: 0x18a48
+  __DATA_CONST.__const: 0x18ac0
   __DATA_CONST.__cfstring: 0xcb40
   __DATA_CONST.__objc_classlist: 0x920
   __DATA_CONST.__objc_catlist: 0x70

   __DATA_CONST.__objc_arrayobj: 0x150
   __DATA_CONST.__objc_doubleobj: 0x50
   __DATA.__objc_const: 0x22e28
-  __DATA.__objc_selrefs: 0xb0b0
+  __DATA.__objc_selrefs: 0xb0c0
   __DATA.__objc_ivar: 0x15ec
   __DATA.__objc_data: 0x7f50
   __DATA.__data: 0x8dd0

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 14738
-  Symbols:   2900
-  CStrings:  13502
+  Functions: 14757
+  Symbols:   2902
+  CStrings:  13512
 
Symbols:
+ _SBSGetScreenLockStatus
+ _SBSRequestPasscodeUnlockAlertUI
CStrings:
+ "[AVRoutingServer] Cancelling authorization request for route %{public}@ because device is locked."
+ "[AVRoutingServer] Device is locked, requesting passcode unlock."
+ "[AVRoutingServer] Device locked after password entry for route %{public}@, requesting unlock again."
+ "[AVRoutingServer] Device locked. Skipping Keychain passcode storage for route: %{public}@"
+ "[AVRoutingServer] Skipping password dialog for route %{public}@ because device is locked."
+ "[AVRoutingServer] User declined to unlock after password entry, cancelling authorization request for route %{public}@."
+ "[AVRoutingServer] User declined to unlock after password entry, skipping route pick for route %{public}@."
+ "_ensureDeviceUnlockedWithCompletion:"
+ "_isDeviceUnlocked"
+ "v12@?0C8"
```
