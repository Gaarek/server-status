---
layout: post
title: Snapraid-status-error 2019-08-16 10:34:00
date: 2019-08-16 10:34:00
excerpt_separator: ""
categories: Snapraid-status-error Snapraid
---
```
Self test...
Loading state from /home/public/HDD7/snapraid.content...
Using 401 MiB of memory for the FileSystem.
SnapRAID status report:

   Files Fragmented Excess  Wasted  Used    Free  Use Name
            Files  Fragments  GB      GB      GB
    1652       1       1       -     205     769  21% d1
   22136       1       3       -    1776     161  91% d2
   12706       0       0       -    1825     141  92% d3
    3097      13      19       -    2010     181  91% d4
 --------------------------------------------------------------------------
   39591      15      23     0.0    5818    1254  82%


 10%|            *      *     *     o            *     *      *     *     *
    |      *     *      *     *     *            *     *      *     *     *
    |      *     *      *     *     *            *     *      *     *     *
    |      *     *      *     *     *            *     *      *     *     *
    |      *     *      *     *     *            *     *      *     *     *
    |      *     *      *     *     *            *     *      *     *     *
    |      *     *      *     *     *            *     *      *     *     *
  5%|      *     *      *     *     *            *     *      *     *     *
    |      *     *      *     *     *            *     *      *     *     *
    |      *     *      *     *     *            *     *      *     *     *
    |      *     *      *     *     *            *     *      *     *     *
    |      *     *      *     *     *            *     *      *     *     *
    |      *     *      *     *     *            *     *      *     *     *
    |      *     *      *     *     *            *     *      *     *     *
  0%|*_____*_____*_o____*_____*_____*____________*_____*______*____**_____*
    80                    days ago of the last scrub/sync                 3

The oldest block was scrubbed 80 days ago, the median 45, the newest 3.

No sync is in progress.
The 1% of the array is not scrubbed.
You have 34842 files with zero sub-second timestamp.
Run the 'touch' command to set it to a not zero value.
No rehash is in progress or needed.
DANGER! In the array there are 163 errors!

They are from block 61601 to 3685872, specifically at blocks: 61601 62081 62369 63041 63169 65825 66241 66369 67329 105675 151499 323298 327170 328450 329538 330530 330594 330626 331106 334242 337154 337186 341474 347970 350626 351298 351458 351490 354018 358146 358178 359682 359842 360002 361538 361730 361858 362498 362722 363106 364354 364962 365410 366754 367330 367458 367587 369026 370370 371170 372898 373442 373443 373474 373506 374338 377218 377730 378210 379362 381346 383938 384034 384130 384802 385858 385922 388834 389378 391906 392930 393442 394722 396258 399362 401442 401506 403618 404514 405282 418089 418889 419497 422624 432016 433360 433968 553492 553556 553876 554548 554804 556788 556948 557940 559444 559636 560052 560148 560436 561108 and 62 more...

To fix them use the command 'snapraid -e fix'.
The errors will disappear from the 'status' at the next 'scrub' command.
```
