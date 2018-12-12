---
layout: post
title: Snapraid-status-error 2018-12-12 10:34:07
date: 2018-12-12 10:34:07
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
    1652       0       0       -     205     781  20% d1
   22130       1       3       -    1770     168  91% d2
   12706       0       0       -    1825     141  92% d3
    3017       7       7       -    1926     266  87% d4
 --------------------------------------------------------------------------
   39505       8      10     0.0    5727    1357  80%


 10%|      *      *      *       *      *      *      *      *      *     *
    |      *      *      *       *      *      *      *      *      *     *
    |      *      *      *       *      *      *      *      *      *     *
    |      *      *      *       *      *      *      *      *      *     *
    |      *      *      *       *      *      *      *      *      *     *
    |      *      *      *       *      *      *      *      *      *     *
    |      *      *      *       *      *      *      *      *      *     *
  5%|      *      *      *       *      *      *      *      *      *     *
    |      *      *      *       *      *      *      *      *      *     *
    |      *      *      *       *      *      *      *      *      *     *
    |      *      *      *       *      *      *      *      *      *     *
    |      *      *      *       *      *      *      *      *      *     *
    |      *      *      *       *      *      *      *      *      *     *
    |      *      *      *       *      *      *      *      *      *     *
  0%|*_____*____o_*______*o______*_o_oo_*______*_o____*____o_*_oo___*__o__*
    71                    days ago of the last scrub/sync                 1

The oldest block was scrubbed 71 days ago, the median 29, the newest 1.

No sync is in progress.
The 1% of the array is not scrubbed.
You have 34836 files with zero sub-second timestamp.
Run the 'touch' command to set it to a not zero value.
No rehash is in progress or needed.
DANGER! In the array there are 1 errors!

They are from block 1137460 to 1137460, specifically at blocks: 1137460

To fix them use the command 'snapraid -e fix'.
The errors will disappear from the 'status' at the next 'scrub' command.
```
