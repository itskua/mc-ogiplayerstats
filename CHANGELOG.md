# Changelog

All notable changes to this fork of **OgiPlayerStats** are documented here.

## [1.0.0-26.3] - 2026-10-27

### Added / Updated
- **Minecraft 26.3 Support**:
  - Upgraded Paper API to `io.papermc.paper:paper-api:26.3.build.226-stable`.
  - Updated `plugin.yml` api-version to `'26.3'`.
- **Java 25 Target**:
  - Configured Maven compiler for Java 25 (`<release>25</release>`).
  - Compiled and verified bytecode major version 69 using OpenJDK 25.
- **Repository Cleanups**:
  - Added `.gitignore` to exclude build artifacts (`target/`), IDE directories, and generated class files from version control.
  - Removed accidentally committed build targets from upstream repository.
