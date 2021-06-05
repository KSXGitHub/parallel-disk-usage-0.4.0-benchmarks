| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --quantity=blksize tmp.sample` | 126.0 ± 4.5 | 121.8 | 136.4 | 1.00 |
| `dust tmp.sample` | 836.4 ± 31.3 | 809.1 | 913.0 | 6.64 ± 0.34 |
| `dutree --usage tmp.sample` | 3793.2 ± 29.2 | 3751.9 | 3856.8 | 30.11 ± 1.10 |
| `dua tmp.sample` | 254.4 ± 11.9 | 231.6 | 277.5 | 2.02 ± 0.12 |
| `ncdu -o /dev/stdout -0 tmp.sample` | 208.7 ± 7.0 | 200.1 | 226.2 | 1.66 ± 0.08 |
| `gdu --non-interactive --no-progress tmp.sample` | 298.1 ± 8.5 | 288.9 | 315.7 | 2.37 ± 0.11 |
| `du tmp.sample` | 189.9 ± 3.8 | 184.5 | 196.6 | 1.51 ± 0.06 |
