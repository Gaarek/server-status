---
layout: post
title: Snapraid-status-error 2018-05-01 10:33:55
date: 2018-05-01 10:33:55
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
    2953       4       4       -    1927     248  88% d4
 --------------------------------------------------------------------------
   39443       5       7     0.0    5743    1345  81%


 12%|                       *       *      o       *                       
    |               o       *       *      *       *                       
    |               *       *       *      *       *       *       *      o
    |       *       *       *       *      *       *       *       *      *
    |       *       *       *       *      *       *       *       *      *
    |       *       *       *       *      *       *       *       *      *
    |       *       *       *       *      *       *       *       *      *
  6%|       *       *       *       *      *       *       *       *      *
    |       *       *       *       *      *       *       *       *      *
    |       *       *       *       *      *       *       *       *      *
    |       *       *       *       *      *       *       *       *      *
    |       *       *       *       *      *       *       *       *      *
    |       *       *       *       *      *       *       *       *      *
    |       *       *       *       *      *       *       *       *      *
  0%|*______*o__o__o*_o____o*o______*o_____*___o__o*o_____o*o_____o*___o__*
    63                    days ago of the last scrub/sync                 0

The oldest block was scrubbed 63 days ago, the median 28, the newest 0.

No sync is in progress.
The 3% of the array is not scrubbed.
You have 34838 files with zero sub-second timestamp.
Run the 'touch' command to set it to a not zero value.
No rehash is in progress or needed.
DANGER! In the array there are 1 errors!

They are from block 5235098 to 5235098, specifically at blocks: 5235098

To fix them use the command 'snapraid -e fix'.
The errors will disappear from the 'status' at the next 'scrub' command.
```
