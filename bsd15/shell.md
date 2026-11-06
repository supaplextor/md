```
root@bsd-1:~ # file -sk /dev/nvme*
/dev/nvme0:    ERROR: cannot read `/dev/nvme0' (Operation not supported by device)
/dev/nvme0n1:  DOS/MBR boot sector, extended partition table (last)\012-  DOS/MBR boot sector\012-  GPT partition table, version 1.0, GUID: ac8d184c-09b3-1841-99d8-af351c6d3fcf, disk size: 1953525168 sectors\012-  of 512 bytes\012- data
/dev/nvme0ns1: symbolic link to nvme0n1
/dev/nvme1:    ERROR: cannot read `/dev/nvme1' (Operation not supported by device)
/dev/nvme1n1:  DOS/MBR boot sector; partition 1 : ID=0xee, start-CHS (0x0,0,2\012- ), end-CHS (0x3ff,255,63\012- ), startsector 1, 1000215215 sectors\012- , extended partition table (last)\012-  DOS/MBR boot sector\012-  GPT partition table, version 1.0, GUID: 3ad4c2ac-5bfa-9e40-973d-ff57bad1655d, disk size: 1000215216 sectors\012-  of 512 bytes\012- data
/dev/nvme1ns1: symbolic link to nvme1n1
```
