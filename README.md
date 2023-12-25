# Build.prop Tweaks
Add these lines in Build.prop, which is located in system/system. (Some probably is placebo i haven't tested all of them)

### 01. Camera Tweaks -> Improves audio and video recording quality
```
ro.media.enc.jpeg.quality=100
ro.media.dec.jpeg.memcap=8000000
ro.media.enc.hprof.vid.bps=8000000
ro.media.capture.maxres=8m
ro.media.panorama.defres=3264×1840
ro.media.panorama.frameres=1280×720
ro.camcorder.videoModes=true
ro.media.enc.hprof.vid.fps=65
```
### 02. Better image quality, lower performance.
```
persist.sys.use_dithering=1
```

### 03. Faster streaming videos
```media.stagefright.enable-player=true
media.stagefright.enable-meta=true
media.stagefright.enable-scan=true
media.stagefright.enable-http=true
media.stagefright.enable-rtsp=true
media.stagefright.enable-record=false
```
### 04. Disables built in error reporting.
```
profiler.force_disable_err_rpt=1
profiler.force_disable_ulog=1
```
### 05. Better net speeds.
```
net.tcp.buffersize.default=4096,87380,256960, 4096, 16384,256960
net.tcp.buffersize.wifi=4096,87380,256960,409 6,163 84,256960
net.tcp.buffersize.umts=4096,8 7380,256960,4096,163 84,256960
net.tcp.buffersize.gprs=4096,8 7380,256960,4096,163 84,256960
net.tcp.buffersize.edge=4096,8 7380,256960,4096,163 84,256960
```
### 06. Disables logcat
```
logcat.live=disable
```
### 07. Phone rings immediately.
```
ro.telephony.call_ring.delay=0
ring.delay=0
```
### 08. Better call voice quality.
```
ro.ril.enable.amr.wideband=1
```
### 09. Better signal.
```
persist.cust.tel.eons=1
ro.config.hw_fast_dormancy=1
```
### 10. Disable notification while adb is active
```
persist.adb.notify=0
```
### 11. General Performance
```
debug.sf.hw=1
persist.sys.ui.hw=1
```
### 11. Saves power
```
ro.ril.disable.power.collapse=1
pm.sleep_mode=1
windowsmgr.max_events_per_sec=60
wifi.supplicant_scan_interval=180
```
### 12. Faster boot time
```
persist.sys.shutdown.mode=hibernate
ro.config.hw_quickpoweron=true
```
### 13. Better Responsiveness & Speed 
```
windowsmgr.max_events_per_sec=300
ro.max.fling_velocity=15000 
ro.min.fling_velocity=8000 
ro.min_pointer_dur=8
touch.pressure.scale=0.1
```
### 14. Video Acceleration Enabled And HW debugging
```
debug.hwui.renderer=skiagl
video.accelerate.hw=1
debug.sf.hw=1
debug.performance.tuning=1
debug.egl.hw=1
debug.composition.type=gpu
```
### 15. GOOGLE DNS
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

Credit: <a href="https://xdaforums.com/t/tweaks-guide-build-prop-tweaks.3376962/">@XDA
</a> | [This post](https://xdaforums.com/t/tweaks-for-the-build-prop.3456214/) <hr>

### ¬ Enable Zygote preforking
```
persist.device_config.runtime_native.usap_pool_enabled=true
```

### ¬ Enable 4K in YouTube ( Some Regions only, can make UI laggy )
```
sys.display-size=3840x2160
video.accelerate.hw=1
ro.media.enc.jpeg.quality=100
ro.media.dec.jpeg.memcap=8000000
ro.media.enc.hprof.vid.bps=8000000
ro.media.enc.hprof.vid.fps=65
```

### ¬ Enable Launcher in Memory
```
ro.HOME_APP_ADJ=15
ro.FOREGROUND_APP_ADJ=0
ro.VISIBLE_APP_ADJ=4
ro.HIDDEN_APP_MIN_ADJ=7
```

### ¬ Enable Multi User
```
fw.max_users=5
fw.show_multiuserui=1
fw.showhiddenusers=1 
fw.poweruserswitcher=1
```

### ¬ Enable Google Assistant
```
ro.opa.eligible_device=true
```

### ¬ SafetyNET Fix
```
ro.knox.enhance.zygote.aslr=1
```

### ¬  Enable Multi Sim
```
ro.multisim.simslotcount=2
```

### ¬  Disable Knox
```
ro.securestorage.knox=false
```

### ¬  RMM Fix
```
ro.security.vaultkeeper.native=0
```

### ¬  Disable Locating
```
ro.com.google.locationfeatures=0
ro.com.google.networklocation=0
```

### ¬  Enable Secure Storage
```
ro.securestorage.support=false
```

### ¬  Disable OEM Unlock Toggle
```
ro.frp.pst=
```

### ¬  ADB Fix
```
persist.adb.notify=0
persist.service.adb.enable=1
persist.sys.usb.config=mtp,adb
persist.service.debuggable=1
```

### ¬ Enable Fast Dormancy
```
ro.fast.dormancy=1
ro.config.hw_fast_dormancy=1
ro.ril.fast.dormancy.rule=1
ro.semc.enable.fast_dormancy=true
```

### ¬ Force GPU Rendering on 2d Operations
```
debug.sf.hw=1
debug.egl.profiler=1
debug.egl.hw=1
```

### ¬ Call Delay Fix
```
ro.telephony.call.ring.delay=0
ring.delay=0
```

### ¬ Increase Time Duration For WiFi scanning
```
wifi.supplicant_scan_interval=XXX
```

### ¬ Save Battery Without Performance Drop
```
pm.sleep_mode=1
ro.ril.disable.power.collapse=0
wifi.supplicant_scan_interval=180
```

### ¬ Fps cap remover
```
debug.gr.swapinterval=0
ro.fps_enable=1
ro.fps.capsmin=40fps
ro.fps.capsmax=60fps
cpu.fps=60
gpu.fps=60
```

### ¬ Faster Booting
```
ro.config.hw_quickpoweron=true
```

### ¬ Dalvik Virtual Machine Tweaks
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

### ¬ FPS Stabilizer
```
debug.sf.showupdates=0
debug.sf.showcpu=0
debug.sf.showbackground=0
debug.sf.showfps=0
```

### ¬ Enable Vulkan
```
ro.hwui.use_vulkan=1
```

### ¬ Dalvik JIT for Dex
```
debug.usejit=true
```

### ¬ RIL Wakelock Optimization
```
ro.ril.wake_lock_timeout=10000
```

### ¬ Audio Improvements
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

### ¬ Extra Dim ( Add in /vendor/build.prop, might cause issues with DRM )
```
ro.surface_flinger.protected_contents=true
```
