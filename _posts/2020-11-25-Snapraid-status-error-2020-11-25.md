---
layout: post
title: Snapraid-status-error 2020-11-25 10:33:57
date: 2020-11-25 10:33:57
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
    1652       1       1       -     205     750  21% d1
   22136       1       3       -    1776     162  91% d2
   12717       1       1       -    1825     140  92% d3
    2944      11      22       -    1887     304  86% d4
 --------------------------------------------------------------------------
   39449      14      27     0.0    5695    1358  80%


 10%|             *      *      *      *       *      *      *      *     *
    |             *      *      *      *       *      *      *      *     *
    |             *      *      *      *       *      *      *      *     *
    |             *      *      *      *       *      *      *      *     *
    |             *      *      *      *       *      *      *      *     *
    |             *      *      *      *       *      *      *      *     *
    |             *      *      *      *       *      *      *      *     *
  5%|             *      *      *      *       *      *      *      *     *
    |      *      *      *      *      *       *      *      *      *     *
    |      *      *      *      *      *       *      *      *      *     *
    |      *      *      *      *      *       *      *      *      *     *
    |      *      *      *      *      *       *      *      *      *     *
    |      *      *      *      *      *       *      *      *      *     *
    |      *      *      *      *      *       *      *      *      *     *
  0%|*_____*______*______*______*______*_______*______*______*______*_____*
    71                    days ago of the last scrub/sync                 1

The oldest block was scrubbed 71 days ago, the median 29, the newest 1.

No sync is in progress.
The full array was scrubbed at least one time.
You have 34853 files with zero sub-second timestamp.
Run the 'touch' command to set it to a not zero value.
No rehash is in progress or needed.
DANGER! In the array there are 92 errors!

They are from block 32802 to 3360478, specifically at blocks: 32802 68448 68576 68736 69120 69152 69632 69696 69984 70080 70272 70304 70528 70560 70624 71680 71872 71904 72000 72064 519762 543025 1073588 1073620 1073652 1073684 3266718 3267294 3267390 3267518 3268158 3268286 3268478 3268510 3268542 3268766 3268798 3269822 3270558 3277502 3281470 3281598 3287198 3287230 3287262 3297534 3305278 3305598 3312254 3318494 3318750 3318814 3318878 3319454 3319582 3320094 3320446 3320574 3321022 3321086 3321246 3321374 3321534 3321566 3321790 3321822 3322430 3322782 3322814 3322942 3322974 3323134 3323486 3324766 3324862 3326046 3326398 3327166 3328734 3328766 3333214 3334622 3338654 3338686 3339166 3341502 3341566 3341758 3342526 3347102 3356158 3360478

To fix them use the command 'snapraid -e fix'.
The errors will disappear from the 'status' at the next 'scrub' command.
```
