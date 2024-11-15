# cu_stats_XXX.txt Throughput Parser
online calculate: https://dustinchen26.github.io/parse_cu

## Example
● Please paste the whole "cu_stats_XXX.txt" content below, and it will parse the non-zero Throughput value.

```
【Input】
#############################################################################################################################
                  UDP TX STATISTICS
#############################################################################################################################
DL-11  Throughput [UDP-DL-Tx 11  (0.02 Mbps)][ CUMM-TX-FAIL: 0]
DL-12  Throughput [UDP-DL-Tx 12  (0.00 Mbps)][ CUMM-TX-FAIL: 0]
UL-13  Throughput [UDP-UL-Tx (176.19 Mbps)][ CUMM-TX-FAIL: 0]
UL-14  Throughput [UDP-UL-Tx (0.00 Mbps)][ CUMM-TX-FAIL: 0]


【Output】

DL-11 Throughput [UDP-DL-Tx 11 (0.02 Mbps)][ CUMM-TX-FAIL: 0]
UL-13 Throughput [UDP-UL-Tx (176.19 Mbps)][ CUMM-TX-FAIL: 0]
```