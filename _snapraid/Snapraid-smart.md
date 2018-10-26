---
layout: post
title: Snapraid-smart
date: 2018-10-26 13:33:02
excerpt_separator: ""
categories: Snapraid-smart Snapraid
---
```
SnapRAID SMART report:

   Temp  Power   Error   FP Size
      C OnDays   Count        TB  Serial           Device    Disk
 -----------------------------------------------------------------------
     34    335       0   5%  4.0  ZFN0AXAE         /dev/sda  d1
     33   2716       0  84%  2.0  WD-WCAZA4781250  /dev/sdc  d2
     38   3064       0  84%  2.0  WD-WCAVY1868172  /dev/sde  d3
     34   1802       0   4%  3.0  WD-WCC1T1092827  /dev/sdb  d4
     32    448       0   9%  3.0  WD-WCC4N2FH6A6Z  /dev/sdf  parity
     33   1219      17 100%  3.0  WD-WCC4N1KACD4K  /dev/sdd  2-parity
     32    414       0  11%  3.0  WD-WCC4N6ZA9X1E  /dev/sdg  -

The FP column is the estimated probability (in percentage) that the disk
is going to fail in the next year.

Probability that at least one disk is going to fail in the next year is 100%.

Probability of data loss in the next year for different parity and
combined scrub and repair time:

  Parity  1 Week                1 Month             3 Months
 -----------------------------------------------------------------------
     1    73.62%                 99.67%               100.00%      
     2    14.41%                 94.26%               100.00%      
     3     1.35%                 65.77%               100.00%      
     4     0.079%                23.53%               100.00%      
     5     0.0023%                3.30%               99.97%       
     6     0.00000000000000%      0.00000000000000%     0.00000000000000%

These values are the probabilities that in the next year you'll have a
sequence of failures that the parity WONT be able to recover, assuming
that you regularly scrub, and in case repair, the array in the specified
time.
```
