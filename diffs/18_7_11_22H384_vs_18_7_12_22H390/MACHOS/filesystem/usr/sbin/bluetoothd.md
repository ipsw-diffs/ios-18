## bluetoothd

> `/usr/sbin/bluetoothd`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-186.4.1.2.0
-  __TEXT.__text: 0x7c73fc
+186.4.1.3.0
+  __TEXT.__text: 0x7c740c
   __TEXT.__auth_stubs: 0x4620
   __TEXT.__objc_stubs: 0x13140
   __TEXT.__init_offsets: 0x54
   __TEXT.__objc_methlist: 0x655c
   __TEXT.__const: 0xa77c
   __TEXT.__gcc_except_tab: 0x61ab4
-  __TEXT.__cstring: 0xa30c0
+  __TEXT.__cstring: 0xa3e88
   __TEXT.__objc_classname: 0x7eb
   __TEXT.__objc_methname: 0x15ebb
   __TEXT.__objc_methtype: 0x44e7
Functions:
~ sub_1005251c8 : 840 -> 852
~ sub_100526814 -> sub_100526820 : 288 -> 292
CStrings:
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Daemon/Server/XpcClassicConnection.mm"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Server/Chipsets/LEHardwareModel.cpp"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Server/Platforms/Darwin/BT_DataElements.cpp"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Server/Platforms/Darwin/DeviceSettings.mm"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Server/Platforms/Darwin/VirtualController/BTVirtualHciCommandChannel.mm"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Server/Platforms/Darwin/VirtualController/BTVirtualHciPacket.mm"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Server/Platforms/Darwin/VirtualController/include/BTVirtualHciPacket.h"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Server/a2dp/A2DPClient.cpp"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Server/aacp/AACPClient.mm"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Server/core/Device.mm"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Server/core/FastConnectManager.mm"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Server/core/LocalDevice.mm"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Stack/Platforms/Darwin/applebt_transport.c"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Stack/Platforms/Darwin/hcilite_filter.c"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Stack/Platforms/Darwin/pcie_mempool.c"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Stack/corestack/cl/BT_CL_Signaling.c"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Stack/corestack/cl/BT_TS_Switching.c"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Stack/corestack/dataelem/marshaller.c"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Stack/corestack/hci/hcicmdapi.c"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Stack/corestack/hci/hcievents.c"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Stack/corestack/hci/hciflow.c"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Stack/corestack/hci/hciparmcache.c"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Stack/corestack/l2cap/chanman.c"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Stack/corestack/l2cap/group.c"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Stack/corestack/l2cap/signalman.c"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Stack/corestack/le/LEA.c"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Stack/corestack/le/LE_Events.c"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Stack/corestack/magicPairing/BT_MagicPairing.c"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Stack/corestack/sdp/sdp.c"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Stack/corestack/sdp/sdpdb.c"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Stack/corestack/sdp/sdpserver.c"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Stack/corestack/support/oi_bytestream.c"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Stack/corestack/support/oi_mbuf.c"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Stack/corestack/support/oi_varstring.c"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Stack/profiles/aacp/aacp_client.c"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Stack/profiles/aap/aap_client.c"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Stack/profiles/av/avctp/avctp.c"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Stack/profiles/av/avdtp/avdtp.c"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Stack/profiles/av/avdtp/avdtp_signal.c"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Stack/profiles/av/avrcp/avrcp_helper.c"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Stack/profiles/av/avrcp/avrcp_metadata.c"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Stack/profiles/bip/oi_bip_private.c"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Stack/profiles/bnep/bnep.c"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Stack/profiles/bnep/bnep_msg.c"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Stack/profiles/map/map_server.c"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Stack/profiles/obex/obexcli_common.c"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Stack/profiles/obex/obexcommon.c"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Stack/profiles/obex/obexsrv_common.c"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Stack/profiles/pan/pan_gn.c"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Stack/profiles/pan/pan_user.c"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Stack/profiles/pbap/pbap_server.c"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Stack/vsc/aci/aci_vsc.c"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Stack/vsc/bcm/bcm_vsc.c"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Stack/vsc/srs/srs_vsc.c"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Stack/vsc/vsc.c"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MobileBluetooth_base/Stack/vsc/vse.c"
+ "21:44:47"
+ "Nov  2 2026"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Daemon/Server/XpcClassicConnection.mm"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Server/Chipsets/LEHardwareModel.cpp"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Server/Platforms/Darwin/BT_DataElements.cpp"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Server/Platforms/Darwin/DeviceSettings.mm"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Server/Platforms/Darwin/VirtualController/BTVirtualHciCommandChannel.mm"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Server/Platforms/Darwin/VirtualController/BTVirtualHciPacket.mm"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Server/Platforms/Darwin/VirtualController/include/BTVirtualHciPacket.h"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Server/a2dp/A2DPClient.cpp"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Server/aacp/AACPClient.mm"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Server/core/Device.mm"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Server/core/FastConnectManager.mm"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Server/core/LocalDevice.mm"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Stack/Platforms/Darwin/applebt_transport.c"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Stack/Platforms/Darwin/hcilite_filter.c"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Stack/Platforms/Darwin/pcie_mempool.c"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Stack/corestack/cl/BT_CL_Signaling.c"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Stack/corestack/cl/BT_TS_Switching.c"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Stack/corestack/dataelem/marshaller.c"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Stack/corestack/hci/hcicmdapi.c"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Stack/corestack/hci/hcievents.c"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Stack/corestack/hci/hciflow.c"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Stack/corestack/hci/hciparmcache.c"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Stack/corestack/l2cap/chanman.c"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Stack/corestack/l2cap/group.c"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Stack/corestack/l2cap/signalman.c"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Stack/corestack/le/LEA.c"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Stack/corestack/le/LE_Events.c"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Stack/corestack/magicPairing/BT_MagicPairing.c"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Stack/corestack/sdp/sdp.c"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Stack/corestack/sdp/sdpdb.c"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Stack/corestack/sdp/sdpserver.c"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Stack/corestack/support/oi_bytestream.c"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Stack/corestack/support/oi_mbuf.c"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Stack/corestack/support/oi_varstring.c"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Stack/profiles/aacp/aacp_client.c"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Stack/profiles/aap/aap_client.c"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Stack/profiles/av/avctp/avctp.c"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Stack/profiles/av/avdtp/avdtp.c"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Stack/profiles/av/avdtp/avdtp_signal.c"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Stack/profiles/av/avrcp/avrcp_helper.c"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Stack/profiles/av/avrcp/avrcp_metadata.c"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Stack/profiles/bip/oi_bip_private.c"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Stack/profiles/bnep/bnep.c"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Stack/profiles/bnep/bnep_msg.c"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Stack/profiles/map/map_server.c"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Stack/profiles/obex/obexcli_common.c"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Stack/profiles/obex/obexcommon.c"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Stack/profiles/obex/obexsrv_common.c"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Stack/profiles/pan/pan_gn.c"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Stack/profiles/pan/pan_user.c"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Stack/profiles/pbap/pbap_server.c"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Stack/vsc/aci/aci_vsc.c"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Stack/vsc/bcm/bcm_vsc.c"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Stack/vsc/srs/srs_vsc.c"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Stack/vsc/vsc.c"
- "/Library/Caches/com.apple.xbs/Sources/MobileBluetooth_base/Stack/vsc/vse.c"
- "18:55:22"
- "Jul 24 2026"
```
