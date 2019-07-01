---
layout: post
title: Snapraid-status-error 2019-07-01 10:33:48
date: 2019-07-01 10:33:48
excerpt_separator: ""
categories: Snapraid-status-error Snapraid
---
```
Self test...
Loading state from /home/public/HDD7/snapraid.content...
Using 401 MiB of memory for the FileSystem.
SnapRAID status report:

   Files Fragmented Excess  Wasted  Used    Free  Use Name
            Files  Fragments  GB      GB      GB
    1652       0       0       -     205     771  21% d1
   22139       1       3       -    1780     158  91% d2
   12706       0       0       -    1825     141  92% d3
    3097      13      19       -    2010     181  91% d4
 --------------------------------------------------------------------------
   39594      14      22     0.0    5821    1253  82%


 10%|      *      *      *      *      *      *      *      *      *      *
    |      *      *      *      *      *      *      *      *      *      *
    |      *      *      *      *      *      *      *      *      *      *
    |      *      *      *      *      *      *      *      *      *      *
    |      *      *      *      *      *      *      *      *      *      *
    |      *      *      *      *      *      *      *      *      *      *
    |      *      *      *      *      *      *      *      *      *      *
  5%|      *      *      *      *      *      *      *      *      *      *
    |      *      *      *      *      *      *      *      *      *      *
    |      *      *      *      *      *      *      *      *      *      *
    |      *      *      *      *      *      *      *      *      *      *
    |      *      *      *      *      *      *      *      *      *      *
    |      *      *      *      *      *      *      *      *      *      *
    |      *      *      *      *      *      *      *      *      *      *
  0%|*_____*______*_o____*______*o_____*o___o_*______*______*_o____*______*
    76                    days ago of the last scrub/sync                 6

The oldest block was scrubbed 76 days ago, the median 34, the newest 6.

No sync is in progress.
The 1% of the array is not scrubbed.
You have 34845 files with zero sub-second timestamp.
Run the 'touch' command to set it to a not zero value.
No rehash is in progress or needed.
DANGER! In the array there are 1 errors!

They are from block 637744 to 637744, specifically at blocks: 637744

To fix them use the command 'snapraid -e fix'.
The errors will disappear from the 'status' at the next 'scrub' command.
```
