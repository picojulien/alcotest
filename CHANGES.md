### 0.3.3 (2015-06-19)

* Control `--show-errors` using the ALCOTEST_SHOW_ERRORS env variable (#9)
* Add an `and_exit` optional argument to `Alcotest.run` to control
  the exit behavior of the main test function (#4)
* Fix the output of `--version`
* Add a `--json` argument to show the test results as a JSON object
  (#14, by @eowzukw)
* Expose `Alcotest.result` to turn a test into a result

### 0.3.2: (2015-06-08)

* Do not fail if the output file does not exist
* Add a simple example (#10, by @leowzukw)
* Add a logo (#12, by @leowzukw)

### 0.3.1 (2015-04-18)

* Fix OCaml 4.01.0 and earlier support (regressed in 0.3.0).
* Add Travis CI tests.

### 0.3.0 (2015-04-13)

* Fix backtrace handling (#2 by @dsheets)
* Use `Bytes` module instead of `String`

### 0.2.0 (2012-12-19)

* Fix issues with redirections
* Display the full errors when only one test is selected

### 0.1.0 (2012-12-12)

* Initial release