---
layout: post
title: Snapraid-status
date: 2018-03-08 10:33:58
excerpt_separator: ""
categories: Snapraid-status Snapraid
---
```
Self test...
Loading state from /home/public/HDD7/snapraid.content...
Using 393 MiB of memory for the FileSystem.
SnapRAID status report:

   Files Fragmented Excess  Wasted  Used    Free  Use Name
            Files  Fragments  GB      GB      GB
    1652       0       0       -     205    1079  15% d1
   22132       1       3       -    1785     153  92% d2
   12706       0       0       -    1825     141  92% d3
    2896       2       2       -    1892     299  86% d4
 --------------------------------------------------------------------------
   39386       3       5     0.0    5708    1673  77%


 10%|                                         o      *      o      o      o
    |                                         *      *      *      *      *
    |             o      o      o      o      *      *      *      *      *
    |      o      *      *      *      *      *      *      *      *      *
    |*     *      *      *      *      *      *      *      *      *      *
    |*     *      *      *      *      *      *      *      *      *      *
    |*     *      *      *      *      *      *      *      *      *      *
  5%|*     *      *      *      *      *      *      *      *      *      *
    |*     *      *      *      *      *      *      *      *      *      *
    |*     *      *      *      *      *      *      *      *      *      *
    |*     *      *      *      *      *      *      *      *      *      *
    |*     *      *      *      *      *      *      *      *      *      *
    |*     *      *      *      *      *      *      *      *      *      *
    |*     *      *      *      *      *      *      *      *      *      *
  0%|*__o__*___oo_*o__o__*oo__o_*o___o_*o___o_*o_o_o_*_o__o_*ooo___*oooo__*
    72                    days ago of the last scrub/sync                 1

The oldest block was scrubbed 72 days ago, the median 30, the newest 1.

WARNING! The array is NOT fully synced.
You have a sync in progress at 99%.
The 3% of the array is not scrubbed.
You have 34847 files with zero sub-second timestamp.
Run the 'touch' command to set it to a not zero value.
No rehash is in progress or needed.
No error detected.
```
