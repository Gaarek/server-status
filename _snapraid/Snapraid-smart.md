---
layout: post
title: Snapraid-smart
date: 2018-07-20 13:33:02
excerpt_separator: ""
categories: Snapraid-smart Snapraid
---
```
SnapRAID SMART report:

   Temp  Power   Error   FP Size
      C OnDays   Count        TB  Serial           Device    Disk
 -----------------------------------------------------------------------
     44    237       0   5%  4.0  ZFN0AXAE         /dev/sda  d1
     40   2618       0  84%  2.0  WD-WCAZA4781250  /dev/sdc  d2
     43   2968       0  84%  2.0  WD-WCAVY1868172  /dev/sde  d3
     42   1704       0   4%  3.0  WD-WCC1T1092827  /dev/sdb  d4
     41    350       0   8%  3.0  WD-WCC4N2FH6A6Z  /dev/sdf  parity
     42   1121      17 100%  3.0  WD-WCC4N1KACD4K  /dev/sdd  2-parity
     42    316       0   9%  3.0  WD-WCC4N6ZA9X1E  /dev/sdg  -

The FP column is the estimated probability (in percentage) that the disk
is going to fail in the next year.

Probability that at least one disk is going to fail in the next year is 100%.

Probability of data loss in the next year for different parity and
combined scrub and repair time:

  Parity  1 Week                1 Month             3 Months
 -----------------------------------------------------------------------
     1    73.51%                 99.66%               100.00%      
     2    14.34%                 94.18%               100.00%      
     3     1.34%                 65.54%               100.00%      
     4     0.079%                23.36%               100.00%      
     5     0.0023%                3.27%               99.97%       
     6     0.00000000000000%      0.00000000000000%     0.00000000000000%

These values are the probabilities that in the next year you'll have a
sequence of failures that the parity WONT be able to recover, assuming
that you regularly scrub, and in case repair, the array in the specified
time.
```
