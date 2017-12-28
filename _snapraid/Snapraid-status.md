---
layout: post
title: Snapraid-status
date: 2017-12-28 10:33:53
excerpt_separator: ""
categories: Snapraid-status Snapraid
---
```
Self test...
Loading state from /home/public/HDD7/snapraid.content...
Using 389 MiB of memory for the FileSystem.
SnapRAID status report:

   Files Fragmented Excess  Wasted  Used    Free  Use Name
            Files  Fragments  GB      GB      GB
    1652       0       0       -     205    1076  16% d1
   22130       1       3       -    1783     155  92% d2
   12706       0       0       -    1825     141  92% d3
    2838       1       1       -    1850     341  84% d4
 --------------------------------------------------------------------------
   39326       2       4     0.0    5664    1714  76%


  8%|                                               o        *      *     o
    |      *       *      *      *      *      o    o *      *      *     *
    |      *       *      *      *      *      *    o *      *      *     *
    |      *       *      *      *      *      *    o *      *      *     *
    |      *       *      *      *      *      *    o *      *      *     *
    |      *       *      *      *      *o     *    o *      *      *     *
    |      *       *      *      *      *o     *    o *      *      *     *
  4%|      *       *      *      *      *o     *    o *      *      *     *
    |      *       *      *      *      *o     *    o *      *      *     *
    |      *       *      *      *      *o     *    o *      *      *     *
    |      *       *      *      *      *o     *    o *      *      *     *
    |      *       *      *      *      *o     *    o *      *      *     *
    |*     *       *      *      *      *o     *    o *      *      *     *
    |*     *       *      *      *      *oo    *    o *      *      *     *
  0%|*_____*_______*______*______*______*oo____*____o_*oooo__*oooo__*___o_*
    72                    days ago of the last scrub/sync                 2

The oldest block was scrubbed 72 days ago, the median 30, the newest 2.

No sync is in progress.
The 17% of the array is not scrubbed.
You have 34845 files with zero sub-second timestamp.
Run the 'touch' command to set it to a not zero value.
No rehash is in progress or needed.
No error detected.
```
