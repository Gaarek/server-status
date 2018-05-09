---
layout: post
title: Snapraid-status-error 2018-05-09 10:34:10
date: 2018-05-09 10:34:10
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
    2959       4       4       -    1918     257  88% d4
 --------------------------------------------------------------------------
   39449       5       7     0.0    5734    1354  80%


 12%|               *       *       *      o                               
    |       o       *       *       *      *                               
    |       *       *       *       *      *       *       *              o
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
  0%|*__o___*oo____o**o_____*o_____o*___o__*o_____o*o_____o*___o__o*_oo___*
    64                    days ago of the last scrub/sync                 1

The oldest block was scrubbed 64 days ago, the median 29, the newest 1.

No sync is in progress.
The 3% of the array is not scrubbed.
You have 34838 files with zero sub-second timestamp.
Run the 'touch' command to set it to a not zero value.
No rehash is in progress or needed.
DANGER! In the array there are 1 errors!

They are from block 5877125 to 5877125, specifically at blocks: 5877125

To fix them use the command 'snapraid -e fix'.
The errors will disappear from the 'status' at the next 'scrub' command.
```
