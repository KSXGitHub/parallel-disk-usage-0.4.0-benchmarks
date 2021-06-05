| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --no-sort --max-depth=1 tmp.sample` | 125.0 ± 3.5 | 119.9 | 133.2 | 1.00 |
| `dua --apparent-size tmp.sample` | 232.6 ± 11.8 | 220.6 | 260.7 | 1.86 ± 0.11 |
| `ncdu -o /dev/null -0 tmp.sample` | 206.9 ± 7.0 | 196.8 | 222.5 | 1.65 ± 0.07 |
| `gdu --show-apparent-size --non-interactive --no-progress tmp.sample` | 303.9 ± 6.7 | 298.9 | 320.7 | 2.43 ± 0.09 |
| `du --apparent-size --total tmp.sample` | 192.1 ± 5.7 | 184.8 | 203.7 | 1.54 ± 0.06 |
