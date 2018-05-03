# Snippets for React/Redux (typescript) [![VS Version Badge](https://vsmarketplacebadge.apphb.com/version-short/Celestory.snippets-for-react-redux-typescript.svg)](https://marketplace.visualstudio.com/items?itemName=Celestory.snippets-for-react-redux-typescript)

## Features

Add several useful snippets for react and redux development in typescript.

![Snippets showcase](images/snippets.gif)

## Snippets

| Snippet                           | Renders                                         |
| --------------------------------- | ----------------------------------------------- |
| `importReact`                     | Import react                                    |
| `importReactAndRedux`             | Import react and redux                          |
| `reactComponent`                  | Generate react component                        |
| `reactComponentWithProps`         | Generate react component with props             |
| `reactComponentWithPropsAndState` | Generate react component with props and state   |
| `reactComponentWithRedux`         | Generate react component with redux             |
| `render`                          | Generate react render()                         |
| `componentWillMount`              | Generate react componentWillMount()             |
| `componentWillUpdate`             | Generate react componentWillUpdate()            |
| `componentDidMount`               | Generate react componentDidMount()              |
| `componentWillReceiveProps`       | Generate react componentWillReceiveProps()      |
| `reactTests`                      | Generate react tests with enzyme chai and sinon |
| `reactHighOrderComponent`         | Generate react high order component             |

## 0.0.2

### Added
- React high order component snippet

### Changed
- Remove recompose from snippets
- Move exports to the end of snippets
- Use arrow function instead of function

### Fixed
- Add missing state in react component with redux snippet
- Import test component from current directory