---
layout: post
title: Snapraid-status
date: 2018-01-22 10:33:48
excerpt_separator: ""
categories: Snapraid-status Snapraid
---
```
Self test...
Loading state from /home/public/HDD7/snapraid.content...
Using 390 MiB of memory for the FileSystem.
SnapRAID status report:

   Files Fragmented Excess  Wasted  Used    Free  Use Name
            Files  Fragments  GB      GB      GB
    1652       0       0       -     205    1079  15% d1
   22131       1       3       -    1785     153  92% d2
   12706       0       0       -    1825     141  92% d3
    2851       1       1       -    1861     330  84% d4
 --------------------------------------------------------------------------
   39340       2       4     0.0    5677    1705  76%


  8%|                        o       *      *      *     o      o     o    
    |      *      *          o *     *      *      *     *      *     *    
    |      *      *     *    o *     *      *      *     *      *     *    
    |      *      *     *    o *     *      *      *     *      *     *    
    |      *      *     *    o *     *      *      *     *      *     *    
    |      *      *o    *    o *     *      *      *     *      *     *    
    |      *      *o    *    o *     *      *      *     *      *     *    
  4%|      *      *o    *    o *     *      *      *     *      *     *    
    |      *      *o    *    o *     *      *      *     *      *     *    
    |      *      *o    *    o *     *      *      *     *      *     *    
    |      *      *o    *    o *     *      *      *     *      *     *    
    |      *      *o    *    o *     *      *      *     *      *     *    
    |      *      *o    *    o *     *      *      *     *      *     *    
    |*     *      *oo   *    o *     *      *      *     *      *     *    
  0%|*_____*______*oo___*o___o_*oooo_*_oooo_*___o_o*__o__*__oo_o*__o__*oo_o
    76                    days ago of the last scrub/sync                 1

The oldest block was scrubbed 76 days ago, the median 41, the newest 1.

No sync is in progress.
The 18% of the array is not scrubbed.
You have 34846 files with zero sub-second timestamp.
Run the 'touch' command to set it to a not zero value.
No rehash is in progress or needed.
No error detected.
```
