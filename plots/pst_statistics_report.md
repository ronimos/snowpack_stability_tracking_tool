# PST Statistics Report

Total observations: 69 across 4 periods
Observation days with nearby avalanches: 8
Observation days without nearby avalanches: 15

## Saw Cut Length (cm)

Test             Context          n    Mean     Std   Min   Max
--------------------------------------------------------------
PST200 (0cm)     Avy days         8    58.8    35.1    33   142
PST200 (0cm)     Non-avy days    15    51.7    40.5    25   162
PST200 (5cm)     Avy days         8    46.6    21.9    27    98
PST200 (5cm)     Non-avy days    15    65.5    41.2    22   158
PST100           Avy days         8    48.0    10.4    34    65
PST100           Non-avy days    15    43.0    15.8    22    73

## Propagation Distance (cm)

Test             Context          n    Mean     Std   Min   Max
--------------------------------------------------------------
PST200 (0cm)     Avy days         5    66.0    54.1    22   159
PST200 (0cm)     Non-avy days    13    26.4    45.9     0   163
PST200 (5cm)     Avy days         6   153.5    25.9   102   173
PST200 (5cm)     Non-avy days    13    91.8    57.1    15   178
PST100           Avy days         8    48.6    13.6    27    66
PST100           Non-avy days    14    44.6    28.4     0    78

## Saw Distance from End (cm)

Test             Context          n    Mean     Std   Min   Max
--------------------------------------------------------------
PST200 (0cm)     Avy days         8   140.0    41.3    41   169
PST200 (0cm)     Non-avy days    15   162.1    41.2    37   195
PST200 (5cm)     Avy days         8    67.1    43.5    27   143
PST200 (5cm)     Non-avy days    15   104.3    49.4    22   178
PST100           Avy days         8    51.5    17.7    34    88
PST100           Non-avy days    14    53.2    20.3    22    85

## Arrest Type Counts

Test             Context          n   End  Arr   SF
----------------------------------------------------
PST200 (0cm)     Avy days         8     2    3    3
PST200 (0cm)     Non-avy days    15     2    2   11
PST200 (5cm)     Avy days         8     6    2    0
PST200 (5cm)     Non-avy days    15     9    2    4
PST100           Avy days         8     7    0    1
PST100           Non-avy days    15    10    1    3

## Paired State Classification (PST200: 0cm vs 5cm)

Avalanche days (8 days):
  UNSTABLE (both End)              2  (25%)
  NEAR THRESHOLD                   4  (50%)
  STABLE (both SF)                 0  (0%)
  MARGINAL (both Arr)              1  (12%)
  Other (SF/Arr)                   1  (12%)

Non-avalanche days (15 days):
  UNSTABLE (both End)              2  (13%)
  NEAR THRESHOLD                   7  (47%)
  STABLE (both SF)                 4  (27%)
  MARGINAL (both Arr)              0  (0%)
  Other (SF/Arr)                   2  (13%)

## PST100 vs PST200 (0cm) Agreement

This quantifies how often the standard 100cm PST saturates at End
when the 200cm PST shows more nuanced results.

  PST200(0cm) = End:
    PST100 End: 4/4 (100%)

  PST200(0cm) = Arr:
    PST100 End: 5/5 (100%)

  PST200(0cm) = SF:
    PST100 End: 8/14 (57%)
    PST100 Arr: 1/14 (7%)
    PST100 SF: 4/14 (29%)

## Sensitivity of 5cm WL Removal

Saw cut difference (5cm removal - standard):
  mean=4.8  std=37.0  range=-44 to 131 cm
  (negative = 5cm removal needed shorter cut, as expected)
  Consistent direction (5cm <= 0cm): 16/23 (70%)