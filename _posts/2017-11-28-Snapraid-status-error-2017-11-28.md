---
layout: post
title: Snapraid-status-error 2017-11-28 10:33:51
date: 2017-11-28 10:33:51
excerpt_separator: ""
categories: Snapraid-status-error Snapraid
---
```
Self test...
Loading state from /home/public/HDD7/snapraid.content...
Using 378 MiB of memory for the FileSystem.
SnapRAID status report:

   Files Fragmented Excess  Wasted  Used    Free  Use Name
            Files  Fragments  GB      GB      GB
    1652       0       0       -     205     247  45% d1
   22130       1       3       -    1783     155  92% d2
   12706       0       0       -    1825     141  92% d3
    2498       0       0       -    1678     384  81% d4
 --------------------------------------------------------------------------
   38986       1       3     0.0    5493     928  85%


 24%|o                                                                     
    |o                                                                     
    |o                                                                     
    |o                                                                     
    |o                                                                     
    |o                                                                     
    |o                                                                     
 12%|o                                                                     
    |o                                                                     
    |o         *                      *      *      *       *      *      *
    |o         *              *       *      *      *       *      *      *
    |o         *              *       *      *      *       *      * o    *
    |o         *              *       *      *      *       *      * o    *
    |o         *       *      *       *      *      *       *      * o    *
  0%|oo________**____o_*_____o*_______*______*______*_______*______*_oo___*
    66                    days ago of the last scrub/sync                 0

The oldest block was scrubbed 66 days ago, the median 35, the newest 0.

No sync is in progress.
The 32% of the array is not scrubbed.
You have 34836 files with zero sub-second timestamp.
Run the 'touch' command to set it to a not zero value.
No rehash is in progress or needed.
DANGER! In the array there are 1 errors!

They are from block 4178495 to 4178495, specifically at blocks: 4178495

To fix them use the command 'snapraid -e fix'.
The errors will disappear from the 'status' at the next 'scrub' command.
```
