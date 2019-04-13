---
layout: post
title: Snapraid-status
date: 2019-04-13 10:33:56
excerpt_separator: ""
categories: Snapraid-status Snapraid
---
```
Self test...
Loading state from /home/public/HDD7/snapraid.content...
Using 401 MiB of memory for the FileSystem.
SnapRAID status report:

   Files Fragmented Excess  Wasted  Used    Free  Use Name
            Files  Fragments  GB      GB      GB
    1652       0       0       -     205     781  20% d1
   22130       1       3       -    1770     168  91% d2
   12706       0       0       -    1825     141  92% d3
    3098      13      19       -    2010     181  91% d4
 --------------------------------------------------------------------------
   39586      14      22     0.0    5811    1272  82%


 10%|       o       o       o       *      *       *       o       *      *
    |       *       *       *       *      *       *       *       *      *
    |       *       *       *       *      *       *       *       *      *
    |*      *       *       *       *      *       *       *       *      *
    |*      *       *       *       *      *       *       *       *      *
    |*      *       *       *       *      *       *       *       *      *
    |*      *       *       *       *      *       *       *       *      *
  5%|*      *       *       *       *      *       *       *       *      *
    |*      *       *       *       *      *       *       *       *      *
    |*      *       *       *       *      *       *       *       *      *
    |*      *       *       *       *      *       *       *       *      *
    |*      *       *       *       *      *       *       *       *      *
    |*      *       *       *       *      *       *       *       *      *
    |*      *       *       *       *      *       *       *       *      *
  0%|*___o__*o__oooo*___oo_o*___oo_o*__o___*o___o__*_o_oo__*___oo__*______*
    67                    days ago of the last scrub/sync                 4

The oldest block was scrubbed 67 days ago, the median 32, the newest 4.

No sync is in progress.
The 4% of the array is not scrubbed.
You have 34836 files with zero sub-second timestamp.
Run the 'touch' command to set it to a not zero value.
No rehash is in progress or needed.
No error detected.
```
