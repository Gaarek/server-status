---
layout: post
title: Snapraid-status-error 2018-05-31 10:33:58
date: 2018-05-31 10:33:58
excerpt_separator: ""
categories: Snapraid-status-error Snapraid
---
```
Self test...
Loading state from /home/public/HDD7/snapraid.content...
Using 395 MiB of memory for the FileSystem.
SnapRAID status report:

   Files Fragmented Excess  Wasted  Used    Free  Use Name
            Files  Fragments  GB      GB      GB
    1652       0       0       -     205     801  20% d1
   22132       1       3       -    1785     153  92% d2
   12706       0       0       -    1825     141  92% d3
    2975       6       6       -    1928     263  87% d4
 --------------------------------------------------------------------------
   39465       7       9     0.0    5744    1360  80%


 12%|             o      o                                                 
    |             *      *                                                 
    |             *      *      o      o                    o      o      o
    |             *      *      *      *      o      o      *      *      *
    |             *      *      *      *      *      *      *      *      *
    |             *      *      *      *      *      *      *      *      *
    |             *      *      *      *      *      *      *      *      *
  6%|             *      *      *      *      *      *      *      *      *
    |      *      *      *      *      *      *      *      *      *      *
    |      *      *      *      *      *      *      *      *      *      *
    |      *      *      *      *      *      *      *      *      *      *
    |      *      *      *      *      *      *      *      *      *      *
    |      *      *      *      *      *      *      *      *      *      *
    |      *      *      *      *      *      *      * o    *      *      *
  0%|*_____*_o____*___o__*o_____*o_____*___o__*_ooo__*_ooo__*__oo__*__oo__*
    72                    days ago of the last scrub/sync                 2

The oldest block was scrubbed 72 days ago, the median 30, the newest 2.

No sync is in progress.
The 3% of the array is not scrubbed.
You have 34838 files with zero sub-second timestamp.
Run the 'touch' command to set it to a not zero value.
No rehash is in progress or needed.
DANGER! In the array there are 1 errors!

They are from block 2118666 to 2118666, specifically at blocks: 2118666

To fix them use the command 'snapraid -e fix'.
The errors will disappear from the 'status' at the next 'scrub' command.
```
