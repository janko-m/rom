# 1.0.1 2017-11-02

### Fixed

* Depends on final release of `rom-core ~> 4.0` (solnic)

# 1.0.0 2017-10-18

rom-changeset was extracted from rom-repository

### Added

- `#changeset` interfaced was ported to a relation plugin and now `Relation#changeset` is available (solnic)

### Changed

- Changesets are no longer coupled to repositories (solnic)
- Changesets use relations to retrieve their commands (solnic)
