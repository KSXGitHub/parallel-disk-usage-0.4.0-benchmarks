| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --min-ratio=0 tmp.sample` | 712.6 ± 18.5 | 690.1 | 755.2 | 3.75 ± 0.13 |
| `dutree tmp.sample` | 3815.4 ± 32.1 | 3751.5 | 3871.7 | 20.07 ± 0.49 |
| `ncdu -o /dev/stdout -0 tmp.sample` | 207.4 ± 5.3 | 198.4 | 220.9 | 1.09 ± 0.04 |
| `du --apparent-size tmp.sample` | 190.1 ± 4.4 | 182.8 | 199.4 | 1.00 |
