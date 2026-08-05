# Resolver Plugins Package Repository

This repository is the distribution endpoint for signed Resolver Plugins
packages. Package catalogs, packages, provenance, and channel metadata are
published as GitHub Release assets; they are not committed to the default
branch.

- `pkg-<series>` is the rolling current channel for an OPNsense series.
- `pkg-<series>-os-bind-rp-<version>` is an immutable rollback snapshot.
- The five newest rollback snapshots are retained for each series.

The release channels are managed by the package release workflow in
[`resolver-plugins/plugins`](https://github.com/resolver-plugins/plugins).
Installation and rollback instructions are maintained with that source.
