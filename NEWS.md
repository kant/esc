# esc 0.3.1

## Bug fixes

* `effect_sizes()` did not always properly extract study names and used numeric indices instead character values.

# esc 0.3.0

## New functions

* `effect_sizes()` to generate a data frame with results of multiple effect size computations, based on data from another data frame.

## Bug fixes
* Fix control statements with condition with greater than one, which currently give a warning, but in future R versions may throw an error.

# esc 0.2.0

## New functions

* `write_esc()` as a convenient wrapper to write results to an Excel csv-file.