# RMX2117 ReSukiSU 4.2.0-rc3 + SUSFS

Build recipe for Realme RMX2117 (MT6853), Android 12.

Based on https://github.com/sanba0519/OPPO-Realme_kernel_4.14_MT6853 and its build workflow.
Root source: official ReSukiSU v4.2.0-rc3, commit 239e1e8871b8fcd51a6e5b3002e0ba522fdd99fb.
SUSFS and root hooks are pinned to the revisions in the workflow.

Run the workflow manually from Actions. Defaults: ReSukiSU, BBR, SUSFS;
DroidSpace and NoMount disabled. The job checks UAPI 4 and uploads the kernel,
kernel configuration and source/hash evidence. This repository contains no device
backups, keyboxes or private device data.

The resulting kernel needs device-specific validation before installation.
Upstream sources and patches retain their original authorship and license terms.
