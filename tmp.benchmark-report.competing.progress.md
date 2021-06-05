| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --progress tmp.sample` | 207.7 ± 0.8 | 206.5 | 209.3 | 1.01 ± 0.02 |
| `ncdu -o /dev/stdout -1 tmp.sample` | 204.7 ± 3.7 | 199.8 | 209.9 | 1.00 |
| `gdu --show-apparent-size --non-interactive tmp.sample` | 309.1 ± 9.3 | 291.2 | 320.2 | 1.51 ± 0.05 |
