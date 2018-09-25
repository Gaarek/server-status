---
layout: post
title: Snapraid-status
date: 2018-09-25 10:33:53
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
    1652       0       0       -     205     781  20% d1
   22130       1       3       -    1770     168  91% d2
   12706       0       0       -    1825     141  92% d3
    2982       7       7       -    1917     274  87% d4
 --------------------------------------------------------------------------
   39470       8      10     0.0    5719    1365  80%


 10%|             *      *             *      *      *      *      *      *
    |      *      *      *      *      *      *      *      *      *      *
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
    |      *  o   *      *      *  o   *      *      *      *      *      *
  0%|*_____*__o___*______*______*__o___*______*____o_*______*______*______*
    70                    days ago of the last scrub/sync                 0

The oldest block was scrubbed 70 days ago, the median 28, the newest 0.

No sync is in progress.
The 2% of the array is not scrubbed.
You have 34836 files with zero sub-second timestamp.
Run the 'touch' command to set it to a not zero value.
No rehash is in progress or needed.
DANGER! In the array there are 358 errors!

They are from block 5916587 to 7237990, specifically at blocks: 5916587 5916875 5917163 5917355 5923115 5924715 5937931 5954987 5963802 5965419 5965771 5966187 5974155 5993547 5994475 5997547 5997643 5998187 5998315 5998603 5999083 5999211 5999499 5999947 6000203 6002187 6002315 6003819 6004203 6004363 6020491 6023851 6024971 6025323 6025515 6026507 6027435 6028011 6028171 6028267 6028523 6030059 6030219 6030283 6030507 6030859 6031147 6031499 6032715 6033067 6033259 6035563 6035787 6036811 6037579 6037995 6038187 6039531 6039883 6040139 6040267 6040491 6040971 6041579 6041995 6043083 6043243 6043403 6043787 6044939 6044971 6045003 6045035 6045131 6045163 6045323 6049323 6049611 6053099 6055851 6057003 6058283 6059979 6066571 6066827 6066891 6067467 6068875 6069099 6069259 6070859 6073035 6074507 6079723 6080139 6080811 6081547 6081835 6085803 6087851 6089483 and 257 more...

To fix them use the command 'snapraid -e fix'.
The errors will disappear from the 'status' at the next 'scrub' command.
```
