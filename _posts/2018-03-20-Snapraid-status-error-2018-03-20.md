---
layout: post
title: Snapraid-status-error 2018-03-20 10:33:56
date: 2018-03-20 10:33:56
excerpt_separator: ""
categories: Snapraid-status-error Snapraid
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
    2915       2       2       -    1908     267  87% d4
 --------------------------------------------------------------------------
   39405       3       5     0.0    5724    1635  77%


 12%|                                                                     o
    |                                                               o     *
    |                              o     *      o      o     *      *     *
    |                              *     *      *      *     *      *     *
    |          o     o      o      *     *      *      *     *      *     *
    |          *     *      *      *     *      *      *     *      *     *
    |          *     *      *      *     *      *      *     *      *     *
  6%|          *     *      *      *     *      *      *     *      *     *
    |          *     *      *      *     *      *      *     *      *     *
    |          *     *      *      *     *      *      *     *      *     *
    |          *     *      *      *     *      *      *     *      *     *
    |          *     *      *      *     *      *      *     *      *     *
    |          *     *      *      *     *      *      *     *      *     *
    |          *     *      *      *     *      *      *     *      *     *
  0%|o__o__o__o*o__o_*o__o_o*___o_o*_o_o_*_o_o_o*oo___o*ooo__*o_o__o*o____*
    73                    days ago of the last scrub/sync                 0

The oldest block was scrubbed 73 days ago, the median 28, the newest 0.

No sync is in progress.
The 3% of the array is not scrubbed.
You have 34847 files with zero sub-second timestamp.
Run the 'touch' command to set it to a not zero value.
No rehash is in progress or needed.
DANGER! In the array there are 1 errors!

They are from block 7075695 to 7075695, specifically at blocks: 7075695

To fix them use the command 'snapraid -e fix'.
The errors will disappear from the 'status' at the next 'scrub' command.
```
