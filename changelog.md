---
layout: default
---

# Changelog


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
