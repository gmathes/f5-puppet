##2015-07-24 Release 1.3.0
###Summary

Small release for support of newer Puppet versions.

#### Features/Improvements
- Puppet 4 support
- Readme update

##2015-05-21 Release 1.2.0
###Summary

This is a feature release that adds domain routing support. Also includes a bugfix and test cleanup.

####Features
- Adds domain routing support.

####Bugfixes
- Adds fixes to validation and idempotency for all port parameters.

##2015-05-21 Release 1.1.1
###Summary

This bugfix release addresses a bug parsing partition and resource names with a dash in the name.

####Bugfixes
- Fixes handling of dashes in partition and resource names. (e.g. "/partition-name/resource-name")

##2015-05-14 Release 1.1.0
###Summary

This feature release adds the ability to have custom partitions, bugfixes, and numerous test improvements.

####Features
- Add F5 partitions.

####Bugfixes
- Fixes handling dashes in partition name.
- Fix validation of service_port if value is an actual integer.
- Fixes f5 parsing of health monitors set to none.

2015-02-17 Release 1.0.1
This release fixes a bug with the 'none' and 'automap' values for
`f5_virtualserver` `source_address_translation` property

2014-12-18 Release 1.0.0

Initial release.