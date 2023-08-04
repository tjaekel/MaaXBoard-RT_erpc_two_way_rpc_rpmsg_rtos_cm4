# MaaXBoard-RT_erpc_two_way_rpc_rpmsg_rtos_cm4
 DualCore RCP demo, from SDK, bi-directional RPC with FreeRTOS

## Two Projects
Project consists of two projects: CM7 (master) and CM4 (slave).
Both appear in IDE as two projects, but the CM7 project has reference
to CM4 project.
It should build also CM4, if not: generate both projects.

You ahve to launch the CM7 (as master), which should flash also CM4, start
both.
CM4 as sub-project does not work.

It is from the SDK examples and works.
It demonstrates how to use a bi-directional RPC on both cores (with FreeRTOS).

