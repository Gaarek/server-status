---
layout: post
title: Snapraid-smart
date: 2019-04-19 13:33:01
excerpt_separator: ""
categories: Snapraid-smart Snapraid
---
```
SnapRAID SMART report:

   Temp  Power   Error   FP Size
      C OnDays   Count        TB  Serial           Device    Disk
 -----------------------------------------------------------------------
     38    510       0   5%  4.0  ZFN0AXAE         /dev/sda  d1
     34   2890       0  84%  2.0  WD-WCAZA4781250  /dev/sdc  d2
     37   3235       0  84%  2.0  WD-WCAVY1868172  /dev/sde  d3
     37   1977       0   4%  3.0  WD-WCC1T1092827  /dev/sdb  d4
     35    623       0  11%  3.0  WD-WCC4N2FH6A6Z  /dev/sdf  parity
     37   1393      17 100%  3.0  WD-WCC4N1KACD4K  /dev/sdd  2-parity
     37    588       0  16%  3.0  WD-WCC4N6ZA9X1E  /dev/sdg  -

The FP column is the estimated probability (in percentage) that the disk
is going to fail in the next year.

Probability that at least one disk is going to fail in the next year is 100%.

Probability of data loss in the next year for different parity and
combined scrub and repair time:

  Parity  1 Week                1 Month             3 Months
 -----------------------------------------------------------------------
     1    73.81%                 99.68%               100.00%      
     2    14.52%                 94.39%               100.00%      
     3     1.37%                 66.18%               100.00%      
     4     0.081%                23.81%               100.00%      
     5     0.0024%                3.35%               99.97%       
     6     0.00000000000000%      0.00000000000000%     0.00000000000000%

These values are the probabilities that in the next year you'll have a
sequence of failures that the parity WONT be able to recover, assuming
that you regularly scrub, and in case repair, the array in the specified
time.
```
