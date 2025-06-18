# 114-Kyle
114-林耕澤 CSI dataset

##Feature Description

### Columns 0–47:
Amplitude values of the 48 subcarriers, with all PILOT, NULL, and LEGACY NULL subcarriers already removed. These represent the cleaned Channel State Information (CSI) amplitude features for each packet.

### AP1_Rssi, AP2_Rssi, AP3_Rssi, AP4_Rssi:
The received signal strength indicator (RSSI) values from four distinct Wi-Fi access points (APs), reflecting the signal environment at each reference point (RP).

### Label:
The reference point (RP) index, indicating the physical location label for each sample.

## Data Synchronization and Collection Method:

CSI and RSSI were collected separately (not simultaneously), simulating an environment with multiple APs and a dedicated CSI sniffer device.

The dataset emulates realistic deployment conditions, where the CSI sniffer captures channel information while RSSI is measured from broadcasted signals of multiple APs.
