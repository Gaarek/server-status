---
layout: post
title: Snapraid-status
date: 2019-08-02 10:34:09
excerpt_separator: ""
categories: Snapraid-status Snapraid
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


 10%|            *      *     *     *      *     o            *     *     *
    |      o     *      *     *     *      *     *            *     *     *
    |      *     *      *     *     *      *     *            *     *     *
    |      *     *      *     *     *      *     *            *     *     *
    |      *     *      *     *     *      *     *            *     *     *
    |      *     *      *     *     *      *     *            *     *     *
    |      *     *      *     *     *      *     *            *     *     *
  5%|      *     *      *     *     *      *     *            *     *     *
    |      *     *      *     *     *      *     *            *     *     *
    |      *     *      *     *     *      *     *            *     *     *
    |      *     *      *     *     *      *     *            *     *     *
    |      *     *      *     *     *      *     *            *     *     *
    |      *     *      *     *     *      *     *            *     *     *
    |      *     *      *     *     *      *     *            *     *     *
  0%|o_____*___o_*______*_____*o____*______*_____*____________*_____*_____*
    80                    days ago of the last scrub/sync                 3

The oldest block was scrubbed 80 days ago, the median 38, the newest 3.

No sync is in progress.
The 1% of the array is not scrubbed.
You have 34842 files with zero sub-second timestamp.
Run the 'touch' command to set it to a not zero value.
No rehash is in progress or needed.
DANGER! In the array there are 781 errors!

They are from block 17020 to 7570920, specifically at blocks: 17020 18236 18972 19196 20060 20444 164863 165279 165439 165471 166207 166815 167135 167711 167871 168479 169055 169087 169407 169951 173407 174783 176319 177279 177663 178715 178811 179099 179611 179643 180059 183803 184379 184571 185691 185787 186011 192123 193339 194683 194747 195067 195451 195547 195579 196379 196507 196571 197371 200699 201243 201947 202139 202299 206619 207451 208027 209914 210106 210778 212794 213018 213498 213594 214170 215450 215610 217914 218394 220954 223194 225402 226266 228410 228474 228602 229338 229690 2224827 2224859 2228315 2228827 2228859 2231291 2232539 2232635 2232667 2235867 2236251 2240603 2241627 2242939 2243611 2245787 2248219 2248603 2249275 2249339 2249371 2250331 2251707 and 680 more...

To fix them use the command 'snapraid -e fix'.
The errors will disappear from the 'status' at the next 'scrub' command.
```
