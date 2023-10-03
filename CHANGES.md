Changes
=======

v2.0.0
------

### Breaking changes

- Replaced all action arguments with a single `pylint-args` option,
  which takes a string of arbitrary command-line parameters to forward
  on to `pylint`.
  [#10](https://github.com/TheFoundryVisionmongers/fn-pylint-action/pull/10)

v1.1.3
------

### Improvements

- Bumped `node` version from `node12` to `node16`, in response to
  deprecation warnings.

v1.1.2
------

### Bug fixes

- Bumped @actions/core from 1.6.0 to 1.9.1

v1.1.1
------

### Bug fixes

- Bumped `node-fetch` version to `v2.6.7` (CVE-2022-0235).

v1.1.0
------

### New features

- Added `pylint-ignore-paths` input, passed to `pylint` via the
  `--ignore-paths` command-line argument.

### Bug fixes

- Usage errors thrown by the `pylint` invocation will now fail the
  action.

v1.0.0
------

- Initial release.
