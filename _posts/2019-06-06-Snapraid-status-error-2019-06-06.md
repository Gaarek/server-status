---
layout: post
title: Snapraid-status-error 2019-06-06 10:33:55
date: 2019-06-06 10:33:55
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
   22133       1       3       -    1774     164  91% d2
   12706       0       0       -    1825     141  92% d3
    3098      13      19       -    2010     181  91% d4
 --------------------------------------------------------------------------
   39589      14      22     0.0    5815    1258  82%


 10%|            *      *     *     *      *     *     *      o     *     *
    |            *      *     *     *      *     *     *      *     *     *
    |            *      *     *     *      *     *     *      *     *     *
    |            *      *     *     *      *     *     *      *     *     *
    |            *      *     *     *      *     *     *      *     *     *
    |            *      *     *     *      *     *     *      *     *     *
    |            *      *     *     *      *     *     *      *     *     *
  5%|            *      *     *     *      *     *     *      *     *     *
    |            *      *     *     *      *     *     *      *     *     *
    |            *      *     *     *      *     *     *      *     *     *
    |            *      *     *     *      *     *     *      *     *     *
    |            *      *     *     *      *     *     *      *     *     *
    |            *      *     *     *      *     *     *      *     *     *
    |            *      *     *     *      *     *     *      *     *     *
  0%|*___________*______*_____*_____*______*o____*_____*o_____*___o_*_____*
    79                    days ago of the last scrub/sync                 2

The oldest block was scrubbed 79 days ago, the median 30, the newest 2.

No sync is in progress.
The 1% of the array is not scrubbed.
You have 34839 files with zero sub-second timestamp.
Run the 'touch' command to set it to a not zero value.
No rehash is in progress or needed.
DANGER! In the array there are 1 errors!

They are from block 3952358 to 3952358, specifically at blocks: 3952358

To fix them use the command 'snapraid -e fix'.
The errors will disappear from the 'status' at the next 'scrub' command.
```
