---
layout: post
title: Snapraid-status-error 2020-02-11 10:33:43
date: 2020-02-11 10:33:43
excerpt_separator: ""
categories: Snapraid-status-error Snapraid
---
```
Self test...
Loading state from /home/public/HDD7/snapraid.content...
Using 393 MiB of memory for the FileSystem.
SnapRAID status report:

   Files Fragmented Excess  Wasted  Used    Free  Use Name
            Files  Fragments  GB      GB      GB
    1652       1       1       -     205     752  21% d1
   22136       1       3       -    1776     162  91% d2
   12717       1       1       -    1825     140  92% d3
    2928       6       9       -    1873     319  85% d4
 --------------------------------------------------------------------------
   39433       9      14     0.0    5681    1374  80%


 10%|       *       *       *       *      *       *       *       *      *
    |       *       *       *       *      *       *       *       *      *
    |       *       *       *       *      *       *       *       *      *
    |       *       *       *       *      *       *       *       *      *
    |       *       *       *       *      *       *       *       *      *
    |       *       *       *       *      *       *       *       *      *
    |       *       *       *       *      *       *       *       *      *
  5%|       *       *       *       *      *       *       *       *      *
    |*      *       *       *       *      *       *       *       *      *
    |*      *       *       *       *      *       *       *       *      *
    |*      *       *       *       *      *       *       *       *      *
    |*      *       *       *       *      *       *       *       *      *
    |*      *       *       *       *      *       *       *       *      *
    |*      *       *       *       *      *       *       *       *      *
  0%|*______*_______*_______*_______*______*____o__*_______*_______*o_____*
    63                    days ago of the last scrub/sync                 0

The oldest block was scrubbed 63 days ago, the median 28, the newest 0.

No sync is in progress.
The 1% of the array is not scrubbed.
You have 34853 files with zero sub-second timestamp.
Run the 'touch' command to set it to a not zero value.
No rehash is in progress or needed.
DANGER! In the array there are 1 errors!

They are from block 233641 to 233641, specifically at blocks: 233641

To fix them use the command 'snapraid -e fix'.
The errors will disappear from the 'status' at the next 'scrub' command.
```
