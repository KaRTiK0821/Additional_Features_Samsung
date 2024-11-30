# Build.prop Tweaks
Add these lines in Build.prop, which is located in system/system.
### 01. Circle to search A14+
```
ro.com.google.cdb.spa1=bsxasm1
ro.bbt.support.circle2search=true
```
> [!NOTE]  
> - These two circle to search build.prop codes aren't enough to enable circle2search, it requires framework & device support, but it's also a part of circle to search that's why it's given here.
### 02. Camera Tweaks -> Improves audio and video recording quality
> [!NOTE]  
> - Can cause issues with video streaming.
```
ro.media.enc.jpeg.quality=100
ro.media.dec.jpeg.memcap=8000000
ro.media.enc.hprof.vid.bps=8000000
ro.media.capture.maxres=8m
ro.media.panorama.defres=3264×1840
ro.media.panorama.frameres=1280×720
ro.camcorder.videoModes=true
ro.media.enc.hprof.vid.fps=65
ro.camera.enableCamera1MaxZsl=1
camera.disable_zsl_mode=1
```
### 03. Better display quality
> [!NOTE]  
> - Can cause performance issues.
```
persist.sys.use_dithering=1
```

### 04. Faster streaming videos
```
media.stagefright.enable-player=true
media.stagefright.enable-meta=true
media.stagefright.enable-scan=true
media.stagefright.enable-http=true
media.stagefright.enable-rtsp=true
media.stagefright.enable-record=false
```
### 05. Disables built in error reporting.
```
profiler.force_disable_err_rpt=1
profiler.force_disable_ulog=1
```
### 06. Better net speeds.
```
net.tcp.buffersize.default=4096,87380,256960,4096,16384,256960
net.tcp.buffersize.wifi=4096,87380,256960,4096,16384,256960
net.tcp.buffersize.umts=4096,87380,256960,4096,16384,256960
net.tcp.buffersize.gprs=4096,87380,256960,4096,16384,256960
net.tcp.buffersize.edge=4096,87380,256960,4096,16384,256960
```
### 07. Disables logcat
```
logcat.live=disable
```
### 08. Phone rings immediately.
```
ro.telephony.call_ring.delay=0
ring.delay=0
```
### 09. Better call voice quality.
```
ro.ril.enable.amr.wideband=1
```
### 10. Better signal.
```
persist.cust.tel.eons=1
ro.config.hw_fast_dormancy=1
```
### 11. Disable notification while adb is active
```
persist.adb.notify=0
```
### 12. General Performance
```
debug.sf.hw=1
persist.sys.ui.hw=1
```
### 13. Saves power
```
ro.ril.disable.power.collapse=1
pm.sleep_mode=1
windowsmgr.max_events_per_sec=60
wifi.supplicant_scan_interval=180
```
### 14. Faster boot time
```
persist.sys.shutdown.mode=hibernate
ro.config.hw_quickpoweron=true
```
### 15. Better Responsiveness & Speed 
```
windowsmgr.max_events_per_sec=300
ro.max.fling_velocity=15000 
ro.min.fling_velocity=8000 
ro.min_pointer_dur=8
touch.pressure.scale=0.1
```
### 16. Gpu Acceleration and HW Debugging
```
debug.hwui.renderer=skiagl
video.accelerate.hw=1
debug.sf.hw=1
debug.performance.tuning=1
debug.egl.hw=1
debug.composition.type=gpu
```
### 17. GOOGLE DNS
```
net.dns1=8.8.8.8
net.dns2=8.8.4.4
net.rmnet0.dns1=8.8.8.8
net.rmnet0.dns2=8.8.4.4
net.ppp0.dns1=8.8.8.8
net.ppp0.dns2=8.8.4.4
net.wlan0.dns1=8.8.8.8
net.wlan0.dns2=8.8.4.4
net.eth0.dns1=8.8.8.8
net.eth0.dns2=8.8.4.4
net.gprs.dns1=8.8.8.8
net.gprs.dns2=8.8.4.4
```

### 18. Enable Zygote preforking
```
persist.device_config.runtime_native.usap_pool_enabled=true
```
### 19. Enable Launcher in Memory
```
ro.HOME_APP_ADJ=15
ro.FOREGROUND_APP_ADJ=0
ro.VISIBLE_APP_ADJ=4
ro.HIDDEN_APP_MIN_ADJ=7
```
> [!NOTE]  
> - Enable launcher in memory isn't supported after android 7+
### 20. Enable Multi User
```
fw.max_users=5
fw.show_multiuserui=1
fw.showhiddenusers=1 
fw.poweruserswitcher=1
```

### 21. Enable Google Assistant
```
ro.opa.eligible_device=true
```
> [!NOTE]  
> - This code will enable Google Assistant 2.0 the new one for all devices, requires Google Assistant supported Google version.
### 22. SafetyNET Fix
```
ro.knox.enhance.zygote.aslr=1
```

### 23.  Enable Multi Sim
```
ro.multisim.simslotcount=2
```

### 24.  Disable Knox
```
ro.securestorage.knox=false
```

### 25.  RMM Fix
```
ro.security.vaultkeeper.native=0
```

### 26.  Disable Locating
```
ro.com.google.locationfeatures=0
ro.com.google.networklocation=0
```

### 27. Enable Secure Storage
```
ro.securestorage.support=false
```

### 28.  Disable OEM Unlock Toggle
```
ro.frp.pst=
```

### 29.  ADB Fix
```
persist.adb.notify=0
persist.service.adb.enable=1
persist.sys.usb.config=mtp,adb
persist.service.debuggable=1
```

### 30. Enable Fast Dormancy
```
ro.fast.dormancy=1
ro.config.hw_fast_dormancy=1
ro.ril.fast.dormancy.rule=1
ro.semc.enable.fast_dormancy=true
```

### 31. Increase Time Duration For WiFi scanning
```
wifi.supplicant_scan_interval=XXX
```

### 32. Save Battery Without Performance Drop
```
pm.sleep_mode=1
ro.ril.disable.power.collapse=0
wifi.supplicant_scan_interval=180
```

### 33. Fps cap remover
```
debug.gr.swapinterval=0
ro.fps_enable=1
ro.fps.capsmin=40fps
ro.fps.capsmax=60fps
cpu.fps=60
gpu.fps=60
```

### 34. Faster Booting (Might create pressure in ram)
```
ro.config.hw_quickpoweron=true
```

### 35. Dalvik Virtual Machine Tweaks
```
dalvik.vm.checkjni=false
dalvik.vm.dexopt-data-only=1
dalvik.vm.heapstartsize=5m
dalvik.vm.heapgrowthlimit=48m
dalvik.vm.heapsize=64m
dalvik.vm.verify-bytecode=false
dalvik.vm.execution-mode=int:jit
dalvik.vm.lockprof.threshold=250
dalvik.vm.dexopt-flags=m=v,o=y
dalvik.vm.stack-trace-file=/data/anr/traces.txt
dalvik.vm.jmiopts=forcecopy
```

### 36. FPS Stabilizer
```
debug.sf.showupdates=0
debug.sf.showcpu=0
debug.sf.showbackground=0
debug.sf.showfps=0
```

### 37. Enable Vulkan
```
ro.hwui.use_vulkan=1
```

### 38. Dalvik JIT for Dex
```
debug.usejit=true
```

### 39. RIL Wakelock Optimization
```
ro.ril.wake_lock_timeout=10000
```

### 40. Audio Improvements
```
vendor.audio.media.stereo.control=0
persist.audio.dualmic.config=endfire
persist.audio.fluence.mode=endfire
persist.audio.fluence.voicecall=true
persist.vendor.audio.fluence.voicecomm=true
persist.audio.fluence.voicerec=false
persist.audio.fluence.speaker=true
audio.deep_buffer.media=true
vendor.voice.conc.fallbackpath=deep-buffer
ro.media.dec.aud.mp3.enabled=1
ro.media.enc.aud.mp3.enabled=1
ro.media.dec.aud.flac.enabled=1
ro.media.enc.aud.flac.enabled=1
ro.media.dec.aud.wma.enabled=1
ro.media.enc.aud.wma.enabled=1
media.aac_51_output_enabled=true
flac.sw.decoder.24bit.support=true
persist.audio.speaker.dualmode=true
vendor.audio.playback.mch.downsample=true
vendor.audio.use.sw.alac.decoder=true
vendor.audio.use.sw.ape.decoder=true
af.fast_track_multiplier=1
```

### 41. Extra Dim ( Add in /vendor/build.prop )
```
ro.surface_flinger.protected_contents=true
```
> [!NOTE]  
> - This code will enable Rounded corners for PIP - Picture in picture.

### 42. Enable Webcam support for OneUI6.0+
```
ro.usb.uvc.enabled=true
```
> [!NOTE]  
> - Requires kernel support & plugins.
### 43. Enable Angle Support OneUi6.0+
```
ro.gfx.angle.supported=true
```
### 44. Change User interface like Tablet
```
ro.build.characteristics=tablet
```
### 45. Less ram and battery usage
```
debug.force_low_ram=true
ro.config.small_battery=true
```
