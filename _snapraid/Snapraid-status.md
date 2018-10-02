---
layout: post
title: Snapraid-status
date: 2018-10-02 10:33:53
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


 10%|            *      *           *      *     *     *      *     *     *
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
    |            *      *     * o   *      *     *     *      *     *     *
  0%|*_____*_o___*______*_____*_o___*______*___o_*_____*______*_____*__*__*
    77                    days ago of the last scrub/sync                 0

The oldest block was scrubbed 77 days ago, the median 28, the newest 0.

No sync is in progress.
The 1% of the array is not scrubbed.
You have 34836 files with zero sub-second timestamp.
Run the 'touch' command to set it to a not zero value.
No rehash is in progress or needed.
DANGER! In the array there are 185 errors!

They are from block 614838 to 5963802, specifically at blocks: 614838 641731 654726 655238 658246 662246 666764 668652 668684 668972 669132 669420 677044 677076 680404 685268 690197 690741 691957 693077 708373 717269 721243 721467 721691 729101 729261 738335 740351 740415 740543 742143 742783 743199 745279 745823 745983 746943 748575 751423 755551 756351 756415 765712 765872 766512 769168 769680 769904 771440 771760 772272 772336 780127 791071 792127 796095 798207 798911 799583 806310 810116 812548 827785 828649 862249 970470 973734 981446 984518 984582 1002751 1003007 1003199 1004255 1004543 1004575 1007901 1008061 1011901 1012221 1013853 1014109 1014685 1018653 1018685 1025533 1044925 1044989 1049149 1049501 1057405 1065437 1065597 1090297 1112935 1112967 1112999 1113319 1114310 1114566 and 84 more...

To fix them use the command 'snapraid -e fix'.
The errors will disappear from the 'status' at the next 'scrub' command.
```
