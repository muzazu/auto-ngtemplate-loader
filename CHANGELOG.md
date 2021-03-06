# Change Log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [v1.3.1](https://github.com/YashdalfTheGray/auto-ngtemplate-loader/tree/v1.3.1) (2018-10-17)

### Fixed

- Ran an NPM security audit and fixed the issues
- Updated package versions, switched to `@babel/preset-env` instead of `babel-preset-es2015`
- Added `prettier` to the codebase

## [v1.3.0](https://github.com/YashdalfTheGray/auto-ngtemplate-loader/tree/v1.3.0) (2018-02-21)

### Added

- The `pathResolver` function now works with versions as old as Webpack v1 using an `autoNgTemplateLoader` key in the Webpack configuration object

## [v1.2.0](https://github.com/YashdalfTheGray/auto-ngtemplate-loader/tree/v1.2.0) (2018-02-16)

### Added

- A `pathResolver` loader option that helps with resolving root-relative paths and adapts to various project structures

## [v1.1.0](https://github.com/YashdalfTheGray/auto-ngtemplate-loader/tree/v1.1.0) (2017-06-11)

### Added

- The variable name that gets used in the compiled code can now be changed

### Fixed

- Paths not prefixed with `./` in the DDO no longer cause problems

## [v1.0.2](https://github.com/YashdalfTheGray/auto-ngtemplate-loader/tree/v1.0.2) (2017-06-09)

### Fixed

- Properly handle the case where `templateUrl` is not set to a string

## [v1.0.1](https://github.com/YashdalfTheGray/auto-ngtemplate-loader/tree/v1.0.1) (2017-06-04)

### Fixed

- Added `yarn.lock` to the ignored files in NPM

## [v1.0.0](https://github.com/YashdalfTheGray/auto-ngtemplate-loader/tree/v1.0.0) (2017-06-04)

First release of the `auto-ngtemplate-loader`
