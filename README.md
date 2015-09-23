# mikrotik-ms-telemetry-blocker
A set of mikrotik rules to block MS telemetry spy activity


```
/ip firewall address-list add list=MStelemetry address=191.232.139.254
/ip firewall address-list add list=MStelemetry address=65.55.252.92
/ip firewall address-list add list=MStelemetry address=65.55.252.63
/ip firewall address-list add list=MStelemetry address=65.55.252.93
/ip firewall address-list add list=MStelemetry address=65.55.252.43
/ip firewall address-list add list=MStelemetry address=65.52.108.29
/ip firewall address-list add list=MStelemetry address=194.44.4.200
/ip firewall address-list add list=MStelemetry address=194.44.4.208
/ip firewall address-list add list=MStelemetry address=157.56.91.77
/ip firewall address-list add list=MStelemetry address=65.52.100.7
/ip firewall address-list add list=MStelemetry address=65.52.100.91
/ip firewall address-list add list=MStelemetry address=65.52.100.93
/ip firewall address-list add list=MStelemetry address=65.52.100.92
/ip firewall address-list add list=MStelemetry address=65.52.100.94
/ip firewall address-list add list=MStelemetry address=65.52.100.9
/ip firewall address-list add list=MStelemetry address=65.52.100.11
/ip firewall address-list add list=MStelemetry address=168.63.108.233
/ip firewall address-list add list=MStelemetry address=157.56.74.250
/ip firewall address-list add list=MStelemetry address=111.221.29.177
/ip firewall address-list add list=MStelemetry address=64.4.54.32
/ip firewall address-list add list=MStelemetry address=207.68.166.254
/ip firewall address-list add list=MStelemetry address=207.46.223.94
/ip firewall address-list add list=MStelemetry address=65.55.252.71
/ip firewall address-list add list=MStelemetry address=64.4.54.22
/ip firewall address-list add list=MStelemetry address=131.107.113.238
/ip firewall address-list add list=MStelemetry address=23.99.10.11
/ip firewall address-list add list=MStelemetry address=68.232.34.200
/ip firewall address-list add list=MStelemetry address=204.79.197.200
/ip firewall address-list add list=MStelemetry address=64.4.54.22
/ip firewall address-list add list=MStelemetry address=157.56.77.139
/ip firewall address-list add list=MStelemetry address=134.170.58.121
/ip firewall address-list add list=MStelemetry address=134.170.58.123
/ip firewall address-list add list=MStelemetry address=134.170.53.29
/ip firewall address-list add list=MStelemetry address=66.119.144.190
/ip firewall address-list add list=MStelemetry address=134.170.58.189
/ip firewall address-list add list=MStelemetry address=134.170.58.118
/ip firewall address-list add list=MStelemetry address=134.170.53.30
/ip firewall address-list add list=MStelemetry address=134.170.51.190
/ip firewall address-list add list=MStelemetry address=157.56.121.89
/ip firewall address-list add list=MStelemetry address=131.107.113.238
/ip firewall address-list add list=MStelemetry address=134.170.115.60
/ip firewall address-list add list=MStelemetry address=204.79.197.200
/ip firewall address-list add list=MStelemetry address=104.82.22.249
/ip firewall address-list add list=MStelemetry address=134.170.185.70
/ip firewall address-list add list=MStelemetry address=64.4.6.100
/ip firewall address-list add list=MStelemetry address=65.55.39.10
/ip firewall address-list add list=MStelemetry address=157.55.129.21
/ip firewall address-list add list=MStelemetry address=207.46.194.25
/ip firewall address-list add list=MStelemetry address=23.102.21.4
/ip firewall address-list add list=MStelemetry address=173.194.113.220
/ip firewall address-list add list=MStelemetry address=173.194.113.219
/ip firewall address-list add list=MStelemetry address=216.58.209.166
/ip firewall address-list add list=MStelemetry address=157.56.91.82
/ip firewall address-list add list=MStelemetry address=157.56.23.91
/ip firewall address-list add list=MStelemetry address=104.82.14.146
/ip firewall address-list add list=MStelemetry address=207.123.56.252
/ip firewall address-list add list=MStelemetry address=185.13.160.61
/ip firewall address-list add list=MStelemetry address=8.254.209.254
/ip firewall address-list add list=MStelemetry address=198.78.208.254
/ip firewall address-list add list=MStelemetry address=185.13.160.61
/ip firewall address-list add list=MStelemetry address=185.13.160.61
/ip firewall address-list add list=MStelemetry address=8.254.209.254
/ip firewall address-list add list=MStelemetry address=207.123.56.252
/ip firewall address-list add list=MStelemetry address=68.232.34.200
/ip firewall address-list add list=MStelemetry address=65.55.252.63
/ip firewall address-list add list=MStelemetry address=65.52.100.91
/ip firewall address-list add list=MStelemetry address=65.52.100.7
/ip firewall address-list add list=MStelemetry address=68.232.34.200
/ip firewall address-list add list=MStelemetry address=64.4.54.32
/ip firewall address-list add list=MStelemetry address=204.79.197.200
/ip firewall address-list add list=MStelemetry address=104.82.22.249
/ip firewall address-list add list=MStelemetry address=207.46.101.29
/ip firewall address-list add list=MStelemetry address=134.170.115.60
/ip firewall address-list add list=MStelemetry address=65.55.108.23
/ip firewall address-list add list=MStelemetry address=23.218.212.69
/ip firewall filter add chain=forward dst-address-list=MStelemetry action=reject comment="Reject MS Telemetry" 

```
