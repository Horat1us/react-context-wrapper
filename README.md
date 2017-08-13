# React Context Provider
[![codecov](https://codecov.io/gh/horat1us/react-context-provider/branch/master/graph/badge.svg)](https://codecov.io/gh/horat1us/react-context-provider)
[![Build Status](https://travis-ci.org/horat1is/react-context-provider.svg?branch=master)](https://travis-ci.org/horat1us/react-context-provider)

Sample wrapper for providing context in tests.
*Includes Typescript definitions and tests.*

If you want to use this package, consider usage of [enzyme](https://github.com/airbnb/enzyme)

## Usage
See in [tests](./tests)


```typescript jsx
import {reactContextProviderFactory} from 'react-context-provider';
const ReactContextProvider = reactContextProviderFactory(YourComponent);

export default <ReactContextProvider context={{
    text: "Context your component will receive"
}}/>
```
## License
MIT