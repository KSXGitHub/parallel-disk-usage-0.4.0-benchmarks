| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --no-sort tmp.sample` | 125.8 ± 3.5 | 120.9 | 136.0 | 1.00 |
| `du --apparent-size tmp.sample` | 193.3 ± 4.3 | 188.0 | 203.3 | 1.54 ± 0.05 |
| `dua --apparent-size tmp.sample` | 227.1 ± 9.7 | 214.6 | 243.9 | 1.81 ± 0.09 |
| `ncdu -o /dev/stdout -0 tmp.sample` | 204.2 ± 6.7 | 192.1 | 221.7 | 1.62 ± 0.07 |
| `gdu --show-apparent-size --non-interactive --no-progress tmp.sample` | 302.0 ± 7.6 | 292.8 | 318.6 | 2.40 ± 0.09 |
