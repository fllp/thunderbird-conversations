Releasing a new version
=======================

* Ensure L10n is up to date
* Ensure the correct changeset is checked out
* Ensure `npm install` has been run
* Run `npm version <version>` (see below for details on `<version>`)
* Push the branch `git push upstream <branch>`
* Push the tag `git push upstream v<version>`

`<version>` is an major/minor/patch version number, with a possible pre-release
tag, e.g.

* 2.14.0
* 3.0.0
* 3.0.0-pre1
* 3.0.0-pre2
* etc.

Lastly, p
