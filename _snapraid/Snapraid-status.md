---
layout: post
title: Snapraid-status
date: 2021-03-14 10:34:00
excerpt_separator: ""
categories: Snapraid-status Snapraid
---
```
Self test...
Loading state from /home/public/HDD7/snapraid.content...
Using 394 MiB of memory for the FileSystem.
SnapRAID status report:

   Files Fragmented Excess  Wasted  Used    Free  Use Name
            Files  Fragments  GB      GB      GB
    1652       1       1       -     205     663  23% d1
   22136       1       3       -    1776     162  91% d2
   12717       1       1       -    1825     140  92% d3
    2947      11      22       -    1887     304  86% d4
 --------------------------------------------------------------------------
   39452      14      27     0.0    5695    1271  81%


 10%|                   *     *     *      *     *     *      *     *     *
    |                   *     *     *      *     *     *      *     *     *
    |                   *     *     *      *     *     *      *     *     *
    |                   *     *     *      *     *     *      *     *     *
    |                   *     *     *      *     *     *      *     *     *
    |                   *     *     *      *     *     *      *     *     *
    |                   *     *     *      *     *     *      *     *     *
  5%|                   *     *     *      *     *     *      *     *     *
    |            *      *     *     *      *     *     *      *     *     *
    |            *      *     *     *      *     *     *      *     *     *
    |            *      *     *     *      *     *     *      *     *     *
    |            *      *     *     *      *     *     *      *     *     *
    |            *      *     *     *      *     *     *      *     *     *
    |            *      *     *     *      *     *     *      *     *     *
  0%|*___________*______*_____*___o_*______*_____*_____*o_____*_____*_____*
    82                    days ago of the last scrub/sync                 5

The oldest block was scrubbed 82 days ago, the median 33, the newest 5.

No sync is in progress.
The 1% of the array is not scrubbed.
You have 34853 files with zero sub-second timestamp.
Run the 'touch' command to set it to a not zero value.
No rehash is in progress or needed.
DANGER! In the array there are 1 errors!

They are from block 5618941 to 5618941, specifically at blocks: 5618941

To fix them use the command 'snapraid -e fix'.
The errors will disappear from the 'status' at the next 'scrub' command.
```
