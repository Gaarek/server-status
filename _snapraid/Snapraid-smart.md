---
layout: post
title: Snapraid-smart
date: 2020-06-12 13:33:02
excerpt_separator: ""
categories: Snapraid-smart Snapraid
---
```
SnapRAID SMART report:

   Temp  Power   Error   FP Size
      C OnDays   Count        TB  Serial           Device    Disk
 -----------------------------------------------------------------------
     42    930       0   5%  4.0  ZFN0AXAE         /dev/sda  d1
     38   3310       0  84%  2.0  WD-WCAZA4781250  /dev/sdc  d2
     45   3646       0  84%  2.0  WD-WCAVY1868172  /dev/sde  d3
     41   2396       0  97%  3.0  WD-WCC1T1092827  /dev/sdb  d4
     40   1042       0  18%  3.0  WD-WCC4N2FH6A6Z  /dev/sdf  parity
     41   1813      17 100%  3.0  WD-WCC4N1KACD4K  /dev/sdd  2-parity
     42   1008       0  42%  3.0  WD-WCC4N6ZA9X1E  /dev/sdg  -

The FP column is the estimated probability (in percentage) that the disk
is going to fail in the next year.

Probability that at least one disk is going to fail in the next year is 100%.

Probability of data loss in the next year for different parity and
combined scrub and repair time:

  Parity  1 Week                1 Month             3 Months
 -----------------------------------------------------------------------
     1    92.74%                 100.00%              100.00%      
     2    34.92%                 99.96%               100.00%      
     3     5.14%                 98.43%               100.00%      
     4     0.43%                 76.72%               100.00%      
     5     0.018%                22.57%               100.00%      
     6     0.00000000000000%      0.00000000000000%     0.00000000000000%

These values are the probabilities that in the next year you'll have a
sequence of failures that the parity WONT be able to recover, assuming
that you regularly scrub, and in case repair, the array in the specified
time.
```
