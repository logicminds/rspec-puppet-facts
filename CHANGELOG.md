## 2018-01-31 - Release 1.9.0
- Bumps facterdb requirement to 0.5.0
- Adds docs for using custom external facts
- hardwaremodel output changed on Windows with Facter 3.x
- Add additional rqspec tests
- Correctly select windows releases that contain spaces
- Facter < 3.4 does not return a proper release name for Windows 2016
- Strip 'Server' prefix from windows release name if present
- Downcase windows to match facter output
- Fix specs for current facterdb release
- Make version fallback testing independent of installed facter gem
- Add SPEC_FACTS_STRICT setting
- Cleanup README
- Add specific test to test minor version ahead of current facter version
- Update test to check for range in case facter version is not currently in FacterDB
- Step down through versions if the current version is not available
- Fix wrong example in README

## 2017-06-23 - Release 1.8.0
- Support specifying facter version

## 2017-01-04 - Release 1.7.1
- Ignore case when choosing H/W models

## 2016-09-16 - Release 1.7.0
- Support custom facts defined by spec_helper

## 2016-05-19 - Release 1.6.1
- Fix a bug where not all specified Ubuntu or OpenBSD were captured

## 2016-05-17 - Release 1.6.0
- Cleanup and refactor methods
- Add YARD documentation
- Refactor and fix rspec
- Add the OS filter support

## 2016-03-29 - Release 1.5.0
- Add some Microsft Windows support

## 2016-02-04 - Release 1.4.1
- Add missing mcollective-client dependency

## 2016-02-04 - Release 1.4.0
- Dynamically set mco_version

## 2015-11-12 - Release 1.3.0
- Dynamically set rubysitedir

## 2015-11-05 - Release 1.2.0
- Requires facterdb 0.3.0

## 2015-09-15 - Release 1.1.1
- Fix OpenBSD support

## 2015-09-09 - Release 1.1.0
- Populate augeasversion, puppetversion and rubyversion

## 2015-09-03 - Release 1.0.3
- Fix FreeBSD support

## 2015-08-31 - Release 1.0.2
- Keys where not symbolized anymore since v1.0.0

## 2015-08-29 - Release 1.0.1
- Fix for old versions of Facter that does not provide operatingsystemmajrelease for some OSes

## 2015-08-27 - Release 1.0.0
- Use facterdb

## 2015-08-10 - Release 0.12.0
- Add Facter3 support

## 2015-06-16 - Release 0.11.0
- Add facts for OpenBSD 5.7

## 2015-05-27 - Release 0.10.0
- Add facts for Solaris 11

## 2015-05-26 - Release 0.9.0
- Add facts for Ubuntu 14.10
- Add facts for Ubuntu 15.04

## 2015-04-27 - Release 0.8.0
- Remove support for Operating System minor release (causes problems with Ubuntu naming)
- Add Gentoo support

## 2015-04-26 - Release 0.7.0
- Add support for Operating System minor release
- Update README.md

## 2015-03-06 - Release 0.6.0
- Add facts for FreeBSD 9

## 2015-03-06 - Release 0.5.0
- Add facts for FreeBSD 10

## 2015-02-22 - Release 0.4.1
- Really useless release :-)

## 2015-01-23 - Release 0.4.0
- Add facts for facter 2.4
- Format json with python's json.tool
- Improve code coverage in unit tests
- Test on more version of facter in travis matrix

## 2015-01-05 - Release 0.3.3
- Add facts for OpenSuse 12
- Add facts for OpenSuse 13

## 2015-01-04 - Release 0.3.2
* Symbolize hash keys

## 2015-01-03 - Release 0.3.1
- Set fqdn to foo.example.com
- Add json as runtime dependency

## 2015-01-02 - Release 0.3.0
- Use json output for facter

## 2014-12-20 - Release 0.2.5
- Don't fail if facts not found

## 2014-12-20 - Release 0.2.4
- Add facts for SLES 11
- Add facts for Ubuntu 10.04
- Fix for SLES 11 SP1

## 2014-12-20 - Release 0.2.3
- Add facts for ArchLinux

## 2014-12-19 - Release 0.2.2
- Fix some bugs
- Add unit tests

## 2014-12-19 - Release 0.2.1
- Add facts for Debian 8

## 2014-12-15 - Release 0.2.0
- Add opts hash parameter
- Tests only with x86_64 by default

## 2014-12-12 - Release 0.1.4
- Fix for Ubuntu

## 2014-12-12 - Release 0.1.4
- Fix for Fedora

## 2014-12-12 - Release 0.1.3
- Add facts for Fedora 19

## 2014-12-12 - Release 0.1.2
- Add facts for Scientific Linux

## 2014-12-12 - Release 0.1.1
- Add more facts

## 2014-12-12 - First Release 0.1.0
- Initial release
