---
layout: post
title: Snapraid-smart
date: 2020-11-27 13:33:02
excerpt_separator: ""
categories: Snapraid-smart Snapraid
---
```
SnapRAID SMART report:

   Temp  Power   Error   FP Size
      C OnDays   Count        TB  Serial           Device    Disk
 -----------------------------------------------------------------------
     42   1098       0   5%  4.0  ZFN0AXAE         /dev/sda  d1
     37   3478       0  84%  2.0  WD-WCAZA4781250  /dev/sdc  d2
     44   3810       0  84%  2.0  WD-WCAVY1868172  /dev/sde  d3
     40   2564       0  97%  3.0  WD-WCC1T1092827  /dev/sdb  d4
     39   1210       0  20%  3.0  WD-WCC4N2FH6A6Z  /dev/sdf  parity
     40   1981      17 100%  3.0  WD-WCC4N1KACD4K  /dev/sdd  2-parity
     41   1176       0  50%  3.0  WD-WCC4N6ZA9X1E  /dev/sdg  -

The FP column is the estimated probability (in percentage) that the disk
is going to fail in the next year.

Probability that at least one disk is going to fail in the next year is 100%.

Probability of data loss in the next year for different parity and
combined scrub and repair time:

  Parity  1 Week                1 Month             3 Months
 -----------------------------------------------------------------------
     1    92.81%                 100.00%              100.00%      
     2    35.08%                 99.96%               100.00%      
     3     5.18%                 98.48%               100.00%      
     4     0.44%                 77.05%               100.00%      
     5     0.018%                22.80%               100.00%      
     6     0.00000000000000%      0.00000000000000%     0.00000000000000%

These values are the probabilities that in the next year you'll have a
sequence of failures that the parity WONT be able to recover, assuming
that you regularly scrub, and in case repair, the array in the specified
time.
```
