---
layout: post
title: Snapraid-smart
date: 2017-11-24 13:33:01
excerpt_separator: ""
categories: Snapraid-smart Snapraid
---
```
SnapRAID SMART report:

   Temp  Power   Error   FP Size
      C OnDays   Count        TB  Serial           Device    Disk
 -----------------------------------------------------------------------
     39   2204       0  84%  1.0  WD-WCC0S0137066  /dev/sdc  d1
     33   2380       0  82%  2.0  WD-WCAZA4781250  /dev/sdb  d2
     40   2735       0  82%  2.0  WD-WCAVY1868172  /dev/sde  d3
     37   1467       0   4%  3.0  WD-WCC1T1092827  /dev/sda  d4
     34    112       0   5%  3.0  WD-WCC4N2FH6A6Z  /dev/sdf  parity
     36    883      17 100%  3.0  WD-WCC4N1KACD4K  /dev/sdd  2-parity
     37     78       0   5%  3.0  WD-WCC4N6ZA9X1E  /dev/sdg  -

The FP column is the estimated probability (in percentage) that the disk
is going to fail in the next year.

Probability that at least one disk is going to fail in the next year is 100%.

Probability of data loss in the next year for different parity and
combined scrub and repair time:

  Parity  1 Week                1 Month             3 Months
 -----------------------------------------------------------------------
     1    83.83%                 99.96%               100.00%      
     2    22.02%                 98.96%               100.00%      
     3     2.51%                 86.53%               100.00%      
     4     0.17%                 44.37%               100.00%      
     5     0.0059%                8.22%               100.00%      
     6     0.00000000000000%      0.00000000000000%     0.00000000000000%

These values are the probabilities that in the next year you'll have a
sequence of failures that the parity WONT be able to recover, assuming
that you regularly scrub, and in case repair, the array in the specified
time.
```
