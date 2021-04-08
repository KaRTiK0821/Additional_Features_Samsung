# Floating Feature Tweaks
Add these lines in vendor/etc/floating_feature.xml or system/etc/floating_feature.xml.

### ¬ Enable Multiwindow tray
```
<SEC_FLOATING_FEATURE_COMMON_CONFIG_MULTIWINDOW_TRAY>TRUE</SEC_FLOATING_FEATURE_COMMON_CONFIG_MULTIWINDOW_TRAY>
```

### ¬ Enable Flagship Launcher Animations
Search for the following line in floating_feature.xml:
```
<SEC_FLOATING_FEATURE_LAUNCHER_CONFIG_ANIMATION_TYPE>
```
And change value from "LowEnd" or "Mass" to "HighEnd"
```
<SEC_FLOATING_FEATURE_LAUNCHER_CONFIG_ANIMATION_TYPE>HighEnd</SEC_FLOATING_FEATURE_LAUNCHER_CONFIG_ANIMATION_TYPE>
```

### ¬ Enable High Performance Mode
```
<SEC_FLOATING_FEATURE_COMMON_SUPPORT_HIGH_PERFORMANCE_MODE>TRUE</SEC_FLOATING_FEATURE_COMMON_SUPPORT_HIGH_PERFORMANCE_MODE>
<SEC_FLOATING_FEATURE_SYSTEM_SUPPORT_ENHANCED_CPU_RESPONSIVENESS>TRUE</SEC_FLOATING_FEATURE_SYSTEM_SUPPORT_ENHANCED_CPU_RESPONSIVENESS>
```

### ¬ Enable Flagship Edge Ligthining+ Animations
Search for the following line in floating_feature.xml:
```
<SEC_FLOATING_FEATURE_COMMON_CONFIG_EDGE>
```
And remove  "-basic_lighting" line, then it should look like this:
```
<SEC_FLOATING_FEATURE_COMMON_CONFIG_EDGE>people,task,circle,panel,-edgefeeds,edgelighting_v2,debug,cornerR:6.2,search,phonecolor,dot_bottom</SEC_FLOATING_FEATURE_COMMON_CONFIG_EDGE>
```

### ¬ Enable Spotify as added alarm
```
<SEC_FLOATING_FEATURE_CLOCK_CONFIG_ALARM_SOUND>spotify</SEC_FLOATING_FEATURE_CLOCK_CONFIG_ALARM_SOUND>
```

### ¬ Enable Side Key Function
```
<SEC_FLOATING_FEATURE_SETTINGS_SUPPORT_FUNCTION_KEY_MENU>TRUE</SEC_FLOATING_FEATURE_SETTINGS_SUPPORT_FUNCTION_KEY_MENU>
```

### ¬ Change Device Name to Your Choosed one
Search for the following line in floating_feature.xml:
```
<SEC_FLOATING_FEATURE_SETTINGS_CONFIG_BRAND_NAME>
```
And edit from Your Model to Your Choosed Name, then it shoud look like this:
```
<SEC_FLOATING_FEATURE_SETTINGS_CONFIG_BRAND_NAME>Your Choosed Name</SEC_FLOATING_FEATURE_SETTINGS_CONFIG_BRAND_NAME>
```


### ¬ Enable AOD Clock Transition Animation
Search for the following line in floating_feature.xml:
```
<SEC_FLOATING_FEATURE_FRAMEWORK_CONFIG_AOD_ITEM>
```
And add "clocktransition" and "activeclock=4" in the following line, then it should look like this:
```
<SEC_FLOATING_FEATURE_FRAMEWORK_CONFIG_AOD_ITEM>aodversion=7,clearcoveroff,clocktransition,activeclock=4</SEC_FLOATING_FEATURE_FRAMEWORK_CONFIG_AOD_ITEM>
```

### ¬ Enable Dolby Atmos without Headsets
```
<SEC_FLOATING_FEATURE_AUDIO_SUPPORT_DUAL_SPEAKER>TRUE</SEC_FLOATING_FEATURE_AUDIO_SUPPORT_DUAL_SPEAKER>
```
Search for the following line in floating_feature.xml:
```
<SEC_FLOATING_FEATURE_AUDIO_CONFIG_SOUNDALIVE_VERSION>
```
And replace which these lines:
```
eq_knob,eq_custom,uhq_switch,uhq_level,adapt,spk_stereo,dvfs_860000,tube,concert
```

### ¬ Enable Music Information in AOD
Search for the following line in floating_feature.xml:
```
<SEC_FLOATING_FEATURE_FRAMEWORK_CONFIG_AOD_ITEM>
```
And remove  "musicoff" line, then it should look like this:
```
<SEC_FLOATING_FEATURE_FRAMEWORK_CONFIG_AOD_ITEM>aodversion=7,clearcoveroff</SEC_FLOATING_FEATURE_FRAMEWORK_CONFIG_AOD_ITEM>
```

### ¬ Enable Dolby Atmos in Games
```
<SEC_FLOATING_FEATURE_AUDIO_SUPPORT_DEFAULT_ON_DOLBY_IN_GAME>TRUE</SEC_FLOATING_FEATURE_AUDIO_SUPPORT_DEFAULT_ON_DOLBY_IN_GAME>
```

### ¬ Enable Dolby Atmos Game Profiles
```
<SEC_FLOATING_FEATURE_AUDIO_SUPPORT_DOLBY_GAME_PROFILE>TRUE</SEC_FLOATING_FEATURE_AUDIO_SUPPORT_DOLBY_GAME_PROFILE>
```

### ¬ Enable Advanced Screen Capture
```
<SEC_FLOATING_FEATURE_FRAMEWORK_SUPPORT_SCREEN_CAPTURE_ADVANCED_EDIT_VI>TRUE</SEC_FLOATING_FEATURE_FRAMEWORK_SUPPORT_SCREEN_CAPTURE_ADVANCED_EDIT_VI>
<SEC_FLOATING_FEATURE_FRAMEWORK_SUPPORT_SCREEN_RECORDER>TRUE</SEC_FLOATING_FEATURE_FRAMEWORK_SUPPORT_SCREEN_RECORDER>
<SEC_FLOATING_FEATURE_FRAMEWORK_CONFIG_SCREEN_RECORDER_ITEM>-pip</SEC_FLOATING_FEATURE_FRAMEWORK_CONFIG_SCREEN_RECORDER_ITEM>
```

### ¬ Enable Wireless PowerShare
```
<SEC_FLOATING_FEATURE_BATTERY_SUPPORT_HV>TRUE</SEC_FLOATING_FEATURE_BATTERY_SUPPORT_HV>
<SEC_FLOATING_FEATURE_BATTERY_SUPPORT_WIRELESS_HV>TRUE</SEC_FLOATING_FEATURE_BATTERY_SUPPORT_WIRELESS_HV>
<SEC_FLOATING_FEATURE_BATTERY_SUPPORT_WIRELESS_NIGHT_MODE>TRUE</SEC_FLOATING_FEATURE_BATTERY_SUPPORT_WIRELESS_NIGHT_MODE>
<SEC_FLOATING_FEATURE_BATTERY_SUPPORT_WIRELESS_TX>TRUE</SEC_FLOATING_FEATURE_BATTERY_SUPPORT_WIRELESS_TX>
<SEC_FLOATING_FEATURE_COMMON_CONFIG_DEX_MODE>dual,wireless,dexforpc</SEC_FLOATING_FEATURE_COMMON_CONFIG_DEX_MODE>
<SEC_FLOATING_FEATURE_COMMON_SUPPORT_DEX_WIRELESS>TRUE</SEC_FLOATING_FEATURE_COMMON_SUPPORT_DEX_WIRELESS>
<SEC_FLOATING_FEATURE_COMMON_SUPPORT_DEX_MULTI_RATIO>TRUE</SEC_FLOATING_FEATURE_COMMON_SUPPORT_DEX_MULTI_RATIO>
<SEC_FLOATING_FEATURE_COMMON_SUPPORT_DEX_ON_PC>TRUE</SEC_FLOATING_FEATURE_COMMON_SUPPORT_DEX_ON_PC>
```

### ¬ Enable Ultra Power Saving
```
<SEC_FLOATING_FEATURE_COMMON_SUPPORT_ULTRA_POWER_SAVING>TRUE</SEC_FLOATING_FEATURE_COMMON_SUPPORT_ULTRA_POWER_SAVING>
```

### ¬ Enable Secure Wifi
```
<SEC_FLOATING_FEATURE_WLAN_SUPPORT_SECURE_WIFI>TRUE</SEC_FLOATING_FEATURE_WLAN_SUPPORT_SECURE_WIFI>
```

### ¬ 60Hz Default
```
<SEC_FLOATING_FEATURE_LCD_CONFIG_HFR_DEFAULT_REFRESH_RATE>60</SEC_FLOATING_FEATURE_LCD_CONFIG_HFR_DEFAULT_REFRESH_RATE>
<SEC_FLOATING_FEATURE_LCD_CONFIG_HFR_MODE>0</SEC_FLOATING_FEATURE_LCD_CONFIG_HFR_MODE>
<SEC_FLOATING_FEATURE_LCD_CONFIG_HFR_SUPPORTED_REFRESH_RATE>60</SEC_FLOATING_FEATURE_LCD_CONFIG_HFR_SUPPORTED_REFRESH_RATE>
<SEC_FLOATING_FEATURE_LCD_CONFIG_SELFMASK_VERSION>0</SEC_FLOATING_FEATURE_LCD_CONFIG_SELFMASK_VERSION>
<SEC_FLOATING_FEATURE_LCD_SUPPORT_SELFMASK>TRUE</SEC_FLOATING_FEATURE_LCD_SUPPORT_SELFMASK>
```

### ¬ Disable Index Scroll
Search for the following line in floating_feature.xml:
```
<SEC_FLOATING_FEATURE_CONTACTS_SUPPORT_INDEX_SCROLL>
```
And change value from "TRUE" to "FALSE.
```
<SEC_FLOATING_FEATURE_CONTACTS_SUPPORT_INDEX_SCROLL>FALSE</SEC_FLOATING_FEATURE_CONTACTS_SUPPORT_INDEX_SCROLL>
```

### ¬ Disable Smart Switch
Search for the following line in floating_feature.xml:
```
<SEC_FLOATING_FEATURE_COMMON_SUPPORT_SMART_SWITCH>
```
And change value from "TRUE" to "FALSE.
```
<SEC_FLOATING_FEATURE_COMMON_SUPPORT_SMART_SWITCH>FALSE</SEC_FLOATING_FEATURE_COMMON_SUPPORT_SMART_SWITCH>
```

### ¬ Enable Drawer Clearer Contrast
```
<SEC_FLOATING_FEATURE_GRAPHICS_SUPPORT_3D_SURFACE_TRANSITION_FLAG>TRUE</SEC_FLOATING_FEATURE_GRAPHICS_SUPPORT_3D_SURFACE_TRANSITION_FLAG>
```

### ¬ Enable Smooth Scroll of Surface Flinger
```
<SEC_FLOATING_FEATURE_FRAMEWORK_SUPPORT_SMOOTH_SCROLL>TRUE</SEC_FLOATING_FEATURE_FRAMEWORK_SUPPORT_SMOOTH_SCROLL>
```

### ¬ Enable 3 Resolution options in Settings
```
<SEC_FLOATING_FEATURE_COMMON_CONFIG_DYN_RESOLUTION_CONTROL>WQHD,FHD,HD</SEC_FLOATING_FEATURE_COMMON_CONFIG_DYN_RESOLUTION_CONTROL>
```

### ¬ Disable Samsung Ads
Search for the following line in floating_feature.xml:
```
<SEC_FLOATING_FEATURE_COMMON_SUPPORT_SAMSUNG_MARKETING_INFO>
```
And change value from "TRUE" to "FALSE.
```
<SEC_FLOATING_FEATURE_COMMON_SUPPORT_SAMSUNG_MARKETING_INFO>FALSE</SEC_FLOATING_FEATURE_COMMON_SUPPORT_SAMSUNG_MARKETING_INFO>
```

### ¬ Enable Haptic Feedback in settings (Needs OneUI 2.5)
```
<SEC_FLOATING_FEATURE_AUDIO_SUPPORT_DC_MOTOR_HAPTIC_FEEDBACK>TRUE</SEC_FLOATING_FEATURE_AUDIO_SUPPORT_DC_MOTOR_HAPTIC_FEEDBACK>
```

### ¬ Enable darker Dark Mode (Needs OneUI 2.5)
```
<SEC_FLOATING_FEATURE_LCD_CONFIG_REPLACE_COLOR_FOR_DARKMODE>#FF171717</SEC_FLOATING_FEATURE_LCD_CONFIG_REPLACE_COLOR_FOR_DARKMODE>
```

### ¬ Enable custom values for Status Bar and QS panel
Change values from 0 to your dependencies
```
<SEC_FLOATING_FEATURE_SYSTEMUI_CONFIG_CORNER_ROUND>0</SEC_FLOATING_FEATURE_SYSTEMUI_CONFIG_CORNER_ROUND>
<SEC_FLOATING_FEATURE_SYSTEMUI_CONFIG_NOTIFICATION_BG_COLOR>0</SEC_FLOATING_FEATURE_SYSTEMUI_CONFIG_NOTIFICATION_BG_COLOR>
<SEC_FLOATING_FEATURE_SYSTEMUI_CONFIG_NOTIFICATION_ICON_SIZE>0</SEC_FLOATING_FEATURE_SYSTEMUI_CONFIG_NOTIFICATION_ICON_SIZE>
<SEC_FLOATING_FEATURE_SYSTEMUI_CONFIG_STATUSBAR_SIDE_PADDING>0</SEC_FLOATING_FEATURE_SYSTEMUI_CONFIG_STATUSBAR_SIDE_PADDING>
```

### ¬ Enable Live Clock in Launcher
```
<SEC_FLOATING_FEATURE_LAUNCHER_SUPPORT_CLOCK_LIVE_ICON>TRUE</SEC_FLOATING_FEATURE_LAUNCHER_SUPPORT_CLOCK_LIVE_ICON>
```

### ¬ Change battery capacity
Change values from 0000 to your dependencies.
```
<SEC_FLOATING_FEATURE_SETTINGS_CONFIG_BATTERY_CAPACITY>0000 mAh</SEC_FLOATING_FEATURE_SETTINGS_CONFIG_BATTERY_CAPACITY>
```

### ¬ Enable Game Launcher in Drawer
```
<SEC_FLOATING_FEATURE_GRAPHICS_SUPPORT_DEFAULT_GAMELAUNCHER_ENABLE>TRUE</SEC_FLOATING_FEATURE_GRAPHICS_SUPPORT_DEFAULT_GAMELAUNCHER_ENABLE>
```

### ¬ Enable Partial Blur (Needs OneUI 3.x)
```
<SEC_FLOATING_FEATURE_GRAPHICS_SUPPORT_PARTIAL_BLUR>TRUE</SEC_FLOATING_FEATURE_GRAPHICS_SUPPORT_PARTIAL_BLUR>
```

### ¬ Enable Semi Native Blur (Needs OneUI 3.x)
```
<SEC_FLOATING_FEATURE_GRAPHICS_SUPPORT_CAPTURED_BLUR>TRUE</SEC_FLOATING_FEATURE_GRAPHICS_SUPPORT_CAPTURED_BLUR>
```

### ¬ Enable Google Discover in Drawer (Needs OneUI 3.x)
```
<SEC_FLOATING_FEATURE_LAUNCHER_CONFIG_ZERO_PAGE_PACKAGE_NAMES>com.google.android.googlequicksearchbox</SEC_FLOATING_FEATURE_LAUNCHER_CONFIG_ZERO_PAGE_PACKAGE_NAMES>
```
