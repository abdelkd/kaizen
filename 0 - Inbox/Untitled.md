1. 4.19.127-perf-g7288046673d5. it is android 13 and Lineage Version: 20-20231105-UNOFFICIAL-blossom
2. Output: Bluetooth Status
  enabled: true
  state: ON
  address: 00:C3:0A:36:F3:FF
  name: Redmi 10A
  time since enabled: 00:30:37.740

Enable log:
  05-08 13:49:04  Enabled  due to SYSTEM_BOOT by android
  05-08 17:08:45 Disabled  due to APPLICATION_REQUEST by com.android.systemui
  05-08 17:08:47  Enabled  due to APPLICATION_REQUEST by com.android.systemui

Bluetooth crashed 0 times

0 BLE apps registered

BluetoothManagerService:
  mEnable:true
  mQuietEnable:false
  mEnableExternal:true
  mQuietEnableExternal:false


AdapterProperties
  Name: Redmi 10A
  Address: 00:C3:0A:36:F3:FF
  BluetoothClass: null
  ScanMode: SCAN_MODE_CONNECTABLE
  ConnectionState: STATE_DISCONNECTED
  State: ON
  MaxConnectedAudioDevices: 5
  A2dpOffloadEnabled: false
  Discovering: false
  DiscoveryEndMs: 0
  Bonded devices:
    41:42:B2:14:0C:C4 [ DUAL ] AirPods Pro

  Scan Mode Changes:
    05-08 17:08:49.049 (uid/pid=1002/18888) SCAN_MODE_CONNECTABLE
mSnoopLogSettingAtEnable = empty
mDefaultSnoopLogSettingAtEnable = null

Enabled Profile Services:
  A2dpService
  AvrcpTargetService
  BatteryService
  HeadsetService
  HidDeviceService
  HidHostService
  GattService
  BluetoothMapService
  BluetoothOppService
  PanService
  BluetoothPbapService
  SapService

AdapterState:
 total records=4
 rec[0]: time=05-08 17:08:48.135 processed=OffState org=OffState dest=TurningBleOnState what=3(0x3) BLE_TURN_ON
 rec[1]: time=05-08 17:08:48.422 processed=TurningBleOnState org=TurningBleOnState dest=BleOnState what=7(0x7) BLE_STARTED
 rec[2]: time=05-08 17:08:48.440 processed=BleOnState org=BleOnState dest=TurningOnState what=1(0x1) USER_TURN_ON
 rec[3]: time=05-08 17:08:49.055 processed=TurningOnState org=TurningOnState dest=OnState what=5(0x5) BREDR_STARTED
curState=OnState

SilenceDeviceManager:
  Address            | Is silenced?

BluetoothDatabase:
  Metadata Changes:

Metadata:
    XX:XX:XX:14:0C:C4 last_active_time=3 {profile connection policy(A2DP=100|A2DP_SINK=-1|CSIP_SET_COORDINATOR=-1|HEADSET=100|HEADSET_CLIENT=-1|HID_HOST=-1|PAN=-1|PBAP=-1|PBAP_CLIENT=-1|MAP=-1|MAP_CLIENT=-1|SAP=-1|HAP=-1|HEARING_AID=-1|LE_AUDIO=-1|VOLUME_CONTROL=-1|LE_CALL_CONTROL=-1|LE_BROADCAST_ASSISTANT=-1|BATTERY=-1), optional codec(support=1|enabled=1), custom metadata(manufacturer_name=null|model_name=null|software_version=null|hardware_version=null|companion_app=null|main_icon=null|is_untethered_headset=null|untethered_left_icon=null|untethered_right_icon=null|untethered_case_icon=null|untethered_left_battery=null|untethered_right_battery=null|untethered_case_battery=null|untethered_left_charging=null|untethered_right_charging=null|untethered_case_charging=null|enhanced_settings_ui_uri=null|device_type=null|main_battery=null|main_charging=null|main_low_battery_threshold=null|untethered_left_low_battery_threshold=null|untethered_right_low_battery_threshold=null|untethered_case_low_battery_threshold=null|spatial_audio=null|fastpair_customized=null|le_audio=null|gmcs_cccd=null|gtbs_cccd=null), hfp client audio policy(callEstablishAudioPolicy=0|connectingTimeAudioPolicy=0|inBandRingtoneAudioPolicy=0)}

Profile: GattService
  mAdvertisingServiceUuids:
  mMaxScanFilters: 0

Registered App
  Scanner:
      app_if: 1, appName: com.google.uid.shared:10100
      app_if: 3, appName: com.google.uid.shared:10100
      app_if: 2, appName: com.google.uid.shared:10100
  Client:
  Server:


GATT Scanner Map
  Entries: 1

  com.google.uid.shared:10100 (Registered)
  LE scans (started/stopped)                                  : 22 / 19
  Scan time in ms (active/suspend/total)                      : 3473152 / 0 / 3473152
  Scan time with mode in ms (Opp/LowPower/Balanced/LowLatency/AmbientDiscovery):0 / 0 / 1202290 / 0 / 1891810
  Scan mode counter (Opp/LowPower/Balanced/LowLatency/AmbientDiscovery):0 / 0 / 14 / 0 / 379060
  Score                                                       : 678934
  Total number of results                                     : 0
  Last 5 scans                                                :
    05-08 17:26:57 - 76108ms Filter 0 results (3) CB Regular Scan
      └ Scan Config: [ ScanMode=AMBIENT_DISCOVERY, callbackType=ALL_MATCHES ]
      └ BluetoothLeScanFilter [ ServiceUuid=0000fef3-0000-1000-8000-00805f9b34fb ]
      └ BluetoothLeScanFilter [ ServiceDataUuid=0000fef3-0000-1000-8000-00805f9b34fb ServiceData=[0] ServiceDataMask=[0] ]
    05-08 17:29:01 - 2963ms Filter 0 results (1) CB Regular Scan
      └ Scan Config: [ ScanMode=BALANCED, callbackType=ALL_MATCHES ]
      └ BluetoothLeScanFilter [ ServiceDataUuid=0000feaa-0000-1000-8000-00805f9b34fb ServiceData=[64] ServiceDataMask=[-16] ]
      └ BluetoothLeScanFilter [ ServiceDataUuid=0000fff6-0000-1000-8000-00805f9b34fb ServiceData=[0] ServiceDataMask=[0] ]
      └ BluetoothLeScanFilter [ ServiceDataUuid=0000fe2c-0000-1000-8000-00805f9b34fb ServiceData=[0] ServiceDataMask=[0] ]
    05-08 17:32:02 - 1899ms Filter 0 results (1) CB Regular Scan
      └ Scan Config: [ ScanMode=BALANCED, callbackType=ALL_MATCHES ]
      └ BluetoothLeScanFilter [ ServiceDataUuid=0000feaa-0000-1000-8000-00805f9b34fb ServiceData=[64] ServiceDataMask=[-16] ]
      └ BluetoothLeScanFilter [ ServiceDataUuid=0000fff6-0000-1000-8000-00805f9b34fb ServiceData=[0] ServiceDataMask=[0] ]
      └ BluetoothLeScanFilter [ ServiceDataUuid=0000fe2c-0000-1000-8000-00805f9b34fb ServiceData=[0] ServiceDataMask=[0] ]
    05-08 17:32:52 - 3046ms Filter 0 results (1) CB Regular Scan
      └ Scan Config: [ ScanMode=BALANCED, callbackType=ALL_MATCHES ]
      └ BluetoothLeScanFilter [ ServiceDataUuid=0000feaa-0000-1000-8000-00805f9b34fb ServiceData=[64] ServiceDataMask=[-16] ]
      └ BluetoothLeScanFilter [ ServiceDataUuid=0000fff6-0000-1000-8000-00805f9b34fb ServiceData=[0] ServiceDataMask=[0] ]
      └ BluetoothLeScanFilter [ ServiceDataUuid=0000fe2c-0000-1000-8000-00805f9b34fb ServiceData=[0] ServiceDataMask=[0] ]
    05-08 17:36:12 - 6063ms Filter 0 results (2) CB Regular Scan
      └ Scan Config: [ ScanMode=BALANCED, callbackType=ALL_MATCHES ]
      └ BluetoothLeScanFilter [ ServiceDataUuid=0000fe2c-0000-1000-8000-00805f9b34fb ServiceData=[-4, 18, -114] ]
      └ BluetoothLeScanFilter [ ServiceUuid=0000fe2c-0000-1000-8000-00805f9b34fb ]
  Ongoing scans                                               :
    05-08 17:36:11 - 193595ms Filter 0 results (1) CB Regular Scan
      └ Scan Config: [ ScanMode=BALANCED, callbackType=ALL_MATCHES ]
      └ BluetoothLeScanFilter [ ServiceDataUuid=0000feaa-0000-1000-8000-00805f9b34fb ServiceData=[64] ServiceDataMask=[-16] ]
      └ BluetoothLeScanFilter [ ServiceDataUuid=0000fff6-0000-1000-8000-00805f9b34fb ServiceData=[0] ServiceDataMask=[0] ]
      └ BluetoothLeScanFilter [ ServiceDataUuid=0000fe2c-0000-1000-8000-00805f9b34fb ServiceData=[0] ServiceDataMask=[0] ]
    05-08 17:36:18 - 186533ms Filter 0 results (2) CB Regular Scan
      └ Scan Config: [ ScanMode=AMBIENT_DISCOVERY, callbackType=ALL_MATCHES ]
      └ BluetoothLeScanFilter [ ServiceDataUuid=0000fe2c-0000-1000-8000-00805f9b34fb ServiceData=[-4, 18, -114] ]
      └ BluetoothLeScanFilter [ ServiceUuid=0000fe2c-0000-1000-8000-00805f9b34fb ]
    05-08 17:36:12 - 192519ms Filter 0 results (3) CB Regular Scan
      └ Scan Config: [ ScanMode=AMBIENT_DISCOVERY, callbackType=ALL_MATCHES ]
      └ BluetoothLeScanFilter [ ServiceUuid=0000fef3-0000-1000-8000-00805f9b34fb ]
      └ BluetoothLeScanFilter [ ServiceDataUuid=0000fef3-0000-1000-8000-00805f9b34fb ServiceData=[0] ServiceDataMask=[0] ]
  Application ID                     : 1
  UUID                               : 13e08566-b3ac-4f2c-9941-026418d9d384
  Connections: 0

GATT Advertiser Map

  last 5 advertising:
    com.google.uid.shared:10100
     Advertising ID                                     : 0
      1:
        └Start time                                     : 05-08 17:26:57
        └Stop time                                      : 05-08 17:26:59
        └Duration(10ms unit)                            : 0
        └Maximum number of extended advertising events  : 0
      └Advertising:
        └Interval(0.625ms)                              : 160
        └TX POWER(dbm)                                  : -7
        └Primary Phy                                    : LE_1M
        └Secondary Phy                                  : LE_1M
        └Legacy                                         : true
        └Anonymous                                      : false
        └Connectable                                    : false
        └Scannable                                      : false
        └Advertise Data:
          └Include Device Name                          : false
          └Include Tx Power Level                       : false
          └Service Data(UUID, length of data)           : 
            [0000fef3-xxxx-xxxx-xxxx-xxxxxxxxxxxx, 6]

    com.google.uid.shared:10100
     Advertising ID                                     : 0
      1:
        └Start time                                     : 05-08 17:27:02
        └Stop time                                      : 05-08 17:28:13
        └Duration(10ms unit)                            : 0
        └Maximum number of extended advertising events  : 0
      └Advertising:
        └Interval(0.625ms)                              : 400
        └TX POWER(dbm)                                  : 1
        └Primary Phy                                    : LE_1M
        └Secondary Phy                                  : LE_1M
        └Legacy                                         : true
        └Anonymous                                      : false
        └Connectable                                    : false
        └Scannable                                      : true
        └Advertise Data:
          └Include Device Name                          : false
          └Include Tx Power Level                       : false
          └Service Uuids                                : 
            [0000fef-xxxx-xxxx-xxxx-xxxxxxxxxxxx
        └Scan Response:
          └Include Device Name                          : false
          └Include Tx Power Level                       : false
          └Service Data(UUID, length of data)           : 
            [0000fef3-xxxx-xxxx-xxxx-xxxxxxxxxxxx, 27]

    com.google.uid.shared:10100
     Advertising ID                                     : 0
      1:
        └Start time                                     : 05-08 17:28:13
        └Stop time                                      : 05-08 17:28:15
        └Duration(10ms unit)                            : 0
        └Maximum number of extended advertising events  : 0
      └Advertising:
        └Interval(0.625ms)                              : 160
        └TX POWER(dbm)                                  : -7
        └Primary Phy                                    : LE_1M
        └Secondary Phy                                  : LE_1M
        └Legacy                                         : true
        └Anonymous                                      : false
        └Connectable                                    : false
        └Scannable                                      : false
        └Advertise Data:
          └Include Device Name                          : false
          └Include Tx Power Level                       : false
          └Service Data(UUID, length of data)           : 
            [0000fef3-xxxx-xxxx-xxxx-xxxxxxxxxxxx, 6]

    com.google.uid.shared:10100
     Advertising ID                                     : 0
      1:
        └Start time                                     : 05-08 17:28:18
        └Stop time                                      : 05-08 17:36:12
        └Duration(10ms unit)                            : 0
        └Maximum number of extended advertising events  : 0
      └Advertising:
        └Interval(0.625ms)                              : 1600
        └TX POWER(dbm)                                  : -15
        └Primary Phy                                    : LE_1M
        └Secondary Phy                                  : LE_1M
        └Legacy                                         : true
        └Anonymous                                      : false
        └Connectable                                    : false
        └Scannable                                      : true
        └Advertise Data:
          └Include Device Name                          : false
          └Include Tx Power Level                       : false
          └Service Uuids                                : 
            [0000fef-xxxx-xxxx-xxxx-xxxxxxxxxxxx
        └Scan Response:
          └Include Device Name                          : false
          └Include Tx Power Level                       : false
          └Service Data(UUID, length of data)           : 
            [0000fef3-xxxx-xxxx-xxxx-xxxxxxxxxxxx, 27]

    com.google.uid.shared:10100
     Advertising ID                                     : 0
      1:
        └Start time                                     : 05-08 17:36:12
        └Stop time                                      : 05-08 17:36:14
        └Duration(10ms unit)                            : 0
        └Maximum number of extended advertising events  : 0
      └Advertising:
        └Interval(0.625ms)                              : 160
        └TX POWER(dbm)                                  : -7
        └Primary Phy                                    : LE_1M
        └Secondary Phy                                  : LE_1M
        └Legacy                                         : true
        └Anonymous                                      : false
        └Connectable                                    : false
        └Scannable                                      : false
        └Advertise Data:
          └Include Device Name                          : false
          └Include Tx Power Level                       : false
          └Service Data(UUID, length of data)           : 
            [0000fef3-xxxx-xxxx-xxxx-xxxxxxxxxxxx, 6]

  Total number of ongoing advertising                   : 1
  Ongoing advertising:
    com.google.uid.shared:10100
     Advertising ID                                     : 0
      1:
        └Start time                                     : 05-08 17:36:17
        └Elapsed time                                   : 187253ms
        └Duration(10ms unit)                            : 0
        └Maximum number of extended advertising events  : 0
      └Advertising:
        └Interval(0.625ms)                              : 400
        └TX POWER(dbm)                                  : 1
        └Primary Phy                                    : LE_1M
        └Secondary Phy                                  : LE_1M
        └Legacy                                         : true
        └Anonymous                                      : false
        └Connectable                                    : false
        └Scannable                                      : true
        └Advertise Data:
          └Include Device Name                          : false
          └Include Tx Power Level                       : false
          └Service Uuids                                : 
            [0000fef-xxxx-xxxx-xxxx-xxxxxxxxxxxx
        └Scan Response:
          └Include Device Name                          : false
          └Include Tx Power Level                       : false
          └Service Data(UUID, length of data)           : 
            [0000fef3-xxxx-xxxx-xxxx-xxxxxxxxxxxx, 27]

GATT Client Map
  Entries: 0

GATT Server Map
  Entries: 0

GATT Handle Map
  Entries: 0
  Requests: 0

Profile: A2dpService
  mActiveDevice: null
  mMaxConnectedAudioDevices: 5
  codecConfigPriorities:
    SBC: 1001
    AAC: 2001
    aptX: 3001
    aptX HD: 4001
    LDAC: 5001
    Opus: 7001
  mA2dpOffloadEnabled: false
  === A2dpStateMachine for 41:42:B2:14:0C:C4 ===
    getConnectionPolicy: 100
    mConnectionState: DISCONNECTED, mLastConnectionState: CONNECTED
    mIsPlaying: false
    getSupportsOptionalCodecs: 1, getOptionalCodecsEnabled: 1
    mCodecConfig: {codecName:AAC,mCodecType:1,mCodecPriority:2001,mSampleRate:0x1(44100),mBitsPerSample:0x1(16),mChannelMode:0x2(STEREO),mCodecSpecific1:0,mCodecSpecific2:0,mCodecSpecific3:0,mCodecSpecific4:0}
    mCodecsSelectableCapabilities:
      {codecName:AAC,mCodecType:1,mCodecPriority:2001,mSampleRate:0x1(44100),mBitsPerSample:0x1(16),mChannelMode:0x2(STEREO),mCodecSpecific1:0,mCodecSpecific2:0,mCodecSpecific3:0,mCodecSpecific4:0}
      {codecName:SBC,mCodecType:0,mCodecPriority:1001,mSampleRate:0x1(44100),mBitsPerSample:0x1(16),mChannelMode:0x3(MONO|STEREO),mCodecSpecific1:0,mCodecSpecific2:0,mCodecSpecific3:0,mCodecSpecific4:0}
    StateMachine: name=A2dpStateMachine state=Disconnected
    StateMachineLog:
      A2dpStateMachine:
       total records=52
       rec[0]: time=05-08 17:13:49.193 processed=Connected org=Connected dest=<null> what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=A2dpStackEvent {type:EVENT_TYPE_AUDIO_STATE_CHANGED, device:41:42:B2:14:0C:C4, value1:STOPPED}
       rec[1]: time=05-08 17:13:53.194 processed=Connected org=Connected dest=<null> what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=A2dpStackEvent {type:EVENT_TYPE_AUDIO_STATE_CHANGED, device:41:42:B2:14:0C:C4, value1:STARTED}
       rec[2]: time=05-08 17:13:56.676 processed=Connected org=Connected dest=<null> what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=A2dpStackEvent {type:EVENT_TYPE_AUDIO_STATE_CHANGED, device:41:42:B2:14:0C:C4, value1:STOPPED}
       rec[3]: time=05-08 17:13:57.239 processed=Connected org=Connected dest=<null> what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=A2dpStackEvent {type:EVENT_TYPE_AUDIO_STATE_CHANGED, device:41:42:B2:14:0C:C4, value1:STARTED}
       rec[4]: time=05-08 17:14:29.598 processed=Connected org=Connected dest=<null> what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=A2dpStackEvent {type:EVENT_TYPE_AUDIO_STATE_CHANGED, device:41:42:B2:14:0C:C4, value1:STOPPED}
       rec[5]: time=05-08 17:14:41.416 processed=Connected org=Connected dest=<null> what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=A2dpStackEvent {type:EVENT_TYPE_AUDIO_STATE_CHANGED, device:41:42:B2:14:0C:C4, value1:STARTED}
       rec[6]: time=05-08 17:14:47.577 processed=Connected org=Connected dest=<null> what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=A2dpStackEvent {type:EVENT_TYPE_AUDIO_STATE_CHANGED, device:41:42:B2:14:0C:C4, value1:STOPPED}
       rec[7]: time=05-08 17:14:54.889 processed=Connected org=Connected dest=<null> what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=A2dpStackEvent {type:EVENT_TYPE_AUDIO_STATE_CHANGED, device:41:42:B2:14:0C:C4, value1:STARTED}
       rec[8]: time=05-08 17:15:18.291 processed=Connected org=Connected dest=<null> what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=A2dpStackEvent {type:EVENT_TYPE_AUDIO_STATE_CHANGED, device:41:42:B2:14:0C:C4, value1:STOPPED}
       rec[9]: time=05-08 17:15:19.588 processed=Connected org=Connected dest=<null> what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=A2dpStackEvent {type:EVENT_TYPE_AUDIO_STATE_CHANGED, device:41:42:B2:14:0C:C4, value1:STARTED}
       rec[10]: time=05-08 17:15:48.052 processed=Connected org=Connected dest=<null> what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=A2dpStackEvent {type:EVENT_TYPE_AUDIO_STATE_CHANGED, device:41:42:B2:14:0C:C4, value1:STOPPED}
       rec[11]: time=05-08 17:15:49.734 processed=Connected org=Connected dest=<null> what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=A2dpStackEvent {type:EVENT_TYPE_AUDIO_STATE_CHANGED, device:41:42:B2:14:0C:C4, value1:STARTED}
       rec[12]: time=05-08 17:16:50.753 processed=Connected org=Connected dest=<null> what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=A2dpStackEvent {type:EVENT_TYPE_AUDIO_STATE_CHANGED, device:41:42:B2:14:0C:C4, value1:STOPPED}
       rec[13]: time=05-08 17:17:00.735 processed=Connected org=Connected dest=<null> what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=A2dpStackEvent {type:EVENT_TYPE_AUDIO_STATE_CHANGED, device:41:42:B2:14:0C:C4, value1:STARTED}
       rec[14]: time=05-08 17:17:05.500 processed=Connected org=Connected dest=<null> what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=A2dpStackEvent {type:EVENT_TYPE_AUDIO_STATE_CHANGED, device:41:42:B2:14:0C:C4, value1:STOPPED}
       rec[15]: time=05-08 17:23:44.761 processed=Connected org=Connected dest=<null> what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=A2dpStackEvent {type:EVENT_TYPE_AUDIO_STATE_CHANGED, device:41:42:B2:14:0C:C4, value1:STARTED}
       rec[16]: time=05-08 17:27:23.431 processed=Connected org=Connected dest=<null> what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=A2dpStackEvent {type:EVENT_TYPE_AUDIO_STATE_CHANGED, device:41:42:B2:14:0C:C4, value1:STOPPED}
       rec[17]: time=05-08 17:27:48.399 processed=Connected org=Connected dest=<null> what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=A2dpStackEvent {type:EVENT_TYPE_AUDIO_STATE_CHANGED, device:41:42:B2:14:0C:C4, value1:STARTED}
       rec[18]: time=05-08 17:29:25.070 processed=Connected org=Connected dest=<null> what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=A2dpStackEvent {type:EVENT_TYPE_AUDIO_STATE_CHANGED, device:41:42:B2:14:0C:C4, value1:STOPPED}
       rec[19]: time=05-08 17:29:25.078 processed=Connected org=Connected dest=Disconnected what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=A2dpStackEvent {type:EVENT_TYPE_CONNECTION_STATE_CHANGED, device:41:42:B2:14:0C:C4, value1:DISCONNECTED}
      curState=Disconnected

Profile: AvrcpTargetService:
  AVRCP version: Invalid
  List of MediaControllers: size=2
    Media Player 1: de.danoeh.antennapod
    MediaController (de.danoeh.antennapod@bfadc6) null
    Current Data:
      Song: { mediaId="currsong" title="Not Provided" artist="" album="" duration=0 trackPosition=1/1 image=null }
      PlayState: PlaybackState {state=1, position=-1, buffered position=0, speed=1.0, updated=12033133, actions=4195150, custom actions=[Action:mName='Rewind, mIcon=2131231277, mExtras=Bundle[mParcelledData.dataSize=144], Action:mName='Fast-forward, mIcon=2131231276, mExtras=Bundle[mParcelledData.dataSize=144], Action:mName='Playback speed, mIcon=2131231282, mExtras=null, Action:mName='Skip episode, mIcon=2131231283, mExtras=null], active item id=-1, error=null}
      Queue: size=1
        { mediaId="currsong" title="Not Provided" artist="" album="" duration=0 trackPosition=1/1 image=null }
    BTAudio Playback State change Event:
  
    Media Player 2: org.thoughtcrime.securesms
    MediaController (org.thoughtcrime.securesms@5b38187) null
    Current Data:
      Song: { mediaId="currsong" title="Not Provided" artist="" album="" duration=0 trackPosition=1/1 image=null }
      PlayState: PlaybackState {state=0, position=0, buffered position=0, speed=0.0, updated=12041801, actions=7339655, custom actions=[], active item id=0, error=null}
      Queue: size=0
    BTAudio Playback State change Event:
  
  List of Browsers: size=0
  BTAudio Active Player Events:
    05-08 17:08:58.695 setActivePlayer(): setting player to de.danoeh.antennapod
    05-08 17:08:58.792 setActivePlayer(): setting player to anddea.youtube.music
    05-08 17:23:30.311 setActivePlayer(): setting player to anddea.youtube.music
  
  BTAudio Audio Playback State Events:
  
  BTAudio Media Key Events:
    05-08 17:29:22.728 getMediaKeyEvent: device=41:42:B2:14:0C:C4 event=70 pushed=true to anddea.youtube.music
    05-08 17:29:22.753 getMediaKeyEvent: device=41:42:B2:14:0C:C4 event=70 pushed=false to anddea.youtube.music
  
  AvrcpVolumeManager:
    mCurrentDevice: null
    Current System Volume: 5
    Device Volume Memory Map:
      Device Address    : Device Name    : Vol : AbsVol
      41:42:B2:14:0C:C4 : AirPods Pro    :   8 : NotConnected
    BTAudio Volume Events:
      05-08 17:09:51.508 sendVolumeChanged: device=41:42:B2:14:0C:C4 avrcpVolume=68 deviceVolume=8 sDeviceMaxVolume=15
      05-08 17:09:51.513 storeVolume: Storing stream volume level for device 41:42:B2:14:0C:C4 : 8
      05-08 17:09:51.550 sendVolumeChanged: device=41:42:B2:14:0C:C4 avrcpVolume=76 deviceVolume=9 sDeviceMaxVolume=15
      05-08 17:09:51.559 storeVolume: Storing stream volume level for device 41:42:B2:14:0C:C4 : 9
      05-08 17:09:51.606 sendVolumeChanged: device=41:42:B2:14:0C:C4 avrcpVolume=85 deviceVolume=10 sDeviceMaxVolume=15
      05-08 17:09:51.610 storeVolume: Storing stream volume level for device 41:42:B2:14:0C:C4 : 10
      05-08 17:09:51.656 sendVolumeChanged: device=41:42:B2:14:0C:C4 avrcpVolume=93 deviceVolume=11 sDeviceMaxVolume=15
      05-08 17:09:51.661 storeVolume: Storing stream volume level for device 41:42:B2:14:0C:C4 : 11
      05-08 17:09:51.707 sendVolumeChanged: device=41:42:B2:14:0C:C4 avrcpVolume=102 deviceVolume=12 sDeviceMaxVolume=15
      05-08 17:09:51.712 storeVolume: Storing stream volume level for device 41:42:B2:14:0C:C4 : 12
      05-08 17:09:51.757 sendVolumeChanged: device=41:42:B2:14:0C:C4 avrcpVolume=110 deviceVolume=13 sDeviceMaxVolume=15
      05-08 17:09:51.760 storeVolume: Storing stream volume level for device 41:42:B2:14:0C:C4 : 13
      05-08 17:09:51.821 sendVolumeChanged: device=41:42:B2:14:0C:C4 avrcpVolume=119 deviceVolume=14 sDeviceMaxVolume=15
      05-08 17:09:51.822 storeVolume: Storing stream volume level for device 41:42:B2:14:0C:C4 : 14
      05-08 17:09:51.856 sendVolumeChanged: device=41:42:B2:14:0C:C4 avrcpVolume=127 deviceVolume=15 sDeviceMaxVolume=15
      05-08 17:09:51.861 storeVolume: Storing stream volume level for device 41:42:B2:14:0C:C4 : 15
      05-08 17:23:46.198 sendVolumeChanged: device=41:42:B2:14:0C:C4 avrcpVolume=119 deviceVolume=14 sDeviceMaxVolume=15
      05-08 17:23:46.211 storeVolume: Storing stream volume level for device 41:42:B2:14:0C:C4 : 14
      05-08 17:23:46.535 sendVolumeChanged: device=41:42:B2:14:0C:C4 avrcpVolume=110 deviceVolume=13 sDeviceMaxVolume=15
      05-08 17:23:46.542 storeVolume: Storing stream volume level for device 41:42:B2:14:0C:C4 : 13
      05-08 17:24:13.642 sendVolumeChanged: device=41:42:B2:14:0C:C4 avrcpVolume=102 deviceVolume=12 sDeviceMaxVolume=15
      05-08 17:24:13.650 storeVolume: Storing stream volume level for device 41:42:B2:14:0C:C4 : 12
      05-08 17:24:41.756 sendVolumeChanged: device=41:42:B2:14:0C:C4 avrcpVolume=93 deviceVolume=11 sDeviceMaxVolume=15
      05-08 17:24:41.761 storeVolume: Storing stream volume level for device 41:42:B2:14:0C:C4 : 11
      05-08 17:26:42.890 sendVolumeChanged: device=41:42:B2:14:0C:C4 avrcpVolume=85 deviceVolume=10 sDeviceMaxVolume=15
      05-08 17:26:42.903 storeVolume: Storing stream volume level for device 41:42:B2:14:0C:C4 : 10
      05-08 17:26:43.356 sendVolumeChanged: device=41:42:B2:14:0C:C4 avrcpVolume=76 deviceVolume=9 sDeviceMaxVolume=15
      05-08 17:26:43.369 storeVolume: Storing stream volume level for device 41:42:B2:14:0C:C4 : 9
      05-08 17:28:44.995 sendVolumeChanged: device=41:42:B2:14:0C:C4 avrcpVolume=68 deviceVolume=8 sDeviceMaxVolume=15
      05-08 17:28:45.004 storeVolume: Storing stream volume level for device 41:42:B2:14:0C:C4 : 8

Profile: BatteryService
  mDevice: 41:42:B2:14:0C:C4
    StateMachine: name=BatteryStateMachine state=Disconnected
    BluetoothGatt: null
    StateMachineLog:
      BatteryStateMachine:
       total records=1
       rec[0]: time=05-08 17:29:24.992 processed=Disconnected org=Disconnected dest=<null> what=2(0x2)
      curState=Disconnected

Profile: HeadsetService
  mMaxHeadsetConnections: 5
  DefaultMaxHeadsetConnections: 5
  mActiveDevice: null
  isInbandRingingEnabled: true
  isInbandRingingSupported: true
  mInbandRingingRuntimeDisable: false
  mAudioRouteAllowed: true
  mVoiceRecognitionStarted: false
  mVoiceRecognitionTimeoutEvent: null
  mVirtualCallStarted: false
  mDialingOutTimeoutEvent: null
  mForceScoAudio: false
  mCreated: true
  mStarted: true
  AudioManager.isBluetoothScoOn(): false
  Telecom.isInCall(): false
  Telecom.isRinging(): false
  ==== StateMachine for 41:42:B2:14:0C:C4 ====
    mCurrentDevice: 41:42:B2:14:0C:C4
    mCurrentState: Disconnected
    mPrevState: Connected
    mConnectionState: 0
    mAudioState: 10
    mNeedDialingOutReply: false
    mSpeakerVolume: 15
    mMicVolume: 9
    mConnectingTimestampMs(uptimeMillis): -9223372036854775808
    mHsClientAudioPolicy: BluetoothSinkAudioPolicy{mCallEstablishPolicy: 0, mConnectingTimePolicy: 0, mInBandRingtonePolicy: 0}
    StateMachine: name=HeadsetStateMachine state=Disconnected
    StateMachineLog:
      HeadsetStateMachine:
       total records=15
       rec[0]: time=05-08 17:08:49.341 processed=Disconnected org=Disconnected dest=Connecting what=1(0x1) CONNECT: arg1=0, arg2=0, obj=41:42:B2:14:0C:C4
       rec[1]: time=05-08 17:08:50.189 processed=Connecting org=Connecting dest=<null> what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=EVENT_TYPE_CONNECTION_STATE_CHANGED[1], valInt=2, valInt2=0, valString=null, valObject=null, device=41:42:B2:14:0C:C4
       rec[2]: time=05-08 17:08:50.249 processed=Connecting org=Connecting dest=<null> what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=EVENT_TYPE_WBS[17], valInt=2, valInt2=0, valString=null, valObject=null, device=41:42:B2:14:0C:C4
       rec[3]: time=05-08 17:08:50.267 processed=Connecting org=Connecting dest=<null> what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=EVENT_TYPE_AT_CIND[12], valInt=0, valInt2=0, valString=null, valObject=null, device=41:42:B2:14:0C:C4
       rec[4]: time=05-08 17:08:50.372 processed=Connecting org=Connecting dest=Connected what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=EVENT_TYPE_CONNECTION_STATE_CHANGED[1], valInt=3, valInt2=0, valString=null, valObject=null, device=41:42:B2:14:0C:C4
       rec[5]: time=05-08 17:08:50.594 processed=Connected org=Connected dest=<null> what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=EVENT_TYPE_NOISE_REDUCTION[9], valInt=0, valInt2=0, valString=null, valObject=null, device=41:42:B2:14:0C:C4
       rec[6]: time=05-08 17:08:50.644 processed=Connected org=Connected dest=<null> what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=EVENT_TYPE_UNKNOWN_AT[15], valInt=0, valInt2=0, valString=+XAPL=000D-0001-0101,2, valObject=null, device=41:42:B2:14:0C:C4
       rec[7]: time=05-08 17:08:50.645 processed=Connected org=Connected dest=<null> what=13(0xd) UNKNOWN(13): arg1=1, arg2=0, obj=null
       rec[8]: time=05-08 17:08:50.645 processed=Connected org=Connected dest=<null> what=10(0xa) DEVICE_STATE_CHANGED: arg1=0, arg2=0, obj=HeadsetDeviceState[hasCellularService=1, isRoaming=0, signalStrength0, batteryCharge=4]
       rec[9]: time=05-08 17:08:50.645 processed=Connected org=Connected dest=<null> what=10(0xa) DEVICE_STATE_CHANGED: arg1=0, arg2=0, obj=HeadsetDeviceState[hasCellularService=1, isRoaming=0, signalStrength5, batteryCharge=4]
       rec[10]: time=05-08 17:08:50.681 processed=Connected org=Connected dest=<null> what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=EVENT_TYPE_BIA[20], valInt=0, valInt2=0, valString=null, valObject=HeadsetAgIndicatorEnableState[service=false, roam=false, signal=false, battery=false], device=41:42:B2:14:0C:C4
       rec[11]: time=05-08 17:08:50.681 processed=Connected org=Connected dest=<null> what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=EVENT_TYPE_VOLUME_CHANGED[6], valInt=1, valInt2=9, valString=null, valObject=null, device=41:42:B2:14:0C:C4
       rec[12]: time=05-08 17:08:50.689 processed=Connected org=Connected dest=<null> what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=EVENT_TYPE_VOLUME_CHANGED[6], valInt=0, valInt2=15, valString=null, valObject=null, device=41:42:B2:14:0C:C4
       rec[13]: time=05-08 17:08:50.754 processed=Connected org=Connected dest=<null> what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=EVENT_TYPE_UNKNOWN_AT[15], valInt=0, valInt2=0, valString=+IPHONEACCEV=1,1,9, valObject=null, device=41:42:B2:14:0C:C4
       rec[14]: time=05-08 17:29:24.969 processed=Connected org=Connected dest=Disconnected what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=EVENT_TYPE_CONNECTION_STATE_CHANGED[1], valInt=0, valInt2=0, valString=null, valObject=null, device=41:42:B2:14:0C:C4
      curState=Disconnected

Profile: HidDeviceService

Profile: HidHostService
  mTargetDevice: null
  mInputDevices:

Profile: BluetoothMapService
  mRemoteDevice: null
  sRemoteDeviceName: null
  mState: 0
  mAppObserver: com.android.bluetooth.map.BluetoothMapAppObserver@bd56cdd
  mIsWaitingAuthorization: false
  mRemoveTimeoutMsg: false
  mPermission: 0
  mAccountChanged: false
  mBluetoothMnsObexClient: null
  mMasInstanceMap:
    null : MasId: 0 Uri:null SMS/MMS:true
  mEnabledAccounts:

Profile: BluetoothOppService
  Shares:
    01-25 13:50:09 -> 6727685/6727685
    01-25 13:50:09 -> 6105691/6105691
    01-25 13:50:09 -> 6651767/6651767
    01-25 13:50:09 -> 5826648/5826648
    01-25 13:50:09 -> 6650223/6650223
    01-25 13:50:09 -> 6210738/6210738
    01-25 13:50:09 -> 7131877/7131877
    01-25 13:50:09 -> 6682714/6682714
    01-25 13:50:09 -> 5652234/5652234
    01-25 13:50:09 -> 6331532/6331532
    01-25 13:50:09 -> 6826581/6826581
    01-25 13:50:09 -> 6184150/6184150
    01-25 13:50:09 -> 6648637/6648637
    01-25 13:50:09 -> 7176648/7176648
    01-25 13:50:09 -> 7214395/7214395
    01-25 13:50:09 -> 6287252/6287252
    01-25 13:50:09 -> 6517786/6517786
    01-25 13:50:09 -> 6737551/6737551
    01-25 13:50:09 -> 6432758/6432758
    01-25 13:50:09 -> 6447047/6447047
    01-25 13:50:09 -> 6729596/6729596
    01-25 13:50:09 -> 6731324/6731324
    01-25 13:50:09 -> 7159114/7159114
    01-25 13:50:09 -> 6989311/6989311
    01-25 13:50:09 -> 7040917/7040917
    01-25 13:50:09 -> 7694201/7694201
    01-25 13:50:09 -> 6829979/6829979
    01-25 13:50:09 -> 6562783/6562783
    01-25 13:50:09 -> 7003021/7003021
    01-25 13:50:09 -> 6791408/6791408
    01-25 13:50:09 -> 6571881/6571881
    01-25 13:50:09 -> 7356562/7356562
    01-25 13:50:09 -> 7527169/7527169
    01-25 13:50:09 -> 6719910/6719910
    01-25 13:50:09 -> 7272565/7272565
    01-25 13:50:09 -> 6294626/6294626
    01-25 13:50:09 -> 6643015/6643015
    01-25 13:50:09 -> 6604164/6604164
    01-25 13:50:09 -> 5956859/5956859
    01-25 13:50:09 -> 6641051/6641051
    01-25 13:50:09 -> 6315231/6315231
    01-25 13:50:09 -> 6711024/6711024
    01-25 13:50:09 -> 7373954/7373954
    01-25 13:50:09 -> 6345125/6345125

Profile: PanService
  mMaxPanDevices: 5
  mPanIfName: bt-pan
  mTetherOn: false
  mPanDevices:

Profile: BluetoothPbapService

Profile: SapService

Connection Events:
  None

Bond Events: 
  Total Number of events: 0

Link Key Types:
  41:42:b2:14:0c:c4
    BR: UNAUTH_COMB
    LE:

A2DP State:
  TxQueue:
  Counts (enqueue/dequeue/readbuf)                        : 26954 / 26553 / 51140
  Last update time ago in ms (enqueue/dequeue/readbuf)    : 0 / 0 / 0
  Frames per packet (total/max/ave)                       : 26651 / 1 / 0
  Counts (flushed/dropped/dropouts)                       : 14 / 84 / 3
  Counts (max dropped)                                    : 28
  Last update time ago in ms (flushed/dropped)            : 0 / 0
  Counts (underflow)                                      : 42
  Bytes (underflow)                                       : 108624
  Last update time ago in ms (underflow)                  : 0
  Enqueue deviation counts (overdue/premature)            : 13266 / 13404
  Enqueue overdue scheduling time in ms (total/max/ave)   : 1054 / 158 / 0
  Enqueue premature scheduling time in ms (total/max/ave) : 803 / 20 / 0
  Dequeue deviation counts (overdue/premature)            : 13204 / 13299
  Dequeue overdue scheduling time in ms (total/max/ave)   : 38085 / 115 / 2
  Dequeue premature scheduling time in ms (total/max/ave) : 33103 / 22 / 2

A2DP Source State: Enabled
  Active peer: 00:00:00:00:00:00

A2DP Sink State: Disabled

Socket Events: 
  Time        	Address          	State             	Role
  17:08:48.775	00:00:00:00:00:00	STATE_LISTENING   	ROLE_LISTEN
  17:08:48.775	00:00:00:00:00:00	STATE_LISTENING   	ROLE_LISTEN
  17:08:48.812	00:00:00:00:00:00	STATE_LISTENING   	ROLE_LISTEN
  17:08:48.813	00:00:00:00:00:00	STATE_LISTENING   	ROLE_LISTEN
  17:08:48.901	00:00:00:00:00:00	STATE_LISTENING   	ROLE_LISTEN
  17:08:48.902	00:00:00:00:00:00	STATE_LISTENING   	ROLE_LISTEN
  17:08:48.905	00:00:00:00:00:00	STATE_LISTENING   	ROLE_LISTEN
  17:08:48.906	00:00:00:00:00:00	STATE_LISTENING   	ROLE_LISTEN
  17:08:49.355	00:00:00:00:00:00	STATE_LISTENING   	ROLE_LISTEN
  17:08:49.357	00:00:00:00:00:00	STATE_LISTENING   	ROLE_LISTEN
  17:08:49.389	00:00:00:00:00:00	STATE_LISTENING   	ROLE_LISTEN
  17:08:49.393	00:00:00:00:00:00	STATE_LISTENING   	ROLE_LISTEN
  17:08:49.402	00:00:00:00:00:00	STATE_LISTENING   	ROLE_LISTEN
  17:08:49.403	00:00:00:00:00:00	STATE_LISTENING   	ROLE_LISTEN
  17:08:50.857	00:00:00:00:00:00	STATE_LISTENING   	ROLE_LISTEN
  17:08:50.858	00:00:00:00:00:00	STATE_LISTENING   	ROLE_LISTEN


AVRCP Target Native Service: 0 devices

Bluetooth Config:
  Config Source: Not loaded
  Devices loaded: 0
  File created/tagged: 
  File source: Backup

Bluetooth HF Client BTA Statistics

Bluetooth Wakelock Statistics:
  Is acquired                    : false
  Acquired/released count        : 41 / 41
  Acquired/released error count  : 0 / 0
  Last acquire/release error code: 0 / 0
  Last acquired time (ms)        : 56641
  Acquired time min/max/avg (ms) : 6 / 61031 / 8297
  Total acquired time (ms)       : 340178
  Total run time (ms)            : 1836655

Bluetooth Memory Allocation Statistics:
  Total allocated/free/used counts : 138204 / 137653 / 551
  Total allocated/free/used octets : 118274251 / 118220171 / 54080

Bluetooth Alarms Statistics:
  Total Alarms: 0

Coordinated Set Service Client:

Hearing Access Service Client:
  no instance

Hearing Aid Manager:
  Hearing Aid Audio HAL:
    Counts (underflow)                                      : 0
    Bytes (underflow)                                       : 0
    Last update time ago in ms (underflow)                  : 0

Device Groups Manager:
  Not initialized 
LeAudio Manager: 
  Not initialized 
  LE AudioHalClient:
    Counts (underflow)                                      : 0
    Bytes (underflow)                                       : 0
    Last update time ago in ms (underflow)                  : 0

 AudioSetConfigurationProvider not initialized: config provider: 0, pimpl: 0 

Le Audio Broadcaster:

Volume Control Manager:


connection_manager state:
	no Low Energy connection attempts

BT Quality Report Events: 
Event queue is empty.
shim::legacy::dumpsys Dumping shim legacy targets:1
 ----- shim::legacy::pan -----
shim::legacy::pan Connections:0 roles configured:C.N[0x5] current:...[0x0] previous:...[0x0]
shim::legacy::pan service_name_user:"Android Network User"
shim::legacy::pan service_name_nap:"Android Network Access Point"
 ----- shim::legacy::hid -----
shim::legacy::hid status:BTIF_HH_ENABLED num_devices:0
shim::legacy::hid status:BTIF_HH_ENABLED
 ----- shim::legacy::record -----
shim::legacy::record 001 xx:xx:xx:xx:0c:c4   DUAL cod:0x040424 remote_info:13-00003-00076 sm4:0x11 SecureConn:F name:"AirPods Pro"
 ----- shim::legacy::acl -----
shim::acl peer:xx:xx:xx:xx:0c:c4 handle:0x0033 is_locally_initiated:true creation_time:2025-05-08 17:08:49.782 teardown_time:2025-05-08 17:29:24.930 disconnect_reason:REMOTE_USER_TERMINATED_CONNECTION
shim::acl Shadow le accept list              size:0   controller_max_size:64
shim::acl Shadow le address resolution list  size:0   controller_max_size:32
 ----- shim::legacy::l2cap -----
 ----- shim::legacy::btm -----
shim::legacy::btm  2025-05-08 17:17:00.051 ACL    Power mode change        : xx:xx:xx:xx:0c:c4 immediate:sniff[0x02] ==> immediate:active[0x00]
shim::legacy::btm  2025-05-08 17:17:00.707 A2DP   Stream started           : xx:xx:xx:xx:00:00 BTA_AV_START_EVT(0x4)
shim::legacy::btm  2025-05-08 17:17:05.419 ACL    Sniff subrating          : xx:xx:xx:xx:0c:c4 max_latency:0.75 peer_timeout:0.00 local_timeout:0.00
shim::legacy::btm  2025-05-08 17:17:05.495 ACL    Sniff subrating          : xx:xx:xx:xx:0c:c4 max_latency:0.75 peer_timeout:0.00 local_timeout:0.00
shim::legacy::btm  2025-05-08 17:17:05.496 A2DP   Stream stopped           : xx:xx:xx:xx:00:00 BTA_AV_SUSPEND_EVT(0xf)
shim::legacy::btm  2025-05-08 17:19:35.658 SCAN   Le scan stopped          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:19:35.677 SCAN   Le scan started          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:19:35.910 SCAN   Le scan stopped          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:19:36.470 ADV    Le advert stopped        : xx:xx:xx:xx:00:00 advert_id:0
shim::legacy::btm  2025-05-08 17:19:36.523 ADV    Le advert started        : xx:xx:xx:xx:00:00 advert_id:-3
shim::legacy::btm  2025-05-08 17:19:36.595 ADV    Le advert started        : xx:xx:xx:xx:00:00 advert_id:-4
shim::legacy::btm  2025-05-08 17:19:39.624 ADV    Le advert stopped        : xx:xx:xx:xx:00:00 advert_id:0
shim::legacy::btm  2025-05-08 17:19:42.184 ADV    Le advert started        : xx:xx:xx:xx:00:00 advert_id:-5
shim::legacy::btm  2025-05-08 17:20:10.671 SCAN   Le scan started          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:20:10.675 SCAN   Le scan stopped          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:20:10.675 SCAN   Le scan started          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:20:11.105 ADV    Le advert stopped        : xx:xx:xx:xx:00:00 advert_id:0
shim::legacy::btm  2025-05-08 17:20:11.143 ADV    Le advert started        : xx:xx:xx:xx:00:00 advert_id:-6
shim::legacy::btm  2025-05-08 17:20:11.185 ADV    Le advert started        : xx:xx:xx:xx:00:00 advert_id:-7
shim::legacy::btm  2025-05-08 17:20:13.160 ADV    Le advert stopped        : xx:xx:xx:xx:00:00 advert_id:0
shim::legacy::btm  2025-05-08 17:20:16.222 ADV    Le advert started        : xx:xx:xx:xx:00:00 advert_id:-8
shim::legacy::btm  2025-05-08 17:20:16.974 SCAN   Le scan stopped          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:20:16.975 SCAN   Le scan started          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:23:44.745 A2DP   Stream started           : xx:xx:xx:xx:00:00 BTA_AV_START_EVT(0x4)
shim::legacy::btm  2025-05-08 17:24:04.598 SCAN   Le scan stopped          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:24:04.598 SCAN   Le scan started          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:24:04.738 SCAN   Le scan stopped          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:24:05.014 ADV    Le advert stopped        : xx:xx:xx:xx:00:00 advert_id:0
shim::legacy::btm  2025-05-08 17:24:05.076 ADV    Le advert started        : xx:xx:xx:xx:00:00 advert_id:-9
shim::legacy::btm  2025-05-08 17:24:05.195 ADV    Le advert started        : xx:xx:xx:xx:00:00 advert_id:-10
shim::legacy::btm  2025-05-08 17:24:07.139 ADV    Le advert stopped        : xx:xx:xx:xx:00:00 advert_id:0
shim::legacy::btm  2025-05-08 17:24:10.216 ADV    Le advert started        : xx:xx:xx:xx:00:00 advert_id:-11
shim::legacy::btm  2025-05-08 17:24:59.552 SCAN   Le scan started          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:24:59.553 SCAN   Le scan stopped          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:24:59.553 SCAN   Le scan started          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:25:05.519 SCAN   Le scan stopped          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:25:05.519 SCAN   Le scan started          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:25:09.981 SCAN   Le scan stopped          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:25:09.984 SCAN   Le scan started          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:25:10.175 SCAN   Le scan stopped          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:25:15.339 SCAN   Le scan started          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:25:15.340 SCAN   Le scan stopped          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:25:15.341 SCAN   Le scan started          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:25:20.109 SCAN   Le scan stopped          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:25:20.109 SCAN   Le scan started          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:25:20.259 SCAN   Le scan stopped          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:26:53.288 SCAN   Le scan started          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:26:53.289 SCAN   Le scan stopped          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:26:53.301 SCAN   Le scan started          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:26:57.159 ADV    Le advert stopped        : xx:xx:xx:xx:00:00 advert_id:0
shim::legacy::btm  2025-05-08 17:26:57.225 ADV    Le advert started        : xx:xx:xx:xx:00:00 advert_id:-12
shim::legacy::btm  2025-05-08 17:26:57.323 ADV    Le advert started        : xx:xx:xx:xx:00:00 advert_id:-13
shim::legacy::btm  2025-05-08 17:26:58.917 SCAN   Le scan stopped          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:26:58.922 SCAN   Le scan started          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:26:59.274 ADV    Le advert stopped        : xx:xx:xx:xx:00:00 advert_id:0
shim::legacy::btm  2025-05-08 17:27:02.990 ADV    Le advert started        : xx:xx:xx:xx:00:00 advert_id:-14
shim::legacy::btm  2025-05-08 17:27:23.376 ACL    Sniff subrating          : xx:xx:xx:xx:0c:c4 max_latency:0.75 peer_timeout:0.00 local_timeout:0.00
shim::legacy::btm  2025-05-08 17:27:23.423 ACL    Sniff subrating          : xx:xx:xx:xx:0c:c4 max_latency:0.75 peer_timeout:0.00 local_timeout:0.00
shim::legacy::btm  2025-05-08 17:27:23.424 A2DP   Stream stopped           : xx:xx:xx:xx:00:00 BTA_AV_SUSPEND_EVT(0xf)
shim::legacy::btm  2025-05-08 17:27:47.915 ACL    Power mode change        : xx:xx:xx:xx:0c:c4 immediate:sniff[0x02] ==> immediate:active[0x00]
shim::legacy::btm  2025-05-08 17:27:48.376 A2DP   Stream started           : xx:xx:xx:xx:00:00 BTA_AV_START_EVT(0x4)
shim::legacy::btm  2025-05-08 17:28:12.959 SCAN   Le scan stopped          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:28:12.960 SCAN   Le scan started          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:28:13.136 SCAN   Le scan stopped          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:28:13.381 ADV    Le advert stopped        : xx:xx:xx:xx:00:00 advert_id:0
shim::legacy::btm  2025-05-08 17:28:13.402 ADV    Le advert started        : xx:xx:xx:xx:00:00 advert_id:-15
shim::legacy::btm  2025-05-08 17:28:13.498 ADV    Le advert started        : xx:xx:xx:xx:00:00 advert_id:-16
shim::legacy::btm  2025-05-08 17:28:15.449 ADV    Le advert stopped        : xx:xx:xx:xx:00:00 advert_id:0
shim::legacy::btm  2025-05-08 17:28:18.531 ADV    Le advert started        : xx:xx:xx:xx:00:00 advert_id:-17
shim::legacy::btm  2025-05-08 17:29:01.763 SCAN   Le scan started          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:29:01.763 SCAN   Le scan stopped          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:29:01.763 SCAN   Le scan started          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:29:04.701 SCAN   Le scan stopped          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:29:04.702 SCAN   Le scan started          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:29:04.718 SCAN   Le scan stopped          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:29:24.930 ACL    Disconnected             : xx:xx:xx:xx:0c:c4 classic reason:REMOTE_USER_TERMINATED_CONNECTION
shim::legacy::btm  2025-05-08 17:29:24.966 A2DP   Stream stopped           : xx:xx:xx:xx:00:00 BTA_AV_STOP_EVT(0x5)
shim::legacy::btm  2025-05-08 17:29:24.968 A2DP   Stream closed            : xx:xx:xx:xx:00:00 BTA_AV_CLOSE_EVT(0x3)
shim::legacy::btm  2025-05-08 17:32:02.316 SCAN   Le scan started          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:32:02.317 SCAN   Le scan stopped          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:32:02.317 SCAN   Le scan started          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:32:04.210 SCAN   Le scan stopped          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:32:04.210 SCAN   Le scan started          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:32:04.213 SCAN   Le scan stopped          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:32:52.040 SCAN   Le scan started          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:32:52.041 SCAN   Le scan stopped          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:32:52.042 SCAN   Le scan started          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:32:55.066 SCAN   Le scan stopped          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:32:55.068 SCAN   Le scan started          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:32:55.082 SCAN   Le scan stopped          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:36:11.428 SCAN   Le scan started          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:36:11.429 SCAN   Le scan stopped          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:36:11.431 SCAN   Le scan started          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:36:12.625 ADV    Le advert stopped        : xx:xx:xx:xx:00:00 advert_id:0
shim::legacy::btm  2025-05-08 17:36:12.651 ADV    Le advert started        : xx:xx:xx:xx:00:00 advert_id:-18
shim::legacy::btm  2025-05-08 17:36:12.704 ADV    Le advert started        : xx:xx:xx:xx:00:00 advert_id:-19
shim::legacy::btm  2025-05-08 17:36:14.681 ADV    Le advert stopped        : xx:xx:xx:xx:00:00 advert_id:0
shim::legacy::btm  2025-05-08 17:36:17.757 ADV    Le advert started        : xx:xx:xx:xx:00:00 advert_id:-20
shim::legacy::btm  2025-05-08 17:36:18.492 SCAN   Le scan stopped          : xx:xx:xx:xx:00:00 
shim::legacy::btm  2025-05-08 17:36:18.492 SCAN   Le scan started          : xx:xx:xx:xx:00:00 
 ----- Filtering as Developer -----
{
  title: "----- Gd Dumpsys ------",
  init_flags: {
    title: "----- Init Flags -----",
    gd_advertising_enabled: true,
    gd_scanning_enabled: true,
    gd_acl_enabled: true,
    gd_hci_enabled: true,
    gd_controller_enabled: true,
    always_send_services_if_gatt_disc_done_is_enabled: true,
    asynchronously_start_l2cap_coc_is_enabled: true,
    btaa_hci_is_enabled: true,
    bta_dm_clear_conn_id_on_client_close_is_enabled: true,
    btm_dm_flush_discovery_queue_on_search_cancel_is_enabled: false,
    clear_hidd_interrupt_cid_on_disconnect_is_enabled: true,
    delay_hidh_cleanup_until_hidh_ready_start_is_enabled: true,
    gatt_robust_caching_client_is_enabled: false,
    gatt_robust_caching_server_is_enabled: false,
    gd_core_is_enabled: false,
    gd_l2cap_is_enabled: false,
    gd_link_policy_is_enabled: false,
    gd_remote_name_request_is_enabled: false,
    gd_rust_is_enabled: false,
    gd_security_is_enabled: false,
    get_hci_adapter: 0,
    irk_rotation_is_enabled: false,
    leaudio_targeted_announcement_reconnection_mode_is_enabled: false,
    logging_debug_enabled_for_all_is_enabled: false,
    pass_phy_update_callback_is_enabled: true,
    queue_l2cap_coc_while_encrypting_is_enabled: true,
    sdp_serialization_is_enabled: true,
    sdp_skip_rnr_if_known_is_enabled: true,
    trigger_advertising_callbacks_on_first_resume_after_pause_is_enabled: true
  },
  wakelock_manager_data: {
    title: "Bluetooth Wakelock Statistics",
    is_acquired: false,
    is_native: true,
    acquired_count: 1,
    released_count: 1,
    acquired_error_count: 0,
    released_error_count: 0,
    last_acquire_error_code: 0,
    last_release_error_code: 0,
    last_acquired_timestamp_millis: 154,
    last_released_timestamp_millis: 12023892,
    last_interval_millis: 154,
    max_interval_millis: 154,
    min_interval_millis: 154,
    avg_interval_millis: 154,
    total_interval_millis: 154,
    total_time_since_reset_millis: 1836828
  },
  shim_dumpsys_data: {
    title: "----- Shim Dumpsys -----",
    number_of_bundled_schemas: 8
  },
  hci_acl_manager_dumpsys_data: {
    title: "----- Acl Manager Dumpsys -----",
    le_filter_accept_list_count: 0,
    le_filter_accept_list: [

    ],
    le_connectability_state: "ConnectabilityState::DISARMED",
    le_create_connection_timeout_alarms_count: 0
  },
  hci_controller_dumpsys_data: {
    title: "----- Hci Controller Dumpsys -----",
    local_version_information: {
      hci_version: "V_5_0",
      hci_revision: 29305,
      lmp_version: "V_5_0",
      manufacturer_name: 70,
      lmp_subversion: 65491
    },
    acl_buffer_size: {
      data_packet_length: 1021,
      total_num_packets: 6
    },
    sco_buffer_size: {
      data_packet_length: 184,
      total_num_packets: 1
    },
    iso_buffer_size: {
      data_packet_length: 0,
      total_num_packets: 0
    },
    le_buffer_size: {
      data_packet_length: 251,
      total_num_packets: 8
    },
    le_connect_list_size: 64,
    le_resolving_list_size: 32,
    le_maximum_data_length: {
      supported_max_tx_octets: 251,
      supported_max_tx_time: 17040,
      supported_max_rx_octets: 251,
      supported_max_rx_time: 17040
    },
    le_maximum_advertising_data_length: 31,
    le_suggested_default_data_length: 251,
    le_number_supported_advertising_sets: 1,
    le_periodic_advertiser_list_size: 0,
    local_supported_commands: [
      {
        index: 0,
        value: 255
      },
      {
        index: 1,
        value: 255
      },
      {
        index: 2,
        value: 255
      },
      {
        index: 3,
        value: 3
      },
      {
        index: 4,
        value: 204
      },
      {
        index: 5,
        value: 255
      },
      {
        index: 6,
        value: 255
      },
      {
        index: 7,
        value: 255
      },
      {
        index: 8,
        value: 255
      },
      {
        index: 9,
        value: 255
      },
      {
        index: 10,
        value: 252
      },
      {
        index: 11,
        value: 159
      },
      {
        index: 12,
        value: 243
      },
      {
        index: 13,
        value: 15
      },
      {
        index: 14,
        value: 232
      },
      {
        index: 15,
        value: 255
      },
      {
        index: 16,
        value: 63
      },
      {
        index: 17,
        value: 247
      },
      {
        index: 18,
        value: 143
      },
      {
        index: 19,
        value: 255
      },
      {
        index: 20,
        value: 28
      },
      {
        index: 21,
        value: 0
      },
      {
        index: 22,
        value: 4
      },
      {
        index: 23,
        value: 0
      },
      {
        index: 24,
        value: 1
      },
      {
        index: 25,
        value: 0
      },
      {
        index: 26,
        value: 0
      },
      {
        index: 27,
        value: 0
      },
      {
        index: 28,
        value: 0
      },
      {
        index: 29,
        value: 56
      },
      {
        index: 30,
        value: 224
      },
      {
        index: 31,
        value: 245
      },
      {
        index: 32,
        value: 243
      },
      {
        index: 33,
        value: 207
      },
      {
        index: 34,
        value: 255
      },
      {
        index: 35,
        value: 255
      },
      {
        index: 36,
        value: 1
      },
      {
        index: 37,
        value: 0
      },
      {
        index: 38,
        value: 0
      },
      {
        index: 39,
        value: 4
      },
      {
        index: 40,
        value: 0
      },
      {
        index: 41,
        value: 0
      },
      {
        index: 42,
        value: 0
      },
      {
        index: 43,
        value: 0
      },
      {
        index: 44,
        value: 0
      },
      {
        index: 45,
        value: 0
      },
      {
        index: 46,
        value: 0
      },
      {
        index: 47,
        value: 0
      },
      {
        index: 48,
        value: 0
      },
      {
        index: 49,
        value: 0
      },
      {
        index: 50,
        value: 0
      },
      {
        index: 51,
        value: 0
      },
      {
        index: 52,
        value: 0
      },
      {
        index: 53,
        value: 0
      },
      {
        index: 54,
        value: 0
      },
      {
        index: 55,
        value: 0
      },
      {
        index: 56,
        value: 0
      },
      {
        index: 57,
        value: 0
      },
      {
        index: 58,
        value: 0
      },
      {
        index: 59,
        value: 0
      },
      {
        index: 60,
        value: 0
      },
      {
        index: 61,
        value: 0
      },
      {
        index: 62,
        value: 0
      },
      {
        index: 63,
        value: 0
      }
    ],
    extended_lmp_features_array: [
      9753670738334531263,
      2,
      773
    ],
    le_local_supported_features: 98301,
    le_supported_states: 4398046511103,
    vendor_capabilities: {
      is_supported: 1,
      max_advt_instances: 8,
      offloaded_resolution_of_private_address: 0,
      total_scan_results_storage: 1632,
      max_irk_list_sz: 8,
      filtering_support: 1,
      max_filter: 10,
      activity_energy_info_support: 0,
      version_supported: 96,
      total_num_of_advt_tracked: 10,
      extended_scan_support: 0,
      debug_logging_supported: 0,
      le_address_generation_offloading_support: 0,
      a2dp_source_offload_capability_mask: 0,
      bluetooth_quality_report_support: 0
    }
  },
  activity_attribution_dumpsys_data: {
    title_device_wakeup: "----- Device-based Wakeup Attribution Dumpsys -----",
    num_device_wakeup: 0,
    device_wakeup_attribution: [

    ],
    title_device_activity: "----- Device-based Activity Attribution Dumpsys -----",
    num_device_activity: 0,
    device_activity_aggregation: [

    ],
    title_app_wakeup: "----- App-based Wakeup Attribution Dumpsys -----",
    num_app_wakeup: 0,
    app_wakeup_attribution: [

    ],
    title_app_activity: "----- App-based Activity Attribution Dumpsys -----",
    num_app_activity: 0,
    app_activity_aggregation: [

    ]
  }
}
3. Output: Audio event log: audio services lifecycle
05-08 13:48:58:897 AudioService()
05-08 17:08:38:801 onAudioServerDied() audioserver died
05-08 17:08:39:304 onAudioServerDied() audioserver started
05-08 17:08:41:645 after audioserver restart: initStreamVolume succeeded

Message handler (watch for unhandled messages):
  Handler (com.android.server.audio.AudioService$AudioHandler) {280b7bf} @ 12598130
    Looper (AudioService, tid 116) {5849e8c}
      (Total messages: 0, polling=true, quitting=false)

MediaFocusControl dump time: 5:40:30 PM

Audio Focus stack entries (last is top of stack):


No external focus policy



 Notify on duck:  true

 In ring or call: false



Audio event log: focus commands as seen by MediaFocusControl
05-08 17:01:51:275 abandonAudioFocus() from uid/pid 10132/1723 clientId=android.media.AudioManager@bbc47f5
05-08 17:01:54:534 requestAudioFocus() from uid/pid 10132/1723 AA=USAGE_NOTIFICATION/CONTENT_TYPE_SONIFICATION clientId=android.media.AudioManager@edf2afa callingPack=com.android.systemui req=3 flags=0x0 sdk=33
05-08 17:01:58:507 abandonAudioFocus() from uid/pid 10132/1723 clientId=android.media.AudioManager@edf2afa
05-08 17:03:16:256 requestAudioFocus() from uid/pid 10132/1723 AA=USAGE_NOTIFICATION/CONTENT_TYPE_SONIFICATION clientId=android.media.AudioManager@8ca5563 callingPack=com.android.systemui req=3 flags=0x0 sdk=33
05-08 17:03:20:485 abandonAudioFocus() from uid/pid 10132/1723 clientId=android.media.AudioManager@8ca5563
05-08 17:04:11:972 requestAudioFocus() from uid/pid 10132/1723 AA=USAGE_NOTIFICATION/CONTENT_TYPE_SONIFICATION clientId=android.media.AudioManager@a9d23e7 callingPack=com.android.systemui req=3 flags=0x0 sdk=33
05-08 17:04:14:006 abandonAudioFocus() from uid/pid 10132/1723 clientId=android.media.AudioManager@a9d23e7
05-08 17:04:54:129 requestAudioFocus() from uid/pid 10132/1723 AA=USAGE_NOTIFICATION/CONTENT_TYPE_SONIFICATION clientId=android.media.AudioManager@5b90621 callingPack=com.android.systemui req=3 flags=0x0 sdk=33
05-08 17:04:54:637 abandonAudioFocus() from uid/pid 10132/1723 clientId=android.media.AudioManager@5b90621
05-08 17:04:56:709 requestAudioFocus() from uid/pid 10132/1723 AA=USAGE_NOTIFICATION/CONTENT_TYPE_SONIFICATION clientId=android.media.AudioManager@d8c0e98 callingPack=com.android.systemui req=3 flags=0x0 sdk=33
05-08 17:04:59:643 abandonAudioFocus() from uid/pid 10132/1723 clientId=android.media.AudioManager@d8c0e98
05-08 17:05:00:638 requestAudioFocus() from uid/pid 10132/1723 AA=USAGE_NOTIFICATION/CONTENT_TYPE_SONIFICATION clientId=android.media.AudioManager@855f419 callingPack=com.android.systemui req=3 flags=0x0 sdk=33
05-08 17:05:01:153 abandonAudioFocus() from uid/pid 10132/1723 clientId=android.media.AudioManager@855f419
05-08 17:08:47:376 requestAudioFocus() from uid/pid 10132/1723 AA=USAGE_NOTIFICATION/CONTENT_TYPE_SONIFICATION clientId=android.media.AudioManager@df2b9b1 callingPack=com.android.systemui req=3 flags=0x0 sdk=33
05-08 17:08:51:171 abandonAudioFocus() from uid/pid 10132/1723 clientId=android.media.AudioManager@df2b9b1
05-08 17:08:57:599 abandonAudioFocus() from uid/pid 10178/19026 clientId=android.media.AudioManager@31592f1de.danoeh.antennapod.playback.service.internal.LocalPSMP$1@a5b2ed6
05-08 17:08:58:804 abandonAudioFocus() from uid/pid 10178/19026 clientId=android.media.AudioManager@49007cdde.danoeh.antennapod.playback.service.internal.LocalPSMP$1@941f882
05-08 17:09:10:700 abandonAudioFocus() from uid/pid 10591/19002 clientId=android.media.AudioManager@bcc7ea4com.calm.android.audio.AudioFocus$audioFocusListener$1@b80140d
05-08 17:09:45:577 requestAudioFocus() from uid/pid 10166/20909 AA=USAGE_MEDIA/CONTENT_TYPE_MUSIC clientId=android.media.AudioManager@91fded6X.9xC@7fb4557 callingPack=com.whatsapp req=2 flags=0x0 sdk=35
05-08 17:09:48:419 abandonAudioFocus() from uid/pid 10166/20909 clientId=android.media.AudioManager@91fded6X.9xC@7fb4557
05-08 17:09:50:401 requestAudioFocus() from uid/pid 10166/20909 AA=USAGE_MEDIA/CONTENT_TYPE_MUSIC clientId=android.media.AudioManager@91fded6X.9xD@111e0dd callingPack=com.whatsapp req=3 flags=0x0 sdk=35
05-08 17:09:53:190 abandonAudioFocus() from uid/pid 10166/20909 clientId=android.media.AudioManager@91fded6X.9xD@111e0dd
05-08 17:12:04:146 requestAudioFocus() from uid/pid 10132/1723 AA=USAGE_NOTIFICATION/CONTENT_TYPE_SONIFICATION clientId=android.media.AudioManager@9cf1fc9 callingPack=com.android.systemui req=3 flags=0x0 sdk=33
05-08 17:12:08:307 abandonAudioFocus() from uid/pid 10132/1723 clientId=android.media.AudioManager@9cf1fc9
05-08 17:12:32:344 requestAudioFocus() from uid/pid 10166/20909 AA=USAGE_MEDIA/CONTENT_TYPE_MUSIC clientId=android.media.AudioManager@91fded6X.9xC@7fb4557 callingPack=com.whatsapp req=2 flags=0x0 sdk=35
05-08 17:12:33:016 abandonAudioFocus() from uid/pid 10166/20909 clientId=android.media.AudioManager@91fded6X.9xC@7fb4557
05-08 17:12:35:737 requestAudioFocus() from uid/pid 10166/20909 AA=USAGE_MEDIA/CONTENT_TYPE_MUSIC clientId=android.media.AudioManager@91fded6X.9xC@7fb4557 callingPack=com.whatsapp req=2 flags=0x0 sdk=35
05-08 17:12:38:187 abandonAudioFocus() from uid/pid 10166/20909 clientId=android.media.AudioManager@91fded6X.9xC@7fb4557
05-08 17:12:42:204 requestAudioFocus() from uid/pid 10166/20909 AA=USAGE_MEDIA/CONTENT_TYPE_MUSIC clientId=android.media.AudioManager@91fded6X.9xD@4a6b65f callingPack=com.whatsapp req=3 flags=0x0 sdk=35
05-08 17:12:42:669 requestAudioFocus() from uid/pid 10132/1723 AA=USAGE_NOTIFICATION/CONTENT_TYPE_SONIFICATION clientId=android.media.AudioManager@ca1d2fb callingPack=com.android.systemui req=3 flags=0x0 sdk=33
05-08 17:12:43:297 abandonAudioFocus() from uid/pid 10132/1723 clientId=android.media.AudioManager@ca1d2fb
05-08 17:12:44:606 abandonAudioFocus() from uid/pid 10166/20909 clientId=android.media.AudioManager@91fded6X.9xD@4a6b65f
05-08 17:12:45:350 requestAudioFocus() from uid/pid 10166/20909 AA=USAGE_MEDIA/CONTENT_TYPE_MUSIC clientId=android.media.AudioManager@91fded6X.9xD@fbfa2e0 callingPack=com.whatsapp req=3 flags=0x0 sdk=35
05-08 17:12:48:084 abandonAudioFocus() from uid/pid 10166/20909 clientId=android.media.AudioManager@91fded6X.9xD@fbfa2e0
05-08 17:12:48:528 requestAudioFocus() from uid/pid 10166/20909 AA=USAGE_MEDIA/CONTENT_TYPE_MUSIC clientId=android.media.AudioManager@91fded6X.9xD@e470879 callingPack=com.whatsapp req=3 flags=0x0 sdk=35
05-08 17:12:52:003 abandonAudioFocus() from uid/pid 10166/20909 clientId=android.media.AudioManager@91fded6X.9xD@e470879
05-08 17:12:52:661 requestAudioFocus() from uid/pid 10166/20909 AA=USAGE_MEDIA/CONTENT_TYPE_MUSIC clientId=android.media.AudioManager@91fded6X.9xD@451d25d callingPack=com.whatsapp req=3 flags=0x0 sdk=35
05-08 17:12:54:812 abandonAudioFocus() from uid/pid 10166/20909 clientId=android.media.AudioManager@91fded6X.9xD@451d25d
05-08 17:12:55:823 requestAudioFocus() from uid/pid 10166/20909 AA=USAGE_MEDIA/CONTENT_TYPE_MUSIC clientId=android.media.AudioManager@91fded6X.9xD@a133067 callingPack=com.whatsapp req=3 flags=0x0 sdk=35
05-08 17:12:58:534 abandonAudioFocus() from uid/pid 10166/20909 clientId=android.media.AudioManager@91fded6X.9xD@a133067
05-08 17:13:18:335 requestAudioFocus() from uid/pid 10132/1723 AA=USAGE_NOTIFICATION/CONTENT_TYPE_SONIFICATION clientId=android.media.AudioManager@5d6221b callingPack=com.android.systemui req=3 flags=0x0 sdk=33
05-08 17:13:20:693 abandonAudioFocus() from uid/pid 10132/1723 clientId=android.media.AudioManager@5d6221b
05-08 17:14:40:223 requestAudioFocus() from uid/pid 10132/1723 AA=USAGE_NOTIFICATION/CONTENT_TYPE_SONIFICATION clientId=android.media.AudioManager@513df4 callingPack=com.android.systemui req=3 flags=0x0 sdk=33
05-08 17:14:44:823 abandonAudioFocus() from uid/pid 10132/1723 clientId=android.media.AudioManager@513df4
05-08 17:15:25:555 requestAudioFocus() from uid/pid 10132/1723 AA=USAGE_NOTIFICATION/CONTENT_TYPE_SONIFICATION clientId=android.media.AudioManager@450030b callingPack=com.android.systemui req=3 flags=0x0 sdk=33
05-08 17:15:29:527 abandonAudioFocus() from uid/pid 10132/1723 clientId=android.media.AudioManager@450030b
05-08 17:16:59:396 requestAudioFocus() from uid/pid 10132/1723 AA=USAGE_NOTIFICATION/CONTENT_TYPE_SONIFICATION clientId=android.media.AudioManager@358422f callingPack=com.android.systemui req=3 flags=0x0 sdk=33
05-08 17:17:02:416 abandonAudioFocus() from uid/pid 10132/1723 clientId=android.media.AudioManager@358422f
05-08 17:23:44:738 requestAudioFocus() from uid/pid 10621/27384 AA=USAGE_MEDIA/CONTENT_TYPE_MUSIC clientId=android.media.AudioManager@137e99basms@6dde138 callingPack=anddea.youtube.music req=1 flags=0x0 sdk=35
05-08 17:36:52:940 focus requester:android.media.AudioManager@137e99basms@6dde138 in uid:10621 pack:anddea.youtube.music died
Multi Audio Focus enabled :false

Stream volumes (device: index)
- STREAM_VOICE_CALL:
   Muted: false
   Muted Internally: false
   Min: 1
   Max: 9
   streamVolume:4
   Current: 1 (earpiece): 4, 2 (speaker): 1, 4 (headset): 9, 8 (headphone): 9, 10 (bt_sco): 1, 20 (bt_sco_hs): 1, 80 (bt_a2dp): 7, 20000000 (ble_headset): 6, 40000000 (default): 6
   Devices: earpiece(1)
   Volume Group: AUDIO_STREAM_VOICE_CALL

- STREAM_SYSTEM (aliased to: STREAM_RING):
   Muted: true
   Muted Internally: false
   Min: 0
   Max: 7
   streamVolume:0
   Current: 1 (earpiece): 5, 2 (speaker): 1, 4 (headset): 1, 8 (headphone): 5, 80 (bt_a2dp): 1, 40000000 (default): 5
   Devices: speaker(2)
   Volume Group: AUDIO_STREAM_SYSTEM

- STREAM_RING:
   Muted: true
   Muted Internally: false
   Min: 0
   Max: 7
   streamVolume:0
   Current: 1 (earpiece): 5, 2 (speaker): 1, 4 (headset): 1, 8 (headphone): 5, 80 (bt_a2dp): 1, 40000000 (default): 5
   Devices: speaker(2)
   Volume Group: AUDIO_STREAM_RING

- STREAM_MUSIC:
   Muted: false
   Muted Internally: false
   Min: 0
   Max: 15
   streamVolume:5
   Current: 1 (earpiece): 0, 2 (speaker): 5, 4 (headset): 10, 8 (headphone): 10, 10 (bt_sco): 0, 20 (bt_sco_hs): 2, 80 (bt_a2dp): 8, 4000000 (usb_headset): 3, 20000000 (ble_headset): 5, 40000000 (default): 5
   Devices: speaker(2)
   Volume Group: AUDIO_STREAM_MUSIC

- STREAM_ALARM:
   Muted: false
   Muted Internally: false
   Min: 1
   Max: 7
   streamVolume:7
   Current: 1 (earpiece): 6, 2 (speaker): 7, 80 (bt_a2dp): 6, 40000000 (default): 6
   Devices: speaker(2)
   Volume Group: AUDIO_STREAM_ALARM

- STREAM_NOTIFICATION:
   Muted: true
   Muted Internally: false
   Min: 0
   Max: 7
   streamVolume:0
   Current: 1 (earpiece): 5, 2 (speaker): 3, 4 (headset): 5, 8 (headphone): 5, 80 (bt_a2dp): 6, 40000000 (default): 5
   Devices: speaker(2)
   Volume Group: AUDIO_STREAM_NOTIFICATION

- STREAM_BLUETOOTH_SCO:
   Muted: false
   Muted Internally: false
   Min: 0
   Max: 15
   streamVolume:15
   Current: 1 (earpiece): 15, 2 (speaker): 15, 4 (headset): 15, 80 (bt_a2dp): 15, 40000000 (default): 7
   Devices: earpiece(1)
   Volume Group: AUDIO_STREAM_BLUETOOTH_SCO

- STREAM_SYSTEM_ENFORCED (aliased to: STREAM_RING):
   Muted: true
   Muted Internally: false
   Min: 0
   Max: 7
   streamVolume:0
   Current: 1 (earpiece): 5, 2 (speaker): 1, 4 (headset): 1, 8 (headphone): 5, 80 (bt_a2dp): 5, 40000000 (default): 5
   Devices: speaker(2)
   Volume Group: AUDIO_STREAM_ENFORCED_AUDIBLE

- STREAM_DTMF (aliased to: STREAM_RING):
   Muted: true
   Muted Internally: false
   Min: 0
   Max: 15
   streamVolume:0
   Current: 1 (earpiece): 11, 2 (speaker): 2, 4 (headset): 2, 8 (headphone): 11, 10 (bt_sco): 11, 20 (bt_sco_hs): 11, 80 (bt_a2dp): 2, 20000000 (ble_headset): 11, 40000000 (default): 11
   Devices: speaker(2)
   Volume Group: AUDIO_STREAM_DTMF

- STREAM_TTS (aliased to: STREAM_MUSIC):
   Muted: false
   Muted Internally: false
   Min: 0
   Max: 15
   streamVolume:8
   Current: 1 (earpiece): 0, 2 (speaker): 8, 4 (headset): 10, 8 (headphone): 10, 10 (bt_sco): 0, 20 (bt_sco_hs): 2, 80 (bt_a2dp): 8, 4000000 (usb_headset): 3, 20000000 (ble_headset): 5, 40000000 (default): 5
   Devices: speaker(2)
   Volume Group: AUDIO_STREAM_TTS

- STREAM_ACCESSIBILITY (aliased to: STREAM_MUSIC):
   Muted: false
   Muted Internally: false
   Min: 1
   Max: 15
   streamVolume:6
   Current: 1 (earpiece): 1, 2 (speaker): 6, 4 (headset): 10, 8 (headphone): 10, 10 (bt_sco): 1, 20 (bt_sco_hs): 3, 80 (bt_a2dp): 9, 4000000 (usb_headset): 4, 20000000 (ble_headset): 6, 40000000 (default): 6
   Devices: speaker(2)
   Volume Group: AUDIO_STREAM_ACCESSIBILITY

- STREAM_ASSISTANT (aliased to: STREAM_MUSIC):
   Muted: false
   Muted Internally: false
   Min: 0
   Max: 15
   streamVolume:5
   Current: 1 (earpiece): 0, 2 (speaker): 5, 4 (headset): 10, 8 (headphone): 10, 10 (bt_sco): 0, 20 (bt_sco_hs): 2, 80 (bt_a2dp): 8, 4000000 (usb_headset): 3, 20000000 (ble_headset): 5, 40000000 (default): 5
   Devices: speaker(2)
   Volume Group: AUDIO_STREAM_ASSISTANT


- mute affected streams = 0x6f

Volume Groups (device: index)
- VOLUME GROUP AUDIO_STREAM_ACCESSIBILITY:
   Muted: false
   Min: 1
   Max: 15
   Current: 1 (earpiece): 1, 2 (speaker): 6, 4 (headset): 10, 8 (headphone): 10, 10 (bt_sco): 1, 20 (bt_sco_hs): 3, 80 (bt_a2dp): 9, 4000000 (usb_headset): 4, 20000000 (ble_headset): 5, 40000000 (default): 6
   Devices: speaker
   Streams: STREAM_ACCESSIBILITY 
- VOLUME GROUP AUDIO_STREAM_ALARM:
   Muted: false
   Min: 1
   Max: 7
   Current: 2 (speaker): 7, 40000000 (default): 6
   Devices: speaker
   Streams: STREAM_ALARM 
- VOLUME GROUP AUDIO_STREAM_BLUETOOTH_SCO:
   Muted: false
   Min: 0
   Max: 15
   Current: 1 (earpiece): 15, 2 (speaker): 15, 4 (headset): 15, 80 (bt_a2dp): 15, 40000000 (default): 7
   Devices: earpiece
   Streams: STREAM_BLUETOOTH_SCO 
- VOLUME GROUP AUDIO_STREAM_DTMF:
   Muted: false
   Min: 0
   Max: 15
   Current: 1 (earpiece): 6, 2 (speaker): 2, 4 (headset): 2, 8 (headphone): 15, 10 (bt_sco): 0, 20 (bt_sco_hs): 0, 80 (bt_a2dp): 2, 40000000 (default): 11
   Devices: speaker
   Streams: STREAM_DTMF 
- VOLUME GROUP AUDIO_STREAM_ENFORCED_AUDIBLE:
   Muted: false
   Min: 0
   Max: 7
   Current: 2 (speaker): 1, 4 (headset): 1, 8 (headphone): 5, 80 (bt_a2dp): 5, 40000000 (default): 5
   Devices: speaker
   Streams: STREAM_SYSTEM_ENFORCED 
- VOLUME GROUP AUDIO_STREAM_MUSIC:
   Muted: false
   Min: 0
   Max: 15
   Current: 1 (earpiece): 0, 2 (speaker): 5, 4 (headset): 10, 8 (headphone): 10, 10 (bt_sco): 0, 20 (bt_sco_hs): 2, 80 (bt_a2dp): 8, 4000000 (usb_headset): 3, 20000000 (ble_headset): 5, 40000000 (default): 5
   Devices: speaker
   Streams: STREAM_MUSIC 
- VOLUME GROUP AUDIO_STREAM_NOTIFICATION:
   Muted: true
   Min: 0
   Max: 7
   Current: 2 (speaker): 3, 4 (headset): 5, 8 (headphone): 5, 80 (bt_a2dp): 6, 40000000 (default): 5
   Devices: speaker
   Streams: STREAM_NOTIFICATION 
- VOLUME GROUP AUDIO_STREAM_PATCH:
   Muted: false
   Min: 0
   Max: 15
   Current: 40000000 (default): 5
   Devices: speaker
   Streams: UNKNOWN_STREAM_13 
- VOLUME GROUP AUDIO_STREAM_REROUTING:
   Muted: false
   Min: 0
   Max: 15
   Current: 40000000 (default): 5
   Devices: speaker
   Streams: UNKNOWN_STREAM_12 
- VOLUME GROUP AUDIO_STREAM_RING:
   Muted: true
   Min: 0
   Max: 7
   Current: 2 (speaker): 1, 4 (headset): 1, 8 (headphone): 5, 80 (bt_a2dp): 1, 40000000 (default): 5
   Devices: speaker
   Streams: STREAM_RING 
- VOLUME GROUP AUDIO_STREAM_SYSTEM:
   Muted: true
   Min: 0
   Max: 7
   Current: 2 (speaker): 1, 4 (headset): 1, 8 (headphone): 5, 80 (bt_a2dp): 1, 40000000 (default): 5
   Devices: speaker
   Streams: STREAM_SYSTEM 
- VOLUME GROUP AUDIO_STREAM_TTS:
   Muted: false
   Min: 0
   Max: 15
   Current: 1 (earpiece): 0, 2 (speaker): 8, 4 (headset): 10, 8 (headphone): 10, 10 (bt_sco): 0, 20 (bt_sco_hs): 2, 80 (bt_a2dp): 8, 4000000 (usb_headset): 3, 20000000 (ble_headset): 5, 40000000 (default): 5
   Devices: speaker
   Streams: STREAM_TTS 
- VOLUME GROUP AUDIO_STREAM_VOICE_CALL:
   Muted: false
   Min: 1
   Max: 9
   Current: 1 (earpiece): 4, 2 (speaker): 1, 4 (headset): 9, 8 (headphone): 9, 10 (bt_sco): 1, 20 (bt_sco_hs): 1, 80 (bt_a2dp): 7, 20000000 (ble_headset): 6, 40000000 (default): 6
   Devices: earpiece
   Streams: STREAM_VOICE_CALL 
- VOLUME GROUP AUDIO_STREAM_ASSISTANT:
   Muted: false
   Min: 0
   Max: 15
   Current: 1 (earpiece): 0, 2 (speaker): 5, 4 (headset): 10, 8 (headphone): 10, 10 (bt_sco): 0, 20 (bt_sco_hs): 2, 80 (bt_a2dp): 8, 4000000 (usb_headset): 3, 20000000 (ble_headset): 5, 40000000 (default): 5
   Devices: speaker
   Streams: STREAM_ASSISTANT 
- VOLUME GROUP AUDIO_STREAM_CALL_ASSISTANT:
   Muted: false
   Min: 0
   Max: 15
   Current: 40000000 (default): 5
   Devices: speaker
   Streams: UNKNOWN_STREAM_14 

Ringer mode: 
- mode (internal) = VIBRATE
- mode (external) = VIBRATE
- zen mode:ZEN_MODE_OFF
- ringer mode affected streams = 0x1a6 (STREAM_SYSTEM,STREAM_RING,STREAM_NOTIFICATION,STREAM_SYSTEM_ENFORCED,STREAM_DTMF)
- ringer mode muted streams = 0x1a6 (STREAM_SYSTEM,STREAM_RING,STREAM_NOTIFICATION,STREAM_SYSTEM_ENFORCED,STREAM_DTMF)
- delegate = ZenModeHelper

Audio mode: 
- Requested mode = MODE_NORMAL
- Actual mode = MODE_NORMAL
- Mode owner: 
   None
- Mode owner stack: 
   Empty

Audio routes:
  mMainType=0x0
  mBluetoothName=null

Other state:
  mVolumeController=VolumeController(android.os.BinderProxy@e0e59d5,mVisible=false)
  mSafeMediaVolumeState=SAFE_MEDIA_VOLUME_INACTIVE
  mSafeMediaVolumeIndex=100
  mSafeUsbMediaVolumeIndex=30
  mSafeUsbMediaVolumeDbfs=-37.0
  sIndependentA11yVolume=false
  mPendingVolumeCommand=null
  mMusicActiveMs=28096700
  mMcc=603
  mCameraSoundForced=false
  mHasVibrator=true
  mVolumePolicy=VolumePolicy[volumeDownToEnterSilent=false,volumeUpToExitSilent=false,doNotDisturbWhenSilent=false,vibrateToSilentDebounce=400]
  mAvrcpAbsVolSupported=false
  mBtScoOnByApp=false
  mIsSingleVolume=false
  mUseFixedVolume=false
  mNotifAliasRing=false
  mFixedVolumeDevices=0x200000
  mFullVolumeDevices=0x40000,0x40001
  mAbsoluteVolumeDevices.keySet()=
  mExtVolumeController=null
  mHdmiAudioSystemClient=null
  mHdmiPlaybackClient=null
  mHdmiTvClient=null
  mHdmiSystemAudioSupported=false
  mHdmiCecVolumeControlEnabled=false
  mIsCallScreeningModeSupported=true
  mic mute FromSwitch=false FromRestrictions=false FromApi=false from system=false  mCurrentImeUid=0
  Accessibility service Uids:
  - 10593
  - 10161
  Assistant service UIDs:
  - 10102

Audio policies:
Audio event log: dynamic policy events (logged when command received by AudioService)

PlaybackActivityMonitor dump time: 5:40:30 PM

  playback listeners:
 (S)com.android.server.audio.PlaybackActivityMonitor$PlayMonitorClient@b3955ea (S)com.android.server.audio.PlaybackActivityMonitor$PlayMonitorClient@c9310db (S)com.android.server.audio.PlaybackActivityMonitor$PlayMonitorClient@e231778


  players:
(not logged)  AudioPlaybackConfiguration piid:111 deviceId:0 type:android.media.SoundPool u/pid:1000/1448 state:idle attr:AudioAttributes: usage=USAGE_ASSISTANCE_SONIFICATION content=CONTENT_TYPE_SONIFICATION flags=0x800 tags= bundle=null sessionId:0
  AudioPlaybackConfiguration piid:119 deviceId:0 type:android.media.SoundPool u/pid:10132/1723 state:idle attr:AudioAttributes: usage=USAGE_ASSISTANCE_SONIFICATION content=CONTENT_TYPE_SONIFICATION flags=0x800 tags= bundle=null sessionId:0
  AudioPlaybackConfiguration piid:89231 deviceId:0 type:android.media.SoundPool u/pid:10491/32450 state:idle attr:AudioAttributes: usage=USAGE_ASSISTANCE_SONIFICATION content=CONTENT_TYPE_SONIFICATION flags=0x800 tags= bundle=null sessionId:0
  AudioPlaybackConfiguration piid:89239 deviceId:0 type:android.media.SoundPool u/pid:10158/31306 state:idle attr:AudioAttributes: usage=USAGE_ASSISTANCE_SONIFICATION content=CONTENT_TYPE_SONIFICATION flags=0x800 tags= bundle=null sessionId:0

  ducked players piids:

  faded out players piids:

  muted player piids due to call/ring:

  banned uids:


  muted players (piids) awaiting device connection:

Audio event log: playback activity as reported through PlayerBase
05-08 17:18:21:334 player piid:88999 new AudioAttributes:AudioAttributes: usage=USAGE_NOTIFICATION_RINGTONE content=CONTENT_TYPE_SONIFICATION flags=0x800 tags= bundle=null
05-08 17:18:21:355 new player piid:89007 uid/pid:10246/22084 type:android.media.MediaPlayer attr:AudioAttributes: usage=USAGE_UNKNOWN content=CONTENT_TYPE_UNKNOWN flags=0x800 tags= bundle=null session:0
05-08 17:18:21:374 player piid:89007 new AudioAttributes:AudioAttributes: usage=USAGE_NOTIFICATION_RINGTONE content=CONTENT_TYPE_SONIFICATION flags=0x800 tags= bundle=null
05-08 17:18:21:396 new player piid:89015 uid/pid:10246/22084 type:android.media.MediaPlayer attr:AudioAttributes: usage=USAGE_UNKNOWN content=CONTENT_TYPE_UNKNOWN flags=0x800 tags= bundle=null session:0
05-08 17:18:21:416 player piid:89015 new AudioAttributes:AudioAttributes: usage=USAGE_NOTIFICATION_RINGTONE content=CONTENT_TYPE_SONIFICATION flags=0x800 tags= bundle=null
05-08 17:18:21:437 new player piid:89023 uid/pid:10246/22084 type:android.media.MediaPlayer attr:AudioAttributes: usage=USAGE_UNKNOWN content=CONTENT_TYPE_UNKNOWN flags=0x800 tags= bundle=null session:0
05-08 17:18:21:449 player piid:89023 new AudioAttributes:AudioAttributes: usage=USAGE_NOTIFICATION_RINGTONE content=CONTENT_TYPE_SONIFICATION flags=0x800 tags= bundle=null
05-08 17:18:21:467 new player piid:89031 uid/pid:10246/22084 type:android.media.MediaPlayer attr:AudioAttributes: usage=USAGE_UNKNOWN content=CONTENT_TYPE_UNKNOWN flags=0x800 tags= bundle=null session:0
05-08 17:18:21:479 player piid:89031 new AudioAttributes:AudioAttributes: usage=USAGE_NOTIFICATION_RINGTONE content=CONTENT_TYPE_SONIFICATION flags=0x800 tags= bundle=null
05-08 17:18:51:951 releasing player piid:89031
05-08 17:18:51:971 releasing player piid:89023
05-08 17:18:51:981 releasing player piid:89015
05-08 17:18:51:985 releasing player piid:89007
05-08 17:18:51:993 releasing player piid:88999
05-08 17:18:51:997 releasing player piid:88991
05-08 17:18:52:008 releasing player piid:88983
05-08 17:18:52:036 releasing player piid:88975
05-08 17:18:52:042 releasing player piid:88967
05-08 17:18:52:052 releasing player piid:88959
05-08 17:18:52:063 releasing player piid:88951
05-08 17:18:52:072 releasing player piid:88943
05-08 17:18:52:082 releasing player piid:88935
05-08 17:18:52:088 releasing player piid:88927
05-08 17:18:52:093 releasing player piid:88919
05-08 17:18:52:112 releasing player piid:88911
05-08 17:18:52:129 releasing player piid:88903
05-08 17:23:23:014 new player piid:89039 uid/pid:10246/22084 type:android.media.MediaPlayer attr:AudioAttributes: usage=USAGE_UNKNOWN content=CONTENT_TYPE_UNKNOWN flags=0x800 tags= bundle=null session:0
05-08 17:23:23:164 player piid:89039 new AudioAttributes:AudioAttributes: usage=USAGE_NOTIFICATION_RINGTONE content=CONTENT_TYPE_SONIFICATION flags=0x800 tags= bundle=null
05-08 17:23:23:297 new player piid:89047 uid/pid:10246/22084 type:android.media.MediaPlayer attr:AudioAttributes: usage=USAGE_UNKNOWN content=CONTENT_TYPE_UNKNOWN flags=0x800 tags= bundle=null session:0
05-08 17:23:23:310 player piid:89047 new AudioAttributes:AudioAttributes: usage=USAGE_NOTIFICATION_RINGTONE content=CONTENT_TYPE_SONIFICATION flags=0x800 tags= bundle=null
05-08 17:23:23:328 new player piid:89055 uid/pid:10246/22084 type:android.media.MediaPlayer attr:AudioAttributes: usage=USAGE_UNKNOWN content=CONTENT_TYPE_UNKNOWN flags=0x800 tags= bundle=null session:0
05-08 17:23:23:340 player piid:89055 new AudioAttributes:AudioAttributes: usage=USAGE_NOTIFICATION_RINGTONE content=CONTENT_TYPE_SONIFICATION flags=0x800 tags= bundle=null
05-08 17:23:23:359 new player piid:89063 uid/pid:10246/22084 type:android.media.MediaPlayer attr:AudioAttributes: usage=USAGE_UNKNOWN content=CONTENT_TYPE_UNKNOWN flags=0x800 tags= bundle=null session:0
05-08 17:23:23:370 player piid:89063 new AudioAttributes:AudioAttributes: usage=USAGE_NOTIFICATION_RINGTONE content=CONTENT_TYPE_SONIFICATION flags=0x800 tags= bundle=null
05-08 17:23:23:386 new player piid:89071 uid/pid:10246/22084 type:android.media.MediaPlayer attr:AudioAttributes: usage=USAGE_UNKNOWN content=CONTENT_TYPE_UNKNOWN flags=0x800 tags= bundle=null session:0
05-08 17:23:23:397 player piid:89071 new AudioAttributes:AudioAttributes: usage=USAGE_NOTIFICATION_RINGTONE content=CONTENT_TYPE_SONIFICATION flags=0x800 tags= bundle=null
05-08 17:23:23:416 new player piid:89079 uid/pid:10246/22084 type:android.media.MediaPlayer attr:AudioAttributes: usage=USAGE_UNKNOWN content=CONTENT_TYPE_UNKNOWN flags=0x800 tags= bundle=null session:0
05-08 17:23:23:551 player piid:89079 new AudioAttributes:AudioAttributes: usage=USAGE_NOTIFICATION_RINGTONE content=CONTENT_TYPE_SONIFICATION flags=0x800 tags= bundle=null
05-08 17:23:23:575 new player piid:89087 uid/pid:10246/22084 type:android.media.MediaPlayer attr:AudioAttributes: usage=USAGE_UNKNOWN content=CONTENT_TYPE_UNKNOWN flags=0x800 tags= bundle=null session:0
05-08 17:23:23:590 player piid:89087 new AudioAttributes:AudioAttributes: usage=USAGE_NOTIFICATION_RINGTONE content=CONTENT_TYPE_SONIFICATION flags=0x800 tags= bundle=null
05-08 17:23:23:616 new player piid:89095 uid/pid:10246/22084 type:android.media.MediaPlayer attr:AudioAttributes: usage=USAGE_UNKNOWN content=CONTENT_TYPE_UNKNOWN flags=0x800 tags= bundle=null session:0
05-08 17:23:23:633 player piid:89095 new AudioAttributes:AudioAttributes: usage=USAGE_NOTIFICATION_RINGTONE content=CONTENT_TYPE_SONIFICATION flags=0x800 tags= bundle=null
05-08 17:23:23:660 new player piid:89103 uid/pid:10246/22084 type:android.media.MediaPlayer attr:AudioAttributes: usage=USAGE_UNKNOWN content=CONTENT_TYPE_UNKNOWN flags=0x800 tags= bundle=null session:0
05-08 17:23:23:676 player piid:89103 new AudioAttributes:AudioAttributes: usage=USAGE_NOTIFICATION_RINGTONE content=CONTENT_TYPE_SONIFICATION flags=0x800 tags= bundle=null
05-08 17:23:23:702 new player piid:89111 uid/pid:10246/22084 type:android.media.MediaPlayer attr:AudioAttributes: usage=USAGE_UNKNOWN content=CONTENT_TYPE_UNKNOWN flags=0x800 tags= bundle=null session:0
05-08 17:23:23:720 player piid:89111 new AudioAttributes:AudioAttributes: usage=USAGE_NOTIFICATION_RINGTONE content=CONTENT_TYPE_SONIFICATION flags=0x800 tags= bundle=null
05-08 17:23:23:736 new player piid:89119 uid/pid:10246/22084 type:android.media.MediaPlayer attr:AudioAttributes: usage=USAGE_UNKNOWN content=CONTENT_TYPE_UNKNOWN flags=0x800 tags= bundle=null session:0
05-08 17:23:23:747 player piid:89119 new AudioAttributes:AudioAttributes: usage=USAGE_NOTIFICATION_RINGTONE content=CONTENT_TYPE_SONIFICATION flags=0x800 tags= bundle=null
05-08 17:23:23:765 new player piid:89127 uid/pid:10246/22084 type:android.media.MediaPlayer attr:AudioAttributes: usage=USAGE_UNKNOWN content=CONTENT_TYPE_UNKNOWN flags=0x800 tags= bundle=null session:0
05-08 17:23:23:776 player piid:89127 new AudioAttributes:AudioAttributes: usage=USAGE_NOTIFICATION_RINGTONE content=CONTENT_TYPE_SONIFICATION flags=0x800 tags= bundle=null
05-08 17:23:23:792 new player piid:89135 uid/pid:10246/22084 type:android.media.MediaPlayer attr:AudioAttributes: usage=USAGE_UNKNOWN content=CONTENT_TYPE_UNKNOWN flags=0x800 tags= bundle=null session:0
05-08 17:23:23:801 player piid:89135 new AudioAttributes:AudioAttributes: usage=USAGE_NOTIFICATION_RINGTONE content=CONTENT_TYPE_SONIFICATION flags=0x800 tags= bundle=null
05-08 17:23:23:822 new player piid:89143 uid/pid:10246/22084 type:android.media.MediaPlayer attr:AudioAttributes: usage=USAGE_UNKNOWN content=CONTENT_TYPE_UNKNOWN flags=0x800 tags= bundle=null session:0
05-08 17:23:23:838 player piid:89143 new AudioAttributes:AudioAttributes: usage=USAGE_NOTIFICATION_RINGTONE content=CONTENT_TYPE_SONIFICATION flags=0x800 tags= bundle=null
05-08 17:23:23:860 new player piid:89151 uid/pid:10246/22084 type:android.media.MediaPlayer attr:AudioAttributes: usage=USAGE_UNKNOWN content=CONTENT_TYPE_UNKNOWN flags=0x800 tags= bundle=null session:0
05-08 17:23:23:870 player piid:89151 new AudioAttributes:AudioAttributes: usage=USAGE_NOTIFICATION_RINGTONE content=CONTENT_TYPE_SONIFICATION flags=0x800 tags= bundle=null
05-08 17:23:23:893 new player piid:89159 uid/pid:10246/22084 type:android.media.MediaPlayer attr:AudioAttributes: usage=USAGE_UNKNOWN content=CONTENT_TYPE_UNKNOWN flags=0x800 tags= bundle=null session:0
05-08 17:23:23:905 player piid:89159 new AudioAttributes:AudioAttributes: usage=USAGE_NOTIFICATION_RINGTONE content=CONTENT_TYPE_SONIFICATION flags=0x800 tags= bundle=null
05-08 17:23:23:923 new player piid:89167 uid/pid:10246/22084 type:android.media.MediaPlayer attr:AudioAttributes: usage=USAGE_UNKNOWN content=CONTENT_TYPE_UNKNOWN flags=0x800 tags= bundle=null session:0
05-08 17:23:23:936 player piid:89167 new AudioAttributes:AudioAttributes: usage=USAGE_NOTIFICATION_RINGTONE content=CONTENT_TYPE_SONIFICATION flags=0x800 tags= bundle=null
05-08 17:23:25:360 releasing player piid:89047
05-08 17:23:25:361 releasing player piid:89103
05-08 17:23:25:361 releasing player piid:89111
05-08 17:23:25:361 releasing player piid:89119
05-08 17:23:25:361 releasing player piid:89135
05-08 17:23:25:361 releasing player piid:89143
05-08 17:23:25:361 releasing player piid:89039
05-08 17:23:25:361 releasing player piid:89071
05-08 17:23:25:362 releasing player piid:89127
05-08 17:23:25:362 releasing player piid:89159
05-08 17:23:25:363 releasing player piid:89087
05-08 17:23:25:364 releasing player piid:89055
05-08 17:23:25:364 releasing player piid:89095
05-08 17:23:25:365 releasing player piid:89167
05-08 17:23:25:367 releasing player piid:89079
05-08 17:23:25:370 releasing player piid:89151
05-08 17:23:25:370 releasing player piid:89063
05-08 17:23:44:663 new player piid:89175 uid/pid:10621/27384 type:android.media.AudioTrack attr:AudioAttributes: usage=USAGE_MEDIA content=CONTENT_TYPE_MUSIC flags=0xA00 tags= bundle=null session:89337
05-08 17:23:44:677 player piid:89175 state:started DeviceId:0
05-08 17:23:44:695 player piid:89175 state:device DeviceId:0
05-08 17:24:30:955 new player piid:89183 uid/pid:10491/27808 type:android.media.SoundPool attr:AudioAttributes: usage=USAGE_ASSISTANCE_SONIFICATION content=CONTENT_TYPE_SONIFICATION flags=0x800 tags= bundle=null session:0
05-08 17:27:00:780 releasing player piid:89183
05-08 17:27:19:605 player piid:89175 state:stopped DeviceId:0
05-08 17:27:47:478 player piid:89175 state:stopped DeviceId:0
05-08 17:27:47:478 releasing player piid:89175
05-08 17:27:47:898 new player piid:89191 uid/pid:10621/27384 type:android.media.AudioTrack attr:AudioAttributes: usage=USAGE_MEDIA content=CONTENT_TYPE_MUSIC flags=0xA00 tags= bundle=null session:89337
05-08 17:27:47:900 player piid:89191 state:started DeviceId:0
05-08 17:27:47:908 player piid:89191 state:device DeviceId:0
05-08 17:29:22:790 player piid:89191 state:paused DeviceId:0
05-08 17:36:52:941 releasing player piid:89191
05-08 17:37:12:389 new player piid:89199 uid/pid:10158/31306 type:android.media.SoundPool attr:AudioAttributes: usage=USAGE_ASSISTANCE_SONIFICATION content=CONTENT_TYPE_SONIFICATION flags=0x800 tags= bundle=null session:0
05-08 17:37:29:149 releasing player piid:89199
05-08 17:37:47:127 new player piid:89207 uid/pid:10158/31306 type:android.media.SoundPool attr:AudioAttributes: usage=USAGE_ASSISTANCE_SONIFICATION content=CONTENT_TYPE_SONIFICATION flags=0x800 tags= bundle=null session:0
05-08 17:37:51:685 releasing player piid:89207
05-08 17:38:36:378 new player piid:89215 uid/pid:10158/31306 type:android.media.SoundPool attr:AudioAttributes: usage=USAGE_ASSISTANCE_SONIFICATION content=CONTENT_TYPE_SONIFICATION flags=0x800 tags= bundle=null session:0
05-08 17:38:47:428 releasing player piid:89215
05-08 17:38:56:205 new player piid:89223 uid/pid:10158/31306 type:android.media.SoundPool attr:AudioAttributes: usage=USAGE_ASSISTANCE_SONIFICATION content=CONTENT_TYPE_SONIFICATION flags=0x800 tags= bundle=null session:0
05-08 17:39:26:795 releasing player piid:89223
05-08 17:39:45:029 new player piid:89231 uid/pid:10491/32450 type:android.media.SoundPool attr:AudioAttributes: usage=USAGE_ASSISTANCE_SONIFICATION content=CONTENT_TYPE_SONIFICATION flags=0x800 tags= bundle=null session:0
05-08 17:40:11:686 new player piid:89239 uid/pid:10158/31306 type:android.media.SoundPool attr:AudioAttributes: usage=USAGE_ASSISTANCE_SONIFICATION content=CONTENT_TYPE_SONIFICATION flags=0x800 tags= bundle=null session:0

  allowed capture policies:

RecordActivityMonitor dump time: 5:40:30 PM


Audio event log: recording activity received by AudioService
05-08 13:50:27:737 rec update riid:159 uid:10166 session:201 src:MIC not silenced pack:com.whatsapp
05-08 13:50:27:898 rec update riid:167 uid:10166 session:209 src:MIC not silenced pack:com.whatsapp
05-08 13:50:30:941 rec stop riid:159 uid:10166 session:201 src:MIC not silenced pack:com.whatsapp
05-08 13:50:31:057 rec stop riid:167 uid:10166 session:209 src:MIC not silenced pack:com.whatsapp
05-08 13:50:40:335 rec update riid:183 uid:10166 session:257 src:MIC not silenced pack:com.whatsapp
05-08 13:50:40:449 rec update riid:191 uid:10166 session:265 src:MIC not silenced pack:com.whatsapp
05-08 13:50:42:239 rec stop riid:183 uid:10166 session:257 src:MIC not silenced pack:com.whatsapp
05-08 13:50:42:325 rec stop riid:191 uid:10166 session:265 src:MIC not silenced pack:com.whatsapp
05-08 16:58:47:949 rec update riid:9255 uid:10166 session:9913 src:VOICE_COMMUNICATION not silenced pack:com.whatsapp
05-08 16:59:40:768 rec stop riid:9255 uid:10166 session:9913 src:VOICE_COMMUNICATION not silenced pack:com.whatsapp
05-08 17:09:45:882 rec update riid:87183 uid:10166 session:87201 src:MIC not silenced pack:com.whatsapp
05-08 17:09:46:035 rec update riid:87191 uid:10166 session:87209 src:MIC not silenced pack:com.whatsapp
05-08 17:09:48:294 rec stop riid:87183 uid:10166 session:87201 src:MIC not silenced pack:com.whatsapp
05-08 17:09:48:373 rec stop riid:87191 uid:10166 session:87209 src:MIC not silenced pack:com.whatsapp
05-08 17:12:36:015 rec update riid:87567 uid:10166 session:87713 src:MIC not silenced pack:com.whatsapp
05-08 17:12:36:183 rec update riid:87575 uid:10166 session:87721 src:MIC not silenced pack:com.whatsapp
05-08 17:12:38:089 rec stop riid:87567 uid:10166 session:87713 src:MIC not silenced pack:com.whatsapp
05-08 17:12:38:162 rec stop riid:87575 uid:10166 session:87721 src:MIC not silenced pack:com.whatsapp

AudioDeviceBroker:
  Message handler (watch for unhandled messages):
    Handler (com.android.server.audio.AudioDeviceBroker$BrokerHandler) {4e7be51} @ 12598213
      Looper (AudioDeviceBroker, tid 117) {64ee6b6}
        (Total messages: 0, polling=true, quitting=false)

  BECOMING_NOISY_INTENT_DEVICES_SET=
 0x400 0x800 0x8000000 0x20000000 0x80 0x100 0x200 0x2000 0x4000 0x4000000 0x20000001 0x20000 0x20000002 0x4 0x8
  Preferred devices for strategy:

  Connected devices:

  APM Connected device (A2DP sink only):

  Communication route clients:

  Computed Preferred communication device: null

  Applied Preferred communication device: null
  Active communication device: AudioDeviceAttributes: role:output type:earpiece addr: name:220233L2G profiles:[{ENCODING_PCM_16BIT, sampling rates=[44100, 48000], channel masks=0x04, encapsulation type=0}, {ENCODING_PCM_32BIT, sampling rates=[44100, 48000], channel masks=0x04, encapsulation type=0}, {ENCODING_PCM_FLOAT, sampling rates=[44100, 48000], channel masks=0x04, encapsulation type=0}] descriptors:[]
  mCommunicationStrategyId: 14
  mAccessibilityStrategyId: 17

  mAudioModeOwner: AudioModeInfo: mMode=MODE_NORMAL, mPid=0, mUid=0

  mBluetoothHeadset: android.bluetooth.BluetoothHeadset@a7dfb7
  mBluetoothHeadsetDevice: null
  mScoAudioState: SCO_STATE_INACTIVE
  mScoAudioMode: SCO_MODE_VIRTUAL_CALL

  mHearingAid: null

  mLeAudio: null
  mA2dp: android.bluetooth.BluetoothA2dp@c2e3324
  mAvrcpAbsVolSupported: false

SoundEffects:
  Message handler (watch for unhandled messages):
  Handler (com.android.server.audio.SoundEffectsHelper$SfxHandler) {518ee8d} @ 12598228
    Looper (AS.SfxWorker, tid 115) {25ab842}
      (Total messages: 0, polling=true, quitting=false)
  Default attenuation (dB): -6
Audio event log: Sound Effects Loading
05-08 13:49:01:892 effects loading started
05-08 13:49:02:803 effect Effect_Tick.ogg loaded
05-08 13:49:02:815 effect KeypressStandard.ogg loaded
05-08 13:49:02:898 effect KeypressSpacebar.ogg loaded
05-08 13:49:02:904 effect KeypressDelete.ogg loaded
05-08 13:49:02:995 effect KeypressReturn.ogg loaded
05-08 13:49:03:001 effect KeypressInvalid.ogg loaded
05-08 13:49:03:002 effects loading completed



Event logs:
Audio event log: phone state (logged after successful call to AudioSystem.setPhoneState(int, int))
05-08 13:53:15:666 setMode(MODE_IN_COMMUNICATION) from package=com.facebook.orca pid=3967 selected mode=MODE_IN_COMMUNICATION by pid=3967
05-08 13:53:21:540 setMode(MODE_NORMAL) from package=android pid=1448 selected mode=MODE_NORMAL by pid=0
05-08 13:53:22:250 setMode(MODE_IN_COMMUNICATION) from package=android pid=1448 selected mode=MODE_IN_COMMUNICATION by pid=3967
05-08 13:53:37:808 setMode(MODE_NORMAL) from package=com.facebook.orca pid=3967 selected mode=MODE_NORMAL by pid=0
05-08 16:27:49:267 setMode(MODE_RINGTONE) from package=com.whatsapp pid=20634 selected mode=MODE_RINGTONE by pid=20634
05-08 16:28:34:055 setMode(MODE_NORMAL) from package=com.whatsapp pid=20634 selected mode=MODE_NORMAL by pid=0
05-08 16:58:47:349 setMode(MODE_IN_COMMUNICATION) from package=com.whatsapp pid=27984 selected mode=MODE_IN_COMMUNICATION by pid=27984
05-08 16:59:41:062 setMode(MODE_NORMAL) from package=com.whatsapp pid=27984 selected mode=MODE_NORMAL by pid=0
05-08 17:08:41:343 setMode(MODE_NORMAL) from package=android pid=1448 selected mode=MODE_NORMAL by pid=0


Audio event log: wired/A2DP/hearing aid device connection
05-08 14:14:54:622 dropping ACTION_AUDIO_BECOMING_NOISY
05-08 14:14:54:655 BT connected: addr=41:42:B2:14:0C:C4 profile=2 state=0 codec=AUDIO_FORMAT_AAC
05-08 14:14:54:719 A2DP device addr=41:42:B2:14:0C:C4 made unavailable
05-08 16:28:34:070 onUpdateCommunicationRoute, preferredCommunicationDevice: null eventSource: setNewModeOwner
05-08 16:28:34:093 removePreferredDevicesForStrategySync, strategy: 14
05-08 16:28:34:093 removePreferredDevicesForStrategySync, strategy: 17
05-08 16:55:42:802 msg: onBluetoothActiveDeviceChange  state=2 addr=41:42:B2:14:0C:C4 prof=2 supprNoisy=true src=AudioService
05-08 16:55:42:820 BT connected: addr=41:42:B2:14:0C:C4 profile=2 state=2 codec=AUDIO_FORMAT_AAC
05-08 16:55:43:026 A2DP device addr=41:42:B2:14:0C:C4 now available
05-08 16:55:43:169 onBluetoothA2dpDeviceConfigChange addr=41:42:B2:14:0C:C4 event=DEVICE_CONFIG_CHANGE
05-08 16:55:43:274 APM handleDeviceConfigChange success for A2DP device addr=41:42:B2:14:0C:C4 codec=AUDIO_FORMAT_AAC
05-08 16:55:43:296 onBluetoothA2dpDeviceConfigChange addr=41:42:B2:14:0C:C4 event=DEVICE_CONFIG_CHANGE
05-08 16:55:43:395 APM handleDeviceConfigChange success for A2DP device addr=41:42:B2:14:0C:C4 codec=AUDIO_FORMAT_AAC
05-08 16:58:47:408 onUpdateCommunicationRoute, preferredCommunicationDevice: null eventSource: setNewModeOwner
05-08 16:58:47:438 removePreferredDevicesForStrategySync, strategy: 14
05-08 16:58:47:438 removePreferredDevicesForStrategySync, strategy: 17
05-08 16:59:41:099 onUpdateCommunicationRoute, preferredCommunicationDevice: null eventSource: setNewModeOwner
05-08 16:59:41:104 removePreferredDevicesForStrategySync, strategy: 14
05-08 16:59:41:105 removePreferredDevicesForStrategySync, strategy: 17
05-08 17:08:41:485 onUpdateCommunicationRoute, preferredCommunicationDevice: null eventSource: MSG_RESTORE_DEVICES
05-08 17:08:41:489 removePreferredDevicesForStrategySync, strategy: 14
05-08 17:08:41:490 removePreferredDevicesForStrategySync, strategy: 17
05-08 17:08:41:512 onUpdateCommunicationRoute, preferredCommunicationDevice: null eventSource: setNewModeOwner
05-08 17:08:41:515 removePreferredDevicesForStrategySync, strategy: 14
05-08 17:08:41:517 removePreferredDevicesForStrategySync, strategy: 17
05-08 17:08:45:693 dropping ACTION_AUDIO_BECOMING_NOISY
05-08 17:08:45:790 A2DP device addr=41:42:B2:14:0C:C4 made unavailable
05-08 17:08:45:797 onUpdateCommunicationRoute, preferredCommunicationDevice: null eventSource: resetBluetoothSco
05-08 17:08:45:805 BT profile service: disconnecting A2DP profile
05-08 17:08:45:805 BT profile service: disconnecting A2DP profile
05-08 17:08:45:817 removePreferredDevicesForStrategySync, strategy: 14
05-08 17:08:45:818 removePreferredDevicesForStrategySync, strategy: 17
05-08 17:08:45:843 msg: onBluetoothActiveDeviceChange  state=0 addr=41:42:B2:14:0C:C4 prof=2 supprNoisy=false src=AudioService
05-08 17:08:45:938 BT profile service: disconnecting HEADSET profile
05-08 17:08:45:938 BT profile service: disconnecting HEADSET profile
05-08 17:08:45:953 BT connected: addr=41:42:B2:14:0C:C4 profile=2 state=0 codec=AUDIO_FORMAT_DEFAULT
05-08 17:08:49:241 BT profile service: connecting HEADSET profile
05-08 17:08:49:242 BT profile service: connecting A2DP profile
05-08 17:08:51:405 msg: onBluetoothActiveDeviceChange  state=2 addr=41:42:B2:14:0C:C4 prof=2 supprNoisy=true src=AudioService
05-08 17:08:51:432 BT connected: addr=41:42:B2:14:0C:C4 profile=2 state=2 codec=AUDIO_FORMAT_AAC
05-08 17:08:52:008 A2DP device addr=41:42:B2:14:0C:C4 now available
05-08 17:08:52:039 onBluetoothA2dpDeviceConfigChange addr=41:42:B2:14:0C:C4 event=DEVICE_CONFIG_CHANGE
05-08 17:08:52:185 APM handleDeviceConfigChange success for A2DP device addr=41:42:B2:14:0C:C4 codec=AUDIO_FORMAT_AAC
05-08 17:29:25:035 onUpdateCommunicationRoute, preferredCommunicationDevice: null eventSource: resetBluetoothSco
05-08 17:29:25:042 removePreferredDevicesForStrategySync, strategy: 14
05-08 17:29:25:043 removePreferredDevicesForStrategySync, strategy: 17
05-08 17:29:25:130 msg: onBluetoothActiveDeviceChange  state=0 addr=41:42:B2:14:0C:C4 prof=2 supprNoisy=false src=AudioService
05-08 17:29:25:169 broadcast ACTION_AUDIO_BECOMING_NOISY
05-08 17:29:26:169 BT connected: addr=41:42:B2:14:0C:C4 profile=2 state=0 codec=AUDIO_FORMAT_AAC
05-08 17:29:26:272 A2DP device addr=41:42:B2:14:0C:C4 made unavailable


Audio event log: force use (logged before setForceUse() is executed)
05-08 16:28:34:081 setForceUse(FOR_VIBRATE_RINGING, FORCE_NONE) due to muteRingerModeStreams() from u/pid:1000/1448
05-08 16:28:34:117 setForceUse(FOR_VIBRATE_RINGING, FORCE_NONE) due to muteRingerModeStreams() from u/pid:1000/1448
05-08 16:55:30:437 setForceUse(FOR_VIBRATE_RINGING, FORCE_NONE) due to muteRingerModeStreams() from u/pid:1000/1448
05-08 16:55:42:825 setForceUse(FOR_MEDIA, FORCE_NONE) due to setBluetoothA2dpOn(true) from u/pid:1000/1448 src:onSetBtActiveDevice
05-08 16:58:48:219 setForceUse(FOR_VIBRATE_RINGING, FORCE_NONE) due to muteRingerModeStreams() from u/pid:1000/1448
05-08 16:58:48:298 setForceUse(FOR_VIBRATE_RINGING, FORCE_NONE) due to muteRingerModeStreams() from u/pid:1000/1448
05-08 16:59:41:357 setForceUse(FOR_VIBRATE_RINGING, FORCE_NONE) due to muteRingerModeStreams() from u/pid:1000/1448
05-08 16:59:41:446 setForceUse(FOR_VIBRATE_RINGING, FORCE_NONE) due to muteRingerModeStreams() from u/pid:1000/1448
05-08 17:08:41:535 setForceUse(FOR_SYSTEM, FORCE_NONE) due to onAudioServerDied
05-08 17:08:41:537 setForceUse(FOR_MEDIA, FORCE_NONE) due to onAudioServerDied()
05-08 17:08:41:778 setForceUse(FOR_DOCK, FORCE_DIGITAL_DOCK) due to onAudioServerDied
05-08 17:08:41:808 setForceUse(FOR_ENCODED_SURROUND, FORCE_NONE) due to onAudioServerDied
05-08 17:08:41:998 setForceUse(FOR_VIBRATE_RINGING, FORCE_NONE) due to muteRingerModeStreams() from u/pid:1000/1448
05-08 17:08:42:264 setForceUse(FOR_VIBRATE_RINGING, FORCE_NONE) due to muteRingerModeStreams() from u/pid:1000/1448
05-08 17:08:42:265 setForceUse(FOR_VIBRATE_RINGING, FORCE_NONE) due to muteRingerModeStreams() from u/pid:1000/1448
05-08 17:08:42:268 setForceUse(FOR_VIBRATE_RINGING, FORCE_NONE) due to muteRingerModeStreams() from u/pid:1000/1448
05-08 17:08:46:095 setForceUse(FOR_VIBRATE_RINGING, FORCE_NONE) due to muteRingerModeStreams() from u/pid:1000/1448
05-08 17:08:51:461 setForceUse(FOR_MEDIA, FORCE_NONE) due to setBluetoothA2dpOn(true) from u/pid:1000/1448 src:onSetBtActiveDevice
05-08 17:17:04:446 setForceUse(FOR_VIBRATE_RINGING, FORCE_NONE) due to muteRingerModeStreams() from u/pid:1000/1448
05-08 17:29:25:052 setForceUse(FOR_VIBRATE_RINGING, FORCE_NONE) due to muteRingerModeStreams() from u/pid:1000/1448


Audio event log: volume changes (logged when command received by AudioService)
05-08 17:09:51:596 sending VOLUME_CHANGED stream:STREAM_TTS index:10 alias:STREAM_MUSIC
05-08 17:09:51:598 sending VOLUME_CHANGED stream:STREAM_MUSIC index:10 alias:STREAM_MUSIC
05-08 17:09:51:601 setAvrcpVolume: index:10
05-08 17:09:51:636 adjustSuggestedStreamVolume(sugg:USE_DEFAULT_STREAM_TYPE dir:ADJUST_RAISE flags:0x1011) from android/android uid:1000
05-08 17:09:51:639 sending VOLUME_CHANGED stream:STREAM_ASSISTANT index:11 alias:STREAM_MUSIC
05-08 17:09:51:640 sending VOLUME_CHANGED stream:STREAM_ACCESSIBILITY index:11 alias:STREAM_MUSIC
05-08 17:09:51:644 sending VOLUME_CHANGED stream:STREAM_TTS index:11 alias:STREAM_MUSIC
05-08 17:09:51:647 sending VOLUME_CHANGED stream:STREAM_MUSIC index:11 alias:STREAM_MUSIC
05-08 17:09:51:650 setAvrcpVolume: index:11
05-08 17:09:51:688 adjustSuggestedStreamVolume(sugg:USE_DEFAULT_STREAM_TYPE dir:ADJUST_RAISE flags:0x1011) from android/android uid:1000
05-08 17:09:51:694 sending VOLUME_CHANGED stream:STREAM_ASSISTANT index:12 alias:STREAM_MUSIC
05-08 17:09:51:695 sending VOLUME_CHANGED stream:STREAM_ACCESSIBILITY index:12 alias:STREAM_MUSIC
05-08 17:09:51:700 sending VOLUME_CHANGED stream:STREAM_TTS index:12 alias:STREAM_MUSIC
05-08 17:09:51:701 sending VOLUME_CHANGED stream:STREAM_MUSIC index:12 alias:STREAM_MUSIC
05-08 17:09:51:703 setAvrcpVolume: index:12
05-08 17:09:51:738 adjustSuggestedStreamVolume(sugg:USE_DEFAULT_STREAM_TYPE dir:ADJUST_RAISE flags:0x1011) from android/android uid:1000
05-08 17:09:51:741 sending VOLUME_CHANGED stream:STREAM_ASSISTANT index:13 alias:STREAM_MUSIC
05-08 17:09:51:742 sending VOLUME_CHANGED stream:STREAM_ACCESSIBILITY index:13 alias:STREAM_MUSIC
05-08 17:09:51:746 sending VOLUME_CHANGED stream:STREAM_TTS index:13 alias:STREAM_MUSIC
05-08 17:09:51:748 sending VOLUME_CHANGED stream:STREAM_MUSIC index:13 alias:STREAM_MUSIC
05-08 17:09:51:750 setAvrcpVolume: index:13
05-08 17:09:51:789 adjustSuggestedStreamVolume(sugg:USE_DEFAULT_STREAM_TYPE dir:ADJUST_RAISE flags:0x1011) from android/android uid:1000
05-08 17:09:51:796 sending VOLUME_CHANGED stream:STREAM_ASSISTANT index:14 alias:STREAM_MUSIC
05-08 17:09:51:797 sending VOLUME_CHANGED stream:STREAM_ACCESSIBILITY index:14 alias:STREAM_MUSIC
05-08 17:09:51:800 sending VOLUME_CHANGED stream:STREAM_TTS index:14 alias:STREAM_MUSIC
05-08 17:09:51:806 sending VOLUME_CHANGED stream:STREAM_MUSIC index:14 alias:STREAM_MUSIC
05-08 17:09:51:817 setAvrcpVolume: index:14
05-08 17:09:51:839 adjustSuggestedStreamVolume(sugg:USE_DEFAULT_STREAM_TYPE dir:ADJUST_RAISE flags:0x1011) from android/android uid:1000
05-08 17:09:51:841 sending VOLUME_CHANGED stream:STREAM_ASSISTANT index:15 alias:STREAM_MUSIC
05-08 17:09:51:842 sending VOLUME_CHANGED stream:STREAM_ACCESSIBILITY index:15 alias:STREAM_MUSIC
05-08 17:09:51:848 sending VOLUME_CHANGED stream:STREAM_TTS index:15 alias:STREAM_MUSIC
05-08 17:09:51:850 sending VOLUME_CHANGED stream:STREAM_MUSIC index:15 alias:STREAM_MUSIC
05-08 17:09:51:852 setAvrcpVolume: index:15
05-08 17:09:51:890 adjustSuggestedStreamVolume(sugg:USE_DEFAULT_STREAM_TYPE dir:ADJUST_RAISE flags:0x1011) from android/android uid:1000
05-08 17:09:51:896 setAvrcpVolume: index:15
05-08 17:12:42:994 adjustSuggestedStreamVolume(sugg:USE_DEFAULT_STREAM_TYPE dir:ADJUST_RAISE flags:0x1011) from android/android uid:1000
05-08 17:12:42:999 setAvrcpVolume: index:15
05-08 17:12:43:205 adjustSuggestedStreamVolume(sugg:USE_DEFAULT_STREAM_TYPE dir:ADJUST_RAISE flags:0x1011) from android/android uid:1000
05-08 17:12:43:209 setAvrcpVolume: index:15
05-08 17:12:43:257 adjustSuggestedStreamVolume(sugg:USE_DEFAULT_STREAM_TYPE dir:ADJUST_RAISE flags:0x1011) from android/android uid:1000
05-08 17:12:43:262 setAvrcpVolume: index:15
05-08 17:12:43:308 adjustSuggestedStreamVolume(sugg:USE_DEFAULT_STREAM_TYPE dir:ADJUST_RAISE flags:0x1011) from android/android uid:1000
05-08 17:12:43:310 setAvrcpVolume: index:15
05-08 17:12:43:359 adjustSuggestedStreamVolume(sugg:USE_DEFAULT_STREAM_TYPE dir:ADJUST_RAISE flags:0x1011) from android/android uid:1000
05-08 17:12:43:362 setAvrcpVolume: index:15
05-08 17:12:43:412 adjustSuggestedStreamVolume(sugg:USE_DEFAULT_STREAM_TYPE dir:ADJUST_RAISE flags:0x1011) from android/android uid:1000
05-08 17:12:43:418 setAvrcpVolume: index:15
05-08 17:12:43:459 adjustSuggestedStreamVolume(sugg:USE_DEFAULT_STREAM_TYPE dir:ADJUST_RAISE flags:0x1011) from android/android uid:1000
05-08 17:12:43:461 setAvrcpVolume: index:15
05-08 17:12:43:512 adjustSuggestedStreamVolume(sugg:USE_DEFAULT_STREAM_TYPE dir:ADJUST_RAISE flags:0x1011) from android/android uid:1000
05-08 17:12:43:516 setAvrcpVolume: index:15
05-08 17:12:43:559 adjustSuggestedStreamVolume(sugg:USE_DEFAULT_STREAM_TYPE dir:ADJUST_RAISE flags:0x1011) from android/android uid:1000
05-08 17:12:43:565 setAvrcpVolume: index:15
05-08 17:12:43:610 adjustSuggestedStreamVolume(sugg:USE_DEFAULT_STREAM_TYPE dir:ADJUST_RAISE flags:0x1011) from android/android uid:1000
05-08 17:12:43:614 setAvrcpVolume: index:15
05-08 17:17:02:619 adjustSuggestedStreamVolume(sugg:USE_DEFAULT_STREAM_TYPE dir:ADJUST_LOWER flags:0x1011) from android/android uid:1000
05-08 17:17:02:623 sending VOLUME_CHANGED stream:STREAM_NOTIFICATION index:6 alias:STREAM_NOTIFICATION
05-08 17:23:46:172 adjustStreamVolumeForUid(stream:STREAM_MUSIC dir:ADJUST_LOWER flags:0x1) from android uid:1000
05-08 17:23:46:175 sending VOLUME_CHANGED stream:STREAM_ASSISTANT index:14 alias:STREAM_MUSIC
05-08 17:23:46:179 sending VOLUME_CHANGED stream:STREAM_ACCESSIBILITY index:14 alias:STREAM_MUSIC
05-08 17:23:46:183 sending VOLUME_CHANGED stream:STREAM_TTS index:14 alias:STREAM_MUSIC
05-08 17:23:46:187 sending VOLUME_CHANGED stream:STREAM_MUSIC index:14 alias:STREAM_MUSIC
05-08 17:23:46:192 setAvrcpVolume: index:14
05-08 17:23:46:515 adjustStreamVolumeForUid(stream:STREAM_MUSIC dir:ADJUST_LOWER flags:0x1) from android uid:1000
05-08 17:23:46:517 sending VOLUME_CHANGED stream:STREAM_ASSISTANT index:13 alias:STREAM_MUSIC
05-08 17:23:46:518 sending VOLUME_CHANGED stream:STREAM_ACCESSIBILITY index:13 alias:STREAM_MUSIC
05-08 17:23:46:526 sending VOLUME_CHANGED stream:STREAM_TTS index:13 alias:STREAM_MUSIC
05-08 17:23:46:527 sending VOLUME_CHANGED stream:STREAM_MUSIC index:13 alias:STREAM_MUSIC
05-08 17:23:46:531 setAvrcpVolume: index:13
05-08 17:24:13:609 adjustSuggestedStreamVolume(sugg:STREAM_MUSIC dir:ADJUST_LOWER flags:0x1000) from android/android uid:1000
05-08 17:24:13:615 sending VOLUME_CHANGED stream:STREAM_ASSISTANT index:12 alias:STREAM_MUSIC
05-08 17:24:13:616 sending VOLUME_CHANGED stream:STREAM_ACCESSIBILITY index:12 alias:STREAM_MUSIC
05-08 17:24:13:622 sending VOLUME_CHANGED stream:STREAM_TTS index:12 alias:STREAM_MUSIC
05-08 17:24:13:628 sending VOLUME_CHANGED stream:STREAM_MUSIC index:12 alias:STREAM_MUSIC
05-08 17:24:13:633 setAvrcpVolume: index:12
05-08 17:24:41:712 adjustSuggestedStreamVolume(sugg:STREAM_MUSIC dir:ADJUST_LOWER flags:0x1000) from android/android uid:1000
05-08 17:24:41:726 sending VOLUME_CHANGED stream:STREAM_ASSISTANT index:11 alias:STREAM_MUSIC
05-08 17:24:41:730 sending VOLUME_CHANGED stream:STREAM_ACCESSIBILITY index:11 alias:STREAM_MUSIC
05-08 17:24:41:735 sending VOLUME_CHANGED stream:STREAM_TTS index:11 alias:STREAM_MUSIC
05-08 17:24:41:741 sending VOLUME_CHANGED stream:STREAM_MUSIC index:11 alias:STREAM_MUSIC
05-08 17:24:41:746 setAvrcpVolume: index:11
05-08 17:26:42:809 adjustSuggestedStreamVolume(sugg:STREAM_MUSIC dir:ADJUST_LOWER flags:0x1000) from android/android uid:1000
05-08 17:26:42:821 sending VOLUME_CHANGED stream:STREAM_ASSISTANT index:10 alias:STREAM_MUSIC
05-08 17:26:42:822 sending VOLUME_CHANGED stream:STREAM_ACCESSIBILITY index:10 alias:STREAM_MUSIC
05-08 17:26:42:833 sending VOLUME_CHANGED stream:STREAM_TTS index:10 alias:STREAM_MUSIC
05-08 17:26:42:834 sending VOLUME_CHANGED stream:STREAM_MUSIC index:10 alias:STREAM_MUSIC
05-08 17:26:42:851 setAvrcpVolume: index:10
05-08 17:26:43:325 adjustSuggestedStreamVolume(sugg:STREAM_MUSIC dir:ADJUST_LOWER flags:0x1000) from android/android uid:1000
05-08 17:26:43:331 sending VOLUME_CHANGED stream:STREAM_ASSISTANT index:9 alias:STREAM_MUSIC
05-08 17:26:43:333 sending VOLUME_CHANGED stream:STREAM_ACCESSIBILITY index:9 alias:STREAM_MUSIC
05-08 17:26:43:338 sending VOLUME_CHANGED stream:STREAM_TTS index:9 alias:STREAM_MUSIC
05-08 17:26:43:342 sending VOLUME_CHANGED stream:STREAM_MUSIC index:9 alias:STREAM_MUSIC
05-08 17:26:43:348 setAvrcpVolume: index:9
05-08 17:28:44:969 adjustSuggestedStreamVolume(sugg:STREAM_MUSIC dir:ADJUST_LOWER flags:0x1000) from android/android uid:1000
05-08 17:28:44:975 sending VOLUME_CHANGED stream:STREAM_ASSISTANT index:8 alias:STREAM_MUSIC
05-08 17:28:44:977 sending VOLUME_CHANGED stream:STREAM_TTS index:8 alias:STREAM_MUSIC
05-08 17:28:44:981 sending VOLUME_CHANGED stream:STREAM_MUSIC index:8 alias:STREAM_MUSIC
05-08 17:28:44:985 setAvrcpVolume: index:8
05-08 17:29:25:169 VolumeStreamState.muteInternally(stream:STREAM_MUSIC, muted)
05-08 17:29:26:423 VolumeStreamState.muteInternally(stream:STREAM_MUSIC, unmuted)


Supported System Usages:
	USAGE_CALL_ASSISTANT



Spatial audio:
mHasSpatializerEffect:false (effect present)
isSpatializerEnabled:false (routing dependent)
SpatializerHelper:
	mState:1
	mSpatLevel:0
	mCapableSpatLevel:0
	mIsHeadTrackingSupported:false
	supported head tracking modes:
	mDesiredHeadTrackingMode:HEAD_TRACKING_MODE_RELATIVE_WORLD
	mActualHeadTrackingMode:HEAD_TRACKING_MODE_UNSUPPORTED
	headtracker available:false
	supports binaural:false / transaural:false
	mSpatOutput:0
	devices:
Audio event log: spatial audio
05-08 13:48:59:287 init effectExpected=false
05-08 13:48:59:287 init(): setting state to STATE_NOT_SUPPORTED due to effect not expected
05-08 13:48:59:287 setFeatureEnabled(false) was featureEnabled:false
05-08 17:08:41:816 Resetting featureEnabled=false
05-08 17:08:41:817 init effectExpected=true
05-08 17:08:41:819 init(): No Spatializer found

AudioSystemAdapter:
 last cache clear time: 05-08 17:29:26:269
 mDevicesForAttrCache:
	AudioAttributes: usage=USAGE_MEDIA content=CONTENT_TYPE_MUSIC flags=0x800 tags= bundle=null forVolume: true stream: STREAM_MUSIC(3)
		AudioDeviceAttributes: role:output type:speaker addr: name: profiles:[] descriptors:[]
	AudioAttributes: usage=USAGE_ASSISTANCE_SONIFICATION content=CONTENT_TYPE_SONIFICATION flags=0x801 tags= bundle=null forVolume: true stream: STREAM_SYSTEM(1)
		AudioDeviceAttributes: role:output type:speaker addr: name: profiles:[] descriptors:[]
	AudioAttributes: usage=USAGE_MEDIA content=CONTENT_TYPE_UNKNOWN flags=0x800 tags= bundle=null forVolume: true stream: STREAM_MUSIC(3)
		AudioDeviceAttributes: role:output type:speaker addr: name: profiles:[] descriptors:[]
	AudioAttributes: usage=USAGE_UNKNOWN content=CONTENT_TYPE_UNKNOWN flags=0x804 tags= bundle=null forVolume: true stream: STREAM_VOICE_CALL(0)
		AudioDeviceAttributes: role:output type:earpiece addr: name: profiles:[] descriptors:[]
	AudioAttributes: usage=USAGE_UNKNOWN content=CONTENT_TYPE_UNKNOWN flags=0x808 tags= bundle=null forVolume: true stream: STREAM_MUSIC(3)
		AudioDeviceAttributes: role:output type:speaker addr: name: profiles:[] descriptors:[]
	AudioAttributes: usage=USAGE_ASSISTANCE_ACCESSIBILITY content=CONTENT_TYPE_UNKNOWN flags=0x800 tags= bundle=null forVolume: true stream: STREAM_ACCESSIBILITY(10)
		AudioDeviceAttributes: role:output type:speaker addr: name: profiles:[] descriptors:[]
	AudioAttributes: usage=USAGE_ASSISTANCE_SONIFICATION content=CONTENT_TYPE_UNKNOWN flags=0x800 tags= bundle=null forVolume: true stream: STREAM_SYSTEM(1)
		AudioDeviceAttributes: role:output type:speaker addr: name: profiles:[] descriptors:[]
	AudioAttributes: usage=USAGE_VOICE_COMMUNICATION content=CONTENT_TYPE_SPEECH flags=0x804 tags= bundle=null forVolume: true stream: STREAM_VOICE_CALL(0)
		AudioDeviceAttributes: role:output type:earpiece addr: name: profiles:[] descriptors:[]
	AudioAttributes: usage=USAGE_ASSISTANT content=CONTENT_TYPE_SPEECH flags=0x800 tags= bundle=null forVolume: true stream: STREAM_ASSISTANT(11)
		AudioDeviceAttributes: role:output type:speaker addr: name: profiles:[] descriptors:[]
	AudioAttributes: usage=USAGE_ALARM content=CONTENT_TYPE_UNKNOWN flags=0x800 tags= bundle=null forVolume: true stream: STREAM_ALARM(4)
		AudioDeviceAttributes: role:output type:speaker addr: name: profiles:[] descriptors:[]
	AudioAttributes: usage=USAGE_VOICE_COMMUNICATION_SIGNALLING content=CONTENT_TYPE_UNKNOWN flags=0x800 tags= bundle=null forVolume: true stream: STREAM_DTMF(8)
		AudioDeviceAttributes: role:output type:speaker addr: name: profiles:[] descriptors:[]
	AudioAttributes: usage=USAGE_NOTIFICATION_RINGTONE content=CONTENT_TYPE_UNKNOWN flags=0x800 tags= bundle=null forVolume: true stream: STREAM_RING(2)
		AudioDeviceAttributes: role:output type:speaker addr: name: profiles:[] descriptors:[]
	AudioAttributes: usage=USAGE_NOTIFICATION content=CONTENT_TYPE_UNKNOWN flags=0x800 tags= bundle=null forVolume: true stream: STREAM_NOTIFICATION(5)
		AudioDeviceAttributes: role:output type:speaker addr: name: profiles:[] descriptors:[]
	AudioAttributes: usage=USAGE_UNKNOWN content=CONTENT_TYPE_SONIFICATION flags=0x808 tags= bundle=null forVolume: true stream: STREAM_MUSIC(3)
		AudioDeviceAttributes: role:output type:speaker addr: name: profiles:[] descriptors:[]
	AudioAttributes: usage=USAGE_VOICE_COMMUNICATION content=CONTENT_TYPE_UNKNOWN flags=0x800 tags= bundle=null forVolume: true stream: STREAM_VOICE_CALL(0)
		AudioDeviceAttributes: role:output type:earpiece addr: name: profiles:[] descriptors:[]
	AudioAttributes: usage=USAGE_MEDIA content=CONTENT_TYPE_UNKNOWN flags=0x800 tags= bundle=null forVolume: true stream: STREAM_MUSIC(3)
		AudioDeviceAttributes: role:output type:speaker addr: name: profiles:[] descriptors:[]
	AudioAttributes: usage=USAGE_ASSISTANCE_SONIFICATION content=CONTENT_TYPE_SONIFICATION flags=0x800 tags= bundle=null forVolume: true stream: STREAM_SYSTEM(1)
		AudioDeviceAttributes: role:output type:speaker addr: name: profiles:[] descriptors:[]
	AudioAttributes: usage=USAGE_ASSISTANCE_ACCESSIBILITY content=CONTENT_TYPE_SPEECH flags=0x800 tags= bundle=null forVolume: true stream: STREAM_ACCESSIBILITY(10)
		AudioDeviceAttributes: role:output type:speaker addr: name: profiles:[] descriptors:[]
	AudioAttributes: usage=USAGE_VOICE_COMMUNICATION content=CONTENT_TYPE_UNKNOWN flags=0x800 tags= bundle=null forVolume: false stream: STREAM_VOICE_CALL(0)
		AudioDeviceAttributes: role:output type:earpiece addr: name: profiles:[] descriptors:[]
	AudioAttributes: usage=USAGE_NOTIFICATION content=CONTENT_TYPE_SONIFICATION flags=0x800 tags= bundle=null forVolume: true stream: STREAM_NOTIFICATION(5)
		AudioDeviceAttributes: role:output type:speaker addr: name: profiles:[] descriptors:[]
	AudioAttributes: usage=USAGE_NOTIFICATION_RINGTONE content=CONTENT_TYPE_SONIFICATION flags=0x800 tags= bundle=null forVolume: true stream: STREAM_RING(2)
		AudioDeviceAttributes: role:output type:speaker addr: name: profiles:[] descriptors:[]
	AudioAttributes: usage=USAGE_VOICE_COMMUNICATION content=CONTENT_TYPE_SPEECH flags=0x800 tags= bundle=null forVolume: true stream: STREAM_VOICE_CALL(0)
		AudioDeviceAttributes: role:output type:earpiece addr: name: profiles:[] descriptors:[]
	AudioAttributes: usage=USAGE_VOICE_COMMUNICATION_SIGNALLING content=CONTENT_TYPE_SONIFICATION flags=0x800 tags= bundle=null forVolume: true stream: STREAM_DTMF(8)
		AudioDeviceAttributes: role:output type:speaker addr: name: profiles:[] descriptors:[]
	AudioAttributes: usage=USAGE_ALARM content=CONTENT_TYPE_SONIFICATION flags=0x800 tags= bundle=null forVolume: true stream: STREAM_ALARM(4)
		AudioDeviceAttributes: role:output type:speaker addr: name: profiles:[] descriptors:[]
	AudioAttributes: usage=USAGE_UNKNOWN content=CONTENT_TYPE_UNKNOWN flags=0x801 tags= bundle=null forVolume: true stream: STREAM_SYSTEM(1)
		AudioDeviceAttributes: role:output type:speaker addr: name: profiles:[] descriptors:[]
4. I get error unknown buffer Bluetooth listed -b
5. - null
- [bluetooth.device.class_of_device]: [90,2,12]
[bluetooth.device.default_name]: [Redmi 10A]
[bluetooth.profile.a2dp.source.enabled]: [true]
[bluetooth.profile.avrcp.target.enabled]: [true]
[bluetooth.profile.bas.client.enabled]: [true]
[bluetooth.profile.gatt.enabled]: [true]
[bluetooth.profile.hfp.ag.enabled]: [true]
[bluetooth.profile.hid.device.enabled]: [true]
[bluetooth.profile.hid.host.enabled]: [true]
[bluetooth.profile.map.server.enabled]: [true]
[bluetooth.profile.opp.enabled]: [true]
[bluetooth.profile.pan.nap.enabled]: [true]
[bluetooth.profile.pan.panu.enabled]: [true]
[bluetooth.profile.pbap.server.enabled]: [true]
[bluetooth.profile.sap.server.enabled]: [true]
[cache_key.bluetooth.bluetooth_adapter_get_connection_state]: [-7960591453153486001]
[cache_key.bluetooth.bluetooth_adapter_get_profile_connection_state]: [-7960591453153486002]
[cache_key.bluetooth.bluetooth_adapter_get_state]: [-7960591453153486007]
[cache_key.bluetooth.bluetooth_adapter_is_offloaded_filtering_supported]: [-7960591453153486015]
[cache_key.bluetooth.bluetooth_device_get_bond_state]: [-7960591453153486014]
[cache_key.bluetooth.bluetooth_map_get_connection_state]: [-7960591453153486011]
[cache_key.bluetooth.bluetooth_sap_get_connection_state]: [-7960591453153486010]
[init.svc.bluetooth-1-0]: [running]
[init.svc_debug_pid.bluetooth-1-0]: [735]
[persist.bluetooth.bluetooth_audio_hal.enabled]: [true]
[persist.bluetooth.btsnoopdefaultmode]: [disabled]
[persist.bluetooth.disableabsvol]: [false]
[persist.bluetooth.force_sco_audio]: [true]
[persist.bluetooth.sco_on_all_apps]: [true]
[persist.bluetooth.sco_on_for_media]: [true]
[persist.bluetooth.showdeviceswithoutnames]: [true]
[ro.boottime.bluetooth-1-0]: [13149650154]