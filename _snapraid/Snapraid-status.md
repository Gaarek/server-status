---
layout: post
title: Snapraid-status
date: 2018-01-18 10:33:51
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
    2849       1       1       -    1859     332  84% d4
 --------------------------------------------------------------------------
   39338       2       4     0.0    5675    1707  76%


  8%|      *      *           o *      *      *      *     o      o      o 
    |      *      *      *    o *      *      *      *     *      *      * 
    |      *      *      *    o *      *      *      *     *      *      * 
    |      *      *      *    o *      *      *      *     *      *      * 
    |      *      * o    *    o *      *      *      *     *      *      * 
    |      *      * o    *    o *      *      *      *     *      *      * 
    |      *      * o    *    o *      *      *      *     *      *      * 
  4%|      *      * o    *    o *      *      *      *     *      *      * 
    |      *      * o    *    o *      *      *      *     *      *      * 
    |      *      * o    *    o *      *      *      *     *      *      * 
    |      *      * o    *    o *      *      *      *     *      *      * 
    |      *      * o    *    o *      *      *      *     *      *      * 
    |      *      * o    *    o *      *      *      *     *      *      * 
    |*     *      * oo   *    o *      *      *      *     *      *      * 
  0%|*_____*______*_oo___*o___oo*oooo__*oooo__*___o_o*__o__*___oo_*o__o__*o
    72                    days ago of the last scrub/sync                 0

The oldest block was scrubbed 72 days ago, the median 37, the newest 0.

No sync is in progress.
The 18% of the array is not scrubbed.
You have 34846 files with zero sub-second timestamp.
Run the 'touch' command to set it to a not zero value.
No rehash is in progress or needed.
No error detected.
```
