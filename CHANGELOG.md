# Changelog

## [8.0.0](https://github.com/eggjs/supertest/compare/v7.0.0...v8.0.0) (2024-12-21)


### ⚠ BREAKING CHANGES

* drop Node.js < 18.19.0 support

part of https://github.com/eggjs/egg/issues/3644

https://github.com/eggjs/egg/issues/5257

<!-- This is an auto-generated comment: release notes by coderabbit.ai
-->

## Summary by CodeRabbit

- **New Features**
- Introduced a new `TestAgent` class for enhanced HTTP and HTTP/2
requests.
	- Added a new `Request` class to facilitate server requests.
	- Implemented a new `AssertError` class for improved error handling.
	- Created new GitHub Actions workflows for CI and package publishing.

- **Documentation**
- Updated the `README.md` to reflect rebranding to `@eggjs/supertest`
and revised installation instructions.

- **Bug Fixes**
	- Enhanced error handling and type safety in tests.

- **Chores**
	- Removed outdated configuration files and unnecessary dependencies.
	- Updated TypeScript configuration for stricter type checking.

<!-- end of auto-generated comment: release notes by coderabbit.ai -->

### Features

* support cjs and esm both by tshy ([#1](https://github.com/eggjs/supertest/issues/1)) ([09fb755](https://github.com/eggjs/supertest/commit/09fb7555aecebc2047cd68efafe0f54dc17b6108))
