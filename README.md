# HC-G80
# Huastlink 5G Home Router
# mt7981ba DDR3-512mb MT7531ae MT7976cn RTL8125bg

# installed software (samba nas etc.) - please see the list: config.buildinf
# including NVMe and USB storage support

# Adds support for cheaper USB modems
# Tested: T99W175 (original USB and USB-mod) T77W968 via modem manager
# FM350 RM520N (GLAA) via app-modem

# How to connect FM350: Add modem manually via app-modem (eth2 /dev/ttyUSB4 type fm350)
# How to connect Fibocom: Add modem via modem manager protocol
# How to connect RM520: App_modem automatically detected

# Supported modems according to developer (not tested):
| Huawei | MH5000-31 | Huawei | USB | ECM, NCM |
| Quectel | RG200U-CN (DONGLE version) | Unisoc | USB | ECM, MBIM, RNDIS, NCM |
| Quectel | RM500U-CN | Unisoc | USB | ECM, MBIM, RNDIS, NCM |
| Quectel | RM500U-EA | Unisoc | USB | ECM, MBIM, RNDIS, NCM |
| Quectel | RM500U-CNV | Unisoc | USB | ECM, MBIM, RNDIS, NCM |
| Quectel | RM500Q-CN | Qualcomm | USB | RMNET, ECM, MBIM, RNDIS, NCM |
| Quectel | RM500Q-AE | Qualcomm | USB | RMNET, ECM, MBIM, RNDIS, NCM |
| Quectel | RM500Q-GL | Qualcomm | USB | RMNET, ECM, MBIM, RNDIS, NCM |
| Quectel | RM502Q-AE | Qualcomm | USB | RMNET, ECM, MBIM, RNDIS, NCM |
| Quectel | RM502Q-GL | Qualcomm | USB | RMNET, ECM, MBIM, RNDIS, NCM |
| Quectel | RM505Q-AE | Qualcomm | USB | RMNET, ECM, MBIM, RNDIS, NCM |
| Quectel | RM520N-CN | Qualcomm | USB | RMNET, ECM, MBIM, RNDIS, NCM |
| Quectel | RM520N-GL | Qualcomm | USB | RMNET, ECM, MBIM, RNDIS, NCM |
| Fibocom | FM650-CN | Unisoc | USB | ECM, MBIM, RNDIS, NCM |
| Fibocom | FM350-GL | MediaTek | USB | RNDIS |
| Fibocom | FM150-AE-01, FM150-AE-11, FM150-AE-21, FM150-NA-01 | Qualcomm | USB | RMNET, ECM, MBIM, RNDIS, NCM |
| Fibocom | FM350-GL | MediaTek | PCIE | MBIM |
| MeiG Smart | SRM815 | Qualcomm | USB | RMNET, ECM, MBIM, RNDIS, NCM |
| MeiG Smart | SRM825 | Qualcomm | USB | RMNET, ECM, MBIM, RNDIS, NCM |
| MeiG Smart | SRM825N | Qualcomm | USB | RMNET, ECM, MBIM, RNDIS, NCM |
