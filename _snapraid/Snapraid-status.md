---
layout: post
title: Snapraid-status
date: 2018-08-15 10:33:53
excerpt_separator: ""
categories: Snapraid-status Snapraid
---
```
Self test...
Loading state from /home/public/HDD7/snapraid.content...
Using 395 MiB of memory for the FileSystem.
SnapRAID status report:

   Files Fragmented Excess  Wasted  Used    Free  Use Name
            Files  Fragments  GB      GB      GB
    1652       0       0       -     205     781  20% d1
   22132       1       3       -    1785     153  92% d2
   12706       0       0       -    1825     141  92% d3
    2992       7       7       -    1922     269  87% d4
 --------------------------------------------------------------------------
   39482       8      10     0.0    5738    1346  81%


 10%|      *      *      *      *      *      *             *      *      *
    |      *      *      *      *      *      *      o      *      *      *
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
    |      *      *      *      *      *      *      *  o   *      *      *
  0%|*_____*__o___*o_____*_o____*______*______*______*__o___*______*______*
    71                    days ago of the last scrub/sync                 1

The oldest block was scrubbed 71 days ago, the median 29, the newest 1.

No sync is in progress.
The 2% of the array is not scrubbed.
You have 34838 files with zero sub-second timestamp.
Run the 'touch' command to set it to a not zero value.
No rehash is in progress or needed.
DANGER! In the array there are 1 errors!

They are from block 2945327 to 2945327, specifically at blocks: 2945327

To fix them use the command 'snapraid -e fix'.
The errors will disappear from the 'status' at the next 'scrub' command.
```
