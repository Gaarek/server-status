---
layout: post
title: Snapraid-status-error 2018-09-28 10:33:57
date: 2018-09-28 10:33:57
excerpt_separator: ""
categories: Snapraid-status-error Snapraid
---
```
Self test...
Loading state from /home/public/HDD7/snapraid.content...
Using 394 MiB of memory for the FileSystem.
SnapRAID status report:

   Files Fragmented Excess  Wasted  Used    Free  Use Name
            Files  Fragments  GB      GB      GB
    1652       0       0       -     205     781  20% d1
   22130       1       3       -    1770     168  91% d2
   12706       0       0       -    1825     141  92% d3
    2982       7       7       -    1917     274  87% d4
 --------------------------------------------------------------------------
   39470       8      10     0.0    5719    1365  80%


 10%|             *      *            *      *      *     *      *      *  
    |             *      *     *      *      *      *     *      *      *  
    |      *      *      *     *      *      *      *     *      *      *  
    |      *      *      *     *      *      *      *     *      *      *  
    |      *      *      *     *      *      *      *     *      *      *  
    |      *      *      *     *      *      *      *     *      *      *  
    |      *      *      *     *      *      *      *     *      *      *  
  5%|      *      *      *     *      *      *      *     *      *      *  
    |      *      *      *     *      *      *      *     *      *      *  
    |      *      *      *     *      *      *      *     *      *      *  
    |      *      *      *     *      *      *      *     *      *      *  
    |      *      *      *     *      *      *      *     *      *      *  
    |      *      *      *     *      *      *      *     *      *      *  
    |      *  o   *      *     *  o   *      *      *     *      *      *  
  0%|*_____*__o___*______*_____*__o___*______*___o__*_____*______*______*_*
    73                    days ago of the last scrub/sync                 0

The oldest block was scrubbed 73 days ago, the median 31, the newest 0.

No sync is in progress.
The 2% of the array is not scrubbed.
You have 34836 files with zero sub-second timestamp.
Run the 'touch' command to set it to a not zero value.
No rehash is in progress or needed.
DANGER! In the array there are 1 errors!

They are from block 5963802 to 5963802, specifically at blocks: 5963802

To fix them use the command 'snapraid -e fix'.
The errors will disappear from the 'status' at the next 'scrub' command.
```
