# Simple Interest Calculator

A calculator that calculates simple interest given principal, annual rate of interest and time period in years. This educational Bash project is part of IBM's Introduction to Git and GitHub course.

## Inputs and output

- `p` — principal amount.
- `t` — time period in years.
- `r` — annual interest rate, entered as a percentage.

When the annual rate is expressed as a fraction of one, simple interest is `p*t*r`. This script accepts a percentage instead, so it calculates `p*t*r/100`. The output is the interest earned, not the principal plus interest.

## Run

Use Bash with the `expr` command available:

```bash
bash simple-interest.sh
```

Enter the principal, annual rate, and time when prompted. For principal **1000**, rate **5**, and time **2**, the calculation is `1000*2*5/100` and the interest is **100**.

The sample uses integer arithmetic through `expr`: enter whole numbers; fractional results are truncated. It is an educational example and is not intended for production financial use.

## Credits and license

Original script: Upkar Lidder (IBM). Additional author: [kanatovs](https://github.com/kanatovs), who adapted the author and formula comments for this submission.

Released under the [Apache License 2.0](LICENSE). See [CONTRIBUTING.md](CONTRIBUTING.md) and [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) for community guidelines.
