---
layout: post
title: Snapraid-status
date: 2018-02-10 10:33:52
excerpt_separator: ""
categories: Snapraid-status Snapraid
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
    2863       1       1       -    1871     320  85% d4
 --------------------------------------------------------------------------
   39352       2       4     0.0    5687    1695  77%


 10%|                                                                   o  
    |     o                                                             *  
    |     o*      *      *      *     o      o      o      o     o      *  
    |     o*      *      *      *     *      *      *      *     *      *  
    |     o*      *      *      *     *      *      *      *     *      *  
    |     o*      *      *      *     *      *      *      *     *      *  
    |     o*      *      *      *     *      *      *      *     *      *  
  5%|o    o*      *      *      *     *      *      *      *     *      *  
    |*    o*      *      *      *     *      *      *      *     *      *  
    |*    o*      *      *      *     *      *      *      *     *      *  
    |*    o*      *      *      *     *      *      *      *     *      *  
    |*    o*      *      *      *     *      *      *      *     *      *  
    |*    o*      *      *      *     *      *      *      *     *      *  
    |*    o*      *      *      *     *      *      *      *     *      *  
  0%|*____o*_ooo__*oooo__*___o_o*__o__*___oo_*__o__o*o__o_o*___o_*o___o_*oo
    74                    days ago of the last scrub/sync                 1

The oldest block was scrubbed 74 days ago, the median 39, the newest 1.

No sync is in progress.
The 12% of the array is not scrubbed.
You have 34846 files with zero sub-second timestamp.
Run the 'touch' command to set it to a not zero value.
No rehash is in progress or needed.
No error detected.
```
