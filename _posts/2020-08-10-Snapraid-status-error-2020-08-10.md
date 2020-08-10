---
layout: post
title: Snapraid-status-error 2020-08-10 10:33:45
date: 2020-08-10 10:33:45
excerpt_separator: ""
categories: Snapraid-status-error Snapraid
---
```
Self test...
Loading state from /home/public/HDD7/snapraid.content...
Using 394 MiB of memory for the FileSystem.
SnapRAID status report:

   Files Fragmented Excess  Wasted  Used    Free  Use Name
            Files  Fragments  GB      GB      GB
    1652       1       1       -     205     750  21% d1
   22136       1       3       -    1776     162  91% d2
   12717       1       1       -    1825     140  92% d3
    2944      11      22       -    1887     304  86% d4
 --------------------------------------------------------------------------
   39449      14      27     0.0    5695    1358  80%


 10%|             *      *      *      *      *      *      *      *      *
    |             *      *      *      *      *      *      *      *      *
    |             *      *      *      *      *      *      *      *      *
    |             *      *      *      *      *      *      *      *      *
    |             *      *      *      *      *      *      *      *      *
    |             *      *      *      *      *      *      *      *      *
    |             *      *      *      *      *      *      *      *      *
  5%|             *      *      *      *      *      *      *      *      *
    |      *      *      *      *      *      *      *      *      *      *
    |      *      *      *      *      *      *      *      *      *      *
    |      *      *      *      *      *      *      *      *      *      *
    |      *      *      *      *      *      *      *      *      *      *
    |      *      *      *      *      *      *      *      *      *      *
    |      *      *      *      *      *      *      *      *      *      *
  0%|*_____*______*______*______*______*______*______*______*______*______*
    76                    days ago of the last scrub/sync                 6

The oldest block was scrubbed 76 days ago, the median 34, the newest 6.

No sync is in progress.
The full array was scrubbed at least one time.
You have 34853 files with zero sub-second timestamp.
Run the 'touch' command to set it to a not zero value.
No rehash is in progress or needed.
DANGER! In the array there are 187 errors!

They are from block 6415399 to 6735314, specifically at blocks: 6415399 6415911 6434245 6452236 6452268 6452684 6460620 6467148 6467180 6467212 6468332 6468364 6468780 6468812 6468876 6469612 6470572 6471660 6471724 6472364 6472972 6474188 6475628 6477996 6479180 6480908 6481356 6481612 6481676 6481708 6481740 6499148 6499468 6499660 6501420 6503020 6503116 6503852 6504524 6505452 6505964 6508556 6508620 6508940 6510668 6510732 6510860 6510892 6510924 6530124 6530156 6530988 6531020 6543308 6544300 6544332 6544684 6544972 6571212 6572108 6572524 6572716 6572748 6620457 6621193 6621801 6628789 6636181 6636213 6636661 6636757 6636885 6637205 6637493 6637813 6637845 6638101 6638677 6638709 6639349 6642613 6644213 6645045 6645141 6646549 6647061 6648533 6651381 6652405 6654389 6655637 6657109 6659566 6660046 6660270 6661038 6661294 6661838 6661902 6662094 6662190 and 86 more...

To fix them use the command 'snapraid -e fix'.
The errors will disappear from the 'status' at the next 'scrub' command.
```
