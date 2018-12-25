A3700-utils-marvell for ESPRESSObin
===================================

This branch of A3700-utils-marvell is for ESPRESSObin board and it is based on
[A3700-utils-marvell][A3700-utils-marvell] branch
[A3700\_utils-armada-17.10][A3700_utils-armada-17.10].

We only provide the build steps and some notes. You can find documentation at
the most recent release of [A3700-utils-marvell][A3700-utils-marvell].

******

Brief
=====

[A3700-utils-marvell][A3700-utils-marvell] is a collection of DDR topology
config file and other image flash tools for marvell armada SoCs. It must use
with [ATF][ATF] together.

This branch must use with [Marvell ATF-ch][Marvell ATF-ch] branch
[atf-v1.3-armada-17.10-ch-dev][atf-v1.3-armada-17.10-ch-dev], any other
combination has tested failed. To reduce workload, we did not fix the
compatibility between different branches of [ATF][ATF] and
[A3700-utils-marvell][A3700-utils-marvell].

Flash tools
-----------

This branch have tools to flash a UART image into ESPRESSObin board, the flash
step by step instruction can be find [here][Bootloader recovery via UART].

TODO
====

******

*Copyright (C) 2018, Hunan ChenHan Information Technology Co., Ltd. All rights reserved.*


[A3700-utils-marvell]: https://github.com/MarvellEmbeddedProcessors/A3700-utils-marvell "A3700-utils-marvell"
[A3700_utils-armada-17.10]: https://github.com/MarvellEmbeddedProcessors/A3700-utils-marvell/tree/A3700_utils-armada-17.10

[Marvell ATF-ch]: https://github.com/chenhaninformation/arm-trusted-firmware
[atf-v1.3-armada-17.10-ch-dev]: https://github.com/chenhaninformation/arm-trusted-firmware/tree/atf-v1.3-armada-17.10-ch-dev

[ATF]: ://github.com/ARM-software/arm-trusted-firmware "ATF ARM-Trusted-Firmware"

[Bootloader recovery via UART]: http://wiki.espressobin.net/tiki-index.php?page=Bootloader+recovery+via+UART#Linux

