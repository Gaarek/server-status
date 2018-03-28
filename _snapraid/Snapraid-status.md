---
layout: post
title: Snapraid-status
date: 2018-03-28 10:33:57
excerpt_separator: ""
categories: Snapraid-status Snapraid
---
```
Self test...
Loading state from /home/public/HDD7/snapraid.content...
Using 394 MiB of memory for the FileSystem.
SnapRAID status report:

   Files Fragmented Excess  Wasted  Used    Free  Use Name
            Files  Fragments  GB      GB      GB
    1652       0       0       -     205    1072  16% d1
   22132       1       3       -    1785     153  92% d2
   12706       0       0       -    1825     141  92% d3
    2918       2       2       -    1909     266  87% d4
 --------------------------------------------------------------------------
   39408       3       5     0.0    5725    1634  77%


 12%|                                                              *      *
    |                                                      o       *      *
    |               *       *       o      o       *       *       *      *
    |               *       *       *      *       *       *       *      *
    |       o       *       *       *      *       *       *       *      *
    |       *       *       *       *      *       *       *       *      *
    |       *       *       *       *      *       *       *       *      *
  6%|       *       *       *       *      *       *       *       *      *
    |o      *       *       *       *      *       *       *       *      *
    |*      *       *       *       *      *       *       *       *      *
    |*      *       *       *       *      *       *       *       *      *
    |*      *       *       *       *      *       *       *       *      *
    |*      *       *       *       *      *       *       *       *      *
    |*      *       *       *       *      *       *       *       *      *
  0%|*___o__*o___o_o*o_o_o__*o___o_o*oo____*oooo___*o__o__o*o_____o*o_____*
    64                    days ago of the last scrub/sync                 1

The oldest block was scrubbed 64 days ago, the median 29, the newest 1.

No sync is in progress.
The 3% of the array is not scrubbed.
You have 34838 files with zero sub-second timestamp.
Run the 'touch' command to set it to a not zero value.
No rehash is in progress or needed.
No error detected.
```
