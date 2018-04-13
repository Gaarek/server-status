---
layout: post
title: Snapraid-smart
date: 2018-04-13 13:33:01
excerpt_separator: ""
categories: Snapraid-smart Snapraid
---
```
SnapRAID SMART report:

   Temp  Power   Error   FP Size
      C OnDays   Count        TB  Serial           Device    Disk
 -----------------------------------------------------------------------
     39    139       0   5%  4.0  ZFN0AXAE         /dev/sda  d1
     35   2520       0  84%  2.0  WD-WCAZA4781250  /dev/sdc  d2
     43   2872       0  84%  2.0  WD-WCAVY1868172  /dev/sde  d3
     38   1606       0   4%  3.0  WD-WCC1T1092827  /dev/sdb  d4
     36    252       0   6%  3.0  WD-WCC4N2FH6A6Z  /dev/sdf  parity
     37   1023      17 100%  3.0  WD-WCC4N1KACD4K  /dev/sdd  2-parity
     37    218       0   7%  3.0  WD-WCC4N6ZA9X1E  /dev/sdg  -

The FP column is the estimated probability (in percentage) that the disk
is going to fail in the next year.

Probability that at least one disk is going to fail in the next year is 100%.

Probability of data loss in the next year for different parity and
combined scrub and repair time:

  Parity  1 Week                1 Month             3 Months
 -----------------------------------------------------------------------
     1    73.40%                 99.66%               100.00%      
     2    14.28%                 94.11%               100.00%      
     3     1.34%                 65.32%               100.00%      
     4     0.078%                23.21%               100.00%      
     5     0.0023%                3.24%               99.97%       
     6     0.00000000000000%      0.00000000000000%     0.00000000000000%

These values are the probabilities that in the next year you'll have a
sequence of failures that the parity WONT be able to recover, assuming
that you regularly scrub, and in case repair, the array in the specified
time.
```
