# ellipsis (development version)

* Improved error message suggesting that you check for misspelled argument 
  names.

* New `check_dots_unnused()` that checks that `...` is empty (#11).

# ellipsis 0.1.0

* New `check_dots_unnamed()` that checks that all components of `...` are
  unnamed (#7).

* Fix a bug that caused `check_dots_used()` to emit many false positives (#8)

# ellipsis 0.0.2

* Fix a `PROTECT`ion error
