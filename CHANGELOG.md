3.5.2 / 2016-10-13
==================

* Need 4.4.7 of build-info-extractor-gradle

3.5.1 / 2016-10-13
==================

* Put hard coded versions in build.gradle to fix pom on gradle plugin portal

3.3.4 / 2016-02-09
==================

* Restore original operation as this blocks publishing to bintray

3.3.3 / 2016-02-05
==================

* Move ordering of configuration in NebulaBintrayPublishingPlugin

3.3.2 / 2016-02-04
==================

* Move ordering of configuration to allow tasks task to run on multiproject

3.3.1 / 2016-02-01
==================

* Move to specific versions as the plugin portal is not using our bintray pom

3.3.0 / 2016-02-01
==================

* Move to artifactory's build-info-extractor-gradle plugin version 4.0.0
* Move to gradle 2.10

3.2.0 / 2015-12-08
==================

* update gradle-bintray-plugin 1.4 -> 1.5
* update build-info-extractor-gradle plugin to 3.1.1 -> 3.2.0

3.1.0 / 2015-08-31
==================

* Remove verifyReleaseStatus and verifySnapshotStatus as all of our other plugins just disable them.

3.0.1 / 2015-08-24
==================

* Fix oss.jfrog.org snapshot publications to look at nebula publication instead of mavenNebula

3.0.0 / 2015-08-20
==================

* switch to publishing nebula publication instead of mavenNebula
* switch to new publishing
* gradle-2.6
* add compatibility matrix testing

2.2.4 / 2015-08-11
==================

* Uncomment the OJO publishing plugin from the umbrella plugin

2.2.3 / 2015-08-10
==================

* Eliminate rest call to do mavenCentral sync, let the gradle-bintray plugin do its job
* Upgrade gradle-bintray-plugin 1.2 -> 1.3.1

2.2.2 / 2015-08-07
==================

* Remove dependency on nebula-publishing-plugin

2.2.1 / 2015-07-16
==================

* Move gradle-bintray-plugin to 1.0 -> 1.2
* Move build-info-extractor-gradle from 3.0.1 -> 3.1.1

2.2.0 / 2015-01-30
==================

* Move to gradle 2.2.1

2.0.1 / 2014-10-16
==================

* Upgrade gradle-bintray-plugin

2.0.0 / 2014-09-17
==================

* Move to gradle 2.0

1.12.6 / 2014-12-02
===================

* Use gradle-bintray-plugin 1.0, compensate for its problems with multi-projects and groovy version.

1.12.5 / 2014-10-22
===================

* Downgrade gradle-bintray-plugin to 0.5, was causing publishing issues

1.12.4 / 2014-10-16
===================

* Upgrade gradle-bintray-plugin

1.12.3 / 2014-07-11
===================

* Improved error messages

1.12.2 / 2014-07-10
===================

* fix jar name

1.12.1 / 2014-07-10
===================

* Rename to nebula-bintray-plugin
* Extracted bintray logic from nebula-plugin-plugin

1.12.0 / 2014-06-12
===================

* Initial release
