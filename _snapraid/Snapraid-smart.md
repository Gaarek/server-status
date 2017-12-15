---
layout: post
title: Snapraid-smart
date: 2017-12-15 13:33:01
excerpt_separator: ""
categories: Snapraid-smart Snapraid
---
```
SnapRAID SMART report:

   Temp  Power   Error   FP Size
      C OnDays   Count        TB  Serial           Device    Disk
 -----------------------------------------------------------------------
     37     20       0   5%  4.0  ZFN0AXAE         /dev/sda  d1
     33   2401       0  83%  2.0  WD-WCAZA4781250  /dev/sdc  d2
     35   2756       0  83%  2.0  WD-WCAVY1868172  /dev/sde  d3
     36   1487       0   4%  3.0  WD-WCC1T1092827  /dev/sdb  d4
     34    133       0   5%  3.0  WD-WCC4N2FH6A6Z  /dev/sdf  parity
     35    904      17 100%  3.0  WD-WCC4N1KACD4K  /dev/sdd  2-parity
     35     99       0   5%  3.0  WD-WCC4N6ZA9X1E  /dev/sdg  -

The FP column is the estimated probability (in percentage) that the disk
is going to fail in the next year.

Probability that at least one disk is going to fail in the next year is 100%.

Probability of data loss in the next year for different parity and
combined scrub and repair time:

  Parity  1 Week                1 Month             3 Months
 -----------------------------------------------------------------------
     1    72.39%                 99.60%               100.00%      
     2    13.73%                 93.36%               100.00%      
     3     1.26%                 63.22%               100.00%      
     4     0.073%                21.80%               100.00%      
     5     0.0021%                2.98%               99.94%       
     6     0.00000000000000%      0.00000000000000%     0.00000000000000%

These values are the probabilities that in the next year you'll have a
sequence of failures that the parity WONT be able to recover, assuming
that you regularly scrub, and in case repair, the array in the specified
time.
```
