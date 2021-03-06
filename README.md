# fuzzer-test-suite

This is a set of tests (benchmarks) for fuzzing engines (fuzzers).

The goal of this project is to have a set of fuzzing benchmakrs derived from real-life
libraries that have interesting bugs, hard-to-find code paths, or other
challenges for bug finding tools.

The current version supports [libFuzzer](http://libFuzzer.info),
in future versions we exect to support [AFL](http://lcamtuf.coredump.cx/afl/)
and potentially other fuzzers.

# Benchmarks

* [c-ares-CVE-2016-5180](./c-ares-CVE-2016-5180)
* [libxml2-v2.9.2](./libxml2-v2.9.2)
* [openssl-1.0.1f](openssl-1.0.1f)
* [openssl-1.0.2d](openssl-1.0.2d)
* [re2-2014-12-09](re2-2014-12-09)
* [woff2-2016-05-06](woff2-2016-05-06)
* [harfbuzz-1.3.2](harfbuzz-1.3.2)

# See also

* [AddressSanitizer](http://clang.llvm.org/docs/AddressSanitizer.html)

# Contributing
See [CONTRIBUTING](CONTRIBUTING) first. 
If you want to add one more benchmark to the test suite,
simply mimic one of the existing benchmarks and send the pull request. 

# Disclaimer
This is not an official Google product.
