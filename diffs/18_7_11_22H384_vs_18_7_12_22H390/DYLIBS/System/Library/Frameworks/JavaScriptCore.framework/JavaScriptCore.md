## JavaScriptCore

> `/System/Library/Frameworks/JavaScriptCore.framework/JavaScriptCore`

```diff

-621.10.1.10.5
-  __TEXT.__text: 0x19e8a0c
+621.10.1.10.6
+  __TEXT.__text: 0x19e8c3c
   __TEXT.__jsc_int: 0x5922c
   __TEXT.__auth_stubs: 0x2f50
   __TEXT.__objc_methlist: 0xb9c
   __TEXT.__const: 0x84c08
   __TEXT.__dlsym_cstr: 0x34
-  __TEXT.__cstring: 0x10b2e6
+  __TEXT.__cstring: 0x10b395
   __TEXT.__oslogstring: 0x9e5
-  __TEXT.__gcc_except_tab: 0x27b8
-  __TEXT.__unwind_info: 0x2578
+  __TEXT.__gcc_except_tab: 0x27cc
+  __TEXT.__unwind_info: 0x2730
   __TEXT.__eh_frame: 0x48
   __TEXT.__objc_classname: 0xee
   __TEXT.__objc_methname: 0x1e4f

   __DATA_DIRTY.__data: 0x14820
   __DATA_DIRTY.__wtf_config: 0x4000
   __DATA_DIRTY.__common: 0x4afc
-  __DATA_DIRTY.__bss: 0x3220
+  __DATA_DIRTY.__bss: 0x3230
   - /System/Library/Frameworks/BrowserEngineCore.framework/BrowserEngineCore
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Foundation

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libicucore.A.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 37900
-  Symbols:   46768
-  CStrings:  20897
+  Functions: 37902
+  Symbols:   46771
+  CStrings:  20899
 
Symbols:
+ GCC_except_table125
+ __ZN3JSC22StructureMemoryManager44computePreferredStructureHeapReservationSizeEv
+ __ZNSt3__117__call_once_proxyB8sn190102INS_5tupleIJOZN3JSC22StructureMemoryManager44computePreferredStructureHeapReservationSizeEvE3$_0EEEEEvPv
Functions:
~ __ZN3JSC31StructureAlignedMemoryAllocator24tryAllocateAlignedMemoryEmm : 668 -> 688
+ __ZN3JSC22StructureMemoryManager44computePreferredStructureHeapReservationSizeEv
~ __ZN3JSC22StructureMemoryManagerC2Ev : 1560 -> 1632
+ __ZNSt3__117__call_once_proxyB8sn190102INS_5tupleIJOZN3JSC22StructureMemoryManager44computePreferredStructureHeapReservationSizeEvE3$_0EEEEEvPv
~ __ZN3WTF9HashTableINSt3__14pairINS_6RefPtrINS_29ThreadSafeWeakPtrControlBlockENS_12RawPtrTraitsIS4_EENS_43ThreadSafeWeakPtrControlBlockRefDerefTraitsEEEPKN3JSC4Wasm14InstanceAnchorEEESE_NS_17IdentityExtractorENS_11DefaultHashISE_EENS_10HashTraitsISE_EESJ_NS_10FastMallocEE17lookupForReinsertERKSE_ : 208 -> 220
~ __ZN3WTF4Xsum16LargeAccumulator19largeAddValueInfNanEsy : 408 -> 360
CStrings:
+ "auto JSC::StructureMemoryManager::computePreferredStructureHeapReservationSize()::(anonymous class)::operator()() const"
+ "com.apple.developer.kernel.extended-virtual-addressing"
```
