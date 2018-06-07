---
layout: post
title: Snapraid-status
date: 2018-06-07 10:33:51
excerpt_separator: ""
categories: Snapraid-status Snapraid
---
```
Self test...
Loading state from /home/public/HDD7/snapraid.content...
Using 396 MiB of memory for the FileSystem.
SnapRAID status report:

   Files Fragmented Excess  Wasted  Used    Free  Use Name
            Files  Fragments  GB      GB      GB
    1652       0       0       -     205     801  20% d1
   22132       1       3       -    1785     153  92% d2
   12706       0       0       -    1825     141  92% d3
    2978       7       7       -    1931     260  88% d4
 --------------------------------------------------------------------------
   39468       8      10     0.0    5747    1357  80%


 12%|       o                                                              
    |       *                                                              
    |       *       *       *                      *       *       *      o
    |       *       *       *       *      o       *       *       *      *
    |       *       *       *       *      *       *       *       *      *
    |*      *       *       *       *      *       *       *       *      *
    |*      *       *       *       *      *       *       *       *      *
  6%|*      *       *       *       *      *       *       *       *      *
    |*      *       *       *       *      *       *       *       *      *
    |*      *       *       *       *      *       *       *       *      *
    |*      *       *       *       *      *       *       *       *      *
    |*      *       *       *       *      *       *       *       *      *
    |*      *       *       *       *      *       *       *       *      *
    |*      *       *       *       *      * o     *       *       *      *
  0%|*___o__*o_____o*o_____o*___o__o*_oo___*_ooo__o*__oo__o*__oo__o*_____o*
    65                    days ago of the last scrub/sync                 2

The oldest block was scrubbed 65 days ago, the median 30, the newest 2.

No sync is in progress.
The 3% of the array is not scrubbed.
You have 34838 files with zero sub-second timestamp.
Run the 'touch' command to set it to a not zero value.
No rehash is in progress or needed.
No error detected.
```
