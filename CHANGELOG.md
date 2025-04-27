# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).


## Unreleased

### Added

### Changed

- Refactored into new mono repo `reactive-graph/tooling`
- Moved plugins `graphql-client` and `graphql-schema-visualization` from `reactive-graph/std` -> `reactive-graph/tooling`
- Prefix plugins with `tooling` (e.g. `libreactive_graph_tooling_graphql_client`)

### Fixed

### Distribution

### Infrastructure

- Build System: Refactored plugin deployment
- CI: Synchronize labels from config file
- CI: Publish binary packages and debian packages
