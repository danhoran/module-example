module-example
==============

A simple example of a Javascript module.

## Notes
* **dist/** **should not** be committed to the module repo.
* A module **will** be able test, lint, uglify and build itself; resulting in module.min.js.
* A module **will** define it's own dependencies (Bower and NPM).
* A module **will** use [semver](http://http://semver.org/) versions.
* A module **will** export itself as an AMD module.

*./lib directory is used for build scripts and helpers*