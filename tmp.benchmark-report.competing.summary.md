| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --max-depth=1 tmp.sample` | 128.2 ± 6.9 | 122.0 | 155.6 | 1.00 |
| `dutree --summary tmp.sample` | 314.5 ± 5.7 | 307.6 | 327.2 | 2.45 ± 0.14 |
| `dua --apparent-size tmp.sample` | 231.5 ± 18.1 | 206.8 | 282.6 | 1.81 ± 0.17 |
| `ncdu -o /dev/null -0 tmp.sample` | 203.7 ± 4.3 | 199.2 | 213.9 | 1.59 ± 0.09 |
| `du --apparent-size --total tmp.sample` | 189.7 ± 3.0 | 186.0 | 196.2 | 1.48 ± 0.08 |
