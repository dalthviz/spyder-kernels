# History of changes

## Version 0.4.4 (2019-04-08)

### Issues Closed

* [Issue 102](https://github.com/spyder-ide/spyder-kernels/issues/102) - Tkinter is now required for version 0.4.3 after patching the turtle code ([PR 103](https://github.com/spyder-ide/spyder-kernels/pull/103))

In this release 1 issue was closed.

### Pull Requests Merged

* [PR 106](https://github.com/spyder-ide/spyder-kernels/pull/106) - PR: Skip test_turtle_launch if Tk is not installed
* [PR 103](https://github.com/spyder-ide/spyder-kernels/pull/103) - PR: Enclose turtle customizations in a try/except to avoid a dependency on Tk ([102](https://github.com/spyder-ide/spyder-kernels/issues/102))

In this release 2 pull requests were closed.

----

## Version 0.4.3 (2019-03-31)

### Issues Closed

* [Issue 91](https://github.com/spyder-ide/spyder-kernels/issues/91) - KeyError when running "%reset -f" programmatically ([PR 96](https://github.com/spyder-ide/spyder-kernels/pull/96))

In this release 1 issue was closed.

### Pull Requests Merged

* [PR 96](https://github.com/spyder-ide/spyder-kernels/pull/96) - PR:  Avoid error when trying to pop __file__ out of the current namespace ([91](https://github.com/spyder-ide/spyder-kernels/issues/91))
* [PR 92](https://github.com/spyder-ide/spyder-kernels/pull/92) - PR: Include user site-packages directory in the list of excluded paths by the UMR ([8776](https://github.com/spyder-ide/spyder/issues/8776))
* [PR 90](https://github.com/spyder-ide/spyder-kernels/pull/90) - PR: Patch turtle.bye to make it work with multiple runnings of the same code ([6278](https://github.com/spyder-ide/spyder/issues/6278))

In this release 3 pull requests were closed.

----

## Version 0.4.2 (2019-02-07)

### Issues Closed

* [Issue 85](https://github.com/spyder-ide/spyder-kernels/issues/85) - NameError: name 'modpath' is not defined ([PR 86](https://github.com/spyder-ide/spyder-kernels/pull/86))

In this release 1 issue was closed.

### Pull Requests Merged

* [PR 88](https://github.com/spyder-ide/spyder-kernels/pull/88) - PR: Improve Cython activation
* [PR 87](https://github.com/spyder-ide/spyder-kernels/pull/87) - PR: Fix running Cython files
* [PR 86](https://github.com/spyder-ide/spyder-kernels/pull/86) - PR: Fix problems with UMR's run method ([85](https://github.com/spyder-ide/spyder-kernels/issues/85))

In this release 3 pull requests were closed.

----

## Version 0.4.1 (2019-02-03)

### Pull Requests Merged

* [PR 84](https://github.com/spyder-ide/spyder-kernels/pull/84) - PR: Better way to skip standard library and site-packages modules from UMR
* [PR 83](https://github.com/spyder-ide/spyder-kernels/pull/83) - PR: Blacklist tensorflow from the UMR ([8697](https://github.com/spyder-ide/spyder/issues/8697))

In this release 2 pull requests were closed.

----

## Version 0.4 (2019-02-02)

### New features
* This release fixes several important issues that prevented
  saving the current namespace to work as expected.

### Issues Closed

* [Issue 75](https://github.com/spyder-ide/spyder-kernels/issues/75) - Namespace serialization silently fails if any object is unserializable, e.g. a Python module ([PR 81](https://github.com/spyder-ide/spyder-kernels/pull/81))
* [Issue 9](https://github.com/spyder-ide/spyder-kernels/issues/9) - Spydata files won't import if the original filename is changed ([PR 80](https://github.com/spyder-ide/spyder-kernels/pull/80))

In this release 2 issues were closed.

### Pull Requests Merged

* [PR 82](https://github.com/spyder-ide/spyder-kernels/pull/82) - PR: Enclose calls to load wurlitzer and autoreload in try/except's ([8668](https://github.com/spyder-ide/spyder/issues/8668))
* [PR 81](https://github.com/spyder-ide/spyder-kernels/pull/81) - PR: Fix and improve saving of Spyder namespace with many types of objects ([75](https://github.com/spyder-ide/spyder-kernels/issues/75))
* [PR 80](https://github.com/spyder-ide/spyder-kernels/pull/80) - PR: Fix loading Spydata file with changed filename and other edge-cases in load_dict ([9](https://github.com/spyder-ide/spyder-kernels/issues/9))

In this release 3 pull requests were closed.

----

## Version 0.3 (2018-11-23)

### New features

* Add Wurlitzer as a new dependency on Posix systems.
* Add tests for the console kernel.

### Issues Closed

* [Issue 62](https://github.com/spyder-ide/spyder-kernels/issues/62) - Add support for AppVeyor ([PR 63](https://github.com/spyder-ide/spyder-kernels/pull/63))
* [Issue 60](https://github.com/spyder-ide/spyder-kernels/issues/60) - Only load Wurlitzer in Posix systems ([PR 64](https://github.com/spyder-ide/spyder-kernels/pull/64))
* [Issue 23](https://github.com/spyder-ide/spyder-kernels/issues/23) - Add tests for the console kernel ([PR 37](https://github.com/spyder-ide/spyder-kernels/pull/37))

In this release 3 issues were closed.

### Pull Requests Merged

* [PR 64](https://github.com/spyder-ide/spyder-kernels/pull/64) - PR: Don't load Wurlitzer extension on Windows because it has no effect there ([60](https://github.com/spyder-ide/spyder-kernels/issues/60))
* [PR 63](https://github.com/spyder-ide/spyder-kernels/pull/63) - PR: Test on Windows with Appveyor ([62](https://github.com/spyder-ide/spyder-kernels/issues/62))
* [PR 61](https://github.com/spyder-ide/spyder-kernels/pull/61) - PR: Patch multiprocessing to make it work when all variables are removed ([8128](https://github.com/spyder-ide/spyder/issues/8128))
* [PR 59](https://github.com/spyder-ide/spyder-kernels/pull/59) - PR: Filter deprecation warnings in ipykernel ([8103](https://github.com/spyder-ide/spyder/issues/8103))
* [PR 56](https://github.com/spyder-ide/spyder-kernels/pull/56) - PR: Add Wurlitzer to Readme
* [PR 55](https://github.com/spyder-ide/spyder-kernels/pull/55) - PR: Exclude all tests from our tarballs
* [PR 54](https://github.com/spyder-ide/spyder-kernels/pull/54) - PR: Add the Wurlitzer package to capture stdout/stderr from C libraries ([3777](https://github.com/spyder-ide/spyder/issues/3777))
* [PR 53](https://github.com/spyder-ide/spyder-kernels/pull/53) - PR: Remove current working directory from sys.path before starting the console kernel ([8007](https://github.com/spyder-ide/spyder/issues/8007))
* [PR 37](https://github.com/spyder-ide/spyder-kernels/pull/37) - PR: Initial tests for the console kernel ([23](https://github.com/spyder-ide/spyder-kernels/issues/23))
* [PR 36](https://github.com/spyder-ide/spyder-kernels/pull/36) - PR: Make tests to really fail in CircleCI
* [PR 21](https://github.com/spyder-ide/spyder-kernels/pull/21) - PR: Add AUTHORS.txt in MANIFEST.in to include in package

In this release 11 pull requests were closed.

----

## Version 0.2.6 (2018-08-09)


### Pull Requests Merged

* [PR 20](https://github.com/spyder-ide/spyder-kernels/pull/20) - PR: Include license file again in tarball

In this release 1 pull request was closed.

----

## Version 0.2.5 (2018-08-09)

### Pull Requests Merged

* [PR 19](https://github.com/spyder-ide/spyder-kernels/pull/19) - PR: Fix inconsistent EOLs
* [PR 18](https://github.com/spyder-ide/spyder-kernels/pull/18) - PR: Fix legal texts and make them consistent across all files
* [PR 17](https://github.com/spyder-ide/spyder-kernels/pull/17) - PR: Add/update descriptions, links and metadata in setup.py
* [PR 16](https://github.com/spyder-ide/spyder-kernels/pull/16) - PR: Include test suite in manifest
* [PR 11](https://github.com/spyder-ide/spyder-kernels/pull/11) - PR: Add codecov support to see coverage
* [PR 10](https://github.com/spyder-ide/spyder-kernels/pull/10) - PR: Start testing with CircleCI
* [PR 8](https://github.com/spyder-ide/spyder-kernels/pull/8) - PR: Demand specific dependency versions needed by Spyder

In this release 7 pull requests were closed.

----

## Version 0.2.4 (2018-06-25)

### Pull Requests Merged

* [PR 6](https://github.com/spyder-ide/spyder-kernels/pull/6) - PR: Handle deprecated 'summary' method for Pandas

In this release 1 pull request was closed.

----

## Version 0.2.3 (2018-06-23)

### Pull Requests Merged

* [PR 5](https://github.com/spyder-ide/spyder-kernels/pull/5) - PR: Add __version__ to package's init

In this release 1 pull request was closed.

----

## Version 0.2.2 (2018-06-22)

### Pull Requests Merged

* [PR 4](https://github.com/spyder-ide/spyder-kernels/pull/4) - PR: Fix debugging in Python 2

In this release 1 pull request was closed.

----

## Version 0.2.1 (2018-06-22)

### Pull Requests Merged

* [PR 3](https://github.com/spyder-ide/spyder-kernels/pull/3) - PR: Fix debugging

In this release 1 pull request was closed.

----

## Version 0.2 (2018-06-20)

### Pull Requests Merged

* [PR 2](https://github.com/spyder-ide/spyder-kernels/pull/2) - PR: Import our customizations directly here
* [PR 1](https://github.com/spyder-ide/spyder-kernels/pull/1) - PR: Fix some errors in sitecustomize

In this release 2 pull requests were closed.

----

## Version 0.1 (2018-06-18)

Initial release
