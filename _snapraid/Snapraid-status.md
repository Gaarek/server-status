---
layout: post
title: Snapraid-status
date: 2017-12-13 10:33:53
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
    1652       0       0       -     205    1095  15% d1
   22130       1       3       -    1783     155  92% d2
   12706       0       0       -    1825     141  92% d3
    2828       1       1       -    1843     349  84% d4
 --------------------------------------------------------------------------
   39316       2       4     0.0    5657    1741  76%


  8%|                                                              o      *
    |                           *     *     *     *     *          o*     *
    |o                          *     *     *     *     *     *    o*     *
    |o                    *     *     *     *     *     *     *    o*     *
    |o                    *     *     *     *     *     *     *    o*     *
    |o                    *     *     *     *     *     * o   *    o*     *
    |o                    *     *     *     *     *     * o   *    o*     *
  4%|o                    *     *     *     *     *     * o   *    o*     *
    |o                    *     *     *     *     *     * o   *    o*     *
    |o              *     *     *     *     *     *     * o   *    o*     *
    |o              *     *     *     *     *     *     * o   *    o*     *
    |o              *     *     *     *     *     *     * o   *    o*     *
    |o              *     *     *     *     *     *     * o   *    o*     *
    |o        *     *     *     *     *     *     *     * oo  *    o*     *
  0%|oo______**___o_*_____*_____*_____*_____*_____*_____*_oo__*o___o*_ooo_*
    81                    days ago of the last scrub/sync                 1

The oldest block was scrubbed 81 days ago, the median 29, the newest 1.

No sync is in progress.
The 24% of the array is not scrubbed.
You have 34845 files with zero sub-second timestamp.
Run the 'touch' command to set it to a not zero value.
No rehash is in progress or needed.
No error detected.
```
