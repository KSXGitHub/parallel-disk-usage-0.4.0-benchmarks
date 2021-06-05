| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --quantity=len tmp.sample` | 150.1 ± 34.7 | 117.8 | 229.7 | 1.00 |
| `dust --apparent-size tmp.sample` | 550.7 ± 21.7 | 525.7 | 593.4 | 3.67 ± 0.86 |
| `dutree tmp.sample` | 3810.0 ± 36.3 | 3757.8 | 3874.5 | 25.39 ± 5.88 |
| `dua --apparent-size tmp.sample` | 235.0 ± 16.8 | 210.2 | 279.7 | 1.57 ± 0.38 |
| `ncdu -o /dev/stdout -0 tmp.sample` | 213.4 ± 6.7 | 205.4 | 225.5 | 1.42 ± 0.33 |
| `gdu --show-apparent-size --non-interactive --no-progress tmp.sample` | 318.9 ± 7.2 | 308.1 | 330.8 | 2.13 ± 0.49 |
| `du --apparent-size tmp.sample` | 196.6 ± 4.3 | 189.1 | 204.5 | 1.31 ± 0.30 |
