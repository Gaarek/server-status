---
layout: post
title: Snapraid-smart
date: 2018-02-23 13:33:02
excerpt_separator: ""
categories: Snapraid-smart Snapraid
---
```
SnapRAID SMART report:

   Temp  Power   Error   FP Size
      C OnDays   Count        TB  Serial           Device    Disk
 -----------------------------------------------------------------------
     37     90       0   5%  4.0  ZFN0AXAE         /dev/sda  d1
     33   2471       0  84%  2.0  WD-WCAZA4781250  /dev/sdc  d2
     36   2824       0  84%  2.0  WD-WCAVY1868172  /dev/sde  d3
     36   1557       0   4%  3.0  WD-WCC1T1092827  /dev/sdb  d4
     34    203       0   6%  3.0  WD-WCC4N2FH6A6Z  /dev/sdf  parity
     36    974      17 100%  3.0  WD-WCC4N1KACD4K  /dev/sdd  2-parity
     36    169       0   6%  3.0  WD-WCC4N6ZA9X1E  /dev/sdg  -

The FP column is the estimated probability (in percentage) that the disk
is going to fail in the next year.

Probability that at least one disk is going to fail in the next year is 100%.

Probability of data loss in the next year for different parity and
combined scrub and repair time:

  Parity  1 Week                1 Month             3 Months
 -----------------------------------------------------------------------
     1    73.36%                 99.65%               100.00%      
     2    14.26%                 94.07%               100.00%      
     3     1.33%                 65.23%               100.00%      
     4     0.078%                23.15%               100.00%      
     5     0.0023%                3.23%               99.97%       
     6     0.00000000000000%      0.00000000000000%     0.00000000000000%

These values are the probabilities that in the next year you'll have a
sequence of failures that the parity WONT be able to recover, assuming
that you regularly scrub, and in case repair, the array in the specified
time.
```
