---
layout: default
---

# Changelog

* * *
### Build 2020-05-05
* * *

#### project build/
*  Bump Security String to 2020-04-05

#### project frameworks/base/
*  Fix potential double destroy of AssetManager
*  Revoke 'always' web handler status when not autoverifying

#### project frameworks/native/
*  Don't leak input events to dumpsys on user builds
*  Resize object capacity when shrinking Parcel

#### project packages/apps/Settings
*  Prevent accounts page directly opening in screen pinning mode

* * *
### Build 2020-04-19
* * *

#### project build/
*  Bump Security String to 2020-03-05

#### project frameworks/base/
*  Fixes NPE when preparing app data during init
*  Handles null outInfo in deleteSystemPackageLI
*  Fix security problem on PermissionMonitor#hasPermission
*  RESTRICT AUTOMERGE Make toasts non-clickable
*  DO NOT MERGE back porting for fixing sysui direct reply
*  DO NOT MERGE: Disable SpellChecker in secondary user's direct reply 

#### project frameworks/native/
*  Don't leak input events to dumpsys on user builds
*  Resize object capacity when shrinking Parcel

#### project packages/apps/Settings
*  Prevent accounts page directly opening in screen pinning mode


* * *
### Build 20200203
* * *

#### project build/
*  Bump Security String to 2020-01-05

#### project frameworks/base/
*  Prevent system uid component from running in an isolated app process
*  Only allow INSTALL_ALLOW_TEST from shell or root
*  DO NOT MERGE Validate wallpaper dimension while generating crop

#### project frameworks/native/
*  Sensor: use FlattenableUtils::align

#### project system/core/
*  FlattenableUtils::align memsets

#### project hardware/qcom/audio-caf/msm8916/
*  audio: free and assign NULL to global static device pointer

#### project hardware/qcom/audio-caf/msm8952/
*  audio: free and assign NULL to global static device pointer

#### project hardware/qcom/audio-caf/msm8960/
*  audio: free and assign NULL to global static device pointer

#### project hardware/qcom/audio-caf/msm8974/
*  audio: free and assign NULL to global static device pointer

#### project hardware/qcom/audio-caf/msm8994/
*  audio: free and assign NULL to global static device pointer

#### project hardware/qcom/audio-caf/msm8996/
*  audio: free and assign NULL to global static device pointer

#### project hardware/qcom/audio-caf/msm8998/
*  audio: free and assign NULL to global static device pointer

#### project android/
*  manifest: Updates for 2019-12 N ASB

#### project build/
*  Bump Security String to 2019-12-05

#### project frameworks/base/
*  Do not compute outside given range in TextLine

#### project external/libavc/
*  decoder: Move initialization of dbp_mgr entries to init_decoder()

#### project external/libnfc-nci/
*  Prevent uncleared memory leaking in rw_i93.c

#### project system/bt/
*  fix -Wdangling-gsl

#### project external/ImageMagick/
*  https://github.com/ImageMagick/ImageMagick/issues/1554

#### project external/libhevc/
*  Check change in CTB size when decoding multiple SPS with same id
*  decoder: Reset slice header at start of slice header decode

#### project packages/apps/Email/
*  AOSP/Email - bug fix: do not allow composing message with hidden private data attachments - Switch intent filtering to be blacklist based rather than whitelist based.
*  Deleted "<action android:name="android.intent.action.SEND_MULTIPLE" />" in "com.android.email.activity.ComposeActivityEmailExternal" activity of the AndroidManifest.xml as part of cleanup.
*  AOSP/Email - Secure UPDATE_WIDGET receiver with a new permission

#### project packages/apps/UnifiedEmail/
*  AOSP/UnifiedEmail - bug fix: do not allow composing message with hidden private data attachments - Switch intent filtering to be blacklist based rather than whitelist based.
*  AOSP/UnifiedEmail - Secure UPDATE_WIDGET receiver with a new permission

#### project system/bt/
*  JustWorks: Auto-accept only incoming temporary pairing.
*  SDP: Disconnect when there is a bad length
*  Use memcpy instead of casting to convert device_class to int
*  SDP: disconnect if sdp_copy_raw_data fails
*  DO NOT MERGE: btif: require pairing dialog for JustWorks SSP

#### project packages/apps/Jelly/
*  Jelly: Use try-with-resource

#### project external/bash/
*  bash: BASH_CMD is writable in restricted bash shells
*  bash: Popd controlled free
*  Bash-4.3 patch 48
*  Bash-4.3 patch 47
*  Bash-4.3 patch 46
*  Bash-4.3 patch 45
*  Bash-4.3 patch 44

#### project external/bash/
*  Bash-4.3 patch 43

#### project external/libselinux/
*  selinux: add selinux_status_getenforce to header


* * *
### Build 20190412
* * *

#### project build/
 ▪ 81ced9524 Bump Security String to 2019-04-05

#### project external/libnfc-nci/
*  Prevent OOB error in rw_i93_sm_update_ndef()
*  Prevent OOB error in rw_i93_sm_read_ndef()
*  Prevent OOB error in rw_i93_sm_detect_ndef()
*  Prevent OOB read in rw_i93_process_sys_info()
*  0ccd688 Prevent integer underflow in rw_t3t_act_handle_check_ndef_rsp()

#### project external/libmpeg2/
*  Add push-pop for Neon D8-D15 registers

#### project external/tremolo/
*  Add some error/overflow checks in codebook handling

#### project system/bt/
*  btm_proc_smp_cback: Don't access p_dev_rec if freed
*  process_l2cap_cmd: Fix OOB

#### project packages/apps/Jelly/
*  Jelly: Add support for multiple windows

[> Back to homepage](./)
