[0.7.0](https://github.com/guillaume-nargeot/hpc-coveralls/issues?q=milestone:v0.7.0+is:closed)
-----
* Fix coverage conversion rule for otherwise bug

[0.6.1](https://github.com/guillaume-nargeot/hpc-coveralls/issues?milestone=8&state=closed)
-----
* Safer implementation of the result coverage value retrieval from coveralls.io (issue 25)
* Set the delay before retrieving the result to 10 seconds (issue #26)

[0.6.0](https://github.com/guillaume-nargeot/hpc-coveralls/issues?milestone=7&state=closed)
-----
* Add flag to print the raw json responses from coveralls.io (issue #24)
* Retrieve and display total coverage result on success response from coveralls.io (issue #21)

[0.5.0](https://github.com/guillaume-nargeot/hpc-coveralls/issues?milestone=6&state=closed)
-----
* Mark `otherwise` as fully covered (issue #3)

[0.4.0](https://github.com/guillaume-nargeot/hpc-coveralls/issues?milestone=5&state=closed)
-----
* Add option to configure the coverage data conversion (issue #15)
* Add option to prevent from sending the coverage report (issue #17)

[0.3.0](https://github.com/guillaume-nargeot/hpc-coveralls/issues?milestone=4&state=closed)
-----
* Support setting multiple test suites (issue #14)
* Process --exclude-dir value as a string prefix instead of a regex (issue #16)

[0.2.2](https://github.com/guillaume-nargeot/hpc-coveralls/issues?milestone=3&state=closed)
-----
* Prevent double compilation (issue #11)
* Concurrently process cabal test stdout and stderr channels (issue #12)
* Test with GHC 7.8.2

[0.2.1](https://github.com/guillaume-nargeot/hpc-coveralls/issues?milestone=2&state=closed)
-----
* Additional CI services support (issue #1)
* Fixed an issue in which mix files could not be found, @maoe contribution (issue #5)
* Introduced a command line argument to exclude files located under a given folder from the coverage report (issue #6)
* Return with non-zero exit code when the tix file is not found (issue #7)
* Introduced a command line argument to specify a custom cabal executable name (issue #8)
* Parse and display response from coveralls.io (issue #9)

0.1.0
-----
* Initial release
