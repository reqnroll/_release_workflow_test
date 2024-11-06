# [vNext]

## Improvements:

* Support DateTimeOffset in value comparer (#180)

## Bug fixes:

* Fix: Rule Backgounds cause "External Data Plugin" to fail (#271)

*Contributors of this release (in alphabetical order): @obligaron* 

# v2.1.1 - 2024-10-08

## Bug fixes:

* Fix: Rule Backgounds cause External Data Plugin to fail (#271)
* Fix: VersionInfo class might provide the version of the runner instead of the version of Reqnroll (#248)
* Fix: Reqnroll.CustomPlugin NuGet package has a version mismatch for the System.CodeDom dependency (#244)
* Fix: Reqnroll.Verify fails to run parallel tests determinately (#254). See our [verify documentation](docs/integrations/verify.md) on how to set up your test code to enable parallel testing.
* Fix: Reqnroll generates invalid code for rule backgrounds in Visual Basic (#283)

*Contributors of this release (in alphabetical order):* @ajeckmans, @clrudolphi, @gasparnagy, @UL-ChrisGlew
