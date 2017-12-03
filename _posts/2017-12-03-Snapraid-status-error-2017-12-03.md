---
layout: post
title: Snapraid-status-error 2017-12-03 10:33:14
date: 2017-12-03 10:33:14
excerpt_separator: ""
categories: Snapraid-status-error Snapraid
---
```
Self test...
Loading state from /home/public/HDD7/snapraid.content...
Using 388 MiB of memory for the FileSystem.
SnapRAID status report:

   Files Fragmented Excess  Wasted  Used    Free  Use Name
            Files  Fragments  GB      GB      GB
    1652       0       0       -     205    1095  15% d1
   22130       1       3       -    1783     155  92% d2
   12706       0       0       -    1825     141  92% d3
    2820       1       1       -    1839     353  83% d4
 --------------------------------------------------------------------------
   39308       2       4     0.0    5653    1745  76%


 24%|o                                                                     
    |o                                                                     
    |o                                                                     
    |o                                                                     
    |o                                                                     
    |o                                                                     
    |o                                                                     
 12%|o                                                                     
    |o                                                                     
    |o                             *      *      *      *     *           o
    |o                      *      *      *      *      *     *      *    o
    |o                      *      *      *      *      *     * o    *    o
    |o                      *      *      *      *      *     * o    *    o
    |o               *      *      *      *      *      *     * o    *    o
  0%|oo________*____o*______*______*______*______*______*_____*_oo___*o___o
    71                    days ago of the last scrub/sync                 0

The oldest block was scrubbed 71 days ago, the median 33, the newest 0.

WARNING! The array is NOT fully synced.
You have a sync in progress at 99%.
The 41% of the array is not scrubbed.
You have 34845 files with zero sub-second timestamp.
Run the 'touch' command to set it to a not zero value.
No rehash is in progress or needed.
DANGER! In the array there are 1 errors!

They are from block 6445041 to 6445041, specifically at blocks: 6445041

To fix them use the command 'snapraid -e fix'.
The errors will disappear from the 'status' at the next 'scrub' command.
```
