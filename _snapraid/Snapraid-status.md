---
layout: post
title: Snapraid-status
date: 2018-05-14 10:33:55
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
    1652       0       0       -     205     801  20% d1
   22132       1       3       -    1785     153  92% d2
   12706       0       0       -    1825     141  92% d3
    2963       5       5       -    1919     272  87% d4
 --------------------------------------------------------------------------
   39453       6       8     0.0    5735    1369  80%


 11%|           o       *       *       o                                  
    |    o      *       *       *       *                                  
    |    *      *       *       *       *      o       *                   
    |    *      *       *       *       *      *       *       *       *   
    |    *      *       *       *       *      *       *       *       *   
    |    *      *       *       *       *      *       *       *       *   
    |    *      *       *       *       *      *       *       *       *   
  5%|    *      *       *       *       *      *       *       *       *   
    |    *      *       *       *       *      *       *       *       *   
    |    *      *       *       *       *      *       *       *       *   
    |    *      *       *       *       *      *       *       *       *   
    |    *      *       *       *       *      *       *       *       *   
    |    *      *       *       *       *      *       *       *       *   
    |    *      *       *       *       *      *       *       *       * o 
  0%|o__o*o_____**o_____*_o____o*___o__o*______*o_____o*___o__o*_ooo__o*_oo
    65                    days ago of the last scrub/sync                 2

The oldest block was scrubbed 65 days ago, the median 34, the newest 2.

No sync is in progress.
The 4% of the array is not scrubbed.
You have 34838 files with zero sub-second timestamp.
Run the 'touch' command to set it to a not zero value.
No rehash is in progress or needed.
No error detected.
```
