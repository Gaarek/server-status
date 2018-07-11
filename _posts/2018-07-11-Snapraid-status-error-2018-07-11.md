---
layout: post
title: Snapraid-status-error 2018-07-11 10:34:08
date: 2018-07-11 10:34:08
excerpt_separator: ""
categories: Snapraid-status-error Snapraid
---
```
Self test...
Loading state from /home/public/HDD7/snapraid.content...
Using 396 MiB of memory for the FileSystem.
SnapRAID status report:

   Files Fragmented Excess  Wasted  Used    Free  Use Name
            Files  Fragments  GB      GB      GB
    1652       0       0       -     205     782  20% d1
   22132       1       3       -    1785     153  92% d2
   12706       0       0       -    1825     141  92% d3
    2985       7       7       -    1939     253  88% d4
 --------------------------------------------------------------------------
   39475       8      10     0.0    5755    1330  81%


 10%|             o      o      o      o      o      *      *      *      *
    |             *      *      *      *      *      *      *      *      *
    |      o      *      *      *      *      *      *      *      *      *
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
    |      * o    *      *      *      *      *      *      *      *      *
  0%|*_o___*_ooo__*__oo__*__oo__*_____o*__o_o_*__o___*o_____*_o____*______*
    71                    days ago of the last scrub/sync                 1

The oldest block was scrubbed 71 days ago, the median 29, the newest 1.

No sync is in progress.
The 3% of the array is not scrubbed.
You have 34838 files with zero sub-second timestamp.
Run the 'touch' command to set it to a not zero value.
No rehash is in progress or needed.
DANGER! In the array there are 704 errors!

They are from block 36571 to 5835331, specifically at blocks: 36571 36923 39419 39611 44091 44187 44795 46555 47515 61211 66811 67323 105573 411262 411294 411326 413374 413406 413758 415934 416446 416926 417118 423754 428874 428906 440284 5179191 5179287 5179575 5180279 5180631 5181399 5182871 5184503 5186455 5187479 5187671 5188183 5190071 5190807 5192919 5194615 5195607 5196695 5197527 5198263 5198391 5198423 5198519 5198551 5201367 5202775 5204503 5204535 5206807 5209623 5210487 5212247 5212791 5212919 5212951 5213207 5214263 5215255 5215479 5215511 5215543 5215575 5215607 5216087 5216183 5217943 5219287 5219383 5220887 5221175 5221911 5221943 5221975 5222103 5222199 5222231 5222327 5223639 5223671 5223703 5223831 5224023 5224055 5224119 5224215 5224439 5225303 5225591 5225623 5225943 5226327 5226391 5226935 5227127 and 603 more...

To fix them use the command 'snapraid -e fix'.
The errors will disappear from the 'status' at the next 'scrub' command.
```
