# Changelog

All notable changes to this project will be documented in this file.

The format is based on Keep a Changelog 1.1.0.

## [Unreleased]

### Fixed

- Keep server-side `if-shell` conditions working after console input injection detaches the server by connecting condition stdin to the null device instead of inheriting an invalid console handle.
