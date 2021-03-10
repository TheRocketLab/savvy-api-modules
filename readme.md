## Spring Framework Modules

Due to package deprecations, some milestone versions specified in the pom.xml file will no longer be available.
Although there may be other compitible versions, the release versions of those packages contain breaking changes relative to the codebase.
The simplest and quickest way to get a working build is to populate the package cache from the backup of a working environment.

The repository.zip file in this repository contains the cache located at ~/.m2/repository/

- Backup your ~/.m2/repository/ directory
- Extract the repository.zip file to the same location
- Re-attempt the build
