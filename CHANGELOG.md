# Change Log
All notable changes to the "snippets-for-react-redux-typescript" extension will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.0.1] - 2018-04-28
### Added
- React import snippets
- React component snippets
- React lifecycle snippets
- React test snippets

## [0.0.2] - 2018-05-03
### Added
- React high order component snippet

### Changed
- Remove recompose from snippets
- Move exports to the end of snippets
- Use arrow function instead of function

### Fixed
- Add missing state in react component with redux snippet
- Import test component from current directory

## [0.0.3] - 2018-05-30
### Added
- React componentWillUnmount snippet

### Changed
- Use named exports instead of default exports

### Fixed
- React high order component use ComponentType instead of ComponentClass to allow wrapping stateless components

## [0.0.4] - 2018-08-26
### Changed
- Use AppReduxState instead of RootState

## [0.0.5] - 2019-06-18
### Added
- React getDerivedStateFromProps snippet

### Changed
- Prefix class with export

### Removed
- React reactHighOrderComponent snippet

## [0.0.6] - 2019-08-27
### Added
- React ref, state and callback hooks snippets

### Changed
- Change react class components to functional components
- Change react import to its simple form

### Removed
- React class snippets