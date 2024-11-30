# Csc Feature Tweaks
- Add these lines in product/omc/(your region)/config or for Dynamic Partition Devices optics/configs/carriers/(your carrier)/conf.
- In Higher One UI versions, you need to decrypt > edit > encrypt the cscfeature.xml. So <a href="https://github.com/ravindu644/OmcTextDecoder/releases/tag/0.4">use this tool to decode your csc file.</a>

<hr>

### 01. Data Icon Style (4G+) 
```
<CscFeature_SystemUI_ConfigOverrideDataIcon>DCM</CscFeature_SystemUI_ConfigOverrideDataIcon>
```

### 02. Camera Shutter Sound menu
```
<CscFeature_Camera_ShutterSoundMenu>TRUE</CscFeature_Camera_ShutterSoundMenu>
```

### 03. Enhance image quality
```
<CscFeature_Common_EnhanceImageQuality>TRUE</CscFeature_Common_EnhanceImageQuality>
<CscFeature_Camera_DefaultQuality>superfine</CscFeature_Camera_DefaultQuality>
```
### 04. Mobile Data button on Power Menu
```
<CscFeature_Framework_SupportDataModeSwitchGlobalAction>TRUE</CscFeature_Framework_SupportDataModeSwitchGlobalAction>
```

### 05. USIM info at the bottom of lock screen
```
<CscFeature_LockScreen_ConfigCarrierTextPolicy>DisplayUsimText;DisplayPlmnOnBottom</CscFeature_LockScreen_ConfigCarrierTextPolicy>
```

### 06. Useful Cards menu in Messages
```
<CscFeature_Message_SupportUsefulcard>TRUE</CscFeature_Message_SupportUsefulcard>
```

### 07. NFC Card Mode
```
<CscFeature_NFC_ConfigDynamicFirmwareLoading>KOO</CscFeature_NFC_ConfigDynamicFirmwareLoading>
<CscFeature_NFC_ConfigReaderModeUI>KOREA</CscFeature_NFC_ConfigReaderModeUI>
```

### 08. NFC icon always in Status Bar
```
<CscFeature_SystemUI_ConfigDefIndicatorAdditionalSystemIcon>nfc</CscFeature_SystemUI_ConfigDefIndicatorAdditionalSystemIcon>
```

### 09. Change 4G icon (value can be CHC, TGY, VZW, ATT, SPR, each one has different 4G icon)
```
<CscFeature_SystemUI_ConfigOpBrandingForIndicatorIcon>CHC</CscFeature_SystemUI_ConfigOpBrandingForIndicatorIcon>
```
<hr> - Special Thanks : <a href="https://t.me/Hiruka_NU">@Hiruka_NU</a> | <a href="https://xdaforums.com/t/csc-feature-mods.4538389/"> This post on XDA </a> | <a href="https://t.me/User7884or7885">@User7884or7885</a><br><hr>

### 01. 5 bar signal (Useless for some regions)
```
<CscFeature_SystemUI_ConfigMaxRssiLevel>5</CscFeature_SystemUI_ConfigMaxRssiLevel>
```
### 02. Play songs while recording a video.
```
<CscFeature_Camera_CamcorderDoNotPauseMusic>TRUE</CscFeature_Camera_CamcorderDoNotPauseMusic>
```
### 03. Camera Tweaks
```
<CscFeature_Camera_CameraFlicker>60hz</CscFeature_Camera_CameraFlicker>
<CscFeature_Camera_DefaultQuality>superfine</CscFeature_Camera_DefaultQuality>
```
### 04. Confirmation popup after tapping the quick tooggle for mobile data
```
<CscFeature_Setting_EnablePromptPopupWhenActivatingDataConnection>TRUE</CscFeature_Setting_EnablePromptPopupWhenActivatingDataConnection>
```
### 05. Data icon style(LTE)
```
<CscFeature_SystemUI_ConfigOverrideDataIcon>LTE</CscFeature_SystemUI_ConfigOverrideDataIcon>
```
### 06. Data usage in quick panel(Need China smart manager)
```
<CscFeature_SystemUI_SupportDataUsageViewOnQuickPanel>TRUE</CscFeature_SystemUI_SupportDataUsageViewOnQuickPanel>
```
### 07. Network speed meter
```
<CscFeature_Setting_SupportRealTimeNetworkSpeed>TRUE</CscFeature_Setting_SupportRealTimeNetworkSpeed>
```
- For One UI 6 and up, you will need this line too:
```
<CscFeature_Common_SupportZProjectFunctionInGlobal>TRUE</CscFeature_Common_SupportZProjectFunctionInGlobal>
```
### 08. Camera will works during a call
```
<CscFeature_Camera_EnableCameraDuringCall>TRUE</CscFeature_Camera_EnableCameraDuringCall>
```
### 09. VoLTE with 3G network(H/H+)
```
<CscFeature_Common_EnableHDVoiceDuring3GConnection>TRUE</CscFeature_Common_EnableHDVoiceDuring3GConnection>
```
### 10. Mobile data icon in power menu
```
<CscFeature_Framework_SupportDataModeSwitchGlobalAction>TRUE</CscFeature_Framework_SupportDataModeSwitchGlobalAction>
```
### 11. Call Recording in Samsung Dialer
```
<CscFeature_VoiceCall_ConfigRecording>RecordingAllowedByMenu</CscFeature_VoiceCall_ConfigRecording>
```
