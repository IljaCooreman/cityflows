# Cityflows
This is the entry repository for the open source Cityflows project. This repo serves as a starting place for documentation and a portal to related microservice repo's.

This is a test setup. 

## Releasing a new version
We have yet to figure out how this might work, but here's an idea. When bumping a version to e.g. v2.0.0:
- every repo in the ecosystem should have the version tag. for example, if you make non-breaking changes to the data-model and not to other services and you want to bump to v2.0.0, you need to tag the data-model as well as all the latest (compatible) commits of all the other repo's with v2.0.0, so it is easy to see what versions go together.
- In this main repo, a changelog for V2.0.0 needs to be added. 
- In this main repo, all submodules of the services that are tagged with V2.0.0 need to be updated, then committed. This commit needs to be tagged with V2.0.0