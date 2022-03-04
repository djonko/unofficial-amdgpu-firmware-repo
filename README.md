## unofficial-amdgpu-firmware-repo
This repository is an insurance policy in case AMD is late in uploading the latest firmware to the [kernel/git/firmware/linux-firmware.git](https://git.kernel.org/pub/scm/linux/kernel/git/firmware/linux-firmware.git/tree/).  
Although the firmware is collected from ROCm (rock-dkms) and [Radeon Software for Linux](http://repo.radeon.com/amdgpu/) (amdgpu-dkms-firmware) other than [kernel/git/firmware/linux-firmware.git](https://git.kernel.org/pub/scm/linux/kernel/git/firmware/linux-firmware.git/tree/), I cannot guarantee that it works properly.  

## Archive this repository
Alex Deucher (AMD, Software developer) is currently providing solid support in firmware for AMDGPUs.  
GC 10.3.7, DCN 3.1.6, PSP 13.0.8, SDMA 5.2.7, their firmware was released earlier than in [linux-firmware.git](https://git.kernel.org/pub/scm/linux/kernel/git/firmware/linux-firmware.git) the Radeon Software for Linux package (repo.amdgpu.com),  
So, I think that it is best to use the official repository ([linux-firmware.git](https://git.kernel.org/pub/scm/linux/kernel/git/firmware/linux-firmware.git)). There is not now need to use this repository.  
This repository will no longer be updated and will be archived.  
If you have been using this repository, I recommend replacing it with [linux-firmware.git](https://git.kernel.org/pub/scm/linux/kernel/git/firmware/linux-firmware.git).

## LICENSE

Copyright (C) 2020  Advanced Micro Devices, Inc. All rights reserved.

REDISTRIBUTION: Permission is hereby granted, free of any license fees,
to any person obtaining a copy of this microcode (the "Software"), to
install, reproduce, copy and distribute copies, in binary form only, of
the Software and to permit persons to whom the Software is provided to
do the same, provided that the following conditions are met:

No reverse engineering, decompilation, or disassembly of this Software
is permitted.

Redistributions must reproduce the above copyright notice, this
permission notice, and the following disclaimers and notices in the
Software documentation and/or other materials provided with the
Software.

DISCLAIMER: THE USE OF THE SOFTWARE IS AT YOUR SOLE RISK.  THE SOFTWARE
IS PROVIDED "AS IS" AND WITHOUT WARRANTY OF ANY KIND AND COPYRIGHT
HOLDER AND ITS LICENSORS EXPRESSLY DISCLAIM ALL WARRANTIES, EXPRESS AND
IMPLIED, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NON-INFRINGEMENT.
COPYRIGHT HOLDER AND ITS LICENSORS DO NOT WARRANT THAT THE SOFTWARE WILL
MEET YOUR REQUIREMENTS, OR THAT THE OPERATION OF THE SOFTWARE WILL BE
UNINTERRUPTED OR ERROR-FREE.  THE ENTIRE RISK ASSOCIATED WITH THE USE OF
THE SOFTWARE IS ASSUMED BY YOU.  FURTHERMORE, COPYRIGHT HOLDER AND ITS
LICENSORS DO NOT WARRANT OR MAKE ANY REPRESENTATIONS REGARDING THE USE
OR THE RESULTS OF THE USE OF THE SOFTWARE IN TERMS OF ITS CORRECTNESS,
ACCURACY, RELIABILITY, CURRENTNESS, OR OTHERWISE.

DISCLAIMER: UNDER NO CIRCUMSTANCES INCLUDING NEGLIGENCE, SHALL COPYRIGHT
HOLDER AND ITS LICENSORS OR ITS DIRECTORS, OFFICERS, EMPLOYEES OR AGENTS
("AUTHORIZED REPRESENTATIVES") BE LIABLE FOR ANY INCIDENTAL, INDIRECT,
SPECIAL OR CONSEQUENTIAL DAMAGES (INCLUDING DAMAGES FOR LOSS OF BUSINESS
PROFITS, BUSINESS INTERRUPTION, LOSS OF BUSINESS INFORMATION, AND THE
LIKE) ARISING OUT OF THE USE, MISUSE OR INABILITY TO USE THE SOFTWARE,
BREACH OR DEFAULT, INCLUDING THOSE ARISING FROM INFRINGEMENT OR ALLEGED
INFRINGEMENT OF ANY PATENT, TRADEMARK, COPYRIGHT OR OTHER INTELLECTUAL
PROPERTY RIGHT EVEN IF COPYRIGHT HOLDER AND ITS AUTHORIZED
REPRESENTATIVES HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGES.  IN
NO EVENT SHALL COPYRIGHT HOLDER OR ITS AUTHORIZED REPRESENTATIVES TOTAL
LIABILITY FOR ALL DAMAGES, LOSSES, AND CAUSES OF ACTION (WHETHER IN
CONTRACT, TORT (INCLUDING NEGLIGENCE) OR OTHERWISE) EXCEED THE AMOUNT OF
US$10.

Notice:  The Software is subject to United States export laws and
regulations.  You agree to comply with all domestic and international
export laws and regulations that apply to the Software, including but
not limited to the Export Administration Regulations administered by the
U.S. Department of Commerce and International Traffic in Arm Regulations
administered by the U.S. Department of State.  These laws include
restrictions on destinations, end users and end use.
