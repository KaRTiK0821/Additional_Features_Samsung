# Csc Feature Tweaks
- Add these lines in product/omc/(your region)/config or for Dynamic Partition Devices optics/configs/carriers/(your carrier)/conf.
- In Higher One UI versions, you need to decrypt > edit > encrypt the cscfeature.xml. So <a href="https://github.com/ravindu644/OmcTextDecoder/releases/tag/0.4">use this tool to decode your csc file.</a>
## ‼️ Don't add anything unless you don't know what the hell actually this line does, cuz it might crash some settings..‼️ 
# New Tweaks 😎
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

### ¬ Alt Z Life
```
<CscFeature_Common_SupportPrivateMode>TRUE</CscFeature_Common_SupportPrivateMode>
<CscFeature_Gallery_SupportAliveZoom>TRUE</CscFeature_Gallery_SupportAliveZoom>
<CscFeature_Sip_ConfigAlivePrediction>multilingual</CscFeature_Sip_ConfigAlivePrediction>
```

### ¬ Smart Manager
```
<CscFeature_SmartManager_DisableAntiMalware>TRUE</CscFeature_SmartManager_DisableAntiMalware>
<CscFeature_SmartManager_ConfigDashboard>dual_dashboard</CscFeature_SmartManager_ConfigDashboard>
<CscFeature_SmartManager_ConfigSubFeatures>applock|appcleanner|autolaunch|autorestart|devicesecurity|storageclean|backgroundapp|chinadualpage|UDS|UDS2|applicationpermission|networkpowersaving|notificationmanager|trafficmanager|roguepopup|data_compression|cstyle</CscFeature_SmartManager_ConfigSubFeatures>
<CscFeature_SmartManager_ConfigUdsSubFeatures>videocompression|uploadcompression</CscFeature_SmartManager_ConfigUdsSubFeatures>
```

### ¬ SystemUI
```
<CscFeature_SystemUI_ConfigOpBranding5GIcon>5GAvailable,RRCStateCheck,UseDisplayTimer</CscFeature_SystemUI_ConfigOpBranding5GIcon>
<CscFeature_SystemUI_ConfigDefQuickSettingItem>Wifi,SilentMode,SoundMode,WindowsLink,Bluetooth,NightMode,FocusMode,Intent,ColorInversion,Ebook,Routines,InstantSession,RotationLock,PowerShare,Flashlight,QRScanner,AirplaneMode,PowerSaving,MobileData,WifiCalling,Performance,BlueLightFilter,WifiHotspot,Hotspot,PersonalMode,SecureFolder,Location,Nfc,Aod,AllShareCast,ShareLive,DeviceVisibility,Dnd,Sync,UDS,BikeMode,PowerPlanning,EdgeLighting,FloatingMessage,RedPacket,DormantMode,NetworkBooster,QuickConnect,SmartStay,SmartPause,AirView,AirBrowse,Toolbox,CarMode,UltraPowerSaving,SFinder,ScreenCapture,ScreenRecorder,VoLte,Dolby,BatteryMode,DailyBoard,DesktopMode,SpenRemote,KidsHome,GrxScreenOnTime,GrxScreenRecord,GrxMultiAction,GrxRecovery</CscFeature_SystemUI_ConfigDefQuickSettingItem>
<CscFeature_SystemUI_ConfigQuickSettingPopup>SER</CscFeature_SystemUI_ConfigQuickSettingPopup>
<CscFeature_SystemUI_ConfigOverrideDataIcon>LTE</CscFeature_SystemUI_ConfigOverrideDataIcon>
<CscFeature_SystemUI_ConfigOpBrandingForIndicatorIcon>TTT</CscFeature_SystemUI_ConfigOpBrandingForIndicatorIcon>
<CscFeature_SystemUI_ConfigOpBrandingForDataIndicator>TTT</CscFeature_SystemUI_ConfigOpBrandingForDataIndicator>
<CscFeature_SystemUI_SupportRecentAppProtection>TRUE</CscFeature_SystemUI_SupportRecentAppProtection>
<CscFeature_SystemUI_SupportAssistanceAppChooser>TRUE</CscFeature_SystemUI_SupportAssistanceAppChooser>
<CscFeature_SystemUI_SupportDataUsageViewOnQuickPanel>TRUE</CscFeature_SystemUI_SupportDataUsageViewOnQuickPanel>
```

### ¬ Calendar
```
<CscFeature_Calendar_EnableWeatherInfo>TRUE</CscFeature_Calendar_EnableWeatherInfo>
<CscFeature_Calendar_SetColorOfDays>XXXXXBR</CscFeature_Calendar_SetColorOfDays>
<CscFeature_Calendar_EnableMsgReminder>TRUE</CscFeature_Calendar_EnableMsgReminder>
```

### ¬ Settings
```
<CscFeature_Settings_EnableUSM>TRUE</CscFeature_Settings_EnableUSM>
<CscFeature_Setting_ConfigAddSuffixModelNumber>/DS</CscFeature_Setting_ConfigAddSuffixModelNumber>
<CscFeature_Setting_EnableMenuBlockCallMsg>TRUE</CscFeature_Setting_EnableMenuBlockCallMsg>
<CscFeature_Setting_EnableDataRoamingMenuInDetail>TRUE</CscFeature_Setting_EnableDataRoamingMenuInDetail>
<CscFeature_Setting_EnableEditingIpVersionType>TRUE</CscFeature_Setting_EnableEditingIpVersionType>
<CscFeature_Setting_EnableMenuDownloadContents>TRUE</CscFeature_Setting_EnableMenuDownloadContents>
<CscFeature_Setting_EnableRoamingMenu>TRUE</CscFeature_Setting_EnableRoamingMenu>
<CscFeature_Setting_IncludeApn4SwUpdate>TRUE</CscFeature_Setting_IncludeApn4SwUpdate>
<CscFeature_Setting_DisableMenuSoftwareUpdate>TRUE</CscFeature_Setting_DisableMenuSoftwareUpdate>
<CscFeature_Setting_CustNetworkSelMenu4>LTEONLY</CscFeature_Setting_CustNetworkSelMenu4>
<CscFeature_Setting_SupportRealTimeNetworkSpeed>TRUE</CscFeature_Setting_SupportRealTimeNetworkSpeed>
<CscFeature_Setting_DataRoamingOption>national</CscFeature_Setting_DataRoamingOption>
<CscFeature_Setting_DisableMenuFindMyMobile>TRUE</CscFeature_Setting_DisableMenuFindMyMobile>
<CscFeature_Setting_EnableDataRoamingButtonInQuickPanel>TRUE</CscFeature_Setting_EnableDataRoamingButtonInQuickPanel>
<CscFeature_Setting_EditOption4ApnType>List</CscFeature_Setting_EditOption4ApnType>
<CscFeature_Setting_ConfigAboutDeviceItems>fcc=disabled;modelnumberNFCsuffix=enabled;</CscFeature_Setting_ConfigAboutDeviceItems>
<CscFeature_Setting_InfinitySoftwareUpdate>TRUE</CscFeature_Setting_InfinitySoftwareUpdate>
<CscFeature_Setting_SkipStepsDuringSamsungSetupWizard>TRUE</CscFeature_Setting_SkipStepsDuringSamsungSetupWizard>
<CscFeature_Setting_SupportWifiCall>TRUE</CscFeature_Setting_SupportWifiCall>
<CscFeature_Settings_Reset_Password>TRUE</CscFeature_Settings_Reset_Password>
<CscFeature_Setting_SupportWiFiCallingMenu>TRUE</CscFeature_Setting_SupportWiFiCallingMenu>
<CscFeature_Setting_EnableMenuNetworkMode>TRUE</CscFeature_Setting_EnableMenuNetworkMode>
<CscFeature_Setting_SkipWifiActvDuringSetupWizard>FALSE</CscFeature_Setting_SkipWifiActvDuringSetupWizard>
<CscFeature_Setting_EnableFactoryResetPasswordWhenNoSIM>FALSE</CscFeature_Setting_EnableFactoryResetPasswordWhenNoSIM>
<CscFeature_Settings_FOTA>FALSE<CscFeature_Settings_FOTA>
<CscFeature_Settings_GOTA>TRUE</CscFeature_Settings_GOTA>
<CscFeature_Settings_FindMyMobile>FALSE</CscFeature_Settings_FindMyMobile>
```

### ¬ Clock
```
<CscFeature_Clock_ConfigDefStatusWorldclockWeather>OFF</CscFeature_Clock_ConfigDefStatusWorldclockWeather>
<CscFeature_Clock_DisableGoogleLocationInfo>TRUE</CscFeature_Clock_DisableGoogleLocationInfo>
<CscFeature_Clock_EnableAutoPowerOnOffMenu>TRUE</CscFeature_Clock_EnableAutoPowerOnOffMenu>
<CscFeature_Clock_ExclusiveEnablingAutoPowerSetting>TRUE</CscFeature_Clock_ExclusiveEnablingAutoPowerSetting>
<CscFeature_Clock_SupportAlarmOptionMenuForWorkingDay>TRUE</CscFeature_Clock_SupportAlarmOptionMenuForWorkingDay>
```

### ¬ Camera
```
<CscFeature_Camera_ShutterSoundMenu>TRUE</CscFeature_Camera_ShutterSoundMenu>
<CscFeature_Camera_CameraFlicker>60hz</CscFeature_Camera_CameraFlicker>
<CscFeature_Camera_EnableCameraDuringCall>TRUE</CscFeature_Camera_EnableCameraDuringCall>
<CscFeature_Camera_EnableSmsNotiPopup>TRUE</CscFeature_Camera_EnableSmsNotiPopup>
<CscFeature_Camera_DefaultQuality>superfine</CscFeature_Camera_DefaultQuality>
<CscFeature_Camera_SecurityMdmService>TRUE</CscFeature_Camera_SecurityMdmService>
<CscFeature_Camera_CamcorderDoNotPauseMusic>TRUE</CscFeature_Camera_CamcorderDoNotPauseMusic>
<CscFeature_Camera_CamcoderForceShutterSoundDuringSnapShot>FALSE</CscFeature_Camera_CamcoderForceShutterSoundDuringSnapShot>
<CscFeature_Camera_CamcorderEnablePromptPopupToSelectRecMode>TRUE</CscFeature_Camera_CamcorderEnablePromptPopupToSelectRecMode>
<CscFeature_Camcorder_DoNotPauseMusic>TRUE</CscFeature_Camcorder_DoNotPauseMusic>
<CscFeature_Camcorder_DefaultQuality>superfine</CscFeature_Camcorder_DefaultQuality>
```

### ¬ AOD
```
<CscFeature_AOD_ConfigAdditionalHomeDoubleKeyAction>;QuickCamera</CscFeature_AOD_ConfigAdditionalHomeDoubleKeyAction>
```

### ¬ Common
```
<CscFeature_Common_AutoConfigurationType>NO_DFLT_CSC, SIMBASED_OMC</CscFeature_Common_AutoConfigurationType>
<CscFeature_Common_ConfigEmergencyModePackages>com.ipsec.service,com.sec.android.providers.iwlansettings,com.sec.android.providers.mapcon</CscFeature_Common_ConfigEmergencyModePackages>
<CscFeature_Common_ConfigYuva>AIBokeh|powerplanning|reserve|zeroforward|mileage|dashboard|setupmygalaxystories|downloadable_spowerplanning|sprotect|downloadable_sprotect|downloadable_usbbackup|MemorySaver|MemorySaver_Refresh|MemorySaver_MOVE_CONTENT_TO_SDCARD_NOT_SUPPORTING</CscFeature_Common_ConfigYuva>
<CscFeature_Common_DisablePhoneNumberFormatting>TRUE</CscFeature_Common_DisablePhoneNumberFormatting>
<CscFeature_Common_EulaVersion>2</CscFeature_Common_EulaVersion>
<CscFeature_Common_SupportRmm>TRUE</CscFeature_Common_SupportRmm>
<CscFeature_Common_SupportWcdmaInSlave>TRUE</CscFeature_Common_SupportWcdmaInSlave>
<CscFeature_Common_EnableHDVoiceDuring3GConnection>TRUE</CscFeature_Common_EnableHDVoiceDuring3GConnection>
<CscFeature_Common_EnableUiDisplayMirroring>TRUE</CscFeature_Common_EnableUiDisplayMirroring>
<CscFeature_Common_EnableVIPMode>TRUE</CscFeature_Common_EnableVIPMode>
<CscFeature_Common_EnableAirMessage>FALSE</CscFeature_Common_EnableAirMessage>
<CscFeature_Common_SupportDualIMS>TRUE</CscFeature_Common_SupportDualIMS>
<CscFeature_Common_AllowExternalApkUsage>TRUE</CscFeature_Common_AllowExternalApkUsage>
<CscFeature_Knox_SupportKnoxGuard>FALSE</CscFeature_Knox_SupportKnoxGuard>
```

### ¬ Voice Call
```
<CscFeature_VoiceCall_SupportShowVowifiEndCall>TRUE</CscFeature_VoiceCall_SupportShowVowifiEndCall>
<CscFeature_VoiceCall_ConfigRecording>RecordingAllowedByMenu</CscFeature_VoiceCall_ConfigRecording>
<CscFeature_VoiceCall_EnableVmsNumberAsDefaultInCallForwarding>TRUE</CscFeature_VoiceCall_EnableVmsNumberAsDefaultInCallForwarding>
<CscFeature_VoiceCall_ConfigCallforwardCfnryTimer>Remove</CscFeature_VoiceCall_ConfigCallforwardCfnryTimer>
<CscFeature_VoiceCall_ConfigOpStyleForHdIcon>XSG_HD,XSG_UHD</CscFeature_VoiceCall_ConfigOpStyleForHdIcon>
<CscFeature_VoiceCall_ConfigOpStyleForRingBackTone>SINGTEL</CscFeature_VoiceCall_ConfigOpStyleForRingBackTone>
<CscFeature_VoiceCall_DisableCallTransfer>TRUE</CscFeature_VoiceCall_DisableCallTransfer> 
<CscFeature_VoiceCall_EnableGroupCallMenu>TRUE</CscFeature_VoiceCall_EnableGroupCallMenu>
<CscFeature_VoiceCall_SupportAutoCallTest>TRUE</CscFeature_VoiceCall_SupportAutoCallTest>
<CscFeature_VoiceCall_SupportAutoDialDuringRoaming>TRUE</CscFeature_VoiceCall_SupportAutoDialDuringRoaming>
<CscFeature_VoiceCall_SupportAutoUnholdForMultiCallFinish>TRUE</CscFeature_VoiceCall_SupportAutoUnholdForMultiCallFinish>
<CscFeature_VoiceCall_SupportClearDialInputData>TRUE</CscFeature_VoiceCall_SupportClearDialInputData>
<CscFeature_VoiceCall_SupportEmergencyCallUsingVolte>TRUE</CscFeature_VoiceCall_SupportEmergencyCallUsingVolte>
<CscFeature_VoiceCall_SupportImsPsBarring>TRUE</CscFeature_VoiceCall_SupportImsPsBarring>
<CscFeature_VoiceCall_ConfigOpStyleForMobileNetSetting>voltesettingscommon,checknonvoltesim,voltesettingOPS</CscFeature_VoiceCall_ConfigOpStyleForMobileNetSetting>
<CscFeature_VoiceCall_SupportInterworkingHdVoiceByIntent>TRUE</CscFeature_VoiceCall_SupportInterworkingHdVoiceByIntent>
<CscFeature_VoiceCall_SupportMenuPersonaliseSoftSound>TRUE</CscFeature_VoiceCall_SupportMenuPersonaliseSoftSound>
<CscFeature_VoiceCall_SupportOpticCmdTest>TRUE</CscFeature_VoiceCall_SupportOpticCmdTest>
<CscFeature_VoiceCall_SupportPopupForDataOff>TRUE</CscFeature_VoiceCall_SupportPopupForDataOff>
```

### ¬ Voice Recorder
```
<CscFeature_VoiceRecorder_SupportPrivacyPolicyPrompt>TRUE</CscFeature_VoiceRecorder_SupportPrivacyPolicyPrompt>
```

### ¬ Video
```
<CscFeature_Video_BlockNotiSoundDuringStreaming>TRUE</CscFeature_Video_BlockNotiSoundDuringStreaming>
<CscFeature_Video_SupportPlayDuringCall>TRUE</CscFeature_Video_SupportPlayDuringCall>
<CscFeature_Video_SupportSpeedControl>TRUE</CscFeature_Video_SupportSpeedControl>
<CscFeature_Video_AddWidgetLayout>TRUE</CscFeature_Video_AddWidgetLayout>
<CscFeature_Video_EnablePopupPlayer>TRUE</CscFeature_Video_EnablePopupPlayer>
```
### ¬ SIP
```
<CscFeature_SIP_EnablePreferredEnglishTypeAsUS>TRUE</CscFeature_SIP_EnablePreferredEnglishTypeAsUS>
<CscFeature_Sip_AddCommaKeyAsDefault>FALSE</CscFeature_Sip_AddCommaKeyAsDefault>
<CscFeature_Sip_EnableContinuousInputInAllEditField>TRUE</CscFeature_Sip_EnableContinuousInputInAllEditField>
<CscFeature_Sip_EnableSymbolInSecondary>en_GB;en_US;af;af_NA;af_ZA;agq;agq_CM;ak;ak_GH;am;am_ET;ar;ar_001;ar_AE;ar_BH;ar_DJ;ar_DZ;ar_EG;ar_ER;ar_IL;ar_IQ;ar_JO;ar_KM;ar_KW;ar_LB;ar_LY;ar_MA;ar_MR;ar_OM;ar_PS;ar_QA;ar_SA;ar_SD;ar_SO;ar_SY;ar_TD;ar_TN;ar_YE;as;as_IN;asa;asa_TZ;az;az_AZ;az_CYRL;az_CYRL_AZ;az_LATN;az_LATN_AZ;bas;bas_CM;be;be_BY;bem;bem_ZM;bez;bez_TZ;bg;bg_BG;bm;bm_ML;bn;bn_BD;bn_IN;bo;bo_CN;bo_IN;br;br_FR;brx;brx_IN;bs;bs_CYRL;bs_CYRL_BA;bs_LATN;bs_LATN_BA;ca;ca_AD;ca_ES;cgg;cgg_UG;chr;chr_US;cs;cs_CZ;cy;cy_GB;da;da_DK;dav;dav_KE;de;de_AT;de_BE;de_CH;de_DE;de_LI;de_LU;dje;dje_NE;dua;dua_CM;dyo;dyo_SN;dz;dz_BT;ebu;ebu_KE;ee;ee_GH;ee_TG;el;el_CY;el_GR;en;en_150;en_AG;en_AS;en_AU;en_BB;en_BE;en_BM;en_BS;en_BW;en_BZ;en_CA;en_CM;en_DM;en_FJ;en_FM;en_GB;en_GD;en_GG;en_GH;en_GI;en_GM;en_GU;en_GY;en_HK;en_IE;en_IM;en_IN;en_JE;en_JM;en_KE;en_KI;en_KN;en_KY;en_LC;en_LR;en_LS;en_MG;en_MH;en_MP;en_MT;en_MU;en_MW;en_NA;en_NG;en_NZ;en_PG;en_PH;en_PK;en_PR;en_PW;en_SB;en_SC;en_SG;en_SL;en_SS;en_SZ;en_TC;en_TO;en_TT;en_TZ;en_UG;en_UM;en_US;en_US_POSIX;en_VC;en_VG;en_VI;en_VU;en_WS;en_ZA;en_ZM;en_ZW;eo;es;es_419;es_AR;es_BO;es_CL;es_CO;es_CR;es_CU;es_DO;es_EA;es_EC;es_ES;es_GQ;es_GT;es_HN;es_IC;es_MX;es_NI;es_PA;es_PE;es_PH;es_PR;es_PY;es_SV;es_US;es_UY;es_VE;et;et_EE;eu;eu_ES;ewo;ewo_CM;fa;fa_AF;fa_FA;fa_IR;ff;ff_SN;fi;fi_FI;fil;fil_PH;fo;fo_FO;fr;fr_BE;fr_BF;fr_BI;fr_BJ;fr_BL;fr_CA;fr_CD;fr_CF;fr_CG;fr_CH;fr_CI;fr_CM;fr_DJ;fr_DZ;fr_FR;fr_GA;fr_GF;fr_GN;fr_GP;fr_GQ;fr_HT;fr_KM;fr_LU;fr_MA;fr_MC;fr_MF;fr_MG;fr_ML;fr_MQ;fr_MR;fr_MU;fr_NC;fr_NE;fr_PF;fr_RE;fr_RW;fr_SC;fr_SN;fr_SY;fr_TD;fr_TG;fr_TN;fr_VU;fr_YT;ga;ga_IE;gl;gl_ES;gsw;gsw_CH;gu;gu_IN;guz;guz_KE;gv;gv_GB;ha;ha_LATN;ha_LATN_GH;ha_LATN_NE;ha_LATN_NG;haw;haw_US;iw;iw_IL;hi;hi_IN;hr;hr_BA;hr_HR;hu;hu_HU;hy;hy_AM;in;in_ID;in;in_ID;ig;ig_NG;ii;ii_CN;is;is_IS;it;it_CH;it_IT;it_SM;iw_IL;ja;ja_JP;jgo;jgo_CM;jmc;jmc_TZ;ka;ka_GE;kab;kab_DZ;kam;kam_KE;kde;kde_TZ;kea;kea_CV;khq;khq_ML;ki;ki_KE;kk;kk_CYRL;kk_CYRL_KZ;kk_KZ;kl;kl_GL;kln;kln_KE;km;km_KH;kn;kn_IN;ko;ko_KP;ko_KR;kok;kok_IN;ks;ks_ARAB;ks_ARAB_IN;ksb;ksb_TZ;ksf;ksf_CM;kw;kw_GB;lag;lag_TZ;lg;lg_UG;ln;ln_AO;ln_CD;ln_CF;ln_CG;lo;lo_LA;lt;lt_LT;lu;lu_CD;luo;luo_KE;luy;luy_KE;lv;lv_LV;mas;mas_KE;mas_TZ;mer;mer_KE;mfe;mfe_MU;mg;mg_MG;mgh;mgh_MZ;mgo;mgo_CM;mk;mk_MK;ml;ml_IN;mn;mn_CYRL;mn_CYRL_MN;mr;mr_IN;ms;ms_LATN;ms_LATN_BN;ms_LATN_MY;ms_LATN_SG;ms_MY;mt;mt_MT;mua;mua_CM;my;my_MM;naq;naq_NA;nb;nb_NO;nd;nd_ZW;ne;ne_IN;ne_NP;nl;nl_AW;nl_BE;nl_CW;nl_NL;nl_SR;nl_SX;nmg;nmg_CM;nn;nn_NO;nus;nus_SD;nyn;nyn_UG;om;om_ET;om_KE;or;or_IN;pa;pa_ARAB;pa_ARAB_PK;pa_GURU;pa_GURU_IN;pa_IN;pl;pl_PL;ps;ps_AF;pt;pt_AO;pt_BR;pt_CV;pt_GW;pt_MO;pt_MZ;pt_PT;pt_ST;pt_TL;rm;rm_CH;rn;rn_BI;ro;ro_MD;ro_RO;rof;rof_TZ;ru;ru_BY;ru_KG;ru_KZ;ru_MD;ru_RU;ru_UA;rw;rw_RW;rwk;rwk_TZ;saq;saq_KE;sbp;sbp_TZ;seh;seh_MZ;ses;ses_ML;sg;sg_CF;shi;shi_LATN;shi_LATN_MA;shi_TFNG;shi_TFNG_MA;si;si_IN;si_LK;sk;sk_SK;sl;sl_SI;sn;sn_ZW;so;so_DJ;so_ET;so_KE;so_SO;sq;sq_AL;sq_MK;sr;sr_CYRL;sr_CYRL_BA;sr_CYRL_ME;sr_CYRL_RS;sr_LATN;sr_LATN_BA;sr_LATN_ME;sr_LATN_RS;sr_RS;sv;sv_AX;sv_FI;sv_SE;sw;sw_KE;sw_TZ;sw_UG;swc;swc_CD;ta;ta_IN;ta_LK;ta_MY;ta_SG;te;te_IN;teo;teo_KE;teo_UG;th;th_TH;ti;ti_ER;ti_ET;tl;tl_PH;to;to_TO;tr;tr_CY;tr_TR;twq;twq_NE;tzm;tzm_LATN;tzm_LATN_MA;uk;uk_UA;ur;ur_IN;ur_PK;uz;uz_ARAB;uz_ARAB_AF;uz_CYRL;uz_CYRL_UZ;uz_LATN;uz_LATN_UZ;uz_UZ;vai;vai_LATN;vai_LATN_LR;vai_VAII;vai_VAII_LR;vi;vi_VN;vun;vun_TZ;xog;xog_UG;yav;yav_CM;yo;yo_NG;zh;zh_CN;zh_HANS;zh_HANS_CN;zh_HANS_HK;zh_HANS_MO;zh_HANS_SG;zh_HANT;zh_HANT_HK;zh_HANT_MO;zh_HANT_TW;zh_HK;zh_SG;zh_TW;zu;zu_ZA;</CscFeature_Sip_EnableSymbolInSecondary>
<CscFeature_Sip_UseSymbolInCMKey>TRUE</CscFeature_Sip_UseSymbolInCMKey>
<CscFeature_Sip_ConfigWhetherToProvideGif>disable</CscFeature_Sip_ConfigWhetherToProvideGif>
<CscFeature_Sip_LangQwertyType4HwKey>HW_KEYBOARD_COUNTRY_TYPE_ARAB_QWERTY</CscFeature_Sip_LangQwertyType4HwKey>
```

### ¬ Contact
```
<CscFeature_Contact_EnableLogIconForVoiceRecord>TRUE</CscFeature_Contact_EnableLogIconForVoiceRecord>
<CscFeature_Contact_FullCountryPrefixSearchSupport>TRUE</CscFeature_Contact_FullCountryPrefixSearchSupport>
<CscFeature_Contact_ConfigDefaultViewBy>AllCalls</CscFeature_Contact_ConfigDefaultViewBy>
<CscFeature_Contact_DisableGoogleTalk>TRUE</CscFeature_Contact_DisableGoogleTalk>
<CscFeature_Contact_EnableCallButtonInList>TRUE</CscFeature_Contact_EnableCallButtonInList>
<CscFeature_Contact_SupportSIMContacts>TRUE</CscFeature_Contact_SupportSIMContacts>
<CscFeature_Contact_ExportAllNumberToSIM>TRUE</CscFeature_Contact_ExportAllNumberToSIM>
<CscFeature_Contact_EnableCopyToDialer>TRUE</CscFeature_Contact_EnableCopyToDialer>
<CscFeature_Contact_ExtendSpeedDialTo100>TRUE</CscFeature_Contact_ExtendSpeedDialTo100>
<CscFeature_Contact_LimitNameLength>1280</CscFeature_Contact_LimitNameLength>
<CscFeature_Contact_EnableDynCallerIdMatchingDigitWithAutoSim>TRUE</CscFeature_Contact_EnableDynCallerIdMatchingDigitWithAutoSim>
<CscFeature_Contact_SetLinkCountMaxAs>999</CscFeature_Contact_SetLinkCountMaxAs>
<CscFeature_Contact_SupportDuoVideoCall>TRUE</CscFeature_Contact_SupportDuoVideoCall>
<CscFeature_Contact_EnableExtraCallServiceMenu>TRUE</CscFeature_Contact_EnableExtraCallServiceMenu>
<CscFeature_Contact_EnableSelectableListToExportSdCard>TRUE</CscFeature_Contact_EnableSelectableListToExportSdCard>
```

### ¬ GMS
```
<CscFeature_GMS_SetClientIDBaseMs>android-samsung-ga-rev1</CscFeature_GMS_SetClientIDBaseMs>
```

### ¬ Messages
```
<CscFeature_Message_SupportUsefulcard>TRUE</CscFeature_Message_SupportUsefulcard>
<CscFeature_Message_EnablePhoneNumberFormattingInMsg>TRUE</CscFeature_Message_EnablePhoneNumberFormattingInMsg>
<CscFeature_Message_EnableEmailOverSms>TRUE</CscFeature_Message_EnableEmailOverSms>
<CscFeature_Message_EnableEditingSenderAddress>TRUE</CscFeature_Message_EnableEditingSenderAddress>
<CscFeature_Message_EnableAddContactIn1stDepthComposerOption>TRUE</CscFeature_Message_EnableAddContactIn1stDepthComposerOption>
<CscFeature_Message_CMASOperator>uae</CscFeature_Message_CMASOperator>
<CscFeature_Message_ConfigFreeMessage>OFF</CscFeature_Message_ConfigFreeMessage>
<CscFeature_Message_EnableSaveRestoreSDCard>TRUE</CscFeature_Message_EnableSaveRestoreSDCard>
<CscFeature_Message_AddSendOptionInComposer>TRUE</CscFeature_Message_AddSendOptionInComposer>
<CscFeature_Message_ConfigEmojiComposing>TRUE</CscFeature_Message_ConfigEmojiComposing>
<CscFeature_Message_ConfigSpamReport>TRUE</CscFeature_Message_ConfigSpamReport>
<CscFeature_Message_ConfigThreadForMultipleDest>TRUE</CscFeature_Message_ConfigThreadForMultipleDest>
<CscFeature_Message_DisableCBNotifications>FALSE</CscFeature_Message_DisableCBNotifications>
<CscFeature_Message_DisableConvertingEffectBetweenSMSMMS>TRUE</CscFeature_Message_DisableConvertingEffectBetweenSMSMMS>
<CscFeature_Message_DisableCopyToSim>FALSE</CscFeature_Message_DisableCopyToSim>
<CscFeature_Message_DisableDeleteButtonOnActionBar>FALSE</CscFeature_Message_DisableDeleteButtonOnActionBar>
<CscFeature_Message_DisableLogs>TRUE</CscFeature_Message_DisableLogs>
<CscFeature_Message_DisableMenuCBChannel>FALSE</CscFeature_Message_DisableMenuCBChannel>
<CscFeature_Message_DisableMenuCBMessage>FALSE</CscFeature_Message_DisableMenuCBMessage>
<CscFeature_Message_DisableMenuMmsCreationMode>FALSE</CscFeature_Message_DisableMenuMmsCreationMode>
<CscFeature_Message_DisableMenuSIMMessages>FALSE</CscFeature_Message_DisableMenuSIMMessages>
<CscFeature_Message_DisableMenuSMSC>FALSE</CscFeature_Message_DisableMenuSMSC>
<CscFeature_Message_DisableMenuSmsInputMode>FALSE</CscFeature_Message_DisableMenuSmsInputMode>
<CscFeature_Message_DisableMmsSubject>FALSE</CscFeature_Message_DisableMmsSubject>
<CscFeature_Message_DisableOptionAttachLocation>FALSE</CscFeature_Message_DisableOptionAttachLocation>
<CscFeature_Message_DisableOptionAttachVCalendar>FALSE</CscFeature_Message_DisableOptionAttachVCalendar>
<CscFeature_Message_DisableOptionAttachVCard>FALSE</CscFeature_Message_DisableOptionAttachVCard>
<CscFeature_Message_DisableOptionAttachVMemo>FALSE</CscFeature_Message_DisableOptionAttachVMemo>
<CscFeature_Message_DisableOptionRecordAudio>FALSE</CscFeature_Message_DisableOptionRecordAudio>
<CscFeature_Message_DisableSaveClassZeroMessage>FALSE</CscFeature_Message_DisableSaveClassZeroMessage>
<CscFeature_Message_DisableSaveRingtoneMenu>FALSE</CscFeature_Message_DisableSaveRingtoneMenu>
<CscFeature_Message_DisableSmscEditable>FALSE</CscFeature_Message_DisableSmscEditable>
<CscFeature_Message_DisableSmsToMmsConversionByTextInput>TRUE</CscFeature_Message_DisableSmsToMmsConversionByTextInput>
<CscFeature_Message_DisplaySmsTimeAs>TRUE</CscFeature_Message_DisplaySmsTimeAs>
<CscFeature_Message_EnableAlias>TRUE</CscFeature_Message_EnableAlias>
<CscFeature_Message_EnableAllContextMenuInMsgViewer>TRUE</CscFeature_Message_EnableAllContextMenuInMsgViewer>
<CscFeature_Message_EnableAnonymousThread>TRUE</CscFeature_Message_EnableAnonymousThread>
<CscFeature_Message_EnableBlackList>TRUE</CscFeature_Message_EnableBlackList>
<CscFeature_Message_EnableCombineAndForwardMessage>TRUE</CscFeature_Message_EnableCombineAndForwardMessage>
<CscFeature_Message_EnableContactInfoInBubble>TRUE</CscFeature_Message_EnableContactInfoInBubble>
<CscFeature_Message_EnableDbBackupKeystring>TRUE</CscFeature_Message_EnableDbBackupKeystring>
<CscFeature_Message_EnableDisplayTotalCount4SimMsg>TRUE</CscFeature_Message_EnableDisplayTotalCount4SimMsg>
<CscFeature_Message_EnableFlickThreadView>TRUE</CscFeature_Message_EnableFlickThreadView>
<CscFeature_Message_EnableFolderView>TRUE</CscFeature_Message_EnableFolderView>
<CscFeature_Message_EnableFontSize>TRUE</CscFeature_Message_EnableFontSize>
<CscFeature_Message_EnableFontSizeByVolumeKey>TRUE</CscFeature_Message_EnableFontSizeByVolumeKey>
<CscFeature_Message_EnableMenuInsertSenderInfoWhenFwdMsg>TRUE</CscFeature_Message_EnableMenuInsertSenderInfoWhenFwdMsg>
<CscFeature_Message_EnableMenuMmsDeliveryTime>TRUE</CscFeature_Message_EnableMenuMmsDeliveryTime>
<CscFeature_Message_EnableMenuMmsExpiryDate>TRUE</CscFeature_Message_EnableMenuMmsExpiryDate>
<CscFeature_Message_EnableMenuMmsPriority>TRUE</CscFeature_Message_EnableMenuMmsPriority>
<CscFeature_Message_EnableMenuRemindAlert>TRUE</CscFeature_Message_EnableMenuRemindAlert>
<CscFeature_Message_EnableMenuSendMmsDeliveryReport>TRUE</CscFeature_Message_EnableMenuSendMmsDeliveryReport>
<CscFeature_Message_EnableMenuSmsExpiryDate>FALSE</CscFeature_Message_EnableMenuSmsExpiryDate>
<CscFeature_Message_EnableMessagePriorityDuringComposing>TRUE</CscFeature_Message_EnableMessagePriorityDuringComposing>
<CscFeature_Message_EnableMessageSentTimeInSimList>TRUE</CscFeature_Message_EnableMessageSentTimeInSimList>
<CscFeature_Message_EnableMmsMobiledataOff>TRUE</CscFeature_Message_EnableMmsMobiledataOff>
<CscFeature_Message_EnableMsgTypeIndicationDuringComposing>TRUE</CscFeature_Message_EnableMsgTypeIndicationDuringComposing>
<CscFeature_Message_EnableMultiCopyToSim>TRUE</CscFeature_Message_EnableMultiCopyToSim>
<CscFeature_Message_EnableMultiDraftBox>TRUE</CscFeature_Message_EnableMultiDraftBox>
<CscFeature_Message_EnableMultiLockMenu>TRUE</CscFeature_Message_EnableMultiLockMenu>
<CscFeature_Message_EnableNotificationBroadcastReceivedMessage>TRUE</CscFeature_Message_EnableNotificationBroadcastReceivedMessage>
<CscFeature_Message_EnableRegisterToCalender>TRUE</CscFeature_Message_EnableRegisterToCalender>
<CscFeature_Message_EnableReplyAll>TRUE</CscFeature_Message_EnableReplyAll>
<CscFeature_Message_BlockSendMmsWithOnlySubject>TRUE</CscFeature_Message_BlockSendMmsWithOnlySubject>
<CscFeature_Message_EnableSaveVMessage>TRUE</CscFeature_Message_EnableSaveVMessage>
<CscFeature_Message_SupportAutoDeleteSpam>TRUE</CscFeature_Message_SupportAutoDeleteSpam>
<CscFeature_Message_EnableScheduledMessage>TRUE</CscFeature_Message_EnableScheduledMessage>
<CscFeature_Message_EnableScheduledMsgBox>TRUE</CscFeature_Message_EnableScheduledMsgBox>
<CscFeature_Message_EnableSearchByInitialConsonant>TRUE</CscFeature_Message_EnableSearchByInitialConsonant>
<CscFeature_Message_EnableSendingEmptySms>TRUE</CscFeature_Message_EnableSendingEmptySms>
<CscFeature_Message_EnableSmsCallbackNumber>TRUE</CscFeature_Message_EnableSmsCallbackNumber>
<CscFeature_Message_EnableSmsForwardPrefix>TRUE</CscFeature_Message_EnableSmsForwardPrefix>
<CscFeature_Message_EnableSMSPcheckWhenSendSMS>TRUE</CscFeature_Message_EnableSMSPcheckWhenSendSMS>
<CscFeature_Message_EnableSpeedDial>TRUE</CscFeature_Message_EnableSpeedDial>
<CscFeature_Message_EnableTextFieldColor>TRUE</CscFeature_Message_EnableTextFieldColor>
<CscFeature_Message_EnableVCard>TRUE</CscFeature_Message_EnableVCard>
<CscFeature_Message_EnableViewByMessageType>TRUE</CscFeature_Message_EnableViewByMessageType>
<CscFeature_Message_MaxSlideCount>999</CscFeature_Message_MaxSlideCount>
<CscFeature_Message_RecipientLimit>999</CscFeature_Message_RecipientLimit>
<CscFeature_Message_SmsToMmsTextThreshold>999</CscFeature_Message_SmsToMmsTextThreshold>
<CscFeature_Message_SmsMaxByte>999</CscFeature_Message_SmsMaxByte>
<CscFeature_Message_ReplaceCRToNewLine>TRUE</CscFeature_Message_ReplaceCRToNewLine>
<CscFeature_Message_ReplaceLabel4RetreivedMsg>TRUE</CscFeature_Message_ReplaceLabel4RetreivedMsg>
<CscFeature_Message_SmsInputMode>automatic</CscFeature_Message_SmsInputMode>
```

### ¬ NFC
```
<CscFeature_NFC_FollowTechnologyRouteToDefRoute>TRUE</CscFeature_NFC_FollowTechnologyRouteToDefRoute>
<CscFeature_NFC_DefStatus>OFF</CscFeature_NFC_DefStatus>
<CscFeature_NFC_StatusBarIconType>DEFAULT</CscFeature_NFC_StatusBarIconType>
```

### ¬ RIL
```
<CscFeature_RIL_ConfigProvideCellInfo>Enable</CscFeature_RIL_ConfigProvideCellInfo>
<CscFeature_RIL_CallerIdMatchingDigit>TRUE</CscFeature_RIL_CallerIdMatchingDigit>
<CscFeature_RIL_ConfigDataStatus>FALSE</CscFeature_RIL_ConfigDataStatus>
<CscFeature_RIL_DefaultDataStateFalse>TRUE</CscFeature_RIL_DefaultDataStateFalse>
<CscFeature_RIL_DisplayStkUssdDialog>TRUE</CscFeature_RIL_DisplayStkUssdDialog>
<CscFeature_RIL_EnableLaunchBrowser>TRUE</CscFeature_RIL_EnableLaunchBrowser>
<CscFeature_RIL_ForceConnectMMS>TRUE</CscFeature_RIL_ForceConnectMMS>
<CscFeature_RIL_HandleInvalidTimezonOffset>TRUE</CscFeature_RIL_HandleInvalidTimezonOffset>
<CscFeature_RIL_HandleUnsupportedDns64DuringDownBooster>TRUE</CscFeature_RIL_HandleUnsupportedDns64DuringDownBooster>
<CscFeature_RIL_SupportLteRoaming>TRUE</CscFeature_RIL_SupportLteRoaming>
<CscFeature_RIL_SupportEsim>FALSE</CscFeature_RIL_SupportEsim>
<CscFeature_RIL_SupportMptcp>TRUE</CscFeature_RIL_SupportMptcp>
<CscFeature_RIL_SupportVolte>TRUE</CscFeature_RIL_SupportVolte>
<CscFeature_RIL_DefTimeZoneHandling>Enable</CscFeature_RIL_DefTimeZoneHandling>
<CscFeature_RIL_Display4gPlusIconBandwidth>14</CscFeature_RIL_Display4gPlusIconBandwidth>
```

### ¬ Vision
```
<CscFeature_Vision_ConfigImageSearch>PTRXX</CscFeature_Vision_ConfigImageSearch>
<CscFeature_Vision_ConfigPlace>FSRXX</CscFeature_Vision_ConfigPlace>
<CscFeature_Vision_ConfigShopping>AMZUK</CscFeature_Vision_ConfigShopping>
<CscFeature_Vision_ConfigTextTranslator>GGLXX</CscFeature_Vision_ConfigTextTranslator>
<CscFeature_Vision_ConfigWine>VVNXX</CscFeature_Vision_ConfigWine>
<CscFeature_Vision_ConfigBeauty>NLLXX</CscFeature_Vision_ConfigBeauty>
<CscFeature_Vision_ConfigFood>NLLXX</CscFeature_Vision_ConfigFood>
<CscFeature_Vision_ConfigImageSearch>PTRXX</CscFeature_Vision_ConfigImageSearch>
<CscFeature_Vision_ConfigPlace>FSRXX</CscFeature_Vision_ConfigPlace>
<CscFeature_Vision_ConfigPlaceLandmark>SFSGO</CscFeature_Vision_ConfigPlaceLandmark>
<CscFeature_Vision_ConfigPlaceMap>GGLXX</CscFeature_Vision_ConfigPlaceMap>
<CscFeature_Vision_ConfigPlaceWeather>TWCXX</CscFeature_Vision_ConfigPlaceWeather>
<CscFeature_Vision_ConfigShopping>NLLXX</CscFeature_Vision_ConfigShopping>
<CscFeature_Vision_ConfigTextExchangerate>OANXX</CscFeature_Vision_ConfigTextExchangerate>
<CscFeature_Vision_ConfigTextTranslator>GGLXX</CscFeature_Vision_ConfigTextTranslator>
<CscFeature_Vision_ConfigWine>NLLXX</CscFeature_Vision_ConfigWine>
```

### ¬ Weather
```
<CscFeature_Weather_ConfigCpType>TWC</CscFeature_Weather_ConfigCpType>
<CscFeature_Weather_SupportCheckingDisputeArea>TRUE</CscFeature_Weather_SupportCheckingDisputeArea>
```

### ¬ Browser
```
<CscFeature_Web_ConfigDefaultSearchEngine>google.com</CscFeature_Web_ConfigDefaultSearchEngine>
<CscFeature_Web_ConfigSyncSource>TRUE</CscFeature_Web_ConfigSyncSource>
<CscFeature_Web_EnableAutoSimHomeUrlInProfile>TRUE</CscFeature_Web_EnableAutoSimHomeUrlInProfile>
```

### ¬ Dialer
```
<CscFeature_Dialer_PhonebookNdigitsMatching>TRUE</CscFeature_Dialer_PhonebookNdigitsMatching>
```

### ¬ VoLTE
```
<CscFeature_VoiceCall_ConfigOpStyleForMobileNetSetting>voltesettingscommon,checknonvoltesim,voltesettingOPS</CscFeature_VoiceCall_ConfigOpStyleForMobileNetSetting>
```

### ¬ Email
```
<CscFeature_Email_AlignmentForRTL>TRUE</CscFeature_Email_AlignmentForRTL>
<CscFeature_Email_DisableFontAttributeDuringComposing>Bold, Italic</CscFeature_Email_DisableFontAttributeDuringComposing>
<CscFeature_Email_EnableSaveAsAttachment>TRUE</CscFeature_Email_EnableSaveAsAttachment>
<CscFeature_Email_EnableSyncAndConnect>TRUE</CscFeature_Email_EnableSyncAndConnect>
```
### ¬ Framework
```
<CscFeature_Framework_ReplaceDataTypeIconAsOpBrand>LTE</CscFeature_Framework_ReplaceDataTypeIconAsOpBrand>
<CscFeature_Framework_SupportDataModeSwitchGlobalAction>TRUE</CscFeature_Framework_SupportDataModeSwitchGlobalAction>
```

### ¬ GPS
```
<CscFeature_GPS_SupportPrivacyLock>TRUE</CscFeature_GPS_SupportPrivacyLock>
<CscFeature_GPS_SupportGoogleSupl2>TRUE</CscFeature_GPS_SupportGoogleSupl2>
```

### ¬ IMS
```
<CscFeature_IMS_EnableVoLTE>TRUE</CscFeature_IMS_EnableVoLTE>
```

### ¬ Launcher
```
<CscFeature_Launcher_DisableFastScrollIndex>TRUE</CscFeature_Launcher_DisableFastScrollIndex>
<CscFeature_Launcher_AddAutoRotationIcon>TRUE</CscFeature_Launcher_AddAutoRotationIcon>
<CscFeature_Launcher_SupportBadgeClearGesture>TRUE</CscFeature_Launcher_SupportBadgeClearGesture>
<CscFeature_Launcher_ConfigMagazineHome>off</CscFeature_Launcher_ConfigMagazineHome>
<CscFeature_Launcher_PerformanceTunning>TRUE</CscFeature_Launcher_PerformanceTunning>
```

### ¬ Music
```
<CscFeature_Music_SupportPlaybackDuringCall>TRUE</CscFeature_Music_SupportPlaybackDuringCall>
<CscFeature_MediaProvider_HideVoiceFilesInMusic>TRUE</CscFeature_MediaProvider_HideVoiceFilesInMusic>
<CscFeature_Music_TranslateUnknownTitle>TRUE</CscFeature_Music_TranslateUnknownTitle>
```

### ¬ My Files
```
<CscFeature_MyFiles_SupportApkCategory>TRUE</CscFeature_MyFiles_SupportApkCategory>
<CscFeature_MyFiles_SupportFolderDescription>TRUE</CscFeature_MyFiles_SupportFolderDescription>
```
### ¬ SyncML
```
<CscFeature_SyncML_DiscardCpSecurityType4>Userpin,Usernetwpin,None</CscFeature_SyncML_DiscardCpSecurityType4>
```

### ¬ Web
```
<CscFeature_Web_AddOptionToTerminate>TRUE</CscFeature_Web_AddOptionToTerminate>
<CscFeature_Web_ConfigSyncSource>TRUE</CscFeature_Web_ConfigSyncSource>
<CscFeature_Web_bool_EnablePriorityUserBookmark>FALSE</CscFeature_Web_bool_EnablePriorityUserBookmark>
<CscFeature_Web_EnableMaxTabs>1000</CscFeature_Web_EnableMaxTabs>
<CscFeature_Web_EnablePromptToExit>TRUE</CscFeature_Web_EnablePromptToExit>
<CscFeature_Web_SetHomepageURL>https://forum.xda-developers.com/member.php?u=10949429</CscFeature_Web_SetHomepageURL>
```

### ¬ Wifi
```
<CscFeature_Wifi_MaxClient4MobileAp>10</CscFeature_Wifi_MaxClient4MobileAp>
<CscFeature_Wifi_SetCountryInfo>TRUE</CscFeature_Wifi_SetCountryInfo>
<CscFeature_Wifi_SupportAdvancedMenu>TRUE</CscFeature_Wifi_SupportAdvancedMenu>
<CscFeature_Wifi_SupportMobileApOnTrigger>TRUE</CscFeature_Wifi_SupportMobileApOnTrigger>
<CscFeature_Wifi_ConfigSnsStatus>DEFAULT_ON</CscFeature_Wifi_ConfigSnsStatus>
<CscFeature_Wifi_ConfigSecureSvcIntegration>TencentSecurityWiFi</CscFeature_Wifi_ConfigSecureSvcIntegration>
<CscFeature_Wifi_SupportSecureWifi>FALSE</CscFeature_Wifi_SupportSecureWifi>
```

### ¬ BikeMode
```
<CscFeature_Common_ConfigBikeMode>bikemode|rewards|globalaction</CscFeature_Common_ConfigBikeMode>
```

### ¬ VT
```
<CscFeature_VT_ConfigPrivacyPolicy>record,capture</CscFeature_VT_ConfigPrivacyPolicy>
<CscFeature_VT_ConfigCapability>emergency,pip_peer</CscFeature_VT_ConfigCapability>
<CscFeature_VT_SupportMerge>TRUE</CscFeature_VT_SupportMerge>
<CscFeature_VT_SupportEmergencyCall>TRUE</CscFeature_VT_SupportEmergencyCall>
<CscFeature_VT_SupportGroupCall>TRUE</CscFeature_VT_SupportGroupCall>
<CscFeature_VT_SupportOutgoingImageFromGallery>TRUE</CscFeature_VT_SupportOutgoingImageFromGallery>
```

### ¬ Setup Wizard
```
<CscFeature_SetupWizard_DisablePrivacyPolicyAgreement>TRUE</CscFeature_SetupWizard_DisablePrivacyPolicyAgreement>
```

### ¬ Lockscreen
```
<CscFeature_LockScreen_ConfigCarrierSecurityPolicy>SupportSimPermanentDisable</CscFeature_LockScreen_ConfigCarrierSecurityPolicy>
<CscFeature_LockScreen_ConfigClockDisplayPolicy>ShowRomaingTime</CscFeature_LockScreen_ConfigClockDisplayPolicy>
```
