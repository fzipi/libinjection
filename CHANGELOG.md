# Changelog

## [4.1.0](https://github.com/fzipi/libinjection/compare/v4.0.0...v4.1.0) (2026-08-30)


### Features

* **analyzer:** use newer ArrayBoundsV2 check ([7e7c29b](https://github.com/fzipi/libinjection/commit/7e7c29b09b7db2a4a35583ceb7a923de19306059))
* **build:** add autotools support ([efa9b30](https://github.com/fzipi/libinjection/commit/efa9b306deae08d1b39f5529c3d597120a7e71a2))
* lint and fix code using clang-format ([73268cf](https://github.com/fzipi/libinjection/commit/73268cfd85f9ee625e1d73ec2b37672bb2fd83f6))
* lint and fix code using clang-format ([141ec39](https://github.com/fzipi/libinjection/commit/141ec3954b424ee9b8b58124237198c900b483fb))
* lint and fix code using clang-format ([a0131c0](https://github.com/fzipi/libinjection/commit/a0131c02e46add68e6704478bfd964389c153bb6))
* **py3:** update build syntax to py3 ([546665c](https://github.com/fzipi/libinjection/commit/546665c0390902acee4593614bd5f5346fd359f6))
* update docs and swig bindings ([86b8a68](https://github.com/fzipi/libinjection/commit/86b8a68b947605b0ab37cb78ef8ebec7cb90d2f4))
* use error return code in place of assert/abort ([837baea](https://github.com/fzipi/libinjection/commit/837baea5385384245f8d69731358fa8424507070))
* use error return code in place of assert/abort ([30f9926](https://github.com/fzipi/libinjection/commit/30f99268fdc5346616a8b965fa1a43a126be5d2d))


### Bug Fixes

* add back onbeforeactivate, onpropertychange ([76e2b71](https://github.com/fzipi/libinjection/commit/76e2b7135259b79cdad966309109cee126314775))
* add func prototype to fix linting ([2c3c2d9](https://github.com/fzipi/libinjection/commit/2c3c2d989231fc968e5794be9f5f0c78a7213887))
* add link to event names source ([e95c0b5](https://github.com/fzipi/libinjection/commit/e95c0b52a3828e81e035cafc041be5ba5ac86b74))
* add unit tests for html decode fix ([4ae437f](https://github.com/fzipi/libinjection/commit/4ae437f4d83ae174bc467f08000267a6618adeb0))
* additional table format ([973ca1e](https://github.com/fzipi/libinjection/commit/973ca1e80f1ee05761a8fcd270a54c8fd0fe2d27))
* address code review comment ([8576be6](https://github.com/fzipi/libinjection/commit/8576be6a4305cd4680c08bb74a145ceedebc8e81))
* **analyzer:** deal with clang analyzer findings ([89a3de5](https://github.com/fzipi/libinjection/commit/89a3de5adaf0daad5f359b2d92194f343bf960c1))
* apply clang format ([a7f2d1f](https://github.com/fzipi/libinjection/commit/a7f2d1f7341b1612edd243165134ef45d3364ee5))
* apply clang-format ([285fe53](https://github.com/fzipi/libinjection/commit/285fe538e115c841c5374e21e376d391b1417c44))
* apply clang-format ([4294a49](https://github.com/fzipi/libinjection/commit/4294a49d72532ea187f99a04043cced8923a5001))
* apply code review comment ([ffb2fbd](https://github.com/fzipi/libinjection/commit/ffb2fbdaccc136617bd389ffd628f684f35503db))
* apply core review suggestion ([be4f03f](https://github.com/fzipi/libinjection/commit/be4f03f865a57fc63b5ba1a3b487f5477b813237))
* apply suggestion from code review ([da6f42f](https://github.com/fzipi/libinjection/commit/da6f42f20ea37082add09644c729e82e3d0e5395))
* **build:** fix warnings at compile time ([9de04b7](https://github.com/fzipi/libinjection/commit/9de04b78b91e923b5a197d9e53bba5094b510f99))
* **build:** move some helpers to makefile ([4172976](https://github.com/fzipi/libinjection/commit/417297685fa35ab5130339c3f98f60eebf9f8aed))
* bump artifact version v4 ([66048d7](https://github.com/fzipi/libinjection/commit/66048d73c7832d42440e313137342710aaa3331f))
* clang format ([4080228](https://github.com/fzipi/libinjection/commit/4080228e6e8099e348593096035cc5aca007de73))
* cppcheck issues ([d7dd56f](https://github.com/fzipi/libinjection/commit/d7dd56f26968591e59a61d10d2bec260081639f6))
* **cppcheck:** update var name to match check ([92bb516](https://github.com/fzipi/libinjection/commit/92bb5161f29bbd67269cc5c00e8a6623a5f4f4e0))
* detect 1.e or 1.E SQLI issue ([52f9aef](https://github.com/fzipi/libinjection/commit/52f9aef2e7aee4f53021c48d5d2dea585414789e))
* embedding version ([51f3a96](https://github.com/fzipi/libinjection/commit/51f3a96e9fcc90a6112f52ac96fd4661e7ab0a44))
* format align ([f6eec9f](https://github.com/fzipi/libinjection/commit/f6eec9fc71f9b82f5f6255f85d9f9e8332bad9ba))
* **fuzzing:** add -fsanitize=fuzzer-no-link ([61a0455](https://github.com/fzipi/libinjection/commit/61a045507bb543c4c3d42a0ffa3a1d7b3038b2d8))
* **fuzzing:** add -fsanitize=fuzzer-no-link ([59538c3](https://github.com/fzipi/libinjection/commit/59538c3ee38953318865ab707c222a441a5f52e6))
* golang memory leak ([271bf39](https://github.com/fzipi/libinjection/commit/271bf395732dcf6fd3689d0d456813018661e48f))
* make clang analyzer happy ([fa0387d](https://github.com/fzipi/libinjection/commit/fa0387d692e4d9b78c3fdc1193d9a64a8ee2f7d7))
* move preprocessor flags to cover whole function ([de8a7ba](https://github.com/fzipi/libinjection/commit/de8a7baa1d766b99f285fefee28b856c1945481f))
* move version back to c file to allow embedding ([60bde2b](https://github.com/fzipi/libinjection/commit/60bde2bcddfc635f83263e0fd78c227706843a49))
* potentially missing parenthesis in solar empire blind injection. ([30919be](https://github.com/fzipi/libinjection/commit/30919be1ee16bd9115b8c74a942cd3aa674a785a))
* rebase and address review comment ([a868c14](https://github.com/fzipi/libinjection/commit/a868c14f87f39141746c2c22c2a6a1ef77a50cc3))
* rebase leftovers ([02e3e91](https://github.com/fzipi/libinjection/commit/02e3e917e135753cb3281db004db89d57cabed3e))
* run clang-format ([842be96](https://github.com/fzipi/libinjection/commit/842be963128d1f12da6d8fe14b2a88e68de27966))
* set correct length of added argument ([ff27bd0](https://github.com/fzipi/libinjection/commit/ff27bd0ba155d1de83b30ae8ae42c02ccedd3742))
* set correct length of added argument ([1836237](https://github.com/fzipi/libinjection/commit/18362370d2531480a81aafb46a48272820739ad7))
* tests for 1.e sqli ([380d95e](https://github.com/fzipi/libinjection/commit/380d95e08485989abd23f583ae2937dd64509115))
* try cstrcasecmp_with_null with another way ([c017af0](https://github.com/fzipi/libinjection/commit/c017af0c7c345ed8cec3ce477375c5bedead570c))
* update null terminated strings comment and fuzzer code ([b9fcaaf](https://github.com/fzipi/libinjection/commit/b9fcaaf9e50e9492807b23ffcc6af46ee1f203b9))
* update test suite to reflect events update ([51796ef](https://github.com/fzipi/libinjection/commit/51796efdbf078c19008c3983817eb0496fccc546))
* use correct boundary check in html_decode_char_at() ([22dc5ba](https://github.com/fzipi/libinjection/commit/22dc5babe1242d5edebd875fb3dc45e1f117c830))
* use version if not defined ([5b69919](https://github.com/fzipi/libinjection/commit/5b69919656b7ea8c3a285ea5255fb8f7736c8ce8))

## v4.0.0 - 2026-03-24

## MAJOR API BREAKING CHANGE

This is a major version release with **breaking API changes**. Applications using libinjection will need to be updated and recompiled.

### New Error Handling Model

* [#65](https://github.com/libinjection/libinjection/pull/65) [#27](https://github.com/libinjection/libinjection/issues/27) **BREAKING:** Changed return type from `int` to `injection_result_t` enum for all detection functions
* **CRITICAL:** libinjection no longer calls `abort()` and terminates the process on parser errors
* **NEW:** Functions now return `LIBINJECTION_RESULT_ERROR` (-1) when parser encounters an invalid state, allowing graceful error handling
* **BACKWARD COMPATIBLE:** `LIBINJECTION_RESULT_FALSE` (0) and `LIBINJECTION_RESULT_TRUE` (1) maintain numeric compatibility with old boolean return values
* **IMPORTANT:** Applications must be updated to check for and handle `LIBINJECTION_RESULT_ERROR` to avoid treating parser errors as benign input

### Affected Functions
* `libinjection_xss()` - now returns `injection_result_t`
* `libinjection_sqli()` - now returns `injection_result_t`
* `libinjection_is_xss()` - now returns `injection_result_t`
* `libinjection_h5_next()` - now returns `injection_result_t`

### New Files
* `src/libinjection_error.h` - defines `injection_result_t` enum

### Migration
See [MIGRATION.md](MIGRATION.md) for detailed migration instructions.

### Why This Change?
Previously, when libinjection's parser encountered an invalid state (e.g., string cursor position exceeding string length), it would call `assert()` or `abort()`, immediately terminating the entire process. This was problematic for:
- Web application servers that would crash on malformed input
- Embedded systems that require high availability
- Applications that need graceful degradation

The new error handling model allows applications to detect and handle parser errors appropriately without process termination.

### Bug Fixes
* [#70](https://github.com/libinjection/libinjection/pull/70) [#72](https://github.com/libinjection/libinjection/pull/72) Fix buffer overread in `html_decode_char_at()` — incorrect length check could read past allocated buffer
* [#62](https://github.com/libinjection/libinjection/pull/62) Fix length check for added argument in SQLi parser
* [#60](https://github.com/libinjection/libinjection/pull/60) Fix detection of `1.e` and `1.E` SQLi patterns

### XSS Detection
* [#57](https://github.com/libinjection/libinjection/pull/57) Update HTML event attributes from upstream WebKit

### Build and Embedding
* Source files now compile standalone without autotools — `LIBINJECTION_VERSION` defaults to `"4.0.0"` when not overridden
* [#74](https://github.com/libinjection/libinjection/pull/74) Updated README with build options and embedding instructions
* [#67](https://github.com/libinjection/libinjection/pull/67) [#68](https://github.com/libinjection/libinjection/pull/68) Fix fuzzing build configuration
* [#47](https://github.com/libinjection/libinjection/pull/47) Add missing parenthesis variations in SQLi insertion samples

### Other Changes
* Removed all `assert()` calls in parser code, replaced with proper error handling
* Updated SWIG bindings for Python, PHP, and Lua to support new return type
* Added comprehensive documentation and migration guide
* [#76](https://github.com/libinjection/libinjection/pull/76) Updated copyright to libinjection Contributors
* [#73](https://github.com/libinjection/libinjection/pull/73) [#64](https://github.com/libinjection/libinjection/pull/64) CI updates: newer runners, action versions, clang-format and cppcheck fixes

## v3.9.2 - 2016-05-21

* Release of whatever changes have been made over the last 2.5 years.

## v3.9.1 - 2013-12-26

Day-After-Christmas Edition

* No functional changes
* Code reverted to strict C90 style to allow builds on embedded systems, Windows and FreeBSD
* For gcc this means `-std=c90 -pedantic`, which seems to simulate Windows behavior on Linux
* Other minor style changes to header files.


## v3.9.0 - 2013-11-29

Black Friday Edition

* Big API Change!! everything in `libinjection.h` is now `libinjection_sqli.h`.  And a new super simple API is in `libinjection.h`
* Improvements to folder to prevent bypasses using SQL types (casts).  This eliminated about 400 fingerprints as well.
* Blacklisted a very degenerate MySQL ODBC case, that is highly unlike to be used in 'real inputs'. thanks to @LightOS foreporting.. not clear who found it originally.
* Over 400 unit tests now!
* Compiles clean under clang with `-Weverything -Wno-padded`   `-Wno-padded` is excluded since it's architecture dependant.   See `clang.sh` to see how to invoke.
* PHP documentation fixes, thanks @LightOS

## v3.8.0 - 2013-10-18

LAMP Special Edition: MySQL and PHP improvements

* [Issue #33](https://github.com/client9/libinjection/issues/54) Fixes MySQL in latin1-mode use of `%A0` as whitespace.  This was tricky since `%A0` might be part of larger UTF-8 encoding as well.  Or perhaps `%C2%A0` (utf-8 encoding) might be treated as whitespace.  Fortunately, MySQL only seems to treat `%A0` as whitespace in latin1 mode.   HT [@ru_raz0r](https://twitter.com/ru_raz0r)
* Fixes to Lua testdriver and portability fixes
* Much improved PHP build and test.  It now uses `phpize` and builds and tests like a real module.
* API CHANGE:  the macro `LIBINJECTION_VERSION` has been replaced by `const char* libinjection_version()`.  This allows us to increment the version number without having to regenerate SWIG (or other) bindings for minor releases.

NOTE:
Pregenerated [SWIG](http://www.swig.org/) bindings are removed.  You'll need to install SWIG before running `make`.  SWIG is packaged on virtually every OS so this should not be a problem.

Here's why:

* Latest versions of swig appear to generate poor quality bindings for LUA and Python.  Bugs are filed upstream [1341](https://sourceforge.net/p/swig/bugs/1341/), [1343](https://sourceforge.net/p/swig/bugs/1343/), [1345](https://sourceforge.net/p/swig/bugs/1345/).  These are fixed or will be fixed in swig 3.0.0.
* In addition, I've received a number of reports of generated code failing various static analysis
* I can't triangulate which SWIG for which language for which OS will work for you
* I may be switching to [libffi](http://cffi.readthedocs.org/) for python, and [luajit.ffi](http://luajit.org/ext_ffi.html) for lua(jit) in the future, anyways.

## v3.7.1 -- 2013-10-13

* Remove un-needed code

## v3.7.0 -- 2013-10-13

Major Release

* [Issue #54](https://github.com/client9/libinjection/issues/54): Add test vectors from [Arne Swinnen](http://www.arneswinnen.net/2013/09/automated-sql-injection-detection/). Thanks [qerub@github](https://github.com/qerub)
* Minor fingerprint update for [Issue #54](https://github.com/client9/libinjection/issues/54).  I don't really think it's valid SQL but it's safe enough to detect without false positives.
* [Issue #55](https://github.com/client9/libinjection/issues/55): Parse MS SQLSERVER use of \[brackets\] for column and table names. This is a big one that closes a lot of holes.  Thanks [nroggle@github](https://github.com/nroggel)
* [Issue #56](https://github.com/client9/libinjection/issues/56): fix buffer over-read.  Thanks [safe3@github](https://github.com/Safe3) and [flily@github](https://github.com/flily)
* Remove use of `-fstack-protector` as it breaks valgrind detecting memory problems
  Read more about it http://blog.client9.com/2013/10/12/gcc-valgrind-stackprotector.html
* Fixed folding issue where `1,-sin(1))` would be folded as `1 (1)`
* Add more test cases and improved test coverage to [98.8%](https://libinjection.client9.com/cicada/artifacts/libinjection-coverage-unittest/lcov-html/c/libinjection_sqli.c.gcov.html)

## v3.6.0 -- 2013-09-11
* New PHP API
* Big fingerprint update
** about 500 new fingerprints added based on fuzzing tests by Reto Ischi
** about 700 impossible, dead fingerprints removed
** adding folding rule for "sqltype sqltype -> sqltype" since
   `select binary binary binary 1` is valid
* Other minor fingerprints added
* -maybe- API change as typedefs and structs were re-arranged for SWIG

## v3.5.3 -- 2013-08-25
* Fingerprint update -- `BETWEEN` operation bypasses
* Fingerprint update -- `ANY/SOME` quasi-function bypasses
* Fixed issue with folding where `1-(2-3)` would fold to "nothing" instead of `1`
* Improved test coverage to [98.0%](https://libinjection.client9.com/cicada/artifacts/libinjection-coverage-unittest/lcov-html/c/libinjection_sqli.c.gcov.html)
* More adjustments to the PHP/MYSQL backtick to reduce false positives

## v3.5.2 -- 2013-08-21
* Fingerprint update.  Credit: Reto Ischi

## v3.5.1 -- 2013-08-21
* found regression in handling of PHP/MySQL backticks.  Tests added
* Dead code removed.
* Improved test coverage to [97.7%](https://libinjection.client9.com/cicada/artifacts/libinjection-coverage-unittest/lcov-html/c/libinjection_sqli.c.gcov.html)

## v3.5.0 -- 2013-08-21
* Bug fix for libinjection_sqli_reset @brianrectanus
  https://github.com/client9/libinjection/pull/50
* Non-critical parser fix for numbers with oracle's ending
  suffix.  "SELECT 1FROM .." -> (SELECT, 1, FROM) not
  (SELECT, 1F, ROM)
* Yet another fix for disambiguating Oracle's "f" suffix for numbers HT  @LightOS
* Better parsing of generated number forms of "10.e" and "10.10e"
  (these are actually table specifiers!) HT @LightOS
* Change sizing of some static arrays to have a length >= 8
  For GCC based applications, this allows -fstack-protector to work
  and -Wstack-protector will now not emit errors.
* Added '-fstack-protector-all -D_FORTIFY_SOURCE=2' to default CFLAGS.
  About 10% performance loss with -fstack-protector-all
* Improvements in reducing false positives, HT modsecurity team
* Add fingerprint, HT @FluxReiners
* Support for parsing of old ODBC-style typing, e.g. 'select {foo 1};' (valid in MySQL)
* Fix tokenization of "IF EXISTS(....", "IF NOT EXISTS(..."
* Fi possible stack over-read, and improve detection of "sp_password" flag
  in short sqli HT modsecurity team

## v3.4.1 2013-07-18
* Fingerprint update only HT @LightOS

## v3.4.0 2013-07-18

* Fix regression with COLLATE
* Handle "procedure analyze" under MySQL
* Make API most robust when setting flags
* Add folding API
* Add new all-C test driver to improve testing speed
* Makefile cleanups
* Fired Jenkins!  Using in-house system.
* Fixed bypass reported by @FluxReiners

## v3.3.0 2013-07-13

* change how backslash is handled to catch old MSSQL servers sqli
  See http://websec.ca/kb/sql_injection#MSSQL_Allowed_Intermediary_Chars_AND-OR
  for details
* Reworking of COLLATE to handle MySQL, TSQL types automatically
* Handle bizarro world TSQL '\%1' which is parsed as "0 % 1"
* Better stacked query detection, fixing some regressions
* Folding improvements
* False positive improvements


## v3.2.0 2013-07-12

* Parse binary litterals "0b010101" used by at least mysql and pgsql
* Add fingerprints '1&EUE', '1&EkU' to work around ambiguous parsing rules
  "-1.for" == '-1.f OR' vs. '-1. FOR'  CREDIT @LightOS
* Add parsing rules for COLLATION in MySQL, CREDIT @LightOS
* Reduce false positives by removing all fingerprints that contained "sn"
* Improvement in handling MySQL 'binary' quasi-operator/type
* Improvements in folding
* Removed dependency on SWIG for installing python module

## v3.1.0 2013-07-02

* Fix for parsing Oracle numeric literals
* Fix for oracle whitespace with null char.
* Add unusual SQL join types to keywords lists
* Minor fixes to python API examples

## v3.0.0 2013-06-23

Big Release and Big Engine change.  Highly recommend

* Numerous evasions and false positives fixed!
* Tokenizer is now really dumb, and publically exposed.  See `libinjection_sqli_tokenize`.
* Folding engine completely rewritten to be simpler and easier to extend, debug, port.
* MySQL `backticks` now handled correctly
* @"var" and @'var' parsed correctly (mysql)
* ":=" operator parsed correctly
* non-ascii SQL variables and barewords handled correctly
* less false positives and those that are false positives
  are more "indeterminate cases" and are only in a few
  fingerprints
* autogeneration of fingerprints with trivial SQL variations
* support for pgsql $ strings
* support for oracle's q and nq strings
* support for mysql's n strings
* parsing stats exposed
* new swig bindings for python and lua, with callbacks into original scripting
  language for accept/reject of fingerprints (i.e. manage fingerprints in
  script, not C code)
* Improved parsing of various special cases in MySQL
* Ban MySQL conditional comments.  If we find them, it's marked as SQLi immediately.
* Probably a bunch of other stuff too

## v2.0.4 2013-05-21 IMPORTANT

All users are advised to upgrade due to risk of DOS

## security
* more fingerprints, more tests
* Issue 34: fix infinite loop

## v2.0.3 2013-05-21

## security
* Add variations on '1U(((', thanks @LightOS
* Add automatically all variations on other cases of
  'parens padding'

## v2.0.2 2013-05-21

## security
* Added fingerprint 'nU(kn' and variations, thanks to
  discussion with @ModSecurity .

## v2.0.1 2013-05-21

## security
* Added fingerprint knknk, thanks @d0znpp

## v2.0.0 2013-05-17

Version 2 is more a software engineering release than SQLi.
The API, the code, and filenames are improved for embedded
use.  Please see the README.md file for details on use.

## security

* Fix Issue30: detection of more small sqli forms with fingerprint "1c".
* Fix Issue32: false positive of '*/*' of type 'oc'  Thanks to @brianrectanus

## API Changes

BIG CHANGES

* File name changes.  These are the only relevant files:
   * `c/libinjection.h`
   * `c/libinjection_sqli.c`
   * `c/libinjection_sqli_data.h`
   * `COPYING`
* Just need to include `libinjection.h` and link with `libinjection_sqli_.c`
* `sqlparse_private.h` and `sqli_fingerprints.h` are deprecated.
   Only use `#include "libinjection.h"`
* API name changes `is_sqli` and `is_string_sqli` are now
  `libinjection_is_sqli` and `libinjection_is_string_sqli`
* API change, `libinjection_is_sqli` now takes a 5th arg for callback data
* API change, `libinjection_is_sqli` accepts `NULL` for arg4 and arg5
  in which case, a default lookup of fingerprints is used.
* `sqlmap_data.json` now includes fingerprint information, so people making
  ports only need to parse one file.

## other

* Allow `clang` compiler (also in Jenkins, a build with clang and
  make-scan is done)
* Optimizations should result in > 10% performance improvement
  for normal workloads
* Add `sqlite3` special functions and keywords (since why not)

## v1.2.0 2013-05-06

## security
* fix regression in detecting SQLi of type '1c'

##
* improved documentation, comments, edits.

## v1.1.0 2013-05-04

## security

* Fix for nested c-style comments used by postgresql and transact-sql.
  Thanks to @Kanatoko for the report.
* Numerous additions to SQL functions lists (in particular pgsql, transact-sql
  and ms-access functions)
  Thanks to Christoffer Sawicki (GitHub "qerub") for report on cut-n-paste error.
  Thanks to @ryancbarnett for reminder that MS-ACCESS exists ;-)
* Adding of fingerprints to detect HPP attacks.
* Algorihmically added new fingerprints to detect new _future_ sqli attacks.  All of these
  new fingerprints have no been seen 'in the wild' yet.

## other

* Replaced BSD memmem with optimzed version.  This eliminates all 3rd party code.
* Added alpha python module (python setup.py install)
* Added sqlparse_fingerprints.h and sqlparse_data.json to aid porting and embeddeding.
* Added version number in sqlparse.h, based on
  http://www.python.org/dev/peps/pep-0386/#normalizedversion

## v1.0.0 2013-04-24

* retroactive initial release
* all memory issues fixed
