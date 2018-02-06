---
layout: post
title: Snapraid-status-error 2018-02-06 10:33:54
date: 2018-02-06 10:33:54
excerpt_separator: ""
categories: Snapraid-status-error Snapraid
---
```
Self test...
Loading state from /home/public/HDD7/snapraid.content...
Using 391 MiB of memory for the FileSystem.
SnapRAID status report:

   Files Fragmented Excess  Wasted  Used    Free  Use Name
            Files  Fragments  GB      GB      GB
    1652       0       0       -     205    1079  15% d1
   22131       1       3       -    1785     153  92% d2
   12706       0       0       -    1825     141  92% d3
    2860       1       1       -    1870     321  85% d4
 --------------------------------------------------------------------------
   39349       2       4     0.0    5686    1696  77%


 10%|                                                                     o
    |         o                                                           *
    |         o *     *      *     o      *     o      o     o      o     *
    |         o *     *      *     *      *     *      *     *      *     *
    |         o *     *      *     *      *     *      *     *      *     *
    |         o *     *      *     *      *     *      *     *      *     *
    |         o *     *      *     *      *     *      *     *      *     *
  5%|    *    o *     *      *     *      *     *      *     *      *     *
    |    *    o *     *      *     *      *     *      *     *      *     *
    |    *    o *     *      *     *      *     *      *     *      *     *
    |    *    o *     *      *     *      *     *      *     *      *     *
    |    *    o *     *      *     *      *     *      *     *      *     *
    |    *    o *     *      *     *      *     *      *     *      *     *
    |    *    o *     *      *     *      *     *      *     *      *     *
  0%|o___*o___o_*oooo_*_ooo__*___o_*__o__o*__oo_*o__o_o*o__o_*o__o_o*___o_*
    75                    days ago of the last scrub/sync                 0

The oldest block was scrubbed 75 days ago, the median 35, the newest 0.

No sync is in progress.
The 11% of the array is not scrubbed.
You have 34846 files with zero sub-second timestamp.
Run the 'touch' command to set it to a not zero value.
No rehash is in progress or needed.
DANGER! In the array there are 1 errors!

They are from block 108268 to 108268, specifically at blocks: 108268

To fix them use the command 'snapraid -e fix'.
The errors will disappear from the 'status' at the next 'scrub' command.
```
