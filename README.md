# perl-rethinkdb

A Pure-Perl RethinkDB Driver

# Notes

* This is still in alpha stage
* This version is compatible with RethinkDB 1.8
* The implementation is close to 100% complete, but is missing the new date &amp; time features
* For now, see tests in `t/*.t` for examples

# Todo

* Implement date &amp; time features
* Double check all method parameters match the official drivers
* Add sugar syntax for `attr` (e.g. `$doc->{attr}`), `slice` (e.g. `$doc->[3..6]`), and `nth` (e.g. `$doc->[3]`)
* Add sugar syntax for as many operators as possible (e.g. `+`, `-`, `/`, `*`)
* Performance testing and fixes
* Submit to [CPAN](http://www.cpan.org/)
* Look into non-blocking IO
* Organize code
* Document source code
* Document in general
